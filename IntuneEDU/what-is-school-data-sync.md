---
title: School データの同期とは何ですか。
titleSuffix: Intune for Education
description: 学校グループとユーザーを Azure AD にインポートするデータ同期を使用して School です。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: angrobe
ms.date: 08/11/2017
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: f9cb6daf-a789-427b-bbfd-fa0a3d36e01f
searchScope:
- IntuneEDU
ms.openlocfilehash: d6d7c2556e4af90bd6d777be8f91367dabf80618
ms.sourcegitcommit: 77b833e0bc82105f1f0d5a0559b0da165453cc4a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2018
---
# <a name="what-is-school-data-sync"></a>School データの同期とは何ですか。

Microsoft の学校のデータ同期 (SDS) を使用して、教育用の Intune での既存の受講者情報システム (SIS) データから school レコードをインポートすることができます。

SDS、SIS からの情報を複製し、Azure Active Directory (AD) にします。 Azure AD は、受講者とデバイスを整理するのに役立つ Microsoft の管理システムです。 教育用の Intune でこのデータを使用して、アプリを展開し、設定を管理することができますし、します。 SDS の展開方法については[ここ](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91)をご覧ください。

SIS から School データ同期の教育を Intune に受講者情報をインポートするときに含めることを確認してください__グレード__と__卒業年__に加える場合[動的グループ](what-are-groups.md#managing-groups-and-subgroups)それらのプロパティです。 これは、下にある__学生オプション__ > __学生プロパティ を選択__です。 プロファイルを作成するのにには、この情報を使用します。  

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

- [Microsoft School Data Sync の詳細](https://sds.microsoft.com)

---
title: 学校データ同期の学校のレコードのインポート
titleSuffix: Intune for Education
description: Azure AD に学校グループとユーザーをインポートする使用 School Data Sync です。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: f9cb6daf-a789-427b-bbfd-fa0a3d36e01f
searchScope:
- IntuneEDU
ms.openlocfilehash: ec80e1b8f8d2851814227420b5026dd3c488277c
ms.sourcegitcommit: ecf53ed32308ea0f592788e19f8649801997cbdb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2018
ms.locfileid: "39230053"
---
# <a name="microsoft-school-data-sync-and-intune-for-education"></a>Microsoft 学校データ同期と Intune for Education

Microsoft School Data Sync (SDS) は、学校の記録から、既存 Student Information System (SIS) をインポートする Office 365 Education に無料サービスです。 作成されますオンライン教室とグループ Microsoft Teams、Intune for Education、およびサード パーティ製のアプリケーション。  

School Data Sync は、ドキュメントに移動して[SDS をデプロイする方法について](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91)します。 

## <a name="create-groups-from-school-roster"></a>学校のリストからグループを作成します。
SDS は、SIS の情報のコピーを作成し、Azure Active Directory (Azure AD) に格納します。 SDS は、intune for Education の設定とアプリを適用できる 2 つのグループを作成します。

* すべての学生
* すべての教師

Intune for Education グループの作成の詳細については、[グループを作成する](create-groups.md)を参照してください。  

## <a name="set-up-dynamic-group-properties"></a>動的なグループ プロパティを設定します。
Intune for Education 学校データ同期に、SIS の生徒の情報をインポートする場合は、次のプロパティを含めます。
*  グレード 
*  卒業年  

これらのプロパティは作成するために必要な[動的グループ](create-groups.md#dynamic-groups)Intune for Education ポータルでの学生向けの規則。  プロパティは、SDS アプリから構成し、内にある__学生オプション__ > __学生のプロパティ を選択__します。

## <a name="what-is-azure-ad"></a>Azure AD とは何ですか。
Azure AD が Intune に統合された Microsoft 管理システムと受講者とデバイスを整理するのに役立ちます。 学生と教員、外のグループを作成できます*4 日の期間の生物学*または*Contoso District 教師*します。 グループは、割り当て、ユーザーまたはデバイスに固有のアプリ、設定、および制限を配布する必要があります。

## <a name="next-steps"></a>次の手順   
高速構成を開始、学生と教職員に関する情報は、Intune for Education と同期されたら、 [Windows](edu-express-config-settings-windows.md)または[iOS](edu-express-config-settings-ios.md)デバイス。  

Microsoft 学校データ同期の詳細を確認します。 参照してください、 [Microsoft 学校データ同期ページ](https://sds.microsoft.com)製品情報についてはします。 

---
title: Intune for Education グループを作成します。
titleSuffix: Intune for Education
description: デバイスを Intune for Education のグループを管理する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: doueby
ms.date: 10/08/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: dc0daff52ab3d0348b7cb0fb9256c6cf480def6b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147476"
---
# <a name="troubleshooting-group-actions"></a>アクション グループのトラブルシューティング

この記事では、作成して、intune for Education グループの編集に関する一般的な質問を回答します。

## <a name="why-cant-i-edit-the-default-groups"></a>既定のグループを編集できない理由

アカウントを作成するには、Intune for Education は、既定では、テナント レベルのグループのセットを作成します。 これらのグループ&ndash;**すべてのユーザー**と**すべてのデバイス**&ndash;変更ことはできません。 学校データ同期から、学校と教師のレコードをインポートした後、Intune と呼ばれる追加のグループを作成します**すべて教師**と**の全学生**します。 これらのグループには、いずれかを変更できません。

まれな状況では、2 つのグループの下にある同じサブグループに入ることがあります。 この問題が発生した場合は、サブグループ上にある最上位グループのいずれかを移動します。

## <a name="why-cant-i-edit-dynamic-groups"></a>動的なグループを編集できない理由

Intune for Education では、Intune の完全な管理ポータルでの動的な属性のサブセットから選択できます。 編集する属性が、Intune for Education ポータルに表示されない場合は、Azure portal または Azure Active Directory で Intune で編集する必要があります。

## <a name="why-cant-i-edit-a-specific-group"></a>特定のグループを編集できない理由  

Intune for Education は、学校でデバイスを管理する簡単な方法に設計されています。 使用して[、Azure portal で Intune](https://docs.microsoft.com/intune/what-is-intune)&ndash;エンタープライズ&ndash;アプリとグループを管理します。 組織内の特定の管理者は、Azure portal で Intune と Intune for Education の両方を使用して、特別なグループを作成する権限します。 場合は、グループを編集することはできません、可能性があり、Azure portal の Intune で作成したグループを変更するアクセス許可がありませんが。  

---
title: Intune for Education グループを作成します。
titleSuffix: Intune for Education
description: デバイスを Intune for Education のグループを管理する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: doueby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: 6392fe3238c69c6f99fdcb4a5ab537faaffa182e
ms.sourcegitcommit: ecf53ed32308ea0f592788e19f8649801997cbdb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2018
ms.locfileid: "39234381"
---
# <a name="troubleshooting-group-actions"></a>アクション グループのトラブルシューティング

作成して、intune for Education グループの編集に関する質問への回答を紹介します。

## <a name="why-cant-i-edit-the-default-groups"></a>既定のグループを編集できない理由

Intune for Education は、既定では、学校のアカウントが作成されたときに、テナント レベルのグループのセットを作成します。 これらのグループ**すべてのユーザー**と**すべてのデバイス**、変更することはできません。 **すべて教師**と**の全学生**School Data Sync がインポートされた学生と教師 Intune for Education では、データとも変更できないグループが作成されます。

まれな状況では、2 つのグループの下にある同じサブグループで最終的する可能性があります。 この問題が発生した場合は、サブグループ上にある最上位グループのいずれかを移動します。

## <a name="why-cant-i-edit-dynamic-groups"></a>動的なグループを編集できない理由

Intune for Education は、Intune の完全な管理ポータルで使用できる動的属性のサブセットから選択できます。 編集する属性が、Intune for Education ポータルに表示されない場合は、intune Azure Portal または Azure Active Directory で編集する必要があります。

## <a name="why-cant-i-edit-a-specific-group"></a>特定のグループを編集できない理由  

Intune for Education は、学校でデバイスを管理する簡単な方法に設計されています。 使用して[、Azure portal で Intune](https://docs.microsoft.com/intune/what-is-intune)、enterprise 製品、アプリとグループを管理します。 組織内の特定の管理者は、Azure portal で Intune と Intune for Education の両方を使用して、特別なグループを作成する権限します。 場合は、グループを編集することはできません、可能性があり、Azure portal の Intune で作成したグループを変更するアクセス許可がありませんが。  

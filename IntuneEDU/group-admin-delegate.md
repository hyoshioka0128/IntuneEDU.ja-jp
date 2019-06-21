---
title: グループに管理者アクセス許可の委任
titleSuffix: Intune for Education
description: Intune for Education グループのロールを管理する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/20/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 9319be2e-cb7e-43c1-98fe-64281c8c09fd
searchScope:
- IntuneEDU
ms.openlocfilehash: 6538520b0364b6ecf4b7ec45d57a465d49907778
ms.sourcegitcommit: c766ef357fb0257951f4e35f6ec6f53d63de811e
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "67285183"
---
# <a name="delegate-admin-permissions-to-groups"></a>グループに管理者アクセス許可の委任
IT スタッフは、学校を通じて学生、教員、および管理者の複数のグループを管理します。  

IT スタッフとは異なり管理者グループのみを割り当てるグループを管理します。 修飾個人のグループに管理者権限を付与すると、承認されていない、または偶発的な変更のリスクを軽減できます。  

## <a name="group-admin-permissions"></a>グループの管理者アクセス許可 

グループの管理者は、intune for Education に割り当てられ、学校のデバイスとアプリを管理する権限を持っています。 グループの管理者は次のとおりです。  

- デバイス、ユーザー、およびアプリについての情報を表示します。
- 割り当てる、作成、削除、表示、およびデバイスとユーザー設定を更新します。
- 割り当てる、作成、削除、表示、およびアプリを更新します。
- レポートを表示します。
- デバイスを工場出荷時設定にリセット、再起動、ロック解除、デバイスをロックおよび同期を強制では、リモート アクションを実行します。  
- 作成、削除、表示、および iOS MDM プッシュ証明書、iOS MDM サーバー トークン、および iOS VPP トークンを更新します。   

> [!TIP]
> 高度なタスクは、管理者のアクセス許可を変更します。 アクセス許可を変更またはカスタムのアクセス許可のセットを作成するかどうかに移動する必要がある[Intune での完全な管理エクスペリエンス](https://docs.microsoft.com/intune/role-based-access-control)します。 これらのアクセス許可には、Intune での組み込みの学校の管理者ロールが構成されています。 

## <a name="assign-an-admin-group"></a>管理グループを割り当てる

1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**グループ**します。
2. グループを選択します。 このグループは、管理者が管理する 1 つになります。
3. をクリックして、 **Admins**タブ >**管理者の追加**します。
4. アプリと設定を管理する管理者のアクセス許可を指定するグループを選択します。
5. クリックして**グループの選択**します。

## <a name="remove-an-admin-group"></a>管理者グループを削除します。
1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**グループ**します。
2. グループを選択します。 このグループを管理から管理グループを削除する 1 つとなります。
3. をクリックして、 **Admins**タブ。
4. 管理者の一覧から 1 つまたは複数のグループを選択します。 クリックして**管理者の削除**します。  

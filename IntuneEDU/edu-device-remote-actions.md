---
title: Intune for Education でリモート デバイス アクション
titleSuffix: Intune for Education
description: リモート操作を使用してトラブルシューティングを行うし、離れた場所にあるデバイスを管理する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/30/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: df7cabf2-1723-4817-b16c-800407a0c753
searchScope:
- IntuneEDU
ms.openlocfilehash: f19a24c78ad3a155b33ccc05bc266160fce7387e
ms.sourcegitcommit: 624b8b648e3148b484f4de163b45bc6c9ea98ac9
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/31/2019
ms.locfileid: "55450187"
---
# <a name="manage-devices-remotely"></a>デバイスをリモートで管理します。  

デバイスと、そのユーザーは異なる場所にしてトラブルシューティングのために必要な場合は、Intune でリモート アクションを使用して、教育機関向け。  


## <a name="remote-actions-for-devices"></a>デバイスのリモート操作  

![教育の 7 リモート アクションの Intune を示す例のスクリーン ショット。](./media/1812_Intune_EDU_Manage_Remote.png)  

ダッシュ ボードに移動します。**デバイス**します。 管理するデバイスを選択します。 ページの下部には、次の操作のいずれかを選択します。

- **再起動**:デバイスの電源を補強し、再起動します。
- **[出荷時の設定にリセット]**:Intune 管理からデバイスを削除し、デバイスからすべてのデータと設定を削除します。 
- **デバイスの同期**:そのデバイスが最新の状態の設定、アプリの割り当て、およびグループ メンバーシップが確認されます。 このアクションは、デバイスのトラブルシューティングを行うしようとしている場合に役立ちます。  
- **Autopilot リセット**:すべてのユーザー データを削除します。&ndash;ユーザー インストール済みアプリと個人用設定を含む&ndash;され、Windows 10 デバイスを Intune に登録されている状態に維持します。 デバイスには、最新のアプリ、ポリシー、および設定の最新の状態は保持されます。 リセットが開始されると、通知が表示されます。 デバイスは、インターネットに接続する [次へ] の時刻をリセットします。  
- **デバイスの名前を変更**:デバイスの新しい名前を示します。 新しい名前で Intune とローカルでデバイスを更新。 有効にする新しい名前の Windows デバイスを再起動する必要があります。  
- **デバイスの削除**:教育機関向けの Intune からデバイスの登録が解除し、Azure Active Directory からデバイスを削除します。 削除されたデバイスは、学校のリソースにアクセスできなくなります。 

## <a name="remote-actions-for-users"></a>ユーザーのリモート操作  

ダッシュ ボードに移動します。**ユーザー**します。 管理するユーザーを選択します。 ページの下部には、次のように選択します。**パスワードのリセット**します。 このアクションは、ユーザーのデバイス上の古い、紛失、または忘れたパスワードをリセットします。  

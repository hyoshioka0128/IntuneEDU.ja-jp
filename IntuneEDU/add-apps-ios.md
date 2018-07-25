---
title: IOS ストアから無料のアプリを追加します。
titleSuffix: Intune for Education
description: Intune for Education に iOS ストアから無料のアプリを追加する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
- IntuneEDU
ms.openlocfilehash: 4d17b0d12758dc781fa89f522f07ace5247cdc2e
ms.sourcegitcommit: ecf53ed32308ea0f592788e19f8649801997cbdb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2018
ms.locfileid: "39234333"
---
# <a name="add-free-ios-apps-to-intune-for-education"></a>Intune for Education に無料の iOS アプリを追加します。  
検索し、iOS App Store から無料のアプリをアプリのインベントリに追加します。 この記事では、表示して、Intune for Education ポータルに割り当てるように無料の iOS アプリを購入する方法について説明します。
 
手順としてリストされているアプリにのみ適用されます**Free** App Store でします。 有料のアプリを追加するには、情報の記事を参照してください。 [VPP の追加購入した iOS アプリを Intune に](add-vpp-apps-ios.md)します。

## <a name="recommendation-set-up-vpp-token"></a>VPP トークンを設定に関する推奨事項。

無料のアプリをインストールする VPP トークンを必要としないが、ことをお勧めします。 VPP トークンは、すべてのアプリ - 無料および有料--VPP ストアを通じてを購入することを許可します。 サイレント モードで、Intune はデバイスで購入した VPP アプリをインストールして、Apple ID を認証するには必要ありません。  

アプリを購入する VPP トークンを使用しないように選択した場合のみ、Intune for Education で無料のアプリを管理することできます。 デバイスのユーザーは、インストールが割り当てられているアプリに Apple ID でサインインする必要があります。

## <a name="add-new-ios-app"></a>新しい iOS アプリを追加します。
Intune for Education に iOS アプリを追加する、次の手順を完了します。
1. Intune for Education ポータルにサインインします。
2. **[アプリ]** をクリックします。
3. 左側のウィンドウで [ **IOS アプリ**、] をクリックして**新しいアプリ**します。
5. 検索ボックスで、アプリの完全または部分的な名前を入力します。
6. アプリを選択し、をクリックして**保存**アプリ、Intune のインベントリを追加します。

## <a name="view-app-details-in-intune-for-education"></a>Intune for Education でアプリの詳細を表示
アプリをアプリの一覧に表示を追加**iOS ストア**します。 アプリの表示をクリックしてその。

* **概要**: アプリ名、パブリッシャー、および Intune に追加する日付を一覧表示されます。 ITunes でアプリを表示するのには、アプリ名をクリックします。
* **グループ**: アプリが割り当てられているすべてのグループを一覧表示します。 ここでのグループ割り当てを変更または特定のグループの詳細ページに移動します。
* **インストール状態**: に割り当てられていたデバイスなどのアプリのインストールの詳細が表示されます。 状態は、最後のチェックイン時刻と、インストールが成功、失敗、または進行中の状態のかどうかにも一覧表示します。  

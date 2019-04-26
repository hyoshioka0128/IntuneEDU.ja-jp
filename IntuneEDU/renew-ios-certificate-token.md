---
title: Apple MDM 証明書を更新します。
titleSuffix: Intune for Education
description: 有効期限が切れた証明書または Intune for Education ポータル内のトークンを更新する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: a5989a02466183e4c891851598ffc885588c78fe
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146614"
---
# <a name="renew-ios-certificate-and-tokens"></a>IOS の証明書とトークンを更新します。
Apple MDM プッシュ証明書、MDM サーバー トークン、および VPP トークンは、作成した後、365 日に期限が切れます。 Intune for Education はアラートを生成するときに、証明書またはトークンに近いか、過去の有効期限の日付。 

Intune for Education のアカウントと Apple アカウント間の接続を維持するためにそれらを更新することを確認してください。  

## <a name="renew-apple-mdm--certificate"></a>Apple MDM 証明書を更新します。  
> [!IMPORTANT]
> Apple MDM 証明書が有効期限が切れた場合、または削除される場合は、リセットし、新しい証明書を使用してデバイスを再登録する必要があります。  

MDM プッシュ証明書は、その作成に使用する Apple ID に関連付けられます。 この同じ Apple ID を持つ証明書を更新します。

1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**テナント設定** > **iOS デバイス管理**します。
2. をクリックして、 **MDM プッシュ証明書**タブ。
3. クリックして**証明書の書き換え**します。
4. 指示に従って、 **MDM プッシュ証明書**ページ。 MDM プッシュ通知証明書を更新する Apple プッシュ証明書ポータルにアクセスする必要があります。 忘れないでください、元の証明書を作成するために使用する Apple ID で Apple Push Certificates portal にサインインします。
5. Apple Push Certificates portal の場合は、期限切れ間近の証明書を更新するためのオプションをクリックします。 
6. Apple ポータルで手順を実行します。 証明書の状態を読み取るとき**Active**をダウンロードし、保存、もう一度クリックします。
7. Intune for Education ポータルに戻り、Apple Push Certificates portal にサインインするために使用する Apple ID を入力します。
8. ダウンロードした証明書をアップロードします。
9. **[保存]** をクリックします。

## <a name="renew-mdm-server-token"></a>MDM サーバー トークンを更新します。

Intune for Education を常に、iOS デバイスの最新の一覧があることを確認するには、年間の MDM サーバー トークンを更新します。

MDM サーバー トークンは、サーバーを追加するために使用する Apple ID に関連付けられます。 この同じ Apple ID を持つトークンを更新します。 

1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**テナント設定** > **iOS デバイス管理**します。
2. をクリックして、 **MDM サーバー トークン**タブ。
3. 更新するトークンを選択します。
4. クリックして**更新トークン**します。
5. 指示に従って、 **MDM サーバー トークン**ページ。 新しい MDM サーバー トークンを生成する Apple School Manager にアクセスする必要があります。 忘れないでください。 Apple School Manager、元のトークンを取得するために使用する Apple ID でサインインします。
6. ダウンロードして、Apple School Manager から新しいトークンを保存した後は、Intune for Education ポータルに戻ります。 元のトークンを作成するために使用した Apple ID を入力します。
7. ダウンロードしたトークンをアップロードします。
8. **[保存]** をクリックします。


## <a name="renew-vpp-token"></a>VPP トークンを更新します。
購入した VPP アプリを表示し、Intune for Education から割り当てられているかどうかを確認するには、年 1 回、VPP トークンを更新します。  

VPP トークンは、その作成に使用する Apple ID に関連付けられます。 この同じ Apple ID を持つトークンを更新します。  

1. **IOS デバイス管理** ページで、をクリックして、 **VPP トークン**タブ。
2. 更新するトークンを選択します。
3. [ **VPP トークン。Microsoft Intune**、] をクリックして**更新トークン**します。
4. 指示に従って、 **VPP トークン**ページ。 新しいトークンを取得する Apple School Manager にアクセスするために必要になります。 忘れないでください、元のトークンを取得するために使用する Apple ID でサインインします。
5. 作成し、トークンをダウンロードする Apple School Manager での手順に従います。 トークンをコンピューターに保存します。
6. Intune for Education ポータルに戻ります。 Apple School Manager にサインインするために使用する Apple ID を入力します。
7. 参照コンピューターのファイル フォルダー アイコンをクリックします。 トークンをダウンロードして、以前に保存したファイルを選択します。
8. 学校のデバイスの場所を選択します。
9. アプリの自動更新を有効にしない場合は、それらを無効にする設定を切り替えます。 
10. **[保存]** をクリックします。

## <a name="next-steps"></a>次の手順
確認できたので、証明書とトークンを更新すると、[グループ設定](edit-groups-intune-for-edu.md)が最新の状態。 Intune でグループの現在の状態を表示するについて説明します。 方法[レポートを表示する](what-are-reports.md)します。  

読み取り[Intune for Education の新](whats-new-in-edu.md)最新の更新プログラムと機能について調べる。
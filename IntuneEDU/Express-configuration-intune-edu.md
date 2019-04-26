---
title: 高速構成
titleSuffix: Intune for Education
description: 高速構成を使用して、Intune for Education でグループを設定します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope:
- IntuneEDU
ms.openlocfilehash: eb3b697973d37d5b4697559b3ba87b64ba9afdb3
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147320"
---
# <a name="express-configuration-in-intune-for-education"></a>Intune for Education で高速構成

  ![高速構成タイルは、「起動高速構成、ここをクリックすると、アプリおよびグループの設定を選択します」と表示](./media/express-config-001-launch-tile.png)

高速構成を使用すると、ユーザーとデバイスに設定とアプリを割り当てることができます。 ステップ バイ ステップ チュートリアルについては、起動のタイルがの最初のページで見つかった、 [Intune for Education ポータル](https://intuneeducation.portal.azure.com)します。 

各ステップをクリックすると、Windows や iOS の設定のほとんどが既に構成されていることが表示されます。 これらの構成では、既定値は、推奨設定として設定されます。 推奨される OS 固有のアプリがあらかじめ選択もできます。 学校の必要に応じて、既定の選択を変更します。 

グループの設定やアプリを変更するときにいつでも、高速構成に戻ります。 

## <a name="launch-express-configuration"></a>高速構成を起動します。
このセクションでは、高速構成の手順を実行する方法について説明します。 最大限に高速構成活用、学校のデータを同期または Azure AD でグループを作成したを確認します。 

1. Intune for Education ポータルにサインインします。
2. ダッシュ ボードで、次のようにクリックします。**起動の高速構成**します。  

高速構成を起動するときに iOS の構成が無効の場合  
1. ダッシュ ボードで、次のように選択します。**すべて** > **iOS デバイス管理**します。
2. Apple MDM プッシュ証明書をアップロードします。
3. 登録、 [Apple MDM サーバー トークン](setup-ios-device-management.md)します。

## <a name="choose-a-group-to-configure"></a>構成するグループを選択します。

一部のグループが作成され、Intune for Education のサブスクリプションに含まれています。 Intune for Education は、学校のレコードから詳細グループを設定します。 これらのグループは次のとおりです。  

 * すべてのデバイス  
 * すべてのユーザー  
 
School Data Sync (SDS) を使用して、学校のレコードをインポートする場合も表示されます。  

 * すべての教師  
 * すべての学生  

Intune for Education では、始めることをお勧め、**すべてのユーザー**グループ。 すべてのユーザーに必要な設定を割り当てます。 たとえば、パスワードの要件と制限事項のポップアップは可能性があります、同じすべてのユーザーです。

  ![グループを選択するユーザーを要求する、選択グループ画面。](./media/express-config-004-choose-group.png)

すべてのグループを非表示を表示または展開/折りたたみの矢印をクリックします。 最上位のグループを構成するときに注意してください、サブグループがそのすべての設定を継承します。

## <a name="choose-apps"></a>アプリケーションを選択する

デバイスには、次のアプリの種類を追加できます。
* [Web アプリ](add-web-apps-edu.md)
* Windows 10 アプリ
    * [Microsoft Office](install-office.md)
    * [教育機関向け Microsoft Store](acquire-store-apps.md)
    * [デスクトップ アプリ](add-desktop-apps-edu.md)
* iOS アプリ
    * [無料の iOS App Store アプリ](add-apps-ios.md)
    * [ボリューム購入プログラム (VPP) アプリ](add-vpp-apps-ios.md)

割り当てる 1 つまたは複数のアプリを選択します。 クリックした後、アプリをグループに割り当てたすぐには**次**します。

  ![アプリの割り当て画面。 アプリは、割り当ての教育用アプリの web アプリ、Microsoft Store をなど、さまざまな種類ごとに整理されます。](./media/express-config-005-choose-apps.png)

Intune for Education も表示されます[教育機関向け Microsoft Store からアプリを人気のある](add-popular-apps-edu.md)からすべての Intune for Education のユーザーの間で。


## <a name="choose-settings"></a>設定を選択します。
高速構成によって、Intune でデバイスとユーザーの一般的な設定が表示します。 設定は、OS 固有のカテゴリに分類されます。Windows の設定および iOS の設定。

推奨値では、既定の設定が事前設定します。 推奨設定を使用しないと変更を行った、 をクリックする場合**次**します。 設定は、グループにすぐに適用されます。 

  ![設定の選択 画面。 設定は、デバイスを共有デバイスの基本設定、アプリの設定、ブラウザーの設定、やなどの区分を含む、折りたたまれた一覧に編成されます。](./media/express-config-006-choose-settings.png)


学校に合わせていつでも高速構成選択の変更は、ポリシーを変更するのです。 Intune for Education でさらにカスタマイズ用の完全な一覧を表示[Windows 10](all-edu-settings-windows.md)と[iOS](all-edu-settings-ios.md)デバイスの設定。

## <a name="review-settings"></a>設定の確認

保存する前に、アプリと選択した設定を確認します。 クリックして**戻る**変更を加えます。 をクリックし、確認が完了したら、**保存**します。

 ![レビューの選択画面。 アプリと高速構成中に選択した設定が表示されます。](./media/express-config-007-save-changes.png)  

  ![完了画面。 [複数のグループの構成] ボタンと完了したオプションが表示されます。 すべての元に戻すオプションは、Azure Active Directory に結合して Intune for Education にデバイスを追加するなど、プロセスの次の内容の短い説明を提供します。](./media/express-config-008-all-done.png)

## <a name="next-steps"></a>次の手順
[グループの管理者を割り当てる](group-admin-delegate.md)作成したグループを管理しやすくします。 高速構成を再考していつでも、グループを編集します。 多くの設定を表示する[グループ タブを参照してください。](create-groups.md)します。


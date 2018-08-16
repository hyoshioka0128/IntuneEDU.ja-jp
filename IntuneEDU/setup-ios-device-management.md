---
title: IOS デバイス管理を設定します。
titleSuffix: Intune for Education
description: 同期し、Intune for Education ポータルから iOS デバイスを管理する iOS デバイスの管理を有効にします。
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
ms.openlocfilehash: 6c87128a9d0e5b37993c8278ad2c9b1ee9044ddf
ms.sourcegitcommit: ecf53ed32308ea0f592788e19f8649801997cbdb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2018
ms.locfileid: "39234430"
---
# <a name="setup-ios-device-management"></a>IOS デバイスの管理をセットアップします。 

管理や、学生と教員に iOS デバイスを割り当てることができます、前に、Intune for Education で iOS デバイスの管理を設定する必要があります。 このセットアップには、MDM プッシュ証明書を追加し、少なくとも 1 つ MDM のサーバー トークン (DEP トークンとも呼ばれます) を構成する必要があります。  

  ![テナントの設定、iOS デバイスの管理ページで、トークン、MDM プッシュ証明書、MDM サーバーに白いチェック マーク付きの緑色の円を表示および VPP トークンのカードのスクリーン ショット。 円は、すべてが構成されていることを示します。 ユーザーには、編集、または構成を更新するには、「管理」ことを示す青い四角形のボタンをクリックできます。](./media/set-up-ios-management-landing-1807.png)   

セットアップ中に、Apple School Manager アカウントで Intune for Education のアカウントを接続します。 接続は、Intune for Education を常に最新の詳細、購入した iOS デバイスがあることを確認します。

この記事で説明する方法。

* Apple MDM プッシュ証明書を追加します。
* 構成し、Apple MDM サーバー トークンを同期します。
* Apple VPP トークンを構成します。

## <a name="what-happens-after-i-setup-device-management"></a>デバイス管理をセットアップするとどうなりますか。
IOS デバイスの管理をセットアップした後に Intune for Education を使用してアプリと、iOS デバイスの設定を管理することができます。 任意の場所の競合を解決するために、レポートやアクションへのアクセスが必要がありますもします。  

学生と教員学校では、学校の web サイトや電子メールに安全にアクセスできなければなります。  

## <a name="requirements"></a>要件
始める前がいることを確認します。  
* インターネットに接続します。
* Apple School Manager アカウントの資格情報。
* Intune for Education のデバイス ライセンス。 デバイス ライセンスの詳細について、 [Intune ライセンス docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)します。  

> [!IMPORTANT]
> Intune for Education では、Apple DEP. を通じて購入したデバイスの iOS デバイスの登録のみがサポートしています Apple School Manager の詳細については、次を参照してください。、 [Apple 教育のサポート サイト](https://support.apple.com/education)します。  

## <a name="add-an-mdm-push-certificate"></a>MDM プッシュ証明書を追加します。
Apple MDM プッシュ証明書を Intune と Apple School Manager アカウント間のセキュリティで保護された接続を設定します。 接続すると、Intune できる継続的に同期および Apple のデバイスとアプリを管理します。 

1. For Education ポータルが Intune にサインインします。
2. サイド バーとクリックに移動して**テナント設定** > **iOS デバイス管理**します。
3. をクリックして、 **MDM プッシュ証明書**タブ。
4. 指示に従って、 **MDM プッシュ証明書**ページ。 MDM プッシュ証明書を作成する Apple プッシュ証明書ポータルにアクセスする必要があります。 学校の Apple id で、個人、1 つない Apple Push Certificates portal にサインインします。
5. Apple ポータルで手順を実行します。 証明書を作成した後をダウンロードして保存する をクリックします。
6. Intune for Education ポータルに戻り、Apple Push Certificates portal にサインインするために使用する Apple ID を入力します。
7. ダウンロードした証明書をアップロードします。
8. **[Save]**(保存) をクリックします。  

プッシュ通知証明書では、すべての 365 日間有効期限です。 そのため、Apple School Manager アカウントに Intune for Education の接続に証明書が必要な[毎年更新する必要があります](renew-ios-certificate-token.md)します。  


## <a name="configure-mdm-server-tokens"></a>MDM サーバー トークンを構成します。  
DEP トークンとも呼ばれる、MDM サーバー トークンには、Apple School Manager から Intune 同期デバイスの詳細ことができます。 これらの詳細は、管理するために必要なデバイスの Intune に通知し、Intune for Education ポータルで、インベントリを設定します。  

1. **IOS デバイス管理** ページで、をクリックして、 **MDM サーバー トークン**タブ。
2. クリックして**トークンを設定する**します。
3. クリックして**ダウンロード**に必要な Intune 公開キーをダウンロードします。 MDM サーバー トークンの作成に Apple School Manager では、このファイルをアップロードする必要があります。 ファイルをコンピューターに保存します。
4. クリックして**Apple School Manager で MDM サーバーに移動**します。 メッセージが表示されたら、学校の Apple id で、個人、1 つない Apple School Manager にサインインします。
5. MDM サーバーを作成する画面の手順に従います。 変更を保存します。 この手順を完了する情報を持っていない場合は、学校の Intune 管理者に問い合わせてください。
6. ダウンロードし、MDM サーバーのトークンを保存します。
7. Apple School Manager で状態を維持し、移動**デバイス割り当て**します。 各デバイスの場合、デバイス全体の購入、または CSV ファイルで、デバイスの一覧の注文番号、シリアル番号を入力します。 
  ![Apple School Manager の web サイト、デバイスの割り当て ページのスクリーン ショット。 ラジオ ボタンの選択と購入済みのデバイスを手動で入力する方法を入力するユーザーの空のフィールド ボックスの手順 1. を「デバイスの選択」を示しています。 表示手順 2、"操作の選択 ドロップダウン メニューでユーザーが「サーバーに割り当てます」を選択する必要があります。](./media/Apple-School-Manager-MDM-Server-token-1807.png)   
1. ドロップダウン メニューから選択**Assign to Server**します。 次に作成した MDM サーバーを選択します。
2. Intune for Education ポータルに戻り、Apple School Manager へのサインインに使用した Apple ID を入力します。
3. ダウンロードした MDM サーバー トークンをアップロードします。
4. **[Save]**(保存) をクリックします。

MDM サーバー トークンは期限 365 日です。 表示し、Intune for Education ポータル デバイスを管理するには、トークンが必要です。 必要があります[毎年更新](renew-ios-certificate-token.md)します。

### <a name="device-enrollment-profile"></a>デバイス登録プロファイル
Intune for Education では、作成し、iOS 登録プロファイルを構成する各 MDM サーバー トークンに適用されます。

Intune for Education に追加されたすべての iOS デバイスは、監視モードに設定されます。 管理者は、監視対象モード、学校のデバイスの詳細に制御できます。 たとえば、プッシュできます新しいアプリまたはアプリの更新プログラム サイレント モードでのデバイスに。 監視モードのみの設定の完全な一覧は、情報の記事を参照してください。[監督が必要とする構成](https://docs.microsoft.com/en-us/intune/device-restrictions-ios#configurations-requiring-supervision)します。  

登録プロファイルの詳細については、表示、[構成設定の一覧](add-devices-ios-edu.md#list-of-preconfigured-settings)登録時にします。

### <a name="sync-managed-devices"></a>マネージド デバイスを同期する
Intune for Education では、iOS デバイスを管理するアクセス許可を持つ、これで、管理対象デバイスの一覧を表示する Apple と同期します。  
1. 教育機関向けの Intune にサインインします。
2. クリックして**テナント設定** > **iOS デバイス管理** > **DEP トークン**します。
3. 表示されているトークンのいずれかをクリックします。
4. クリックして**同期デバイス一覧**します。 

一覧に表示されるデバイスの登録準備ができました。 登録プロセスを最初に電源をします。

## <a name="configure-vpp-tokens"></a>VPP トークンを構成します。

 VPP トークンは、Apple VPP または Apple School Manager アカウントに Intune for Education のアカウントをリンクします。 。 組織全体でアプリを管理する 1 つの VPP トークンを作成します。または、別の場所や管理者の管理を分散する複数の VPP トークンを作成することができます。  

VPP トークンは、intune する必要があります。  
* Intune for Education ポータルでアプリの詳細を同期します。
* 購入した VPP アプリをグループに割り当てます。
* デバイスのユーザーの Apple ID の不要な学校のデバイスで購入した VPP アプリをサイレント モードでインストールします。

、VPP トークンを使用せずも検索および取得することができます[の無料のアプリ ストアから iOS アプリ](add-apps-ios.md)します。 ただし、デバイスでアプリをインストールするデバイスのユーザーする必要がありますでサインイン、Apple id。 

1. **IOS デバイス管理** ページで、をクリックして、 **VPP トークン**タブ。
2. をクリックして**Apple School Manager を開いて**し、個性されません、学校の Apple ID でサインインします。
3. Apple School を作成し、トークンをダウンロードする管理の手順に従います。 トークンをローカル ドライブに保存します。
4. Intune for Education ポータルに戻ります。 Apple School Manager にサインインするために使用する Apple ID を入力します。
5. 参照コンピューターのファイル フォルダー アイコンをクリックします。 トークンをダウンロードして、以前に保存したファイルを選択します。
6. 学校のデバイスの場所を選択します。
7. アプリの自動更新を有効にしない場合は、それらを無効にする設定を切り替えます。 
8. **[Save]**(保存) をクリックします。

トークンは期限 365 日です。 トークンはそのため、購入した VPP アプリを管理するために必要な[それらを毎年更新する必要があります](renew-ios-certificate-token.md)します。

### <a name="whats-a-managed-device"></a>管理対象デバイスとは何ですか。
マネージ コードと非管理対象デバイスの違いを理解するためは、次のシナリオを見てみましょう。

教師は、学校に個人の iOS デバイスを表示します。 学校の時間内に、教師は、親会議のスケジュール設定して、クラスの割り当てを追跡するデバイスを使用します。  

 Apple DEP プログラムを通じて学校によってデバイスを購入されませんでした。 Intune for Education のテナントが登録されていません。 その結果、Intune 教師のデバイスと通信するための方法はありません。 デバイスは、管理、IT 管理者が学校時間中に、教師がデバイスを使用する方法の制御を持たない--いないと見なされます。 

同様に、既知の管理対象デバイスではないために、教師が電子メールなどの保護された学校のリソースにアクセスことはできません。  

## <a name="next-steps"></a>次の手順

購入[の無料のアプリ ストアからアプリ](add-apps-ios.md)、または[、購入した VPP アプリを追加する](add-vpp-apps-ios.md)intune for Education ポータル。  

---
title: 新機能
titleSuffix: Intune for Education
description: Intune for Education で最近リリースされたことを確認します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 05/16/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 7d8dfd82-8cee-4874-85f6-edaf84e49c4c
searchScope:
- IntuneEDU
.#ms.devlang: ''
ms.openlocfilehash: 535823dad23e5e4109fdddfd7373643186fb6d17
ms.sourcegitcommit: c766ef357fb0257951f4e35f6ec6f53d63de811e
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "67285217"
---
# <a name="whats-new-in-intune-for-education"></a>Intune for Education の新機能新機能
Intune for Education の新機能新機能について説明します。 今後の変更、製品の通知、および以前のリリースからの機能について調べます。

## <a name="june-2019"></a>6 月 2019  

### <a name="perform-bulk-actions"></a>一括操作を実行します。 
一度に最大 100 個のデバイスで特定のリモート アクションを実行します。  一括選択をするためには、手動でデバイスの一覧からデバイスを選択したりを押しながら、 **Ctrl**または**コマンド**一度に複数のデバイスを選択するキー。 
 
 ![選択すると、複数のデバイスの例のイメージと一括再起動の確認を実行します。](./media/1906-remote-bulk.png)  

Intune for Education は、次のデバイス操作に対して一括機能をサポートします。  

* 再起動  
* 工場出荷時のリセット  
* 同期  
* Autopilot のリセット  
* DELETE   

 ![一括同期確認の例のイメージ。](./media/1906-remote-bulk-selection.png)  

### <a name="easier-migration-to-intune-for-education-licenses"></a>Intune for Education のライセンスに簡単に移行  
Intune for Education のサインアップした後、Intune は学校向けに推奨される値を持つすべてのデバイス グループいくつかの設定を自動的に構成します。 今すぐ追加すると Intune テナントを既に Education が、Intune サブスクリプションが、推奨されるポリシーが表示されますが、Intune も自動的に割り当てられません。 この変更は、既存の環境に望ましくない変更が行われませんことを確認します。  

### <a name="new-permissions-for-assigned-group-admins"></a>割り当てられたグループの管理者の新しいアクセス許可  
Intune の組み込み学校管理者ロールを今すぐ作成は、読み取り、更新、および管理されているアプリの (CRUD) アクセス許可を削除します。 この更新プログラムにより、intune for Education グループの管理者として割り当てられている場合ことができますようになりました作成、表示、更新、および iOS MDM プッシュ証明書、iOS MDM サーバー トークン、および iOS VPP のトークンと共に削除[の既存のアクセス許可があります](https://docs.microsoft.com/intune-education/group-admin-delegate#group-admin-permissions)。 これらのアクションを実行するには**テナント設定** > **iOS デバイス管理**します。  

### <a name="new-deployment-documentation"></a>新しいデプロイに関するドキュメント  
[登録セクション](https://docs.microsoft.com/intune-education/add-devices-windows)ドキュメントの学校の Pc と Windows Autopilot の学校の環境に基づいて設定を比較するのに役立つ新しい情報がわかり、セットアップが必要です。 この情報を使用して、各オプションでは、またはその両方のデバイスのセットアップを使用するタイミングを決定します。 

## <a name="may-2019"></a>2019 年の月   

### <a name="distinguish-between-online-and-offline-licensed-microsoft-store-for-education-apps"></a>教育機関向け Microsoft Store のオンラインおよびオフラインでライセンスされる区別します。  

教育用アプリの Microsoft Store に、オンラインまたはオフラインのライセンスが含まれていることができます。 Intune for Education と表示されます、ライセンスの種類で高速構成アプリの詳細 ページで、管理、および正しいグループにアプリを展開するが簡単します。 オンライン ライセンスを持つアプリでは、ユーザーがデバイスにサインインした後のインストールを開始しを使用する Microsoft Store への接続を必要とします。 オフラインのライセンスを持つアプリでは、ユーザーのサインインが必要とせずにインストールしを使用する Microsoft Store への接続を必要としないです。  

### <a name="new-ios-settings"></a>新しい iOS の設定  

IOS Classroom アプリをより詳細に制御を提供する、新しい設定が追加されています。  

### <a name="apply-an-ios-device-naming-template"></a>IOS デバイスの名前付けテンプレートを適用します。  

グループ化し、iOS デバイスを識別するのに役立つ新しい名前付けの設定が追加されました。 IOS の登録と MDM サーバー トークンのセットアップでは、Intune for Education に自動的に名前が一意のデバイスのシリアル番号を使用してデバイスの各します。 プレフィックスに、Contoso または Math1 などのカスタム名を追加できます。 名前をカスタマイズする場合は、デバイスのシリアル番号がの末尾にアタッチされます。 以下に例を示します。Contoso012a345b67c8. 構成または MDM サーバー トークンの名前付けテンプレートを更新するはそのトークンに関連付けられているすべてのデバイスの名前が変更されます: 後に既存のデバイスとそれらの両方を登録、名前付けテンプレートが適用されます。 

## <a name="april-2019"></a>4 月 2019  

### <a name="updated-ios-settings-names-and-added-more-tooltips"></a>IOS の設定名を更新し、複数のツールヒントを追加  
IOS の intune for Education の設定を簡単に検索を理解する名前、ツールヒント、およびカテゴリの設定の多くに改訂しました。 これらの設定の詳細な一覧を参照してください。 [Intune for Education で iOS デバイスの設定](all-edu-settings-ios.md)します。  

### <a name="refined-list-of-ios-settings-in-express-configuration"></a>高速構成での iOS 設定の一覧を絞り込んだ   
私たちが調整、[高速構成での iOS 設定の一覧](edu-express-config-settings-ios.md)デバイスを取得して、グループを設定するさらに速くできるようにします。 一部の設定が高速の構成と内を移動する新しい設定から移動することを確認します。 削除の設定は構成内に引き続き使用できます**グループ** > **設定** > **iOS デバイスの設定**します。 Intune for Education でデバイスの設定の完全な一覧で、次を参照してください。 [iOS デバイスの設定](all-edu-settings-ios.md)と[Windows 10 デバイスの設定](all-edu-settings-windows.md)します。  

###  <a name="new-settings-for-windows-10-devices"></a>Windows 10 デバイスの新しい設定  
いくつかの新しい Windows 10 デバイスの設定があります。 Intune for Education で構成できるようになりました設定のほんの一部を次に示します。
* Windows Update の通知:この設定では、ユーザーが Windows の更新に関する通知を表示するかどうかを選択できます。  
* Windows の手動更新:この設定では、ユーザーが Windows 更新プログラムのスキャン、ダウンロード、および機能のインストールへのアクセスがあるかどうかを選択できます。  


## <a name="february-2019"></a>2019 年 2 月  

### <a name="set-custom-wallpaper-and-lock-screen-images-for-your-ios-devices"></a>カスタムの壁紙を設定し、iOS デバイスの画面イメージをロック  
Intune for Education を使用して、独自の壁紙を設定し、学校のデバイスで画面をロックすることができますようになりました。 イメージをアップロードするには**グループ** > **iOS デバイスの設定** > **壁紙、ロック画面イメージ**します。  

   ![IOS デバイスの設定、カスタムの壁紙、ロック画面イメージのスクリーン ショット。](./media/ios-1901-custom-image-settings.png)  


## <a name="january-2019"></a>2019 年 1 月  

### <a name="set-up-ios-devices-with-shared-ipad-features"></a>共有 iPad 機能を使用して iOS デバイスをセットアップします。
Intune for Education で iOS デバイスの登録の設定を構成、するときに今すぐ共有 iPad 機能を有効になっているを登録する iOS デバイスを構成するオプションがあります。  共有の iPad が管理されている Apple ID を持つ school デバイスにサインインするには、学生と教員を必要とする iOS の機能 デバイスを有効になっている保存されたアクセスし、実行中の作業、アプリ、およびタスクに学校との間サインインすることができます。 Intune for Education で共有 iPad の詳細については、次を参照してください。 [Shared iPad 構成](setup-ios-device-management.md#shared-ipad-configuration)します。  

### <a name="new-settings-for-windows-10-devices"></a>Windows 10 デバイスの新しい設定  
セキュリティ、Windows 更新プログラム、サインインのデバイスおよびブラウザー エクスペリエンスなどの領域をさらに制御を提供する新しい設定が追加されました。 この 1 か月が表示されます、いくつかの新しい設定を次に示します。  

* **Azure Active Directory テナントの優先ドメインを構成する**:この設定は、テナントのドメイン名のないデバイスにサインインする受講者を許可します。 その別名だけに迅速かつ簡単に、受講者サインインできます。  

* **新しいタブ ページを構成する**:この設定を使用して、学生が Microsoft Edge でタブを追加したときに開くページを選択できます。 空白のページまたは学校のホーム ページなど、カスタムの 1 つの新しいタブを開きます。  

* **スイッチのモードを解除**:この設定は、管理者が S のモードで Windows 10 からデバイスを切り替えることができます。 または学生が S モードから自分のデバイスを切り替えることを防ぎます。    

### <a name="updated-windows-settings-names-and-added-useful-tooltips"></a>更新された Windows 設定の名前と便利なツールヒントが追加されました  
設定の名前と intune for Education に検索を理解しやすくためのヒントの多くが改訂されいます。 さらに多くの詳細については、各設定では、次を参照してください。 [Intune for Education の Windows 10 デバイスの設定](all-edu-settings-windows.md)します。  

### <a name="rename-windows-devices"></a>Windows デバイスの名前を変更します。  
For Education ポータルが Intune からリモートで任意の Windows 10 (バージョン 1803 以降) デバイスの名前を変更します。 名前を変更するには**デバイス**、デバイスを選択します > **Rename デバイス**します。 デバイスを変更することも、**デバイスの詳細**ページ。  

## <a name="november-2018"></a>2018 年 11 月  

### <a name="remote-autopilot-reset"></a>リモートの Autopilot のリセット 
これで、Autopilot リセット for Education ポータルが Intune を使用してリモートでを呼び出すことができます。 Autopilot のリセットは、デバイスは常にすべての最新のアプリ、ポリシー、および設定の最新の状態のために、Intune でユーザーがインストールしたアプリと個人設定とデバイスの登録を保持を含むすべてのユーザー データを削除します。 この機能により、すばやくワイプし、新しい学校年度の準備を行う一括で学生の Pc を再構成できます。 Autopilot リセット詳細については[ここ](autopilot-reset.md)します。

### <a name="new-features-for-ios-management"></a>IOS 管理の新機能
- Intune for Education に今すぐは、教育と Apple School Manager の両方の Intune から VPP トークンを簡単に識別できるように、Apple School Manager VPP トークンの場所の情報を表示します。 
- 簡単にラベル付けと組織の intune for Education、VPP トークンのニックネームを指定できます。 
- 登録は、MDM サーバー トークンを設定するときに、iOS デバイスをさらに高速ようになりました。 Intune for Education は、MDM サーバー トークンに関連付けられているデバイスをタップしてセットアップ アシスタント画面が少ないために、登録の設定を自動的に構成されます。 
 
### <a name="delete-device"></a>デバイスを削除します。
これで、for Education ポータルが Intune でデバイスを削除することができます。 デバイスの削除。
- Intune にデバイスの登録が解除されます。
- デバイスは、環境の一部が不要になったために、Azure Active Directory からのデバイス レコードを削除します。
 
### <a name="immersive-reader-for-all-tenants"></a>すべてのテナントの没入型のリーダー 
教育機関向けのインベントリ、Windows ストアは、Intune for Education にサインアップするときに、没入型のリーダーの無制限ライセンスを取得します。 没入型リーダーは、すべての年齢層と機能の学習器のアクセシビリティと包含の読みやすさを作成する学習ツールです。 詳細については、没入型リーダーは[ここ](https://www.onenote.com/learningtools)します。
 
### <a name="effective-policy-page"></a>有効なポリシー ページ
有効なポリシー ページには、すべてのアプリとグループ メンバーシップに基づいてユーザーとデバイスの組み合わせに適用する設定が表示されます。 このページから、競合している問題のトラブルシューティングを行う可能性のある設定を確認できます。 2 つの方法で有効なポリシー ページに到達することができます。
- ユーザーをクリックして >**ユーザーの詳細に移動**> デバイスをそのユーザーの選択でチェックが最近です。
- デバイスをクリックして >**デバイスの詳細に移動して**> そのデバイスで最近チェックインしたユーザーを選択します。



## <a name="july-2018"></a>2018 年 7 月 

### <a name="all-new-support-for-ios-classroom-devices"></a>クラスルームの iOS デバイス向けのすべての新しいサポート  

Intune for Education に今すぐには、教室での iOS デバイスの管理がサポートしています。 Intune for Education の関係者全員のセットアップと管理プロセスを簡単にする新機能とページが追加されました。 ダッシュ ボードで、すべてが正常にセットアップ、構成、およびデバイスを登録する必要がある必要があります。  

* IOS デバイスの管理をセットアップするには。新しいページを追加しました[ステップ バイ ステップ ガイダンス](setup-ios-device-management.md)Apple アカウントを Intune for Education にすばやく接続できます。 画面に表示されるインジケーターは、必須および省略可能な手順、正常に完了したものと有効期限が近づいているものを明確に確認できます。
* 高速構成:IOS デバイスに合わせて、Windows 10 エクスペリエンスと同様に[iOS 用の高速構成](express-configuration-intune-edu.md)迅速に割り当てるし、アプリと設定を変更するのに役立ちます。 ユーザーまたはデバイスのグループを選択し、Microsoft の推奨設定から選択します。 これら[の推奨事項があらかじめ選択](edu-express-config-settings-ios.md)、ですが、学校のポリシーに一致するように、いつでも変更できます。  
* アプリと設定:別のアプリとデバイスの設定のビューには、追加したいずれかに注目する[iOS](all-edu-settings-ios.md)または[Windows 10](all-edu-settings-windows.md)デバイスの管理。 使用すると追加[Apple VPP サポート](add-vpp-apps-ios.md)、Intune for Education で購入した VPP アプリを同期し、ダッシュ ボードから直接割り当てることができます。 
* 動的なグループ化します。特定のデバイス プラットフォームの規則を適用することができますので、[動的なグループ](create-groups.md#dynamic-groups)します。 デバイスまたは Windows 10 での受講者に適用するルールを作成*または*iOS デバイス。  

詳細を取得し、新しいページとワークフロー内を移動する方法について説明します、 [Intune for Education](what-is-intune-for-education.md)ドキュメント。   

## <a name="january-2018"></a>2018 年 1 月

### <a name="history-of-group-actions-taken-by-admins"></a>管理者によって行われたグループ アクションの履歴

これで、グループの管理者、アプリケーション、および、承認されたグループの設定を変更する管理者によって実行されたすべてのアクションの履歴を表示できます。 この履歴でのログを検索する**グループ** > **履歴**します。

### <a name="windows-defender-report"></a>Windows Defender レポート

新しいレポートが追加されました。 [レポート] ページを選択できます**Windows Defender レポート**レポートの一覧から。 これにより、すべてのデバイスの Windows Defender デバイス正常性の状態を表示できます。 これでどのように確認できます、[レポートとは?](what-are-reports.md)ドキュメント。

### <a name="use-role-based-access-control-to-enable-group-admins"></a>ロール ベース access control を使用して、グループの管理者を有効にするには

ここでの他のグループの設定を管理するユーザー グループを選択できます。 たとえば、という名前のグループがある*高校管理者*メンバーが、チームの担当地域の高校の管理者は、します。 *高校 Admins*高校生のグループの設定を管理するアクセス許可グループを指定する可能性があります。 参照してください、[グループとは? doc](what-are-groups.md)します。

### <a name="user-and-device-search"></a>ユーザーとデバイスの検索

サイド バーに 2 つの新しいオプションが追加されました。**ユーザー**と**デバイス**します。 これらを使用して、個々 のユーザーまたはデバイスを検索し、すばやく開くことができます、**詳細**これらの項目。 これらの検索を追加するには、サイド バーに**すべてを参照してください** > **星ボタン (お気に入り)** お気に入りの一覧に追加します。

### <a name="remote-actions"></a>リモート操作

これで、ユーザーとデバイス上のリモート操作を実行できます。 アクションを実行し、詳細ページから、次の操作のいずれかを選択するデバイスを選択します。

#### <a name="devices"></a>[デバイス]

- 再起動
- 工場出荷時設定にリセットします。
- 同期
- 管理対象から削除します。

#### <a name="users"></a>ユーザー

- パスワードの再設定

詳細について[リモート操作](edu-device-remote-actions.md)します。

### <a name="wi-fi-profiles"></a>Wi-Fi プロファイル

サイドバーに新しいオプションを追加しました**Wi-fi プロファイル**します。 これにより、さまざまなデバイス、ユーザー、およびグループに割り当てることができる Wi-fi 設定を定義できます。

## <a name="october-2017"></a>2017 年 10 月

### <a name="dynamic-groups"></a>動的なグループ

ルールを定義して、自動的に設定し、これに基づいてグループを作成します。

### <a name="new-app-status"></a>新しいアプリの状態

アプリを追加するときに、デバイスごとにわかりますようになりましたされ、アプリのユーザーごとの状態がインストールされます。

### <a name="updated-details-pages"></a>更新の詳細 ページ

グループのいずれかで、ユーザーまたはデバイスを選択します。 ペインには詳細、そのオブジェクトを取得することができます、画面下部とのアプリと設定を設定した状態からをスライドようになりました。

## <a name="may-2017-initial-release"></a>2017 年 5 月 (初期リリース)

### <a name="intune-for-education-is-now-available"></a>教育機関向けの Intune では、使用できるようになりました。

Intune for Education ポータルが開始します。 Intune for Education は、学校および教育機関 Windows 10 デバイスを管理する効率的なエクスペリエンスです。 これらのドキュメントの Intune for Education の詳細を確認します。

## <a name="next-steps"></a>次の手順

- [Intune for Education の詳細をについてください。](what-is-intune-for-education.md)
- [Intune を使用したフル デバイス管理エクスペリエンスの詳細をについてください。](https://docs.microsoft.com/intune/understand-explore/introduction-to-microsoft-intune)

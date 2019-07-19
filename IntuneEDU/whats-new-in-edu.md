---
title: 新機能
titleSuffix: Intune for Education
description: Intune for Education で最近リリースされたものを確認します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 7d8dfd82-8cee-4874-85f6-edaf84e49c4c
searchScope:
- IntuneEDU
.#ms.devlang: ''
ms.openlocfilehash: 258768b919d824e511452c3974b2c86c61c87a3d
ms.sourcegitcommit: 1791319c6f8a8fb2c35cf9620ca4785c421b2071
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/19/2019
ms.locfileid: "68329443"
---
# <a name="whats-new-in-intune-for-education"></a>Intune for Education の新機能
Intune for Education の新機能について説明します。 今後の変更、製品の通知、および以前のリリースからの機能について説明します。


## <a name="july-2019"></a>2019年7月  

### <a name="perform-bulk-rename"></a>一括名前変更の実行  
一度に最大で100のデバイスの名前を変更します。 一括選択を行うには、[デバイス] の一覧からデバイスを手動で選択するか、 **Ctrl**キーまたは**コマンド**キーを押しながら複数のデバイスを一度に選択します。  

次に、選択したデバイスのグループに名前付けテンプレートを適用できます。これには、一意の識別子によって追加されたカスタムプレフィックスが含まれます。 一意の識別子には、シリアル番号、カウンター、または Wi-fi MAC アドレスを指定できます。  

 
 ![カウンター識別子が選択されている [デバイス] ページの [一括名前変更] のスクリーンショット。](./media/edu-bulk-rename-1907.png)  


 ![[デバイス] ページのスクリーンショット。一括名前変更が進行中で、シリアル番号が選択されています。](./media/edu-bulk-rename-1907-01.png)   


## <a name="june-2019"></a>2019年6月  

### <a name="perform-bulk-actions"></a>一括操作の実行 
一度に最大100のデバイスに対して、特定のリモート操作を実行します。  一括選択を行うには、[デバイス] の一覧からデバイスを手動で選択するか、 **Ctrl**キーまたは**コマンド**キーを押しながら複数のデバイスを一度に選択します。 
 
 ![選択された複数のデバイスのイメージの例と一括再起動の確認。](./media/1906-remote-bulk.png)  

Intune for Education では、次のデバイスアクションの一括機能がサポートされます。  

* 再起動  
* 工場出荷時のリセット  
* 同期  
* 自動操縦リセット  
* 削除   

 ![一括同期の確認の例。](./media/1906-remote-bulk-selection.png)  

### <a name="easier-migration-to-intune-for-education-licenses"></a>Intune for Education ライセンスへの移行の簡素化  
Intune for Education にサインアップすると、[すべてのデバイス] グループの一部の設定が、学校に推奨される値で自動的に構成されます。 これで、既に Intune サブスクリプションがあるテナントに Intune for Education を追加すると、推奨されるポリシーが表示されますが、Intune によって自動的に割り当てられません。 この変更により、既存の環境に対して望ましくない変更が行われないようにします。  

### <a name="new-permissions-for-assigned-group-admins"></a>割り当てられたグループ管理者の新しいアクセス許可  
Intune の組み込み学校管理者ロールには、管理対象アプリに対する作成、読み取り、更新、削除 (CRUD) のアクセス許可が付与されるようになりました。 この更新プログラムにより、intune for Education グループの管理者として割り当てられている場合ことができますようになりました作成、表示、更新、および iOS MDM プッシュ証明書、iOS MDM サーバー トークン、および iOS VPP のトークンと共に削除[の既存のアクセス許可があります](https://docs.microsoft.com/intune-education/group-admin-delegate#group-admin-permissions)。 これらのアクションを実行するには、[**テナントの設定** > ] **[iOS デバイス管理]** に移動します。  

### <a name="new-deployment-documentation"></a>新しい展開ドキュメント  
ドキュメントの[「登録」セクション](https://docs.microsoft.com/intune-education/add-devices-windows)では、学校の環境およびセットアップのニーズに基づいて、school Pc と Windows 自動操縦のセットアップを比較するのに役立つ新しい情報を紹介します。 この情報を使用して、デバイスのセットアップに各オプションを使用するか、またはその両方を使用するかを決定します。 

## <a name="may-2019"></a>5月2019   

### <a name="distinguish-between-online-and-offline-licensed-microsoft-store-for-education-apps"></a>教育用アプリのオンラインおよびオフラインのライセンス Microsoft Store を区別する   

教育用アプリの Microsoft Store にオンラインまたはオフラインのライセンスがあるかどうかを確認できます。 Intune for Education では、Express 構成とアプリの詳細ページにライセンスの種類が表示されるため、適切なグループにアプリを簡単に管理し、展開することができます。 オンラインライセンスを持つアプリは、ユーザーがデバイスにサインインした後にインストールを開始し、Microsoft Store に接続して使用する必要があります。 オフラインライセンスを持つアプリは、ユーザーのサインインを必要とせずにインストールされ、Microsoft Store に接続する必要はありません。  

### <a name="new-ios-settings"></a>新しい iOS の設定  

新しい設定が追加され、iOS のクラスルームアプリをより細かく制御できるようになりました。  

### <a name="apply-an-ios-device-naming-template"></a>IOS デバイスの名前付けテンプレートを適用する  

IOS デバイスのグループ化と識別に役立つ新しい名前付け設定が追加されました。 IOS の登録と MDM サーバートークンのセットアップ中に、Intune for Education によって、各デバイスに一意のデバイスのシリアル番号が自動的に付けられます。 その後、Contoso や Math1 などのカスタム名をプレフィックスに追加できます。 名前をカスタマイズすると、デバイスのシリアル番号がその末尾に付加されます。 例えば:Contoso012a345b67c8. MDM サーバートークンの名前付けテンプレートを構成または更新すると、そのトークンに関連付けられているすべてのデバイスの名前が変更されます。既存のデバイスと名前付けテンプレートの適用後に登録されたデバイスの両方が変更されます。 

## <a name="april-2019"></a>2019年4月  

### <a name="updated-ios-settings-names-and-added-more-tooltips"></a>IOS 設定の名前が更新され、ツールヒントが追加されました  
設定の検索と理解を容易にするために、Intune for Education の iOS 設定の名前、ツールヒント、カテゴリの多くを修正しました。 これらの設定の詳細な一覧については、「 [Intune for Education での iOS デバイスの設定](all-edu-settings-ios.md)」を参照してください。  

### <a name="refined-list-of-ios-settings-in-express-configuration"></a>高速構成における iOS 設定の洗練される一覧   
デバイスとグループを迅速にセットアップできるように、[高速構成で iOS の設定の一覧](edu-express-config-settings-ios.md)を調整しています。 一部の設定が高速構成から移動され、新しい設定がに移動したことがわかります。 削除された設定は、[**グループ** > **設定** > ] **[iOS デバイス設定]** で構成できます。 Intune for Education のデバイス設定の完全な一覧については、「 [iOS デバイス設定](all-edu-settings-ios.md)と[Windows 10 デバイス設定](all-edu-settings-windows.md)」を参照してください。  

###  <a name="new-settings-for-windows-10-devices"></a>Windows 10 デバイスの新しい設定  
Windows 10 デバイスの新しい設定がいくつかあります。 Intune for Education で構成できる設定のほんの一部を次に示します。
* Windows Update 通知:この設定を使用すると、Windows 更新プログラムに関する通知をユーザーに表示するかどうかを選択できます。  
* 手動 Windows Update:この設定を使用すると、ユーザーが Windows Update スキャン、ダウンロード、およびインストール機能にアクセスできるかどうかを選択できます。  


## <a name="february-2019"></a>2019 年 2 月  

### <a name="set-custom-wallpaper-and-lock-screen-images-for-your-ios-devices"></a>IOS デバイスの壁紙とロック画面のカスタムイメージを設定する  
Intune for Education を使用して、school デバイスでカスタムの壁紙とロック画面のイメージを設定できるようになりました。 イメージをアップロードするには、[**グループ** > ] [iOS] [**デバイス設定** >  **] [壁紙] および [ロック画面の画像]** にアクセスします。  

   ![IOS デバイスの設定、壁紙のカスタマイズ、およびロック画面の画像のスクリーンショット。](./media/ios-1901-custom-image-settings.png)  


## <a name="january-2019"></a>2019 年 1 月  

### <a name="set-up-ios-devices-with-shared-ipad-features"></a>IPad の共有機能を使用して iOS デバイスをセットアップする
IOS デバイス登録の Intune for Education で設定を構成するときに、共有 iPad 機能が有効になっている状態で登録するように iOS デバイスを構成するオプションが用意されました。  共有 iPad は、学生や教師が管理対象の Apple ID で school デバイスにサインインする必要がある iOS の機能です。 学校で有効になっているデバイスにサインインおよびサインアウトして、保存された、進行中の作業、アプリ、およびタスクにアクセスすることができます。 Intune for Education の共有 iPad の詳細については、「[共有 ipad の構成](setup-ios-device-management.md#shared-ipad-configuration)」を参照してください。  

### <a name="new-settings-for-windows-10-devices"></a>Windows 10 デバイスの新しい設定  
セキュリティ、Windows の更新、デバイスのサインイン、ブラウザーのエクスペリエンスなどの領域をより細かく制御できるように、新しい設定が追加されました。 今月は、次のような新しい設定をいくつか紹介します。  

* **優先 Azure Active Directory テナントドメインの構成**:この設定により、学生はテナントドメイン名を使用せずにデバイスにサインインできるようになります。 学生は、エイリアスだけを使用してすばやく簡単にサインインできます。  

* **新しいタブページの構成**:この設定を使用すると、Microsoft Edge で学生がタブを追加したときに開くページを選択できます。 新しいタブでは、空のページや、学校のホームページなどのカスタムのページを開くことができます。  

* **S モードから切り替え**ます:この設定により、管理者は、デバイスをモードで Windows 10 から切り替えることができます。または、学生が自分のデバイスを S モードから切り替えることができなくなります。    

### <a name="updated-windows-settings-names-and-added-useful-tooltips"></a>Windows の設定名を更新し、役に立つヒントを追加しました  
Intune for Education の設定名とツールヒントの多くが変更され、見つけやすく、理解しやすくなっています。 各設定の詳細については、「 [Intune for Education の Windows 10 デバイス設定](all-edu-settings-windows.md)」を参照してください。  

### <a name="rename-windows-devices"></a>Windows デバイスの名前を変更する  
Intune for Education ポータルから、Windows 10 (バージョン1803以降) デバイスの名前をリモートで変更します。 名前を変更するには、[デバイス] にアクセス**してデバイス**> 選択し、デバイスの**名前を変更**します。 デバイスの**詳細**ページからデバイスの名前を変更することもできます。  

## <a name="november-2018"></a>2018 年 11 月  

### <a name="remote-autopilot-reset"></a>リモート自動再設定のリセット 
Intune for Education ポータルを使用して、自動操縦リセットをリモートで起動できるようになりました。 自動操縦リセットは、ユーザーがインストールしたアプリと個人設定を含むすべてのユーザーデータを削除し、デバイスを Intune に登録したままにして、最新のすべてのアプリ、ポリシー、設定を使用してデバイスを最新の状態に保ちます。 この機能を使用すると、学生の Pc をすばやくワイプして再構成し、新しい school year 用に準備することができます。 自動操縦リセットの詳細について[はこちら](autopilot-reset.md)をご覧ください。

### <a name="new-features-for-ios-management"></a>IOS 管理の新機能
- Intune for Education では、Apple School Manager VPP トークンの場所情報が表示されるため、Intune for Education と Apple School Manager の両方から VPP トークンを簡単に識別できます。 
- Intune for Education に VPP トークンのニックネームを指定して、ラベル付けと組織を簡単に行うことができます。 
- MDM サーバートークンを設定すると、iOS デバイスの登録がより高速になりました。 Intune for Education によって登録設定が自動的に構成されるため、MDM サーバートークンに関連付けられているデバイスには、タップするセットアップアシスタント画面が少なくなります。 
 
### <a name="delete-device"></a>デバイスの削除
Intune for Education ポータルでデバイスを削除できるようになりました。 デバイスを削除しています:
- Intune にデバイスを登録解除します。
- デバイスレコードを Azure Active Directory から削除します。これにより、デバイスは環境に含まれなくなります。
 
### <a name="immersive-reader-for-all-tenants"></a>すべてのテナントのイマーシブリーダー 
教育機関向け Windows ストアでは、Intune for Education にサインアップするときに、イマーシブリーダーのライセンスを無制限に取得できます。 イマーシブリーダーは、すべての年齢と機能について学習するためのアクセシビリティとの包含を含む読み取り体験を作成するための学習ツールです。 イマーシブリーダーの詳細について[は、こちら](https://www.onenote.com/learningtools)を参照してください。
 
### <a name="effective-policy-page"></a>[有効なポリシー] ページ
[有効] ポリシーページには、グループメンバーシップに基づいてユーザーとデバイスの組み合わせに適用されたすべてのアプリと設定が表示されます。 このページでは、競合している可能性がある設定を確認し、問題のトラブルシューティングを行うことができます。 有効なポリシーページには、次の2つの方法で接続できます。
- ユーザー > をクリックし、[**ユーザーの詳細] にアクセス**して、ユーザーが最近チェックインしたデバイスを選択 > ます。
- デバイスをクリックし > [**デバイスの詳細] にアクセス**し、そのデバイスで最近チェックインされたユーザーを選択 > ます。



## <a name="july-2018"></a>2018 年 7 月 

### <a name="all-new-support-for-ios-classroom-devices"></a>IOS クラスルームデバイスのすべての新しいサポート  

Intune for Education が、教室での iOS デバイス管理をサポートするようになりました。 Intune for Education に新しい機能とページが追加され、すべてのユーザーがセットアップと管理を簡単に行えるようになりました。 ダッシュボードから、デバイスを正常にセットアップ、構成、および登録するために必要なすべてのものを取得できます。  

* IOS デバイス管理のセットアップ:Apple アカウントを Intune for Education にすばやく接続するための[ステップバイステップガイダンス](setup-ios-device-management.md)を含む新しいページが追加されました。 画面インジケーターを使用すると、必要な手順とオプションの手順、正常に完了した手順、有効期限が近づいているものを明確に確認できます。
* 高速構成:Windows 10 のエクスペリエンスと同じように、iOS デバイス向けに設計されているので、 [ios の高速構成](express-configuration-intune-edu.md)を使用すると、アプリと設定をすばやく割り当てたり変更したりできます。 ユーザーまたはデバイスのグループを選択し、Microsoft が推奨する設定から選択します。 これらの[推奨事項は事前に選択され](edu-express-config-settings-ios.md)ていますが、学校のポリシーに合わせていつでも変更できます。  
* アプリと設定:[IOS](all-edu-settings-ios.md)または[Windows 10](all-edu-settings-windows.md)デバイスの管理に集中できるように、アプリとデバイスの設定のビューを個別に追加しました。 [APPLE vpp サポート](add-vpp-apps-ios.md)を追加したので、vpp で購入したアプリを Intune for Education と同期し、ダッシュボードから直接割り当てることができます。 
* 動的なグループ化:これで、特定のデバイスプラットフォーム規則を[動的グループ](create-groups.md#dynamic-groups)に適用できるようになりました。 Windows 10*または*iOS デバイス上のデバイスまたは学生に適用する規則を作成します。  

詳細については、 [Intune for Education](what-is-intune-for-education.md)のドキュメントで新しいページとワークフローを移動する方法に関するページを参照してください。   

## <a name="january-2018"></a>2018 年 1 月

### <a name="history-of-group-actions-taken-by-admins"></a>管理者が実行したグループアクションの履歴

管理者によって実行されるすべてのアクションの履歴を表示して、承認されたグループのグループ管理者、アプリ、および設定を変更できるようになりました。 この履歴のログは、**グループ** > の**履歴**」で確認できます。

### <a name="windows-defender-report"></a>Windows Defender レポート

新しいレポートが追加されました。 [レポート] ページでは、レポートの一覧から **[Windows Defender レポート]** を選択できます。 これにより、すべてのデバイスの Windows Defender デバイスの正常性状態を表示できます。 これは、[レポートとは何ですか?](what-are-reports.md) doc で確認できます。

### <a name="use-role-based-access-control-to-enable-group-admins"></a>ロールベースのアクセス制御を使用してグループ管理者を有効にする

他のグループの設定を管理するユーザーのグループを選択できるようになりました。 たとえば、"高校の*管理者*" というグループを作成することができます。ここでは、メンバーは、学区の高校を持つ管理者のチームです。 *High School Admins*グループには、高校の学生のグループの設定を管理するためのアクセス許可が付与されている可能性があります。 詳細については、「[グループとは](what-are-groups.md)」を参照してください。

### <a name="user-and-device-search"></a>ユーザーとデバイスの検索

サイドバーに2つの新しいオプションが追加されました。**ユーザー**と**デバイス**。 これらの方法を使用して、個々のユーザーまたはデバイスを検索し、これらの項目の**詳細**をすばやく開くことができます。 これらの検索をサイドバーに追加するには、**すべて** > の**星ボタン (お気に入り) をクリック**してお気に入りの一覧に追加します。

### <a name="remote-actions"></a>リモート操作

これで、ユーザーとデバイスでリモート操作を実行できるようになりました。 アクションを実行するデバイスを選択し、[詳細] ページで次の操作のいずれかを選択します。

#### <a name="devices"></a>[デバイス]

- 再起動
- 工場出荷時の設定にリセットする
- 同期
- 管理から削除

#### <a name="users"></a>ユーザー

- パスワードの再設定

[リモート操作](edu-device-remote-actions.md)の詳細については、こちらを参照してください。

### <a name="wi-fi-profiles"></a>Wi-Fi プロファイル

**Wi-fi プロファイル**のサイドバーに新しいオプションが追加されました。 これにより、別のデバイス、ユーザー、およびグループに割り当てることができる Wi-fi 設定を定義できます。

## <a name="october-2017"></a>2017 年 10 月

### <a name="dynamic-groups"></a>動的グループ

ルールを定義し、それらに基づいて自動的に設定されるグループを作成します。

### <a name="new-app-status"></a>新しいアプリの状態

アプリを追加すると、アプリのインストールのデバイスごとおよびユーザーごとの状態が表示されるようになります。

### <a name="updated-details-pages"></a>更新された詳細ページ

いずれかのグループのユーザーまたはデバイスを選択します。 ウィンドウが画面の下部から上にスライドするようになり、そのオブジェクトに関する詳細情報と、割り当てられているアプリと設定の状態が表示されます。

## <a name="may-2017-initial-release"></a>5月 2017 (初回リリース)

### <a name="intune-for-education-is-now-available"></a>Intune for Education が利用可能になりました。

Intune for Education ポータルを起動しました。 Intune for Education は、学校および教育機関が Windows 10 デバイスを管理するための合理化されたエクスペリエンスです。 Intune for Education の詳細については、こちらのドキュメントを参照してください。

## <a name="next-steps"></a>次の手順

- [詳細については、Intune for Education を参照してください。](what-is-intune-for-education.md)
- [Intune でのデバイス管理エクスペリエンスの詳細については、こちらを参照してください。](https://docs.microsoft.com/intune/understand-explore/introduction-to-microsoft-intune)

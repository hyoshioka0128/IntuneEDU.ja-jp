---
title: 新機能
titleSuffix: Intune for Education
description: Intune for Education で最近リリースされたことを確認します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 12/3/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 7d8dfd82-8cee-4874-85f6-edaf84e49c4c
searchScope:
- IntuneEDU
.#ms.devlang: ''
ms.openlocfilehash: 2adeb14cf197f543f312d0cbd1bb46b322736eb8
ms.sourcegitcommit: 7c51c36929e1406eb5fb26d76dc755c98611fd19
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2018
ms.locfileid: "52886460"
---
# <a name="whats-new-in-intune-for-education"></a>Intune for Education の新機能新機能
Intune for Education の新機能新機能について説明します。 今後の変更、製品の通知、および以前のリリースからの機能について調べます。

## <a name="november-2018"></a>2018 年 11 月 

### <a name="remote-autopilot-reset"></a>リモートの Autopilot のリセット 
これで、Autopilot リセット for Education コンソールと Intune を使用してリモートでを呼び出すことができます。 Autopilot のリセットは、デバイスは常に最新のすべての最新のアプリ、ポリシー、および設定するために、Intune でユーザーがインストールしたアプリと個人設定とデバイスの登録を保持を含むすべてのユーザー データを削除します。 この機能により、すばやくワイプし、新しい学校年度の準備を行う一括で学生の Pc を再構成できます。 Autopilot リセット詳細については[ここ](autopilot-reset.md)します。

### <a name="new-features-for-ios-management"></a>IOS 管理の新機能
- Intune for Education に今すぐは、教育と Apple School Manager の両方の Intune から VPP トークンを簡単に識別できるように、Apple School Manager VPP トークンの場所の情報を表示します。 
- 簡単にラベル付けと組織の intune for Education、VPP トークンのニックネームを指定できます。 
- 登録は、MDM サーバー トークンを設定するときに、iOS デバイスをさらに高速ようになりました。 Intune for Education は、MDM サーバー トークンに関連付けられているデバイスをタップしてセットアップ アシスタント画面が少ないために、登録の設定を自動的に構成されます。 
 
### <a name="delete-device"></a>デバイスを削除します。
これで、for Education コンソールと、Intune でデバイスを削除することができます。 デバイスの削除。
- Intune にデバイスの登録が解除されます。
- デバイスは、環境の一部が不要になったために、Azure Active Directory からのデバイス レコードを削除します。
 
### <a name="immersive-reader-for-all-tenants"></a>すべてのテナントの没入型のリーダー 
教育機関向けのインベントリ、Windows ストアは、Intune for Education にサインアップするときに、没入型のリーダーの無制限ライセンスを取得します。 没入型リーダーは、すべての年齢層と機能の学習器のアクセシビリティと包含の読みやすさを作成する学習ツールです。 詳細については、没入型リーダーは[ここ](https://www.onenote.com/learningtools)します。
 
### <a name="effective-policy-page"></a>有効なポリシー ページ
有効なポリシー ページには、すべてのアプリとグループ メンバーシップに基づいてユーザーとデバイスの組み合わせに適用する設定が表示されます。 このページからは、競合している問題のトラブルシューティングを行う可能性のある設定を確認できます。 2 つの方法で有効なポリシー ページに到達することができます。
- デバイスをクリックしてユーザーをクリックしますでそのユーザーが最近チェックします。
- デバイスでクリックし、そのデバイスで最近チェックインしたユーザーのをクリックします。



## <a name="july-2018"></a>2018 年 7 月 

### <a name="all-new-support-for-ios-classroom-devices"></a>クラスルームの iOS デバイス向けのすべての新しいサポート  

Intune for Education に今すぐには、教室での iOS デバイスの管理がサポートしています。 Intune for Education の関係者全員のセットアップと管理プロセスを簡単にする新機能とページが追加されました。 ダッシュ ボードで、すべてが正常にセットアップ、構成、およびデバイスを登録する必要がある必要があります。  

* IOS デバイス管理のセットアップ: を含む新しいページが追加されました[ステップ バイ ステップ ガイダンス](setup-ios-device-management.md)Apple アカウントを Intune for Education にすばやく接続するためです。 画面に表示されるインジケーターは、必須および省略可能な手順、正常に完了したものと有効期限が近づいているものを明確に確認できます。
* 高速構成: が、iOS デバイスに合わせて、Windows 10 エクスペリエンスと同様に[iOS 用の高速構成](express-configuration-intune-edu.md)迅速に割り当てるし、アプリと設定を変更するのに役立ちます。 単にユーザーまたはデバイスのグループを選択し、Microsoft の推奨設定から選択します。 これら[の推奨事項があらかじめ選択](edu-express-config-settings-ios.md)、ですが、学校のポリシーに一致するように、いつでも変更できます。  
* アプリと設定: 個別のアプリとデバイスの設定のビューには、追加したいずれかに注目する[iOS](all-edu-settings-ios.md)または[Windows 10](all-edu-settings-windows.md)デバイスの管理。 使用すると追加[Apple VPP サポート](add-vpp-apps-ios.md)、Intune for Education で購入した VPP アプリを同期し、ダッシュ ボードから直接割り当てることができます。 
* 動的なグループ化: に特定のデバイス プラットフォームの規則を適用することができますので、[動的なグループ](create-groups.md#dynamic-groups)します。 デバイスまたは Windows 10 での受講者に適用するルールを作成*または*iOS デバイス。  

詳細を取得し、新しいページとワークフロー内を移動する方法について説明します、 [Intune for Education](what-is-intune-for-education.md)ドキュメント。   

## <a name="january-2018"></a>2018 年 1 月

### <a name="history-of-group-actions-taken-by-admins"></a>管理者によって行われたグループ アクションの履歴

これで、グループの管理者、アプリケーション、および、承認されたグループの設定を変更する管理者によって実行されたすべてのアクションの履歴を表示できます。 この履歴でのログを検索する**グループ** > **履歴**します。

### <a name="windows-defender-report"></a>Windows Defender レポート

新しいレポートが追加されました。 [レポート] ページを選択できます**Windows Defender レポート**レポートの一覧から。 これにより、すべてのデバイスの Windows Defender デバイス正常性の状態を表示できます。 これでどのように確認できます、[レポートとは?](what-are-reports.md)ドキュメント。

### <a name="use-role-based-access-control-to-enable-group-admins"></a>ロール ベース access control を使用して、グループの管理者を有効にするには

ここでの他のグループの設定を管理するユーザー グループを選択できます。 たとえば、という名前のグループがある*高校管理者*メンバーが、チームの担当地域の高校の管理者は、します。 *高校 Admins*高校生のグループの設定を管理するアクセス許可グループを指定する可能性があります。 参照してください、[グループとは? doc](what-are-groups.md)します。

### <a name="user-and-device-search"></a>ユーザーとデバイスの検索

サイド バーに 2 つの新しいオプションが追加されました:**ユーザー**と**デバイス**します。 これらを使用して、個々 のユーザーまたはデバイスを検索し、すばやく開くことができます、**詳細**これらの項目。 これらの検索を追加するには、サイド バーに**すべてを参照してください** > **星ボタン (お気に入り)** お気に入りの一覧に追加します。

### <a name="remote-actions"></a>リモート操作

これで、ユーザーとデバイス上のリモート操作を実行できます。 アクションを実行し、詳細ページから、次の操作のいずれかを選択するデバイスを選択します。

#### <a name="devices"></a>[デバイス]

- 再起動
- 工場出荷時設定にリセットします。
- 同期
- 管理対象から削除します。

#### <a name="users"></a>Users

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

---
title: 既定の高速構成での iOS の設定
titleSuffix: Intune for Education
description: 既定の設定の名前と高速構成を使用する場合の設定の動作を示します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/19/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: af6eca94a4098885ef7c932f39e9c787e2a4450b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147493"
---
# <a name="default-ios-settings-in-express-configuration"></a>既定の高速構成での iOS の設定
高速構成は、iOS デバイスまたはユーザーのグループをすばやくセットアップするための推奨設定であらかじめ設定されています。 Intune for Education では、Microsoft によって推奨されてな学校環境に最適な設定を選択します。 学校のルールとポリシーに合わせて推奨事項を適用する設定 ページを直接クリックしてしたり変更を加えます。 

設定と説明の完全な一覧で、次を参照してください。 [Intune for Education のすべての iOS 設定](all-edu-settings-ios.md)します。 

> [!IMPORTANT]
> 高速構成を起動するときに iOS の構成が無効の場合は、MDM Apple プッシュ証明書と DEP トークンの両方を設定したことを確認します。 これらの両方がある場合は、どちらも期限が切れたことを確認します。 IOS デバイス管理の設定に関する詳細については、次を参照してください[iOS デバイス管理の設定。](setup-ios-device-management.md)


## <a name="app-store-itunes-store-and-book-store"></a>アプリ ストア、iTunes ストア、および帳ストア  
設定|提案される値|  
|---|---|
|アプリ ストアを禁止|ブロック|
|アプリ内購入のブロック|ブロック|
|App Store と iTunes ストアに明示的なコンテンツをブロック|ブロック|
|アダルトのフラグが Apple ブックの「コンテンツのダウンロードを禁止する|ブロック|  

## <a name="built-in-apps"></a>組み込みアプリ  
設定|提案される値|  
|---|---|
|カメラをブロックします。|ブロック|
|Facetime をブロックします|ブロック|
|Game Center のブロック|ブロック|  
|Apple Music のブロック|ブロック|
|メッセージ アプリをブロック|ブロック|
|Apple のブックをブロックします。|ブロック|  

## <a name="device-restrictions"></a>デバイスの制限  
設定の名前|提案される値|
|---|---|
|デバイスの名前を変更するブロック|ブロック|
|壁紙の変更をブロックします。|ブロック|
|通知設定の変更をブロックします。|ブロック|
|コンテンツとプライバシーの制約に変更をブロック|ブロック|
|すべてのコンテンツと設定を消去するブロック ボタン|ブロック|  

## <a name="icloud"></a>iCloud
|設定|提案される値|
|---|---|
|ICloud バックアップのブロック|ブロック|
|ドキュメントと icloud の同期をブロックします。|ブロック|
|ICloud フォト ライブラリをブロックします。|ブロック|  

## <a name="lock-screen-and-wallpaper"></a>ロック画面と壁紙
設定|提案される値|
|---|---|
|ロック画面で通知をブロック|ブロック|
|ロック画面から Wallet へのアクセスをブロック|ブロック|
|デバイス ロック画面イメージの設定|.Jpg または .png ファイルです。最大サイズは 960 KB|
|デバイスのホーム画面の画像の設定|.Jpg または .png ファイルです。最大サイズは 960 KB|  

## <a name="passcode-touch-id-and-face-id"></a>パスコード、タッチの ID と Face ID  
設定|提案される値|
|---|---|  
|パスコードが必要です。|未構成|
|パスコードの変更をブロックします。|ブロック|
|デバイスがワイプされるまでのパスコードが失敗した試行回数|未構成|
|ブロック タッチ ID と Face ID|ブロック|

## <a name="siri-and-search"></a>Siri と検索 
設定|提案される値|
|---|---|   
|Siri をブロック|ブロック|  

## <a name="reset-default-settings"></a>既定の設定をリセットします。
既定値には、すべての設定を復元するには、クリックして**提案された既定値にリセット**します。 

## <a name="next-steps"></a>次の手順  
グループ、設定、および intune for Education の監視の競合についてすべて説明します。 
* 間の差を調べる[と動的な割り当て](create-groups.md)グループ
* 割り当てる[グループ管理者](group-admin-delegate.md)内または学区間で、学校の教室設定の管理に役立つ
* 学習方法[設定の継承](settings-inheritance.md)影響グループの割り当て
* レビュー[レポート](what-are-reports.md)を特定し、設定の競合のトラブルシューティング

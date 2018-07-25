---
title: Windows 10 のすべてのデバイス グループのプリセット
titleSuffix: Intune for Education
description: サインアップ時に、あらかじめ設定されている Windows 10 デバイスの設定の一覧を参照してください。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: b056056676d561471ee2de625b7aab0f8d0c6224
ms.sourcegitcommit: ecf53ed32308ea0f592788e19f8649801997cbdb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2018
ms.locfileid: "39234429"
---
# <a name="all-devices-group-presets-for-windows-10"></a>すべてのデバイスは、Windows 10 用のプリセットをグループ化します。
アカウントにサインアップすると、Intune for Education 事前設定、設定の一部、すべてのデバイス グループでされます。 これらの設定には、教室での Windows 10 デバイスの管理を簡単に開始するのに役立ちます。 設定を調整するのには、Intune for Education ポータルに移動 >**グループ** > **すべてのデバイス** > **Windows デバイスの設定**します。  

すべての Windows 10 デバイスの設定の説明の一覧については、次を参照してください。 [Windows 10 デバイスの設定](all-edu-settings-windows.md)します。  

|Category|設定|事前定義された値|
|---|---|---|
|Windows Defender|Windows Defender の設定をユーザーのアクセスをブロック|Enabled
|Windows Defender|リアルタイムの監視|Enabled
|Windows Defender|動作の監視|Enabled
|Windows Defender|ユーザーにサンプル送信|データを送信することはありません。
|Windows Defender|実行するシステム スキャンの種類|クイック スキャン|
|Windows Defender|日次クイック スキャン時刻|2 午前時|
|Windows Defender|ダウンロードされたすべてのファイルをスキャンします。|Enabled|
|Windows Defender|Microsoft の web ブラウザーで実行されるスクリプトをスキャンします。|Enabled|
|Windows Defender|フル スキャン中にリムーバブル ドライブをスキャンします。|Enabled|
|Windows Defender|ネットワーク経由で開かれたファイルをスキャンします。|Enabled|
|Windows Defender|フル スキャン中にリモート フォルダーをスキャンします。|Enabled|
|Windows Defender|アーカイブ ファイルをスキャンする|Enabled|
|Windows Defender|着信電子メールをスキャンします。|Enabled|
|Windows Defender|ファイルとプログラムのアクティビティをスキャンします。|すべてのファイルを監視|
|Windows Defender|検疫済みマルウェアを削除する前に日|0|
|Windows Defender|設定の更新頻度|8 時間|
|Windows Defender|クラウド ベースの保護を有効にします。|Enabled|
|Microsoft Store|プライベート ストアからインストールする教育機関向け Microsoft Store が必要です。|Require|
|Microsoft Store|信頼できるアプリ|ブロック|  
|Microsoft Edge|開発者ツールをブロックする|ブロック|
|Microsoft Edge|Cortana をブロックします。|ブロック|
|基本的なデバイス|手動での登録解除をブロックします。|ブロック|
|基本的なデバイス|プロビジョニング パッケージの追加をブロックします。|ブロック|
|基本的なデバイス|プロビジョニング パッケージの削除をブロックします。|ブロック|
|デバイスの更新|ブランチ準備レベル|半期チャネル (対象指定)
|デバイスの更新|プレリリース版の機能|許可しない
|デバイスの更新|配信の最適化モード|Nat ピアリング対応のブレンド HTTP |
|デバイスの更新|更新プログラムとメンテナンス期間|自動的にインストールし、エンドユーザーによる制御なしに再起動|
|共有デバイス|共有使用のデバイスを最適化します。|Enabled|  

## <a name="next-steps"></a>次の手順

- [完全な Windows 10 の設定の管理エクスペリエンス Intune で使用可能な詳細します。](https://docs.microsoft.com/intune/deploy-use/windows-10-policy-settings-in-microsoft-intune)

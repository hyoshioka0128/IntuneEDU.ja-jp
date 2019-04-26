---
title: 管理での iOS デバイスを登録します。
titleSuffix: Intune for Education
description: Intune for Education の Windows 10 デバイスを設定する方法について説明します。
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
ms.openlocfilehash: 36f545b21c94b4ab171b5dc7201eb4db2f58b7e1
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62145919"
---
# <a name="enroll-ios-devices-in-intune-for-education"></a>教育機関向けの Intune で iOS デバイスを登録します。

デバイスは電源をオンにした後、管理に登録できます。

* Intune for Education のセットアップ[学校に関する情報と](what-is-school-data-sync.md)-学生レコード、アプリケーション、およびデバイスの設定などです。
* IOS デバイスを管理する Intune を有効にする[Apple プッシュ MDM 証明書と Apple MDM サーバー トークンを設定する](setup-ios-device-management.md#add-an-mdm-push-certificate)します。
* [Apple MDM サーバー トークンの同期](setup-ios-device-management.md#sync-managed-devices)で Intune for Education とデバイスの登録準備完了の一覧を参照してください。  

> [!NOTE]
> デバイスがインターネットに接続されているし、十分な Intune は、セットアップを完了する for Education のデバイス ライセンスを持つアカウントの確認します。 ライセンスについて詳しく[ユーザーにライセンスを割り当てる](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)します。

## <a name="pre-configured-enrollment-profile"></a>事前に構成された登録プロファイル
Intune for Education では、作成し、学校に最適化された登録プロファイルを同期された各デバイスに割り当てます。  

デバイス自体の設定および管理に登録する方法を指示する登録プロファイルが構成されます。 Intune は、お客様の加入契約を高速化するのに役立つ設定を構成します。  デバイスの電源を入れると、登録プロファイルはデバイスのセットアップを直ちに開始します。

## <a name="list-of-preconfigured-settings"></a>事前構成済み設定の一覧
デバイスの初期セットアップ中にデバイスを次の構成と登録します。

* ユーザー アフィニティなし
* 監視モードを有効になっています。
* 同期またはその他のデバイスとのペアリングをブロック
* ロックされた登録は、意味のユーザーが自分のデバイスの管理設定を変更できません。


登録時に、次のセットアップ アシスタントの設定が非表示になります。
* パスコードの設定
* 位置情報サービス
* デバイスの復元
* iCloud と Apple ID
* Touch ID セットアップ
* Apple Pay のセットアップ
* ズームのオプションが表示されます。
* Siri のセットアップ
* 診断データのオプション

登録時に次のセットアップ アシスタントの設定が表示されます。
* 使用条件

### <a name="what-is-setup-assistant"></a>セットアップ アシスタントとは
という教育の起動、iOS のボックスのエクスペリエンスを初めてお使いのデバイスをオンにする Intune*セットアップ アシスタント*します。 セットアップ アシスタントでは、一連の画面について説明し、学校の使用には、デバイスを準備します。  

## <a name="enroll-a-device"></a>デバイスを登録します。

完全なデバイスの登録には、次の手順について説明します。

1. iOS デバイスをオンにします。 
2. **[Language\(言語\)]** を選択した後、デバイスを Wi-Fi に接続します。
3. **IOS デバイスを設定する**画面で、、**国/地域**します。
4. Wi-fi に接続を自動または手動で画面に表示される指示に従います。 接続すると、後に、**構成**登録の詳細と、画面が表示されます。  
5. 同意、**条件を読んで**します。 Apple に診断情報を送信するかどうかを決定します。  

## <a name="next-steps"></a>次の手順
これでデバイスには、セットアップおよび学校の使用の準備ができるが、更新、監視、およびトラブルシューティングする方法を説明します。   
* さらに追加[無料](add-apps-ios.md)と[VPP](add-vpp-apps-ios.md)校 1 年を通じて iOS アプリ
* 割り当てる[グループ管理者](group-admin-delegate.md)内または学区間で、学校の教室設定の管理に役立つ
* 学習方法[設定の継承](settings-inheritance.md)新しいグループに影響を与えます
* レビュー[レポート](what-are-reports.md)を特定し、エラーのトラブルシューティング 
* 更新[iOS の証明書し、トークン](renew-ios-certificate-token.md)毎年

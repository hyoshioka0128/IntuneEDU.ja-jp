---
title: "設定の管理方法"
titleSuffix: Intune for Education
description: "Intune を介して教育ポリシーの設定を管理するこれらの手順に従います。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 20c0f6c9-f1de-4048-aa96-5b0a068c1b75
searchScope: IntuneEDU
.md#ms.tgt_pltfrm: 
ms.openlocfilehash: a8a9619476315459d49dc128e14c3bc0f2f7794e
ms.sourcegitcommit: 2914b0e879129878ab55f59d288a0739f0e00fb9
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/24/2017
---
# <a name="how-do-i-manage-settings"></a>設定の管理方法

さまざまなユーザー、アプリ、および Intune でデバイスの設定を管理することができます。 方法は変更するデバイスをユーザーの操作に応答できる方法をお勧めします。

デバイスのグループに適用される設定と、そのグループからデバイスをアクセスするときにユーザーが影響をします。 設定が、ユーザーのグループに適用されている場合

デバイスの設定は、そのグループ内のすべてのデバイスに適用されます。 設定**未構成**ユーザー自身がデバイスにその設定を定義できるようにします。

## <a name="manage-settings-for-groups"></a>グループの設定を管理します。

教育用の Intune の設定の完全な一覧を管理するのにには、次の手順を使用します。
1. [教育用の Intune](https://intuneeducation.portal.azure.com)コンソールの左側のナビゲーション メニューで、選択**グループ**です。
2. 設定を管理するグループを選択します。 完全な一覧についてを参照してください。[使用可能な設定](what-are-settings.md)です。
3. をクリックして**設定**を利用可能な設定の完全な一覧を表示するページの上部にあります。
4. カテゴリを展開し、選択したグループの個々 の設定を変更します。
5. をクリックして**保存**そのグループに対する変更を保存します。 設定は、そのグループ内のデバイスに自動的に送信されます。

## <a name="manage-settings-with-express-configuration"></a>Express の構成と設定を管理します。

Express 構成を簡単にすばやく作業を開始するが、デバイスを簡単に変更することができます。

  ![Express の構成設定の修正プログラム](./media/express-config-006-choose-settings.png)

1. [教育用の Intune](https://intuneeducation.portal.azure.com)コンソールで、選択**Express 構成を起動して**です。 レビュー、**ようこそ**ページし、選択**開始**です。
2. 確認、**学校の情報を取得**ページ。 既に学校の情報を追加した場合は、選択**次**です。
3. グループ設定を管理、および順に選択する対象を選択して**次**です。
4. アプリの一覧を確認し、**次**です。
5. **設定** ページで、使用可能な設定のカテゴリを展開します。
  * [基本的なデバイスの設定](available-settings.md#basic-device-settings)
  * [Microsoft Edge の設定](available-settings.md#microsoft-edge-settings)
  * [デバイスの設定の更新](available-settings.md#device-update-settings)
  * [ワイヤレス設定](available-settings.md#wireless-settings)
  * [アプリの設定](available-settings.md#app-settings)
  * [サインイン設定](available-settings.md#sign-in-settings)

  カテゴリを展開し、設定を変更し、コントロールを切り替える**次**です。

6. 選択内容を確認し、**完了**を保存する、変更内容を更新、選択したグループ内のデバイス。

## <a name="can-i-ever-have-settings-that-dont-work-together"></a>I を持つことが連携していない設定しますか。

互換性のない設定を同じグループに適用することができます。 これらの不整合エラーが生じるときに、ユーザーまたはデバイスに設定されている設定が異なる複数の場所にします。 これは、ユーザーまたはデバイスが複数のグループのメンバーの結果として発生します。

などのメンバーである Esperanza、 *6 グレード*グループ化し、という名前のグループのメンバーでも*地球サイエンス*です。 ホーム ページの設定を構成して割り当てる場合*6 グレード*、別のホーム ページの設定を構成し、それを割り当てると*地球サイエンス*、自分のユーザーに割り当てられている 2 つの競合するホーム ページ設定を今すぐ持ってです。 一貫性のない設定の割り当てがエラーに先行する結果になります。 使用して設定エラーのあるデバイスとユーザーを見つけることができます、[設定エラー レポート](what-are-reports.md)です。

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

- [Intune のポリシー全体の管理エクスペリエンスについて詳しくを調べます](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)

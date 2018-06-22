---
title: 設定の管理方法
titleSuffix: Intune for Education
description: Intune を介して教育ポリシーの設定を管理するこれらの手順に従います。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: angrobe
ms.date: 05/06/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 20c0f6c9-f1de-4048-aa96-5b0a068c1b75
searchScope:
- IntuneEDU
.md#ms.tgt_pltfrm: ''
ms.openlocfilehash: eff69edf43b2dcaa9278af0baf7132c1db693a0a
ms.sourcegitcommit: 957bb155e37f507fcc1c6c114536256fdfbe71fe
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2018
ms.locfileid: "33808028"
---
# <a name="how-do-i-manage-settings"></a>設定の管理方法

割り当てるし、ユーザー、アプリ、およびデバイスの設定を編集します。 適用される設定、*デバイスのグループ*グループのユーザーがデバイスにアクセスする方法を決定します。 適用される設定、*ユーザーのグループ*ディクテーション、グループのすべてのデバイスの動作方法です。 

Intune の設定としてマークされている場合**未構成**、受講者が自分のデバイスから設定にアクセスし、必要な方法に設定ことができます。

## <a name="manage-group-settings"></a>グループ設定を管理します。

グループの設定を管理する次の手順を実行します。
1. [教育用の Intune](https://intuneeducation.portal.azure.com)し、左側のナビゲーション メニューに移動して選択**グループ**です。
2. 設定を管理するグループを選択します。 完全な一覧についてを参照してください。[使用可能な設定](what-are-settings.md)です。
3. をクリックして**設定**を利用可能な設定の完全な一覧を表示します。
4. カテゴリを展開を選択し、選択したグループに個々 の設定を編集します。
5. をクリックして**保存**そのグループに対する変更を保存します。 設定は、そのグループ内のデバイスに自動的に送信されます。

## <a name="manage-settings-with-express-configuration"></a>Express の構成と設定を管理します。

Express 構成では、すぐに Intune で開始することができます。 行えますがいつでも設定を簡単に変更します。 Express の構成設定を変更する次の手順を実行します。

  ![Express の構成設定の修正プログラム](./media/express-config-006-choose-settings.png)

1. [教育用の Intune](https://intuneeducation.portal.azure.com)、選択**Express 構成を起動して**です。 
2. レビュー、**ようこそ**ページし、をクリックして**開始**です。
2. 確認、**学校の情報を取得**ページ。 学校の情報を既に追加した場合はクリックして**次**です。
3. 設定を管理するグループを選択します。 **[次へ]** をクリックします。
4. アプリの一覧を確認します。 **[次へ]** をクリックします。
5. **設定** ページで、使用可能なすべての設定を表示するカテゴリを展開します。 設定を変更するためにコントロールを切り替えます。
   * [基本的なデバイスの設定](available-settings.md#basic-device-settings)
   * [Microsoft Edge の設定](available-settings.md#microsoft-edge-settings)
   * [デバイスの設定の更新](available-settings.md#device-update-settings)
   * [ワイヤレス設定](available-settings.md#wireless-settings)
   * [アプリの設定](available-settings.md#app-settings)
   * [サインイン設定](available-settings.md#sign-in-settings)

6. 完了したら、設定を編集するには、をクリックして**次**です。
7. 選択内容を確認します。 をクリックして**完了**して変更を保存します。

## <a name="conflicting-settings-in-intune-for-education"></a>教育用の Intune の設定の競合
同じグループ内の競合する設定を適用することができます。 ときに、割り当てがこれらの設定をデバイスまたはユーザーは、エラーが発生する可能性があります。 競合する設定の値を持つユーザーまたはデバイスが所属するグループが構成されている場合、エラーが発生します。

などのメンバーである Esperanza、 *6 グレード*グループ化し、という名前のグループのメンバーでも*地球サイエンス*です。 ホーム ページの設定を割り当てる*6 グレード*です。 別の値のホーム ページの同じ設定を構成し、それを割り当てる*地球サイエンス*です。 両方のグループに属する Esperanza には、これらのホーム ページ設定の競合が割り当てられます。 この割り当ては、エラーが発生します。 モニターの設定エラーおよび表示する方法を学習[設定エラー レポート](what-are-reports.md)です。

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

- [Intune のポリシー全体の管理エクスペリエンスについて詳しくを調べます](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)

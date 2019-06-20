---
title: Windows 10 デバイスを登録します。
titleSuffix: Intune for Education
description: Intune for Education の Windows 10 デバイスを設定する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 29d4b238fb906eac01f3ffe36dd252f8b657d046
ms.sourcegitcommit: 9c43411a2c210cf1d755c3120015c89611e33613
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/18/2019
ms.locfileid: "67213392"
---
# <a name="enroll-windows-10-devices"></a>Windows 10 デバイスを登録します。

情報を含む Intune for Education を設定した後: 生徒の記録、アプリ、およびデバイスの設定など、Intune for Education にデバイスを接続します。 新しい Windows 10 デバイスの場合は、デバイスの初期セットアップ中に接続が確立されています。   

## <a name="when-to-use-set-up-school-pcs-vs-windows-autopilot"></a>学校の Pc と Windows Autopilot 設定を使用する場合  
次の表では、学校の Pc と Windows Autopilot のどちらか一方または両方のデバイスの初期セットアップの設定を使用する場合について説明します。 使用して、**考慮すべき点**学校の環境とセットアップのニーズを考慮する列。  

|考慮すべき点| 学校の Pc を設定します。 |Windows Autopilot  |
|---------|---------|---------|  
|IT staff (IT スタッフ) | IT スタッフは、デバイスがボックス化解除を実行、最初に、およびデバイスの構成は、IT スタッフによって実行します。|IT スタッフからの限られたエンゲージメントに適しています。 学生と教員は、デバイスがボックス化解除、初めて電源オンと初期構成を実行できます。|
|デバイスのユーザー|  共有デバイスと、低学年の方に最適です。|1 対 1 のデバイスと、古い受講者に最適です。|
|アプリ     | 低速ネットワークで同時に大規模なアプリを展開するために最適です。|あらゆる規模のアプリでうまく機能します。| 
|ネットワーク | 信頼性の高いインターネット接続が必要です。低帯域幅のネットワークに最適です。| 信頼性の高いインターネット接続が必要です。ネットワーク帯域幅の消費量が必要なアプリの同時実行デバイス設定の数とサイズに基づいて。 受講者は、ホーム ネットワーク上のデバイスをセットアップできます。|
|クラスの最初の日|デバイスは、サインインの準備が整ったし、すぐに使用します。| 受講者がボックス化解除し、ネットワークに接続する必要があります。セットアップで自動的に完了します。|
|デプロイ時|1 ~ 2 分ほどかかることができます。同時実行デバイスの設定、ネットワーク帯域幅、および必要なアプリケーションのサイズの数に基づいて時間が増加します。|1 ~ 2 分ほどかかることができます。同時実行デバイスの設定、ネットワーク帯域幅、および必要なアプリケーションのサイズの数に基づいて時間が増加します。|
|Oem/パートナー|該当なし。  |パートナー (CSP) や OEM プロバイダーによって、Windows Autopilot サービス デバイス Id の登録が必要です。 |
|既存のオンプレミス構成| Windows 構成デザイナーのみでサポートされます。 | ハイブリッド AD 参加をサポートしています。デバイスは、Active Directory ドメイン コント ローラーと同じネットワークである必要があります。|  
### <a name="setting-up-devices-with-windows-autopilot"></a>Windows Autopilot のデバイスのセットアップ
 使用してデバイスを設定する[Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/windows-autopilot-requirements)に移動して、 [Intune](https://devicemanagement.microsoft.com) > **デバイスの登録** > **Windows 登録**  > **デバイス**します。   

### <a name="setting-up-devices-with-set-up-school-pcs-app"></a>学校の Pc のアプリを設定すると、デバイスの設定
学校の Pc のアプリの設定を Intune に Windows デバイスを追加します。 アプリでは、構成し、複数の Pc に配布できる 1 つのデバイス プロファイルを保存する方法について説明します。 USB ドライブは、保存し、デバイスのセットアップ中に各デバイスにプロファイルのダウンロードに使用されます。 

アプリの詳細については、次を参照してください。、[設定されている学校の Pc を?](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)記事。 

## <a name="setup-windows-devices"></a>Windows デバイスのセットアップ  
Intune for Education に、Windows 10 デバイスを追加する、次の手順を完了します。 セットアップ中には、インターネットへのアクセスがデバイスに必要です。 

1. 新しい Windows 10 デバイスの電源を入れます。 
2. 新規またはリセットのデバイスで最初のセットアップ画面を読み取り、**リージョンから始まることができます。正しいですか。** Pc が配置されているリージョンを選択します。 選び**はい**します。  

   ![Windows 10 の OOBE の開始セットアップ画面のスクリーン ショットの例です。 選択したリージョンと米国が強調表示されます。](./media/RS5_Choose_Region.png)  

3. キーボード レイアウトを選択します。 この手順では、キーボードの物理的なレイアウトを一致するようにスクリーン キーボードを構成します。 言語およびキーボードの文字も構成します。 選択**はい**を続行します。  

      ![キーボード レイアウト画面、選択したレイアウトとして強調表示されている米国の例のスクリーン ショット。](./media/RS5_Choose_Keyboard.png)  

4. もう 1 つのキーボード レイアウトを追加する場合は、選択**追加レイアウト**します。 それ以外の場合、選択**スキップ**します。   

     ![右上隅にある追加のレイアウトとスキップするオプションを使用して、2 番目のキーボード レイアウト画面のスクリーン ショットの例です。](./media/RS5_Second_keyboard.png)  

5. 選択**を職場や学校を設定する**します。 選び**次**します。  

     ![例のスクリーン ショット、* * 方法を選んで設定するか? * * 画面で、職場または学校の設定するオプションを強調表示します。](./media/RS5_Choose_Setup_Type.png)  

6. 電子メール アドレスの種類は、学校の管理者または登録マネージャー アカウントに関連付けられています。 選び**次**します。  

     ![例のスクリーン ショット、* * * * Microsoft 画面、Microsoft のロゴ、および電子メールのフィールドが空でサインインします。](./media/RS5_Sign_In.png)  

7. アカウントのパスワードを入力します。 選び**次**します。  

     ![例のスクリーン ショット、* *、組織のロゴ、およびパスワード フィールドが空で、画面 * パスワード * を入力します。](./media/RS5_Enter_Password.png)  



8. デバイスのプライバシー設定を選択します。 学校のポリシーに基づくこれらの設定を構成します。 一部の設定など**音声認識**と**場所**既定でオンにします。  

     ![プライバシー設定の一部の設定を使用して、オプションの一覧を表示するスクリーン ショットの例は、既定でオンにします。](./media/RS5_Choose_Settings.png)  


9. 選択**Accept**デバイス セットアップを完了します。 セットアップを完了すると、そのため、自由に別のデバイスでセットアップを開始するまで数分かかる場合があります。  

## <a name="next-steps"></a>次の手順
デバイスでは、学校用に最大と準備ができたらを設定は、これで、更新、監視、およびトラブルシューティングする方法を説明します。   
* 割り当てる[グループ管理者](group-admin-delegate.md)内または学区間で、学校の教室設定の管理に役立つ
* すべて確認[Windows 設定](all-edu-settings-windows.md)に調整します。
* 学習方法[設定の継承](settings-inheritance.md)新しいグループに影響を与えます
* レビュー[レポート](what-are-reports.md)を特定し、エラーのトラブルシューティング  

 

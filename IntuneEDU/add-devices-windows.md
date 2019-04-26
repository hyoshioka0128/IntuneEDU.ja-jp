---
title: デバイスを追加する
titleSuffix: Intune for Education
description: Intune for Education の Windows 10 デバイスを設定する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 10/30/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 1cb892665cc597e29ad315fe4d95a2e1ec26c2f2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146421"
---
# <a name="add-windows-devices"></a>Windows デバイスを追加します。

情報を含む Intune for Education を設定した後: 生徒の記録、アプリ、およびデバイスの設定など、Intune for Education にデバイスを接続します。 新しい Windows 10 デバイスの場合は、デバイスの初期セットアップ中に接続が確立されています。

## <a name="setting-up-devices-with-windows-autopilot"></a>Windows Autopilot のデバイスのセットアップ
[Windows Autopilot](https://docs.microsoft.com/intune/enrollment-autopilot) for Azure portal で Intune に設定するには、教育機関が Intune との互換性です。 Autopilot を使用してデバイスをセットアップするには[Intune](https://portal.azure.com) > デバイスの登録 > Windows 登録 > デバイス。  

## <a name="before-you-begin"></a>アンインストールの準備
セットアップ中には、インターネットへのアクセスがデバイスに必要です。 

## <a name="windows-device-setup"></a>Windows デバイスのセットアップ
Intune for Education に、Windows 10 デバイスを追加する、次の手順を完了します。

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

## <a name="set-up-school-pcs-app"></a>学校の Pc のアプリを設定します。
学校の Pc のアプリの設定を Intune に Windows デバイスを追加します。 アプリでは、構成し、複数の Pc に配布できる 1 つのデバイス プロファイルを保存する方法について説明します。 USB ドライブは、保存し、デバイスのセットアップ中に各デバイスにプロファイルのダウンロードに使用されます。 

アプリの詳細については、次を参照してください。、[設定されている学校の Pc を?](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)記事。 

   ![学校の PC のアプリ、スタート画面の設定の例のスクリーン ショット。](./media/Set_up_School_PC.png)  

 

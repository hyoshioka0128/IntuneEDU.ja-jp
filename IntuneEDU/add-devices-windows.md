---
title: デバイスを追加する
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
ms.openlocfilehash: ca0d1b9e4abcdde3cf6bf697ca57d665bd74dd56
ms.sourcegitcommit: ecf53ed32308ea0f592788e19f8649801997cbdb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2018
ms.locfileid: "39234673"
---
# <a name="add-windows-devices"></a>Windows デバイスを追加します。

情報を含む Intune for Education を設定した後: 生徒の記録、アプリ、およびデバイスの設定など、Intune for Education にデバイスを接続します。 新しい Windows 10 デバイスの場合は、デバイスの初期セットアップ中に接続が確立されています。

## <a name="before-you-begin"></a>始める前に
セットアップ中に、デバイスが必要です。
* インターネットにアクセスします。
* Intune for Education のデバイス ライセンス。 Intune でデバイスのライセンスについて詳しく[ライセンス docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)します。  

## <a name="windows-device-setup"></a>Windows デバイスのセットアップ
Intune for Education に、Windows 10 デバイスを追加する、次の手順を完了します。

1. 新しい Windows 10 デバイスの電源を入れます。 標準の Windows デバイスのセットアップに従ってください。 
2. **この PC の所有者は誰でしょうか。** 画面で、**職場または学校が所有してその**。

   ![「ユーザー所有この PC ですか?」のスクリーン ショット Windows セットアップで画面](./media/devices-001-who-owns-this-pc.png)

2. **を接続する方法を選択して**画面で、 **Azure AD に参加**します。

   ![Windows セットアップで「の接続方法の選択」画面のスクリーン ショット](./media/devices-002-how-you-connect-pc.png)

3. Intune for Education 登録の管理者またはマネージャーのアカウントの詳細を入力します。 **[次へ]** をクリックします。

4. デバイス[が Azure AD で認証](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access)グループまたはグループに属していると識別します。  
セットアップの完了後、すべてのアプリとそのグループに割り当てられている設定、デバイスが表示されます。

## <a name="set-up-school-pcs-app"></a>学校の Pc のアプリを設定します。
学校の Pc のアプリの設定を Intune に Windows デバイスを追加します。 アプリでは、構成し、複数の Pc に配布できる 1 つのデバイス プロファイルを保存する方法について説明します。 USB ドライブは、保存し、デバイスのセットアップ中に各デバイスにプロファイルのダウンロードに使用されます。 

アプリの詳細については、次を参照してください。 [**学校の Pc 設定**アプリ](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)します。

[Intune にデバイスを追加する完全なエクスペリエンスの詳細について検索をしますか。](https://docs.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune)

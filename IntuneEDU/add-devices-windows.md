---
title: デバイスを追加する
titleSuffix: Intune for Education
description: Intune for Education の Windows 10 デバイスを設定する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 10/24/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 4f687e4833a9ba98bdea15a915aa96c5840796cd
ms.sourcegitcommit: 30c3fc997170745070794e9fbb6725a29c9e502b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2018
ms.locfileid: "50088973"
---
# <a name="add-windows-devices"></a>Windows デバイスを追加します。

情報を含む Intune for Education を設定した後: 生徒の記録、アプリ、およびデバイスの設定など、Intune for Education にデバイスを接続します。 新しい Windows 10 デバイスの場合は、デバイスの初期セットアップ中に接続が確立されています。

## <a name="setting-up-devices-with-windows-autopilot"></a>Windows Autopilot のデバイスのセットアップ
[Windows Autopilot](https://docs.microsoft.com/intune/enrollment-autopilot) for Azure portal で Intune に設定するには、教育機関が Intune との互換性です。 Autopilot を使用してデバイスをセットアップするには[Intune](https://portal.azure.com) > デバイスの登録 > Windows 登録 > デバイス。  

## <a name="before-you-begin"></a>始める前に
セットアップ中には、インターネットへのアクセスがデバイスに必要です。 

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

---
title: "デバイスを追加します。"
titleSuffix: Intune for Education
description: "教育用の Intune の Windows 10 デバイスを設定する方法を説明します。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope: IntuneEDU
ms.openlocfilehash: 7b5343d996868ceaf18a58812a4db14d626d2969
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/15/2017
---
# <a name="how-do-i-add-devices-to-intune-for-education"></a>教育用の Intune にデバイスを追加する方法

お客様の情報で教育用の Intune を設定した後: 学生レコード、アプリ、およびデバイスの設定など — 教育を Intune にデバイスを接続する必要があります。 これは、新しい Windows 10 デバイスのセットアップ エクスペリエンスの一部としての操作を行うことができます。


> [!NOTE]
> デバイスがインターネットへのアクセスを必要し、十分な Intune のセットアップの完了に使用可能な教育デバイスのライセンスの必要があります。 詳細については、これを調べることができます、[ライセンス docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)です。

## <a name="add-devices-to-intune-for-education"></a>教育用の Intune にデバイスを追加します。

表示する必要があります for Education Intune による管理に Windows 10 デバイスを表示するには、次の操作を行います。

1. 新しい Windows 10 デバイスを有効にし、標準の Windows セットアップを開始します。 達すると、**この PC の所有者はだれですか?**画面で、**職場または学校に所有されている**です。

  ![「の所有者はだれこの PC ですか?」のスクリーン ショット Windows セットアップで画面](./media/devices-001-who-owns-this-pc.png)

2. **接続する方法を選択して**画面で、 **Azure AD に参加**です。

  ![Windows セットアップで「の接続方法の選択」画面のスクリーン ショット](./media/devices-002-how-you-connect-pc.png)

3. 教育管理用の Intune のアカウントの詳細を入力または**他の登録の権限がユーザー**選択**[次へ]**です。

デバイスは[Azure AD で認証](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access)とセットアップが完了したら、割り当てられているアプリと設定を受信します。

デバイスを登録する別の方法は、使用、[空き__学校の Pc 設定__アプリ](how-should-i-enroll-devices.md)USB キーを使用して Pc を迅速にセットアップします。 

## <a name="find-out-more"></a>詳細は以下のページをご覧ください
- [について、**学校の Pc 設定**アプリ](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)
- [Intune にデバイスの追加の完全なエクスペリエンスについて詳しくを調べます](https://docs.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune)

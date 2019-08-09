---
title: デバイスを登録するにはどうすればよいですか。
titleSuffix: Intune for Education
description: Intune for Education にデバイスを登録する方法についてのアドバイスを得ます。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 45160df9-126d-4c51-a0d3-0e9fad0fe929
searchScope:
- IntuneEDU
ms.openlocfilehash: 006fa1267566524b86acbf0e5a29235f41eb5ac2
ms.sourcegitcommit: 05576d32cac5cc3998ea579404ce84a2813c9083
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/09/2019
ms.locfileid: "68866724"
---
# <a name="how-should-i-enroll-devices"></a>デバイスを登録する方法

Intune for Education 管理でデバイスを登録する方法について説明します。 学校に最適な方法を選択するには、次の点を考慮してください。  
* 地区の規模。    
* デバイスの受信者の種類。    
* ヘルプで利用できるスタッフの数。   
 
学校にデバイスを登録するための最適な方法を決定するには、「」を参照してください。    

## <a name="run-the-set-up-school-pcs-app"></a>School Pc のセットアップアプリを実行する 
Windows 10 の各 Pc に、school に最適化された設定の1つのセットをアップロードします。 「 [School pc のセットアップ」アプリ](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)では、学校に適したインストールパッケージを作成する方法を説明しています。 ネットワークとデバイスの設定の構成が完了すると、アプリはパッケージを USB ドライブに保存します。 各学生 PC に直接 USB ドライブを挿入し、学生用にデバイスを自動的に設定します。 このアプリは、Windows 10 バージョン1903以前を実行している Pc と互換性があります。

## <a name="give-school-faculty-enrollment-manager-permissions"></a>School 教職員登録マネージャーのアクセス許可を付与する
登録マネージャーまたは登録マネージャーアカウントを追加して、スタッフがデバイスの登録を支援できるようにします。 [登録マネージャー](add-enrollment-managers.md)は、最大1000のデバイスを登録できます。  

## <a name="allow-users-to-enroll-their-own-devices"></a>ユーザーが自分のデバイスを登録できるようにする
信頼されたユーザーが自分のデバイスを登録できるようにします。 これらのユーザーは、デバイスを Azure AD に自動的に参加させることができます。  

## <a name="next-steps"></a>次の手順  

デバイスを登録する準備ができましたか? Intune for Education 管理で[iOS](add-devices-ios-edu.md)デバイスと[Windows 10](add-devices-windows.md)デバイスを追加する方法について説明します。  

* Microsoft Store から[ **School Pc のセットアップ**アプリをダウンロード](https://www.microsoft.com/store/p/set-up-school-pcs/9nblggh4ls40)するには、ストアのドキュメントを参照してください。 
* 詳細[について](https://docs.microsoft.com/education/windows/set-up-windows-10)は、Microsoft 教育 > windows のドキュメントを参照してください。


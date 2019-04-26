---
title: アプリのインストール方法
titleSuffix: Intune for Education
description: Intune for Education でアプリを管理する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 635a5cc7-7dd4-45f9-9b18-3eddb76d0c74
searchScope:
- IntuneEDU
ms.openlocfilehash: 260679748d8ddb891d042abd6e0d7d0f5f698b34
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146549"
---
# <a name="installing-apps-on-school-devices"></a>学校のデバイスでアプリのインストール

学校のデバイスでアプリをインストールするには、最初に、グループに割り当てるがあります。 この記事では、学生の教師にアプリを割り当てるの 3 つの方法について説明します。  

アプリを割り当てた後、アプリは、適切なデバイスに送信されます。 Intune for Education にデバイスがチェックインする際に、アプリのインストールが開始されます。 

## <a name="add-apps-to-intune-for-education-inventory"></a>アプリを Intune に教育のインベントリを追加します。
既定では、人気のアプリが直接割り当ての Intune for Education で利用できます。 アプリを割り当てる必要がある場合、インベントリは、Intune for Education では、次の記事のいずれかに追加する方法を学習します。
* [教育機関向け Microsoft Store](acquire-store-apps.md)
* [無料の iOS App Store アプリ](add-apps-ios.md)
* [iOS VPP アプリ](add-vpp-apps-ios.md)
* [Windows 10 のデスクトップ アプリ](add-desktop-apps-edu.md)
* [Web アプリ](add-web-apps-edu.md)  

## <a name="assign-apps-with-express-configuration"></a>高速構成を使用したアプリを割り当てる
移動して[高速構成](Express-configuration-intune-edu.md)を 1 つのグループに複数のアプリを割り当てます。 

1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**高速構成**します。  
2. アプリに追加するグループを選択します。 **[次へ]** をクリックします。
3. グループに展開する 1 つまたは複数のアプリを選択します。 **[次へ]** をクリックします。 
4. アプリは、グループに自動的に割り当てられます。 高速構成の手順を続行します。

##  <a name="assign-apps-to-a-single-group"></a>1 つのグループにアプリを割り当てる
グループを選択し、そのグループ内のデバイスに 1 つまたは複数のアプリをインストールします。

1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**グループ**します。
2. アプリを展開するグループを選択します。
3. 上部にあるタスク バーに移動し、をクリックして**アプリ**使用可能なアプリの一覧を表示します。  
4. グループに展開する 1 つまたは複数のアプリを選択します。 
5. 選択**保存**そのグループに選択したアプリを展開します。 インストールは、デバイスのチェックインを Intune for Education に次回を自動的に開始されます。  

## <a name="asign-apps-to-multiple-groups"></a>複数のグループに Asign アプリ
アプリを選択し、インストールの 1 つまたは複数のグループに割り当てます。

1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**アプリ**します。
2. 左上のアプリの一覧からには、割り当てるアプリを選択します。
3. 上部にあるタスク バーに移動し、をクリックして**グループ** > **グループ割り当ての変更**します。 
4. アプリを割り当てるグループを選択します。  

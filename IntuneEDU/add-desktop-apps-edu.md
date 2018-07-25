---
title: Intune for Education にデスクトップ アプリを追加します。
titleSuffix: Intune for Education
description: アップロードして、Intune for Education にデスクトップ アプリの新しいファイルを追加する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
- IntuneEDU
ms.openlocfilehash: 91c7a3bd20bcc51000ce16a1f77109c2093bb21b
ms.sourcegitcommit: ecf53ed32308ea0f592788e19f8649801997cbdb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2018
ms.locfileid: "39234692"
---
# <a name="add-desktop-apps-in-intune-for-education"></a>Intune for Education でデスクトップ アプリを追加します。

アップロードし、デスクトップ アプリを Intune for Education のインベントリに追加します。 後に、アプリを追加したら、[をグループに割り当てる](install-apps.md)し、Windows 10 デバイスにインストールします。  

次の手順を完了するには、インストール ファイルを追加するアプリの必要があります。  

1. Intune for Education ポータルにサインインします。
2. **[アプリ]** をクリックします。
3. 左側のウィンドウで [**デスクトップ アプリ**、] をクリックして**新しいアプリ**します。
4. **新しいデスクトップ アプリ**セクションで、次の詳細を入力します。
   * **アプリ ファイル**-MSI インストーラーをアプリをアップロードします。
   * **アプリ名**— デバイス上で表示するアプリの名前。
   * **説明**— は迅速なアプリの説明では、それを識別します。
   * **パブリッシャー** -すぐに始めるため、アプリの発行元の名前は、アプリ開発者を識別します。
   * **アイコン**-アプリのアイコンとして使用する PNG または JPG ファイルをアップロードします。
5. フォルダー アイコンをクリックし、コンピューターからのアプリのインストール ファイルを選択します。 
6. **[Save]**(保存) をクリックします。 アプリは、Intune for Education にし、アップロードされます。 アップロードが完了したら[デバイスにアプリを割り当てる](install-apps.md)します。 

   ![サンプル アプリでは、evernote 追加新しいデスクトップ アプリ、画面のすべてのフィールドが記入します。](./media/apps-004-filled-out-desktop-app.png)  

> [!NOTE]
> エラーが発生した、「、アプリは、インストール ファイルが見つからない」または「アプリのインストール ファイルが追加されませんでした」、ファイルが正しくアップロードされません。 これを解決するには、アップロードをもう一度ファイルを保存してみてください。

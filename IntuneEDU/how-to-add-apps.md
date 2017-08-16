---
title: "アプリを追加する"
titleSuffix: Intune for Education
description: "教育用 intune アプリを追加する方法を説明します。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope: IntuneEDU
ms.openlocfilehash: 7a2298d4a1b55d8a1355ca9e828d92c0a561eac8
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/15/2017
---
# <a name="how-do-i-add-apps-to-intune-for-education"></a>教育用 intune アプリを追加する方法

For Education、学校のデバイスを Intune でアプリをインストールすることができます、前にそれらのアプリが教育アカウントに、Intune に追加する必要があります。

教育用の Intune には、次の種類のアプリがサポートされています。
- Web アプリのように[Word オンライン](https://office.live.com/start/Word.aspx)
- Microsoft ストア アプリについては教育、いずれかである[ストアによって配布されているユニバーサル アプリ](https://technet.microsoft.com/itpro/windows/manage/apps-in-windows-store-for-business)
- デスクトップ アプリでなど[スタンドアロンの Microsoft Office](https://products.office.com/products)

アプリを追加すると、後にすることができます[がアプリをインストール](install-apps.md)デバイスのグループにします。

設定は、アプリのグループを含む、すべてのグループに適用されます。 グループが設定されて、別の上の 1 つのグループの階層としてため[グループに割り当てられているすべてのアプリは、すべてのサブグループによって継承](settings-inheritance.md)です。

## <a name="add-web-apps"></a>Web アプリを追加します。

A _web アプリ_ブラウザー ファイルを排他的にユーザーによってアクセスされるアプリです。 これらは、各自のデバイスにインストール ファイルを送信するのではなく、web サイトへのリンクは、すべてのユーザーに送信する必要があるため、割り当てる簡単できます。

教育用の Intune を使用して Windows 10 デバイスの [スタート] メニューでのリンクとして web アプリケーションを割り当てることができます。 アプリを割り当てる必要があります最初に追加する Intune での Education の**アプリを管理する**セクションです。

  ![追加、新しい web アプリケーション ページをユーザーに次の手順で説明されている情報の入力を求められる。](./media/apps-001-add-webapp.png)

1. [教育用の Intune](https://intuneeducation.portal.azure.com)コンソールで、選択**アプリ**です。

2. **Web アプリの** **+ 新しいアプリ**、次の詳細を入力します。
 * **URL** — を割り当てる、アプリの URL
 * **アプリ名**-デバイスで [スタート] メニューに表示されるアプリの名前
 * **アイコン**-アプリのアイコンとして使用するコンピューターから、PNG、JPG またはのアップロード

3. **[保存]** を選びます。 Web アプリは、準備ができました。

4. できるようになりました[デバイスにアプリをインストール](install-apps.md)です。

選択して、いつでもアプリを編集できます**編集**、その詳細ページを再び開くをします。

## <a name="add-desktop-apps"></a>デスクトップ アプリを追加します。

同じインターフェイスを使ってデスクトップ アプリをインストールすることができます、**アプリ**ページ。 このプロセスは似ていますが、web アプリをインストールする web アプリを必要としないインストール ファイルが含まれます。

![新しいデスクトップ アプリ画面。](./media/apps-003-add-desktop-app.png)

1. [教育用の Intune](https://intuneeducation.portal.azure.com)コンソールで、選択**アプリ**です。

2. **デスクトップ アプリ** **+ 新しいアプリ**です。 これが開き、**新しいデスクトップ アプリ**画面では、次の詳細を入力します。
 * **アプリ ファイル**-アプリの MSI インストーラーのアップロード
 * **アプリ名**: デバイスに表示するアプリの名前
 * **説明**— はどのアプリをすばやく特定するを支援するにはアプリの説明
 * **パブリッシャー** — を迅速に、アプリの開発元を識別するを支援する、アプリの発行者の名前
 * **アイコン**-アプリのアイコンとして使用するコンピューターから、PNG、JPG またはのアップロード

3. 選択**を保存してファイルをアップロード**です。

  ![Evernote のサンプル アプリの追加新しいデスクトップ アプリ、画面のすべてのフィールドに入力します。](./media/apps-004-filled-out-desktop-app.png)

4. アプリは、教育を Intune にアップロードし、されます。 アップロードが完了したら[デバイスにアプリをインストール](install-apps.md)です。

> [!NOTE]
> 場合があります「、アプリは、インストール ファイルが見つからない」や「アプリのインストール ファイルが追加されませんでした」というエラーに遭遇する可能性があります。 これは、ファイルが正しくアップロードしていないことを意味します。 保存し、このエラーを解決するには、もう一度ファイルをアップロードしようとします。

## <a name="add-popular-apps"></a>一般的なアプリを追加します。

一般的な教育用のアプリは、教育向け Microsoft ストアからもすばやくインストールできます。 目標は、検索し、ユーザーのお気に入りのアプリのインストールを簡単にです。 これらのアプリは、教育者、役に立ちますいるため、お勧めします。 Express の構成では、または下にあるこれらのアプリを見つけることができます、**アプリを管理する**を並べて表示します。

  ![Express の構成で追加アプリケーション プロセス中に一般的なアプリの選択します。](./media/apps-005-popular-apps.png)

教育ポータル、Intune とを示しています上部 12 教育用の web アプリの下に追加していないアプリの教育 12 個の教育用 Microsoft ストアの上位**アプリ**管理します。

> [!TIP]
> 実行する方法を調べることができます教育アカウントに教育用 Intune アプリを追加する、Microsoft のストアをセットアップしていない場合[ここ](acquire-store-apps.md)です。

1. [教育用の Intune](https://intuneeducation.portal.azure.com)コンソールで、選択**アプリの管理** > **アプリを追加する** > **クイック追加人気のあるアプリ**です。 一連の**Web アプリの**と**Microsoft ストア アプリ**が表示されます。

  ![クイックは、人気のあるアプリ 画面を追加します。](./media/apps-006-add-popular-apps.png)

2. を追加し、を選択するアプリを選ぶ**アプリを追加する**です。

  ![ポータルに追加する複数の一般的なアプリを選択します。](./media/apps-007-select-multiple-popular-apps.png)

3. アプリは、背景に追加して、準備ができたら、左側にあるサイドバーに表示されます。

  ![アプリは、画面に追加されているされます。](./media/apps-008-your-popular-apps-are-being-added.png)

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

- [Intune を使用してアプリの管理の完全なエクスペリエンスについて詳しくを調べます](https://docs.microsoft.com/intune/deploy-use/add-apps)

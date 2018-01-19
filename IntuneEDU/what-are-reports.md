---
title: "レポートとは"
titleSuffix: Intune for Education
description: "レポートが役立つ教育用の Intune でのアクティビティを理解する方法について説明します。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 01/17/2018
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: a5922c35-261c-43db-9c7b-c5c93af9cbec
searchScope: IntuneEDU
ms.reviewer: travisj
ms.openlocfilehash: 1abe5e35e574e1bc058c861247974105333e1b18
ms.sourcegitcommit: eec0d728af6e8404c08b4b71fb557a5b946b2853
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/19/2018
---
# <a name="what-are-reports-in-intune-for-education"></a>教育用の Intune のレポートとは

教育用の Intune では、デバイスと教育用の Intune で管理されているアプリからの特定のアクティビティを表示するのに便利なレポートを提供します。 これらのレポートを確認してオフラインをダウンロードすることができます。

現在、教育用の Intune で表示できるレポートの 3 種類があります:__デバイスのインベントリ__、__アプリケーション インベントリ__、および__設定エラー__です。

1. [教育用の Intune](https://intuneeducation.portal.azure.com)コンソールで、選択**レポート**左側のナビゲーション バーでします。

2. 表示するレポートを選択します。 次のレポートは、教育用の Intune で利用できます。

  * **デバイスのインベントリ**— 教育用の Intune で管理されているデバイスの一覧です。

  ![デバイス インベントリ レポート画面、教育管理に Intune でデバイスの一覧を表示します。](./media/reports-001-device-inventory.png)

  * **アプリケーション インベントリ**Education、そのアプリがインストールされているデバイスの数などの Intune で管理対象デバイスにインストールされているアプリの一覧です。

  ![アプリケーション インベントリ レポート画面、教育管理向けに Intune でアプリの一覧を表示します。](./media/reports-002-app-inventory.png)

  * **設定エラー** — は設定の一覧[競合で現在](settings-inheritance.md)階層内のグループに対してです。

  ![設定のエラーは、設定の競合の一覧を表示 画面を報告します。](./media/reports-003-settings-error.png)

  その特定の種類のアプリに関する (web アプリ、デスクトップ アプリ、Microsoft のストア アプリ) のみの情報を表示するアプリの種類を選択することもできます。

## <a name="download-reports"></a>レポートをダウンロードします。

レポートの教育 Intune をダウンロードすることもできます。 [教育用の Intune](https://intuneeducation.portal.azure.com)コンソールで、ダウンロード中に関心があるレポートを検索します。 選択、**レポートをダウンロード**エクスポートし、表示およびなどのスプレッドシート アプリケーションに変更されたことができますをコンマ区切り値 (.csv) ファイルとしてレポートをダウンロードするにはボタン[Excel](https://support.office.com/article/Import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba)です。

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

- [Intune での完全なレポート作成エクスペリエンスについて詳しくを調べます](https://docs.microsoft.com/intune/deploy-use/understand-microsoft-intune-operations-by-using-reports)
- [Microsoft Graph を使用するレポートについて詳しくを調べます](https://developer.microsoft.com/graph/docs/overview/overview)

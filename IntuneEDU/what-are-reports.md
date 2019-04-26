---
title: 表示し、intune for Education のレポートのダウンロード
titleSuffix: Intune for Education
description: デバイス、設定、および Intune for Education でアプリケーションのアクティビティを理解するのに役立つレポートを取得します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: a5922c35-261c-43db-9c7b-c5c93af9cbec
searchScope:
- IntuneEDU
ms.reviewer: travisj
ms.openlocfilehash: 8bc3fe827d3ca1b37a1b0f8ab226d4d15a30db05
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147255"
---
# <a name="view-and-download-reports"></a>表示し、レポートのダウンロード  

Intune for Education には、現在、デバイス、アプリケーション、設定、および正常性のインベントリを表示します。 レポートを確認またはオフラインの共有をダウンロードします。

この記事では、使用可能なレポートと Intune for Education に表示する方法について説明します。

## <a name="device-inventory"></a>デバイスのインベントリ
すべての学校の管理対象デバイスとデバイスの詳細を表示します。 デバイスは、故障または、アプリや設定を受信していない、ときに、最終チェックインを Intune で検出するには、このレポートに参照できます。   

   ![デバイス インベントリ レポート画面、教育機関向けの管理用に Intune でデバイスの一覧を表示します。](./media/reports-001-device-inventory.png)

## <a name="application-inventory"></a>アプリケーション インベントリ
学校で管理対象デバイスにインストールされているすべてのアプリを表示します。 このレポートは、展開の問題のトラブルシューティングに役立つ詳細を提供します。 デバイスにアプリが属しているとインストールされている現在のバージョンの数などの重要な詳細を参照してください。  
 
 ![アプリケーション インベントリ レポート画面、教育機関の管理のための Intune でアプリの一覧を表示します。](./media/reports-002-app-inventory.png)  

## <a name="settings-errors"></a>設定エラー
現在の設定エラーと影響を受けるグループの一覧を表示します。 このレポートには、デバイスと競合する、未解決の設定を持つユーザーの両方が一覧表示します。   

   ![設定エラー レポートの画面で、設定の競合の一覧を表示します。](./media/reports-003-settings-error.png)

## <a name="windows-defender"></a>Windows Defender
学校では、すべての管理対象デバイスの Windows Defender デバイスの正常性状態を表示します。 このレポートには、完全にセキュリティで保護されていないデバイスにアラートを生成するデバイスの正常性状態が表示されます。 

## <a name="access-your-reports"></a>レポートにアクセスできます。

1. [Intune for Education のダッシュ ボード](https://intuneeducation.portal.azure.com)、 をクリックして**レポート**します。  
2. 表示するレポートを選択します。 
3. 検索ボックスを使用すると、特定のデバイス、アプリケーション、および設定を検索できます。
4. レポートをダウンロードするには、次のようにクリックします。**レポートのダウンロード**します。 Intune for Education は、レポートをコンマ区切り値 (.csv) ファイルとしてコンピューターにダウンロードされます。 ビューとスプレッドシート アプリケーションでは、ファイルを変更できますよう[Excel](https://support.office.com/article/Import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba)します。  

## <a name="next-steps"></a>次の手順  
詳細について、 [Intune でのエクスペリエンスを完全なレポート](https://docs.microsoft.com/intune/deploy-use/understand-microsoft-intune-operations-by-using-reports)またはレポートについて[Microsoft Graph を使用して](https://developer.microsoft.com/graph/docs/overview/overview)します。

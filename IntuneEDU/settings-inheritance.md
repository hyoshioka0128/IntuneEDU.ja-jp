---
title: 設定の継承とは何ですか。
titleSuffix: Intune for Education
description: Intune for Education を使用してデバイスのグループの設定を管理する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 09/26/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope:
- IntuneEDU
ms.openlocfilehash: 5a981fb8916dc0318cc1599002ebe9001f1ef41b
ms.sourcegitcommit: f2b41a6a72016fbf36924881a312ec194ef5c0d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47237529"
---
# <a name="what-is-settings-inheritance"></a>設定の継承とは何ですか。

設定は、グループに適用されます。 グループが、上記の 1 つのグループの階層として設定するため、グループに適用されるすべての設定は、サブグループによって継承されます。 サブグループは、すぐ上のグループに加えた変更は、自動的にことができます。 このアクションの呼び出し_継承_します。 設定の継承 ia に多数のユーザーとデバイスの設定を適用する場合に便利です。  


  ![グループとサブグループのツリー。](./media/groups-002-inheritance.png)  


## <a name="configure-subgroups-individually"></a>サブグループを個別に構成します。  

最近の継承された設定を無効にするには、サブグループに直接移動します。 個別にして構成を削除するか、設定を追加します。 変更を保存します。

## <a name="settings-in-conflict"></a>競合の設定  

場合は、同じグループに競合する設定を適用すると、Intune はそれぞれを個別に分析します。 Intune は、常に確信を持っての 学校のポリシーに準拠する設定を選択します。

その他の場合は、Intune は、競合を解決できない場合に確認してください、[設定が競合](what-are-reports.md)レポートします。

### <a name="example-of-inheritance-conflict"></a>継承の競合の例  

例として、サブグループを検討してください。 *12 グレード AP コンピューター サイエンス*します。 親グループ、サブグループが分類*12 グレード*します。 すべてのファイルに要件をスキャンする厳密なセキュリティを割り当てるし、アプリ内のデバイスがダウンロードされました、 *12 グレード*グループ。

ただし、あるとわかっている割り当て、今後の*12 グレード AP コンピューター サイエンス*スキャンする必要がない JavaScript ファイルをダウンロードする必要があります。 設定の継承より制限の厳しいを上書きしない場合*12 番目のグレード*設定がユーザーに適用されます*12 グレード AP コンピューター サイエンス*します。

## <a name="settings-error-report"></a>設定エラー レポート

設定を解決できない場合は、設定のエラー レポートに表示されます。 レポートの詳細については、次を参照してください。[レポートの表示とダウンロード](what-are-reports.md)します。  

## <a name="next-steps"></a>次の手順  
詳細について、[すべてのグループが Intune で経験](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)します。

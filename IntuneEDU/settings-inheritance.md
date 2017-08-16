---
title: "設定の継承とは何ですか。"
titleSuffix: Intune for Education
description: "教育用の Intune でデバイスのグループの設定を管理する方法を説明します。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope: IntuneEDU
ms.openlocfilehash: 388e4f4468c3184d4dd941c74f8524a6302694f3
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/15/2017
---
# <a name="what-is-settings-inheritance"></a>設定の継承とは何ですか。

設定は、グループに適用されます。 としてグループが設定されているために、上のグループに適用される、別の任意の設定の 1 つのグループの階層は、すべてのサブグループに継承されます。 これにより、ユーザー、アプリ、およびデバイスの大規模なグループに設定を適用しやすくします。

  ![グループとサブグループのツリーです。](./media/groups-002-inheritance.png)

これは、すべてのグループの下にあるサブグループで、サブグループが自動的に継承するすぐ上のグループに加えた変更はどのようなことを意味します。 これと呼ばれる_継承_です。

## <a name="can-i-configure-subgroups-differently-after-inheriting-settings-from-another-group"></a>できます構成サブグループが異なる別のグループから設定を継承した後にか。

サブグループは、上位グループから設定を継承する場合でも、個別に構成できます。 継承された設定をオーバーライドするには、単に、必要な設定を構成し、それらを保存します。

## <a name="can-i-ever-end-up-with-settings-that-do-not-work-together"></a>これまでになる可能性が一緒に機能していない設定しますか。

同じグループに複数の設定が適用されたら、各設定は教育用の Intune で個別に分析されます。 ユーザーがデバイスの設定に準拠させる操作を強制的に特定の設定は常に優先他の設定。

、サブグループを検討してください*12 番目グレード AP コンピューター サイエンスの世界*、グループに*12 番目のグレード*です。 AP コンピューター科学クラスはセキュリティ スキャン、必要としない一部の JavaScript ファイルをダウンロードする必要がありますが、全体のレベルが同じ操作を実行しないようにすることがわかります。 設定の継承より制限の厳しいをオーバーライドしていない場合*12 番目のグレード*設定がユーザーに適用されます*12 番目グレード AP コンピューター サイエンスの世界*です。

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

  - [Intune でれたエクスペリエンスの詳細については、すべてのグループを見つける](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)

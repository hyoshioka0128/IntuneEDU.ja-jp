---
title: 設定とは
titleSuffix: Intune for Education
description: Intune を介して教育ポリシーの設定を管理する方法を説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU
ms.openlocfilehash: 8b65da8b3b10361407cd31335bfb7e3a811aeb85
ms.sourcegitcommit: 77b833e0bc82105f1f0d5a0559b0da165453cc4a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2018
ms.locfileid: "30297278"
---
# <a name="what-are-settings"></a>設定とは

_設定_を使用すると、ユーザーが自分のデバイスで機能させる方法を定義します。 デバイスの応答方法または単にデバイスで何かからユーザーを停止することによって、アクションを実行しようとしています。 ユーザーにこれを変更します。 教育設定用の Intune では、学校のデバイスで各機能を管理できます。

設定は、グループに適用されます。 グループが設定されて、別の上の 1 つのグループの階層と任意ため[グループに適用される設定はすべてのサブグループによって継承](settings-inheritance.md)です。 これにより、ユーザー、アプリ、およびデバイスの大規模なグループに設定を適用しやすくします。

## <a name="manage-settings"></a>設定を管理します。

これには教育用の Intune の設定を管理する次の 3 つの方法があります。

* __構成の express__: 最もよく使用される school 設定の選択で利用可能な[Express 構成](how-do-i-manage-settings.md#manage-settings-with-express-configuration)のため安全かつ教室でデバイスを使用して生産性を受講者として使用することができます。

* __グループ__: すべての個々 のグループのすべての設定を管理できます。 これは、Express の構成で使用可能な比較の設定の一覧を展開します。 調べる[設定がここで使用可能な](available-settings.md)します。

* __テナント設定__: テナントの設定に影響を与えるすべてのユーザーとデバイスの管理下にある必要があります。 これらの設定がで特定の管理者によって管理できるのみ、[テナントへのアクセスのレベルを適切な](what-are-tenants.md)します。

設定の設定し、グループを介してユーザーとデバイスに割り当てられていることができます。 グループ内のユーザーに割り当てられている設定が使用しているデバイスに関係なく、ユーザーのオプションを使用します。 グループ内のデバイスに割り当てられている設定は、デバイスにログオンしているユーザーに関係なく、デバイスに適用されます。

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

- [アプリと Intune の完全な管理エクスペリエンスを使用してデータを保護する方法について詳しく調べます](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)

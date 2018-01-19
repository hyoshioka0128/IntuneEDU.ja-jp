---
title: "グループの管理を委任する方法は?"
titleSuffix: Intune for Education
description: "教育用の Intune でのグループのロールを管理する方法を説明します。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 01/18/2018
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 9319be2e-cb7e-43c1-98fe-64281c8c09fd
searchScope: IntuneEDU
ms.openlocfilehash: 9daeb5c7a2aeb437c672337aed4c83fa015cdc60
ms.sourcegitcommit: eec0d728af6e8404c08b4b71fb557a5b946b2853
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/19/2018
---
# <a name="what-is-delegating-group-management"></a>グループの管理を委任するは何ですか。

お客様の IT スタッフは、学生、教師、および、学校の管理者のグループを管理する必要があります。 グループ管理者がのみ、特定のグループを管理する必要があるため*委任*admins の別のグループへのアクセスは、これらの管理者が承認されていない変更を加えるされないことを確認します。 管理グループは、このような作業を行う管理者で構成されます。

## <a name="what-can-admins-do-to-their-delegated-groups"></a>何ができる管理者の委任されたグループにしますか。

すべての管理者ロールは、教育用の Intune での特定の領域にアクセスする権限を持っています。 これらの領域を管理者グループのアクセスを委任する場合は、学校のデバイスやアプリを管理するための適切なアクセスを持つ組み込みの管理者ロールを自動的に割り当てられます。 

グループ管理者が、いくつかのさまざまな種類のアクションを起こすことです。

- デバイス、ユーザー、およびアプリに関する情報の表示
- 割り当てる、作成、削除、表示、およびデバイスとユーザー設定の更新
- 割り当てる、作成、削除、表示、およびアプリを更新します。
- レポートの表示
- 工場出荷時設定にリセットしています、再起動、ロックされていないデバイスをロックおよび同期の強制をなどのデバイスでリモート操作を実行します。

> [!TIP]
> これらのアクセス許可の変更は、高度なタスクです。 アクセス許可を変更またはカスタムのアクセス許可のセットを作成するかどうかに移動する必要があります[、完全な管理エクスペリエンス Intune](group-admin-delegate.md#find-out-more)です。 これらのアクセス許可は、Intune での組み込みの学校管理者ロールを構成します。 

## <a name="how-do-i-assign-admin-groups"></a>管理グループを割り当てる方法

1. 管理グループ管理者を許可するグループを開きます。
2. 開く、**グループ管理者** タブでそのグループ。
3. クリックして、**管理者の追加**ボタンをクリックし、選択**選択グループ**です。

次の手順を完了すると、このグループを管理できるように、グループの管理者のいずれかのする必要があります。

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

  - [Intune を使用した役割に基づいた管理の制御](https://docs.microsoft.com/intune/role-based-access-control)

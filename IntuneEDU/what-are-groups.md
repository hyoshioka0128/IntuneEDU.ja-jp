---
title: "グループとは"
titleSuffix: Intune for Education
description: "教育用の Intune でデバイスのグループを管理する方法を説明します。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 925fee7b2807a340d2b4d0e1e9aa4ca069875f84
ms.contentlocale: ja-jp
ms.lasthandoff: 07/05/2017


---

# <a name="what-are-groups"></a>グループとは

使用する_グループ_ユーザー、アプリ、および Education の Intune でデバイスを管理します。 ユーザーまたはデバイスに個別に各デバイスを管理することではなく一緒にグループ化することができます。 これにより、多数のユーザーとデバイスにアプリと設定を簡単に割り当てることができます。

グループを作成するときに適用するしくみの設定とアプリをユーザーとデバイスを検討してください。 たとえば、すべてのデバイスの場所のサービスを使用してアプリをブロックする必要があります。 これに代わる方法がどのように特定のグループ、受講者を行うのと同じものが必要になる[AP コンピューター サイエンスの世界](https://www.tealsk12.org)アプリのコードを編集します。

設定は、グループに適用されます。 グループが設定されて、別の上の 1 つのグループの階層としてため[グループに適用されるすべての設定はすべてのサブグループによって継承](settings-inheritance.md)です。 これにより、ユーザー、アプリ、およびデバイスの大規模なグループに設定を適用しやすくします。

教育用の Intune が自動的に作成、__すべてのデバイス__と__すべてのユーザー__テナントが作成されるときにグループ化します。 これらの既定グループは、ユーザーと、学校または学区でデバイスの広範なカテゴリを表すと[移動できない](what-are-groups.md#why-cant-i-move-certain-groups)です。


## <a name="managing-groups-and-subgroups"></a>グループとサブグループを管理します。

移動してグループを作成することができます**グループ**を選択し、**グループの作成**グループの一覧の先頭からです。 グループを作成することでさらに編成できます*サブグループ*下にある任意のグループ以外の__すべてのデバイス__または__すべてのユーザー__です。

  ![サブグループの作成の 2 つの場所の作成 サブグループ ページ-グループの名前と、サイドバーの上部にある、赤色で周回](./media/groups-007-create-subgroup.png)

1. [教育コンソール用の Intune](https://intuneeducation.portal.azure.com)**ユーザーとデバイスのグループを管理する**です。
2. その下に、サブグループを作成するグループを選択します。
3. をクリックして**サブグループを作成**、enter、**グループ名**です。

## <a name="making-changes-to-groups"></a>グループを変更をします。

グループを作成した後に可能であればそのメンバーシップを編集する必要があります: 担当地域の別の学校のデバイスが必要な場合の転送などです。

  ![グループ内のデバイスの編集](./media/groups-008-edit-group-membership.png)

1. グループを編集するメンバーを選択します。
2. 選択、**デバイス**タブです。
3. 選択、**デバイスを編集**を選択し、このボタンをクリックすると、**のデバイスの追加**リストからより多くのデバイスを追加するまたは**X**それを削除するデバイスの横にあります。

グループの名前を変更する必要がある場合は、名前を変更する必要があるグループを選択し、**の名前を変更**名を編集するボタンをクリックします。

## <a name="move-a-group"></a>グループを移動します。

グループを移動するには、グループ構造内でまたは**階層**です。

  ![赤で周回ボタンをグループに移動します。](./media/groups-010-move-groups.png)

1.  [教育ポータル用の Intune](https://intuneeducation.portal.azure.com)、選択**グループの管理**です。
2. 移動する必要があるグループを選択します。
3.  をクリックして**グループの移動**メニューの一覧に、または選択して、**グループの移動**ボタンをクリックします。
4.  グループ名を検索して、または階層を選択して、このグループを移動するグループの場所を選択します。
5.  選択**OK**して変更を保存します。

## <a name="why-cant-i-move-certain-groups"></a>特定のグループを移動する理由ことはできませんか。

教育用の Intune が提供する一連の既定のグループを移動することはできません**すべてのユーザー**と**すべてのデバイス**、ときに、[テナントが作成されて](what-are-tenants.md)です。 **すべて教師**と**すべて受講者**School データ同期は、教育用の Intune に生徒と教員のデータをインポート後に作成される既定のグループは、します。

ほとんどどこなる場合がありますを使用したサブグループ 2 つのグループの下に問題があります。

  ![複数のグループのエラー メッセージ サブグループが表示されます。](./media/groups-012-subgroup-is-under-two-groups-warning.png)

この場合、このサブグループ上に 1 つのグループを選択する必要があります。

## <a name="delete-a-group"></a>グループを削除します。

グループを削除すると、教育用の Intune は、そのグループのメンバーである任意のデバイスのアプリと設定のコレクションを削除します。 グループの削除は削除されませんようなユーザーまたはデバイスの管理から。

  ![ボタンが赤で周回 グループを削除](./media/groups-011-delete-groups.png)

1.  [教育ポータル用の Intune](https://intuneeducation.portal.azure.com)、選択**グループの管理**です。
2. 削除するグループを選択します。
3.  をクリックして**グループの削除**タスク一覧のいずれか。

## <a name="find-out-more"></a>詳細は以下のページをご覧ください

- [Intune の管理のエクスペリエンス全体のグループについて詳しくを調べます](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)


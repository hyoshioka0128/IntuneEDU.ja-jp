---
title: 登録マネージャーを追加します。
titleSuffix: Intune for Education
description: Intune for Education 登録マネージャーを追加する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 08/30/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: b496bc02-714e-4391-b533-4c9bdcf57483
searchScope:
- IntuneEDU
ms.openlocfilehash: 26b9a9c6eaabe85dbe77acd9a52f7b86b8a99d4d
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146991"
---
# <a name="add-enrollment-managers"></a>登録マネージャーを追加します。  

既存のユーザーにデバイス登録のアクセス許可を付与します。 デバイス登録マネージャー アカウントを持つユーザーは、intune for Education の最大 1000 台の Windows 10 デバイスを登録できます。

 登録マネージャー アカウントは、共有の Windows 10 デバイスを登録するのには、何千ものある大規模な組織で役立ちます。  

## <a name="requirements"></a>必要条件  

ユーザーをデバイス登録マネージャーとして追加するには、そのユーザーが Azure Portal に存在する必要があります。

デバイス登録のアクセス許可は、他の登録方法と一緒に使用できません。Apple Configurator セットアップ アシスタント、Apple Configurator と直接登録、Apple School Manager (ASM) または Device Enrollment Program (DEP) を使用します。  

## <a name="assign-enrollment-permissions"></a>登録のアクセス許可を割り当てる  

1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**登録マネージャー**します。
2. **[登録のアクセス許可を割り当てます] をクリック**します。
3. アクセス許可を割り当てるユーザーを選択します。 ユーザーの名前がわかっている場合、検索フィールドに検索できます。
4. **[保存]** をクリックします。

## <a name="remove-enrollment-permissions"></a>登録のアクセス許可を削除します。  
1. **登録マネージャー**画面の左側に移動し、ユーザーを選択します。 
2. クリックして**登録アクセス許可を削除**します。
3. クリックして**削除**操作を確定します。 デバイス登録マネージャーを削除しても、登録済みのデバイスに影響はありません。
  ![個々 の登録マネージャーのページの表示中に選択されている登録アクセス許可 ボタンを削除します。](./media/enroll-mgrs-003-remove-enrollment-permissions.png)

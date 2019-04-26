---
title: 購入した VPP アプリを追加します。
titleSuffix: Intune for Education
description: Intune for Education に購入した VPP アプリを追加する方法について説明します。
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
ms.openlocfilehash: 69af75f14afb144bfed01919b1cba65d34a440f2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146615"
---
# <a name="add-vpp-purchased-ios-apps-to-intune"></a>Intune に VPP 購入した iOS アプリを追加します。

Intune for Education ポータルからの Volume Purchase Program (VPP) iOS アプリを追加します。 この記事では、Microsoft Intune に同期されている VPP 購入アプリを管理する方法について説明します。

無料と有料のアプリの両方でアプリ ストアからボリューム購入に利用できます。 無料の iOS アプリをインストールする*VPP トークンを使用せず*を参照してください方法[無料の iOS アプリを Intune に追加](add-apps-ios.md)します。  

## <a name="what-is-the-volume-purchase-program"></a>Volume Purchase Program とは何ですか。
Apple Volume Purchase Program では、組織一括にアプリのライセンスを購入し、モバイル デバイス manager (MDM) を管理することができます。 Intune for Education などの MDM でライセンスを管理し、し、生徒のデバイスを無線サイレント モードで導入することができます。 VPP/MDM パートナーシップは、学校や組織の多くのデバイスで同じアプリが必要な場所に最適です。 

## <a name="before-you-begin"></a>アンインストールの準備
表示し、Intune for Education ポータルからライセンスを管理、おく必要があります。  
* 構成、 [VPP トークン](setup-ios-device-management.md)します。
* Apple VPP の仕入先、または Apple School Manager を通じてアプリを購入 > アプリとブックのストア。
* 既存の転送は、適切な Intune VPP トークンにライセンスを購入します。 参照してください、 [Apple 教育のサポート サイト](https://support.apple.com/education)にライセンスを転送する方法について説明します。 

## <a name="search-and-add-apps"></a>検索し、アプリの追加
検索し、Intune for Education ポータルから、有料の iOS アプリを追加するには、次の手順を完了します。 

無料のアプリは、ポータルから直接購入可能にされます。 ただし、VPP アカウントを使用せずにユーザーが簡単に取得しているために、これらのアプリは提供されます。 無料のアプリをサイレント モードで、ボリュームで、学校のデバイスを展開する場合は、Apple VPP または Apple School Manager の web サイトを通じて購入する必要があります。

1. Intune for Education ポータルにサインインします。
2. **[アプリ]** をクリックします。
3. アプリの一覧から [ **iOS アプリ**、] をクリックして**新しいアプリ**します。
4. アプリを購入しているから国を選択します。
5. アプリの完全または部分的な名前を入力します。 Intune では、アプリ ストアから関連する結果の一覧を返します。 
6. アプリを選択します。 
7. Apple School Manager で、購入を完了するよう求めるメッセージが表示されます。 Apple School Manager に移動するリンクをクリックします。
8. 購入を完了する Apple School Manager での手順に従います。 適切な場所に、ライセンスを割り当てる求め。
9. Intune for Education 戻ります >**アプリ**します。 アプリが表示されます、 **iOS アプリ**一覧。 場合はすぐに表示されない、数分待ってから、ページを更新します。

### <a name="view-app-details"></a>アプリの詳細の表示
アプリをアプリの一覧に表示**iOS アプリ**します。 アプリの表示をクリックしてその。

* **概要**:アプリ名、パブリッシャー、および Intune に追加する日付を一覧表示します。 またを割り当てるには使用可能なライセンスの数を一覧表示します。
* **グループ**: アプリに割り当てられているすべてのグループを一覧表示します。 ここでのグループ割り当てを変更または特定のグループの詳細ページに移動します。
* **インストール状態**:割り当てられていたデバイスなどのアプリのインストールに関する詳細を示します。 状態は、最後のチェックイン時刻と、インストールが成功、失敗、または進行中の状態のかどうかにも一覧表示します。

## <a name="reassign-vpp-purchased-licenses"></a>購入した VPP ライセンスを再割り当てください。
Intune for Education から購入した VPP アプリを削除できません。 ただし、割り当て済みのグループからユーザーを削除または割り当てからグループ全体を削除できます。  


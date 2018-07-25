---
title: グループ設定とは
titleSuffix: Intune for Education
description: Intune で教育機関のポリシーの設定を管理する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU
ms.openlocfilehash: 998b207bdfc0f8d48cd7eddff3020d00673377a2
ms.sourcegitcommit: ecf53ed32308ea0f592788e19f8649801997cbdb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/24/2018
ms.locfileid: "39234382"
---
# <a name="what-are-group-settings"></a>グループ設定とは

学校での学生、教員、およびデバイスの動作を管理するグループの設定を構成します。

使用されるどのようなデバイスに関係なくユーザーに、ユーザーに割り当てる設定に従います。 同様に、設定、デバイスに割り当てることは、使用するユーザーに関係なく、デバイスに従います。

設定は、グループに適用されます。 グループの設定、別の上の 1 つのグループの階層としていずれかから[グループに適用する設定がすべてのサブグループによって継承されます](settings-inheritance.md)します。 継承によって、ユーザー、アプリ、およびデバイスの大きなグループに設定を適用しやすくします。  

Intune for Education グループの設定を管理する 2 つの方法はあります。  

* __高速構成__: 学校の最もよく使用される設定の選択範囲を構成します。 [高速構成](Express-configuration-intune-edu.md)に選択し、割り当てるグループの設定に役立つチュートリアル形式のセットアップが簡単にします。 設定は、Microsoft の推奨値に事前に構成が、学校のポリシーに合わせて変更することができます。 

* __グループ__: デバイスまたはユーザーのすべてのグループのすべての設定を構成します。 **グループ** タブで、ポータルで使用できる設定の完全な一覧が表示されます。 参照してください設定できるは[Windows](all-edu-settings-windows.md)および[iOS](all-edu-settings-ios.md)グループ。  

## <a name="configure-express-configuration-settings"></a>高速構成設定を構成します。  

高速構成ができる場合に使用されます。
* 始めたばかりで、ポータル。
* 使用してきたことの間と、簡単に変更します。   

高速構成手順の詳細については、次を参照してください。 [intune for Education の構成を Express](Express-configuration-intune-edu.md)します。

  ![高速の構成設定の修正プログラム](./media/express-config-006-choose-settings.png)  

## <a name="configure-settings-in-groups"></a>グループの設定を構成します。

次の手順から設定を割り当てる方法を説明する、**グループ**intune for Education のページ。 このページから、デバイスの制限と機能の完全な一覧が表示されます。  
1. 教育機関向けのダッシュ ボードは、Intune から次のようにクリックします。**グループ**します。
2. 構成するグループを選択します。
3. クリックして**設定**使用可能な設定の完全な一覧を表示します。
4. 選択したグループの個々 の設定を変更するには、各カテゴリを展開します。
5. 完了したら、クリックして**保存**します。 設定は、グループ内のすべてのデバイスで自動的に更新されます。  

## <a name="can-i-ever-have-settings-that-dont-work-together"></a>これまで一緒に動作しない設定ことはできますか。

互換性のない設定を同じグループに適用することができます。 これらの不整合はエラーを発生するときに、ユーザーまたはデバイスを設定している別の設定で複数の場所にします。 競合は、ユーザーまたはデバイスのメンバーは、複数のグループに属している場合に発生します。

などのメンバーである Esperanza、 *6 グレード*グループ化し、という名前のグループのメンバーであるも*地球科学*。 ホーム ページ設定を構成して割り当てる場合*6 グレード*、ホーム ページのさまざまな設定を構成し、それを割り当てると*地球科学*Esperanza が割り当てられている 2 つの競合しているホーム ページ設定を持つようになりましたさん。 一貫性のない設定の割り当ては、エラーにつながります。 これを解決するたいとグループを見て[設定エラー レポート](what-are-reports.md)します。  

## <a name="next-steps"></a>次の手順
[ユーザーとデバイス グループを作成する](what-are-groups.md)intune for Education の設定の構成を開始できるようにします。  

[アプリと Intune の完全な管理エクスペリエンスを使用してデータを保護する方法の詳細についてください。](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)

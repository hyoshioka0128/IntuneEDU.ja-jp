---
title: Autopilot リセットを使用して、Intune for Education でデバイスを再構成する
titleSuffix: Intune for Education
description: Intune for Education で自動再設定する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/17/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: ''
searchScope:
- IntuneEDU
ms.openlocfilehash: 23430e2902eeb5673f1915b1a9e547bdde1e17dd
ms.sourcegitcommit: 05576d32cac5cc3998ea579404ce84a2813c9083
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/09/2019
ms.locfileid: "68866716"
---
# <a name="autopilot-reset"></a>Autopilot のリセット
Autopilot リセットを使用して、個人のファイル、アプリ、設定をデバイスから削除できます。 デバイスは Intune に登録されたままになり、完全に構成された状態または既知の承認済みの状態に戻ります。
デバイスは、Intune for Education ポータルからローカルまたはリモートで再設定できます。  

Intune for Education ポータルを使用すると、IT スタッフが各デバイスにアクセスしてプロセスを開始する必要がなくなります。 ポータルから、1つのデバイスをリセットしたり、グループ内のすべてのデバイスに一括リセットを実行したりできます。 グループ内のすべてのデバイスをリセットすると、生徒のデバイスをすばやくワイプして再構成し、新しい school year 用に準備することができます。  

リセット後に、元の設定がデバイスに適用され、Intune と同期して最新のポリシーを取得します。 AutoPilot リセットがデバイスで使用されると、デバイスのプライマリ ユーザーが削除されます。 リセット後に初めてサインインしたユーザーがプライマリ ユーザーとして設定されます。   

## <a name="requirements"></a>必要条件
Autopilot リセットは、Windows 10 バージョン1709以降を実行しているデバイスでのみ使用できます。
AutoPilot リセットをリモートで使用することは、Windows 10 ビルド17672以降を実行しているデバイスでのみ使用できます。

## <a name="use-autopilot-reset-locally"></a>AutoPilot リセットをローカルで使用する
1つのデバイスをワイプする必要がある場合は、デバイス上で直接行うことができます。 デバイスで、CTRL + WIN + R キーを押します。 Ctrl + WIN + R キーを押した後、リセットをトリガーするために、管理者の資格情報で認証する必要があります。

## <a name="use-autopilot-reset-remotely-for-a-single-device"></a>1つのデバイスに対してAutoPilot リセットをリモートで使用する
1. Intune for Education で、 **[グループ]** を選択し > デバイスグループを選択します。
2. デバイス >**Autopilot リセット**を選択します。 リセットを確定するには、 **[Autopilot リセット]** を選択します。
2.  リセットが開始されると、メッセージが表示されます。 デバイスは、次にインターネットに接続したときにリセットされます。  

## <a name="use-autopilot-reset-remotely-for-devices-in-bulk"></a>デバイスを一括してAutopilot リセットを使用する  
1.  Intune for Education で、 **[グループ]** を選択し > グループを選択します。
2. **Autopilot すべてのデバイスをリセット** を選択します。
2. **[Autopilot リセットグループ]** ボックスに、現在のグループの名前を入力します。 次に、 **[Autopilot リセット]** を選択して確認します。
3.  各デバイスは、次回インターネットに接続するときにリセットされます。 いずれかのデバイスでリモート自動再設定のリセットがサポートされていない場合は、 **[デバイスをリセットできませんでした]** という名前のテーブルが表示されます。 表には、各デバイスと、リセットできなかった理由が一覧表示されます。  

## <a name="next-steps"></a>次の手順
[リモート操作によってデバイスを管理する](edu-device-remote-actions.md)




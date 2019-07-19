---
title: 自動操縦リセットを使用して、Intune for Education でデバイスを再構成する
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
ms.openlocfilehash: bfe0f385bdc66109fb189003e9a6cbaa894f1029
ms.sourcegitcommit: c85320170b0317de68be966581dd0e71d0cd58bd
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "68313991"
---
# <a name="autopilot-reset"></a>自動操縦リセット
自動設定のリセットを使用して、個人のファイル、アプリ、設定をデバイスから削除できます。 デバイスは Intune に登録されたままになり、完全に構成された状態または既知の承認済みの状態に戻ります。
デバイスは、Intune for Education ポータルからローカルまたはリモートで再設定できます。  

Intune for Education ポータルを使用すると、IT スタッフが各デバイスにアクセスしてプロセスを開始する必要がなくなります。 ポータルから、1つのデバイスをリセットしたり、グループ内のすべてのデバイスに一括リセットを実行したりできます。 グループ内のすべてのデバイスをリセットすると、生徒のデバイスをすばやくワイプして再構成し、新しい school year 用に準備することができます。  

リセット後に、元の設定がデバイスに適用され、Intune と同期して最新のポリシーを取得します。 デバイスで自動再設定のリセットを使用すると、デバイスのプライマリユーザーが削除されます。 リセット後にサインインする次のユーザーは、プライマリユーザーとして設定されます。   

## <a name="requirements"></a>必要条件
自動再設定のリセットは、Windows 10 バージョン1709以降を実行しているデバイスでのみ使用できます。
自動操縦リセットをリモートで使用することは、Windows 10 ビルド17672以降を実行しているデバイスでのみ使用できます。

## <a name="use-autopilot-reset-locally"></a>自動操縦リセットをローカルで使用する
1つのデバイスをワイプする必要がある場合は、デバイス上で直接行うことができます。 デバイスで、CTRL + WIN + R キーを押します。  

## <a name="use-autopilot-reset-remotely-for-a-single-device"></a>1つのデバイスに対して自動操縦リセットをリモートで使用する
1. Intune for Education で、 **[グループ]** を選択し > デバイスグループを選択します。
2. デバイス >**自動再設定のリセット**を選択します。 リセットを確定するには、 **[自動操縦リセット]** を選択します。
2.  リセットが開始されると、メッセージが表示されます。 デバイスは、次にインターネットに接続したときにリセットされます。  

## <a name="use-autopilot-reset-remotely-for-devices-in-bulk"></a>デバイスを一括して自動操縦リセットを使用する  
1.  Intune for Education で、 **[グループ]** を選択し > グループを選択します。
2. **自動再設定** すべてのデバイス を選択します。
2. **[自動操縦のリセットグループ]** ボックスに、現在のグループの名前を入力します。 次に、 **[自動再設定]** を選択して確認します。
3.  各デバイスは、次回インターネットに接続するときにリセットされます。 いずれかのデバイスでリモート自動再設定のリセットがサポートされていない場合は、 **[デバイスをリセットできませんでした]** という名前のテーブルが表示されます。 表には、各デバイスと、リセットできなかった理由が一覧表示されます。  

## <a name="next-steps"></a>次の手順
[リモート操作によってデバイスを管理する](edu-device-remote-actions.md)




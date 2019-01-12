---
title: Autopilot のリセットを使用して、デバイスを Intune for Education を再構成するには
titleSuffix: Intune for Education
description: 説明では、Intune for Education の Autopilot リセットする方法。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 12/3/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: ''
searchScope:
- IntuneEDU
ms.openlocfilehash: a10b16fb17da0353d0fe1011ec7de273dc3330e4
ms.sourcegitcommit: f229fdc217c384fffcf8809af4e252b0b50ad534
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/11/2018
ms.locfileid: "53197740"
---
# <a name="autopilot-reset"></a>Autopilot のリセット
Autopilot のリセットを使用する、デバイスから個人のファイル、アプリ、および設定を削除します。 デバイスは Intune で登録されたままし、完全に構成されているか、既知の IT 承認済み状態に戻ります。
Autopilot リセット デバイス ローカルまたはリモートからできます Intune for Education ポータル。
プロセスを開始する IT スタッフが各デバイスの必要性を避けるため、Intune for Education ポータルを使用します。 ポータルから、1 つのデバイスをリセットまたは一括操作を行います、グループ内のすべてのデバイスをリセットします。 グループ内のすべてのデバイスをリセットするには、すばやくワイプし、新しい学校年度の準備を行う生徒のデバイスを再構成することができます。
リセット後、元の設定は、デバイスに適用して、最新のポリシーを取得するために Intune と同期します。
## <a name="requirements"></a>必要条件
ローカル、Autopilot のリセットの使用は Windows 10 バージョン 1709 以降を実行しているデバイスはできるだけです。
Autopilot のリセットをリモートで使用が 17672 またはそれ以降、Windows 10 ビルドを実行しているデバイスをできるだけです。

## <a name="use-autopilot-reset-locally"></a>ローカルで、Autopilot のリセットの使用します。
1 つのデバイスをワイプする必要がある場合は、デバイス上で直接これ行うことができます。
デバイスで、CTRL + WIN+R キーを押します。
## <a name="use-autopilot-reset-remotely-for-a-single-device"></a>使用して Autopilot のリセット リモートで単一のデバイス
1.  Intune for Education には、次のように選択します。**グループ**> グループを選択 > デバイスを選択 > **Autopilot リセット**  > **Autopilot リセット**します。
2.  リセットが開始されたときに、通知が示されます。 次回にインターネットに接続するときに、デバイスがリセットされます。
## <a name="use-autopilot-reset-remotely-for-devices-in-bulk"></a>一括でデバイスをリモートでリセットの Autopilot を使用
1.  Intune for Education には、次のように選択します。**グループ**> グループを選択 > **Autopilot は、すべてのデバイスをリセット**します。
2.  **Autopilot リセット グループ**ボックス、テキスト ボックスに、グループの名前を入力し、 **Autopilot リセット**します。
3.  リモート Autopilot リセットどのデバイスでもサポートされていない場合、状態の一覧が表示されます。 インターネットに接続されている次回各デバイスがリセットされます。

## <a name="next-steps"></a>次の手順
[リモート操作によってデバイスを管理する](edu-device-remote-actions.md)



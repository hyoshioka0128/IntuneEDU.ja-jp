---
title: 教育用の Intune とは
titleSuffix: Intune for Education
description: Intune についての教育と iOS デバイスと教育環境で Windows デバイスを管理する方法について説明します。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/03/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c66e1700-aac0-44c0-af89-d5d9d4fac9ae
searchScope:
- IntuneEDU
ms.openlocfilehash: 6e85a1c80c3a74735b716dbaa553baa06bbe7f3f
ms.sourcegitcommit: 91d13ba57591077f560f5b33ce31e43f909abd09
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/30/2019
ms.locfileid: "55252550"
---
# <a name="what-is-intune-for-education"></a>教育用の Intune とは

Microsoft Intune for Education は、学校向けのクラウド ベースのモバイル デバイス管理 (MDM) サービスです。 により、教師と生徒のクラスルームのデバイスで生産性を維持し、セキュリティで保護された学校のデータを保持します。 

Intune for Education は、次のことができます。
* クラスルーム データにアクセスするデスクトップおよびモバイル デバイスの受講者の使用を管理します。
* 構成して、アプリを割り当てる、教室で受講者を使用します。
* 学生と教員にアクセスする方法を制御と教室の情報を共有します。
* 学校のセキュリティ要件をデバイスとアプリに適用されます。

Intune for Education ポータルが設定のみを含めるように設計および学校のデバイスの iOS および Windows を管理する必要があるワークフロー。 ポータルでは表示して、デバイス、ユーザー、およびアプリ インベントリに対してアクションを実行します。 Intune for Education には、教師が教室デバイスから直接、学生の進捗状況を評価することができるテスト アプリにとるもサポートしています。  

## <a name="sign-up-for-intune-for-education"></a>Intune for Education をサインアップします。
Intune for Education のアカウントにまだサインアップして場合、学習[開始方法](https://docs.microsoft.com/intune/account-sign-up)します。 記事では、システム管理者向けの学校、Intune サブスクリプションにサインアップする準備が整いました。 

## <a name="manually-add-users-to-you-intune-subscription"></a>Intune サブスクリプションにユーザーを手動で追加します。
必要な場合は、Microsoft School Data Sync (SDS) サービスを使用すると、学生と教職員のレコードをインポートしていない、 [Intune サブスクリプションにユーザーを手動で追加](https://docs.microsoft.com/intune/users-add)します。 学生と教員は、Azure portal または Office 365 ポータルを介して追加できます。 ユーザーのセットアップ時に、管理者のアクセス許可を付与するがもします。 

## <a name="supported-os-and-browsers"></a>サポートされている OS とブラウザー
完全な Intune 管理サービスには、多くのデバイスのオペレーティング システムがサポートしています。 自分のような学校設定教育機関向けの Intune の使用をお勧めします。 そのポータルの Windows 10 のサポート専用に設定し、iOS デバイスを学校します。  

Intune でサポートされている web ブラウザーとオペレーティング システムの完全な一覧を表示するのを参照してください。[サポートされるオペレーティング システムとブラウザー](https://docs.microsoft.com/intune/supported-devices-browsers)で Microsoft Intune のドキュメント。  

## <a name="configuring-your-intune-for-education-tenant"></a>Intune for Education のテナントを構成します。
*テナント*Intune for Education の組織のインスタンスを表します。 テナント レベルの設定では、組織の Intune サブスクリプションに影響します。 Intune for Education では、両方を持つ**全般**設定と**iOS デバイス管理**テナント設定します。 

### <a name="general-settings"></a>全般設定
**全般**テナント設定のページ要求の学校の IT の連絡先とリソースの情報。 この情報の大部分は省略可能ですが、学生と教員の連絡先の IT ポイントを提供すると便利です。  全般設定の編集に関する詳細については、次を参照してください。[全般設定を編集](edu-tenant-general-settings.md)します。 

### <a name="ios-device-management-settings"></a>iOS デバイス管理の設定  
**iOS デバイス管理**については、Apple アカウントの設定を要求します。 これらの設定は、Intune で iOS デバイスを管理する組織の要件です。 IOS のデバイス管理を構成するまでは、表示または Intune for Education ポータルでの iOS に関連する設定を管理できません。

デバイスの iOS デバイス管理の設定の設定に関する詳細については、次を参照してください。 [iOS デバイスの管理をセットアップ](setup-ios-device-management.md)します。

のみ[委任された管理者](group-admin-delegate.md)intune for Education を表示し、テナントの設定の変更は許可します。

## <a name="does-intune-for-education-work-on-shared-devices"></a>Intune for Education は、共有デバイスで動作しますか。  
Intune for Education では、共有デバイス、連携して、1 つのデバイスで複数のユーザーの管理をサポートします。 デバイスを共有した受講者は、別のアプリと設定の対象になるがあります。 受講者がデバイスにサインインするときにアプリケーションとそれらに割り当てられている設定のみ表示されます。  

## <a name="compatible-resources-and-tools"></a>互換性のあるリソースとツール

などの他の Microsoft 管理ツールへのアクセスがあります。
* Microsoft Intune、Azure portal で、[完全なデバイス、アプリ、およびユーザー管理エクスペリエンス](https://docs.microsoft.com/intune/understand-explore/introduction-to-microsoft-intune)
* Microsoft Azure Active Directory (Azure AD) [id およびアクセス管理システム](https://docs.microsoft.com/azure/active-directory/active-directory-administer)
* [Microsoft 学校データ同期](https://sds.microsoft.com)
* [Office 365 for Education](https://support.office.com/article/Get-started-with-Office-365-Education-AB02ABE5-A1EE-458C-B749-5B44416CCF14)

For Education と Intune を使用して[Microsoft Education](https://docs.microsoft.com/education/#pivot=itpro)などのツールします。

- [Office 365 for Education](https://support.office.com/article/Set-up-Office-365-for-business-6a3a29a0-e616-4713-99d1-15eda62d04fa)
- [教育機関向け Windows 10](https://docs.microsoft.com/education/windows)
- [教育機関向け Microsoft Store](https://docs.microsoft.com/microsoft-store/index?toc=/microsoft-store/education/toc.json)
- [Minecraft:教育機関向けエディション](https://docs.microsoft.com/education/windows/school-get-minecraft)

> [!VIDEO https://www.youtube.com/embed/ukrnCwcLvV8]

## <a name="get-started-with-intune-for-education"></a>Intune for Education を概要します。
Microsoft 学校データ同期の生徒レコードをインポートします。学校の Pc のアプリの設定で学校の Windows デバイスを構成またはへのサインイン[Intune for Education](https://intuneeducation.portal.azure.com) iOS デバイスの Apple の管理をセットアップします。

[ダッシュ ボード](how-do-i-customize-my-dashboard.md)、起動[高速構成](Express-configuration-intune-edu.md)します。 ユーザーまたはデバイス グループを選択します (学生など教師、または_2 階のコンピューター ラボ_) と、アプリと設定の割り当てを開始します。

![Intune for Education にログインして 1 回のランディング ページのスクリーン ショット。](./media/dashboard-001-landing-page.png)

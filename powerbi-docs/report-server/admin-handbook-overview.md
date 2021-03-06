---
title: 管理の概要、Power BI Report Server
description: この記事では、Power BI Report Server の管理の概要について説明します。Power BI Report Server は、Power BI レポート、モバイル レポート、およびページ分割されたレポートを格納および管理するためのオンプレミスの場所です。
author: maggiesMSFT
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-report-server
ms.topic: conceptual
ms.date: 05/22/2019
ms.author: maggies
ms.openlocfilehash: c670c78b03a1cd3fd6ce1ad3aeaa0003ce794eec
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2019
ms.locfileid: "66187351"
---
# <a name="admin-overview-power-bi-report-server"></a>管理の概要、Power BI Report Server
この記事では、Power BI Report Server の管理の概要について説明します。Power BI Report Server は、Power BI レポート、モバイル レポート、およびページ分割されたレポートを格納および管理するためのオンプレミスの場所です。 この記事では、Power BI Report Server の計画、展開、管理の概念について説明します。また、詳細情報へのリンクが用意されています。

![](media/admin-handbook-overview/admin-handbook.png)

## <a name="installing-and-migration"></a>インストールと移行
Power BI Report Server の使用を開始するには、インストールする必要があります。 このタスクの処理方法を説明する記事があります。

Power BI Report Server のインストール、アップグレードまたは移行を開始する前に、レポート サーバーの[システム要件](system-requirements.md)をご覧ください。

### <a name="installing"></a>インストール中
新しい Power BI レポート サーバーを展開する場合は、次のドキュメントが役立ちます。 

[Power BI レポート サーバーのインストール](install-report-server.md)

### <a name="migration"></a>移行
SQL Server Reporting Services のインプレース アップグレードはありません。 Power BI Report Server にする既存の SQL Server Reporting Services インスタンスがある場合は、それを移行する必要があります。 移行を実行する理由は他にもあります。 詳細については、移行のドキュメントを確認してください。

[レポート サーバー インストールの移行](migrate-report-server.md)

## <a name="configuring-your-report-server"></a>レポート サーバーを構成する
レポート サーバーを構成する際には、多数のオプションがあります。 SSL を使用するか、 電子メール サーバーを構成しているか、 Power BI サービスと統合して視覚化をピン留めするか、などです。

構成の大部分は、Report Server の構成マネージャー内で行われます。 詳細については、[構成マネージャー](https://docs.microsoft.com/sql/reporting-services/install-windows/reporting-services-configuration-manager-native-mode)のドキュメントで確認してください。

## <a name="security"></a>セキュリティ
セキュリティと保護は、すべての組織にとって重要です。 認証、承認、役割およびアクセス許可については、[セキュリティ](https://docs.microsoft.com/sql/reporting-services/security/reporting-services-security-and-protection)に関するドキュメントで学習することができます。

## <a name="next-steps"></a>次の手順
[Power BI レポート サーバーのインストール](install-report-server.md)  
[レポート サーバーのプロダクト キーを検索する](find-product-key.md)  
[Power BI レポート サーバー向けに最適化された Power BI Desktop のインストール](install-powerbi-desktop.md)  
[レポート ビルダーのダウンロード](https://www.microsoft.com/download/details.aspx?id=53613)  
[SQL Server Data Tools (SSDT) のダウンロード](http://go.microsoft.com/fwlink/?LinkID=616714)

他にわからないことがある場合は、 [Power BI コミュニティで質問してみてください](https://community.powerbi.com/)。


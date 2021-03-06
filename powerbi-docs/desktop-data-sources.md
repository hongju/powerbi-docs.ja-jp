---
title: Power BI Desktop のデータ ソース
description: Power BI Desktop のデータ ソース
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 05/15/2019
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: f045e9076cdd8552d6e35e72b9c5f6e2319add68
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2019
ms.locfileid: "65853456"
---
# <a name="data-sources-in-power-bi-desktop"></a>Power BI Desktop のデータ ソース
Power BI Desktop を使用すると、多種多様なソースからデータに接続できます。 使用できるデータ ソースの完全な一覧は、このページの下部にあります。

データに接続するには、 **[ホーム]** リボンの **[データの取得]** を選択します。 下向きの矢印を選択するか、ボタン上の **[データの取得]** テキストを選択すると、次の画像に示されているように **[最も一般的]** なデータ型が記載されたメニューが表示されます。

![Power BI Desktop でデータを取得する](media/desktop-data-sources/data-sources_01.png)

**[その他]** を **[最も一般的]** メニューから選択すると、 **[データの取得]** ウィンドウが表示されます。 **[データの取得]** ウィンドウを表示する場合 ( **[最も一般的]** メニューをバイパスします)、 **[データの取得]** **アイコン ボタン** を直接選択することもできます。

![[データの取得] ボタン](media/desktop-data-sources/data-sources_02.png)

> [!NOTE]
> Power BI チームは **Power BI Desktop** や **Power BI サービス**で利用できるデータ ソースを継続的に拡張しています。 そのため、*ベータ*や*プレビュー*などのマークが付いた、未完成の早期バージョンのデータ ソースが頻繁に公開されています。 データ ソースに*ベータ*や*プレビュー*などのマークが付いている場合、サポートや機能が限定されています。運用環境では利用しないでください。

## <a name="data-sources"></a>データ ソース
データ型は、次のカテゴリに分類されます。

* すべて
* ファイル
* データベース
* Power BI
* Azure
* オンライン サービス
* その他

**[すべて]** カテゴリには、すべてのカテゴリにあるすべてのデータ接続の種類が含まれます。

**[ファイル]** カテゴリには、次のデータ接続があります。

* Excel
* TEXT/CSV
* XML
* JSON
* フォルダー
* PDF
* SharePoint フォルダー

次の図は、 **[ファイル]** の **[データの取得]** ウィンドウを示しています。

![[データの取得] > [ファイル]](media/desktop-data-sources/data-sources_03.png)

**[データベース]** カテゴリには、次のデータ接続があります。

* SQL Server データベース
* Access データベース
* SQL Server Analysis Services
* Oracle データベース
* IBM DB2 データベース
* IBM Informix データベース (ベータ版)
* IBM Netezza
* MySQL データベース
* PostgreSQL データベース
* Sybase データベース
* Teradata データベース
* SAP HANA データベース
* SAP Business Warehouse Application サーバー
* SAP Business Warehouse メッセージ サーバー
* Amazon Redshift
* Impala
* Google BigQuery
* Vertica
* Snowflake
* Essbase
* AtScale キューブ (ベータ)
* BI コネクタ
* Dremio
* Exasol
* Indexima (ベータ)
* InterSystems IRIS (ベータ)
* Jethro (ベータ)
* Kyligence Enterprise (ベータ)
* MarkLogic (ベータ)

> [!NOTE]
> 一部のデータベース コネクタの場合、有効にするためには、 **[ファイル]、[オプションと設定]、[オプション]** の順に選択し、 **[プレビュー機能]** を選択し、コネクタを有効にする必要があります。 前途コネクタの一部が表示されず、その中に使用したいコネクタも含まれている場合は、 **[プレビュー機能]** を確認してください。 データ ソースに*ベータ*や*プレビュー*などのマークが付いている場合、サポートや機能が限定されていることにもご注意ください。運用環境では利用しないでください。

次の図は、 **[データベース]** の **[データの取得]** ウィンドウを示しています。

![[データの取得] > [データベース]](media/desktop-data-sources/data-sources_04.png)

**[Power BI]** カテゴリには、次のデータ接続があります。

* Power BI データ セット
* Power BI データフロー

次の図は、 **[Power BI]** の **[データの取得]** ウィンドウを示しています。

![[データの取得] > [Power BI]](media/desktop-data-sources/data-sources_05.png)

**[Azure]** カテゴリには、次のデータ接続があります。

* Azure SQL Database
* Azure SQL Data Warehouse
* Azure Analysis Services データベース
* Azure Blob Storage
* Azure Table Storage
* Azure Cosmos DB (ベータ版)
* Azure Data Lake Storage Gen1
* Azure HDInsight (HDFS)
* Azure HDInsight Spark
* HDInsight 対話型クエリ
* Azure のデータ エクスプ ローラー (Kusto)
* Azure Cost Management (ベータ)

次の図は、 **[Azure]** の **[データの取得]** ウィンドウを示しています。

![[データの取得] > [Azure]](media/desktop-data-sources/data-sources_06.png)

**[オンライン サービス]** カテゴリには、次のデータ接続があります。

* SharePoint Online リスト
* Microsoft Exchange Online
* Dynamics 365 (オンライン)
* Dynamics NAV
* Dynamics 365 Business Central
* Dynamics 365 Business Central (オンプレミス)
* アプリ用 Common Data Service (ベータ)
* Microsoft Azure Consumption Insights (ベータ)
* Azure DevOps (ベータ)
* Azure DevOps Server (ベータ)
* Salesforce オブジェクト
* Salesforce レポート
* Google アナリティクス
* Adobe Analytics
* appFigures (ベータ)
* Data.World - データセットの取得 (ベータ)
* Facebook
* GitHub (Beta)
* MailChimp (Beta)
* Marketo (Beta)
* Mixpanel (ベータ)
* Planview Enterprise One - PRM (ベータ)
* Planview Projectplace (ベータ)
* QuickBooks Online (ベータ)
* Smartsheet
* SparkPost (ベータ)
* Stripe (ベータ)
* SweetIQ (ベータ)
* Planview Enterprise One - CMT (ベータ)
* Twilio (ベータ)
* tyGraph (Beta)
* Webtrends (Beta)
* Zendesk (ベータ)
* Emigo Data Source (ベータ)
* IndustrialAppStore (ベータ)
* Microsoft Graph Security (ベータ)
* TeamDesk (Beta)

次の図は、 **[オンライン サービス]** の **[データの取得]** ウィンドウを示しています。

![[データの取得] > [オンライン サービス]](media/desktop-data-sources/data-sources_07.png)

**[その他]** カテゴリには、次のデータ接続があります。

* Web
* SharePoint リスト
* OData フィード
* Active Directory
* Microsoft Exchange
* Hadoop ファイル (HDFS)
* Spark
* R スクリプト
* Python スクリプト
* ODBC
* OLE DB
* BI360 の予算と財務レポート (ベータ)
* Denado
* Information Grid (ベータ)
* Paxata 
* QubolePresto (ベータ)
* Quick Base (ベータ)
* Roamler (ベータ)
* SurveyMonkey (ベータ)
* Tenforce (ベータ)
* Workforce Dimensions (ベータ)
* 空のクエリ

次の図は、 **[その他]** の **[データの取得]** ウィンドウを示しています。

![[データの取得] > [その他]](media/desktop-data-sources/data-sources_08.png)

> [!NOTE]
> 現時点では、Azure Active Directory を使用して保護されているカスタム データ ソースに接続することはできません。

## <a name="connecting-to-a-data-source"></a>データ ソースへの接続
データ ソースに接続するには、 **[データの取得]** ウィンドウでデータ ソースを選択し、 **[接続]** を選びます。 次の図の場合、 **[その他]** データ接続カテゴリで **[Web]** が選択されています。

![Web への接続](media/desktop-data-sources/data-sources_08.png)

対象のデータ接続に固有の接続ウィンドウが表示されます。 資格情報が必要な場合には、入力を求めるプロンプトが表示されます。 次の図には、Web データ ソースに接続するために URL を入力している様子が示されています。

![Web URL を入力する](media/desktop-data-sources/datasources_fromwebbox.png)

URL またはリソースの接続情報を入力したら、 **[OK]** を選択します。 Power BI Desktop はデータ ソースに接続し、 **[ナビゲーター]** に利用可能なデータ ソースが示されます。

![[ナビゲーター] 画面](media/desktop-data-sources/datasources_fromnavigatordialog.png)

**[ナビゲーター]** ウィンドウの下部にある **[読み込み]** ボタンを選択してデータを読み込むか、 **[編集]** ボタンを選択してクエリを編集してからデータを読み込みます。

これで、Power BI Desktop でデータ ソースに接続できます。 データ ソースの一覧は拡大を続けており、ここからデータへの接続をお試しください。一覧への追加は絶えず続いているため、頻繁にご確認ください。

## <a name="next-steps"></a>次の手順
Power BI Desktop を使用すると、さまざまなことを行えます。 そのような機能について詳しくは、次のリソースをご覧ください。

* [Power BI Desktop とは何ですか?](desktop-what-is-desktop.md)
* [Power BI Desktop でのクエリの概要](desktop-query-overview.md)
* [Power BI Desktop でのデータ型](desktop-data-types.md)
* [Power BI Desktop でのデータの整形と結合](desktop-shape-and-combine-data.md)
* [Power BI Desktop での一般的なクエリ タスク](desktop-common-query-tasks.md)    

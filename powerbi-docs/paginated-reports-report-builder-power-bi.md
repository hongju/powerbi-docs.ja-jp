---
title: Power BI Premium のページ分割されたレポートとは (プレビュー)
description: ページ分割されたレポート (SQL Server Reporting Services での標準レポート形式) を、Power BI サービスで使用できるようになりました。 これらのレポートは印刷または共有できます。 レポートのレイアウトを正確に制御できます。 たとえばテーブルが複数のページにまたがる場合でも、テーブルのすべてのデータが表示されます。
author: maggiesMSFT
ms.author: maggies
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: report-builder
ms.topic: overview
ms.date: 05/20/2019
ms.openlocfilehash: 8da24bb8f7d3b8d507dbb6792556004083b673fe
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2019
ms.locfileid: "65991066"
---
# <a name="what-are-paginated-reports-in-power-bi-premium-preview"></a>Power BI Premium のページ分割されたレポートとは (プレビュー)

ページ分割されたレポート (SQL Server Reporting Services での標準レポート形式) を、Power BI サービスで使用できるようになりました。 これらのレポートは印刷または共有できます。 これらは、1 ページにちょうど収まるように設定されているため "ページ分割された" と呼ばれます。 テーブルが複数のページにまたがる場合でも、テーブルのすべてのデータが表示されます。 レポート ページのレイアウトを厳密に制御できるため、"ピクセル単位で完璧" と呼ばれることもあります。 ページ分割されたレポートは、SQL Server Reporting Services の RDL レポート テクノロジに基づいています。 レポート ビルダーは、ページ分割されたレポートを作成するためのスタンドアロン ツールです。 

ページ分割されたレポートは、多くのページを含むことができます。 たとえば、このレポートは 563 ページです。 請求書ごとに 1 ページが使用されて、ヘッダーとフッターが繰り返されるように、各ページが正確にレイアウトされています。

![Power BI サービスにおけるページ分割されたレポート](media/paginated-reports-report-builder-power-bi/power-bi-paginated-wwi-report-page.png)

レポート ビルダーでレポートをプレビューした後、Power BI サービス (http://app.powerbi.com) に発行することができます。 サービスにレポートを発行するには、Power BI Pro ライセンスが必要です。 ワークスペースが Power BI Premium 容量に存在する限り、マイ ワークスペースまたはアプリ ワークスペースにページ分割されたレポートを発行して共有できます。 また、Power BI 管理者は、Power BI 管理ポータルでページ分割されたレポートを有効にする必要があります。 

## <a name="create-reports-in-power-bi-report-builder"></a>Power BI のレポート ビルダーでレポートを作成します。

改ページ調整されたレポートでは、独自のデザイン ツール、Power BI のレポート ビルダーがあります。 Power BI Report Server または SQL Server Reporting Services (SSRS) の改ページ調整されたレポートを作成する以前を使用したツールと同じ基盤を共有する新しいツールです。 実際、SSRS 2016 や 2017 または Power BI Report Server オンプレミス用に作成したページ分割されたレポートは、Power BI サービスと互換性があります。 Power BI サービスは下位互換性が維持されているので、レポートを上位バージョンに移行でき、以前のバージョンのページ分割されたレポートをアップグレードすることができます。 起動時は一部のレポート機能が利用できません。 詳細については、この記事の「[制限事項と考慮事項](#limitations-and-considerations)」を参照してください。
     
## <a name="report-from-a-variety-of-data-sources"></a>さまざまなデータ ソースからのレポート

1 つのページ分割されたレポートで、さまざまな異なるデータ ソースを使用できます。 Power BI レポートとは異なり、基になるデータ モデルはありません。 Power BI サービスでのページ分割されたレポートの初期リリースでは、レポート自体にデータ ソースとデータセットを埋め込みます。 現在のところ、共有データ ソースと共有データセットは使用できません。 ローカル コンピューター上のレポート ビルダーでレポートを作成します。 レポートでオンプレミスのデータに接続する場合は、レポートを Power BI サービスにアップロードした後、ゲートウェイを作成し、データ接続をリダイレクトする必要があります。 この時点に接続できるデータ ソースを次に示します。

- Azure SQL Database と Data Warehouse
- (SSO) を使用して azure Analysis Services
- ゲートウェイ経由の SQL Server
- ゲートウェイ経由の SQL Server Analysis Services
- Power BI Premium のデータセット
- Oracle
- Teradata
 
他のデータ ソースについては、プレビュー期間中に対応されます。

## <a name="design-your-report"></a>レポートをデザインする  

### <a name="create-paginated-reports-with-matrix-chart-and-free-form-layouts"></a>マトリックス、グラフ、および自由形式レイアウトでページ分割されたレポートを作成する

テーブル形式のレポートは、列ベースのデータで有効です。 クロス集計レポートやピボット テーブル レポートなどのマトリックス形式のレポートは、概要データに適しています。 グラフ形式のレポートはデータをグラフィカル形式で表示し、自由形式の "*リスト*" レポートは請求書などその他ほぼすべてのものを表示できます。 
  
いずれかのレポート ビルダー ウィザードを使用して始めることができます。 テーブル、マトリックス、およびグラフのウィザードでは、埋め込みデータ ソース接続と埋め込みデータセットを作成する手順が示されます。 その後、フィールドをドラッグ アンド ドロップしてデータセット クエリを作成し、レイアウトとスタイルを選択して、レポートをカスタマイズします。  
  
マップ ウィザードでは、地図や幾何図形を背景として集計データを表示するレポートを作成します。 マップ データには、Transact-SQL クエリまたは Environmental Systems Research Institute, Inc.(ESRI) シェープファイルの空間データを使用できます。 Microsoft Bing マップ タイルの背景を追加することもできます。  

### <a name="add-more-to-your-report"></a>レポートにさらに追加する

データのフィルター処理、グループ化、並べ替えを行って、または数式や式を追加して、データを変更します。 グラフ、ゲージ、スパークライン、インジケーターを追加して、データをビジュアル形式でまとめます。  パラメーターとフィルターを使用し、データをフィルター処理してビューをカスタマイズします。 外部コンテンツなど、画像や他のリソースを埋め込んだり参照したりします。  

レポート自体からすべてのテキスト ボックス、画像、テーブル、グラフまで、ページ分割されたレポート内のすべてのものには、レポートの外観を意図したとおりに設定できる一連のプロパティがあります。

## <a name="creating-a-report-definition"></a>レポート定義の作成

ページ分割されたレポートを設計するとき、実際には "*レポート定義*" を作成します。 それにデータは含まれません。 それでは、データを取得する場所、取得するデータ、データを表示する方法を指定します。 レポートを実行すると、指定したレポート定義がレポート プロセッサによって取得されて、データが取得され、レポートのレイアウトと組み合わせることでレポートが生成されます。 レポート定義は、Power BI サービス http://app.powerbi.com のマイ ワークスペースまたは同僚と共有しているワークスペースにアップロードします。 レポート データ ソースがオンプレミスにある場合は、レポートをアップロードした後、ゲートウェイを経由するようにデータ ソース接続をリダイレクトします。 

## <a name="view-your-paginated-report"></a>ページ分割されたレポートを表示する
ページ分割されたレポートは、ブラウザーの Power BI サービスまたは Power BI モバイル アプリで表示します。 Power BI サービスから、HTML、MHTML、PDF、XML、CSV、TIFF、Word、Excel など、さまざまな形式にレポートをエクスポートできます。 他のユーザーと共有することもできます。  

## <a name="create-a-subscription-to-your-report"></a>レポートへのサブスクリプションを作成します。

Power BI サービスでの改ページ調整されたレポートの自分や他のユーザーの電子メール サブスクリプションを設定することができますようになりました。 一般に、プロセスは、レポートと Power BI サービスでダッシュ ボードにサブスクライブすることと同じです。 メールの受信するどのくらいの頻度を選択するサブスクリプションを設定: 毎日、毎週、または 1 時間ごと。 サブスクリプションには、レポート全体の出力の PDF 添付ファイルが含まれています。

詳細については、この記事を参照してください。[自分や他のユーザーを Power BI サービスでの改ページ調整されたレポートにサブスクライブ](paginated-reports-subscriptions.md)します。 

## <a name="limitations-and-considerations"></a>制限事項と考慮事項

最初のリリースでは、次のような他のいくつかの機能がサポートされていません。

- レポート ページまたはビジュアルの Power BI ダッシュボードへのピン留め。 Power BI Report Server または Reporting Services のレポート サーバー上のオンプレミスのページ分割されたレポートから視覚エフェクトを Power BI ダッシュボードにピン留めすることは引き続き可能です。 詳しくは、[Reporting Services のアイテムの Power BI ダッシュボードへのピン留め](https://docs.microsoft.com/sql/reporting-services/pin-reporting-services-items-to-power-bi-dashboards)に関するページをご覧ください。
- ドキュメント マップや表示/非表示ボタンなどの対話機能。
- サブレポートとドリルスルー レポート。
- 共有データ ソースと共有データセット。
- Power BI レポートからのビジュアル。
 
## <a name="next-steps"></a>次の手順

- [Microsoft ダウンロード センターからの Power BI のレポート ビルダーをインストールします。](https://go.microsoft.com/fwlink/?linkid=2086513)
- [チュートリアル:ページ分割されたレポートを作成する](paginated-reports-quickstart-aw.md)
- [ページ分割されたレポートに直接データを入力する](paginated-reports-enter-data.md)

  


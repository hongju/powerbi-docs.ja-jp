---
title: Power BI サービスおよび Power BI Desktop でのレポートの視覚エフェクトの概要
description: Microsoft Power BI でのレポートの視覚エフェクト (ビジュアル) の概要
author: mihart
ms.author: mihart
manager: kvivek
ms.reviewer: ''
featuredvideoid: SYk_gWrtKvM
ms.service: powerbi
ms.subservice: powerbi-service
ms.topic: conceptual
ms.date: 05/28/2019
LocalizationGroup: Visualizations
ms.openlocfilehash: d470a262bd8a5e6590746fb07889b1230f5cfc25
ms.sourcegitcommit: 8bf2419b7cb4bf95fc975d07a329b78db5b19f81
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2019
ms.locfileid: "66375661"
---
# <a name="visualizations-in-power-bi-reports"></a>Power BI レポートでの視覚エフェクト

視覚エフェクト (ビジュアルとも呼ばれる) は、データ内で検出された洞察を表示します。 Power BI レポートは、ビジュアルが 1 つ使用された単一のページのこともあれば、ビジュアルが多数含まれる複数ページから成ることもあります。 Power BI サービスでは、ビジュアルを[レポートからダッシュボードにピン留め](../service-dashboard-pin-tile-from-report.md)することができます。

レポートを区別することが重要*デザイナー*とレポート*コンシューマー*構築または変更、レポートを担当しているかどうかは、デザイナーは。  デザイナーでは、レポートとその基になるデータセットの編集アクセス許可を持っています。 これは、Power BI Desktop では、データ ビューでデータセットを開き、レポート ビューでビジュアルを作成できることを意味し、 Power BI サービスで、つまり、レポート エディターで、データセットまたはレポートを開くことができます[編集ビュー](../consumer/end-user-reading-view.md)します。 自分がレポートまたはダッシュボードの[共有相手](../consumer/end-user-shared-with-me.md)である場合は、レポート **コンシューマー**となります。 レポートとそのビジュアルを表示して操作することができますが、主要な変更を保存することはできません。

さまざまな種類のビジュアルが Power BI の [視覚化] ウィンドウから直接使用できます。

![](media/power-bi-report-visualizations/power-bi-templates.png)

さらに多くの選択肢については、[Microsoft AppSource コミュニティ サイト](https://appsource.microsoft.com)にアクセスし、Microsoft およびコミュニティによって提供されている[カスタム ビジュアル](../developer/custom-visual-develop-tutorial.md)を見つけて[ダウンロード](https://appsource.microsoft.com/marketplace/apps?page=1&product=power-bi-visuals)してください。

<iframe width="560" height="315" src="https://www.youtube.com/embed/SYk_gWrtKvM?list=PL1N57mwBHtN0JFoKSR0n-tBkUJHeMP2cP" frameborder="0" allowfullscreen></iframe>


  Power BI を初めて使用する場合や、復習したい場合は、以下のリンクを使用して、Power BI 視覚エフェクトの基本を確認してください。  または、目次 (この記事の左側) を使用して役に立つ情報を見つけます。

## <a name="add-a-visualization-in-power-bi"></a>Power BI での視覚化の追加

レポートのページに[視覚エフェクトを作成](power-bi-report-add-visualizations-i.md)します。 [使用できる視覚エフェクトと使用できる視覚エフェクトのチュートリアルの一覧を参照](power-bi-visualization-types-for-reports-and-q-and-a.md)します。 

## <a name="upload-a-custom-visualization-and-use-it-in-power-bi"></a>カスタムの視覚化をアップロードして Power BI で使用する

自分で作成した、または [Microsoft AppSource コミュニティ サイト](https://appsource.microsoft.com/marketplace/apps?product=power-bi-visuals)で見つけたカスタムの視覚エフェクトを追加します。 自分でカスタマイズする場合は、 ソース コードを調べ、[開発者ツール](../developer/custom-visual-develop-tutorial.md)を使用して新しい視覚化の種類を作成して、[コミュニティと共有](../developer/office-store.md)してください。 カスタム ビジュアルの開発について詳しくは、「[Power BI カスタム ビジュアルを開発する](../developer/custom-visual-develop-tutorial.md)」をご覧ください。

## <a name="change-the-visualization-type"></a>視覚化の種類の変更

[視覚エフェクトの種類の変更](power-bi-report-change-visualization-type.md)を試して、そのデータに関して最も効果的な視覚エフェクトを確認します。

## <a name="pin-the-visualization"></a>視覚化のピン留め

Power BI サービスでは、希望する視覚エフェクトができたら、タイルとしてその[視覚エフェクトをダッシュボードにピン留め](../service-dashboard-pin-tile-from-report.md)します。 ピン留めした後、レポートで使用されている視覚エフェクトを変更しても、ダッシュボードのタイルは変更されません。つまり、レポート内の視覚エフェクトが折れ線グラフである場合、それをドーナツ グラフに変更しても、視覚エフェクトは折れ線グラフのままです。

## <a name="limitations-and-considerations"></a>制限事項と考慮事項
- データ ソースと、フィールド (メジャーまたは列) の数に応じてビジュアルを緩やかに変化読み込む可能性があります。  読みやすさとパフォーマンス上の理由 10 ~ 20 合計フィールドにビジュアルを制限することをお勧めします。 

- ビジュアルの上限は、100 のフィールド (メジャーまたは列) です。 ビジュアルに読み込みに失敗した場合は、フィールドの数を減らします。   

## <a name="next-steps"></a>次の手順

* [Power BI での視覚化の種類](power-bi-visualization-types-for-reports-and-q-and-a.md)
* [カスタム ビジュアル](../power-bi-custom-visuals.md)
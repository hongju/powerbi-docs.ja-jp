---
title: パート I、Power BI レポートへの視覚化の追加
description: パート I、Power BI レポートへの視覚化の追加
author: mihart
manager: kvivek
ms.reviewer: ''
featuredvideoid: IkJda4O7oGs
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 08/23/2018
ms.author: mihart
LocalizationGroup: Visualizations
ms.openlocfilehash: 52c0211aea0462e0bf79d7a48808f1f826c09fb6
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2019
ms.locfileid: "60978557"
---
# <a name="part-i-add-visualizations-to-a-power-bi-report"></a>パート I、Power BI レポートへの視覚化の追加
この記事では、Power BI サービスまたは Power BI Desktop を使用してレポートで視覚化を作成する方法を簡単に説明します。  より高度な内容を調べるには、「[パート II](power-bi-report-add-visualizations-ii.md)」をご覧ください。 Amanda がレポート キャンバスでのビジュアルの作成、編集、書式設定についてさまざまな方法を示します。 このデモの後に、[売上およびマーケティングのサンプル](../sample-datasets.md)を使用して、レポートを作成してみてください。

<iframe width="560" height="315" src="https://www.youtube.com/embed/IkJda4O7oGs" frameborder="0" allowfullscreen></iframe>


## <a name="open-a-report-and-add-a-new-page"></a>レポートを開き、新しいページを追加します。
1. [レポートを編集表示で](../consumer/end-user-reading-view.md)開きます。 このチュートリアルでは、[売上およびマーケティングのサンプル](../sample-datasets.md)を使います。
2. フィールド ウィンドウが表示されない場合は、矢印アイコンを選んで開きます。 
   
   ![](media/power-bi-report-add-visualizations-i/pbi_nancy_fieldsfiltersarrow.png)
3. 空のページをレポートに追加します。

## <a name="add-visualizations-to-the-report"></a>視覚化をレポートに追加する
1. 視覚化を作成するため、 **[フィールド]** ウィンドウでフィールドを選びます。  
   
   [SalesFact] > [Sales $] のように、**数値フィールドから始めます**。 Power BI によって、1 つの列のみが含まれた縦棒グラフが作成されます。
   
   ![](media/power-bi-report-add-visualizations-i/pbi_onecolchart.png)
   
   **カテゴリ フィールドから始める** ([Name] や [Product] など):Power BI によってテーブルが作成され、そのフィールドが **[値]** ウェルに追加されます。
   
   ![](media/power-bi-report-add-visualizations-i/pbi_agif_createchart3.gif)
   
   **もしくは、地理フィールドから始めます** ([Geo] > [City] など)。 Power BI と Bing 地図によって、マップの視覚化が作成されます。
   
   ![](media/power-bi-report-add-visualizations-i/power-bi-map.png)
2. 視覚化を作成し、その種類を変更します。 **[Product] > [Category]** および **[Product] > [Count of Product]** を選び、それらを **[値]** ウェルに追加します。
   
   ![](media/power-bi-report-add-visualizations-i/part1table1.png)
3. 視覚化を縦棒グラフに変更するため、縦棒グラフ アイコンを選びます。
   
   ![](media/power-bi-report-add-visualizations-i/part1converttocolumn.png)
4. レポート内に視覚化を作成するときには、[視覚化をダッシュボードにピン留め](../service-dashboard-pin-tile-from-report.md)します。 視覚化をピン留めするには、ピン アイコン ![](media/power-bi-report-add-visualizations-i/pinnooutline.png) を選びます。
   
   ![](media/power-bi-report-add-visualizations-i/part1pin1.png)
  

## <a name="next-steps"></a>次の手順
 「[パート 2:Power BI レポートへの視覚化の追加](power-bi-report-add-visualizations-ii.md)」に進む
   
   レポート内の[視覚化を操作する](../consumer/end-user-reading-view.md)
   
   [視覚化に対しその他の操作を実行する](power-bi-report-visualizations.md)
   
   [レポートを保存する](../service-report-save.md)

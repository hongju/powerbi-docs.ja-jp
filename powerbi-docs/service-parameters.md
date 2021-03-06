---
title: Power BI サービスのパラメーター設定を編集する
description: クエリ パラメーターは Power BI Desktop で作成されますが、Power BI サービスで確認および更新できます
author: maggiesMSFT
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-service
ms.topic: conceptual
ms.date: 11/21/2018
ms.author: maggies
LocalizationGroup: Create reports
ms.openlocfilehash: 8db6f106ecc2285cb66ff980bc72fa666456f81a
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2019
ms.locfileid: "61226028"
---
# <a name="edit-parameter-settings-in-the-power-bi-service"></a>Power BI サービスのパラメーター設定を編集する
レポートの作成者は Power BI Desktop でレポートにクエリ パラメーターを追加します。 パラメーターを使用すると、1 つまたは複数のパラメーターの*値*に基づいてレポートの各部分を作成できます。 たとえば、レポート作成者は、1 つの国または地域に対してデータを制限するパラメーターや日付、時刻、テキストなどのフィールドに使用できる形式を定義するパラメーターを作成できます。

![Desktop で [パラメーターの管理] オプションを表示している [ホーム] タブ](media/service-parameters/power-bi-manage-parameters.png)

## <a name="review-and-edit-parameters-in-power-bi-service"></a>Power BI サービスでパラメーターを確認および編集する

レポートの作成者は Desktop でパラメーターを定義します。 [そのレポートを Power BI サービスに発行する](desktop-upload-desktop-files.md)と、パラメーターの設定と選択も共に移動します。 一部のパラメーターは Power BI サービスで確認し、編集できます。利用できるデータを制限するパラメーターは編集できませんが、使用できる値を定義して表現するパラメーターは編集できます。

1. Power BI サービスで、![歯車アイコン](media/service-parameters/power-bi-cog.png) を選択して、 **[設定]** を開きます。

2. **[データセット]** のタブを選択して、リスト内のデータセットを強調表示します。 
    
    ![[データセット] タブが選択されている [設定] ウィンドウ](media/service-parameters/power-bi-select-dataset2.png)

3. **[パラメーター]** を展開します。  選択したデータセットにパラメーターがない場合、クエリ パラメーターに関する詳細へのリンクを含むメッセージが表示されます。 ただし、データセットにパラメーターが存在する場合は、 **[パラメーター]** 見出しを展開すると、そのパラメーターが表示されます。 

    ![[パラメーター] が展開されている [設定] ウィンドウ](media/service-parameters/power-bi-settings.png)

    必要に応じて、パラメーターの設定を確認し、変更します。 灰色表示のフィールドは編集できません。 


## <a name="next-steps"></a>次の手順
シンプルなパラメーターを追加する特別な方法として、[URL を変更します](service-url-filters.md)。
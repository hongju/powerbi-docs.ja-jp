---
title: Power BI API の機能
description: Power BI API の機能
author: rkarlin
ms.author: rkarlin
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-developer
ms.topic: conceptual
ms.date: 03/25/2019
ms.openlocfilehash: fd49c69a14d3dac6b1a045f6aba407ec7aac0deb
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2019
ms.locfileid: "61269449"
---
# <a name="what-can-developers-do-with-the-power-bi-api"></a>Power BI API の開発者向け機能

Power BI REST API を使用すると、Power BI レポート、ダッシュボード、およびタイルと統合されるアプリを作成できます。

Power BI REST API を使用すると、レポート、データセット、ワークスペースなどの Power BI オブジェクトで管理タスクを実行できます。

Power BI API を使って行うことのできる例は以下のとおりです。

| **詳細については** | **この情報を参照します。** |
|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| Power BI ユーザーと Power BI 以外のユーザーのためにレポート、ダッシュボード、タイルを埋め込む | [Power BI ダッシュ ボード、レポート、およびタイルを埋め込む方法 ](embedding-content.md) |
| Power BI オブジェクトで管理タスクを実行する | [Power BI REST API リファレンス](https://docs.microsoft.com/rest/api/power-bi/) |
| 既存のビジネス ワークフローを拡張して、主要なデータを Power BI ダッシュボードにプッシュします。 | [ダッシュ ボードにデータをプッシュします。 ](walkthrough-push-data.md) |
| Power BI に対して認証を行う | [Power BI への認証します。 ](get-azuread-access-token.md) |

> [!NOTE]
> Power BI API では引き続き、アプリ ワークスペースをグループと呼びます。 したがって、グループと記述されている場合はすべて、アプリ ワークスペースを使用していることを意味します。

## <a name="api-developer-tools"></a>API 開発者ツール

| ツール | 説明 |  |  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|---|---|
| [プレイ グラウンド ツール](https://microsoft.github.io/PowerBI-JavaScript/demo) | Power BI JavaScript API を使用した完全なサンプルを体験できます。 このツールを使うと、さまざまな種類の Power BI Embedded のサンプルを簡単に再生することもできます。 |  |  |
| [Power BI の JavaScript の wiki](https://github.com/Microsoft/powerbi-javascript/wiki) | Power BI JavaScript API の詳細情報が得られます。 |  |  |
| [Postman](https://www.getpostman.com/) | 要求の実行、テスト、デバッグ、監視、自動テストの実行などを行います。 |

## <a name="push-data-into-power-bi"></a>Power BI にデータをプッシュする

Power BI API を使って、[データセットにデータをプッシュ](walkthrough-push-data.md)できます。 この機能により、データセット内のテーブルに行を追加できます。 ダッシュボードのタイルやレポートのビジュアルに新しいデータが反映されます。

![サンプル データ をプッシュする](media/what-can-you-do/powerbi-push-data.png)

## <a name="github-repositories"></a>GitHub リポジトリ

* [Power BI の開発者向けサンプル](https://github.com/Microsoft/PowerBI-Developer-Samples)
* [.NET SDK](https://github.com/Microsoft/PowerBI-CSharp)
* [JavaScript API](https://github.com/Microsoft/PowerBI-JavaScript)

## <a name="next-steps"></a>次の手順

* [データセットにデータをプッシュする](walkthrough-push-data.md)
* [Power BI カスタム ビジュアルの開発](custom-visual-develop-tutorial.md)
* [Power BI REST API リファレンス](rest-api-reference.md)
* [Power BI REST API](https://docs.microsoft.com/rest/api/power-bi/)

他にわからないことがある場合は、 [Power BI コミュニティで質問してみてください](http://community.powerbi.com/)。

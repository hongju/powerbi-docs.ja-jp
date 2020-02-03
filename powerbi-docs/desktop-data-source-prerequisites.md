---
title: Power BI データ ソースの前提条件
description: Power BI データ ソースの前提条件
author: davidiseminger
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 01/29/2020
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: c3ccbe6ad87a813185943845431fa1a859b09a76
ms.sourcegitcommit: 8b300151b5c59bc66bfef1ca2ad08593d4d05d6a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/30/2020
ms.locfileid: "76888433"
---
# <a name="power-bi-data-source-prerequisites"></a>Power BI データ ソースの前提条件
Power BI は、データ プロバイダーごとにオブジェクトの特定のプロバイダーのバージョンをサポートしています。 Power BI で使用できるデータ ソースについて詳しくは、[データ ソース](desktop-data-sources.md)に関するページをご覧ください。 次の表では、これらの要件について説明します。

| データ ソースの | プロバイダー | 最小のプロバイダー バージョン | 最小のデータ ソース バージョン | サポートされているデータ ソース オブジェクト | ダウンロード リンク |
| --- | --- | --- | --- | --- | --- |
| SQL Server |ADO.net (.NET Framework に組み込み) |.NET Framework 3.5 (のみ) |SQL Server 2005 以降 |テーブル/ビュー、スカラー関数、テーブル関数 |.NET framework 3.5 以降に含まれる |
| アクセス |Microsoft Access データベース (ACE) |ACE 2010 SP1 |制限なし |テーブル/ビュー |[ダウンロード リンク](https://go.microsoft.com/fwlink/?linkid=285987&clcid=0x409) |
| Excel (.xls ファイルのみ) (注 1 を参照) |Microsoft Access データベース (ACE) |ACE 2010 SP1 |制限なし |テーブル、シート |[ダウンロード リンク](https://go.microsoft.com/fwlink/?linkid=285987&clcid=0x409) |
| Oracle (注 2 を参照) |ODP.NET |ODAC 11.2 リリース 5 (11.2.0.3.20) |9.x 以降 |テーブル/ビュー |[ダウンロード リンク](https://go.microsoft.com/fwlink/?linkid=272376&clcid=0x409) |
| | System.Data.OracleClient (.Net Framework に組み込み) |.NET Framework 3.5 |9.x 以降 |テーブル/ビュー |.NET Framework 3.5 以降に含まれる |
| IBM DB2 |IBM の ADO.Net クライアント (IBM データ サーバー ドライバー パッケージの一部) |10.1 |9.1+ |テーブル/ビュー |[ダウンロード リンク](https://go.microsoft.com/fwlink/?linkid=274911&clcid=0x409) |
| MySQL |コネクタ/Net |6.6.5 |5.1 |テーブル/ビュー、スカラー関数 |[ダウンロード リンク](https://go.microsoft.com/fwlink/?linkid=278885&clcid=0x409) |
| PostgreSQL |NPGSQL ADO.NET プロバイダー |2.0.12 |9.4 |テーブル/ビュー |[ダウンロード リンク](https://go.microsoft.com/fwlink/?linkid=282716&clcid=0x409) |
| Teradata |.NET Data Provider for Teradata |14+ |12+ |テーブル/ビュー |[ダウンロード リンク](https://go.microsoft.com/fwlink/?linkid=278886&clcid=0x409) |
| SAP Sybase SQL Anywhere |iAnywhere.Data.SQLAnywhere for .NET 3.5 |16+ |16+ |テーブル/ビュー |[ダウンロード リンク](https://go.microsoft.com/fwlink/?linkid=324846) |

>[!NOTE]
>.xlsx 拡張子を持つ Excel ファイルには、別個のプロバイダーのインストールは不要です。

>[!NOTE]
>Oracle プロバイダーでは、Oracle クライアント ソフトウェア (バージョン 8.1.7 以降) も必要です。
> 
> 


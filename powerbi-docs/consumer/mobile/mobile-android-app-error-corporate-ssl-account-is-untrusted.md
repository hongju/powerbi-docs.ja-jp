---
title: "\"お使いの企業 SSL 証明書が信頼されていません\" を修正する"
description: Power BI 用の Android アプリにサインインするとき、"お使いの企業 SSL 証明書が信頼されていないため、認証できませんでした" というメッセージが表示されることがあります
.": ''
author: mshenhav
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-mobile
ms.topic: conceptual
ms.date: 05/18/2018
ms.author: mshenhav
ms.openlocfilehash: de103412e21e0d26d20058e2d4e1fb9a8a5449bf
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2019
ms.locfileid: "61341353"
---
# <a name="fixing-corporate-ssl-certificate-is-untrusted---power-bi"></a>"企業 SSL 証明書が信頼されていません" を修正する
Microsoft Power BI 用の Android モバイル アプリにサインインするとき、"お使いの企業 SSL 証明書がこのデバイスによって信頼されていないため、認証できませんでした。 会社の IT 管理者にお問い合わせください。" というメッセージが表示されることがあります。 

このメッセージへの対処方法は、通常、Android デバイスのオペレーティング システムによって異なりますが、このエラーの原因になる可能性のある問題が他にも 2 つあります。

## <a name="on-android-7-or-later"></a>Android 7 以降
**Chrome** という名前のアプリの更新プログラムを探してインストールします。

## <a name="on-android-6-and-earlier"></a>Android 6 以前
デバイスの System Webview の更新バージョンが必要な場合があります。 既にデバイスにインストールされている可能性があり、その場合は **[更新]** をクリックする必要があるだけです。

System Webview がデバイスにインストールされていない場合:

1. Android デバイスで、Power BI を閉じます。
2. Google Play ストアを開き、Google Inc. の **System Webview** を検索します。
3. インストールします。
4. Power BI アプリを再起動し、サインインします。

## <a name="time-zone-settings"></a>タイム ゾーンの設定
デバイスのタイム ゾーンの設定が正しくない可能性があります。 

**[設定]**  >  **[システム]**  >  **[日付と時刻]** で確認します。

## <a name="custom-authentication-server"></a>カスタム認証サーバー
カスタム認証サーバーを使っている場合、会社の認証サーバーの SSL 証明書が有効ではない可能性があります。 ご自身の組織の IT と協力し、[こちらの記事](https://support.microsoft.com/en-us/help/3203929/using-adal-to-authenticate-from-android-devices-fails-if-additional-ce)のガイダンスに従って、会社の認証サーバーの構成をテストしてください。

## <a name="next-steps"></a>次の手順
* Android アプリ ストアから [Android アプリをダウンロード](http://go.microsoft.com/fwlink/?LinkID=544867)する。
* わからないことがある場合は、 [Power BI コミュニティで質問してみてください](http://community.powerbi.com/)。 


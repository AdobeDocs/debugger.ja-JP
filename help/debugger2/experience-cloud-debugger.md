---
description: Debugger は、Web ページを調べて、Experience Cloud ソリューションの実装方法に関する問題を見つけるのを支援します。
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Adobe Experience Cloud Debugger 2.0 Chrome および Firefox 拡張機能の技術ドキュメント - Web ページを調べて Experience Cloud ソリューションの実装の問題を理解します
seo-title: Adobe Experience Platform Debugger ChromeおよびFirefox Extension
title: Adobe Experience Platform Debugger Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: dc723f0848c56794e9a1a6eda405de2f4ea6b8fa

---


# （ベータ版）Adobe Experience Platform Debugger 2.0 {#adobe-experience-platform-debugger}

> [!IMPORTANT]
>
> Adobe Experience Cloud Debugger 2.0は現在ベータ版です。 ドキュメントと機能は変更される場合があります。

The [Adobe Experience Platform Debugger for Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adobe-experience-platform-dbg/) examines your web pages and helps you find problems with how your Experience Cloud solutions are implemented.

次のようなワークフロー用に、Adobe Experience Platform Debuggerを他のAdobeアクティベーションソリューションと共に使用します。

1. [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) または [DTM](https://docs.adobe.com/content/help/en/dtm/using/dtm-home.html) を使用して、ページ上で [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) ソリューションをアクティベートするコードを挿入します。

1. [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) を使用して実装をテストします。
1. Adobe Experience Platform Debuggerを使用して、Auditorで見つかった問題をデバッグしたり、実装に関する他の情報を調べたりします。

上記の手順は、この順番で実行する必要はありませんが、共通のプロセスです。

Web ページ上で Debugger を実行できますが、開いている Chrome タブのいずれかで Experience Cloud に認証されている場合のみ、拡張機能で非公開データを使用できます。

## 使用例 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Debugger を使用して、Experience Cloud ソリューションの実装方法を理解するのに役立つ情報を収集します。以下に例を示します。

* **起動：** ページにデプロイされるプロパティ、環境、ビルドを確認します。
* **Target：**&#x200B;どのアクティビティが適合し、どれが適合しないかとその理由を確認します。

---
description: Experience Platform Debugger は Web ページを調べて、Experience Cloud ソリューションの実装方法に関する問題を顧客が見つけられるよう支援します。
keywords: debugger;experience Platform Debugger extension;chrome;extension
seo-description: Adobe Experience Platform Debugger Chrome および Firefox 拡張機能の技術ドキュメント - Web ページを調べて Experience Cloud ソリューションの実装の問題を把握します
seo-title: Adobe Experience Platform Debugger Chrome および Firefox 拡張機能
title: Adobe Experience Platform Debugger 拡張機能
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 62%

---


# （ベータ版）Adobe Experience Platform Debugger {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger は現在ベータ版です。ドキュメントと機能は変更される場合があります。

[Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) および [](https://addons.mozilla.org/ja/firefox/addon/adobe-experience-platform-dbg/) Firefox用Adobe Experience Platformデバッガーは、Webページを調べて、Experience Cloudソリューションの実装方法に関する問題を見つけるのに役立ちます。

次のようなワークフロー用の他のAdobeアクティベーションソリューションと共に、Platform Debuggerを使用します。

1. [Launch](https://docs.adobe.com/content/help/ja-JP/launch/using/overview.html) または [DTM](https://docs.adobe.com/content/help/ja-JP/dtm/using/dtm-home.html) を使用して、ページ上で [Adobe Experience Cloud](https://docs.adobe.com/content/help/ja-JP/core-services/interface/experience-cloud.html) ソリューションをアクティベートするコードを挿入します。

1. Use [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/ja-JP/auditor/using/overview.html) to test your implementations.
1. Adobe Experience Platform Debugger を使用して、Auditor によって検出された問題をデバッグしたり、実装に関する他の情報を調べたりします。

上記の手順は、この順番で実行する必要はありませんが、共通のプロセスです。

Platform DebuggerはどのWebページでも実行できますが、パブリックでないデータは、開いているChromeのいずれかのタブでExperience Cloudに認証された場合にのみ、拡張で使用できます。

## 使用例 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Platform Debuggerを使用して、Experience Cloudソリューションの実装方法を理解するための情報を収集します。 以下に例を示します。

* **Adobe Experience Platform Launch:** ページにデプロイされるプロパティ、環境、ビルドを確認します。
* **Target：**&#x200B;どのアクティビティが適合し、どれが適合しないかとその理由を確認します。

## ビデオチュートリアル

>[!VIDEO](https://video.tv.adobe.com/v/32156?quality=12&learn=on)
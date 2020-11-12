---
description: Debugger は、Web ページを調べて、Experience Cloud ソリューションの実装方法に関する問題を見つけるのを支援します。
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Adobe Experience Cloud Debugger Chrome 拡張機能の技術ドキュメント - Web ページを調べて Experience Cloud ソリューションの実装の問題を理解します
seo-title: Adobe Experience Cloud Debugger Chrome 拡張機能
title: Adobe Experience Cloud Debugger 拡張機能
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 85%

---


# Adobe Experience Cloud Debugger 拡張機能 {#adobe-experience-cloud-debugger-extension}

[Chrome 用 Adobe Experience Cloud Debugger 拡張機能](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj)は Web ページを調べ、ユーザーが Experience Cloud ソリューションの実装方法に関する問題を見つけるのを支援します。

以下のようなワークフローに対して、他の Adobe Activation ソリューションと共に Adobe Experience Cloud Debugger 拡張機能を使用します。

1. [Adobe Experience Platform Launch](https://docs.adobe.com/content/help/ja-JP/launch/using/overview.html) または [DTM](https://docs.adobe.com/content/help/ja-JP/dtm/using/dtm-home.html) を使用して、ページ上の [Adobe Experience Cloud](https://docs.adobe.com/content/help/ja-JP/experience-cloud/user-guides/home.html) ソリューションをアクティブにするコードを挿入します。

1. Use [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/ja-JP/auditor/using/overview.html) to test your implementations.
1. Adobe Experience Cloud Debugger 拡張機能を使用して、Auditor によって検出された問題をデバッグしたり、実装に関する他の情報を調べたりします。

上記の手順は、この順番で実行する必要はありませんが、共通のプロセスです。

Web ページ上で Debugger を実行できますが、開いている Chrome タブのいずれかで Experience Cloud に認証されている場合のみ、拡張機能で非公開データを使用できます。

## 使用例 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Debugger を使用して、Experience Cloud ソリューションの実装方法を理解するのに役立つ情報を収集します。以下に例を示します。

* **プラットフォームの起動：** ページにデプロイされるプロパティ、環境、ビルドを確認します。
* **Target：**&#x200B;どのアクティビティが適合し、どれが適合しないかとその理由を確認します。

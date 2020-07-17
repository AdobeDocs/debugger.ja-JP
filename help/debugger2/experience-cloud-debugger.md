---
description: Debugger は、Web ページを調べて、Experience Cloud ソリューションの実装方法に関する問題を見つけるのを支援します。
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Adobe Experience Cloud Debugger 2.0 Chrome および Firefox 拡張機能の技術ドキュメント - Web ページを調べて Experience Cloud ソリューションの実装の問題を理解します
seo-title: Adobe Experience Platform Debugger Chrome および Firefox 拡張機能
title: Adobe Experience Platform Debugger 拡張機能
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: ht
source-git-commit: 64506a22964d68bfec84404b870c8432b0ff374c
workflow-type: ht
source-wordcount: '307'
ht-degree: 100%

---


# （ベータ版）Adobe Experience Platform Debugger 2.0 {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 は現在ベータ版です。ドキュメントと機能は変更される場合があります。

[Adobe Experience Platform Debugger 拡張機能（Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) および [Firefox](https://addons.mozilla.org/ja/firefox/addon/adobe-experience-platform-dbg/) 用）は、ユーザーが Web ページを調べ、Experience Cloud ソリューションの実装方法に関する問題を見つけられるよう支援します。

以下のようなワークフローに対して、他の Adobe Activation ソリューションと共に Adobe Experience Platform Debugger を使用します。

1. [Launch](https://docs.adobe.com/content/help/ja-JP/launch/using/overview.html) または [DTM](https://docs.adobe.com/content/help/ja-JP/dtm/using/dtm-home.html) を使用して、ページ上で [Adobe Experience Cloud](https://docs.adobe.com/content/help/ja-JP/core-services/interface/experience-cloud.html) ソリューションをアクティベートするコードを挿入します。

1. [Adobe Cloud Platform Auditor](https://docs.adobe.com/content/help/ja-JP/auditor/using/overview.html) を使用して実装をテストします。
1. Adobe Experience Platform Debugger を使用して、Auditor によって検出された問題をデバッグしたり、実装に関する他の情報を調べたりします。

上記の手順は、この順番で実行する必要はありませんが、共通のプロセスです。

Web ページ上で Debugger を実行できますが、開いている Chrome タブのいずれかで Experience Cloud に認証されている場合のみ、拡張機能で非公開データを使用できます。

## 使用例 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Debugger を使用して、Experience Cloud ソリューションの実装方法を理解するのに役立つ情報を収集します。以下に例を示します。

* **Launch：**&#x200B;ページにデプロイされるプロパティ、環境、ビルドを確認します。
* **Target：**&#x200B;どのアクティビティが適合し、どれが適合しないかとその理由を確認します。

## ビデオチュートリアル

>[!VIDEO](https://video.tv.adobe.com/v/32156?quality=12&learn=on&captions=jpn)
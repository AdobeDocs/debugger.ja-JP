---
description: Debugger は、Web ページを調べて、Experience Cloud ソリューションの実装方法に関する問題を見つけるのを支援します。
keywords: debugger;experience cloud debugger 拡張機能;chrome;拡張機能
seo-description: Technical documentation for the Adobe Experience Cloud Debugger Chrome Extension - examine your web pages and understand problems with your Experience Cloud solution mplementations
seo-title: Adobe Experience Cloud Debugger Chrome Extension
title: Adobe Experience Cloud Debugger 拡張機能
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
exl-id: 02d88172-3fb1-4111-a80d-e9d46df9ea1e
source-git-commit: 3b07bfe5764b46a2510b577df8978a35a753ab7b
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 84%

---

# Adobe Experience Cloud Debugger 拡張機能{#adobe-experience-cloud-debugger-extension}

>[!IMPORTANT]
>
>現在利用可能な Debugger の新しいバージョンがあります。 最新の機能について詳しくは、 [Adobe Experience Platform Debugger ドキュメント](../debugger2/experience-cloud-debugger.md).

[Chrome 用 Adobe Experience Cloud Debugger 拡張機能](https://chrome.google.com/webstore/detail/adobe-experience-platform/bfnnokhpnncpkdmbokanobigaccjkpob)は Web ページを調べ、ユーザーが Experience Cloud ソリューションの実装方法に関する問題を見つけるのを支援します。

以下のようなワークフローに対して、他の Adobe Activation ソリューションと共に Adobe Experience Cloud Debugger 拡張機能を使用します。

1. 用途 [タグ](https://experienceleague.adobe.com/docs/launch/using/home.html?lang=ja) 有効にするコードを挿入するには [Adobe Experience Cloud](https://experienceleague.adobe.com/docs/home.html) ソリューションを使用して、
1. Adobe Experience Platform Auditor を使用して実装をテストします。
1. Adobe Experience Cloud Debugger 拡張機能を使用して、Auditor によって検出された問題をデバッグしたり、実装に関する他の情報を調べたりします。

上記の手順は、この順番で実行する必要はありませんが、共通のプロセスです。

Web ページ上で Debugger を実行できますが、開いている Chrome タブのいずれかで Experience Cloud に認証されている場合のみ、拡張機能で非公開データを使用できます。

## ユースケース {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Debugger を使用して、Experience Cloud ソリューションの実装方法を理解するのに役立つ情報を収集します。以下に例を示します。

* **Platform Launch：**&#x200B;ページにデプロイされるプロパティ、環境、ビルドを確認します。
* **Target：**&#x200B;どのアクティビティが適合し、どれが適合しないかとその理由を確認します。

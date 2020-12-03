---
description: Experience Platform Debugger ネットワーク画面
keywords: debugger;experience Platform Debugger extension;chrome;extension;network;information
seo-description: Experience Platform Debugger ネットワーク画面
seo-title: ネットワーク情報
title: ネットワーク情報
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: tm+mt
source-git-commit: 53f027d5a5ae56c7a8e812b10a2649a38df3b31d
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 100%

---


# ネットワーク {#network}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger は現在ベータ版です。ドキュメントと機能は変更される場合があります。

ネットワーク情報を表示するには、**[!UICONTROL Network]** をクリックします。

ネットワーク画面は、ページでのすべての Adobe Experience Cloud ソリューション呼び出しを集計して、左から右の順に表示します。標準パラメーターは、わかりやすい名前で自動的にラベル付けされ、同じ役割の共通パラメーターにグループ化されて配置されます。

![](assets/network.jpg)

この画面は、複数のヒットをまたいでキーと値のペアを比較する場合に便利です。Experience Cloud 訪問者 ID や追加データ IDなど、統合に使用されたパラメーターが統合内で一貫していることを確認できます。

>[!NOTE]
>
>この時点では、ソリューション呼び出し（例えば、Analytics コンテキスト変数、Target カスタムパラメーター、Experience Cloud ID サービス顧客 ID）に渡されたすべてのパラメーターがネットワーク画面に表示されているわけではありません。

情報をソリューションで変更するには、左側のナビゲーションのリストから表示するソリューションを選択します。次の例は、Analytics のみを表示するようにフィルターされています。

![](assets/network-analytics.jpg)

すべてのソリューションの表示に戻るには、**[!UICONTROL Network]** をクリックします。

ネットワーク表示の項目をクリックすると、展開されて表示されます。展開された表示ウィンドウから、表示された情報をクリップボードにコピーできます。

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

リストを消去するには、**[!UICONTROL Remove Events]** をクリックします。

この画面に関する情報を含む Excel ファイルをダウンロードするには、**[!UICONTROL Download]** をクリックします。
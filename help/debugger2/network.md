---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;network;information
seo-description: 'null'
seo-title: ネットワーク情報
title: ネットワーク情報
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: ht
source-git-commit: 2c3d056451c5b7b4bf5603c22bf3bbdbc693491f

---


# ネットワーク情報 {#network-information}

ネットワーク情報を表示するには、**[!UICONTROL Network]** をクリックします。

ネットワーク画面は、ページでのすべての Adobe Experience Cloud ソリューション呼び出しを集計して、左から右の順に表示します。標準パラメーターは、わかりやすい名前で自動的にラベル付けされ、同じ役割の共通パラメーターにグループ化されて配置されます。

![](assets/network.jpg)

この画面は、複数のヒットをまたいでキーと値のペアを比較する場合に便利です。Experience Cloud 訪問者 ID や追加データ IDなど、統合に使用されたパラメーターが統合内で一貫していることを確認できます。

>[!NOTE]
>
>この時点では、ソリューション呼び出し（例えば、Analytics コンテキスト変数、Target カスタムパラメーター、Experience Cloud ID サービス顧客 ID）に渡されたすべてのパラメーターがネットワーク画面に表示されているわけではありません。

情報をソリューションでフィルターするには、左側のナビゲーションのリストから表示するソリューションを選択します。次の例は、Analytics のみを表示するようにフィルターされています。

![](assets/network-analytics.jpg)

すべてのソリューションの表示に戻るには、**[!UICONTROL Network]** をクリックします。

ネットワーク表示の項目をクリックすると、展開されて表示されます。展開された表示ウィンドウから、表示された情報をクリップボードにコピーできます。

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

リストを消去するには、**[!UICONTROL Remove Events]** をクリックします。

この画面に関する情報を含む Excel ファイルをダウンロードするには、**[!UICONTROL Download]** をクリックします。
---
description: Experience Cloud Debugger ツール画面
keywords: debugger;experience cloud debugger 拡張機能;chrome;拡張機能;ツール;dtm;target
seo-description: Experience Cloud Debugger Tools screen
seo-title: Tools
title: ツール
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
exl-id: ad108515-030f-4790-a29c-70f82e58a55d
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '396'
ht-degree: 100%

---

# ツール{#tools}

ツール画面では、インストールしたソリューション用の様々なツールを有効または無効にできます。例えば、Target のコンソールデバッグステートメントをオンにしたり、DTM ステージング用ライブラリを使用したりできます。これらのツールは、Target および DTM がページにインストールされている場合にのみ使用できます。

![](assets/tools.jpg)

任意のページで Adobe Experience Platform Launch または DTM を動的に挿入して、Platform Launch または DTM がインストールされていないページをテストできます。**[!UICONTROL Embed Code]** アイコンをクリックして、[埋め込みコード](https://docs.adobe.com/content/help/ja-JP/dtm/using/client-side/deployment.html)を入力し、**[!UICONTROL Save]** をクリックします。

![](assets/tools-embedcode.jpg)

## DTM 情報 {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> ツール </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> DTM コンソールログ </p> </td> 
   <td colname="col2"> <p>このツールは、DTM 特有のデバッグステートメントをブラウザーコンソールに表示します。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ステージング用ライブラリを使用 </p> </td> 
   <td colname="col2"> <p>このツールは、DTM デバッグ情報にステージング用ライブラリを使用します。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>DTM を無効にする </p> </td> 
   <td colname="col2"> <p>このツールは、DTM 情報がチェックされるのをブロックします。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> DTM を動的に挿入 </p> </td> 
   <td colname="col2"> <p> このツールは、ページに DTM コードを挿入します。埋め込みコードエディターを使用して、挿入されたコードを編集します。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## Target 情報 {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> ツール </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Target コンソール ログ </p> </td> 
   <td colname="col2"> <p>このツールは、<span class="codeph">mboxDebug=true</span> と呼ばれる cookie をブラウザーに追加することで、すべて <span class="codeph">AT:</span> プレフィックスで始まる、Target 特有のデバッグステートメントをブラウザーコンソールに表示します。この時点では、コンソールステートメントは Debugger ログ画面内に表示されませんが、ブラウザーのネイティブデバッグコンソール.に表示されます。 </p> <p> このツールには、at.js 0.9.6 以降が必要です。古いバージョンの at.js を使用している場合、コンソールログをオンにするための <span class="codeph">?mboxDebug=true</span> クエリ文字列パラメーターを URL に追加できます。mbox.js を使用している場合、<span class="codeph">?_AT_Debug=console</span> パラメーターを追加して、Visual Experience Composer アクティビティに制限されるコンソールログをオンにできます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox Traces を有効にする </p> </td> 
   <td colname="col2"> <p>このツールは、詳細情報を Target 応答に追加します。Debugger の <span class="uicontrol">Target／Mbox Trace</span> 画面に表示できます。 </p> <p> このツールを有効にするには、いずれかの Chrome タブでExperience Cloud にログインする必要があります。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target を無効にする </p> </td> 
   <td colname="col2"> <p>このツールは、<span class="codeph">mboxDisable=true</span> と呼ばれる cookie をブラウザーに追加することで、すべての Target リクエストを無効にします。 </p> <p> このツールには、at.js 0.9.6 以降が必要です。古いバージョンを使用している場合、mbox を無効にするための <span class="codeph">?mboxDisable=true</span>クエリ文字列パラメーターを URL に追加できます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> mbox ハイライト </p> </td> 
   <td colname="col2"> <p> このツールは、従来のラップスタイルの mbox の周囲に赤いボックスを描画します。 </p> </td> 
  </tr> 
 </tbody> 
</table>

以下のビデオでは、Debugger 拡張機能と Adobe Target の使用方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)

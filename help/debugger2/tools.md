---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: ツール
title: ツール
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: b9147536b8312599dd3144cac31dea9f0f1c3625

---


# ツール {#tools}

ツール画面では、インストールしたソリューション用の様々なツールを有効または無効にできます。例えば、Target のコンソールデバッグステートメントをオンにしたり、DTM ステージング用ライブラリを使用したりできます。これらのツールは、Target および DTM がページにインストールされている場合にのみ使用できます。

![](assets/tools.jpg)

任意のページで Launch または DTM を動的に挿入して、Launch または DTM がインストールされていないページをテストできます。Click the **[!UICONTROL Embed Code]** icon, then type your [embed code](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) and click **[!UICONTROL Save]**.

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

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=jpn)
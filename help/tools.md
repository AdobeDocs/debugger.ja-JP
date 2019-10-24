---
description: 'null'
keywords: デバッガー；Experience Cloud Debugger Extension;chrome;Extension；ツール；dtm;Target
seo-description: 'null'
seo-title: ツール
title: ツール
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# ツール{#tools}

ツール画面では、インストール済みのソリューションに対して様々なツールを有効または無効にできます。 例えば、Targetのコンソールデバッグステートメントを有効にしたり、DTMステージングライブラリを使用したりできます。 これらのツールは、TargetとDTMがページにインストールされている場合にのみ使用できます。

![](assets/tools.jpg)

LaunchまたはDTMがインストールされていないページでは、LaunchまたはDTMを動的に挿入して、何かをテストできます。 アイコンをク **[!UICONTROL Embed Code]** リックし、埋め込みコードを [入力して](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) 、をクリックしま **[!UICONTROL Save]**&#x200B;す。

![](assets/tools-embedcode.jpg)

## DTM情報 {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> ツール </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> DTMコンソールログ </p> </td> 
   <td colname="col2"> <p>このツールは、DTM固有のデバッグ文をブラウザーコンソールに公開します。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ステージング用ライブラリの使用 </p> </td> 
   <td colname="col2"> <p>このツールは、DTMデバッグ情報にステージング用ライブラリを使用します。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>DTMを無効にする </p> </td> 
   <td colname="col2"> <p>このツールは、DTM情報の確認をブロックします。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> DTMの動的挿入 </p> </td> 
   <td colname="col2"> <p> このツールは、ページにDTMコードを挿入します。 埋め込みコードエディターを使用して、挿入するコードを編集します。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## Target情報 {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> ツール </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>ターゲットコンソールログ </p> </td> 
   <td colname="col2"> <p><span class="codeph"> このツールは、 </span> ATから始まる、Target固有のデバッグ文をブラウザーコンソールに公開します。プレフィックスを使用して、 <span class="codeph"> mboxDebug=trueという名前のCookieをブラウザーに追加します</span> 。 現時点では、コンソール文は「デバッガログ」画面には表示されませんが、ブラウザのネイティブデバッグコンソールには表示されます。 </p> <p> このツールにはat.js 0.9.6以降が必要です。 古いバージョンのat.jsを使用している場合は、コンソールログを有効にするために <span class="codeph"> ?mboxDebug=true</span> query文字列パラメーターをURLに追加できます。 mbox.jsを使用している場合は、 <span class="codeph"> ?_AT_Debug=consoleパラメーターを追加して</span> 、Visual Experience Composerアクティビティに限定されたコンソールログを有効にできます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> mboxトレースの有効化 </p> </td> 
   <td colname="col2"> <p>このツールは、Targetの応答に詳細な情報を追加します。この情報は、デバッガ <span class="uicontrol"> ーのTarget</span> /Mboxトレース画面で確認できます。 </p> <p> このツールを有効にするには、ChromeのいずれかのタブでExperience cloudにログインしている必要があります。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ターゲットの無効化 </p> </td> 
   <td colname="col2"> <p>このツールは、 <span class="codeph"> mboxDisable=trueという名前のCookieをブラウザーに追加することで、すべてのTargetリクエストを無効にします</span> 。 </p> <p> このツールにはat.js 0.9.6以降が必要です。 古いバージョンを使用している場合は、URLに <span class="codeph"> ?mboxDisable=trueクエリ文字列パ </span>ラメーターを追加して、mboxを無効にできます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> mboxのハイライト </p> </td> 
   <td colname="col2"> <p> このツールは、ラッピングスタイルのレガシーmboxの周囲に赤いボックスを描画します。 </p> </td> 
  </tr> 
 </tbody> 
</table>

次のビデオでは、Adobe targetでデバッガー拡張機能を使用する方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=jpn)

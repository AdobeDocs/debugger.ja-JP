---
description: 'null'
keywords: デバッガー；Experience Cloud Debugger Extension;chrome;Extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;idサービス
seo-description: 'null'
seo-title: 概要画面
title: 概要画面
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 概要画面{#summary-screen}

Experience cloudデバッガーを実行するには、拡張機能バーの拡張機能アイコンをクリックし、Chromeで確認するページを開きます。

![](assets/start-icon.jpg)

Adobe Experience cloudデバッガーの概要画面が表示されます。

![](assets/summary.jpg)

この画面には、ページのサムネールと、ページのURLおよびタイトルが表示されます。 また、各Adobe Experience cloudソリューションに関する情報も表示されます。 表示される情報はソリューションによって異なりますが、通常、ソリューションライブラリとバージョン（「AppMeasurement v2.9」など）、アカウント識別子（AnalyticsレポートスイートID、Targetクライアントコード、Audience ManagerパートナーIDなど）などの情報が含まれます。

ウィンドウ上部のタブの横に表示される青色の数字は、行われたサーバーコールの数を示します。 これらをゼロにリセットするには、各タブ内 **[!UICONTROL Clear All Requests]** をクリックします。

例えば、次の図はAdobe targetに関する情報を示しています。 以下に示すアクティビティの詳細を認証なしで公開するには、コードマネージャーまたはタグマネージャーにデバッグイベントリスナーを実装し、Target UIで必要な応答トークンを [有効にする](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) 必要があります。

![](assets/summary-target2.jpg)

## Auditorでの監査の実行 {#section-82bc57440406461ebf27a16855b71655}

Adobe Auditorを使用して、ページに対して一連の監査を実行できます。 Auditorを実行するには、上部のメニ **[!UICONTROL Auditor]** ューでをクリックし、をクリックしま **[!UICONTROL Audit Page Now]**&#x200B;す。 Adobe Auditorを開くには、をクリックしま **[!UICONTROL Run Multi-Page Audit Now]**&#x200B;す。

## デバッガーに表示される情報 {#section-88a95ba53dca43d9b96a585e75e5f5cf}

デバッガーには、各ソリューションに関する次の情報が表示されます。

**ページ情報**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>ページのスクリーンショット </p> </td> 
   <td colname="col2"> <p>ページのサムネール </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>ページのURL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Title </p> </td> 
   <td colname="col2"> <p>&lt;TITLE&gt;タグで指 <span class="codeph"> 定した名前</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>レポートスイート </p> </td> 
   <td colname="col2"> <p>A <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external"> report suite</a> defines the complete, independent reporting on a chosen website, set of websites, or subset of web pages </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>バージョン </p> </td> 
   <td colname="col2"> <p>ページに <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> 対して定義されているAppMeasurement</a> バージョン </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>訪問者のバージョン </p> </td> 
   <td colname="col2"> <p>訪問者IDライブラリ <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> のバージョン</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ページ名 </p> </td> 
   <td colname="col2"> <p>Analyticsに送 <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> 信され</a> 、サイトのわかりやすい名前を含むpageName変数。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>モジュール </p> </td> 
   <td colname="col2"> <p>Adobe Analyticsによって読み込まれるモジュール </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>パートナー </p> </td> 
   <td colname="col2"> <p>DILイン <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> スタンスの</a> 、パートナー名 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>バージョン </p> </td> 
   <td colname="col2"> <p>DILインスタンス<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> のバージョン</a> 番号です。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>DILイン <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> スタンスに関連付けられ</a> 、一意のユーザーID </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>名前 </p> </td> 
   <td colname="col2"> <p>Adobe Launchプロパティの名 <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> 前</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>バージョン </p> </td> 
   <td colname="col2"> <p>タービンのバージ <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> ョン</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ビルド日 </p> </td> 
   <td colname="col2"> <p>Launch <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> library</a> build date </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>環境 </p> </td> 
   <td colname="col2"> <p>起動ラ <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> イブラリ</a> で使用される環境 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>スクリプトディレクトリ </p> </td> 
   <td colname="col2"> <p>起動スクリプトが保存されるディレクトリ </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>ライブラリ名 </p> </td> 
   <td colname="col2"> <p>Adobe DTMライブラリの名前<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> 。</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>バージョン </p> </td> 
   <td colname="col2"> <p>タービンのバージョン </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ビルド日 </p> </td> 
   <td colname="col2"> <p>Launch <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> library</a> build date </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>環境 </p> </td> 
   <td colname="col2"> <p>DTMライブラリで使用される環境 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>スクリプトディレクトリ </p> </td> 
   <td colname="col2"> <p>DTMスクリプトが保存されるディレクトリ </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID サービス**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience cloud組織ID </p> </td> 
   <td colname="col2"> <p>Your <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organization ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>バージョン </p> </td> 
   <td colname="col2"> <p>訪問者IDライブラリのバージョン<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> (The version</a> of the visitor ID library) </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Client Code </p> </td> 
   <td colname="col2"> <p>Your Target <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Client Code </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>バージョン </p> </td> 
   <td colname="col2"> <p>現在の <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> またはmbox.jsバージョン </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Global Mbox Name </p> </td> 
   <td colname="col2"> <p>グローバル<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mboxは</a> 、Target実装の各Webページの最上部で行われる単一のサーバー呼び出しを指します </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>mbox 名 </p> </td> 
   <td colname="col2"> <p>ページ上の場所の周囲のmbox <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> の</a> 名前。 コードまたはタグマネージャーにデバッグイベントリスナーを実装し、Target UIで必要な応答トークンを有効にした場合にの <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> み</a> 、認証なしで使用できます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>アクティビティ名 </p> </td> 
   <td colname="col2"> <p>Targetのキャンペーンまたはア <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> クティビティの名前</a>。 コードまたはタグマネージャーにデバッグイベントリスナーを実装し、Target UIで必要な応答トークンを有効にした場合にの <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> み</a> 、認証なしで使用できます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>アクティビティID </p> </td> 
   <td colname="col2"> <p>TargetアクティビティのID。 コードまたはタグマネージャーにデバッグイベントリスナーを実装し、Target UIで必要な応答トークンを有効にした場合にの <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> み</a> 、認証なしで使用できます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>レシピ名 </p> </td> 
   <td colname="col2"> <p>Targetエクスペリエンスの <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> 名前</a>。 コードまたはタグマネージャーにデバッグイベントリスナーを実装し、Target UIで必要な応答トークンを有効にした場合にの <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> み</a> 、認証なしで使用できます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>レシピ ID </p> </td> 
   <td colname="col2"> <p>TargetレシピのID。 コードまたはタグマネージャーにデバッグイベントリスナーを実装し、Target UIで必要な応答トークンを有効にした場合にの <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> み</a> 、認証なしで使用できます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>オファー </p> </td> 
   <td colname="col2"> <p>Targetオファーの名 <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> 前</a>。 コードまたはタグマネージャーにデバッグイベントリスナーを実装し、Target UIで必要な応答トークンを有効にした場合にの <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> み</a> 、認証なしで使用できます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>オファー ID </p> </td> 
   <td colname="col2"> <p>TargetオファーのID。 コードまたはタグマネージャーにデバッグイベントリスナーを実装し、Target UIで必要な応答トークンを有効にした場合にの <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> み</a> 、認証なしで使用できます。 </p> </td> 
  </tr> 
 </tbody> 
</table>


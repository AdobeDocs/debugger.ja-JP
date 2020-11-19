---
description: Experience Cloud Debugger のリリースノート
keywords: debugger;experience cloud debugger extension;chrome;extension;release notes
seo-description: Experience Cloud Debugger のリリースノート
seo-title: リリースノート
title: リリースノート
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: ht
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: ht
source-wordcount: '723'
ht-degree: 100%

---


# リリースノート {#release-notes}

## リリースノート {#topic-a92c3eb799b74e7fa404af8af5efb215}

## バージョン 0.0.817 2019 年 5 月 17 日 {#topic-5dc9026cac864330b04361b1da8309a8}

## 新機能 {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 機能 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>ヒットデータの後処理 </p> </td> 
   <td colname="col2"> <p> <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local">処理ルールを実行した後に Analytics ヒットの値を表示</a>する機能を追加しました。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## バージョン 0.0.810 2019 年 3 月 6 日 {#topic-83bb7ddd68594177be9fd7826b650b80}

## 新機能 {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 機能 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Adobe Experience Platform Auditor のテスト </p> </td> 
   <td colname="col2"> <p> <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local">Platform Auditor のテスト</a>を Experience Cloud Debugger に追加しました </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Experience Cloud Debugger に AAM 応答が表示されるようになりました </p> </td> 
  </tr> 
 </tbody> 
</table>

## バグの修正 {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* フッターがページの下部にあるコンテンツを隠していた問題を修正しました。

* Experience Cloud Debugger のフッターを更新しました。
* 古い用語が Target で使用されていた問題を修正しました。

## バージョン 0.0.809 2019 年 2 月 28 日 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## 新機能 {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 機能 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>埋め込みコード機能 </p> </td> 
   <td colname="col2"> <p> 埋め込みコード機能を分割、置換および挿入しました。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 機能強化 {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* 不要部分が削除されていないユーザー入力による潜在的な脆弱性の問題を修正しました。

## バグの修正 {#section-556417ff055848c1bf037354dd43cbd0}

* AAM タブで AAM DIL イベントがキャプチャされなかった問題を修正しました。

* Launch を動的に挿入で、間違ったタイミングで別の埋め込みコードにマッピングするためのユーザーインターフェイスが表示されていた問題を修正しました。
* Launch を動的に挿入で間違った URL が表示され続けていた問題を修正しました。
* Experience Cloud Debugger ウィンドウが閉じていても、Experience Cloud Debugger が埋め込みコードの置き換えを続けていた問題を修正しました。

## バージョン 0.0.806 2018 年 9 月 10 日 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## 新機能 {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 機能 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>「ツール」タブの Analytics リンク </p> </td> 
   <td colname="col2"> <p>IMS ログインによる Analytics API の eVars／props のわかりやすい名前を表示します。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Launch を動的に挿入 </p> </td> 
   <td colname="col2"> <p>「ツール」タブから、任意のページで Adobe Experience Platform Launch を動的に挿入して、Platform Launch がインストールされていないページをテストできます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target の機能強化 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Target リクエストのパフォーマンスタイミングを追加しました。 </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">adobe.target.trackEvent をキャプチャします。 </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 機能強化 {#section-56003a12c32f4998bf1cf2a25a518592}

* 「ネットワーク」タブの表示が強化され、表が縦に長すぎて、縦にスクロールしないと横にスクロールできないということがなくなりました。以前は、スクロールバーが表の下に表示されていました。表が非常に大きくなる可能性があるので、スクロールバーを表示するためにユーザーは一番下までスクロールする必要がありました。
* 「ツール」タブの ObservePoint へのリンクを更新しました。

## バグの修正 {#section-d9231f5c77254d0888347e5f569a8b1d}

* 「Experience Cloud」タブが更新されていなかった問題を修正しました。

* 「ネットワーク」タブのソリューション行に、現在の「Advertising Cloud」ではなく、「Media Manager」が表示されていた問題を修正しました。
* Experience Cloud Debugger によって各ページに _satellite が挿入されていた問題を修正しました。

## バージョン 0.0.803 2018 年 8 月 10 日 {#topic-d2901fb70ce04a5586f6c7a994fce875}

バージョン 0.0.803 にお客様向けの変更は含まれていません。

## バージョン 0.0.802 2018 年 8 月 1 日 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## 新機能 {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 機能 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>「ツール」タブの Platform Auditor リンク </p> </td> 
   <td colname="col2"> <p>Experience Cloud Debugger から Platform Auditor へのリンクを追加しました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>折りたたまれたタブ </p> </td> 
   <td colname="col2"> <p>「サマリ」および「ツール」タブで折りたたまれたタブが保持されます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>クリックして表示 </p> </td> 
   <td colname="col2"> <p> クリックして表示機能がすべてのタブに追加されました。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 機能強化 {#section-0e7090e3e6a645f085d4553b983ecff8}

* Media Manager の名前を Advertising Cloud に変更しました。
* ソリューションが見つからない場合に、「ネットワーク」タブからソリューションを削除しました。

## バグの修正 {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* 「セルをクリックして表示」機能が更新されていなかった問題を修正しました。
* AAM ヒットが「AAM」タブに表示されていなかった問題を修正しました。

## バージョン 0.0.798 2018 年 6 月 14 日 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## 新機能 {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 機能 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Excel 書き出しオプション </p> </td> 
   <td colname="col2"> <p>「ネットワーク」タブに Excel 書き出しオプションを追加しました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>外観の強化 </p> </td> 
   <td colname="col2"> <p>Chrome 拡張機能のフォントを Adobe Clean に更新しました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> トラックパッドスワイプ機能 </p> </td> 
   <td colname="col2"> <p>進む／戻るのトラックパッドスワイプ機能を無効にしました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>生のサーバー呼び出しインジケーター </p> </td> 
   <td colname="col2"> <p>生のサーバー呼び出し文字列がコピーされたインジケーターが追加されました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>「ログをクリーンアップ」タブ </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">ログにそのソリューションの行項目が見つからない場合に、ソリューションフィルターのソリューションを非表示にします。 </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">DTM 呼び出しが見つからない場合に、レベルフィルターを非表示にします（DTM にのみ適用されるので）。 </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">クリックしても何も起こらない場合にクリックできるように見えないように、レベル列に表示されるアイコンを変更します。 </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">DTM 行項目の「コードを表示」の書式を標準化します。 </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>フッターのヘルプリンクの更新 </p> </td> 
   <td colname="col2"> <p>フッターのヘルプリンクを <a href="https://docs.adobe.com/content/help/ja-JP/debugger/using/experience-cloud-debugger.html" format="https" scope="external">https://docs.adobe.com/content/help/ja-JP/debugger/using/experience-cloud-debugger.html</a> に更新しました。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## バグの修正 {#section-c292cf7dcb17463bb1928de73bd55121}

* バッジ番号が明確でなかった問題を修正しました。
* お客様がレポートしていた空のサマリの詳細の問題を修正しました。

## バージョン 0.0.797 2018 年 5 月 25 日 {#topic-51490f4f42aa40eb879663fad9d62916}

## 新機能 {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 機能 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>mbox トグル </p> </td> 
   <td colname="col2"> <p>「Target」タブに mbox トグルが追加されました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>フィルター設定が固定可能に </p> </td> 
   <td colname="col2"> <p>フィルター設定が「ネットワーク」および「ログ」タブの画面の上部に固定できるようになりました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ネットワーク値の表示とコピー </p> </td> 
   <td colname="col2"> <p>「ネットワーク」タブで任意のセルの値の詳細を表示したりコピーしたりできます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>法的事項のフッターリンクと著作権 </p> </td> 
   <td colname="col2"> <p>ユーザーインターフェイスに法的事項のフッターリンクと著作権情報を追加しました。 </p> </td> 
  </tr> 
 </tbody> 
</table>


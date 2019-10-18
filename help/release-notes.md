---
description: 'null'
keywords: デバッガー；Experience Cloud Debugger Extension;chrome;Extension；リリースノート
seo-description: 'null'
seo-title: リリースノート
title: リリースノート
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# リリースノート {#release-notes}

## リリースノート {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 May 17, 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

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
   <td colname="col1"> <p>後処理のヒットデータ </p> </td> 
   <td colname="col2"> <p> 処理ルールの実行後にAnalytics <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> ヒットの値を表示する機能が追加されました</a>。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## バージョン0.0.810、2019年3月6日 {#topic-83bb7ddd68594177be9fd7826b650b80}

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
   <td colname="col1"> <p>監査テスト </p> </td> 
   <td colname="col2"> <p> デバッガ <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> ーにAuditorテスト</a> を追加しました </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>デバッガーにAAM応答が表示されるようになりました </p> </td> 
  </tr> 
 </tbody> 
</table>

## バグの修正 {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* フッターでページの下部にコンテンツが表示されない問題を修正しました

* デバッガーフッターを更新しました
* Targetで古い用語が使用される問題を修正しました

## バージョン0.0.809、2019年2月28日 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

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
   <td colname="col1"> <p>埋め込みコード関数 </p> </td> 
   <td colname="col2"> <p> ディバイド置換および埋め込みコード関数の挿入 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 機能強化 {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* 非サニスト化されたユーザー入力に起因する潜在的な脆弱性を修正しました。

## バグの修正 {#section-556417ff055848c1bf037354dd43cbd0}

* AAM DILイベントが「AAM」タブでキャプチャされない問題を修正しました

* 動的挿入の開始で、ユーザーインターフェイスが別の埋め込みコードにマッピングされていない場合に表示される問題を修正しました
* 動的挿入の開始で、不正なURLが引き続き表示される問題を修正しました
* デバッガーウィンドウが閉じても、デバッガーが埋め込みコードを置き換え続ける問題を修正しました

## バージョン0.0.806、2018年9月10日 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

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
   <td colname="col1"> <p>「ツール」タブの「解析」リンク </p> </td> 
   <td colname="col2"> <p>IMSログインを使用して、Analytics APIを介してeVar/propのわかりやすい名前を表示します。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>起動を動的に挿入 </p> </td> 
   <td colname="col2"> <p>「ツール」タブから、「起動」がインストールされていないページに対して、任意のページに動的に「起動」を挿入してテストできます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Targetの機能強化 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Target要求のパフォーマンスタイミングを追加しました。 </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">adobe.target.trackEventのキャプチャ </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 機能強化 {#section-56003a12c32f4998bf1cf2a25a518592}

* 「ネットワーク」タブの表示を改善し、テーブルの高さが大きくなりすぎず、ユーザーが水平方向にスクロールする前に垂直方向にスクロールするようにしました。 以前は、スクロールバーはテーブルの下部に表示されていました。 テーブルが非常に大きくなる可能性があるので、ユーザーがテーブルを表示するには、すべてを垂直方向にスクロールする必要がありました。
* [ツール]タブからObservePointへのリンクを更新。

## バグの修正 {#section-d9231f5c77254d0888347e5f569a8b1d}

* 「Experience Cloud」タブが更新されない問題を修正しました

* 現在の「Advertising Cloud」名ではなく、「ネットワーク」タブの「ソリューション」行に「Media Manager」が表示される問題を修正しました
* デバッガーがすべてのページに_satelliteを挿入する問題を修正しました

## バージョン0.0.803、2018年8月10日 {#topic-d2901fb70ce04a5586f6c7a994fce875}

バージョン0.0.803には、お客様向けの変更は含まれていません。

## バージョン0.0.802 2018年8月1日 {#topic-b93cd396af5e49dc97cd86264871aeb4}

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
   <td colname="col1"> <p>「ツール」タブの「監査者」リンク </p> </td> 
   <td colname="col2"> <p>デバッガーからAuditorへのリンクを追加しました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>折りたたまれたタブ </p> </td> 
   <td colname="col2"> <p>折りたたまれたタブは「概要」タブと「ツール」タブに保持されます </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>クリックして表示 </p> </td> 
   <td colname="col2"> <p> すべてのタブにクリックトゥビュー機能を追加 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 機能強化 {#section-0e7090e3e6a645f085d4553b983ecff8}

* Media Managerの名前をAdvertising cloudに変更しました
* 見つからない場合は、「ネットワーク」タブからソリューションを削除しました。

## バグの修正 {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* 「セルをクリックして表示」機能が更新されない問題を修正しました
* AAMのヒットが「AAM」タブに表示されない問題を修正しました

## バージョン0.0.798、2018年6月14日 {#topic-3b2d44277f2f4c0295d82724c34bf467}

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
   <td colname="col1"> <p>Excelエクスポートオプション </p> </td> 
   <td colname="col2"> <p>[ネットワーク]タブにExcelのエクスポートオプションを追加。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>外観の改善 </p> </td> 
   <td colname="col2"> <p>Chrome拡張機能フォントをAdobe Cleanに更新しました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> トラックパッドスワイプ機能 </p> </td> 
   <td colname="col2"> <p>トラックパッドのスワイプの進む/戻る機能を無効にしました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>生のサーバーコールインジケーター </p> </td> 
   <td colname="col2"> <p>生のサーバー呼び出し文字列がコピーされたことを示すインジケーターを追加しました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>「ログのクリーンアップ」タブ </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">そのソリューションの行項目がログに見つからない場合は、ソリューションフィルターでソリューションを非表示にします </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">DTM呼び出しが見つからない場合は、DTMにのみ適用されるので、レベルフィルターを非表示にします </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">「レベル」列に表示されるアイコンを変更し、 </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">DTM行項目の「コードを表示」のフォーマットを標準化 </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>フッターのヘルプリンクを更新 </p> </td> 
   <td colname="col2"> <p>フッターのヘルプリンクをhttps://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/に更新しま <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external"> す。</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## バグの修正 {#section-c292cf7dcb17463bb1928de73bd55121}

* バッジ番号がクリアされない問題を修正しました
* 顧客が空白のサマリーの詳細を報告する問題を修正しました

## Version 0.0.797 May 25, 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

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
   <td colname="col1"> <p>mbox 切り替え </p> </td> 
   <td colname="col2"> <p>mboxの切り替えが「ターゲット」タブに追加されました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>フィルター設定が定着しました </p> </td> 
   <td colname="col2"> <p>フィルター設定がネットワーク上の画面の上部に表示され、ログタブが表示されるようになりました。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ネットワーク値の表示とコピー </p> </td> 
   <td colname="col2"> <p>詳細を表示し、任意のセルの値を[ネットワーク]タブにコピーできます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>法的なフッターリンクと著作権 </p> </td> 
   <td colname="col2"> <p>ユーザーインターフェイスに法的なフッターリンクと著作権情報を追加しました。 </p> </td> 
  </tr> 
 </tbody> 
</table>


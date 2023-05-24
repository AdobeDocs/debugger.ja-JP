---
title: リリースノート
description: Adobe Experience Platform Debugger の最新のリリースノートです。
keywords: デバッガー;Experience Platform Debugger 拡張機能;Chrome;拡張機能;リリースノート
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 91%

---

# リリースノート

## バージョン 1.3.0 - 2022年1月28日（PT）

* 最新のリリースバージョンとメモを表示するためのバージョン情報リンクが追加されました。
* Analytics リクエストの処理後のヒットを表示する切替スイッチが追加されました。切替スイッチは「Analytics」セクションで使用できます。
* デバッガーの外部でセッションが閉じられた場合のリモートデバッグセッションの問題を修正しました。
* 「Web SDK Edge トランザクション」タブに表示されていたエラー通知を修正しました。
* デバッガーが _satellite オブジェクトにアクセスしたときのページ非推奨（廃止予定）の警告に関する Adobe タグを修正しました。
* AppMeasurement インスタンスがページで見つからなかった一部のケースを修正しました。
* デバッガーウィンドウを初めて開いたときに発生したページ接続の問題を修正しました。

## バージョン 1.2.0 - 2021年10月26日（PT）

* ネットワークビューでは、すべてのブラウザータブのイベントを表示します。現在のタブのイベントのみを表示するには、デバッガーの右下隅にあるロックアイコンを選択します。
* ブランディングを更新しました。

## バージョン 1.1.0 - 2021年10月5日（PT）

* リモートデバッグビジュアライゼーション - Adobe Experience Platform Web SDK／「Edge トランザクション」セクションで、リモートデバッグイベントを視覚的なフローチャートに整理します。
* 新しいリモートデバッグセッションを開始する際に、ページで使用するAdobe Experience Platform Web SDK IMS 組織が、ログイン組織と一致する必要があります。
* 接続されたタブのエッジトランザクションのみを表示します。Target Trace のログは、ログ／「エッジ」セクションで引き続き参照できます。
* ページ上の Adobe Experience Platform Web SDK のインスタンスごとに、別個のデータストリーム ID 設定の上書きが可能です。デバッグを有効にする切替スイッチを追加します。
* Adobe Experience Platform Web SDK のリモートデバッグセッションで、Adobe Target Trace トークンが必ずしも常に送信されなかった問題を修正しました。

## バージョン 1.0.0 - 2021年5月5日（PT）

* Experience Platform Debugger の最初のメインリリースです。Experience Cloud Debugger の代わりとなることを目的としています。

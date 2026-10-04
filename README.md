# 采来 — サイクル —

AIに采配を。開発に連続性を。

## 公開マニュアル

https://kanameshiga-dev.github.io/saikuru-manual/

利用者ガイド（0〜13章）と保守者向け付録（A〜G）を収録しています。

このリポジトリはマニュアルのみです。本体コードは含みません。

index.htmlをダウンロードすれば、画像を含めオフラインで読めます。


## 判断Providerの計測

[導入・計測 総合レポート](https://kanameshiga-dev.github.io/saikuru-manual/reports/provider-evaluation-report.html)

限定した合成操作での暫定評価です。ケースが少ないため、今後も計測を続け、失敗例・条件・根拠とともに更新します。生ログ・認証情報・実環境のパスは公開しません。

[実台帳3方式・120件の比較レポート](https://kanameshiga-dev.github.io/saikuru-manual/reports/ledger-evaluation-report.html)

読取・検索・分類・画面移動を比較しました。固定手順を優先し、Ollamaは状態に応じた操作選択の候補として継続評価します。異常系の反復と通信断後の復旧比較は残課題です。


## 適用範囲の追加測定（2026-10-02）

[実画面追加評価](reports/extended-evaluation-report.html) / [判断部分の分類別最終測定](reports/final-provider-evaluation-report.html)

単純選択への限定適用を推奨。全経路の自動分類を実装したという意味ではありません。合成状態の結果を未知の実アプリへ一般化せず、長期観測を継続します。


[限定運用の実装後測定](reports/limited-runtime-evaluation-report.html)：修正後の比較は6/6達成、CLI入力約9%減。反復が少ないため暫定評価です。


## 紹介資料

[采来 AI駆動開発の取り組み（2026-10-04・第8版、PDF・27ページ）](presentations/saikuru-ai-development-20261003-v8.pdf)


## プロジェクト履歴

[履歴ページの使い方と画面例](https://kanameshiga-dev.github.io/saikuru-manual/#project-history)

プロジェクト別に依頼・工程・承認・作業イベントを確認します。画面例はサンプルデータで、人の担当者のログイン・本人確認は未実装です。


## 2026-10-04 更新

[判断待ち・試行別トークン・操作案内・台帳タブ・常駐通知](index.html#decision-wait-manual)を追加しました。通知は初期無効です。検証済み範囲と未確認事項は本文に記載しています。

## 2026-10-04 参考ファイル添付
新規依頼・台帳相談の添付操作、対応形式、事前検査による拒否、保存・引き継ぎ、未確認事項をマニュアルへ追加。第8版PDFと共有済みURLを維持しています。

## 2026-10-04 指示ファイルの警告と作成
容量・行数・階層合計候補、不足警告と台帳フィルタ、コンバートで作成する手順、確認の限界を追記しました。第8版PDFと既存の共有URLを維持しています。

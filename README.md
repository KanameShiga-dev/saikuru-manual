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

[采来 AI駆動開発の取り組み（2026-10-03・第5版、PDF・21ページ）](presentations/saikuru-ai-development-20261003-v5.pdf)

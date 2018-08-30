オンラインスクール顧客・売り上げ確認アプリケーション
====

Overview
英語、ファイナンス、プログラミングなど様々なジャンルについて時間単位の課金で学習できるオンラインスクールがあり、
そのスクールで、顧客と受講記録を管理し、毎月の請求金額や売り上げ金額を確認できるアプリケーションです。

## Description
・「メニュー画面」
各ページへのリンクが記載されています。

・「顧客一覧」
顧客の一覧表示と登録、編集を行う画面です。

・「レッスン受講記録」
顧客の受講記録を登録、編集、またはその登録一覧を確認する画面です。
※受講時間のバリデーションを設定できていません。

・「月別請求一覧」
特定の月の請求すべき金額を確認できる画面です。
※請求金額の計算方法が誤っており、修正間に合っておりません。
（同一の顧客に対して基本料金を受講毎に加算してしまっている。）

・「レポート」
ジャンルや年齢層別にどれくらいの売り上げがあるかを確認できる画面です。
※ジャンルと性別別・ジャンルと年齢層別の各テーブルに必要なデータの集計はできておりますが、
それを表に当てはめて表示するところまで至りませんでした。
ページ下部に集計結果を表示しています。
※月別の切り替えも実装間に合いませんでした。

## Requirement
前月などの日時計算の為にdateutilを使用しました。
$ pip3 install python-dateutil
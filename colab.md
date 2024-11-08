author: shogo.yamada
summary: 「単体テストの考え方/使い方」という本から作成したcolab
id: original_unit_test_colab
categories: codelab,markdown
environments: Web
status: Draft
feedback link: https://github.com/yshogo
analytics account: XXXXXXXX

# Codelab: Jetpack Composeでの単体テスト学習

## Step 1: プロジェクトセットアップ
概要: シンプルなカウンターアプリを作成します。ボタンを押すたびにカウントが増加し、テキスト表示が更新されます。

## Step 2: 単体テストの目的
テスト内容: incrementメソッドが正しく動作し、カウントが増加することを確認します。

## Step 3: 単体テストの学派（古典 vs ロンドン）
内容: ロンドン学派と古典学派の違いを示します。ロンドン学派ではViewModelをモック化してテスト。

## Step 4: 単体テストの構造とAAAパターン
内容: Arrange-Act-Assert（AAA）パターンでのテスト構造を示し、コードを一貫性のある構造にします。

## Step 5: 良いテストの4本の柱
内容: CounterScreenのUIテストで状態が正しく表示されているか確認し、リファクタリング耐性と保守性について学びます。

## Step 6: テストダブルの活用
内容: モックとスタブの違いを理解し、ログを持つViewModelのテストでモック化を体験します。

## Step 7: 単体テストの3つの手法
内容: 出力値ベース、状態ベース、コミュニケーションベースの3つのテスト手法を示します。

## Step 8: 複雑なコードのリファクタリング
内容: ViewModelに履歴機能を持たせ、ビジネスロジックとUIの分離を学びます。

## Step 9: 完成形とまとめ
完成形コード: 最終的なCounterアプリとテストコードを確認します。
まとめ: テストの基本原則とJetpack Compose特有のUIテストの利点を確認し、リファクタリング耐性と保守性について学びます。

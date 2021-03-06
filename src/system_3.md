
# [システム 03] 継続的インテグレーション 

## なぜ、重要か。
継続的インテグレーションとは、自動的で定期的に実施される結合テスト環境のことです。

この環境が簡単でかつ信頼できるほど、開発者は、誰かの手作業によるテストを待つ必要がなくなり、自分の手元でソースコードの改善を繰り返しやすくなります。これは生産性と品質向上に寄与します。

## チェックリスト 

### メトリクスの計測
+ すべてのインテグレーションテストにかかる時間が計測されており、それは30分以内に完了するか。

### 学習と改善
+ テストカバレッジ基準や自動テストガイドラインを用意し、これらを継続的に改善するための工数がチームで割かれているか。

### プラクティスと習慣
+ プロダクトの半分以上のモジュール/クラスファイルに対して、ユニットテストが存在しているか。
+ テスト用データやスタブ/モックなどを整備し、テストを書きやすくするための環境整備をしているか。
+ 継続的インテグレーション環境が存在し、開発者は開発ブランチの全テストをリソース調整することなく、自由に行うことができるか。

### アンチパターン
+ 一部の人だけがテストを書き、一部の人はテストを書かないといったように自動テスト習慣を個々人の努力目標などになっている。
+ テスト自体が複雑になって、長期間メンテナンスされていない。
+ 自動テストが失敗したまま、そのコードが本番デプロイされることを許容している。
            
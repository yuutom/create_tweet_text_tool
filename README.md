# システム概要
- twitterAPIを利用してツイートデータを収集
- 機械学習を利用してIT関連のツイートのみ収集(tweet_test.csvに出力)
- 「いいね数」「リツイート数」「投稿日時」からスコアを算出
- 上位のツイートに限りtweet_ranking.csvに出力

## 手順
1. main.pyを実行
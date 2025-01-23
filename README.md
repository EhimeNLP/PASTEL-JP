# PASTEL-JP（PArallel text Style Tranfer corpus for EvaLuation in JaPanese）
120文対×7スタイルの日本語スタイル変換の評価用パラレルコーパスを人手で構築しました。
これらは、5人の大学生によって人手で構築された、文単位のパラレルコーパスです。


# ファイルについて
- 7スタイルのフォルダがそれぞれあり、その中に2つのtxtファイルが含まれています。2つのtxtファイルはスタイルの文が行ごとにペアになっています。
  - Formality：`formal.txt`と`informal.txt`はそれぞれフォーマルな文とインフォーマルな文です。
  - Gender：`feminine.txt`と`masculine.txt`はそれぞれ女性的な文と男性的な文です。
  - Politeness：`impolite.txt`と`polite.txt`はそれぞれ無礼な文と丁寧な文です。
  - Romance：`factual.txt`と`romance.txt`はそれぞれ事実的な文とロマンスな文です。
  - Sentiment：`negative.txt`と`positive.txt`はそれぞれネガティブな文とポジティブな文です。
  - Simplicity：`comp.txt`と`simp.txt`はそれぞれネ難解な文と平易な文です。
  - Toxicity：`non-offensive.txt`と`offensive.txt`はそれぞれネ非攻撃的な文と攻撃的な文です。

- PASTEL-JPのFormalityには以下のような文対が含まれています。
  
  | formal.txt     | informal.txt   |
  |:-----------:|:---------:|
  | 真剣な様子で見入っていました。  | 真面目に見ていた。   |
  | 今日は友達と食事に行きます。     | 今日、友達とご飯いってくるね。   |
  | 隣町の峠まで車を運転しました。     | 隣町の峠までドライブした。   |
  | コーヒーや紅茶はいかがですか。    | コーヒーか紅茶飲む？   |
  | 昨日は一日中家でくつろいでいました。     | 昨日は一日中家でごろごろしていた。   |




# 文献情報
- 花房 健太郎, 柳本 大輝, 梶原 智之, 二宮 崇．<br>
  大規模言語モデルによる日本語スタイル変換の性能評価．<br>
  言語処理学会第31回年次大会, 2025．

- 花房 健太郎, 柳本 大輝, 梶原 智之, 二宮 崇．<br>
  大規模言語モデルによる11種類の日本語スタイル変換の性能評価．<br>
  NLP若手の会第19回シンポジウム（YANS）, September 2024．

# 公開ライセンス
Creative Commons Attribution 4.0 International License (CC BY 4.0)

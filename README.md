# 分量シミュレーター

[github page](https://awtnb.github.io/gaisan/)

------------------------------

1. 文字列を改行区切りで分割する
1. 連続するスペースは1つに集約する
1. Microsoft Word の見出し書式、箇条書き書式で挿入される制御文字を取り除く
1. 連続する空行を1行とみなす
1. 段落の文字数を字詰めで割る
    + このとき、アルファベットなどのASCII文字は2文字で1カウントし、紙面上のグリッド換算で行数を概算する
1. すべての段落について紙面上の行数をカウントし、集計する
1. 1ページあたりの行取りで割ってページ数を概算する

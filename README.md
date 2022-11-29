# robosys2022
ロボットシステム学の練習リポジトリ

# plusコマンド
![test](https://github.com/Mark-D127/robosys2022/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字までの数字を足す。

#ダウンロード

1.Ubuntu をダウンロードする。
2.git が入ってない場合は以下のコマンドでインストールする。
　sudo apt install git

#インストール

以下のコマンドでインストールする。
　git clone https://github.com/Mark-D127/robosys2022 

#起動する手順
1. cd robosys2022 でおりる。
2. seq (数字) | ./plus で実行する。

#使用例

seq 5 | ./plus
結果
15

seq 10 | ./plus
結果
55

## 必要なソフトウェア
* Python
  * テスト済み: 3.7～3.10

## テスト環境
* Ubuntu
*このソフトウェアパッケージは, 3条項BSDライセンスの下, 再頒布及び使用が許可されています。
*© 2022 Masaki Daira

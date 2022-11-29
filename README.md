# robosys2022
 
ロボットシステム学の練習リポジトリ

# plusコマンドのテスト

![test](https://github.com/ahaya8810/robosys2022/actions/workflows/test.yml/badge.svg)

## 機能

標準入力から読み込んだ数字までの連続した整数の数字を足した結果を表示する。

その後、計算結果が偶数か奇数かを表示する。


## インストール方法

``
$  git clone  https://github.com/ahaya8810/robosys2022.git 　
``
　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　
## 実行方法

``
$ seq 〇　| ./plus

$ cd robosys2022

$ chmod +x plus   
``
   
（〇には任意の数字が入る。）

## 起動例

```
$ seq 5 | ./plus
15.0 
奇数
 ```

## 必要なソフトウェア
* Python 3.7〜3.10

## テスト環境
* Ubuntu 22.04.1 LTS

## 権利

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．

© 2022 ahaya8810


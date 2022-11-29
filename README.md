# robosys2022
 
ロボットシステム学の練習リポジトリ

# plusコマンドのテスト

![test](https://github.com/ahaya8810/robosys2022/actions/workflows/test.yml/badge.svg)

## 機能

標準入力から読み込んだ数字までの連続した整数の数字を足した結果を表示する。

その後、答えの二乗を計算する。


## インストール方法

```
$  git clone  https://github.com/ahaya8810/robosys2022.git 　
```
　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　
## 実行方法

```
$ seq 〇　| ./plus   
```
   
（〇には任意の整数を入れる。）

## 起動例

```
$ seq 5 | ./plus
答えは15.0その二乗は225.0 

```

## 必要なソフトウェア
* Python 3.7〜3.10

## テスト環境
* Ubuntu 22.04.1 LTS

## 権利

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．

© 2022 ahaya8810


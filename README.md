# robosys2022
 
![test](https://github.com/ahaya8810/robosys2022/actions/workflows/test.yml/badge.svg)

ロボットシステム学の練習リポジトリ

# plusコマンド

### 機能

標準入力から読み込んだ整数を足した結果と結果を二乗したものを表示する

### インストール方法

```
$  git clone  https://github.com/ahaya8810/robosys2022.git 　
```
　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　
### 実行方法の例

```
$ seq 〇　| ./plus   
```
   
〇には任意の整数が入り、読み込んだ数字までの連続した整数を足す。

また、次のようにnumに任意の数字を複数入力して行う方法もある。

```
$ ./plus < num
```

### 起動例

```
$ seq 5 | ./plus
答えは15.0その二乗は225.0 
```

```
$ ./pius < num
答えは46.0その二乗は2116.0
```

### 必要なソフトウェア
* Python 3.7〜3.10

### テスト環境
* Ubuntu 22.04.1 LTS

## 権利

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．

© 2022 ahaya8810


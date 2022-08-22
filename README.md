This script is a program that generates a large number of images by combining IMG files randomly selected for each layer.


## Samples of completed image files
https://github.com/moyattodataman/generative_art/tree/main/output_sample

## Resource files per layer
https://github.com/moyattodataman/generative_art/tree/main/components

## Procedure

### 1. Clone the repository

```
git clone https://github.com/moyattodataman/generative_art.git
```

### 2. Prepare resource files

1. Create resource files for each layer.
2. Files to the directory of each layer.
3. If layers not enough, create additional directories. If layers are in excess, delete the directories.

```
Directory "1"; bottom layer
directory "2"; second layer from the bottom
directory "3": third layer from the bottom
same as below
```

### 3. Start the program.
The completed file is generated in the "output" directory.

```
python generative_art/generate.py
```



======

このスクリプトは、レイヤーごとにランダムに抽出したIMGファイルを組み合わせた画像を大量生成するプログラムです。

## 完成版のサンプル
https://github.com/moyattodataman/generative_art/tree/main/output_sample

## レイヤーごとのリソースファイル
https://github.com/moyattodataman/generative_art/tree/main/components

## 手順

### 1. リポジトリをクローンしてください。

```
git clone https://github.com/moyattodataman/generative_art.git
```

### 2. リソースファイルの配置

1. レイヤーごとのリソースファイルを作成してください。
2. レイヤー別にディレクトリへ格納してください。
3. レイヤーが足りない場合は、追加作成してください。レイヤーが余る場合は、ディレクトリを削除してください。

```
ディレクトリ"1"; 一番下のレイヤー
ディレクトリ"2": 下から2番目のレイヤー
ディレクトリ"3": 下から3番目のレイヤー
以後同様
```

### 3. プログラムを起動してください。
完成ファイルが"output"ディレクトリに生成されます。

```
python generative_art/generate.py
```

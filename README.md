このスクリプトは、レイヤーごとにランダムに抽出したIMGファイルを組み合わせた画像を大量生成するプログラムです。


## 完成版のサンプル
https://github.com/moyattodataman/generative_art/tree/main/output_sample

## レイヤーごとのリソースファイル
https://github.com/moyattodataman/generative_art/tree/main/components

## 手順

1. リポジトリをクローンしてください。

```
git clone https://github.com/moyattodataman/generative_art.git
```

1. リソースファイルの配置
レイヤーごとのリソースファイルを作成してください。
レイヤー別にディレクトリへ格納してください。
レイヤーが足りない場合は、追加作成してください。
レイヤーが余る場合は、ディレクトリを削除してください。

ディレクトリ"1"; 一番下のレイヤー
ディレクトリ"2": 下から2番目のレイヤー
ディレクトリ"3": 下から3番目のレイヤー
以後同様

1. generative_artディレクトリに移動してください。

```
cd generative_art
```

1. プログラムを起動してください。

```
python generate.py
```

1. 完成ファイルが"output"ディレクトリに生成されます。

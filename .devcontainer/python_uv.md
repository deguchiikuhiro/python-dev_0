# python uv slimコンテナ

## 利用方法

コンテナはuvのインストール、uvによるpythonのインストール、ツールのインストールまでを実装します。   
プロジェクトの作成以降はコンテナ実行後に実施してください。

## プロジェクトの初期化例

```bash
uv init
uv add --dev ipykernel jupyter
```

## コンテナの特徴

- uvの場合、slimでもalpineでもイメージサイズに差異が発生しない。→ slimで進める。
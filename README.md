# NLP-100Knocks

- 自然言語処理（NLP）の100本ノック。

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
├── docker-compose.yml
├── docs
├── models
├── notebooks
├── pyproject.toml
├── requirements.txt
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境詳細

- Python : 3.9.9

## 事前準備

- Docker インストール

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/NLP-100Knocks）

```
cd Desktop/NLP-100Knocks
```

- Dockerによる環境構築（フォルダをマウント：Desktop/NLP-100Knocks）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## 動作環境

マシンスペック（Mac)

- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
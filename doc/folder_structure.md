# フォルダ構成（ディレクトリ構造）

本プロジェクトのフォルダ構成は以下の通りです。
<details>
<summary>📂 <code>cycle_computer/</code></summary>
<pre>
cycle_computer/
├── data/           # センサーデータやログなどの保存先
├── doc/            # ドキュメント
├── include/        # ヘッダファイル群
│   ├── core/
│   ├── display/
│   ├── gpio/
│   ├── sensors/
│   │   ├── i2c/
│   │   ├── sensor_base.h
│   │   ├── spi/
│   │   └── uart/
│   └── util/
├── LICENSE         # ライセンス情報
├── cycom_main.cc   # メインプログラム
├── README.md       
├── scripts/        # ビルドや実行スクリプト
├── src/            # 実装コード
│   ├── core/
│   ├── display/
│   ├── gpio/
│   ├── sensors/
│   │   ├── i2c/
│   │   ├── spi/
│   │   └── uart/
│   └── util/
└── tests/          # テストコード
    ├── core/
    ├── display/
    ├── gpio/
    └── sensors/
        ├── i2c/
        └── uart/
</pre>
</details>

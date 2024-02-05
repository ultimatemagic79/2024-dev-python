# Python 2024 主流技術の学習

このリポジトリは、2024年にPythonで主流となる技術：pyenv + poetry、Pydantic、click + typer、loguruの学習に特化しています。[Uzabase Tech Blog](https://tech.uzabase.com/entry/2024/02/02/120601)の記事を参考に、これらの技術を組み合わせて、強力で効率的なPythonアプリケーションの開発方法を学びます。

## 学習技術

- **pyenv + poetry**: Pythonバージョンの管理と依存関係の取り扱い、プロジェクト環境の構築を学びます。
- **Pydantic**: データのバリデーションと設定管理を行うモダンな方法について学びます。
- **click + typer**: 2つのライブラリを使って、使いやすいコマンドラインインターフェースを作成します。
- **loguru**: Pythonでのロギングをシンプルかつ効果的に行う方法を学びます。

## プロジェクト構成

```plaintext
project/
│
├── pyproject.toml  # poetryの設定ファイル
├── main.py         # アプリケーションのエントリーポイント
└── models.py       # Pydanticモデルを定義
```

## はじめに

1. **プロジェクトのセットアップ**: pyenvでPythonのバージョンを設定し、poetryで新しいプロジェクトを作成します。
2. **依存関係の追加**: poetryを使用して、Pydantic, click, typer, loguruをプロジェクトに追加します。

   ```bash
   poetry add pydantic click typer loguru
   ```

3. **モデルの定義**: Pydanticを使用して、アプリケーションで使用するデータモデルを`models.py`に定義します。
4. **CLIの実装**: `main.py`にて、clickとtyperを組み合わせたCLIを実装します。
5. **ロギングの設定**: loguruを使用して、アプリケーションのロギングを設定します。

## 貢献方法

このリポジトリへの貢献を歓迎します。プルリクエストを通じて改善提案を送るか、新機能のリクエストやバグ報告のためにissueを開いてください。

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は`LICENSE`ファイルを参照してください。

## 謝辞

- この学習プロジェクトは、[Uzabase Tech Blog](https://tech.uzabase.com/entry/2024/02/02/120601)の記事に触発され、Pythonコミュニティとその豊富なエコシステムに感謝を込めて作成されました。
- 各技術の開発者と貢献者に感謝します。

Pythonの力を最大限に引き出して、一緒に学びましょう！

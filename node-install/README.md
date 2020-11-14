# Node.js のインストール

## Windows (WSL を使う場合)

Windows Subsystem for Linux (WSL) を使うことで、Linux のコマンドラインを Windows で使用できます。オススメ。

1. WSL2 を有効にし、Ubuntu をインストールする (https://docs.microsoft.com/ja-jp/windows/wsl/install-win10)
1. スタートメニューから「Ubuntu」を起動する
1. https://github.com/nodesource/distributions/blob/master/README.md の Using Ubuntu の指示に従う
1. `node -v` でインストールできていることを確認

## Windows (PowerShell を使う場合)

PowerShell など、Windows のネイティブ環境で Node.js を使いたい場合。

1. [Node.js](https://nodejs.org/en/) にアクセス
1. Current バージョンのインストーラをダウンロードし、インストール
1. PowerShell を開き、`node -v` でインストールできていることを確認

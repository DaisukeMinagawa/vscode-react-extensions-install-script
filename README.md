# VSCode React開発おすすめ拡張機能一括インストールスクリプト
## React.js 開発に役立つ VSCode 拡張機能を一括でインストールするためのシェルスクリプトです。
  
### インストールする拡張機能

1. ES7 React/Redux/GraphQL/React-Native snippets
2. Prettier - Code formatter
3. ESLint
4. Auto Close Tag
5. Auto Rename Tag
6. Bracket Pair Colorizer
7. GitLens
8. JavaScript (ES6) code snippets
9. Live Server
10. Path Intellisense
11. Debugger for Chrome
12. React Native Tools
13. vscode-styled-components
14. Tabnine AI Autocomplete
  
## 使用方法

このリポジトリをクローンするか、install_react_extensions.sh ファイルをダウンロードします。
ターミナルを開き、スクリプトファイルがあるディレクトリに移動します。
以下のコマンドを実行して、スクリプトに実行権限を付与します：
```bash
chmod +x install_react_extensions.sh
```


以下のコマンドを実行して、スクリプトを実行します：
```bash
./install_react_extensions.sh
```
  
スクリプトが実行され、リストアップされた拡張機能が VSCode に自動的にインストールされます。
インストールが完了したら、VSCode を再起動して拡張機能を有効にしてください。

> [!CAUTION]
> 注意事項

このスクリプトを実行するには、VSCode がシステムにインストールされており、code コマンドがパスに設定されている必要があります。
インターネット接続が必要です。
既にインストールされている拡張機能がある場合は、そのまま維持されます。

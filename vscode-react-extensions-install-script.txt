#!/bin/bash

extensions=(
  "dsznajder.es7-react-js-snippets"
  "esbenp.prettier-vscode"
  "dbaeumer.vscode-eslint"
  "formulahendry.auto-close-tag"
  "formulahendry.auto-rename-tag"
  "coenraads.bracket-pair-colorizer"
  "eamodio.gitlens"
  "xabikos.javascriptsnippets"
  "ritwickdey.liveserver"
  "christian-kohler.path-intellisense"
  "msjsdiag.debugger-for-chrome"
  "msjsdiag.vscode-react-native"
  "styled-components.vscode-styled-components"
  "tabnine.tabnine-vscode"
)

for extension in "${extensions[@]}"
do
  code --install-extension "$extension"
done

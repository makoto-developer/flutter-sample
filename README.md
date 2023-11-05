# Flutter

## バージョン管理

`fvm`を使う

```shell
brew tap leoafarias/fvm
brew install fvm
```

## fvm使い方

```shell
# 利用可能なバージョン一覧
fvm releases
```

グローバルで設定したバージョン

```
fvm global 3.13.9
#-> /Users/user/fvm/default/binにインストールされる
```

PATHを通す

```shell
# zsh
vi ~/.zshrc
## 以下を追記
export PATH="$PATH":"$HOME/fvm/default/bin"

# fish shell
vi ~/.config/fish/config.fish
## 以下を追記
set -g FLUTTERPATH $HOME/fvm/default
fish_add_path $FLUTTERPATH/bin
```

## なぜFlutter

- React Nativeより速度が早い、ビルドの問題が起きづらい。
- ガベージコレクションが高速 -> 快適

## flutter Architecture

https://github.com/flutter/flutter/wiki/The-Engine-architecture

## References

- https://docs.flutter.dev/get-started/install/macos#get-sdk


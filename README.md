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

## References

- https://docs.flutter.dev/get-started/install/macos#get-sdk


# dotfiles
## Brewfile
### 手順
1. Homebrewをインストール
    - `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
1. `brew doctor`でHomebrewを問題無く利用できる環境か確認
1. brew-fileをインストール
    - `brew install argon/mas/mas`
    - `brew install rcmdnk/file/brew-file`
1. `Brewfile`をローカルにダウンロードして`~/.brewfile`以下に配置
1. `brew file install`でインストールを実行

### 参考
- [macOS 用パッケージマネージャー — macOS 用パッケージマネージャー](https://brew.sh/index_ja)
- [Brewfileを使った新Mac移行手順 - Qiita](https://qiita.com/darai0512/items/d88662773a070b1bc750)

# 参考
- [mizoguche/dotfiles](https://github.com/mizoguche/dotfiles)

# 【WIP】Chromenv
## 概要
google-chromeとchromedriverのバージョン管理CLIツール。
MacOSのみ対応。

## Installation

- uninstall google-chrome in your PC.

- if you set `google-chrome` alias or command, remove it.

- install brew package.

  ```
  brew tap onigiri3670/homebrew-tap
  brew install -v chromenv
  ```

## Command Reference
- google-chrome

  open google-chrome selected by chromenv.

- chromenv versions

  show enable versions.

- chromenv install [version number]

  install google-chrome and chromedriver.

- chromenv install -l

  show installable versions.

- chromenv global [version number]

  set global version of google-chrome and chromedriver version.

- chromenv help

   show manual.

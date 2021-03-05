# Chromenv (experimental)
## About

Chromenv is CLI tool to manage google-chrome and chromedriver environment.
For MacOS.

## Installation

- backup google-chrome in your PC.

  ```
  mv /Applications/Google\ Chrome.app /Applications/Google\ Chrome.app.bk
  ```


- if you set `google-chrome` alias or command, remove it.

  ```
  unset google-chrome
  ```

  ```
  unalias google-chrome
  ```

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

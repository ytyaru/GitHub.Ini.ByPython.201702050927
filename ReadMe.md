# このソフトウェアについて

GitHubリポジトリ作成スクリプトのINI部分。

[こちら](https://github.com/ytyaru/GitHub.Console.ByPython.201702041951)で使用するINIファイル部分。

# 開発環境

* Linux Mint 17.3 MATE
* [Python 3.4.3](https://www.python.org/downloads/release/python-343/)
    * [dataset](https://github.com/pudo/dataset)

## WebService

* [GitHub](https://github.com/)
    * [アカウント](https://github.com/join?source=header-home)
    * [AccessToken](https://github.com/settings/tokens)

# 準備

## 必要なデータベースを作成する

* [GitHub.Accounts.Database](https://github.com/ytyaru/GitHub.Accounts.Database.20170107081237765)
    * [GiHubApi.Authorizations.Create](https://github.com/ytyaru/GiHubApi.Authorizations.Create.20170113141429500)
* [GitHub.Repositories.Database.Create](https://github.com/ytyaru/GitHub.Repositories.Database.Create.20170114123411296)

# 実行

以下のいずれかを実行する。

```sh
bash TestData.sh
```

```sh
python3 -m unittest TestData.py
```

# 結果

Data.pyの単体試験を行う。

# ライセンス #

このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

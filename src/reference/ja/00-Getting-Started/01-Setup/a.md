---
out: Installing-sbt-on-Mac.html
---

  [MSI]: $sbt_native_package_base$/v$app_version$/sbt-$windows_app_version$.msi
  [ZIP]: $sbt_native_package_base$/v$app_version$/sbt-$app_version$.zip
  [TGZ]: $sbt_native_package_base$/v$app_version$/sbt-$app_version$.tgz
  [Manual-Installation]: Manual-Installation.html
  [AdoptiumOpenJDK]: https://adoptium.net

macOS への sbt のインストール
--------------------------

### JDK のインストール

リンクをたどって [JDK 8 もしくは JDK 11][AdoptiumOpenJDK] をインストールする。

もしくは [SDKMAN!](https://sdkman.io/) を使う:

```
\$ sdk install java \$(sdk list java | grep -o "8\.[0-9]*\.[0-9]*\.hs-adpt" | head -1)
```

#### [SDKMAN!](https://sdkman.io/)

```
\$ sdk install sbt
```

### ユニバーサルパッケージからのインストール

[ZIP][ZIP] か [TGZ][TGZ] をダウンロードしてきて解凍する。

### サードパーティパッケージを使ってのインストール

> **注意:** サードパーティが提供するパッケージは最新版を使っているとは限らない。
> 何か問題があれば、パッケージメンテナに報告してほしい。

#### [Homebrew](https://brew.sh/)

```
\$ brew install sbt
```

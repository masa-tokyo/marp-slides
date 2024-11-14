---
marp: true
theme: "base"
header: "Flutter Tokyo Community #0"
footer: ""
headingDivider: 1
paginate: true
size: 16:9
math: katex
---
<!-- TODO: modify the background color -->

# CI/CD って何？ <br>アプリ開発を効率化するはじめの一歩

<!--_class: lead -->

## Masaki Sato

# Masaki Sato / 佐藤将来

<!-- TODO: align on the left -->
<!-- TODO: add ice breaking intro -->

![bg right:40%](./images/self-intro.png)

- Flutter エンジニア(フリーランス)
- Codemagic 日本語記事担当
- イベント運営
  - 東京Flutterハッカソン
  - FlutterGakkai
  - FlutterNinjas
- 好きな 🍜
  - 家系（武道家）
  - 鶏白湯（ようすけ）
  - つけ麺（武虎）

# 「CI/CD」を聞いたことある人？🤚
<!--_class: lead -->

# CI/CD を使っている人？🤚
<!--_class: lead -->

# はじめに

使ってない方 → 「へー、CI/CD 使ってみるのアリかも！」

使っている方 → 「改めて、CI/CD ってすごい！」

# CI/CD とは
<!-- TODO: add images of services -->

<!-- _footer: "出典: [ビジネス+IT](https://www.sbbit.jp/article/cont1/81640)" -->

![w:840](./images/cicd-flowchart.png)

# CI について

![w:840](./images/cicd-flowchart-ci.png)

<!-- _footer: "出典: [ビジネス+IT](https://www.sbbit.jp/article/cont1/81640)" -->

![w:760](./images/cicd_flowchart.png)

# 手動だと...

![w:1080](./images/dart-analysis.png)

![w:1080](./images/flutter-test.png)

# CI だと...

![w:760](./images/ci-check.png)

# CD とは

![w:840](./images/cicd-flowchart-cd.png)

<!-- _footer: "出典: [ビジネス+IT](https://www.sbbit.jp/article/cont1/81640)" -->

# 手動だと...

#### コマンドラインでビルドして...

![w:1080](./images/ios-upload-1.png)

# 手動だと...

#### Xcodeで色々...

![w:1080](./images/ios-upload-2.png)

![w:1080](./images/ios-upload-3.png)

# CD だと...

#### ボタン一つで完了 🙌

![w:400](./images/start-new-build.png)

# CD だと...

#### PRと紐付けることも出来る！

![w:1080](./images/pull-request.png)

# 手動だと...

#### 環境の再現性がない...

- ソースコード
- ビルド引数
- ビルド環境
  - Flutter
  - Xcode
  - CocoaPods

# CD だと...

#### どのコミットがビルドされたのか記録が残る

![w:760](./images/codemagic-commit.png)

# CD だと...

#### 環境が固定出来る

![w:760](./images/codemagic-build-mode.png)

![w:760](./images/codemagic-build-env.png)

# CI/CD の恩恵

<!-- _footer: "*n=950 by [Rollbar Research: Traditional Error Monitoring Is Missing the Mark, 2021](https://www.businesswire.com/news/home/20210216005484/en/Rollbar-Research-Shows-That-Traditional-Error-Monitoring-Is-Missing-the-Mark)" -->

#### どのくらいの時間をバグ改修に使っていますか？

![w:760](./images/statistics-1.png)

# CI/CD の恩恵

#### 1ヶ月に直すと...

![w:760](./images/statistics-2.png)

# CI/CD の恩恵

#### 人件費が5000円/時だとすると...

![w:760](./images/statistics-3.png)

# CI/CD の恩恵

#### 会社に5人いたら...

![w:760](./images/statistics-4.png)

# 終わりに
<!-- TODO: show on the 1st screen -->

[CI/CD ツール(Codemagic) を使って Flutter アプリを App Store へ公開する](https://zenn.dev/codemagic/articles/3ade99d0485de4)

![w:1120](./images/zenn-blog.png)

---
<!-- TODO: show entire screen -->

<!-- _header: "" -->
![w:1120](./images/raffle.png)

# Thank you!
<!--_class: lead -->
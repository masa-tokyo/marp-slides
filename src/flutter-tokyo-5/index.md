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
  - 家系
  - 鶏白湯
  - つけ麺

# はじめに
<!--_class: lead -->

# 「CI/CD」を聞いたことある人？🤚
<!--_class: lead -->

# 「CI/CD」使っている人？🤚
<!--_class: lead -->

# はじめに

使ってない方 → 「へー、CI/CD 使ってみるのアリかも！」

使っている方 → 「改めて、CI/CD ってすごい！」

# CI/CD とは
<!-- TODO: add images of services -->

<!-- _footer: "出典: [ビジネス+IT](https://www.sbbit.jp/article/cont1/81640)" -->

![w:760](./images/cicd-flowchart.png)

# CI について

![w:760](./images/cicd-flowchart-ci.png)

<!-- _footer: "出典: [ビジネス+IT](https://www.sbbit.jp/article/cont1/81640)" -->

![w:760](./images/cicd_flowchart.png)

# 自力だと...

![w:760](./images/dart-analysis.png)

![w:760](./images/flutter-test.png)

# CIだと...

![w:760](./images/ci-check.png)

# CD とは

![w:760](./images/cicd-flowchart-cd.png)

<!-- _footer: "出典: [ビジネス+IT](https://www.sbbit.jp/article/cont1/81640)" -->

# 自力だと...

#### 結構手間...

![w:760](./images/ios-upload-1.png)

![w:760](./images/ios-upload-2.png)

![w:760](./images/ios-upload-3.png)

# CDだと...

#### 簡単🙌

![w:760](./images/start-new-build.png)

![w:760](./images/pull-request.png)

# 自力だと...

#### 環境の再現性がない...

- ソースコード
  - 実行ブランチ
  - ビルド時引数
- ビルド環境
  - Flutter
  - Xcode
  - CocoaPods


# CDだと...

#### 全て固定出来る

![w:760](./images/codemagic-commit.png)

![w:760](./images/codemagic-build-env.png)

# CI/CD の恩恵

<!-- _footer: "*n=950 by [Rollbar Research: Traditional Error Monitoring Is Missing the Mark, 2021](https://www.businesswire.com/news/home/20210216005484/en/Rollbar-Research-Shows-That-Traditional-Error-Monitoring-Is-Missing-the-Mark)" -->

どのくらいの時間をバグ改修に使っていますか？

![w:760](./images/statistics-1.png)

# CI/CD の恩恵

1ヶ月に直すと...

![w:760](./images/statistics-2.png)

# CI/CD の恩恵

人件費が5000円/時だとすると...

![w:760](./images/statistics-3.png)

# CI/CD の恩恵

会社に5人いたら...

![w:760](./images/statistics-4.png)

# 終わりに
<!-- TODO: show on the 1st screen -->

![w:1120](./images/zenn-blog.png)

---
<!-- TODO: show entire screen -->

<!-- _header: "" -->
![w:1120](./images/raffle.png)

# Thank you!
<!--_class: lead -->
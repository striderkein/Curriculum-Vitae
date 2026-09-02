# 職務経歴書（要約版）

[詳細版（日本語）](https://striderkein.github.io/Curriculum-Vitae) | [English (Summary)](https://striderkein.github.io/Curriculum-Vitae/summary/en)

## 基本情報

|key|value|
|---|---|
|氏名|小澤 史朗 (Shirow Ozawa)|
|生年月日|1972-10-10|
|居住地|東京都|
|最終学歴|山梨大学教育科学部（現・教育人間科学部）|

---

## キャリアサマリー

ソフトウェア開発歴 15 年のフルスタックエンジニア。TypeScript / React によるフロントエンドと、Node.js / Java / Ruby によるバックエンドを軸とする。現在は物流 DX SaaS の開発チームリーダーとして、Claude Code による AI 駆動開発を日常の開発フローに組み込んでいる。

- **AI 駆動開発の日常的な実践**：Claude Code を毎日の開発環境として使用し、チームへの導入も主導。並列実装からコードレビュー自動化、E2E の自動修復まで運用
- **4 名チームの開発リーダー**として物流 DX SaaS「LogiGo」を担当（TypeScript + React / NestJS + Prisma / PostgreSQL / AWS）。インフラ設定以外の全開発領域を担当
- **Playwright による E2E・VRT テスト基盤をゼロから構築**し全面移行をリード。夜間自動実行、失敗時の Issue 自動起票と AI による自動修正、カバレッジ計測まで整備
- **数値で表れる事業成果**：コンバージョン導線の UI 改善で CVR 12% 向上、コンテンツ基盤の改善で新規流入 10% 増・SEO スコア 5〜6% 改善
- **大規模サービスの開発経験**：ユーザー数 50 万人の電力小売 PWA、UU 4 万人の WebRTC オンラインレッスン基盤
- **レガシーコードのモダン化**を得意とし、ユニットテスト・CI/CD・開発者向けツール整備を常に開発の一部として実践
- **幅広いドメイン経験**：物流、エネルギー、金融、EC、公共、通信。自社プロダクトと受託開発の双方を経験

---

## AI 駆動開発（Claude Code）

Claude Code を主開発環境として日常的に使用し、実装・リファクタリング・レビュー・運用対応まで幅広く担当している。現職ではチームへの導入を主導し、周辺の運用ルールとツールを整備した。

- **並列開発**：Git worktree ごとに複数の Claude Code セッションを走らせ、複数の機能追加・修正を同時に進行。自身の役割は仕様の言語化・タスク分解・レビューへ比重を移している
- **自作スキルのチーム資産化**：PR 作成、RED / GREEN コミットによるテストファーストのバグ修正、レビュー指摘の解消、コードベースに基づく仕様 Q&A といったチームの手順をスキルとして実装し、誰でも同じ手順を再現できる状態にしている
- **CI へのエージェント組み込み**：Claude Code と GitHub Actions を組み合わせ、コードレビュー、レビュー依頼、チケット管理システムとの双方向同期、各種通知を自動化
- **テストの自動修復**：E2E 失敗時に Issue を自動起票し AI による自動修正を走らせることで、夜間実行の結果を放置されない状態に保っている
- **品質のガードレール**：AI の出力はレビュー対象の入力として扱う。テストは失敗する状態から書き、lint と VRT を CI のゲートに置き、すべての変更に人のレビューを通す

---

## 保有スキル

- JavaScript / TypeScript + React.js OR Vue.js でのフロントエンド開発・設計
- レガシーコードからモダンなフロントエンドへのリファクタリング
- フロントエンド開発基盤の整備（テスト環境、フレームワークの初期設定、CI/CD）
- UT を基本とした保守性と再利用性を意識したコーディング
- NestJS, Ruby on Rails, express, Spring Boot でのサーバーサイド開発
- Claude Code による AI 駆動開発（並列セッション、自作スキル、開発プロセスの自動化）
- アジャイル、スクラムの経験。チームリード、コードレビュー、指導・育成

---

## 技術スタック

### 言語

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white" />
  <img alt="Ruby" src="https://img.shields.io/badge/-Ruby-CC342D?style=flat-square&logo=Ruby&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=Java&logoColor=white" />
  <img alt="Swift" src="https://img.shields.io/badge/-Swift-000096?style=flat-square&logo=Swift&logoColor=white" />
  <img alt="ObjectiveC" src="https://img.shields.io/badge/-ObjectiveC-009600?style=flat-square&logo=ObjectiveC&logoColor=white" />
  <img alt="PHP" src="https://img.shields.io/badge/-PHP-730000?style=flat-square&logo=PHP&logoColor=white" />
</p>

### フレームワーク・その他

<p>
  <img alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />
  <img alt="Vue" src="https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=white" />
  <img alt="Ruby-on-Rails" src="https://img.shields.io/badge/-Rails-CC0000?style=flat-square&logo=Ruby-on-Rails&logoColor=white" />
  <img alt="Apollo" src="https://img.shields.io/badge/-Apollo%20GraphQL-311C87?style=flat-square&logo=apollo-graphql&logoColor=white" />
  <img alt="GraphQL" src="https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" />
  <img alt="Firebase" src="https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=Firebase&logoColor=white" />
  <img alt="Gatsby" src="https://img.shields.io/badge/-Gatsby-663399?style=flat-square&logo=Gatsby&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=Vite&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
  <img alt="mongoDB" src="https://img.shields.io/badge/-mongoDB-03684A?style=flat-square&logo=mongoDB&logoColor=white" />
</p>

---

## 職務経歴

### シマント株式会社（2026/01 - 現在）／ 開発チームリーダー

物流 DX SaaS「LogiGo」のフルスタック開発。インフラ設定以外の全領域（新機能開発、パフォーマンス改善、API 設計、テスト整備）を担当。4 名チーム。Claude Code をチームに導入し、現在の並列開発手法を確立した。

**技術スタック：** TypeScript + React / NestJS + Prisma / PostgreSQL / AWS / Playwright / GitHub Actions

- 請求・支払まわりの機能開発をリード。付帯費用の入力・集計・帳票/CSV 出力、消費税対応（税区分、内税/外税、端数処理）、締日基準の検索・集計機能の変更設計を担当
- 配車計画（配車板）の機能開発・改善を多数担当。強制割当・入替・配車解除、車検期日アラート、検索機能の強化、ドラッグ操作まわりの不具合修正
- 各種マスタ管理機能の拡充（車両・地点・荷主の項目追加、荷主と地点の紐付け UI）とデータモデルの改善
- Playwright による E2E・VRT テスト基盤をゼロから構築し全面移行をリード。ビジュアルリグレッションテスト、夜間自動実行、E2E 失敗時の Issue 自動起票と AI による自動修正、カバレッジ計測（ダークマップ）を導入
- Claude Code スキル群と GitHub Actions で開発プロセスを自動化。コードレビュー、レビュー依頼、チケット管理システムとの双方向同期、各種通知。Git worktree 上で複数セッションを並走させ機能開発を並列化
- CI/CD とパフォーマンスの改善。高速ランナーへの移行によるコスト・時間削減、マイグレーション drift 検知、VRT の安定化、API レスポンス圧縮、監視アラームの IaC 化、認証トークン期限切れに起因する本番障害の恒久対応

### サーバーフリー株式会社（2024/02 - 2025/11）／ 詳細設計・実装

大手インフラ企業の業務システム開発。バックエンド API 開発、フロントエンド改修、クラウドインフラ構築を担当。2 名体制。

**技術スタック：** React + TypeScript / Spring Boot / MySQL / Azure

- Spring Boot によるデータ連携バッチと PDF 作成 REST API を開発
- jQuery で構築された業務システムのフロントエンドを改修
- Spring Boot API を Azure App Service へデプロイ
- 離職理由：一身上の都合

### 株式会社ゼヒトモ（2022/08 - 2023/08）／ 詳細設計・実装・テスト・コードレビュー

中小事業者と個人顧客とのマッチングサービスの開発。ユーザーの利便性を高める追加機能の設計・実装を主導し、フロントエンドの改善活動をリード。スマホアプリ開発の知見を生かしたレスポンシブ対応も主導。3〜5 名のスクラム開発。

**技術スタック：** TypeScript + Next.js / Redux, AngularJS / express, MongoDB / AWS ECS, S3 / WordPress

- コンバージョンを促す UI を実装し、**CVR を 12% 改善**
- express と MongoDB による API 開発（インフラは AWS ECS, S3）
- 低品質なブログコンテンツを改善して **SEO スコアを 5〜6% 改善**、新規コンテンツの開発で **新規顧客の流入を 10% 増加**
- 離職理由：業績悪化に伴う希望退職

### 株式会社セカンドコミュニティ（2022/01 - 2022/07）／ 動画配信のリードエンジニア

オンラインレッスン向けに、チャット・ビデオ会議・描画機能を提供する WebRTC ウェブアプリケーションを開発。UU 4 万人規模のサイト。2 名体制。

**技術スタック：** Vue / Nuxt.js / Ruby on Rails / Docker / Amazon S3

- ビデオ会議画面の基本機能とレスポンシブ対応を実装
- チャット機能へのファイル添付・絵文字対応を実装
- localStorage を用いた描画機能の Undo / Redo を実装
- 離職理由：就業時間中のカメラ常時オンを全社員に義務付ける社内規則の突然の変更

### 株式会社グッドワークス（2021/02 - 2021/12）／ 詳細設計・実装・コードレビュー・OJT

SES。1〜5 名体制で 4 つのプロジェクトを担当。

- **動画配信ウェブアプリ（2021/05 - 2021/11）：** フロントエンドとバッチの詳細設計・実装、課金レポートバッチの仕様変更と単体・結合テスト、ユニキャスト配信の技術調査、ムービーチケット番号の認証ウェブアプリの開発
- **公共交通機関向けスマホアプリのログ収集バッチ（2021/10）：** Python, AWS Batch, AWS SAM による個人開発
- **官公庁向け災害情報管理システム（2021/04）：** Vue + Amplify, Apollo Client, GraphQL, AWS CodeCommit によるフロントエンド開発
- **IoT 機器との連携システム（2021/02 - 2021/03）：** 新型コロナ対策の工事作業員入退場管理システム。フロントエンドは Vue3 / Vue、バックエンドは express
- 離職理由：自社開発企業で働きたかったため

### 株式会社システムアイ（2019/12 - 2020/12）／ 要件定義〜結合テスト

電力小売事業者の契約ユーザー向け PWA の開発（**ユーザー数 50 万人**）。5〜10 名体制。

- Cognito を用いたユーザー認証基盤のプロトタイプ開発
- TypeScript による Push 通知作成バッチの開発
- 既存 Node.js アプリケーションの Docker 化
- 離職理由：職場のハラスメント

### 株式会社ムロド（2019/03 - 2019/12）／ 要件定義〜結合テスト

受託開発。5〜10 名体制および個人開発。

- EC サイト運営企業向けに、PHP / Laravel による EC プラットフォームのカスタマイズと保守開発、在庫管理ツールの開発・保守を担当
- P2P チャットアプリを設計・実装。Firebase（Realtime Database, Authentication）による認証基盤と、React Native（Web, iOS, Android）によるフロントエンド
- 離職理由：会社の倒産

### 光栄システム株式会社（2017/10 - 2019/02）／ 基本設計〜テスト

配車システムの開発とサービス提供。4 つのプロジェクトを個人で担当。

- C# による PDF 生成 RESTful API を開発。POST リクエストを受けて DB のデータから PDF を生成
- Oracle と連携するウェブ API を開発
- 配車システムのフロントエンド開発。D3.js によるタンクローリーのインタラクティブな配車表を実装
- サーバー稼働記録の可視化ウェブアプリと、ログファイルを Google Charts 用 JSON へ変換するバッチを開発。AWS EC2 上の HTTP プロキシの構築・運用も担当

### 株式会社デルタウイング（2013/03 - 2017/09）／ 設計・実装・テスト

SES。1〜6 名のウォーターフォール／アジャイル体制で 13 のプロジェクトに参画。金融、公共、通信、コンテンツ領域が中心。

|期間|プロジェクト|技術|
|---|---|---|
|2017/07 - 2017/09|銀行口座情報を国際的にやり取りするオープン系新規システム|Java, HiRDB|
|2017/02 - 2017/06|EC ウェブアプリと iOS アプリの保守、コンテンツプロバイダアプリ開発|Objective-C, PHP / Smarty, MySQL|
|2016/12 - 2017/01|衛星放送向け 4K 対応セットトップボックス|VanillaJS|
|2016/10 - 2016/11|携帯基地局管理システムへの災害対応機能追加（基本設計）|—|
|2016/04 - 2016/09|銀行向け帳票管理システム（PDF 処理・SOAP API 連携 DLL の新規開発）|C++|
|2015/10 - 2016/03|海上防衛の艦船位置情報システム、GIS サーバーの製品調査・選定|JavaScript / D3.js, Java|
|2015/03 - 2015/09|コンテンツ事業の BI 運用、保険営業向け顧客情報管理ツール|汎用機データのブラウザ出力|
|2014/08 - 2015/02|ディズニージャパン会員サイトのリニューアル（RESTful API）|Java / Apache Wink, jQuery|
|2013/10 - 2014/07|共同宅配システムの配送支援、クレジットカード加盟店管理システム改修|バッチ・ストアド・JSP|
|2013/03 - 2013/11|法人向け社内 SNS iOS アプリ、歩行者移動支援アプリの iOS 移植|Objective-C|

### それ以前の経歴（1995 - 2013）

|期間|会社・職種|概要|
|---|---|---|
|2012/10 - 2013/02|株式会社プレザント|金融機関向けミドルウェア。銀行合併に伴う受付システム統合で、印刷機能と別プロセス起動を担う DLL を開発（3 名体制）|
|2011/10 - 2012/03|株式会社フロンティア（社内 SE）|物流企業の資材管理・発注システムを、社内 LAN の C# アプリからウェブアプリへ移行（Java, JSP, MSSQL）|
|2010/04 - 2011/03|公務員|小学校教諭|
|2007/11 - 2009/04|アデコ株式会社|B フレッツの営業|
|2003/02 - 2005/02|ヤマト運輸株式会社|セールスドライバー|
|2002/07 - 2003/01|株式会社ナンバーフォー|受託開発（個人）。非接触 IC カードによる自動ログイン（Visual C++）、不動産業者向け画像取得ツール（VB6）、携帯電話向け掲示板 CGI（Perl, HDML, cHTML）|
|1995/04 - 2001/03|公務員|小学校教諭|

---

## 課外活動

- **OSS・個人開発：** [backlog-tamer](https://github.com/striderkein/backlog-tamer)（CLI ツール）の開発、および MDN ドキュメント翻訳をはじめとする OSS への PR 作成

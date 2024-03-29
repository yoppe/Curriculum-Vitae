# オープン職務経歴書（スキルシート）

公開出来ない情報は伏せているので、より詳しいスキルシートを見たい方はメール( yohei.ookubo@gmail.com )にて、お問い合わせください。
(オープン職務経歴書を書くにあたって参考にさせていただいた記事: [オープン職務経歴書を書いてみた](https://qiita.com/Sa2Knight/items/4af2f24fac9290d26119))

- [基本情報](#基本情報)
    - [自己紹介](#自己紹介)
    - [転職について](#転職について)
    - [関心の強いワード](#関心の強いワード)
    - [資格](#資格)
    - [自然言語](#自然言語)
    - [自主制作物](#自主制作物)
- [技術スタック](#技術スタック)
- [直近で関わった開発案件](#直近で関わった開発案件)
    - [大手ECサービスの広告システムのインフラ構築/運用](#大手ecサービスの広告システムのインフラ構築運用)
    - [Web広告の運用ツール開発](#web広告の運用ツール開発)
    - [大手アパレルECの海外向けECシステム構築](#大手アパレルecの海外向けecシステム構築)
    - [Web広告運用における分析用データの収集システムの開発](#web広告運用における分析用データの収集システムの開発)
    - [人材育成支援システム（Webサービス）](#人材育成支援システムwebサービス)
- [その他の過去に関わった開発案件](#その他の過去に関わった開発案件)
    - [Web広告運用ツール③（リプレイス）](#web広告運用ツール③リプレイス)
    - [Web広告運用ツール②](#web広告運用ツール②)
    - [Web広告運用ツール①](#web広告運用ツール①)
    - [Twitterのツイートをリアルタイムに検索サービス](#twitterのツイートをリアルタイムに検索サービス)
    - [Twitterを利用した大学内SNSの開発](#twitterを利用した大学内snsの開発)

## 基本情報

key|value  
--|--
Name|大久保陽平
Birth|1990/01/11
Family|既婚・子ども１人
Location|東京都 世田谷区
Education|国立大学卒
Job|[Anyflow inc](http://anyflow.jp) のCTO
Mail|[yohei.ookubo@gmail.com](mailto:yohei.ookubo@gmail.com)
Github|[yoppe](https://github.com/yoppe)
Facebook|[大久保 陽平](https://www.facebook.com/ookubo.yohei)
Twitter|[yoppe18](https://twitter.com/yoppe18)
Qiita|[@yoppe](https://qiita.com/yoppe)
LinkedIn|[yohei-okubo](https://www.linkedin.com/in/yohei-okubo/)

### 自己紹介

Webサービスを中心とした開発を７年ほど行っており、現在は[Anyflow inc](http://anyflow.jp) という業務の自動化を行うSaaSを開発している会社でCTOをやっています。

以前の職場でドメイン駆動設計とスクラムを開発に取り入れていたため、仕様の決まりきった物をそのまま作る作業的な開発よりも、
プロダクトマネージャーと密にコミュニケーションを取りながらより価値の高いものを共に作り上げていけるような開発を得意としています。

言語的にはバックエンドはScala・Pythonを得意とし、型システムを活かした保守性の高いWebシステムを開発することが得意です。
それ以外にもCakePHPやRailsを使ったWebサービスの開発経験などがあります。
フロントエンドはAngularを始めとするモダンな技術を使った開発が得意です。
またSASSなどを使用したUIデザインやApache Beamを使った大規模データ処理基盤、k8s(GKE)を使った広告配信のインフラ基盤の構築/運用、Terraformによるサーバ環境構築の自動化を行った経験もあり、バックエンドからフロントエンド、インフラ周りまで幅広い領域をカバーしています。

様々な言語・フレームワーク・ツールを経験する中で習得した、可読性・保守性の高いコードを書く技術に関しては自信を持っております。

### 転職について

~~よほどの理由がない限り、フリーランスを辞めて企業に就職することは考えておりません。
案件のオファーなどはいつでも歓迎しております。~~

⇛ CTOとして[Anyflow inc](http://anyflow.jp)にジョインしました。（絶賛エンジニア募集中です⇛ https://anyflow.jp/corp/recruit/ ）

### 関心の強いワード

- Kubernetes
  - Istio
  - 分散トレーシング
- 大規模データ処理
  - リアルタイムストリーミング処理
  - バッチの分散処理
- 機械学習
  - Word2Vec,LSTMといった自然言語系
  - 強化学習

### 資格

取得年月|資格名
--|--
2012-12|応用情報技術者
2007-12|基本情報技術者

いずれも学生時代に取得。

### 自然言語

平均的に対人コミュニケーションが苦手とされるエンジニア業界の中では比較的まともにコミュニケーションが取れる方だと思ってます。 英語は苦手で簡単なコミュニケーションも取れないレベルなので、現在勉強中です。

### 自主制作物

key|value
--|--
サービス名|流ツイ
公開年|2014年
公開URL|http://ryutwi.yoppe.net/
概要|Twitter（ツイッター）に投稿されたツイート（つぶやき）をリアルタイムに検索することができるツイッター検索サイト
使用技術|PHP,WebSocketなど（詳細：http://ryutwi.yoppe.net/thanks.php ）
月間UU|5,000〜10,000

## 技術スタック

下記に一通り書いていますが、特に得意な技術スタックとしては、**Scala × PlayFramework**、**TypeScript × Angular2+**、**Python × Django**で、設計手法は**DDD**が得意です。

言語|備考
--|--
Scala|４年／一番得意な言語で、仕事のアプリケーション開発では一番使用している。１からシステムを設計することができ、教育・指導もできるレベルで習得
Java|４ヶ月／仕事で少しSeasar2を使った程度。書けなくはないがJavaで作る必要のある要件のものは可能な限りScalaで作りたいと思っている
Python|２年／プライベートでも仕事でも一番使用している言語。機械学習系のライブラリで株価予測プログラム、スクレイピングバッチ、ログ収集基盤作成、Airflowの処理系、ワークフローエンジン開発などを経験。１からシステムを設計することができるレベルで習得
Ruby|６ヶ月／仕事でもプライベートでもある程度使っていた言語。ある程度は書けるがRubyの性質上、チーム開発では保守性の高いコードを維持しづらいため、積極的に使っていない。
PHP|１年６ヶ月／学生時代に一番得意としていた言語。学生時代の制作物はすべてPHPで作成。仕事でも副業案件で触ることがあるが、積極的に触ることはない。１からシステムを実装することができるレベルで習得
JavaScript|５年／学生時代からほぼ全ての案件で触ってきている。ES6含め広く浅く経験。JavaScriptよりはTypeScriptを使っていきたいと思っている
TypeScript|２年／プライベートではあまり使わないが仕事でフロントエンドを開発する場合は積極的に採用している。ある程度型安全に書けるため、保守性を担保できて助かる。１からシステムを実装することができるレベルで習得
C|１年／学生時代にプログラミング学習や研究で使用したレベル
Go|１ヶ月／勉強のためにチュートリアルをやったレベル。業務でv1.12のビルドフロー構築経験あり

フレームワーク|備考
--|--  
PlayFreamework|４年／Scalaを用いた案件のほぼ全てで使用。プレゼンテーション層のみをPlayに依存させ、他は独自に作ることが多い
Django|２年／仕事でもプライベートの開発でも使用経験あり。管理画面付きのWebサービスをスピード重視で作成したい時などに使用。
flask|１ヶ月／勉強のためにチュートリアルをやったレベル。[flaskを用いたハンズオン勉強会の講師経験あり](https://qiita.com/yoppe/items/651a9ce8a7c655299eda)
Angular2×RxJS|１年／自身で技術選定を行い、仕事で設計から実装まで行った経験あり。最初の学習コストさえ払ってしまえば、スピードと保守性を両立させて作れる印象。特にangular-cliの存在は大きく、ビルド周りの構築に時間をかけずにいいのは助かる。１からシステムを設計することができるレベルで習得
React×Redux|２ヶ月／既存プロジェクトのヘルプをしたときに使用。Reduxの理解や各種ライブラリの選定、ビルド周りの整備など、ちゃんと作るためには初期コストを大きく払わないといけない印象。慣れれば早いのだろうがまだその領域に達せていない
Riot.js×Bacon.js|１年／仕事で全体的な設計から実装まで担当。規模が大きくなり保守性が下がったため、Bacon.jsを使用し、一部リアクティブな実装に再設計した。（今後、使うことはないだろうが）１からシステムを設計することができるレベルで習得
AngularJS|６ヶ月／既存プロジェクトの追加開発時に使用。（今後、使うことはないだろうが）保守できるレベルでは習得
CakePHP|１年／学生時代のプライベート開発や仕事での副業案件で使用。１からシステムを実装することができるレベルで習得していたが、最近は全く触っていないため、知識のアップデートができていない
Ruby on Rails|６ヶ月／既存プロジェクトの追加開発時に触った程度。
sinatra|２ヶ月／チュートリアルを行い、仕事のサブプロジェクトで少し触った程度
Seasar2|４ヶ月／既存プロジェクトの追加開発時に少し触った程度

フロントツール周り|備考
--|--  
Webpack|１年／１からビルド周りを構築できるレベルで習得。[設定周りの記事](https://qiita.com/yoppe/items/e8f2a63248e270d29095)を書ける程度に熟知
gulp.js|１年／１からビルド周りを構築できるレベルで習得。[簡単な導入記事](https://qiita.com/yoppe/items/f5f0beb6d6714e214f78)を書ける程度
Grunt|６ヶ月／（今後、使うことはないだろうが）保守できるレベルで習得

インフラ周り|備考
--|--
RDB/NoSQL|６年／MySQL/PostgreSQL/Redisの経験があり、SQLアンチパターンや経験からDB設計を行えるレベル。大まかな最適化をしたことはあるが、細かいチューニングの経験はない
クラウドサービス(AWS)|３年／アプリエンジニアとして基本的なサービスの運用経験あり。小規模なサーバ環境であれば仕事での構築経験あり。<br>経験技術； EC2 / VPC / S3 / RDS / IAM / Route53
クラウドサービス(GCP)|２年６ヶ月／アプリエンジニア・SREとしてGCP全般の運用/構築経験あり。またマネージドサービスを組み合わせたインフラ基盤設計の基礎知識あり。<br>経験技術； GCE / CloudSQL / GAE/SE(Standard Environment) / GAE/FE(Flexible Environment) / GKE(Kubernetes) / GCS / Dataflow / Bigtable / BigQuery / Datastore / CloudPub/Sub / CloudFunctions / CloudCDN / CloudIAP / CloudKMS / CloudNAT / CloudArmor / GLB / Cloud Build / Stackdriver Logging / Stackdriver Monitoring
インフラ自動化(Terraform)|２年／AWS,GCPともに構築経験あり。
インフラ自動化(Ansible/Chef)|２年／Chefは保守経験のみ。最近はAnsibleばかりで、Ansibleは構築経験あり
Vagrant|６ヶ月／[ネットワーク周りの記事](http://labs.septeni.co.jp/entry/20140707/1404670069)を書ける程度には理解
Docker|２年／SRE業務で構築・保守経験あり。苦なく作成・デバッグ／運用できるレベルで習得。
Kubernetes|１年６ヶ月／SRE業務で構築・保守経験あり。自身で設計・構築・デバッグ／運用できるレベルで習得。
Jenkins|１年／SRE業務で保守経験あり。OpenIDの認証機構追加したり、JenkinsAPIを使った処理の制御など一通り複雑な運用もできるレベルで習得。

その他の技術スタック|備考
--|--
設計手法|３年／DDD(ドメイン駆動設計)。アーキテクチャとしては、レイヤードアーキテクチャとヘキサゴナルアーキテクチャを仕事で経験。どちらも１から構築できるレベルで理解。
WebSocket|４ヶ月／サーバ、クライアントともに１から実装経験あり。プライベートでWebSocketを使用して作ったWebサービス（[流ツイ](http://ryutwi.yoppe.net/)）
ElasticSearch|４ヶ月／仕事でログ解析のために使用。簡単なプラグイン導入ができるレベルで習得。[ElasticSearch関連の執筆記事](https://qiita.com/yoppe/items/3e61fd567ae1d4c40a96)
fluentd|４ヶ月／仕事でログ収集のために使用。設定ファイルをいじれるレベルで習得
Kibana|４ヶ月／仕事でログの可視化のために使用。簡単なダッシュボードを作れるレベルで習得
Celery|６ヶ月／仕事で分散処理可能なワーカー開発で使用
Pandas|６ヶ月／仕事でもプライベートでも機械学習用のデータの加工のために使用。ある程度処理効率を考えて、データの加工ができるレベルで習得
Treasure Data|４ヶ月／仕事でログ解析のために使用
DataDog|６ヶ月／GCPの監視ツールとして使用。
テスト|３年／ScalaではScalaTest,Spec2, JavaScriptではKarma/Jasmineなどを使用し、ビジネスロジックが含まれる部分や複雑な変換処理のみ単体テストを書いていくべきという考えを持っております

## 直近で関わった開発案件

### ベンチャー企業（[Anyflow inc](http://anyflow.jp) ）のiPaaS開発
期間: 2020年1月(業務委託) - 2020年12月に正式ジョインし、 2021年1月からCTO職 
- 担当業務
  - FastAPIを使ったAPI開発
  - 戦略的DDD（ドメイン駆動設計）を使ったプロジェクト推進
  - 戦術的DDD（ヘキサゴナルアーキテクチャ）を使ったシステム設計
  - エンジニアのマネジメント全般
  - Djangoを使ったAPI開発
  - Celeryを使ったワークフローエンジンの開発
    - 独自の型システム設計・実装
    - タスクの入力インターフェイス設計・実装
    - タスクのテスト実行機能開発
    - テストコードの整備
    - etc.
  - SaaSとの連携コネクタ開発
  - 全体的な設計の改善提案とリファクタリング実施
  - CI周りの自動化
  - ログ監視の整備
  - Kubernetesを使ったサービス運用
  - スクラムの導入補助と運営
- 役割
  - バックエンドエンジニア、2021年1月からCTO職 
- チーム
  - 全体：１０人程度
  - エンジニア：５人〜７人
- 習得スキル
  - DDD（ドメイン駆動設計）の実践ノウハウ
  - 各種マネジメント業務
  - Django・FastAPIの基礎知識
  - Celeryを使った分散処理ワーカー開発の基礎知識
  - 多種多様なサービスとのAPI連携のノウハウ
  - スクラムの運営ノウハウ
- コメント
  - TODO
- 開発環境
  - 言語/FW: Python, Django、FastAPI
  - DB/NoSQL: MySQL(CloudSQL), Redis
  - CI/CD: CircleCI
  - GCPツール: GKE, GCS, CloudSQL, CloudIAP, CloudNAT, CloudBuild, BigQuery, CloudKMS, CloudPub/Sub, StackDriver
  - ミドルウェア: Celery
  - インフラ自動化: Terraform, argo CD
  - その他: DDD(ドメイン駆動設計)、GitHub, Slack, IntelliJ IDEA, Datadog, netlifycms

### マーケティング企業のデータ連携用のバッチ基盤構築
期間: 2019年11月 - 12月
- 担当業務
  - TerraformとAnsibleを使ったGCPインフラ構築の自動化
  - ジョブスケジューラの選定／Airflowのサーバ構築
  - パッチのジョブフロー設計・構築
  - Datafow(scio)のバッチ処理開発／Datafowのテンプレート化
- 役割
  - データエンジニア
- チーム
  - 全体：５〜６人程度
  - データエンジニア：２人
- 習得スキル
  - Datafow開発の基礎知識
  - Bigtableを使ったデータ設計の基礎知識
  - Airflowの基礎知識
- コメント
  - 大規模なデータ連携を行う上でシステム的なボトルネックが生まれないような設計を意識し、バッチシステムを開発させていただきました。
  - GCPのインフラ運用に関してはチーム内で私が特に長けている領域だったため、ネットワーク周りのデバッグやすぐにできるインフラコストの削減提案など、担当業務以外でもプラスαの価値を提供できる動き方をさせていただきました。
- 開発環境
  - 言語: Scala, Python
  - DB: MySQL(CloudSQL)
  - CI/CD: CircleCI
  - GCPツール: GCE, GCS, CloudSQL, DataFlow, Bigtable, CloudPub/Sub, CloudIAP, StackDriver
  - ミドルウェア: Airflow
  - インフラ自動化: Terraform, Ansible
  - その他: Gatling(負荷テストツール), GitHub, Slack, IntelliJ IDEA


### 大手ECサービスの広告システムのインフラ構築/運用
期間: 2018年12月 - 2019年10月
- 担当業務
  - SREとしてGCP上のインフラの構築
  - 障害対応などの各種インフラの運用業務
  - TerraformとAnsibleを使ったインフラ構築の自動化
  - Jenkins/CloudBuildを用いたGolangの自動ビルド&デプロイフローの構築
  - バッチサーバ(Digdag)のk8s化
  - インフラのコード生成処理の再構築(高速化)
  - マネージドサービスを使ったセキュリティ強化のためのインフラ設計
  - KubernetesとGatlingを用いた負荷テスト基盤の構築
  - 負荷テストのシナリオ作成と実施(秒間最大6万リクエスト超)/ボトルネックの調査＆改善
- 役割
  - エンジニア（SRE）
- チーム
  - プロジェクト全体：２０人程度
  - SRE：２〜３人
- 習得スキル
  - Kubernetesを用いたインフラ構築・運用の基礎知識
  - 広告システムにおける監視の基礎知識
  - Jenkinsの運用ノウハウ
  - KubernetesにおけるInfrastructure as Codeの実践ノウハウ
- コメント
  - SRE未経験ながらSSPのインフラを担うSREチームにジョインさせていただきました
  - SREチームではk8sのマルチクラスター運用を行うなどアグレッシブなインフラ運用に携わりました
  - インフラは２〜3人体制で運用していたため幅広い実務経験を積むことができました
- 開発環境
  - DB: MySQL(CloudSQL)
  - CI/CD: Jenkins, CloudBuild
  - GCPツール: GKE, GCE, GCS, GLB, CloudSQL, CloudNAT, CloudIAP, CloudKMS, CloudNAT, CloudArmor, DataFlow, BigQuery, CloudPub/Sub, StackDriver
  - ミドルウェア: Digdag, AeroSpike
  - インフラ自動化: Terraform, Ansible, Packer
  - その他: Gatling(負荷テストツール), DataDog(監視ツール), GitHub, Jira(チケット管理), Slack, IntelliJ IDEA

### Web広告の運用ツール開発
期間: 2018年09月 - 2018年12月(３ヶ月)
- 担当業務
  - GCP上のインフラの再設計・構築
  - TerraformとAnsibleを使ったインフラ構築の自動化
  - CloudBuildを用いた自動ビルド&デプロイフローの構築
  - ログの監視の基盤構築
  - Rubyを使ったTwitterAdsAPIとの接続基盤の構築
  - Railsを用いたサービス開発
- 役割
  - エンジニア（バックエンド、インフラ）
- チーム
  - プロジェクト全体：５人程度
  - エンジニア：２〜３人
- 習得スキル
  - GCPを用いたインフラ構築の基礎知識
  - Ruby/Railsを用いたサービス設計の基礎知識
- コメント
  - ３〜４人の開発チームで既存プロダクトのインフラのリプレイスやRailsによる機能追加などに携わらせていただきました
  - 特にインフラに関しては、現行の設計ではプロダクトのスケールが困難な状況だったため、再設計案をいくつか提案させていただきました
  - また、議論の上でGoogleAppEngineを使用することとなり、GAE/FEを用いたサービスインフラのリプレイス作業に従事しました
  - その過程でTerraformやAnsibleといった構成管理ツールを利用し、インフラ全体の保守性向上に寄与しました
- 開発環境
  - FW: Ruby on Rails
  - DB: MySQL
  - サーバー: GAE/FE, GCS, CloudBuilds, CloudPub/Sub, CloudFunctions
  - インフラ自動化: Terraform, Ansible
  - その他: StackDriver, GitHub, Jira(チケット管理), Slack, IntelliJ IDEA

### 大手アパレルECの海外向けECシステム構築
期間: 2018年01月〜2018年06月(６ヶ月)
- 担当業務
  - Scala × PlayFreameworkを使ったWebAPIアプリ開発
  - テックリードとして、現場社員の教育
  - システム全体の大規模なリファクタリング指針の策定＆改修作業実施
  - ドメイン駆動設計を用いたサービス全体の設計見直しの提案
- 役割
  - エンジニア（テックリード）
- チーム
  - 全体：３０人程度
- 習得スキル
  - Scalaを用いたシステムの再設計＆基盤作成ノウハウ
- コメント
  - Scala経験者があまりいないプロジェクトで、私が入った当初は継続的な開発に耐えるのが難しいシステム設計になっていたため、同じフリーランスのエンジニアとリファクタリングの提案を行い、大改修を実施した。
  - 要件がほとんど定まっていなかったログイン周りの機能を担当した際は、ユーザーストーリーの分析をもとにフローのたたき台を作成。決定権を持つステークホルダを集め、要件の策定を行った
  - 組織としてチーム開発のナレッジがなく、開発の改善フローが回せない状態だったためスクラムを提案し、デイリースクラムの実施などを提案・実行補助を行った。
- 開発環境
  - 言語: Scala
  - DB: PostgreSQL
  - FW・ライブラリ: PlayFreamework, ScalaTest(単体テスト)
  - サーバー: Docker(AWS)
  - その他: Github, CircleCI, Slack, IntelliJ IDEA

### Web広告運用における分析用データの収集システムの開発
期間: 2017年09月〜11月(３ヶ月)
- 担当業務
  - Djangoを使った分析用データの収集システムの基盤作成
  - FacebookやLINEなどのWeb広告運用データの収集・加工
  - 収集システムのバッチ化
  - Treasure Dataへのデータ投入・出力
  - TerraformとAnsibleを使ったインフラ(AWS)の環境整備＆自動化
- 役割
  - エンジニア
- チーム
  - 全体：５人程度
- 習得スキル
  - Treasure Data関連の知識
  - Djangoの関連の知識（特にORM）
  - Pythonを用いたデータ加工ノウハウ(特にPandas)
  - Terraformを用いたAWSのサーバ・ネットワーク構築の基礎知識
- コメント
  - チームにはWeb開発が未経験のエンジニアが多かったため、システムの基盤設計・構築、インフラ整備などを進めました
  - また、現場の技術力底上げのためにエンジニアメンバーに対してインフラ周りの技術教育を行いました
- 開発環境
  - 言語: Python
  - DB: MySQL, PostgreSQL
  - FW・ライブラリ: Django, Pandas(Python)
  - サーバー: CentOS7(AWS)
  - インフラ自動化: Terraform(AWS), Ansible
  - その他: TreasureData(Presto), Slack, IntelliJ IDEA

### 人材育成支援システム（Webサービス）
期間: 2016年10月 - 2017年09月(１年)
- 担当業務
  - ドメイン駆動設計を用いたサービス全体の要件定義・設計
  - Scala × PlayFreameworkを使ったWebAPIアプリ＆バッチアプリの開発
  - TypeScript × Angular2を使ったSPAアプリの設計・開発
  - SASSを使ったフロントエンドのデザイン全般
  - 新卒エンジニア戦力化のための教育・指導
  - Docker + Kubernetesを使ったGCPにおけるサーバ運用
  - TerraformとAnsibleを使ったインフラ(GCP)の環境運用
- 役割
  - エンジニア
- チーム
  - 全体：６人程度
- 習得スキル
  - ドメイン駆動設計とScalaを組み合わせた実装ノウハウ
  - TypeScript × Angular2を用いたサービス開発知識
  - Docker + Kubernetesに関するサービス運用知識
  - Terraform、Ansibleなどのサーバ構築自動化ノウハウ
- コメント
  - 仕様があいまいな状態でプロジェクトがスタートした案件だったので、ディレクターの方と密にコミュニケーションを取り、サービスイメージを要件に落とし込み、要件からドメインや仕様を定義していきました
  - フロントエンドの技術選定も担当し、少ないメンバーでもスピードと保守性を両立できるTypeScript × Angular2を採用することを決めました
  - チームが少人数だったこともあり、バックエンドからフロントエンド、インフラまですべての開発を担当しました
- 開発環境
  - 言語: Scala, TypeScript(JavaScript), Python
  - 設計: DDD（ドメイン駆動設計）
  - DB: MySQL
  - FW・ライブラリ
    - バックエンド: PlayFreamework, SkinnyORM, Spec2(単体テスト), Angular2
    - フロントエンド: Angular2, angular-cli, RxJS, Karma × Jasmine(単体テスト)
  - サーバー: CentOS7(GCP), Docker, Kubernetes
  - インフラ自動化: Terraform(GCP), Ansible, Fabric(Python)
  - その他: Mackerel(サーバ監視), Bamboo(CI/CDツール), Bitbucket(Git), Jira(チケット管理), Conference(ドキュメント管理), Slack, IntelliJ IDEA

--

## その他の過去に関わった開発案件

その他の過去に関わった開発案件と担当業務は下記の通りです

### Web広告運用ツール③（リプレイス）
期間: 2015年09月	-	2016年09月(13ヶ月間)
- ドメイン駆動設計を用いたサービス全体の要件定義・設計
- Scala × PlayFreameworkを使ったWebAPIアプリ開発
- Akkaを使ったバッチアプリの開発
- Riot.js × ES6を使ったSPAアプリの設計・開発
- フロントエンドの表示速度高速化
- SASSを使ったフロントエンドのデザイン修正
- React × Reduxを使った簡易的なアプリ開発
- 新卒エンジニアの教育・指導
- fluentd + ElasticSearch + Kibanaを用いたログ収集＆可視化

### Web広告運用ツール②
期間: 2015年01月	-	2015年09月(9ヶ月間)
- ドメイン駆動設計を用いたサービスの要件定義
- Scala × PlayFreameworkを使ったWebAPIアプリ開発
- AngularJS × TypeScriptを使ったSPAアプリの開発
- SASSを使ったフロントエンドのデザイン修正

### Web広告運用ツール①
期間: 2014年09月	-	2015年01月(5ヶ月間)
- Java × Seasar2(SAStruts)を使ったWebAPIアプリ開発
- AngularJSを使ったSPAアプリの開発

### Twitterのツイートをリアルタイムに検索サービス
期間: 2013年11月	-	2014年01月(3ヶ月間)
- 個人プロジェクトでのサービス開発
- 開発サービス：流ツイ（ http://ryutwi.yoppe.net/ )
- 要件定義から開発・デザインまでの全てを担当
- PHPのWebSocketサーバ(Ratchet)を使用したWebアプリケーション構築
- Twitterのツイートストリームを流しながらユーザーから非同期なリクエストに答えるため、ZeroMQを使用した非同期通信をPub/Subモデルで構築
- サービスのスマホ対応

### Twitterを利用した大学内SNSの開発
期間: 2012年06月	-	2013年01月(8ヶ月間)
- 学内ベンチャーの立ち上げを目的とした学内SNSのWebサービスの開発
- 要件定義から開発・デザインまでの全てを担当
- CakePHPを使用したWebアプリケーション構築
- TwitterAPIと連携し、WebSocketを使ったリアルタイムストリーミングによるツイート取得

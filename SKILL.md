## Language
- 業務経験あり
  - Ruby / Ruby on Rails
    - パフォーマンスチューニングが可能
  - Python
  - Elixir / Phoenix
  - Go
- 個人開発レベル
  - Unity / C#
    - 3Dモデルをリアルタイム動作させ、踊らせることが可能
  - Vue.js / Node.js / Perl

## Cloud Infrastructure

各サービスのメリットデメリットを把握しつつ、技術選定をすることが可能。

- 構成管理
    - CloudFormation / Terraform / Ansible / Chef
- AWS
    - EC2 / ECS (Fargate) / EKS / Lambda
    - RDS / ElastiCache / DynamoDB / EFS / S3
    - VPC / WAF / CloudFront / Route 53 / ACM / Traffic Mirroring
    - SSM / CloudWatch / SQS / SNS / CodeBuild / CodePipeline / Secrets Manager
    - AWS Config / GuardDuty / Trusted Advisor / Inspector / CloudTrail / IAM / CostExplorer
    - EC2 Image Builder / Systems Manager
- Google Cloud
    - Compute Engine / App Engine / Cloud Run / Cloud Functions
    - Cloud Storage / Cloud SQL / BigQuery / PubSub / Dataflow
    - Cloud Logging / Cloud Monitoring / Cloud Scheduler / Cloud Build
    - Security Command Center

## SRE
- キャパシティプランニング、プロビジョニング
- 可用性向上・負荷対策
- パフォーマンスチューニング
- 監視メトリクス設計・可観測性向上
- トイルの撲滅
- インシデント対応・トラブルシュート
- セキュリティ対策
- コスト管理・削減
- 負荷テスト
  - Jmeter / Locust / Gatling
  - 25000 rps の API負荷テストの仕組み構築が可能。

トラブルシュートの [参考ブログ](https://zenn.dev/e_koma/articles/20201218-adventcalendar-1a8e2ea4)

## Cloud Security
- AWS / GCPの全アカウントを横断したCSPM
  - 社内ポリシー違反したセキュリティ設定を自動検出し、セミリアルタイムに管理者に通知する仕組み
  - クラウドで用意されているマネージドサービスでは融通が効かない箇所を、組織のワークフローに沿って、柔軟にカスタマイズした現実的な運用を構築することが可能。

## OS
- Linux
    - 構成管理に加え、負荷対策のためのOSパラメータチューニングなどが可能
- Windows Server
    - 構成管理ツールを使い、レジストリ設定の自動化などが可能
    - Windows Serverのクラウドデスクトップ化

## DBMS
- スキーマ / index設計
- DB Administrator
  - 水平 or 垂直分割
  - バックアップ
  - Replication
  - Parameter Tuning
    - トランザクション分離レベルの判断
    - コネクションが上限まで使いそうな際の負荷対策チューニング
  - Caching
- 監視・パフォーマンス分析
- クエリ分析

## DevOps / Container Orchestration
継続的デプロイの設計・運用が可能

- Docker / Kubernetes
  - EKS クラスタ運用・管理
  - Karpenter による自動スケーリング
  - カナリアデプロイメント実装
  - マルチクラスタ運用
- Jenkins / Github Actions / CircleCI / Perforce

## API
- Rest APIの設計

## MiddleWare / SaaS
- Fluentd / fluent bit / Nginx / Memcached / Redis
- Datadog / NewRelic / Mackerel
- forseti

## Message Queue / Event Streaming
- AWS SQS による分散処理・排他制御
- Redis による分散ロック・キューイング
- 大規模システムでのメッセージング設計・実装

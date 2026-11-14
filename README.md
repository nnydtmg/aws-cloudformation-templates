# aws-cloudformation-templates
個人検証時のCloudFormation Template置き場


# コード説明
## 01.aws-vpc-nopublic
VPC内にプライベートサブネットを2つ作成する。パブリックサブネットは作成しない。

## 02.aws-vpc-nopublic-ec2
01テンプレートを基に、プライベートサブネットにEC2を一台構築する。
EICを使用したEC2へのログインと、パッケージインストール用のS3 Gateway Endpointを設定。

## 03.aws-vpc-public-private
VPC内にパブリックサブネットとプライベートサブネットを2つずつ構築する。



## セキュリティに関する注意

- 学習用のサンプルテンプレートです。本番で利用する場合は、セキュリティグループの許可範囲や IAM 権限を要件に合わせて見直してください。
- EC2 インスタンスは IMDSv2 を必須にしています。

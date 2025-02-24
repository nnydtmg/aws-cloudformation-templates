# aws-cloudformation-templates
個人検証時のCloudFormation Template置き場


# コード説明
## 01.aws-vpc-nopublic
VPC内にプライベートサブネットを2つ作成する。パブリックサブネットは作成しない。

## 02.aws-vpc-nopublic-ec2
01テンプレートを基に、プライベートサブネットにEC2を一台構築する。
EICを使用したEC2へのログインと、パッケージインストール用のS3 Gateway Endpointを設定。


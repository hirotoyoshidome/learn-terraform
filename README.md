# learn_terraform
## terraformのインストール
https://www.terraform.io/downloads.html

```
wget https://releases.hashicorp.com/terraform/0.11.13/terraform_0.11.13_linux_amd64.zip
unzip terraform_0.11.13_linux_amd64.zip
sudo mv terraform /usr/local/bin
rm -rf terraform_0.11.13_linux_amd64.zip
terraform --version
```

## AWSのリソースを管理する場合
* IAMユーザーの作成(アクセスキーとシークレットキーの生成)
* AWS CLIの設定（キーの設定）

## terraform
簡単な記載方法のみを記述

* 最初のみ初期化する

```
terraform init
```

* 定義内容をチェックする

```
terraform plan
```

* 実行する

```
terraform apply
```

* 変更の確認

```
terraform show
```

* terraformで定義したリソースをすべて削除する

```
terraform destroy
```


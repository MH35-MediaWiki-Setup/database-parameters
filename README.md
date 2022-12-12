# Database Parameters
RDSのパラメータグループ・オプショングループのレポジトリです

## 使い方

1. `aws cloudformation deploy --template-file formation.yml --stack-name [your stack name]`する
2. デプロイ完了まで待つ

## 作成されるもの

* utf8mb4の文字コードでAsia/Tokyoタイムゾーンを指定したMySQL 8.0用パラメータグループ
* 接続とクエリを監査ログに指定したオプショングループ

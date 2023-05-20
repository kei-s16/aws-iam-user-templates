# aws-iam-user-templates
## このリポジトリはなにか？
自分用のIAM設定集。  
アカウント作成直後にrootユーザでさくっと作る想定なのでCloudformationで定義する。  

## これはなにか？
### iam-user-groups.yaml
普段使いの開発用(POWER-USERS)と確認用(READ-ONLY-USERS)のグループを作成する。  
任意でAdministratorのグループも作成できる。  

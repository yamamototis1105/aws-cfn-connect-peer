## 概要
　本コードは、TGW Connect Attachmentを作成するCloud Formationテンプレートのサンプルです。<br/>
以下の通り、TGW Connect AttachmentでTGW～EC2(Catalyst 8000v)間を接続します。<br/>

![topology](https://github.com/yamamototis1105/aws-cfn-tgw-connect-peer/assets/114621183/4444a592-19b1-488d-b742-bfddc6fbc6b5)

## 利用方法
### スタック作成時
1. CloudFormation > スタックへアクセスし、スタックの作成ボタンを選択してください。
1. 「tgw-connect-attachment.json」をアップロードし、次へボタンを押下してください。
1. スタック名は任意の名称、スタックパラメータは「Catalyst 8000vのAMI ID)」を入力し、次へボタンを押下してください。
1. スタックオプションはデフォルトのままで、次へボタンを押下してください。
1. 送信ボタンを押下してください。
<br/>

### スタック削除時
1. VPC > Transit Gatewayへアクセスし、Connectアタッチメント > Connectピアを選択のうえ削除ボタンを押下してください。
1. Connectアタッチメントを選択のうえ削除ボタンを押下してください。
1. CloudFormation > スタックへアクセスし、スタックを選択のうえ削除ボタンを押下してください。<br/>
1. 1度目は失敗で終了しますので、2度目は削除失敗リソースをスキップのうえ削除ボタンを押下してください。
1. 2度目も失敗で終了しますので、3度目も削除失敗リソースをスキップのうえ削除ボタンを押下してください。

## 関連技術
<img src="https://img.shields.io/badge/AWS-Cloud_Formation-blue"></img>

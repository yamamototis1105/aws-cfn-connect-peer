## 概要
　本コードは、TGW Connect Attachmentを作成するCloud Formationテンプレートのサンプルです。<br/>
以下の通り、TGW Connect AttachmentでTGW～EC2(Catalyst 8000v)間を接続します。<br/>

![topology](https://github.com/yamamototis1105/aws-cfn-tgw-connect-peer/assets/114621183/4444a592-19b1-488d-b742-bfddc6fbc6b5)

## 利用方法
* スタック作成時
  * Cloud Formationへアクセスし、「tgw-connect-attachment.json」をアップロードしてください。
  * スタックパラメータとして、EC2(Catalyst 8000v)のAMI IDを入力してください。
  * スタックオプションはデフォルトのままで、確認のうえ送信ボタンを押下してください。
<br/>

* スタック削除時
  * VPCへアクセスし、TGW Connect Peerを手動で削除してください。
  * TGW Connect Attachmentを手動で削除してください。
  * Cloud Formationへアクセスし、スタックを選択のうえ削除ボタンを押下してください。

## 関連技術
<img src="https://img.shields.io/badge/AWS-Cloud_Formation-blue"></img>

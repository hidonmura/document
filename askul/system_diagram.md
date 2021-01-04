# askulAlert phase1
アラートメールを受信しDBに保存管理する
 
# DEMO
![AWS](https://github.com/hidonmura/autoCaller/blob/main/AWS-7-4.png)
 
# Features
- アラートメール受信をトリガーにオペレータが手動で電話連絡するフローの自動化を実現
- 受信したアラートメールの件名および本文を参照し内容に応じて連絡先を自動で選択するフィルタリング機能も実装
 
# Requirement
 
* Python 3.8
* AWS
  * Lambda
  * Route53
  * SES
  * S3
  * EC2
  * RDS
  * RDS Proxy
 
# Installation
工事中
 
# Usage
1. srcへ移動
```
$ cd src
```
2. zip化
```
$ zip -r call.zip .
```
3. Lambdaの関数コード→コードエントリータイプからzipファイルをアップロード
# Note

 
# Author
 
* 作成者
Takuya

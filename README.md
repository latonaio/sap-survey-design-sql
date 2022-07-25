# sap-survey-design-sql  
sap-survey-design-sqlは、主にエッジアプリケーションにおいて、SAPと連携された調査設計データを保存するSQLテーブルを作成するためのレポジトリです。  
sap-survey-design-sqlは、そのままクラウド環境におけるアプリケーションにも、適用可能です。

## 前提条件  
sap-partner-sql は、SQL の SAP とのデータ連携にあたり、オンプレミス版である（＝クラウド版ではない）SAPC4HANA API の利用を前提としています。  
クラウド版APIを利用する場合は、ご注意ください。  
https://api.sap.com/api/surveydesign/overview    
本レポジトリ の sql設定ファイルの内容は、上記URL の API 仕様を前提としています。 

## sqlの設定ファイル
sap-survey-design-sqlには、sqlの設定ファイルとして以下のsqlファイルが含まれています。  

* sap-survey-root-collection-data.sql (調査設計データ)

## MySQLのセットアップ / Kubernetesの設定 / SQLテーブルの作成方法
MySQLのセットアップ / Kubernetesの設定 / 具体的なSQLテーブルの作成方法、については、[mysql-kube](https://github.com/latonaio/mysql-kube)を参照ください。
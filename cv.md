# 業務経歴書

## 基本情報

|key|value|
|-|-|
|性別|男性|
|国籍|日本|
|住所|大阪府 大阪市|
|IT資格|基本情報技術者/応用情報技術者/データベーススペシャリスト|
|英語資格|TOEIC700点|
|その他資格|歴史能力検定 世界史2級|
|最終学歴|大阪府立大学 人間社会学部 人間科学科 卒業|
|情報収集|はてなブックマークのテクノロジーカテゴリ、Qiita、Menthas、TechFeed、その他技術ブログやnote|
|その他|[雑食系エンジニアサロン](https://kentakatsumata.net/archives/10)会員、[エンジニアと人生サロン](https://community.camp-fire.jp/projects/view/280040)会員|

## 勤務条件
|key|value|
|-|-|
|参画開始可能日|-|
|参画可能地域|大阪府内（できれば大阪市内）|
|休日出勤可否|可能|
|残業可否|月40h以内|
|出張可否|可能|

## 自己紹介

- これまでは主にMicrosoft系の開発業務を行ってきました。フェーズとしては基本設計～リリースまで経験しています。また、サーバサイド・フロントエンドに加えてインフラ的なこともやってきたので、対応可能範囲は広い方かと思います。
- プライベートではMacを使用しており、近年Windows、.Net環境での開発を離れたい気持ちが高まっています。そのため、ポートフォリオはPythonで開発しています。またネットワークやセキュリティにも興味があるため、AWSを活用して書籍とハンズオンを行ったり来たりしながら学んでいるところです。
- 開発方針として、  
①無駄なコードを書かないこと  
②チームメンバーの作業量を少なくすること  
③ユーザーが使いやすくなること  
を常に意識するようにしています。  
- 基本的に「郷に入っては郷に従え」という考え方を持っており、まずは合わせるタイプです。
- スピード重視の開発よりは、難易度の高い開発で試行錯誤する方が好みです。

## スキル

- 実務で使用した技術のみ記載しています。

### OS

Windows10 | Windows8.1 | Windows7

### 言語

TypeScript | JavaScript | PowerShell | C# | VB.NET | VBA

### フレームワーク等

Node.js | React | Xamarin | UWP | ASP.NET MVC | ASP.NET | WPF | .NET | MvvmCross | jQuery | SPFX（Microsoft SharePointをカスタマイズするためのフレームワーク）

### データベース

MySQL（Amazon RDS） | SQLServer2017 | SQLServer2014 | Access2007 | Oracle 11g | HiRDB | SQLite

### クラウド

#### AWS

Amazon API Gateway | Amazon RDS | Amazon Cognito | AWS Lambda | Amazon S3 | AWS Elemental MediaConvert

#### Azure

App Service/Azure SQL Database/Azure Active Directory

### その他

npm | GitHub | Tomcat | Gulp | Webpack | CSS | SCSS | HTML | SQL | XML | JSON | Microsoft SharePoint Online | IIS | XAML | Postman | Redmine | Kintone | Visual Studio | Eclipse | Active Directory | MySQL Work bench | DB browser for SQLite

## 業務経歴

### 簡易な教育系動画配信サービス開発（2020年）

《開発タイプ》  
完全新規開発

《業務内容》  
フロントエンドエンジニアとして基本設計〜結合試験まで担当

《チーム人数》  
3名

《コメント》  
教育系の会社様向けに開発したセミナー動画の配信サービス。もともとかなり余裕を持った見積りだったこともあると思うが、想定開発期間2.5ヶ月に対して実際の開発期間は1ヶ月だった。

#### 使用技術など  
| key  | value |
| ---- | ----- |
|言語|JavaScript|
|パッケージマネージャ|npm|
|ビルドツール|Webpack|
|データベース|未使用　※Amazon S3で代用|
|クラウド|AWS（Amazon Cognito/AWS Lambda/Amazon S3）|
<br> 

### 機器の点検を行うUWPアプリ開発（2019年〜2020年）

《開発タイプ》  
完全新規開発

《担当業務》  
UWPアプリエンジニアとして主にビジネスロジックを担当。基本設計〜受け入れ試験まで行った。

《チーム人数》  
6名

《コメント》  
現場に現役のWindows系エンジニアが自分一人、かつUWP未経験、かつモバイルアプリ未経験という状態で基本設計から参画した。バックグラウンドでのビーコン検知などチャレンジングな仕様もありかなり苦労したが、なんとか完成まで漕ぎ着けることができた。また、本案件は「今回開発するのはUWPアプリのみだが、今後AndroidやiPhoneアプリにも展開しやすいようXamarinを選択した」という経緯があった。そのため、展開できるかどうかを調査するためのサンプル実装などを通して、AndroidやiPhoneアプリについての知見も多少得ることができた。

#### 使用技術など  
| key  | value |
| ---- | ----- |
|OS|Windows10|
|言語|C#/Xaml/PowerShell|
|フレームワーク|Xamarin Native/MvvmCross|
|パッケージマネージャ|NuGet|
|データベース|SQLite/MySQL（Amazon RDS）|
|テーブル数|20|
|クラウド|AWS（Amazon API Gateway/Amazon Cognito/AWS Lambda/Amazon RDS/Amazon S3）|
|テストフレームワーク|MSTest|
|ツール|MySQL Work bench/Redmine/mitmproxy/Postman|
|その他|sqlite-net-pcl|



### ActiveDirectoryを用いたグローバルアドレス帳（2019年）

《開発タイプ》  
機能追加

《業務内容》  
バックエンド/インフラを担当し、主に下記業務を行った。  
①社員情報/組織情報/グループ情報について、取得/作成/更新/削除を行うREST APIを追加。  
②取得処理については経験の浅いメンバーに任せ、そのサポートを行った。  
③別案件のメンバーのサポートも並行して行った。

《コメント》  
経験の浅いメンバーとの開発にあたっては、席が離れており気軽に質問し辛いことを考慮し、なるべくこちらから詰まっている箇所や疑問点はないかなど確認するように努めた。（ある程度自走力のある方だったため多すぎない程度に）特に、業務終了時には極力確認を入れるようにした

《チーム人数》  
3名

#### 使用技術など  
| key  | value |
| ---- | ----- |
|OS|Windows10|
|言語|C#/TypeScript/PowerShell|
|フレームワーク|ASP.NET MVC|
|パッケージマネージャ|NuGet|
|データベース|SQL Server（Azure SQL Database）|
|テーブル数|4|
|クラウド|Azure（App Service/Azure SQL Database/Azure Active Directory）|
|ツール|Postman/SQL Server Management Studio|
|その他|IIS/Knockout.js|



### IT資産管理システム（パッケージソフト）（2018年〜2019年）

《開発タイプ》  
リプレース、および機能追加

《業務内容》  
フロントエンド/バックエンド/インフラを横断的に担当し、上位バージョンへのリプレースを実施

《コメント》  
リプレースと同時に機能追加を行ったことや、対応ブラウザが増えたことなどもあり、非常に修正箇所が多かった。また、仕様が曖昧な部分が多かったため、頻繁にメンバー間で確認を取りながら進めた。

《チーム人数》  
5名

#### 使用技術など  
| key  | value |
| ---- | ----- |
|OS|Windows10|
|言語|C#/JavaScript|
|フレームワーク|ASP.NET|
|パッケージマネージャ|NuGet|
|データベース|SQLServer2017|
|テーブル数|200|
|ツール|SQL Server Management Studio|
|その他|IIS/Hyper-V|



### SharePointOnlineのカスタマイズ（SPFXを使用）（2018年）

《開発タイプ》
完全新規開発のヘルプ

《業務内容》
SPFXを用いたSharePointOnlineのカスタマイズを実施。主にブラウザ互換対応を行った
※この時、グローバルアドレス帳のテーブルを１つ追加

《コメント》
ヘルプとして参画したため、メイン開発者（1名）の方にコードの意図などを確認しながら、既存のソースをなるべく変えず最小限の修正を行うよう意識した。

《チーム人数》
4名

TypeScriptWindows10Node.jsJavaScriptSPOのリストをテーブルとして使用SPFXSharePointOnlineReact.jsテーブル数クラウドSQL Server Management Studio 3Azure（App Service/Azure SQL Database/Azure Active Directory）npm

### IT資産管理システム（パッケージソフト）（2018年）

《開発タイプ》
機能追加

《業務内容》
Excelを用いて自由に申請書を作成、および申請、登録できる機能の開発

《コメント》
複雑な機能だったので、稼働は高めであった。お客様先に同行して機能説明なども行った。

《チーム人数》
2名

C#Windows10ASP.NETJavaScriptSQLServer2014IISNPOIHyper-VSQL Server Management Studio テーブル数Nuget200

### ActiveDirectory移行ツール（2018年）

《開発タイプ》
完全新規開発

《業務内容》
①ObjectSidHistoryの移行ツール（既存ツールを併用）の開発
②ScriptPathの移行ツールの開発

《コメント》
お客様先に同行して機能説明なども行った。

《チーム人数》
3名

PowerShellWindows10Hyper-V

### ActiveDirectoryを活用したグローバルアドレス帳（2018年）

《開発タイプ》
別システムを流用した新規開発

《処理の流れ》
ActiveDirectoryから社員情報を取得
↓
DBに格納
↓
グローバルアドレス帳の画面からDBのデータを取得、更新

《コメント》
お客様先で機能説明なども行った。

《チーム人数》
3名

C#Windows10ASP.NET MVCTypeScriptAzure SQL DatabaseIISPowerShellSQL Server Management Studio [Knockout.js](http://Knockout.js)Nugetテーブル数クラウド3Azure（App Service/Azure SQL Database/Azure Active Directory）

### SharePointOnlineのカスタマイズ（JSLinkを使用）（2017年〜2018年）

《開発タイプ》
機能追加

《業務内容》
SharePointOnline上のワークフローシステムに対する、PowerShellを用いたメール送信機能の開発

《チーム人数》
2名

PowerShellWindows10SharePointOnlineJavaScriptJSLink

### IT資産管理システム（パッケージソフト）（2017年）

《開発タイプ》
機能追加

《業務内容》
①SharePointOnlineのサイト構築申請機能の開発
②Office365ライセンス管理機能の開発

《コメント》
お客様先に同行して機能説明なども行った。

《チーム人数》
2名

C#Windows10ASP.NETJavaScriptSQLServer2014IISHyper-VSQL Server Management Studio テーブル数Nuget200

### SharePointOnlineのカスタマイズ（JSLinkを使用）（2017年）

《開発タイプ》
機能追加

《業務内容》
PowerShellを用いたlistアイテムのステータス更新機能開発

《コメント》
お客様先に同行して機能説明なども行った。

《チーム人数》
2名

PowerShellWindows10SharePointOnlineJavaScriptJSLink

### 薬局向け調剤システム（パッケージソフト）（2016年〜2017年）

《開発タイプ》
機能追加、およびバグ改修

《業務内容》
薬局の請求情報や来局者の服薬情報などを管理するシステムについて、新機能追加やバグ改修などを実施

《チーム人数》
15名程度

VB.netWindows10.NETSQLServer2014WPFXAMLWCFSQL Server Management Studio Redmineテーブル数kintone100VMware

### 利子補給システム（2016年）

《開発タイプ》
資料作成

《業務内容》
自身の退職にあたり、次の担当者に向けて引き継ぎ資料を作成

《チーム人数》
1名

VB.netWindows7.NETAccess2007SQL Server Management Studio SQLServer2014テーブル数20

### レセプト電算処理システム（2016年）

《開発タイプ》
機能追加

《業務内容》
レセプトを審査する機能のうち、原審査機能の改修に係る内部設計を実施

《チーム人数》
100名程度

VB.netWindows8.1.NETOracle 11gテーブル数300

### 利子補給システム（2015年〜2016年）

《開発タイプ》
機能追加

《業務内容》
自治体の利子補給制度を管理するシステムの改修について、詳細設計以降、SQLServer導入、運用保守を担当

《コメント》
お客様先に同行して機能説明なども行った。

《チーム人数》
3名

VB.netWindows7.NETAccess2007SQL Server Management Studio SQLServer2014テーブル数20

### レセプト電算処理システム（2015年）

《開発タイプ》
機能追加

《業務内容》
レセプトを審査する機能のうち、原審査機能の改修に係る製造・単体テストを実施

《チーム人数》
100名程度

VB.netWindows7.NETOracle 11gテーブル数300

### 医療事務電算処理システム（2015年）

《開発タイプ》
テスト

《業務内容》
Windows7から8.1へのマイグレーションにおける結合テストを実施

《チーム人数》
100名程度

VB.netWindows7.NETOracle 11gテーブル数300

### レセプト電算処理システム（2015年）

《開発タイプ》
テスト

《業務内容》
レセプト（医療機関が保険者に患者の保険診療費を請求する際の診療報酬明細書）を審査する機能のうち、再審査機能ついて改修後の結合テストを実施

《チーム人数》
100名程度

VB.netWindows7.NETOracle 11gテーブル数300

### 医療事務電算処理システム（2015年）

《開発タイプ》
調査

《業務内容》
新元号開始時に対応できるよう改修を行うにあたり、改修前の調査分析を実施

《チーム人数》
100名程度

VB.netWindows7.NETOracle 11gテーブル数300

### 国民健康保険システム（2014年）

《開発タイプ》
調査、およびテスト

《業務内容》
被保険者への給付金支払い機能について、調査および結合テストを実施

《コメント》
業務の中で高額療養費制度について詳しくなり、リーダーの方にその点を買っていただいていたと思う。また、テストについて細かい部分まで見てくれるということでよく頼まれた。

《チーム人数》
100名程度

JavaWindows7TomcatHiRDBA5:SQL Mk-2テーブル数300

### 利子補給システム（2013年）

《開発タイプ》
完全新規開発

《業務内容》
自治体の利子補給制度を管理するシステムについて、製造・単体テストを実施

《チーム人数》
6名程度

VB.netWindows7.NETAccess2007テーブル数20
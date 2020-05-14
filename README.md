# 日本マイクロソフト 社内緊急コミュニケーション CDSを使用したPower Appsソリューションテンプレート
(Crises Communication for CDS environment)

## はじめに

**
アプリケーション概要

社内緊急コミュニケーションは世界的なCOVID-19蔓延に際し、オフィスでの密な業務連携が難しくなった2020年3月に米国Microsoft Corporation で問題を解決するために作成されたサンプルテンプレートです。3月に初期バージョンが2日間で作成され、その後デザイン改良が施されたVersion2が提供されています。
これらのアプリケーションはデータ保存場所としてSharePoint Onlineを使用するよう設計されました。しかし、COVID-19が長期にわたってビジネスに影響を及ぼすことが予想されるため、既存のアプリケーションの機能をそのまま踏襲し、データ保存場所として長期にわたって安定して利用できる「Common Data Service」を利用可能としたソリューションとして変更を施し、日本市場のお客様に提供することとなりました。
本バージョンでは、利用に際しCommon Data Serviceのライセンスを必要とし、Power Appsキャンバスアプリケーションとモデル駆動型アプリケーションを使用します。

## 構成内容
本テンプレートは次の要素で構成されています
 1. CDSに展開するソリューション（マネージド・アンマネージド）
 2. 社内緊急コミュニケーション管理用 モデル駆動型アプリケーション
 3. エンドユーザー利用Power Appsキャンバスアプリケーション
 4. （サンプル）Power BIテンプレート
 5. 管理者向け展開ガイド
 6. エンドユーザー向け利用者ガイド

## 展開・利用に必要な条件
本テンプレートを展開・利用するには有償のPower Appsライセンスが必要です。詳しくは下記をご参照いただくか、日本マイクロソフト担当者までお問い合わせください。
[https://powerapps.microsoft.com/ja-jp/pricing/](https://powerapps.microsoft.com/ja-jp/pricing/)

## 準備されている言語
本テンプレートは日本語で準備されており、追加で以下の言語に対応します

 - 日本語 (Japanese)
 - 英語 (English)

## 主な機能
緊急時に企業が従業員に対して必要な情報を提供できるよう、「情報発信」「情報閲覧」を中心に、以下の代表的な機能があります。

 - 管理者が共有した会社のニュース・世界のニュース・便利な情報・よくある質問・リンク集・緊急連絡先の参照
 - 業務状況と業務場所の共有
 - 共有内容の自動メール送信
 - 業務開始、途中退出、業務終了レポートの作成と送信
 - 日報レポートの作成と送信（フリーフォーマット）
![モデル駆動型アプリ](https://infosharefl.blob.core.windows.net/%24web/webimages/ModelDrivenSample.jpg?sv=2019-10-10&ss=bqtf&srt=sco&sp=rwdlacuptfx&se=2020-05-01T12:58:34Z&sig=RibYdcYyy96xvfmqUGk%2Bu6tv52pgoXLbSxjZsRuRuZU%3D&_=1588309419808)

![キャンバスアプリ](https://infosharefl.blob.core.windows.net/%24web/webimages/CanvasAppSample.jpg?sv=2019-10-10&ss=bqtf&srt=sco&sp=rwdlacuptfx&se=2020-05-01T13:04:47Z&sig=wY12ZeB3Fyp9eLgjy5xY90%2BqFSw8lznBXNt2Mfx5rmw%3D&_=1588309499090)


## 展開方法
パッケージに含まれている管理者向け展開ガイドを参照してください

## マネージドソリューションとアンマネージドソリューション
2種類のソリューションを用意しています。インストールにはマネージドソリューションを使用することをおすすめします。アンマネージドは開発環境への展開や、追加の開発・カスタマイズを実施する環境で展開してください。詳しくは管理者向けのドキュメントを参照してください。

## FAQ

 - Q.自社向けに、内容や機能をカスタマイズすることは可能ですか？
	 - A.可能です。カスタマイズすることを前提にシンプルで汎用的な作りになっています
 
 - Q.展開パートナーはどのように見つけることができますか？
	 - A.日本マイクロソフト担当者までお問い合わせください




　　　　　　　　　　 
 





**免責事項**

本テンプレートはサンプルであり、Microsoft Power Appsにおいて、参考情報の提供や、個人と企業のコミュニケーションを促進する目的でのみ使用することができます。本テンプートおよび関連サービスは、恒久的なアプリケーション使用を意図したものではありません。インフォシェア株式会社、また日本マイクロソフトはそのような目的で本テンプレートおよび関連サービスを使用するライセンスや権利を本テンプレート利用組織に付与していません。
本テンプレートおよび関連サービスは、各企業のニーズを全て含めるように設計されたものではなく、そのような用途で使用されるものではありません。実際の利用や必要な追加のカスタマイズは導入支援パートナーに確認・依頼してください。
本テンプレートおよび関連サービスのいかなる使用においても、利用者がすべてリスクと責任を負うものとします。また、実装した本テンプレートおよび関連マイクロソフト サービスの使用に関して、適切な警告や情報をエンドユーザーに提供することについても、利用者が責任を負うものとします。
本テンプレートは、日本国内での使用のみを目的とし、欠陥などがある可能性を含んだままの状態で提供されており、いかなる種類の保証も適用されません。

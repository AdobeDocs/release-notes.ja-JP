---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: リリースノート
last-update: 2019 年 5 月
author: mfrei
translation-type: tm+mt
source-git-commit: 79b40383300bb2b48fe916caeaade87c8a8ba5d4

---


# Adobe Experience Cloud リリースノート

Adobe Experience Cloud の新機能および修正点です。

>[!NOTE]
>>[Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。通知はリリースの 3～5 営業日前に届きます。リリース後に発表された新情報には、更新の日付が明記されます。


**リリース日:2019年5月**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard／Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platformリリースノート

バージョン1.0、2019年5月16日

* エクスペリエンスプラットフォームの最新の更新については、Adobe. ioの [Experience Platformリリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) を参照してください。

### Experience Platform Launch

* 最新の情報については [、エクスペリエンスプラットフォームの起動](https://docs.adobelaunch.com/) を参照してください。

### Experience Cloud ID サービス

リリース日：**2019 年 5 月 14 日**

* バージョン 4.3.0 をリリースしました。
* ITP 2.1 をサポートする ECID ライブラリを追加しました。
* secureCookie の設定に関する問題を修正しました。

## Analytics {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analyticsの新機能および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)

製品ドキュメントについては、[Analytics ヘルプホーム](https://marketing.adobe.com/resources/help/en_US/reference/)を参照してください。

### Adobe Analyticsの新機能および修正点 {#aa-features}

| 機能 | 説明 |
| -----------| ---------- |  
| [!DNL AppMeasurement Version 2.14.0] <ul><li>複数のヒットが保留中の場合に、トラッカーパラメーターの状態の管理に関する問題を修正しました。（AN-176931、AN-176629、DTM-12758）</li><li>AppMeasurementが更新され、Visitor. js4.3.0が含まれるようになりました。（AN-180049）</li></ul> |
| [!DNL Analysis Workspace]: 新しい「_繰り返しインスタンスを含める_」フロービジュアライゼーション設定 | 「_繰り返しインスタンスを含める_」フロー設定で、繰り返しインスタンス（ページのリロードなど）を含めるか除外するかを指定できます。また、「すべてのフロー」ビジュアライゼーションはインスタンスのみに基づくようになりました。 |
| [!DNL Ad Hoc Analysis]: Java 11 との互換性 | Ad Hoc Analysis は、Java 11 をサポートするようになりました。Java11でAd Hoc Analysisを実行 [する方法について](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html)説明します。 |
| **データ収集:** 新しいs_ ecid cookie | CNAMEを設定している場合、データ収集サーバーが訪問者の ECID を格納するファーストパーティのサーバー cookie（s_ecid）をセットするようになりました。 |

**Analysis Workspace の修正点**

* ページでの滞在時間に影響 **[!UICONTROL する問題を修正]** しました。[!DNL Analysis Workspace] レポートでは、滞在時間を計算する際、ページ名を利用しないことで、精度を改善しました。**[!UICONTROL ]****[!UICONTROL ]**（AN-140479）
* パフォーマンスを向上 [!DNL Analysis Workspace] させるために、行のビジュアライゼーションのパフォーマンスの問題を修正しました。（AN-174878）
* ダウンロードされた .csv ファイルに UTF-8 エンコードが適用されない問題を修正しました。（AN-178393）
* プロジェクトのパフォーマンスが低下 [!DNL Analysis Workspace] する問題を修正しました。（AN-177710）
* y 軸の精度に小さい範囲で表示される折れ線グラフのビジュアライゼーションの問題を修正しました。（AN-176467）

**Analytics のその他の修正**

* [!DNL Audience Analytics]:オーディエンス名が変更さ [!DNL Audience Manager (AAM)] れた後に発生していた問題を修正しました。（AN-176237）
* ユーザーが[!DIL [!DNL Audience Manager]Analyticsセグメントを参照してください。この問題は、既存の AAM フォルダーに大文字の名前と小文字の名前が混在していたことによって発生していました。すべてのフォルダーで大文字と小文字が区別しないようにすることで、これらが同期されるようになりました。（AN-177934）
* ユーザーがログ [!DNL Analytics][!DNL Experience Cloud] インしてセッションがタイムアウトすると発生していた問題を修正しました。セッションを再開すると、ユーザーは誤った URL にリダイレクトされていました。（AN-176812）
* リクエストの [!DNL Data Warehouse] タイムゾーンのオフセットの問題を修正しました。（AN-177585）

### Analytics 管理者向けの重要な注意事項{#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| **[!UICONTROL 日付対応]** および **[!UICONTROL 数値2分類に関する今後のサポートの変更]** | 2019 年 5 月 28 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。この変更は、2019年7月のメンテナンスリリースで有効になります。「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。<br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポートの合計_の計算に対して予定されている変更 | 2019 年 5 月 2 日更新 | **2019 年 6 月 14 日** に、_レポートの合計_値の算出方法をすべてのディメンションおよび指標で共通化します。これにより、一部のレポート（通常、Prop または顧客属性レポート）の合計が変更されます。この変更以前は、レポートに_未指定_が表示されているかどうかにかかわらず、合計に_未指定_の行項目を含めるレポートと含めないレポートが混在していました。<br/>2019 年 6 月 14 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。また、この変更によって、「_存在する_」または「_存在しない_」ロジックを使用しているセグメントでは、一部のディメンションで異なる結果が表示される場合があります。この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| CSVダウンロードの更新 [!DNL Analysis Workspace] | 2019 年 4 月 10 日 | 2019年4月11日から **[!UICONTROL 、CSVダウンロード]** （およびクリップボードに **[!UICONTORL コピー]**）から、エクスポートされたデータからフォーマットを [!DNL Analysis Workspace] 削除するいくつかの変更が行われました。  <ul><li>千単位区切り文字は含まれなくなりました。小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]** で定義された形式が適用されます。注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。パーセンテージは 10 進形式になります。例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| [!DNL Analysis Workspace] 今後のデバッガーコマンドの変更 | 2019 年 4 月 4 日 | [!DNL Analysis Workspace] デバッガーをオンにするコンソールコマンドが、2019年6月13日に **AdobeTool. debug. includeoberOnXmlに変更されて** います。この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 7 日 | 2019 年 1 月 8 日より、モバイルブラウザーバージョン番号を 3 桁から 2 桁に変更しました。この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| 提供終了 [!DNL Ad Hoc Analysis] | 2019 年 1 月 29 日 | 2018年8月6日に、アドビは提供終了の意図を発表 [!DNL Ad Hoc Analysis]しました。サポート終了日については確定次第お知らせします。<br/>サポート終了の予定や詳細については [Discover Workspace](https://adobe.ly/discoverworkspace) を参照してください。 |
| Analytics レポートリンク | 2019 年 1 月 14 日 | 2019 年 1 月 17 日（木）以降、定期的なスケジュールで、直近 1 年間に訪問されていない短い Analytics レポートリンクは、削除されるようになります。 |
| TLS 1.0 のサポート終了 | 2019 年 1 月 10 日更新 | 2019 年 2 月 12 日現在、Adobe Analytics レポートで TLS（Transport Layer Security）1.0 の暗号化がサポートされなくなっています。この変更は、最高レベルのセキュリティ基準を維持して、お客様のデータの安全を確保するための継続的な取り組みの一環です。2019年2月11日以降にAdobe Analyticsレポートに接続できない場合は、ブラウザーを [最新バージョンにアップグレードする必要](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)があります。<br/>2019 年 2 月 21 日以降、Adobe Analytics のデータ収集で TLS 1.0 がサポートされなくなりました。この変更により、TLS 1.1 以上をサポートしていない旧型のデバイスや Web ブラウザーを使用しているエンドユーザーの Analytics データは収集されなくなりました。この変更が、お客様の顧客のデータやレポートに大きな影響を及ぼすことはないと認識しています。（お客様の Web サイトが既に TLS 1.0 をサポートしていない場合、影響は一切ありません。）<br/>2019 年 4 月 12 日以降、Adobe Analytics レポート API は TLS 1.0 の暗号化をサポートしていません。API にアクセスするお客様は、この変更による影響の有無を確認してください。 <ul><li>デフォルト設定で Java 7 を使用している API クライアントは、[TLS 1.2](https://www.java.com/en/configure_crypto.html) をサポートするように変更してください（「_Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2_」を参照、ブラウザーの翻訳機能をお使いください）。 </li><li>デフォルト設定はTLS1.2であるため、Java8を使用するAPIクライアントは影響を受けません。</li><li> その他のフレームワークを使用している API クライアントは、TLS 1.2 のサポートについてベンダーにお問い合わせください。</li></ul> |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 9 日 | 2019 年 2 月 8 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。この変更により、処理中にpost_ product_ listに追加されるマーチャンダイジングeVarの値が製品と売上の値の切り捨てにならないようにします。post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 MB に達した時点で値を切り捨てるようにしてください。 |
| 非アクティブ [!DNL Analytics Live Stream] なエンドポイントに影響を与える管理の変更 | 2018 年 12 月 20 日 | 2019年2月1日以降、アクティブなコンシューマー接続のない [!DNL Live Stream] エンドポイントは無効になることがあります。カスタマーケアに連絡して [!DNL Live Stream] エンドポイントについて問い合わせ、必要に応じて、再度有効にすることができます。また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 7 日 | TLS1.0のサポート終了により、 [!DNL Report Builder] バージョンv5.6.21を2019年2月より前にダウンロードすることをお勧めします。その後、以前のバージョンは [!DNL Report Builder] 機能しなくなります。 |

## Audience Manager {#aam}

| 機能 | 説明 |
| -----------| ---------- |  
| [IPアドレスの難読化](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | 世界液なプライバシー規制のトレンドを受け、多くの国で IP アドレスの難読化が求められるようになってきました。Audience Manager を使用すると、訪問者の IP アドレス全体または国ごとに難読化できます。 |
| [カスタムパートナーの統合 - Oracle Data Cloud](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | このページには、Audience Manager とデータパートナー間のカスタム統合の一覧が掲載されています。Audience Manager は、受信データファイルを使用して、Oracle Data Cloud for Audience Marketplace から cookie とモバイル ID データを取り込みます。このページで説明するカスタム統合仕様は、モバイル ID（IDFA および Android デバイスID）を含む受信データファイルのみを対象としています。 |

**修正点、機能強化および廃止された機能**

* 宛先の一般レポートに 2 つの新しい列を追加しました。宛先へのセグメントマッピングに開始日と終了日が表示されるようになりました。（AAM-44781）

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

**AEM 6.5**

AEM 6.5（2019 年 4 月 8 日から利用可能）は、AEM 6.4 コードベースに対するアップグレードリリースです。AEM 6.5 への最新のアップデートでは、お客様のビジネスをさらに加速させる優れた機能が利用可能になりました。

* [Adobe Experience Manager 6.5 の新機能](https://www.adobe.com/marketing/experience-manager/new.html)
* [Adobe Experience Manager 6.5 リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

最新の Cloud Manager リリース（2019.4.0。リリース日：2019 年 4 月 19 日）には、フランス語、ドイツ語、および日本語にローカライズされたユーザーインターフェイスが加わりました。また、デプロイメント手順が改善されました。

* [Cloud Manager 2019.4.0 のリリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 製品メンテナンス

**AEM 6.4.4.0**

2019 年 4 月 5 日にリリースされた AEM 6.4 Service Pack 4（6.4.4.0）は重要なアップデートであり、2018 年 4 月の AEM 6.4 の一般リリース以降にリリースされたお客様向けの主要な修正が含まれています。

[AEM 6.4 Service Pack のリリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[AEM Forms リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM S3 Connector**

2019 年 6 月 24 日に署名バージョン 2 のサポートが終了された後、古いバージョンの S3 Datastore コネクタを使用する AEM インスタンスがS3 アクセスエラーによって利用できなくなることがあります。AEM のお客様は、お使いの S3 Datastore コネクタのバージョンを確認することをお勧めします。必要に応じて、最新バージョンに更新します。

「[Amazon S3 における AWS 署名バージョン 2 の廃止による影響](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)」を参照してください。

### セルフサービス

**AEM Sites コードベースの最新化**

最新のAEMテクノロジーを活用してAEMサイトのコードベースを最新化する方法について説明します。 [既存のAdobe Experience Manager Sitesコードベースの最新化](https://expleague.azureedge.net/labs/L761/index.html)

**AEM リッチテキストエディター – 詳細**

リッチテキストエディターのベストプラクティスと AEM でのリッチテキストエディターの使用について学習します。

「[AEM Rich Text Editor（RTE）の詳細](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)」を参照してください。

### その他のリソース

* [AEM 6.5 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Campaign {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

* Campaign Classic18.10.4-ビルド8983
* Campaign Classic18.10.5-ビルド8984

修正点と機能改善については、[Adobe Campaign Classic リリースノート](http://docs.campaign.adobe.com/doc/AC/en/RN.html)を参照してください。

製品ドキュメントについては、以下を参照してください。

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 機能のビデオ](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 機能のビデオ](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| 機能 | 説明 |
| -----------| ---------- |  
| 検索ツール | （Google Ads アカウントを持っている広告主）Advertising Cloud では、Advertising Cloud コンバージョン追跡サービスを用いた Google Ads キャンペーンを追跡する、すべてのコンバージョンデータを Google Ads にアップロードできます（オプション）。毎日のアップロードには、広告主レベルのアトリビューションモデルを使用して定義されたコンバージョン値が含まれます。アップロードされたすべてのコンバージョンには、「Adobe_ACS_」（コンバージョン「サブスクリプション」の場合は「Adobe_ACS_Subscriptions」など）の接頭辞が付きます。 <br/> **注意：** アップロードには、フィードファイルから Advertising Cloud にアップロードされたコンバージョンは含まれません。 |
| キャンペーンの検索 | **検索** / **キャンペーン** / **キャンペーンのメニューが階層化** され、「アカウント」の下のキャンペーンが表示されるようになりました。キャンペーンの広告グループ、およびキーワード（サブメニュー付き）、広告、製品グループ（ライブビューのみ）、プレースメント（サブメニュー付き）および広告グループの自動ターゲット。<br/>ライブビューでは、オーディエンスと拡張機能は、独自のサブメニューを持つアカウントと同じレベルにあります。 |

## Target Standard／Premium 19.5.1 {#target}

このリリースには、次の機能、変更点、および機能強化が含まれています。

（括弧内の問題番号はアドビ社内で使用されます。）

### 機能の更新

| 機能/拡張機能 | 説明 |
| --- | --- |
| シングルページアプリケーション Visual Experience Composer （SPA VEC） | SPA VEC に、作業を高速化または効率化するための以下の機能が追加されました。<ul><li>VEC で Web サイトの読み込みをキャンセルし、アクティビティを編集できない状況を解消できるようになりました。アクティビティに小規模な編集を加える、設定を確認、カスタムコードを追加するといった場合や、サイトの読み込みを待てない場合などに便利です。（TGT-33872）</li><li>VEC でページがロードされる前や、ページを読み込めなかった場合（例えば、カスタムコードが動作しなくなった場合など）には、様々なアクションを実行できます。サイト読み込み前に編集できないアクションは、Target UI では無効化されます。（TGT-33851 および TGT-34149）</li></ul> |
| Automated Personalization（AP）アクティビティと自動ターゲットアクティビティ | AP または自動ターゲットアクエィビティを作成する際、コントロールとして使用するエクスペリエンスを選択できます。この機能を使用すると、アクティビティで設定されたトラフィック配分率に基づいて、コントロールトラフィック全体を特定のエクスペリエンスにルーティングすることができます。その後、コントロールエクスペリエンスに対するパーソナライズされた配信のパフォーマンスを評価できます。（TGT-26572） |
| Recommendations | 「最近表示したアイテム」ロジックを作成する際、「以前購入された品目をレコメンデーション」を使用できます。（TGT-34030） |

### 機能強化、修正および変更

* VEC 内でページの読み込みをキャンセルした後、ツールバーアイコンが適切に表示されます。ページが完全に読み込まれるまで特定の操作が実行できない場合、関連するツールバーアイコンが無効になります。（TGT-33811）
* フォルダーの階層内を移動する代わりに、Assets ピッカーのオファーフォルダーを使用して、より簡単に表示およびナビゲートできるようになりました。（TGT-33725）

以下の製品に関する最新のリリース情報については、[Adobe Target リリースノート](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)を参照してください。

* Target StandardおよびTarget Premium
* Recommendations Classic

## Magento {#magento}

Magento は、柔軟なショッピングカートを備えたオンラインマーチャントを提供し、オンラインストアの外観、コンテンツ、機能を制御できる E コマースプラットフォームです。Magento には、オープンソースのバージョンとフル機能コマースバージョンがあります。

Magento Commerce は、Adobe Commerce Cloud に含まれており、エンタープライズ向けのパワー、無制限のスケーラビリティ、および B2C / B2B エクスペリエンス向けのオープンソースの柔軟性を備えた e コマースソリューションを提供します。。

オープンソースとコマースの両方のエディションのリリースノートは [、リリース情報](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) ページで確認できます。

## Primetime {#primetime}

Adobe Primetime は、メディア企業に適したマルチスクリーン TV プラットフォームです。ユーザーの心をつかむパーソナライズ可能な視聴体験を提供し、収益化できます。

[Primetime リリースノート](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime ヘルプのホーム](http://help.adobe.com/en_US/primetime/)
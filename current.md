---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: リリースノート
last-update: 2019年8月
author: mfrei
translation-type: tm+mt
source-git-commit: b3fa98427b027218e9600cb4c5e10dd2ba880f89

---


# 先行公開 - Adobe Experience Cloud のリリースノート

Adobe Experience Cloud の新機能および修正点です。

>[!IMPORTANT]
>
>このページに記載される内容は、リリース前の情報であり、リリース予定日の前に変更される可能性があります。

>[!NOTE]
>
>[Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。通知はリリースの 3～5 営業日前に届きます。 リリース後に発表された新情報には、更新の日付が明記されます。

**リリース日： 2019 年 8 月**

* [エクスペリエンスプラットフォームと管理](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) （ソリューションヘルプへのリンク）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) （ソリューションヘルプへのリンク）

## [!UICONTROL エクスペリエンスプラットフォーム] と管理 {#platform}

[!UICONTROL Experience Platform]、Experience Cloudインターフェイス、製品管理、Experience Platform Launch、IDサービス、セキュリティ速報のリリースノートです。

* [Experience Cloud インターフェイス](#core-services)
* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html)（すべてのアドビ製品）

### Experience Cloud インターフェイス {#core-services}

* 一部のユーザーのセッションログアウトにつながるExperience Cloudログインの重大な問題を修正しました。（MCUI-6908）
* パフォーマンスを向上させ、遅延を減らすために、Experience Cloudログインを更新しました。（MCE-6854、MCID-6869、MCID-6883）
* インターフェイスの外観が更新されました。（MCE-6861、MCID-6911、MCID-6862）
* トリガー定義で「いいね!"節の誤った解釈につながるExperience Cloud [!UICONTROL Triggers]__ の問題を [!UICONTROL 修正] しました。（MCUI-6611）

製品ドキュメントについては [、Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)を参照してください。

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analyticsの新機能、拡張機能および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| 機能 | 説明 |
| -----------| ---------- |  
| SAMSSite cookieの設定のサポート | Analyticsによって設定されたすべてのcookieに、SAMSsite cookieの設定が追加されます。この変更により、SameSite cookieフィールドを必要とするChromeの変更に準拠できます。 |
| ワークスペース:ドロップダウンフィルターの項目制限を50から200に増やす | ドロップダウンフィルターに配置できる項目の制限を50から200に増やしました。この強化により、すべての国（195）をフィルターに追加するなど、様々な使用事例に対応しています。 |

#### 修正点

* フルスクリーンモードで、リアルタイムレポートでテキストが表示される問題を修正しました。（AN-183168）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日 または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 分類ルールビルダーの制限 | 追加日：2019 年 6 月 5 日 | これらの制限は新しいものではありませんが、ドキュメント [に追加](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)されました。 |
| 新しいセグメント演算子の制限 | 追加日：2019 年 5 月 31 日 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. この制限は、この日以降、すべての新しいセグメントおよび変更されたセグメントに適用されます。 制限を超過している既存のセグメントは、引き続きサポートされますが、入力フィールドが減らされるまで変更または保存できません。 これらの制限は、クエリパフォーマンス向上のための継続的な取り組みの一環として適用されています。 |
| **[!UICONTROL 日付分類]**&#x200B;および&#x200B;**[!UICONTROL 数値 2 分類]**&#x200B;に関するサポートの変更予定 | 2019 年 5 月 28 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。 この変更は 2019 年 7 月のメンテナンスリリースから有効になります。 「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。 <br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポートの合計_&#x200B;の計算に対して予定されている変更 | 更新日：2019 年 7 月 9 日 | **2019 年 6 月 18 日**&#x200B;に、_レポートの合計_&#x200B;値の算出方法をすべてのディメンションおよび指標で共通化します。 これにより、一部のレポート（通常、Prop または顧客属性レポート）の合計が変更されます。 この変更以前は、レポートに&#x200B;_未指定_&#x200B;が表示されているかどうかにかかわらず、合計に&#x200B;_未指定_&#x200B;の行項目を含めるレポートと含めないレポートが混在していました。 <br/>2019 年 6 月 18 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。 さらに、_存在する_&#x200B;または&#x200B;_存在しない_&#x200B;ロジックを使用するセグメントは、この変更後、一部のディメンションで異なる結果が表示される可能性があります（特に、_未指定_&#x200B;を特有な値としてレポートするディメンションに影響します。リファラータイプディメンションの「手動入力/ブックマーク」行項目やデバイスタイプディメンションの「その他」行項目が該当します）。 この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| [!DNL Analysis Workspace] CSV ダウンロード機能の更新点  | 2019 年 4 月 10 日 | 2019 年 4 月 11 日以降、**[!UICONTROL CSV ダウンロード]**&#x200B;および&#x200B;**[!UICONTORL クリップボードへのコピー]**（[!DNL Analysis Workspace]）にいくつかの変更が加えられ、書き出されたデータから書式が削除されます。  <ul><li>桁区切り記号は含まれなくなりました。 小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]**&#x200B;で定義された形式が適用されます。 注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。 パーセンテージは 10 進形式になります。 例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| [!DNL Analysis Workspace] Debugger コマンドの変更 | 2019 年 4 月 4 日 | [!DNL Analysis Workspace] Debugger をオンにするためのコンソールコマンドは、**2019 年 6 月 13 日**&#x200B;に adobeTools.debug.includeOberonXml に変更されます。 この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 7 日 | 2019 年 1 月 8 日より、モバイルブラウザーバージョン番号を 2 桁から 1 桁に変更しました。 この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| [!DNL Ad Hoc Analysis]のサポート終了  | 2019 年 1 月 29 日 | 2018 年 8 月 6 日、アドビは [!DNL Ad Hoc Analysis] のサポート終了の意向を表明しました。 サポート終了日については確定次第お知らせします。<br/>サポート終了の予定や詳細については [Discover Workspace](https://adobe.ly/discoverworkspace) を参照してください。 |
| 短い [!DNL Analytics] レポートリンク | 2019 年 1 月 14 日 | 2019 年 1 月 17 日（木）以降、直近 1 年間に訪問されていない短い [!DNL Analytics] レポートリンクは、定期的に削除されるようになります。 |
| TLS 1.0 のサポート終了 | 2019 年 1 月 10 日更新 | 2019 年 2 月 11 日現在、Adobe Analytics レポートで TLS（Transport Layer Security）1.0 の暗号化がサポートされなくなっています。 この変更は、最高レベルのセキュリティ基準を維持して、お客様のデータの安全を確保するための継続的な取り組みの一環です。 If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> 2019 年 2 月 20 日以降、Adobe Analytics のデータ収集で TLS 1.0 がサポートされなくなりました。この変更により、TLS 1.1 以上をサポートしていない旧型のデバイスや Web ブラウザーを使用しているエンドユーザーの [!DNL Analytics] データは収集されなくなりました。 この変更が、お客様の顧客のデータやレポートに大きな影響を及ぼすことはないと認識しています。 （お客様の Web サイトが既に TLS 1.0 をサポートしていない場合、影響は一切ありません。） <br/>2019 年 4 月 11 日以降、Adobe Analytics レポート API は TLS 1.0 の暗号化をサポートしていません。 API にアクセスするお客様は、この変更による影響の有無を確認してください。 <ul><li>デフォルト設定で Java 7 を使用している API クライアントは、[TLS 1.2](https://www.java.com/en/configure_crypto.html) をサポートするように変更してください（「_Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2_」を参照、ブラウザーの翻訳機能をお使いください）。 </li><li>Java 8 を使用している API クライアントは、デフォルト設定が TLS 1.2 なので、影響を受けません。</li><li> その他のフレームワークを使用している API クライアントは、TLS 1.2 のサポートについてベンダーにお問い合わせください。</li></ul> |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。 この変更は、処理中に post_product_list に追加されるマーチャンダイジング eVar 値により、製品および売上高の値の切り捨てが発生しないようにします。 post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 KB に達した時点で値を切り捨てるようにしてください。 |
| [!DNL Analytics Live Stream] エンドポイントの管理における変更点 | 2018 年 12 月 20 日 | 2019 年 2 月 1 日以降、顧客からのアクティブな接続が 90 日間なかった [!DNL Live Stream] エンドポイントが無効化される場合があります。 使用中の [!DNL Live Stream] エンドポイントについてはサポートに問い合わせて確認でき、必要に応じて再度有効にすることができます。 また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 7 日 | TLS 1.0 のサポート終了に伴い、[!DNL Report Builder] ユーザーの皆様には 2019 年 2 月までにバージョン 5.6.21 をダウンロードされることをお勧めします。 この日以降、以前のバージョンの [!DNL Report Builder] は機能しなくなります。 |

### AppMeasurement {#appm}

[!UICONTROL AppMeasurement] 2.16.0リリース（2019年8月8日）

| 機能 | 説明 |
| -----------| ---------- |
| `sendBeacon` 離脱リンクのサポート | `sendBeacon`[!UICONTROL AppMeasurement] での離脱リンクのサポートを実装しました。これにより離脱リンクトラッキングが改善され、トラフィックが増加する可能性があります。 |
| ECID/fid値 | optin設定が変更されても、ECID/fid値が最初のヒットにキャッシュされるようになりました。 |
| DIL 9.3 | Audience ManagementモジュールのDIL9.3への更新 |
| スクロールリーチの追跡 | s. Activity Map.trackScrollリーチのスイッチが公開され、スクロールリーチの追跡がオンまたはオフになりました。 |
| 訪問者IDサービス4.4.0 | AppMeasurementがアップグレードされ、訪問者IDサービス4.4.0が使用されるようになりました。 |

#### 修正点

* isReadyToTrackがtrueの前に発生するAppMeasurementキューのバグを修正しました。

See [AppMeasurement release history](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) for a release history of AppMeasurement on the following platforms:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone、Xbox、Silverlight および .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

## Audience Manager {#aam}

**修正点および改善点**

* 管理者権限を持つユーザーアカウントにのみ「管理」タブが表示されるようになりました（AAM-48557）。
* リストユーザーAPIで、完全なユーザーの詳細が返されるようになりました（AAM-48662）。
* 特性フォルダーリストのサイズを変更できるようになりました（AAM-48800）。
* 複数のUIアクセシビリティの最適化（AAM-48865、AAM-48933）。
* 管理およびデータソースページの最適化のロード（AAM-48514）

## [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。 顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### Adobe Campaign Standard

[キャンペーンStandard19.3リリース](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| 機能 | 説明 |
| -----------| ---------- |  
| 外部APIアクティビティ（パブリックベータ版） | より深いパーソナライゼーションを実現するために、外部APIアクティビティを使用すると、外部システムからのデータをREST API呼び出し経由でワークフローに取り込むことができます。RESTエンドポイントは、顧客管理システム、Adobe I/OランタイムまたはAdobe Experience Cloud RESTエンドポイント（例: Data Platform、Target、Analytics、Campaign）です。この機能は現在パブリックベータ版です。詳しくは、 [詳細ドキュメント](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) とハウツービデオ [](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html)を参照してください。 |
| ワークフローセグメントのレポート | この機能により、マーケティング担当者は、セグメントコードごとに配信パフォーマンスを分類できます。ワークフローを作成し、セグメント化アクティビティを使用して配信母集団にセグメントを割り当てると、これらのセグメントが同じ配信に移行できるようになります。これにより、単一の配信内で複数のセグメントに基づいてオープン/クリックの統計を表示できます。詳しくは、 [詳細ドキュメント](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) とハウツービデオ [](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html)を参照してください。 |

### Adobe Campaign Classic

[Campaign Classic19.1.3アップデート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) -ビルド9031

### Adobe Campaignコントロールパネル

[新しいコントロールパネル機能](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) には、Campaign Classicがデータやファイル転送に接続するURLを追加する機能があります。

[!UICONTROL コントロールパネル] は、AWSでホストされているAdobe Campaign ClassicとAdobe Campaign Standardの両方のユーザーに使用できます。コントロールパネルにはアップグレードは必要ありません。

### その他のリソース

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
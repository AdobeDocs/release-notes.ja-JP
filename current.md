---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: リリースノート
last-update: 2019 年 10 月 日
author: mfrei
translation-type: tm+mt
source-git-commit: 04228df4d9a7279fe2c8627aeb0bb7492d34327e

---


# 先行アクセス — Experience cloudリリースノート — 2019年10月

Adobe Experience Cloud の新機能および修正点です。

>[!IMPORTANT]
>
>このページに記載される内容は、リリース前の情報であり、リリース予定日の前に変更される可能性があります。
>
>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. リリース後に発表された新情報には、更新の日付が明記されます。

## リリース日：2019 年 10 月 10 日

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、ID サービスおよびセキュリティ速報のリリースノートです。

* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics の新機能、機能強化および修正点{#aa-features}

| 機能 | 説明 |
| -----------| ---------- |  
| Privacy Service API: CCPA | The California Consumer Privacy Act (CCPA) enhances privacy rights and consumer protection for residents of California, United States. This Act is set to become effective on January 1, 2020.<br/>The CCPA provides new data privacy rights to California residents, such as the right to access and delete their personal data, to know whether their personal data is sold or disclosed (and to whom), and to refuse the sale of their personal data.<br/>In anticipation of the CCPA, the Privacy Service will support requests to opt out of the selling of personal data.<br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/>CCPA in Analytics: `[Link to new CCPA page in Analytics]()`<br/>[Privacy Service Overview](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| プライバシーレポート：Analytics管理コンソール | Enabling Privacy Reporting for Analytics adds a set of reserved variables to a report suite.  これらの変数は、ヒットレベルでの消費者の同意データの収集を支援するように設計されています。<br/>新しいディメンション：<br/><ul><li>同意管理オプトアウト</li><li>同意管理オプトイン</li><li>同意管理変数： `[Link to new Consent Variables page in Analytics]()`</li></ul> |
| オーディオとビデオの分析：プライバシーサポート | 2つの新しい変数がメディアコレクションAPIに追加されました。<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul>これらは、ヒット時の消費者の同意のステータスを取得するために使用できるオプションの変数です。<br/>[メディア収集APIドキュメ](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/>ント新しいAnalytics Consent Managementコンテキストデータ変数がフェデレーテッド分析フォームに追加されました。 これらの変数を、フェデレーションの「共有からのオプトアウト」または「フェデレーションのヒットの販売」のフラグ付けに使用できるようになりました。<br/>[Download Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace: Update to Freeform table totals | フリーフォームテーブルに、テーブルの合計と **[!UICONTROL 総合計の]** 2つの合計が含まれる **[!UICONTROL ようになりました]**。 表の合計行は、適用されたレポートフィ [ルターを考慮し](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) ます。 以前は、セグメント化のみが影響を受けていました。 [Learn moreIn addition, Show Totals and Show Grand Total options have been added to Column Settings.](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>************<br/>このフリーフォーム合計の変更により、依存するビジュアライゼーション(リンクされた概要番号ビジュアライゼーション **** )、およびCSVおよびPDFデータのエクスポートが更新されます。 |
| Analysis Workspace:「未指定」または「なし」を削除するオプション | 「未指定（なし）」を簡単に削除する機能が、フィルターをレポートするオプションとして追加されました。 |
| Analysis Workspace:紫の精度のコンポーネントの廃止 | 紫の精度の時間コンポーネント（分、時間、日、週、月、四半期、年）は廃止されました。 紫の時間コンポーネントは、常にオレンジ色の時間ディメンションとまったく同じように動作するので、この変更によってエクスペリエンスがシンプルになります。 **紫色の時間コンポーネントの** 1つを以前に使用した場合は、何も行う必要はありません。<br/>この変更により、紫の時間セク **[!UICONTROL ションも]** 「日付範囲」に名前が変更 **[!UICONTROL されました]**。 |

#### 修正点

* Analysis Workspace:左側のレールでディメンション項目を検索すると、検索結果が正しくない問題を修正しました。 （AN-185065）
* Adobe Audience Manager(AAM)で共有セグメントを削除または非公開にできない問題を修正しました。 AAMが応答しない場合にセグメントを削除しないように修正しました。 (AN-185882、AN-185883、AN-184607)
* Ad Hoc Analysisでセグメントを読み込めない場合にタイムアウトになる問題を修正しました。 （AN-184654）
* 最後に使用したレポートスイートがその後非表示になったり、このレポートスイートへのアクセス権限がなくなったりする問題を修正しました。 この場合、Experience cloudからログインできなくなりました。 （AN-181777）
* セグメントに基づいてVRSを作成するのが困難になったセグメントのタイムアウトの問題を修正しました。 （AN-179684）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. |
| San Jose FTP Broker Ending for London and Singapore | 2020 年 7 月 | For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center ftp.omniture.com.[](ftp://ftp.omniture.com/)<br/>For London use ftp3.omniture.comFor Singapore use ftp4.omniture.com[](ftp://ftp3.omniture.com/)<br/>[](ftp://ftp4.omniture.com/) |
| Analysis Workspace フリーフォームテーブルの合計を更新 | 2019 年 9 月 12 日 | In October 2019, freeform table total rows will begin accounting for report filters applied. [](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)これまでは、合計はセグメント化にのみが反映されていました。この変更により、エクスポートされた CSV や PDF データだけでなく、依存するビジュアライゼーション（例：リンクされた [!UICONTROL 概要番号]ビジュアライゼーションなど）も更新されます。 |
| Analytics ユーザーの `createDate` フィールドに関する変更予定 | 2019 年 8 月 30 日 | 2019 年 10 月または 2019 年 11 月に、Analytics ユーザーの `createDate` フィールドが米国太平洋時刻から、タイムゾーン情報を反映した正しい形式に更新されます。（AN-183468） |
| 履歴タイムゾーンオフセットのサポート | 2019 年 8 月 9 日 | Analytics は、タイムスタンプ付きのヒットに対して、タイムゾーンオフセットを自動的に処理するようになりました。この変更に従い、履歴処理用にデータで読み込むシステムは、データで送信する前にタイムゾーンオフセットを調整する必要がなくなりました。 |
| 分類ルールビルダーの制限 | 追加日：2019 年 6 月 5 日 | These limits are not new, but have been added to the documentation here.[](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html) |
| 新しいセグメント演算子の制限 | 追加日：2019 年 5 月 31 日 | 2019 年 7 月 18 日以降、セグメント演算子「_次のいずれかを含む_」、「_次のいずれかを含まない_」、「_次のすべてを含む_」および「_次のすべてを含まない_」は、入力フィールドあたり 100 語に制限されます。この制限は、この日以降、すべての新しいセグメントおよび変更されたセグメントに適用されます。制限を超過している既存のセグメントは、引き続きサポートされますが、入力フィールドが減らされるまで変更または保存できません。これらの制限は、クエリパフォーマンス向上のための継続的な取り組みの一環として適用されています。 |
| **[!UICONTROL 日付分類]**&#x200B;および&#x200B;**[!UICONTROL 数値 2 分類]**&#x200B;に関するサポートの変更 | 2019 年 5 月 28 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。この変更は 2019 年 7 月のメンテナンスリリースから有効になりました。「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。<br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポートの合計_&#x200B;の計算に対する変更 | 更新日：2019 年 7 月 9 日 | **2019 年 6 月 18 日**&#x200B;に、Adobe Analytics では、_レポートの合計_&#x200B;値の算出方法をすべてのディメンションおよび指標で共通化しました。これにより、一部のレポート（通常、Prop または顧客属性レポート）の合計が変更されました。この変更以前は、レポートに&#x200B;_未指定_&#x200B;が表示されているかどうかにかかわらず、合計に&#x200B;_未指定_&#x200B;の行項目を含めるレポートと含めないレポートが混在していました。<br/>2019 年 6 月 18 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。さらに、_存在する_&#x200B;または&#x200B;_存在しない_&#x200B;ロジックを使用するセグメントは、この変更後、一部のディメンションで異なる結果が表示される可能性があります（特に、_未指定_&#x200B;を特有な値としてレポートするディメンションに影響します。リファラータイプディメンションの「手動入力/ブックマーク」行項目やデバイスタイプディメンションの「その他」行項目が該当します）。この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| Analysis Workspace CSV ダウンロード機能の更新点 | 2019 年 4 月 10 日 | 2019 年 4 月 12 日以降、Analysis Workspace からの **[!UICONTROL CSV ダウンロード]**（**[!UICONTORL クリップボードへのコピー]**）にいくつかの変更が加えられ、書き出されたデータから書式が削除されます。  <ul><li>桁区切り記号は含まれなくなりました。小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]**&#x200B;で定義された形式が適用されます。注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。パーセンテージは 10 進形式になります。例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| Analysis Workspace Debugger コマンドの変更 | 2019 年 4 月 4 日 | Analysis Workspace Debugger をオンにするためのコンソールコマンドは、**2019 年 6 月 13 日**&#x200B;に adobeTools.debug.includeOberonXml に変更されます。この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 7 日 | 2019 年 1 月 8 日より、モバイルブラウザーバージョン番号を 2 桁から 1 桁に変更しました。この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| [!DNL Ad Hoc Analysis] のサポート終了  | 2019 年 1 月 29 日 | 2018 年 8 月 6 日、アドビは [!DNL Ad Hoc Analysis] のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。<br/>サポート終了の予定や詳細については、[[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace) を参照してください。 |
| 短い [!DNL Analytics] レポートリンク | 2019 年 1 月 14 日 | 2019 年 1 月 17 日（木）以降、直近 1 年間に訪問されていない短い [!DNL Analytics] レポートリンクは、定期的に削除されるようになります。 |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。この変更は、処理中に post_product_list に追加されるマーチャンダイジング eVar 値により、製品および売上高の値の切り捨てが発生しないようにします。post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 KB に達した時点で値を切り捨てるようにしてください。 |
| [!DNL Analytics Live Stream] エンドポイントの管理における変更点 | 2018 年 12 月 20 日 | 2019 年 2 月 1 日以降、顧客からのアクティブな接続が 90 日間なかった [!DNL Live Stream] エンドポイントが無効化される場合があります。使用中の [!DNL Live Stream] エンドポイントについてはサポートに問い合わせて確認でき、必要に応じて再度有効にすることができます。また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 7 日 | TLS 1.0 のサポート終了に伴い、[!DNL Report Builder] ユーザーの皆様には 2019 年 2 月までにバージョン 5.6.21 をダウンロードされることをお勧めします。この日以降、以前のバージョンの [!DNL Report Builder] は機能しなくなります。 |

### [!DNL AppMeasurement] {#appm}

See AppMeasurement for Javascript release notes.[](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)

## Audience Manager {#aam}

Audience Manager の新機能、拡張機能および修正点です。

**修正点および改善点**

* All customer accounts created after July 1st, 2019, will automatically be assigned a  license, providing them access to their reports. [!DNL Tableau]If your account was created before July 1st, 2019, and you still do not have access to your  reports, please contact Customer Care.[!DNL Tableau]
* We've removed incorrectly generated activity trait memberships for visitor profiles that did not have an ID synchronization with the trait data source (AAM-45371).
* We've removed invalid global device IDs from global data sources. See Global Data Sources to learn what valid device IDs should look like to be accepted by Audience Manager (AAM-41259).[](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html)
* 保護されたセグメントを削除しようとすると、セグメントページが応答を停止するバグを修正しました。(AAM-49881)
* Twitter用にカスタマイズされたオーディエンスの宛先を編集する場合、 [!UICONTROL Account] Selectorがアクティブになるのは、その宛先にアカウントが割り当てられて [!DNL Twitter Ads] いない場合のみです(AAM-49975)。
* 購読が無効な場合に [!UICONTROL Audience Marketplace] データフィードが無効にならないバグを修正しました。(AAM-49640)
* Audience Manager ユーザーインターフェイスのアクセシビリティに関するいくつかの改善を行いました。

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品メンテナンス

* **AEM 6.3.3.6**

   AEM 6.3、Service Pack 3、Cumulative Fix Pack 6（2019年9月26日リリース6.3.6）は、2017年4月のAEM 6.3の一般リリース(GA)以降にリリースされた主なお客様向け修正を含む重要なアップデートです。
   * [リリースノート](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4、Service Pack 6.0（2019年9月19日リリースの6.4.6.0）は、2018年4月のAEM 6.4の一般リリース(GA)以降にリリースされた主なお客様向け修正を含む重要なアップデートです。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0** AEM 6.5、Service Pack 2.0（2019年9月19日リリース6.5.2.0）は、2019年4月のAEM 6.5の一般リリース(GA)以降にリリースされた主なお客様向け修正を含む重要なアップデートです。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### セルフサービス

* **Scene7:アセットの再処理ワークフロー**

   後で変更した既存の処理プロファイルが既に存在するフォルダー内のアセットを再処理できるようになりました。
処理プ [ロファイルを編集した後のフォルダー内のアセットの再処理を参照してください](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)。

* **Dynamic Media ViewerとAdobe AnalyticsおよびAdobe Launchの統合**

   Dynamic Media Viewers Extension for Adobe LaunchとDynamic Media Viewer 5.13のリリースにより、Dynamic Media、Adobe AnalyticsおよびAdobe Launchのお客様は、Adobe Launch設定で、Dynamic Media Viewerに固有のイベントとデータを使用できます。
詳しくは、 [ダイナミックメディアビューアとAdobe AnalyticsおよびAdobe launchの統合を参照してください](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html)。

* **AEMデスクトップアプリ**

   AEM Assetsで作業するクリエイティブ、マーケター、基幹業務ユーザー向けにAEMデスクトップアプリ2.0が提供されました。
AEMデスクトップア [プリのリリースノートを参照してください。](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **コアコンポーネント**
   * コアコンポーネントのローカリゼーション機能とAEMテンプレートの使用方法について説明します。
      [例を参照してください](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html)。
   * コアコンポーネント2.6.0には、エクスペリエンスフラグメントコンポーネントが導入されています。 The component is now available along with authoring documentation and developer details and project download available on GitHub.[](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html)[](https://github.com/adobe/aem-core-wcm-components)

* **AEM Assets**
   * 視覚/類似性検索機能に関する新しいドキュメント。
See Find similar images.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)
   * 接続されたアセット機能で、画像ファイル形式に加えて、リモートDAMデプロイメントで使用可能なドキュメントが使用されるようになりました。
AEMサイト [でのDAMアセットの共有に接続されたアセットの使用を参照してください](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html)。
   * アセットの検索と検出に関する新しいコンテンツ。 The Search assets in AEM topic is your one-stop-shop for information on using, configuring, troubleshooting, limitations, and tips.
__ AEMでのア [セットの検索を参照してください](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html)。

### その他のリソース

* [AEM 6.5 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older Versions of AEM Documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classicヘルプホーム](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

<!-- ### Adobe Campaign Classic

* [Campaign Classic 19.1.4 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) – build 9032
* [Campaign Classic 19.1.5 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) – build 9033

### Adobe Campaign [!UICONTROL Control Panel]

Text

### Additional resources -->

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

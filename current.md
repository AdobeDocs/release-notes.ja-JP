---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: リリースノート
last-update: 2019 年 10 月
author: mfrei
translation-type: tm+mt
source-git-commit: 3d35a004385f3e94feeb205d25e6c420e54ca835

---


# 先行公開 - Experience Cloud のリリースノート - 2019 年 10 月

Adobe Experience Cloud の新機能および修正点です。

>[!IMPORTANT]
>
>このページに記載される内容は、リリース前の情報であり、リリース日の前後に変更される可能性があります。

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. リリース後に発表された新情報については、更新日と併せて追加公開します。

## リリース日：2019 年 10 月 11 日

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) （ソリューションヘルプへのリンク）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) （ソリューションヘルプへのリンク）

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、ID サービスおよびセキュリティ速報のリリースノートです。

* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html) （すべてのアドビ製品）

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
| プライバシーサービス API：CCPA | カリフォルニア州消費者プライバシー法（CCPA）は、米国カリフォルニア州の居住者のプライバシー権と消費者保護を厳格化します。この法律は、2020 年 1 月 1 日に施行されます。<br/><br/>CCPA は、カリフォルニア州の居住者に新しいプライバシー権を提供します。これには、自身の個人データにアクセスして削除する権利、自身の個人データが（誰に）販売または公開されているかどうかを知る権利、および自身の個人データの販売を拒否する権利が含まれます。<br/><br/>CCPAに備えて、プライバシーサービスは個人データの販売を停止する要求をサポートします。<br/><br/>プライバシーサービス（旧 GDPR サービス）は、以前の機能をすべて保持し、CCPA をサポートするよう拡張されました。<br/><br/>[AnalyticsのCCPAプライバシー](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br/><br/>[サービスの概要](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| プライバシーレポート：Analytics Admin Console | Analytics でプライバシーレポートを有効化すると、レポートスイートに一連の変数が追加されます。これらの変数は、消費者の同意データをヒットレベルで収集するためのものです。<br/><br/>追加されるディメンション：<br/><ul><li>同意管理のオプトアウト</li><li>同意管理のオプトイン</li><li>[同意管理変数](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| オーディオとビデオの分析：プライバシーサポート | メディアコレクション API に 2 つの新しい変数が追加されました。<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>これらは、ヒット時の消費者の同意のステータスを取得するための変数です。<br/><br/>[メディア収集APIドキュメ](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>ント新しいAnalytics Consent Managementコンテキストデータ変数がフェデレーテッド分析フォームに追加されました。 これらの変数を、フェデレーションの「共有のオプトアウト」または「販売ヒット数」のフラグ付けに使用できるようになりました。<br/><br/>[フェデレーテッドフォームのダウンロード](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace：フリーフォームテーブルの合計の更新 | フリーフォームテーブルに、**[!UICONTROL テーブルの合計]**&#x200B;と、**[!UICONTROL 総計]**&#x200B;の 2 つの合計が表示されるようになりました。表の合計行は、適用されたレポートフィ [ルターを考慮し](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) ます。 以前は、セグメントのみが合計に影響を与えていました。[詳細](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>：列設定に、「合計を表 **[!UICONTROL 示]** 」オプ **[!UICONTROL ションと「総合計を表示]** 」オプションが追加さ **[!UICONTROL れました]**。<br/>この変更により、出力された CSV や PDF データだけでなく、依存するビジュアライゼーション（例：リンクされた **[!UICONTROL 概要番号]**&#x200B;ビジュアライゼーションなど）も更新されます。 |
| Analysis Workspace：「未指定」または「なし」を削除するオプション | レポートフィルターのオプションに、「未指定（なし）」を簡単に削除する機能が追加されました。 |
| Analysis Workspace：紫色の精度コンポーネントの廃止 | 紫色の精度の時間コンポーネント（分、時間、日、週、月、四半期、年）は廃止されました。紫の時間コンポーネントは常に、オレンジ色のディメンションと同じ動作をするので、この変更によって画面や操作がシンプルになります。紫色の時間コンポーネントを以前使用したことがある場合、**何もおこなう必要はありません**。<br/>この変更により、紫色の「**[!UICONTROL 日時]**」セクションの名前が、「**[!UICONTROL 日付範囲]**」に変更されました。 |

#### 修正点

* Analysis Workspace：左側のレールでディメンション項目を検索すると、間違った検索結果が表示される問題を修正しました。（AN-185065）
* Adobe Audience Manager（AAM）で共有セグメントを削除または非公開にできない問題を修正しました。修正では、AAM が応答しない場合にセグメントを削除しないようにしました。（AN-185882、AN-185883、AN-184607）
* Ad Hoc Analysis でセグメントを読み込めずタイムアウトする問題を修正しました。（AN-184654）
* 最後に使用したレポートスイートがその後非表示になったり、このレポートスイートへのアクセス権限がなくなったりする問題を修正しました。この場合、Experience Cloud からログインできなくなっていました。（AN-181777）
* セグメントに基づいて仮想レポートスイートを作成するのを困難にしていた、セグメントでのタイムアウトの問題を修正しました。（AN-179684）
* まれに誤ったエンコードが行われる場合にデータが切り捨てられる問題を修正しました。 （AN-186707）
* Yandex検索エンジンが国別に適切に分類されるようになりました。 （AN-181728）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Analysis Workspace フリーフォームテーブルの合計を更新 | 2019 年 9 月 13 日 | 2019年10月に、フリーフォームテーブルの合計行が、適用されたレポートフィルターに対す [る課金を開始し](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) ます。 これまでは、合計はセグメントのみが反映されていました。この変更により、出力された CSV や PDF データだけでなく、依存するビジュアライゼーション（例：リンクされた [!UICONTROL 概要番号]ビジュアライゼーションなど）も更新されます。 |
| Analytics ユーザーの `createDate` フィールドに関する変更予定 | 2019 年 8 月 31 日 | 2019 年 10 月または 2019 年 11 月に、Analytics ユーザーの `createDate` フィールドが米国太平洋時刻から、タイムゾーン情報を反映した正しい形式に更新されます。（AN-183468） |
| 履歴タイムゾーンオフセットのサポート | 2019 年 8 月 9 日 | Analytics は、タイムスタンプ付きのヒットに対して、タイムゾーンオフセットを自動的に処理するようになりました。この変更に従い、履歴処理用にデータで読み込むシステムは、データで送信する前にタイムゾーンオフセットを調整する必要がなくなりました。 |
| 分類ルールビルダーの制限 | 追加日：2019 年 6 月 6 日 | これらの制限は新しいものではありませんが、ここで説明するドキュメントに追加さ [れました](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)。 |
| 新しいセグメント演算子の制限 | 追加日：2019 年 6 月 1 日 | 2019 年 7 月 19 日以降、セグメント演算子「_次のいずれかを含む_」、「_次のいずれかを含まない_」、「_次のすべてを含む_」および「_次のすべてを含まない_」は、入力フィールドあたり 100 語に制限されます。この制限は、この日以降、すべての新しいセグメントおよび変更されたセグメントに適用されます。制限を超過している既存のセグメントは、引き続きサポートされますが、入力フィールドが減らされるまで変更または保存できません。これらの制限は、クエリパフォーマンス向上のための継続的な取り組みの一環として適用されています。 |
| **[!UICONTROL 日付分類]**&#x200B;および&#x200B;**[!UICONTROL 数値 2 分類]**&#x200B;に関するサポートの変更 | 2019 年 5 月 29 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。この変更は 2019 年 7 月のメンテナンスリリースから有効になりました。「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。<br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポートの合計_&#x200B;の計算に対する変更 | 更新日：2019 年 7 月 10 日 | **2019 年 6 月 19 日**&#x200B;に、Adobe Analytics では、_レポートの合計_&#x200B;値の算出方法をすべてのディメンションおよび指標で共通化しました。これにより、一部のレポート（通常、Prop または顧客属性レポート）の合計が変更されました。この変更以前は、レポートに&#x200B;_未指定_&#x200B;が表示されているかどうかにかかわらず、合計に&#x200B;_未指定_&#x200B;の行項目を含めるレポートと含めないレポートが混在していました。<br/>2019 年 6 月 19 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。さらに、_存在する_&#x200B;または&#x200B;_存在しない_&#x200B;ロジックを使用するセグメントは、この変更後、一部のディメンションで異なる結果が表示される可能性があります（特に、_未指定_&#x200B;を特有な値としてレポートするディメンションに影響します。リファラータイプディメンションの「手動入力/ブックマーク」行項目やデバイスタイプディメンションの「その他」行項目が該当します）。この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| Analysis Workspace CSV ダウンロード機能の更新点 | 2019 年 4 月 11 日 | 2019 年 4 月 12 日以降、Analysis Workspace からの **[!UICONTROL CSV ダウンロード]**（**[!UICONTORL クリップボードへのコピー]**）にいくつかの変更が加えられ、書き出されたデータから書式が削除されます。  <ul><li>桁区切り記号は含まれなくなりました。小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]**&#x200B;で定義された形式が適用されます。注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。パーセンテージは 10 進形式になります。例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| Analysis Workspace Debugger コマンドの変更 | 2019 年 4 月 5 日 | Analysis Workspace Debugger をオンにするためのコンソールコマンドは、**2019 年 6 月 14 日**&#x200B;に adobeTools.debug.includeOberonXml に変更されます。この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 8 日 | 2019 年 1 月 9 日より、モバイルブラウザーバージョン番号を 2 桁から 1 桁に変更しました。この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| [!DNL Ad Hoc Analysis] のサポート終了  | 2019 年 1 月 30 日 | 2018 年 8 月 7 日、アドビは [!DNL Ad Hoc Analysis] のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。<br/>サポート終了の予定や詳細については、[[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace) を参照してください。 |
| 短い [!DNL Analytics] レポートリンク | 2019 年 1 月 15 日 | 2019 年 1 月 18 日（金）以降、直近 1 年間に訪問されていない短い [!DNL Analytics] レポートリンクは、定期的に削除されるようになります。 |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 10 日 | 2019 年 2 月 8 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。この変更は、処理中に post_product_list に追加されるマーチャンダイジング eVar 値により、製品および売上高の値の切り捨てが発生しないようにします。post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 KB に達した時点で値を切り捨てるようにしてください。 |
| [!DNL Analytics Live Stream] エンドポイントの管理における変更点 | 2018 年 12 月 21 日 | 2019 年 2 月 2 日以降、顧客からのアクティブな接続が 90 日間なかった [!DNL Live Stream] エンドポイントが無効化される場合があります。使用中の [!DNL Live Stream] エンドポイントについてはサポートに問い合わせて確認でき、必要に応じて再度有効にすることができます。また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 8 日 | TLS 1.0 のサポート終了に伴い、[!DNL Report Builder] ユーザーの皆様には 2019 年 2 月までにバージョン 5.6.21 をダウンロードされることをお勧めします。この日以降、以前のバージョンの [!DNL Report Builder] は機能しなくなります。 |

### [!DNL AppMeasurement] {#appm}

JavaScript版AppMeasurementリ [リースノートを参照してください](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager の新機能、拡張機能および修正点です。

**修正点および改善点**

* 2019 年 7 月 2 日以降にアカウントを作成したすべてのお客様には、自動的に [!DNL Tableau] ライセンスが割り当てられ、レポートへのアクセス権が提供されます。アカウントが 2019 年 7 月 1 日より前に作成され、まだ。[!DNL Tableau] レポートにアクセスできない場合は、カスタマーサポートにお問合せください。
* アクティビティ特性の誤った生成、および人為的な一致率とオーディエンスサイズの増加の原因となっていたバグを修正しました。 この修正に従うと、自動生成されたアクティビティ特性を使用して作成されたセグメントのサイズが小さくなる場合があります。 これは正常で、予期される動作です(AAM-45371)。
* グローバルデータソースから無効なグローバルデバイス IDを削除しました。Audience Managerで受け [](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) 入れられる有効なデバイスIDがどのように表示されるかを確認するには、「グローバルデータソース」を参照してください(AAM-41259)。
* 保護されているセグメントを削除しようとすると、セグメントページの応答が停止する問題を修正しました。（AAM-49881）
* Twitter に合わせたオーディエンス用の宛先を編集した場合、宛先に [!DNL Twitter Ads] アカウントが割り当てられていない場合にのみ、「[!UICONTROL アカウント]」セレクターがアクティブになります。（AAM-49975）
* サブスクリプションが無効化されている場合にユーザーが[!UICONTROL Audience Marketplace] データを無効にできないバグを修正しました。（AAM-49640）
* Audience Manager ユーザーインターフェイスのアクセシビリティに関するいくつかの改善を行いました。

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

* **Cloud Manager 2019.9.0**

   * Cloud Manager 2019.9.0（2019 年 9 月 13 日リリース）は、セキュリティテスト条件の更新、ダウンロード可能な監視グラフの追加、お客様から報告された操作性の問題の修正をおこないました。
   * [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 製品メンテナンス

* **AEM 6.3.3.6**

   2019 年 9 月 26 日にリリースされた AEM 6.3 Service Pack 3–Cumulative Fix Pack 6（6.3.3.6）は重要なアップデートであり、2017 年 4 月の AEM 6.3 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。
   * [リリースノート](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   2019 年 9 月 20 日にリリースされた AEM 6.4 Service Pack 4（6.4.6.0）は重要なアップデートであり、2018 年 4 月の AEM 6.4 の一般リリース以降にリリースされたお客様向けの主要な修正が含まれています。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0**
2019 年 9 月 20 日にリリースされた AEM 6.5.2.0 Service Pack 4（6.5.2.0）は重要なアップデートであり、2019 年 4 月の AEM 6.5 の一般リリース以降にリリースされたお客様向けの主要な修正が含まれています。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### セルフサービス

* **Scene7：アセットの再処理ワークフロー**

   既存の処理プロファイルを後で変更したフォルダー内のアセットを、再処理できるようになりました。処理プ [ロファイルを編集した後のフォルダー内のアセットの再処理を参照してください](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)。

* **Dynamic Media Viewers と Adobe Analytics および Adobe Launch の統合**

   Adobe Launch の Dynamic Media Viewers 拡張機能を、Dynamic Media Viewers 5.13 のリリースとともに使用することで、Dynamic Media、Adobe Analytics、および Adobe Launch のユーザーは、Adobe Launch 設定 Dynamic Media Viewers に固有のイベントやデータを使用できます。See [Integrating Dynamic Media Viewers with Adobe Analytics and Adobe Launch](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **AEM デスクトップアプリ**

   AEM Assets で作業するクリエイティブ、マーケター、基幹業務ユーザー向けに AEM デスクトップアプリ 2.0 がリリースされました。
「[AEM デスクトップアプリのリリースノート](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **コアコンポーネント**
   * コアコンポーネントのローカライゼーション機能と AEM テンプレートのしくみについて説明します。
      [例を参照してください](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html)。
   * コアコンポーネント 2.6.0 では、エクスペリエンスフラグメントコンポーネントを導入しています。コンポーネントが、オーサリングドキュメント [、開発者の詳細](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) 、およびGitHubで [のプロジェクトのダウンロードと共に使用できるようになりました](https://github.com/adobe/aem-core-wcm-components)。

* **AEM Assets**
   * 視覚／類似性検索機能に関する新しいドキュメント。詳しくは、類 [似画像の検索を参照してくださ](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)い。
   * Connected Asset の機能で、画像ファイル形式に加えて、リモート DAM デプロイメントで使用可能なドキュメントを使用するようになりました。AEMサイト [でのDAMアセットの共有に接続されたアセットの使用を参照してください](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html)。
   * アセットの検索と検出に関する新しいコンテンツ。「_AEM でのアセット検索_」のトピックでは、使用、設定、トラブルシューティング、制限、ヒントに関する情報をワンストップで提供します。AEMでのア [セットの検索を参照してください](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html)。

### その他のリソース

* [AEM 6.5 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEMドキュメントの旧バージョン](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classicヘルプホーム](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### Adobe Campaign Classic

* [Campaign Classic 19.1.4の更新](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) — ビルド9032
* [Campaign Classic 19.1.6の更新](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-19-1-6-build-9035) — ビルド9035

### その他のリソース

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

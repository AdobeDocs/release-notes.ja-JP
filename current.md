---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: リリースノート
last-update: 2019 年 11 月 日
author: mfrei
translation-type: tm+mt
source-git-commit: 2c6076aa0af7b9a273e31b1f8919e006ff48e6b4

---


# 先行公開 - Adobe Experience Cloud のリリースノート - 2019 年 11 月

> [!IMPORTANT]このページに記載される内容は、リリース前の情報であり、リリース日の前後に変更される可能性があります。

Adobe Experience Cloud の新機能および修正点です。

> [!NOTE][[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。リリース後に発表された新情報については、更新日と併せて追加公開します。

**リリース日：2019 年 30 月 11 日**

* [Experience Cloud インターフェイス](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（ソリューションヘルプへのリンク）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（ソリューションヘルプへのリンク）
* [!DNL Advertising Cloud](#adcloud)

## Experience Cloud インターフェイス {#ecloud}

Experience Cloud インターフェイスおよび製品管理のリリースノートです。

* フィードページは2019年12月に廃止予定です。 製品内廃止通知を探します。 （MCUI-10039）
* アプリセレク [ターから](https://www.adobe.com/marketing/campaign.html) 、Adobe Campaignの「詳細情報」リンクを更新しました。 （MCUI-10034）
* Experience cloudインターフェイスのコアプラットフォームの安定性と応答性が向上しました。 （MCUI-6822）
* Experience Cloud UIのセキュリティの脆弱性を修正しました。 （MCUI-9942）
* 顧客属性で、一部の顧客のスキーマ検証がブロックされる重大な問題を修正しました。 (MCUI-10024、MCUI-6479)
* オーディエンスライブラリが改善され、リアルタイムオーディエンスの作成がサポートされていないディメンションが削除されるようになりました。 （MCUI-10046）

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、ID サービスおよびセキュリティ速報のリリースノートです。

* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html)（すべてのアドビ製品）

### Experience Platform Launch {#launch}

リリースノートおよび製品ドキュメントについては、[Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) を参照してください。

## [!DNL Analytics] {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

製品ドキュメントについては、[Adobe Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

### Adobe Analytics の新機能、機能強化および修正点 {#aa-features}

| 機能 | 説明 |
| -----------| ---------- | 
| 顧客の遍歴分析 | 2019年11月22日に、アドビは [Customer Jareny Analyticsを](https://www.adobe.com/analytics/customer-journey-analytics.html) Adobe Analyticsのアドオンとして提供します。<br><br/>顧客の遍歴分析を使用すると、あらゆるチャネルからすべての顧客データを取り込むことができます。 オンラインとオフラインの両方 — 」をAdobe Experience Platformに追加し、今すぐAnalysis Workspaceを使用して、既存のデジタルデータと同様にこのデータを分析します。 顧客の遍歴分析には、共通の顧客IDに基づいて、Analysis Workspaceのオンラインデータとオフラインデータをどのように接続するかを制御する機能が含まれ、最終的にアトリビューション、セグメント化、フロー、フォールアウトなどを実行できます。 をAdobe Analyticsの顧客データセット全体に対して使用できます。<br><br/>Analytics Select、PrimeおよびUltimateのお客様は、このアドオン製品を購入できます。 詳しくは、アドビのアカウントチームにお問い合わせください。 |
| プライバシーサービス API：CCPA | カリフォルニア州消費者プライバシー法（CCPA）は、米国カリフォルニア州の居住者のプライバシー権と消費者保護を厳格化します。この法律は、2020 年 1 月 1 日に施行されます。<br><br/>CCPA は、カリフォルニア州の居住者に新しいプライバシー権を提供します。これには、自身の個人データにアクセスして削除する権利、自身の個人データが（誰に）販売または公開されているかどうかを知る権利、および自身の個人データの販売を拒否する権利が含まれます。<br><br/>CCPA を見越し、プライバシーサービスは個人データの販売のオプトアウトに対するリクエストをサポートします。<br><br/>プライバシーサービス（旧 GDPR サービス）は、以前の機能をすべて保持し、CCPA をサポートするよう拡張されました。<br/><br/>[Analytics の CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[プライバシーの概要](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| プライバシーレポート：Analytics Admin Console | Analytics でプライバシーレポートを有効化すると、レポートスイートに一連の変数が追加されます。これらの変数は、消費者の同意データをヒットレベルで収集するためのものです。<br><br/>追加されるディメンション：<br/><ul><li>同意管理のオプトアウト</li><li>同意管理のオプトイン</li><li>[同意管理変数](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| オーディオとビデオの分析：プライバシーサポート | メディアコレクション API に 2 つの新しい変数が追加されました。<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>これらは、ヒット時の消費者の同意のステータスを取得するための変数です。<br/><br/>[メディアコレクション API ドキュメント](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>新しい Analytics Consent Management コンテキストデータ変数が Federated Analytics フォームに追加されました。これらの変数を、フェデレーションの「共有のオプトアウト」または「販売ヒット数」のフラグ付けに使用できるようになりました。<br/><br/>[フェデレーテッドフォームのダウンロード](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### 修正点

* 「不明なユーザー」が所有する日付範囲を削除しようとするとエラーが発生する問題を修正しました。（AN-185540）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| EOL of **[!UICONTROL View Archiveオプション]** | 2019年10月30日 | ダッシュボードマネージャーの「アーカイブを表示」オプションの提供終了日( **[!UICONTROL 2020年1月]** )を発&#x200B;**[!UICONTROL 表します(コンポーネント/ダッシュボード]**)。 |
| EOL of **[!UICONTROL Enforce IP Login Restrictionsオプション]** | 2019年10月30日 | 2020年1月に、管理者/カンパニー設定/セキュリティメニューのIPログインホワイトリスト(**[!UICONTROL IPログイン制限の実施]**)機能の提供終了日をお知らせします **** 。 |
| CookieのSameSite属性の処理を更新しました | 2019 年 10 月 15 日 | 2019年8月に、アドビは、Analyticsが設定するすべてのcookieにSameSite cookie設定が追加されたと発表しました。 ロジックの更新が適用されます。<ul><li>Webkitに基づいていないすべてのサードパーティCookieのSameSite属性がに設定されていま `none`す。</li><li>その他のすべてのCookieには、SameSite属性が設定されていません。</li></ul> |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Analysis Workspace フリーフォームテーブルの合計を更新 | 2019 年 9 月 13 日 | 2019 年 10 月より、フリーフォームテーブルの合計行が、適用された[レポートフィルター](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)を考慮するようになります。これまでは、合計はセグメントのみが反映されていました。この変更により、出力された CSV や PDF データだけでなく、依存するビジュアライゼーション（例：リンクされた [!UICONTROL 概要番号]ビジュアライゼーションなど）も更新されます。 |
| Analytics ユーザーの `createDate` フィールドに関する変更予定 | 2019 年 8 月 31 日 | 2019 年 10 月または 2019 年 11 月に、Analytics ユーザーの `createDate` フィールドが米国太平洋時刻から、タイムゾーン情報を反映した正しい形式に更新されます。（AN-183468） |
| 履歴タイムゾーンオフセットのサポート | 2019 年 8 月 9 日 | Analytics は、タイムスタンプ付きのヒットに対して、タイムゾーンオフセットを自動的に処理するようになりました。この変更に従い、履歴処理用にデータで読み込むシステムは、データで送信する前にタイムゾーンオフセットを調整する必要がなくなりました。 |
| 分類ルールビルダーの制限 | 追加日：2019 年 6 月 6 日 | これらの制限は新しいものではありませんが、[こちら](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)のドキュメントに追加されました。 |
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

[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)を参照してください。

## Audience Manager {#aam}

Audience Manager の新機能、拡張機能および修正点です。

| 機能 | 説明 |
|--- |----|
| [プロファイル結合ルールの強化](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | プロファイル結合ルールに関する一連の機 [!UICONTROL 能強化をリリースしました]。 <ul><li>最大100台のデバイスに対して、セグメント評価がバッチでサポートされるようになりました。</li><li>特性とセグメントの訪問者のレポート精度を改善しました。</li><li>デバイス間IDを使用して生成されたバッチファイルの精度が向上しました。</li><li>各ルールの使用例をさらに詳しく説明し、ドキュメントを更新しました。 詳しくは、 [プロファイル結合ルールの一般的な使用例](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)、外部デバ [イスグラフの使用例](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)、およびプ [ロファイルリンクデバイスグラフの使用例を参照してください](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)。</li></ul> |
| [一括管理ツール](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | MacOSおよびMicrosoft Windowsオペレーティングシステムで動作し、Experience cloudログインをサポートする新しいバージョンのバルク管理ワークシートがリリースされました。 |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | cookieのハイジャック攻撃やプロトコ [!DNL HTTP Strict-Transport-Security]ルダウングレード攻撃から保護するWebセキュリティポリシーに対するサポートが追加されました。 |

**修正点および改善点**

* Audience Marketplaceで、顧客が月別のセグメント使用量を送信する際にUIからエラー409が返されるバグを修正しました。 （AAM-50825）
* Derived Signalsで、短時間お客様が新しい派生シグナルを作成できないバグを修正しました。 （AAM-50968）
* ユーザーベースの宛先で、顧客が宛先の名前を変更できなかったバグを修正しました。 （AAM-51025）
* 一部のユーザーがAudience Manager UIにログインする際に重複するアカウントを持つバグを修正しました。 重複したアカウントに関連付けられた権限が原因で、これらのユーザーはUIの一部にアクセスして操作を実行できなかった問題を修正しました。 （AAM-50818）
* 引き続き、Audience Manager UIのアクセシビリティが向上しました。 (AAM-48932、AAM-49043、AAM-49054、AAM-49371、AAM-49375)

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5は、Brand portalユーザー（外部のエージェンシー/チーム）に対して、作成者環境にアクセスせずにBrand portalにコンテンツをアップロードし、AEM Assetsに公開する機能を提供する機能リリースです。 この機能はBrand Portalでの [](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)Asset Sourcingと呼ばれ、グローバルに分散した他のBrand portalユーザとアセットを貢献および共有する双方向のメカニズムを提供することで、顧客体験を向上させます。

   AEM Assetsブ [ランドポータルの新機能を参照してください](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html)。

   See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **AEM Forms自動変換サービス**

   自動フォーム変換サービスは、PDFフォームをアダプティブフォームに自動変換することで、データ取得エクスペリエンスのデジタル化と最新化を促進します。 Adobe Senseiが提供するサービスは、PDFフォームを、デバイスに優しく、レスポンシブで、HTML5ベースのアダプティブフォームに自動的に変換します。 PDFフォームとXFAに対する既存の投資を活用しながら、このサービスは、変換中にアダプティブフォームフィールドに適切な検証、スタイル設定、レイアウトも適用します。

   詳しくは、 [Adobe Experience Manager Forms自動コンバージョンサービスを参照してください](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)。

* **Cloud Manager 2019.10.0**

   Cloud Manager 2019.10.0の一般的なリリースノートが利用できるようになりました。 また、配置手順の更新と、プロジェクトバージョンの管理に関する更新も記載されています。

   詳し [くは、Cloud Manager 2019.10.0リリースノートを参照してください](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)。

### セルフサービス

* **Activity Map**

   Adobe Analytics API内のセキュリティの変更により、AEMに含まれるバージョンのActivity mapを使用できなくなりました。 詳しく [は、Adobe Analyticsへの接続の設定を参照してください](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics)。

   Adobe Analyticsが提供するChrome [、FirefoxまたはInternet Explorer用の](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) Activity mapブラウザープラグインを使用する必要があります。

* **AEM Screensプロジェクトのベストプラクティスガイド**

   新しいAEM Screensのベストプ _ラクティスガイドは_ 、デジタル署名の実装を想像し、設計し、意図的な顧客体験をもたらすための、包括的なインサイトと実践的なアドバイスを提供します。 また、AEM Screensにデジタル署名プロジェクトを展開しながら、ベストプラクティスを使用してビジネスに良い影響を与える方法についても説明します。

   AEM Screensプロジ [ェクトのベストプラクティスガイドを参照してください](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html)。

* **ヘッドレスエクスペリエンス管理**

   単一ページアプリケ [ーションのサーバー側レンダリングに使用されるリモートコンテンツレンダラーの機能が](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) 、ドキュメントに記載されるようになりました。

* **SPAとサーバ側のレンダリング**

   AEM駆動型SPAがサーバー側のレンダリングに使用するリモートコンテンツレンダリングサービスを、ニーズに合わせて拡張およびカスタマイズできます。

   「 [SPAとサーバ側レンダリング」を参照してください](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer)。

* **AEMプロジェクトのアーキタイプ**

   AEMプロジェクトのアーキタイプは、最小限のベストプラクティスベースのAdobe Experience Managerプロジェクトを独自のAEMプロジェクトの起点として作成します。 このアーキタイプを使用する場合に指定する必要があるプロパティを使用すると、このプロジェクトのすべての部分の名前を指定し、特定のオプション機能を制御できます。

   「 [AEMプロジェクトアーキタイプ」を参照してくださ](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html)い。

* **AEMドキュメントの更新**

   過去3か月間のAdobe Experience Managerに関する重要なドキュメントの変更と更新についてお読みください。

   AEMのドキ [ュメントを参照してください。最近のドキュメントの更新](https://helpx.adobe.com/experience-manager/documentation-updates.html)。

### その他のリソース

* [AEM 6.5 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### ドキュメントのリソース

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [リリース計画](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

2019 年 10 月 12 日リリース用に更新

| 表示 | 機能 |
|------|---------|
| キャンペーンの検索 | Advertising Cloud で、Yahoo! Japan ディスプレイネットワークのアカウントの広告レベルの追跡機能を同期および提供できるようになりました。アカウントにログインの詳細を提供した場合、アカウント内の既存のキャンペーン、広告グループおよび広告は、キャンペーン管理ビューで読み取り専用として使用できます。クリック、コスト、コンバージョン、その他のパフォーマンスデータは、キャンペーン管理ビュー内、および基本レポートと詳細レポートで使用できます。 |
|  | （Google Analytics の広告主）Advertising Cloud 検索では、特定の Google Analytics アカウントと、プロパティ、ビューを組み合わせたコンバージョン指標を同期して、最適化とレポートをおこなうことができます。ページビュー数、セッション数、直帰率（バウンス／セッションとして計算）、セッション時間が自動的に含まれます。1 つのデータソースにつき最大 16 個の指標を含めることができます。 |
|  | （Advertising Cloud と Adobe Analytics の統合を使用した、広告主の既存の Google 広告アカウント）s_kwcid トラッキングコードで新しい形式が使用できます。これにより、Advertising Cloud はアカウントに関するデータを、Adobe Analytics のレポート機能および分析機能と共有できます。最新の形式には、キャンペーン ID と広告グループ ID のパラメーターが含まれます。これらのパラメーターは、Analytics で Google ドラフト＆エクスペリメントキャンペーン用に、キャンペーンおよび広告グループレベルで正確なレポートをおこなうために必要です。既存の Google アカウントに Google ドラフト＆エクスペリメントキャンペーンが含まれる場合は、新しい s_kwcid に移行するために、各アカウントのアカウントトラッキング設定を編集します。Google ドラフト＆エクスペリメントキャンペーンがない場合は、新しい形式への移行は任意です。注：新しい Google アカウントはすべて、自動的に新しい形式を使用します。 |
| アドバンスキャンペーン管理（ACM）の検索 | （Google 広告キャンペーン）Google テキスト広告およびショッピング広告テンプレートに対して、キャンペーンレベルで最終ページ URL のサフィックスを設定できるようになりました。 |
|  | （Google 広告キャンペーン）Google の拡張テキスト広告で、「ヘッドライン3」と「説明2」のオプションのフィールドを使用できます。 |
| レポート | 次の Bing Ads インプレッション共有指標は、最新の Bing Ads API で提供が終了したので、10 月 11 日以降は収集されません：Search IS% Lost to Rank、Search IS% Lost to Bid (Bing)、Search IS% Lost to Page Relevance (Bing)、および Search IS% Lost to Keyword Relevance (Bing)。以前に収集された指標は、引き続きレポートで使用できます。 |
| Adobe Analytics との統合 | （Adobe Analytics を使用している広告主のみ）Analysis Workspace では、データを収集したことのない「デバイス（AMO ID）」ディメンションは使用できなくなります。オンライン Analytics データに関するレポートを作成するには、「モバイルデバイスタイプ」ディメンションを使用します。デバイスタイプ別の検索エンジントラフィック指標（クリック数、コスト、インプレッション数など）のレポートをおこなうには、引き続き Advertising Cloud 検索でレポートを使用します。 |

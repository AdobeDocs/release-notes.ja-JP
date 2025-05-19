---
title: 最新のリリースノート
description: Adobe [!DNL Experience Cloud] 製品とサービスの最新リリースノートおよびナレッジベースの問題をお読みください。Experience League に関する今後のイベントおよび新しいドキュメントについて説明します。  [!DNL Experience Cloud]  アプリケーションの最新のチュートリアルとコースを確認します。
doc-type: release notes
last-update: May 2025
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: f6585d8fc2f8e927156d7358ce74f393cad8fc1a
workflow-type: tm+mt
source-wordcount: '5424'
ht-degree: 33%

---

# Experience Cloud リリースノート - 2025年5月

<!-- badgeReview: label="Internal Review" type="Negative" -->

<!-- ![Banner](assets/release-notes-header.png) -->

このページは、Experience League に関するアプリケーション固有のリリースノート、今後のイベント、新しいチュートリアル、最新のサポート記事を見つけるのに役立ちます。

<!-- * [Customize your learning](https://experienceleague.adobe.com/en/home/profile-settings): Help us customize your learning experience. Select your role, industry, and the products that interest you.
* [Browse and discover](https://experienceleague.adobe.com/en/browse): Find popular content, new tutorials, documentation, upcoming events, and more!
* [Get fresh perspectives](https://experienceleague.adobe.com/en/perspectives): We've gathered a variety of real-world use cases and best practices, written by your peers and Adobe product experts. 
* [Get certified](https://experienceleague.adobe.com/en/certification-home): The new Adobe Certification Portal makes honing your skills and getting certified a simple process.
* [Engage with a community of peers](https://experienceleaguecommunities.adobe.com/): Join groups, meet our Experience League Community Advisors, and even learn how to become one. -->

このページの更新に関するメール通知を毎月受信するには、[アドビ優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)を購読してください。

**更新日：2025 年 5 月 19 日（PT）**

+++製品リンクを表示

* [[!DNL Adobe System Status]](#status)
* [[!DNL Adobe Experience Cloud] - 一元的なインターフェイスと管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Real-Time CDP]](#rtcdp)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Adobe Customer Journey Analytics]](#cja)
* [[!DNL Adobe Streaming Media Analytics]](#sma)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Journey Optimizer B2B Edition]](#ajo-b2b)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe GenStudio for Performance Marketing]](#genstudio-marketing)
* [[!DNL Adobe Mix Modeler]](#mix-modeler)
* [[!DNL Adobe Advertising]](#advertising)
* [[!DNL Adobe Pass]](#pass)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [顧客データ管理 - 担当者の声](#voices)
* [デジタルエクスペリエンスブループリント](#blueprints)
* [アドビでの認定](https://experienceleague.adobe.com/ja/certification-home)
* [アドビ製品のセキュリティの脆弱性](https://helpx.adobe.com/jp/security.html)

+++

## [!DNL Experience League] のイベント {#events}

興味のある[イベント](https://experienceleague.adobe.com/ja/events)を見つけて登録してください。

+++今後のイベント

* **[!DNL Workfront]** | _CreativeでWorkfrontのリソースを管理する方法_ | リソースプランナーやワークロードバランサーなどの従来のツールに依存せずにWorkfrontでリソースを管理する方法を学びたいと考えていますか？ もしそうなら、このセッションはあなたのためです！ | **5 月 20 日火曜日** | [ 登録 ](https://events.teams.microsoft.com/event/126180b0-7153-414f-8ef3-a2bbc53176bb@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Commerce]** | _Commerceとコーヒー：SEO による成長の促進_ |本セッションでは、Commerce上級戦略顧問の Corey Gelato 氏と、Commerce戦略顧問の Agbi Bajrushi 氏が、SEO について深く掘り下げます。 | **5 月 21 日水曜日（PT）** | [ 登録 ](https://events-emea5.adobeconnect.com/content/adobeconnect/43/5415868397/en/events/event/shared/5750600822/event_landing.html?sco-id=5750592916&amp;campaign-id=ExL&amp;_charset_=utf-8)

* **[!DNL Workfront]** | _迅速に立ち上げ、スマートに拡張：Workfrontプランニングでチームレベルの成功を実現_ |企業全体で新しい計画ソリューションを展開すると、今すぐ作業を完了したいチームのニーズから切り離され、コストがかかり、遅くなり、大騒ぎになったように感じる可能性があります。 このセッションでは、連邦政府と州政府の実装モデルを展開し、早期導入者がWorkfront プランニングを使用して企業全体のコンセンサスを待たずに価値を迅速に得ている方法を示します。  | **5 月 28 日水曜日（PT）** | [ 登録 ](https://events.teams.microsoft.com/event/2fa2a2f4-ada5-4810-9014-aa7fe34d0354@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Workfront]** | _Workfront Data Connect の機能を活用_ | Workfront レポートを次のレベルに引き上げますか？ Ultimate パッケージに含まれていますが、Select またはPrimeのお客様向けのアドオン（$）として使用できます。この 1 時間ウェビナーはAdobe Workfront Product Management とのパートナーシップでホストされ、Data Connect と機能を紹介します。  | **5 月 29 日木曜日** | [ 登録 ](https://events.teams.microsoft.com/event/5adb7454-e13d-408d-a430-eb3a69a08510@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Experience Manager Guides]** | _Adobe ディタワールド 2025_ | 2025 年 6 月 3 日～5 日の 3 日間、業界の専門家によるプレゼンテーションと業界の同業者との素晴らしいチャットで参加する計画を立ててください。 | **6 月 3～5 日** | [ 登録 ](https://2025-adobe-dita-world.meetus.adobeevents.com/?utm_campaign=community_forum&amp;utm_source=experience_league)

* **[!DNL Workfront]** | _Workfrontで目を覚ます：最適化して昇格。 Adobe Workfront インスタンスの監査と調整_ |説明 | **月、日@午前 10:00 MT** | [ 登録 ](https://events-emea5.adobeconnect.com/content/adobeconnect/43/5415868397/en/events/event/shared/5748588430/event_landing.html?sco-id=5748605291&amp;campaign-id=ExL&amp;_charset_=utf-8)

Experience League の[今後](https://experienceleague.adobe.com/ja/events)のイベントと[オンデマンド](https://experienceleague.adobe.com/ja/docs/events/experience-league-recorded-events/overview)イベントの完全なリストを表示します。

+++

## [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] では、アドビ製品およびサービスに関する詳細情報、ステータス更新およびメール通知を提供します。停止、中断およびメンテナンスイベントに関する通知を受け取れます。[status.adobe.com/ja](https://status.adobe.com/ja) でご確認ください。

+++リリースノート

[!DNL Adobe System Status] の以前のリリースノート：

* [2025 年 4 月 ](https://experienceleague.adobe.com/en/docs/release-notes/experience-cloud/previous/2025/04162025#status)
* [2024年8月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2024/09142023#status)
* [2024年5月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2024/05152024#status)
* [2024年1月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2024/02142024#status)
* [2023年10月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2023/10042023#status)
* [2023年8月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2023/08092023#status)
* [2023年3月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2023/03082023#status)
* [2023年1月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2023/02082023#status)

+++

## [!DNL Experience Cloud] – 主要なインターフェイスと管理 {#ecloud}

[!DNL Experience Cloud] 管理インターフェイスと中央インターフェイスコンポーネントの更新について説明します。

+++新機能

5 月は更新はありません。

以下に関するヘルプについて詳しくは、[Experience Cloud インターフェイスおよび管理](https://experienceleague.adobe.com/ja/docs/core-services/interface/experience-cloud)ガイドを参照してください。

* User management と product licenses （Admin Console）
* Experience Cloud アプリケーションのジェネレーティブ AI
* 顧客属性とオーディエンスライブラリ
* Experience Cloud のアセット
* Experience Cloud の Cookie

+++

## [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] と [!UICONTROL Mobile SDK] の最新リリース情報と新規ドキュメントについて説明します。新しいチュートリアルとナレッジベースのサポート記事を参照してください。

+++リリースノート、チュートリアル、サポート記事

* [[!DNL Experience Platform] リリースノート](https://experienceleague.adobe.com/ja/docs/experience-platform/release-notes/latest)

* [[!DNL Experience Platform] Mobile SDK リリースノート](https://developer.adobe.com/client-sdks/documentation/release-notes/)

<!-- ### New [!DNL Experience Platform] tutorials{#tutorials-aep}

New tutorials published for Adobe [!DNL Experience Platform] on Experience League.

| Published | Applications | Name | Type | Description |
| ----------| ---------- | ---------- | ---------- |---------- |
|April 2025| [!DNL Experience Platform] | [Evaluate batch audiences on demand](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/audiences/evaluate-audiences-on-demand)| New video | Evaluate batch audiences on demand with flexible audience evaluation. |
|April 2025| [!DNL Experience Platform] | [Migrate a mobile app from Target to Journey Optimizer](https://experienceleague.adobe.com/en/docs/platform-learn/migrate-target-to-mobile-sdk-decisioning/overview)| New video | Learn how to migrate your mobile app implementation from the Adobe Target to the Adobe Journey Optimizer - Decisioning extension|
|April 2025| [!DNL Experience Platform] | [Configure a dataset export destination in Experience Platform](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/destinations/configure-dataset-export-destination)| Updated video | Learn about the configuration, workflow, and use cases for exporting datasets from Adobe Experience Platform to a cloud storage location using a destination connection. |
 -->

### 新しい [!DNL Experience Platform] でのナレッジベースのサポート{#kb-aep}

[!DNL Experience Platform] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年4月 | [AEP：アクティブ化率は高いものの  [!DNL TikTok]  宛先のオーディエンス量が少ない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26380) | 新しい記事 | Adobe [!DNL Experience Platform] （AEP）の宛先が、高いアクティベーション率（約 99%） [!DNL TikTok] もかかわらず、オーディエンス量が少ないと報告する問題の解決策について説明します。 |
| 2025年4月 | [Adobeでのデータセット書き出しの問題の解決  [!DNL Experience Platform]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26413) | 新しい記事 | API で作成されたデータセットの制限により、Adobeでのデータセット書き出し [!DNL Experience Platform] 問題が発生した場合の解決策について説明します。 |
| 2025年4月 | [Adobeでのバッチ取り込みエラーと重複取り込みの解決  [!DNL Experience Platform]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26349) | 新しい記事 | Adobe [!DNL Experience Platform] でのバッチ取得が重複取得の作成中に失敗する問題の解決策について説明します。 |
| 2025年4月 | [[!DNL Snowflake] Adobeでのコネクタ認証エラー  [!DNL Experience Platform]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26294) | 新しい記事 | Adobe [!DNL Experience Platform] （AEP）および [!DNL Snowflake] で秘密鍵の形式や設定の問題が原因で認証に失敗した場合の、この問題の解決策について説明します。 |
| 2025年4月 | [*406 （受け入れられません）* コンテンツテンプレートの昇格時にエラーが発生しました ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26320) | 新しい記事 | API ヘッダーを調整して、Adobe [!DNL Experience Platform] の [!UICONTROL Journey Orchestration] で発生した *406 （受け入れられません）* エラーを解決する方法を説明します。 |
| 2025年4月 | [AEP - HTTP API 宛先とDestination SDKの違いは何ですか？](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26316) | 新しい記事 | HTTP API Destination とDestination SDKが機能と目標でどのように異なるか、およびどのように異なるかについて説明します。 |

+++

## [!DNL Real-Time CDP] {#rtcdp}

[!DNL Real-Time CDP] の最新のチュートリアルをご確認ください。

+++新しいチュートリアル

| 公開日 | 名前 | タイプ | 説明 |
| ----------| ---------- | ---------- |---------- |
| 2025年5月 | [Azure Blob 宛先の設定](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination) | 更新されたビデオ | 接続を設定し、[!DNL Real-Time Customer Data Platform] で Azure Blob ストレージの宛先にデータを送信する方法を説明します。 この宛先では、データセットとオーディエンスの書き出しをサポートしており、ファイルヘッダーとデータ属性をカスタマイズできます。 |

詳しくは、次を参照してください。

* ビデオチュートリアル：[Real-Time Customer Data Platform について](https://experienceleague.adobe.com/ja/docs/platform-learn/tutorials/rtcdp/understanding-the-real-time-customer-data-platform)

* 製品ドキュメント：[Real-Time Customer Data Platform](https://experienceleague.adobe.com/ja/docs/real-time-customer-data-platform)

+++

## [!DNL Analytics] {#analytics}

[!DNL Adobe Analytics] と [!DNL AppMeasurement] の最新のリリース情報を確認してください。新しいチュートリアルとサポート記事を参照してください。

+++リリースノートと新しいチュートリアル

[!DNL Analytics] リリース日：**2025年5月14日（PT）**

* [!DNL Analytics] [リリースノート](https://experienceleague.adobe.com/ja/docs/analytics/release-notes/latest)

* [!DNL Analytics] [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/ja/docs/analytics)

### AppMeasurement {#appm}

* [JavaScript 版 AppMeasurement リリースノート](https://github.com/adobe/appmeasurement/releases)

<!-- ### New Analytics tutorials {#tutorials-analytics}

New or updated video tutorials published for Adobe Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|April 2025|[Configure variables in Report Suite Manager](https://experienceleague.adobe.com/en/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-variables-in-the-admin-console)| New video |Configure variables and events in [!UICONTROL Report Suite Manager], ensuring that the reports, dimensions, and metrics have the right names and behavior.| -->

+++

## [!DNL Customer Journey Analytics] {#cja}

[!DNL Customer Journey Analytics] の最新のリリース情報をご確認ください。Experience League で新しいチュートリアルを参照してください。

+++リリースノートと新しいチュートリアル

* [リリースノート](https://experienceleague.adobe.com/ja/docs/analytics-platform/using/releases/latest#releases)

  [!DNL Customer Journey Analytics] のリリースは継続的に行われます。 そのため、リリースノートは月に数回更新されます。 定期的に確認してください。

* [ 製品ドキュメントとチュートリアル ](https://experienceleague.adobe.com/ja/docs/customer-journey-analytics)

### 新しい [!DNL Customer Journey Analytics] チュートリアル {#tutorials-cja}

[!DNL Customer Journey Analytics] の新しいチュートリアルが公開されました。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年5月 | [[!UICONTROL  クイックインサイト ] パネルの使用 ](https://experienceleague.adobe.com/en/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/panels/use-the-quick-insights-panel) | 新しいビデオ | [!DNL Customer Journey Analytics] の _[!UICONTROL クイックインサイト]_ パネルを使用して、ビジネス上の質問にすばやく簡単に回答する方法を説明します。 |

+++

## [!DNL Streaming Media Analytics] {#sma}

[!DNL Streaming Media Analytics] の最新のリリース情報をご確認ください。Experience League で新しいチュートリアルを参照してください。

+++リリースノート

更新はありません。

* [!DNL Streaming Media Analytics] [リリースノート](https://experienceleague.adobe.com/ja/docs/media-analytics/using/release-notes/release-notes)

* [!DNL Streaming Media Analytics] [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/ja/docs/media-analytics/using/media-overview)

+++

## [!DNL Experience Manager] {#aem}

[!DNL Experience Manager] の新機能、修正点および更新。アドビでは、安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

+++リリースノート、新しいチュートリアル、サポート記事

### Experience Manager リリース情報

[!DNL Experience Manager as a Cloud Service] メンテナンスリリース [2025.4.0](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current)。

次回の予定リリースは **2025 年 6 月 5 日** です。

[!DNL Experience Manager] のリリースノートはすべて次のページに記載されています。

* [ [!DNL Experience Manager] as a Cloud Serviceの最新のリリースノート ](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current)
* [最新リリースの概要ビデオ](https://experienceleague.adobe.com/ja/docs/events/aemcs-release-update-recordings/overview)
* [[!DNL Experience Manager] リリースの更新とロードマップ](https://experienceleague.adobe.com/ja/docs/experience-manager-release-information/aem-release-updates/home)
* [[!DNL Experience Manager]  6.5 サービスパックリリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-65/content/release-notes/release-notes)
* [[!DNL Experience Manager]  Cloud Manager リリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-manager/content/release-notes/current)
* [自動フォーム変換サービスリリースノート](https://experienceleague.adobe.com/ja/docs/aem-forms-automated-conversion-service/using/release-notes)
* [[!DNL Experience Manager]  Assets Dynamic Media リリースノート](https://experienceleague.adobe.com/ja/docs/dynamic-media-developer-resources/release-notes/s7rn2017)
* [[!DNL Experience Manager]  Brand Portal リリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes)
* [[!DNL Experience Manager]  デスクトップアプリケーションリリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-desktop-app/using/release-notes)
* [[!DNL Experience Manager]  Dispatcher リリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-dispatcher/using/getting-started/release-notes)

### 新しい [!DNL Experience Manager] チュートリアル {#tutorials-aem}

[!DNL Experience Manager] の [!DNL Experience Manager] 向けに新しいチュートリアルが公開されました。

| 公開日 | アプリケーション | 名前 | タイプ | 説明 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2025年5月 | [!DNL Experience Manager Sites] | [AEM Sitesのビデオとチュートリアル ](https://experienceleague.adobe.com/en/docs/experience-manager-learn/sites/overview) | 更新されたチュートリアルホーム | Adobe Experience Manager Sitesの特長と機能に関するビデオとチュートリアルをご覧ください。 AEM Sitesは、優れた experience management platform です。 |
| 2025年5月 | [!DNL Experience Manager as a Cloud Service] | [OpenAPI ベースの AEM API の設定](https://experienceleague.adobe.com/ja/docs/experience-manager-learn/cloud-service/aem-apis/openapis/setup) | 新しいビデオ | AEM as a Cloud Service環境を設定して、OpenAPI ベースのAEM API へのアクセスを有効にする方法について説明します。 |
| 2025年5月 | [!DNL Experience Manager Forms] | [ アダプティブ Forms ブロックを使用したフォームの作成 ](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/edge-delivery/build-forms/getting-started-edge-delivery-services-forms/create-forms) | 新しいビデオ | Edge Delivery Services for AEM Formsの基本を学びます。 完璧なフォームを素早く作成！ AEM Forms Edge Deliveryのドキュメントベースのオーサリング =かつてないスピードと SEO に対応したフォームで、よりハッピーなユーザーと検索エンジンを実現。 |
| 2025年5月 | [!DNL Experience Manager Sites] - ヘッドレス | [AEM ヘッドレスの高度な概念 ](https://experienceleague.adobe.com/en/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/advanced-tutorial/overview) | 新しいビデオ | Adobe Experience Manager（AEM）GraphQL API の高度な概念を説明したエンドツーエンドチュートリアルです。 |

### 新しい [!DNL Experience Manager] でのナレッジベースのサポート{#kb-aem}

[!DNL Experience Manager] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|--------|---------|---------|
| 2025年4月 | [ ワークフローインスタンスが実行中ステータスでスタックする ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26078) | 新しい記事 | ワークフロー（WF）インスタンスが長時間実行中のステータスのままになる場合の問題の解決策について説明します。 |
| 2025年4月 | [ ワークフローが古いためにAEMでパフォーマンスが遅くなる問題の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26369) | 新しい記事 | でオーサー環境の速度が遅く、古いワークフローインスタンスが多すぎると [!DNL Adobe Experience Manager (AEM) Sites] この問題の解決策について説明します。 |
| 2025年4月 | [VPN の作成後、*java.net.UnknownHostException でトラフィックの送信が失敗します*](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26374) | 新しい記事 | VPN が作成され、ステータスが *準備完了* であるが、トンネルを介したトラフィックの送信が *java.net.UnknownHostException* で失敗する場合の問題の解決策について説明します。 |
| 2025年4月 | [ACS AEM[!UICONTROL Commons コピープロパティ ] の修正：プロセスステップの失敗 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26327) | 新しい記事 | プロセスリソースの設定がないことが原因で ACS AEM[!UICONTROL Commons Copy プロパティ ] のプロセスステップが失敗する場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Experience Manager as a Cloud Service: HTTP から HTTPS へのトラフィック リダイレクト ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26336) | 新しい記事 | AEM as a Cloud Serviceがすべてのトラフィックを HTTP から HTTPS に自動的にリダイレクトする際の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Experience Manager as a Cloud Service: [!DNL Adobe I/O Projects]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26337) の *[!UICONTROL イベント]* 設定の [!UICONTROL  読み取り専用 ] ステータス | 新しい記事 | [!DNL Adobe Developer Console] [!DNL (Adobe I/O Projects)] 内で、新しい **[!UICONTROL イベント]** 設定でAEM as a Cloud Serviceの選択オプションが表示されない、または既存の **[!UICONTROL イベント]** 設定が *[!UICONTROL 読み取り専用]* ステータスでロックされている場合の問題の解決策を説明します。 |
| 2025年4月 | [Adobe Experience Managerでのコンテンツツリーの並べ替えの修正 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26241) | 新しい記事 | Adobe Experience Manager（AEM）のディレクトリが 1,000 個を超えると、並べ替え動作が予期せず変化する問題の解決策について説明します。 |
| 2025年4月 | [AEMでのビデオファイルのオーディオ  [!DNL Dynamic Media]  問題の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197) | 新しい記事 | Adobe Experience Manager as a Cloud Service（AEMaaCS）で [!DNL Dynamic Media] を使用する際にビデオファイルでオーディオ同期の問題を解決する方法を説明します。 |
| 2025年4月 | [AEM as a Cloud Serviceでの無効なユーザー偽装エラーの解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26118) | 新しい記事 | [!DNL Adobe Experience Manager as a Cloud Service - Sites] で *無効なユーザー* エラーが発生して偽装が失敗した場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Experience Manager（AEM）  [!DNL Microsoft Translation Service]  セットアップできない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26096) | 新しい記事 | Adobe Experience Manager（AEM）as a Cloud Serviceで [!DNL Microsoft Translation Service] を設定する際の問題の解決策について説明します。[!DNL Microsoft Azure] で提供されるエンドポイントとキーは、[!DNL AEM Translation] 設定フォームで認識されません。 |
| 2025年4月 | [AEM環境のヘルスステータスの監視 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25893) | 新しい記事 | ビルトインのヘルスチェックエンドポイントを使用して、AEM環境のヘルスをプログラムで監視する方法について説明します。 |
| 2025年4月 | [Adobe Targetへのコンテンツフラグメントの書き出しの問題を解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26167) | 新しい記事 | Adobe Experience ManagerからAdobe Targetにコンテンツフラグメントを書き出す際に発生する *Adobe Targetとの同期に失敗しました* エラーの解決策について説明します。 |
| 2025年4月 | [ [!DNL Time-to-Live]  （TTL）キャッシングによるAEM パブリッシュサーバーの高負荷の問題の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26393) | 新しい記事 | [!DNL AEMaaCS - Sites] での 5 分間の TTL キャッシュ戦略によってAEM パブリッシュサーバーのパフォーマンスが急増した場合の問題の解決策について説明します。 |
| 2025年4月 | [AEM Cloud Service の製品リストコンポーネントにおける製品選択の制限 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26019) | 新しい記事 | Adobe Experience Manager（AEM）Cloud Serviceの商品リストコンポーネントで「**[!UICONTROL すべてを選択]**」チェックボックスを使用しても 20 個を超える商品（SKU）を追加できない問題の解決策について説明します。 |
| 2025年4月 | [ に新しくアップロードされたアセットの自動タグ付け  [!DNL AEMaaCS - Assets]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) | 新しい記事 | 新しくアップロードされたアセットが標準の向きタグで自動的にタグ付けされ、既存のメタデータ管理プラクティスに影響を与える [!DNL AEMaaCS - Assets] の問題を解決する方法を説明します。 |
| 2025年4月 | [Adobe Experience Manager（AEM）as a Cloud Serviceでの誤ったコンテンツ提供の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25922) | 新しい記事 | Adobe Experience Manager（AEM）as a Cloud Serviceのデプロイメント内での設定の競合が原因で、誤ったコンテンツが提供された場合の問題の解決策について説明します。 |

+++

## [!DNL Commerce] {#commerce}

[!DNL Adobe Commerce] のリリースノート、新しいチュートリアルおよびナレッジベースサポート記事にアクセスできます。

+++リリースノート、新しいチュートリアル、サポート記事

* 最新情報について詳しくは、最新の [ [!DNL Adobe Commerce]  および  [!DNL Magento Open Source]](https://experienceleague.adobe.com/ja/docs/commerce-operations/release/notes/overview)のリリースノートを参照してください。
* Commerce サービスのリリース情報とドキュメントを確認するには、[Adobe [!DNL Commerce] サービスガイド](https://experienceleague.adobe.com/ja/docs/commerce/user-guides/home)を参照してください。
* 個々の製品のリリースノートにアクセスして可用性を確認する方法について詳しくは、[製品の可用性](https://experienceleague.adobe.com/ja/docs/commerce-operations/release/product-availability)を参照してください。

### [!DNL Adobe Commerce] の新しいチュートリアル {#tutorials-commerce}

Experience League に関する [!DNL Adobe Commerce] の新しいチュートリアル。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年5月 | [ 成功アクセラレータの組織対応 ](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-organizational-readiness) | 新しいビデオ | Adobeの組織対応サクセスアクセラレーターについて説明します。 |
| 2025年5月 | [Commerce サポートアドオン ](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/commerce-support-add-ons) | 新しいビデオ | Expert Success、Ultimate Success、戦略的支援のための様々なアドオンなど、強化されたカスタマーサポートプランについて説明します。 |
| 2025年5月 | [Expert Successとは？](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/what-is-expert-success) | 新しいビデオ | Adobe Commerce エキスパート success planについて説明します。 3 つのサポートチャネルとサービスレベルターゲットを含む詳細について説明します。 |
| 2025年5月 | [Success アクセラレータの技術対応 ](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-technical-readiness) | 新しいビデオ | 最適なパフォーマンスを得るための、Commerce Success Accelerator の技術対応、ソリューションレビュー、イベント計画、24 時間年中無休のモニタリングについて説明します。 |
| 2025年5月 | [ サクセスアクセラレーターの採用と有効化 ](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-adoption-and-enablement) | 新しいビデオ | 戦略的開発、スキル強化、ガバナンスのためのAdobe Commerce Success Accelerator の採用とイネーブルメントについて説明します。 |
| 2025年5月 | [Ultimate Successとは？](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/what-is-ultimate-success) | 新しいビデオ | Adobe Commerce Ultimate Successのプロアクティブなサポートと、高パフォーマンスのデジタルエクスペリエンスに対する戦略的ガイダンスについて説明します。 |
| 2025年5月 | [ テクニカルオンボーディング - SaaS 製品 ](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/adobe-commerce-cloud/technical-onboarding-hardware-handoff/saas-offerings-support-communications-next-steps) | 新しいビデオ | Adobe Commerce Cloud の SaaS 製品、サポート、その他のコミュニケーションおよび一部の次の手順について説明します。 |

### 新しい [!DNL Commerce] のナレッジベースへのサポート{#kb-commerce}

Adobe Commerce の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|--------|---------|---------|
| 2025年4月 | [[!DNL Quality Patches Tool]  （QPT） ](https://experienceleague.adobe.com/ja/docs/commerce-operations/tools/quality-patches-tool/patches-available-in-qpt/patches-available-in-qpt-tool-overview) | 新しい記事 | QPT 1.1.60、QPT 1.1.61 および QPT 1.1.62 で使用可能なパッチの適用方法に関する新しい記事が公開され、それぞれの節で参照できるようになりました。 |
| 2025年4月 | [APSB25-08 セキュリティパッチ後のすべての一括非同期 web エンドポイントの実行時間が長くなりました ](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/increased-execution-time-for-bulk-asynchronous-web-endpoints-post-apsb25-08-security-patch) | 新しい記事 | この記事では、1,000 以上のエントリを持つ `POST rest/all/async/bulk/V1/products` など、APSB25-08 セキュリティパッチを適用した後に実行時間が大幅に長くなる、すべての一括非同期 web エンドポイントのホットフィックスを提供します。 |
| 2025年4月 | [B2B 1.5.2`Magento_Company` 更新後のモジュールのアップグレードにおけるパフォーマンスの問題 ](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/troubleshooting/installation-and-upgrade/magento-company-module-upgrade-performance-issue) | 新しい記事 | この記事では、B2B 1.5.2 へのアップデート後に `Magento_Company` モジュールをアップグレードする際のパフォーマンスの問題に関するホットフィックスを提供し、`company_structure` テーブル内の大規模なデータセット（100,000 件以上のレコード）の処理時間が非常に長くなる問題に対処します。 |
| 2025年4月 | [B2B 1.5.2 へのアップグレードが、`REGEXP_LIKE` 関数がないために SQL 構文エラーで失敗します ](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/troubleshooting/installation-and-upgrade/sql-syntax-error-due-to-missing-regexp-like-function) | 新しい記事 | この記事では、`company_structure` テーブルを更新しようとしたときに `REGEXP_LIKE` 関数が見つからなかったことが原因で発生する SQL 構文エラーのホットフィックスを示します。 |
| 2025年4月 | [*Cookie の最大数を超える可能性があります* Adobe Commerceのエラー ](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/maximum-number-of-cookies-would-be-exceeded-error) | 新しい記事 | この記事では、Adobe Commerceの *最大数を超えると cookie が表示される* というエラーを解決するパッチを提供します。 |
| 2025年4月 | クラウドインフラストラクチャー上のAdobe Commerceで「無効」状態を表示している [[!DNL Web Application Firewall]  （WAF） [!UICONTROL  管理者 ] インターフェイス ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26387) | 新しい記事 | クラウドインフラストラクチャー上のAdobe Commerceの [!DNL Web Application Firewall] （WAF）が有効で正しく機能しているにもかかわらず、[!UICONTROL  管理者 ] 側で無効のように表示される場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Commerce セキュリティパッチのクラウドデプロイメントの失敗の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26408) | 新しい記事 | Cloud Infrastructure 上のAdobe Commerceでサポートされていないバックエンドキャッシュ設定が原因で、デプロイメントエラーが発生した場合の問題の解決策について説明します。 |
| 2025年4月 | [Cloud Infrastructure 上のAdobe Commerceでログバッファーがいっぱいになったエラーを解決する ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26382) | 新しい記事 | ログバッファーがいっぱいになり、サイトの停止中にアクセスログリクエストが切り詰められる問題の解決策について説明します。 |
| 2025年4月 | [Cloud Infrastructure 上のAdobe Commerceでのデータベースダンプエラーのトラブルシューティング ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26385) | 新しい記事 | `magento-cloud db:dump` エラーを解決してデータベースのダンプを正常に実行する方法を説明します。 |
| 2025年4月 | [ スキャン結果へのアクセ  [!DNL Security Scan Tool]  に関する問題の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26357) | 新しい記事 | Adobe Commerce [!DNL Security Scan Tool] でマルウェアや重大な問題が検出されても、スキャン結果にアクセスできない状況の対処方法を説明します。 |

+++

## [!DNL Target] {#target}

[!DNL Adobe Target] のプレリリースノート、現在のリリースノートおよび新しいチュートリアルにアクセスできます。

+++リリースノート

<!-- ### New [!DNL Target] support knowledge base{#kb-target}

|Published|Name|Type|Description|
|---------|----|----|-----------|
|July 2024|[[!DNL Adobe Target] bulk profile update [!DNL API] throws *[!DNL Unexpected Error]* when using [!DNL Postman]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24281)|New article| Learn about how to fix the issue when running the [!DNL Target Bulk Profile Update API] throws the *[!DNL Unexpected Error]* message in [!DNL Postman].|
-->

* プレリリース情報については、[[!DNL Adobe Target] プレリリース](https://experienceleague.adobe.com/ja/docs/target/using/release-notes/target-release-notes)を参照してください。
* 現在の情報については、[[!DNL Adobe Target] リリースノート](https://experienceleague.adobe.com/ja/docs/target/using/release-notes/release-notes)を参照してください。

+++

## [!DNL Campaign] {#ac}

[!DNL Adobe Campaign] の最新のアップデート情報を取得できます。Experience League で新しいチュートリアルとナレッジベースのサポート記事を確認してください。

+++リリースノートとサポート記事

### 最新の Campaign 製品リリース

* [!DNL Web User Interface]: 2025 年 5 月 – [ リリースノート ](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/release-notes/release-notes) | [ 製品ドキュメント ](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/campaign-web-home)

* [!DNL Campaign] v8: 2025 年 4 月 25 日（PT） - [ リリースノート ](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/releases/release-notes#release-8-7-4) | [ 製品ドキュメント ](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/campaign-home)

* [!DNL Campaign Standard]：25.1：[リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-standard/using/release-notes/release-notes) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-standard/using/campaign-standard-home)

* [!DNL Campaign Classic] 7.4.2：2025年5月12日（PT）[リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-classic/using/release-notes/latest-release#release-7-4-2) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-classic/using/campaign-classic-home)

<!-- ### New [!DNL Campaign] tutorials {#tutorials-campaign}

New or updated videos tutorials published for Adobe Campaign.

| Published | Application | Name | Type | Description |
| ----------| ---------- | ---------- | ---------- |---------- |
|January 2025| |[Create and manage test profiles](https://experienceleague.adobe.com/en/docs/campaign-web-learn/tutorials/profiles-and-audiences/create-and-manage-test-profiles)|New video |Learn how to create a test profile in the client console and how to manage, and edit profiles in the Adobe Campaign Web UI.|
|January 2025| |[Enhance a delivery with dynamic content](https://experienceleague.adobe.com/en/docs/campaign-web-learn/tutorials/content-management/enhance-a-delivery-with-dynamic-content)|New video |Learn how to make message content dynamic by using the expression editor to personalize your message or add conditional content.| -->

### 新しい [!DNL Campaign] でのナレッジベースのサポート{#kb-campaign}

[!DNL Campaign] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年4月 | [URL マーカーを追跡は、Adobe Campaignの適切な URL を置き換えます ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26309) | 新しい記事 | Adobe Campaignのトラッキング URL マーカーの問題の解決策について説明します。 |
| 2025年4月 | [ ファイルの抽出中に列挙のラベルを書き出しが機能しません ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26155) | 新しい記事 | Adobe Campaign ワークフローで列挙ラベルが正しく書き出されない問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign Standardでの内部メールアドレスの強制隔離ルールの管理 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26334) | 新しい記事 | 内部メールアドレスが強制隔離テーブルに追加され、重要な通信がブロックされた場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign Classicでパスワードを変更した後の問題の解決  [!DNL Snowflake] [!UICONTROL  データ読み込み ]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26368) | 新しい記事 | Adobe Campaign Classicの [!DNL Snowflake] 接続で **[!UICONTROL 外部アカウント]** のパスワードをアップデートすると、新しい [!UICONTROL  データ読み込み ] アクティビティで問題が発生する問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign Classic フォルダーで検索フィルターを表示できない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26160) | 新しい記事 | Adobe Campaign Classic Hosted （v7）の特定のフォルダー内に検索フィルターが表示されない問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign Classicでの E メール配信の開封率の低下 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26266) | 新しい記事 | ワークフローやコンテンツは変更されていないのに、メール配信の開封率が低下した場合の問題の解決策について説明します。 |
| 2025年4月 | [ にログインできません  [!DNL Adobe Campaign Managed Cloud]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26119) | 新しい記事 | [!DNL Adobe Campaign Managed Cloud] にログインすると、「不明な認証モード：ネゴシエート *というエラーメッセージが表示される問題の解決策を説明* ます。 |
| 2025年4月 | [ メールシードが、インボックスでは送信されたが受信されなかったと表示される ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26162) | 新しい記事 | Adobe Campaign経由で送信されたメールが配信ログには表示されるが、受信者のインボックスには迅速に受信されない問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaignでのフォルダー表示の問題の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26292) | 新しい記事 | Adobe Campaign Classic インスタンスに特定のフォルダーが表示されない場合の問題の解決策について説明します。 |
| 2025年4月 | [ でのロードバランサー URL の問題を解決  [!DNL Adobe Campaign Classic Hosted]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26264) | 新しい記事 | アプリ統合のロードバランサー URL が失敗し、HTTPS リクエストの設定が不適切なために 401 エラーが発生した場合の、[!DNL Adobe Campaign Classic Hosted] の問題の解決策について説明します。 |

+++

## [!DNL Journey Optimizer] {#journey-opt}

[!DNL Journey Optimizer] の最新のリリース情報について説明します。Experience League で最新のチュートリアルおよびナレッジベースのサポート記事を確認してください。

+++リリースノートと新しいチュートリアル

### [!DNL Journey Optimizer] 製品リリースのアップデート

最新リリース：**2025 年 5 月**

* アップデートおよびヘルプについては、[Journey Optimizer リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes)を参照してください

**注意：** [B2B edition用Journey Optimizer](#journey-optimizer-b2b-edition) は別売りです。

### 新しい [!DNL Journey Optimizer] チュートリアル {#tutorials-ajo}

Experience League に関する Adobe [!DNL Journey Optimizer] の新しいチュートリアルが公開されました。

| 公開日 | アプリケーション | 名前 | タイプ | 説明 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2025年5月 | [!DNL Journey Optimizer] | [ オーケストレーションをJourney Optimizerのオムニチャネルエンゲージメントに拡張 ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/scaling-orchestration-to-omnichannel-engagement/introduction) | 新しいビデオ | ビジネスコミュニケーションを、基本的なアウトバウンドメッセージから高度なオムニチャネルエクスペリエンスに変換する方法を説明します。 実践的な例を通じて、プロアクティブなアウトリーチとレスポンシブエンゲージメントを組み合わせたカスタマージャーニーを作成します。 元々は、Adobe Summit 2025 で Lab L535 として発表されていました。 |
| 2025年5月 | Journey Optimizer | [トリガーの毎日のジャーニーは、バッチセグメント化の完了後に実行され ](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/create-journeys/trigger-daily-journey-runs-after-batch-segmentation-completion) す。 | 新しいビデオ | セグメント化ジョブの完了後にのみ開始するようにオーディエンスジャーニーの読み取りを設定し、データの精度とコンプライアンスを確保する方法を説明します。 |
| 2025年5月 | Journey Optimizer、Adobe Express | [Adobe Expressでのアセットの編集 ](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/content-management/assets/edit-assets-with-adobe-express) | 新しいビデオ | Adobe Express ツールを使用して Adobe Journey Optimizer でアセットを編集する方法について説明します。 |
| 2025年5月 | [!DNL Journey Optimizer] | [Personalization エディタープレイグラウンド ](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/personalize-content/personalization-editor-playground) | 新しいビデオ | 定義済みコードサンプルの活用、ダミーのプロファイルペイロードの編集、パーソナライゼーションコードの出力のリアルタイムプレビューについて、それぞれの方法を説明します。 |
| 2025年5月 | [!DNL Journey Optimizer]; [!DNL Experience Platform] | [Decisioning を使用した web オファーのパーソナライズ ](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/use-decisioning-to-personalize-web-offers/introduction?lang=en) | 新しい記事 | Journey Optimizer（AJO AEP） [!UICONTROL Decisioning） ] を使用し、[!DNL Experience Platform] に組み込まれたオーディエンスセグメント化を活用して、パーソナライズされたオファーを web ページで提供する方法を説明します。 |
| 2025年5月 | [!DNL Journey Optimizer]; [!DNL Experience Platform] | [Web SDKを使用したオーディエンスの作成 ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/create-audiences-using-web-sdk/introduction) | 新しい記事 | Web フォームを通じてユーザーの環境設定を取得し、そのデータをリアルタイムでAdobe [!DNL Experience Platform] （AEP）に送信し、選択内容に基づいてユーザーをターゲットオーディエンスに動的に選定する方法を説明します。 |

### 新しい [!DNL Journey Optimizer] でのナレッジベースのサポート{#kb-ajo}

[!DNL Journey Optimizer] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年4月 | [ プッシュメッセージがAJOの web URL にリダイレクトされない場合のクリック動作 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26226) | 新しい記事 | クリック時に設定済み web URL にリダイレクトするようにプッシュメッセージを設定しても期待どおりに動作しない問題の解決策について説明します。 |
| 2025年4月 | [Journey Optimizer: `consents.marketing.sms.value=y`](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26258) があるにもかかわらず、トランザクション SMS が配信されません | 新しい記事 | SMS メッセージに応答すると、トランザクションメッセージを含め、その短い数から後続のすべての SMS がブロックされる問題の解決策 `STOP` ついて説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでのオーディエンス母集団の問題を解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26333) | 新しい記事 | コンポーネントやリソースが見つからない、権限に影響を与える、プロビジョニングなど、オーディエンス母集団の問題を解決する方法について説明します。 |
| 2025年4月 | [ の [!UICONTROL  アプリ内チャネル ] に関してレポートできません  [!DNL Customer Journey Analytics]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26206) | 新しい記事 | [!DNL Adobe Customer Journey Analytics] （CJA）内の [!UICONTROL  アプリ内チャネル ] でレポートする際の問題を解決する方法を説明します。 |
| 2025年4月 | [Journey Optimizer：手動のセグメント評価が原因で、オーディエンス数が古くなっています ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26166) | 新しい記事 | ジャーニーに最新の認定済みデータが反映されない問題の解決策について説明します。 |
| 2025年4月 | [ ジャーニーにエントリするプロファイル数とAJOの関連オーディエンスのプロファイル数が一致しない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26253) | 新しい記事 | ジャーニー（特にバッチオーディエンスを使用するジャーニー）にエントリするプロファイル数が、関連するオーディエンスのプロファイル数と一致しない問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでのプロファイル更新エラーの解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26352) | 新しい記事 | ジャーニーの [!UICONTROL  プロファイルを更新 ] ノードを実行した後、特定のフィールド値が正しく更新されないような問題の解決策について説明します。 |
| 2025年4月 | [ キャンペーンがAdobe Journey Optimizerで期待されたファイルを生成しない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26235) | 新しい記事 | 毎日実行した時間の後にダイレクトメールキャンペーンを繰り返し開始すると、その日のメールが処理されない問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでのオファーコレクション作成の問題の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26265) | 新しい記事 | カタログがプロビジョニングされないので、Adobe Journey Optimizer（AJO）内でオファーコレクションを作成する際に問題が発生する問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでのカスタムアクションに対する TLS v1.3 の有効化 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26223) | 新しい記事 | AJOでカスタムアクションの [!DNL Transport Layer Security] （TLS） v1.3 を有効にして、サードパーティシステムに接続する際にデータの整合性とセキュリティを維持する方法について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでオーディエンスを変更した後のジャーニートリガーの問題の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26224) | 新しい記事 | Adobe Journey Optimizer（AJO）のジャーニーが、関連するオーディエンスに変更が加えられるとトリガーされなくなる問題の解決策（結合ポリシーの変更など）について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでクエリからダッシュボードを作成できない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26201) | 新しい記事 | ユーザーがクエリから直接ダッシュボードを作成できない場合の、問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer：多言語機能が取得します *メッセージ検証エラー（CJMMAS - 1069-500）*](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26168) | 新しい記事 | 多言語機能にリンクされた *メッセージ検証エラー（CJMMAS - 1069-500）により* ジャーニーがテストモードに設定されたり公開されたりしない場合の、問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでのイベントキャッピングが原因でプロファイルが終了する ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26018) | 新しい記事 | イベントキャッピングが原因でプロファイルが予期せずジャーニーから離脱し、通信の欠落につながった場合の問題の解決策について説明します。 |
| 2025年4月 | [AJO メールテンプレートでHTML コンポーネントを使用した場合のリンクの動作に不一致 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26221) | 新しい記事 | HTML コンポーネントをメールコンテンツテンプレートに追加する際の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでジャーニーがトリガーされないイベント ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26031) | 新しい記事 | すべての条件が満たされていても、イベントで目的のジャーニーをトリガーに入れることができない場合がある問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer: カスタムアクションの外部サードパーティエンドポイントがタイムアウトしました ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26156) | 新しい記事 | 外部のサードパーティエンドポイントを呼び出すようにAdobe Journey Optimizer（AJO）でカスタムアクションを設定すると、タイムアウトエラーが発生する場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでの [!UICONTROL  エンゲージメント可能なプロファイル ] 数の増加 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26161) | 新しい記事 | Adobe Journey Optimizer（AJO）の [!UICONTROL  エンゲージメント可能なプロファイル ] 数が短期間に大幅に増加する理由について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでの **[!UICONTROL キャッピングルール]** ドロップダウンの問題のトラブルシューティング ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26204) | 新しい記事 | Adobe Journey Optimizer（AJO）の **[!UICONTROL キャッピングルール]** ドロップダウンメニューに関する問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerでのプロファイルのジャーニーからの離脱が早い ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26127) | 新しい記事 | プロファイルが指定されたノードを通過せずにジャーニーから予期せず離脱した場合の問題の解決策について説明します。 |
| 2025年4月 | [!UICONTROL  データストリーム ] 設定に [Adobe Journey Optimizerチェックボックスがありません ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26131) | 新しい記事 | Adobe [!DNL Experience Platform] （AEP）サービスの下の [!UICONTROL  データストリーム ] 設定に「Adobe Journey Optimizer」チェックボックスがない場合の問題の解決策について説明します。 |
| 2025年4月 | Adobe Journey Optimizerで [[!UICONTROL  独自にコーディング **[!UICONTROL モードで ] プリヘッダー]** フィールドが表示されない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26174) | 新しい記事 | **[!UICONTROL メール本文を編集]** 機能の [!UICONTROL  独自にコーディング ] モードで **[!UICONTROL プリヘッダー]** 入力フィールドが表示されない問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizerで **[!UICONTROL Offer Decisioningにアクセスできません]**](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26175) | 新しい記事 | Adobe Journey Optimizer（AJO）を使用してAdobe Targetをアプリケーションに統合すると、**[!UICONTROL Offer Decisioning]** オプションが [!UICONTROL  データストリーム ] 設定内でアクセスできないことを示す警告が表示される問題の解決策について説明します。 |
| 2025年4月 | [ アクセスに関する問題の解決  [!DNL Adobe Journey Optimizer Query Service API]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26196) | 新しい記事 | [!DNL Postman] または類似のツールを使用して [!DNL Adobe Journey Optimizer Query Service API] にアクセスしようとすると、権限が不十分なためにアクセスエラーが発生する問題の解決策について説明します。 |
| 2025年4月 | [AJOで API トリガーのトランザクションメールキャンペーンを設定する際に Mail Exchanger エラーが発生する ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26200) | 新しい記事 | Adobe Journey Optimizer（AJO）で API トリガーのトランザクションメールキャンペーンを設定する際に、メール交換（MX）エラーが原因で新しいチャネル設定を作成できない場合の問題の解決策について説明します。 |
| 2025年4月 | [Journey Optimizer：日付関数の設定 `AFTER` 誤ると、意図しないオーディエンスにメールが送信される ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26173) | 新しい記事 | Adobe Journey Optimizer（AJO）の `AFTER` 日付関数の設定の誤りの問題の解決策を説明します。これにより、対象オーディエンスに該当しないメンバーにメールが送信されます。 |
| 2025年4月 | [AJO内のファイルのルーティング  [!DNL Azure]  確立できない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26323) | 新しい記事 | Adobe Journey Optimizer（AJO）から [!DNL Azure] への [!UICONTROL delivery management] （DM）出力ファイルのファイルルーティングを設定する際に、[!DNL Azure] 接続文字列とコンテナの設定が正しくないことが原因でエラーが発生する問題の解決策について説明します。 |
| 2025年4月 | [ イベント条件を満たしているにもかかわらず、ジャーニーがプロファイルのトリガーにならない ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26305) | 新しい記事 | Adobe [!DNL Experience Platform] の（AEP） [!DNL Journey Orchestration] ークフローでは、イベント条件が満たされているにもかかわらず、ジャーニーが特定のプロファイルに対してトリガーされない場合がある問題の解決策について説明します。 |

### [!DNL Journey Optimizer] のその他のリソース

* [[!DNL Journey Optimizer] ドキュメント](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/ajo-home) - [リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes) - [チュートリアルビデオ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/overview)
* [意思決定管理ドキュメント](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/decisioning/offer-decisioning/get-started-decision/starting-offer-decisioning) - [リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes) - [チュートリアルビデオ](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/decision-capabilities/decision-management/introduction-to-decision-management) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/documentation-updates)

+++

## [!DNL Journey Optimizer B2B Edition] {#ajo-b2b}

[!DNL Journey Optimizer B2B Edition] の最新のリリース情報について説明します。

+++リリースノートとドキュメント

最新リリース：**2025 年 4 月 10 日**

* [[!DNL Journey Optimizer B2B Edition]](https://experienceleague.adobe.com/en/docs/journey-optimizer-b2b) （すべてのセルフヘルプ）
* [!DNL Journey Optimizer B2B Edition] の [ リリースノート ](https://experienceleague.adobe.com/en/docs/journey-optimizer-b2b/user/release-notes)
* [ 製品ドキュメント ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b/user/guide-overview) を参 [!DNL Journey Optimizer B2B Edition]
* [ ビデオの概要とチュートリアル ](https://experienceleague.adobe.com/en/docs/journey-optimizer-b2b-learn/tutorials/overview) （[!DNL Journey Optimizer B2B Edition] 用）
* [ 製品の説明とライセンス ](https://helpx.adobe.com/legal/product-descriptions/adobe-journey-optimizer-b2b.html#_blankl) （[!DNL Journey Optimizer B2B Edition]）

<!-- New videos, tutorials, or courses published for Journey Optimizer B2B Edition.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February 2025|[Account Journeys](https://experienceleague.adobe.com/en/docs/journey-optimizer-b2b-learn/tutorials/account-journeys/introducing-account-journeys)|New videos |Visit the Account Journeys tutorial home. Learn about Account Journeys and how to use them to engage your target audience.|
|February 2025|[Use Case Playbook - Abandoned shopping cart](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/use-cases/abandoned-cart)|New video |Learn how to implement the abandoned shopping cart use case, using the Playbook feature in Adobe Journey Optimizer.|
|February 2025|[Import and activate an audience by uploading a CSV file](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/profiles-audiences-subscriptions/import-and-activate-an-audience-by-uploading-a-csv-file)|New video |Discover how to efficiently import and activate an audience by uploading a CSV file. Learn to personalize your content using enrichment attributes from the CSV file, ensuring a more tailored experience for your audience.| -->

詳しくは、次を参照してください。

* 製品情報は、[[!DNL Journey Optimizer B2B Edition]](https://business.adobe.com/jp/products/journey-optimizer-b2b-edition.html) を参照してください。

+++

## [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] の最新のリリースノートとリリーススケジュールについて説明します。

+++リリースノート、チュートリアル、サポート記事

### Core Marketo Engage の更新

* 最新情報については、[現在のリリースノート](https://experienceleague.adobe.com/ja/docs/marketo/using/release-notes/current)を参照してください。
* 最新のリリーススケジュール情報とリリースノートについては、[!DNL Marketo Engage] [リリーススケジュール](https://experienceleague.adobe.com/ja/docs/marketo/using/release-notes/release-schedule)を参照してください。

<!-- ### New Marketo tutorials {#tutorials-marketo}

New tutorials published for Adobe Marketo.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|March 2025|[Best practices to implement live chat](https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/dynamic-chat/live-chat-best-practices)| New video |Learn about the best practices to follow when you're implementing the live chat feature in Dynamic Chat.| -->

最新の製品ドキュメントについて詳しくは、[Marketo 製品ドキュメント](https://experienceleague.adobe.com/ja/docs/marketo/using/home)ホームを参照してください。

### 新しい [!DNL Marketo] でのナレッジベースのサポート

[!DNL Marketo] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年4月 | [[!UICONTROL Everytouch アトリビューション ] で設定が予期せず変更される  [!DNL Marketo Measure]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26378) | 新しい記事 | [!DNL Marketo Measure] の [!UICONTROL Everytouch アトリビューションメソッド ] が **[!UICONTROL 連絡先の役割の使用]** と **[!UICONTROL アカウント ID の使用]** の間で予期せず変更される場合の問題の解決策について説明します。 |

+++

## [!DNL Workfront] {#workfront}

[!DNL Adobe Workfront] の最新のリリースノートについて説明します。Experience League で新しいチュートリアルを確認してください。

+++リリースノートと新しいチュートリアル

### [!DNL Adobe Workfront] の更新

* [2025年第 2 四半期リリースの概要](https://experienceleague.adobe.com/ja/docs/workfront/using/product-announcements/product-releases/release-25-q2/25-q2-release-overview)

すべてのリリース情報について：

* [!DNL Workfront] のリリーススケジュール情報とリリースノートについては、[Adobe  [!DNL Workfront]  製品のリリース](https://experienceleague.adobe.com/ja/docs/workfront/using/product-announcements/product-releases/product-releases)のページを参照してください。

* Fusion の最新情報については、[Adobe [!DNL Workfront] Fusion リリースアクティビティの概要](https://experienceleague.adobe.com/ja/docs/workfront-fusion/using/fusion-release-activity/fusion-release-activity)を参照してください。

### 新しい Adobe [!DNL Workfront] チュートリアル {#tutorials-workfront}

Experience League の新しい [!DNL Workfront] チュートリアルとイベント。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年5月 | [ タイムラインビューの作成 ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/workfront-planning/create-and-manage-timeline-views) | 新しいビデオ | Workfront Planning でタイムラインビューを管理およびカスタマイズする方法を説明します。 |
| 2025年5月 | [ 複数の請求レートについて ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/multiple-billing-rates) | 新しいビデオ | プロジェクト内の担当業務の請求レートを管理およびカスタマイズする方法を説明します。 |
| 2025年5月 | [ 為替レートの設定 ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-exchange-rates) | 新しいビデオ | 柔軟な為替レート管理、グローバルおよびプロジェクトレベルのカスタマイズ、正確な財務追跡のための手動入力オプションにより、通貨設定をカスタマイズします。 |
| 2025年5月 | [ 財務の更新 ](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/update-and-review-finances) | 新しいビデオ | レートの定義、タスクへのコストと収益のタイプの割り当て、費用の管理、請求記録の作成により、コストの追跡と請求を効率化します。 Workfrontでは、実際の請求は行いません。 |
| 2025年5月 | [パフォーマンス指標について](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/understand-performance-metrics) | 新しいビデオ | 柔軟な計算方法、グローバルなデフォルト、プロジェクトレベルの上書きにより、適応可能な財務業績指標を確認します。 |
| 2025年5月 | [ タスクの収益とコストのデフォルトの設定 ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-task-revenue-and-cost-defaults) | 新しいビデオ | 収益タイプとコストタイプを使用する場所と、システムのデフォルトを設定する方法について説明します。 |
| 2025年5月 | [ 財務アクセスについて ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/understand-financial-access) | 新しいビデオ | カスタマイズ可能な権限を通じて財務データアクセスを制御し、安全な管理、プロジェクトレベルの監視、財務の可視性に合わせた共有オプションを確保する方法を説明します。 |
| 2025年5月 | [ 費用タイプの設定 ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-expense-types) | 新しいビデオ | 費用の入力時に事前定義済みの費用タイプを使用する方法と、新しい費用タイプを作成する方法を説明します。 |
| 2025年5月 | [ 基本フィルターの作成 ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-basic-filter) | 新しいビデオ | Workfrontでフィルターを作成および使用して、特定の条件に基づいてリストレポートをカスタマイズする方法を説明します。 |
| 2025年5月 | [ レポートコンポーネントについて ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/reporting-components) | 新しいビデオ | カスタマイズされたインサイトに合わせて、オブジェクトベースのフィルター、動的ビュー、構造化されたグループ化、ワイルドカード機能を使用してデータビジュアライゼーションを絞り込むレポートコンポーネントについて説明します。 |
| 2025年5月 | [ 財務情報の検索 ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/find-financial-information) | 新しいビデオ | プロジェクトとタスクの財務データに効率的にアクセス、分析、管理する方法を確認し、プロジェクトとタスクの両方のレベルで予算、収益、コスト、パフォーマンス指標をカバーします。 |
| 2025年5月 | [ グラフを使用したレポートの作成 ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-reports-with-charts) | 新しいビデオ | グラフを使用して、特にプロジェクトタスクを追跡するために、データを効果的に視覚化する方法を説明します。 |
| 2025年5月 | [Microsoft Outlook アドインのインストール ](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/integrations/outlook/integrations-microsoft-outlook) | 新しいビデオ | Microsoft Outlook アドインをインストールして、Microsoft Outlook のカレンダーとWorkfrontのホームのカレンダーを統合する方法を説明します。 |


### 新しい [!DNL Workfront] でのナレッジベースのサポート

[!DNL Workfront] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年4月 | [ シナリオで 500 エラーを解決  [!DNL Adobe Workfront Fusion]  る ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26250) | 新しい記事 | [!DNL Adobe Workfront Fusion] のシナリオで次のメッセージで 500 エラーが返される問題の解決策について説明します：*`[ 500] Cannot invoke "java.lang.Class.getName()" because "cls" is null.`* |
| 2025年4月 | [Adobe Workfrontで個人のプロジェクトを削除できない問題の解決 ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26238) | 新しい記事 | 管理者が、エラーで作成された個人プロジェクトを削除または完了できない問題の解決策について説明します。 |

最新の製品ドキュメントについて詳しくは、[アドビ [!DNL Workfront] ドキュメントのホームページ](https://experienceleague.adobe.com/ja/docs/workfront/using/home)を参照してください。

+++

## パフォーマンスマーケティング用の GenStudio {#genstudio-marketing}

[!DNL GenStudio for Performance Marketing] の最新リリース情報と新規ドキュメントについて説明します。

+++リリースノートとドキュメント

* [2025.04.10 - GenStudio for Performance Marketingのリリースノ ](https://experienceleague.adobe.com/ja/docs/genstudio-for-performance-marketing/user-guide/release-notes#latest) ト
* [パフォーマンスマーケティング用の GenStudio](https://experienceleague.adobe.com/ja/browse/genstudio-for-performance-marketing)（すべてセルフヘルプ）
* パフォーマンスマーケティング用の GenStudio の[製品ドキュメント](https://experienceleague.adobe.com/ja/docs/genstudio-for-performance-marketing/user-guide/home)
* [パフォーマンスマーケティング用の GenStudio](https://business.adobe.com/jp/products/genstudio-for-performance-marketing.html) の製品情報

+++

## [!DNL Mix Modeler] {#mix-modeler}

+++リリースノートとドキュメント

最新の情報について詳しくは、次のページを参照してください。

* Mix Modeler[2025 年 3 月/4 月 – リリースノート ](https://experienceleague.adobe.com/ja/docs/mix-modeler/using/releases/latest)
* Mix Modeler [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/mix-modeler)

+++

## Adobe [!DNL Advertising] {#advertising}

[!DNL Adobe Advertising] の最新リリース情報と新規ドキュメントについて説明します。

+++リリースノート

Adobe [!DNL Advertising] ヘルプを参照するには、[Adobe Advertising ドキュメント](https://experienceleague.adobe.com/ja/docs/advertising)を参照してください。

### [!DNL Advertising DSP] の新機能 {#advertising-dsp}

2025 年 5 月 7 日（Pt）

[ [!DNL Advertising DSP] の新機能](https://experienceleague.adobe.com/ja/docs/advertising/dsp/home)を参照してください。

### [!DNL Advertising Search, Social, & Commerce] の新機能 {#advertising-search}

2024年3月26日（PT）

[ [!DNL Advertising Search, Social, & Commerce] の新機能](https://experienceleague.adobe.com/ja/docs/advertising/search-social-commerce/home)を参照してください。

+++

## [!DNL Adobe Pass] {#pass}

[!DNL Adobe Pass] は、放送局、ケーブルネットワークおよびサービスプロバイダーに適した、マルチスクリーン TV プラットフォームです。ユーザーの心をつかむパーソナライズ可能な視聴体験を作成し、収益化できます。

+++ドキュメント

Adobe Pass用に公開された新しいチュートリアル。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- |---------- |
| 2025年4月 | [Adobe Pass – 新しい REST API v2](https://experienceleague.adobe.com/en/docs/events/experience-league-recorded-events/solution/hidden/adobe-pass-rest-api-v2) | 新しいビデオ | Adobeの新しい REST API v2 とその移行プロセスについて説明します。 |

リリース固有の情報、システム要件、制限事項、修正された問題および既知の問題については、[Adobe Pass ドキュメント](https://experienceleague.adobe.com/ja/docs/pass)を参照してください。

+++

## [!DNL Document Cloud] {#doc-cloud}

[!DNL Document Cloud]（[!DNL Acrobat Services] と [!DNL Acrobat Sign] を含む）向けに公開された新しいチュートリアル。

+++新しいチュートリアル

Adobe Document Cloud 向けに新しく公開されたチュートリアル。

| 公開日 | アプリケーション | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2025年5月 | アプリケーション | [PDFに関するコメント ](https://experienceleague.adobe.com/en/docs/document-cloud-learn/acrobat-learning/getting-started/comment-on-pdf-files) | 更新されたビデオ | Web ブラウザーのみを使用して、共有PDFにコメントを追加する方法を説明します。 チームで共同作業を行う場合でも、ドキュメントを校正する場合でも、Acrobatのコメントツールを使用すると、アクションにつながる明確なフィードバックを簡単に提供できます。 |

[!DNL Document Cloud] のチュートリアルについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/acrobat-learning/overview)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/sign-learning-hub/overview)
* [Adobe Acrobat Services API チュートリアル](https://experienceleague.adobe.com/ja/docs/acrobat-services-learn/tutorials/overview)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

+++

## [!DNL Creative Cloud] エンタープライズ版 {#creative-cloud}

[!DNL Adobe Creative Cloud for enterprise] のアプリケーションに関する新しいチュートリアルが公開されました。

+++最新のチュートリアル

<!-- | Published | Application | Name | Type | Description |
| -----------| ---------- | ---------- | ---------- |---------- |
| February 2025 | Applications | [Effortless brand consistency with templates](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/use-templates) | New video | Learn how to create on-brand content quickly and efficiently across your entire organization. This tutorial walks through how to create fresh new on-brand content that can immediately be shared and localized.|
| February 2025 | Applications | [Maximize efficiency: Create reusable templates](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates) | New video | Learn how to bring brand consistency, efficiency, professionalism, and cost savings to your organization with Adobe Express templates. | -->

最新のチュートリアルについて詳しくは、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview)を参照してください。

+++

## 顧客データ管理 - 担当者の声 {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/ja/docs/events/customer-data-management-voices-recordings/overview) は、顧客データ管理の技術およびマーケティングプラクティスのリーダーやスペシャリストのためのページです。このチュートリアルのコレクションには、同僚から話を聞き、インスピレーションを得て、MarTech の開発について学ぶためのリソースが一箇所に集められています。登録は不要です。クリックで視聴できます。

## デジタルエクスペリエンスブループリント {#blueprints}

[デジタルエクスペリエンスブループリント](https://experienceleague.adobe.com/ja/docs/blueprints-learn/architecture/overview)は、戦略に取り組み、確立されたビジネス上の問題を解決するための反復可能な実装です。各ブループリントは、価値の高いビジネス上の問題、アーキテクチャ、実装手順、技術的な考慮事項、および関連ドキュメントへのリンクを説明する一連の成果物を提供します。

<!-- |Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2025|[Guardrails](https://experienceleague.adobe.com/en/docs/blueprints-learn/architecture/architecture-overview/deployment/guardrails)|Updated article |Learn about guardrails, the performance expectations and impact for the components and services within Adobe Experience Platform and Applications.| -->

<!-- ## ![Icon](/assets/certification-badge.png) Certification{#certification}

Attention all Adobe certification candidates! Visit the Experience Cloud [Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) site on Experience League. 

+++Details

The [Experience Cloud Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) site is your one-stop shop for all [!DNL Experience Cloud] certification-related content and is updated regularly with:

* Available certifications
* Certification renewals for Adobe applications
* Certification program updates

And more! Head over to [Adobe Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) on Experience League and start your certification journey today!

+++ -->


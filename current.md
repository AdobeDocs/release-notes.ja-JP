---
title: 最新のリリースノート
description: Adobe [!DNL Experience Cloud] 製品とサービスの最新リリースノートおよびナレッジベースの問題をお読みください。Experience League に関する今後のイベントおよび新しいドキュメントについて説明します。  [!DNL Experience Cloud]  アプリケーションの最新のチュートリアルとコースを確認します。
doc-type: release notes
last-update: May 2025
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: de37e4a05aecb904915b79618169c0e9a23c90d8
workflow-type: tm+mt
source-wordcount: '5303'
ht-degree: 96%

---

# Experience Cloud リリースノート - 2025年5月

<!-- badgeReview: label="Internal Review" type="Negative" -->

<!-- ![Banner](assets/release-notes-header.png) -->

このページは、Experience League に関するアプリケーション固有のリリースノート、今後のイベント、新しいチュートリアル、最新のサポート記事を見つけるのに役立ちます。

<!-- * [Customize your learning](https://experienceleague.adobe.com/ja/home/profile-settings): Help us customize your learning experience. Select your role, industry, and the products that interest you.
* [Browse and discover](https://experienceleague.adobe.com/ja/browse): Find popular content, new tutorials, documentation, upcoming events, and more!
* [Get fresh perspectives](https://experienceleague.adobe.com/ja/perspectives): We've gathered a variety of real-world use cases and best practices, written by your peers and Adobe product experts. 
* [Get certified](https://experienceleague.adobe.com/ja/certification-home): The new Adobe Certification Portal makes honing your skills and getting certified a simple process.
* [Engage with a community of peers](https://experienceleaguecommunities.adobe.com/?profile.language=ja): Join groups, meet our Experience League Community Advisors, and even learn how to become one. -->

このページの更新に関するメール通知を毎月受信するには、[アドビ優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)を購読してください。

**更新日：2025 年 6 月 3 日**

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

更新日：**2025 年 6 月 3 日**

+++今後のイベント

* **[!DNL Experience Manager Guides]** | _Adobe DITAWORLD 2025_ | 2025年6月3日～5日（PT）の 3 日間、業界のエキスパートによるプレゼンテーションや、同業の方々との素晴らしい交流が満載のイベントを開催します。ぜひご参加ください。| **6月3日～5日（PT）** | [登録](https://2025-adobe-dita-world.meetus.adobeevents.com/?utm_campaign=community_forum&amp;utm_source=experience_league)

* **[!DNL Workfront]** | _Workfront の使用を開始：最適化して改善。Adobe Workfront インスタンスの監査と調整_ | Adobe Workfront インスタンスを継承したばかりでも、長年にわたって管理してきた場合でも、構造化されたレビューは、長期的な成功に向けた最初のステップです。 何が機能しているのか、どこにチャンスがあるのかを特定し、スケーラブルな改善を実現するための準備をする方法を特定し、明確かつ目的を持ってインスタンスを評価する方法を説明します。 | **6 月 5 日木曜日** | [ 登録 ](https://events-emea5.adobeconnect.com/content/adobeconnect/43/5415868397/en/events/event/shared/5748588430/event_landing.html?sco-id=5748605291&amp;campaign-id=ExL&amp;_charset_=utf-8)

* **[!DNL Workfront]** | _Admin 101: Workfront データの取得_ | Workfrontへようこそ。 初心者のシステム管理者向けに設計されたこのシリーズのイベントでは、新しい管理者に、使用可能なリソースの紹介、システムナビゲーションの概要、初期設定、取り込み、基本的なレポートに関するベストプラクティスが提供されます。 | **6 月 6 日火曜日** | [ 登録 ](https://events.teams.microsoft.com/event/91b3c81f-d8b8-4f30-94e1-8d532b2853e1@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

Experience League の[今後](https://experienceleague.adobe.com/ja/events)のイベントと[オンデマンド](https://experienceleague.adobe.com/ja/docs/events/experience-league-recorded-events/overview)イベントの完全なリストを表示します。

+++

## [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] では、アドビ製品およびサービスに関する詳細情報、ステータス更新およびメール通知を提供します。停止、中断およびメンテナンスイベントに関する通知を受け取れます。[status.adobe.com/ja](https://status.adobe.com/ja) でご確認ください。

+++リリースノート

[!DNL Adobe System Status] の以前のリリースノート：

* [2025年4月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2025/04162025#status)
* [2024年8月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2024/09142023#status)
* [2024年5月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2024/05152024#status)
* [2024年1月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2024/02142024#status)
* [2023年10月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2023/10042023#status)
* [2023年8月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2023/08092023#status)
* [2023年3月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2023/03082023#status)
* [2023年1月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2023/02082023#status)

+++

## [!DNL Experience Cloud] - 一元的なインターフェイスと管理 {#ecloud}

[!DNL Experience Cloud] 管理インターフェイスと中央インターフェイスコンポーネントの更新について説明します。

+++新機能

以下に関するヘルプについて詳しくは、[Experience Cloud インターフェイスおよび管理](https://experienceleague.adobe.com/ja/docs/core-services/interface/experience-cloud)ガイドを参照してください。

* **新登場。** [Experience Cloud アプリケーションにおけるジェネレーティブ AI](https://experienceleague.adobe.com/ja/docs/core-services/interface/features/generative-ai)
* [ ユーザー管理および製品ライセンス ](https://experienceleague.adobe.com/ja/docs/core-services/interface/administration/admin-console) （Admin Console）
* [ 顧客属性、オーディエンスライブラリ、Assetsなど ](https://experienceleague.adobe.com/ja/docs/core-services/interface/services/overview)

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
|April 2025| [!DNL Experience Platform] | [Evaluate batch audiences on demand](https://experienceleague.adobe.com/ja/docs/platform-learn/tutorials/audiences/evaluate-audiences-on-demand)| New video | Evaluate batch audiences on demand with flexible audience evaluation. |
|April 2025| [!DNL Experience Platform] | [Migrate a mobile app from Target to Journey Optimizer](https://experienceleague.adobe.com/ja/docs/platform-learn/migrate-target-to-mobile-sdk-decisioning/overview)| New video | Learn how to migrate your mobile app implementation from the Adobe Target to the Adobe Journey Optimizer - Decisioning extension|
|April 2025| [!DNL Experience Platform] | [Configure a dataset export destination in Experience Platform](https://experienceleague.adobe.com/ja/docs/platform-learn/tutorials/destinations/configure-dataset-export-destination)| Updated video | Learn about the configuration, workflow, and use cases for exporting datasets from Adobe Experience Platform to a cloud storage location using a destination connection. |
 -->

### 新しい [!DNL Experience Platform] でのナレッジベースのサポート{#kb-aep}

[!DNL Experience Platform] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年4月 | [AEP：アクティベーション率が高いにもかかわらず、 [!DNL TikTok]  の宛先でオーディエンス数が少ない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26380) | 新しい記事 | Adobe [!DNL Experience Platform]（AEP）の [!DNL TikTok] の宛先で、アクティベーション率が高い（～99％）にもかかわらず、オーディエンス数が少なく報告される場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe  [!DNL Experience Platform] でのデータセットの書き出しの問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26413) | 新しい記事 | API で作成されたデータセットの制限により、Adobe [!DNL Experience Platform] でデータセットの書き出し時に問題が発生する場合の解決策について説明します。 |
| 2025年4月 | [Adobe  [!DNL Experience Platform] でのバッチ取り込みの失敗と重複取り込みの解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26349) | 新しい記事 | Adobe [!DNL Experience Platform] でバッチ取り込みが失敗し、重複取り込みが発生する問題の解決策について説明します。 |
| 2025年4月 | [[!DNL Snowflake] Adobe  [!DNL Experience Platform] でのコネクタの認証エラー](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26294) | 新しい記事 | Adobe [!DNL Experience Platform]（AEP）および [!DNL Snowflake] での認証エラーが、秘密鍵の形式や設定の問題に起因する場合の解決策について説明します。 |
| 2025年4月 | [*コンテンツテンプレートの昇格時に発生する 406（許容できない）*&#x200B;エラー](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26320) | 新しい記事 | API ヘッダーを調整して、Adobe [!DNL Experience Platform] の [!UICONTROL Journey Orchestration] で発生する *406（許容できない）*&#x200B;エラーを解決する方法について説明します。 |
| 2025年4月 | [AEP - HTTP API 宛先と Destination SDK の違い](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26316) | 新しい記事 | HTTP API 宛先と Destination SDK の機能と目的の違いについて説明します。 |

+++

## [!DNL Real-Time CDP] {#rtcdp}

[!DNL Real-Time CDP] の最新のチュートリアルをご確認ください。

+++新しいチュートリアル

| 公開日 | 名前 | タイプ | 説明 |
| ----------| ---------- | ---------- |---------- |
| 2025年5月 | [Azure Blob 宛先の設定](https://experienceleague.adobe.com/ja/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination) | 更新されたビデオ | [!DNL Real-Time Customer Data Platform] で接続を設定し、Azure Blob Storage の宛先にデータを送信する方法について説明します。この宛先では、データセットとオーディエンスの書き出しがサポートされ、ファイルヘッダーとデータ属性をカスタマイズできます。 |

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
|April 2025|[Configure variables in Report Suite Manager](https://experienceleague.adobe.com/ja/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-variables-in-the-admin-console)| New video |Configure variables and events in [!UICONTROL Report Suite Manager], ensuring that the reports, dimensions, and metrics have the right names and behavior.| -->

+++

## [!DNL Customer Journey Analytics] {#cja}

[!DNL Customer Journey Analytics] の最新のリリース情報をご確認ください。Experience League で新しいチュートリアルを参照してください。

+++リリースノートと新しいチュートリアル

* [リリースノート](https://experienceleague.adobe.com/ja/docs/analytics-platform/using/releases/latest#releases)

  [!DNL Customer Journey Analytics] のリリースは継続的に行われます。したがって、リリースノートは月に数回更新されます。定期的に確認してください。

* [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/ja/docs/customer-journey-analytics)

### 新しい [!DNL Customer Journey Analytics] チュートリアル {#tutorials-cja}

[!DNL Customer Journey Analytics] の新しいチュートリアルが公開されました。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年5月 | [[!UICONTROL クイックインサイト]パネルの使用](https://experienceleague.adobe.com/ja/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/panels/use-the-quick-insights-panel) | 新しいビデオ | [!DNL Customer Journey Analytics] の&#x200B;_[!UICONTROL クイックインサイト]_&#x200B;パネルを使用して、ビジネス上の質問にすばやく簡単に回答する方法について説明します。 |

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

次回のリリース予定日は、**2025年6月5日（PT）**&#x200B;です。

[!DNL Experience Manager] のリリースノートはすべて次のページに記載されています。

* [ [!DNL Experience Manager]  as a Cloud Service の最新のリリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current)
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
| 2025年5月 | [!DNL Experience Manager Sites] | [AEM Sites のビデオとチュートリアル](https://experienceleague.adobe.com/ja/docs/experience-manager-learn/sites/overview) | 更新されたチュートリアルホーム | Adobe Experience Manager Sites の機能に関するビデオとチュートリアルを参照してください。AEM Sites は、優れたエクスペリエンス管理プラットフォームです。 |
| 2025年5月 | [!DNL Experience Manager as a Cloud Service] | [OpenAPI ベースの AEM API の設定](https://experienceleague.adobe.com/ja/docs/experience-manager-learn/cloud-service/aem-apis/openapis/setup) | 新しいビデオ | AEM as a Cloud Service 環境を設定して、OpenAPI ベースの AEM API へのアクセスを有効にする方法について説明します。 |
| 2025年5月 | [!DNL Experience Manager Forms] | [アダプティブフォームブロックを使用したフォームの作成](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/edge-delivery/build-forms/getting-started-edge-delivery-services-forms/create-forms) | 新しいビデオ | AEM Forms の Edge Delivery Services の基本を学びます。最適なフォームをすばやく作成できます。AEM Forms Edge Delivery のドキュメントベースのオーサリングは、ユーザーが使いやすく、検索エンジン向けに最適化された、驚異的なスピードと SEO に配慮したフォームを実現します。 |
| 2025年5月 | [!DNL Experience Manager Sites] - ヘッドレス | [AEM ヘッドレスの高度な概念](https://experienceleague.adobe.com/ja/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/advanced-tutorial/overview) | 新しいビデオ | Adobe Experience Manager（AEM）GraphQL API の高度な概念を説明するエンドツーエンドのチュートリアルです。 |

### 新しい [!DNL Experience Manager] でのナレッジベースのサポート{#kb-aem}

[!DNL Experience Manager] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|--------|---------|---------|
| 2025年4月 | [ワークフローインスタンスが実行ステータスのままになる](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26078) | 新しい記事 | ワークフロー（WF）インスタンスが長期間実行ステータスのままになる場合の問題の解決策について説明します。 |
| 2025年4月 | [古いワークフローによる AEM のパフォーマンス低下の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26369) | 新しい記事 | [!DNL Adobe Experience Manager (AEM) Sites] 内の古いワークフローインスタンスが多すぎるためにオーサー環境の速度が低下する場合の問題の解決策について説明します。 |
| 2025年4月 | [VPN を作成した後、*java.net.UnknownHostException* が原因でトラフィックの送信が失敗する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26374) | 新しい記事 | VPN を作成し、*準備完了*&#x200B;ステータスになっているが、トンネル経由でのトラフィックの送信が *java.net.UnknownHostException* によって失敗する場合の問題の解決策について説明します。 |
| 2025年4月 | [ACS AEM [!UICONTROL Commons プロパティをコピー]プロセスステップの失敗の修正](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26327) | 新しい記事 | プロセスリソース設定の不足により、ACS AEM [!UICONTROL Commons プロパティをコピー]プロセスステップが失敗する場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Experience Manager as a Cloud Service：HTTP から HTTPS へのトラフィックリダイレクト](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26336) | 新しい記事 | AEM as a Cloud Service がすべてのトラフィックを HTTP から HTTPS に自動的にリダイレクトする場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Experience Manager as a Cloud Service： [!DNL Adobe I/O Projects] の[!UICONTROL イベント]設定が&#x200B;*[!UICONTROL 読み取り専用]*&#x200B;ステータスになる](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26337) | 新しい記事 | [!DNL Adobe Developer Console] [!DNL (Adobe I/O Projects)] 内で、新しい&#x200B;**[!UICONTROL イベント]**&#x200B;設定に AEM as a Cloud Service の選択オプションが表示されないか、既存の&#x200B;**[!UICONTROL イベント]**&#x200B;設定が&#x200B;*[!UICONTROL 読み取り専用]*&#x200B;ステータスでロックされていることを検出した場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Experience Manager でのコンテンツツリーの並べ替えの修正](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26241) | 新しい記事 | Adobe Experience Manager（AEM）のディレクトリのフォルダー数が 1,000 個を超えると、並べ替え動作が予期せず変更される場合の問題の解決策について説明します。 |
| 2025年4月 | [AEM で  [!DNL Dynamic Media]  を使用する際のビデオファイルのオーディオの問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26197) | 新しい記事 | Adobe Experience Manager as a Cloud Service（AEMaaCS）で [!DNL Dynamic Media] を使用する際に、ビデオファイルのオーディオ同期の問題を解決する方法について説明します。 |
| 2025年4月 | [AEM as a Cloud Service での無効なユーザーエラーによる偽装の失敗の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26118) | 新しい記事 | [!DNL Adobe Experience Manager as a Cloud Service - Sites] で&#x200B;*無効なユーザー*&#x200B;エラーが発生して偽装が失敗する場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Experience Manager（AEM）で  [!DNL Microsoft Translation Service]  を設定できない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26096) | 新しい記事 | Adobe Experience Manager（AEM）as a Cloud Service で [!DNL Microsoft Translation Service] を設定する際に、[!DNL Microsoft Azure] によって指定されるエンドポイントとキーが [!DNL AEM Translation] 設定フォームで認識されない場合の問題の解決策について説明します。 |
| 2025年4月 | [AEM 環境のヘルスステータスの監視](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-25893) | 新しい記事 | ビルトインのヘルスチェックエンドポイントを使用して、AEM 環境のヘルスをプログラムで監視する方法について説明します。 |
| 2025年4月 | [Adobe Target へのコンテンツフラグメントの書き出しの問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26167) | 新しい記事 | Adobe Experience Manager から Adobe Target にコンテンツフラグメントを書き出す際に発生する *Adobe Target との同期に失敗しました*&#x200B;というエラーの解決策について説明します。 |
| 2025年4月 | [ [!DNL Time-to-Live] （TTL）キャッシュによる AEM パブリッシュサーバーの高負荷問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26393) | 新しい記事 | [!DNL AEMaaCS - Sites] での 5 分間の TTL キャッシュ戦略によって AEM パブリッシュサーバーのパフォーマンスが急増した場合の問題の解決策について説明します。 |
| 2025年4月 | [AEM Cloud Service の製品リストコンポーネントでの製品選択の制限](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26019) | 新しい記事 | Adobe Experience Manager（AEM）Cloud Service の製品リストコンポーネントで、ユーザーが「**[!UICONTROL すべて選択]**」チェックボックスを使用した場合に、20 を超える製品（SKU）を追加できない問題の解決策について説明します。 |
| 2025年4月 | [ [!DNL AEMaaCS - Assets] に新しくアップロードしたアセットの自動タグ付け](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-25925) | 新しい記事 | 新しくアップロードしたアセットに標準の向きタグが自動的にタグ付けされ、既存のメタデータ管理プラクティスが影響を受ける場合の [!DNL AEMaaCS - Assets] の問題を解決する方法について説明します。 |
| 2025年4月 | [Adobe Experience Manager（AEM）as a Cloud Service での誤ったコンテンツ配信の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-25922) | 新しい記事 | Adobe Experience Manager（AEM）as a Cloud Service デプロイメント内の設定の競合により、誤ったコンテンツが配信される場合の問題の解決策について説明します。 |

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
| 2025年5月 | [サクセスアクセラレーターによる組織の準備](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-organizational-readiness) | 新しいビデオ | アドビのサクセスアクセラレーターを使用して組織の準備を整える方法について説明します。 |
| 2025年5月 | [Commerce サポートアドオン](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/commerce-support-add-ons) | 新しいビデオ | Expert Success、Ultimate Success、戦略的支援のための様々なアドオンなど、強化されたカスタマーサポートプランについて説明します。 |
| 2025年5月 | [Expert Success とは](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/what-is-expert-success) | 新しいビデオ | Adobe Commerce の Expert Success plan について説明します。3 つのサポートチャネルとサービスレベルターゲットを含む詳細について詳しく説明します。 |
| 2025年5月 | [サクセスアクセラレーターの技術的な準備](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-technical-readiness) | 新しいビデオ | 最適なパフォーマンスを実現するための Commerce サクセスアクセラレーターの技術的な準備、ソリューションのレビュー、イベント計画、24 時間年中無休のモニタリングについて説明します。 |
| 2025年5月 | [サクセスアクセラレーターの導入と有効化](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-adoption-and-enablement) | 新しいビデオ | 戦略的開発、スキル強化、ガバナンスのための Adobe Commerce サクセスアクセラレーターの導入と有効化について説明します。 |
| 2025年5月 | [Ultimate Success とは](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/what-is-ultimate-success) | 新しいビデオ | 高パフォーマンスのデジタルエクスペリエンスを実現するための Adobe Commerce Ultimate Success のプロアクティブなサポートと戦略的ガイダンスについて説明します。 |
| 2025年5月 | [テクニカルオンボーディング - SaaS 製品](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/adobe-commerce-cloud/technical-onboarding-hardware-handoff/saas-offerings-support-communications-next-steps) | 新しいビデオ | Adobe Commerce Cloud の SaaS 製品、サポート、その他のコミュニケーションおよび一部の次の手順について説明します。 |

### 新しい [!DNL Commerce] のナレッジベースへのサポート{#kb-commerce}

Adobe Commerce の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|--------|---------|---------|
| 2025年4月 | [[!DNL Quality Patches Tool] （QPT）](https://experienceleague.adobe.com/ja/docs/commerce-operations/tools/quality-patches-tool/patches-available-in-qpt/patches-available-in-qpt-tool-overview) | 新しい記事 | QPT 1.1.60、QPT 1.1.61 および QPT 1.1.62 で使用可能なパッチの適用方法に関する新しい記事が公開され、それぞれの節で参照できるようになりました。 |
| 2025年4月 | [APSB25-08 セキュリティパッチ適用後のすべての一括非同期 web エンドポイントの実行時間の増加](https://experienceleague.adobe.com/ja/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/increased-execution-time-for-bulk-asynchronous-web-endpoints-post-apsb25-08-security-patch) | 新しい記事 | この記事では、APSB25-08 セキュリティパッチの適用後に実行時間が大幅に長くなる、1000 以上のエントリを持つすべての一括非同期 web エンドポイント（`POST rest/all/async/bulk/V1/products` など）に関するホットフィックスについて説明します。 |
| 2025年4月 | [B2B 1.5.2 アップデート後の `Magento_Company` モジュールのアップグレードでのパフォーマンスの問題](https://experienceleague.adobe.com/ja/docs/commerce-knowledge-base/kb/troubleshooting/installation-and-upgrade/magento-company-module-upgrade-performance-issue) | 新しい記事 | この記事では、B2B 1.5.2 アップデート後に `Magento_Company` モジュールのアップグレードで発生する、`company_structure` テーブル内の大規模なデータセット（最大 100,000 件以上のレコード）の処理時間が過度に増加するパフォーマンス問題に関するホットフィックスについて説明します。 |
| 2025年4月 | [`REGEXP_LIKE` 関数の欠落により、B2B 1.5.2 へのアップグレードが SQL 構文エラーで失敗する](https://experienceleague.adobe.com/ja/docs/commerce-knowledge-base/kb/troubleshooting/installation-and-upgrade/sql-syntax-error-due-to-missing-regexp-like-function) | 新しい記事 | この記事では、`REGEXP_LIKE` 関数の欠落により `company_structure` テーブルの更新時に発生する SQL 構文エラーに関するホットフィックスについて説明します。 |
| 2025年4月 | [*Cookie の最大数を超えています*&#x200B;というエラーが Adobe Commerce で発生する](https://experienceleague.adobe.com/ja/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/maximum-number-of-cookies-would-be-exceeded-error) | 新しい記事 | この記事では、Adobe Commerce で発生する *Cookie の最大数を超えています*&#x200B;というエラーを解決するためのパッチについて説明します。 |
| 2025年4月 | [[!DNL Web Application Firewall] （WAF）がクラウドインフラストラクチャー上の Adobe Commerce の[!UICONTROL 管理者]インターフェイスで無効と表示される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26387) | 新しい記事 | クラウドインフラストラクチャー上の Adobe Commerce で [!DNL Web Application Firewall]（WAF）が有効で正常に機能しているにもかかわらず、[!UICONTROL 管理者]側で無効と表示される場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Commerce セキュリティパッチのクラウドデプロイメントエラーの解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26408) | 新しい記事 | クラウドインフラストラクチャー上の Adobe Commerce で、サポートされていないバックエンドキャッシュ設定が原因でデプロイメントエラーが発生する場合の問題の解決策について説明します。 |
| 2025年4月 | [クラウドインフラストラクチャー上の Adobe Commerce でログバッファーが満杯の場合に発生するエラーの解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26382) | 新しい記事 | ログバッファーが満杯になり、サイト停止中にアクセスログリクエストが切り捨てられる場合の問題の解決策について説明します。 |
| 2025年4月 | [クラウドインフラストラクチャー上の Adobe Commerce でのデータベースのダンプエラーのトラブルシューティング](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26385) | 新しい記事 | `magento-cloud db:dump` エラーを解決して、データベースのダンプを正常に実行する方法について説明します。 |
| 2025年4月 | [ [!DNL Security Scan Tool]  のスキャン結果へのアクセスに関する問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26357) | 新しい記事 | Adobe Commerce [!DNL Security Scan Tool] でマルウェアまたは重大な問題を検出したが、スキャン結果にアクセスできない状況に対処する方法について説明します。 |

+++

## [!DNL Target] {#target}

[!DNL Adobe Target] のプレリリースノート、現在のリリースノートおよび新しいチュートリアルにアクセスできます。

+++リリースノート

<!-- ### New [!DNL Target] support knowledge base{#kb-target}

|Published|Name|Type|Description|
|---------|----|----|-----------|
|July 2024|[[!DNL Adobe Target] bulk profile update [!DNL API] throws *[!DNL Unexpected Error]* when using [!DNL Postman]](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-24281)|New article| Learn about how to fix the issue when running the [!DNL Target Bulk Profile Update API] throws the *[!DNL Unexpected Error]* message in [!DNL Postman].|
-->

* プレリリース情報については、[[!DNL Adobe Target] プレリリース](https://experienceleague.adobe.com/ja/docs/target/using/release-notes/target-release-notes)を参照してください。
* 現在の情報については、[[!DNL Adobe Target] リリースノート](https://experienceleague.adobe.com/ja/docs/target/using/release-notes/release-notes)を参照してください。

+++

## [!DNL Campaign] {#ac}

[!DNL Adobe Campaign] の最新のアップデート情報を取得できます。Experience League で新しいチュートリアルとナレッジベースのサポート記事を確認してください。

+++リリースノートとサポート記事

### 最新の Campaign 製品リリース

* [!DNL Web User Interface]：2025年5月 - [リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/release-notes/release-notes) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/campaign-web-home)

* [!DNL Campaign] v8：2025年4月25日（PT）- [リリースノート](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/releases/release-notes#release-8-7-4) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/campaign-home)

* [!DNL Campaign Standard]：25.1 - [リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-standard/using/release-notes/release-notes) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-standard/using/campaign-standard-home)

* [!DNL Campaign Classic] 7.4.2：2025年5月12日（PT）- [リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-classic/using/release-notes/latest-release#release-7-4-2) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-classic/using/campaign-classic-home)

<!-- ### New [!DNL Campaign] tutorials {#tutorials-campaign}

New or updated videos tutorials published for Adobe Campaign.

| Published | Application | Name | Type | Description |
| ----------| ---------- | ---------- | ---------- |---------- |
|January 2025| |[Create and manage test profiles](https://experienceleague.adobe.com/ja/docs/campaign-web-learn/tutorials/profiles-and-audiences/create-and-manage-test-profiles)|New video |Learn how to create a test profile in the client console and how to manage, and edit profiles in the Adobe Campaign Web UI.|
|January 2025| |[Enhance a delivery with dynamic content](https://experienceleague.adobe.com/ja/docs/campaign-web-learn/tutorials/content-management/enhance-a-delivery-with-dynamic-content)|New video |Learn how to make message content dynamic by using the expression editor to personalize your message or add conditional content.| -->

### 新しい [!DNL Campaign] でのナレッジベースのサポート{#kb-campaign}

[!DNL Campaign] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年4月 | [Adobe Campaign で適切な URL がトラッキング用の URL マーカーで置き換えられる](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26309) | 新しい記事 | Adobe Campaign でのトラッキング URL マーカーの問題の解決策について説明します。 |
| 2025年4月 | [ファイルの抽出中に列挙ラベルが適切に書き出されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26155) | 新しい記事 | Adobe Campaign ワークフローで列挙ラベルが正しく書き出されない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign Standard での内部メールアドレスの強制隔離ルールの管理](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26334) | 新しい記事 | 内部メールアドレスが強制隔離テーブルに追加され、重要なコミュニケーションがブロックされる場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign Classic でのパスワード変更後の [!DNL Snowflake] [!UICONTROL データ読み込み]の問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26368) | 新しい記事 | Adobe Campaign Classic で [!DNL Snowflake] 接続の&#x200B;**[!UICONTROL 外部アカウント]**&#x200B;のパスワードを更新する際に、新しい[!UICONTROL データ読み込み]アクティビティで問題が発生する場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign Classic フォルダーで検索フィルターを表示できない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26160) | 新しい記事 | Adobe Campaign Classic Hosted（v7）の特定のフォルダー内で検索フィルターが表示されない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign Classic でのメール配信の開封率の低下](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26266) | 新しい記事 | ワークフローやコンテンツに変更を加えていないにもかかわらず、メール配信の開封率が低下した場合の問題の解決策について説明します。 |
| 2025年4月 | [ [!DNL Adobe Campaign Managed Cloud] にログインできない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26119) | 新しい記事 | [!DNL Adobe Campaign Managed Cloud] にログインすると、「*不明な認証モード：ネゴシエート*」というエラーメッセージが表示される場合の問題の解決策について説明します。 |
| 2025年4月 | [メールシードが送信済みとして表示されるが、インボックスに届いてない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26162) | 新しい記事 | Adobe Campaign 経由で送信したメールが配信ログでは送信済みとして表示されるが、受信者のインボックスにすぐに届かない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Campaign でのフォルダー表示の問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26292) | 新しい記事 | Adobe Campaign Classic インスタンスで特定のフォルダーが表示されない場合の問題の解決策について説明します。 |
| 2025年4月 | [ [!DNL Adobe Campaign Classic Hosted] でのロードバランサー URL の問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26264) | 新しい記事 | [!DNL Adobe Campaign Classic Hosted] で、アプリ統合時にロードバランサー URL が機能せず、HTTPS リクエストの不適切な設定により 401 エラーが発生する場合の問題の解決策について説明します。 |

+++

## [!DNL Journey Optimizer] {#journey-opt}

[!DNL Journey Optimizer] の最新のリリース情報について説明します。Experience League で最新のチュートリアルおよびナレッジベースのサポート記事を確認してください。

+++リリースノートと新しいチュートリアル

### [!DNL Journey Optimizer] 製品リリースのアップデート

最新リリース：**2025年5月**

* アップデートおよびヘルプについては、[Journey Optimizer リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes)を参照してください

**注意：** [B2B edition用Journey Optimizer](#journey-optimizer-b2b-edition) は別売りです。

### 新しい [!DNL Journey Optimizer] チュートリアル {#tutorials-ajo}

Experience League に関する Adobe [!DNL Journey Optimizer] の新しいチュートリアルが公開されました。

| 公開日 | アプリケーション | 名前 | タイプ | 説明 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2025年5月 | [!DNL Journey Optimizer] | [Adobe Journey Optimizer でのオーケストレーションのオムニチャネルエンゲージメントへの拡張](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/scaling-orchestration-to-omnichannel-engagement/introduction) | 新しいビデオ | ビジネスコミュニケーションを基本的なアウトバウンドメッセージングから高度なオムニチャネルエクスペリエンスに変革する方法について説明します。実用的な例を通じて、プロアクティブなアウトリーチとレスポンシブエンゲージメントを組み合わせたカスタマージャーニーを作成します。この内容は当初、Adobe Summit 2025 でラボ L535 として発表されました。 |
| 2025年5月 | Journey Optimizer | [バッチセグメント化の完了後の毎日のジャーニー実行のトリガー](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/create-journeys/trigger-daily-journey-runs-after-batch-segmentation-completion) | 新しいビデオ | データの精度とコンプライアンスを確保するために、セグメント化ジョブが完了した後にのみオーディエンスを読み取りジャーニーを開始するように設定する方法について説明します。 |
| 2025年5月 | Journey Optimizer、Adobe Express | [Adobe Express を使用したアセットの編集](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/content-management/assets/edit-assets-with-adobe-express) | 新しいビデオ | Adobe Express ツールを使用して Adobe Journey Optimizer でアセットを編集する方法について説明します。 |
| 2025年5月 | [!DNL Journey Optimizer] | [パーソナライゼーションエディタープレイグラウンド](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/personalize-content/personalization-editor-playground) | 新しいビデオ | 定義済みコードサンプルの活用、ダミーのプロファイルペイロードの編集、パーソナライゼーションコードの出力のリアルタイムプレビューについて、それぞれの方法を説明します。 |
| 2025年5月 | [!DNL Journey Optimizer]、[!DNL Experience Platform] | [Decisioning を使用した web オファーのパーソナライズ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/use-decisioning-to-personalize-web-offers/introduction?lang=ja) | 新しい記事 | Journey Optimizer（AJO）の [!UICONTROL Decisioning] を使用し、[!DNL Experience Platform]（AEP）のビルトインのオーディエンスのセグメント化を活用して、web ページでパーソナライズしたオファーを配信する方法について説明します。 |
| 2025年5月 | [!DNL Journey Optimizer]、[!DNL Experience Platform] | [Web SDK を使用したオーディエンスの作成](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/create-audiences-using-web-sdk/introduction) | 新しい記事 | Web フォームを通じてユーザーの環境設定を取得し、そのデータを Adobe [!DNL Experience Platform]（AEP）にリアルタイムで送信し、選択に基づいてユーザーを動的にターゲットオーディエンスに選定する方法について説明します。 |

### 新しい [!DNL Journey Optimizer] でのナレッジベースのサポート{#kb-ajo}

[!DNL Journey Optimizer] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年4月 | [プッシュメッセージのクリック動作が AJO の web URL にリダイレクトされない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26226) | 新しい記事 | クリック時に設定済み web URL にリダイレクトするようにプッシュメッセージを設定しているが、期待どおりに機能しない場合の問題の解決策について説明します。 |
| 2025年4月 | [Journey Optimizer：`consents.marketing.sms.value=y` が設定されているにもかかわらず、トランザクション SMS が配信されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26258) | 新しい記事 | SMS メッセージに `STOP` と応答すると、トランザクションメッセージを含む、その短縮番号からの後続のすべての SMS がブロックされる場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer でのオーディエンス母集団の問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26333) | 新しい記事 | コンポーネントやリソースの欠落、権限への影響、プロビジョニングなど、オーディエンス母集団に関する問題の解決策について説明します。 |
| 2025年4月 | [ [!DNL Customer Journey Analytics] で[!UICONTROL アプリ内チャネル]に関してレポートできない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26206) | 新しい記事 | [!DNL Adobe Customer Journey Analytics]（CJA）内の[!UICONTROL アプリ内チャネル]に関するレポートの問題を解決する方法について説明します。 |
| 2025年4月 | [Journey Optimizer：手動セグメント評価によるオーディエンス数の不一致](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26166) | 新しい記事 | ジャーニーが最新の認定済みデータを反映していない場合の問題の解決策について説明します。 |
| 2025年4月 | [ジャーニーにエントリするプロファイル数と AJO の関連オーディエンスのプロファイル数の不一致](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26253) | 新しい記事 | 特にバッチオーディエンスを使用するジャーニーで、ジャーニーにエントリするプロファイル数が、関連オーディエンスのプロファイル数と一致しない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer でのプロファイル更新エラーの解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26352) | 新しい記事 | ジャーニーで[!UICONTROL プロファイルを更新]ノードを実行した後、特定のフィールド値が適切に更新されない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer でキャンペーンが期待どおりのファイルを生成しない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26235) | 新しい記事 | 繰り返しのダイレクトメールキャンペーンを毎日の実行時間後に開始すると、その日のメールが処理されない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer でのオファーコレクション作成の問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26265) | 新しい記事 | カタログがプロビジョニングされていないので、Adobe Journey Optimizer（AJO）内でオファーコレクションを作成する際に問題が発生する場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer のカスタムアクションに対して TLS v1.3 を有効にする](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26223) | 新しい記事 | AJO のカスタムアクションに対して [!DNL Transport Layer Security]（TLS）v1.3 を有効にして、サードパーティシステムに接続する際にデータの整合性とセキュリティを維持する方法について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer でのオーディエンス変更後のジャーニートリガーの問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26224) | 新しい記事 | 結合ポリシーの変更など、関連オーディエンスに変更を行った際に、Adobe Journey Optimizer（AJO）のジャーニーがトリガーされなくなる場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer でクエリからダッシュボードを作成できない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26201) | 新しい記事 | ユーザーがクエリから直接ダッシュボードを作成できない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer：多言語機能で&#x200B;*メッセージ検証エラー（CJMMAS - 1069-500）*&#x200B;が発生する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26168) | 新しい記事 | 多言語機能にリンクされた&#x200B;*メッセージ検証エラー（CJMMAS - 1069-500）*&#x200B;により、ジャーニーをテストモードに設定したり公開したりできない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer でのイベントキャッピングによるプロファイルの離脱](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26018) | 新しい記事 | イベントキャッピングによりプロファイルが予期せずジャーニーから離脱し、コミュニケーションの損失につながる場合の問題の解決策について説明します。 |
| 2025年4月 | [AJO メールテンプレートで HTML コンポーネントを使用した場合のリンク動作の不一致](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26221) | 新しい記事 | メールコンテンツテンプレートに HTML コンポーネントを追加する際に発生する問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer でイベントがジャーニーをトリガーしない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26031) | 新しい記事 | すべての条件が満たされていても、イベントが意図したジャーニーをトリガーできない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer：カスタムアクションの外部サードパーティエンドポイントがタイムアウトする](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26156) | 新しい記事 | Adobe Journey Optimizer（AJO）でカスタムアクションを設定して外部サードパーティエンドポイントを呼び出す際にタイムアウトエラーが発生する場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer での[!UICONTROL エンゲージ可能なプロファイル]数の増加](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26161) | 新しい記事 | Adobe Journey Optimizer（AJO）で[!UICONTROL エンゲージ可能なプロファイル]数が短期間で大幅に増加する理由について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer での&#x200B;**[!UICONTROL キャッピングルール]**&#x200B;ドロップダウンの問題のトラブルシューティング](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26204) | 新しい記事 | Adobe Journey Optimizer（AJO）の&#x200B;**[!UICONTROL キャッピングルール]**&#x200B;ドロップダウンメニューに関する問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer におけるプロファイルのジャーニーからの早期離脱](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26127) | 新しい記事 | プロファイルが指定されたノードを通過せずに、予期せずジャーニーから離脱する場合の問題の解決策について説明します。 |
| 2025年4月 | [[!UICONTROL データストリーム]設定に Adobe Journey Optimizer チェックボックスがない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26131) | 新しい記事 | Adobe [!DNL Experience Platform]（AEP）サービスの[!UICONTROL データストリーム]設定で Adobe Journey Optimizer チェックボックスが表示されない場合の問題の解決策について説明します。 |
| 2025年4月 | [[!UICONTROL プリヘッダー]フィールドが Adobe Journey Optimizer の&#x200B;**[!UICONTROL 独自のコーディング]**&#x200B;モードで表示されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26174) | 新しい記事 | **[!UICONTROL メール本文を編集]**&#x200B;機能の&#x200B;**[!UICONTROL 独自のコーディング]**&#x200B;モードで[!UICONTROL プリヘッダー]入力フィールドが表示されない場合の問題の解決策について説明します。 |
| 2025年4月 | [Adobe Journey Optimizer の **[!UICONTROL Offer Decisioning]** にアクセスできない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26175) | 新しい記事 | Adobe Journey Optimizer（AJO）を使用して Adobe Target をアプリケーションに統合する際に、[!UICONTROL データストリーム]設定内で「**[!UICONTROL Offer Decisioning]**」オプションにアクセスできないことを示す警告が表示される場合の問題の解決策について説明します。 |
| 2025年4月 | [ [!DNL Adobe Journey Optimizer Query Service API] に関するアクセスの問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26196) | 新しい記事 | [!DNL Postman] または類似のツールを通じて [!DNL Adobe Journey Optimizer Query Service API] にアクセスしようとした際に、権限の不足によりアクセスエラーが発生する場合の問題の解決策について説明します。 |
| 2025年4月 | [AJO で API トリガーのトランザクションメールキャンペーンを設定する際に Mail Exchanger エラーが発生する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26200) | 新しい記事 | Adobe Journey Optimizer（AJO）で API トリガーのトランザクションメールキャンペーンを設定する際に、Mail Exchanger（MX）エラーにより新しいチャネル設定を作成できない場合の問題の解決策について説明します。 |
| 2025年4月 | [Journey Optimizer：`AFTER` 日付関数の誤った設定により、意図しないオーディエンスにメールが送信される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26173) | 新しい記事 | Adobe Journey Optimizer（AJO）で、`AFTER` 日付関数の誤った設定により、意図したオーディエンスに該当しないメンバーにメールが送信される場合の問題の解決策について説明します。 |
| 2025年4月 | [AJO で  [!DNL Azure]  のファイルルーティングを確立できない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26323) | 新しい記事 | Adobe Journey Optimizer（AJO）から [!DNL Azure] への[!UICONTROL 配信管理]（DM）出力ファイルのファイルルーティングを設定する際に、[!DNL Azure] 接続文字列やコンテナの誤った設定によりエラーが発生する場合の問題の解決策について説明します。 |
| 2025年4月 | [イベント条件を満たしているにもかかわらず、プロファイルのジャーニーがトリガーされない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26305) | 新しい記事 | Adobe [!DNL Experience Platform]（AEP）の [!DNL Journey Orchestration] で、イベント条件を満たしているにもかかわらず、特定のプロファイルに対してジャーニーがトリガーされない場合の問題の解決策について説明します。 |

### [!DNL Journey Optimizer] のその他のリソース

* [[!DNL Journey Optimizer] ドキュメント](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/ajo-home) - [リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes) - [チュートリアルビデオ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/overview)
* [意思決定管理ドキュメント](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/decisioning/offer-decisioning/get-started-decision/starting-offer-decisioning) - [リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes) - [チュートリアルビデオ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/decision-capabilities/decision-management/introduction-to-decision-management) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/documentation-updates)

+++

## [!DNL Journey Optimizer B2B Edition] {#ajo-b2b}

[!DNL Journey Optimizer B2B Edition] の最新のリリース情報について説明します。

+++リリースノートとドキュメント

最新リリース：**2025年4月10日（PT）**

* [[!DNL Journey Optimizer B2B Edition]](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b) （すべてのセルフヘルプ）
* [!DNL Journey Optimizer B2B Edition] の [ リリースノート ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b/user/release-notes)
* [ 製品ドキュメント ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b/user/guide-overview) を参 [!DNL Journey Optimizer B2B Edition]
* [ ビデオの概要とチュートリアル ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b-learn/tutorials/overview) （[!DNL Journey Optimizer B2B Edition] 用）
* [ 製品の説明とライセンス ](https://helpx.adobe.com/jp/legal/product-descriptions/adobe-journey-optimizer-b2b.html#_blankl) （[!DNL Journey Optimizer B2B Edition]）

<!-- New videos, tutorials, or courses published for Journey Optimizer B2B Edition.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February 2025|[Account Journeys](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b-learn/tutorials/account-journeys/introducing-account-journeys)|New videos |Visit the Account Journeys tutorial home. Learn about Account Journeys and how to use them to engage your target audience.|
|February 2025|[Use Case Playbook - Abandoned shopping cart](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/use-cases/abandoned-cart)|New video |Learn how to implement the abandoned shopping cart use case, using the Playbook feature in Adobe Journey Optimizer.|
|February 2025|[Import and activate an audience by uploading a CSV file](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/profiles-audiences-subscriptions/import-and-activate-an-audience-by-uploading-a-csv-file)|New video |Discover how to efficiently import and activate an audience by uploading a CSV file. Learn to personalize your content using enrichment attributes from the CSV file, ensuring a more tailored experience for your audience.| -->

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
|March 2025|[Best practices to implement live chat](https://experienceleague.adobe.com/ja/docs/marketo-learn/tutorials/dynamic-chat/live-chat-best-practices)| New video |Learn about the best practices to follow when you're implementing the live chat feature in Dynamic Chat.| -->

最新の製品ドキュメントについて詳しくは、[Marketo 製品ドキュメント](https://experienceleague.adobe.com/ja/docs/marketo/using/home)ホームを参照してください。

### 新しい [!DNL Marketo] でのナレッジベースのサポート

[!DNL Marketo] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年4月 | [[!UICONTROL Everytouch アトリビューション]設定が  [!DNL Marketo Measure] で予期せず変更される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26378) | 新しい記事 | [!DNL Marketo Measure] の [!UICONTROL Everytouch アトリビューションメソッド]が&#x200B;**[!UICONTROL 取引先責任者ロールの使用]**&#x200B;と&#x200B;**[!UICONTROL アカウント ID の使用]**&#x200B;の間で予期せず変更される場合の問題の解決策について説明します。 |

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
| 2025年5月 | [タイムラインビューの作成](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/workfront-planning/create-and-manage-timeline-views) | 新しいビデオ | Workfront プランニングでタイムラインビューを管理およびカスタマイズする方法について説明します。 |
| 2025年5月 | [複数の請求率について](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/multiple-billing-rates) | 新しいビデオ | プロジェクト内の担当業務の請求率を管理およびカスタマイズする方法について説明します。 |
| 2025年5月 | [為替レートの設定](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-exchange-rates) | 新しいビデオ | 柔軟な為替レート管理、グローバルおよびプロジェクトレベルでのカスタマイズ、正確な財務トラッキング用の手動入力オプションを使用して通貨設定をカスタマイズします。 |
| 2025年5月 | [財務の更新](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/update-and-review-finances) | 新しいビデオ | レートの定義、コストと収益タイプのタスクへの割り当て、費用の管理、請求記録の作成により、コストのトラッキングと請求を効率化します。Workfront では、実際の請求は行いません。 |
| 2025年5月 | [パフォーマンス指標について](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/understand-performance-metrics) | 新しいビデオ | 柔軟な計算方法、グローバルなデフォルト、プロジェクトレベルの上書きを使用した、適応可能な財務パフォーマンス指標について説明します。 |
| 2025年5月 | [タスクの収益とコストのデフォルトの設定](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-task-revenue-and-cost-defaults) | 新しいビデオ | 収益タイプおよびコストタイプを使用する場所と、システムのデフォルトの設定方法について説明します。 |
| 2025年5月 | [財務アクセスについて](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/understand-financial-access) | 新しいビデオ | カスタマイズ可能な権限を通じて財務データへのアクセスを制御し、安全な管理、プロジェクトレベルの監視、財務表示の調整された共有オプションを確保する方法について説明します。 |
| 2025年5月 | [費用タイプの設定](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-expense-types) | 新しいビデオ | 費用の入力時に事前定義済みの費用タイプを使用する方法と、新しい費用タイプを作成する方法について説明します。 |
| 2025年5月 | [基本フィルターの作成](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-basic-filter) | 新しいビデオ | Workfront でフィルターを作成および使用して、特定の条件に基づいてリストレポートをカスタマイズする方法について説明します。 |
| 2025年5月 | [レポートコンポーネントについて](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/reporting-components) | 新しいビデオ | オブジェクトベースのフィルター、動的ビュー、構造化されたグループ化、ワイルドカード機能を使用して調整されたインサイトを取得し、データビジュアライゼーションを改善するためのレポートコンポーネントについて説明します。 |
| 2025年5月 | [財務情報の検索](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/find-financial-information) | 新しいビデオ | プロジェクトとタスクの両方のレベルで予算、収益、コスト、パフォーマンス指標を対象とし、プロジェクトとタスクの財務データに効率的にアクセス、分析、管理する方法について説明します。 |
| 2025年5月 | [グラフを使用したレポートの作成](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-reports-with-charts) | 新しいビデオ | 特にプロジェクトタスクのトラッキングに関して、グラフを使用してデータを効果的に視覚化する方法について説明します。 |
| 2025年5月 | [Microsoft Outlook アドインのインストール](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/integrations/outlook/integrations-microsoft-outlook) | 新しいビデオ | Microsoft Outlook アドインをインストールして、Microsoft Outlook カレンダーを Workfront ホームカレンダーと統合する方法について説明します。 |


### 新しい [!DNL Workfront] でのナレッジベースのサポート

[!DNL Workfront] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年4月 | [ [!DNL Adobe Workfront Fusion]  シナリオでの 500 エラーの解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26250) | 新しい記事 | [!DNL Adobe Workfront Fusion] シナリオで次のメッセージを含む 500 エラーが返される場合の問題の解決策について説明します。*`[ 500] Cannot invoke "java.lang.Class.getName()" because "cls" is null.`* |
| 2025年4月 | [Adobe Workfront で個人プロジェクトを削除できない問題の解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-26238) | 新しい記事 | 管理者が誤って作成された個人プロジェクトを削除または完了できない場合の問題の解決策について説明します。 |

最新の製品ドキュメントについて詳しくは、[アドビ [!DNL Workfront] ドキュメントのホームページ](https://experienceleague.adobe.com/ja/docs/workfront/using/home)を参照してください。

+++

## パフォーマンスマーケティング用の GenStudio {#genstudio-marketing}

[!DNL GenStudio for Performance Marketing] の最新リリース情報と新規ドキュメントについて説明します。

+++リリースノートとドキュメント

* GenStudio for Performance Marketing の [2025.04.10 - リリースノート](https://experienceleague.adobe.com/ja/docs/genstudio-for-performance-marketing/user-guide/release-notes#latest)
* [GenStudio for Performance Marketing](https://experienceleague.adobe.com/ja/browse/genstudio-for-performance-marketing)（すべてセルフヘルプ）
* パフォーマンスマーケティング用の GenStudio の[製品ドキュメント](https://experienceleague.adobe.com/ja/docs/genstudio-for-performance-marketing/user-guide/home)
* [パフォーマンスマーケティング用の GenStudio](https://business.adobe.com/jp/products/genstudio-for-performance-marketing.html) の製品情報

+++

## [!DNL Mix Modeler] {#mix-modeler}

+++リリースノートとドキュメント

最新の情報について詳しくは、次のページを参照してください。

* Mix Modeler [2025年3月／4月 - リリースノート](https://experienceleague.adobe.com/ja/docs/mix-modeler/using/releases/latest)
* Mix Modeler [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/mix-modeler)

+++

## Adobe [!DNL Advertising] {#advertising}

[!DNL Adobe Advertising] の最新リリース情報と新規ドキュメントについて説明します。

+++リリースノート

Adobe [!DNL Advertising] ヘルプを参照するには、[Adobe Advertising ドキュメント](https://experienceleague.adobe.com/ja/docs/advertising)を参照してください。

### [!DNL Advertising DSP] の新機能 {#advertising-dsp}

2025年5月7日（PT）

[ [!DNL Advertising DSP] の新機能](https://experienceleague.adobe.com/ja/docs/advertising/dsp/home)を参照してください。

### [!DNL Advertising Search, Social, & Commerce] の新機能 {#advertising-search}

2024年3月26日（PT）

[ [!DNL Advertising Search, Social, & Commerce] の新機能](https://experienceleague.adobe.com/ja/docs/advertising/search-social-commerce/home)を参照してください。

+++

## [!DNL Adobe Pass] {#pass}

[!DNL Adobe Pass] は、放送局、ケーブルネットワークおよびサービスプロバイダーに適した、マルチスクリーン TV プラットフォームです。ユーザーの心をつかむパーソナライズ可能な視聴体験を作成し、収益化できます。

+++ドキュメント

Adobe Pass 向けに公開された新しいチュートリアル。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- |---------- |
| 2025年4月 | [Adobe Pass - 新しい REST API v2](https://experienceleague.adobe.com/ja/docs/events/experience-league-recorded-events/solution/hidden/adobe-pass-rest-api-v2) | 新しいビデオ | アドビの新しい REST API v2 とその移行プロセスについて説明します。 |

リリース固有の情報、システム要件、制限事項、修正された問題および既知の問題については、[Adobe Pass ドキュメント](https://experienceleague.adobe.com/ja/docs/pass)を参照してください。

+++

## [!DNL Document Cloud] {#doc-cloud}

[!DNL Document Cloud]（[!DNL Acrobat Services] と [!DNL Acrobat Sign] を含む）向けに公開された新しいチュートリアル。

+++新しいチュートリアル

Adobe Document Cloud 向けに新しく公開されたチュートリアル。

| 公開日 | アプリケーション | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2025年5月 | アプリケーション | [PDF に関するコメント](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/acrobat-learning/getting-started/comment-on-pdf-files) | 更新されたビデオ | Web ブラウザーのみを使用して、共有 PDF にコメントを追加する方法について説明します。チームで共同作業を行う場合でも、ドキュメントを校正する場合でも、Acrobat のコメントツールを使用すると、明確で実用的なフィードバックを簡単に提供できます。 |

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
| February 2025 | Applications | [Effortless brand consistency with templates](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/use-templates) | New video | Learn how to create on-brand content quickly and efficiently across your entire organization. This tutorial walks through how to create fresh new on-brand content that can immediately be shared and localized.|
| February 2025 | Applications | [Maximize efficiency: Create reusable templates](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates) | New video | Learn how to bring brand consistency, efficiency, professionalism, and cost savings to your organization with Adobe Express templates. | -->

最新のチュートリアルについて詳しくは、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview)を参照してください。

+++

## 顧客データ管理 - 担当者の声 {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/ja/docs/events/customer-data-management-voices-recordings/overview) は、顧客データ管理の技術およびマーケティングプラクティスのリーダーやスペシャリストのためのページです。このチュートリアルのコレクションには、同僚から話を聞き、インスピレーションを得て、MarTech の開発について学ぶためのリソースが一箇所に集められています。登録は不要です。クリックで視聴できます。

## デジタルエクスペリエンスブループリント {#blueprints}

[デジタルエクスペリエンスブループリント](https://experienceleague.adobe.com/ja/docs/blueprints-learn/architecture/overview)は、戦略に取り組み、確立されたビジネス上の問題を解決するための反復可能な実装です。各ブループリントは、価値の高いビジネス上の問題、アーキテクチャ、実装手順、技術的な考慮事項、および関連ドキュメントへのリンクを説明する一連の成果物を提供します。

<!-- |Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2025|[Guardrails](https://experienceleague.adobe.com/ja/docs/blueprints-learn/architecture/architecture-overview/deployment/guardrails)|Updated article |Learn about guardrails, the performance expectations and impact for the components and services within Adobe Experience Platform and Applications.| -->

<!-- ## ![Icon](/assets/certification-badge.png) Certification{#certification}

Attention all Adobe certification candidates! Visit the Experience Cloud [Certification](https://experienceleague.adobe.com/ja/docs/certification/program/overview) site on Experience League. 

+++Details

The [Experience Cloud Certification](https://experienceleague.adobe.com/ja/docs/certification/program/overview) site is your one-stop shop for all [!DNL Experience Cloud] certification-related content and is updated regularly with:

* Available certifications
* Certification renewals for Adobe applications
* Certification program updates

And more! Head over to [Adobe Certification](https://experienceleague.adobe.com/ja/docs/certification/program/overview) on Experience League and start your certification journey today!

+++ -->


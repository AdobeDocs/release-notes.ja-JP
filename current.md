---
title: 主要なリリースノート
description: Adobe [!DNL Experience Cloud] 製品とサービスの最新リリースノートおよびナレッジベースの問題をお読みください。 Experience League に関する今後のイベントおよび新しいドキュメントについて説明します。  [!DNL Experience Cloud]  アプリケーションの最新のチュートリアルとコースを確認します。
doc-type: release notes
last-update: January 2026
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: 42549e49ab75ce4afc47d7e3dc1d9d9f47c5ebf4
workflow-type: tm+mt
source-wordcount: '4801'
ht-degree: 99%

---

# Experience Cloud の主要なリリースノート - 2026年1月

<!-- badgeReview: label="Internal Review" type="Negative" -->

このページは次の場合に役立ちます。

* アプリケーション固有のリリースノートへのリンクを検索
* Experience League のイベントを検索して、内容を確認する
* アプリケーションごとに新しいビデオチュートリアルを表示する
* 最新のサポート記事を参照する

最終更新日：**2026年1月29日（PT）**

## Experience League のコース

[コース](https://experienceleague.adobe.com/ja/courses)は Experience League で利用できます。 エキスパートが作成した、構造化された学習コンテンツです。アドビのソリューションをまたいで迅速にスキルを構築、専門知識を検証し、自信を持って進めることができます。

* 無料で利用可能
* 複雑なトピックを簡単に完了できる、短いモジュール
* いつでも一時停止および再開できる進行状況トラッキング
* 知識チェックとクイズで理解を深め、各段階での学習成果を検証
* コースの要件を満たした場合に授与される、共有可能な修了証明書（無料）

各コースの最後には、共有可能な修了証明書が発行され、内部や LinkedIn で自分の成果を具体的に示すことができます。

[詳細情報](https://experienceleague.adobe.com/ja/courses)

**このページの製品リンク**

+++セクションリンクを表示

* [イベントスケジュール](#events)
* [&#x200B; [!DNL Experience Cloud]](#ai) の AI 機能（更新日：**1 月 29 日（PT**））
* [[!DNL Adobe System Status]](#status)
* [[!DNL Adobe Experience Cloud] - 一元的なインターフェイスと管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Real-Time CDP]](#rtcdp)
* [[!DNL Adobe Analytics]](#analytics) （更新日：**1 月 15 日**）
* [[!DNL Adobe Customer Journey Analytics]](#cja) （更新日：**1 月 15 日**）
* [[!DNL Adobe Streaming Media Analytics]](#sma)
* [[!DNL Adobe Experience Manager]](#aem) （更新日：**1 月 29 日（PT**）
* [[!DNL Adobe LLM Optimizer]](#llm-optimizer)
* [[!DNL Adobe Brand Concierge]](#brand-concierge)
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

## イベントスケジュール {#events}

興味のある[イベント](https://experienceleague.adobe.com/ja/events)を見つけて登録してください。

+++今後のイベントを表示

* **[!DNL Adobe Summit]**   _マーケティング、クリエイティビティ、AI の未来を見る_   マーケティング、クリエイティビティ、AI の最新情報を参照してください。 | **ラスベガス、4月19日～22日（PT）** | [登録](https://summit.adobe.com/na/)

Experience League の[今後](https://experienceleague.adobe.com/ja/events)のイベントと[オンデマンド](https://experienceleague.adobe.com/ja/docs/events/experience-league-recorded-events/overview)イベントの完全なリストを表示します。

+++

## Experience League の最新の AI リソース {#ai}

Experience Cloud の生成 AI（genAI）、AI アシスタント、エージェント型 AI 向けに公開された最新の学習リソースを検索します。

+++詳細

| 製品 | リソース | 説明 | 更新済み |
| ------- | ------- | ------- | ------- |
| [!DNL Experience Cloud] | [Experience Cloud アプリケーションのエージェント型 AI](https://experienceleague.adobe.com/ja/docs/core-services/interface/features/agentic-ai) | Experience Cloudで Agentic AI を有効にする方法について説明します。 エージェントジョブと AI クレジット消費の仕組みを説明します。 | **2026年1月29日（PT）** |
| [!DNL Experience Manager as a Cloud Service] | [AEM のエージェント型 AI](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/ai-in-aem/overview?#agentic-ai-in-aem) | AEM CS の新規 AI エージェントについて説明します。 | 2025年11月21日（PT） |
| [!DNL Experience Cloud] | [Experience Cloud アプリケーションの生成 AI](https://experienceleague.adobe.com/ja/docs/core-services/interface/features/generative-ai) | Experience Cloudで AI を活用した機能を利用できる場所について説明します。 | 2025年11月 |
| AI ドキュメンテーションのホーム | [AI ドキュメンテーション](https://experienceleague.adobe.com/en/docs/ai) | Experience Cloudの AI を活用した機能（生成 AI および AI エージェント）に関する情報へのリンクについて詳しくは、新製品ドキュメンテーションのランディングを参照してください。 | 2025年10月 |

+++

## [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] では、アドビ製品およびサービスに関する詳細情報、ステータス更新およびメール通知を提供します。 停止、中断およびメンテナンスイベントに関する通知を受け取れます。 [status.adobe.com/ja](https://status.adobe.com/ja) でご確認ください。

+++リリースノート

リリース日：**2025年12月8日（PT）**

**新機能**

* 仮想アシスタントの機能強化
* バグ修正と改善

| 機能 | 説明 |
| ------- | ------- |
| **仮想アシスタントのフィードバック** | <ul><li>_仮想アシスタント_&#x200B;を使用すると、Web やモバイル上でステータスを使用しているお客様は、クイックアクションを実行し、フィードバックを提供できます。 仮想アシスタントは、すべてのクエリを一元的に解決する場所として機能します。</li><li>仮想アシスタントは、status.adobe.com にログインしているすべてのお客様が利用できます。 status.adobe.com にログインし、_アシスタントに質問_&#x200B;ウィジェットを使用することでアクセスできます。</li><li>このリリースでは、ワークフローを効率化し、ボタンの代わりに直感的なアイコンを使用し、仮想アシスタント内またはバックグラウンドページで可能な限り多くの情報を提供することで、ガイド付きワークフローエクスペリエンスをさらに強化しました。</li><li>今後の AI 仮想アシスタントの顧客ベータ版への参加をご希望の場合は、[statuscom-adobe-support](mailto:statuscom-adobe-support@adobe.com) までメールを送信してください。</li></ul> |
| **バグ修正と改善** | <ul><li>お知らせイベントバナーでお知らせに、誤って「_メンテナンス_」のラベルが付けられていました。</li><li>一部のビジネスサービス名は、使いやすいとは言えませんでした。</li><li>新しいアップデート後、お客様は 40 日を超えて開いている CSO や 40 日前に閉じられた CSO を表示できなくなりました。</li><li>Slack の設定が未完了の Adobe Status サブスクライバーには通知が送信され、インストールを完了するための手順が提供されました。</li><li>Web サイトのヘッダーとフッターのパフォーマンスが向上しました。</li></ul> |

[!DNL Adobe System Status] の以前のリリースノート：

* [2025年8月](https://experienceleague.adobe.com/ja/docs/release-notes/experience-cloud/previous/2025/08132025#status)

+++

## [!DNL Experience Cloud]管理および一元的なインターフェイス {#ecloud}

[!DNL Experience Cloud]管理および一元的なインターフェイスのコンポーネントの更新について説明します。

+++リリースノート

| 日付 | 更新 | 説明 | 該当する製品 |
| -----------| -----------| ---------- | ---------- |
| **2026年1月14日（PT）** | カスタマイズ可能な左側のナビゲーションメニュー | Experience Cloud でアプリケーションの左側のナビゲーションメニューをカスタマイズできるようになりました。 最も重要な機能にすばやくアクセスできるよう、ナビゲーション項目を並べ替えて、その表示を制御します。 このアップデートにより、ワークフローが効率化され、認知負荷が軽減され、完全なキーボードアクセシビリティがサポートされます。 | <ul><li>Experience Platform</li><li>Journey Optimizer</li><li>Journey Optimizer B2B エディション</li><li>Dynamic Chat</li></ul> |

以下に関するヘルプについて詳しくは、[Experience Cloud インターフェイスおよび管理](https://experienceleague.adobe.com/ja/docs/core-services/interface/experience-cloud)ガイドを参照してください。

<!-- * [Generative AI in Experience Cloud applications](https://experienceleague.adobe.com/en/docs/core-services/interface/features/generative-ai)
* [User management and product licenses](https://experienceleague.adobe.com/en/docs/core-services/interface/administration/admin-console) (Admin Console)
* [Customer Attributes, Audience Library, Assets](https://experienceleague.adobe.com/en/docs/core-services/interface/services/overview), and more -->

+++

## [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] と [!UICONTROL Mobile SDK] の最新リリース情報と新規ドキュメントについて説明します。 新しいチュートリアルとナレッジベースのサポート記事を参照してください。

+++更新を表示

**Experience Platform**

**2025年10月22日（PT）**&#x200B;アップデート：詳しくは、[[!DNL Experience Platform] リリースノート](https://experienceleague.adobe.com/ja/docs/experience-platform/release-notes/latest)を参照してください。

**Mobile SDK**

更新日：**2026年1月7日（PT）**

詳しくは、[[!DNL Experience Platform] Mobile SDK リリースノート](https://developer.adobe.com/client-sdks/documentation/release-notes/)を参照してください。

<!-- ### New [!DNL Experience Platform] tutorials{#tutorials-aep}

New tutorials published for Adobe [!DNL Experience Platform] on Experience League.

| Published | Applications | Name | Type | Description |
| ----------| ---------- | ---------- | ---------- |---------- |
|November 2025| [!DNL Experience Platform] | [Use the Adobe Experience Platform Agent Orchestrator interface](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/ai-assistant/agent-orchestrator-ui)| Video | Learn how to interact with Experience Cloud solutions through contextual prompts, dynamic objects, and multiple specialized agents using Adobe Experience Platform Agent Orchestrator.  | -->

### 新しい [!DNL Experience Platform] でのナレッジベースのサポート{#kb-aep}

[!DNL Experience Platform] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年12月 | [Adobe Experience Platform でのプライバシーアクセスと削除リクエストの処理方法](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29736) | 新しい記事 | Adobe Experience Platform でのプライバシーアクセスと削除リクエストの処理方法について説明します。 |
| 2025年12月 | [カスタム CSV アップロードの場合、30 日後にオーディエンス母集団が減少する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29670) | 新しい記事 | Adobe Experience Platform（AEP）で CSV ファイルをアップロードして作成されたオーディエンスが、30 日後に選定済みプロファイルで急激な減少を示すことがある場合の、問題の解決策について説明します。 |
| 2025年12月 | [Power BI を Customer Journey Analytics AEP に接続する際に資格情報認証エラーが発生する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29668) | 新しい記事 | SQL クライアントを使用して Power BI を Adobe Customer Journey Analytics の BI コネクタに接続する際に認証エラーが発生したときの、AEP の問題の解決策について説明します。 |
| 2025年12月 | [Adobe Experience Platform の XDM ExperienceEvent データセットでアップデートがサポートされていない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29689) | 新しい記事 | データフローが Adobe Experience Platform の XDM ExperienceEvent データセットに対してアップデート操作やアップサート操作を実行しようとした際に、「*イベントのアップデートはサポートされていません*」というエラーが発生したときの、問題の解決策について説明します。 |
| 2025年12月 | [*書き出し順序に有効な宛先 ID が含まれていません*&#x200B;というエラーが、オーディエンスをアクティブ化する際に、 [!DNL Azure Blob]  の宛先で発生する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29708) | 新しい記事 | AEP で [!DNL Azure Blob] 接続を設定した後、必要なアクセス権が付与されていない場合にセグメントのアクティブ化中にエラーが発生したときの、問題の解決策について説明します。 |

+++

## [!DNL Real-Time CDP] {#rtcdp}

詳しくは、[!DNL Real-Time CDP] の最新のチュートリアルを参照してください。

+++新しいチュートリアルを表示

<!-- | Published | Name | Type | Description |
| ----------| ---------- | ---------- |---------- |
| October 2025 | [Configure a social destination](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/destinations/configure-a-social-destination#destinations) |  Video | Learn how to connect and activate audiences to a social destination. This video demonstrates the workflow using a LinkedIn Matched Audiences destination in Adobe Real-Time Customer Data Platform.| -->

ヘルプについては、以下を参照してください。

* ビデオチュートリアル：[Real-Time Customer Data Platform について](https://experienceleague.adobe.com/ja/docs/platform-learn/tutorials/rtcdp/understanding-the-real-time-customer-data-platform)

* 製品ドキュメント：[Real-Time Customer Data Platform](https://experienceleague.adobe.com/ja/docs/real-time-customer-data-platform)

+++

## [!DNL Analytics] {#analytics}

[!DNL Adobe Analytics] と [!DNL AppMeasurement] の最新のリリース情報を確認してください。 新しいチュートリアルとサポート記事を参照してください。

+++リリースノートと新しいチュートリアル

Adobe Analytics リリースは、継続的な配信モデルに基づいて動作します。このモデルにより、機能のデプロイメントに対する、よりスケーラブルかつ段階的なアプローチが可能になります。 リリースノートは月に数回更新されます。

更新日：**2026年1月15日（PT）**

詳しくは、[[!DNL Analytics] リリースノート](https://experienceleague-review.corp.adobe.com/docs/analytics/release-notes/latest.html)を参照してください。

### AppMeasurement {#appm}

詳しくは、[AppMeasurement JavaScript 版リリースノート](https://github.com/adobe/appmeasurement/releases)を参照してください。

<!-- ### New Analytics tutorials {#tutorials-analytics}

New or updated video tutorials published for Adobe Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|November 2025|[Classification sets job history](https://experienceleague.adobe.com/en/docs/analytics-learn/tutorials/components/classifications/classification-sets-job-history)| Video |See your job history of uploading and downloading classification set data.|
|November 2025|[Classification sets data import methods](https://experienceleague.adobe.com/en/docs/analytics-learn/tutorials/components/classifications/classification-sets-data-import-methods)| Video |Learn different methods of importing classification data with classification sets, as well as some associated use cases.| -->

<!--
### New [!DNL Analytics] support knowledge base{#kb-analytics}

New articles and updates to existing articles for [!DNL Analytics].

|Published|Name|Type|Description|
|---------|--------|---------|---------|
|November 2025|[Why does the **[!UICONTROL Workspace]** **[!UICONTROL Page]** dimension show over 100 bytes (page length exceeds 100-bytes limit)?](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-28067)|New article| Learn about the solutions to the issue when a page listed in the **[!UICONTROL Page]** dimension appeared to have a string value exceeding 100 bytes, even though the page dimension has a 100-byte limit.|
-->

+++

## [!DNL Customer Journey Analytics] {#cja}

[!DNL Customer Journey Analytics] の最新のリリース情報をご確認ください。 Experience League で新しいチュートリアルを参照してください。

+++リリースノートと新しいチュートリアル

[!DNL Customer Journey Analytics] のリリースは継続的に行われます。 したがって、リリースノートは月に数回更新されます。 定期的に確認してください。

更新日：**2026年1月15日（PT）**

詳しくは、[Customer Journey Analytics（CJA）リリースノート](https://experienceleague-review.corp.adobe.com/docs/analytics-platform/using/releases/latest.html#releases)を参照してください。

### 新しい [!DNL Customer Journey Analytics] チュートリアル {#tutorials-cja}

[!DNL Customer Journey Analytics] の新しいチュートリアルが公開されました。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2026年1月 | [CJA ステッチの有効化と検証](https://experienceleague.adobe.com/ja/docs/customer-journey-analytics-learn/tutorials/visitor-id/stitching-enablement-and-validation) | ビデオ | 任意のイベントデータセットでステッチを有効にする方法について説明します。 |
| 2026年1月 | [AI トラフィックの追跡と分析](https://experienceleague.adobe.com/ja/docs/customer-journey-analytics-learn/tutorials/use-cases/ai/track-and-analyze-ai-traffic) | ビデオ | 派生フィールド、セグメント、Workspace プロジェクトを使用して、Adobe Customer Journey Analytics で AI 生成トラフィックを特定およびフィルタリングし、正確で人間に焦点を当てた顧客インサイトを確保する方法について説明します。 |

<!--
### New [!DNL Customer Journey Analytics] support knowledge base{#kb-cja}

New articles and updates to existing articles for [!DNL Customer Journey Analytics].

|Published|Name|Type|Description|
|---------|----|----|-----------|
|July 2025|[Access issues with shared metrics and dimensions in CJA](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27020)|New article| Learn about the solutions to the issue in Adobe Customer Journey Analytics where you can't access **[!UICONTROL Shared Metrics and Dimensions]**.|
-->

+++

## [!DNL Streaming Media Analytics] {#sma}

[!DNL Streaming Media Analytics] の最新のリリース情報をご確認ください。 Experience League で新しいチュートリアルを参照してください。

+++リリースノート

更新日：**2025年10月**

* [!DNL Streaming Media Analytics] [リリースノート](https://experienceleague.adobe.com/ja/docs/media-analytics/using/release-notes/release-notes)

* [!DNL Streaming Media Analytics] [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/ja/docs/media-analytics/using/media-overview)

+++

## [!DNL Experience Manager] {#aem}

[!DNL Experience Manager] の新機能、修正点および更新。 アドビでは、安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

+++リリースノート、新しいチュートリアル、サポート記事

### Experience Manager as a Cloud Service リリースノート

新規：[AEM のエージェント型 AI](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/ai-in-aem/overview?#agentic-ai-in-aem)

現在のリリース：**2026.1.0 - 2026年1月29日（PT）**

* [AEM CS のリリースノートのホーム](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current)
* [最新の AEM CS リリースの概要ビデオ](https://experienceleague.adobe.com/ja/docs/events/aemcs-release-update-recordings/overview)

他の [!DNL Experience Manager] 製品のリリースノートは次のページに記載されています。

* [[!DNL Experience Manager]  6.5 サービスパックリリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-65/content/release-notes/release-notes)
* [[!DNL Experience Manager]  Cloud Manager リリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-manager/content/release-notes/current)
* [自動フォーム変換サービスリリースノート](https://experienceleague.adobe.com/ja/docs/aem-forms-automated-conversion-service/using/release-notes)
* [[!DNL Experience Manager]  Assets Dynamic Media リリースノート](https://experienceleague.adobe.com/ja/docs/dynamic-media-developer-resources/release-notes/s7rn2017)
* [[!DNL Experience Manager]  Brand Portal リリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes)
* [[!DNL Experience Manager]  デスクトップアプリケーションリリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-desktop-app/using/release-notes)
* [[!DNL Experience Manager]  Dispatcher リリースノート](https://experienceleague.adobe.com/ja/docs/experience-manager-dispatcher/using/getting-started/release-notes)

### 新しい [!DNL Experience Manager] チュートリアル {#tutorials-aem}

[!DNL Experience Manager as a Cloud Service] の新しいビデオとチュートリアル（記事）が公開されました。

| 公開日 | アプリケーション | 名前 | 形式 | 説明 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2026年1月 | [!DNL AEM Assets] | [Dynamic Media URL 構文と画像プリセットのベストプラクティス](https://experienceleague.adobe.com/ja/docs/experience-manager-learn/assets/dynamic-media/images/dynamic-media-urls-and-image-presets) | ビデオ | AEM Assets の Dynamic Media URL 構文を探索し、画像プリセットを使用して価値を最大化する方法について説明します。 アセット管理機能を強化し、ワークフローの効率を向上させます。 |
| 2026年1月 | [!DNL AEM Assets] | [AEM Assets コンテンツハブでのアセットのダウンロード](https://experienceleague.adobe.com/ja/docs/experience-manager-learn/assets/content-hub/download-assets) | ビデオ | Adobe Experience Manager Assets コンテンツハブでアセットをナビゲート、検索、ダウンロードする方法について説明します。 |
| 2026年1月 | [!DNL AEM CS] | [AEM のエージェント](https://experienceleague.adobe.com/ja/docs/experience-manager-learn/cloud-service/ai/agents-in-aem) | ビデオ | AEM エージェントが Adobe Experience Manager でタスクを自動化してワークフローを効率化する方法について説明します。 |

### 新しい [!DNL Experience Manager] でのナレッジベースのサポート{#kb-aem}

[!DNL Experience Manager] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|--------|---------|---------|
| 2025年12月 | [Dynamic Media Scene7 キャッシュの有効期間（TTL）に関する質問](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29687) | 新しい記事 | Dynamic Media Scene7 キャッシュの有効期間（TTL）設定について説明します。 |
| 2025年12月 | [特定の地域のユーザーのサブセットに対して Dynamic Media 画像の読み込みが失敗する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29709) | 新しい記事 | 特定の URL を他のユーザーが正常に読み込める際、ユーザーの特定のサブセットが Dynamic Media に読み込めない場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM でコレクションを更新した後、Brand Portal 共有リンクにアセットが表示されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28072) | 新しい記事 | アセットを追加または更新した後に共有コレクションリンクに「*表示するコンテンツがありません*」と表示される場合の AEM Brand Portal の問題の解決策について説明します。 |
| 2025年12月 | [エンドポイント URL フィールドを使用しない AEM 6.5.23 での  [!DNL Microsoft Translator]  の設定](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28099) | 新しい記事 | [!DNL Microsoft Translator] を Adobe Experience Manager（AEM）6.5.23 と統合する際に、設定ダイアログに Microsoft エンドポイント URL を入力するフィールドが表示されない場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM Dynamic Media のエンコーディングの破損により、ビデオの再生に失敗する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29548) | 新しい記事 | 特定のビデオアセットのエンコーディングの破損により、Adobe Experience Manager（AEM）Dynamic Media でビデオの再生が途中で停止した場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM Dynamic Media で HLS／DASH 用の大量のビデオアセットを効率的に再処理する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29601) | 新しい記事 | AEM Dynamic Media で HLS／DASH ストリーミング用のビデオアセットを再処理する際、一括で実行するとシステムが過負荷になり、エラーが発生する場合の問題の解決策について説明します。 |
| 2025年12月 | [JSON ファイルを使用すると、AEM で不要な DAM のアセット更新ワークフローがトリガーされる](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29606) | 新しい記事 | JSON ファイルを Assets にアップロードすると DAM のアセットの更新ワークフローがトリガーされ、不要な処理とレンディションが作成される場合の AEM の問題の解決策について説明します。 |
| 2025年12月 | [AEM ログに「*`FT_GRANITE-61513` の切り替えが無効です*」と表示される理由](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29639) | 新しい記事 | AEM as a Cloud Service で公開する際に、`FT_GRANITE-61513` が無効であることを示すログが表示される場合の問題の解決策について説明します。 |
| 2025年12月 | [Adobe Experience Manager：AEM 6.5 LTS SP1 にアップグレードした後、多くのインデックスアップデートメッセージが再表示される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29732) | 新しい記事 | AEM 6.5 LTS SP1 にアップグレードした後、以前は表示されなかったインデックスログメッセージがアップグレード後に再表示される場合の問題の解決策について説明します。 |
| 2025年12月 | [Adobe Experience Manager：AEM as a Cloud Service で「*フォームを送信できませんでした*」というエラーメッセージが表示され、ローンチコンテンツを保存できない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29733) | 新しい記事 | ローンチに追加されたコンテンツを保存しようとした際に、「*フォームを送信できませんでした*」というエラーメッセージが表示され、変更が正常に保存されない場合の AEMaaCS の問題の解決策について説明します。 |
| 2025年12月 | [AEM 6.5 SP23 へのアップグレード後に `model.json` で `allowedComponents` が見つからない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28057) | 新しい記事 | サービスパック 23 にアップグレードした後、パブリッシュインスタンスの `model.json` の書き出しに `allowedComponents` メタデータが含まれなくなった場合の AEM の問題の解決策について説明します。 |
| 2025年12月 | [AEM パブリッシュインスタンスで繰り返し発生する *SegmentNotFoundException* エラーの解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28172) | 新しい記事 | *SegmentNotFoundException* エラーが繰り返し発生し、Adobe Experience Manager（AEM）パブリッシュインスタンスがクラッシュして応答しなくなる場合の問題の解決策について説明します。 |
| 2025年12月 | [WebP サポートのための AEM `AdaptiveImageServletMappingConfigurationFactory` の上書き](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29598) | 新しい記事 | `AdaptiveImageServletMappingConfigurationFactory` 設定に WebP 拡張機能が含まれていない限り、Adobe Experience Manager（AEM）の画像コンポーネントが WebP アセットをレンダリングしない場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM 6.5 の権限で発生するタグ移動エラーの解決](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29651) | 新しい記事 | タグをある名前空間から別の名前空間に移動してから元の場所に戻すと、「*アクセスが拒否されました*」というエラーが表示され、操作に失敗した場合の問題の解決策について説明します。 |
| 2025年12月 | [親ページが AEM で公開されるまで、子ページの変更が表示されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29671) | 新しい記事 | 親ページも公開しない限り、子ページに行った変更がライブサイトに表示されない場合の AEM Managed Services の問題の解決策について説明します。 |
| 2025年12月 | [AEM でロックされた子ページにより、言語マスターページの非公開に失敗する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29650) | 新しい記事 | AEM でロックされた子ページにより、言語マスターページの非公開に失敗した場合の問題の解決策について説明します。 |
| 2025年12月 | [Acrobat のセキュリティ設定により、PDF Generator で PDF の書き出しに失敗し、エラー *ALC-PDG-010-011* が発生する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28137) | 新しい記事 | [!DNL Windows Server 2022] 上の AEM Forms 6.5.23 で PDF Generator を使用して PDF を [!DNL Word]、[!DNL Excel]、その他の形式に書き出す際に、PDFMaker に接続できないことを示すエラー *ALC-PDG-010-011* が発生してプロセスに失敗した場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM 6.5（Forms およびその他のソリューション）の  [!DNL Groovy Console]  監査証跡により発生するセグメントストアの増加を解決する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28178) | 新しい記事 | AEM 6.5 オンプレミスまたは AMS 環境で突然のディスクスパイクが発生し、[!UICONTROL TarMK] セグメントストアが急速に増加した場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM Forms でのフォーム起動中にシリアル化に失敗する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29676) | 新しい記事 | AEM Forms へのアップグレード後にシリアル化エラーが発生してサーバーの起動に失敗した場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM Sites のインラインスクリプトに対するコンテンツセキュリティポリシー nonce のサポート](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29587) | 新しい記事 | 安全でないディレクティブを使用せずにインラインスクリプトを読み込むための CSP nonce または安全な代替手段を AEM Sites がサポートしているかどうかについて説明します。 |
| 2025年12月 | [AEM as a Cloud Service でリポジトリなしの環境を設定する際の認証エラー](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-27823) | 新しい記事 | Adobe Experience Manager（AEM）as a Cloud Service で EDS/xwalk プロジェクトのリポジトリなしの環境を設定する際に、「*403 Forbidden [admin] not authorized*」エラーが発生した場合の問題の解決策について説明します。 |
| 2025年12月 | [Dynamic Media または AEM Assets のアセットがコンテンツハブに表示されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28074) | 新しい記事 | AEM as a Cloud Service のコンテンツハブで、公開および承認後も Dynamic Media または AEM Assets のアセットが表示されない場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM コンテンツフラグメントのカスタムロケールフォルダーで一意のフィールド検証に失敗する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28085) | 新しい記事 | AEM のカスタムロケールフォルダー名が言語ルートとして認識されないことが原因で、一意のフィールド検証エラーが発生した場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM as a Cloud Service でのユーザーノードの破損によるログインエラー](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28127) | 新しい記事 | Adobe Experience Manager（AEM）as a Cloud Service で、ユーザーノードに無効なメールアドレスなどの破損したデータや正しくないデータが含まれている際に、特定のユーザーにログインエラーが発生した場合の問題の解決策について説明します。 |
| 2025年12月 | [ワークフローのベルアイコンに、AEM の Admin Console ユーザーのローカルタスクが表示されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28140) | 新しい記事 | 参加者のステップ承認などのローカルワークフロータスクが、インボックスに表示されているにもかかわらず、Admin Console と同期されたユーザーのベルアイコンに表示されない場合の問題の解決策について説明します。 |
| 2025年12月 | [AEMaaCS で更新すると、編集モードで Dynamic Media レイアウトコンテナが表示されなくなる](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28171) | 新しい記事 | Adobe Experience Manager as a Cloud Service（AEMaaCS）でビデオオーサリング用の Dynamic Media コアコンポーネントを操作する際に、更新後に編集モードのページからレイアウトコンテナが表示されなくなる場合の問題の解決策について説明します。 |
| 2025年12月 | [AEM as a Cloud Service の機能テスト中に 401 未認証エラーが発生する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28177) | 新しい記事 | Dispatcher がサポートされていない基本認証を使用しているので、AEM as a Cloud Service の機能テスト中に 401 未認証エラーが発生した場合の問題の解決策について説明します。 |
| 2025年12月 | [Adobe Experience Manager as a Cloud Service で&#x200B;**[!UICONTROL 送信元]**&#x200B;アドレスが異なるとワークフローメールが配信されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29609) | 新しい記事 | Day CQ メールサービスの&#x200B;**[!UICONTROL 送信元]**&#x200B;アドレスが Day CQ ワークフローメール通知サービスの送信元アドレスと一致しない際に、ワークフローメール通知の送信に失敗する場合の AEMaaCS の問題の解決策について説明します。 |
| 2025年12月 | [AEMaaCS の権限不足により、コンテンツフラグメントを含む DAM フォルダーの公開に失敗する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29652) | 新しい記事 | Adobe Experience Manager as a Cloud Service（AEMaaCS）でコンテンツフラグメントを含む DAM フォルダーを公開する際に、公開を管理する権限が不十分であるというエラーが発生した場合の、問題の解決策について説明します。 |
| 2025年12月 | [AEMaaCS の承認済みアセットの配信 URL が見つからない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28098) | 新しい記事 | OpenAPI を備えた Dynamic Media が有効になっているが、ユーザー権限が見つからない際に、Adobe Experience Manager as a Cloud Service（AEMaaCS）で承認および公開済みアセットの配信 URL が表示されない場合の、問題の解決策について説明します。 |
| 2025年12月 | [エンコードされたスラッシュを含む URL で 403 Forbidden エラーが返される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28182) | 新しい記事 | URL にエンコードされたスラッシュ（`%2F`）が含まれ、Adobe Experience Manager as a Cloud Service で 403 Forbidden エラーが返される場合の、問題の解決策について説明します。 |

+++

## [!DNL Adobe LLM Optimizer] {#llm-optimizer}

詳しくは、生成エンジン最適化用のアドビの新しい生成 AI ファーストアプリケーションである LLM Optimizer のヘルプを参照してください。

+++最新のチュートリアル

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2025年11月 | [LLM Optimizer のベストプラクティス](https://experienceleague.adobe.com/ja/docs/llm-optimizer/using/essentials/best-practices) | ビデオ | AI 検索でのブランドの可視性を高めるための LLM 最適化のベストプラクティスについて説明します。 コンテンツのベンチマークと最適化に関するインサイトについても説明します。 |
| 2025年11月 | [カテゴリ、トピック、プロンプトなどを設定するためのベストプラクティス](https://experienceleague.adobe.com/ja/docs/llm-optimizer/using/essentials/best-practices-topics-prompts) | ビデオ | カスタマイズされたブランド監視と戦略的なコンテンツ分析のために、競合他社を含む、追跡するカテゴリ、トピック、プロンプト、その他のブランドを設定して、LLM インサイトを最適化します。 |

+++

## [!DNL Brand Concierge] {#brand-concierge}

[!DNL Brand Concierge] の最新のチュートリアルとビデオをご確認ください。

+++新しいチュートリアル

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2026年1月 | [会議の予約](https://experienceleague.adobe.com/ja/docs/brand-concierge/content/getting-started/meeting-booking) | ビデオ | 会議の予約方法について説明します。 顧客としてエクスペリエンスを確認し、担当者がカレンダーを使用してレポートを表示するように設定する |

詳しくは、[Adobe Brand Concierge](https://experienceleague.adobe.com/ja/docs/brand-concierge/content/home) チュートリアルのホームページを参照してください。

+++

## [!DNL Commerce] {#commerce}

[!DNL Adobe Commerce] のリリースノート、新しいチュートリアルおよびナレッジベースサポート記事にアクセスできます。

+++リリースノート、新しいチュートリアル、サポート記事

* 最新情報について詳しくは、最新の [&#x200B; [!DNL Adobe Commerce]  および  [!DNL Magento Open Source]](https://experienceleague.adobe.com/ja/docs/commerce-operations/release/notes/overview)のリリースノートを参照してください。
* Commerce サービスのリリース情報とドキュメントを確認するには、[Adobe [!DNL Commerce] サービスガイド](https://experienceleague.adobe.com/ja/docs/commerce/user-guides/home)を参照してください。
* 個々の製品のリリースノートにアクセスして可用性を確認する方法について詳しくは、[製品の可用性](https://experienceleague.adobe.com/ja/docs/commerce-operations/release/product-availability)を参照してください。

### [!DNL Adobe Commerce] の新しいチュートリアル {#tutorials-commerce}

Experience League に関する [!DNL Adobe Commerce] の新しいチュートリアル。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2026年1月 | [オブザーバビリティの概要](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/observability/overview) | ビデオ | 一元化されたオブザーバビリティが最新の Adobe Commerce アーキテクチャに不可欠である理由について説明します。 |
| 2026年1月 | [Open Telemetry](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/observability/open-telemetry) | ビデオ | Open Telemetry が単一の監視ツールにロックされることなく、ログ、トレース、指標全体のオブザーバビリティを標準化する方法について説明します。 |
| 2026年1月 | [設定](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/observability/demo-setup-configuration) | ビデオ | 標準化された相関テレメトリを使用して、Adobe Commerce とカスタムアプリケーション全体でエンドツーエンドのオブザーバビリティを実現する方法について説明します。 |
| 2026年1月 | [オブザーバビリティデモ](https://experienceleague.adobe.com/ja/docs/commerce-learn/tutorials/observability/demo) | ビデオ | Adobe Commerce がオブザーバビリティ、Webhook、イベント相関性を使用して、シームレスな順序のトラッキングとデバッグを行う方法について説明します。 |

### 新しい [!DNL Commerce] のナレッジベースへのサポート{#kb-commerce}

Adobe Commerce の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|--------|---------|---------|
| 2025年12月 | [[!DNL Quality Patches Tool] （QPT）](https://experienceleague.adobe.com/ja/docs/commerce-operations/tools/quality-patches-tool/patches-available-in-qpt/patches-available-in-qpt-tool-overview) | 新しい記事 | QPT 1.1.74 で使用可能なパッチの適用方法に関する新しい記事が公開され、それぞれの節で参照できるようになりました。 |
| 2025年12月 | [複数の組織に割り当てられたユーザーの Adobe Identity Management Service（IMS）ログインの問題](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29604) | 新しい記事 | 複数の Adobe IMS 組織に属する Adobe Commerce ユーザーがログイン時に間違った組織を選択した際、ログインに失敗した場合の問題の解決策について説明します。 |
| 2025年12月 | [[!DNL Fastly]  キャッシュが Adobe Commerce on Cloud インフラストラクチャーで機能しない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29629) | 新しい記事 | [!DNL Fastly] キャッシュがサイトで機能しない場合の問題の解決策について説明します。 |
| 2025年12月 | [&#x200B; 無効化されたキャッシュにより、応答時間が低下する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29631) | 新しい記事 | Adobe Commerce ストアのパフォーマンスを低下させることがある、キャッシュの無効化を防ぐ方法について説明します。 |
| 2025年12月 | [Adobe Commerce のデータベースストレージに関するトラブルシューティング](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29633) | 新しい記事 | Adobe Commerce のデータベースストレージの問題の解決策について説明します。 |
| 2025年12月 | [Adobe Commerce デプロイメントに関するトラブルシューティング](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29640) | 新しい記事 | Adobe Commerce でデプロイメントの停止やデプロイメントの失敗が発生した場合の問題の解決策について説明します。 |
| 2025年12月 | [Adobe Commerce バックエンドでエンティティを保存できない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29642) | 新しい記事 | Adobe Commerce バックエンドでエンティティを保存できない場合の問題の解決策について説明します。 |
| 2025年12月 | [CSV の読み込み後、新規顧客がカスタマーグリッドに表示されない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29643) | 新しい記事 | `.csv` ファイルから読み込んだ後、**[!UICONTROL 顧客]**／**[!UICONTROL すべての顧客]**&#x200B;の下に新規顧客が表示されない場合の、問題の解決策について説明します。 |
| 2025年12月 | [Adobe Commerce の `/tmp` マウントがいっぱいになる問題のトラブルシューティング](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29644) | 新しい記事 | `/tmp` マウントがいっぱいで、サイトがダウンしている可能性があり、ノードに SSH 接続できない場合の問題の解決策について説明します。 |
| 2025年12月 | [ソースの削除またはソースコードの変更を実行できない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29648) | 新しい記事 | システムにより、ソースの削除またはソースコードの変更が制限されているので、これらのアクションを実行できない場合の、問題の解決策について説明します。 |
| 2025年12月 | [「*生成された／コードディレクトリにクラスを保存できません*」エラーの修正](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29649) | 新しい記事 | 依存関係の指定方法によりクラスがその場で自動生成されず、「*生成された／コードディレクトリにクラスを保存できません*」というエラーメッセージが表示される場合の問題の解決策について説明します。 |
| 2025年12月 | [Adobe Commerce の  [!DNL Fastly]  に関するトラブルシューティング](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29661) | 新しい記事 | Adobe Commerce ユーザー向けのこの [!DNL Fastly] に関するトラブルシューティングでは、発生した症状に関する回答に基づく解決策について説明します。 |
| 2025年12月 | [クラウド上の  [!DNL Fastly]  キャッシュのパージ中にエラー（*パージリクエストが正常に処理されませんでした*）が発生する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29667) | 新しい記事 | [!DNL Fastly] パージオプションが使用され、「*パージリクエストが正常に処理されませんでした*」というエラーが発生した場合の問題の解決策について説明します。 |
| 2025年12月 | [1,000 個以上の製品を含むカテゴリを保存すると、504 ゲートウェイタイムアウトエラーが発生する](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29703) | 新しい記事 | 大規模なカテゴリ（1,000 個以上の製品）に対して操作を実行する際に発生するタイムアウトの問題の解決策について説明します。 |


+++

## [!DNL Target] {#target}

[!DNL Adobe Target] のプレリリースノート、現在のリリースノートおよび新しいチュートリアルにアクセスできます。

+++リリースノート

リリース日：**2025年11月14日（PT）**

<!-- ### New [!DNL Target] support knowledge base{#kb-target}

|Published|Name|Type|Description|
|---------|----|----|-----------|
|July 2024|[[!DNL Adobe Target] bulk profile update [!DNL API] throws *[!DNL Unexpected Error]* when using [!DNL Postman]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24281)|New article| Learn about how to fix the issue when running the [!DNL Target Bulk Profile Update API] throws the *[!DNL Unexpected Error]* message in [!DNL Postman].|
-->

* プレリリース情報については、[[!DNL Adobe Target] プレリリース](https://experienceleague.adobe.com/ja/docs/target/using/release-notes/target-release-notes)を参照してください。
* 現在の情報については、[[!DNL Adobe Target] リリースノート](https://experienceleague.adobe.com/ja/docs/target/using/release-notes/release-notes)を参照してください。

+++

## [!DNL Campaign] {#ac}

[!DNL Adobe Campaign] の最新のアップデート情報を取得できます。 Experience League で新しいチュートリアルとナレッジベースのサポート記事を確認してください。

+++リリースノートとサポート記事

### 最新の Campaign 製品リリース

* [!DNL Web User Interface]：2025年10月25日（PT）- [リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/release-notes/release-notes) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/campaign-web-home)

* [!DNL Campaign] v8：2025年10月9日（PT）- [リリースノート](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/releases/release-notes#release-8-7-4) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/campaign-home)

* [!DNL Campaign Standard]：25.1.2 - 夏 2025 - [リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-standard/using/release-notes/release-notes) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-standard/using/campaign-standard-home)

* [!DNL Campaign Classic] 7.4.2：2025年5月12日（PT）- [リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-classic/using/release-notes/latest-release#release-7-4-2) | [製品ドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-classic/using/campaign-classic-home)

<!-- ### New [!DNL Campaign] tutorials {#tutorials-campaign}

New or updated videos tutorials published for Adobe Campaign.

| Published | Application | Name | Type | Description |
| ----------| ---------- | ---------- | ---------- |---------- |
|August 2025|Campaign v8 Web User Interface |[Enhance a delivery with dynamic content](https://experienceleague.adobe.com/en/docs/campaign-web-learn/tutorials/content-management/enhance-a-delivery-with-dynamic-content)| Video tutorial |Learn how to use the generative AI powered Content Generator to create and enhance the email content, optimizing your email deliveries to better resonate with your audience.|
|August 2025|Campaign v8 Web User Interface |[Configure JavaScript code activity](https://experienceleague.adobe.com/en/docs/campaign-web-learn/tutorials/workflows/configure-java-script-code-activity)| Video tutorial |Learn how to use the JavaScript Code activity in Adobe Campaign Web v8 to enhance your workflows. This tutorial covers both simple and advanced scripting modes. It explains execution settings and error handling. View real-world examples, such as targeting VIP profiles, transforming data, and triggering conditional operations. |
 -->

### 新しい [!DNL Campaign] でのナレッジベースのサポート{#kb-campaign}

[!DNL Campaign] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年12月 | [`queryDef` により、Adobe Campaign ワークフローで 10,000 個のレコードのみが返される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28003) | 新しい記事 | Adobe Campaign Classic でワークフローを実行する際に、`lineCount` 属性を指定しないと、JavaScript アクティビティ内の `queryDef` により、10,000 個のレコードのみが返される場合の問題の解決策について説明します。 |
| 2025年12月 | [Adobe Campaign Standard の配信数のしきい値により、レポートでのキャンペーンの表示が制限される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28077) | 新しい記事 | Adobe Campaign Standard でキャンペーン名でフィルタリングする際に、一部のビジネスユーザーが「一般&#x200B;**[!UICONTROL レポート]**」セクションで特定の毎月のキャンペーンを表示できない場合の問題の解決策について説明します。 |
| 2025年12月 | [外部アカウントのクリーンアップにより、Adobe Campaign Classic のリストテーブルが削除される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28069) | 新しい記事 | Adobe Campaign Classic（ACC）環境で受信者リストと非受信者リストのデータベーステーブルが毎日削除される場合の問題の解決策について説明します。 |
| 2025年12月 | [Campaign Standard：キャンペーンラベルでグローバルレポートをフィルタリングすると、ユーザーごとに異なる結果が表示される](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-29728) | 新しい記事 | キャンペーンの名前をフィルターとして使用して&#x200B;**[!UICONTROL グローバルレポート]**&#x200B;をフィルタリングする際に、様々な役割を持つユーザーに異なる数値が表示される理由について説明します。 |

+++

## [!DNL Journey Optimizer] {#journey-opt}

[!DNL Journey Optimizer] の最新のリリース情報について説明します。 Experience League で最新のチュートリアルおよびナレッジベースのサポート記事を確認してください。

+++リリースノートと新しいチュートリアル

### [!DNL Journey Optimizer] 製品リリースのアップデート

最新リリース：**2025年11月24日（PT）**

詳しくは、[Journey Optimizer リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes)を参照してください（**メモ：**&#x200B;[Journey Optimizer B2B Edition 版](#journey-optimizer-b2b-edition)は別の製品です）。

### 新しい [!DNL Journey Optimizer] チュートリアル {#tutorials-ajo}

Experience League に関する Adobe [!DNL Journey Optimizer] の新しいチュートリアルが公開されました。

| 公開日 | アプリケーション | 名前 | タイプ | 説明 |
| ---------- | ---------- | ---------- | ---------- |---------- |
| 2026年1月 | [!DNL Journey Optimizer] | [モバイル学習ハブ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/mobile-learning-hub/overview) | 複数ページのチュートリアル | Adobe Journey Optimizer を使用して、モバイルエンゲージメント戦略をすぐに開始または強化します。 モバイル学習ハブは、開発者、管理者、マーケターおよびアナリストに、インバウンドとアウトバウンドのモバイルチャネルを設定し、強力なクロスチャネルキャンペーンやジャーニーへとシームレスに統合するために必要なすべてを提供します。 |

### 新しい [!DNL Journey Optimizer] でのナレッジベースのサポート{#kb-ajo}

[!DNL Journey Optimizer] の新しい記事と既存記事の更新です。

| 公開日 | 名前 | タイプ | 説明 |
|---------|----|----|-----------|
| 2025年12月 | [Journey Optimizer のカスタムアクション応答で配列がサポートされていない](https://experienceleague.adobe.com/ja/docs/experience-cloud-kcs/kbarticles/ka-28054) | 新しい記事 | Adobe Journey Optimize（AJO）のカスタムアクションから API を呼び出す際に、応答として配列が返される場合の問題の解決策について説明します。 |


### [!DNL Journey Optimizer] のその他のリソース

* [[!DNL Journey Optimizer] ドキュメント](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/ajo-home) - [リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes) - [チュートリアルビデオ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/overview)
* [意思決定管理ドキュメント](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/decisioning/offer-decisioning/get-started-decision/starting-offer-decisioning) - [リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/release-notes) - [チュートリアルビデオ](https://experienceleague.adobe.com/ja/docs/journey-optimizer-learn/tutorials/decision-capabilities/decision-management/introduction-to-decision-management) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/whats-new/documentation-updates)

+++

## [!DNL Journey Optimizer B2B Edition] {#ajo-b2b}

[!DNL Journey Optimizer B2B Edition] の最新のリリース情報について説明します。

+++リリースノートとドキュメント

最新リリース：**2025.10 - 2025年10月31日（PT）**

詳しくは、[AJO B2B Edition リリースノート](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b/user/release-notes)を参照してください。

**AJO B2B リソース**

* [[!DNL Journey Optimizer B2B Edition]](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b)（すべてのセルフヘルプ）
* [!DNL Journey Optimizer B2B Edition] の[製品ドキュメント](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b/user/guide-overview)
* [!DNL Journey Optimizer B2B Edition] の[ビデオの概要とチュートリアル](https://experienceleague.adobe.com/ja/docs/journey-optimizer-b2b-learn/tutorials/overview)
* [!DNL Journey Optimizer B2B Edition] の[製品の説明とライセンス](https://helpx.adobe.com/jp/legal/product-descriptions/adobe-journey-optimizer-b2b.html#_blankl)

<!-- New videos, tutorials, or courses published for Journey Optimizer B2B Edition.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February 2025|[Account Journeys](https://experienceleague.adobe.com/en/docs/journey-optimizer-b2b-learn/tutorials/account-journeys/introducing-account-journeys)|New videos |Visit the Account Journeys tutorial home. Learn about Account Journeys and how to use them to engage your target audience.|
|February 2025|[Use Case Playbook - Abandoned shopping cart](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/use-cases/abandoned-cart)|New video |Learn how to implement the abandoned shopping cart use case, using the Playbook feature in Adobe Journey Optimizer.|
|February 2025|[Import and activate an audience by uploading a CSV file](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/profiles-audiences-subscriptions/import-and-activate-an-audience-by-uploading-a-csv-file)|New video |Discover how to efficiently import and activate an audience by uploading a CSV file. Learn to personalize your content using enrichment attributes from the CSV file, ensuring a more tailored experience for your audience.| -->

+++

## [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] の最新のリリースノートとリリーススケジュールについて説明します。

+++リリースノート、チュートリアル、サポート記事

### Core Marketo Engage の更新

最新リリース：**2025年10月**

* [最新のリリースノート](https://experienceleague.adobe.com/ja/docs/marketo/using/release-notes/current)
* [!DNL Marketo Engage] [リリーススケジュール](https://experienceleague.adobe.com/ja/docs/marketo/using/release-notes/release-schedule)
* Dynamic Chat [リリースノート](https://experienceleague.adobe.com/ja/docs/marketo/using/release-notes/dynamic-chat)（2025年6月30日（PT））

<!-- ### New Marketo tutorials {#tutorials-marketo}

New tutorials published for Adobe Marketo.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|March 2025|[Best practices to implement live chat](https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/dynamic-chat/live-chat-best-practices)| New video |Learn about the best practices to follow when you're implementing the live chat feature in Dynamic Chat.| -->

最新の製品ドキュメントについて詳しくは、[Marketo 製品ドキュメント](https://experienceleague.adobe.com/ja/docs/marketo/using/home)ホームを参照してください。

<!-- ### New [!DNL Marketo] support knowledge base

New articles and updates to existing articles for [!DNL Marketo].

|Published|Name|Type|Description|
| -----------| ---------- | ---------- | ---------- |
|July 2025|[Marketo Measure touchpoints not syncing to Marketo Engage](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26692)|New article| Learn about the solutions to the issue when Marketo Measure touchpoints don't appear in Marketo Engage person records, even though they sync successfully to [!DNL Salesforce].| 
-->

+++

## [!DNL Workfront] {#workfront}

[!DNL Adobe Workfront] の最新のリリースノートについて説明します。 Experience League で新しいチュートリアルを確認してください。

+++リリースノートと新しいチュートリアル

### [!DNL Adobe Workfront] の更新

* [2026年第 1 四半期リリースの概要](https://experienceleague.adobe.com/ja/docs/workfront/using/product-announcements/product-releases/release-26-q1/26-q1-release-overview)

* [2025年第 4 四半期リリースの概要](https://experienceleague.adobe.com/ja/docs/workfront/using/product-announcements/product-releases/release-25-q4/25-q4-release-overview)

すべてのリリース情報について：

* [!DNL Workfront] のリリーススケジュール情報とリリースノートについては、[Adobe  [!DNL Workfront]  製品のリリース](https://experienceleague.adobe.com/ja/docs/workfront/using/product-announcements/product-releases/product-releases)のページを参照してください。

* Fusion の最新情報については、[Adobe [!DNL Workfront] Fusion リリースアクティビティの概要](https://experienceleague.adobe.com/ja/docs/workfront-fusion/using/fusion-release-activity/fusion-release-activity)を参照してください。

### 新しい Adobe [!DNL Workfront] チュートリアル {#tutorials-workfront}

Experience League の新しい [!DNL Workfront] チュートリアルとイベント。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2026年1月 | [Adobe Workfront プラグインを使用した Creative Cloud との統合](https://experienceleague.adobe.com/ja/docs/workfront-learn/tutorials-workfront/integrations/adobe-creative-cloud/use-adobe-workfront-extensions-for-creative-cloud) | ビデオ | Workfront を Creative Cloud と統合します。 Creative Cloud アプリケーション（Photoshop、XD、InDesign、Illustrator、Premiere Pro、After Effects）を離れることなく、Workfront で自分に割り当てられた作業を検索および更新できます。 |

<!--
### New [!DNL Workfront] support knowledge base

New articles and updates to existing articles for [!DNL Workfront].

|Published|Name|Type|Description|
| -----------| ---------- | ---------- | ---------- |
|August 2025|[Calendar appears blank when owner is deactivated in Workfront](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27192)|New article| Learn about the solutions to the issue when the owner of a calendar is deactivated, the calendar becomes blank, and no tasks or events are visible.|
|August 2025|[Error appears when assigning resource managers in Workfront](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27251)|New article| Learn about the solutions to the issue when the error *Only users with a plan license can be added as resource managers* occurs when attaching a project template that includes resource managers without the required license type.|
|August 2025|[Issue to project conversion grants home group "view" access by default in Workfront](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27261)|New article| Learn about the solutions to the issue when converting an issue into a project using a template in Adobe Workfront, the creator's home group automatically receives view access to the resulting project.|
|August 2025|[Duplicate folders auto-created in Workfront via [!DNL Fusion] scenarios](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27287)|New article| Learn about the solutions to the issue when duplicate folders are automatically created in certain Adobe Workfront projects due to active [!DNL Fusion] connections.|
|August 2025|[Unable to report on specific approver actions in Adobe Workfront](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27298)|New article| Learn about the solutions to the issue when Adobe Workfront reports don't natively support isolating actions taken by specific approvers in multi-stage approval workflows.|
|August 2025|[Unable to attach template to an existing project in Workfront](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27305)|New article| Learn about the solutions to the issue when an error occurs when attaching a template to an existing project in Adobe Workfront related to system-wide sharing permissions settings.|

For the latest product documentation, see the [Adobe [!DNL Workfront] documentation home page](https://experienceleague.adobe.com/en/docs/workfront/using/home).
-->

+++

## パフォーマンスマーケティング用の GenStudio {#genstudio-marketing}

[!DNL GenStudio for Performance Marketing] の最新リリース情報と新規ドキュメントについて説明します。

+++リリースノートとドキュメント

GenStudio for Performance Marketing について詳しくは、[2025.12.12 - リリースノート](https://experienceleague.adobe.com/ja/docs/genstudio-for-performance-marketing/user-guide/release-notes#latest)を参照してください。

<!-- ### New tutorials for GenStudio for Performance Marketing {#genstudio-tutorials}

Video tutorials for GenStudio for Performance Marketing.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|October 2025|[Assign Brand permissions](https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/intro/configure-brand-permissions)| Video |Learn about assigning entitlements for GenStudio for Performance Marketing Brand creators and editors.| -->

**GenStudio for Performance Marketing のリソース**

* [GenStudio for Performance Marketing](https://experienceleague.adobe.com/ja/browse/genstudio-for-performance-marketing)（すべてセルフヘルプ）
* パフォーマンスマーケティング用の GenStudio の[製品ドキュメント](https://experienceleague.adobe.com/ja/docs/genstudio-for-performance-marketing/user-guide/home)
* [パフォーマンスマーケティング用の GenStudio](https://business.adobe.com/jp/products/genstudio-for-performance-marketing.html) の製品情報

+++

## [!DNL Mix Modeler] {#mix-modeler}

+++リリースノートとドキュメント

詳しくは、Mix Modeler [2025年11月 - リリースノート](https://experienceleague.adobe.com/ja/docs/mix-modeler/using/releases/latest)を参照してください。

+++

## Adobe [!DNL Advertising] {#advertising}

[!DNL Adobe Advertising] の最新リリース情報と新規ドキュメントについて説明します。

+++リリースノート

Adobe [!DNL Advertising] ヘルプを参照するには、[Adobe Advertising ドキュメント](https://experienceleague.adobe.com/ja/docs/advertising)を参照してください。

### [!DNL Advertising DSP] の新機能 {#advertising-dsp}

2025年12月17日（PT）

[&#x200B; [!DNL Advertising DSP] の新機能](https://experienceleague.adobe.com/ja/docs/advertising/dsp/home)を参照してください。

### [!DNL Advertising Search, Social, & Commerce] の新機能 {#advertising-search}

2025年11月12日（PT）

[&#x200B; [!DNL Advertising Search, Social, & Commerce] の新機能](https://experienceleague.adobe.com/ja/docs/advertising/search-social-commerce/home)を参照してください。

+++

## [!DNL Adobe Pass] {#pass}

[!DNL Adobe Pass] は、放送局、ケーブルネットワークおよびサービスプロバイダーに適した、マルチスクリーン TV プラットフォームです。ユーザーの心をつかむパーソナライズ可能な視聴体験を作成し、収益化できます。

+++ドキュメント

リリース固有の情報、システム要件、制限事項、修正された問題および既知の問題については、[Adobe Pass ドキュメント](https://experienceleague.adobe.com/ja/docs/pass)を参照してください。

+++

## [!DNL Document Cloud] {#doc-cloud}

[!DNL Document Cloud]（[!DNL Acrobat Services] と [!DNL Acrobat Sign] を含む）向けに公開された新しいチュートリアルを参照してください。

+++最新のチュートリアルとコース

| 公開日 | アプリケーション | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2026年1月 | Acrobat | [PDF アクセシビリティの基本事項](https://experienceleague.adobe.com/en/courses/acr-pdf-accessibility-essentials) | コース | Acrobat Pro、Premium、Studio を使用して、アクセシビリティを備えた PDF を作成、確認、修正する方法について説明します。 |
| 2026年1月 | Acrobat | [複雑なテーブル](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/acrobat-learning/accessibility-tutorials/complex-tables) | ビデオ | Acrobat で、テーブルにアクセシビリティ用のタグ付けを行う方法について説明します。 |
| 2026年1月 | Acrobat | [タグ付けの基本](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/acrobat-learning/accessibility-tutorials/basics-tagging) | ビデオ | PDF ファイルにタグ付けしてアクセシビリティを確保する方法の基本について説明します。 |
| 2026年1月 | Acrobat | [Acrobat でのアクセシブルな PDF の作成](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/acrobat-learning/accessibility-tutorials/accessible-acrobat) | ビデオ | Acrobat で開始して、アクセシブルな PDF を作成する方法について説明します。 |
| 2026年1月 | Acrobat | 「[[!UICONTROL アクセシビリティを確保する]」ガイド付きアクション](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/acrobat-learning/accessibility-tutorials/make-accessible-action) | ビデオ | 「_[!UICONTROL アクセシビリティを確保する]_」ガイド付きアクションを使用して、PDF ファイルをアクセシブルにする方法について説明します。 |
| 2026年1月 | Acrobat Sign | [モバイル対応ビューの作成](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/sign-learning-hub/mobile/mobile-tutorials/create-mobile-friendly) | ビデオ | 開発者のサポートなしで、モバイル対応ドキュメントをシームレスに生成する方法について説明します。 |
| 2026年1月 | Acrobat Sign | [モバイル対応ビュー](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/sign-learning-hub/mobile/mobile-tutorials/mobile-friendly) | ビデオ | モバイル対応ビューを使用して、モバイルデバイスでフォームを完了する方法について説明します。 |
| 2026年1月 | Acrobat Sign | [カスタムワークフローの作成](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/building-a-custom-workflow) | ビデオ | カスタムワークフローを作成および使用して、契約書の作成と送信のプロセスを高速化する方法について説明します。 |

[!DNL Document Cloud] のチュートリアルについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/acrobat-learning/overview)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/ja/docs/document-cloud-learn/sign-learning-hub/overview)
* [Adobe Acrobat Services API チュートリアル](https://experienceleague.adobe.com/ja/docs/acrobat-services-learn/tutorials/overview)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

+++

## [!DNL Creative Cloud] エンタープライズ版 {#creative-cloud}

Firefly を含む [!DNL Adobe Creative Cloud for enterprise] のアプリケーション向けに公開された新しいチュートリアルを参照してください。

+++最新のチュートリアル

<!-- |Published|Application|Name|Type|Description |
| -----------| -----------|---------- | ---------- | ---------- |
| September 2025 | Firefly | [Create a Custom Model](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-tutorials/custom-model) |  Video | Learn how to build Custom Models in Firefly to create fresh new imagery for your organization's brand using specific types of styles--such as backgrounds, colors, and hues. |
| September 2025 | Firefly | [Background removal and replacement](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-creative-production/background) |  Video | Learn how to use Firefly Creative Production to remove and/or replace backgrounds at scale. | -->

詳しくは、[Creative Cloud エンタープライズ版](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview)のチュートリアルライブラリを参照してください。

+++

## 顧客データ管理 - 担当者の声 {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/ja/docs/events/customer-data-management-voices-recordings/overview) は、顧客データ管理の技術およびマーケティングプラクティスのリーダーやスペシャリストのためのページです。 このチュートリアルのコレクションには、同僚から話を聞き、インスピレーションを得て、MarTech の開発について学ぶためのリソースが一箇所に集められています。 登録は不要です。クリックで視聴できます。

## デジタルエクスペリエンスブループリント {#blueprints}

[デジタルエクスペリエンスブループリント](https://experienceleague.adobe.com/ja/docs/blueprints-learn/architecture/overview)は、戦略に取り組み、確立されたビジネス上の問題を解決するための反復可能な実装です。 各ブループリントは、価値の高いビジネス上の問題、アーキテクチャ、実装手順、技術的な考慮事項、および関連ドキュメントへのリンクを説明する一連のアーティファクトを提供します。

<!-- ## ![Icon](/assets/certification-badge.png) Certification{#certification}

Attention all Adobe certification candidates! Visit the Experience Cloud [Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) site on Experience League. 

+++Details

The [Experience Cloud Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) site is your one-stop shop for all [!DNL Experience Cloud] certification-related content and is updated regularly with:

* Available certifications
* Certification renewals for Adobe applications
* Certification program updates

And more! Head over to [Adobe Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) on Experience League and start your certification journey today!

+++ -->

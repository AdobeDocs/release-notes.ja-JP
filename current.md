---
title: 最新のリリースノート
description: ' [!DNL Experience Cloud]  製品およびサービスに関する最新のリリースノート、新機能、新規ドキュメントについて説明します。 [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise]、 [!DNL Document Cloud] に関する新しいヘルプとチュートリアルを検索します。'
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 32c6aff94fda6fa1a7d916b440aea7d656eafa44
workflow-type: tm+mt
source-wordcount: '5575'
ht-degree: 94%

---

# Adobe Experience Cloud リリースノート - 2022年7月

![バナー](assets/experience-cloud-banner-3.png)

Experience Maker として成功するための道のりは、[Experience League](https://experienceleague.adobe.com/?lang=ja#home) から始まります。膨大なハウツードキュメントのライブラリ、セルフガイドのチュートリアル、ハウツービデオ、あらゆるレベルや役割に対応したコース、仲間とのオンラインコミュニティ、必要な時には専門家によるサポートを利用できます。

>[!NOTE]
>
>このページの更新に関するメール通知を毎月受け取るには、[Adobe Priority 製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)を購読してください。Experience League の最新情報を把握できるよう、頻繁にチェックしてください。

最終更新：**2022年7月19日（PT）**

* [[!DNL Experience League] イベント](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - 主要なインターフェイスコンポーネントと管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [デジタルエクスペリエンスブループリント - チュートリアル](#blueprints)

サポートが必要な場合[Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスして、製品および技術ドキュメント、アドビがキュレートしたコース、ビデオチュートリアル、クイックアンサー、コミュニティインサイト、インストラクター主導のトレーニングをご覧ください。

## ![アイコン](/assets/experience-league.png) [!DNL Experience League] イベント {#events}

Experience League イベントでは、アドビの製品エキスパートから学び、やり取りし、回答を得ることができます。2022年7月の最新情報について詳しくは、Experience League の[イベント](https://experienceleague.adobe.com/events/?lang=ja)を参照してください。

更新日：**2022年7月17日（PT）**

| イベント | タイプ | 説明 |
| -----------|---------- | ----|
| [エキスパートに質問する：データストリームとデータ準備](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=ja) | Experience League LIVE | Adobe Experience Cloud のデータ収集に関する 3 回のセッションのうちのこの最後のセッションでは、アドビのエキスパートが、データ収集のためのデータ準備などの機能を含む、アドビの高度なデータ収集機能を掘り下げます。このセッションの最後に、参加者はデジタルエクスペリエンスからデータを収集するための最新で最も強力な機能に自信を持つようになります&#x200B;<br>**日付：** 7 月 21 日@午前 9 時 (PDT) - [詳細](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

今後のイベントと過去のエピソードについて詳しくは、Experience League の[イベント](https://experienceleague.adobe.com/events/?lang=en)を参照してください。

## ![アイコン](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] は、アドビ製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/ja) でご確認ください。

最新のリリース情報については、Adobe System Status の[リリースノート](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=ja#status)を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud - 主要なインターフェイスコンポーネントと管理 {#ecloud}

Experience Cloud の[主要な UI コンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)には、ホームページで使用できる機能と、永続的な製品ヘッダーが含まれます。これらの機能には、ユーザープロファイル設定、環境設定、検索などが含まれます。また、ユーザーと製品の管理、顧客属性、Experience Cloud Audiences に関するヘルプも参照できます。

### プロビジョニングの更新

>[!IMPORTANT]
>
>Experience Cloudのプロビジョニングに関する次の通知を確認してください。

Adobeは、一部のExperience Cloud製品間の相互運用性を支援する基本的な機能に対するすべてのExperience Cloudのお客様のアクセスを提供するために、プロビジョニングを更新しています。 ユーザーには、Adobe Experience PlatformをExperience Cloud組織に新しい権限として追加し、 [!UICONTROL データ収集] を付属のサービスとして使用します。

Adobe Experience Platform [!UICONTROL データ収集] 次を含む [タグ](https://experienceleague.adobe.com/docs/tags.html?lang=en) を使用すると、シンプルな universal tag management を実現し、信頼性の高い、堅牢で完全なストリーミングデータインフラストラクチャを提供します。 タグを使用すると、顧客体験のデータ収集を簡略化し、エクスペリエンス配信を効率化できます。

**Admin Consoleの変更**

管理者は、次のように、Admin Consoleの変更や追加を確認できます。

* Admin ConsoleのAdobe Experience Platform製品カードには、次が含まれます。

   * Places
   * アシュランス
   * ID 名前空間
   * サンドボックス
   * エクスペリエンスデータモデル
   * スキーマ
   * データストリーム
   * 訪問者 ID

   現在Experience Platformを使用していない組織の場合、 _Adobe Experience Platform_ 上記の機能を含む、Admin Console内の製品。

   現在Experience Platformを使用している組織の場合、 _場所_ は、Experience Platformカードに統合されます。

* Adobe Experience Platformのデータ収集（以前の Launch）およびプライバシーは、他のExperience Platform機能とは別の製品カードとして引き続き表示されます。

新機能の詳細については、各機能のExperience Leagueを参照してください。

* [データ収集](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html)
* [Places](https://experienceleague.adobe.com/docs/places/using/home.html?lang=ja)
* [アシュランス](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html)
* [ID 名前空間](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html?lang=ja)
* [サンドボックス](https://experienceleague.adobe.com/docs/experience-platform/sandbox/home.html?lang=ja)
* [エクスペリエンスデータモデル](https://experienceleague.adobe.com/docs/experience-platform/xdm/home.html?lang=ja)
* [スキーマ](https://experienceleague.adobe.com/docs/experience-platform/xdm/schema/composition.html?lang=ja)
* [データストリーム](https://experienceleague.adobe.com/docs/experience-platform/edge/datastreams/overview.html?lang=en)
* [訪問者 ID](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services.html?lang=en#section_3C9F6DF37C654D939625BB4D485E4354)
* [プライバシー](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html?lang=ja)

### 機能の更新

リリースされた機能： **2022 年 7 月 12 日**

| 機能 | 説明 |
| ------- | ------- |
| 統合ホーム - クイックアクセスウィジェット | **より速く移動：**&#x200B;ホームエクスペリエンスをさらにパーソナライズし、よく使用するアプリケーションを指定できるようになりました。新しいピン留め機能を使用して、[!UICONTROL クイックアクセス]の前面と中央に表示するアプリケーションを選択します。<br>**スマートピン留めで最新情報を入手：**&#x200B;新しいアプリケーションを見つけやすくなりました。新しく割り当てられたアプリケーションには&#x200B;_新規_&#x200B;バッジと[!UICONTROL クイックアクセス]への自動ピン留めが表示されます。 |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components] と管理に関するその他のヘルプリソース**

* Experience Cloud 中央 UI コンポーネントの[リースノート](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=ja) 
* Experience Cloud（管理）の[ユーザーおよび製品の管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)
* Places Service [リリースノート](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ja)
* [ユーザー向けの製品ドキュメント - 顧客属性とオーディエンスライブラリ](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ja)
* [オブジェクトとエンティティの統合検索](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] と [!UICONTROL Mobile SDK] の最新リリース情報および新規ドキュメント：

リリース予定日：**2022年7月27日（PT）**

* [Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja)

### 新しい [!DNL Experience Platform] のチュートリアルとコース {#tutorials-platform}

[!DNL Experience Platform] 用に公開された新しいビデオチュートリアル、記事およびコース。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年7月 | [イベント転送の監視](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html?lang=ja) | ビデオ | データ収集インターフェイスでイベント転送を監視する方法を説明します。 | データ収集 |
| 2022年7月 | [データ取り込みの監視](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html?lang=ja) | ビデオ | 監視ダッシュボードを使用して、Adobe Experience Platform に取り込まれたデータを監視および追跡する方法について説明します。 | データ収集 |
| 2022年7月 | [Adobe Experience Platform へのサンプルデータのインポート](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html?lang=ja) | 記事 | サンプルデータを使用して Experience Platform サンドボックス環境をセットアップする方法を説明します。Postman Collection を使用すると、フィールドグループ、スキーマ、データセットを作成して、Experience Platform にサンプルデータをインポートできます。 | Experience Platform |
| 2022年7月 | [受信データのセグメント一致](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html?lang=ja) | ビデオ | セグメント一致を使用すると、戦略的パートナーからあなたにデータを共有できます。このビデオでは、データの承認および受信方法、そのデータの確認場所、独自のセグメントへの追加方法について説明します。 | Experience Platform - セグメント |
| 2022年7月 | [エキスパートに質問する：Real-Time CDP 接続](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=ja) | Experience League LIVE ビデオ | データ収集に関する 3 つのセッションのうちのこの 2 番目のライブストリーミングセッションでは、お気に入りのエキスパートが、サーバーサイドタグ管理システムを使用してアドビ以外の宛先にイベントを転送できる、Adobe RTCDP [!UICONTROL 接続]を詳細に紹介します。 | データ収集 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Adobe Experience Platform Mobile SDK の[リリースノートと変更ログ](https://aep-sdks.gitbook.io/docs/release-notes)を参照してください。

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

次期リリース：**2022年7月20日（PT）**

最終更新日：**2022年7月13日（PT）**

* Adobe Analytics [リリースノート](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=ja)
* Adobe Analytics [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

### AppMeasurement {#appm}

リリースバージョン：**2.22.4**

* [JavaScript 版 AppMeasurement リリースノート](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja)

### 新しい [!DNL Analytics] のチュートリアルとコース {#tutorials-analytics}

Adobe Analytics 用に公開された新しいビデオチュートリアル、記事およびコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [2022年フローの改善](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html?lang=ja) | ビデオ | [!UICONTROL フロー]ビジュアライゼーションに対する優れた強化点について説明します。改善点には、目的のパスの開始や終了を設定できる、列をフィルタリングして特定の項目を含めたり除外する、事前に設定可能な詳細設定などが含まれます。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

最終更新：**2022年7月12日（PT）**

* Customer Journey Analytics [リリースノート](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=ja)
* Customer Journey Analytics [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=ja)

### 新しい Customer Journey Analytics チュートリアルとコース {#tutorials-cja}

CJA 用に公開された新しいビデオ、チュートリアル、またはコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [次または前の項目パネルの設定](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html?lang=ja) | ビデオ | [!DNL Customer Journey Analytics] で次または前の項目パネルを設定する方法について説明します。このパネルでは、特定のディメンション値の次または前の項目を識別するテーブルおよびビジュアライゼーションを生成します。 |
| 2022年7月 | [注釈の作成](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=ja) | ビデオ | キャンペーンの開始、データの問題、休日などのイベントが発生した場合に、[!DNL Customer Journey Analytics] プロジェクトで注釈を作成する方法を説明します。この機能は、これらの日付または日付範囲における指標の相違をユーザーに通知します。 |
| 2022年7月 | [クイックフィルターの作成](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html?lang=ja) | ビデオ | [!DNL Customer Journey Analytics] プロジェクトで直接クイックフィルターを作成し、完全なフィルタービルダーの複雑さを回避します。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

最終更新日：**2022年3月23日（PT）**

* [!DNL Streaming Media Analytics] [リリースノート](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=ja)
* [!DNL Streaming Media Analytics] [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の修正点と改善点：

| 改善点 | 説明 |
| -----------| ---------- |  
| 他の会社に属するターゲットデータソースのバリデーター | Audience Manager は、[バッチデータのオンボーディングプロセス](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=ja)の改善をリリースしました。他のパートナーが所有するターゲットデータソースに、誤ってファイルやデータをオンボーディングしてしまうのを防ぐために、Audience Manager では、他のパートナーが所有するパートナー ID（PID）とデータソース（DPID）の間にマッピング要件を追加しました。 <ul><li>[Amazon S3 の受信データファイル用の名前およびファイルサイズに関する要件](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=ja#name-elements)の __DPID_TARGET_DATA_OWNER_ フィールドも参照してください。</li><li>アドビ社内のコンサルタントとカスタマーケアは、改善が必要な新しいマッピングと新しいマッピングをリクエストする方法について、[セカンドパーティデータのオンボーディングアクセスの管理](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=ja)を参照する必要があります。</li><li>既存のデータ共有関係のマッピングをリクエストする必要はあり&#x200B;_ません_。PID に属するターゲットデータソースにデータをオンボーディングする場合も、マッピングは必要あり&#x200B;_ません_。</li></ul> |

{style=&quot;table-layout:auto&quot;}

セルフヘルプリソースについては、Experience League の [Audience Manager ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/audience-manager.html?lang=ja)を参照してください。

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

 Experience Manager の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

[Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することをお勧めします。

### 製品アップデートビデオ

* 2022.6 リリースの概要に関する [2022年6月リリースの概要ビデオ](https://video.tv.adobe.com/v/344308/?quality=12)。

以前の製品アップデートビデオ：

* 2022.5.0（2022年5月）リリースで追加された機能の概要に関する [2022年5月リリースの概要ビデオ](https://video.tv.adobe.com/v/343321/?quality=12)。
* [2022年4月リリースの概要ビデオ](https://video.tv.adobe.com/v/342612?quality=12)
* [2022 年 3 月リリースの概要ビデオ](https://video.tv.adobe.com/v/341465)
* [2022 年 1 月リリースの概要ビデオ](https://video.tv.adobe.com/v/340120)
* [2021 年 12 月リリースの概要ビデオ](https://video.tv.adobe.com/v/339278)
* [2021 年 10 月リリースの概要ビデオ](https://video.tv.adobe.com/v/338253)
* [2021 年 9 月リリースの概要ビデオ](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] as a [!DNL Cloud Service]

[!DNL Sites] の新機能：

* コンテンツ管理者とコンテンツ作成者が、ヘッドレスのユースケースでのコンテンツフラグメントの管理（公開、非公開、コピー、移動などのアクション）、検索／フィルタリング、作成を効率的に行うための[新しいユーザーインターフェイス](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=ja)が使用できるようになりました。

* 新しい[目次コンポーネント](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=ja)は、[!UICONTROL コアコンポーネント]だけでなく、すべてのコンポーネントで機能し、コンテンツページの目次を自動的にレンダリングします。さらに、サーバーサイドでレンダリングされ、Dispatcher で完全にキャッシュされるので、読み込みも効率的です。

### Experience Manager [!DNL Assets] as a [!DNL Cloud Service]

[!DNL Assets] の新機能：

* Experience Manager [!DNL Assets] は Adobe Sensei AI 機能を使用し、[画像内の色を区別して、取り込み時にそれらをタグとして自動的に適用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=ja)できるようになりました。このタグを使用すると、画像の色構成に基づいて、検索エクスペリエンスを強化できます。画像にタグ付けされる色の数を 1 ～ 40 の範囲で設定し、後でそれらの色に基づいて画像を検索できます。

### Experience Manager Forms as a Cloud Service

[!DNL Forms] の新機能：

* [[!UICONTROL アダプティブフォーム]と Microsoft® Power Automate の統合](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=ja)：送信時に Microsoft® Power Automate Cloud Flow を実行するようにアダプティブフォームを設定できるようになりました。設定済みのアダプティブフォームは、キャプチャされたデータ、添付ファイルおよびレコードのドキュメントを Power Automate Cloud Flow に送信して処理します。Microsoft® Power Automate の機能を活用しながら、カスタムのデータキャプチャエクスペリエンスを構築し、取り込んだデータに関するビジネスロジックを構築し、顧客ワークフローを自動化できます。

**アダプティブフォームを作成するためのウィザード**：ビジネスユーザーにとってわかりやすいウィザードを使用して、[!UICONTROL アダプティブフォーム]をすばやくオーサリングできます。このウィザードでは、事前設定済みのテンプレート、スタイル設定、フィールド、送信オプションを簡単に選択して、アダプティブフォームを作成するためのクイックタブナビゲーションを提供します。

### Adobe Experience Manager as a Cloud Service の基盤

新機能：

5月（2022.5.0）のリリースノートに記載されているように、レプリケーションエージェント管理者画面の「配布」タブにあった「ツリーを追加」オプションは削除されました。代わりに、コンテンツのツリー階層を持つパッケージは、「公開を管理」またはコンテンツツリーを公開ワークフローを使用してレプリケートされる必要があります。

### [!DNL Cloud Manager]

新機能：

* [!DNL Cloud Manager] ユーザーは、ランディングページの[!UICONTROL ようこそ]カードからいつでも、便利なビデオチュートリアルにアクセスできるようになりました。

* 環境の詳細ページの「[コンテンツを復元](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=ja)」タブ上にマウスポインターを置くと、ユーザーがローカルで変更を表示できる、git コマンドの便利なリストが表示されるようになりました。

### 新しい Adobe Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年7月 | [エンタープライズワークフロー管理を最大限に活用](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=ja) | ビデオ | アセット管理にワークフローを使用する利点とワークフローをすばやく作成する方法を説明します。 | AEM - エクスペリエンスワークフロー管理 |
| 2022年7月 | [Adobe Experience Manager でヘッドレスエクスペリエンスを提供](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=ja) | ビデオ | 機能強化された最新の Experience Manager [!UICONTROL コンテンツフラグメント]およびヘッドレスコンテンツ配信のための新しい GraphQL API を使用したヘッドレスエクスペリエンス管理について説明します。 | Experience Manager [!DNL Sites] |
| 2022年7月 | [Adobe Experience Manager Assets でのメタデータのビジネスへの対応](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=ja) | ビデオ | タグアセットに対する負荷を軽減し、アセットをさらに検索可能にして、AEM Assets でメタデータを活用する方法を説明します。 | Experience Manager [!DNL Assets] |
| 2022年7月 | [iOS アプリ](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html?lang=ja) | ビデオ | サンプルアプリケーションは、Adobe Experience Manager のヘッドレス機能を調査するための優れた手段です。この iOS アプリケーションは、永続クエリを使用する AEM の [!UICONTROL GraphQL API] を使用してコンテンツをクエリする方法を実演します。 | Adobe Experience Manager [!DNL Assets]、[!DNL Sites] |
| 2022年7月 | [Android™ アプリ](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html?lang=ja) | ビデオ | この Android™ アプリケーションは、AEM の [!UICONTROL GraphQL API] を使用してコンテンツをクエリする方法を実演します。 | Adobe Experience Manager [!DNL Assets]、[!DNL Sites] |
| 2022年7月 | [Adobe Experience Manager as a Cloud Service の OSGi の設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=ja) | ビデオ | AEM CS 用に OSGI を設定する方法を説明します。例えば、OSGi バンドルの管理および AEM コードプロジェクトの一部である設定ファイルを使用した OSGi コンポーネントの設定の管理について説明します。 | AEM as a Cloud Service |
| 2022年7月 | [フォームデータモデルプロパティの上書き](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=ja) | ビデオ | フォームデータモデルプロパティを上書きして、様々なエンドポイントに対する 1 つのフォームデータモデルのテストを簡単にする方法を説明します。 | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;}

### Adobe Experience Manager リリース情報

Experience Manager のリリースノートはすべて以下のページに記載されています。

* [Adobe Experience Manager as a Cloud Service リリース情報](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=ja)
* [Adobe Experience Manager Cloud Manager リリースノート](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=ja)
* [自動フォーム変換サービスリリースノート](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=ja)
* [Adobe Experience Manager 6.5 Service Pack リリースノート](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=ja)
* [Adobe Experience Manager 6.4 累積修正パックリリースノート](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ja)
* [Adobe Experience Manager Assets Dynamic Media リリースノート](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=ja)
* [Adobe Experience Manager Brand Portal リリースノート](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ja)
* [Adobe Experience Manager デスクトップアプリケーションリリースノート](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=ja)
* [Adobe Experience Manager Dispatcher リリースノート](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=ja)
* [Adobe Primetime リリースノート](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=ja)
* [Livefyre リリースノート](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=ja)

### Experience Manager に関するその他のヘルプリソース

* [Adobe Experience Manager as a Cloud Service に関するガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=ja)
* [Cloud Manager ユーザガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=ja)
* [Adobe Experience Manager 6.5 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ja)
* [Adobe Experience Manager 6.4 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ja)
* [Adobe Experience Manager 6.3 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja)
* [Adobe Experience Manager 6.2 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja#previous-updates)
* [Adobe Experience Manager ドキュメントの以前のバージョン](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic ヘルプホーム](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ja)
* [Adobe Experience Manager ドキュメント：最近の更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ja#aem-as-a-cloud-service)

## ![アイコン](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] は、AEM にデプロイされたアプリケーションです。Adobe Experience Manager でのネイティブ DITA サポートを可能にし、AEM が DITA ベースのコンテンツの作成と配信を処理できる、強力なエンタープライズグレードのコンポーネントコンテンツ管理ソリューション（CCMS）です。

詳しくは、[[!DNL Experience Manager Guides]](https://www.adobe.com/jp/products/xml-documentation-for-experience-manager/features.html)を参照してください。

### その他のリソース

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=ja) - Experience League のチュートリアル
* [[!DNL Experience Manager Guides] ラーニングとサポート](https://helpx.adobe.com/jp/support/xml-documentation-for-experience-manager.html) - 製品ドキュメント

## ![アイコン](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Adobe Commerce リリースノートについては、以下のリンクを参照してください。

* [Adobe Commerce および Magento Open Source 2.4.x リリースノート](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite のリリースノート](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新しい Adobe Commerce のチュートリアルとドキュメント {#tutorials-commerce}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [Adobe Commerce 入門ガイド](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html?lang=ja) | 製品ドキュメント | Adobe Commerce および Magento Open Source の新しい商社およびシステム管理者を対象としたガイド。彼らの視点から見たプラットフォームの概要や、機能的なストアを実現するための基本機能についての詳細情報を説明します。 |
| 2022年7月 | [ページビルダーユーザーガイド](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html?lang=ja) | 製品ドキュメント | ページビルダー機能について説明し、基本的なコンテンツコンポーネントの作成を 3 つのステップで確認します。このガイドは、管理者向けです。ここでは、Adobe Commerce のコア設定と機能に関する基本的な知識を前提としています。 |
| 2022年7月 | [Adobe Commerce の B2B ガイド](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html?lang=ja) | 管理ガイド | 機能の設定および管理を含む、このモジュールのインストールおよび有効化に関する詳細情報を提供します。 |
| 2022年7月 | [Adobe Commerce の B2B - チュートリアル](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=ja) | ビデオ（複数） | Adobe Commerce の[!UICONTROL 会社]ページについて説明します。会社アカウントを管理でき、承認待ちのリクエストがリストの上部に表示されます。 |
| 2022年7月 | [Quality Patch Tool の使用](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html?lang=ja) | ビデオ | Adobe Commerce および Magento Open Source のクオリティパッチを実現するコマンドラインツール、[!UICONTROL Quality Patch Tool] について説明します。 |
| 2022年7月 | [Site-Wide Analysis Tool ダッシュボード](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html?lang=ja) | ビデオ | Site-Wide Analysis Tool について説明します。この機能は、プロアクティブなセルフサービスのツールで、Adobe Commerce インストールのセキュリティと操作性を保証するための詳細なシステムインサイトおよびレコメンデーションが含まれている中央リポジトリです。 |
| 2022年7月 | [支払いサービスの使用](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html?lang=ja) | ビデオ | 運用にかかる諸経費を削減し、売上高を増加するための[!UICONTROL 支払いサービス]の使用方法を説明します。 |
| 2022年7月 | [注文ステータスの管理](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html?lang=ja) | ビデオ | 注文ステータスおよびその詳細を確認する方法と、必要に応じて注文のステータスを変更する方法を説明します。 |
| 2022年7月 | [マーケティングツール](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=ja) | ビデオ（複数） | カタログ価格ルール、買い物かご価格ルール、管理関連の製品ルール、ライブ検索などの作成について説明します。 |
| 2022年7月 | [ビジネス価値をもたらすコンテンツパーソナライゼーションのイノベーション](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=ja) | ビデオ | スキルビルダーのプレゼンテーションを表示して、コンテンツオーサリングの民主化、オムニチャネル配信の円滑化、パーソナライゼーションの拡張に役立つアドビのコンテンツソリューションの最新のイノベーションについて確認してください。 |
| 2022年7月 | [カタログ管理](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html?lang=ja) | ビデオ | Adobe Commerce のカタログ管理について説明します。カテゴリを作成したり、カテゴリで製品を管理したり、在庫を管理したりします。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/target.png) [!DNL Adobe Target] {#target}

最終更新日：**2022年6月30日（PT）**

* プレリリース情報については、[Adobe Target プレリリース](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ja)を参照
* 現在の情報については、[Adobe Target リリースノート](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=ja)を参照

### 新しい Adobe Target コースとチュートリアル {#tutorials-target}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [オーディエンスの作成](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html?lang=ja) | ビデオ | アクティビティで使用するための、[!DNL Target] でのカスタムオーディエンスの作成および保存を説明します。 |
| 2022年7月 | [Adobe Target を使用したパーソナライズと自動化](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=ja) | ビデオ | [!UICONTROL 自動ターゲット]と[!UICONTROL 自動パーソナライゼーション]を使用した Adobe Target 機能の自動化および最適化の中心概念について説明します。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 最新の Campaign 製品リリース

* [Campaign v7.3 リリース](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ja)
* [コントロールパネル 6月リリース](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=ja)
* Experience League の[チュートリアルとコース](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=ja#tutorials-campaign)

### 新しい [!DNL Campaign] のチュートリアルとコース {#tutorials-campaign}

新しく公開された Adobe Campaign ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年7月 | [ハイブリッドホスティングモデルのコントロールパネル](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html?lang=ja) | ビデオ | Adobe Campaign ハイブリッドホスティングモデルのコントロールパネルを有効にする方法、コントロールパネルにアクセスする方法および主な機能のロックを解除する方法を説明します。 | コントロールパネル |
| 2022年7月 | [スループットと待ち時間の監視](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=ja) | ビデオ | Campaign インスタンスの配信スループットとトランザクションメッセージの待ち時間を監視する方法について説明します。 | コントロールパネル |
| 2022年7月 | [リソース使用状況の最適化のための監視ワークフロー](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=ja) | ビデオ | ワークフローの一時的なストレージ使用状況を監視する方法、およびインスタンスでのデータベースやワークフローの問題を回避するためのワークフロー設定の場所について説明します。 | コントロールパネル |
| 2022年7月 | [Adobe Campaign Classic でのデータモデルの開発とカスタマイズ](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=ja) | ビデオ（スキルビルダーイベント） | Campaign トレーナーと共にこのセッションに参加して、Campaign Classic を使用したデータモデル内のデータスキーマの開発方法を学習してください。 | Campaign Classic v7 |
| 2022年7月 | [配信品質のベストプラクティスと成果を導く戦略](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html?lang=ja) | ビデオ | メールキャンペーンの企画や製作にかかる膨大な時間を最小化する方法を説明します。 | Campaign Classicv7 |
| 2022年7月 | [Adobe Campaign Classic を使用したクロスチャネルマーケティングのレベルアップ](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=ja) | ビデオ | Adobe Campaign Classic のお客様向けのワークフロー、自動化、パーソナライゼーションおよび測定に焦点を当てたこの詳細なウェビナーをご覧ください。 | Campaign Classicv7 |
| 2022年7月 | [時間節約のためのプロからのヒント](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=ja) | ビデオ | 新しい年度の始まりは、Adobe Campaign プロからのヒントやテクニックと共に。キャンペーンの作成と開始をより効率的に行い、より有意義でカスタマイズされたクロスチャネルエクスペリエンスを提供する方法を説明します。 | Campaign Classicv7 |
| 2022年7月 | [マーケティングエコシステムによる Adobe Campaign 統合](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=ja) | ビデオ | マーケティングエコシステムによる Adobe Campaign 統合について説明します。Adobe Campaign などのクロスチャネルマーケティングソリューションは、他のテクノロジーやチームと切り離して設定すべきではありません。異なるシステムによって、顧客の完全な理解が妨げられたり、クロスチャネル戦略が阻害されたりすることのないようにします。 | Campaign Classicv7 |
| 2022年7月 | [Adobe Campaign Standard カスタマースポットライト - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=ja) | ビデオ | Microsoft® のマーケティングチームによる Adobe Campaign Standard の使用方法、アーキテクチャと基本理念、ベストプラクティスを紹介します。 | Campaign Standard |
| 2022年7月 | [Adobe Campaign カスタマースポットライト - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=ja) | ビデオ | Adobe Campaign のお客様が、どのように課題を克服し、ニューノーマルに適応し、キャンペーン管理を効率化し、Adobe Campaign を通じて有意義な価値を生み出しているかを紹介します。 | Campaign Classicv7 |
| 2022年7月 | [Adobe Campaign Classic V7 と V8 の比較](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=ja) | ビデオ | 最新の製品アップデートや、V7 と V8 の違いについて、プロダクトマネージャーが説明します。 | Campaign Classic v7、Campaign v8 |
| 2022年7月 | [キーノート - B2B と B2C にわたるカスタマージャーニーのトレンドとイノベーション](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=ja) | ビデオ | B2B と B2C にわたる Customer Journey Management の最新のトレンドについて説明します。主要なジャーニーアプリケーションや広範な Adobe Experience Cloud および Platform の最新のイノベーションを確認します。 | Marketo、Campaign Classic v7、Campaign v8 |
| 2022年7月 | [Adobe Campaign Standard の効果的なヒントとテクニック](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=ja) | ビデオ | Adobe Campaign Standard インスタンに接続し、ターゲティング、パーソナライゼーション、マーケティング疲労に関するベストプラクティスを見つけて、ACS をより良く活用します。 | Campaign Standard |
| 2022年7月 | [クロスチャネルマーケティングをサポートするための必要なチーム、スキル、組織設計](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html?lang=ja) | ビデオ | いつでも、どこでも、好きなように活動できるようにする方法を説明します。計画、実行、測定をサポートするマーケティング組織の重要性を説明します。 | Campaign Classic v7、Campaign v8、Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Campaign ヘルプリソース

* Adobe Campaign v8：[ドキュメント](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=ja) - [実装ガイド](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ja)
* Adobe Campaign Standard：[Campaign Standard ドキュメント](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ja) - [リリース計画](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ja)
* Adobe Campaign Classic：[Campaign Classic v7 ドキュメント](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ja) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ja)
* Adobe Campaign コントロールパネル：[ドキュメント](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ja)／[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ja) のハウツービデオ

## ![アイコン](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Journey Optimizer では、スケジュールされたオムニチャネルキャンペーンや数百万人の顧客の 1 対 1 の瞬間を、1 つのアプリケーションで管理できます。また、インテリジェントな意思決定とインサイトにより、ジャーニー全体を最適化します。

### 最新の Journey Optimizer 製品リリース

最新の機能、改善点および修正点について詳しくは、[Journey Optimizer リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ja)を参照してください。

### 新しい Journey Optimizer のチュートリアルとコース {#tutorials-ajo}

新しく公開された Adobe Journey Optimizer ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [メッセージ頻度ルールの設定](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html?lang=ja) | ビデオ | 頻度ルールを作成、アクティブ化、テストおよびレポートする方法について説明します。メッセージに継承する頻度ルールを決定する方法について説明します。 |
| 2022年7月 | [SMS メッセージの設定、作成および配信](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html?lang=ja) | ビデオ | SMS メッセージを設定、作成およびカスタマージャーニーに含める方法について説明します。 |
| 2022年7月 | [SMS の受信キーワードのサポート](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html?lang=ja) | ビデオ | SMS のネイティブ受信キーワードサポート（開始、停止、停止解除）の仕組みについて説明します。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] のその他のリソース

* [Journey Optimizer ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ja) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ja)
* [意思決定管理ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=ja) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

### 最新の [!DNL Journey Orchestration] 製品リリース

最新の機能、改善点、修正点について詳しくは、[[!DNL Journey Orchestration] リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ja)を参照してください。

#### [!DNL Journey Orchestration] のその他のリソース

* [Journey Orchestration ドキュメント](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ja) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ja)

## ![アイコン](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーのすべてのステージにわたるエンゲージメントを通じてカスタマーエクスペリエンスを変革しようとしている経営陣や B2B マーケター向けの完全なアプリケーションです。

### コア Marketo Engage の更新

最新のリリーススケジュール情報とリリースノートについては、[!DNL Marketo Engage] [リリーススケジュール](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ja)を参照してください。

### 新しい Marketo チュートリアルとコース {#tutorials-marketo}

新しく公開された Adobe Marketo ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [Marketo Engage と Adobe Experience Cloud による B2B エクスペリエンス](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=ja) | ビデオ | Marketo Engage と Adobe Experience Cloud アプリケーションの統合と、解決される問題点を紹介します。 | Marketo Engage |
| 2022年7月 | [連携して機能強化 - Adobe Marketo Engage と Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=ja) | ビデオ | Marketo Engage と RT-CDP（B2B エディション）を使用して B2B キャンペーンを調整する方法と、そのユースケースおよび利点について説明します。 | Marketo、Real-time Customer Data Platform |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] は、アイデアの共有、コンテンツの作成、複雑なプロセスの管理、および最高の作業を行うための統合作業管理アプリケーションです。

すべての製品の最新情報のまとめについては、[[!DNL Workfront] リリース](https://one.workfront.com/s/product-releases) ページを参照してください。

## ![アイコン](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

リリースノート：[!DNL Adobe Advertising Cloud]

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [ [!DNL Advertising Cloud DSP] の新機能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] の新機能](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

### [!DNL Advertising Cloud DSP] の新機能 {#adcloud-dsp}

最終更新日：**2022年7月14日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| カスタムレポート | （5月31日（PT）リリース、ベータ版機能）Advertising Cloud DSP は、顧客データプラットフォーム（CDP）内で作成された認証済みシグナルで構成される、ファーストパーティセグメントを取り込めるようになりました。 |
| [!UICONTROL 在庫] | （6月29日（PT）リリース）新しい[!UICONTROL 在庫]／[!UICONTROL 取引]表示には、[!UICONTROL キャンペーン]表示と同じデータカスタマイズ機能が含まれています（追加のフィルター、列のカスタマイズおよびカスタム表示、列の並び替え、データビジュアライゼーション（グラフ）表示を保存するオプションなど）。取引名の後の省略記号（…）をクリックすることで、各行でコマンドメニューを開くことができます。 |
| [!UICONTROL 在庫インスペクター] | （6月29日（PT）リリース）プレースメント[!UICONTROL インスペクター]の「[!UICONTROL 在庫]」タブには、[!UICONTROL ビューアビリティ率]、[!UICONTROL クリック数]、[!UICONTROL 昨日の CPM]など、カスタマイズ可能なデータビジュアライゼーショングラフおよび拡張されたパフォーマンス指標が含まれています。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] の新機能 {#adcloud-search}

最終更新日：**2022年7月14日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| [!UICONTROL インサイト] | （6月11日（PT）リリース）インプレッション共有の損失分析を、ベータ版機能として再び使用できるようになりました。 |
| [!DNL Advanced Campaign Management] | （6月20日（PT））（[!DNL Google Ads] および [!DNL Microsoft Advertising] キャンペーン）[!UICONTROL キャンペーン]／[!UICONTROL 詳細設定（ACM）]から、在庫のコンテンツに基づいて、検索エンジン特有の広告テンプレートを使用した動的なレスポンシブ検索広告のバリエーションを作成できるようになりました。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Adobe Document Cloud 向けに新しく公開されたチュートリアルとコース。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年7月 | [承認者の役割の使用](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=ja) | ビデオ（更新） | 承認プロセスを通じてドキュメントを送信する方法を説明します。 | Adobe Sign |
| 2022年7月 | [Web フォームの設定](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html?lang=ja) | ビデオ（更新） | Web サイトで直接電子的に署名できれるドキュメントを作成する方法を説明します。 | Adobe Sign |
| 2022年7月 | [委任者の役割の使用](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=ja) | ビデオ（更新） | 説明 | Adobe Sign |
| 2022年7月 | [ドキュメントへの電子的な署名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=ja) | ビデオ（更新） | Acrobat Sign を使用すれば、送信されてきたドキュメントに署名するのがいかに簡単かを説明します。 | Adobe Sign |
| 2022年7月 | [Acrobat Sign 管理者向けのセットアップと運用](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=ja) | ビデオ（更新） | Acrobat Sign をすばやくセットアップして運用するために、管理者が注力すべき 7 つのポイントについて説明します。 | Adobe Sign |
| 2022年7月 | [Outlook での署名用に送信](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=ja#) | ビデオ（更新） | Microsoft® Outlook 内で直接ドキュメントを署名用に送信することで、ドキュメントワークフローを合理化する方法を説明します。 | Adobe Sign |
| 2022年7月 | [Outlook での入力と署名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=ja) | ビデオ（更新） | Microsoft Outlook 内で直接入力して署名することで、ドキュメントワークフローを合理化する方法を説明します。 | Adobe Sign |
| 2022年7月 | [グループの作成と管理](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=ja) | ビデオ（更新） | グループを作成したり、グループにユーザーを追加したり、グループ設定を編集したりする方法を説明します。 | Adobe Sign |
| 2022年7月 | [他のユーザーへの署名の委任](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=ja) | ビデオ（更新） | ドキュメントの署名を他のユーザーに委任する方法を説明します。 | Adobe Sign |

{style=&quot;table-layout:auto&quot;}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud 学習とサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Adobe Creative Cloud エンタープライズ版 {#creative-cloud}

最新のチュートリアルについては、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ja) を参照してください。

## ![アイコン](/assets/experience-league.png) Customer Data Management - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=ja) は、顧客データ管理の技術およびマーケティングプラクティスのリーダーやスペシャリストのためのページです。このチュートリアルのコレクションには、同僚から話を聞き、インスピレーションを得て、MarTech の開発について学ぶためのリソースが一箇所に集められています。登録は不要です。クリックで視聴できます。

## ![アイコン](/assets/experience-league.png) デジタルエクスペリエンスブループリント {#blueprints}

[デジタルエクスペリエンスブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=ja)は、戦略に取り組み、確立されたビジネス上の問題を解決するための反復可能な実装です。各ブループリントは、価値の高いビジネス上の問題、アーキテクチャ、実装手順、技術的な考慮事項、および関連ドキュメントへのリンクを説明する一連の成果物を提供します。

[トップ](#events)

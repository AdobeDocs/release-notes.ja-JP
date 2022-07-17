---
title: 最新のリリースノート
description: ' [!DNL Experience Cloud]  製品およびサービスに関する最新のリリースノート、新機能、新規ドキュメントについて説明します。 [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise]、 [!DNL Document Cloud] に関する新しいヘルプとチュートリアルを検索します。'
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 609676006717d61512be133a65bfac44a15c8651
workflow-type: tm+mt
source-wordcount: '5262'
ht-degree: 51%

---

# Adobe Experience Cloud リリースノート - 2022 年 7 月

![バナー](assets/experience-cloud-banner-3.png)

Experience Maker として成功するための道のりは、[Experience League](https://experienceleague.adobe.com/?lang=ja#home) から始まります。膨大なハウツードキュメントのライブラリ、セルフガイドのチュートリアル、ハウツービデオ、あらゆるレベルや役割に対応したコース、仲間とのオンラインコミュニティ、必要な時には専門家によるサポートを利用できます。

>[!NOTE]
>
>このページの更新に関するメール通知を毎月受け取るには、[Adobe Priority 製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)を購読してください。Experience League の最新情報を把握できるよう、頻繁にチェックしてください。

最終更新：**2022 年 7 月 15 日（PT）**

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

Experience League イベントでは、アドビの製品エキスパートから学び、やり取りし、回答を得ることができます。詳しくは、 [イベント](https://experienceleague.adobe.com/events/?lang=ja) Experience Leagueが 2022 年 7 月に更新されました。

更新済み **2022 年 7 月 18 日**

| イベント | タイプ | 説明 |
| -----------|---------- | ----|
| [エキスパートに質問する：データストリームとデータ準備](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) | Experience League LIVE | Adobe Experience Cloudのデータ収集に関する 3 つのセッションの最後に、アドビのエキスパートが、Adobeのデータ収集準備などの機能を含む、データの高度なデータ収集機能について詳しく説明します。 このセッションの最後に、参加者はデジタルエクスペリエンスからデータを収集するための最新で最も強力な機能に自信を持つようになります&#x200B;<br>**日付：** 7 月 21 日@午前 9 時 (PST) - [詳細](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

詳しくは、 [イベント](https://experienceleague.adobe.com/events/?lang=en) Experience Leagueで、今後のイベントや過去のエピソードの最新情報を常に確認できます。

## ![アイコン](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] は、Adobe製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/ja) でご確認ください。

最新のリリース情報については、Adobe System Status の[リリースノート](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=ja#status)を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud - 主要なインターフェイスコンポーネントと管理 {#ecloud}

Experience Cloud の[主要な UI コンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)には、ホームページで使用できる機能と、永続的な製品ヘッダーが含まれます。これらの機能には、ユーザープロファイル設定、環境設定、検索などが含まれます。また、ユーザーと製品の管理、顧客属性、Experience Cloud Audiences に関するヘルプも参照できます。

リリース： **2022 年 7 月 12 日**

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
| 2022年7月 | [イベント転送の監視](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html) | ビデオ | データ収集インターフェイスでイベント転送を監視する方法を説明します。 | データ収集 |
| 2022年7月 | [データ取得の監視](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html) | ビデオ | 監視ダッシュボードを使用して、Adobe Experience Platformに取り込まれるデータを監視および追跡する方法について説明します。 | データ収集 |
| 2022年7月 | [サンプルデータをAdobe Experience Platformに読み込む](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html?lang=ja) | 記事 | サンプルデータを使用したExperience Platformサンドボックス環境の設定方法について説明します。 Postmanコレクションを使用して、フィールドグループ、スキーマ、データセットを作成し、サンプルデータをExperience Platformに読み込むことができます。 | Experience Platform |
| 2022年7月 | [データを受け取るセグメントマッチ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html) | ビデオ | セグメントマッチを使用すると、戦略パートナーがデータを共有できます。 このビデオでは、データを承認して受け取る方法と、データを表示して独自のセグメントに追加できる場所について説明します。 | Experience Platform — セグメント |
| 2022年7月 | [エキスパートに質問する：Real-Time CDP Connections](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=en) | Experience Leagueライブビデオ | データ収集に関する 3 つのライブストリームセッションの第 2 回では、お気に入りのエキスパートがAdobeRTCDP を詳細にご覧いただけます [!UICONTROL 接続]のお客様は、サーバー側のタグ管理システムを使用して、Adobe以外の宛先にイベントを転送できます。 | データ収集 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Adobe Experience Platform Mobile SDK の[リリースノートと変更ログ](https://aep-sdks.gitbook.io/docs/release-notes)を参照してください。

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

次期リリース： **2022 年 7 月 21 日**

最終更新日： **2022 年 7 月 14 日**

* Adobe Analytics [リリースノート](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=ja)
* Adobe Analytics [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

### AppMeasurement {#appm}

リリースバージョン：**2.22.4**

* [JavaScript 版 AppMeasurement リリースノート](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja)

### 新しい [!DNL Analytics] のチュートリアルとコース {#tutorials-analytics}

Adobe Analytics 用に公開された新しいビデオチュートリアル、記事およびコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [2022年フローの改善](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html) | ビデオ | の優れた改善点の一部を説明します。 [!UICONTROL フロー] ビジュアライゼーション。 改善点には、目的のパスの開始や終了を設定できる、列をフィルターして特定の項目を含めたり除外する、事前に設定可能な詳細設定などが含まれます。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

最終更新：**2022 年 7 月 12 日（PT）**

* Customer Journey Analytics [リリースノート](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=ja)
* Customer Journey Analytics [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=ja)

### 新しい Customer Journey Analytics チュートリアルとコース {#tutorials-cja}

CJA 用に公開された新しいビデオ、チュートリアル、またはコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [次または前の項目パネルの設定](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html) | ビデオ | [!DNL Customer Journey Analytics] で次または前の項目パネルを設定する方法について説明します。このパネルでは、特定のディメンション値の次または前の項目を識別するテーブルおよびビジュアライゼーションを生成します。 |
| 2022年7月 | [注釈の作成](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=en) | ビデオ | 注釈を [!DNL Customer Journey Analytics] キャンペーンの起動、データの問題、休日などのイベントが発生した場合にプロジェクトを作成します。 この機能は、これらの日付または日付範囲における指標の相違をユーザーに通知します。 |
| 2022年7月 | [クイックフィルターの作成](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html) | ビデオ | [!DNL Customer Journey Analytics] プロジェクトで直接クイックフィルターを作成し、完全なフィルタービルダーの複雑さを回避します。 |

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

* [2022 年 6 月リリースの概要ビデオ](https://video.tv.adobe.com/v/344308/?quality=12) :2022.6 リリースの概要。

以前の製品アップデートビデオ：

* [2022 年 5 月リリースの概要ビデオ](https://video.tv.adobe.com/v/343321/?quality=12) 2022.5.0（2022 年 5 月）リリースに追加された機能の概要。
* [2022年4月リリースの概要ビデオ](https://video.tv.adobe.com/v/342612?quality=12)
* [2022年3月リリースの概要ビデオ](https://video.tv.adobe.com/v/341465)。
* [2022年1月リリースの概要ビデオ](https://video.tv.adobe.com/v/340120)。
* [2021年12月リリースの概要ビデオ](https://video.tv.adobe.com/v/339278)。
* [2021年10月リリースの概要ビデオ](https://video.tv.adobe.com/v/338253)。
* [2021年9月リリースの概要ビデオ](https://video.tv.adobe.com/v/337381)。

### Experience Manager [!DNL Sites] as a [!DNL Cloud Service]

の新機能 [!DNL Sites]:

* A [新しいユーザーインターフェイス](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=en) は、コンテンツ管理者とコンテンツ作成者が、効率的に管理（公開、非公開、コピー、移動などのアクションを実行）したり、検索/フィルターをおこなったり、ヘッドレスユースケース用のコンテンツフラグメントを作成したりできるようになりました。

* 新しい [目次コンポーネント](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=en) は、 [!UICONTROL コアコンポーネント] ただし、すべてのコンポーネントを使用すると、コンテンツページ上に目次を自動的にレンダリングできます。 また、サーバー側でレンダリングされ、Dispatcher によって完全にキャッシュされるので、読み込みも効率的です。

### Experience Manager [!DNL Assets] as a [!DNL Cloud Service]

の新機能 [!DNL Assets]:

* Experience Manager [!DNL Assets] 現在はAdobe Sensei AI 機能を使用 [画像内の色を区別し、取り込み時に自動的にタグとして適用する](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=ja). これらのタグにより、画像の色合いに基づいて、検索エクスペリエンスを強化することが可能になります。1 ～ 40 の範囲で、画像にタグ付けされるカラーの数を設定し、後でそれらのカラーに基づいて画像を検索できます。

### Experience Manager Forms as a Cloud Service

の新機能 [!DNL Forms]:

* [統合 [!UICONTROL アダプティブForms] Microsoft® Power Automate を使用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=en):送信時にMicrosoft® Power Automate Cloud Flow を実行するようにアダプティブフォームを設定できるようになりました。 設定済みのアダプティブフォームは、キャプチャされたデータ、添付ファイルおよびレコードのドキュメントを Power Automate Cloud Flow に送信して処理します。Microsoft® Power Automate の機能を活用しながら、カスタムのデータキャプチャエクスペリエンスを構築し、取り込んだデータに関するビジネスロジックを構築し、顧客ワークフローを自動化できます。

**アダプティブフォームを作成するためのウィザード：** ビジネスユーザーに適したウィザードを使用して、すばやくオーサリングできます [!UICONTROL アダプティブForms]. このウィザードでは、事前設定済みのテンプレート、スタイル設定、フィールド、送信オプションを簡単に選択して、アダプティブフォームを作成するためのクイックタブナビゲーションを提供します。

### Adobe Experience Manager as a Cloud Service の基盤

最新情報:

2022 年 5 月 (2022.5.0) リリースノートで述べたように、レプリケーションエージェント管理画面の「配布」タブの「ツリーを追加」オプションは削除されました。 代わりに、コンテンツのツリー階層を持つパッケージは、「公開を管理」またはコンテンツツリーの公開ワークフローを使用してレプリケートされます。

### [!DNL Cloud Manager]

新機能:

* [!DNL Cloud Manager] ユーザーは、次の便利なビデオチュートリアルにアクセスできるようになりました。 [!UICONTROL ようこそ] カードをランディングページにいつでも貼り付けることができます。

* のポップオーバー [コンテンツを復元](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=en) 環境の詳細ページの「 」タブに、ユーザーが変更をローカルに表示できる git コマンドの便利なリストが表示されるようになりました。

### 新しい Adobe Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年7月 | [エンタープライズワークフロー管理を最大限に活用](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=en) | ビデオ | アセット管理にワークフローを使用する利点と、それらをすばやく作成する方法について説明します。 | AEM - Experience Workflow Management |
| 2022年7月 | [Adobe Experience Managerでヘッドレスエクスペリエンスを提供](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=en) | ビデオ | 最新のExperience Managerを使用したヘッドレスエクスペリエンス管理について説明します [!UICONTROL コンテンツフラグメント] 機能強化と、ヘッドレスコンテンツ配信用の新しい GraphQL API です。 | Experience Manager [!DNL Sites] |
| 2022年7月 | [Adobe Experience Manager Assets でのビジネスに合わせたメタデータの作成](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=en) | ビデオ | アセットのタグ付けの負荷を軽減し、アセットを検索しやすくすることで、AEM Assetsでメタデータを最大限に活用する方法を説明します。 | Experience Manager [!DNL Assets] |
| 2022年7月 | [iOSアプリ](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html) | ビデオ | アプリケーション例は、Adobe Experience Managerのヘッドレス機能を調べる優れた方法です。 このiOSアプリケーションでは、AEMを使用してコンテンツに対してクエリを実行する方法を示します [!UICONTROL GraphQL API] 永続クエリの使用 | Adobe Experience Manager [!DNL Assets], [!DNL Sites] |
| 2022年7月 | [Android™アプリ](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html) | ビデオ | この Android™アプリケーションでは、 [!UICONTROL GraphQL API] AEM. | Adobe Experience Manager [!DNL Assets], [!DNL Sites] |
| 2022年7月 | [Adobe Experience Manager as a Cloud Service の OSGi の設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=en) | ビデオ | AEM CS 用の OSGI の設定方法を説明します。 例えば、AEMコードプロジェクトの一部である設定ファイルを使用した OSGi バンドルの管理と、OSGi コンポーネントの設定の管理について説明します。 | AEM as a Cloud Service |
| 2022年7月 | [フォームデータモデルのプロパティを上書き](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=en) | ビデオ | フォームデータモデルのプロパティを上書きして、1 つのフォームデータモデルを異なるエンドポイントに対して簡単にテストできるようにする方法を説明します。 | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;}

### Adobe Experience Manager リリース情報

Experience Manager のリリースノートはすべて以下のページに記載されています。

* [Adobe Experience Manager as a Cloud Service リリース情報](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=ja)
* [Adobe Experience Manager Cloud Manager リリースノート](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=en)
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
* [Cloud Manager ユーザガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=en)
* [Adobe Experience Manager 6.5 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ja)
* [Adobe Experience Manager 6.4 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ja)
* [Adobe Experience Manager 6.3 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja)
* [Adobe Experience Manager 6.2 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja#previous-updates)
* [Adobe Experience Manager ドキュメントの以前のバージョン](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic ヘルプホーム](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ja)
* [Adobe Experience Manager ドキュメント：最近の更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ja#aem-as-a-cloud-service)

## ![アイコン](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] は、AEMにデプロイされたアプリケーションです。 Adobe Experience Manager でのネイティブ DITA サポートを可能にし、AEM が DITA ベースのコンテンツの作成と配信を処理できる、強力なエンタープライズグレードのコンポーネントコンテンツ管理ソリューション（CCMS）です。

詳しくは、[[!DNL Experience Manager Guides]](https://www.adobe.com/jp/products/xml-documentation-for-experience-manager/features.html)を参照してください。

### その他のリソース

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en) - Experience League のチュートリアル
* [[!DNL Experience Manager Guides] ラーニングとサポート](https://helpx.adobe.com/jp/support/xml-documentation-for-experience-manager.html) - 製品ドキュメント

## ![アイコン](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Adobe Commerce リリースノートについては、以下のリンクを参照してください。

* [Adobe Commerce および Magento Open Source 2.4.x リリースノート](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite のリリースノート](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新しい Adobe Commerce のチュートリアルとドキュメント {#tutorials-commerce}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [Adobe Commerce入門ガイド](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html) | 製品ドキュメント | Adobe CommerceとMagento Open Sourceを初めて使用する商人やシステム管理者向けのガイドです。 プラットフォームの概要と、機能ストアを有効にする基本機能に関する詳細情報を、それぞれの観点からご確認ください。 |
| 2022年7月 | [Page Builder ユーザーガイド](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html) | 製品ドキュメント | 基本的なコンテンツコンポーネントを構築するための 3 つの手順を含む、ページビルダーの機能について説明します。 このガイドは管理者向けです。 ここでは、主なAdobe Commerceの設定と機能に関する基本的な知識を前提としています。 |
| 2022年7月 | [B2B for Adobe Commerceガイド](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html) | 管理ガイド | このモジュールのインストールと有効化に関する詳細な情報（機能の設定や管理など）を取得します。 |
| 2022年7月 | [Adobe Commerce用 B2B — チュートリアル](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=en) | ビデオ（複数） | 詳しくは、 [!UICONTROL 会社] Adobe Commerceのページ 会社アカウントを管理し、承認の保留中のリクエストをリストの上部に表示できます。 |
| 2022年7月 | [クォリティパッチツールの使用](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html) | ビデオ | 詳しくは、 [!UICONTROL クォリティパッチツール]:Adobe CommerceとMagento Open Sourceの品質パッチを提供するコマンドラインツールです。 |
| 2022年7月 | [サイト全体の分析ツールダッシュボード](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html) | ビデオ | サイト全体分析ツールの詳細 この機能は、Adobe Commerceインストールのセキュリティと操作性を確保するための詳細なシステムインサイトと推奨事項を含む、プロアクティブでセルフサービスツールおよび中央リポジトリです。 |
| 2022年7月 | [支払いサービスを使用](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html) | ビデオ | 使用方法を学ぶ [!UICONTROL 支払いサービス] 運用オーバーヘッドを削減するには、収益を増やします。 |
| 2022年7月 | [注文ステータスの管理](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html) | ビデオ | オーダーのステータスとその詳細を確認する方法、および必要に応じてオーダーのステータスを変更する方法について説明します。 |
| 2022年7月 | [マーケティングツール](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=en) | ビデオ（複数） | カタログ価格ルール、買い物かごの価格ルールの作成、関連する製品ルールの管理、ライブ検索などについて説明します。 |
| 2022年7月 | [ビジネス価値を実現するコンテンツのパーソナライゼーションの革新](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=en) | ビデオ | スキルビルダーのプレゼンテーションを表示し、コンテンツのオーサリングを民主化し、オムニチャネル配信を簡単にし、パーソナライゼーションを拡大するのに役立つAdobeのコンテンツソリューションの最近のイノベーションについて説明します。 |
| 2022年7月 | [カタログ管理](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html) | ビデオ | Adobe Commerceでのカタログ管理について説明します。 カテゴリの作成、カテゴリ内の製品の管理、在庫の管理などを行います。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/target.png) [!DNL Adobe Target] {#target}

最終更新日：**2022年6月30日（PT）**

* プレリリース情報については、[Adobe Target プレリリース](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ja)を参照
* 現在の情報については、[Adobe Target リリースノート](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=ja)を参照

### 新しい Adobe Target コースとチュートリアル {#tutorials-target}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [オーディエンスの作成](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html) | ビデオ | でカスタムオーディエンスを作成して保存する方法を説明します。 [!DNL Target] を使用して、アクティビティで使用します。 |
| 2022年7月 | [Adobe Targetを使用したパーソナライズと自動化](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=en) | ビデオ | 次を使用してAdobe Target機能を自動化および最適化する際の主な概念について説明します。 [!UICONTROL 自動ターゲット] および [!UICONTROL 自動パーソナライゼーション]. |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 最新の Campaign 製品リリース

* [Campaign v8.3 リリース](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/release-notes.html?lang=ja)
* [Campaign Standard 22.2 リリース](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ja)
* [Campaign コントロールパネル6 月リリース](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en)
* [チュートリアルとコース](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=ja#tutorials-campaign) Experience League

### 新しい [!DNL Campaign] のチュートリアルとコース {#tutorials-campaign}

新しく公開された Adobe Campaign ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年7月 | [ハイブリッドホスティングモデルのコントロールパネル](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html) | ビデオ | Adobe Campaign ハイブリッドホスティングモデルのコントロールパネルを有効にする方法、コントロールパネルにアクセスする方法および主な機能のロックを解除する方法を説明します。 | コントロールパネル |
| 2022年7月 | [スループットと遅延の監視](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=ja) | ビデオ | キャンペーンインスタンスの配信スループットとトランザクションメッセージの待ち時間を監視する方法について説明します。 | コントロールパネル |
| 2022年7月 | [ワークフローを監視してリソース使用量を最適化する](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=ja) | ビデオ | ワークフローの一時的なストレージ使用状況を監視する方法、およびインスタンスでのデータベースやワークフローの問題を回避するためのワークフロー設定の場所について説明します。 | コントロールパネル |
| 2022年7月 | [Adobe Campaign Classicでのデータモデルの開発とカスタマイズ](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=en) | ビデオ（スキルビルダーイベント） | このセッションに Campaign のトレーナーと共に参加して、Campaign Classic内のデータモデル内でデータスキーマを開発する方法を学びます。 | Campaign Classic v7 |
| 2022年7月 | [結果を導く配信品質のベストプラクティスと戦略](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html) | ビデオ | メールキャンペーンの計画と実稼働にかかる数え切れない時間を最小限に抑える方法を学びます。 | Campaign Classicv7 |
| 2022年7月 | [Adobe Campaign Classicでのクロスチャネルマーケティングのレベルアップ](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=en) | ビデオ | Adobe Campaign Classicのお客様向けのワークフロー、自動化、パーソナライゼーション、測定に焦点を当てた、詳細なウェビナーをご覧ください。 | Campaign Classicv7 |
| 2022年7月 | [プロからの時間節約のヒント！](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=en) | ビデオ | Adobe Campaign・プロのヒントとテクニックから新年を始めましょう。 キャンペーンの作成と開始、およびより意味のあるカスタマイズされたクロスチャネルエクスペリエンスを提供する方法について、より効率的に学びます。 | Campaign Classicv7 |
| 2022年7月 | [Adobe Campaignとマーケティングエコシステムの統合](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=en) | ビデオ | マーケティングエコシステムとAdobe Campaignの統合について説明します。 Adobe Campaignのようなクロスチャネルマーケティングソリューションを、他のテクノロジーやチームから分離して配置しないでください。 異なるシステムが顧客の完全な理解を妨げ、クロスチャネル戦略を中断させないようにします。 | Campaign Classicv7 |
| 2022年7月 | [Adobe Campaign Standard Customer Spotlight - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=en) | ビデオ | Microsoft®のマーケティングチームから、Adobe Campaign Standardの使用方法、アーキテクチャとガイドの原則、ベストプラクティスについてお聞かせください。 | Campaign Standard |
| 2022年7月 | [Adobe Campaign Customer Spotlight - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=en) | ビデオ | Adobe Campaignのお客様は、課題を解決し、新しい標準に合わせて調整し、キャンペーンを管理してより効率的になり、Adobe Campaignを通じて有意義な価値を高める方法を共有しています。 | Campaign Classicv7 |
| 2022年7月 | [Adobe Campaign Classic V7 と V8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=en) | ビデオ | 最新の製品アップデートの詳細を確認し、アドビの製品マネージャーから V7 と V8 の違いを理解します。 | Campaign Classicv7、Campaign v8 |
| 2022年7月 | [基調 — B2B および B2C における顧客ジャーニーの動向とイノベーション](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=en) | ビデオ | B2B および B2C にわたる顧客ジャーニー管理の最新の傾向について説明します。 主要なジャーニーアプリケーションやAdobe Experience Cloud、Platform の最新のイノベーションをご覧ください。 | Marketo、Campaign Classicv7、Campaign v8 |
| 2022年7月 | [Adobe Campaign Standardの主なヒントとテクニック](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=en) | ビデオ | ACS をより適切に使用するために、Adobe Campaign Standardインスタンスにプラグインし、ターゲティング、パーソナライゼーション、マーケティング疲労に関するベストプラクティスを見つけます。 | Campaign Standard |
| 2022年7月 | [クロスチャネルマーケティングのサポートに必要なチーム、スキル、組織設計](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html) | ビデオ | どこでも、いつでも、好きな場所でエンゲージできるようにする方法を学びます。 計画、実行、測定をサポートするマーケティング組織が存在することの重要性について説明します。 | Campaign Classicv7, Campaign v8,Campaign Standard |

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

新しく公開されたAdobe Journey Optimizerビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [メッセージ頻度ルールの設定](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html) | ビデオ | 頻度ルールを作成、アクティブ化、テストおよびレポートする方法について説明します。メッセージに継承する頻度ルールを決定する方法について説明します。 |
| 2022年7月 | [SMS メッセージの設定、作成および配信](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html) | ビデオ | SMS メッセージを設定、作成、およびカスタマージャーニーに含める方法について説明します。 |
| 2022年7月 | [SMS の受信キーワードのサポート](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html) | ビデオ | SMS のネイティブ受信キーワードサポート（開始、停止、停止解除）の仕組みについて説明します。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] のその他のリソース

* [Journey Optimizer ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ja)
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

新しく公開されたAdobeMarketo向けビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年7月 | [Marketo EngageとAdobe Experience Cloudを使用した B2B エクスペリエンス](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=en) | ビデオ | Adobe Experience CloudとMarketo Engageの統合に関する説明と、解決される問題点について説明します。 | Marketo Engage |
| 2022年7月 | [共により良い —Adobe Marketo EngageとReal-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=en) | ビデオ | Marketo Engageと RT-CDP（B2B エディション）を使用して B2B キャンペーンを調整する方法と、最も多くの使用例とロック解除されたメリットについて説明します。 | Marketo、Real-time Customer Data Platform |

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

最終更新日： **2022 年 7 月 15 日**

| 機能 | 説明 |
| ------- | ----------- |
| カスタムレポート | (31)5 月リリースベータ版機能 )Advertising Cloud DSPは、顧客データプラットフォーム (CDP) 内で作成された認証済みシグナルで構成されるファーストパーティセグメントを取り込めるようになりました。 |
| [!UICONTROL 在庫] | （6 月 30 日リリース）新機能 [!UICONTROL 在庫] > [!UICONTROL 契約] ビューには、 [!UICONTROL キャンペーン] 追加のフィルター、列のカスタマイズ、カスタムビュー、列の並べ替え、データビジュアライゼーション（グラフ）ビューを保存するオプションを含むビュー。 取引名の後の省略記号 (...) をクリックして、各行のコマンドメニューを開くことができます。 |
| [!UICONTROL 在庫インスペクター] | （6 月 29 日リリース） [!UICONTROL 在庫] 配置のタブ [!UICONTROL 検査官] には、カスタマイズ可能なデータ視覚化グラフと、次のような拡張されたパフォーマンス指標が含まれます。 [!UICONTROL 視認性率], [!UICONTROL クリック数]、および [!UICONTROL 昨日の CPM]. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] の新機能 {#adcloud-search}

最終更新日： **2022 年 7 月 15 日**

| 機能 | 説明 |
| ------- | ----------- |
| [!UICONTROL インサイト] | （6 月 12 日リリース）インプレッション共有損失分析は、ベータ版機能として再び使用できるようになりました。 |
| [!DNL Advanced Campaign Management] | （6 月 21 日）([!DNL Google Ads] および [!DNL Microsoft Advertising] キャンペーン ) 在庫の内容に基づいて、検索エンジン固有の広告テンプレートを使用して、動的なレスポンシブ検索広告バリエーションを次の場所から作成できるようになりました。 [!UICONTROL キャンペーン] > [!UICONTROL アドバンス (ACM)]. |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Adobe Document Cloud 向けに新しく公開されたチュートリアルとコース。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年7月 | [承認者の役割の使用](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=en) | ビデオ（更新） | 承認プロセスを通じてドキュメントを送信する方法を説明します。 | Adobe Sign |
| 2022年7月 | [Web フォームの設定](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html) | ビデオ（更新） | Web サイト上で直接電子署名が可能なドキュメントを作成する方法を説明します。 | Adobe Sign |
| 2022年7月 | [委任者の役割の使用](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | ビデオ （更新済み） | 説明 | Adobe Sign |
| 2022年7月 | [ドキュメントの電子署名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=en) | ビデオ（更新） | Acrobat Signで送信されたドキュメントに簡単に署名できる方法を説明します。 | Adobe Sign |
| 2022年7月 | [Acrobat Sign管理者向けのインストールおよび導入](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=en) | ビデオ（更新） | 管理者がAcrobat Signをすぐに使い始めるために注力する必要がある 7 つの主要な領域について説明します。 | Adobe Sign |
| 2022年7月 | [Outlook のSend for Signature](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=en#) | ビデオ（更新） | Microsoft® Outlook 内で直接署名用のドキュメントを送信することで、ドキュメントワークフローを効率化する方法を説明します。 | Adobe Sign |
| 2022年7月 | [Outlook での入力と署名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=en) | ビデオ（更新） | Microsoft Outlook 内で直接フォームに入力して署名することで、ドキュメントワークフローを合理化する方法を説明します。 | Adobe Sign |
| 2022年7月 | [グループの作成と管理](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=en) | ビデオ（更新） | グループの作成、グループへのユーザーの追加、およびグループ設定の編集の方法について説明します。 | Adobe Sign |
| 2022年7月 | [他のユーザーに署名を委任](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=en) | ビデオ（更新） | ドキュメントの署名を他のユーザーに委任する方法を説明します。 | Adobe Sign |

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

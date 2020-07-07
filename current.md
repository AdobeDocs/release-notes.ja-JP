---
title: Adobe Experience Cloud リリースノート
description: Adobe Experience Cloud リリースノート
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: efd848cda1046613c889825fff57b868b67e1c80
workflow-type: tm+mt
source-wordcount: '7021'
ht-degree: 99%

---


# Adobe Experience Cloud リリースノート - 2020 年 6 月

![バナー](/assets/experience-cloud-banner-3.png)

このページでは、[!DNL Adobe Experience Cloud] の新機能、修正点および重要な注意事項について説明します。また、Experience Cloud を最大限に活用するための新しいドキュメント、トレーニングコース、ビデオチュートリアルも紹介しています。

>[!NOTE]
>
>[Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。

**リリース日：2020 年 6 月 19 日**

製品のリリース日は変更される場合があります。頻繁に更新を確認してください。

最終更新日：**2020 年 6 月 19 日**

* [Adobe システムステータス](#status)
* [Experience Cloud インターフェイス](#ecloud)
* [Experience Platform](#platform)
* [ジャーニーオーケストレーション](#journey-orch)
* [Analytics](#analytics)（および [Customer Journey Analytics](#cust-journey)）
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/ja-JP/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/jp/primetime/user-guide.html)（Primetime のヘルプページへのリンク）

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。

## ![アイコン](/assets/adobe.png) Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

リリース日：**2020 年 5 月 22 日**

**最新情報**

* Adobe ID を使用して、製品オファーやアドオンレベルまで掘り下げた、より精度の高いイベント通知を登録できます。購読をよりすばやく設定するのを支援するために、セルフサブスクリプションプロセスで、製品の使用権限に基づいてお勧めの製品およびサービスが表示されるようになりました。これにより、受信する電子メールの数が減り、より関連性の高い通知をインボックスに配信できます。はじめに [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit) をご覧ください。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| 購読と通知に関するユーザーエクスペリエンスを改善 | <ul><li>[!DNL Marketo Engage] の地域は、選択した製品やサービスのリストに基づいてフィルタリングされるようになりました。</li><li>[!DNL Marketo Engage] の電子メール通知は、ユーザーの地域、場所および環境の設定に関連します。</li></ul> |
| イベント購読の確認 | <ul><li>進行中の単一イベントの更新を購読する際に、電子メールによる確認を受け取れるようになりました。</li></ul> |
| グローバルナビゲーションのユーザビリティの強化 | <ul><li>`Adobe.com` のトップレベルナビゲーションメニューの操作の一貫性が向上しました。</li></ul> |

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud インターフェイス {#ecloud}

Experience Cloud インターフェイスに対する一般的なアップデートです。

**統合製品ドメイン**

アドビでは、すべての Adobe Experience Cloud アプリケーションでエクスペリエンスを統合し、向上させるために、ドメインとインターフェイスのヘッダーを更新しています。これらの機能強化は、小規模ではあっても、重要な方法でエクスペリエンスをシンプルにするように設計されています。これらの機能強化では、現在のワークフローは変更されません。

更新内容は次のとおりです。

* 新しいアプリケーション URL：`experience.adobe.com/<application name>`：
   * すべての製品で、最終的にこの URL パターンが採用されます。1 か月間にわたって効果的な新しい URL を探します。
   * ブラウザーのサポート：サポートされるブラウザーには、[!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari]、および [!DNL Opera]（最新バージョン）が含まれます。**メモ：** Experience Cloud インターフェイスはこれらのブラウザーをサポートしていますが、個々のアプリケーションがすべてのブラウザーに対応しているわけではありません（例えば、[Analytics](https://docs.adobe.com/content/help/ja-JP/analytics/admin/sys-reqs.html) は [!DNL Opera] をサポートしておらず、[Target](https://docs.adobe.com/help/ja-JP/target/using/implement-target/before-implement/supported-browsers.html) は [!DNL Safari] をサポートしていません）。
   * （[!DNL Safari] のみ）ドメインの変更によって、[!DNL Safari] で cookie の問題が発生する場合があります。[!DNL Safari] のプライバシー設定で「_サイト越えトラッキングを防ぐ_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Experience Cloud がこの新しいドメインで機能するようになります。
* 組織間または別のアプリケーション間の切り替えが容易になりました。
* 製品ヘルプの改善：ヘルプ検索にコミュニティフォーラムやビデオコンテンツの結果も含められるよう、[!UICONTROL Experience League] は製品に統合されています。この変更により、より多くのコンテンツへのアクセスが簡素化され、Experience Cloud を最大限に活用できるようになります。さらに、**[!UICONTROL ヘルプ]** ／ **[!UICONTROL フィードバック]**&#x200B;をクリックして問題を報告したり、アドビとアイデアを共有したりします。

次のアプリは、新しい experience.adobe.com ドメインを使用します。

| アプリまたはサービス | ドメイン |
| -----------| ---------- |
| Experience Cloud ホームページ | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Journey Management | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign コントロールパネル | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| ソフトウェア配布 | `experience.adobe.com/downloads` |
| 管理ツール（ベータ版） | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL ボードとコレクション]**（[!UICONTROL Experience Cloud Assets] セレクターのレガシーフィルター）は廃止されます。

## ![アイコン](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

[!DNL Experience Platform] およびアプリケーションサービスのリリースノート（[!DNL Experience Platform Launch,] [!UICONTROL 、Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services]、およびセキュリティ速報を含む）。

リリース日：**2020 年 6 月 10 日**

[!DNL Adobe Experience Platform] には、次の新機能が含まれています。

* **Data Science Workspace：**[!DNL JupyterLab Launcher] に、リアルタイムマシンラーニング（アルファ）用の [!DNL Python] ノートブックスターターが含まれるようになりました。
* **セグメント化：** 日付関数の「記念日」フィールドが追加され、年が含まれない日付を評価できるようになりました。
* **ソース：**[!DNL Apache HDFS] および [!DNL Couchbase] 用の新しいソースコネクタです。

これらの機能について詳しくは、[Experience Platform リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)を参照してください。

### その他の Experience Platform のリリース情報

* [Experience Platform Launch リリースノート](https://docs.adobe.com/content/help/ja-JP/launch/using/intro/release-notes/current.html)
* [セキュリティ速報および情報](https://helpx.adobe.com/jp/security.html)（すべてのアドビ製品）

### 新しい Experience Platform コースとチュートリアル {#tutorials-plat}

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |
| [Adobe Experience Platform の概要](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | コース | データを各チャネルでアクティブ化できる堅牢なリアルタイムの顧客プロファイルと AI に基づくインサイトに変換することで、Adobe Experience Platform が適切なエクスペリエンスを提供する方法を説明します。この入門レベルのコースでは、Experience Platform の機能、使用例、Adobe Experience Cloud との関係、基本的なアーキテクチャ、インターフェイス、プロジェクトの役割について概要を説明します。 |
| [Web SDK と Edge ネットワークの概要](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | ビデオチュートリアル | Adobe Experience Platform SDK と Edge ネットワークの概要です。Experience Platform Web SDK は、顧客が JavaScript ライブラリ、ビーコンタイプ、データストリーム、サーバーサイドの宛先を それぞれ 1 つ使用して、すべてのアドビアプリケーションとサードパーティの宛先にデータを送信できる、クライアントサイド JavaScript ライブラリです。 |
| [Web SDK と Edge ネットワークのデモ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | ビデオチュートリアル | アドビへの 1 回の呼び出しで Adobe Experience Platform、Analytics、Audience Manager および Target にデータを送信する、Experience Platform Web SDK および Edge ネットワークの動作を視聴します。 |
| [リアルタイム顧客データプラットフォームのデモ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | ビデオチュートリアル | リアルタイム CDP を使用して複数のソースからデータを収集する方法について説明します。このデータを 1 つのリアルタイム顧客プロファイルに統合し、そのデータをアクティブ化して、パーソナライズされた顧客エクスペリエンスを作成できます。 |

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Adobe Experience Platform を使用すると、それぞれの顧客のニーズをリアルタイムでインテリジェントに予測し、どのようなジャーニーをたどっていても、個別カスタマージャーニーをエクスペリエンスチャネル全体で大規模に編成することができます。

### 最新リリース

最新のリリースのアップデートについて詳しくは、[Journey Orchestration](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html) リリースノートを参照してください

### 新しい Journey Orchestration コースとチュートリアル {#jo-tutorials}

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |
| [Journey Orchestration を使い始める（管理者向け）](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | コース | Journey Orchestration の設定方法と使用方法について説明します。このコースでは、ジャーニーの編成を有効にするために必要な主要概念と構成手順について説明します。編成されたジャーニーを作成、公開、レポートおよび分析する方法について学びます。 |
| [Journey Orchestration を使い始める（ビジネスユーザー向け）](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | コース | Journey Orchestration の設定方法と使用方法について説明します。このコースでは、主な概念について説明します。編成されたジャーニーを作成、公開、レポートおよび分析する方法について学びます。 |

### Jargeny Orchestration の追加リソース

[ドキュメント](https://docs.adobe.com/content/help/ja-JP/journeys/using/journey-orchestration-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2020 年 6 月 18 日**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Media Analytics](#media-aa) の新機能です。
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [新しい Adobe Analytics コースとチュートリアル](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | [一般公開](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| -----------| ---------- |-------|
| Attribution IQ：アルゴリズムアトリビューション | 2020 年 6 月 19 日 | Analysis Workspace の [!UICONTROL アルゴリズムアトリビューション]モデルでは、統計的手法を使用して、選択した指標に対するクレジットの最適な配分を動的に決定します。Adobe Analytics Ultimate のお客様が利用できます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/attribution/algorithmic.html) |
| Attribution IQ：カスタムルックバックウィンドウ | 2020 年 6 月 19 日 | [!UICONTROL Attribution IQ] で任意のアトリビューションモデルを設定して、レポート期間の最大 90 日前のタッチポイントを含められるようになりました。これにより、通常、前月（または過去数か月）に発生したインタラクションを考慮することで、レポートの初期に発生するイベントのアトリビューション精度を高めます。Adobe Analytics Foundation、Select、Prime、Premium、Premium Attribution、Premium Complete、および Ultimate のお客様が利用できます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/attribution/models.html#ルックバックウィンドウ) |
| 共有 Workspace プロジェクトのプロジェクトロール | 2020 年 6 月 19 日 | Workspace プロジェクトを共有する際は、受信者を、使用するプロジェクトエクスペリエンスに応じて、編集、複製、表示の 3 つのプロジェクトの役割のいずれかに受信者を配置できるようになりました。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 表示専用 Workspace プロジェクト | 2020 年 6 月 19 日 | Workspace プロジェクトは、「表示可能」としてのみユーザーに共有できます。「表示」受信者が共有プロジェクトを開くと、左側のパネルが表示されず、操作が制限された状態となる、より制限が厳格なプロジェクトエクスペリエンスが提供されます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Workspace プロジェクトを共同編集できる機能 | 2020 年 6 月 19 日 | 「編集可能」の役割に追加された受信者は、それらのユーザーと共有されているプロジェクトを上書き保存できます。これは、管理者と非管理者の両方に適用されます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Workspace の空白パネルの更新 | 2020 年 6 月 19 日 | Workspace の空白パネルにパネルとビジュアライゼーションが追加され、最適な分析ワークフローを、よりシームレスに選択できるようになりました。 |
| 中国で使用可能なファーストパーティドメイン | 2020 年 6 月 19 日 | `.cn` ドメインを持つお客様が、中国本土内での使用をファーストパーティドメインにリクエストできるようになります。（中国のパフォーマンス最適化 SKU の購入に関するドキュメント） |
| Workspace のクイックインサイトパネル | 2020 年 6 月 26 日 | クイックインサイトは、Analysis Workspace のアナリスト以外のユーザーと新規ユーザーに対して、ビジネスの質問にすばやく簡単に答える方法を学ぶためのガイダンスを提供します。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| ワークスペース の Analytics for Target パネル | 2020 年 6 月 26 日 | Analytics for Target（A4T）パネルを使用すると、Analysis Workspace で上昇率と信頼性を使用して Adobe Target のアクティビティとエクスペリエンスを分析できます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL Workspace について]ページ | 2020 年 6 月 19 日 | [!UICONTROL Workspace について]ページには、Analysis Workspace 環境や Adobe Analytics 管理者（サポートが必要な場合）に関する情報、および製品内でフィードバックを提供する方法が記載されています。**[!UICONTROL Workspace]**／**[!UICONTROL ヘルプ]**／**[!UICONTROL Workspace について]**&#x200B;で確認できます。 |

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | [一般公開](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| -----------| ---------- |-----|
| オブジェクト配列のサポート | 2020 年 6 月 19 日 | CJA のお客様は、Adobe Experience Platform データセットスキーマ内のオブジェクト配列に表示されるディメンションと指標についてレポートできるようになりました。[詳細情報...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-usecases/object-arrays.html) |
| Attribution IQ：[!UICONTROL アルゴリズムアトリビューション] | 2020 年 6 月 19 日 | [!UICONTROL Analysis Workspace] の [!UICONTROL アルゴリズムアトリビューション]モデルでは、統計的手法を使用して、選択した指標に対するクレジットの最適な配分を動的に決定します。Adobe Analytics Ultimate のお客様が利用できます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics-platform/using/cja-workspace/attribution/algorithmic.html) |
| Attribution IQ：カスタムルックバックウィンドウ | 2020 年 6 月 19 日 | [!UICONTROL Attribution IQ] で任意のアトリビューションモデルを設定して、レポート期間の最大 90 日前のタッチポイントを含められるようになりました。これにより、通常、前月（または過去数か月）に発生したインタラクションを考慮することで、レポートの初期に発生するイベントのアトリビューション精度を高めます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics-platform/using/cja-workspace/attribution/models.html) |
| 共有 [!UICONTROL Workspace] プロジェクトのプロジェクトロール | 2020 年 6 月 19 日 | [!UICONTROL Workspace] プロジェクトを共有する際は、受信者を、使用するプロジェクトエクスペリエンスに応じて、編集、複製、表示の 3 つのプロジェクトの役割のいずれかに受信者を配置できるようになりました。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| 表示専用 [!UICONTROL Workspace] プロジェクト | 2020 年 6 月 19 日 | [!UICONTROL Workspace] プロジェクトは、「_[!UICONTROL 表示可能]_」としてのみユーザーに共有できます。「表示」受信者が共有プロジェクトを開くと、左側のパネルが表示されず、操作が制限された状態となる、より制限が厳格なプロジェクトエクスペリエンスが提供されます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics-platform/using/cja-workspace/curate-share/view-only-projects.html) |
| [!UICONTROL Workspace] プロジェクトを共同編集できる機能 | 2020 年 6 月 19 日 | _[!UICONTROL 編集可能]_ 役割に追加された受信者は、それらのユーザーと共有されているプロジェクトを上書き保存できます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| [!UICONTROL Workspace] のクイックインサイトパネル | 2020 年 6 月 26 日 | クイックインサイトは、[!UICONTROL Analysis Workspace] のアナリスト以外のユーザーと新規ユーザーに対して、ビジネスの質問にすばやく簡単に答える方法を学ぶためのガイダンスを提供します。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics-platform/using/cja-workspace/panels/quickinsight.html) |
| [!UICONTROL Workspace について]ページ | 2020 年 6 月 19 日 | [!UICONTROL Workspace について]ページには、Analysis Workspace 環境や Adobe Analytics 管理者（サポートが必要な場合）に関する情報、および製品内でフィードバックを提供する方法が記載されています。**[!UICONTROL Workspace]**／**[!UICONTROL ヘルプ]**／**[!UICONTROL Workspace について]**&#x200B;で確認できます。 |

<!-->Support for [!UICONTROL Anomaly Detection] - July ??, 2020 - [!UICONTROL Anomaly Detection] provides a statistical method to determine how a given metric has changed in relation to previous data. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html)<-->

### [!UICONTROL Media Analytics] の新機能です {#media-aa}

更新日：**2020 年 6 月 19 日**

| 機能 | [一般公開](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| -----------| ---------- | ---------- |
| [サポートされるデバイスとプラットフォーム](https://docs.adobe.com/content/help/ja-JP/media-analytics/using/supported-devices.html) | 2020 年 6 月 19 日 | AEP SDK を含むメディア Launch 拡張機能で、以下の OTT デバイスがサポートされるようになりました。<ul><li>Apple TV（tvOS）</li><li>Fire TV（Fire OS）</li><li>Android TV</li></ul> |  | [サポートされるデバイスとプラットフォーム](https://docs.adobe.com/content/help/ja-JP/media-analytics/using/supported-devices.html) | 2020 年 6 月 19 日 | AEP SDK を含むメディア Launch 拡張機能で、以下の OTT デバイスがサポートされるようになりました。<ul><li>Apple TV（tvOS）</li><li>Fire TV（Fire OS）</li><li>Android TV</li></ul> |
| [プレーヤーステートトラッキング](https://docs.adobe.com/content/help/ja-JP/media-analytics/using/player-state-tracking/player-state-overview.html) | 2020 年 5 月 30 日 | [!UICONTROL Media Analytics] のお客様は、標準的なソリューション変数のセット（フルスクリーン、クローズドキャプション、ミュート、ピクチャインピクチャ、インフォーカス）を使用して、再生中の閲覧者のインタラクションをキャプチャできます。また、カスタムプレーヤー状態を柔軟に作成することもできます。[!UICONTROL Analysis Workspace] のレポートで、プレイヤー状態追跡変数を使用できるようになりました。この機能を使用するには、次のいずれかが必要です。 <ul><li>Media [!DNL JavaScript] SDK 3.0 以降</li><li>[!DNL Adobe Experience Platform]（AEP）SDK で使用する場合：</li><li>[!UICONTROL Media Analytics 拡張機能]（Web 用）：[!UICONTROL Adobe Media Analytics]（3.x SDK）for Audio および Adobe Media Analytics for Video v1.0 以降</li><li>[!UICONTROL Media Analytics Extension]（モバイル用）：[!UICONTROL Adobe Media Analytics for Audio] および Adobe Media Analytics for Video v2.0 以降</li><li>[!UICONTROL メディアコレクション]</li></ul> |

### Adobe Analytics の修正点 {#aa-fixes}

* マルチバイトのセグメントで特定のレポートスイートを検索しても、何も一致しない問題を修正しました。現在は、正しい文字列と一致するようになりました。（AN-220043）
* [!UICONTROL Reports &amp; Analytics] で[!UICONTROL 項目フィルター]が機能しない問題を修正しました。（AN-206132）
* [!UICONTROL スケジュール済みプロジェクト]インターフェイスの応答時間が遅い問題を修正しました。（AN-214837）
* Analytics レポート API 2.0 で日付範囲エラーが発生する問題を修正しました。（AN-215087）
* インスタンス／訪問／訪問者が[!UICONTROL 滞在時間]指標の分母としてカウントされない問題を修正しました。この問題は、同じ時間（秒）にディメンションの値を持たないヒット（Pagename など）が続いた場合に発生していました。（AN-211074）
* ユーザーが、自分と共有された [!UICONTROL Workspace] プロジェクトにアクセスできない問題を修正しました。（AN-217561）
* キーが [!UICONTROL 分類ルールビルダー]で分類されない問題を修正しました。（AN-221538）
* [!UICONTROL サーバーコールの使用状況]で、使用状況データがレポートされない問題を修正しました。（AN-210452）
* Adobe Analytics セグメントを公開すると、Audience Manager でデータが欠落する問題を修正しました。（AN-220208、AN-220659）
* レポートにデータが表示されるが、[!UICONTROL データフィード]ログには「Data Warehouse データがありません」と表示される問題を修正しました。（AN-220784、AN-220858）
* `experiencecloud.com` ドメインから[!UICONTROL Ad Hoc Analysis] が起動されない問題を修正しました。（AN-219680、AN-221629）
* 「Ctrl（または Command）+ C」ホットキーの使用に関する問題を修正しました。（AN-221101、AN-221537）
* [!UICONTROL Activity Map] 有効化ページの問題を修正しました。（AN-222029、AN-221242）
* [!UICONTROL フォールアウト]ビジュアライゼーションの途中にタッチポイントを追加できなかった問題を修正しました。（AN-221648）

#### その他の Adobe Analytics の修正点

AN-218269、AN-218455、AN-218492、AN-219888、AN-220447、AN-220546、AN-220788、AN-220866、AN-221165、AN-221545、AN-221712、AN-221832、AN-221853、AN-222000、AN-222505、AN-222559

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 統合製品ドメインへの移行 | 発効日：2020 年 5 月 29 日 | Adobe Analytics の統合製品ドメインへの移行は 2020 年 1 月に開始され、2020 年 5 月 29 日に完了しました。Adobe Analytics はアーキテクチャからすべての `omniture.com` ドメイン参照を削除しますが、サードパーティ Cookie として許可リスト `omniture.com` を作成することが重要です。アーキテクチャの完全な移行が（間もなく）完了したら、リリースノートからお知らせいたします。すると、この許可リストの手順は不要になります。許可リストに登録する必要のある推奨 IP アドレスとドメインの完全なリストは、[こちら](https://helpx.adobe.com/jp/analytics/kb/adobe-ip-addresses.html)をご覧ください。<br>組織がサードパーティ Cookie をブロックしている場合は、カスタマーケアに連絡して、Adobe Analytics へのアクセスを再取得してください。 |
| 新しい Adobe Analytics のデフォルトランディングページ | 発効日：2020 年 6 月 19 日 | 2020 年 6 月 19 日に、Adobe Analytics のデフォルトのランディングページが[!UICONTROL レポート]から [!UICONTROL ワークスペース] に変更されます。この変更は、過去にカスタムランディングページを設定していないユーザーに対して適用されます。 |
| サードパーティのテクノロジー許可リスト | 2020 年 3 月 13 日（発効日） | Adobe Analytics は、サードパーティのテクノロジーを活用して、機能のロールアウト管理と製品内サポートを開始しました。すべての機能にアクセスできるよう、必要なネットワークファイアウォールの許可リストに、次の URL を追加する必要があります。<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| [!UICONTROL Analysis Workspace] の可用性に対する冗長性の向上 | 2020 年 5 月 22 日 | [!UICONTROL Analysis Workspace] の可用性を確保するために、セカンダリ CDN（コンテンツ配信ネットワーク）を追加し、冗長性を高めます。必要なネットワークファイアウォールの許可リストに、次の URL を追加する必要があります。<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| [!UICONTROL ワークスペース] での[!UICONTROL 入口／出口]の計算方法の変更 | 2020 年 4 月 8 日 | 2020 年 3 月の時点で、[!UICONTROL Analysis Workspace] における「_なし_」の値と[!UICONTROL 入口／出口]との相互作用を変更しました。[!UICONTROL Analysis Workspace] で「_なし_」をオン／オフにできるようになったので、入口または出口の後に「_なし_」を適用します。（eVar の場合）以前は、これらの前に適用されていました。例えば、訪問の最初のヒットに eVar の値がないが、2 回目のヒットに eVar の値があるとします。[!UICONTROL Reports &amp; Analytics] では、最初のヒットがそのエントリに対して「_未指定_」と表示されますが、[!UICONTROL Analysis Workspace] では 2 回目のヒットの値が表示されます。 |
| **[!UICONTROL ダッシュボードアーカイブ]**&#x200B;のサービス終了 | 2020 年 3 月 28 日 | [!UICONTROL Reports &amp; Analytics] の「**[!UICONTROL ダッシュボードを管理]**」の「**[!UICONTROL アーカイブを表示]**」設定は、2020 年 10 月から使用できなくなります。 |
| 提供終了 - Analytics レガシー API | 2020 年 1 月 10 日 | 2020 年 11 月に、以下の Analytics レガシー API サービスが提供終了となり、シャットダウンされます。これらのサービスを使用して構築された現在の統合は機能しなくなります。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問に対する回答と進め方に関するガイダンスを提供するために、[従来の API EOL の FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis のサポート終了 | 2018 年 8 月 7 日 | アドビは Ad Hoc Analysis のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。詳しくは、[Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) を参照してください。 |

#### 新しい Analytics コースとチュートリアル {#tutorials-analytics}

Analytics と Customer Journey Analytics の新しいコース、チュートリアルビデオ、記事。

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |
| [Customer Journey Analytics を使い始める（ユーザー向け）](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | コース | このコースでは、Customer Journey Analytics（CJA）を使用して様々なデータソースのデータを分析する方法について学びます。Adobe Analytics と Customer Journey Analytics の違い、および CJA でのデータの処理方法について学習します。このコースを受講した後は、クロスチャネルのビジュアライゼーションを作成およびカスタマイズして、顧客に対する理解を深めることができるようになります。 |
| [Customer Journey Analytics を使い始める（管理者向け）](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | コース | [!UICONTROL Journey Orchestration] の設定方法と使用方法について説明します。このコースでは、ジャーニーの編成を有効にするために必要な主要概念と構成手順について説明します。編成されたジャーニーを作成、公開、レポートおよび分析する方法について学びます。 |
| [Customer Journey Analytics を使い始める（データエンジニア向け）](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | コース | このコースでは、Customer Journey Analytics に取り込まれるデータと、そのデータがアナリストのレポートに与える影響について学びます。このコースは、Adobe Experience Platform に関するお客様の一般的な知識に基づいて構築されます。 |
| [Customer Journey Analytics を使い始める（管理者向け）](https://video.tv.adobe.com/v/34349?captions=jpn) | ビデオチュートリアル | 管理者向けの Customer Journey Analytics の紹介ビデオです。 |
| [ガイド付き Analytics の実装](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | コース | このコースでは、Adobe Analytics の実装を開始する方法、Analytics の概念を理解する方法、計画を作成する方法、および Experience Platform Launch を使用した Adobe Analytics の実装方法を学びます。 |
| [Adobe Analytics を使い始める（リーダー向け）](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | コース | このコースでは、Analytics の基本と、Analysis Workspace によってビジネスを変える方法について説明します。Adobe Sensei でインサイトを明らかにする方法や顧客の声を聞く方法を学び、Summit 2019 で業界の専門家による講演のハイライトを視聴します。 |
| [Analysis Workspace を使い始める](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | コース | Analysis Workspace の使用を開始する方法を説明します。最初のプロジェクトを作成し、プロジェクトで日付範囲を定義、セグメントを適用、および共有と共同作業をおこなう方法を学びます。 |
| [Adobe Analytics ダッシュボードのスコアカードビルダー](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | ビデオチュートリアル | このビデオでは、[!UICONTROL Analysis Workspace] で[!UICONTROL スコアカード]を作成および共有し、Adobe Analytics ダッシュボード（モバイルアプリ）で表示する方法について説明します。 |
| [Adobe Analytics ダッシュボードのアプリ内エクスペリエンス](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | ビデオチュートリアル | このビデオでは、Adobe Analytics ダッシュボード（モバイルアプリケーション）を使用して、自分が作成または共有した表示[!UICONTROL スコアカード]にアクセスする方法について説明します。 |

#### AppMeasurement {#appm}

AppMeasurementリリースの最新の更新については、AppMeasurement for JavaScriptリリースノートを参照して [ください](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/appmeasurement-updates.html)。

#### Analytics ヘルプリソース

* [Adobe Analytics チュートリアル](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 製品ドキュメント](https://docs.adobe.com/content/help/ja-JP/analytics/landing/home.html)

## ![アイコン](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager の新機能、修正点、ドキュメントおよびチュートリアルです。

更新日：**2020 年 6 月 11 日**

### ユーザーインターフェイスの更新

Audience Manager では、エクスペリエンスを向上し、他の Experience Cloud アプリケーションと統合するために、ドメインおよびヘッダーバーが更新されます。

* 組織間または別のアプリケーション間の切り替えが容易になりました。
* ヘルプメニューの特集記事やコンテキストの関連するビデオなど、ユーザーヘルプが強化されました。
* Experience Platform およびファイルサポートチケットに関するフィードバックを提供する機能が追加されました。
* 新しいより簡単な URL パターン。新しい URL、`experience.adobe.com/audience-manager` にブックマークを更新してください。

これらの更新は、Adobe ID を使用してログインしているユーザーのみ利用できます。Adobe ID ログインに切り替えるには、[Experience Cloud ユーザーと製品の管理](https://docs.adobe.com/content/help/ja-JP/core-services/interface/manage-users-and-products/admin-getting-started.html)を参照してください。

### Adobe Audience Manager の新機能および修正点

| 機能 | 説明 |
| -----------| ---------- |  
| [IAB TCF 用 Audience Manager プラグイン v2.0](https://docs.adobe.com/content/help/ja-JP/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | アドビでは、2020 年 6 月 11 日以降、IAB TCF 用 Audience Manager プラグインを IAB Transparency &amp; Consent Framework（TCF）バージョン 2.0 にアップグレードします。IAB TCF 用 Audience Manager プラグインを実装したお客様がこの機能を引き続き使用するには、2020 年 8 月 15 日までにバージョン 2.0 にアップグレードする必要があります。2020 年 8 月 16 日以降、バージョン 1.1 は非推奨となり、サポートは終了します。 |

**修正点**

* 特定の地域の法的要件を反映するように [!UICONTROL Audience Marketplace 利用条件]を更新しました。（AAM-54518）
* ブックマークから[!UICONTROL 特性]ページにアクセスすると 404 エラーが発生する問題を修正しました。（AAM-54768）
* [!UICONTROL アルゴリズムのモデル]の取得中に、宛先の更新 API がタイムアウトする問題が修正されました。（AAM-54342）
* ユーザーは、[!UICONTROL スマートペルソナ]のモデル分類精度インジケーターを表示できるようになりました。（AAM-54847）
* 特性式を追加した後に Enter キーを押すと、式が保存されずに削除される問題を修正しました。（AAM-54210）
* VIEW_MODELS 権限を持たないユーザーの場合に、[!UICONTROL 特定] API の GET メソッドに対する呼び出しが失敗する問題を修正しました。（AAM-53104）
* [!UICONTROL フォルダー特性]を含む[!UICONTROL アルゴリズムモデル]を削除できない問題を修正しました。（AAM-50192）
* 長い特性式が複数行にわたって折り返されるようになりました。（AAM-54972）
* 読み取り専用の権限を持つユーザーが、アルゴリズムモデルページに「[!UICONTROL 新規作成]」ボタンを表示できてしまう問題を修正しました。（AAM-54889）
* [!UICONTROL 一般]および[!UICONTROL トレンド]レポートの読み込みインジケーターが、CSV のダウンロードが完了した後も回転し続ける問題を修正しました。（AAM-54571）
* [!UICONTROL セグメントビルダー]でセグメントに一括特性を追加できなかった問題を修正しました。（AAM-55033）
* インターフェイス全体で複数のアクセシビリティを改善しました。（-47269、AAM-、AAM-48966、AAM-48976、AAM-49369、AAM-49023、AAM-49042）

### 新しい Audience Manager コースとチュートリアル {#tutorials-aam}

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |  
| [Audience Manager の概要](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | コース | このコースでは、Audience Manager の基本と、それを使って解決できる問題について説明します。一般的な使用例と主な Audience Manager の用語およびと概念について説明します。 |
| [Audience Manager での ID の概要](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | ビデオチュートリアル | 内部プロファイルやプロファイルの結合、パートナーとの ID 同期など、Adobe Audience Manager による ID の管理方法について説明します。 |
| [LinkedIn の人ベースの宛先の概要と設定](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | コース | このビデオでは、LinkedIn への人ベースの宛先を作成するための概念と手順について説明します。人ベースの宛先に関する追加のビデオおよびドキュメントを基に構築されます。 |
| [ルールに基づく特性の作成](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | ビデオチュートリアル | Audience Managerインターフェイスの [!UICONTROL 特性ビルダー]を使用してルールベースの特性を作成し、リアルタイムのアクティビティを Audience Manager プロファイルに取り込む方法について説明します。 |
| [IAB TCF 2.0 用 Audience Manager プラグインの有効化](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | ビデオチュートリアル | IAB TCF 用 Audience Manager プラグインを有効にする方法について説明します。Adobe Experience Platform Launch を使用している場合は、このプラグインは簡単に有効化できます。 |
| [IAB TCF 2.0 用 Audience Manager プラグインのデモ](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | ビデオチュートリアル | このビデオでは、Experience Cloud ID サービスおよびソリューションの cookie とビーコンが、IAB ユーザーによる選択の影響を受けるしくみについて説明します。 |

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品のアップデート

* **AEM 6.5.5.0**

   AEM 6.5、Service Pack 5（2020 年 6 月 5 日リリース 6.5.5.0）は、2019 年 4 月の AEM 6.5 の一般リリース以降にリリースされた新機能、お客様向けの主な機能強化、パフォーマンス、安定性、セキュリティの向上を含む重要なアップデートです。

   * [リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [AEM Forms リリース成果物](https://helpx.adobe.com/jp/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4、Service Pack 8、Cumulative Fix Pack （2020 年 6 月 4 日リリース）は重要なアップデートです。2020 年 3 月の AEM 6.4、Service Pack 8（6.4.8.0）の一般リリース以降におこなわれた複数の内部修正やお客様向けの修正が含まれています。

   * [リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-64/release-notes/cfp-release-notes.html)
   * [AEM Forms リリース成果物](https://helpx.adobe.com/jp/aem-forms/kb/aem-forms-releases.html)

### セルフサービス

* **AEM as a Cloud Service**

   AEM as a Cloud Service の新機能には何がありますか？

   主な機能は次のとおりです。

   * AEM Sites コマース統合フレームワーク。
   * スマートタグが強化され、UI のガイド付きトレーニングエクスペリエンスが新たに追加されました。
   * Adobe XD 向け Adobe Asset Link のサポート。
   * AEM Assets Dynamic Media 3D のサポート。
   * 新しいセルフサービスの強化により、サンドボックス操作に対するアドビへの依存性が軽減されました。
      * Cloud Manager のセルフサービスサンドボックスのサポートが強化され、権利を付与されたユーザーはサンドボックス内のすべての環境を削除してクレジットを受け取ることができるようになりました。
      * 自動休止サンドボックス環境は、無操作状態が続くと、自動的にサンドボックスを「休止」します。お客様は、「休止解除」を積極的にトリガーできます。
   * クラウドアクセラレーションをサポートするトランジションツール。

   オンプレミスから Cloud Service へのトランジションにかかる時間とコストを削減するため、今月 2 つのトランジションツールが立ち上げられました。これらのツールは、トランジションプロセス中の主要タスクの一部を自動化するように設計されており、結果として、全体的な作業を削減します。

   1. [コンテンツ転送ツール](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html)（SD で利用可能）を使用すると、コンテンツ転送アクティビティが効率化され、拡張性が向上します。ユーザーにわかりやすい UI を備えたこのツールは、既存のお客様およびパートナー（オンプレミス/AMS）が AEM as a Cloud Service に変換される既存の顧客やパートナー（オンプレミス／AMS）用のセルフサービスです。
   1. AMS Dispatcher 設定から Cloud Service Dispatcher 設定への変換を自動化する [AMS Dispatcher コンバーター](https://github.com/adobe/aem-cloud-service-dispatcher-converter)（オープンソース）ツール。

   [AEM as a Cloud Service 2020.6.0 のリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   トランジションツール：

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **コアコンポーネント**

   コアコンポーネント 2.9.0 では、[Adobe Client Data Layer](https://github.com/adobe/adobe-client-data-layer) と新しいプログレスバーコンポーネントの統合を導入し、[オーサリングドキュメント](https://docs.adobe.com/content/help/ja-JP/experience-manager-core-components/using/introduction.html)および [GitHub で入手可能な オーサリングドキュメント開発者の詳細](https://github.com/adobe/aem-core-wcm-components)とともにリリースしました。

* **AEM as a Cloud Service への移行**

   [AEM as a Cloud Service への移行](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/moving/home.html)では、既存の AEM の顧客が Cloud Service に移行する際に推奨されるトランザクションのジャーニーについて説明します。このドキュメントの目標は、お客様がこのトランジションに備え、構造化された予測可能な方法でこのジャーニーを作成できるように、情報、ガイダンス、ベストプラクティスを提供することです。

   クラウドトランジションツールの 1 つであるコンテンツ転送ツールがリリースされました。[コンテンツ転送ツール](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html)は、アドビが開発し、既存のコンテンツをソース AEM インスタンス（オンプレミスまたは AMS）からターゲット AEM as a Cloud Service インスタンスに移動するためのものです。

   コードリファクタリングツールの 1 つである AEM Dispatcher コンバーターがリリースされました。[AEM Dispatcher コンバーター](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html)は、既存の AEM Dispatcher 設定を AEM as a Cloud Service Dispatcher 設定に変換するユーティリティです。

* **アクセシビリティと WCAG 2.1 ガイドライン**

   WCAG 2.1 ガイドラインに関する更新事項：

   * [Adobe Experience Manager as a Cloud Service と Web アクセシビリティのガイドライン](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [WCAG 2.1 クイックガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [アクセシブルなコンテンツ（WCAG 2.1 適合）の作成 ](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **AEM ニュースレター**

   Experience League による AEM ニュースレターは、AEM の概要を短期間で習得して、すぐに価値を実現できるようにすることを目的としています。次に、最新のニュースレターを示します。

   * [Volume 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html)：Experience Manager はクラウドサービスとして使用できるようになりました。
   * Experience Insider ニュースレターを[購読](https://adobeeventsonline.com/AEM/2017/NL/Optin/)してください。
   * Adobe Experience Manager 6.5 ラーニングとサポートページの [AEM リソース](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)節でニュースレターのアーカイブを表示できます。

### **コミュニティ**

* **AEM コミュニティのディスカッション**

   AEM のすべてのお知らせと、内外のブロガーに対する興味深い言及を一か所で確認できます。AEM コミュニティの[ディスカッション](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)の節を参照してください。

### 新しい Experience Manager コースとチュートリアル

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |
| [Adobe Asset Link を使い始める（ビジネスユーザー向け）](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | コース | このコースでは、Adobe Asset Link の機能を使用して、Adobe Experience Manager アセットに保存されたコンテンツをクリエイティブなデザインに反映させる方法について説明します。このコースでは、アドビのアセットリンクの起動方法、基本的なアセット操作、検索および参照のオプション、他のユーザーとの効率的な共同作業方法など、あらゆる内容について説明します。 |
| [ビジネスユーザー向け AEM Assets の概要](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | コース | ビジネスユーザー向けの AEM Assets の使用開始方法を説明します。AEM Assets、コラボレーション機能、アセットの検索、編成、アセットとレンディションのダウンロードの基本について説明します。 |
| [AEM Sites を使い始める（ビジネスユーザー向け）](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | コース | AEM Sites の主な機能を使用して、組織の Web ページを管理する方法について学びます。このコースでは、AEM Sites の紹介、オーサリングの基本概念、高度なオーサリング機能、ページ管理機能など、あらゆる内容について説明します。 |
| [AEM プロジェクトの構造](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | 記事 | AEM Cloud Service との互換性を持たせるため、Adobe Experience Manager Maven プロジェクトに加える必要がある変更について説明します。 |
| [Sling Model](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | ビデオチュートリアル | スリングモデル Web コンソールを使用した、AEM as a Cloud Service SDK のローカルクイックスタートのデバッグについて説明します。 |
| [AEM Web コンソールのコンポーネント](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | ビデオチュートリアル | コンポーネント Web コンソールを使用した、AEM as a Cloud Service SDK のローカルクイックスタートのデバッグについて説明します。 |
| [ログを使用した AEM SDK のローカルクイックスタートのデバッグ](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | ビデオチュートリアル | バンドル Web コンソールを使用した、AEM as a Cloud Service SDK のローカルクイックスタートのデバッグについて説明します。 |
| [Cloud Service SDK のローカルクイックスタートとしての AEM のリモートデバッグ](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | ビデオチュートリアル | IDE からのリモート Java デバッグについて学習します。AEM でのライブコードの実行手順を進め、実行フローを正確に理解できます。 |
| [スマートタグの設定](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | ビデオチュートリアル | Adobe I/O を使用して Adobe Experience Manager（AEM）とスマートコンテンツサービスを統合する手順を説明します。 |
| [ドキュメントのバッチ生成](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | 記事 | バッチ API を使用して、テンプレートから複数のインタラクティブな通信を作成する方法について説明します。 |
| [AEM Forms での印刷チャネルドキュメントの作成](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | 記事 | 印刷チャネル用のインタラクティブな通信を作成するために必要な手順を説明します。 |
| [Adobe Asset Link へのアクセス](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | ビデオチュートリアル | Creative Cloud デスクトップアプリケーションを使い慣れている場合でも、Adobe Experience Manager アセット（AEM Assets）保存されたコンテンツにアクセスする方法について説明します。 |
| [Asset Link パネルの概要](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | ビデオチュートリアル | Adobe Asset Link を使用すると、クリエイティブユーザーは、InDesign、Photoshop および Illustrator のアプリケーション内パネルを使用して、AEM Assets に保存されたアセットを参照、検索、チェックアウトおよびチェックインできます。Adobe Asset Link パネルの UI とその機能について説明します。 |
| [アセット検索](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | ビデオチュートリアル | クリエイティブユーザーは、キーワードを使用して AEM Assets に保存されているアセットを検索したり、特定の場所で検索を実行したりできます。 |
| [ファイルのバージョン管理とコメント](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | ビデオチュートリアル | Adobe Asset Link パネルを使用すると、AEM Assets 内のアセットに関するファイルの詳細（サムネール、基本メタデータ、バージョン）にパネル内からアクセスできます。 |
| [チェックインとチェックアウト](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | ビデオチュートリアル | Adobe Asset を使用すると、作業中のクリエイティブアプリケーションから AEM Assets を直接チェックアウトでき、すぐに編集を開始できます。 |
| [AEM Assets 用の For Placement Only レンディション](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | ビデオチュートリアル | AEM Assets 用の For Placement Only（FPO）レンディションの作成方法と使用方法について説明します。 |
| [コピーを配置](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | ビデオチュートリアル | 「コピーを配置」操作を使用して AEM Assets のアセットを使用する方法について説明します。 |
| [ダウンロードとアップロード](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | ビデオチュートリアル | Asset Link パネルを使用して、AEM Assets でアセットファイルのダウンロードとアップロードをおこなう方法について説明します。 |
| [ファイルとコレクション](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | ビデオチュートリアル | Asset Link パネルから AEM Assets ファイルやコレクションへとすばやく簡単にアクセスする方法について説明します。 |
| [ダウンロード](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | ビデオチュートリアル | アセットとそのレンディションをローカルマシンにダウンロードして、使用および共有する方法について説明します。 |

### その他のリソース

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/jp/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/ja-JP/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://docs.adobe.com/content/help/ja-JP/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre リリースノート](https://docs.adobe.com/content/help/ja-JP/livefyre/using/release-notes/c-rn.html)

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 新しい製品リリース

[Adobe Campaign Classic 20.2 リリース](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html)には、以下が含まれます：

* _絵文字のサポート_ - _Azure Synapse FDA コネクタ_ - _新しいプライバシー規制_
* キャンペーンコントロールパネル：[アクティブなプロファイル監視](https://docs.adobe.com/content/help/ja-JP/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### 新しい Campaign コースとチュートリアル

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |  
| [Adobe Campaign Standard の概要（ビジネスユーザー向け）](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | コース | インターフェイスをナビゲート、配信を操作、受信者データを作成および管理する方法について説明します。 |
| [Adobe Campaign クライアントのインストールとセットアップ](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | ビデオ | Adobe Campaign クライアントコンソールをダウンロードしてインストールする方法、複数の環境への接続を作成して管理する方法、および Adobe Campaign クライアントコンソールへのアクセスの検証方法について説明します。 |

### ヘルプリソース

* Adobe Campaign Standard：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/campaign-standard-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/overview.html) - [リリース計画](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-planning.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/campaign-classic-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/documentation-updates.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/control-panel/using/release-notes.html)- [Campaign Standard](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) のハウツービデオ

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Advertising Cloud DSP の新機能](#adcloud-dsp)
* [Advertising Cloud Search の新機能](#adcloud-search)

### Advertising Cloud DSP の新機能 {#adcloud-dsp}

更新日：**2020 年 6 月 24 日**

| 機能 | 説明 |
| -----------| ---------- |
| ドメインの移行 | （6 月 23 日リリース）Advertising Cloud DSP は、https://www.tubemogul.com から [https://advertising.adobe.com](https://advertising.adobe.com) に移行されました。 |
| Adobe Analytics の統合 | （6 月 19 日リリース）オプションとして、DSP で、Analytics に送信するデータから AMO コスト指標を抑制できるようになりました。指標を抑制しない場合は、アドビのアカウントマネージャーにお問い合わせください。 |
| 人物ベースのデバイスグラフ | （6 月 23 日リリース）セルフサービス DSP のお客様は、任意の新しいキャンペーンをまたいでユーザーベースのターゲティングと頻度管理をおこなう際に、デバイスグラフ（Adobe Experience Cloud Device Co-op または LiveRamp）を利用できるようになりました。これにより、所有するデバイス間でオーディエンスに到達して、ユーザーの広告公開を制限できます。 |
| CCPA オプトアウトオブセール | （6 月 23 日リリース）新しい CCPA オプトアウトオブセールセグメントを使用して、CCPA オプトアウトオブセールの要求を Advertising Cloud に伝えられるようになりました。このセグメントは、[!UICONTROL オーディエンス／セグメント]から作成できます。また、a）[!UICONTROL オーディエンス／セグメント]から、または b）Advertising Cloud トラフィック指定 API を使用して、顧客がアカウントに対してオプトアウトオブセールのリクエストとして送信した ID の月別レポートを取得できます。詳しくは、https://docs.adobe.com/content/help/en/advertising-cloud/all/privacy/ad-cloud-ccpa-opt-out-of-sale.html を参照してください。 |
| DoubleVerify Authentic Brand Safety | （6 月 23 日リリース）広告主は、DoubleVerify での入札後のブロックルールを模倣できる包括的な Brand Safety フィルターを使用して、入札前に単一の DoubleVerify セグメント ID をターゲットに設定できるようになりました。これは、[!UICONTROL 設定／広告主]で、広告主設定の「メディア品質のターゲティング」セクションでおこなえるようになりました。このサービスについて詳しくは、programmaticsales@doubleverify.com にお問い合わせください。この機能には追加料金が適用されます。 |
| CPA/ROAS の最適化 | （5 月 20 日リリース）Campaign 管理者は、予算の割り当て超過を防ぐために、パッケージ内の新しい配置を制限する必要がなくなりました。配置には、CPM または CPA／ROAS のパフォーマンスに基づいた動的な予算配分が適用されるようになりました。 |
| [!UICONTROL Campaign] ホーム | （6 月 3 日リリース）提供されたキャンペーン予算と経過時間に基づいた、新しいキャンペーンレベルのペーシング指標を利用できます。 |
| [!UICONTROL 配置] | （6 月 23 日リリース）サイトの多様性とプレイヤーのサイズのフィルターが削除され、配置の設定が簡単になりました。 |
| 配置の予測 | （6 月 3 日リリース）配置レベルで最適化をおこなう CTV およびビデオ配置の場合、配置設定に複数の広告の長さ（15 秒および 30 秒）の予測が含まれるようになりました。また、VAST と VPAID の両方の在庫に対する予測も含まれます。 |
| [!UICONTROL 在庫] | （6 月 23 日のベータリリース）新しい取引 ID フォームを使用すると、既にネゴシエート済みの個人取引をすばやく設定できます。 |
|  | （6 月 23 日ベータ版リリース）VAST インベントリでインタラクティブプリロールを利用できるようになりました。単一のインタラクティブプリロール広告と配置を設定して、広告と配置の数を減らすことができます。 |
| ACTV オーディエンスレンズ | （6 月 19 日リリース）オーディエンスレンズを使用すると、セカンダリオーディエンスの読み取りを作成して、計画、注文、レポートワークフローに適用できます。これにより、（1）セカンダリオーディエンスに対する迅速なインサイトを得て、（2）希望するオーディエンス上で柔軟に取引し、（3）複数のオーディエンスの「レンズ」を通してキャンペーンの実行を測定することができます。 |

### [!UICONTROL Advertising Cloud Search] の新機能 {#adcloud-search}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL Campaigns] | Microsoft Advertising（旧称 Bing Ads）では、2020 年 10 月 1 日以降、平均順位指標は非推奨となります。これに備え、7 月 11 日から位置に基づく制約は無視され、すべてのタイプの制約で、位置に基づく条件が無視されるようになります。 |
| [!UICONTROL 広告インサイト] | （6 月 14 日リリース）次のインサイトが削除されました。<br/><br/><ul><li>Audience Target のパフォーマンス（新しいバージョン）</li><li>過去のパフォーマンス（新しいバージョン）</li><li>一致タイプ（新しいバージョン）</li><li>監査の設定（新しいバージョン）</li><li>ポートフォリオの事前投稿（レガシー）</li></ul><br/>残りのインサイトは従来のバージョンで、「_レガシー_」ラベルは名前から削除されました。さらに、ライブ／編集モードが削除されました。 |

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

Magent リリースノートについては、以下を参照してください。

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![アイコン](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーの各ステージを通じてエンゲージメントをおこなうことで顧客体験を変えようとしているリード管理や B2B マーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

最新のリリース情報については、[!DNL Marketo] [リリースノート](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)を参照してください。

### 予定されている機能

今四半期を通じて、次の機能がリリースされます。

| 機能 | 説明 |
|------|---------|
| [!DNL Bizible] | <ul><li>新しいアカウントベースのセグメント化</li><li>ダッシュボード固有のフィルターの保存</li><li>Bizbile ダッシュボードを PDF 形式で書き出し</li></ul> |
| Sales Connect | ウィンドウとコマンドセンターの構成の更新／機能強化 |

### 発表

**Marketo Engage サクセスセンター：** 2020 年 2 月に立ち上げ予定。サクセスセンターは製品内ヘルプセンターで、製品ドキュメントとコミュニティの検索、ハウツーガイドの起動、導入コンテンツへのアクセスなどをおこなうことができます。注意：この機能は ANZ でベータ版として開始され、四半期の後半に北米で公開予定です。

### 廃止

* **アセットAPI &quot;_method&quot; パラメーター：** 2020 年 9 月以降、アセット API エンドポイントでは、URI の長さ制限を回避するために、POST 本文にクエリパラメーターを渡す `_method` を使用できなくなります。
* **Internet Explorer のサポートの廃止：** 2020 年 7 月 31 日のリリース以降、Marketo Engage ユーザーインターフェイスは Internet Explorer でサポートされなくなります。

これまでのリリースノートと過去のリリースノートについては、[Marketo リリースノート](https://docs.marketo.com/x/CgA6Ag)を参照してください。

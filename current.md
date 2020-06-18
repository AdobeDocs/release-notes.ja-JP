---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: af0ded4b9a09349d811a998a002b0f1c0f72403f
workflow-type: tm+mt
source-wordcount: '6486'
ht-degree: 39%

---


# 早期アクセス — Adobe Experience Cloudリリースノート（2020年6月）

![バナー](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. また、Experience Cloudを最大限に活用するための新しいドキュメント、トレーニングコース、ビデオチュートリアルも紹介しています。

>[!IMPORTANT]
>
>このページに記載される内容は、リリース前の情報であり、リリース日の前後に変更される可能性があります。

>[!NOTE]
>
>[Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。

**リリース日：2020 年 6 月 18 日**

製品リリース日は異なる場合があります。 頻繁にチェックバックして更新を確認してください。

Latest update: **June 15, 2020**

* [Adobe システムステータス](#status)
* [Experience Cloud インターフェイス](#ecloud)
* [Experience Platform](#platform)
* [ジャーニーオーケストレーション](#journey-orch)
* [Analytics](#analytics) (および [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/ja-JP/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/jp/primetime/user-guide.html)（Primetime のヘルプページへのリンク）

サポートが必要な場合は、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、クイックアンサー、コミュニティインサイト [](https://experienceleague.adobe.com/#home) 、講師が指導するトレーニングを見つけるには、Adobe Experience Leagueを参照してください。

## ![アイコン](/assets/adobe.png) Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

リリース済み： **2020年5月21日**

**最新情報**

* Adobe ID を使用して、製品オファーやアドオンレベルまで掘り下げた、より精度の高いイベント通知を登録できます。購読をよりすばやく設定するのを支援するために、セルフサブスクリプションプロセスで、製品の使用権限に基づいてお勧めの製品およびサービスが表示されるようになりました。これにより、受信する電子メールの数が減り、より関連性の高い通知をインボックスに配信できます。はじめに [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit) をご覧ください。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| 購読と通知に関するユーザーエクスペリエンスを改善 | <ul><li>[!DNL Marketo Engage] の地域は、選択した製品やサービスのリストに基づいてフィルタリングされるようになりました。</li><li>[!DNL Marketo Engage] の電子メール通知は、ユーザーの地域、場所および環境の設定に関連します。</li></ul> |
| イベント購読の確認 | <ul><li>進行中の単一イベントの更新を購読する際に、電子メールによる確認を受け取れるようになりました。</li></ul> |
| グローバルナビゲーションのユーザビリティの強化 | <ul><li>`Adobe.com` のトップレベルナビゲーションメニューの操作の一貫性が向上しました。</li></ul> |

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud インターフェイス {#ecloud}

Experience Cloudインターフェイスの一般的な更新。

**統合製品ドメイン**

アドビでは、すべての Adobe Experience Cloud アプリケーションでエクスペリエンスを統合し、向上させるために、ドメインとインターフェイスのヘッダーを更新しています。これらの機能強化は、小規模ではあっても、重要な方法でエクスペリエンスをシンプルにするように設計されています。これらの機能強化では、現在のワークフローは変更されません。

更新内容は次のとおりです。

* 新しいアプリケーション URL：`experience.adobe.com/<application name>`：
   * すべての製品で、最終的にこの URL パターンが採用されます。1 か月間にわたって効果的な新しい URL を探します。
   * ブラウザーのサポート：サポートされるブラウザーには、[!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari]、および [!DNL Opera]（最新バージョン）が含まれます。**注意：** Experience Cloudインターフェイスはこれらのブラウザーをサポートしていますが、個々のアプリケーションがすべてのブラウザーをサポートしているとは限りません。 （例えば、[Analytics](https://docs.adobe.com/content/help/ja-JP/analytics/admin/sys-reqs.html) は [!DNL Opera] をサポートしておらず、[Target](https://docs.adobe.com/help/ja-JP/target/using/implement-target/before-implement/supported-browsers.html) は [!DNL Safari] をサポートしていません）。
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

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

リリース日：**2020 年 6 月 10 日**

[!DNL Adobe Experience Platform] には、次の新機能が含まれています。

* **Data Science Workspace:** には、リアルタイム機械学習（アルファ）用の [!DNL JupyterLab Launcher][!DNL Python] ノートブックスターターが含まれるようになりました。
* **セグメント：** 日付関数の「記念日」フィールドが追加され、年を含まない日付を評価できるようになりました。
* **資料：** および用の新しいソースコネクタ [!DNL Apache HDFS] で [!DNL Couchbase]す。

これらの機能について詳しくは、「 [Experience Platformリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)」を参照してください。

### その他の Experience Platform のリリース情報

* [Experience Platform Launchのリリースノート](https://docs.adobe.com/content/help/ja-JP/launch/using/intro/release-notes/current.html)
* [セキュリティ速報および情報](https://helpx.adobe.com/jp/security.html)（すべてのアドビ製品）

### 新しいExperience Platformコースとチュートリアル {#tutorials-plat}

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |
| [Adobe Experience Platformの概要](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | コース | データを各チャネルでアクティブ化できる堅牢なリアルタイムの顧客プロファイルとAIに基づくインサイトに変換することで、Adobe Experience Platformが適切なエクスペリエンスを提供する方法を説明します。 この入門レベルのコースでは、Experience Platformの機能、使用例、Adobe Experience Cloudとの関係、基本的なアーキテクチャ、インターフェイス、プロジェクトの役割について概要を説明します。 |
| [Web SDKとEdgeネットワークの概要](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | ビデオチュートリアル | Adobe Experience PlatformSDKとEdge Networkの概要を示します。 Experience PlatformWeb SDKは、1つのJavaScriptライブラリ、1つのビーコンタイプ、1つのデータストリーム、1つのサーバー側宛先を使用して、すべてのアドビアプリケーションとサードパーティの宛先にデータを送信できるクライアント側のJavaScriptライブラリです。 |
| [Web SDKとEdgeネットワークのデモ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | ビデオチュートリアル | Adobe Experience Platform、Analytics、Audience ManagerおよびTargetにデータを送信するアドビへの1回の呼び出しで、Experience PlatformのWeb SDKおよびEdgeネットワークの動作を視聴します。 |
| [リアルタイム顧客データPlatformのデモ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | ビデオチュートリアル | リアルタイムCDPを使用して複数のソースからデータを収集する方法を説明します。 このデータを1つのリアルタイム顧客プロファイルに統合し、そのデータをアクティブ化して、パーソナライズされた顧客エクスペリエンスを作成できます。 |

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Adobe Experience Platform を使用すると、それぞれの顧客のニーズをリアルタイムでインテリジェントに予測し、どのようなジャーニーをたどっていても、個別カスタマージャーニーをエクスペリエンスチャネル全体で大規模に編成することができます。

### 最新リリース

最新のリリースのアップデートについて詳しくは、 [Journey Orchestrationリリースノートを参照してください](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html)

### 新しいJourney Orchestrationコースとチュートリアル {#jo-tutorials}

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |
| [管理者向けJourney Orchestration — はじめに](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | コース | Journey Orchestrationを設定および使用する方法について説明します。 このコースでは、主要な概念と、旅のオーケストレーションを有効にするために必要な設定手順について説明します。 調整されたジャーニーを作成、投稿、レポートおよび分析する方法について説明します。 |
| [ビジネスユーザー向けJourney Orchestrationの概要](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | コース | Journey Orchestrationを設定および使用する方法について説明します。 このコースでは、主な概念について説明します。 調整されたジャーニーを作成、投稿、レポート、分析する方法を学びます。 |

### Jargeny Orchestration の追加リソース

[ドキュメント](https://docs.adobe.com/content/help/ja-JP/journeys/using/journey-orchestration-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Updated **June 10, 2020**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Media Analytics](#media-aa) の新機能です。
* [アドビAnalyticsの修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [新しいアドビAnalyticsコースとチュートリアル](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | [一般公開](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| -----------| ---------- |-------|
| アトリビューションIQ: アルゴリズムアトリビューション | 2020 年 6 月 19 日 | Analysis Workspaceの [!UICONTROL アルゴリズムアトリビューション] モデルでは、統計的手法を使用して、選択した指標に対する最適なクレジットの配分を動的に決定します。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| アトリビューションIQ: カスタムのルックバックウィンドウ | 2020 年 6 月 19 日 | アトリビューションIQ  の任意のアトリビューションモデルを設定して、レポート期間の最大90日前のタッチポイントを含めることができるようになりました。 これは、通常、前月に発生したインタラクションを考慮することで、レポートの初期に発生するイベントのアトリビューション精度を高めます。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| 共有Workspaceプロジェクトのプロジェクトロール | 2020 年 6 月 19 日 | Workspaceプロジェクトを共有する際、受信者を、使用するプロジェクトの経験に応じて、次の3つのプロジェクトの役割のいずれかに配置できるようになりました。 編集、重複、表示。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 表示のみのWorkspaceプロジェクト | 2020 年 6 月 19 日 | Workspaceプロジェクトは、「表示可能」としてのみユーザーに共有できます。 表示受信者が共有プロジェクトを開くと、より制限の多いプロジェクト操作が得られ、左側のレールも操作の制限もありません。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Workspaceプロジェクトの共同編集機能 | 2020 年 6 月 19 日 | 「編集可能」ロールに追加された受信者は、共有されたプロジェクトを保存できます。 これは、管理者と非管理者の両方に適用されます。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Workspaceの空白パネルの更新 | 2020 年 6 月 19 日 | Workspaceの空のパネルにパネルとビジュアライゼーションが追加され、最適な分析ワークフローをよりシームレスに選択できるようになりました。 |
| 中国のRDCで使用可能なファーストパーティドメイン | 2020 年 6 月 19 日 | ドメインを持つお客様が、中国本土内での使用をファーストパーティドメインにリクエストできるようにします。 `.cn` （「中国パフォーマンス最適化」 SKUの購入時に入手可能なドキュメント） |
| ワークスペースのクイックインサイトパネル | 2020 年 6 月 26 日 | クイックインサイトは、Analysis Workspace のアナリスト以外のユーザーと新規ユーザーに対して、ビジネスの質問にすばやく簡単に答える方法を学ぶためのガイダンスを提供します。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| ワークスペース の Analytics for Target パネル | 2020 年 6 月 26 日 | Target用Analytics(A4T)パネルを使用すると、Adobe Targetのアクティビティとエクスペリエンスを、上昇率と信頼性を持つAnalysis Workspaceで分析できます。 [詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | [一般公開](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| -----------| ---------- |-----|
| アトリビューションIQ: [!UICONTROL アルゴリズムアトリビューション] | 2020 年 6 月 19 日 | [!UICONTROL Analysis Workspaceの] アルゴリズムアトリビューション  モデルでは、統計的手法を使用して、選択した指標に対するクレジットの最適な配分を動的に決定します。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| アトリビューションIQ: カスタムのルックバックウィンドウ | 2020 年 6 月 19 日 | アトリビューションIQ  の任意のアトリビューションモデルを設定して、レポート期間の最大90日前のタッチポイントを含めることができるようになりました。 これは、通常、前月に発生したインタラクションを考慮することで、レポートの初期に発生するイベントのアトリビューション精度を高めます。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| [!UICONTROL 異常値検出のサポート] | 2020 年 6 月 19 日 | [!UICONTROL 異常値検出は、以前のデータに関連して特定の指標がどのように変化したかを判定するための統計的手法です。][詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| 共有 [!UICONTROL Workspace] プロジェクトのプロジェクトロール | 2020 年 6 月 19 日 | [!UICONTROL Workspace] プロジェクトを共有する際に、受信者を、使用するプロジェクトの経験に応じて、次の3つのプロジェクトの役割のいずれかに配置できるようになりました。 編集、重複、表示。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 表示のみの [!UICONTROL Workspace] プロジェクト | 2020 年 6 月 19 日 | [!UICONTROL Workspace] プロジェクトは、 _[!UICONTROL Can表示のみとしてユーザーに共有できます]_。 表示受信者が共有プロジェクトを開くと、左側のパネルがなく、操作が制限される、より厳しいプロジェクト操作を受け取ります。[詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Workspace [!UICONTROL プロジェクトの共同編集] | 2020 年 6 月 19 日 | 「編集 _[!UICONTROL 可能]_」ロールに追加された受信者は、共有されているプロジェクトに保存できます。[詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| [!UICONTROL ワークスペース]のクイックインサイトパネル | 2020 年 6 月 26 日 | クイックインサイトは、[!UICONTROL Analysis Workspace] のアナリスト以外のユーザーと新規ユーザーに対して、ビジネスの質問にすばやく簡単に答える方法を学ぶためのガイダンスを提供します。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/panels/quickinsight.html) |

### [!UICONTROL Media Analytics] の新機能です。{#media-aa}

更新日：**2020 年 5 月 30 日**

**プレイヤー状態の追跡：** [!UICONTROL Media Analytics] のお客様は、標準的なソリューション変数のセット（フルスクリーン、クローズドキャプション、ミュート、ピクチャインピクチャ、インフォーカス）を使用して、再生中の閲覧者のインタラクションをキャプチャできます。また、カスタムプレーヤー状態を柔軟に作成することもできます。[!UICONTROL Analysis Workspace] のレポートで、プレイヤー状態追跡変数を使用できるようになりました。この機能を使用するには、次のいずれかが必要です。

* Media [!DNL JavaScript] SDK 3.0 以降
* [!DNL Adobe Experience Platform]（AEP）SDK で使用する場合：
   * [!UICONTROL Media Analytics 拡張機能]（Web 用）：[!UICONTROL Adobe Media Analytics]（3.x SDK）for Audio および Adobe Media Analytics for Video v1.0 以降
   * [!UICONTROL Media Analytics Extension]（モバイル用）：[!UICONTROL Adobe Media Analytics for Audio] および Adobe Media Analytics for Video v2.0 以降
* [!UICONTROL メディアコレクション]

[プレイヤーステートトラッキングについて](https://docs.adobe.com/content/help/ja-JP/media-analytics/using/player-state-tracking/player-state-overview.html)を参照してください。

### アドビAnalyticsの修正点 {#aa-fixes}

* 特定のレポートスイートに対してマルチバイト検索を行うセグメントが何も一致しない問題を修正しました。 現在は、正しい文字列と一致します。 （AN-220043）
* 「 [!UICONTROL レポートとAnalytics] 」の「 [!UICONTROL 項目フィルタ] 」が機能しない問題を修正しました。 （AN-206132）
* スケジュールされたプロジェクト [!UICONTROL インターフェイスの応答時間の遅さを修正] 。 （AN-214837）
* AnalyticsレポートAPI 2.0で日付範囲エラーが発生する問題を修正しました。 （AN-215087）
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. これは、ディメンションの値を持たないヒット（Pagenameなど）が同じ秒に続いた場合に発生します。 （AN-211074）
* ユーザーが共有している [!UICONTROL Workspace] プロジェクトにアクセスできない問題を修正しました。 （AN-217561）
* キーが [!UICONTROL 分類ルールビルダーで分類されない問題を修正しました]。 （AN-221538）
* 「 [!UICONTROL サーバーコールの使用状況] 」で使用状況データがレポートされない問題を修正しました。 （AN-210452）
* 公開したAdobe ServerセグメントでAudience Managerにデータがない問題を修正しました。 （AN-220208、AN-220659）
* レポートにデータが表示されるが、 [!UICONTROL データフィード] (ログには「Data warehouseデータがありません」と表示されていた問題を修正しました。 （AN-220784、AN-220858）
* ド [!UICONTROL メインからの起動を妨げていた]`experiencecloud.com` Ad hoc analysis問題を修正しました。 （AN-219680、AN-221629）
* 「Ctrl（またはCommand）+ C」ホットキーの使用に関する問題を修正しました。 （AN-221101、AN-221537）
* [!UICONTROL Activity Map] 有効化ページの問題を修正しました。 （AN-222029、AN-221242）
* フォールアウトビジュアライゼーションの途中にタッチポイントを追加できなかった問題を修正し [!UICONTROL ました] 。 （AN-221648）

#### その他の Adobe Analytics の修正点

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 統合製品ドメインへの移行 | 発効日：2020 年 5 月 29 日 | Adobe Analytics の統合製品ドメインへの移行は 2020 年 1 月に開始され、2020 年 5 月 29 日に完了しました。While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist (formerly, allowlist) `omniture.com` as a third-party cookie. アーキテクチャの完全な移行が（間もなく）完了したら、リリースノートからお知らせいたします。この許可リスト手順は必要ありません。 [許可リストが必要な推奨IPアドレスとドメインの完全なリストを以下に示します](https://helpx.adobe.com/jp/analytics/kb/adobe-ip-addresses.html) 。<br>組織がサードパーティ Cookie をブロックしている場合は、カスタマーケアに連絡して、Adobe Analytics へのアクセスを再取得してください。 |
| 新しい Adobe Analytics のデフォルトランディングページ | 発効日：2020 年 6 月 19 日 | 2020 年 6 月 19 日に、Adobe Analytics のデフォルトのランディングページが[!UICONTROL レポート]から [!UICONTROL ワークスペース] に変更されます。この変更は、過去にカスタムランディングページを設定していないユーザーに対して適用されます。 |
| サードパーティのテクノロジー許可リスト | 2020 年 3 月 13 日（発効日） | Adobe Analytics は、サードパーティのテクノロジーを活用して、機能のロールアウト管理と製品内サポートを開始しました。機能に完全にアクセスできるように、必要なネットワークファイアウォール許可リストに次のURLを追加する必要があります。<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 2020 年 5 月 22 日 | [!UICONTROL Analysis Workspaceの可用性を確保するために]、冗長性を高めるためにセカンダリCDN(コンテンツ配信ネットワーク)を追加しています。 必要なネットワークファイアウォール許可リストには、次のURLを追加する必要があります。<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| [!UICONTROL ワークスペース] での[!UICONTROL 入口／出口]の計算方法の変更 | 2020 年 4 月 8 日 | 2020 年 3 月の時点で、[!UICONTROL Analysis Workspace] における「_なし_」の値と[!UICONTROL 入口／出口]との相互作用を変更しました。[!UICONTROL Analysis Workspace] で「_なし_」をオン／オフにできるようになったので、入口または出口の後に「_なし_」を適用します。（eVar の場合）以前は、これらの前に適用されていました。例えば、訪問の最初のヒットに eVar の値がないが、2 回目のヒットに eVar の値があるとします。[!UICONTROL Reports &amp; Analytics] では、最初のヒットがそのエントリに対して「_未指定_」と表示されますが、[!UICONTROL Analysis Workspace] では 2 回目のヒットの値が表示されます。 |
| **[!UICONTROL ダッシュボードアーカイブ]**&#x200B;のサービス終了 | 2020 年 3 月 28 日 | [!UICONTROL Reports &amp; Analytics] の「**[!UICONTROL ダッシュボードを管理]**」の「**[!UICONTROL アーカイブを表示]**」設定は、2020 年 10 月から使用できなくなります。 |
| 提供終了 - Analytics レガシー API | 2020 年 1 月 10 日 | 2020 年 11 月に、以下の Analytics レガシー API サービスが提供終了となり、シャットダウンされます。これらのサービスを使用して構築された現在の統合は機能しなくなります。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問に対する回答と進め方に関するガイダンスを提供するために、[従来の API EOL の FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis のサポート終了 | 2018 年 8 月 7 日 | アドビは Ad Hoc Analysis のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。詳しくは、[Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) を参照してください。 |

#### 新しいAnalyticsコースとチュートリアル {#tutorials-analytics}

AnalyticsとCustomer Journey Analyticsの新しいコース、チュートリアルビデオ、記事。

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- | 
| [Customer Journey Analytics使用の手引き](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | コース | このコースでは、Customer Journey Analytics(CJA)を使用して様々なデータソースのデータを分析する方法を学びます。 アドビのAnalyticsとCustomer Journey Analyticsの違い、およびCJAでのデータの処理方法について学習します。 このコースを受講した後は、クロスチャネルのビジュアライゼーションを作成およびカスタマイズして、顧客の理解を深めることができます。 |
| [管理者向けCustomer Journey Analytics — はじめに](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | コース | [!UICONTROL Journey Orchestrationを設定および使用する方法を説明します]。 このコースでは、ジャーニーの調整を有効にするために必要な主要概念と構成手順について説明します。 ここでは、調整されたジャーニーを作成、公開し、レポートおよび分析する方法について学びます。 |
| [データエンジニア向けCustomer Journey Analyticsの概要](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | コース | このコースでは、Customer Journey Analyticsに入るデータと、そのデータがアナリストのレポートに与える影響について学びます。 このコースは、Adobe Experience Platformに関する一般的な知識に基づいて構築されます。 |
| [管理者向けCustomer Journey Analytics — はじめに](https://video.tv.adobe.com/v/34349?captions=jpn) | ビデオチュートリアル | 管理者向けのCustomer Journey Analytics向けの紹介ビデオです。 |
| [ガイド付きAnalytics導入](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | コース | このコースでは、アドビAnalyticsの実装を開始する方法、Analyticsの概念を理解する方法、計画を作成する方法、Experience Platform Launchを使用したアドビAnalyticsの実装方法を学びます。 |
| [リーダー向けアドビAnalytics基本原則](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | コース | このコースでは、Analyticsの基本原則とAnalysis Workspaceがビジネスを変える方法について説明します。 Adobe Sensieの洞察を明らかにする方法、お客様の声を聞く方法、Summit 2019で業界の専門家から強みを得る方法を説明します。 |
| [Analysis Workspace使用の手引き](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | コース | Analysis Workspaceの使用を開始する方法を説明します。 最初のプロジェクトを作成し、日付範囲を定義し、セグメントを適用し、プロジェクトで共有および共同作業する方法を学びます。 |
| [AdobeAnalyticsダッシュボードスコアカードビルダー](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | ビデオチュートリアル | このビデオでは、アドビの [!UICONTROL Analyticsダッシュボード（モバイルアプリ）で表示する] Analysis Workspaceのスコアカードを作成して共有する方法 [!UICONTROL (] )を説明します。 |
| [AdobeAnalyticsダッシュボードのアプリ内エクスペリエンス](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | ビデオチュートリアル | このビデオでは、AdobeAnalyticsダッシュボード（モバイルアプリ）を使用して、自分が作成または共有した [!UICONTROL 表示スコアカードにアクセスする方法を説明します] 。 |

#### Analytics ヘルプリソース

* [Adobe Analytics チュートリアル](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 製品ドキュメント](https://docs.adobe.com/content/help/ja-JP/analytics/landing/home.html)

## ![Icon](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager の新機能、修正点、ドキュメントおよびチュートリアルです。

Updated **June 10, 2020**

### ユーザーインターフェイスの更新

Audience Manager では、エクスペリエンスを向上し、他の Experience Cloud アプリケーションと統合するために、ドメインおよびヘッダーバーが更新されます。

* 組織間または別のアプリケーション間の切り替えが容易になりました。
* ヘルプメニューの特集記事やコンテキストの関連するビデオなど、ユーザーヘルプが強化されました。
* Experience Platformおよびファイルサポートのチケットに関するフィードバックを提供する機能。
* 新しいより簡単な URL パターン。新しい URL、`experience.adobe.com/audience-manager` にブックマークを更新してください。

これらの更新は、Adobe ID を使用してログインしているユーザーのみ利用できます。Adobe ID ログインに切り替えるには、[Experience Cloud ユーザーと製品の管理](https://docs.adobe.com/content/help/ja-JP/core-services/interface/manage-users-and-products/admin-getting-started.html)を参照してください。

### Adobe Audience Manager の新機能および修正点

| 機能 | 説明 |
| -----------| ---------- |  
| [IAB TCF v2.0 用 Audience Manager プラグイン ](https://docs.adobe.com/content/help/ja-JP/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | アドビでは、2020 年 6 月 10 日より、IAB TCF 用 Audience Manager プラグインを IAB の透明性および同意フレームワーク（TCF）バージョン 2.0 にアップグレードします。IAB TCF 用 Audience Manager プラグインを実装したお客様がこの機能を引き続き使用するためには、2020 年 8 月 16 日までにバージョン 2.0 にアップグレードする必要があります。2020年8月15日以降、バージョン1.1は非推奨となり、サポートは終了します。 |

**修正点**

* 特定の地域の法的要件を反映するように [!UICONTROL Audience Marketplace利用条件] （英語）を更新しました。 （AAM-54518）
* ブックマークから [!UICONTROL 特性] ページにアクセスすると404エラーが発生する問題を修正しました。 （AAM-54768）
* アルゴリズムのモデルの取得中に宛先の更新APIがタイムアウトする問題が修正され [!UICONTROL ました]。 （AAM-54342）
* ユーザーは、 [!UICONTROL スマートパーソナのモデル分類精度インジケーターを表示できるようになりました]。 （AAM-54847）
* 特性式を追加した後にEnterキーを押すと、式が保存されるのではなく削除される問題を修正しました。 （AAM-54210）
* 表示 [!UICONTROL _MODELS権限を持たないユーザーで、] Traits APIのGETメソッドの呼び出しが失敗する問題を修正しました。 （AAM-53104）
* フォル [!UICONTROL ダーの特性を含む] アルゴリズムモデルを削除できない問題を修正しました 。 （AAM-50192）
* 長い特性式が複数行にわたって折り返されるようになりました。 （AAM-54972）
* 読み取り専用の権限を持つユーザーが、アルゴリズムによるモデルページに「 [!UICONTROL 新規作成] 」ボタンを表示できる問題を修正しました。 （AAM-54889）
* CSVのダウンロードが完了した後も、 [!UICONTROL 一般] / [!UICONTROL トレンド] レポートの読み込みインジケーターが回転し続ける問題を修正しました。 （AAM-54571）
* セグメントビルダーでセグメントにバルク特性を追加できなかった [!UICONTROL 問題を修正しました]。 （AAM-55033）
* インターフェイス全体で複数のアクセシビリティを改善しました。(AAM-47269、AAM-48966、AAM-48976、AAM-49369、AAM-49023、AAM-49042)。

### 新しいAudience Managerコースとチュートリアル {#tutorials-aam}

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |  
| [Audience Managerの概要](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | コース | このコースでは、Audience Managerの基本と、それを使って解決できる問題について説明します。 一般的な使用例と主なAudience Manager用語と概念について説明します。 |
| [Audience ManagerでのIDの概要](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | ビデオチュートリアル | 内部プロファイルやプロファイルの結合、パートナーとのID同期など、Adobe Audience ManagerがIDを管理する方法を説明します。 |
| [LinkedInの人ベースの宛先についてと設定](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | コース | このビデオでは、LinkedInへの人物ベースのリンク先を作成するための概念と手順について説明します。 これは、人ベースの宛先に関する追加のビデオおよびドキュメントに基づいて構築されます。 |
| [ルールに基づく特性の作成](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | ビデオチュートリアル | Audience Managerインターフェイスの [!UICONTROL 特性ビルダー] (Trait Builder)を使用してルールベースの特性を作成し、Audience Managerプロファイルにリアルタイムのアクティビティを取り込む方法について説明します。 |
| [IAB TCF 2.0用Audience Managerプラグインの有効化](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | ビデオチュートリアル | IAB TCF用Audience Managerプラグインを有効にする方法を説明します。 Adobe Experience Platform起動を使用している場合は、このプラグインを有効にするのは簡単です。 |
| [IAB TCF 2.0のAudience Managerプラグインのデモ](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | ビデオチュートリアル | このビデオでは、Experience CloudIDサービスおよびソリューションのcookieとビーコンがIABユーザー選択によってどのように影響を受けるかを確認します。 |

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品のアップデート

* **AEM 6.5.5.0**

   AEM 6.5、Service Pack 5（2020年6月4日にリリースされた6.5.0）は、新機能、お客様から要望のあった主な機能強化、パフォーマンス、安定性、セキュリティの向上を含む重要なアップデートです。2019年4月のAEM 6.5の一般リリース以降にリリースされました。

   * [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [AEM Forms リリース成果物](https://helpx.adobe.com/jp/em-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4、Service Pack 8、Cumulative Fix Pack （2020年6月4日リリース）は重要なアップデートで、2020年3月のAEM 6.4、Service Pack 8(6.4.8.0)の一般リリース以降に行われた内部およびお客様向けの修正が含まれています。

   * [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [AEM Forms リリース成果物](https://helpx.adobe.com/jp/em-forms/kb/aem-forms-releases.html)

### セルフサービス

* **AEM as a Cloud Service**

   Cloud ServiceとしてのAEMの新機能

   主な機能は次のとおりです。

   * AEM Sitesコマース統合フレームワークを参照してください。
   * スマートタグが強化され、UIのガイド付きトレーニングエクスペリエンスが新たに追加されました。
   * Adobe XdでのAdobe Asset Linkのサポート。
   * AEM AssetsDynamic Media3Dのサポート。
   * 新しいセルフサービスの強化により、サンドボックス操作に対するアドビへの依存性が低下しました。
      * Cloud Managerのセルフサービスサンドボックスのサポートが強化され、権利を付与されたユーザーはサンドボックス内のすべての環境を削除してクレジットを受け取ることができます。
      * 自動休止サンドボックス環境は、無操作状態が続くと、自動的にサンドボックスを「休止」します。 お客様は、「休止解除」を積極的にトリガーできます。
   * クラウドアクセラレーションをサポートするトランジションツール
   オンプレミスからCloud Serviceまでのトランジションに要する時間とコストを削減する目的で、今月は2つのトランジションツールが開始されました。 これらのツールは、トランジションプロセス中の主要タスクの一部を自動化するように設計されており、その結果、全体的な作業を削減します。 .

   1. [コンテンツ転送ツール](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) （SDで利用可能）を使用すると、コンテンツ転送アクティビティが合理化され、拡張性が向上します。 ユーザーにわかりやすいUIを使用すると、このツールは、既存のお客様およびパートナー（オンプレミス/AMS）がCloud ServiceとしてAEMに移行する際のセルフサービスとなります。
   1. [AMSDispatcherコンバータ](https://github.com/adobe/aem-cloud-service-dispatcher-converter) （オープンソース）ツールを使用して、AMSDispatcher設定からCloud ServiceDispatcher設定への変換を自動化できます。
   [Cloud Service2020.6.0としてのAEMのリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   トランジションツール：

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **コアコンポーネント**

   Core Components 2.9.0は、 [Adobe Client Data Layer](https://github.com/adobe/adobe-client-data-layer) と新しいProgress Barコンポーネントとの統合を導入し、GitHubで入手可能な [オーサリングドキュメント](https://docs.adobe.com/content/help/ja-JP/experience-manager-core-components/using/introduction.html) 、 [開発者の詳細](https://github.com/adobe/aem-core-wcm-components)、プロジェクトのダウンロードと共に利用できるようになりました。

* **AEM as a Cloud Service への移行**

   [AEMへのCloud Service移行：既存のAEMトランジションがCloud Serviceに移行する際に推奨される方法について説明します](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/moving/home.html) 。 このドキュメントの目標は、お客様がこのトランジションに備え、構造化され予測可能な方法でこの遍歴を作成できるように、情報、ガイダンス、ベストプラクティスを提供することです。

   クラウドトランジションツールの1つであるコンテンツ転送ツールがリリースされました。 [コンテンツ転送ツール](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) はアドビが開発したもので、既存のコンテンツをソースAEMインスタンス（オンプレミスまたはAMS）からターゲットAEMCloud Serviceインスタンスに移動するのに使用できます。

   コードリファクタリングツールの1つ — AEMDispatcherコンバーターがリリースされました。 [AEMDispatcherコンバーター](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) は、既存のAEMDispatcherーの設定をCloud ServiceDispatcherの設定としてAEMに変換するためのツールです。

* **アクセシビリティとWCAG 2.1ガイドライン**

   WCAG 2.1ガイドラインに関する更新事項：

   * [Adobe Experience Manager as a Cloud Service と Web アクセシビリティのガイドライン](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [WCAG 2.1 クイックガイド](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [アクセシブルなコンテンツ（WCAG 2.1 適合）の作成 ](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **AEM ニュースレター**

   Experience League による AEM ニュースレターは、AEM の概要を短期間で習得して、すぐに価値を実現できるようにすることを目的としています。次に、最新のニュースレターを示します。

   * [Volume 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html)：Experience Manager はクラウドサービスとして使用できるようになりました。
   * Experience Insider ニュースレターを[購読](https://adobeeventsonline.com/AEM/2017/NL/Optin/)してください。
   * Adobe Experience Manager 6.5 ラーニングとサポートページの [AEM リソース](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)節でニュースレターのアーカイブを表示できます。

### **コミュニティ**

* **AEMコミュニティのディスカッション**

   AEMのすべてのお知らせと、内外のブロガーに対する興味深い言及を一か所で見ることができます。 AEMコミュニティの [ディスカッションの節を参照してください。](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### 新しいExperience Managerコースとチュートリアル

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |
| [ビジネスユーザー向けAdobe Asset Linkはじめに](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | コース | このコースでは、Adobe Asset Linkの機能を使用して、Adobe Experience Managerアセットに保存されたコンテンツをクリエイティブなデザインに反映させる方法について説明します。 このコースでは、アドビのアセットリンクの起動方法、基本的なアセット操作、検索と参照のオプション、他のユーザーとの効率的な共同作業方法など、あらゆる内容について説明します。 |
| [ビジネスユーザー向けAEM Assetsの概要](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | コース | ビジネスユーザー向けのAEM Assetsを使い始める方法を説明します。 AEM Assets、コラボレーション機能、アセットの検索、編成、アセットとレンディションのダウンロードの基本について説明します。 |
| [ビジネスユーザー向けAEM Sitesの概要](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | コース | AEM Sitesの主な機能を使用して組織のWebページを管理する方法を学びます。 このコースでは、AEM Sitesの紹介、オーサリングの基本概念、高度なオーサリング機能、ページ管理機能など、あらゆる内容について説明します。 |
| [AEM プロジェクトの構造](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.translate.html) | 記事 | AEMCloud Serviceと互換性があるように、Adobe Experience ManagerMavenプロジェクトに必要な変更について説明します。 |
| [Sling Model](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | ビデオチュートリアル | SlingモデルWebコンソールを使用した、Cloud ServiceSDKのローカルクイックスタートとしてのAEMのデバッグについて説明します。 |
| [AEM Webコンソールのコンポーネント](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | ビデオチュートリアル | コンポーネントWebコンソールを使用したCloud ServiceSDKのローカルクイックスタートとしてのAEMのデバッグについて説明します。 |
| [ログを使用したAEM SDKのローカルクイックスタートのデバッグ](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | ビデオチュートリアル | Bundles Webコンソールを使用した、Cloud ServiceSDKのローカルクイックスタートとしてのAEMのデバッグについて説明します。 |
| [Cloud ServiceSDKのローカルクイックスタートとしてのAEMのリモートデバッグ](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | ビデオチュートリアル | IDEからのリモートJavaデバッグについて学習します。AEMでのライブコードの実行手順を実行し、正確な実行フローを理解できます。 |
| [スマートタグの設定](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | ビデオチュートリアル | Adobe I/Oを使用してAdobe Experience Manager(AEM)をSmart Content Serviceに統合する手順を説明します。 |
| [ドキュメントのバッチ生成](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | 記事 | Batch APIを使用して、テンプレートから複数のインタラクティブな通信を作成する方法について説明します。 |
| [AEM Formsでの印刷チャネルドキュメントの作成](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | 記事 | 印刷チャネル用のインタラクティブな通信を作成するために必要な手順を説明します。 |
| [Adobe Assetリンクにアクセス](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | ビデオチュートリアル | Creative Cloudデスクトップアプリケーションを使い慣れている場合でも、Adobe Experience Managerアセット(AEM Assets)に保存されたコンテンツにアクセスする方法を説明します。 |
| [アセットリンクパネルの概要](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | ビデオチュートリアル | Adobe Asset Linkを使用すると、クリエイティブユーザーは、InDesign、PhotoshopおよびIllustratorのアプリケーション内パネルを使用して、AEM Assetsに保存されたアセットの参照、検索、チェックアウトおよびチェックインを実行できます。 AdobeアセットリンクパネルのUIとその機能について説明します。 |
| [アセットの検索](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | ビデオチュートリアル | Creative Usersでは、AEM Assetsーに保存されたアセットをキーワードを使用して検索したり、特定の場所で検索を実行したりできます。 |
| [ファイルのバージョン管理とコメント](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | ビデオチュートリアル | Adobeアセットリンクパネルを使用すると、サムネール、基本メタデータ、バージョンなど、AEM Assets内のアセットに関するファイルの詳細にパネル内からアクセスできます。 |
| [Check-In Check-Out](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | ビデオチュートリアル | Adobe Assetを使用すると、作業中のクリエイティブアプリケーションからAEM Assetsを直接チェックアウトでき、すぐに編集を開始できます。 |
| [AEM Assets用のレンディションのみ配置](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | ビデオチュートリアル | AEMアセット用のFor Placement Only(FPO)レンディションの作成方法と使用方法を学びます。 |
| [コピーを配置](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | ビデオチュートリアル | 「コピーを配置」操作を使用して、AEM Assetsのアセットを使用する方法を説明します。 |
| [ダウンロードとアップロード](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | ビデオチュートリアル | アセットリンクパネルを使用して、アセットファイルをダウンロードし、AEM Assetsにアップロードする方法を説明します。 |
| [ファイルとコレクション](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | ビデオチュートリアル | アセットリンクパネルからAEM Assetsファイルやコレクションにすばやく簡単にアクセスする方法を説明します。 |
| [ダウンロード](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | ビデオチュートリアル | アセットとそのレンディションをローカルマシンにダウンロードして、使用および共有する方法を説明します。 |

### その他のリソース

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/jp/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/ja-JP/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre リリースノート](https://docs.adobe.com/content/help/en/livefyre/using/release-notes/c-rn.html)

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 新製品リリース

[Adobe Campaignクラシック20.2リリースには](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html) 、次の機能が含まれます。

* _絵文字のサポート_ - _Azure SynapseFDAコネクタ_ - _新しいプライバシー規制_
* キャンペーンコントロールパネル： [アクティブなプロファイル監視](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### 新しいキャンペーンコースとチュートリアル

| コンテンツ | コンテンツタイプ | 説明 |
| -----------| ---------- | ---------- |  
| [ビジネスユーザー向けAdobe Campaign Standardの概要](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | コース | インターフェイスを操作する方法、配信を使用する方法、受信者データを作成および管理する方法について説明します。 |
| [Adobe Campaignクライアントのインストールとセットアップ](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Video | Adobe Campaignクライアントコンソールをダウンロードしてインストールし、複数の環境への接続を作成して管理し、Adobe Campaignクライアントコンソールへのアクセスを確認する方法を説明します。 |

### ヘルプリソース

* Adobe Campaign Standard：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/campaign-standard-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/overview.html) - [リリース計画](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-planning.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/campaign-classic-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/documentation-updates.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/control-panel/using/release-notes.html) - [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classicのハウツービデオ](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Advertising Cloud DSP の新機能](#adcloud-dsp)
* [Advertising Cloud Search の新機能](#adcloud-search)

### Advertising Cloud DSP の新機能 {#adcloud-dsp}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL キャンペーン] ホーム | （6月3日リリース）提供されたキャンペーン予算と経過時間に基づく新しいキャンペーンレベルのぺーシング指標が利用できます。 |
| 配置予測 | （6月3日リリース）配置レベルの最適化を伴うCTVおよびビデオ配置の場合、配置設定に複数の広告の長さ（15秒および30秒）の予測が含まれるようになりました。 また、VAST在庫とVPAID在庫の両方に対する予測も含まれます。 |
| CPA/ROASの最適化 | （5月20日リリース）キャンペーン管理者は、予算の割り当て超過を防ぐために、パッケージ内の新しい配置を制限する必要がなくなりました。 プレースメントには、CPMまたはCPA/ROASのパフォーマンスに基づく動的な予算配分が適用されるようになりました。 |

### [!UICONTROL Advertising Cloud Search] の新機能 {#adcloud-search}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL キャンペーン] | Microsoft Advertising（旧称Bing Ads）では、2020年9月30日以降の平均掲載順位指標は非推奨となります。 これに備えて、7月11日から、位置に基づく制約は無視され、どのタイプの制約でも位置に基づく条件は無視されます。 |
| [!UICONTROL 広告インサイト] | （6月13日リリース）次のインサイトが削除されました。<br/><br/><ul><li>オーディエンスTargetのパフォーマンス（新しいバージョン）</li><li>過去のパフォーマンス（新しいバージョン）</li><li>一致タイプ（新しいバージョン）</li><li>監査の設定（新しいバージョン）</li><li>ポートフォリオ事前投稿（レガシー）</li></ul><br/>残りのインサイトは従来のバージョンで、 _レガシー_ ラベルは名前から削除されました。 さらに、ライブ/編集モードが削除されました。 |

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

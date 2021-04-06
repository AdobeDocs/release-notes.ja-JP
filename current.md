---
title: 最新のリリースノート
description: Experience Cloud 製品および サービスに関する最新のリリースノート、新機能および新規ドキュメントについて説明します。Experience Cloud、Creative Cloud エンタープライズ版および Document Cloud に関する新しいヘルプとチュートリアルをご覧ください。
doc-type: release notes
last-update: March 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
translation-type: tm+mt
source-git-commit: 6146981c558499f22dbdc56bc12e2ebce2d00439
workflow-type: tm+mt
source-wordcount: '7872'
ht-degree: 29%

---

# Adobe Experience Cloud リリースノート - 2021 年 3 月

![バナー](/assets/experience-cloud-banner-3.png)

Experience Cloud のソリューションとサービスは毎月更新されます。 このページは、[!DNL Experience Cloud]製品とサービスの最新リリースアップデート、ドキュメント、およびチュートリアルを見つけるための中心的な場所です。 また、[!DNL Creative Cloud for Enterprise] と [!DNL Document Cloud] の新しいドキュメントも参照できます。

>[!NOTE]
>
>毎月[アドビの優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)をサブスクライブして、このページの更新に関する電子メール通知を受信します。 このページは1か月を通して保持され、リリース日より前に変更される可能性のあるコンテンツが含まれている場合があります。 定期的にもう一度確認して、Adobeのエンタープライズ製品とExperience Leagueのドキュメントの更新を確認してください。

最新の更新：**2021年4月6日**

* [Digital Experience Blueprints](#blueprints) （新しい導入ドキュメント）
* [Adobe システムステータス](#status)
* [Experience CloudUIコンポーネント、サービス、管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [Analytics](#analytics) **（2021年4月6日更新）** および [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud エンタープライズ版](#creative-cloud)

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。

## ![IconDigital Experience Blueprints](/assets/adobe.png)   {#blueprints}

Digital Experience Blueprintsは、戦略に対処し、確立されたビジネス上の問題を解決するための繰り返し可能な実装です。 Blueprintsは、価値ある期間を短縮し、成功への迅速なパスを提供します。

| 公開日 | 説明 |
| -----------| ---------- |
| [デジタルエクスペリエンスのブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html) | [!UICONTROL デジタル設計図]の概要。 各Blueprintオファーには、高価値のビジネス上の問題、アーキテクチャ、導入手順、技術上の考慮事項、および関連ドキュメントへのリンクについて説明する一連のアーティファクトが記載されています。 |
| [Audience Activationブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/audience-activation/overview.html) | このオーディエンス優先のアクティベーションにより、ブランドは複数のチャネル間で顧客との対話を結び付け、一元化されたオーディエンスを提供し、すべてのチャネルに対してアクティブ化できます。 |
| [お客様のアクティビティハブのブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture//customer-activity-hub/overview.html) | 外部アプリケーションがAdobe Experience Platformの[!UICONTROL リアルタイム顧客プロファイル]にアクセスする方法を説明します。 |
| [Customer Journey Analyticsブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journey-analytics/overview.html) | ブランドが様々なインタラクションチャネルやソースから顧客データや行動を統一し、すべての顧客インタラクションに関するジャーニーベースの表示を作成する方法を説明します。 |
| [プロファイルエンリッチメント設計図のカスタムデータサイエンス](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-science/overview.html) | [!UICONTROL Data Science Workspace]がAdobe Experience Platformのデータをどのように使用して、機械学習の洞察を提供するためのモデルのトレーニング、導入、スコアリングを行うかを説明します。 |
| [データの準備と取り込みのBlueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-ingestion/overview.html) | ソースデータを[!UICONTROL エクスペリエンスデータモデル](XDM)スキーマにマップする方法を説明します。 この設計図には、日付の形式設定、フィールドの分割、連結、変換などのデータ変換や、レコードの結合、結合、再生も含まれます。 |
| [企業データ調査およびレポートのブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-exploration/overview.html) | Experience Platformの[!UICONTROL クエリサービス]では、SQLクエリをデータに対して実行できます。 [!UICONTROL Data Science Workspace]を使用して、データ調査、データ科学、および機械学習のワークロードをデータに対して実行する方法を説明します。 |
| [複数チャネルメッセージオーケストレーションのブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/multi-channel-message-orchestration/overview.html) | ブランドがEメール、SMS、モバイルアラートなどのチャネルを通じて、顧客と積極的に関わり合い、顧客とコミュニケーションを取る方法を学びます。 |
| [サーバー側エンタープライズデータ収集ブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/server-side-enterprise-data-collection/overview.html) | Adobe Experience PlatformWebおよびモバイルSDKで収集されたデータを、Experience Platform[!UICONTROL Edge Network]から目的の宛先に転送する方法を説明します。 |
| [WebおよびモバイルパーソナライゼーションのBlueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/web-personalization/overview.html) | 複数のアプリケーションでオーディエンスのセグメント化を使用して、顧客体験をパーソナライズし、最適化する方法を説明します。 顧客の行動、人口統計、忠誠度レベルおよび前のトランザクションを使用して、レイアウト、誘い文句（CTA：コールトゥアクション）、コンテンツをパーソナライズできます。 |

## ![アイコン](/assets/adobe.png) Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

Adobeシステムの状態に対する最新の更新は、[Adobeシステムの状態 — 2020年5月21日](https://docs.adobe.com/content/help/ja-JP/release-notes/experience-cloud/previous/2020/05212020.html#status)にあります。

## ![](/assets/ec_appicon_24.png) IconExperience Cloud UIコンポーネント、サービス、管理  {#ecloud}

| 機能 | 説明 |
| -----------| ---------- |
| 統合検索 | 現在はExperience Platformに使用できる統合検索で、Experience Platformユーザー向けのソースと宛先の検索がサポートされるようになりました。 この機能を使用すると、セグメント、データセット、スキーマ、ソースおよび宛先を検索できます。 |

## ![アイコン](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Experience Platform と Experience Platform Launch に関するリリース更新情報が含まれます。

* [Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html). （更新日2021年2月24日）
* [Experience Platform Launch リリースノート](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=ja). （更新日2021年2月18日）

### Experience Platform チュートリアルおよびコース

Experience Platform およびサービス用に公開された新しいビデオ、チュートリアル、またはコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年3月 | [監視ダッシュボード](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/monitoring-dashboard.html) | ビデオ | 監視ダッシュボードを使用して、Adobe Experience Platformに取り込まれるデータを監視および追跡する方法を説明します。 この監視ダッシュボードは、ソース・レークを介したソース・データ処理のトップ・ダウン・表示を、ソース、データ・フロー、データ・フローの各実行レベルでプロファイルおよびIDサービスに提供し、迅速に対応可能なアドバイザリを提供します。 |
| 2021年3月 | [ソースコネクタを使用したストリームデータ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-source-connector.html) | ビデオ | このビデオでは、クラウドストレージソースからプラットフォームにデータをリアルタイムでストリーミングし、そのデータをリアルタイムで顧客の関与に使用する方法を示します。 |
| 2021 年 3 月 5 日 | [データエンジニア向けのデータ取り込み](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1.dataingestion) | コース | 複数のソースからのデータをAdobe Experience Platformに取り込む方法など。 |
| 2021年3月 | [Azure Blob 宛先の設定](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=ja#destinations) | ビデオ | [!UICONTROL リアルタイム顧客データプラットフォーム] （リアルタイムCDP）で、Azure Blobストレージ先のセットアップと構成に必要な手順を実行する方法を説明します。 |
| 2021 年 3 月 5 日 | [マーケター向けOffer decisioningの概要](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | コース | Adobe Experience Platformの上に構築された[!UICONTROL Offer decisioning]アプリケーションサービスについて説明します。 このコースは、顧客に最高のオファーを提供することで、売上高、顧客エクスペリエンス、忠誠度を向上させたいマーケターを対象としています。 |
| 2021 年 3 月 5 日 | [APIを使用したストリーミングデータ取り込み](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-http-api.html) | ビデオ | このビデオでは、HTTP APIエンドポイントを使用してリアルタイムでデータをAdobe Experience Platformにストリーミングする方法を示します。 |
| 2021 年 3 月 5 日 | [APIを使用したデータ収集の監視](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/data-monitoring.html?lang=ja#data-ingestion) | ビデオ | Platform の UI と API を使用して Adobe Experience Platform に取り込まれるデータを監視および追跡する方法について説明します。 |
| 2021 年 3 月 5 日 | [データベースからデータを取り込む](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-databases.html?lang=en#sources) | ビデオ | このビデオでは、データベースソースからAdobe Experience Platformのリアルタイム顧客プロファイルとエクスペリエンスデータレークにデータをバッチ取り込む方法を、シームレスで拡張性の高い方法で説明します。 |
| 2021 年 3 月 5 日 | [AmazonS3からデータを取り込む](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-amazon-s3.html) | ビデオ | このビデオでは、クラウドストレージサービスからAdobe Experience Platformのリアルタイム顧客プロファイルとデータレークに、簡単にデータをバッチイングしてシームレスで拡張可能な方法で取り込む方法を説明します。 |
| 2021 年 3 月 5 日 | [Salesforce CRMからデータを取り込む](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | ビデオ | このビデオでは、CRMソースからAdobe Experience Platformのリアルタイム顧客プロファイルとデータレークに、簡単にデータをバッチイングしてシームレスで拡張可能な方法で取り込む方法を示します。 |
| 2021 年 3 月 5 日 | [Adobe Analyticsからデータを取り込む](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | ビデオ | Adobe Analyticsソースコネクタを使用すると、Adobe AnalyticsからAdobe Experience Platformのリアルタイム顧客プロファイルおよびエクスペリエンスデータレークに、シームレスで拡張性の高い方法で簡単にデータをストリーミングできます。 |
| 2021 年 3 月 5 日 | [ソースコネクタについて](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/overview.html?lang=en#sources) | ビデオ | このビデオでは、ソースまたはソースコネクタのExperience Platformに関する概要を説明します。 |
| 2021 年 3 月 5 日 | [AdobeIOコンソールエクスポートポストマンの詳細](https://experienceleague.adobe.com/docs/platform-learn/tutorials/apis/postman.html) | ビデオ | Experience PlatformAPIを認証し、アクセスする方法を説明します。 |
| 2021 年 3 月 5 日 | [データ収集について](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/understanding-data-ingestion.html#data-ingestion) | ビデオ | リアルタイムの顧客プロファイルを管理するためのオープンで拡張性の高い1つのプラットフォームにデータを統合できる、Experience Platformのデータ取り込み機能について説明します。 |

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Adobe Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

### 最新の製品リリース

2021年2月のリリース — 最新の機能、改善点、および修正点について詳しくは、[Journey Orchestrationリリースノート](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html)を参照してください。

### 新しい Journey Orchestration コースとチュートリアル

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 3 月 16 日 | [プロファイルの更新操作](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/update-profile-action.html?lang=en#building-a-journey) | ビデオ | 既存のExperience Platformプロファイルを、イベント、データソース、または特定の値を使用した情報で更新する方法について説明します。 |

### Journey Orchestration の追加リソース

[ドキュメント](https://docs.adobe.com/content/help/ja-JP/journeys/using/journey-orchestration-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![](/assets/experience_platform_appicon_24.png) IconOffer Decisioning  {#offer-decisioning}

[!UICONTROL オファー] 決定は、Adobe Experience Platformと統合されたアプリケーションサービスです。[!UICONTROL Offer decisioning]を使用して、すべてのタッチポイントにわたって適切なタイミングで最高のオファーと経験を顧客に提供します。

### 最新の製品リリース

2021年2月のリリース — 最新の機能について詳しくは、[Offer decisioningリリースノート](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new)を参照してください。

### その他のOffer decisioningリソース

[ドキュメント](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=en) - [使い方に関するビデオ](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2021 年 3 月 25 日**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)  **（更新日2021年4月6日）**
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | [一般公開](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| ----------- | ---------- | ------- |
| データ修復APIの更新 | 2021 年 3 月 25 日 | データ修復APIで、[!UICONTROL ページ]と[!UICONTROL IPアドレス]、モバイル変数およびビデオ変数、カスタム[!UICONTROL props]と[!UICONTROL eVars]などの標準変数がサポートされるようになりました。  変数内の値は削除できるほか、新しい値を設定できます。 APIで、URL、クエリ文字列、記号などをフィルタリングするオファーも追加されました。 |
| Analysis Workspace:[!UICONTROL コンポーネント] > [!UICONTROL ユーザー設定] | 2021 年 3 月 25 日 | [!UICONTROL コンポーネント]/[!UICONTROL ユーザーの環境設定]ページでは、[!UICONTROL Analysis Workspace]の設定と、ユーザーに関連するコンポーネントを管理できます。 [!UICONTROL ユーザー] 環境設定は、すべての新しいプロジェクトおよびパネルに適用されます。<br>**注意：** 次の設定は、 [!UICONTROL ユーザー] 環境設定ページに移動しました。<ul><li>レポート設定：千単位区切り文字（現在は&#x200B;_数値の形式_）</li><li>レポート設定：CSV区切り文字</li><li>Workspaceプロジェクト：ヘルプ/ヒントを有効にする</li><li>Workspaceプロジェクト：空のパネル&#x200B;_このパネル_&#x200B;オプションを使用して新しいプロジェクトを開始</li></ul> |
| Analysis Workspace:[!UICONTROL ヒストグラムスマートバケット予測] | 2021 年 3 月 25 日 | [!UICONTROL ヒストグラムのスマートバケット] 予測は、データ分散に使用するグループの正しい幅と数を自動的に識別することで、カーディナリティ指標の高いヒストグラムの処理に役立ちます。低カーディナリティ指標の場合、ビジュアライゼーションは以前と同じように動作します。 |
| [!UICONTROL 使用状況] ログAPI | 2021 年 3 月 25 日 | これは、新しいv2.0 Analytics APIで、**[!UICONTROL 管理者]**/**[!UICONTROL ログ]**/**[!UICONTROL 使用状況およびアクセスログ]**&#x200B;で利用できるのと同じ使用状況ログデータに、プログラムレベルでアクセスできます。 認証、スキーマ、サンプルレスポンスに関する詳細は、[こちら](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/usage-logs.md)を参照してください。 |
| Analyticsダッシュボードでのカスタム日付範囲のサポート | 2021 年 4 月 23 日 | スコアカードの作成者は、カスタム日付範囲を作成して、モバイルスコアカードプロジェクトに適用できます。 作成者は、使い慣れたワークスペースやモバイルの日付範囲のプリセットから選択したり、カスタムの日付範囲を作成したりできます。 [詳細情報](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/curator.html#mobapp). |

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | [一般公開](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| ----------- | ---------- | ----- |
| [!UICONTROL Adobe Analyticsダッシュボード]のサポート | 2021 年 3 月 25 日 | [!UICONTROL Customer Journey Analytics] (CJA)で、 [!UICONTROL Adobe Analyticsダッシュボードスコアカード] ビルダーとモバイルアプリがサポートされるようになりました。これにより、エグゼクティブやビジネスユーザーは、すでにAdobe Analyticsで使用しているのと同じアプリを使用して、CJAデータに基づくチャネル間のKPIを確認できます。 |
| Analysis Workspace:**[!UICONTROL コンポーネント]** > **[!UICONTROL ユーザー設定]** | 2021 年 3 月 25 日 | [!UICONTROL コンポーネント]/[!UICONTROL ユーザーの環境設定]ページでは、[!UICONTROL Analysis Workspace]の設定と、ユーザーに関連するコンポーネントを管理できます。 [!UICONTROL ユーザー] 環境設定は、すべての新しいプロジェクトおよびパネルに適用されます。<br>**注意：** 次の設定は、 [!UICONTROL ユーザー] 環境設定ページに移動しました。<ul><li>Workspaceプロジェクト：ヘルプ/ヒントを有効にする</li><li>Workspaceプロジェクト：空のパネル&#x200B;_このパネル_&#x200B;オプションを使用して新しいプロジェクトを開始</li></ul> |
| Analysis Workspace:[!UICONTROL ヒストグラムスマートバケット予測] | 2021 年 3 月 25 日 | [!UICONTROL ヒストグラムのスマートバケット] 予測は、データ分散に使用するグループの正しい幅と数を自動的に識別することで、カーディナリティ指標の高いヒストグラムの処理に役立ちます。低カーディナリティ指標の場合、ビジュアライゼーションは以前と同じように動作します。 |
| AnalyticsダッシュボードでのCustomer Journey Analyticsのサポート | 2021 年 3 月 25 日 | AnalyticsダッシュボードアプリでCustomer Journey Analyticsがサポートされるようになりました。 Customer Journey Analyticsを持つユーザーは、AnalyticsダッシュボードアプリでAdobe Experience Platformに取り込まれた任意のデータからKPIを引き出すことができます。 Customer Journey Analyticsを使用すると、複数のデータソースを組み合わせて、顧客体験を真のマルチチャネル表示できます。 Analyticsダッシュボードアプリを使用すると、いつでもどこでも、最新の全体的なビジネス表示を得ることができます。 [詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/curator.html?lang=en#cja-dashboards). |

### Adobe Analytics の修正点 {#aa-fixes}

* セグメントの新しい所有者を編集および保存した後、この新しい所有者がセグメントUIに反映されない問題を修正しました。 (AN-234502;AN-250970;(AN-250286)
* アプリレポートスイートで、プライマリサーバーコールとモバイルプライマリサーバーコールの両方が使用される問題を修正しました。 （AN-244029）
* [!UICONTROL Workspace]プロジェクトを開くとUI応答時間が遅くなる問題を修正しました。 （AN-242553）
* 最新バージョンにアップグレードした後、[!UICONTROL Report Builder]にログインできない問題を修正しました。 （AN-248825）
* 管理者以外のユーザーのユーザー権限に関する問題を修正しました。[!UICONTROL Admin Console]内のプロファイルの少なくとも1つに追加されている限り、ユーザーには権限が必要です。 プロファイルにユーザーを追加する場合は、そのユーザーの権限にのみ追加する必要があり、他の製品プロファイルを使用して既に権利を付与されているものを削除しないでください。 （AN-242723）
* [!UICONTROL データフィード]で発生していた言語エンコーディングの問題を修正しました。 （AN-249862）
* 共有[!UICONTROL Workspace]プロジェクトにユーザーがアクセスできない問題を修正しました。 （AN-247814）
* [!UICONTROL アラートプレビュー]がトリガーされた[!UICONTROL アラート]の数と一致しない問題を修正しました。 (AN-249392;(AN-250804)

#### その他の Adobe Analytics の修正点

AN-206099;AN-237460;AN-241803;AN-243735;AN-244081;AN-244615;AN-244687;AN-246832;AN-247227;AN-248237;AN-248478;AN-248852;AN-249115;AN-249140;AN-249216;AN-249275;AN-249538;AN-249963;AN-250034;AN-250270;AN-250320;AN-250338;AN-250377;AN-250378;AN-250557;AN-250609;AN-250614;AN-250615;AN-250885;AN-251088;AN-251137;AN-251190;AN-251192;AN-251193;AN-251301;AN-251496;AN-251545;AN-251734;AN-251735;AN-251744;AN-251816;AN-251982;AN-251972;AN-252051;AN-252073;AN-252105;AN-252409;AN-252640

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| データフィードとData WarehouseのIPアドレスの変更 | 2021年4月7日 | 6月17日から、データフィードとData Warehouse配信システムはアドビのデータセンター内で再配置されるため、外部IPアドレスの変更がお客様に表示される可能性があります。  レポートおよびフィードが提供されるデータセンターのIP CIDRブロックが、管理対象の任意の宛先システムに関して、任意のファイアウォールに存在することを確認する必要があります。 [ファイアウォールの許可リストに配置するIPアドレス範囲の完全なリストを以下に示します](https://https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html#data-collection-and-ftp-ip-address-blocks)。 |
| Analyticsメニューの変更に関するお知らせ | 2021 年 3 月 24 日 | 2021年4月22日に、パフォーマンスを上げるために、**[!UICONTROL コンポーネント]**、**[!UICONTROL ツール]**、**[!UICONTROL 管理者]**&#x200B;のドロップダウンメニューを更新します。 これらのページはすべて、**[!UICONTROL すべてのコンポーネント]**、**[!UICONTROL すべてのツール]**、**[!UICONTROL すべての管理者]**&#x200B;のリンクから引き続き利用できます。ドロップダウンメニューから削除されます。 ドロップダウンメニューから削除され、それぞれのリンクページに配置されるメニュー項目を示します。<br><br> [!UICONTROL コンポーネント]<ul><li>[!UICONTROL ブックマーク]</li><li>[!UICONTROL ダッシュボード]</li><li>[!UICONTROL ターゲット]</li><li>[!UICONTROL カレンダーイベント]</li><li>[!UICONTROL 予定レポート]</li><li>[!UICONTROL レポート設定]</li></ul>[!UICONTROL ツール]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL ユーザー管理]</li><li>[!UICONTROL 分類インポーター]</li><li>[!UICONTROL 分類ルールビルダー]</li><li>[!UICONTROL データソース]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL カンパニー設定]</li><li>[!UICONTROL ログ]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL コードマネージャー]</li><li>[!UICONTROL IPアドレスごとに除外]</li><li>[!UICONTROL トラフィック管理]</li></ul> |
| [!UICONTROL SiteCatalystと同じVISTA処理] =オン | 2021 年 3 月 17 日 | 2021年6月17日に、すべてのレポートスイートが[!UICONTROL SiteCatalystと同じVISTA処理]をオンに設定するように更新されます。 この変更は、処理ルールに一致するようにデータを処理することによって、[!UICONTROL Data Warehouse]のレポートに影響します。 ご質問や明確な説明については、Adobeカスタマーケアにお問い合わせください。 |
| [!UICONTROL フル処理] [!UICONTROL データソース]のEOL | 2021 年 3 月 10 日（PT） | Adobeは、将来的には[!UICONTROL フル処理] [!UICONTROL データソース]を非推奨とする予定です。 2021 年 3 月 25 日（PT）現在、このタイプの新規インポートは作成できなくなっています。 [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md)を使用して、このタイプのデータをインポートします。 [詳細情報](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html) |
| Reports &amp; Analytics のランディングページオプション | 2021 年 2 月 19 日（PT） | 2021 年 3 月 25 日（PT）に、新しい Reports &amp; Analytics ダッシュボードまたはその他のコンテンツを Adobe Analytics ランディングページとして設定するオプションが削除されます。 以前に Reports &amp; Analytics ページをカスタムランディングページとして設定していた場合、[!UICONTROL ユーザーの環境設定]でランディングページが変更されるまで、このページは引き続き機能します。  |
| Ad Hoc Analysis のサポート終了 | 2021 年 1 月 | [!UICONTROL Ad Hoc Analysis] は、2021 年 3 月 1 日（PT）にサポート終了日に達します。詳しくは、[Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) を参照してください。 |
| 3 つの Analytics API サービスの提供終了 | 2021 年 1 月 6 日（PT） | 2021 年 4 月 30 日（PT）、以下の Analytics 従来の API サービスの提供が終了し、サービスが停止されます。 これらのサービスを使用して構築された現在の統合は、その日以降使用できなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問への回答、および進め方に関するガイダンスを提供するために、[従来の API EOL に関する FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email#) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| Adobe Data Connectors のサポート終了 | 2020 年 7 月 13 日（PT） | Adobe [!UICONTROL Data Connectors] は、実行不可能またはサポート対象外のレガシーテクノロジーによって動作します。[Adobe Exchange パートナープログラム](https://partners.adobe.com/exchangeprogram/experiencecloud)で新しい標準が利用できます。 どの統合でも、その標準を使用して、引き続き提供およびサポートできます。 正式なサポート終了日は 2021 年 8 月 1 日（PT）です。 [詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/import/dataconnectors/data-connectors-eol.html) |

### AppMeasurement {#appm}

AppMeasurement リリースの最新の更新については、[AppMeasurement for JavaScript リリースノート](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/appmeasurement-updates.html)を参照してください。

### Analytics ヘルプリソース

* [Adobe Analytics 製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja-JP)

## ![アイコン](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Managerの修正点と改善点。

### 修正点および改善点 {#aam-fixes-and-improvements}

* [オンボーディングステータスレポート](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html?lang=ja)の問題を修正しました。 この問題では、レポートのレコードとオンボーディングパートナーがアップロードしたファイルのレコードに食い違いがありました。 （AAM-57415）
* **[!UICONTROL 人ベースの宛先]**&#x200B;に対する重複セグメントマッピングの検証が正しくない問題を修正しました。 （AAM-56631）
* 一部のユーザーが&#x200B;**[!UICONTROL オーディエンスレポート]**&#x200B;にアクセスできない問題を修正しました。 （AAM-57412）
* [!UICONTROL リモートコード実行]の脆弱性にパッチを適用しました。この脆弱性は、攻撃者が機密データにアクセスする際に使用する可能性があります。 （AAM-57495）

### 新しい Audience Manager コースとチュートリアル {#tutorials-aam}

新しく公開された Audience Manager ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 3 月 19 日 | [Audience Managerユーザー向けのリアルタイムCDPにおけるデータ・ガバナンスの理解](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-data-gov-for-aam-users.html) | ビデオ | [!UICONTROL リアルタイム顧客データプラットフォーム]のデータガバナンス機能について説明します。 |
| 2021 年 3 月 19 日 | [ブランドと消費者の2つの認知の物語](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/brands-vs-consumers.html) | ビデオ | このウェビナーでは、Adobeが、広告主と発行者の理解と準備レベルを、無料の将来に向けて明確に解明し、使用事例への影響や、より広いエコシステムに対する認識を明らかにします。 |
| 2021 年 3 月 5 日 | [責任あるお客様のデータ管理に関する10の考慮事項](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/ten-considerations-for-responsible-customer-data-management.html) | イベント | 責任あるデータ管理に関する主な考慮事項について、AdobeとScotiabank Digitalからお問い合わせください。 |
| 2021 年 3 月 19 日 | [データ管理の未来と変化する環境](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/the-future-of-data-management-and-the-changing-environment.html) | イベント | このウェビナーでは、Adobeと451 Researchが、新しいマーケティング環境に対応し、データ管理の将来に向けたビジネスの準備を始めるために、テクノロジーとデータの未来についてどのように考えているかを見てみましょう。 |
| 2021 年 3 月 21 日 | [Audience Manager・ユーザー向けのリアルタイムCDPにおけるスキーマとXDMの理解](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=en#other-integrations) | ビデオ | Audience Managerからリアルタイム・カスタマー・データ・プラットフォーム（リアルタイムCDP）に移行する際に、新しい概念と慣例がいくつか出てきます。 スキーマとXDMは、このカテゴリに該当します。 このビデオでは、これらの概念について説明します。 |
| 2021 年 3 月 17 日 | [Audience Manager・ユーザに対するリアルタイムCDPでのシグナルの理解](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-signals-for-aam-users.html) | ビデオ | このビデオは、Real-time Customer Data Platform(Real-time CDP)に移行するAudience Managerユーザーを対象としており、特性を構築するAudience Managerで使用するシグナル（キーと値のペア）がPlatformでどのように使用されるかを説明しています。 |
| 2021 年 3 月 12 日 | [Audience Manager・ユーザー向けのリアルタイムCDPにおけるスキーマとXDMの理解](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html) | ビデオ | Audience Managerからリアルタイム・カスタマー・データ・プラットフォーム（リアルタイムCDP）に移行する際に、新しい概念と慣例がいくつか出てきます。 スキーマとXDMは、このカテゴリに該当します。 このビデオでは、これらの概念について説明します。 |
| 2021 年 3 月 12 日 | [Audience Managerユーザー向けのリアルタイムCDPでのWebデータ取り込みの理解](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-web-ingestion-for-aam-users.html) | ビデオ | WebサイトデータをReal-time Customer Data Platform(Real-time CDP)に取り込む概念を説明し、Audience Managerデータコネクタの適合箇所に関する高度なタッチと、Web SDKを介してWebサイトからReal-time CDPにデータを直接移動する方法を含みます。 |
| 2021 年 3 月 3 日 | [Audience Managerユーザー向けのリアルタイムCDPでのセグメントの理解](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-segments-for-aam-users.html?lang=en#other-integrations) | ビデオ | セグメントの違い、およびAudience ManagerとリアルタイムCDPのセグメント作成について説明します。 |
| 2021 年 3 月 3 日 | [Audience Managerユーザー向けのリアルタイムCDPの特徴の理解](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-traits-for-aam-users.html?lang=en#other-integrations) | ビデオ | Audience Managerの特徴と、Real-time CDPの特徴を説明します。 |
| 2021 年 3 月 3 日 | [Audience Managerユーザー向けのリアルタイムCDPにおけるファーストパーティデータ取り込みについて](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-1pd-ingestion-for-aam-users.html?lang=en#other-integrations) | ビデオ | ファーストパーティのオフラインデータをリアルタイム顧客データプラットフォーム（リアルタイムCDP）に取り込む方法を説明します。 データ取り込みに関する2つの製品の主な違いと、プロセスがリアルタイムCDPに移行するまで、Audience ManagerData Connectorを停止ギャップとして使用する方法を説明します。 |
| 2021 年 3 月 1 日 | [Audience Marketplaceに対するオファーによる所有オーディエンスの商品化](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/audience-marketplace/selling-data/commercialize-owned-audiences-on-marketplace.html?lang=en#audience-marketplace) | ビデオ | データをプライベートデータフィードまたはパブリックデータフィードとしてAudience Marketplaceに設定し、セカンドパーティまたはサードパーティのデータプロバイダーにする方法について説明します。 |
| 2021年3月 | [Audience Managerでのデータアクティベーションの作成と管理](https://experienceleague.adobe.com/?lang=ja&amp;recommended=AudienceManager-U-1-2020.4) | コース | このコースでは、エンドユーザーのエクスペリエンスをカスタマイズするために、オーディエンスデータを宛先パートナーに送信するなど、オーディエンスのアクティブ化について説明します。 送信先の基本事項、適切な送信先を選択する方法およびCookieではなく、ユーザーに基づいてソーシャルネットワークの送信先にオーディエンスデータを準備して送信する方法について説明します。 |
| 2021年3月 | [Audience Managerの高度なスキル](https://experienceleague.adobe.com/?lang=ja&amp;recommended=AudienceManager-U-1-2020.5) | コース | Audience Managerの基本を習得したら、このコースを受講して、オーディエンス管理を次のレベルに進める方法を学びます。 アルゴリズムモデルでAIを使用する方法、プロファイル結合ルールを使用して顧客をデバイスではなく人物として理解する方法、およびDMPの使用を拡張するその他の優れたトピックについて説明します。 |

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

 Experience Manager の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

>[!NOTE]
>
>[Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することを推奨します。

### 製品リリース

* **AEM 6.5.8.0**
AEM 6.5、Service Pack 8（2021 年 3 月 11 日リリース 6.5.8.0）は、2019 年 4 月の AEM 6.5 の一般リリース以降にリリースされた新機能、お客様向けの主な機能強化、パフォーマンス、安定性、セキュリティの向上を含む重要なアップデートです。
   * [リリースノート](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=ja#service-pack)
   * [AEM Forms リリース成果物](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=ja#forms-updates)

* **AEM 6.4.8.4**
AEM 6.4、Service Pack 8、Cumulative Fix Pack 4（2021年2月25日リリース6.4.8.4）は重要なアップデートで、AEM 6.4、Service Pack 8(6.4.8.0)の一般リリース（2020年3月）以降の社内およびお客様向けの修正が含まれています。
   * [リリースノート](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ja)
   * [AEM Forms リリース成果物](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **Adobe Experience Manager as a Cloud Service**

   Cloud ServiceとしてのExperience Managerの新機能

   * **Cloud ServiceとしてのExperience Managerサイト**

      * [RemotePageコンポーネント](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html?lang=en):を使用して、Experience Manager内の外部SPAを表示および編集するためのサポートを追加しました。
      * [Experience Manager内での外部SPAの編集](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html?lang=en):スタンドアロンの単一ページアプリをExperience Managerインスタンスにアップロードする機能、編集可能なコンテンツセクションの追加、オーサリングの有効化を追加しました。
   * **Experience Manager Assets as a Cloud Service**

      * Experience Managerアセットは、Cloud Serviceとして、事前設定済みのブランドポータルインスタンスを持つ権利が付与されます。 Cloud Managerユーザーは、Cloud ServiceーアセットでブランドポータルをExperience Managerとしてアクティブ化できます。 「[Brand Portalを使用したBrand Portalのアクティブ化](https://experienceleague.corp.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html)」を参照してください。
      * ブランドポータルを使用してアセットをソースできるようになりました。 アセットソーシング機能では、Brand Portalを使用して、エージェンシーユーザーとの関わりを深め、新しいマーケティングキャンペーン、フォトシュート、プロジェクトのアセットをソースできるよう支援します。 『ブランドポータルガイド』の「[アセットソーシングの概要](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html?lang=en)」を参照してください。
      * ブランドポータルの使用状況レポートに、アクティブなユーザーのみが表示されるようになりました。 非アクティブなユーザーは現在表示されません。 アクティブなユーザーとは、Admin Console内の製品プロファイルにアカウントが割り当てられているユーザーです。 ブランドポータルガイドの[レポートの操作](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html?lang=en)を参照してください。
      * Brand Portalに新しいダウンロード設定が導入されました。この設定を使用すると、フォルダーやコレクションなどをダウンロードするときに、アセットごとに個別のフォルダーを作成できます。 『ブランドポータルガイド』の「**ブランドポータル**&#x200B;からのアセットのダウンロード」の「[アセットのダウンロード](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html?lang=en)」を参照してください。
   * **Cloud ServiceとしてのFormsExperience Manager**

      AEM Formsは、多くの組織が長年にわたって素晴らしいオンボーディングや入学経験を提供するのを助けてきた。 これらのエクスペリエンスは、組織がリードを販売に転換したり、取り込んだ顧客データを処理したり、オーディエンスプロファイルに基づいてレスポンシブなエクスペリエンスを提供するのに役立っています。 現在、AEM Formsはクラウドサービスとして利用できます。

      AEM FormsをCloud Serviceとして使用し、デジタルフォームの作成、既存のデータソースへのフォームの接続、フォームとAdobe Signとの統合を行ってフォームに電子署名を追加し、レコードドキュメント(DoR)を生成して送信済みのフォームをPDFファイルとしてアーカイブできます。 また、このサービスでは、既存のPDF formsをデジタルフォームに変換することもできます。 標準的なAEM Formsの機能に加えて、自動拡張、アップグレードのダウンタイムゼロ、クラウドネイティブの開発環境など、クラウドネイティブの機能をいくつかオファーしています。 [このブログ記事](https://blog.adobe.com/en/publish/2021/03/11/experience-manager-forms-as-a-cloud-service.html)を読み、Cloud ServiceとしてのAEM Formsの能力や特徴を知る。

      デモを見るか、サービスに新規登録するには、Adobeの担当者にお問い合わせください。


   * **Cloud ServiceとしてのExperience Managerコマース**

      * 製品エクスペリエンス管理：エクスペリエンスフラグメントを使用して、商品カタログページを個別に拡張する。
      * 関連するコンテンツにすばやく移動するアクションなど、アセットとエクスペリエンスフラグメントのリンクを表示するための製品コンソールプロパティを拡張しました。
      * 最新のCIFコアコンポーネントバージョン1.8.0が含まれるCIFベニアリファレンスサイト — 2021.02.24をリリースしました。詳しくは、[CIFベニアリファレンスサイト2021.02.24](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.24)を参照してください。
      * CIFコアコンポーネントのバージョン1.8.0をリリースしました。詳しくは、[CIFコアコンポーネント1.8.0](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.8.0)を参照してください。
   * **Cloud Manager**

      * [IP許可リスト](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/ip-allow-lists/check-ip-allow-list-status.html?lang=en#pre-existing-cdn)、[SSL証明書](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-ssl-certificates/check-status-ssl-certificate.html?lang=en#pre-existing-cdn)、[カスタムドメイン名](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/custom-domain-names/check-domain-name-status.html?lang=en#pre-existing-cdn)の既存のカスタムドメイン名の設定を持つ環境のお客様には、以前の設定に関するメッセージが表示されるようになりました。 また、ユーザーインターフェイスを介してセルフサービスを行うこともできます。
      * 必要な権限を持つユーザーは、プログラムを編集でき、セルフサービスの方法で次の操作を行うことができます。
         * ア追加セットを含む既存のプログラムに対するサイトソリューション、または逆の方法
         * サイトとアセットの両方を含む既存のプログラムからサイトまたはアセットを削除します。
         * 2つ目追加は、使用されていないソリューションエンタイトルメントを、既存のプログラムに対して、または新しいプログラムとして使用する方法です。
      * **パイプライン実行画面とアクティビティ** 画面の両方にAEM Push  *Updatelabelが表示されるようにな*  ** りました。
      * 環境が休止状態になっているが、Experience Managerの更新も利用可能な場合、**Hibernated**&#x200B;ステータスは&#x200B;**Update available**&#x200B;よりも優先されます。
      * 統合シェルのユーザープロファイルアイコン（右上）に移動した後、**表示Cloud Managerの役割**&#x200B;を選択すると、Cloud Managerの役割を表示できるようになりました。
      * ラベル&#x200B;**承認申請**&#x200B;が&#x200B;**実稼動承認**&#x200B;にラベル変更され、より明確になりました。
      * **バージョン**&#x200B;ラベルが、実稼動パイプライン実行画面の&#x200B;**Gitタグ**&#x200B;に再ラベル付けされました。
      * 重要な指標が定義されたしきい値を満たさない場合の動作を定義するラベルは、その真の動作を反映するために再ラベル付けされています。**すぐにキャンセル**&#x200B;と&#x200B;**すぐに承認**。
      * Experience Manager Cloud ServiceSDKのバージョン`2021.3.4997.20210303T022849Z-210225`に基づいて、クラスとメソッドの非推奨リストが更新されました。
      * Cloud Manager実稼動パイプラインに、[カスタムUIテスト](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/functional-testing.html?lang=en#custom-ui-testing)機能が追加されました。




### **コミュニティ**

* **アドビ開発者ライブ 2021 | セッションの完全なリスト**

   [こ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-2021-complete-session-list/m-p/394595#M27875) れは、 **Adobe開発者ライブで発生したすべてのExperience Managerセッションの集計リストです**。

* **Adobeサミット2021 |Experience Managerセッションリストの完了**

   [こ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-complete-aem-session-list/td-p/398344) れは、 **Adobe・サミット2021で行われるすべてのExperience Manager・セッションのリストを集約したものです**。

### Experience Manager リリース情報

Experience Manager のリリースノートはすべて次のページに記載されています。

* [Experience Manager リリースのアップデートとロードマップ](https://docs.adobe.com/content/help/ja-JP/experience-manager-release-information/aem-release-updates/home.html)
* [Adobe Experience Manager as a Cloud Service リリース情報](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/release-notes/home.html)
* [Experience Manager Cloud Manager リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [自動フォーム変換サービスリリースノート](https://docs.adobe.com/content/help/ja-JP/aem-forms-automated-conversion-service/using/release-notes.html)
* [Experience Manager 6.5 Service Pack リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Experience Manager 6.4 累積修正パックリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-64/release-notes/cfp-release-notes.html)
* [Experience Manager Assets Dynamic Media リリースノート](https://docs.adobe.com/content/help/ja-JP/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Experience Manager Brand Portal リリースノート](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Experience Manager デスクトップアプリケーションリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-desktop-app/using/release-notes.html)
* [Experience Manager Dispatcher リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Livefyre リリースノート](https://docs.adobe.com/content/help/ja-JP/livefyre/using/release-notes/c-rn.html)

### Experience Manager コースおよびチュートリアル

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 3 月 | [Experience Manager Cloud Service時のコンテンツ配信](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/content/feb2021/content-delivery.html#content) | イベント | Cloud ServiceとしてのAdobe Experience Managerは、強力な事前設定済みコンテンツ配信アーキテクチャを備えています。 最適化されたコンテンツ配信設定を最大限に活用する方法を実演する |
| 2021 年 3 月 | [ExLへのFormsおよびドキュメントの種類に関するヘルプ記事の移行](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/pdf-forms-and-documents.html?lang=en#document-services) | 記事 | 様々なタイプのPDF formsとドキュメントを説明する記事。 |
| 2021 年 3 月 | [AEM発行環境を使用した実稼働環境へのデプロイメント](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/production-deployment.html#graphql) | チュートリアル | 作成者インスタンスから発行インスタンスにコンテンツが配布されることをシミュレートするには、ローカル環境を設定します。 GraphQL APIを使用して、AEM Publish環境のコンテンツを使用するように設定されたリアクトアプリの実稼働版ビルドを生成します。 この過程で、環境変数を効果的に使用する方法と、AEM CORS設定を更新する方法について学びます。 |
| 2021 年 3 月 | [GraphQL APIを使用したヘッドレスコンテンツ管理](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.headless) | コース | AEMのGraphQL APIとヘッドレス機能を、外部アプリで表示されるパワーエクスペリエンスにどのように使用できるかを調べます。 |
| 2021 年 3 月 | [起動回数 — 機能のビデオ](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/launches.html) | ビデオ | AEM Sitesでの起動により、将来のリリースでWebサイトのコンテンツを作成、作成、確認する方法が提供されます。 打ち上げの開始時には、実稼動版のWebサイトは、通常どおり進化し、日々変化する可能性があります。 |
| 2021 年 3 月 | [LinRelateおよびUnrelateアセット — 機能ビデオテキスト](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html?lang=ja) | ビデオ | AEMでアセット間の関係を確立し、管理する方法を説明します。 |
| 2021 年 3 月 | [外部アプリケーションからの AEM as a Cloud Service への認証](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | コース | 外部アプリケーションがローカル開発アクセストークンとサービス資格情報を使用して、AEMをHTTP経由のCloud Serviceとしてプログラム的に認証する方法を説明します。 |
| 2021 年 3 月 | [住宅ローン申し込みフォームでの複数のフォームの入力と署名](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.7.forms&amp;lang=ja-JP) | コース | AEM Formsと署名の統合を使用して、ドキュメントのパッケージにシームレスに署名します。 フォームに入力したデータは、パッケージ内の後続のフォームに事前入力するために使用できます。 |
| 2021 年 3 月 | [AEMでのバージョン/タイムワープ](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/timewarp-feature-video-use.html) | ビデオ | TimewarpはAdobe Experience Manager Sitesの機能で、過去の特定の時刻にページの状態を簡単に確認する方法を作成者に提供します。 |
| 2021 年 3 月 | [基盤 — ワークフロー管理](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-workflow-management.html?lang=en#workflow) | ビデオ | このビデオでは、ワークフローモデルを使用して、この機能のセットを紹介します。ただし、AEM Launchersにも当てはまります。 |
| 2021 年 3 月 | [エクスペリエンスフラグメントブロック](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/building-blocks.html) | ビデオ | 構築ブロックは、エクスペリエンスフラグメントのサブ機能です。 コンテンツ作成者は、構築ブロックを使用して、様々なバリエーションのエクスペリエンスフラグメントでコンポーネントを再利用できます。 |
| 2021 年 3 月 | [ワークフローエディター](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-the-workflow-editor.html?lang=en#workflow) | ビデオ | ワークフローは、Experience Manager上のビジネス・プロセス管理を可能にし、コンテンツの自動処理に加えて、人的な意思決定を必要とするガバナンスやプロセスの促進に使用されます。 |
| 2021 年 3 月 | [AEM Assetsの非公開ユーザーグループ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/closed-user-groups.html) | ビデオ | Closed User Groups(CUGs)は、公開済みサイト上の特定のユーザーグループに対してコンテンツへのアクセスを制限するために使用される機能です。 このビデオでは、閉じたユーザーグループをAdobe Experience Managerアセットと共に使用して、アセットの特定のフォルダへのアクセスを制限する方法を示します。 |
| 2021 年 3 月 | [レポート ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/asset-reports.html) | ビデオ | AEM Assetsが、直観的なユーザーエクスペリエンスを通じて大規模なリポジトリに対して拡張可能なエンタープライズレベルのレポートフレームワークを提供する方法について説明します。 |
| 2021 年 3 月 | [AEM Assetsの画像用のスマートタグ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/image-smart-tags.html) | ビデオ | 画像のスマートタグは、画像のコンテンツに基づいてメタデータタグを画像アセットに自動的かつインテリジェントに追加することで、AEM検索機能を拡張します。 |
| 2021 年 3 月 | [メタデータのカスケード、表示](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/cascade-metadata-feature-video-use.html) | ビデオ | フィールド要件、表示、コンテキストの選択に関する新しい動的ルールについて説明します。 このビデオでは、管理者がこれらのルールをカスタムメタデータスキーマに適用するのに必要な手順についても説明しています。 |
| 2021 年 3 月 | [プロジェクトマスター](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/projects/use-project-masters.html?lang=en#delete-project-masters) | ビデオ | マスタープロジェクトを削除すると、使用できない派生プロジェクトになります。 |
| 2021 年 3 月 | [ページプロパティのカスタマイズ](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/developing/page-properties-technical-video-develop.html) | ビデオ | ページプロパティの最適な拡張とカスタマイズ方法に関するテクニカルビデオの作成を参照してください。 |
| 2021 年 3 月 | [コンテンツフラグメントの変換](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-translation-feature-video-use.html) | ビデオ | コンテンツフラグメントをAdobe Experience Managerでローカライズおよび翻訳する方法を説明します。 コンテンツフラグメントに関連付けられた混在メディアアセットも、抽出および変換できます。 |
| 2021 年 3 月 | [エクスペリエンスフラグメント](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/experience-fragments-feature-video-use.html) | ビデオ | エクスペリエンスフラグメントを使用して、コンテンツ作成者がサイトページやサードパーティ製システムを含む複数のチャネルでコンテンツを再利用する方法について説明します。 |
| 2021 年 3 月 | [強化された検索検索ブースト](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/search-and-discovery/search-boost.html?lang=ja) | ビデオ | 検索ブーストについて説明します。 |

### Experience Manager に関するその他のヘルプリソース

* [Adobe Experience Manager as a Cloud Service のガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/landing/home.html)
* [Experience Manager 6.5 のラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)
* [Experience Manager 6.4 のラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-4.html)
* [Experience Manager 6.3 のラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [Experience Manager 6.2 のラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-2.html)
* [Cloud Manager ユーザガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Experience Manager ドキュメントの以前のバージョン](https://helpx.adobe.com/jp/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/ja-JP/dynamic-media-classic/using/home.html)

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 最新の製品リリース

リリースされた最新の機能、改善点、修正点について詳しくは、

* [Campaign Standard リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html)
* [Campaign Classic リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html)。

>[!IMPORTANT]
>
>[Adobe Campaign Classicに必要な構成の更新](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/acc-config-updates.html?lang=en)について説明します。

### 新しい Campaign コースとチュートリアル

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | ソリューション | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 23 日（PT） | [配信品質 — 配信品質の指標](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/metrics-overview.html) | Campaign Classic/標準 | 監視する主要な配信品質指標と、評価の問題を特定するためのそれらの指標の使用方法について説明します。 |
| 2021 年 2 月 23 日（PT） | [配信品質 — バウンス](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bounces.html) | Campaign Classic/標準 | バウンスのタイプについて説明します。 |
| 2021 年 2 月 23 日（PT） | [配信品質 — 苦情](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/complaints.html) | Campaign Classic/標準 | ユーザーが、不要または予期しない E メールであることを指摘した場合に登録される、苦情について説明します。 |
| 2021 年 2 月 23 日（PT） | [配信品質 — スパムトラップ](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/spam-traps.html) | Campaign Classic/標準 | バウンスのタイプについて説明します。 |
| 2021 年 2 月 23 日（PT） | [配信品質 — 一括およびブロック](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bulking-and-blocking.html) | Campaign Classic/標準 | ISP が E メールメッセージをバルクフォルダーに入れたりブロックしたりする理由について説明します。 |
| 2021 年 2 月 23 日（PT） | [配信品質 —トランジションプロセス — インフラストラクチャ](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/infrastructure.html) | Campaign Classic/標準 | 電子メールインフラストラクチャを適切に構築するために必要な要件を学びます。 |
| 2021 年 2 月 23 日（PT） | [配信品質 — 関与](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/engagement.html) | Campaign Classic/標準 | エンゲージメントの様々なタイプと、配信品質に関してエンゲージメントが重要な理由について説明します。 |
| 2021 年 2 月 23 日（PT） | [配信品質 —トランジションプロセス：ターゲット条件](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/targeting-criteria.html) | Campaign Classic/標準 | 関与の少ないオーディエンスをロールインする前に、Get Goから肯定的な評価を確立して、信頼を効果的に構築する方法を説明します。 |
| 2021 年 2 月 23 日（PT） | [配信品質 —トランジションプロセス — IP暖機中のISP固有の考慮事項](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/isp-specific-considerations-during-ip-warming.html) | Campaign Classic/標準 | ISPプロバイダがトラフィックを調べる際に持つ様々な規則と方法について説明します。 |
| 2021 年 2 月 24 日（PT） | [配信品質 — 第1インプレッション — 概要](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/introduction.html) | Campaign Classic/標準 | 電子メールプログラムが成功するように設定する方法について説明します。その際に、最初の印象を明確にする必要があります。 |
| 2021 年 2 月 24 日（PT） | [配信品質 —トランジションプロセス：ボリューム](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/volume.html) | Campaign Classic/標準 | 送信量が電子メールキャンペーンの配信品質に与える影響を理解します。 |
| 2021 年 2 月 24 日（PT） | [配信品質 — 第1インプレッション — 収集とリストの増加に対応](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html) | Campaign Classic/標準 | 新しい電子メールアドレスの最適なソースは何か、高いデータ品質を確保する方法、および法的ガイドラインに沿った配置方法について説明します。 |
| 2021 年 2 月 25 日（PT） | [配信品質 — 最初のインプレッション — お知らせメール](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html) | Campaign Classic/標準 | ウェルカム戦略の主な要素を学ぶ。 |
| 2021 年 2 月 25 日（PT） | [配信品質 —トランジションプロセス：電子メールプラットフォームの切り替え](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/switching-email-platforms.html) | Campaign Classic/標準 | 電子メールプラットフォームを切り替える際のスムーズなトランジション方法を説明します。 |
| 2021 年 2 月 26 日（PT） | [配信品質 — 最適な配信品質を実現するためのコンテンツのベストプラクティス](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/content-best-practices-for-optimal-delivery.html) | Campaign Classic/標準 | 電子メールの内容を配信品質に最適化するためのヒントです。 |
| 2021 年 2 月 26 日（PT） | [配信品質 — 送信者の永続性](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/sender-permanence.html) | Campaign Classic/標準 | 一貫性のある送信ボリュームを確立することが重要な理由を説明します。 |
| 2021 年 2 月 26 日（PT） | [配信品質 — 継続的な監視](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/ongoing-monitoring.html) | Campaign Classic/標準 | 配信を監視する際に注意する必要がある問題を把握する。 |
| 2021 年 2 月 26 日（PT） | [配信品質 — 実際の状態](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/putting-it-in-practice.html) | Campaign Classic/標準 | 成功への4つの重要な柱。 |
| 2021 年 3 月 10 日（PT） | [リーダー、ビジネスユーザー、管理者向けの配信品質のベストプラクティス](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.deliverability) | Campaign Classic | マーケティングプログラムを確実に成功させるための主要な配信品質用語、概念、およびアプローチについて説明します。 |

### ヘルプリソース

* Adobe Campaign Standard：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/campaign-standard-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/overview.html) - [リリース計画](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-planning.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/campaign-classic-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-classic-learn/tutorials/overview.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/documentation-updates.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/control-panel/using/release-notes.html) - [Campaign Standard](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/ja-JP/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) のハウツービデオ

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

以下は、Adobe Advertising Cloud のリリースノートです。

* [Advertising Cloud DSP の新機能](#adcloud-dsp)
* [Advertising Cloud Search の新機能](#adcloud-search)

### [!DNL Advertising Cloud DSP] の新機能 {#adcloud-dsp}

最終更新日：**2020 年 10 月 28 日（PT）**

| 機能 | 説明 |
| -----------| ---------- |
| 新規ヘルプ | （10 月 28 日のリリース）レガシーのヘルプは更新されたページに置き換えられました。ページは DSP のメインメニューの「ヘルプ」リンクから利用でき、[https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=ja](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=ja)でいつでも利用できます。 |
| キャンペーン | （10 月 28 日のリリース）以前の Campaign ベータ版のビューがデフォルトの Campaign ビューになり、より迅速なインサイト、簡素化されたワークフロー、カスタマイズされたビューを実現しました。 |
| プライベート在庫 | （10 月 15 日のリリース）すべてのユーザーが、新しい Deal ID フォームを使用して、Deal ID の詳細を設定および編集できるようになりました。これは、従来の [!UICONTROL Smart Ad Serving] フォームをシンプルにしたバージョンです。新しい Deal ID の詳細を設定するには、**[!UICONTROL Inventory／Deals]** に移動し、「**[!UICONTROL Create]**」をクリックしてから、「**[!UICONTROL Deal ID Beta]**」をクリックします。 |
| プレースメントの予測 | （10 月 15 日のリリース）プレースメントレベルのペーシングを使用したプレースメントの場合、プレースメント設定の「[!UICONTROL Forecast]」セクションには、新しい「[!UICONTROL Estimated Maximums]」セクションが含まれます。このセクションは、現在のターゲット設定でどれくらい多くの容量が使用できるかを示します。 |

### [!DNL Advertising Cloud Search] の新機能 {#adcloud-search}

最終更新日：**2022年3月29日、3月27日リリース**

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL キャンペーンの検索]<br> レポート | (Microsoft広告キャンペーン)Microsoftの広告キャンペーンのデフォルトの入札戦略である、Microsoftの強化されたコストパークリック(eCPC)入札戦略で、入札サポートが利用できるようになりました。 お使いのキャンペーンに対して、キャンペーンレベルの[!UICONTROL 入札戦略]を指定できるようになりました。 [!UICONTROL 手動CPC]と[!UICONTROL 拡張CPC]が含まれます。 [!UICONTROL 拡張CPC]は、検索、既存の動的検索広告、およびショッピングキャンペーンで使用できます。<br>eCPCを持つキャンペーンを最適化されたAdvertising Cloudポートフォリオに追加すると、Advertising Cloudは基本入札を最適化し、「キャンペーン予算の上限を自動調整」オプションが有効な場合はキャンペーン予算を最適化します。Microsoftはすべての入札調整を適用し、ユーザークエリ時に、Advertising Cloudが生成した入札を独自のデータとインサイトに基づいて変更する場合があります。<br>「 [!UICONTROL 入札] 戦略カスタム」列は、  キャンペーンビューとレポートで使用できます。 |
| [!UICONTROL キャンペーンの検索]<br> [!UICONTROL 隔壁シート] | (Microsoft広告キャンペーン)拡張テキスト広告に対して、3つ目のヘッドライン（[!UICONTROL 広告タイトル3]）と2つ目の説明（[!UICONTROL 説明2]）をオプションでサポートするようになりました。 サポートは[!UICONTROL 広告]表示と[!UICONTROL 一括送信シート]で入手できます。 |
| [!UICONTROL 広告インサイト] | 新しい[!UICONTROL 広告インサイト]が2つあります。<ul><li>[!UICONTROL 遅延売上高]:ポートフォリオのコンバージョンの遅延（SEMクリックから後続のコンバージョンまでの経過時間）を測定し、遅延による重み付け売上高、ROI、モデル精度の違いを示します。</li><li>[!UICONTROL クエリのクロスマッチ]:Googleが複数のクエリに一致した検索キーワードのインスタンスを検索し、トラフィックを誘導する場所の提案を示します。</li></ul> |

### Advertising Cloud チュートリアルとコース

更新日：**2021 年 2 月 23 日（PT）**

| チュートリアル | 説明 |
| -----------| ---------- |
| [Workspace とレポートの概要](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-analysis-workspace-a4adc.html?lang=ja) | Adobe Analytics Analysis Workspace で、Advertising Cloud のデータを使用して視覚的なレポートを作成する方法を説明します。 |

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

最新のリリース情報については、Magento Commerce および Open Source の[リリースノート](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)を参照してください。

## ![アイコン](/assets/target.png)[!DNL Target] {#target}

最新のリリース情報については、[[!DNL Target]  リリースノート](https://docs.adobe.com/content/help/ja-JP/target/using/release-notes/target-release-notes.html)を参照してください。

## ![アイコン](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーのすべてのステージにわたるエンゲージメントを通じてカスタマーエクスペリエンスを変革しようとしている経営陣や B2B マーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

最新のリリース情報については、[!DNL Marketo Engage] [リリースノート](https://docs.marketo.com/display/public/DOCS/Release+Notes)を参照してください。

### 予定されている機能

今四半期を通じて、次の機能がリリースされます。

| 機能 | 説明 |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>新しいアカウントベースのセグメント化</li><li>ダッシュボード固有のフィルターの保存</li><li>Bizbile ダッシュボードを PDF 形式で書き出し</li></ul> |
| Sales Connect | ウィンドウとコマンドセンターの構成の更新／機能強化 |

### 廃止

* **アセット API &quot;_method&quot; パラメーター：** 2020 年 9 月以降、アセット API エンドポイントでは、URI の長さ制限を回避するために、POST 本文にクエリパラメーターを渡す `_method` を使用できなくなります。
* **Internet Explorer のサポートの廃止：** 2020 年 7 月 31 日（PT）のリリース以降、Marketo Engage ユーザーインターフェイスは Internet Explorer でサポートされなくなります。

## ![アイコン](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat ラーニングハブ](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign ラーニングハブ](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Creative Cloud エンタープライズ版 {#creative-cloud}

Creative Cloud エンタープライズ版の新しいチュートリアル。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年3月 | [固有のユーザーライセンスについて](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/nameduserlicensing.html) | 記事 | 固有のユーザーライセンスの重要性について説明します。 |
| 2021 年 3 月 5 日 | [シリアル番号の有効期限](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/cceserial.html) | ビデオ | エンドユーザーが引き続きAdobeのアプリケーションやサービスにアクセスできるようにするために必要な手順を説明します。 |
| 2021年3月 | [ランディングの導入と管理 — サポートするアセット](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/overview-deploy.html) | ビデオ | Enterprise向けCreative Cloudが、カスタム導入と柔軟なライセンスの真のアップをサポートし、他のAdobeのエンタープライズ製品と連携する方法を説明します。 |
| 2021 年 3 月 5 日 | [Adobe Stockベクトルのイラストレーションの色のカスタマイズ](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/customizecolors.html) | ビデオ | 見栄えのす追加るイラストを使って、あらゆるプロジェクトに磨きをかける。 Adobe Stockで最適なベクトルを探し、Adobe Illustratorを使用してプロジェクトのパレットの色を一致させます。 |
| 2021 年 3 月 5 日 | [Adobe Stockプレゼンテーションテンプレートをカスタマイズして、プロフェッショナルな外観で目を引く](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/presentationtemplate.html) | ビデオ | Adobe Stockの画像やテンプレート、使いやすい特殊効果を使用して、数分で美しいスタイルのプレゼンテーションを作成できます。 |
| 2021 年 3 月 5 日 | [読み込み画面のアニメーションをAdobe StockとXDでカスタマイズする](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/loadingscreen.html) | ビデオ | Adobe Stockのベクトルアートワークをカスタマイズして、モバイルアプリ用のチリング読み込み画面のアニメーションを作成します。 |
| 2021 年 3 月 5 日 | [Adobe Stockの画像を使ってリアルな合成写真を作成する](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/realisticcomposite.html) | ビデオ | Adobe Stockの素晴らしい写真を2枚集めて、人々をソーシャル投稿に引き込みます。 |
| 2021 年 3 月 5 日 | [Adobe Stockを使えば、素晴らしい雰囲気の板をすぐに作れる](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/moodboard.html) | ビデオ | 情報、アイデア、ビジュアルおよびカラーパレットをチームやクライアントに伝えるためのプロジェクトムードボードを作成します。 |
| 2021 年 3 月 5 日 | [美しいグラデーションとAdobe Stockアセットを使用して、まとまったブランド画像を作成します。](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/brandgradients.html) | ビデオ | Adobe Stock向けに編集可能なベクトルを使用して、アニメーションをニュースレターグラフィックに取り込みます。 |
| 2021 年 3 月 5 日 | [Adobe StockとPhotoshopを使った電子メール向けアニメーションの作成](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/animationemail.html) | ビデオ | Adobe StockとPhotoshopでのストップアクションアニメーションによる電子メールの機能強化。 |
| 2021 年 3 月 5 日 | [Adobe StockとXDでインタラクティブな観光写真を作成する](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/interactivetourismphoto.html) | ビデオ | Adobe StockとXDを使用して、Webサイトのプロトタイプ内にインタラクティブな写真をすばやく作成できます。 |

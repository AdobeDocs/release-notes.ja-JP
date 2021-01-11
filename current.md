---
title: Adobe Experience Cloud リリースノート
description: Adobe Experience Cloud リリースノート
doc-type: release notes
last-update: January 2021
author: mfrei
translation-type: tm+mt
source-git-commit: 5175e3e92bd445254532c614bda3f7a048f31a86
workflow-type: tm+mt
source-wordcount: '6419'
ht-degree: 42%

---


# Adobe Experience Cloud リリースノート - 2021 年 1 月

![バナー](/assets/experience-cloud-banner-3.png)

このページでは、[!DNL Adobe Experience Cloud] の新機能、修正点および重要な注意事項について説明します。また、Experience Cloud を最大限に活用するための新しいドキュメント、トレーニングコース、ビデオチュートリアルも紹介しています。

>[!NOTE]
>
>毎月[Adobe優先度製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)を購読して、このページの更新に関する電子メール通知を受信します。 このページは1か月を通じて管理されるので、Adobeのエンタープライズ製品とExperience Leagueのドキュメントの更新については、定期的にご確認ください。

最新の更新：**2020年1月11日**

* [Adobeシステムの状態](#status) （未更新）
* [Experience Cloud サービスと管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) および [Customer Journey Analytics](#cust-journey) (リリース日：**2021 年 1 月 14 日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo) (更新日： **2021年1月11日**)
* [Document Cloud](#doc-cloud)

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/?lang=ja-JP#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。コンテンツは`docs.adobe.com`からこの場所に移動されました。 ブックマークは適宜更新してください。

## ![アイコン](/assets/adobe.png) Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

今月は更新はありません。

最新のリリース情報については、[Adobe システムステータス — 2020 年 5 月 21 日](https://docs.adobe.com/content/help/ja-JP/release-notes/experience-cloud/previous/2020/05212020.html#status)を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud サービスと管理 {#ecloud}

[Experience Cloudサービスと](https://docs.adobe.com/content/help/ja-JP/core-services/interface/experience-cloud.html) 管理ドキュメントには、顧客属性、オーディエンスライブラリ( Peopleservice)、アクティベーション、ユーザーと製品の管理、およびExperience Cloudcookieが含まれます。

今月は更新はありません。

最新のリリース情報について詳しくは、「[Experience Cloud サービスに関するこれまでのリリースノート](https://docs.adobe.com/content/help/ja-JP/core-services/interface/release-notes/release-notes.html)」を参照してください。

## ![アイコン](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Experience PlatformとExperience Platform Launchに関するリリースの更新情報が含まれます。

| 機能 | リリース日 | 説明 |
| ------- | ------| ------- |
| Experience Platformに対する製品内サポートのインタラクションの強化 | 2021 年 1 月 15 日 | Experience Platformインターフェイスを離れることなく、Experience Platformに関する質問や問題の報告を行えるようになりました。 **[!UICONTROL ヘルプ]** > **[!UICONTROL サポート]** > **[!UICONTROL サポートチケットを作成]**&#x200B;に移動し、問い合わせ先を入力して、サポート案件をカスタマーサポートに直接送信します。 ケースIDが記載された電子メール通知が届き、カスタマーサポートチームから、必要に応じてチケットを通じて連絡が取れます。 |

最終更新日：**2020 年 12 月 9 日**

以下に適用される最新の更新については、[Experience Platformリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)を参照してください。

* [!UICONTROL データフロー]
* [!UICONTROL Data Science Workspace]
* [!UICONTROL ソース]

### Experience Platform Launch

Platform Launch について詳しくは、[Experience Platform Launch リリースノート](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html)を参照してください。

### Adobe Mobile

iOSバージョン4.21.0

一般 — SDKは、既存のインテルアーキテクチャのサポートを維持しながら、新しいApple M1アーキテクチャでハードウェアをサポートするために、[!DNL XCFrameworks]を使用して配布されました。

* 重要：AdobeMobile [!DNL XCFrameworks]にアップグレードするには、Xcode 12.0以降が必要です。
* 重要：[!DNL Cocoapods]を使用する場合、AdobeMobile [!DNL XCFrameworks]にアップグレードするには[!DNL Cocoapods] 1.10.0以降が必要です。

### Experience Platform とサービスのチュートリアルとコース

Experience Platform およびサービス用に公開された新しいビデオ、チュートリアル、またはコース。

更新日：**2021年1月6日**

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 23 日 | [和集合スキーマの概要](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/union-schemas-overview.html) | ビデオ | Adobe Experience Platformのリアルタイム顧客プロファイルが使用する和集合スキーマについて説明します。 |
| 2020 年 12 月 22 日 | [マルチエンティティセグメントの作成](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-multi-entity-segments.html) | ビデオ | Adobe Experience Platformのセグメントビルダーで複数エンティティのセグメントを作成する方法を説明します。 |
| 2020 年 12 月 21 日 | [オファーアクティビティの作成](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-offer-activities.html) | ビデオ | [!UICONTROL Offer Decisioning]でオファーアクティビティを作成する方法を説明します。 オファーアクティビティは、プレースメントとコレクションを1つのエンティティに結合するので、最も関連性の高いオファーを顧客に提供することを決定できます。 |
| 2020 年 12 月 21 日 | [コレクションの作成](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-collections.html) | ビデオ | [!UICONTROL Offer Decisioning]でコレクションを作成する方法を説明します。 コレクションは、論理グループ内のオファーの管理に使用され、Offer Decisioningアクティビティの作成に必要です。 |
| 2020 年 12 月 21 日 | [意思決定APIでオファーを提供する](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/deliver-offers-with-the-decisions-api.html) | ビデオ | Decisions APIで[!UICONTROL Offer Decisioning]オファーを配信する方法を説明します。 |
| 2020 年 12 月 15 日 | [パーソナライズされたオファーの作成](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-personalized-offers.html) | ビデオ | [!UICONTROL Offer Decisioning]でパーソナライズされたオファーを作成する方法を説明します。 |
| 2020 年 12 月 15 日 | [フォールバックオファーの作成](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-fallback-offers.html) | ビデオ | [!UICONTROL Offer Decisioning]でフォールバックオファーを作成する方法を説明します。 |
| 2020年12月14日（更新） | [リアルタイム顧客プロファイル](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/understanding-the-real-time-customer-profile.html) | ビデオ | このビデオでは、Adobe Experience Platformがリアルタイム顧客プロファイルをアセンブルおよび更新する方法、およびこれらのプロファイルにアクセスして使用する方法を説明します。 |
| 2020 年 12 月 10 日 | タグを作成します。[](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-tags.html)  | ビデオ | [!UICONTROL Offer Decisioning]でタグを作成する方法を説明します。 タグは、オファーのオプションの構築ブロックコンポーネントです。 これらを使用して、オファーを整理し、動的なコレクションにグループ化できます。 |
| 2020 年 12 月 9 日 | [Offer Decisioningでのルールの作成](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-rules.html) | ビデオ | [!UICONTROL Offer Decisioning]でルールを作成する方法を説明します。 ルールは、プラットフォームの[!UICONTROL リアルタイム顧客プロファイル]のイベントと属性を使用して作成され、オファーの適格性の制約を形成します。 |
| 2020 年 12 月 9 日 | [配置の作成](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-placements.html) | ビデオ | Offer Decisioningで配置を作成する方法を学びます。 配置は、電子メール内の画像やWebサイトのHTMLコードなど、コンテンツタイプとチャネルの組み合わせです。 |
| 2020年10月29日（更新） | [Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/demo-of-offer-decisioning.html?lang=ja-JP) | ビデオ | 企業がアドビの [!UICONTROL Offer Decisioning] サービスを使用して、オファーを定義および管理、リアルタイム顧客データを活用、顧客が期待する適切なエクスペリエンスを提供する方法を説明します。 |
| 2020年10月26日（更新） | [Offer Decisioning の紹介](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/introduction-to-offer-decisioning.html) | ビデオ | このビデオでは、Adobe Experience Platform 上に構築されたアプリケーションサービス、[!UICONTROL Offer Decisioning] の概要を説明します。このビデオでは、[!UICONTROL Offer Decisioning] が解決するビジネス上の課題、その主な機能、基本的なアーキテクチャ、主な使用例について説明します。 |
| 2020年10月26日（更新） | [Salesforce CRMソースコネクタを使用したデータの取り込み](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | ビデオ | Salesforce CRMソースコネクタを使用すると、Salesforce CRMからAdobe Experience Platformのリアルタイム顧客プロファイルおよびエクスペリエンスデータレークにデータを簡単にバッチでき、シームレスで拡張性の高い方法で取り込むことができます。 |
| 2020年10月13日（更新） | [Salesforce CRMソースコネクタを使用したデータの取り込み](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | ビデオ | Salesforce CRMソースコネクタを使用すると、Salesforce CRMからAdobe Experience Platformのリアルタイム顧客プロファイルおよびエクスペリエンスデータレークにデータを簡単にバッチでき、シームレスで拡張性の高い方法で取り込むことができます。 |
| 2020年10月23日（更新） | [データをリアルタイムの顧客プロファイルに導く](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html) | ビデオ | リアルタイムのお客様プロファイルにより、お客様の遍歴の各段階を通じて、チャネル間のパーソナライゼーションを大幅に実現します。 |
| 2020年10月13日（更新） | [Attribution AI の設定](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-attribution-ai.html) | ビデオ | Attribution AI のインスタンスを作成して、マーケティングチャネルやキャンペーンが及ぼす影響を理解する方法について説明します。 |
| 2020年10月13日（更新） | [Customer AI の設定](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-customer-ai.html) | ビデオ | 顧客 AI のインスタンスを作成して、顧客の行動を予測する方法について説明します。 |

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Adobe Experience Platformを使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネル全体にわたって顧客の遍歴を調整します。

### 新しい製品リリース

* 11月のリリース — [詳細情報](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#november-release)
* 10月のリリース — [詳細情報](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#october-release)

### Journey Orchestration の追加リソース

[ドキュメント](https://docs.adobe.com/content/help/ja-JP/journeys/using/journey-orchestration-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2021 年 1 月 14 日**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)
* [Report Builder](#arb)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | [一般公開](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| ----------- | ---------- | ------- |
| Analysis Workspace  — コンポーネントの選択 | 2021 年 2 月 5 日 | [!UICONTROL クイックインサイト]にあるドロップダウン/ドロップゾーンコンポーネントは、[!UICONTROL ワークスペース]のすべてのドロップゾーンに追加されました。 この機能強化により、互換性のあるコンポーネントのドロップダウンリストから選択したり、スペースをドロップゾーンとして引き続き使用したりできます。 |
| Analysis Workspace — 画像URL | 2021 年 1 月 14 日 | 公開画像URLを参照することで、[!UICONTROL Workspace]プロジェクトに画像を追加できます。 |

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | [一般公開](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| ----------- | ---------- | ----- |
| [!UICONTROL デバイス]および[!UICONTROL 地理的]ディメンション | 2020 年 10 月 30 日 | これらのディメンションは、Adobe Analytics[!UICONTROL ソースコネクタ]の[グローバル参照](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-usecases/global-lookups.html?lang=en#use-global-lookups-with-adobe-data-connector-datasets)サポートプロジェクトの一部として、デフォルトで使用できるようになりました。 この多くの要望をいただいた追加により、[Adobe Analytics と CJA の間のパリティ](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-overview/cja-aa.html?lang=en#cja-overview)が増加しました。 |
| ジャーニーIQ:[!UICONTROL クロスチャネル分析] | 2021 年 1 月 11 日 | ジャーニーIQ:[!UICONTROL クロスチャネル分析]を使用すると、Experience Platformデータレーク内のAdobe Analytics（または他の）イベントデータセットをID名前空間間で再キーできます。 通常、これは、cookie ベースの ID から人物ベースの ID にイベントデータセットを再入力することを意味します。このようにして、再キー設定されたデータセットをCJA接続で他の人ベースのデータと組み合わせることができ、Analysis Workspaceでのクロスチャネルおよびクロスデバイス分析が可能になります。 [詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/cca/overview.html?lang=ja-JP#cja-connections) |
| Analysis Workspace — コンポーネントの選択 | 2021 年 2 月 5 日 | [!UICONTROL クイックインサイト]にあるドロップダウン/ドロップゾーンコンポーネントは、[!UICONTROL ワークスペース]のすべてのドロップゾーンに追加されました。 この機能強化により、互換性のあるコンポーネントのドロップダウンリストから選択したり、スペースをドロップゾーンとして引き続き使用したりできます。 |
| Analysis Workspace — 画像URL | 2021 年 1 月 14 日 | 公開画像URLを参照して、画像をWorkspaceプロジェクトに追加できます。 |

### Adobe Analytics の修正点 {#aa-fixes}

* WorkspaceでダウンロードしたCSVレポートのフォーマット、ダウンロード、送信に関する問題を修正。 (AN-224844)
(AN-240295)
* Analyticsレポートスイートにデータが含まれていても、モバイル属性のデータがライブストリームに表示されない問題を修正しました。 （AN-241169）
* リアルタイムレポートにデータが表示されない問題を修正しました。 （AN-242477）
* Reports &amp; Analyticsで、_次を含む_&#x200B;フィルターを使用するとデータが表示されない問題を修正しました。 （AN-237354）
* Adobe Analyticsから削除したセグメントがキャンペーンデータコネクタで引き続き使用される問題を修正しました。 （AN-236713）
* 予定レポートがレポートキューで動かなくなる問題を修正しました。 (AN-242599、AN-242554、AN-242900、AN-243329)
* Reports &amp; Analyticsの共有ターゲットレポートの問題を修正しました。 （AN-234638）
* 棒グラフにWorkspaceでデータが表示されない問題を修正しました。 （AN-232127）
* お客様がAdobe Analyticsにログインできない問題を修正しました。 (AN-241882 AN-238802)
* モバイルデバイスレポートが更新され、Samsung Galaxy Z Fold2 5Gが含まれるようになりました。 （AN-238246）
* Workspaceの予定レポートでエラーが発生する問題を修正しました。 （AN-236707、AN-243449）
* データソースファイルがFTPで取得されない問題を修正しました。 （AN-240347）
* [!UICONTROL Advertising Analytics]にアクセスしようとするとエラーが発生する問題を修正しました。 （AN-241478）
* 分類FTPからファイルが取得されない問題を修正しました。 （AN-242490）
* WorkspaceでのUIレンダリングエラーを修正しました。 （AN-243123）
* SFTPサーバーからファイルを受け取れないというData Warehouseの問題を修正。 （AN-244679）
* [!UICONTROL 管理者]/[!UICONTROL ログ]/[!UICONTROL 使用状況およびアクセスログ]にある[!UICONTROL レポート]のダウンロードリンクが機能しない問題を修正しました。 （AN-238058）

#### その他の Adobe Analytics の修正点

AN-204659;AN-221726;AN-230949;AN-231984;AN-232835; AN-233989;AN-235593;AN-235989;AN-236823;AN-236840;AN-237168;AN-237262;AN-237265;AN-237633;AN-237740;AN-238523;AN-238870;AN-238941;AN-239414;AN-239649;AN-239652;AN-239676;AN-239703;AN-240184;AN-240219;AN-240412;AN-240530;AN-240609;AN-240625;AN-240664;AN-240682;AN-240715;AN-241052;AN-241077;AN-241112;AN-241149;AN-241578;AN-241714;AN-242157;AN-242485;AN-242535;AN-242573;AN-242608;AN-242728;AN-242818;AN-242820;AN-242963;AN-242978;AN-243013;AN-243054;AN-243105;AN-243172;AN-243181;AN-243255;AN-243326;AN-243418;AN-243449;AN-243463;AN-243507;AN-243518;AN-243519;AN-243598;AN-243805;AN-243814;AN-243910;AN-243929;AN-244009;AN-244012;AN-244105;AN-244121;AN-244137;AN-244188;AN-244225;AN-244305;AN-244357;AN-244363;AN-244419;AN-244607;AN-244695;AN-244713;AN-244828;AN-244843;AN-244876;AN-244877;AN-245388;AN-245470

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| 必要な[!UICONTROL Report Builder]の更新 | 2021 年 1 月 8 日 | 2021年4月30日までに、すべての[!UICONTROL Report Builder]ユーザーは、[!UICONTROL Report Builder]アドインをバージョン5.6.47以降に更新する必要があります。 このバージョンには、ログインプロセスに対する重要な更新が含まれています。 バージョン5.6.47以降にアップデートしないユーザーは、2021年4月30日を過ぎるとサインインできなくなります。 [!UICONTROL Report ] Builderバージョン5.6.47以降では、Experience Cloudログインのみがサポートされ、SiteCatalystのシングルサインオンや標準ログインなどの従来のログインはサポートされません。詳しくは、[Report Builderサインイン](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/report-builder-setup/login.html?lang=en#section_6D54B8ADAE7F416BB83F5082B3771CFA)を参照してください。 |
| 3つのAnalytics APIサービスの提供終了 | 2021 年 1 月 6 日 | 2021年4月30日に、以下のAnalyticsレガシーAPIサービスが提供終了日に達する予定で、サービスが停止されます。 これらのサービスを使用して構築された現在の統合は、その日に機能しなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>お客様の質問に対する回答と進め方に関するガイダンスの提供に役立つ[従来のAPI EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)を提供しました。 これらのサービスを使用するAPI統合は、[1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email)や[2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)に移行できます。 従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email#) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| すべての受信 HTTPS リクエストの対する HSTS ヘッダーの追加 | 2020 年 9 月 30 日 | 2020 年 9 月 30 日に、HTTPS を使用するすべての受信リクエストに対して、HSTS ヘッダーの追加を開始しました。これは、将来のすべてのリクエストを、セキュリティ上のベストプラクティスと考えられる HTTPS でおこなうようにブラウザー／クライアントに指示します。現時点では、HTTP を使用した受信リクエストについては、これはおこないません。 |
| [!UICONTROL Experience CloudIDサービス] cookie設定に変更 | 2020 年 9 月 23 日 | Chrome バージョン 80 のプライバシー設定に対する更新は、Google AMP ページを表示する一部のユーザーをトラッキングするための Adobe Analytics の機能に影響します。特に、Google がホストする AMP ページを表示するユーザーのクロスドメイントラッキングを妨げます。この結果、ユニーク訪問者数に影響する可能性があります。この修正を利用すると、その ECID Cookie の設定を変更することで、この問題に対処できます。<br>現在、Analytics は、（Chrome の 80 より前のバージョンでクロスドメイントラッキングを許可する）設定 `SameSite = Lax` により、Experience Cloud ID サービス（ECID）Cookie を設定しています。これは、今後は適用されません。この変更により、ユーザーは、ECID Cookie 用の SameSite 設定を `None` に更新できます。<br>これによって、より多くの状況で Analytics Cookie が共有される可能性がありますが、Analytics Cookieには機密情報は含まれていないことに留意してください。また、この設定を選択する場合、データが HTTPS 接続経由でのみ渡されるように、Cookie が `Secure` に設定されている必要があります。この変更をおこなう場合は、カスタマーケアのサポート対象ユーザーがチケットを開いてください。 |
| `omniture.com` ドメインから `adobe.com` ドメインの移行 | 2020 年 8 月 22 日 | 2020 年 8 月 13 日、Adobe Analytics はフロントエンドアーキテクチャを `omniture.com|http://omniture.com/` から `adobe.com|http://adobe.com/` に移行しました。この変更により、2020 年 5 月 28 日の初回統合製品ドメインの変更後に発生したサードパーティ Cookie の問題が改善される可能性があります。このアップデートの結果、新しい `.adobe.com|http://an.adobe.com/` ドメインまたは `experience.adobe.com|http://experience.adobe.com/` ドメインを信頼するようにブラウザーが促す場合があります。 |
| Ad Hoc Analysis Java 8 の互換性のアップデート | 2020 年 8 月 22 日 | Ad Hoc Analysis は現在、Java 8 バージョン 1.8.0_261 以降と互換性がありません。このツールへのアクセスが[提供終了日](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)に達する前に中断されないようにするため、1.8.0_261 以前の Java 8 バージョンを維持することをお勧めします。 |
| Adobe Data Connectors の EOL | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] は、実行不可能またはサポート対象外のレガシーテクノロジーによって動作します。[Adobe Exchange パートナープログラム](https://partners.adobe.com/exchangeprogram/experiencecloud)には、引き続き提供およびサポートを希望する統合に対して採用する新しい標準があります。正式な終了日はまだ決定していませんが、今後 12 ～ 18 か月（2021 年中旬 ～ 2021 年末）になると予想されています。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/import/dataconnectors/data-connectors-eol.html) |
| Ad Hoc Analysis のサポート終了 | 2018 年 8 月 7 日 | アドビは、2021 年 3 月 1 日に Ad Hoc Analysis のサポートを終了する意向を表明しました。詳しくは、[Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) を参照してください。 |

### AppMeasurement {#appm}

AppMeasurement リリースの最新の更新については、[AppMeasurement for JavaScript リリースノート](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/appmeasurement-updates.html)を参照してください。

### Report Builder {#arb}

| 機能 | [一般公開](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| ----------- | ---------- | ----- |
| Analytics [!UICONTROL Report Builder]へのログインの更新 | 2021 年 1 月 14 日 | [!UICONTROL Report Builder]のログインプロセスの改善により、従来のテクノロジーへの依存性が取り除かれ、ログインプロセスがAdobe Experience Cloudと連携します。 Experience Cloudサインインを使用すると、Adobe IDまたはEnterprise ID（シングルサインオン）を使用してAdobe Experience Cloudにサインインできます。 2021年4月30日までに、すべての[!UICONTROL Report Builder]ユーザーは、[!UICONTROL Report Builder]アドインをバージョン5.6.47以降に更新する必要があります。 [!UICONTROL Report ] Builderバージョン5.6.47以降では、Experience Cloudのサインインのみがサポートされ、SiteCatalystのシングルサインオンや標準のサインインなど、従来のサインインはサポートされません。詳しくは、[Report Builderサインイン](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/report-builder-setup/login.html?lang=en#section_6D54B8ADAE7F416BB83F5082B3771CFA)を参照してください。 |

### Analytics ヘルプリソース

* [Adobe Analytics製品ドキュメントとTutorials](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![アイコン](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager の新機能、修正点、ドキュメントおよびチュートリアルです。

<!-- ### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixed an issue in the Predictive Audience feature where some users were unable to delete any of their models, even if no segments were mapped to the models. (AAM-55881)
* Fixed an issue where some users were unable to delete traits or segments which had been used as baseline for deleted predictive audience models. (AAM-56476)
* We continued making accessibility improvements across the interface. (AAM-53215) -->

### 新しい Audience Manager コースとチュートリアル {#tutorials-aam}

新しく公開された Audience Manager ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 15 日 | [ロールベースのアクセス制御を使用した権限の設定](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/user-management/setting-permissions-with-role-based-access-control.html?lang=en#setup-and-admin) | ビデオ | グループレベルで権限を管理し、特性、セグメント、宛先およびモデルなど、アセットを表示および操作するユーザーを制御する方法について説明します。 権限グループを設定し、ユーザーを追加します。 |

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

>[!NOTE]
>
>アドビでは、[Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html)を頻繁に確認して、リリース情報に関する最新情報を入手することを推奨します。

### 製品のアップデート

* **AEM 6.5.7.0**
AEM 6.5、Service Pack 7（2020年11月26日リリース）は、AEM 6.5の一般リリース(GA)以降にリリースされた新機能、お客様向けの主な機能強化、パフォーマンス、安定性、セキュリティの向上を含む重要なアップデートです。
   * [リリースノート](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en#service-pack)
   * [AEM Forms リリース成果物](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **AEM 6.4.8.3**
AEM 6.4、Service Pack 8、Cumulative Fix Pack 3（2020年11月26日リリース6.4.8.3）は重要なアップデートで、AEM 6.4、Service Pack 8(6.4.8.0)の一般リリース（2020年3月）以降の社内およびお客様向けの修正が含まれています。
   * [リリースノート](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
   * [AEM Forms リリース成果物](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

### 製品リリース

* **AEM as a Cloud Service**

   AEM as a Cloud Service の新機能

   * **Adobe Experience Manager Sites as a Cloud Service**
      * [コンテンツフラグメントHTTP API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html):HTTP 追加 APIを使用して、 [!UICONTROL コンテンツ] フラグメントのバリエーションを追加/更新および削除する機能。
   * **Adobe Experience Manager Assets as a Cloud Service**

      * 現在、Adobe InDesign Serverとの統合は、[!UICONTROL Cloud Service]としてExperience Managerできます。 Adobe InDesign Serverスクリプティングを使用してAdobe InDesignファイルを処理する自動化機能を提供し、アセットテンプレートを使用してパンフレットや広告を作成できるようにします。 Adobe Managed ServicesによってホストされるInDesign Serverのみが、[!UICONTROL Cloud Service]としてのExperience Managerに対してサポートされます。
      * [!UICONTROL 接続されたアセット]機能を使用したリモートExperience Managerサイト展開でアセットが使用された場合、アセット参照を追跡および表示するExperience Managerが強化されました。 アセットの[!UICONTROL プロパティ]ページに新しい[!UICONTROL 参照]タブが追加され、アセットのローカル参照とリモート参照がリストされるようになりました。 この参照により、DAMユーザーは[!UICONTROL サイト]ページおよび[!UICONTROL アセット]内の複合アセットでのアセットの使用状況を追跡できます。
[接続されたアセットの設定と使用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/use-assets-across-connected-assets-instances.html)を参照してください。
      * [!UICONTROL 動的な] Mediacapabilitiesは、SiteSimageベースのコアコンポー  ネントを介してアクセスできるようになりました。作成者は、Webページの作成時に[!UICONTROL 画像プリセット]、[!UICONTROL スマート切り抜き]、[!UICONTROL 画像修飾子]を使用するように、コンポーネントをすばやく設定できます。
[コアコンポーネント2.13.0リリース](https://github.com/adobe/aem-core-wcm-components/releases/tag/core.wcm.components.reactor-2.13.0)を参照してください。
      * Experience Managerデスクトップアプリでは、ファイルやフォルダーをアップロードする際に、デスクトップアプリケーションインターフェイス上のWindowsエクスプローラーまたはMac Finderからファイルをドラッグできます。
詳しくは、[デスクトップアプリを使用したアセットの追加](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/using.html?lang=en#upload-and-add-new-assets-to-aem)を参照してください。
   * **Adobe Experience Manager Commerce as a Cloud Service**

      * 最新のCIFコアコンポーネントバージョンv1.6.0が含まれるCIFベニアリファレンスサイト — 2020.12.01のリリースです。
[CIFベニアリファレンスサイト](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2020.12.01)を参照してください。
      * CIFコアコンポーネントv1.6.0をリリースしました。
[CIFコアコンポーネント](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.6.0)を参照してください。
   * **Cloud Manager**

      * [SSL証明書](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/manage-ssl-certificates/introduction.html)と[カスタムドメイン名](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/custom-domain-names/introduction.html)のセルフサービス管理。
      * [IP許可リスト](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/ip-allow-lists/introduction.html)のセルフサービス管理。
      * 環境の詳細ページが更新され、環境上の[!UICONTROL カスタムドメイン名]と[!UICONTROL IP許可リスト]を管理できるようになりました。
   * **コードリファクタリングツール**

      * AIO-CLIプラグインの新しいバージョンがリリースされました。 このプラグインの最新バージョンには、AEM Dispatcher ConverterとRepository Modenizerのバグ修正が含まれ、新しいユーティリティであるIndex Converterもサポートされています。
このプラグインの詳細については、[統合エクスペリエンス](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/refactoring-tools/unified-experience.html#benefits)を参照してください。
      * Index Converterは、Cloud Service互換のOAKインデックス定義として、顧客のカスタムOAKインデックス定義をAEMに変換するために使用できるユーティリティです。
「[インデックスコンバータ](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/index-converter)」を参照してください。
      * [Repository Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer)に追加された新機能。すべてのOSGi設定を含む個別のパッケージ`ui.config`を作成します。





[AEM as a Cloud Service リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)を参照してください。

### セルフサービス

**[!DNL Experience Manager as a Cloud Service]**

新機能に関するドキュメントの更新は、上記のリンクからご利用いただけます。 その他のドキュメントの更新内容は次のとおりです。

* **ベストプラクティスアナライザ**

   * [!UICONTROL Cloud Readiness ] Analyzerは、 [!UICONTROL BPA(] ベストプラクティスアナライザ)に変更されました。BPAは、現在のAEM実装のベストプラクティスの評価を提供し、既存のAEMインスタンスからAEMに[!UICONTROL Cloud Service]として移行する準備を評価するのに役立ちます。

* **財団**

   * ワークフロー — ワークフローインスタンスの検索に、[!UICONTROL ワークフロータイトル]、[!UICONTROL ワークフローモデル]、[!UICONTROL ステータス]、[!UICONTROL 開始者]、[!UICONTROL ペイロードパス]、[!UICONTROL 開始日&lt;a111/>.
]「[検索ワークフローインスタンス](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/administering/workflows-administering.html#administering)」を参照してください。
   * 発行層ユーザーデータの同期 —プロファイル属性やグループのメンバーシップを含むユーザーデータは、発行層に保持できます。
[登録、ログイン、ユーザープロファイルに関するドキュメント](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/personalization/user-and-group-sync-for-publish-tier.html#authoring)を参照してください。

### [!DNL Experience Manager] フォーム

6.5.7.0リリースに含まれる次の機能に関するドキュメントを使用できます。

* Service Packのインストール後に、サーバー側の検証とアダプティブフォーム変換のPDFをより高速に実行できます。

* アダプティブフォームのレイアウトモードで、すべてのサイズ変更を取り消し、各コンポーネントにデフォルトのレイアウトを適用できるようになりました。 詳しくは、[レイアウトモードを使用したコンポーネントのサイズ変更](https://experienceleague.adobe.com/docs/experience-manager-65/forms/adaptive-forms-basic-authoring/resize-using-layout-mode.html?lang=en)を参照してください。

* [!DNL Experience Manager Forms] フォームデータモデルを使用して、データソースとしてRESTful Webサービスとの統合時に、接続管理用のHTTPクライアント設定が含まれるようになりました。[データソースの設定](https://experienceleague.adobe.com/docs/experience-manager-65/forms/form-data-model/configure-data-sources.html?lang=en#configure-relational-database)を参照してください。

### コミュニティ

**2021年1月のExperience Leagueの最新のAdobe Experience Managerコンテンツ**  — 特集ビデオ、記事、チュートリアル、コースの [包括的なリストはこちら](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/td-p/392549)。

### 新しい Experience Manager コースとチュートリアル

更新日：**2021年1月10日**

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 7 日 | [フラグメント参照を使用した高度なデータモデリング](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/fragment-references.html) | 記事 | Adobe Experience Manager(AEM)とGraphQLの使い始めに 高度なデータモデリングで[!UICONTROL フラグメント参照]機能を使用し、2つの異なる[!UICONTROL コンテンツフラグメント]の間に関係を作成する方法を説明します。 GraphQLクエリを変更して、参照モデルのフィールドを含める方法を学びます。 |
| 2020 年 12 月 7 日 | [外部アプリからGraphQLを使用したクエリAEM](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | 記事 | Adobe Experience Manager(AEM)とGraphQLの使い始めに AEM GraphQL APIを参照し、サンプルのWKND GraphQL Reactアプリを参照してください。 この外部アプリがAEMに対してGraphQL呼び出しを行い、体験を強化する方法を説明します。 基本的なエラー処理を実行する方法を説明します。 |
| 2020 年 12 月 7 日 | [GraphQL APIの参照](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | 記事 | Adobe Experience Manager(AEM)とGraphQLの使い始めに 組み込みのGraphQL IDEを使用してAEM GraphQL APIを調べます。 コンテンツフラグメントモデルに基づいてAEMがGraphQLスキーマを自動的に生成する方法を説明します。 GraphQL構文を使用して、基本的なクエリを作成してみてください。 |
| 2020年12月 | [コンテンツフラグメントのオーサリング](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/author-content-fragments.html) | 記事 | Adobe Experience Manager(AEM)とGraphQLの使い始めに [!UICONTROL コンテンツフラグメントモデル]に基づいて、新しいコンテンツフラグメントを作成し、編集します。 [!UICONTROL コンテンツフラグメント]のバリエーションを作成する方法を説明します。 |
| 2020 年 12 月 7 日 | [コンテンツフラグメントモデルの定義](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/content-fragment-models.html) | 記事 | Adobe Experience Manager(AEM)とGraphQLの使い始めに AEMでコンテンツをモデル化し、コンテンツフラグメントモデルを使用してスキーマを構築する方法について説明します。 既存のモデルを確認し、新しいモデルを作成します。 スキーマの定義に使用できる様々なデータタイプについて説明します。 |
| 2020 年 12 月 9 日 | [APIの互換性](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/developer-reference-material-apis.html) | 記事 | 様々な[!UICONTROL Assets]操作で使用できるAEM API(npm、Java、HTTP)を明確に伝える簡単な記事を作成します。 |
| 2020 年 12 月 2 日 | [コンテンツフラグメントのダウンロード](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html?lang=ja-JP) | ビデオ | コンテンツフラグメントのダウンロード機能の概要を示します。 |
| 2020 年 12 月 7 日 | [コンテンツフラグメントの編集機能](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html) | ビデオ | [!UICONTROL コンテンツフラグメント]エディターの高度な機能に関する概要ビデオです。 [!UICONTROL コンテンツフラグメント]との注釈とバージョン比較の使い方を説明します。 |
| 2020 年 12 月 4 日 | [政府発行ドキュメントのバーコードを含む/含まないOCRデータ抽出](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/ocr-data-extraction.html?lang=en#some-useful-integrations) | 記事 | 運転免許証やパスポートなど、政府発行のドキュメントからデータを抽出し、アダプティブフォームに入力します。 |
| 2020 年 12 月 14 日 | [AEM Headless with GraphQLの概要](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/overview.html) | ビデオ | Adobe Experience ManagerまたはAEMで実装されたGraphQL APIの概要を示します。 AEMのGraphQL APIは主に、ヘッドレスデプロイメントの一環として、[!UICONTROL Content Fragment]データをダウンストリームアプリケーションに配信するように設計されています。 |
| 2020 年 12 月 16 日 | [Dynamic Mediaコアコンポーネント](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/dynamic-media-core-components.html) | ビデオ | Experience Managerコアコンポーネントの一部であるイメージコンポーネントは、Dynamic Mediaの組み込みサポートを備えています。 画像コンポーネントを使用して、AEM Sitesページ上で、画像プリセット、スマート切り抜き、画像修飾子など、Dynamic Mediaの機能をコンテンツ作成者が使用できるようにする方法について説明します。 |

### Experience Manager リリース情報

Experience Manager のリリースノートはすべて次のページに記載されています。

* [Experience Manager リリースのアップデートとロードマップ](https://docs.adobe.com/content/help/ja-JP/experience-manager-release-information/aem-release-updates/home.html)
* [AEM as a Cloud Service リリース情報](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [自動フォーム変換サービスリリースノート](https://docs.adobe.com/content/help/ja-JP/aem-forms-automated-conversion-service/using/release-notes.html)
* [AEM 6.5 Service Pack リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [AEM 6.4 Cumulative Fix Pack リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-64/release-notes/cfp-release-notes.html)
* [AEM Assets Dynamic Media リリースノート](https://docs.adobe.com/content/help/ja-JP/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [AEM Brand Portal リリースノート](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [AEM デスクトップアプリケーションリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-desktop-app/using/release-notes.html)
* [AEM Dispatcher リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Livefyre リリースノート](https://docs.adobe.com/content/help/ja-JP/livefyre/using/release-notes/c-rn.html)

### AEM のその他のヘルプリソース

* [AEM as a Cloud Service ガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-2.html)
* [Cloud Manager ユーザガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/jp/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/ja-JP/dynamic-media-classic/using/home.html)

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 新しい製品リリース

Campaign Classic、Campaign Standard、コントロールパネルのリリース情報

#### Campaign Classic

<!-- [Incident Response Bulletin](https://helpx.adobe.com/security/products/campaign/apsb21-04.html) (January 12) -->

* 20.3.3 リリース — [詳細情報](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* 20.3.1 リリース — [詳細情報](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* 20.2.4 リリース — [詳細情報](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-2.html#release-20-2-4-build-9187)
* 20.1.4 リリース — [詳細情報](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-1.html#release-20-1-4-build-9126)
* 19.2.4 リリース — [詳細情報](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-2.html#release-19-2-4-build-9082)
* 19.1.8 リリース — [詳細情報](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-8-build-9039)

#### Campaign Classicゴールド標準

* Gold Standard 11リリース — [詳細情報](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/gs-release/gold-standard.html?lang=en#gs-11)

### ヘルプリソース

* Adobe Campaign Standard：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/campaign-standard-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/overview.html) - [リリース計画](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-planning.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/campaign-classic-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-classic-learn/tutorials/overview.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/documentation-updates.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/control-panel/using/release-notes.html)- [Campaign Standard](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/ja-JP/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) のハウツービデオ

#### 新しい Campaign コースとチュートリアル

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | ソリューション | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 23 日 | [動的コンテンツの設定](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/configuring-dynamic-content.html#sending-messages) | Campaign Classic | （ビデオ）動的コンテンツの様々なタイプを理解し、パーソナライゼーションブロックや条件ステートメントを作成して配信に適用する方法を学びます。 |
| 2020 年 12 月 9 日 | [コントロールパネル - Google TXT レコード管理](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/subdomains-and-certificates/google-txt-record-management.html#subdomains-and-certificates) | Campaign Standard | （ビデオ）[!UICONTROL キャンペーンCampaign コントロールパネル]を使用してGMAILアドレスに電子メールを送信するために使用するすべてのサブドメインに、Google TXTサイト検証レコードを追加する方法を説明します。 |

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

以下は、Adobe Advertising Cloud のリリースノートです。

* [Advertising Cloud DSP の新機能](#adcloud-dsp)
* [Advertising Cloud Search の新機能](#adcloud-search)

### [!DNL Advertising Cloud DSP] の新機能 {#adcloud-dsp}

最終更新日：**2020年10月28日**

| 機能 | 説明 |
| -----------| ---------- |
| 新規ヘルプ | （10 月 28 日のリリース）レガシーのヘルプは更新されたページに置き換えられました。ページは DSP のメインメニューの「ヘルプ」リンクから利用でき、[https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=ja-JP](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=ja-JP) でいつでも利用できます。 |
| キャンペーン | （10 月 28 日のリリース）以前の Campaign ベータ版のビューがデフォルトの Campaign ビューになり、より迅速なインサイト、簡素化されたワークフロー、カスタマイズされたビューを実現しました。 |
| プライベート在庫 | （10 月 15 日のリリース）すべてのユーザーが、新しい Deal ID フォームを使用して、Deal ID の詳細を設定および編集できるようになりました。これは、従来の [!UICONTROL Smart Ad Serving] フォームをシンプルにしたバージョンです。新しい Deal ID の詳細を設定するには、**[!UICONTROL Inventory／Deals]** に移動し、「**[!UICONTROL Create]**」をクリックしてから、「**[!UICONTROL Deal ID Beta]**」をクリックします。 |
| プレースメントの予測 | （10 月 15 日のリリース）プレースメントレベルのペーシングを使用したプレースメントの場合、プレースメント設定の「[!UICONTROL Forecast]」セクションには、新しい「[!UICONTROL Estimated Maximums]」セクションが含まれます。このセクションは、現在のターゲット設定でどれくらい多くの容量が使用できるかを示します。 |

### [!DNL Advertising Cloud Search] の新機能 {#adcloud-search}

最終更新日：**2020年10月17日**

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL キャンペーンの検索] | 「[!UICONTROL Accounts]」表示では、[!UICONTROL Access] 列にいつ [!DNL Advertising Cloud Search] が有効な検索エンジンアカウントにログインできないかが示されるようになりました。エラーの原因を確認するには、警告アイコンの上にマウスポインターを置いたままにします。 |
| [!UICONTROL Custom Alerts] | 以前の [!UICONTROL Alerts Beta] は、現在は [!UICONTROL Custom Alerts] と呼ばれています。 |
| [!UICONTROL カスタムアラート] | Custom Alerts では、以前の期間の指標から指定した日付範囲でいつ指標が増加または減少したかを特定するワークフローがシンプル化され、「[!UICONTROL Filters]」タブに移動しました。 |

### Ad Cloud チュートリアルとコース

更新日：**2020 年 12 月 2 日**

| 公開日 | 名前 | ソリューション | 説明 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 11 月 14 日 | [Adobe Analytics と Advertising Cloud ダッシュボードの作成](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-dashboards-a4adc.html?lang=ja-JP) | ビデオ | ライブキャンペーン監視用の Advertising Cloud ダッシュボードを作成する方法。 |
| 2020 年 11 月 14 日 | [Advertising Cloud サイト入口レポートの作成](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-site-entry-a4adc.html?lang=ja-JP#analytics) | ビデオ | 曜日、時間帯、ブラウザー、および地理的な影響を監視する Advertising Cloud サイトエントリレポートを作成します。 |
| 2020 年 11 月 14 日 | [Advertising Cloud データを使用した Analytics カスタム指標の作成](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-custom-metrics-a4adc.html?lang=ja-JP#analytics) | ビデオ | Adobe Analytics 内で Advertising Cloud データを使用する場合に作成するのに便利なカスタム指標。 |
| 2020 年 11 月 14 日 | [アクティベーションおよびレポート用の Analytics セグメントの作成](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-segments-a4adc.html?lang=ja-JP#analytics) | ビデオ | Advertising Cloud ディメンションを使用したレポートと分析に優れたセグメントの作成。 |
| 2020 年 11 月 14 日 | [Predictive Audiences について](https://experienceleague.corp.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html?lang=ja-JP#build-and-manage-audiences) | ビデオ | このビデオでは、Audience Manager の Predictive Audiences の概要とその仕組みの詳細を説明し、使用例を示します。 |
| 2020 年 11 月 14 日 | [Advertising Cloud のアクティベーションおよびレポート用の Analytics プロファイルの作成](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-profiles-a4adc.html?lang=ja-JP#analytics) | ビデオ | Adobe Analytics を使用して、Advertising Cloud リマーケティング用の堅牢なサイトリターゲティングプールを作成する方法。 |
| 2020 年 11 月 14 日 | [Advertising Cloud マーケティングチャネルを使用したレポート](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-reporting-a4adc.html?lang=ja-JP#analytics) | ビデオ | Advertising Cloud のビュースルーおよびクリックスルーエントリデータが Adobe Analytics マーケティングチャネルと連携する仕組みを紹介します。 |
| 2020 年 11 月 14 日 | [Adobe Analytics を使用した、開始前キャンペーン分析の作成](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-pre-launch-a4adc.html?lang=ja-JP) | ビデオ | Adobe Analytics を使用して Advertising Cloud 有料メディアキャンペーンの開始の基盤を設定する方法。 |

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

Magent リリースノートについては、以下を参照してください。

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![アイコン](/assets/target.png)[!DNL Target] {#target}

最新のリリース情報については、[[!DNL Target]  リリースノート](https://docs.adobe.com/content/help/ja-JP/target/using/release-notes/target-release-notes.html)を参照してください。

## ![アイコン](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーの各ステージを通じてエンゲージメントをおこなうことで顧客体験を変えようとしているリード管理や B2B マーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

最新のリリース情報については、[!DNL Marketo] [リリースノート](https://docs.marketo.com/display/public/DOCS/Jan+%2721)を参照してください。

### 予定されている機能

今四半期を通じて、次の機能がリリースされます。

| 機能 | 説明 |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>新しいアカウントベースのセグメント化</li><li>ダッシュボード固有のフィルターの保存</li><li>Bizbile ダッシュボードを PDF 形式で書き出し</li></ul> |
| Sales Connect | ウィンドウとコマンドセンターの構成の更新／機能強化 |

### 廃止

* **アセット API &quot;_method&quot; パラメーター：** 2020 年 9 月以降、アセット API エンドポイントでは、URI の長さ制限を回避するために、POST 本文にクエリパラメーターを渡す `_method` を使用できなくなります。
* **Internet Explorer のサポートの廃止：** 2020 年 8 月 1 日のリリース以降、Marketo Engage ユーザーインターフェイスは Internet Explorer でサポートされなくなります。

これまでのリリースノートと過去のリリースノートについては、[Marketo リリースノート](https://docs.marketo.com/display/public/DOCS/Release+Notes)を参照してください。

## ![アイコン](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Adobe Document Cloud のリリース情報およびヘルプリソースです。

### Acrobatチュートリアル

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 29 日 | [ページの整理](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/organize.html) | 記事 | PDFのページの追加、置換、抽出、回転、削除、移動を行うには、AcrobatDocument Cloudの「[!UICONTROL ページを整理]」を使用します。 |
| 2020 年 12 月 29 日 | [入力可能なフォームの作成](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/create-fillable-forms.html) | 記事 | InDesign、Microsoft WordやExcelで作成したスキャン済みの紙のフォームやドキュメントを、入力可能なPDFフォームに変換します。 |
| 2020 年 12 月 29 日 | [スキャンとOCR](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/scan-and-ocr.html) | 記事 | ドキュメントのスキャン画像や画像を、検索可能で編集可能なPDFファイルに変換し、結果のファイルの品質を調整します。 |
| 2020 年 12 月 28 日 | [アクセシブルなPDFファイルの準備](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility.html) | 記事 | PDFファイルを作成します。 |
| 2020 年 12 月 28 日 | [フォームデータの操作](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/formdata.html) | 記事 | 完成した一連のフォームがあり、データをコンパイルする必要がある場合は、AcrobatDCを使用して、回答を単一のスプレッドシートに結合できます。 |
| 2020 年 12 月 28 日 | [ファイルサイズの縮小と最適化](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/reduce.html) | 記事 | 共有、投稿、アーカイブの品質を損なうことなく、大きなファイルを減らし、PDFを最適化します。 |
| 2020 年 12 月 21 日 | [PDF署名欄のアクセシビリティ向上](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/by-industry/gov/pdfs/making-pdf-ballots-accessible.html) | ウェビナー | スクリーンリーダーなどの支援テクノロジーを使用するユーザーが投票を読み、完了するのに必要な、PDFへのアクセシビリティの主な領域について説明します。 |
| 2020 年 12 月 21 日 | [Redact &amp; Sanitize](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/redact.html) | 記事 | PDFから個人情報や機密情報を完全に削除したり、ドキュメントを不要なものから削除するには、修正ツールを使用します。 |
| 2020 年 12 月 18 日 | [Action Wizard](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/action.html) | 記事 | 1つまたは複数のファイルに一連のコマンドを自動的に適用するアクションを作成します。 |
| 2020 年 12 月 15 日 | [特性有効期限と有効期限(TTL)設定の設定](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/configuring-trait-expiration-with-the-time-to-live-ttl-setting.html?lang=en#build-and-manage-audiences) | ビデオ | [!UICONTROL 有効期間]の使い方を学びます。これは、指定された期間内に再資格を得ない場合に、特性のメンバーシップの有効期限となります。 |
| 2020 年 12 月 4 日 | [Adobe PDFツールAPIを使用したPDFファイルのOCR](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/ocr.html) | 記事 | [!UICONTROL 光学式文字認識]を使用して、スキャンしたPDFのロックを解除し、テキストを抽出して検索可能なファイルを作成する方法を学びます。 |
| 2020 年 12 月 4 日 | [Adobe PDFツールAPIおよびJava使用の手引き](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartedjava.html) | 記事 | 使用可能なすべてのWebサービスにアクセスするために用意されたサンプルファイルを実行できる状態で、開発者は数分で作業を開始できます。 このチュートリアルでは、PDFツールJava SDKを使用してサンプルを実行する開始のすべての手順を説明します。 |
| 2020 年 12 月 4 日 | [Adobe PDFツールAPIおよび.Netの使い始めに](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartednet.html) | 記事 | 使用可能なすべてのWebサービスにアクセスするために用意されたサンプルファイルを実行できる状態で、開発者は数分で作業を開始できます。 このチュートリアルでは、PDF Tools .Net SDKを使用してサンプルを実行する開始のすべての手順を説明します。 |
| 2020 年 12 月 4 日 | [PDFツールAPIを活用してWord、PowerPointなどにExport PDF](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/exportpdf.html) | 記事 | PDFファイルをMS Wordに変換して、コンテンツの編集、承認、後で署名の送信を行い、カスタム契約ワークフローを作成します。 または、PDFコンテンツをMS Excel形式にエクスポートして、請求書や財務計算、データ分析を行うこともできます。 |
| 2020 年 12 月 4 日 | [PDFツールAPIとNode.jsを使用して、HTMLまたはMS Officeから数分でPDFを作成する](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/createpdffromhtml.html) | 記事 | 新しいAdobe PDFツールAPIを使用したドキュメントワークフローのデジタル化について説明します。 このAPIは、複雑なビジネスワークフローのニーズに対応するために、複数の強力なPDF操作サービスを自由に選択できるAPIです。 |

### 新しい Adobe Sign コースとチュートリアル

新しく公開された Adobe Document Cloud ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 22 日 | [給与保護](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/expand/recipes/gov/usecasegovpaycheck.html) | デモ | Adobe Signを使用して、支払い保護プログラムフォームをオンラインのインタラクティブフォームに変換する方法をご覧ください。 |

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat ラーニングハブ](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja-JP)
* [Adobe Sign ラーニングハブ](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja-JP)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

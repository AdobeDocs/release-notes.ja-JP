---
title: Experience CloudとExperience Platformに関するリリースノート
description: Experience CloudとExperience Platformに関する最新のリリースノート、新機能および新しいドキュメントについて説明します。 EnterpriseおよびDocument CloudのCreative Cloudに関する新しいヘルプとチュートリアルをご覧ください。
doc-type: release notes
last-update: February 2021
author: mfrei
translation-type: tm+mt
source-git-commit: b785653a7f35f188c17f2ed05ec7a8b143c192b4
workflow-type: tm+mt
source-wordcount: '6381'
ht-degree: 33%

---


# Adobe Experience Cloud リリースノート - 2021 年 2 月

![バナー](/assets/experience-cloud-banner-3.png)

Experience Cloudのソリューションとサービスは毎月更新されます。 このページは、[!DNL Experience Cloud]とExperience Platformの最新リリースアップデート、ドキュメント、およびチュートリアルを見つけるための中心的な場所です。 また、[!DNL Creative Cloud for Enterprise]と[!DNL Document Cloud]の新しいドキュメントも見つかります。

>[!IMPORTANT]
>
>このページにはプレリリースコンテンツが含まれ、リリース日より前に変更されることがあります。

>[!NOTE]
>
>毎月[アドビの優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)をサブスクライブして、このページの更新に関する電子メール通知を受信します。 このページは1か月を通じて管理されるので、Adobeのエンタープライズ製品とExperience Leagueのドキュメントの更新については、定期的にご確認ください。

最新の更新：**2021年2月12日**

* [Adobe システムステータス](#status)
* [Experience Cloud サービスと管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [](#analytics) **解析更新日2021年2月20日**
* [Customer Journey Analytics](#cust-journey)`
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud企業](#creative-cloud)

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。

## ![アイコン](/assets/adobe.png) Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

今月は更新はありません。

最新のリリース情報については、[Adobe システムステータス — 2020 年 5 月 21 日（PT）](https://docs.adobe.com/content/help/ja-JP/release-notes/experience-cloud/previous/2020/05212020.html#status)を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud サービスと管理 {#ecloud}

[Experience Cloud サービスと管理](https://docs.adobe.com/content/help/ja-JP/core-services/interface/experience-cloud.html)ドキュメントには、顧客属性、オーディエンスライブラリ（[!UICONTROL People] サービス）、アクティベーション、ユーザーおよび製品管理、Experience Cloud Cookie が含まれます。

**2021 年 2 月 4 日（PT）**

* **サインインの更新：Experience Cloud** を更新すると、Experience Cloudの初回ログインの開始画面が削除されます。2 月 4 日（PT）以降、`https://experience.adobe.com/login` からアドビのログイン画面に直接リダイレクトされるようになります。

## ![アイコン](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Experience Platform と Experience Platform Launch に関するリリース更新情報が含まれます。

* [Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja). (2021 年 1 月 27 日（PT）)
* [Experience Platform Launch リリースノート](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=ja). (2021 年 1 月 13 日（PT）)

### Experience Platformチュートリアルとコース

Experience Platform およびサービス用に公開された新しいビデオ、チュートリアル、またはコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 10 日（PT） | [Azure Blob宛先の構成](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=en#destinations) | ビデオ | リアルタイム顧客データプラットフォーム（リアルタイムCDP）でのAzure Blobストレージ先のセットアップと構成に必要な手順を説明します。 |
| 2021 年 2 月 5 日 | [表示IDグラフ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/view-identity-graphs.html) | ビデオ | IDグラフビューア機能を使用して、検証とデバッグのためにIDグラフを検索、調査およびフィルタリングする方法。 |
| 2021 年 2 月 3 日（PT） | [バッチデータ取り込みの概要](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/batch-ingestion-overview.html) | ビデオ | Adobe Experience Platformでのバッチデータ取り込みの概要です。 APIを使用してバッチデータを取り込む方法を説明します。 |
| 2021 年 2 月 3 日（PT） | [Adobe以外のアプリケーションへのデータのアクティブ化](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/activate-data-to-non-adobe-applications.html) | ビデオ | AdobeのReal-Time CDPが、お客様のオーディエンスとの真のパーソナライゼーション戦略の構築にどのように役立つかを説明します。 また、Microsoft、Google、Facebookの既存のエコシステムと非Adobeアプリにどのように折り込むかを説明します。 |
| 2021 年 1 月 21 日（PT） | [マーケティング担当者向けインテリジェントサービスの使用を開始するためのコースの概要](https://video.tv.adobe.com/v/330805?quality=12&learn=on) | ビデオ | 「Getting Started with Intelligent Services for Marketers」コースの概要を説明します。 |
| 2021 年 1 月 13 日（PT） | [マーケター向けOffer Decisioningの概要](https://video.tv.adobe.com/v/330520?quality=12&learn=on) | ビデオ | また、マーケター向けの「Offer Decisioningの使い始めに」コースの概要を説明します。 |
| 2021 年 1 月 31 日（PT） | [レシピビルダーテンプレートを使用して、モデルのトレーニング、スコア、作成を行います。](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/train-score-and-productize-models.html) | ビデオ | 更新されたレシピビルダーテンプレートを使用して、小売の販売スキーマとデータセットを使用してレシピを作成する方法を説明します。 |
| 2021 年 1 月 31 日（PT） | [JupterLabノートブックにデータを読み込む](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/load-data-in-jupyterlab-notebooks.html) | ビデオ | Data Science WorkspaceのJupyterLabについて説明します。 |
| 2021 年 1 月 12 日（PT） | [結合ポリシーの作成](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/create-merge-policies.html) | ビデオ | Adobe Experience Platformで結合ポリシーを作成する方法を説明します。 |

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Adobe Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

### 最新の製品リリース

最新の機能、改善点、および修正点について詳しくは、[Journey Orchestrationリリースノート](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html)を参照してください。

### 新しい Journey Orchestration コースとチュートリアル

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 1 月 22 日（PT） | [別のジャーニーへのジャンプ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/jumping-to-another-journey.html?lang=ja) | ビデオ | 個人を別のジャーニーに移動させる方法を説明します。 |

### その他のJourney Orchestrationリソース

[ドキュメント](https://docs.adobe.com/content/help/ja-JP/journeys/using/journey-orchestration-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2021 年 2 月 18 日**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)  **更新日2021年2月19日**
* [Analytics コースとチュートリアル](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | [一般公開](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| ----------- | ---------- | ------- |
| Analysis Workspace - コンポーネントの選択 | 2021 年 2 月 5 日 | [!UICONTROL クイックインサイト]にあるドロップダウン／ドロップゾーンコンポーネントは、[!UICONTROL Workspace]のすべてのドロップゾーンに追加されました。 この機能強化により、互換性のあるコンポーネントのドロップダウンリストから選択したり、スペースをドロップゾーンとして引き続き使用したりできます。 |
| Analyticsダッシュボードの言語の選択 | 2021 年 1 月 14 日（PT） | Analyticsダッシュボードで言語を選択できるようになりました。 |

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | [一般公開](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - ターゲット日 | 説明 |
| ----------- | ---------- | ----- |
| Analysis Workspace - コンポーネントの選択 | 2021 年 2 月 5 日 | [!UICONTROL クイックインサイト]にあるドロップダウン／ドロップゾーンコンポーネントは、[!UICONTROL Workspace]のすべてのドロップゾーンに追加されました。 この機能強化により、互換性のあるコンポーネントのドロップダウンリストから選択したり、スペースをドロップゾーンとして引き続き使用したりできます。 |
| CJA API | 2021 年 2 月 18 日（PT） | CJA APIが利用できるようになりました。 これらのAPIを使用すると、コンポーネントをプログラムで編集し、レポートを取得できます。 詳しくは、[CJA APIドキュメント](https://adobe.io/cja-apis/docs)を参照してください。 |

### Adobe Analytics の修正点 {#aa-fixes}

* Adobe Analytics2.0 APIゲートウェイのタイムアウトを300秒（5分）に増やす問題を修正しました。 （AN-232335）
* Workspace、API 2.0、Adobe Report Builderレポートのパフォーマンスの問題を修正しました。(AN-245644、AN-244504、AN-243060)
* Analytics [!UICONTROL データフィード]で追加、****&#x200B;をクリックするとエラーが発生する問題を修正しました。 （AN-243171）
* 分類でデータが分類されない問題を修正しました。 (AN-243823、AN-247049、AN-244114)
* スケジュールされたプロジェクトの問題を修正しました。顧客が所有していたプロジェクトのみを表示できたが、すべてのスケジュールされたプロジェクトは表示できなかった(AN-246955)
* [!UICONTROL ワークスペース]のA4Tパネルで、プロジェクトが開かない問題を修正しました。 （AN-246881）
* [!UICONTROL Workspace]で、A4T [!UICONTROL 計算指標]に関連するエラーがスローされる問題を修正しました。 （AN-247082）
* Data WarehouseAPIリクエストがデータを返さない問題を修正しました。 （AN-236931）
* 親レポートスイートへのアクセスと併せて仮想レポートスイートへのアクセスのみが可能になる問題を修正しました。 （AN-247042）
* プロジェクトを[!UICONTROL Ad Hoc Analysis]から[!UICONTROL ワークスペース]に変換する際にエラーが発生する問題を修正しました。 （AN-221215）
* [!UICONTROL Workspaceプロジェクトマネージャー]に表示されるフィルターされたプロジェクトの数が正しくない問題を修正しました。 （AN-244934）

#### その他の Adobe Analytics の修正点

AN-224987;AN-229009;AN-239750;AN-239765;AN-241620;AN-242996;AN-243577;AN-243774;AN-244509;AN-244746;AN-244763;AN-244868;AN-244960;AN-245016;AN-245097;AN-245727;AN-246141;AN-246283;AN-246340;AN-246532;AN-246669;AN-246744;246763;AN-246892;AN-246898;AN-246961;AN-247643;AN-247048;AN-247134;AN-247758;AN-247774;AN-248179;AN-248226;AN-248297;AN-248300;AN-248303;AN-248376;AN-248495;AN-248647

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| Reports &amp; Analyticsのランディングページオプション | 2021 年 2 月 19 日（PT） | 2021年3月25日に、新しいReports &amp; Analyticsダッシュボードまたはその他のコンテンツを設定するためのオプションが、Adobe Analyticsランディングページとして削除されます。 以前にReports &amp; Analyticsページをカスタムランディングページとして設定した場合、[!UICONTROL ユーザーの環境設定]でランディングページが変更されるまで、このページは引き続き機能します。 2021年3月26日以降、新しいReports &amp; Analyticsカスタムランディングページを定義できなくなりました。 |
| Ad Hoc Analysis のサポート終了 | 2021年1月 | [!UICONTROL Ad Hoc ] Analysisは、2021年3月1日に提供終了日に達します。詳しくは、[Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) を参照してください。 |
| 3 つの Analytics API サービスの提供終了 | 2021 年 1 月 6 日（PT） | 2021 年 4 月 30 日（PT）、以下の Analytics 従来の API サービスの提供が終了し、サービスが停止されます。 これらのサービスを使用して構築された現在の統合は、その日以降使用できなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問への回答、および進め方に関するガイダンスを提供するために、[従来の API EOL に関する FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email#) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| Adobe Data Connectors の EOL | 2020 年 7 月 13 日（PT） | Adobe [!UICONTROL Data Connectors] は、実行不可能またはサポート対象外のレガシーテクノロジーによって動作します。[Adobe交換パートナープログラム](https://partners.adobe.com/exchangeprogram/experiencecloud)で新しい標準が利用できます。 どの統合でも、その標準を使用して、引き続き提供およびサポートできます。 正式な終了日は2021年8月1日です。 [詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/import/dataconnectors/data-connectors-eol.html) |
| すべての受信 HTTPS リクエストの対する HSTS ヘッダーの追加 | 2020 年 9 月 29 日（PT） | 2020年9月29日、Adobeは、HTTPSを使用するすべての着信要求にHSTSヘッダーの追加を開始しました。 このヘッダーは、今後すべての要求をHTTPSで行うようブラウザーまたはクライアントに指示します。これは、セキュリティ上のベストプラクティスと考えられます。 この時点では、Adobeは、HTTPを使用する受信要求に対してこの要求を強制しません。 |
| [!UICONTROL Experience Cloud ID サービス]の Cookie 設定に対する変更 | 2020 年 9 月 22 日（PT） | Chrome バージョン 80 のプライバシー設定に対する更新は、Google AMP ページを表示する一部のユーザーをトラッキングするための Adobe Analytics の機能に影響します。特に、Google がホストする AMP ページを表示するユーザーのクロスドメイントラッキングを妨げます。この結果、ユニーク訪問者数に影響する可能性があります。この修正を利用すると、その ECID Cookie の設定を変更することで、この問題に対処できます。<br>現在、Analytics は、（Chrome の 80 より前のバージョンでクロスドメイントラッキングを許可する）設定 `SameSite = Lax` により、[!UICONTROL Experience Cloud ID サービス]（ECID）Cookie を設定しています。これは、今後は適用されません。この変更により、ユーザーは、ECID Cookie 用の SameSite 設定を `None` に更新できます。<br>この変更により、より多くの状況でAnalytics cookieを共有できますが、Analytics cookieに機密情報が含まれていません。また、この設定を選択する場合、データが HTTPS 接続経由でのみ渡されるように、Cookie が `Secure` に設定されている必要があります。この変更を行う場合、サポート対象ユーザーはカスタマーケアに連絡してチケットをオープンできます。 |

### AppMeasurement {#appm}

AppMeasurement リリースの最新の更新については、[AppMeasurement for JavaScript リリースノート](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/appmeasurement-updates.html)を参照してください。

### Analytics コースとチュートリアル {#tutorials-analytics}

[!DNL Analytics] と [!UICONTROL Customer Journey Analytics] の新しいコース、チュートリアル、記事。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日（PT） | [線のビジュアライゼーションへの近似曲線の追加](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/adding-trendlines-to-line-visualizations.html?lang=en) | ビデオ | [ビジュアライゼーションの設定]で、回帰または移動平均近似曲線を線系列に追加できます。 この機能は、データ内のパターンをより明確に表現するのに役立ちます。 |
| 2021 年 2 月 8 日（PT） | [プラットフォームの起動への導入プラグインの追加](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/implementation/via-adobe-launch/adding-implementation-plug-ins-in-launch.html?lang=en#implementation) | ビデオ | 導入プラグインは、Analytics実装に追加して追加のカスタムデータを追跡できるJavaScriptコードの一部です。 このビデオでは、プラットフォームの起動でコードを追加する方法と場所を学びます。 |
| 2021 年 1 月 6 日（PT） | [Analysis Workspace のメディア同時視聴者数パネル](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/media-concurrent-viewers-panel-in-analysis-workspace.html?lang=en#analysis-workspace) | ビデオ | ピーク同時実行が発生した場所、または下降が発生した場所を把握する。 コンテンツの質とViewerの関与に関する貴重な情報を得ることができます。また、ボリュームと規模のトラブルシューティングや計画に役立ちます。 |

### Analytics ヘルプリソース

* [Adobe Analytics 製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Managerの新機能、修正点、ドキュメント、チュートリアル。

| 機能 | 追加日または更新日 | 説明 |
|----|----|----|
| [Admin Console への Audience Manager ユーザーの移行](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/admin-console-migration.html) | 2021 年 2 月 1 日（PT） | Audience Manager のユーザーアカウント管理が Adobe Admin Console に移行され、すべてのアドビソリューションでエクスペリエンスが効率化されます。<br>ユーザー移行を容易にするには、この記事で説明する手順に従います。すべてのAudience Manager管理者は、できるだけ早急にユーザーアカウントをAdobe Admin Consoleに移行する開始を取る必要があります。 |

### 修正点および改善点 {#aam-fixes-and-improvements}

* [オンボーディングステータスレポート](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html)の問題を修正しました。 この問題では、レポートのレコードとオンボーディングパートナーがアップロードしたファイルのレコードに食い違いがありました。 （AAM-57415）
* **[!UICONTROL 予測オーディエンス]**&#x200B;機能の&#x200B;**[!UICONTROL モデル]**&#x200B;の複製に関する問題を修正しました。 （AAM-56775）
* 特性とセグメントの複製で、間違った特性またはセグメントが重複する問題を修正しました。 （AAM-57351）
* **[!UICONTROL モデル/特性を除外]**&#x200B;の&#x200B;**[!UICONTROL 「すべて]**&#x200B;を選択」チェックボックスがユーザーに対してクリックできなかった問題を修正しました。 （AAM-57366）
* **[!UICONTROL セグメントビルダー]**&#x200B;で、「**[!UICONTROL すべて選択]**」チェックボックスですべての特性が選択されない問題を修正しました。 （AAM-55640）

### 新しい Audience Manager コースとチュートリアル {#tutorials-aam}

新しく公開された Audience Manager ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 5 日（PT） | [ファイルベースのデータを取り込む手順](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/steps-for-ingesting-file-based-data.html?lang=en#integrating-offline-data) | ビデオ | オフラインデータをAudience Managerにオンボードする際に考慮する必要がある手順（データファイルのファイル名要件など）を説明します。 |
| 2021 年 2 月 5 日（PT） | [ファイルベースのデータの形式設定と取り込み](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/formatting-and-ingesting-file-based-data.html?lang=en#integrating-offline-data) | ビデオ | ファーストパーティデータをAudience Managerに取り込み、お客様の理解とターゲットを深める場合、データには特定のフォーマット要件があります。 主なオプションの一部と、詳細情報の入手先について説明します。 |
| 2021 年 2 月 5 日（PT） | [クロスデバイスデータソースの作成と認証](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/data-sources/creating-a-cross-device-data-source-and-authenticating.html?lang=en#setup-and-admin) | ビデオ | ファーストパーティのCRMデータをAudience Managerに取り込む際に、CRM IDとデータを格納するクロスデバイスデータソースを作成する方法を説明します。 このビデオでは、その方法と`setCustomerIDs()`メソッドをログインExperience Platform Launchで設定する方法を紹介します。 |
| 2021 年 2 月 3 日（PT） | [コースの概要 —Audience Managerでのデータアクティベーションの作成と管理](https://video.tv.adobe.com/v/331001) | ビデオ | オーディエンスセグメントは、実際にセグメントを使用しない限り、何の価値もありません。 このコースでは、オーディエンスを使用してユーザーエクスペリエンスをカスタマイズする方法について説明します。 この導入ビデオは、パスでの作業を開始するためのものです。 |
| 2021 年 1 月 28 日（PT） | [特性の作成と管理](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.3) | コース | 製品内[!UICONTROL 特性ビルダー]から[!UICONTROL バルク管理]ツールまでの特性の作成と整理について説明します。 また、[!UICONTROL Data Explorer]ツールを使用して、Audience Managerに入る重要なシグナルを発見し、それらの特徴を作成する方法についても説明します。 |
| 2021 年 1 月 22 日（PT） | [Audience Optimizationレポートを使用したメディアのパフォーマンスの把握](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/using-audience-optimization-reports-to-understand-media-performance.html?lang=en#reports) | ビデオ | Audience Optimizationレポートを使用してキャンペーンを改善する方法、マーケティングに寄与する場所、投資を停止する場所を理解する方法について説明します。 また、最適な周波数制限を決定し、これらのレポートで他の宝石を見つける方法も説明します。 |
| 2021 年 1 月 15 日（PT） | [重複レポートを使用する関連オーディエンスについて](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/understand-related-audiences-with-overlap-reports.html?lang=en#reports) | ビデオ | 重複レポートを使用すると、特性オーディエンスとセグメント訪問者が相互にどのように重なり合うか（複数の特性またはセグメントで同じ）を確認できるので、コンバージョンを増やしたり、リーチの拡大に焦点を当てたりできます。 |
| 2021 年 1 月 12 日（PT） | [データ・エクスポート・ラベルを使用したデータ・フローの制御](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/data-activation/destinations-basics/using-data-export-labels-to-control-data-flow.html?lang=en#data-activation) | ビデオ | データの書き出しラベルには、様々なデータタイプ/ソースのフローを制御するメカニズムがAudience Managerされているので、プライバシー要件を満たすことができます。 データエクスポートコントロールとデータエクスポートラベルを設定する方法と場所を、この点と連携させて説明します。 |
| 2021 年 1 月 22 日（PT） | [Adobe AnalyticsからAudience Managerへのセグメントのインポート](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/import-aa-segments-into-aam.html?lang=en#build-and-manage-audiences) | ビデオ | リアルタイムデータをAdobe AnalyticsからAudience Managerに転送するだけでなく、後処理されたデータを含むセグメントをAnalyticsからExperience Cloud経由でAudience Managerに読み込むこともできます。 |

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

 Experience Manager の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

>[!NOTE]
>
>Adobeは、リリース情報に関する最新の情報を得るために、[Experience Managerリリースの更新情報とロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスすることを推奨します。

### 製品リリース

* **Experience Manager as a Cloud Service**

   Cloud ServiceとしてのExperience Managerの新機能

   * **Experience Manager Assets as a Cloud Service**

      * **ヘッドレスコンテンツ管理サービス**

         * [GraphQL API for Content Fragment配信](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-api-content-fragments.html):GraphQL構文を使用したコンテンツフラグメントのクエリ、およびコンテンツフラグメントモデルに基づくスキーマ（JSON形式で出力）
         * [GraphQL APIリクエストの認証サポート](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-authentication-content-fragments.html):GraphQL APIリクエストをアクセストークンで認証し、サーバ側APIを使用できる。
         * [RemotePageコンポーネント](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html):を使用して、AEM内の外部SPAを表示および編集するためのサポートを追加しました。
         * [AEM内での外部SPAの編集](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html):スタンドアロンのシングルページアプリケーションをAEMインスタンスにアップロードする機能、編集可能なコンテンツセクションを追加する機能、およびオーサリングを有効にする機能が追加されました。
         * JSON形式やロケールでリッチテキストを出力する機能など、GraphQL APIからのJSON出力の強化。
         * コンテンツフラグメントモデルのネストをサポートし、ネストされたコンテンツフラグメント構造を作成できます。このためには、専用のコンテンツフラグメント参照データ型またはコンテンツフラグメント参照を複数行テキストフィールド内にインラインで作成します。
         * 「一意」、「必須」、「変換可能」など、コンテンツフラグメントモデルのデータ型で使用できる検証ルールが増えています。
         * コンテンツフラグメントモデルにタグ付けし、タグまたはパスによるポリシーを持つフォルダー内でコンテンツフラグメントを作成できます。
         * コンテンツフラグメントエディターでの使い勝手の向上（公開アクションや、フラグメントが基づくモデルの表示など）。
         * コンテンツフラグメントエディターでJSON出力を直接プレビューできる機能。
      * **プログレッシブWebアプリ(PWA)**

         * [プログレッシブWeb App(PWA)版の](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/enable-pwa.html?lang=en) サイトは、簡単な設定でプロジェクトレベルで有効にできるようになりました。
   * **Cloud ServiceとしてのExperience Managerアセット**

      * Cloud ServiceとしてのExperience Managerは、スマートタグ機能を拡張して、テキストベースのアセット内のキーワードとエンティティの識別をサポートします。 テキストを識別し、インデックスを作成し、メタデータとして使用できるようにして、設定を行うことなく検索体験を向上させます。 「[スマートタグ](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/smart-tags.html)」を参照してください。
      * MXFファイル形式がサポートされるようになりました。 [サポートされているファイル形式](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/file-format-support.html#video-formats)を参照してください。
   * **Experience Manager Commerce as a Cloud Service**

      * **最新情報?**

         * 製品エクスペリエンス管理：アセットおよびエクスペリエンスフラグメント用の新しい「コマース」プロパティタブ。 このタブでは、製品やカテゴリをアセットやエクスペリエンスフラグメントにリンクできます。 また、このタブには、リンクされた製品/カテゴリのリアルタイムデータと、製品コンソールに詳細を表示するリンクが表示されます。
         * 最新のCIFコアコンポーネントバージョンv1.7.0が含まれるCIFベニアリファレンスサイト — 2021.02.02をリリースしました。詳細は、[CIFベニアリファレンスサイト](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.02)を参照してください。
         * CIF コアコンポーネント v1.7.0 をリリースしました。詳しくは、[CIF コアコンポーネント](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.7.0)を参照してください。
      * **SDK ビルドアナライザー**

         Cloud ServiceSDKビルドアナライザーMavenプラグインとしてのExperience Managerは、Mavenプロジェクト内の問題（依存関係の欠落など）を検出します。 開発者は、ローカル開発中に問題を見つけ、Cloud Managerを使用してCloud環境に展開する前に、問題を見つける機会を得ることができます。

         このリリースでは、2つの新しいアナライザーが追加されました。

         * リポイント分析器
         * bundle-nativecode

         詳しくは、[ドキュメント](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html#developing)を参照してください。
   * **クラウド移行ツール**

      * **コンテンツ転送ツールの新機能**

         * コンテンツ転送ツール — ユーザーマッピングツールに追加された新しい機能とUI。 この機能は、コンテンツ移行アクティビティの一環として、既存のユーザーとグループをAdobeのIdentity ManagementシステムIDに自動的にマッピングします。
「[ユーザーマッピングツールの使用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-user-mapping-tool.html)」を参照してください。
         * コンテンツ転送ツールは、移行セット内で参照されているすべてのグループとユーザーを子も含めて移行するようになりました。
         * 移行セットの作成時に、`/etc`の下の特定のパスを選択できます。







### **コミュニティ**

* **Adobe開発者ライブ2021 |セッションリストの完了**

   一般的なリクエストによって、[ここ](https://adobe.ly/3cldljt)は、Adobe開発者ライブで発生したすべてのExperience Managerセッションの集計リストです。 各セッションの記録とQ&amp;Aは、それぞれのコンテキストスレッドに投稿されます。

* **Experience Leagueでの最新のAdobe Experience Managerコンテンツのリスト | 2021年1月**

   Adobeが作成したデジタルエクスペリエンスの技術コンテンツの正式なソース。 [ここ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)の完全なリストを参照してください。

### Experience Manager リリース情報

Experience Manager のリリースノートはすべて次のページに記載されています。

* [Experience Manager リリースのアップデートとロードマップ](https://docs.adobe.com/content/help/ja-JP/experience-manager-release-information/aem-release-updates/home.html)
* [Cloud Serviceリリース情報としてのExperience Manager](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/release-notes/home.html)
* [Experience ManagerCloud Managerリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [自動フォーム変換サービスリリースノート](https://docs.adobe.com/content/help/ja-JP/aem-forms-automated-conversion-service/using/release-notes.html)
* [Experience Manager6.5 Service Packリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Experience Manager6.4累積Fix Packリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-64/release-notes/cfp-release-notes.html)
* [Experience ManagerAssetsDynamic Mediaリリースノート](https://docs.adobe.com/content/help/ja-JP/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Experience Managerブランドポータルのリリースノート](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ja)
* [Experience Manager デスクトップアプリケーションリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-desktop-app/using/release-notes.html)
* [Experience Managerディスパッチャーリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Livefyre リリースノート](https://docs.adobe.com/content/help/ja-JP/livefyre/using/release-notes/c-rn.html)

### Experience Managerコースとチュートリアル

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 11 日（PT） | [外部アプリケーションからのCloud ServiceとしてのAEMへの認証](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | コース | 外部アプリケーションで、[!UICONTROL ローカル開発アクセストークン]と[!UICONTROL サービス資格情報]を使用して、HTTP経由のCloud ServiceとしてExperience Managerに対してプログラム的に認証する方法を説明します。 |
| 2021 年 2 月 11 日（PT） | [アセットの関連付けと関連付け解除](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) | ビデオ | Experience Manager内のアセット間の関係を確立し、管理する方法について説明します。 |
| 2021 年 2 月 8 日（PT） | [AEM Sites- WKNDチュートリアル](https://docs.adobe.com/content/help/en/experience-manager-learn/getting-started-wknd-tutorial-develop/overview.html) | チュートリアル | Experience Managerを初めて使用する開発者向けのマルチパートチュートリアルへようこそ。 このチュートリアルでは、WKNDの架空のライフスタイルブランドのExperience Managerサイトの導入方法を説明します。 |
| 2021 年 2 月 1 日（PT） | [最初のOSGiバンドルの作成](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/create-your-first-osgi-bundle.html?lang=en) | 記事 | mavenとeclipseを使用して最初のOSGiバンドルを作成する方法を学びます。 |
| 2021 年 2 月 1 日（PT） | [アセットを公開](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/publish.html) | ビデオ | Experience Manager作成者からAEM発行にアセットとそのレンディションを公開する方法を説明します。 |
| 2021 年 2 月 5 日 | [ローカル開発](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/local-development-environment.html) | ビデオ | Experience ManagerをCloud ServiceSDKとして使用して、ローカル開発環境をダウンロードし、設定する方法を説明します。 |
| 2021 年 2 月 5 日 | [プロジェクト構造](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/project-structure.html) | ビデオ | AEM用のExperience ManagerMavenプロジェクトをCloud Serviceとして構築するためのベストプラクティスを紹介します。 |
| 2021 年 2 月 5 日 | [ディスパッチャー設定の移行](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/dispatcher-configuration.html) | ビデオ | ディスパッチャー設定の違いの概要と、Adobe Managed Services(AMS)からCloud ServiceとしてExperience Managerにディスパッチャーを移行するためのヒントとテクニックを紹介します。 |
| 2021 年 2 月 2 日（PT） | [AEM SDKの概要](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/aem-sdk.html) | ビデオ | Cloud ServiceとしてのExperience Manager用SDKの使用と設定 |
| 2021 年 2 月 2 日（PT） | [AEMCloud Serviceとは](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/what-is-aem-as-a-cloud-service.html) | ビデオ | Cloud ServiceとしてのExperience Managerと、他のバージョンのAdobe Experience Managerとの違いを調べます。 |
| 2021 年 2 月 2 日（PT） | [Cloud Managerの役割](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/cloud-manager.html) | ビデオ | [!UICONTROL Cloud Manager]の目的と、Cloud ServiceーとしてのExperience Managerとの連携について説明します。 |
| 2021 年 2 月 2 日（PT） | [Cloud ServiceとしてのAEMの進化](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/evolution.html) | ビデオ | オンプレミスExperience Manager、Adobe Managed Services AEM、およびCloud ServiceとしてのExperience ManagerのExperience Managerの履歴と違いを調べます。 |
| 2021 年 2 月 2 日（PT） | [AEM as a Cloud Service のアーキテクチャ](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/architecture.html) | ビデオ | 基盤となるアーキテクチャと重要なExperience Manager部分をCloud Serviceとして調べます。 Cloud ManagerとAPIについて詳しく説明します。 |
| 2021 年 2 月 2 日（PT） | [Cloud Manager APIの使用](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/cloud-manager-apis.html) | ビデオ | Cloud Manager APIを使用して他のシステムを拡張および統合する方法について説明します。 |
| 2021 年 2 月 2 日（PT） | [テスト結果の分析](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/analyze-test-results.html) | ビデオ | コードのコンパイルエラーを調べ、このコードがCloud ServiceとしてのExperience Managerのベストプラクティスに従っているかどうかを調べます。 |
| 2021 年 2 月 2 日（PT） | [パイプラインを設定](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/configure-pipelines.html) | ビデオ | Cloud Managerで様々なタイプのパイプラインを調べ、プロジェクトを成功させるためのパイプラインの設定方法を確認します。 |
| 2021 年 2 月 2 日（PT） | [ディスパッチャー設定の管理](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/dispatcher-configurations.html) | ビデオ | ベストプラクティスと例を使用して、ディスパッチャーがCloud ServiceおよびCloud ManagerとしてのExperience Managerとどのように連携するかを調べます。 |
| 2021 年 2 月 2 日（PT） | [連続統合とCloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/continuous-integration.html) | ビデオ | Adobeクラウドマネージャーを使用したベストプラクティスと継続的な統合について理解します。 |
| 2021 年 2 月 2 日（PT） | [Cloud Managerを使用した展開のためのAEMプロジェクトの統合](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/merge-projects.html) | ビデオ | Cloud Managerを使用して、複数のプロジェクトを単一のプロジェクトに結合し、Cloud ServiceとしてExperience Managerにデプロイする方法を学びます。 |
| 2021 年 2 月 2 日（PT） | [Cloud Managerプロジェクトのデプロイ](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/deploy-code.html) | ビデオ | Cloud Managerのgitリポジトリを外部gitリポジトリと統合し、プロジェクトをCloud ServiceとしてExperience Managerにデプロイします。 |
| 2021 年 2 月 2 日（PT） | [コンテンツの公開](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/content-publishing.html) | ビデオ | コンテンツ配信の概念やAdobeパイプラインなど、Experience ManagerでのCloud Serviceとしてのコンテンツ公開の仕組みを調べます。 |
| 2021 年 2 月 2 日（PT） | [トークンベースの認証 — サービス資格情報](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials.html?lang=en#authentication) | ビデオ | Cloud ServiceとしてのExperience Managerとの統合のためのトークンベースの認証について説明します。 |
| 2021 年 2 月 2 日（PT） | [複数のFormsに署名](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/introduction.html?lang=en#sign-multiple-documents) | チュートリアル | 住宅ローンを申し込む場合も、新しい銀行口座を開く場合も、複数のフォームに記入して署名する必要があります。 Experience ManagerFormsとAdobe Signの統合により、複数のフォームへの入力と署名が容易になります。 |
| 2021 年 1 月 28 日（PT） | [トークンベースの認証 — ローカル開発アクセストークン](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/local-development-access-token.html?lang=en#authentication) | ビデオ | Experience ManagerのDeveloper Consoleを使用して、開発者が一時アクセストークンを自己生成できる方法を説明します。この一時Experience Managerは、プログラムによってにアクセスする場合に使用できます。 |
| 2021 年 1 月 28 日（PT） | [Cloud ServiceとしてのAEMへのトークンベースの認証](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | ビデオ | 外部アプリケーションが、アクセストークンを使用して、HTTP経由のCloud Serviceとして、プログラムによってExperience Managerを認証し、やり取りする方法を説明します。 |
| 2021 年 1 月 24 日（PT） | [プロセスをトリガーするメインフォームの作成](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/create-initial-form.html) | 記事 | 最初のフォーム（絞り込みフォーム）は、[!UICONTROL 複数のFormsに署名AEM]ワークフローをトリガーして、複数のフォームに署名するために使用されます。 |
| 2021 年 1 月 8 日（PT） | [AdobeCloud Manager CI/CD実稼働パイプラインの実行](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | ビデオ | CI/CD Production Pipeline設定では、パイプラインを開始するトリガー、実稼働環境を制御するパラメータ、パフォーマンステストのパラメータを定義します。 |
| 2021 年 1 月 8 日（PT） | [AdobeCloud Managerアクティビティ](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/activity.html) | ビデオ | Cloud Managerは、プログラムのアクティビティに統合された表示を提供し、本番環境と非実稼働環境の両方で、すべてのCI/CDパイプライン実行を一覧表示します。 この機能を使用すると、現在進行中のパイプラインを表示し、以前のデプロイメントを確認できます。 |
| 2021 年 1 月 8 日（PT） | [AdobeCloud Manager CI/CD非実稼働パイプライン](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-non-production-pipeline.html) | ビデオ | CI/CD非実稼働パイプラインは、コード品質パイプラインと展開パイプラインの2つのカテゴリに分割されます。 コード品質パイプラインは、Gitブランチのすべてのコードをビルドし、Cloud Managerのコード品質スキャンに対して評価するためのものです。 |
| 2021 年 1 月 8 日（PT） | [AdobeCloud Manager CI/CD実稼働パイプラインの設定](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | ビデオ | CI/CD Production Pipeline設定は、パイプラインを開始するトリガーを定義します。パラメータは、実稼働環境の展開とパフォーマンステストのパラメータを制御します。 |
| 2021 年 1 月 8 日（PT） | [AdobeCloud Managerの環境](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/environments.html) | ビデオ | Cloud Managerの環境は、Experience Manager作成者、Experience Manager発行、ディスパッチャーの各サービスで構成されます。 異なる環境は役割をサポートし、異なるCI/CDパイプラインを使用して関与できます。 通常、Cloud Manager環境には、実稼働環境1つ、ステージ環境1つ、開発環境1つがあります。 |
| 2021 年 1 月 8 日（PT） | [ヘッドレスグラフQLの概要](https://internal.adobedemo.com/content/demo-hub/en/demos/internal/aem-headless-graphql.html) | デモ | Experience ManagerのGraphQL APIは、Experience Managerのコンテンツフラグメントからダウンストリームアプリケーションにコンテンツを公開します。 GraphQL APIは、ヘッドレスおよびハイブリッドの両方の使用例で使用できます。 |
| 2021 年 1 月 8 日（PT） | [AdobeCloud Managerのプログラム](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/programs.html) | ビデオ | Cloud Managerのプログラムは、ビジネスイニシアチブの論理的なセットをサポートする一連のExperience Manager環境を表します。通常は、購入したSLA(Service Level Agreement)に対応します。 |
| 2021 年 1 月 8 日（PT） | [トークンベースの認証](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | ビデオ | Cloud Managerのプログラムは、ビジネスイニシアチブの論理的なセットをサポートする一連のExperience Manager環境を表します。通常は、購入したSLA(Service Level Agreement)に対応します。 |
| 2021 年 1 月 8 日（PT） | [一括インポート](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html) | ビデオ | Cloud ServiceとしてExperience Managerされる一括インポートツールを使用すると、管理者は、クラウドストレージ(Azure BlobストレージまたはAmazonS3)からアセットを一括で安全かつ効率的にインポートできます。 |

### Experience Managerに関するその他のヘルプリソース

* [Cloud ServiceガイドとしてのExperience Manager](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/landing/home.html)
* [Experience Manager6.5ラーニングとサポートホーム](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)
* [Experience Manager6.4ラーニングとサポートホーム](https://helpx.adobe.com/jp/support/experience-manager/6-4.html)
* [Experience Manager6.3ラーニングとサポートホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [Experience Manager6.2ラーニングとサポートホーム](https://helpx.adobe.com/jp/support/experience-manager/6-2.html)
* [Cloud Manager ユーザガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Experience Managerドキュメントの古いバージョン](https://helpx.adobe.com/jp/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/ja-JP/dynamic-media-classic/using/home.html)

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 最新の製品リリース

リリースされた最新の機能、改善点および修正点について詳しくは、

* [Campaign Standard リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html)
* [Campaign Classic リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html)

### 新しい Campaign コースとチュートリアル

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | ソリューション | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 5 日（PT） | [ビジネスユーザー向けにAdobe Campaign Classicを使い始める](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.classic) | Campaign Classic | このコースを修了すると、Adobe Campaign Classicの概念と、初めてのマーケティングキャンペーンの作成方法を理解できるようになります。 |
| 2021 年 2 月 1 日（PT） | [マルチチャネルとクロスチャネルの概要](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/introduction-to-cross-and-multi-channel-campaigns.html) | Campaign Classic | マルチチャネルとクロスチャネルのキャンペーンの違い、およびマルチチャネルとクロスチャネルのキャンペーンの使用例を理解します。 |
| 2021 年 2 月 1 日（PT） | [SMS配信の作成](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/sms-channel/create-a-sms-delivery.html) | Campaign Classic | SMS配信の作成方法を説明します。 |
| 2021 年 2 月 1 日（PT） | [チャネル間のキャンペーンの作成](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/cross-channel-campaigns.html) | Campaign Classic | チャネル間のキャンペーンを作成し、実行する方法を説明します。 |
| 2021 年 1 月 29 日（PT） | [コントロール母集団の使用](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/use-control-groups.html) | Campaign Classic | コントロール母集団の概念を理解し、配信にコントロール母集団を使用する方法を学びます。 |
| 2021 年 1 月 28 日（PT） | [配達確認の送信と検証](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/send-and-validate-proofs.html) | Campaign Classic | 配達確認を送信し、検証する方法を説明します。 |
| 2021 年 1 月 28 日（PT） | [配信品質を考慮した電子メールの設計](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/design-emails-for-deliverability.html) | Campaign Classic | 配信品質のベストプラクティスを適用する方法を学びます。 |
| 2021 年 1 月 28 日（PT） | [電子メール配信の作成と設計](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/create-and-design-email-deliveries.html) | Campaign Classic | 電子メール配信を作成するプロセスを理解し、電子メールコンテンツを設計およびパーソナライズする方法を学びます。 |
| 2021 年 1 月 27 日（PT） | [イベントトリガーキャンペーンの作成](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/getting-started/create-event-triggered-campaigns.html) | Campaign Classic | イベントトリガーキャンペーンを作成する方法とその用途を説明します。 |

### ヘルプリソース

* Adobe Campaign Standard：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/campaign-standard-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/overview.html) - [リリース計画](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-planning.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/campaign-classic-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-classic-learn/tutorials/overview.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/documentation-updates.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/control-panel/using/release-notes.html)- [Campaign Standard](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/ja-JP/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) のハウツービデオ

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

以下は、Adobe Advertising Cloud のリリースノートです。

* [Advertising Cloud DSP の新機能](#adcloud-dsp)
* [Advertising Cloud Search の新機能](#adcloud-search)

### [!DNL Advertising Cloud DSP] の新機能 {#adcloud-dsp}

最終更新日：**2020 年 10 月 28 日（PT）**

| 機能 | 説明 |
| -----------| ---------- |
| 新規ヘルプ | （10 月 28 日（PT）のリリース）レガシーのヘルプは更新されたページに置き換えられました。ページは DSP のメインメニューの「ヘルプ」リンクから利用でき、[https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=ja](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=ja-JP)でいつでも利用できます。 |
| キャンペーン | （10 月 28 日（PT）のリリース）以前の Campaign ベータ版のビューがデフォルトの Campaign ビューになり、より迅速なインサイト、シンプルなワークフロー、カスタマイズされたビューを実現しました。 |
| プライベート在庫 | （10 月 15 日（PT）のリリース）すべてのユーザーが、新しい Deal ID フォームを使用して、Deal ID の詳細を設定および編集できるようになりました。これは、従来の [!UICONTROL Smart Ad Serving] フォームをシンプルにしたバージョンです。新しい Deal ID の詳細を設定するには、**[!UICONTROL Inventory／Deals]** に移動し、「**[!UICONTROL Create]**」をクリックしてから、「**[!UICONTROL Deal ID Beta]**」をクリックします。 |
| プレースメントの予測 | （10 月 15 日（PT）のリリース）プレースメントレベルのペーシングを使用したプレースメントの場合、プレースメント設定の「[!UICONTROL Forecast]」セクションには、新しい「[!UICONTROL Estimated Maximums]」セクションが含まれます。このセクションは、現在のターゲット設定でどれくらい多くの容量が使用できるかを示します。 |

### [!DNL Advertising Cloud Search] の新機能 {#adcloud-search}

最終更新日：**2021 年 1 月 22 日（PT）（1 月 23 日（PT）のリリース用）**

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL キャンペーンの検索]<br> レポート | Advertising Cloud Search で、Microsoft Advertising キャンペーンの新しい平均順位データのレポートが作成されなくなりました。 平均順位列には、1 月 23 日（PT）から始まる日付の値が 0（ゼロ）で表示されます。 これは、Microsoft が 2021 年 1 月におこなう平均順位データの廃止に備えたものです。<br>1 月 22 日（PT）までに収集された平均順位データは、引き続きレポートで使用できます。 |

### Ad Cloud チュートリアルとコース

更新日：**2020 年 12 月 2 日**

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

最新のリリース情報については、Magento CommerceおよびOpen Source [リリースノート](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)を参照してください。

## ![アイコン](/assets/target.png)[!DNL Target] {#target}

最新のリリース情報については、[[!DNL Target]  リリースノート](https://docs.adobe.com/content/help/ja-JP/target/using/release-notes/target-release-notes.html)を参照してください。

## ![アイコン](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーの各段階を通じて顧客体験を変えようと考えているリードマネジメントとB2Bマーケター向けの完全なアプリケーションです。

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

新しく公開された Adobe Document Cloud ビデオ、チュートリアル、コース。

### Acrobat チュートリアル

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日（PT） | [Acrobat概要ランディング](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html) | 学習ハブ | Adobe Acrobatラーニングハブへようこそ。 Adobe Acrobatに焦点を当てた幅広い学習体験が見られます。 チュートリアル、ウェビナー、使用例は、初心者向けと上級者向けの両方をAdobe Acrobatで素早く習得できるように設計されています。 |

### Adobe Signチュートリアル

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日（PT） | [ランディングの概要 — サポートするアセット](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html) | 学習ハブ | Adobe Signラーニングハブへようこそ。 Adobe Signに焦点を当てた幅広い学習体験が見られます。 チュートリアル、ウェビナー、使用例は、初心者、管理者の両方がAdobe Signで素早く対応できるように設計されています。 |

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat ラーニングハブ](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Sign ラーニングハブ](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![](/assets/creative-cloud-24.png) IconCreative Cloudエンタープライズ  {#creative-cloud}

Creative Cloudエンタープライズの新しいチュートリアル。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 3 日（PT） | [Photoshopで映画を作る](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/cinemagraphps.html?lang=en#cceoverview) | ビデオ | Adobe StockのビデオとPhotoshopの賢いマスキングテクニックを組み合わせて、生き写真を作る方法を学びます。 |
| 2021年2月4日 | [iPad用にAdobe StockとPhotoshopを使用して、ユニークな合成画像を作成](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/compositepsipad.html?lang=en) | ビデオ | タッチベースのインターフェイスを再設計し、お気に入りのCreative Cloudアプリケーションの1つを新しい方法で使用する方法を学びます。 |
| 2021 年 2 月 3 日（PT） | [DimensionとAdobe Stockを使用して3Dモデルをカスタマイズし、ブランド化する](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/3ddimensionstock.html?lang=en) | ビデオ | マテリアル、環境特性、照明、写真を使用して、Dimensionの3Dモデルをカスタマイズおよびブランディングし、任意のデザインプロジェクトに写実的な画像を作成します。 |
| 2021 年 2 月 2 日（PT） | [Adobe XDのコンポーネントの使い方](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/xdoverview/components.html) | ビデオ | コンポーネントを使用して、スピードと一貫性の両方を設計ワークフローに適用する前例のない柔軟性を提供する方法について説明します。 |
| 2021 年 2 月 2 日（PT） | [CGIで3D照明を習得するためのヒントとテクニック](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/mastering3dlighting.html?lang=en) | 記事 | 3D照明について学習し、コンピュータ生成シーンを完全に変更し、オブジェクトの外観を完全に変更する様々な光条件を作成する方法を学びます。 |
| 2021 年 2 月 2 日（PT） | [3Dレンダリングと合成を使用して、フォトリアリスティックなバーチャルフォトグラフィを作成する](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/photorealistic.html?lang=en#3doverview) | 記事 | 3Dレンダリングと合成を使用して、フォトリアリスティックなバーチャルフォトグラフィを作成する方法を学びます。 |
| 2021 年 1 月 29 日（PT） | [CCEクイックリファレンスガイド](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/overview-ref.html) | クイックリファレンスガイド | Creative Cloudの新機能を学ぶのに役立つクイックリファレンスガイドにアクセスできます。 |

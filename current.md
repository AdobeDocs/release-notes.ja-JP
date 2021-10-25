---
title: 最新のリリースノート
description: ' [!DNL Experience Cloud]  製品およびサービスに関する最新のリリースノート、新機能、新規ドキュメントについて説明します。 [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud] に関する新しいヘルプとチュートリアルをご覧ください。'
doc-type: release notes
last-update: November 2021
author: mfrei
mini-toc-levels: 1
exl-id: null
source-git-commit: c22db21d36f9ff7309f1ca835ff3241f87b86286
workflow-type: tm+mt
source-wordcount: '4190'
ht-degree: 60%

---

# Adobe Experience Cloud リリースノート - 2021 年 11 月

![バナー](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] アプリケーションおよびサービスは毎月更新されます。このページには、[!DNL Experience Cloud] と [!DNL Experience Platform] の最新のリリースアップデート、ドキュメントおよびチュートリアルが集約されています。また、[!DNL Creative Cloud for enterprise] と [!DNL Document Cloud] の新しいドキュメントも参照できます。

>[!NOTE]
>
>毎月[アドビの優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)をサブスクライブして、このページの更新に関する電子メール通知を受信します。このページはひと月にわたって保持されるので、定期的にアクセスして、アドビのエンタープライズ製品と Experience League のドキュメントが更新されていないか確認してください。

リリース月: **11 月2021**

最終更新日：**2021 年 10 月 22 日**

* [[!DNL Experience League] ライブイベント](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; 管理](#ecloud)
* [アドビ [!UICONTROL システムステータス]](#status)
* [[!DNL Adobe Analytics]](#analytics) および [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。

## ![アイコン](/assets/experience-league.png) [!DNL Experience League] ライブイベント {#events}

[エクスペリエンスに関するライブイベントは、adobe ](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) エキスパートや、adobe テクノロジを使用しているユーザーを対象としています。 以下のスケジュールを参照してライブに参加したり、過去の録画イベントを視聴したりしましょう。

| イベントの日付 | 時間 | イベント名 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021年10月21日（PT） | オンデマンド | [クリックしたのは誰でしょう？Adobe Analytics によるリンククリックの高度なレポート機能](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) | ライブビデオイベント | Web またはモバイルプロパティとのユーザーインタラクションに関するレポート作成は、顧客のジャーニーを把握するうえで重要です。Adobe Analytics を使用すると、アプリケーション内でクリックしたユーザー、対象、理由、場所を把握できます。Adobe Analytics のエキスパートが Activity Map の分類とカスタム属性を使用して、ユーザーエンゲージメントをより深く理解するためのヒントを紹介します。 |
| 2021 年 10 月 4 日（PT） | オンデマンド | [アドビ開発者向け](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | ビデオ | イベントを見逃したり、特定のセッションの再生を探したりすることができます。 このような体験は、リーグで見つけることができます。 開発者は、最新の技術進歩および開発者向けツールを使用して、工業環境におけるデザイン、コンテンツ作成ワークフロー、ドキュメントサービス、カスタマーエクスペリエンス管理を行うことができます。 基調講演の内容を表示します。また、アナリティクス Api、クライアントデータレイヤー、Adobe i/o オープンソースプロジェクトなどについて学習します。 |

{style=&quot;table-layout:auto&quot;}

その他のビデオについては、YouTube の [Adobe Experience League チャンネル](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] と管理 {#ecloud}

| 機能 | 説明 |
| ------- | ------- |
| ホームページ | このようなクラウドのホームフッター情報は、法律上の注意や、環境設定で選択した言語を含むユーザープロファイルカードに移動されました。 |
| AEP ダッシュボード | [!DNL Helios Lite] では、経験プラットフォーム widget 作成ワークフローでのグラフの推奨事項が表示されます。 データ選択 (現在は variable データ選択) を指定した場合、helios はそのデータ選択を伴う適切なビジュアル化を推奨します。 |
| AEP ダッシュボード | [!DNL Instory] では、ML によって作成されたグラフ用のナレーションとキャプションが提供されています。 この decorates には、「AEP」ダッシュボードページに、グラフ化されたデータの大きな変更やインシデントを出した関連する行頭文字ポイントが含まれています。 |

{style = &quot;テーブル-layout: auto&quot;}

**[!DNL Experience Cloud Central UI Components]と管理に関するその他のヘルプリソース**

* [主要なインターフェイスコンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)およびユーザー管理の管理ヘルプ
* [Places - 位置情報サービス](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ja)のヘルプとリリースノート
* [People - 顧客属性とオーディエンスライブラリ](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ja)に関するヘルプ

## ![アイコン](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] は、Adobe製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/ja) でご確認ください。

（[!DNL Adobe System Status]の最新のリリース情報は、[2020年5月21日（PT）](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ja)のリリースノートをご覧ください。）

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2021 年 10 月 28 日**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [Analytics コースとチュートリアル](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=ja) - ターゲット日 |
| ----------- | ---------- | ------- |
| Analysis Workspace での日付の範囲 (1 分間) | パネルのカレンダーの詳細設定では、分レベルの日付の範囲を適用することも、カスタム日付範囲を作成することもできます。 日付の範囲が指定されている場合は、開始時間が最初の日付に適用され、終了時刻は範囲内の最後の日付に適用されます。 | 2021年10月19日 |
| [!UICONTROL メディア再生滞在時間] | アドビのストリーミングメディア再生[!UICONTROL 滞在時間] は、ビューアのエンゲージメントに関する貴重なインサイトを提供し、メディア企業は日分割機能を備えた高度な滞在時間分析を通じて、分単位のユーザーエンゲージメントに関する、より深く、より詳細なインサイトを得ることができます。特定の時点でのメディアストリームの視聴時間を確認できます。「新しい5分」、「15分」および「30分間の granularities」など、様々な granularities を使用して再生時間を分割することができます。 [詳細情報](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=ja) | 2021年10月19日 |
| クイック[!UICONTROL セグメントビルダー] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで、基本的なセグメントをすばやく適用できます。[!UICONTROL セグメントビルダー]に移動する必要はありません。[詳細情報](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=ja) | 2021年10月21日（PT） |
| Analysis Workspace 左パネルの検索の改善 | 左側のレール検索 1) は、条件に一致するものが見つかった場合は、コンポーネントの使用と関連性について継続的に対応させることができます。 2）一致した文字をハイライトして、検索結果をわかりやすくします。3）ディメンションに関連する分類を見つけやすくなります。4）最後に、ワイルドカード（`*`）検索をサポートして、必要な特定のコンポーネントをより簡単に見つけます。注意：ワイルドカード検索は、ディメンション項目レベルではまだ機能しません。 | 2021年10月21日（PT） |
| Analysis Workspace ダークテーマ | ダークテーマは表示オプションとして使用できます。 | 2021年10月21日（PT） |

{style = &quot;テーブル-layout: auto&quot;}

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html) - ターゲット日 |
| ----------- | ---------- | ----- |
| Analysis Workspace での日付の範囲 (1 分間) | パネルのカレンダーの詳細設定では、分レベルの日付の範囲を適用することも、カスタム日付範囲を作成することもできます。 日付の範囲が指定されている場合は、開始時間が最初の日付に適用され、終了時刻は範囲内の最後の日付に適用されます。 | 2021年10月19日 |
| クイック[!UICONTROL フィルタービルダー] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで、基本的なセグメントをすばやく適用できます。[!UICONTROL フィルタービルダー]に移動する必要はありません。[詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html) | 2021年10月21日（PT） |
| Analysis Workspace 左パネルの検索の改善 | 左側のレール検索 1) は、条件に一致するものが見つかった場合は、コンポーネントの使用と関連性について継続的に対応させることができます。 2）一致した文字をハイライトして、検索結果をわかりやすくします。3）ディメンションに関連する分類を見つけやすくなります。4）最後に、ワイルドカード（`*`）検索をサポートして、必要な特定のコンポーネントをより簡単に見つけます。注意：ワイルドカード検索は、ディメンション項目レベルではまだ機能しません。 | 2021年10月21日（PT） |
| Analysis Workspace ダークテーマ | ダークテーマは表示オプションとして使用できます。 | 2021年10月21日（PT） |
| ディメンジョン割り当て用に戻るウィンドウ | 「データビュー」設定の「持続性」の「ディメンション割り当て」設定に、最大90日のルックアップウィンドウが追加されました。 [詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html) | 2021 年 10 月 28 日（PT） |

{style = &quot;テーブル-layout: auto&quot;}

### Adobe Analytics の修正点 {#aa-fixes}

* アラートマネージャーで警告を削除できないという問題が修正されています。 （AN-270656）
* データウェアハウスに断続的なエラーが発生したときに問題が解決されていました。 （AN-273713、AN-272790）
* 分類が更新されない問題が修正されています。 （AN-272211）

### お客様の旅解析の修正 {#cja-fixes}

* CJA のパフォーマンスの問題を修正しました (プロジェクトの読み込み中のエラーメッセージ)。 （AN-269451、AN-270649）
* セッションを開始したときの問題を修正したのは、ページ名のフローエントリと一致しませんでした。 （AN-273501）
* Fallout レポートが正常に機能しないという問題が修正されています。 （AN-269761）

#### Adobe Analytics におけるその他の修正点

A-263327;A-267807;A-269757;A-272789;A-272888;A-273155;A-273320;A-273369;A-273405;A-273469;A-273581;A-273642;A-273688;A-273988;A-274007;A-274030;A-274156;A-274188;A-274226

#### CJA でのその他の修正

A-270649

### [!DNL Analytics] 管理者向けの重要な注意事項  {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| 3 つの Analytics API サービスの提供終了 | 2021年9月16日（PT） | **2021年10月20日（PT）**、次の Analytics レガシー API サービスの提供が終了し、サービスが停止されます。これらのサービスを使用して現在構築されている統合は、その日以降使用できなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>アドビでは、お客様のご質問に対する回答や進め方に関するガイダンスを提供するために、[従来の API の EOL（サポート終了）に関する FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe I/O](https://developer.adobe.com/console) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API のどちらにアクセスする場合にも使用できます。 |
| データソースでの完全な処理のための EOL | 2021年10月19日 | **2022 年1月31日に** は、Adobe は完全な処理を終了します。これにより、ユーザーは、オフラインでのヒットデータをアナリティクスに取り込むことができます。この機能は [ 、バルクデータ挿入 API によって利用でき ](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) ます。 [詳細情報](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=ja?lang=ja) |

{style = &quot;テーブル-layout: auto&quot;}

### AppMeasurement {#appm}

AppMeasurement リリース（バージョン 2.22.2）の最新の更新については、[JavaScript リリースノートの AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja) を参照してください。

### Analytics コースとチュートリアル {#tutorials-analytics}

[!DNL Analytics] および [!UICONTROL Customer Journey Analytics] の最新のコース、チュートリアル、記事。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年11月 | [Adobe アナリティクスでのセグメントコンテナ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-containers.html?lang=en) | ビデオ (アップデート) | このビデオでは、コンテナの使用方法について説明します。各タイプのコンテナの例を示しています。 |
| 2021年11月 | [Adobe アナリティクスでの逐次セグメンテーション](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/sequential-segmentation.html?lang=en#) | ビデオ (アップデート) | サイトまたはアプリケーション内の一連のビヘイビアーから、解析ワークスペース内のセグメントを作成する方法について説明します。 |
| 2021年11月 | [順次セグメント化での前後のシーケンス](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/before-after-sequences-in-sequential-segmentation.html?lang=en) | ビデオ (アップデート) | Adobe アナリティクスでセグメント化する方法について説明します。これにより、特定のユーザーパスの前後のデータのみを取得することができます。 |
| 2021年11月 | [Customer Journey Analytics 用の Report Builder](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/report-builder-for-customer-journey-analytics.html) | ビデオ | Report Builder のシンプルで柔軟なドラッグ＆ドロップ UI を使用すると、Customer Journey Analytics データから複雑なデータクエリやカスタムレポートをすべて Excel 内で作成できます。 |
| 2021年10月 | [ビジュアライゼーションを使用したデータストーリーの把握](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | コース | 視覚的な視覚化について、プロジェクトに追加する方法、データを取得する方法、ビジュアリゼーションについて説明しています。 必要な正確なデータを取得するための設定方法を説明します。また、標準的な分析にビジュアライゼーションを使用できるようにするためのヒントや使用例を説明します。 |

{style = &quot;テーブル-layout: auto&quot;}

### Analytics ヘルプリソース

* [Adobe Analytics 製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の修正点と改善点。

* すべての API 呼び出しが `Undocumented` Swagger インターフェイスを通じて実行されたときにエラーを返す問題が解決されました。 （AAM-59190）
* 問題が解決されました。状況によっては、パートナーに間違ったユーザーロールが割り当てられることがあります。 （AAM-59451）
* この API で大文字と小文字が区別される認証ヘッダーが要求される問題を解決しました。 （AAM-58528）


## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Experience Platform と[!UICONTROL モバイル SDK] に関するリリース更新情報と新しいドキュメントが含まれます。

**2021 年 9 月 29 日**

詳しくは、 [Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja) を参照してください。

### Experience Platform チュートリアルおよびコース {#tutorials-platform}

Experience Platform およびサービス用に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年11月 | [ ファーストパーティのデータコンテキストでのデータ共同作業 ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/industry/data-collaboration-in-the-first-party-data-context.html?lang=en#) | ビデオ | より少ないデータにアクセスすることによって、経験からの成果を提供します。 このウェビナーは、広告主、出版社、政府機関に関係なく、将来、サードパーティの cookie を使用せずにデータ共同作業を行うことができないようにするのに役立ちます。 |
| 2021年10月 | [[!DNL Platform] 管理](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | コース | 権限やサンドボックス管理など、Experience Platform の管理アクティビティについて説明します。 |

{style = &quot;テーブル-layout: auto&quot;}

### Adobe Mobile SDK

Adobe Experience Platform Mobile SDK の [リリースノートと変更ログ](https://aep-sdks.gitbook.io/docs/release-notes) を参照してください。

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

Adobe Journey Optimizer を使用すると、1 つのアプリケーションで、スケジュールされたオムニチャネルキャンペーンや何百万人もの顧客向けの 1 対 1 の瞬間を管理でき、インテリジェントな意思決定とインサイトにより、ジャーニー全体を最適化します。

### 最新の Journey Optimizer 製品リリース

最新の機能、改善点および修正点について詳しくは、[Journey Optimizer リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ja)を参照してください。

### Journey Optimizer のチュートリアルとコース {#tutorials-ajo}

最新の Journey Optimizer チュートリアル：

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年10月 | [データエンジニア向け [!DNL Journey Optimizer] データの設定と管理](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | コース | Journey Optimizer でのジャーニー管理に必要なデータの設定と管理方法について説明します。 |
| 2021年10月 | [ジャーニー管理者およびマネージャー [!DNL Journey Optimizer] の概要](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | コース | 最初の旅を作成するために必要な情報をすべてご確認ください。 |
| 2021年10月 | [ジャーニー管理者用 [!DNL Journey Optimizer] の設定](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | コース | [!DNL Journey Optimizer] のアーキテクチャと統合のポイントを理解します。[!DNL Journey Optimizer] の設定方法を説明します。 |

{style = &quot;テーブル-layout: auto&quot;}

### [!DNL Journey Optimizer] のその他のリソース

[ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

### 最新の [!DNL Journey Orchestration] 製品リリース

最新の機能、改善点および修正点について詳しくは、[[!DNL Journey Orchestration]  リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ja)を参照してください。

### [!DNL Journey Orchestration] のその他のリソース

[ドキュメント ](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja) - [ リリースノート ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [ 最新のドキュメントの ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ja-JP) [ 更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ja)

## ![アイコンの ](/assets/experience_platform_appicon_24.png) 意思決定管理 {#offer-decisioning}

[!UICONTROL オファー Decisioning ] は、Adobe エクスペリエンスプラットフォームと統合されたサービスです。 [!UICONTROL Offer Decisioning] を使用すると、すべてのタッチポイントにわたって適切なタイミングで最高のオファーとエクスペリエンスを顧客に提供できます。

### 最新の意思決定管理製品リリース

意思決定管理リリースノートの最新機能、機能強化、修正について詳しくは、こちらを参照 [ ](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) してください。

### 意思決定管理に関するその他のリソース 

[ドキュメント ](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=ja) - [ リリースノート ](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ 最新のドキュメントの ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html) [ 更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=ja)

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

[Adobe Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することをお勧めします。

**アップデート 10/13/2021:** [ ](https://video.tv.adobe.com/v/337381) 新機能の概要については、「2021 9 月のリリース概要」ビデオをご確認ください。

### コミュニティ

* [アドビ開発者向けライブ](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021年10月4～5日、7:00（PDT）

   アドビ開発者向けライブは、多様な背景と単一の目的を持つアドビ開発者とエクスペリエンスビルダーを結集し、素晴らしいエンドツーエンドのエクスペリエンスを作り出します。この 2 日間の会議では、開発者向けの重要な更新、技術セッション、コミュニティネットワークの機会を紹介します。

   経験豊かなアドビ製品チームには、クラウド、ドキュメントクラウド、クリエイティブクラウドを利用した、最新の技術革新および開発者向けツールがあります。これらを使用して、工業環境でのデザイン、コンテンツ作成ワークフロー、ドキュメントサービス、カスタマーエクスペリエンス管理を行うことができます。

   アドビでは、20 回の Experience Manager セッションが予定されています。周囲の人も誘ってぜひ参加ください。

   * [セッションリストの完了](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041?profile.language=ja#M120517)
   * [無料登録 — RSVP にログインします](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [アドビ開発者ライブコミュニティ](https://experienceleaguecommunities.adobe.com:443/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-4th-amp-5th/td-p/422127)

### 新しい Adobe Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | 説明 | タイプ | バージョン |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021年11月 | [Adobe エクスペリエンスマネージャサイトの基礎](https://experienceleague.adobe.com/docs/experience-manager-skill-builder/skill-builder/2021/authoring-fundamentals.html?lang=en) | ビデオシリーズ | この5パートのウェビナーシリーズでは、Adobe Experience Manager で豊富で魅力的なカスタマーエクスペリエンスを作成する方法について説明しています。 まず、コンテンツオーサリングの構築ブロックから始め、基本的な概念と操作について学習します。 では、サイト管理機能と、AEM 内のデジタルアセットの操作に関する基礎について説明しています。 後で、コンテンツを再利用してチャネル間で配信することによって、時間を節約し、効率を向上させるための機能が見つかります。 | AEM Sites |
| 2021年11月 | [クラウドサービスとしての AEM への移行を計画する](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2021.1.migration) | コース | クラウドサービスとして EM に移行する際の考慮事項と、このプロセスを簡略化するために使用できるツールについて説明します。 | AEM CS |
| 2021年11月 | [AEM as a Cloud Service への移行](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2021.1.migration) | コース | ここでは、a と a のクラウドサービスとして、1対1の操作を実行する方法について説明します。 | AEM CS |
| 2021年11月 | [インタラクティブ機能をダウンロードします。](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/generate-interactive-dor.html?lang=en#create-custom-servlet) | ビデオ | インタラクティブな DoR をアダプティブフォームデータと共にダウンロードする方法について説明します。 | AEM Forms |
| 2021年11月 | [クラウドサービスエキスパートシリーズの Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/aem-experts-series.html?lang=en) | ビデオシリーズ | Adobe Experience Manager (AEM) は、それを構築している Adobe Professional Professional エンジニアと、それを提供するプロフェッショナルサービスチームによるクラウドサービスとして提供されています。 クラウドサービスとしてどのような機能を使用しているか、どのようにクラウドサービスとして比較し、どのようにしてクラウドサービスとしての移行を行うかについて説明します。 | AEM CS |
| 2021年11月 | [サービスユーザー](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/advanced/service-users.html?lang=en) | ビデオ | Aem リポジトリに、プログラムによって制御されるアクセスを提供するために、のサービスユーザーを作成して、プログラムによってアクセスできるようにする方法について説明します。 | AEM CS |

{style = &quot;テーブル-layout: auto&quot;}

### Adobe Experience Manager リリース情報 {#aem-links}

Adobe Experience Manager に関するリリースノートやその他のリリース情報のリンクは次のとおりです。

* [[!DNL Experience Manager as a Cloud Service]  リリースノート](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=ja)
* [[!DNL Experience Manager as a Cloud Service] リリース情報](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=ja)
* [[!DNL Experience Manager Cloud Manager]  リリースノート](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=ja)
* [自動フォーム変換サービスリリースノート](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=ja)
* [Adobe Experience Manager 6.5 Service Pack リリースノート](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=ja)
* [Adobe Experience Manager 6.4 累積修正パックリリースノート](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ja)
* [[!DNL Experience Manager Assets Dynamic Media]  リリースノート](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=ja)
* [[!DNL Experience Manager Brand Portal]  リリースノート](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ja)
* [Adobe Experience Manager デスクトップアプリケーションリリースノート](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=ja)
* [[!DNL Experience Manager Dispatcher]  リリースノート](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=ja)
* [Adobe Primetime リリースノート](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=ja)
* [Livefyre リリースノート](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=ja)

### Adobe Experience Manager に関するその他のヘルプリソース

* [[!DNL Experience Manager as a Cloud Service] ガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=ja)
* [Adobe Experience Manager 6.5 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ja)
* [Adobe Experience Manager 6.4 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ja)
* [Adobe Experience Manager 6.3 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja)
* [Adobe Experience Manager 6.2 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja#previous-updates)
* [Adobe Experience Manager ドキュメントの以前のバージョン](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager]  ユーザーガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=ja)
* [[!DNL Dynamic Media Classic] ヘルプホーム](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ja)
* [Adobe Experience Manager ドキュメント：最近の更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ja#aem-as-a-cloud-service)

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 最新の Campaign 製品リリース

リリースされた最新の機能、機能強化、修正について詳しくは、以下を参照してください。

* [Campaign v8 リリースノート](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=ja)
* [Campaign Classic v7 リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ja)
* [Campaign Standard リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ja)

### 新しい [!UICONTROL Campaign] コースとチュートリアル {#tutorials-campaign}

Adobe Campaign の最新のチュートリアルとコースです。

| 公開日 | 名前 | 説明 | タイプ | バージョン |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021年11月 | [Campaign を Experience Platform に接続して宛先にする](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/connect-campaign-to-experience-platform-as-destination.html?lang=en) | ビデオ | Amazon S3 の接続タイプを使用し、宛先に対して Adobe Experience Platform セグメントをアクティブ化する方法を説明します。 | AEP &amp; キャンペーン V8 |
| 2021年11月 | [Experience Platform との統合 - 概要](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/overview.html?lang=en) | ビデオ | Campaign と Experience Cloud 間でのデータの共有方法を説明します。 | AEP &amp; キャンペーン V8 |
| 2021年11月 | [受信者データを Experience Platform から読み込んでメールを送信する](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/import-recipient-data-from-platform.html?lang=en) | ビデオ | Adobe Experience Platform から Campaign に受信者データを読み込むために Adobe Campaign で外部アカウントを設定する方法を説明します。 Experience Platform  から読み込んだ受信者をアップロードおよびターゲティングするワークフローの作成方法を理解します。 | AEP &amp; キャンペーン V8 |
| 2021年11月 | [ワークフローでの SOAP Api の使用](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | ビデオチュートリアル | Adobe Campaign Soap API を使用し、API 経由で受信したデータに基づいて高度な配信ワークフローを作成する方法を説明します。 | Campaign V8 |

{style = &quot;テーブル-layout: auto&quot;}

### Campaign ヘルプリソース

* Adobe キャンペーン v8: [ Documentation ](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ja) : [ リリースノート ](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=ja) : [ 実装ガイド](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ja)
* Adobe Campaign Standard：[Campaign Standard ドキュメント](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ja) - [リリース計画](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ja)
* Adobe Campaign Classic：[Campaign Classic v7 ドキュメント](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ja)
* Adobe Campaign コントロールパネル:[ドキュメント](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=ja) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ja)／[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ja) のハウツービデオ

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

リリースノート： [!DNL Adobe Advertising Cloud]

* [ [!DNL Advertising Cloud DSP] の新機能 ](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] の新機能 ](#adcloud-search)

### [!DNL Advertising Cloud DSP] の新機能  {#adcloud-dsp}

最終更新日：**2021 年 10 月 7 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| ドキュメント | のすべての [ DSP およびその他の広告クラウドドキュメント ](https://experienceleague.adobe.com/docs/advertising-cloud.html) [!DNL Experience League] は、使用可能なすべての言語に翻訳されるようになりました。 表示言語を変更するには、ページの左下にある「言語の変更」メニューを使用します。 |

{style = &quot;テーブル-layout: auto&quot;}

### [!DNL Advertising Cloud Search] の新機能  {#adcloud-search}

最終更新日：**2021 年 10 月 7 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| [!UICONTROL レポート ] , [!UICONTROL  通知センター] | (リリース9年10月)レポートの電子メール通知はすべて、カスタムレポートまたはスケジュール設定されたレポートが完了または失敗したときに送信され、通知センターによって処理されるようになりました  。 レポートについては、電子メール通知と web 通知がデフォルトで有効になっていますが、通知設定を変更することもできます。 この変更により、次の操作を行います。<ul><li>電子メールの受信者は、登録クラウド検索に登録されている認証されたユーザーに制限され、広告主アカウントにアクセスすることができます。 この機能により、不正なユーザーに機密データが送信されるのを防ぐことができます。</li><li>電子メールの形式と内容には、  レポートの詳細情報や、すべてのレポート形式への直接ダウンロードリンクが含まれている、通知センターテンプレートが使用されます。</li><li>レポート通知は、独自の通知設定を備えた新しい通知タイプで、通知センターに表示され  ます。</li></ul>何らかの方法で電子メール通知からレポートをプルする場合は、フィルタリングロジックを更新すると、プロセスの連続性が保証されます。 |
| 広告インサイト | ベータモードでは、追加のインサイトを利用できます。 |

{style = &quot;テーブル-layout: auto&quot;}

## ![アイコン](/assets/magento.png) [!DNL Commerce]（Magento） {#magento}

Adobe Commerce リリースノートについては、次のリンクを参照してください。

* [Adobe Commerce と Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新しい Adobe Commerce チュートリアル {#commerce-tutorials}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年11月 | [Adobe Commerce ビデオおよびチュートリアル](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/overview.html?lang=en) | チュートリアルホーム | このチュートリアルのリソースには、トピックの概要と、特定のタスクとプロセスを対象とした個々のビデオが表示されるビデオシリーズが含まれています。 このコレクションは、バックエンド開発者、フロントエンド開発者、システム管理者、商人、および組織内のその他のロールに有用なコンテンツを提供するように設計されています。 |

## ![アイコン](/assets/target.png) [!DNL Target] {#target}

最終更新日: **2021 年10月20日**

最新のリリース情報については、[[!DNL Target] リリースノート](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ja)を参照してください。

## ![アイコン](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーのすべてのステージにわたるエンゲージメントを通じてカスタマーエクスペリエンスを変革しようとしている経営陣や B2B マーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

最新のリリーススケジュール情報とリリースノートについては、[!DNL Marketo Engage] [リリーススケジュール](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ja)を参照してください。

## ![アイコン](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] は、アイデアの共有、コンテンツの作成、複雑なプロセスの管理、および最高の作業を行うための統合作業管理アプリケーションです。

すべての製品の最新情報のまとめについては、[[!DNL Workfront] リリース](https://one.workfront.com/s/product-releases)ページを参照してください。

## ![アイコン](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

新しく公開された Adobe Document Cloud ビデオ、チュートリアル、コース。

### Document Cloud のコースとチュートリアル {#tutorials-doc-cloud}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年11月 | [ワークスペースの基本](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/get-to-know-the-acrobat-dc-interface.html) | ビデオ (アップデート) | Acrobat DC インターフェイスでは、一貫したワークスペースの操作を使用して、デスクトップ、web およびモバイルデバイス間のファイルやツールへのアクセスを容易にする方法について説明します。 |
| 2021年11月 | [Acrobat web を使用した、あらゆる場所での作業](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/acrobatweb.html) | ビデオ | ブラウザーに表示された Acrobat web ツールを使用して、任意の場所からのビジネスドキュメント要求を処理する方法について説明します。 |
| 2021年11月 | [Web 用の Office での Pdf の作成 ](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/createofficeweb.html) | ビデオ | Microsoft® Office を web アプリケーションの外に移動せずに、PDF ファイルを作成する方法について説明します。 このアドオンには、エンタープライズサブスクリプション版の場合は、teams または Acrobat DC への登録が必要です。 |
| 2021年11月 | [リアルタイムで共同作業します。](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/collaborate.html) | ビデオ | コメントを収集し、応答について共同作業を行い、どの場所からもドキュメントの進行状況をリアルタイムに追跡することによって、プロジェクトを先に進めることができます。 |
| 2021年11月 | [ 外出先での生産性](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/productivity.html) | ビデオ | Acrobat Reader モバイルアプリを使用して、タブレットまたは携帯電話からより適切に作業を行うことができます。 |

{style = &quot;テーブル-layout: auto&quot;}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Creative Cloud エンタープライズ版 {#creative-cloud}

最新のチュートリアルについては、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en)を参照してください。

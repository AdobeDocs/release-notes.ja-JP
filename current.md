---
title: 最新のリリースノート
description: ' [!DNL Experience Cloud]  製品およびサービスに関する最新のリリースノート、新機能、新規ドキュメントについて説明します。に関する新しいヘルプおよびチュートリアルを見つける [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise]、および [!DNL Document Cloud].'
doc-type: release notes
last-update: November 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: b9ede188c852a99934bc91cf428cdf924ed26322
workflow-type: tm+mt
source-wordcount: '4903'
ht-degree: 97%

---

# Adobe Experience Cloud リリースノート - 2021 年 11 月

![バナー](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] アプリケーションおよびサービスは毎月更新されます。このページには、[!DNL Experience Cloud] と [!DNL Experience Platform] の最新のリリースアップデート、ドキュメントおよびチュートリアルが集約されています。また、[!DNL Creative Cloud for enterprise] と [!DNL Document Cloud] の新しいドキュメントも参照できます。

>[!NOTE]
>
>毎月[アドビの優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)をサブスクライブして、このページの更新に関する電子メール通知を受信します。このページはひと月にわたって保持されるので、定期的にアクセスして、アドビのエンタープライズ製品と Experience League のドキュメントが更新されていないか確認してください。

リリース月：**2021 年 11 月**

最新の更新：**2022 年 1 月 4 日（PT）**

* [[!DNL Experience League] イベント](#events)（更新日：2021 年 11 月 15 日（PT））
* [[!DNL Experience Cloud Central Interface Components] &amp; 管理](#ecloud)
* [アドビ [!UICONTROL システムステータス]](#status)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics) (**更新日： 2022 年 1 月 5 日**)
* [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud) (**2021 年 10 月 27 日（PT）**)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。

## ![アイコン](/assets/experience-league.png) [!DNL Experience League] イベント {#events}

Experience League イベントは、アドビの製品エキスパートから回答を得るのに最適な場所です。利用可能なイベントは次のとおりです。

* [Experience League ライブ](#exl-live)：YouTube でのライブおよびオンデマンドのビデオイベント
* [コミュニティ Q＆A コーヒーブレーク](#coffee)：コミュニティフォーラムの製品マネージャーとチャット
* [アドビ開発者のライブ](#dev-live)：Experience League で利用可能なオンデマンドのビデオイベント

スケジュールとイベントは次のとおりです。

### Experience League Live {#exl-live}

[Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=ja) Experience League チームが制作したライブストリーミング番組です。アドビ製品のエキスパートとつながり、Adobe Experience Cloud アプリケーションで適用できる実用的なヒント、テクニック、戦略を学ぶ機会です。

今後のイベント：

| イベントの日付 | 時間 | イベント名 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021 年 11 月 18 日（PT） | 午後 12:00（EST） | [Adobe Experience Manager で迅速にサイトを作成し、これまで以上に高速に運用を開始](https://www.youtube.com/watch?v=7-Lcw5PejhI) | ライブビデオイベント | バックエンド開発を行わずに、機能豊富でパーソナライズされた web エクスペリエンスを数日でデプロイします。事前定義された[!UICONTROL サイトテンプレート]を使用して、ローコードアプローチで Adobe Experience Manager でサイトを作成する方法を説明します。アドビの製品マネージャーである Shankari Panchapakesan、Gabriel Walt、Danny Gordon とのライブプレゼンテーションおよびデモにご参加ください。ライブコーディングも行われるかもしれません。 |

{style=&quot;table-layout:auto&quot;}

過去のエピソードについては、[Experience League ライブ](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en)を参照してください。

### コミュニティ Q＆A コーヒーブレーク{#coffee}

特別なゲストと 1 時間を過ごし、Experience League コミュニティで質問を送信しましょう。このコミュニティでは、アドビの製品エキスパートから回答を得ることができます。

| イベント名 | 日時 | アプリケーション | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| Adobe Target - セットアップと管理 UI、A4T 統合、AEM 統合、一般 UI  | 12 月 8 日 水曜日 午前 8:00（PT） | Adobe Target | フォーラム Q＆A | Adobe Target コミュニティで、Adobe Target のシニア製品マネージャーである Robert Calangiu（@Robert_Calangiu）が参加し、Adobe Target の専門知識に関する質問について直接お答えします。<br>[詳細](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-12-8-21-8am-pt-robert-calangiu/td-p/426697?profile.language=ja) |
| Adobe Campaign - 他のアプリケーションを介したデータのインポート | 2021 年 12 月 2 日 木曜日 午前 8:00（PT） | Adobe Campaign | フォーラム Q＆A | 他のアプリケーションを介したデータのインポート - シニアテクニカルコンサルタントの Zariely Garcia が、テクニカルワークフローを使用して、SFTP/API を介してデータをインポートするためのベストプラクティスを説明します。 <br>[詳細](https://forms.office.com/Pages/ResponsePage.aspx?id=Wht7-jR7h0OUrtLBeN7O4UuYOxSr9BdGsLPtk3ITDIdUMFYwT0REQTk5RDZPTjlEWFlSUk1XWTBHVy4u&amp;wdLOR=cEEEC3C73-227C-457C-AA83-44CC08D697B9). |

{style=&quot;table-layout:auto&quot;}

### アドビ開発者ライブ {#dev-live}

| イベント名 | 日時 | トピック | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021 年 10 月 4～5 日（PT） | オンデマンド | [アドビ開発者ライブ](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=ja) | ビデオ | イベントを見逃した方や、特定のセッションをもう一度見たい場合は、Experience League で見つけることができます。Developers Live では、業界をまたいで設計、コンテンツ作成ワークフロー、ドキュメントサービス、顧客体験管理を支える最新の技術進歩と開発者ツールを紹介します。基調講演を視聴できるほか、Analytics API、クライアントデータレイヤー、Adobe I/O オープンソースプロジェクト、その他多くのことを学習できます。 |

{style=&quot;table-layout:auto&quot;}

その他のビデオについては、YouTube の [Adobe Experience League チャンネル](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] と管理 {#ecloud}

| 機能 | 説明 |
| ------- | ------- |
| ホームページ | Experience Cloud ホームのフッター情報は、環境設定の法律上の注意事項や言語の選択など、ユーザープロファイルカードに移動されました。 |
| AEP ダッシュボード | [!DNL Helios Lite] は、Experience Platform ウィジェット作成ワークフロー内におけるグラフの推奨事項を提供します。データ選択（現在は単一の変数データ選択）が指定されている場合、[!DNL Helios] では、データの選択に伴う適切なビジュアライゼーションが推奨されます。 |
| AEP ダッシュボード | [!DNL Instory] は、グラフに ML ベースの書き込みナレーションとキャプションを提供します。AEP ダッシュボードページのグラフに、データの大きな変更点やインシデントを示す箇条書きを追加します。 |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components]と管理に関するその他のヘルプリソース**

* [主要なインターフェイスコンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)およびユーザー管理の管理ヘルプ
* [Places - 位置情報サービス](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ja)のヘルプとリリースノート
* [People - 顧客属性とオーディエンスライブラリ](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ja)に関するヘルプ

## ![アイコン](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] は、Adobe製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/ja) でご確認ください。

（[!DNL Adobe System Status]の最新のリリース情報は、[2020 年 5 月 21 日（PT）](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ja)のリリースノートをご覧ください。）

## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Experience Platform と[!UICONTROL モバイル SDK] に関するリリース更新情報と新しいドキュメントが含まれます。

**2021 年 9 月 29 日（PT）**

詳しくは、[Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja)を参照してください。

### Experience Platform チュートリアルおよびコース {#tutorials-platform}

Experience Platform およびサービス用に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [ファーストパーティデータコンテキストでのデータ共同作業](https://experienceleague.adobe.com/docs/platform-learn/tutorials/industry/data-collaboration-in-the-first-party-data-context.html?lang=ja) | ビデオ | アクセスするデータを少なく抑え、エクスペリエンスプロミスで配信します。広告主、媒体社、代理店を問わず、このウェビナーを通じて、サードパーティ Cookie を使用しない将来のデータコラボレーションの機会を解放できます。 |
| 2021 年 10 月 | [[!DNL Platform] 管理](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin&amp;lang=ja) | コース | 権限やサンドボックス管理など、Experience Platform の管理アクティビティについて説明します。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

Adobe Experience Platform Mobile SDK の [リリースノートと変更ログ](https://aep-sdks.gitbook.io/docs/release-notes) を参照してください。

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2021 年 10 月 28 日（PT）**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices) （更新日 2022 年 1 月 5 日）
* [Analytics コースとチュートリアル](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=ja) - ターゲット日 |
| ----------- | ---------- | ------- |
| Analysis Workspace の分レベルの日付範囲 | 分レベルの日付範囲は、パネルカレンダーの詳細設定で、またはカスタム日付範囲を作成する際に適用できます。日付範囲が何日にもわたるレポートを作成する場合、開始時間は最初の日、終了時間は範囲内の最終日に適用されます。 | 2021 年 10 月 18 日（PT） |
| [!UICONTROL メディア再生滞在時間] | アドビのストリーミングメディア再生[!UICONTROL 滞在時間] は、ビューアのエンゲージメントに関する貴重なインサイトを提供し、メディア企業は日分割機能を備えた高度な滞在時間分析を通じて、分単位のユーザーエンゲージメントに関する、より深く、より詳細なインサイトを得ることができます。特定の時点でのメディアストリームの視聴時間を確認できます。再生時間は、様々な粒度（新たな 5 分、15 分、30 分の時間粒度を含む）で分割できます。[詳細情報](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=ja) | 2021 年 10 月 18 日（PT） |
| クイック[!UICONTROL セグメントビルダー] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで、基本的なセグメントをすばやく適用できます。[!UICONTROL セグメントビルダー]に移動する必要はありません。[詳細情報](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=ja) | 2021 年 10 月 21 日（PT） |
| Analysis Workspace 左パネルの検索の改善 | 左パネル検索は、1）コンポーネントの最新性と関連性を引き続き考慮に入れることに加えて、部分一致よりも完全一致を優先します。2）一致した文字をハイライトして、検索結果をわかりやすくします。3）ディメンションに関連する分類を見つけやすくなります。4）最後に、ワイルドカード（`*`）検索をサポートして、必要な特定のコンポーネントをより簡単に見つけます。注意：ワイルドカード検索は、ディメンション項目レベルではまだ機能しません。 | 2021 年 10 月 21 日（PT） |
| ダークテーマ | [ダークテーマ](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/user-preferences.html?lang=ja#dark-theme)は表示オプションとして使用できます。 | 2021 年 10 月 21 日（PT） |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=ja) - ターゲット日 |
| ----------- | ---------- | ----- |
| Analysis Workspace の分レベルの日付範囲 | 分レベルの日付範囲は、パネルカレンダーの詳細設定で、またはカスタム日付範囲を作成する際に適用できます。日付範囲が何日にもわたるレポートを作成する場合、開始時間は最初の日、終了時間は範囲内の最終日に適用されます。 | 2021 年 10 月 18 日（PT） |
| クイック[!UICONTROL フィルタービルダー] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで、基本的なセグメントをすばやく適用できます。[!UICONTROL フィルタービルダー]に移動する必要はありません。[詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=ja) | 2021 年 10 月 21 日（PT） |
| Analysis Workspace 左パネルの検索の改善 | 左パネル検索は、1）コンポーネントの最新性と関連性を引き続き考慮に入れることに加えて、部分一致よりも完全一致を優先します。2）一致した文字をハイライトして、検索結果をわかりやすくします。3）ディメンションに関連する分類を見つけやすくなります。4）最後に、ワイルドカード（`*`）検索をサポートして、必要な特定のコンポーネントをより簡単に見つけます。注意：ワイルドカード検索は、ディメンション項目レベルではまだ機能しません。 | 2021 年 10 月 21 日（PT） |
| ダークテーマ | [ダークテーマ](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-workspace/user-preferences.html?lang=ja#dark-theme)は表示オプションとして使用できます。 | 2021 年 10 月 21 日（PT） |
| ディメンション割り当てのルックバックウィンドウ | データビュー設定の「永続性」の下で、ディメンション割り当て設定に最大 90 日のルックバックウィンドウが追加されます。[詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html?lang=ja) | 2021 年 10 月 28 日（PT） |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics の修正点 {#aa-fixes}

* アラートマネージャーでアラートを削除できなかった問題を修正しました。（AN-270656）
* Data Warehouse リクエストが断続的に失敗する問題を修正しました。（AN-273713、AN-272790）
* 分類が更新されない問題を修正しました。（AN-272211）

### Customer Journey Analytics の修正点 {#cja-fixes}

* CJA のパフォーマンスの問題（プロジェクトの読み込み中のエラーメッセージ）を修正しました。（AN-269451、AN-270649）
* CJA で、セッション開始がページ名のフローエントリと一致しなかった問題を修正しました。（AN-273501）
* CJA のフォールアウトレポートが正しく機能しない問題を修正しました。（AN-269761）

#### Adobe Analytics におけるその他の修正点

AN-263327、AN-267807、AN-269757、AN-272789、AN-272888、AN-273155、AN-273320、AN-273369、AN-273405、AN-273469、AN-273581、AN-273642、AN-273688、AN-273988、AN-274007、AN-274030、AN-274156、AN-274188、AN-274226

#### CJA のその他の修正点

AN-270649

### [!DNL Analytics] 管理者向けの重要な注意事項  {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| Reports &amp; Analytics の EOL | 2022 年 1 月 4 日（PT） | 2023 年 12 月 31 日に、Adobeは、Reports &amp; Analytics およびそれに伴うレポートと機能を廃止する予定です。 Reports &amp; Analytics を強化するレポート、ビジュアライゼーション、基盤となる技術は、Adobeの技術標準を満たさなくなりました。 Reports &amp; Analytics のほとんどの機能は、 [Analysis Workspace](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/home.html?lang=ja). 2015 年のAnalysis Workspaceのリリース以降、Reports &amp; Analytics の機能はAnalysis Workspaceに移行され、ワークフローパリティのしきい値に達しました。 [この通知](https://spark.adobe.com/page/6WnF8JK6IRDhf) では、提供終了プロセスについて説明しています。 |
| 「グローバル + 中国」RDC タイプ | 2021 年 11 月 22 日（PT） | 「グローバル + 中国」は、[!UICONTROL 中国のパフォーマンス最適化アドオンパッケージ]を使用して、グローバルな顧客のトラフィックのルーティングを簡素化する新しい地域データ収集（RDC）タイプです。以前は、データを中国の収集エンドポイントにルーティングするか、グローバルな収集エンドポイントの 1 つにルーティングするかを決定する必要がありました。これで、この RDC **タイプ**&#x200B;を選択して、アドビがユーザーの位置情報に基づいて最適な収集エンドポイントを決定できるようになります。 |
| 3 つの Analytics API サービスの提供終了 | 2021 年 09 月 16 日（PT） | **2021 年 10 月 20 日（PT）**、次の Analytics レガシー API サービスの提供が終了し、サービスが停止されます。これらのサービスを使用して現在構築されている統合は、その日以降使用できなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>アドビでは、お客様のご質問に対する回答や進め方に関するガイダンスを提供するために、[従来の API の EOL（サポート終了）に関する FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe I/O](https://developer.adobe.com/console) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API のどちらにアクセスする場合にも使用できます。 |
| データソースでのフル処理のサポート終了 | 2021 年 10 月 18 日（PT） | **2022 年 1 月 31 日（PT）**、アドビはフル処理のサポートを終了します。これにより、ユーザーはオフラインのヒットデータを Analytics に取り込めるようになります。この機能は、[一括データ挿入 API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) を介して利用できます。[詳細情報](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=ja ) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

AppMeasurement リリース（バージョン 2.22.2）の最新の更新については、[JavaScript リリースノートの AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja) を参照してください。

### Analytics コースとチュートリアル {#tutorials-analytics}

[!DNL Analytics] および [!UICONTROL Customer Journey Analytics] の最新のコース、チュートリアル、記事。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [Adobe Analytics のセグメントコンテナ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-containers.html?lang=ja) | ビデオ（更新） | このビデオでは、コンテナの使用方法と、各タイプのコンテナの例をいくつか学びます。 |
| 2021 年 11 月 | [Adobe Analytics での順次セグメント化](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/sequential-segmentation.html?lang=ja) | ビデオ（更新） | サイト上またはアプリケーション上での一連の行動から、Analysis Workspace でセグメントを作成する方法を説明します。 |
| 2021 年 11 月 | [順次セグメント化での前後のシーケンス](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/before-after-sequences-in-sequential-segmentation.html?lang=ja) | ビデオ（更新） | 特定のユーザーパスの前または後のデータのみを取得できるように Adobe Analytics でセグメント化する方法を説明します。 |
| 2021 年 11 月 | [Customer Journey Analytics 用の Report Builder](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/report-builder-for-customer-journey-analytics.html?lang=ja) | ビデオ | Report Builder のシンプルで柔軟なドラッグ＆ドロップ UI を使用すると、Customer Journey Analytics データから複雑なデータクエリやカスタムレポートをすべて Excel 内で作成できます。 |
| 2021 年 10 月 | [ビジュアライゼーションを使用したデータストーリーの把握](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations&amp;lang=ja) | コース | プロジェクトにビジュアライゼーションを追加する方法、ビジュアライゼーションにデータを取り込む方法、各ビジュアライゼーションで表示できる内容など、ビジュアライゼーションの基本について説明します。必要な正確なデータを取得するための設定方法を説明します。また、標準的な分析にビジュアライゼーションを使用できるようにするためのヒントや使用例を説明します。 |

{style=&quot;table-layout:auto&quot;}

### Analytics ヘルプリソース

* [Adobe Analytics 製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の修正点と改善点。

* すべての API 呼び出しで、Swagger インターフェイスを介して実行すると `Undocumented` エラーを返す問題を修正しました。（AAM-59190）
* 場合によって誤ったユーザーの役割がパートナーに割り当てられる問題を修正しました。（AAM-59451）
* API で大文字と小文字を区別する認証ヘッダーが必要となる問題を修正しました。（AAM-58528）

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

[Adobe Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することをお勧めします。

### リリースの概要ビデオ

* [2021 年 12 月リリースの概要](https://video.tv.adobe.com/v/339278) 新機能のビデオ。
* 新機能の [2021 年 10 月リリースの概要](https://video.tv.adobe.com/v/338253)ビデオ。
* 新機能の [2021 年 9 月リリースの概要](https://video.tv.adobe.com/v/337381)ビデオ。

### コミュニティ

* [アドビ開発者向けライブ](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021 年 10 月 4～5 日、7:00（PDT）

   アドビ開発者向けライブは、多様な背景と単一の目的を持つアドビ開発者とエクスペリエンスビルダーを結集し、素晴らしいエンドツーエンドのエクスペリエンスを作り出します。この 2 日間の会議では、開発者向けの重要な更新、技術セッション、コミュニティネットワークの機会を紹介します。

   Experience Cloud、Document Cloud、Creative Cloud のアドビ製品チームは、業界をまたいだ設計、コンテンツ作成ワークフロー、ドキュメントサービス、顧客体験管理を支える最新の技術進歩と開発者ツールを紹介します。

   アドビでは、20 回の Experience Manager セッションが予定されています。周囲の人も誘ってぜひ参加ください。

   * [セッションリストの完了](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041?profile.language=ja#M120517)
   * [無料登録 — RSVP にログインします](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [アドビ開発者ライブコミュニティ](https://experienceleaguecommunities.adobe.com:443/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-4th-amp-5th/td-p/422127?profile.language=ja)

### 新しい Adobe Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | 説明 | タイプ | バージョン |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021 年 11 月 | [Adobe Experience Manager Sites の基本](https://experienceleague.adobe.com/docs/experience-manager-skill-builder/skill-builder/2021/authoring-fundamentals.html?lang=ja) | ビデオシリーズ | 豊富で魅力的な顧客体験を Adobe Experience Manager で作成する方法については、5 部構成のウェビナーシリーズを参照してください。基本的な概念と操作を学習しながら、コンテンツのオーサリングの構成要素から始めます。AEM 内でのデジタルアセットの管理機能と操作の基本について説明します。その後、コンテンツを再利用して複数のチャネルに配信することで、時間を節約し、より効率的な機能を見つけ出すことができます。 | AEM Sites |
| 2021 年 11 月 | [AEM as a Cloud Service への移行の計画](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2021.1.migration&amp;lang=ja) | コース | AEM as a Cloud Service への移行に関する考慮事項と、プロセスを簡略化する使用可能なツールについて説明します。 | AEM CS |
| 2021 年 11 月 | [AEM as a Cloud Service への移行](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2021.1.migration&amp;lang=ja) | コース | AEM 6 から Experience Manager as a Cloud Service に正常に移行する方法を説明します。 | AEM CS |
| 2021 年 11 月 | [インタラクティブ DoR のダウンロード](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/generate-interactive-dor.html?lang=ja#create-custom-servlet) | ビデオ | アダプティブフォームデータを含むインタラクティブ DoR のダウンロード方法を説明します。 | AEM Forms |
| 2021 年 11 月 | [Adobe Experience Manager as a Cloud Service エキスパートシリーズ](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/aem-experts-series.html?lang=ja) | ビデオシリーズ | Adobe Experience Manager (AEM) as a Cloud Service を構築するアドビのエキスパートエンジニアと、これを提供する Professional Services チームから説明します。アドビの専門家に参加していただき、AEM as a Cloud Service とは何か、AEM 6 との比較、AEM 6 から AEM as a Cloud Service への移行方法を確認します。 | AEM CS |
| 2021 年 11 月 | [サービスユーザー](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/advanced/service-users.html?lang=ja) | ビデオ | AEM コードでサービスユーザーを作成および使用して、AEM リポジトリーへの制御されたプログラムによるアクセスを提供する方法を説明します。 | AEM CS |

{style=&quot;table-layout:auto&quot;}

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

## ![アイコン](/assets/magento.png) [!DNL Commerce]（Magento） {#magento}

Adobe Commerce リリースノートについては、次のリンクを参照してください。

* [Adobe Commerce と Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新しい Adobe Commerce チュートリアル {#commerce-tutorials}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [Adobe Commerce のビデオとチュートリアル](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/overview.html?lang=ja) | チュートリアルホーム | これらのチュートリアルリソースには、トピックの概要を示すビデオシリーズや、特定のタスクおよびプロセスを対象とする個々のビデオが含まれます。このコレクションは、バックエンド開発者、フロントエンド開発者、システム管理者、マーチャント、組織内のその他の役割に役立つコンテンツを提供するように設計されています。 |

## ![アイコン](/assets/target.png) [!DNL Target] {#target}

最終更新日：**2021 年 10 月 20 日（PT）**

最新のリリース情報については、[[!DNL Target] リリースノート](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ja)を参照してください。

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
| 2021 年 11 月 | [Campaign を Experience Platform に接続して宛先にする](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/connect-campaign-to-experience-platform-as-destination.html?lang=ja) | ビデオ | Amazon S3 の接続タイプを使用し、宛先に対して Adobe Experience Platform セグメントをアクティブ化する方法を説明します。 | AEP と Campaign V8 |
| 2021 年 11 月 | [Experience Platform との統合 - 概要](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/overview.html?lang=ja) | ビデオ | Campaign と Experience Cloud 間でのデータの共有方法を説明します。 | AEP と Campaign V8 |
| 2021 年 11 月 | [受信者データを Experience Platform から読み込んでメールを送信する](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/import-recipient-data-from-platform.html?lang=ja) | ビデオ | Adobe Experience Platform から Campaign に受信者データを読み込むために Adobe Campaign で外部アカウントを設定する方法を説明します。Experience Platform から読み込んだ受信者をアップロードおよびターゲティングするワークフローの作成方法を理解します。 | AEP と Campaign V8 |
| 2021 年 11 月 | [ワークフローでの SOAP API の使用](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=ja) | ビデオチュートリアル | Adobe Campaign Soap API を使用し、API 経由で受信したデータに基づいて高度な配信ワークフローを作成する方法を説明します。 | Campaign V8 |

{style=&quot;table-layout:auto&quot;}

### Campaign ヘルプリソース

* Adobe Campaign v8：[ドキュメント](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=ja) - [実装ガイド](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ja)
* Adobe Campaign Standard：[Campaign Standard ドキュメント](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ja) - [リリース計画](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ja)
* Adobe Campaign Classic：[Campaign Classic v7 ドキュメント](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ja)
* Adobe Campaign コントロールパネル:[ドキュメント](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=ja) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ja)／[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ja) のハウツービデオ

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

Adobe Journey Optimizer を使用すると、1 つのアプリケーションで、スケジュールされたオムニチャネルキャンペーンや何百万人もの顧客向けの 1 対 1 の瞬間を管理でき、インテリジェントな意思決定とインサイトにより、ジャーニー全体を最適化します。

### 最新の Journey Optimizer 製品リリース

最新の機能、改善点および修正点について詳しくは、[Journey Optimizer リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ja)を参照してください。

### Journey Optimizer のチュートリアルとコース {#tutorials-ajo}

最新の Journey Optimizer チュートリアル：

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [データエンジニア向け [!DNL Journey Optimizer] データの設定と管理](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2&amp;lang=ja) | コース | Journey Optimizer でのジャーニー管理に必要なデータの設定と管理方法について説明します。 |
| 2021 年 10 月 | [ジャーニー管理者およびマネージャー [!DNL Journey Optimizer] の概要](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1&amp;lang=ja) | コース | 初めてのジャーニーを作成するために知っておくことをすべて説明します。 |
| 2021 年 10 月 | [ジャーニー管理者用 [!DNL Journey Optimizer] の設定](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1&amp;lang=ja) | コース | [!DNL Journey Optimizer] のアーキテクチャと統合のポイントを理解します。[!DNL Journey Optimizer] の設定方法を説明します。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] のその他のリソース

* [Journey Optimizer ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ja)
* [意思決定管理ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=ja) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

### 最新の [!DNL Journey Orchestration] 製品リリース

最新の機能、改善点、修正点について詳しくは、[[!DNL Journey Orchestration] リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ja)を参照してください。

#### [!DNL Journey Orchestration] のその他のリソース

* [Journey Orchestration ドキュメント](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ja-JP) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ja)

## ![アイコン](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーのすべてのステージにわたるエンゲージメントを通じてカスタマーエクスペリエンスを変革しようとしている経営陣や B2B マーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

最新のリリーススケジュール情報とリリースノートについては、[!DNL Marketo Engage] [リリーススケジュール](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ja)を参照してください。

## ![アイコン](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] は、アイデアの共有、コンテンツの作成、複雑なプロセスの管理、および最高の作業を行うための統合作業管理アプリケーションです。

すべての製品の最新情報のまとめについては、[[!DNL Workfront] リリース](https://one.workfront.com/s/product-releases)ページを参照してください。

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

リリースノート： [!DNL Adobe Advertising Cloud]

* [ [!DNL Advertising Cloud] 全体の新機能](#adcloud-all)
* [ [!DNL Advertising Cloud DSP] の新機能 ](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] の新機能 ](#adcloud-search)

### [!DNL Advertising Cloud] 全体の新機能 {#adcloud-all}

最終更新日：**2021 年 10 月 27 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| Advertising Cloud 向け Analytics | 組織がデータ収集のために従来の Adobe Analytics `visitorAPI.js` ライブラリから Adobe Experience Platform ライブラリ（`alloy.js`）を使用するように切り替える場合は、ID スティッチングを有効にするためにいくつかの変更を加える必要があります。[Adobe Experience Platform [!DNL Web SDK]での [!DNL Last Event Service] JavaScript ライブラリの使用](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=ja)を参照してください。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud DSP] の新機能  {#adcloud-dsp}

最終更新日：**2021 年 10 月 27 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| カスタムレポート | カスタムレポート用に、[!DNL Amazon S3] および *[!DNL report destinations]* と呼ばれる様々なタイプの FTP 配信場所を作成および管理できるようになりました。レポートの宛先を設定したら、新しいカスタムレポートをそれぞれ 1 つ以上の宛先タイプの場所に配信したり、電子メールの受信者に配信したりするように設定できます。[!DNL Amazon S3] および FTP 資格情報を更新しても、レポートの配信が中断されることはありません。<br><br>既存のレポートは、指定した電子メール受信者に引き続き送信されます。別のレポートの宛先への配信を設定するには、新しい宛先で新しいレポートを作成します。 |
| [!UICONTROL パッケージ]、[!UICONTROL プレースメント]、および [!UICONTROL 広告]ビュー | 1 日分のデータを表示する場合、トレンドグラフに時間別データが含まれるようになりました。任意の時点にカーソルを置くと、その時間のデータが表示されます。 |
| [!UICONTROL プレースメント] | プレースメント[!UICONTROL インスペクター]に「[!UICONTROL 在庫]」タブが含まれるようになりました。このタブには、プレースメントのすべての取引とそれに関連する指標が表示されます。この情報を使用すると、カスタムレポートを生成せずに、すばやく調整を行ったり、問題をトラブルシューティングしたりできます。 |
| [!UICONTROL 広告] | （広告に Clearcastclock 番号を含める権限を持つユーザー）別の広告に添付されている時計番号を使用しても、DSP でエラーが表示されなくなりました。**注意：**&#x200B;ベストプラクティスは、各ビデオ広告に一意の時計番号を使用することです。そうしないと、出版社はすべての広告を承認しません。 |
| [!UICONTROL 取引 ID] | [!UICONTROL 取引 ID] 設定およびユーザーインターフェイスのその他の場所は、次の [!DNL Magnite] SSP<br> の新しいブランディングを反映しています。<ul><li>SSP「[!DNL Tremor]」（[!DNL Telaria]）は「[!DNL Magnite CTV]」になりました。</li><li>今後数週間で、「[!DNL Rubicon]」は「[!DNL Magnite DV+]」に変更されます。[!DNL DV+] はディスプレイ、ビデオ、およびオーディオなどのその他の形式を表します。</li></ul> |
| [!DNL Freewheel] プログラムで保証された取引 | [!DNL Freewheel] プログラムで保証された取引の広告のステータスを[!UICONTROL 広告]表示から確認できるようになりました。以前は、[!UICONTROL 取引]表示からのみステータスを確認できました。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] の新機能  {#adcloud-search}

最終更新日：**2021 年 10 月 7 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| [!UICONTROL レポート]、[!UICONTROL 通知センター] | （10 月 9 日（PT）リリース）カスタムレポートまたは予定レポートの作成が完了または失敗したときに Advertising Cloud Search から送信されるレポート関連のすべてのメール通知は、[!UICONTROL 通知センター]で処理されるようになりました。レポートについては、メール通知と web 通知がデフォルトで有効になっていますが、オプションで通知設定を変更できます。今回の変更により、<ul><li>メールの受信者は、Advertising Cloud Search に登録されている認証済みユーザーでかつ広告主のアカウントにアクセスできるユーザーに限定されます。この機能により、権限のないユーザーには機密データが送信されなくなります。</li><li>メールの形式とコンテンツでは、[!UICONTROL 通知センター]のテンプレートが使用されます。このテンプレートには、レポートの詳細が記述されており、すべてのレポート形式に対応する直接ダウンロードリンクが含まれています。</li><li>レポート通知は、[!UICONTROL 通知センター]の新しい通知タイプで、独自の通知設定を備えています。</li></ul>何らかの自動処理を使用してメール通知からレポートを取り込む場合は、フィルタリングロジックを更新して、プロセスが確実に継続されるようにしなければならないことがあります。 |
| 広告インサイト | ベータモードでは、追加のインサイトを利用できます。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

新しく公開された Adobe Document Cloud ビデオ、チュートリアル、コース。

### Document Cloud のコースとチュートリアル {#tutorials-doc-cloud}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [ワークスペースの基本](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/get-to-know-the-acrobat-dc-interface.html?lang=ja) | ビデオ（更新） | Acrobat DC インターフェイスを使用して、一貫したワークスペースエクスペリエンスで、デスクトップ、web およびモバイルデバイス全体でファイルやツールに簡単にアクセスできるようにする方法を説明します。 |
| 2021 年 11 月 | [Acrobat Web でどこでも作業](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/acrobatweb.html?lang=ja) | ビデオ | ブラウザーの Acrobat Web ツールを使用して、どこからでもビジネスドキュメントのリクエストを処理する方法を説明します。 |
| 2021 年 11 月 | [Office web 版での PDF の作成](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/createofficeweb.html?lang=ja) | ビデオ | Microsoft® Office Web アプリ版を開いたまま PDFファイルを作成する方法を説明します。このアドオンでは、チーム向け Acrobat DC またはエンタープライズ向け Acrobat DC のサブスクリプションが必要です。 |
| 2021 年 11 月 | [リアルタイムでの共同作業](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/collaborate.html?lang=ja) | ビデオ | コメントを収集、回答に共同作業で対応、ドキュメントの進行状況を追跡するといった作業をどこにいてもリアルタイムで行うことで、プロジェクトを先に進めます。 |
| 2021 年 11 月 | [外出時の生産性](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/productivity.html?lang=ja) | ビデオ | Acrobat Reader モバイルアプリを使用すれば、タブレットや携帯電話からより多くの適切な処理を実行できます。 |

{style=&quot;table-layout:auto&quot;}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Creative Cloud エンタープライズ版 {#creative-cloud}

最新のチュートリアルについては、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ja)を参照してください。

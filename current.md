---
title: 最新のリリースノート
description: ' [!DNL Experience Cloud]  製品およびサービスに関する最新のリリースノート、新機能、新規ドキュメントについて説明します。 [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud] に関する新しいヘルプとチュートリアルをご覧ください。'
doc-type: release notes
last-update: November 2021
author: mfrei
mini-toc-levels: 1
exl-id: null
source-git-commit: ed5f9c6b35b65bab0c26887788e2232a0e9a6ab5
workflow-type: tm+mt
source-wordcount: '4147'
ht-degree: 63%

---

# Adobe Experience Cloud リリースノート - 2021 年 11 月

![バナー](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] アプリケーションおよびサービスは毎月更新されます。このページには、[!DNL Experience Cloud] と [!DNL Experience Platform] の最新のリリースアップデート、ドキュメントおよびチュートリアルが集約されています。また、[!DNL Creative Cloud for enterprise] と [!DNL Document Cloud] の新しいドキュメントも参照できます。

>[!NOTE]
>
>毎月[アドビの優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)をサブスクライブして、このページの更新に関する電子メール通知を受信します。このページはひと月にわたって保持されるので、定期的にアクセスして、アドビのエンタープライズ製品と Experience League のドキュメントが更新されていないか確認してください。

リリース月： **2021 年 11 月**

最終更新日：**2021 年 10 月 22 日**

* [[!DNL Experience League] ライブイベント](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; 管理](#ecloud)
* [アドビ [!UICONTROL システムステータス]](#status)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics) および [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。

## ![アイコン](/assets/experience-league.png) [!DNL Experience League] ライブイベント {#events}

[Experience Leagueライブイベント](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) は、Adobeの専門家や特別なゲストとのディスカッションで、Adobe技術をお客様に提供するのに役立ちます。 以下のスケジュールを参照してライブに参加したり、過去の録画イベントを視聴したりしましょう。

| イベントの日付 | 時間 | イベント名 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021年10月21日（PT） | オンデマンド | [クリックしたのは誰でしょう？Adobe Analytics によるリンククリックの高度なレポート機能](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) | ライブビデオイベント | Web またはモバイルプロパティとのユーザーインタラクションに関するレポート作成は、顧客のジャーニーを把握するうえで重要です。Adobe Analytics を使用すると、アプリケーション内でクリックしたユーザー、対象、理由、場所を把握できます。Adobe Analytics のエキスパートが Activity Map の分類とカスタム属性を使用して、ユーザーエンゲージメントをより深く理解するためのヒントを紹介します。 |
| 2021 年 10 月 4 日（PT） | オンデマンド | [アドビ開発者ライブ](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=ja) | ビデオ | イベントを見逃したか、特定のセッションの再生を探しているか。 Experience League。 Developers Live は、業界をまたいだ設計、コンテンツ作成ワークフロー、ドキュメントサービス、顧客体験管理を支える最新の技術進歩と開発者ツールを紹介します。 基調講演を表示し、Analytics API、クライアントデータレイヤー、Adobe I/Oオープンソースプロジェクトなどについて学びます。 |

{style=&quot;table-layout:auto&quot;}

その他のビデオについては、YouTube の [Adobe Experience League チャンネル](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] と管理 {#ecloud}

| 機能 | 説明 |
| ------- | ------- |
| ホームページ | Experience Cloudホームのフッター情報は、環境設定の法律上の注意事項や言語の選択など、ユーザープロファイルカードに移動されました。 |
| AEP ダッシュボード | [!DNL Helios Lite] は、ウィジェット作成ワークフロー内で推奨されるExperience Platformを提供します。 データ選択（現在は単一の変数データ選択）が指定されている場合、 [!DNL Helios] では、データの選択に伴う適切なビジュアライゼーションが推奨されます。 |
| AEP ダッシュボード | [!DNL Instory] は、グラフに ML ベースの書き込みナレーションとキャプションを提供します。 AEP ダッシュボードページのグラフに、グラフ化されたデータの大きな変更やインシデントを呼び出す、関連する箇条書きでデコレートします。 |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components]と管理に関するその他のヘルプリソース**

* [主要なインターフェイスコンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)およびユーザー管理の管理ヘルプ
* [Places - 位置情報サービス](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ja)のヘルプとリリースノート
* [People - 顧客属性とオーディエンスライブラリ](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ja)に関するヘルプ

## ![アイコン](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] は、Adobe製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/ja) でご確認ください。

（[!DNL Adobe System Status]の最新のリリース情報は、[2020年5月21日（PT）](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ja)のリリースノートをご覧ください。）

## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Experience Platform と[!UICONTROL モバイル SDK] に関するリリース更新情報と新しいドキュメントが含まれます。

**2021 年 9 月 29 日**

詳しくは、 [Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja) を参照してください。

### Experience Platform チュートリアルおよびコース {#tutorials-platform}

Experience Platform およびサービス用に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年11月 | [ ファーストパーティデータコンテキストでのデータ共同作業 ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/industry/data-collaboration-in-the-first-party-data-context.html?lang=en#) | ビデオ | より少ないデータへのアクセスで、エクスペリエンスプロミスで配信。 広告主、発行者、代理店を問わず、このウェビナーを通じて、サードパーティ Cookie を使用しない将来のデータコラボレーションの機会を解放できます。 |
| 2021年10月 | [[!DNL Platform] 管理](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | コース | 権限やサンドボックス管理など、Experience Platform の管理アクティビティについて説明します。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

Adobe Experience Platform Mobile SDK の [リリースノートと変更ログ](https://aep-sdks.gitbook.io/docs/release-notes) を参照してください。

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
| Analysis Workspaceの分レベルの日付範囲 | パネルカレンダーの詳細設定で、またはカスタム日付範囲を作成する際に、分レベルの日付範囲を適用できます。 何日もにわたる日付範囲でレポートを作成する場合、開始時間は最初の日に適用され、終了時間は範囲内の最終日に適用されます。 | 2021年10月19日 |
| [!UICONTROL メディア再生滞在時間] | アドビのストリーミングメディア再生[!UICONTROL 滞在時間] は、ビューアのエンゲージメントに関する貴重なインサイトを提供し、メディア企業は日分割機能を備えた高度な滞在時間分析を通じて、分単位のユーザーエンゲージメントに関する、より深く、より詳細なインサイトを得ることができます。特定の時点でのメディアストリームの視聴時間を確認できます。再生時間は、新しい 5 分、15 分および 30 分の精度を含む様々な精度で分割できます。 [詳細情報](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=ja) | 2021年10月19日 |
| クイック[!UICONTROL セグメントビルダー] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで、基本的なセグメントをすばやく適用できます。[!UICONTROL セグメントビルダー]に移動する必要はありません。[詳細情報](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=ja) | 2021年10月21日（PT） |
| Analysis Workspace 左パネルの検索の改善 | 左レール検索 1) は、コンポーネントの最新性と関連性に加え、部分一致以上の完全一致を優先します。 2）一致した文字をハイライトして、検索結果をわかりやすくします。3）ディメンションに関連する分類を見つけやすくなります。4）最後に、ワイルドカード（`*`）検索をサポートして、必要な特定のコンポーネントをより簡単に見つけます。注意：ワイルドカード検索は、ディメンション項目レベルではまだ機能しません。 | 2021年10月21日（PT） |
| ダークテーマ | [ダークテーマは表示オプションとして使用できます。](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/user-preferences.html?lang=en#dark-theme) | 2021年10月21日（PT） |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html) - ターゲット日 |
| ----------- | ---------- | ----- |
| Analysis Workspaceの分レベルの日付範囲 | パネルカレンダーの詳細設定で、またはカスタム日付範囲を作成する際に、分レベルの日付範囲を適用できます。 何日もにわたる日付範囲でレポートを作成する場合、開始時間は最初の日に適用され、終了時間は範囲内の最終日に適用されます。 | 2021年10月19日 |
| クイック[!UICONTROL フィルタービルダー] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで、基本的なセグメントをすばやく適用できます。[!UICONTROL フィルタービルダー]に移動する必要はありません。[詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html) | 2021年10月21日（PT） |
| Analysis Workspace 左パネルの検索の改善 | 左レール検索 1) は、コンポーネントの最新性と関連性に加え、部分一致以上の完全一致を優先します。 2）一致した文字をハイライトして、検索結果をわかりやすくします。3）ディメンションに関連する分類を見つけやすくなります。4）最後に、ワイルドカード（`*`）検索をサポートして、必要な特定のコンポーネントをより簡単に見つけます。注意：ワイルドカード検索は、ディメンション項目レベルではまだ機能しません。 | 2021年10月21日（PT） |
| ダークテーマ | [ダークテーマは表示オプションとして使用できます。](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-workspace/user-preferences.html?lang=en#dark-theme) | 2021年10月21日（PT） |
| ディメンション割り当てのルックバックウィンドウ | データビュー設定の「永続性」の下で、ディメンション割り当て設定に最大 90 日のルックバック期間が追加されます。 [詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html) | 2021 年 10 月 28 日（PT） |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics の修正点 {#aa-fixes}

* アラートマネージャーでアラートを削除できなかった問題を修正しました。 （AN-270656）
* Data Warehouseリクエストが断続的に失敗する問題を修正しました。 （AN-273713、AN-272790）
* 分類が更新されない問題を修正しました。 （AN-272211）

### Customer Journey Analyticsの修正点 {#cja-fixes}

* CJA のパフォーマンスの問題（プロジェクトの読み込み中にエラーメッセージ）を修正しました。 （AN-269451、AN-270649）
* CJA で、セッション開始がページ名のフローエントリと一致しなかった問題を修正しました。 （AN-273501）
* CJA のフォールアウトレポートが正しく機能しない問題を修正しました。 （AN-269761）

#### Adobe Analytics におけるその他の修正点

AN-263327;AN-267807;AN-269757;AN-272789;AN-272888;AN-273155;AN-273320;AN-273369;AN-273405;AN-273469;AN-273581;AN-273642;AN-273688;AN-273988;AN-274007;AN-274030;AN-274156;AN-274188;AN-274226

#### CJA のその他の修正点

AN-270649

### [!DNL Analytics] 管理者向けの重要な注意事項  {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| 3 つの Analytics API サービスの提供終了 | 2021年9月16日（PT） | **2021年10月20日（PT）**、次の Analytics レガシー API サービスの提供が終了し、サービスが停止されます。これらのサービスを使用して現在構築されている統合は、その日以降使用できなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>アドビでは、お客様のご質問に対する回答や進め方に関するガイダンスを提供するために、[従来の API の EOL（サポート終了）に関する FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe I/O](https://developer.adobe.com/console) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API のどちらにアクセスする場合にも使用できます。 |
| データソースでのフル処理のサポート終了 | 2021年10月19日 | オン **2022 年 1 月 31 日**、Adobeはフル処理のサポートを終了し、オフラインのヒットデータを Analytics に取り込めるようになります。 この機能は、 [一括データ挿入 API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md). [詳細情報](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=ja?lang=ja) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

AppMeasurement リリース（バージョン 2.22.2）の最新の更新については、[JavaScript リリースノートの AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja) を参照してください。

### Analytics コースとチュートリアル {#tutorials-analytics}

[!DNL Analytics] および [!UICONTROL Customer Journey Analytics] の最新のコース、チュートリアル、記事。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年11月 | [Adobe Analyticsのセグメントコンテナ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-containers.html?lang=en) | ビデオ（更新） | このビデオでは、コンテナの使用方法と、各タイプのコンテナの例をいくつか学びます。 |
| 2021年11月 | [Adobe Analyticsでの順次セグメント化](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/sequential-segmentation.html?lang=en#) | ビデオ（更新） | サイト上またはアプリケーション上での一連の行動から、Analysis Workspaceでセグメントを作成する方法を説明します。 |
| 2021年11月 | [順次セグメント化での前後のシーケンス](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/before-after-sequences-in-sequential-segmentation.html?lang=en) | ビデオ（更新） | 特定のユーザーパスの前または後のデータのみを取得できるようにAdobe Analyticsでセグメント化する方法を説明します。 |
| 2021年11月 | [Customer Journey Analytics 用の Report Builder](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/report-builder-for-customer-journey-analytics.html) | ビデオ | Report Builder のシンプルで柔軟なドラッグ＆ドロップ UI を使用すると、Customer Journey Analytics データから複雑なデータクエリやカスタムレポートをすべて Excel 内で作成できます。 |
| 2021年10月 | [ビジュアライゼーションを使用したデータストーリーの把握](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | コース | ビジュアライゼーションの基本について説明します。例えば、プロジェクトへの追加方法、プロジェクトへのデータの取得方法、各ビジュアライゼーションで表示できる内容などです。 必要な正確なデータを取得するための設定方法を説明します。また、標準的な分析にビジュアライゼーションを使用できるようにするためのヒントや使用例を説明します。 |

{style=&quot;table-layout:auto&quot;}

### Analytics ヘルプリソース

* [Adobe Analytics 製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の修正点と改善点。

* すべての API 呼び出しで `Undocumented` Swagger インターフェイスで実行中にエラーが発生しました。 （AAM-59190）
* 場合によって誤ったユーザーの役割がパートナーに割り当てられる問題を修正しました。 （AAM-59451）
* API で大文字と小文字を区別する認証ヘッダーが必要となる問題を修正しました。 （AAM-58528）

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

[Adobe Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することをお勧めします。

### リリースの概要ビデオ

* [2021 年 10 月リリースの概要](https://video.tv.adobe.com/v/338253) 新機能のビデオ。
* [2021 年 9 月リリース概要](https://video.tv.adobe.com/v/337381) 新機能のビデオ。

### コミュニティ

* [アドビ開発者向けライブ](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021年10月4～5日、7:00（PDT）

   アドビ開発者向けライブは、多様な背景と単一の目的を持つアドビ開発者とエクスペリエンスビルダーを結集し、素晴らしいエンドツーエンドのエクスペリエンスを作り出します。この 2 日間の会議では、開発者向けの重要な更新、技術セッション、コミュニティネットワークの機会を紹介します。

   Experience Cloud、Document Cloud、Creative CloudをまたいだAdobe製品チームは、デザイン、コンテンツ作成ワークフロー、ドキュメントサービス、顧客体験管理を業界全体で実行する最新の技術進歩と開発者ツールを紹介します。

   アドビでは、20 回の Experience Manager セッションが予定されています。周囲の人も誘ってぜひ参加ください。

   * [セッションリストの完了](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041?profile.language=ja#M120517)
   * [無料登録 — RSVP にログインします](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [アドビ開発者ライブコミュニティ](https://experienceleaguecommunities.adobe.com:443/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-4th-amp-5th/td-p/422127)

### 新しい Adobe Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | 説明 | タイプ | バージョン |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021年11月 | [Adobe Experience Manager Sites Basics](https://experienceleague.adobe.com/docs/experience-manager-skill-builder/skill-builder/2021/authoring-fundamentals.html?lang=en) | ビデオシリーズ | Adobe Experience Managerで豊富で魅力的な顧客体験を作成する方法については、5 部構成のウェビナーシリーズを参照してください。 基本的な概念と操作を学習しながら、コンテンツオーサリングの構成要素から始めます。 AEM内でのデジタルアセットの管理機能と操作の基本について説明します。 その後、コンテンツを再利用して複数のチャネルに配信することで、時間を節約し、より効率的な機能を見つけ出すことができます。 | AEM Sites |
| 2021年11月 | [AEMへの移行の計画をas a Cloud Service](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2021.1.migration) | コース | AEM as a Cloud Serviceへの移行に関する考慮事項と、プロセスを簡略化する使用可能なツールについて説明します。 | AEM CS |
| 2021年11月 | [AEM as a Cloud Service への移行](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2021.1.migration) | コース | AEM 6 からas a Cloud ServiceExperience Managerへの移行に成功する方法を説明します。 | AEM CS |
| 2021年11月 | [インタラクティブ DoR をダウンロード](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/generate-interactive-dor.html?lang=en#create-custom-servlet) | ビデオ | アダプティブフォームデータを含むインタラクティブ DoR をダウンロードする方法を説明します。 | AEM Forms |
| 2021年11月 | [Adobe Experience Manager as a Cloud Service Experts Series](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/aem-experts-series.html?lang=en) | ビデオシリーズ | Adobe Experience Manager(AEM) を構築するAdobeのエキスパートエンジニア、およびそれを提供する Professional Services チームからas a Cloud Serviceした情報を紹介します。 Adobeの専門家に参加して、AEMのas a Cloud Serviceとは何か、AEM 6 との比較、AEM 6 からAEM as a Cloud Serviceへの移行方法を調べてください。 | AEM CS |
| 2021年11月 | [サービスユーザー](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/advanced/service-users.html?lang=en) | ビデオ | AEMコードでサービスユーザーを作成および使用して、制御された、プログラムによってAEMリポジトリにアクセスする方法について説明します。 | AEM CS |

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

### 新しいAdobe Commerceチュートリアル {#commerce-tutorials}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年11月 | [Adobe CommerceのビデオとTutorials](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/overview.html?lang=en) | チュートリアルホーム | これらのチュートリアルリソースには、トピックの概要を示すビデオシリーズや、特定のタスクおよびプロセスを対象とする個々のビデオが含まれます。 このコレクションは、バックエンド開発者、フロントエンド開発者、システム管理者、マーチャント、組織内のその他の役割に役立つコンテンツを提供するように設計されています。 |

## ![アイコン](/assets/target.png) [!DNL Target] {#target}

最終更新日： **2021 年 10 月 21 日**

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
| 2021年11月 | [Campaign を Experience Platform に接続して宛先にする](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/connect-campaign-to-experience-platform-as-destination.html?lang=en) | ビデオ | Amazon S3 の接続タイプを使用し、宛先に対して Adobe Experience Platform セグメントをアクティブ化する方法を説明します。 | AEP と Campaign V8 |
| 2021年11月 | [Experience Platform との統合 - 概要](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/overview.html?lang=en) | ビデオ | Campaign と Experience Cloud 間でのデータの共有方法を説明します。 | AEP と Campaign V8 |
| 2021年11月 | [受信者データを Experience Platform から読み込んでメールを送信する](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/import-recipient-data-from-platform.html?lang=en) | ビデオ | Adobe Experience Platform から Campaign に受信者データを読み込むために Adobe Campaign で外部アカウントを設定する方法を説明します。 Experience Platform  から読み込んだ受信者をアップロードおよびターゲティングするワークフローの作成方法を理解します。 | AEP と Campaign V8 |
| 2021年11月 | [ワークフローでの SOAP API の使用](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | ビデオチュートリアル | Adobe Campaign Soap API を使用し、API 経由で受信したデータに基づいて高度な配信ワークフローを作成する方法を説明します。 | Campaign V8 |

{style=&quot;table-layout:auto&quot;}

### Campaign ヘルプリソース

* Adobe Campaign v8: [ドキュメント](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=ja) - [実装ガイド](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ja)
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
| 2021年10月 | [データエンジニア向け [!DNL Journey Optimizer] データの設定と管理](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | コース | Journey Optimizer でのジャーニー管理に必要なデータの設定と管理方法について説明します。 |
| 2021年10月 | [ジャーニー管理者およびマネージャー [!DNL Journey Optimizer] の概要](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | コース | 最初のジャーニーを作成するために知っておく必要のあるすべてを学びます。 |
| 2021年10月 | [ジャーニー管理者用 [!DNL Journey Optimizer] の設定](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | コース | [!DNL Journey Optimizer] のアーキテクチャと統合のポイントを理解します。[!DNL Journey Optimizer] の設定方法を説明します。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] のその他のリソース

* [Journey Optimizerドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ja) - [リリースルート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ja)
* [決定管理ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html) - [最新のドキュメントの更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

### 最新の [!DNL Journey Orchestration] 製品リリース

の最新の機能、改善点、修正点について詳しくは、 [[!DNL Journey Orchestration] リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ja).

#### [!DNL Journey Orchestration] のその他のリソース

* [Journey Orchestration文書](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ja-JP) - [最新のドキュメントの更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ja)

## ![アイコン](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーのすべてのステージにわたるエンゲージメントを通じてカスタマーエクスペリエンスを変革しようとしている経営陣や B2B マーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

最新のリリーススケジュール情報とリリースノートについては、[!DNL Marketo Engage] [リリーススケジュール](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ja)を参照してください。

## ![アイコン](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] は、アイデアの共有、コンテンツの作成、複雑なプロセスの管理、および最高の作業を行うための統合作業管理アプリケーションです。

すべての製品の最新情報のまとめについては、[[!DNL Workfront] リリース](https://one.workfront.com/s/product-releases)ページを参照してください。

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

リリースノート： [!DNL Adobe Advertising Cloud]

* [ [!DNL Advertising Cloud DSP] の新機能 ](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] の新機能 ](#adcloud-search)

### [!DNL Advertising Cloud DSP] の新機能  {#adcloud-dsp}

最終更新日：**2021 年 10 月 7 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| ドキュメント | すべて [DSPおよびその他のAdvertising Cloudドキュメント](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=ja) オン [!DNL Experience League] は、すべての使用可能な言語に機械翻訳されるようになりました。 表示言語を変更するには、ページの左下にある「言語を変更」メニューを使用します。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] の新機能  {#adcloud-search}

最終更新日：**2021 年 10 月 7 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| [!UICONTROL レポート]、[!UICONTROL 通知センター] | （10月9日リリース）カスタムレポートまたは予定レポートの作成が完了または失敗したときに Advertising Cloud Search から送信されるレポート関連のすべてのメール通知は、[!UICONTROL 通知センター]で処理されるようになりました。レポートについては、メール通知と web 通知がデフォルトで有効になっていますが、オプションで通知設定を変更できます。今回の変更により、<ul><li>電子メール受信者は、Advertising Cloud Searchの登録ユーザー、認証済みユーザー、および広告主アカウントへのアクセス権を持つユーザーに制限されます。 この機能により、権限のないユーザーに機密データを送信しなくなります。</li><li>メールの形式とコンテンツでは、[!UICONTROL 通知センター]のテンプレートが使用されます。このテンプレートには、レポートの詳細が記述されており、すべてのレポート形式に対応する直接ダウンロードリンクが含まれています。</li><li>レポート通知は、[!UICONTROL 通知センター]の新しい通知タイプで、独自の通知設定を備えています。</li></ul>何らかの自動処理を使用してメール通知からレポートを取り込む場合は、フィルタリングロジックを更新して、プロセスが確実に継続されるようにしなければならないことがあります。 |
| 広告インサイト | ベータモードでは、追加のインサイトを利用できます。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

新しく公開された Adobe Document Cloud ビデオ、チュートリアル、コース。

### Document Cloud のコースとチュートリアル {#tutorials-doc-cloud}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年11月 | [ワークスペースの基本](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/get-to-know-the-acrobat-dc-interface.html) | ビデオ（更新） | Acrobat DCインターフェイスを使用して、一貫したワークスペースエクスペリエンスで、デスクトップ、Web およびモバイルデバイス全体でファイルやツールに簡単にアクセスできるようにする方法を説明します。 |
| 2021年11月 | [Acrobat Web を使用してどこでも作業](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/acrobatweb.html) | ビデオ | ブラウザーのAcrobat Web ツールを使用して、どこからでもビジネスドキュメントのリクエストを処理する方法を説明します。 |
| 2021年11月 | [Office で Web 用のPDFを作成する ](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/createofficeweb.html) | ビデオ | Web アプリ用のMicrosoft® Office から離れることなくPDFファイルを作成する方法を説明します。 このアドオンでは、チーム向けAcrobat DCのサブスクリプションか、エンタープライズ向けAcrobat DCのサブスクリプションが必要です。 |
| 2021年11月 | [リアルタイムでの共同作業](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/collaborate.html) | ビデオ | コメントを収集し、回答に関する共同作業を行い、ドキュメントの進捗状況をリアルタイムでどこからでも追跡することで、プロジェクトを前に進めます。 |
| 2021年11月 | [ 生産性を常に向上](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/productivity.html) | ビデオ | Acrobat Readerモバイルアプリで、タブレットや携帯電話からより適切に操作できます。 |

{style=&quot;table-layout:auto&quot;}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Creative Cloud エンタープライズ版 {#creative-cloud}

最新のチュートリアルについては、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en)を参照してください。

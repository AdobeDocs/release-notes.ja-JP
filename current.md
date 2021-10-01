---
title: 最新のリリースノート
description: ' [!DNL Experience Cloud]  製品およびサービスの最新のリリースノート、新機能、新しいドキュメントについて説明します。  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud] に関する新しいヘルプとチュートリアルを見つけます。'
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
source-git-commit: 8b36fbc422c8b7b2bf3f2a7497a5dc51495e0562
workflow-type: tm+mt
source-wordcount: '5136'
ht-degree: 40%

---

# Adobe Experience Cloud リリースノート - 2021 年 10 月

![バナー](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] アプリケーションおよびサービスは毎月更新されます。このページには、[!DNL Experience Cloud] と [!DNL Experience Platform] の最新のリリースアップデート、ドキュメントおよびチュートリアルが集約されています。また、[!DNL Creative Cloud for enterprise] と [!DNL Document Cloud] の新しいドキュメントも参照できます。

>[!NOTE]
>
>毎月[アドビの優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)をサブスクライブして、このページの更新に関する電子メール通知を受信します。このページはひと月にわたって保持されるので、定期的にアクセスして、アドビのエンタープライズ製品と Experience League のドキュメントが更新されていないか確認してください。

最終更新日：**2021 年 10 月 1 日**

* [[!DNL Experience League] ライブイベント](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; 管理](#ecloud)
* [Adobe [!UICONTROL システムステータス]](#status)
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

[!DNL Experience League] ライブイベントとは、アドビの技術を学べる、Adobe の専門家や特別なゲストとのディスカッションです。以下のスケジュールを参照してライブに参加したり、過去の録画イベントを視聴したりしましょう。

| イベントの日付 | イベント名 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年9月23日（PT） | [ホリデーキャンペーンを目立たせるためのエキスパートのヒント](https://www.youtube.com/watch?v=bsU1lAv0xes) | ライブビデオイベント | 休暇に備えた買い物を始めるのに早すぎることがないのと同じように、ホリデーマーケティングキャンペーンを大成功に導くための計画に早すぎることはありません。Adobe Campaign を使用すると、組織の目標を達成するキャンペーンを設計、計画、実行できます。<br>でも、1 年を超えて大きな成果を上げるキャンペーンを実行するためのヒントを知っていますか？Sandra に参加して、3 人のAdobe専門家が集団的な専門知識を持つライブディスカッションを行います。 |
| 2021年8月26日（PT） | [次のオーディエンスセグメントを従来よりもスマートに](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=jp) | イベントの録画 | すべての優れたマーケティングキャンペーンを成功させるには、オーディエンスのターゲティングを正確におこなう必要があります。新しい Adobe Experience Platform [!UICONTROL セグメントビルダー] を使用すると、チャネルをまたいでプロファイルデータと時間ベースのユーザー行動を使用して、次のオーディエンスセグメントを作成できます。最も必要としている人にメッセージを届けるのに、これ以上の方法はありません。 |
| 2021年7月29日（PT） | [Adobe Analytics の実装に関する 3 つのお気に入りのヒント](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=jp) | イベントの録画 | Summit のステージで彼をご覧になった方もいるでしょう。Adobe インサイダーツアーでは、専門家としてアドバイスを提供しました。お客様自身の Adobe Analytics 実装に、彼と一緒に取り組めるというメリットが得られるかもしれません。エリック・マティソフフは、このメンバー限定 Experience League のライブディスカッションで、Adobe Analytics の実装に関する 3 つのお気に入りのヒントを紹介します。 |

{style=&quot;table-layout:auto&quot;}

その他のビデオについては、YouTube の [Adobe Experience League チャンネル](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] と管理 {#ecloud}

| 機能 | 説明 |
| ------- | ------- |
| 統合検索 | 統合検索では、引き続き検索インデックスにオブジェクトタイプが追加されます。 この更新では、グローバル検索で、Experience Leagueコンテンツと次のJourney Optimizerオブジェクトタイプをまたいで検索するようになりました。 <ul><li>データセット</li><li>宛先</li><li>クエリ</li><li>スキーマ</li><li>セグメント</li><li>ソース</li><li>オファー</li><li>コンポーネント</li><li>メッセージ</li><li>ジャーニー</li></ul> |
| 製品使用データの同意 | 初回ログイン時に、AdobeがExperience Cloud製品の使用状況データに基づいて、チュートリアル、ガイド、クイックヒント、レコメンデーション、学習ビデオなど、パーソナライズされた便利なコンテンツを提供する方法に関する環境設定を送信するよう求められます。 このリクエストには、<https://experience.adobe.com/preferences> でのこれらのデータの収集と使用に関する環境設定の更新も含まれています。 |
| Experience Cloud[!UICONTROL トリガー] ナビゲーション | [Experience Cloudト](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) リガーは、プロビジョニングされたユーザーのヘッダーのアプリケーション切り替えボタンから直接ナビゲーションできます。 |
| **注意：** 計画的なインターフェイスナビゲーション更新 | 2021 年 11 月に、_[!UICONTROL Launch /データ収集]_ に移動ナビゲーション機能が <https://experience.adobe.com/implement> から削除されます。 |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components]と管理に関するその他のヘルプリソース**

* [主要なインターフェイスコンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)およびユーザー管理の管理ヘルプ
* [Places - 位置情報サービス](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ja)のヘルプとリリースノート
* [People — 顧客属性とオーディエンスライブラリ ](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en) に関するヘルプ

## ![アイコン](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] は、Adobe製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

（[!DNL Adobe System Status]の最新のリリース情報は、[2020年5月21日（PT）](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ja)のリリースノートをご覧ください。）

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2021 年 10 月 7 日**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [Analytics コースとチュートリアル](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=jp) - ターゲット日 |
| ----------- | ---------- | ------- |
| Analytics ダッシュボードのビジュアライゼーション | Analytics [!UICONTROL  ダッシュボード ] には、3 つの新しいビジュアライゼーションが導入され、エグゼクティブや意思決定者がデータを一目で把握できるようになりました。 新しい [!UICONTROL  ドーナツ ]、[!UICONTROL  線 ]、[!UICONTROL  横 ] の棒グラフを使用すると、詳細ビューを開かなくても、個々のディメンション項目のデータを簡単に確認できます。 （後に続くドキュメントリンク） | 2021年10月7日（PT） |
| [!UICONTROL メディア再生滞在時間] | Adobeストリーミングメディア再生 [!UICONTROL  滞在時間 ] は、ビューアの関与に関する貴重なインサイトを提供し、日分割機能を備えた高度な滞在時間分析を通じて、分単位のユーザーエンゲージメントでより深く詳細なインサイトを得ます。 特定の時点でのメディアストリームの視聴に費やした時間を確認できます。 再生時間は、新しい 5 分、15 分、30 分の精度を含む様々な精度で分割できます。 [詳細情報](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 2021 年 10 月 19 日 |
| クイック [!UICONTROL  セグメントビルダー ] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで、基本的なセグメントをすばやく適用できます。 [!UICONTROL  セグメントビルダー ] に移動する必要はありません。 [詳細情報](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 2021年10月21日（PT） |
| Analysis Workspace左パネルの検索の改善 | 左パネルの検索 1) コンポーネントの最新性と関連性を引き続き考慮するのに加え、部分一致を上回る完全一致を優先します。 2) 一致した文字を強調表示して、検索結果をわかりやすくします。 3) ディメンションに関連する分類を見つけやすくなります。 4) 最後に、必要な特定のコンポーネントをより簡単に見つけるために、ワイルドカード (`*`) 検索をサポートします。 注意：ワイルドカード検索は、ディメンション項目レベルではまだ機能しません。 | 2021年10月21日（PT） |
| Analysis Workspaceダークテーマ | ダークテーマは表示オプションとして使用できます。 | 2021年10月21日（PT） |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - ターゲット日 |
| ----------- | ---------- | ----- |
| Report Builder支援 | Report Builderは、Microsoft® [!DNL Excel] アドインで、Customer Journey Analyticsデータを使用して、カスタムレポートを簡単に作成、編集、更新できます。 Report Builderと Excel を使用すると、シンプルで柔軟なドラッグ&amp;ドロップ UI を使用して、複雑なデータリクエストを簡単に作成できます。 Customer Journey AnalyticsのReport Builderを使用すると、次のことができます。<ul><li>既存のワークシートのセルを参照して、完全な行順、日付範囲、またはフィルターを取得します</li><li>カレンダー、セル参照、日付計算を使用してカスタム日付を作成する</li><li>使い慣れた Excel の書式設定ツールを使用して、テーブルやビジュアライゼーションをデザインする</li><li>MacOS、Web 用 Microsoft 365、および Microsoft Windows で利用可能</li></ul> | 2021年10月7日（PT） |
| Analytics ダッシュボードのビジュアライゼーション | Analytics [!UICONTROL  ダッシュボード ] には、3 つの新しいビジュアライゼーションが導入され、エグゼクティブや意思決定者がデータを一目で把握できるようになりました。 新しいドーナツグラフ、折れ線グラフ、横棒グラフを使用すると、詳細ビューを開かなくても、個々のディメンション項目のデータを簡単に確認できます。 （後に続くドキュメントリンク） | 2021年10月7日（PT） |
| Customer Journey Analytics監査ログ（API のみ） | 監査ログは、セキュリティコンプライアンスの重要な部分であり、データやユーザーアクションを監査するうえで重要です。 | 2021年10月7日（PT） |
| クイック [!UICONTROL  フィルタービルダー ] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで、基本的なセグメントをすばやく適用できます。 [!UICONTROL  フィルタービルダー ] に移動する必要はありません。 [詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 2021年10月21日（PT） |
| Analysis Workspace左パネルの検索の改善 | 左パネルの検索 1) コンポーネントの最新性と関連性を引き続き考慮するのに加え、部分一致を上回る完全一致を優先します。 2) 一致した文字を強調表示して、検索結果をわかりやすくします。 3) ディメンションに関連する分類を見つけやすくなります。 4) 最後に、必要な特定のコンポーネントをより簡単に見つけるために、ワイルドカード (`*`) 検索をサポートします。 注意：ワイルドカード検索は、ディメンション項目レベルではまだ機能しません。 | 2021年10月21日（PT） |
| Analysis Workspaceダークテーマ | ダークテーマは表示オプションとして使用できます。 | 2021年10月21日（PT） |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics の修正点と CJA の修正点 {#aa-fixes}

* 予定レポートのエラーのCustomer Journey Analytics。 （AN-271721）
* [!UICONTROL Workspace] の [!UICONTROL  検索コンポーネント ] で、完全に一致しない問題を修正しました。 （AN-253937、AN-271707）

#### Adobe Analytics におけるその他の修正点

AN-256136;AN-265420;AN-268455;AN-269768;AN-270276;AN-270287;AN-271601;AN-271969;AN-272056;AN-272111;AN-272457

### [!DNL Analytics] 管理者向けの重要な注意事項  {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| 3 つの Analytics API サービスの提供終了 | 2021年9月16日（PT） | **2021 年 10 月 28 日** に、次の Analytics レガシー API サービスが提供終了日に達し、シャットダウンされます。 これらのサービスを使用して現在構築されている統合は、その日以降使用できなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>アドビでは、お客様のご質問に対する回答や進め方に関するガイダンスを提供するために、[従来の API の EOL（サポート終了）に関する FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe I/O](https://developer.adobe.com/console) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API のどちらにアクセスする場合にも使用できます。 |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

AppMeasurement リリース（バージョン 2.22.2）の最新の更新については、[JavaScript リリースノートの AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja) を参照してください。

### Analytics コースとチュートリアル {#tutorials-analytics}

[!DNL Analytics] と [!UICONTROL Customer Journey Analytics] の最新のコース、チュートリアル、記事。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年10月 | [ビジュアライゼーションを使用したデータストーリーの把握](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | コース | データからインサイトを引き出そうとするだけで、テーブルの後にテーブルをスカーするのは誰ですか？ お前は！ このコースでは、ビジュアライゼーションの基本について説明します。例えば、プロジェクトへの追加方法、データの取得方法、各ビジュアライゼーションで表示できる内容などです。 必要な正確なデータを取得するための設定方法を説明します。 また、ビジュアライゼーションを通常の分析に役立てるのに役立つヒントと使用例を紹介します。 |

{style=&quot;table-layout:auto&quot;}

### Analytics ヘルプリソース

* [Adobe Analytics 製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の新機能 - 更新日 **2021年9月14日（PT）**:

| 機能 | 説明 |
| ------- | ------- |
| モバイル ID データ収集の同意 | モバイル ID データ収集の同意のサポートが追加されました。このアップデートのメリットを享受するには、[AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) 以降にアップグレードする必要があります。 |

## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

リリースの更新情報と、Experience Platformおよび [!UICONTROL Mobile SDK] の新しいドキュメントが含まれています。

**2021 年 9 月 29 日**

| 機能 | 説明 |
| ------- | ------- |
| [[!UICONTROL データランディングゾーン]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL Data Landing Zone は、プロビジョニ] ングさ [!DNL Platform]れた  Azure Blob Store で、サンドボックスごとに 1 つの安全で一時的なストレージでファイルをExperience Platformに取り込むことができます。 |
| [ データの準備 ](https://www.adobe.com/go/monitor-streaming-dataflows-en) のストリーミングソースのサポート | ストリーミングソースでデータの準備がサポートされ、XDM と互換性のないソースデータをターゲット XDM スキーマにマッピングする JSON ソーススキーマを提供できるようになりました。 |
| [期限切れでない資格情報](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | [!UICONTROL  クエリサービス ] ユーザーの期限が切れていない資格情報は、24 時間ごとに資格情報を更新する代わりに、外部クライアントへのより多くの永続的な接続を許可します。 |
| [[!UICONTROL 宛先 SDK]](https://www.adobe.com/go/destination-sdk-overview-en) | [!UICONTROL  宛先 SDK] を使用して [!DNL Platform] と統合し、増え続ける宛先カタログに貢献します。 この機能へのアクセスは、Experience Platformのアクティベーションのお客様のみがおこなえます。 |

詳しくは、 [Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja) を参照してください。

### Experience Platform チュートリアルおよびコース {#tutorials-platform}

Experience Platformおよびサービス用に公開された最新のビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年10月 | [[!DNL Platform] 管理](https://experienceleague.corp.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | コース | 権限やサンドボックス管理など、Experience Platformの管理アクティビティについて説明します。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

Adobe Experience Platform Mobile SDK の [リリースノートと変更ログ](https://aep-sdks.gitbook.io/docs/release-notes) を参照してください。

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

最新の機能、改善点および修正点について詳しくは、[Journey Orchestration リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ja)を参照してください。

### Journey Optimizerのチュートリアルとコース {#tutorials-ajo}

最新のJourney Optimizerチュートリアル：

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年10月 | [データエンジニア向け [!DNL Journey Optimizer] のデータの設定と管理](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | コース | Journey Optimizerでのジャーニー管理に必要なデータの設定と管理方法について説明します。 |
| 2021年10月 | [ジャーニー管理者お [!DNL Journey Optimizer] よびマネージャーの概要](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | コース | 最初のジャーニーを作成するために知っておく必要のあるすべてを学びます。 |
| 2021年10月 | [ [!DNL Journey Optimizer] ジャーニー管理者用の設定](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | コース | [!DNL Journey Optimizer] のアーキテクチャと統合のポイントを理解します。 [!DNL Journey Optimizer] の設定方法を説明します。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] の追加リソース

[ヘルプセンター](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハ ウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

### 最新の [!DNL Journey Orchestration] 製品リリース

最新の機能、改善点および修正点について詳しくは、[[!DNL Journey Orchestration]  リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ja)を参照してください。

#### [!DNL Journey Orchestration] の追加リソース

[ヘルプセンター](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ja-JP) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL オファー] 判定は、Adobe Experience Platformと統合されたサービスです。[!UICONTROL Offer Decisioning] を使用すると、すべてのタッチポイントにわたって適切なタイミングで最高のオファーとエクスペリエンスを顧客に提供できます。

### 最新のOffer decisioning製品リリース

最新の機能、改善点、および修正点について詳しくは、[Offer decisioningリリースノート ](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) を参照してください。

#### [!UICONTROL Offer Decisioning] のその他のリソース

[ヘルプセンター](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

[Adobe Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することをお勧めします。

### コミュニティ

* [Adobe開発者向けライブ](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021 年 10 月 4～5 日、7:00 PDT

   Adobe開発者ライブは、多様な背景と特異な目的を持つAdobe開発者とエクスペリエンスビルダーを統合し、素晴らしいエンドツーエンドのエクスペリエンスを作り出します。 この 2 日間の会議では、開発者向けの重要な更新、技術セッション、コミュニティネットワークの機会を紹介します。

   Adobe Experience Cloud、Document Cloud、Creative CloudのAdobe製品チームは、設計、コンテンツ作成ワークフロー、ドキュメントサービス、および業界全体での顧客体験管理を支える、最新の技術進歩と開発者ツールを紹介します。

   Adobeでは、20 回のExperience Managerセッションが予定されています。 広げろ！

   * [セッションリストの完了](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [無料登録 — RSVP にログインします。](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe開発者ライブコミュニティ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### 新しい Adobe Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年10月 | [XML ドキュメントの概要](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | コース | Adobe Experience Manager向けの XML ドキュメントを使用して、コンテンツを作成、整理、オーサリング、および公開する方法について説明します。 |
| 2021年10月 | [とAssets Essentialsを使用したクリエイティブ [!DNL Workfront] ワークフローの管理](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | コース | Adobe[!DNL Workfront] とExperience Managerの詳細 |
| 2021年10月 | [AEM Assets Essentials 使用の手引き](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | コース | AEM Assets Essentials で組織のアセット管理を効率化する方法を説明します。 |
| 2021年10月 | [[!UICONTROL コンテンツ転送ツール]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | ビデオ | [!UICONTROL  コンテンツ転送ツール ] を使用して、AEM 6.3 以降からCloud ServiceとしてAEMにコンテンツを移行する方法を説明します。 |
| 2021年10月 | [[!UICONTROL 一括インポートサービス]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | ビデオ | AEM as a AEM [!UICONTROL  一括読み込みサービス ] を使用して、非Cloud Servicesソースからアセットを読み込む方法を説明します。 |
| 2021年10月 | [通信（Output サービス）](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | ビデオ | AEM Forms as aCloud Serviceが通信の使用例をサポートする方法を説明します。 |
| 2021年10月 | [デジタル登録](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | ビデオ | AEM Forms as aCloud Serviceがデジタル登録の使用例をサポートする方法について説明します。 |
| 2021年10月 | [Cloud Acceleration  [!UICONTROL Manager ツールの] 使用](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | ビデオ | [!UICONTROL Cloud Acceleration Manager] ツールを使用した説明 |
| 2021年10月 | [Cloud Acceleration  [!UICONTROL Manager の操作]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | ビデオ | [!UICONTROL Cloud Acceleration Manager] のナビゲーションを参照し、Cloud ServiceとしてのExperience Managerを確認します。 |
| 2021年10月 | [アセットワークフロー移行ツール](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | ビデオ | [!UICONTROL  アセットワークフローの移行 ] ツールを使用して、既存のAEM Assets Workflows をAEMにCloud Serviceとして移行する方法を説明します。 |
| 2021年10月 | [[!UICONTROL インデックスコンバーター]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | ビデオ | [!UICONTROL  インデックスコンバータ ] が既存のAEMインデックス定義を、Cloud Service互換の AEM に自動的に変換する方法を説明します。 |
| 2021年10月 | [[!UICONTROL Dispatcher コンバーター]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | ビデオ | [!UICONTROL Dispatcher コンバーター ] が既存のAEM Dispatcher 設定を自動的に更新し、AEMとの互換性をCloud Serviceに持たせる方法を説明します。 |
| 2021年10月 | [[!UICONTROL Code Repository Modernizer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | ビデオ | [!UICONTROL Core Repository Modernizer] が既存のAEM Maven プロジェクトを自動的に更新し、Cloud Serviceとの互換性をAEMに保つ方法を説明します。 |
| 2021年10月 | [[!UICONTROL コードリファクタリングツール]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | ビデオ | AEMの [!UICONTROL  コードリファクタリングツール ] が、既存のAEMプロジェクトの変換を自動化して、Cloud Serviceとの互換性をAEMにする方法を説明します。 |
| 2021年10月 | [[!UICONTROL コンテンツ転送ツール]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | ビデオ | [!UICONTROL  コンテンツ転送ツール ] を使用して、AEM 6.5 からAEMにCloud Serviceとしてコンテンツを効率的に移動する方法を説明します。 |
| 2021年10月 | [ [!UICONTROL Cloud Acceleration Manager の実装フェーズ]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | ビデオ | [!UICONTROL Cloud Acceleration Manager] を使用して、主な実装フェーズを確認し、理解するか、AEM as a Acceleration に移行します。 |
| 2021年10月 | [準備とベス [!UICONTROL トプラクティス分析]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | ビデオ | [!UICONTROL  ベストプラクティスアナライザー ] が、AEMオンプレミスまたは Adobe Managed Services からCloud ServiceとしてExperience Managerに移行する準備に役立つ方法を説明します。 |
| 2021年10月 | [Cloud Acceleration Manager の概要](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | ビデオ | [!UICONTROL Cloud Acceleration Manager] をCloud Serviceとしてすばやく簡単にExperience Managerに移行する方法を説明します。 |
| 2021年10月 | [AEM Forms as aCloud Service- AEM CS への移行](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | ビデオ | AEM Forms as aCloud Serviceでサポートされる使用例と機能について説明します。 |
| 2021年10月 | [AEM as aCloud Serviceのトラブルシューティング](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | ビデオ | AEM SDK、AEM as aCloud Service、ビルドおよびデプロイプロセスのトラブルシューティングとデバッグの方法について説明します。 |
| 2021年10月 | [AEM  [!UICONTROL Assets マイクロサービス]  - AEM as a Assets への移行](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | ビデオ | AEM Assets as a Cloud Service as a AEMのasset computeマイクロサービスを使用すると、従来のワークフローのこの役割に代わって、アセットに関するレンディションを自動的かつ効率的に生成できます。 |
| 2021年10月 | [検索とインデックス作成](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | ビデオ | Cloud Service検索インデックスとしてのAEM、Cloud ServiceとしてのAEM 6 のインデックス定義をAEMに変換する方法、およびCloud ServiceとしてのインデックスのAEMへのデプロイ方法について説明します。 |
| 2021年10月 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | ビデオ | AEM 6 の [!UICONTROL Dispatcher]、[!UICONTROL Dispatcher] 変換ツール、および Dispatcher ツール SDK の使用方法に重点を置いた、AEMのAEM [!UICONTROL Dispatcher] について説明します。 |
| 2021年10月 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | ビデオ | AEM as aCloud Service版の Cloud Manager と、Cloud Manager for AEM on Cloud Manager Services(AMS) との違いについて説明します。 |
| 2021年10月 | [AEM as a Cloud Service のオンボーディング](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | ビデオ | [!UICONTROL Cloud Manager] を使用したCloud Serviceの設定を通じて、契約段階から始まる環境としてのAEMのオンボーディングについて説明します。 |
| 2021年10月 | [リポジトリの最新化](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | ビデオ | リポジトリの最新化、可変および不変コンテンツ、パッケージ構造、およびリポジトリの最新化 CLI ツールについて説明します。 |
| 2021年10月 | [[!UICONTROL AEM Modernization Tools]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | ビデオ | AEM [!UICONTROL Modernization Tools] を使用して、既存のAEMプロジェクトとコンテンツをCloud Serviceとの互換性を持つようにアップグレードする方法を説明します。 |
| 2021年10月 | [AEM Modernization Tools](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | ビデオ | AEMを実装として異なる考え方をする方法をCloud Serviceします。 |
| 2021年10月 | [ベストプラクティスアナライザーと Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | ビデオ | ベストプラクティスアナライザー (BPA) と Cloud Acceleration Manager(CAM) が、AEMへの移行に関するカスタマイズされたガイドをCloud Serviceとして提供する方法を説明します。 |
| 2021年10月 | [バージョン履歴の管理](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | ビデオ | Adobe WorkfrontとExperience Manager[!UICONTROL Assets Essentials] を使用して、[!DNL Workfront] ドキュメントとAssets Essentialsアセットのバージョンを管理する方法を説明します。 |
| 2021年10月 | [ドキュメントの送信とアセットのリンク](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | ビデオ | WorkfrontドキュメントをAssets Essentialsに送信し、Assets EssentialsアセットをWorkfrontにリンクする方法を説明します。 |
| 2021年10月 | [統合の設定](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | ビデオ | Adobe WorkfrontとAssets Essentialsの統合を設定する方法について説明します。 |
| 2021年10月 | [電子署名とは](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | ビデオ | 世界中で最も厳格な法規制に準拠し、署名者の ID を最高レベルで保証する、証明書ベースの電子署名について説明します。 |
| 2021年10月 | [Adobe Analyticsのセグメントビルダー](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | ビデオ | Adobe Analyticsでは、セグメント化を使用して、データを多角的に分析します。 このビデオでは、[!UICONTROL  セグメントビルダー ] の概要を説明します。 |
| 2021年10月 | [メタデータのマッピング](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | ビデオ | WorkfrontフィールドとAssets Essentialsプロパティの間でメタデータマッピングを設定する方法、およびマッピングされた値を表示するようにAssets Essentialsを設定する方法について説明します。 |

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

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 最新の Campaign 製品リリース

リリースされた最新の機能、機能強化、修正について詳しくは、以下を参照してください。

* [Campaign v8 リリースノート](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=ja)
* [Campaign Classic v7 リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ja)
* [Campaign Standard リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ja)

### 新しい [!UICONTROL Campaign] コースとチュートリアル {#tutorials-campaign}

Adobe Campaignの最新のチュートリアルとコース。

| 公開日 | 名前 | アプリケーション | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021年10月 | [Adobe Campaign V8 を使用したビジネスユーザー向けの高度なキャンペーンの構築](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | Campaign V8 | Adobe Campaign V8 を使用して高度なマーケティングキャンペーンを設定および実行する方法について説明します。 前提条件、高度なキャンペーンの作成と設定、配信、購読の管理について説明します。 |

{style=&quot;table-layout:auto&quot;}

### Campaign ヘルプリソース

* Adobe Campaign v8：[ヘルプセンター](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=ja) - [実装ガイド](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ja)
* Adobe Campaign Standard：[Campaign Standard ドキュメント](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ja) - [リリース計画](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ja)
* Adobe Campaign Classic：[Campaign Classic v7 ドキュメント](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ja)
* Adobe Campaign コントロールパネル:[ドキュメント](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=ja) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ja)／[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ja) のハウツービデオ

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

リリースノート： [!DNL Adobe Advertising Cloud]

* [ [!DNL Advertising Cloud DSP] の新機能 ](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] の新機能 ](#adcloud-search)

### [!DNL Advertising Cloud DSP] の新機能  {#adcloud-dsp}

最終更新日：**2021 年 9 月 28 日**

| 機能 | 説明 |
| ------- | ----------- |
| キャンペーン管理ビュー | [!UICONTROL Campaigns]、[!UICONTROL  パッケージ ]、[!UICONTROL  配置 ]、[!UICONTROL Ads] の各ビューのカスタム列セットで、「[!UICONTROL  作成日 ]」列を使用できるようになりました。 [!UICONTROL  プレースメント ] および [!UICONTROL  広告 ] ビューを [!UICONTROL  作成日 ] でフィルタリングすることもできます。 |
| プログラムで保証された取引 | （8 9 月リリース）プログラム保証 (PG) 取引のデフォルトの配置に対して、[!UICONTROL  最大入札 ] を編集できるようになりました。 しかし、PG の取引は常に固定 CPM を持っているので、通貨交換料を考慮して [!UICONTROL  最大入札額 ] を編集する必要があるのは、海外のお客様だけです。 |
|  | （8 9 月リリース）「[!DNL FreeWheel Programmatic Guaranteed]」権限を持つユーザーは、[!UICONTROL  広告 ] ビューまたは [!UICONTROL  プレースメント ] ビューから [!DNL FreeWheel Programmatic Creative API] に広告を送信できるようになりました。 引き続き [!UICONTROL  掘り出し物 ] ビューから広告を送信できます。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] の新機能  {#adcloud-search}

最終更新日：**2021 年 9 月 28 日**

| 機能 | 説明 |
| ------- | ----------- |
| 広告インサイト | ベータモードでは、追加のインサイトを利用できます。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/magento.png) [!DNL Commerce]（Magento） {#magento}

Adobe Commerce リリースノートについては、次のリンクを参照してください。

* [Adobe Commerce と Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![アイコン](/assets/target.png) [!DNL Target] {#target}

最終更新日：**2021年8月3日**

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
| 2021年10月 | [電子署名とは](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | ビデオ | Adobe Signで世界中のデジタル ID を使用する方法を説明します。 |
| 2021年10月 | [新しい送信者向けAdobe Signの概要](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | ビデオ | Adobe Signを初めて使用する場合は、このチュートリアルを開始すると役に立ちます。 この包括的なチュートリアルでは、Adobe Signをすぐに使い始めるための、すべての基本事項に焦点を当てています。 |
| 2021年10月 | [PDF コメントのInDesignへの読み込み](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | ビデオ | この 60 秒のビデオチュートリアルでは、Acrobatでの共有レビューの後に PDF コメントをInDesignに読み込む方法を学びます。 このデジタルワークフローは、レコード時間のリビジョンを完了するのに役立ちます。 |
| 2021年10月 | [ [!DNL Intesi Group] からのデジタル ID の取得（適合）](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | ビデオ | [!DNL Intesi] グループから適格なデジタル署名証明書を取得する方法を説明します。 登録され、ID が検証されると、[!DNL Intesi] Group はAdobe Signのクラウド署名の適用に使用されるデジタル ID を発行します。 |
| 2021年10月 | [を使用した署名 [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | ビデオ | Intesi Group のデジタル ID を使用して、ID を認証し、ドキュメント上のリモートデジタル署名（クラウド署名）を認証する方法を説明します。 |
| 2021年10月 | [ [!DNL Intesi Group] からのデジタル ID の取得（詳細）](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | ビデオ | Intesi Group から高度なデジタル署名証明書を取得する方法を説明します。 登録され、ID が検証されると、Intesi Group はAdobe Signのクラウド署名の適用に使用されるデジタル ID を発行します。 |
| 2021年10月 | [を使用した署名 [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | ビデオ | [!DNL Digidentity] デジタル ID を使用して ID を認証し、ドキュメント上のリモートデジタル署名（クラウド署名）を認証する方法を説明します。 |
| 2021年10月 | [からのデジタル ID の取得 [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | ビデオ | [!DNL Digidentity] から電子署名証明書を取得する方法を説明します。 登録が完了し、ID が確認されると、[!DNL Digidentity] はAdobe Signのクラウド署名の適用に使用するデジタル ID を発行します。 |
| 2021年10月 | [2 つの PDF 間の違いの検出](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | ビデオ | 間違ったバージョンのファイルを扱う場合は、必ず間違いを犯してください。 2 つの PDF ファイル間の違いを迅速かつ正確に検出し、ドキュメントレビューワークフローを改善します。 |
| 2021年10月 | [Microsoft® Edge での参照時に PDF コンテンツを作成](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | ビデオ | Adobe Acrobat Extension for Microsoft® Edge を使用して、Web ページを PDF にその場でアーカイブする方法について説明します。 この Windows 専用ツールは、研究プロジェクトや Web ベースの情報のオフライン表示に非常に役立ちます。 |
| 2021年10月 | [Outlook での電子メールメッセージと添付ファイルの PDF への変換](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | ビデオ | Outlook で電子メールメッセージと添付ファイルをプロジェクト用に PDF にアーカイブする方法を説明します。 添付ファイルを PDF に自動的に変換して、よりプロフェッショナルで安全な方法で情報を配信する方法を説明します。 このツールは、Windows でのみ使用できます。 |

{style=&quot;table-layout:auto&quot;}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Creative Cloud エンタープライズ版 {#creative-cloud}

最新のチュートリアルについては、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ja) を参照してください。

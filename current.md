---
title: 最新のリリースノート
description: 最新のリリースノート、新機能、製品とサービスの新しいドキュメントについて説明して  [!DNL Experience Cloud]  います。 新しいヘルプとチュートリアルが見つかり  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud] ます。
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: ccdd4f3514cc11f9e0f373de29d0b21464bee923
workflow-type: tm+mt
source-wordcount: '5702'
ht-degree: 38%

---

# Adobe Experience Cloud リリースノート - 2021 年 10 月

![バナー](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] アプリケーションおよびサービスは毎月更新されます。このページには、[!DNL Experience Cloud] と [!DNL Experience Platform] の最新のリリースアップデート、ドキュメントおよびチュートリアルが集約されています。また、[!DNL Creative Cloud for enterprise] と [!DNL Document Cloud] の新しいドキュメントも参照できます。

>[!NOTE]
>
>毎月[アドビの優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)をサブスクライブして、このページの更新に関する電子メール通知を受信します。このページはひと月にわたって保持されるので、定期的にアクセスして、アドビのエンタープライズ製品と Experience League のドキュメントが更新されていないか確認してください。

最終更新日：**2021 年 10 月 13 日**

* [[!DNL Experience League] ライブイベント](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; 管理](#ecloud)
* [Adobe [!UICONTROL システムステータス]](#status)
* [[!DNL Adobe Analytics]](#analytics) および [Customer Journey Analytics](#cust-journey)**更新日2021年10月7日**
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem) (更新された **2021 10 月13日** )
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud) (更新された **2021 10 月7日** )
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。

## ![アイコン](/assets/experience-league.png) [!DNL Experience League] ライブイベント {#events}

[!DNL Experience League] ライブイベントとは、アドビの技術を学べる、Adobe の専門家や特別なゲストとのディスカッションです。以下のスケジュールを参照してライブに参加したり、過去の録画イベントを視聴したりしましょう。

| イベントの日付 | 時間 | イベント名 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021 年 10 月 4 日（PT） | 必要に応じて | [アドビ開発者向け](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | ビデオ | Adobe エクスペリエンスクラウド、ドキュメントクラウド、クリエイティブクラウドを使用したアドビ製品チームには、最新の tech 前貸しや開発者向けツール、パワーデザイン、コンテンツ作成ワークフロー、ドキュメントサービスおよびカスタマーエクスペリエンス管理があり、各産業にわたっていました。 基調講演の内容を表示します。また、アナリティクス Api、クライアントデータレイヤー、Adobe i/o オープンソースプロジェクトなどについて説明しています。 |
| 2021 年 10 月 21 日（PT） | 午後12時 (EST) | [誰がクリックしたか? Adobe Analytics を使用したリンクのクリックの高度なレポート](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) | ライブビデオイベント | ユーザーが web やモバイルプロパティを操作する際のレポートは、お客様の旅を理解するための重要な要素です。 Adobe Analytics を使用すると、アプリケーションでクリックされるたびに、ユーザー、内容、理由、および場所を理解できます。 Adobe アナリティクスのエキスパートが説明するのは、アクティビティマップ分類とカスタム属性を使用して、ユーザーの業務についてより理解を深めるためのヒントです。 |
| 2021 年 9 月 23 日（PT） | 必要に応じて | [ホリデーキャンペーンを目立たせるためのエキスパートのヒント](https://www.youtube.com/watch?v=bsU1lAv0xes) | ライブビデオイベント | 休暇に備えた買い物を始めるのに早すぎることがないのと同じように、ホリデーマーケティングキャンペーンを大成功に導くための計画に早すぎることはありません。Adobe Campaign を使用すると、組織の目標を達成するキャンペーンを設計、計画、実行できます。<br>ただし、年には! マークが付いたキャンペーンを実行するためのヒントについて説明しています。 これについては、Sandra を使用して、豊富な専門知識を持つ Adobe エキスパートが参加した3つのライブ討論に参加してください。 |
| 2021年8月26日（PT） | 必要に応じて | [次のオーディエンスセグメントを従来よりもスマートに](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=ja) | イベントの録画 | すべての優れたマーケティングキャンペーンを成功させるには、オーディエンスのターゲティングを正確におこなう必要があります。新しい Adobe Experience Platform [!UICONTROL セグメントビルダー] を使用すると、チャネルをまたいでプロファイルデータと時間ベースのユーザー行動を使用して、次のオーディエンスセグメントを作成できます。最も必要としている人にメッセージを届けるのに、これ以上の方法はありません。 |
| 2021年7月29日（PT） | 必要に応じて | [Adobe Analytics の実装に関する 3 つのお気に入りのヒント](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=ja) | イベントの録画 | Summit のステージで彼をご覧になった方もいるでしょう。Adobe インサイダーツアーでは、専門家としてアドバイスを提供しました。お客様自身の Adobe Analytics 実装に、彼と一緒に取り組めるというメリットが得られるかもしれません。エリック・マティソフフは、このメンバー限定 Experience League のライブディスカッションで、Adobe Analytics の実装に関する 3 つのお気に入りのヒントを紹介します。 |

{style=&quot;table-layout:auto&quot;}

その他のビデオについては、YouTube の [Adobe Experience League チャンネル](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] と管理 {#ecloud}

| 機能 | 説明 |
| ------- | ------- |
| 統合検索 | 集中検索では、検索インデックスにオブジェクトタイプが追加され続けます。 このアップデートでは、グローバル検索により、経験内のコンテンツと次のような Flash Optimizer オブジェクトタイプが検索されます。 <ul><li>データセット</li><li>宛先</li><li>クエリ</li><li>スキーマ</li><li>セグメント</li><li>ソース</li><li>オファー</li><li>コンポーネント</li><li>メッセージ</li><li>ジャーニー</li></ul> |
| 製品の使用状況に関する同意 | 初期ログイン時には、チュートリアル、ガイド、クイックヒント、アドバイス、ラーニングビデオなどの便利な個人用コンテンツを Adobe に提供するための環境設定を、ご希望の操作性に基づいて送信します。 この依頼には、のデータを収集して使用するための環境設定のアップデートも含まれてい <https://experience.adobe.com/preferences> ます。 |
| エクスペリエンスクラウドの [!UICONTROL  開始 ] 操作 | [エクスペリエンスクラウドトリガー ](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) は、プロビジョニングされたユーザー用にヘッダー内のアプリケーション切り替えに直接移動することができます。 |
| **注意:** インターフェイスナビゲーションの更新の計画 | 11月2021に、「 _[!UICONTROL 起動/データコレクションへ移動」]_ 機能が削除され <https://experience.adobe.com/implement> ます。 |

{style = &quot;テーブル-layout: auto&quot;}

**[!DNL Experience Cloud Central UI Components]と管理に関するその他のヘルプリソース**

* [主要なインターフェイスコンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)およびユーザー管理の管理ヘルプ
* [Places - 位置情報サービス](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ja)のヘルプとリリースノート
* [ユーザー向けヘルプ-カスタマー属性および対象ユーザー向けライブラリ](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![アイコン](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] は、Adobe製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/ja) でご確認ください。

（[!DNL Adobe System Status]の最新のリリース情報は、[2020年5月21日（PT）](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ja)のリリースノートをご覧ください。）

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2021 年 10 月 7 日**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)**更新日2021年10月7日**
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [Analytics コースとチュートリアル](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=ja) - ターゲット日 |
| ----------- | ---------- | ------- |
| アナリティクスダッシュボードのビジュアル化 | アナリティクス [!UICONTROL  ダッシュボード ] には3つの新しい視覚化が導入されており、エグゼクティブや意思決定者に、データについての理解を深めることができます。 新しい [!UICONTROL  ドーナツ ] 、 [!UICONTROL  直線 ] 、 [!UICONTROL  水平 ] 棒グラフにより、細部を表示せずに、個々のディメンションアイテムのデータを表示することが容易になります。 [詳細情報](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/create-scorecard.html?lang=en#apply-visualizations) | 2021 年 10 月 7 日 |
| [!UICONTROL メディア再生滞在時間] | Adobe ストリーミングメディア [!UICONTROL  の再生時間を ] 利用すれば、閲覧者の役に立つ洞察が得られます。また、メディア組織は、1日の拡張機能を使用して、長期間に渡って、1分間でのユーザー取り組みをより詳細に行うことができます。 特定の時点でのメディアストリーミングの表示にかかった時間を確認することができます。 再生デュレーションは、新しい5分間、15分間、30分間の granularities など、様々な方法で分割することができます。 [詳細情報](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 2021 年 10 月 18 日（PT） |
| クイック [!UICONTROL  セグメントビルダー] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで基本的なセグメントをすばやく適用できます。 セグメントビルダーに移動する必要はありません  。 [詳細情報](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 2021 年 10 月 21 日（PT） |
| 分析ワークスペースの左側のレール検索機能 | 「レール検索」を使用すると、コンポーネントの内容や関連性について引き続き考慮することに加えて、一致するアイテムの上にある完全な一致を優先して実行できます。 2) 検索結果をわかりやすくするために、一致する文字をハイライト表示します。 3) 次元に関連する分類を簡単に見つけられるようになりました。 4) 最後に、 `*` 必要な特定のコンポーネントをより簡単に検索できるように、ワイルドカード () をサポートしています。 注意: ワイルドカード検索は、ディメンションアイテムレベルでは実行されません。 | 2021 年 10 月 21 日（PT） |
| 分析ワークスペースの濃色のテーマ | 濃色のテーマは、表示オプションとして使用できます。 | 2021 年 10 月 21 日（PT） |

{style = &quot;テーブル-layout: auto&quot;}

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | 説明 | [一般公開](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - ターゲット日 |
| ----------- | ---------- | ----- |
| [!UICONTROL 接続 ] データ保存用のローリングウィンドウ | **注意: この設定を実装するには、カスタマーケアまたはお使いのアカウントマネージャーにお問い合わせください。 CJA UI ではまだ使用できません。**<p>CJA のデータ保持設定を、  データセットレベルではなく、接続レベルで月 (3 か月、6か月) として定義でき  ます。 データ保存は、イベントデータセットのタイムスタンプに基づいており、イベントデータセットにのみ適用されます。 適切なタイムスタンプが設定されていないため、profile または lookup データセットのデータ保存設定は存在しません。 主な利点は、適切かつ有用なデータについてのみ保存またはレポートを作成し、不要になった古いデータを削除できることです。 これにより、契約上の制限を超え、過剰なコストのリスクを軽減することができます。 | 2021 年 10 月 7 日 |
| レポートビルダーのサポート | レポートビルダーは、 [!DNL Excel] カスタマーの旅の解析データを使用して独自のレポートを容易に作成、編集、更新できる Microsoft®アドインです。 レポートビルダーと Excel を使用すると、単純なドラッグ &amp; ドロップ UI を使用して、複雑なデータ要求を簡単に作成できます。 お客様の旅の分析については、以下のレポートビルダーを使用できます。<ul><li>既存のワークシートのセルを参照して、完全な行の順序、日付の範囲、またはフィルターを取得します。</li><li>カレンダー、セル参照、日付計算を使用したカスタム日付の作成</li><li>慣れ親しんだ Excel フォーマットツールを使用したテーブルとビジュアル化のデザイン</li><li>MacOS の Excel で利用可能です。 Microsoft 365 web 用、Microsoft Windows</li></ul>[詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-reportbuilder/report-buider-overview.html#) | 2021 年 10 月 7 日 |
| アナリティクスダッシュボードのビジュアル化 | アナリティクス [!UICONTROL  ダッシュボード ] には3つの新しい視覚化が導入されており、エグゼクティブや意思決定者に、データについての理解を深められるようにしています。 新しいドーナツ、直線、水平棒グラフにより、細部を表示せずに、個々のディメンションアイテムのデータを表示することが容易になります。 [詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html?lang=en#apply-visualizations) | 2021 年 10 月 7 日 |
| お客様の旅分析監査ログ API | [監査ログ ](https://adobe.io/cja-apis/docs/endpoints/auditlogs/) API エンドポイントを使用すると、Adobe から監査ログデータを要求できます。これは、セキュリティのコンプライアンスにおいて重要であり、データやユーザーアクションの監査にも重要です。 | 2021 年 10 月 7 日 |
| クイック [!UICONTROL  フィルタービルダー] | ビジネスユーザーは、シンプルなインラインプロジェクトワークフローで基本的なセグメントをすばやく適用できます。 フィルタービルダーに移動する必要はありません  。 [詳細情報](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 2021 年 10 月 21 日（PT） |
| 分析ワークスペースの左側のレール検索機能 | 「レール検索」を使用すると、コンポーネントの内容や関連性について引き続き考慮することに加えて、一致するアイテムの上にある完全な一致を優先して実行できます。 2) 検索結果をわかりやすくするために、一致する文字をハイライト表示します。 3) 次元に関連する分類を簡単に見つけられるようになりました。 4) 最後に、 `*` 必要な特定のコンポーネントをより簡単に検索できるように、ワイルドカード () をサポートしています。 注意: ワイルドカード検索は、ディメンションアイテムレベルでは実行されません。 | 2021 年 10 月 21 日（PT） |
| 分析ワークスペースの濃色のテーマ | 濃色のテーマは、表示オプションとして使用できます。 | 2021 年 10 月 21 日（PT） |

{style = &quot;テーブル-layout: auto&quot;}

### Adobe Analytics の修正点と CJA の修正点 {#aa-fixes}

* お客様の旅解析で、報告された定期レポートのエラーを修正しました。 （AN-271721）
* [!UICONTROL ワークスペース内の検索コンポーネントで問題が解決 ]  されていても、完全に一致する結果にはなりません。（AN-253937、AN-271707）

#### Adobe Analytics におけるその他の修正点

A-256136;A-265420;A-268455;A-269768;A-270276;A-270287;A-271601;A-271969;A-272056;A-272111;A-272457

### [!DNL Analytics] 管理者向けの重要な注意事項  {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| 3 つの Analytics API サービスの提供終了 | 2021年9月16日（PT） | **2021 年10月20日の間に、** 次の ANALYTICS 従来 API サービスは、生涯終了日に到達してシャットダウンされます。これらのサービスを使用して現在構築されている統合は、その日以降使用できなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>アドビでは、お客様のご質問に対する回答や進め方に関するガイダンスを提供するために、[従来の API の EOL（サポート終了）に関する FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe I/O](https://developer.adobe.com/console) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API のどちらにアクセスする場合にも使用できます。 |

{style = &quot;テーブル-layout: auto&quot;}

### AppMeasurement {#appm}

AppMeasurement リリース（バージョン 2.22.2）の最新の更新については、[JavaScript リリースノートの AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja) を参照してください。

### Analytics コースとチュートリアル {#tutorials-analytics}

では、最新のコース、チュートリアルおよび記事 [!DNL Analytics] および、 [!UICONTROL  お客様向けの旅の分析が ] できます。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [ビジュアル化を使用したデータストーリーの通知](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | コース | データを取得するためだけにテーブルの後にテーブルを scour する場合は、 あなたじゃないです！ このコースでは、ビジュアル化の基礎 (プロジェクトに追加する方法、データを取得する方法など) について学習します。 必要な正確なデータを取得するための設定を行う方法について説明します。 また、通常の解析において視覚化を行うためのヒントと使用例を示しています。 |

{style = &quot;テーブル-layout: auto&quot;}

### Analytics ヘルプリソース

* [Adobe Analytics 製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の新機能 - 更新日 **2021年9月14日（PT）**:

| 機能 | 説明 |
| ------- | ------- |
| モバイル ID データ収集の同意 | モバイル ID データ収集の同意のサポートが追加されました。このアップデートのメリットを享受するには、[AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) 以降にアップグレードする必要があります。 |

## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

リリースアップデート情報、およびエクスペリエンスプラットフォームとモバイル SDK の新しいドキュメントが記載されてい  ます。

**2021 年 9 月 29 日**

| 機能 | 説明 |
| ------- | ------- |
| [[!UICONTROL データランディングゾーン]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL データランディングゾーン ] は、 [!DNL Platform]  1 つのセキュリティで保護された、サンドボックスあたりの一時記憶領域としてファイルをエクスペリエンスプラットフォームに取り込むことができる、プロビジョニング済みの Azure ブロブストアです。 |
| データ準備のストリーミングソースのサポート [](https://www.adobe.com/go/monitor-streaming-dataflows-en) | ストリーミングソースはデータの準備を現在サポートしているので、JSON ソーススキーマを使用して、XDM に対応していないソースデータをターゲットの XDM スキーマにマップすることができます。 |
| [無期限の資格情報](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | このようなクエリサービスユーザーについては、  24 時間ごとに更新するのではなく、外部クライアントに恒久的な接続を行うことができます。 |
| [[!UICONTROL ターゲット SDK]](https://www.adobe.com/go/destination-sdk-overview-en) | 統合先の SDK を使用して、 [!UICONTROL  成長率の最も ] [!DNL Platform] 高まる宛先カタログに統合します。 この機能にアクセスするには、プラットフォームのライセンス認証を行うユーザーのみが利用できます。 |

詳しくは、 [Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja) を参照してください。

### Experience Platform チュートリアルおよびコース {#tutorials-platform}

経験のあるプラットフォームおよびサービスについて、最新のビデオ、チュートリアル、またはコースが公開されています。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [[!DNL Platform] 管理](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | コース | 権限管理およびサンドボックス管理を含む、経験のあるプラットフォーム用の管理アクティビティについて説明しています。 |

{style = &quot;テーブル-layout: auto&quot;}

### Adobe Mobile SDK

Adobe Experience Platform Mobile SDK の [リリースノートと変更ログ](https://aep-sdks.gitbook.io/docs/release-notes) を参照してください。

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

最新の機能、改善点および修正点について詳しくは、[Journey Orchestration リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ja)を参照してください。

### 旅オプティマイザーのチュートリアルとコース {#tutorials-ajo}

最新の旅オプティマイザーのチュートリアル:

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [データエンジニア向けのデータの設定と管理  [!DNL Journey Optimizer] ](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | コース | このような場合は、旅のオプティマイザーでの旅の管理に必要なデータを設定して管理する方法を説明します。 |
| 2021 年 10 月 | [まず  [!DNL Journey Optimizer]  、旅の管理者およびマネージャーについて学習します。](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | コース | 最初の道を作成するために必要な情報をすべてご確認ください。 |
| 2021 年 10 月 | [ [!DNL Journey Optimizer] 旅の管理者向けの設定](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | コース | [!DNL Journey Optimizer]統合のアーキテクチャとポイントについて理解します。の設定方法について説明 [!DNL Journey Optimizer] します。 |

{style = &quot;テーブル-layout: auto&quot;}

### のその他のリソース [!DNL Journey Optimizer]

[ヘルプセンター](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハ ウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

### 最新の [!DNL Journey Orchestration] 製品リリース

最新の機能、改善点および修正点について詳しくは、[[!DNL Journey Orchestration]  リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ja)を参照してください。

#### のその他のリソース [!DNL Journey Orchestration]

[ヘルプセンター](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ja-JP) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL オファー Decisioning ] は、Adobe エクスペリエンスプラットフォームと統合されたサービスです。 [!UICONTROL Offer Decisioning] を使用すると、すべてのタッチポイントにわたって適切なタイミングで最高のオファーとエクスペリエンスを顧客に提供できます。

### 最新のキャンペーン Decisioning 製品リリース

Decisioning リリースノートの最新機能、機能強化、修正について詳しくは、こちらを参照して [ ](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) ください。

#### [!UICONTROL Offer Decisioning] のその他のリソース

[ヘルプセンター](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

[Adobe Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することをお勧めします。

**アップデート 10/13/2021:** [ ](https://video.tv.adobe.com/v/337381) 新機能の概要については、「2021 9 月のリリース概要」ビデオをご確認ください。

### コミュニティ

* [Adobe デベロッパーライブ ](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 4-5 2021 年10月、7:00 PDT

   アドビ開発者がアドビデベロッパーを利用して、多種多様な背景と単数目的でビルダーを使用することで、優れたエンドツーエンドエクスペリエンスを作成することができます。 この2日に開催される会議には、重要な開発者向けアップデート、テクニカルセッション、およびコミュニティのネットワーク機能があります。

   Adobe エクスペリエンスクラウド、ドキュメントクラウド、クリエイティブクラウドを使用したアドビ製品チームは、最新の技術進歩と開発ツールを使用して、パワーデザイン、コンテンツ作成ワークフロー、ドキュメントサービス、および各産業上でカスタマーエクスペリエンス管理を行うことができます。

   Adobe では、20個の経験管理セッションが予定されています。 「!

   * [セッションの終了リスト](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [無料登録– RSVP にログインします。](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [アドビデベロッパーライブコミュニティ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### 新しい Adobe Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [XML ドキュメントを使用した作業の開始](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | コース | Adobe Experience Manager 用の XML ドキュメントを使用して、コンテンツを作成、整理、オーサリング、パブリッシュする方法について説明します。 |
| 2021 年 10 月 | [「およびアセットを使用したクリエイティブワークフローの管理」  [!DNL Workfront]  エッセンシャル](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | コース | アドビ [!DNL Workfront] および Experience Manager の操作方法について説明します。 |
| 2021 年 10 月 | [基本的な EM アセットの基礎](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | コース | 「EM アセットの基礎」により組織の資産管理が能率化できることを説明します。 |
| 2021 年 10 月 | [[!UICONTROL コンテンツ転送ツール]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | ビデオ | [!UICONTROL コンテンツ転送ツールを ] 使用して、em 6.3 以降のクラウドサービスとしてコンテンツを移行する方法を説明しています。 |
| 2021 年 10 月 | [[!UICONTROL バルクインポートサービス]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | ビデオ | クラウドサービスのバルクインポートサービスとして EM を使用して、  aem 以外のソースからアセットを読み込む方法について説明します。 |
| 2021 年 10 月 | [通信 (出力サービス)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | ビデオ | クラウドサービスとしての EM フォームが通信ユースケースをサポートする方法について説明します。 |
| 2021 年 10 月 | [電子登録](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | ビデオ | クラウドサービスとして EM フォームを使用する方法について詳しくは、デジタル登録ユースケースのサポートを参照してください。 |
| 2021 年 10 月 | [[!UICONTROL クラウドアクセラレーションマネージャーツールの使用 ]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | ビデオ | Narrated について学習し  ます。 |
| 2021 年 10 月 | [[!UICONTROL クラウドアクセラレーションマネージャーの移動]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | ビデオ | クラウド  サービスとしての操作性を実現するために、クラウドアクセラレーションマネージャーの操作を体験してください。 |
| 2021 年 10 月 | [アセットワークフロー移行ツール](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | ビデオ | [!UICONTROL アセットワークフロー移行 ] ツールを使用して、既存の Aem アセットワークフローをクラウドサービスとして移行する方法について説明しています。 |
| 2021 年 10 月 | [[!UICONTROL インデックスコンバーター]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | ビデオ | [!UICONTROL インデックスコンバーターが、 ] 既存の aem インデックス定義を自動的にクラウドサービスとして使用するように変換する方法について説明します。 |
| 2021 年 10 月 | [[!UICONTROL Dispatcher コンバーター]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | ビデオ | ここ [!UICONTROL  では、Dispatcher コンバーターが ] 既存の aem ディスパッチャー設定を自動的に更新し、クラウドサービスと互換性のある形式にする方法について説明します。 |
| 2021 年 10 月 | [[!UICONTROL コードリポジトリ Modernizer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | ビデオ | [!UICONTROL Modernizer では、コアリポジトリを使用して、既存の ] Aem Maven プロジェクトを自動的に更新し、クラウドサービスとしてサポートされるようにする方法について説明します。 |
| 2021 年 10 月 | [[!UICONTROL コードリファクタリングツール]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | ビデオ | このガイドでは、AEM [!UICONTROL  コードリファクタリングツールを使用し ] て、既存の aem プロジェクトを自動的にクラウドサービスと互換性のある形式に変換する方法について説明します。 |
| 2021 年 10 月 | [[!UICONTROL コンテンツ転送ツール]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | ビデオ | [!UICONTROL コンテンツ転送ツールを使用し ] て、a em 6.5 からクラウドサービスとしてコンテンツを効率的に移動する方法について説明しています。 |
| 2021 年 10 月 | [[!UICONTROL クラウドアクセラレーションマネージャーの実装段階]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | ビデオ | 実装の主な段階を確認して理解しておくか、またはクラウド促進マネージャーを使用してクラウドサービスとして EM に移行して  ください。 |
| 2021 年 10 月 | [準備と [!UICONTROL  ベストプラクティスアナライザー]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | ビデオ | [!UICONTROL ベストプラクティスアナライザーにより、 ] オンプレミスまたは Adobe 管理サービスからクラウドサービスとして提供されるエクスペリエンスを提供するための準備について説明しています。 |
| 2021 年 10 月 | [クラウドアクセラレーションマネージャについて](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | ビデオ | [!UICONTROL クラウド ] サービスとして、効率的にエクスペリエンスマネージャーに移動するために、Cloud 加速化 manager を使用する方法を説明しています。 |
| 2021 年 10 月 | [クラウドサービスとしてのフル EM フォーム-EM の移動](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | ビデオ | クラウドサービスとしての EM フォームによってサポートされるユースケースと機能について説明します。 |
| 2021 年 10 月 | [クラウドサービスとしての EM のトラブルシューティング](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | ビデオ | ここでは、AEM SDK、クラウドサービスとしての AEM、構築とデプロイのプロセスについて説明しています。 |
| 2021 年 10 月 | [AEM [!UICONTROL  資源マイクロサービス ] -クラウドサービスとしての「em」に移行](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | ビデオ | クラウドサービスの資産計算に EM アセットを作成する方法について説明しています。これにより、アセットのレンディションを自動的かつ効率的に生成することができます。 |
| 2021 年 10 月 | [検索とインデックス作成](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | ビデオ | クラウドサービスの検索インデックスとしての em EM について、その定義をクラウドサービスと互換性のある形式に変換する方法と、インデックスをクラウドサービスとして EM にデプロイする方法について説明します。 |
| 2021 年 10 月 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | ビデオ |  クラウドサービスとしての em のディスパッチャーについて説明し、dispatcher の変更については、  [!UICONTROL  Dispatcher ] 変換ツールと dispatcher Tools SDK の使用方法を中心に説明します。 |
| 2021 年 10 月 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | ビデオ | クラウドサービスとしてのクラウドマネージャーについて、および Adobe 管理サービス (AMS) でのクラウドマネージャーとの違いについて説明します。 |
| 2021 年 10 月 | [AEM as a Cloud Service のオンボーディング](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | ビデオ | クラウドサービスとしてのクラウドサービスとして EM のオンボードについて詳しくは、cloud Manager を使用して環境を設定することが  あります。 |
| 2021 年 10 月 | [リポジトリ近代化](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | ビデオ | リポジトリ近代化、mutable および不変コンテンツ、パッケージ構造、リポジトリ modernizer CLI ツールについて説明します。 |
| 2021 年 10 月 | [[!UICONTROL AEM Modernization Tools]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | ビデオ | この [!UICONTROL  ツール ] を使用して、既存の aem プロジェクトとコンテンツをクラウドサービスに適合するようにアップグレードする方法を説明しています。 |
| 2021 年 10 月 | [AEM Modernization Tools](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | ビデオ | クラウドサービス実装のように EM について異なる考え方について説明します。 |
| 2021 年 10 月 | [ベストプラクティスアナライザーと Cloud 加速化 Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | ビデオ | クラウドサービスとして移行するために、ベストプラクティスアナライザー (BPA) および Cloud 加速化 Manager (CAM) を利用して、カスタマイズされたガイドを提供する方法を学習します。 |
| 2021 年 10 月 | [改版履歴の管理](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | ビデオ | Adobe の操作方法について詳しく [!UICONTROL  は、 ] [!DNL Workfront] ドキュメントおよびアセット essentials アセットのバージョンの管理を参照してください。 |
| 2021 年 10 月 | [ドキュメントの送信とアセットのリンク](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | ビデオ | アセットの要点に対して、Front ドキュメントを送信する方法について説明します。また、アセットのエッセンシャルアセットを最初に活用する方法を説明します。 |
| 2021 年 10 月 | [統合の設定](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | ビデオ | Adobe の製品の基礎とアセットの統合を設定する方法について説明します。 |
| 2021 年 10 月 | [デジタル署名について](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | ビデオ | 世界中の最も厳格な法律規制に準拠する証明書ベースのデジタル署名について説明します。また、署名者の id を最高レベルの保証にすることができます。 |
| 2021 年 10 月 | [Adobe Analytics のセグメントビルダー](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | ビデオ | Adobe Analytics のセグメント化を使用して、データをスライスし、多角的に分析します。このビデオでは、セグメントビルダーを使用して、  基本的な概要について説明します。 |
| 2021 年 10 月 | [メタデータのマッピング](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | ビデオ | ワークセンターフィールドおよびアセット Essentials プロパティ間のメタデータマッピングを設定する方法と、割り当てられた値を表示するための「アセットの基礎」設定を行う方法について説明します。 |

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

Adobe キャンペーンの最新のチュートリアルとコース

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [ビジネスユーザー向けの Adobe キャンペーン V8 を使用した高度なキャンペーンの構築](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | コース | Adobe キャンペーン V8 を使用して、高度なマーケティングキャンペーンを設定して実行する方法について説明します。 前提条件について説明し、詳細なキャンペーンの作成と設定、配信、およびサブスクリプションを管理します。 |
| 2021 年 10 月 | [ワークフローでの SOAP API の使用 - はじめに](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=ja) | チュートリアル | Adobe キャンペーン Soap API の使用方法について説明し、API 経由で受信したデータに基づく高度な配信ワークフローを作成します。 |
| 2021 年 10 月 | [イベントの作成](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | チュートリアル | イベントを設定する方法について詳しくは、イベントのストリーミングエンドポイントとペイロードを指定します。 |
| 2021 年 10 月 | [データソースの設定](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | チュートリアル | データソースの概要と、Experience Platform と外部データソースを設定する方法について説明します。 |
| 2021 年 10 月 | [Use case-メッセージのバースト](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | チュートリアル | バーストメッセージに適用可能なユースケースを理解します。バーストメッセージのジャーニーを設定する方法と、適用するベストプラクティスを説明します。 |

{style = &quot;テーブル-layout: auto&quot;}

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

最終更新日：**2021 年 10 月 7 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| ドキュメント | のすべての [ DSP およびその他の広告クラウドドキュメント ](https://experienceleague.adobe.com/docs/advertising-cloud.html) [!DNL Experience League] は、使用可能なすべての言語に翻訳されるようになりました。 表示言語を変更するには、ページの左下にある「言語の変更」メニューを使用します。 |

{style = &quot;テーブル-layout: auto&quot;}

### [!DNL Advertising Cloud Search] の新機能  {#adcloud-search}

最終更新日：**2021 年 10 月 7 日（PT）**

| 機能 | 説明 |
| ------- | ----------- |
| [!UICONTROL レポート ] , [!UICONTROL  通知センター] | (リリース9年10月)レポートの電子メール通知はすべて、カスタムレポートまたはスケジュール設定されたレポートが完了または失敗したときに送信され、通知センターによって処理されるようになりました  。 レポートについては、電子メール通知と web 通知がデフォルトで有効になっていますが、通知設定を変更することもできます。 この変更により、次の操作を行います。<ul><li>電子メールの受信者は、登録クラウド検索に登録されている認証されたユーザーに制限されているので、広告主のアカウントを accessto にすることができます。 これにより、不正なユーザーに機密データが送信されるのを防ぐことができます。</li><li>電子メールの形式と内容には、  レポートの詳細情報や、すべてのレポート形式への直接ダウンロードリンクが含まれている、通知センターテンプレートが使用されます。</li><li>レポート通知は、独自の通知設定を備えた新しい通知タイプで、通知センターに表示され  ます。</li></ul>何らかの方法で電子メール通知からレポートをプルする場合は、フィルタリングロジックを更新すると、プロセスの連続性が保証されます。 |
| 広告インサイト | その他の詳細については、ベータモードを参照してください。 |

{style = &quot;テーブル-layout: auto&quot;}

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
| 2021 年 10 月 | [デジタル署名について](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | ビデオ | Adobe 記号を使用して、世界中のデジタル Id を使用する方法について説明します。 |
| 2021 年 10 月 | [新規センダー用の Adobe Sign 入門](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | ビデオ | Adobe 署名を初めて使用する場合は、このチュートリアルを開始することをお勧めします。 この包括的なチュートリアルでは、Adobe Sign を使用してすばやく作業を開始するためのすべての基礎について重点的に説明します。 |
| 2021 年 10 月 | [InDesign への PDF コメントの読み込み](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | ビデオ | この 60-2 のビデオチュートリアルでは、Acrobat の共有レビューの後に PDF コメントを InDesign に読み込む方法について説明します。 このデジタルワークフローは、記録時間内に変更履歴を記録するのに役立ちます。 |
| 2021 年 10 月 | [電子 ID を (認定される) から取得します  [!DNL Intesi Group]  。](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | ビデオ | グループから認証されたデジタル署名証明書を取得する方法について説明 [!DNL Intesi] します。 登録が完了すると、その id を使用して、 [!DNL Intesi] Adobe Sign cloud 署名を適用するために使用されているデジタル ID がグループによって報告されます。 |
| 2021 年 10 月 | [署名を使用して [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | ビデオ | Intesi Group デジタル ID を使用して id を認証し、リモート電子署名 (クラウドシグネチャ) をドキュメントに認証する方法について説明します。 |
| 2021 年 10 月 | [電子 ID を取得する  [!DNL Intesi Group]  (詳細)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | ビデオ | Intesi グループからアドバンスドデジタル署名証明書を取得する方法について説明します。 登録が完了して id が検証されると、Intesi グループでは、Adobe Sign cloud 署名を適用するために使用されたデジタル ID を使用できます。 |
| 2021 年 10 月 | [署名を使用して [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | ビデオ | 電子 ID を使用し [!DNL Digidentity] て id を認証し、リモート電子署名 (クラウドシグネチャ) をドキュメントに認証する方法について説明します。 |
| 2021 年 10 月 | [からデジタル ID を取得します。 [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | ビデオ | からデジタル署名証明書を取得する方法について説明 [!DNL Digidentity] します。 登録が完了して id が検証されると、 [!DNL Digidentity] Adobe Sign cloud 署名を適用するために使用されているデジタル ID を使用して、そのことを確認します。 |
| 2021 年 10 月 | [2つの Pdf の違いを検出](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | ビデオ | 間違ったバージョンのファイルを操作しても間違いにはなりません。 ドキュメントのレビューワークフローが改善されるように、2つの PDF ファイルの違いがすばやく正確に検出されます。 |
| 2021 年 10 月 | [Microsoft® Edge での閲覧中に PDF コンテンツを作成](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | ビデオ | Adobe Acrobat 用拡張機能を使用して、web ページを PDF に保存する方法については、®を参照してください。 この Windows のみのツールは、リサーチプロジェクトおよび web ベースの情報をオフラインで表示する場合に非常に便利です。 |
| 2021 年 10 月 | [Outlook の電子メールメッセージと添付ファイルの PDF への変換](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | ビデオ | では、電子メールメッセージと添付ファイルを、プロジェクトの Outlook で PDF にアーカイブする方法を説明しています。 添付ファイルを自動的に PDF に変換することによって、より効率的で安全な方法で情報を提供する方法について説明します。 このツールは Windows でのみ使用できます。 |

{style = &quot;テーブル-layout: auto&quot;}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Creative Cloud エンタープライズ版 {#creative-cloud}

最新のチュートリアルについては [ 、Creative Cloud for enterprise チュートリアルを参照してください ](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ja) 。

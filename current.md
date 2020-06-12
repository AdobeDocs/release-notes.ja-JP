---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 1afcf2185512cf05aa2fd7444c5835186681432e
workflow-type: tm+mt
source-wordcount: '5640'
ht-degree: 97%

---


# Adobe Experience Cloud リリースノート - 2020 年 5 月

![バナー](/assets/experience-cloud-banner-3.png)

このページには、[!DNL Adobe Experience Cloud] の新機能、修正点および重要な注意事項が記載されています。ソリューションのリリース日は変更される場合があります。最新の更新を頻繁に確認してください。

>[!NOTE]
>
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。

**リリース日：2020 年 5 月**

Latest update: **June 4, 2020**

* [Adobe システムステータス](#status)
* [Experience Cloud インターフェイス](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**更新日2020年6月4日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/ja-JP/target/using/release-notes/target-release-notes.html)（Target のヘルプページへのリンク）
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/jp/primetime/user-guide.html)（Primetime のヘルプページへのリンク）

サポートが必要な場合は、[[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) にアクセスして、アドビがキュレーションしたコース、技術ドキュメント、クイックアンサー、コミュニティインサイトおよびインストラクターによるトレーニングなどを見つけてください。

## ![アイコン](/assets/adobe.png) Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

リリース日：**2020 年 5 月 21 日**

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
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign コントロールパネル | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places サービス | `experience.adobe.com/places` |
| ソフトウェア配布 | `experience.adobe.com/downloads` |
| 管理ツール（ベータ版） | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL ボードとコレクション]**（[!UICONTROL Experience Cloud Assets] セレクターのレガシーフィルター）は廃止されます。

## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!DNL Experience Platform,] のリリースノート（[!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration]、[!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services]、およびセキュリティ速報を含む）。

### インターフェイスの強化

更新日：**2020 年 5 月 16 日**

[!DNL Adobe Experience Platform] では、エクスペリエンスを向上し、他の Experience Cloud アプリケーションと統合するために、ドメインおよびヘッダーバーが更新されます。更新内容は次のとおりです。

* 組織間または別のアプリケーション間の切り替えが容易になりました。
* ヘルプメニューの特集記事やコンテキストの関連するドキュメントなど、ユーザーヘルプが強化されました。
* Experience Platform およびファイルサポートチケットに関するフィードバックを提供する機能が追加されました。

詳しくは、[Experience Platform リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)を参照してください。

### 顧客属性 - 新規ドキュメント

更新日：**2020 年 5 月 16 日**

* [CCPA（カリフォルニア州消費者プライバシー法）向けの顧客属性のサポート](https://docs.adobe.com/content/help/ja-JP/core-services/interface/customer-attributes/ccpa.html)
* [GDPR（一般データ保護規則）向けの顧客属性のサポート](https://docs.adobe.com/content/help/ja-JP/core-services/interface/customer-attributes/gdpr.html)

### ジャーニーオーケストレーション {#journey}

Adobe Experience Platform を使用すると、それぞれの顧客のニーズをリアルタイムでインテリジェントに予測し、どのようなジャーニーをたどっていても、個別カスタマージャーニーをエクスペリエンスチャネル全体で大規模に編成することができます。

* [ドキュメント](https://docs.adobe.com/content/help/ja-JP/journeys/using/journey-orchestration-home.html)
* [リリースノート](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html)
* [ハウツービデオ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### その他の Experience Platform のリリース情報

* [Experience Platform Launch リリースノート](https://docs.adobe.com/content/help/ja-JP/launch/using/intro/release-notes/current.html)
* [Experience Platform リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)
* [セキュリティ速報および情報](https://helpx.adobe.com/jp/security.html)（すべてのアドビ製品）

## ![アイコン](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Adobe Analytics](#aa-features) (**更新日2020年6月4日**)の新機能
* [Customer Jeurney Analytics](#cust-journey) (**更新日2020年6月4日**)の新機能
* [Media Analytics の新機能](#media-aa)（**更新日：2020 年 5 月 30 日**）
* [Analytics 管理者向けの重要な注意事項](#aa-notices)（**更新日：2020 年 6 月 2 日**）
* [Adobe Analytics の修正](#aa-fixes)（**更新日：2020 年 5 月 22 日**）
* [AppMeasurement](#appm)
* [新しい Analytics チュートリアル](#tutorials-analytics)

### Adobe Analytics の新機能 {#aa-features}

<!--First-Party Domains Available in China RDC: June 18 - Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... 
Anomaly det. support in CJA - June 18; Project Sharing Roles - June 18; Blank panel in WS now includes panels and vizs - June 18; -->

| 機能 | [一般公開日](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) -ターゲット日 | 説明 |
| -----------| ------------ | ---------- |
| [!UICONTROL Workspaceのターゲット用Analytics][!UICONTROL パネル] | 2020年6月25日 | [!UICONTROL Analytics forターゲット] (A4T)パネルを使用すると、 [!UICONTROL Analysis WorkspaceでAdobe Targetのアクティビティとエクスペリエンスを分析できます。] [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL ワークス][!UICONTROL ペースのクイックインサイトパネル] | 2020年6月25日 | [!UICONTROL クイックインサイト] (Quick Insights [!UICONTROL )では、] Analysis Workspaceのアナリストでないユーザーおよび新しいユーザー向けのガイダンスを提供し、ビジネスの質問にすばやく簡単に答える方法を学習します。 [詳細情報](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| [!UICONTROL 一括データ挿入 API] | 2020 年 6 月 1 日 | Analytics データのバッチを容易かつ独立して取り込むことができます。サーバーサイドデータとオフラインデータに役立ちます。[詳細情報...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) |
| Adobe Analytics support for [!UICONTROL Adobe Experience Platform Edge Network] | 2020 年 6 月 1 日 | 1 つのタグを使用して、Adobe Analytics、Adobe Target、Adobe Audience Manager、Adobe Experience Platform Data Lake、統合プロファイルおよび Experience Cloud ID サービスなど、複数のアドビソリューションにデータを送信できます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/experience-platform/edge/solutions/analytics/analytics-overview.html) |
| [!UICONTROL Adobe Analytics ダッシュボード] | 2020 年 5 月 22 日 | [!UICONTROL Adobe Analytics ダッシュボード]は、ユーザーがいつでもどこからでも Adobe Analytics にアクセスしてインサイトを得ることが可能なモバイルアプリです。このアプリは、主要指標への外部からのアクセスを求めるエグゼクティブを対象にしています。キュレーションされたインタラクティブなスコアカードにアクセスでき、iOS と Android の両方のオペレーティングシステムで使用できます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/mobapp/home.html) |
| [!UICONTROL ワークスペース]：空白の状態から[!UICONTROL フリーフォームテーブル]を自動的に作成 | 2020 年 5 月 22 日 | 以前は、空のプロジェクトや空のパネルにコンポーネントを直接ドロップすることはできず、最初に[!UICONTROL フリーフォームテーブル]を追加する必要がありました。現在は、空のプロジェクトまたはパネルにコンポーネントを直接ドロップできるようになりました。[!UICONTROL フリーフォームテーブル]は推奨される形式で自動的に作成されます。また、空のフリーフォームテーブルにドロップした場合の混合コンポーネントタイプ（ディメンションや指標など）の処理方法も強化されました。 |
| [!UICONTROL Adobe Analytics パッケージ]に機能[!UICONTROL アクセスレベル]ページが追加されました。 | 2020 年 5 月 22 日 | 会社に使用権原が付与されている [!UICONTROL Adobe Analytics パッケージ]（SKU）を、**[!UICONTROL 管理者]**／**[!UICONTROL 会社設定]**／**[!UICONTROL アクセスレベル機能]**&#x200B;で表示できるようになりました。 |
| アクセシビリティの強化 | 2020 年 5 月 22 日 | Adobe Analytics チームでは、キーボードナビゲーション、カラーコントラスト、スクリーンリーダーのサポートの強化など、Analysis Workspace に関していくつかのアクセシビリティの改善をおこないました。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/workspace-faq/aw-accessibility.html) |

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | [一般公開日](https://docs.adobe.com/content/help/ja-JP/analytics/landing/an-releases.html) -ターゲット日 | 説明 |
| -----------| --------- | ---------- |
| [!UICONTROL ワークス][!UICONTROL ペースのクイックインサイトパネル] | 2020年6月25日 | [!UICONTROL クイックインサイト] (Quick Insights [!UICONTROL )では、] Analysis Workspaceのアナリストでないユーザーおよび新しいユーザー向けのガイダンスを提供し、ビジネスの質問にすばやく簡単に答える方法を学習します。 [詳細情報](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| [!UICONTROL Customer Journey Analytics]：グローバルに利用可能 | 2020 年 5 月 22 日 | EMEA および APAC のお客様は、[!UICONTROL Customer Journey Analytics] を利用できるようになります。 |
| [!UICONTROL Customer Journey Analytics]：[!UICONTROL Adobe Experience Platform サンドボックス]のサポート | 2020 年 5 月 22 日 | CJA 接続を構築するための特定の [!UICONTROL Adobe Experience Platform サンドボックス]を選択できます。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics-platform/using/cja-connections/create-connection.html) |
| [!UICONTROL ワークスペース]：空白の状態から[!UICONTROL フリーフォームテーブル]を自動的に作成 | 2020 年 5 月 22 日 | 以前は、空のプロジェクトや空のパネルにコンポーネントを直接ドロップすることはできず、最初に[!UICONTROL フリーフォームテーブル]を追加する必要がありました。現在は、空のプロジェクトまたはパネルにコンポーネントを直接ドロップできるようになりました。[!UICONTROL フリーフォームテーブル]は推奨される形式で自動的に作成されます。また、空のフリーフォームテーブルにドロップした場合の混合コンポーネントタイプ（ディメンションや指標など）の処理方法も強化されました。 |
| アクセシビリティの強化 | 2020 年 5 月 22 日 | Adobe Analytics チームでは、キーボードナビゲーション、カラーコントラスト、スクリーンリーダーのサポートの強化など、Analysis Workspace に関していくつかのアクセシビリティの改善をおこないました。[詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/analysis-workspace/workspace-faq/aw-accessibility.html) |

#### [!UICONTROL Media Analytics] の新機能です。{#media-aa}

更新日：**2020 年 5 月 30 日**

**プレイヤー状態の追跡：** [!UICONTROL Media Analytics] のお客様は、標準的なソリューション変数のセット（フルスクリーン、クローズドキャプション、ミュート、ピクチャインピクチャ、インフォーカス）を使用して、再生中の閲覧者のインタラクションをキャプチャできます。また、カスタムプレーヤー状態を柔軟に作成することもできます。[!UICONTROL Analysis Workspace] のレポートで、プレイヤー状態追跡変数を使用できるようになりました。この機能を使用するには、次のいずれかが必要です。

* Media [!DNL JavaScript] SDK 3.0 以降
* [!DNL Adobe Experience Platform]（AEP）SDK で使用する場合：
   * [!UICONTROL Media Analytics 拡張機能]（Web 用）：[!UICONTROL Adobe Media Analytics]（3.x SDK）for Audio および Adobe Media Analytics for Video v1.0 以降
   * [!UICONTROL Media Analytics Extension]（モバイル用）：[!UICONTROL Adobe Media Analytics for Audio] および Adobe Media Analytics for Video v2.0 以降
* [!UICONTROL メディアコレクション]

[プレイヤーステートトラッキングについて](https://docs.adobe.com/content/help/ja-JP/media-analytics/using/player-state-tracking/player-state-overview.html)を参照してください。

#### Adobe Analytics の修正点 {#aa-fixes}

* [!UICONTROL 滞在時間]指標が変更され、計算に「未指定」が含まれなくなりました。つまり、UI に「未指定」を含めると表示されているどうかに関係なく、[!UICONTROL 滞在時間]の計算で常に「未指定」を除外する特別な例外を設定します。したがって、[!UICONTROL 滞在時間]指標を含むレポートを「未指定」に設定した場合でも、「未指定」の行項目の滞在時間には常に「0」が返されます。これにより、Reports &amp; Analytics およびレポート API v1.4 での履歴レポートが変更される場合があります。（AN-197958）
* インスタンス／訪問／訪問者が[!UICONTROL 滞在時間]指標の分母としてカウントされない問題を修正しました。この問題は、同じ時間（秒）にディメンションの値を持たないヒット（[!UICONTROL Pagename]など）が続いた場合に発生していました。（AN-211074）
* Audience Manager で [!DNL Analytics] のセグメントデータが欠落する問題を修正しました。（AN-206221）
* [!UICONTROL データソース]の処理で日付が正しく表示されない問題を修正しました。（AN-213604）
* 分類ファイルが FTP に正しくアップロードされない問題を修正しました。（AN-214102）
* API メソッド `Segments.Get` で完全な応答が返されなかった問題を修正しました。（AN-206210）
* [!DNL Workspace] PDF をダウンロードする際、テーブルの行項目が特殊文字に変換される問題を修正しました。（AN-196153）
* Adobe Analytics API 1.4 の呼び出し `visattrcustomeridcustomerattributes` が正常に機能しない問題を修正しました。（AN-186873）
* レポートにデータが表示されるけれど、[!UICONTROL データフィード]に表示されない問題を修正しました。（AN-211923）
* [!UICONTROL 製品プロファイル]をコピーできない問題を修正しました。（AN-211113）
* Federated ID を持つユーザーが [!UICONTROL Report Builder] にログインできない問題を修正しました。（AN-207750）
* [!UICONTROL AdWords] データが [!UICONTROL Advertising Analytics] に表示されない問題を修正しました。（AN-213249）
* 分類データがトレンドビューに表示されない問題を修正しました。（AN-212761）
* [!UICONTROL セグメントマネージャー]で、パブリッシュされたセグメントの数が間違った数になる問題を修正しました。（AN-213374）
* [!UICONTROL 計算指標エディター]の「**[!UICONTROL 上昇傾向を次の形式で表示]**」オプションで、フィルターを適用すると機能しなかった問題を修正しました。（AN-214223）
* [!UICONTROL 分類]の読み込みおよび書き出しでの複数の問題を修正しました。（AN-213488、AN-215309、AN-216345、AN-215307、AN-216671）
* [!UICONTROL 分類ルールビルダー]の複数の問題を修正しました。（AN-213826、AN-213550、AN-213095）
* [!UICONTROL データソース]処理の問題を修正しました。（AN-218083、AN-213604、AN-214102、AN-215485、AN-215339、AN-212911、AN-217551、AN-217947、AN-219018、AN-214691、AN-218401）
* FTP 接続の問題を修正しました。（AN-115525）
* 複数の [!DNL Analytics] [!UICONTROL データフィード]の問題を修正しました。（AN-176769、AN-160480、AN-211923、AN-204286、AN-212977、AN-214528、AN-215080、AN-217784、AN-219093、AN-218817、AN-217798、AN-218267、AN-218382）
* [!UICONTROL Data Warehouse] リクエストの問題を修正しました。（AN-181836）
* PDF ダウンロードした [!UICONTROL Workspace] プロジェクトで、値が特殊文字に変換されていた問題を修正しました。（AN-196153）
* [!UICONTROL Admin Console] で[!UICONTROL 製品プロファイル]権限をコピーできない問題を修 正しました。（AN-211113）
* 計算指標の時刻の形式が壊れて負の値になっていた問題を修正しました。（AN-210900）
* ユーザーが静的な行指標の[!UICONTROL アトリビューションモデル]を変更できなかった問題を修正しました。（AN-207872）
* [!UICONTROL 予定レポート]ビルダーが原因で、待機中ステータスのままになっていた問題を修正しました。（AN-215317）
* [!UICONTROL ExactTarget データコネクタ]を修正しました。（AN-210794）
* [!UICONTROL Bulk Ingestion API] の遅延の問題を修正しました。（AN-210165）
* ユーザーが Federated ID を使用して [!UICONTROL Report Builder] にログインできなかった問題を修正しました。（AN-207750）
* [!UICONTROL Advertising Analytics] で [!DNL Google AdWords] データが表示されなかった問題を修正しました。（AN-213249）
* [!UICONTROL Workspace] の[!UICONTROL プロジェクトが表示されました]イベントがログに表示されなかった問題を修正しました。（AN-214134）
* [!UICONTROL Workspace] で日付範囲を変更して「**[!UICONTROL すべてのパネルに適用]**」を選択した場合に発生していた問題を修正しました。一部のパネルで日付が変更されませんでした。（AN-214944）
* アラートを作成または編集できなかった問題を修正しました。（AN-215920）
* 週の最初を月曜日から日曜日に散発的に切り替えることが原因で、[!UICONTROL Workspace] のすべての動的な日付範囲が間違った日付を表示していた問題を修正しました。（AN-218835）

#### その他の Adobe Analytics の修正点

AN-101871、AN-115525、AN-123869、AN-152580、AN-160480、AN-178128、AN-186907、AN-199299、AN-201342、AN-201397、AN-204286、AN-204518、AN-206045、AN-206948、AN-208607、AN-209486、AN-210743、AN-211550、AN-211539、AN-211826、AN-211943、AN-212130、AN-212151、AN-212653、AN-212673、AN-212709、AN-212833、AN-212961、AN-212977、AN-213095、AN-213422、AN-213450、AN-213490、AN-213752、AN-213827、AN-214094、AN-214153、AN-214214、AN-214234、AN-214253、 AN-214255、AN-214343、AN-214355、AN-214401、AN-214427、AN-214528、AN-214642、AN-214691、AN-214772、AN-214793、AN-214924、AN-215017、AN-215080、AN-215212、AN-215312、AN-215377、AN-215402、AN-215545、AN-215905、AN-215963、AN-216447、AN-216676、AN-216880、AN-216999、AN-217245、AN-218450、AN-218899、AN-219487、AN-219677

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 統合製品ドメインへの移行 | 発効日：2020 年 5 月 29 日 | Adobe Analytics の統合製品ドメインへの移行は 2020 年 1 月に開始され、2020 年 5 月 29 日に完了しました。Adobe Analytics はアーキテクチャからすべての `omniture.com` ドメイン参照を削除しますが、サードパーティ Cookie としてホワイトリスト `omniture.com` を作成することが重要です。アーキテクチャの完全な移行が（間もなく）完了したら、リリースノートからお知らせいたします。すると、このホワイトリストの手順は不要になります。ホワイトリストに登録する必要のある推奨 IP アドレスとドメインの完全なリストは、[こちら](https://helpx.adobe.com/jp/analytics/kb/adobe-ip-addresses.html)をご覧ください。<br>組織がサードパーティ Cookie をブロックしている場合は、カスタマーケアに連絡して、Adobe Analytics へのアクセスを再取得してください。 |
| 新しい Adobe Analytics のデフォルトランディングページ | 発効日：2020 年 6 月 19 日 | 2020 年 6 月 19 日に、Adobe Analytics のデフォルトのランディングページが[!UICONTROL レポート]から [!UICONTROL Workspace] に変更されます。この変更は、過去にカスタムランディングページを設定していないユーザーに対して適用されます。 |
| サードパーティのテクノロジーホワイトリスト | （発効日： 2020 年 3 月 13 日 | Adobe Analytics は、サードパーティのテクノロジーを活用して、機能のロールアウト管理と製品内サポートを開始しました。すべての機能にアクセスできるよう、必要なネットワークファイアウォールのホワイトリストに、次の URL を追加する必要があります。<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| Analysis Workspace の可用性に対する冗長性の向上 | 2020 年 5 月 22 日 | Analysis Workspace の可用性を確保するために、セカンダリ CDN（コンテンツ配信ネットワーク）を追加し、冗長性を高めます。必要なネットワークファイアウォールのホワイトリストに、次の URL を追加する必要があります。<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| [!UICONTROL Workspace] での[!UICONTROL 入口／出口]の計算方法の変更 | 2020 年 4 月 8 日 | 2020 年 3 月の時点で、[!UICONTROL Analysis Workspace] における「_なし_」の値と[!UICONTROL 入口／出口]との相互作用を変更しました。[!UICONTROL Analysis Workspace] で「_なし_」をオン／オフにできるようになったので、入口または出口の後に「_なし_」を適用します。（eVar の場合）以前は、これらの前に適用されていました。例えば、訪問の最初のヒットに eVar の値がないが、2 回目のヒットに eVar の値があるとします。[!UICONTROL Reports &amp; Analytics] では、最初のヒットがそのエントリに対して「_未指定_」と表示されますが、[!UICONTROL Analysis Workspace] では 2 回目のヒットの値が表示されます。 |
| **[!UICONTROL コンバージョンレベル]**&#x200B;設定のサポート終了 | 2020 年 3 月 4 日 | **[!UICONTROL 管理ツール]**／**[!UICONTROL レポートスイート]**／**[!UICONTROL 一般的なアカウント設定]**&#x200B;で、機能しない[コンバージョンレベル](https://docs.adobe.com/content/help/ja-JP/analytics/admin/admin-tools/general-acct-settings-admin.html)設定は、2020 年 3 月 13 日にユーザーインターフェイスから削除されます。 |
| **[!UICONTROL ダッシュボードアーカイブ]**&#x200B;のサービス終了 | 2020 年 3 月 28 日 | [!UICONTROL Reports &amp; Analytics] の「**[!UICONTROL ダッシュボードを管理]**」の「**[!UICONTROL アーカイブを表示]**」設定は、2020 年 10 月から使用できなくなります。 |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| 新しい Adobe Analytics ドメイン | 2019 年 12 月 19 日 | 2020 年 1 月 17 日に、Adobe Analytics は新しいドメインへの移行を開始しました。`https://experience.adobe.com/analytics.`<br>**メモ&#x200B;**：この変更は、Adobe ID または Enterprise ID を使用して Analytics にアクセスするすべてのユーザーに適用されます。<ul><li>ドメインの変更により、Safari で Analytics を読み込む際に cookie の問題が発生する可能性があります。[!DNL Safari] のプライバシー設定で「_サイト越えトラッキングを防ぐ_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Analytics がこの新しい Adobe Experience Cloud ドメインで機能するようになります。この問題が影響するのは [!DNL Safari] ユーザーのみなので、ユーザーは問題なく他のブラウザーを使用できます。</li><li>ドメインの変更により、[ある特定のケースにおいて](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/activity-map/activity-map.html)、一部の顧客に対して [!UICONTROL Activity Map] が機能しなくなる場合があります。</li></ul> |
| 提供終了 - Analytics レガシー API | 2020 年 1 月 10 日 | 2020 年 11 月に、以下の Analytics レガシー API サービスが提供終了となり、シャットダウンされます。これらのサービスを使用して構築された現在の統合は機能しなくなります。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問に対する回答と進め方に関するガイダンスを提供するために、[従来の API EOL の FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis のサポート終了 | 2018 年 8 月 7 日 | アドビは Ad Hoc Analysis のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。詳しくは、[Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) を参照してください。 |

### [!DNL AppMeasurement] {#appm}

「[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/appmeasurement-updates.html)」を参照してください。バージョン 2.20.0 は 2020 年 3 月 6 日にリリースされました。

### 新しい Analytics チュートリアル {#tutorials-analytics}

| コンテンツ | 説明 |
| -----------| ---------- |
| [Analysis Workspaceのトレーニングチュートリアルテンプレート](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | [!UICONTROL Analysis Workspace] トレーニングチュートリアルテンプレートでは、[!UICONTROL Workspace] で最初のプロジェクトを作成するための一般的な用語と手順を順に説明します。 |
| [トレンドへの前月比および前年比の追加](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | [!UICONTROL Analysis Workspace] の任意の指標に対して、月ごとおよび年ごとのトレンド比較を作成するためのカスタム日付範囲の適用方法を説明します。 |
| [Analysis Workspace 向けダークモード拡張機能](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Dark Reader Chrome 拡張機能を有効にして、Analysis Workspace をダークモードに切り替えます。 |
| [カスタムパレットを定義するための Color Eyedropper 拡張機能](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | [!UICONTROL Workspace] プロジェクトのカスタムカラーパレットで必要な 16 進数の値を簡単に見つけるための ColorPick EyeDropper Chrome 拡張機能の使用方法を説明します。 |

#### Analytics ヘルプリソース

* [Adobe Analytics チュートリアル](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 製品ドキュメント](https://docs.adobe.com/content/help/ja-JP/analytics/landing/home.html)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の新機能、修正点、ドキュメントおよびチュートリアルです。

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
| [一括管理ツール（BAAAM）](https://docs.adobe.com/content/help/ja-JP/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | 次の新しい一括管理ツールワークシートをアップロードしました。<br><br><ul><li>特性階層のサブフォルダーをリスト化できます（AAM-51528）</li><li>CRM ID（クロスデバイス ID）に関連付けられた特性を求められた場合に指標を取得します（AAM-52135）</li><li>韓国語文字の言語エンコードの問題を修正しました（AAM-AAM-54006）</li></ul> |

**修正点**

* 特性の数が多いフォルダーでトレンドレポートがタイムアウトしていた問題を修正しました。（AAM-54457）
* 特性の作成／編集ワークフローで、[!UICONTROL 式ビルダー]が表示されなかった問題を修正しました。（AAM-54255）
* UI のエラーメッセージが短時間しか表示されず、お客様がエラーメッセージを読む前に消えてしまっていた問題を修正しました。これは、例えば、宛先にマッピングされたセグメントを削除しようとした場合に発生していました。（AAM-54031）
* [!UICONTROL Audience Marketplace] をもう使用していないお客様が月次の請求電子メールを受け取っていた問題を修正しました。（AAM-54602）
* お客様が UI の他の場所から特定の特性をクリックすると、特性ではなく、壊れたリンクが表示されていた問題を修正しました。（AAM-54768）
* 特性式の編集モードで、Enter キーを押すとページが更新され、特性式が失われる問題を修正しました。（AAM-54210）
* インターフェイス全体で複数のアクセシビリティを改善しました。（AAM-47781、AAM-49075、AAM-49360、AAM-49361、AAM-49376、AAM-50432、AAM-52550、AAM-54660）.

### Audience Manager の新しいチュートリアル {#tutorials-aam}

| コンテンツ | 説明 |
| -----------| ---------- |  
| [Audience Manager の基本用語と概念について](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | このビデオでは、シグナル、特性、セグメントなど、Audience Manager の基本的な用語と概念の一部を説明します。 |
| [Audience Manager のデータフローについて](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | このビデオでは、アプリケーションとのデータフローについて詳しく説明します。Adobe Audience Manager の理解に役立ちます。 |
| [Audience Manager - DMP の概要](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | クロスチャネルパーソナライゼーションの主な課題と Adobe Audience Manager がカスタマージャーニーを推進する方法について説明します。また、Audience Manager でオンボーディング可能なデータタイプを説明し、Audience Manager と統合された広告テクエコシステムパートナーを特定します。 |
| [Audience Manager の使用例](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | このビデオでは、4 つの一般的な Audience Manager の使用例を特定し、関連するベストプラクティスについて説明します。 |
| [Audience Manager のデバイス間指標について](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | このビデオでは、デバイスプロファイルとデバイス間プロファイルの違いについて説明し、UI のどの数値がこれらの異なるプロファイルタイプと一致するかを示します。 |
| [Audience Manager の Predictive Audiences について](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | このビデオでは、Audience Manager の Predictive Audiences の概要とその仕組みの詳細を説明し、使用例を示します。 |
| [Audience Manager の Predictive Audiences の設定とレポート](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | このビデオでは、Audience Manager インターフェイスの Predictive Audiences 設定について説明します。また、モデルの結果を示すレポートについて確認します。 |

## ![アイコン](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品のアップデート

* **AEM as a Cloud Service**

   * アセット処理を強化および修正しました。アセットの再処理ダイアログボックスには、より多くのコントロールが表示され、特定の処理プロファイルを選択したり、事後処理ワークフローをトリガーするかどうかを選択したりできます。
   * Dynamic Media アセットの取り込みパフォーマンスが強化されました。

### セルフサービス

* **自動フォーム変換サービス - リリース AFC-2020.03.1**

   最新のコネクタをインストールすると、新しいオプションが使用できます。

   **[!UICONTROL 自動検出論理セクション]**：「[!UICONTROL 自動検出論理セクション]」オプションを使用して、ページレベルのパネル（ページ番号ベースのパネル）を破棄して、論理パネルのみを作成できます。また、先行する論理セクションを持つセクションに属さないフィールドと、隣接する 2 ページにまたがる論理セクションのフィールドを 1 つの論理セクションにまとめます。例えば、論理セクションの一部のフィールドが 1 ページ目の終わりにあり、一部が 2 ページ目の最初にある場合、そのようなフィールドはすべて 1 つの論理セクションにまとめられます。

* **Dynamic Media でサポートされていない画像形式**

   [!UICONTROL Dynamic Media] でサポートされていないラスター画像ファイル形式のサブタイプに関する情報です。

   [Dynamic Media でサポートされていないラスター画像形式](https://docs.adobe.com/content/help/ja-JP/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media)を参照してください。

* **コンテンツフラグメント**

   [AEM Assets HTTP API でサポートされるコンテンツフラグメント](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)、[コンテンツフラグメントのカスタマイズと拡張](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)および[レンダリング用コンテンツフラグメント設定コンポーネント](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html)に関する情報です。

* **AEM Experience League コミュニティ**

   [AEM Experience League コミュニティ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community)とつながりを持つ：学習仲間や AEM エキスパートに質問したり、スレッドを参照したり、ヒントや専門知識を共有したりします。

* **AEM ニュースレター**

   [!UICONTROL Experience League] による AEM ニュースレターは、AEM の概要を短期間で習得して、すぐに価値を実現できるようにすることを目的としています。次に、最新のニュースレターを示します。

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)：Experience Manager はクラウドサービスとして使用できるようになりました。
   * Experience Insider ニュースレターを[購読](https://adobeeventsonline.com/AEM/2017/NL/Optin/)してください。
   * Adobe Experience Manager 6.5 ラーニングとサポートページの [AEM リソース](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)節でニュースレターのアーカイブを表示できます。

### Experience Manager の新しいチュートリアル

| コンテンツ | 説明 |
| -----------| ---------- |  
| [ローカル AEM ランタイムの設定](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager（AEM）は、[!UICONTROL AEM as a Cloud Service] SDK の [!UICONTROL Quickstart Jar] として使用して、ローカルで実行できます。これにより、開発者は、カスタムコード、設定およびコンテンツをソース管理にコミットする前に、それらをデプロイおよびテストし、[!UICONTROL AEM as a Cloud Service] 環境にデプロイできます。 |
| [AEM Assets 使用の手引き](https://video.tv.adobe.com/v/33624?captions=jpn) | ビジネスユーザー向けに AEM Assets の概要を紹介するビデオです。 |
| [メタデータフォルダースキーマ](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | メタデータフォルダースキーマを使用すると、アセット上で直接管理するのではなく、アセットフォルダー自体に関連付けられたメタデータを管理および確認できます。 |
| [タグ付け](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | タグは、アセットのフォルダー階層全体でアセットを管理するための不可欠なツールです。タグ分類の確立は、ユーザーが AEM 内のアセットを検出して整理できるようにするうえで重要です。 |
| [メタデータプロファイル](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | メタデータプロファイルを使用すると、デフォルトのメタデータをアセットフォルダー内のアセットに自動的に適用できます。これにより、AEM ユーザーのメタデータ管理の負荷を軽減し、メタデータの一貫性を向上できます。 |
| [メタデータスキーマ](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | メタデータスキーマは、AEM でアセットメタデータを公開するインターフェイスを定義します。このビデオでは、アセットの適用に使用する方法の組み合わせについて説明します。 |

### その他のリソース

* [AEM as a Cloud Service リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM as a Cloud Service のドキュメント](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [AEM Cloud Manager リリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/jp/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/ja-JP/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://docs.adobe.com/content/help/ja-JP/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre リリースノート](https://docs.adobe.com/content/help/ja-JP/livefyre/using/release-notes/c-rn.html)

## ![アイコン](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### Campaign Standard

* [Adobe Campaign Standard 20.3 リリース](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Campaign コントロールパネル

| 機能 | 説明 |
| -----------| ---------- |  
| GPG キー管理 | Campaign から送信したデータを暗号化したり、受信データを復号化したりするために、マーケティングインスタンスに GPG キーをインストール／生成します。 |
| CNAME サブドメインの証明書管理 | コントロールパネルを使用して、CNAME メソッドでデリゲートされたサブドメインの SSL 証明書を更新できるようになりました。 |

### Campaign の新しいチュートリアル

* 新しい Campaign Standard のチュートリアル

| コンテンツ | 説明 |
| -----------| ---------- |  
| [コントロールパネル - Google TXT レコード管理](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Campaign コントロールパネルを使用して、Gmail アドレス宛ての E メール送信に使用するすべてのサブドメインに Google TXT サイト検証レコードを追加する方法を説明します。 |
| [外部 API アクティビティを含むワークフローの設定と実行](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | 外部 API アクティビティを使用した外部 REST API エンドポイントの呼び出し方法を説明します。 |
| [Android 用プッシュ通知使用の手引き - チュートリアル](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | このチュートリアルでは、Campaign Standard および Android アプリケーションでプッシュ通知を設定するために必要な手順を説明します。 |

* Campaign Classic の新しいチュートリアル

| コンテンツ | 説明 |
| -----------| ---------- |  
| [Snowflake のビッグデータ管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Adobe Campaign Classic の Snowflake コネクタの活用方法を説明します。 |
| [コントロールパネル - Google TXT レコード管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Campaign コントロールパネルを使用して、Gmail アドレス宛ての E メール送信に使用するすべてのサブドメインに Google TXT サイト検証レコードを追加する方法を説明します。 |

### Campaign ヘルプリソース

* Adobe Campaign Standard：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/campaign-standard-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/ja-JP/campaign-standard-learn/tutorials/overview.html) - [リリース計画](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-planning.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/campaign-classic-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [最新ドキュメントの更新](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/documentation-updates.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/control-panel/using/release-notes.html)

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Advertising Cloud DSP の新機能](#adcloud-dsp)
* [Advertising Cloud Search の新機能](#adcloud-search)

### Advertising Cloud DSP の新機能 {#adcloud-dsp}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL Campaigns Classic] および [!UICONTROL Campaigns ベータ版] | 詐欺およびブランドの安全性に対する IAS の測定設定（オプションで各キャンペーンに設定可能）に、VAST および VPAID インベントリでの測定オプションが追加されました。 |
| [!UICONTROL Campaigns ベータ版] | データのビジュアライゼーションおよびページの読み込み時間が向上しました。 |
|  | すべてのページで、現在のフィルターおよび表示に基づく Excel レポートをダウンロードできるようになりました。 |
|  | （5 月 23 日リリース）新しい指標には、全時間指標、現在の間隔配信、日付特有の OTS が含まれます。 |
| [!UICONTROL ブラックリスト] | 予測システムは、広告主レベルまたはアカウントレベルのブラックリストを自動的に使用するようになりました。ユーザーは、プレースメント設定にブラックリストを貼り付ける必要はなくなりました。 |
| [!UICONTROL 在庫取引] | （非公開ベータ版）シンプル化された新しいフォームを使用すると、Deal ID Inbox ではできないサプライサイドプラットフォーム（SSP）取引をすばやく設定、編集、トラブルシューティングできます。 |
|  | Deal ID Inbox でプログラム的に保証された取引のパッケージを受け入れると、各取引 ID に対するデフォルトのプレースメントを作成する必要があるというアラートが表示されるようになりました。 |

### [!UICONTROL Advertising Cloud Search] の新機能 {#adcloud-search}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL キャンペーン] | （Google 広告アカウント、ベータ版サービス）5 月下旬より、Advertising Cloud Search では、Google Gmail ディスプレイキャンペーンおよび Google スマートショッピングキャンペーンのデータを、トラッキングおよびレポートのために Google コンバージョンと同期できるようになります。また、このサービスでは、キャンペーンおよび広告グループの表示から、既存のキャンペーンのキャンペーン設定および広告グループ設定を編集することもできます。このサービスはオプションです。サービスが一般公開されると、追加費用が適用されます。<br>ベータ版プログラムや今後の範囲など、サービスについて詳しくは、アドビのアカウントマネージャーにお問い合わせください。 |

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

Magent リリースノートについては、以下を参照してください。

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![アイコン](/assets/marketo.png) [!DNL Marketo] {#marketo}

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

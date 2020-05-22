---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 36c098558e178fdaea0bab49528e54a93980ac0b
workflow-type: tm+mt
source-wordcount: '4998'
ht-degree: 38%

---


# Adobe Experience Cloudリリースノート — 2020年5月

![バナー](/assets/experience-cloud-banner-3.png)

このページには、の新機能、修正、重要な注意事項が記載されてい [!DNL Adobe Experience Cloud]ます。 ソリューションのリリース日は異なる場合があります。 最新の更新については、頻繁に再度確認してください。

>[!NOTE]
>
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。

**リリース日：2020 年 5 月**

最新の更新： **2020年5月21日**

* [Adobe システムステータス](#status)
* [Experience Cloud インターフェイス](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**更新日2020年5月21日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/ja-JP/target/using/release-notes/target-release-notes.html)（Target のヘルプページへのリンク）
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/jp/primetime/user-guide.html)（Primetime のヘルプページへのリンク）

ヘルプが必要ですか？ アドビが担当するコース、技術ドキュメント、回答、コミュニティインサイト、講師が指導するトレーニングについては、 [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) をご覧ください。

## ![アイコン](/assets/adobe.png) Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

リリース日：**2020 年 5 月 21 日**

**最新情報**

* Adobe ID を使用して、製品オファーやアドオンレベルまで掘り下げた、より精度の高いイベント通知を登録できます。購読のセットアップを迅速に行うために、購読プロセスでは、製品の権利付与に基づく製品とサービスの選択をお勧めします。 これにより、受信する電子メールの数が減り、インボックス内でより適切な通知を配信できます。 はじめに [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit) をご覧ください。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| 購読と通知に関するユーザーエクスペリエンスを改善 | <ul><li>[!DNL Marketo Engage] 地域別の場所が、選択した商品のリストに基づいてフィルタリングされるようになりました。</li><li>[!DNL Marketo Engage] 電子メール通知は、地域、場所および環境の環境設定に関連します。</li></ul> |
| イベント購読確認 | <ul><li>進行中の単一イベントの更新を購読する際に、電子メールによる確認を受け取れるようになりました。</li></ul> |
| グローバルナビゲーションの操作性の強化 | <ul><li>トップレベルのナビゲーションメニュー `Adobe.com` でのユーザーエクスペリエンスとの一貫性。</li></ul> |

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud インターフェイス {#ecloud}

Experience Cloudインターフェイスの一般的なアップデートです。

**統合製品ドメイン**

アドビでは、ドメインとインターフェイスのヘッダーを更新して、すべてのExperience Cloudアプリケーションでエクスペリエンスを統合し、向上させています。 これらの機能強化は、小規模ではあっても、重要な方法でエクスペリエンスをシンプルにするように設計されています。これらの拡張機能によって現在のワークフローは変更されません。

更新内容は次のとおりです。

* 新しいアプリケーション URL：`experience.adobe.com/<application name>`：
   * すべての製品で、最終的にこの URL パターンが採用されます。1 ヶ月間にわたって効果的な新しい URL を探します。
   * ブラウザーのサポート：サポートされるブラウザーには、[!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari]、および [!DNL Opera]（最新バージョン）が含まれます。**メモ：** Experience Cloud インターフェイスはこれらのブラウザーをサポートしていますが、個々のアプリケーションがすべてのブラウザーに対応しているわけではありません（例えば、[Analytics](https://docs.adobe.com/content/help/ja-JP/analytics/admin/sys-reqs.html) は [!DNL Opera] をサポートしておらず、[Target](https://docs.adobe.com/help/ja-JP/target/using/implement-target/before-implement/supported-browsers.html) は [!DNL Safari] をサポートしていません）。
   * （[!DNL Safari] のみ）ドメインの変更によって、[!DNL Safari] で cookie の問題が発生する場合があります。[!DNL Safari] のプライバシー設定で「_サイト越えトラッキングを防ぐ_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Experience Cloud がこの新しいドメインで機能するようになります。
* 組織間または別のアプリケーション間の切り替えが容易になりました。
* 製品ヘルプの改善：ヘルプ検索にコミュニティフォーラムやビデオコンテンツの結果も含められるよう、[!UICONTROL Experience League] は製品に統合されています。この変更により、より多くのコンテンツへのアクセスが簡素化され、Experience Cloud を最大限に活用できるようになります。さらに、**[!UICONTROL ヘルプ]** ／ **[!UICONTROL フィードバック]**&#x200B;をクリックして問題を報告したり、アドビとアイデアを共有したりします。

次のアプリは、新しいexperience.adobe.comドメインを使用しています。

| アプリまたはサービス | ドメイン |
| -----------| ---------- |
| Experience Cloudホームページ | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| ジャーニー管理 | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign コントロールパネル | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places サービス | `experience.adobe.com/places` |
| ソフトウェア配布 | `experience.adobe.com/downloads` |
| 管理ツール（ベータ版） | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL 「ボードとコレクション]**」は、 [!UICONTROL Marketing Cloud Assets] Selectorのレガシーフィルターで、廃止されます。

## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!DNL Experience Platform,] のリリースノート（[!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration]、[!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services]、およびセキュリティ速報を含む）。

### インターフェイスの強化

Updated: **May 15, 2020**

[!DNL Adobe Experience Platform] は、エクスペリエンスを向上させ、他のExperience Cloudアプリケーションとの統合を図るために、ドメインとヘッダーバーの更新をリリースしています。 更新内容は次のとおりです。

* 組織間または別のアプリケーション間の切り替えが容易になりました。
* ヘルプメニューの特集記事やコンテキストに関するドキュメントなど、ユーザーヘルプが改善されました。
* エクスペリエンスプラットフォームとファイルサポートチケットに関するフィードバックを提供する機能。

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### 顧客属性 — 新しいドキュメント

Updated: **May 15, 2020**

* [CCPA](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)の顧客属性サポート
* [GDPR(General Data Protection Regulation)に対する顧客属性のサポート](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html)

### ジャーニーオーケストレーション {#journey}

Adobe Experience Platform を使用すると、それぞれの顧客のニーズをリアルタイムでインテリジェントに予測し、どのようなジャーニーをたどっていても、個別カスタマージャーニーをエクスペリエンスチャネル全体で大規模に編成することができます。

* [ドキュメント](https://docs.adobe.com/content/help/ja-JP/journeys/using/journey-orchestration-home.html)
* [リリースノート](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html)
* [ハウツービデオ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### その他の Experience Platform のリリース情報

* [Experience Platform Launch リリースノート](https://docs.adobe.com/content/help/ja-JP/launch/using/intro/release-notes/current.html)
* [Experience Platform リリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [セキュリティ速報および情報](https://helpx.adobe.com/jp/security.html)（すべてのアドビ製品）

## ![アイコン](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [カスタマージャーニー分析の新機能](#cust-journey)
* [Adobe Analytics の新機能](#aa-features)
* [Analytics管理者向けの重要な注意事項](#aa-notices) (**更新日2020年5月21日**)
* [Adobe Analyticsの修正](#aa-fixes) (**更新日2020年5月21日**)
* [AppMeasurement](#appm)
* [新しい Analytics チュートリアル](#tutorials-analytics)

### カスタマージャーニー分析の新機能 {#cust-journey}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL 顧客の遍歴分析]: グローバルな可用性 | Analytics [!UICONTROL のカスタマージャーニーを、EMEAおよびAPACのお客様が利用できるようにします] 。 |
| [!UICONTROL 顧客の遍歴分析]: Adobe Experience Platform Sandboxのサ [!UICONTROL ポート] | CJA接続を構築する特定の [!UICONTROL Adobe Experience Platform Sandbox] を選択できます。 [詳細情報...](https://docs.adobe.com/content/help/ja-JP/analytics-platform/using/cja-connections/create-connection.translate.html) |

### Adobe Analytics の新機能 {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| 機能 | 説明 |
| -----------| ---------- |
| Adobe Experience Platform Edge Networkの解析サポート  | 1つのタグを使用して、Adobe Analytics、Adobeターゲット、Adobeオーディエンスマネージャー、Adobe Experience Platform Data Lake、統合プロファイル、Experience Cloud IDサービスなど、複数のアドビソリューションにデータを送信できます。 [詳細情報...](https://docs.adobe.com/content/help/en/experience-platform/edge/solutions/analytics/analytics-overview.html) |
| [!UICONTROL Adobe Analyticsダッシュボード] | [!UICONTROL Adobe Analyticsダッシュボード] は、Adobe Analyticsからのインサイトに、いつでもどこでもアクセスできるモバイルアプリです。 このアプリは、主要指標に対して外出先でアクセスを求めているエグゼクティブ向けです。 キュレーションされたインタラクティブスコアカードにアクセスでき、iOSとAndroidの両方のオペレーティングシステムで使用できます。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace][!UICONTROL ：空白の状態からフリーフォームテーブルを自動的に作成する] | Previously, you could not drop components directly into a blank project or blank panel; you had to add a [!UICONTROL Freeform Table] first. You can now drop components directly into a blank project or panel, and a [!UICONTROL Freeform Table] is automatically built for you in a recommended format. また、空のフリーフォームテーブルにドロップした場合の混合コンポーネントタイプ（ディメンションや指標など）の処理方法も改善されました。 |
| [!UICONTROL 「] 機能アクセスレベル  」ページに追加されたAdobe Analyticsパッケージ | 会社にどの [!UICONTROL Adobe Analyticsパッケージ] (SKU)の権利を付与されているかを、管理者 **[!UICONTROL /]** 会社設定 **[!UICONTROL /]******&#x200B;アクセスレベル機能で表示できるようになりました。 |
| アクセシビリティの強化 | Adobe Analyticsチームでは、キーボードナビゲーション、カラーコントラスト、スクリーンリーダーのサポートの強化など、分析ワークスペースに対していくつかのアクセシビリティの改善を行っています。 |

#### Adobe Analyticsの修正(#aa-fixes)

* 滞在 [!UICONTROL 時間指標が「なし] 」を含まないように変更されました。 つまり、UIが「なし」と呼ぶかどうかに関係なく、 [!UICONTROL 滞在時間] (Time Spent)の計算に常に「なし」を除外する特別な例外を作成します。 したがって、滞在  時間指標を含むレポートを「なしを含む」に設定した場合でも、「なし」の行項目に対しては常に0滞在時間が返されます。 これにより、Reports &amp; AnalyticsおよびレポートAPI v1.4の履歴レポートが変更される可能性があります。 （AN-197958）
* インスタンス/訪問/訪問者が滞在 [!UICONTROL 時間] 指標の分母としてカウントされない問題を修正しました。  これは、ディメンションの値を持たないヒット( [!UICONTROL Pagename]など)が同じ秒間に続いた場合に発生します。 （AN-211074）
* Fixed an issue that caused missing [!DNL Analytics] segment data in Audience Manager. （AN-206221）
* [!UICONTROL データソース]の処理で日付が正しく表示されない問題を修正しました。（AN-213604）
* 分類ファイルが FTP に正しくアップロードされない問題を修正しました。（AN-214102）
* API メソッド `Segments.Get` で完全な応答が返されなかった問題を修正しました。（AN-206210）
* [!DNL Workspace] PDF をダウンロードする際、テーブルの行項目が特殊文字に変換される問題を修正しました。（AN-196153）
* Adobe Analytics API 1.4 の呼び出し `visattrcustomeridcustomerattributes` が正常に機能しない問題を修正しました。（AN-186873）
* レポートにデータが表示されるけれど、[!UICONTROL データフィード]に表示されない問題を修正しました。（AN-211923）
* [!UICONTROL 製品プロファイル]をコピーできない問題を修 正しました。（AN-211113）
* Fixed an issue where users with Federated IDs were not able to log in to [!UICONTROL Report Builder]. （AN-207750）
* [!UICONTROL AdWords] データが [!UICONTROL Advertising Analytics] に表示されない問題を修正しました。（AN-213249）
* 分類データがトレンドビューに表示されない問題を修正しました。（AN-212761）
* [!UICONTROL セグメントマネージャー]で、パブリッシュされたセグメントの数が間違った数になる問題を修正しました。（AN-213374）
* **[!UICONTROL 計算指標エディターの「上昇傾向を表示。.]** 」オプションに関する問題を修正しました。このオプションは、  フィルターを適用する際に機能しませんでした。 （AN-214223）
* 分 [!UICONTROL 類のインポート] /エクスポートに関する複数の問題を修正。 (AN-213488、AN-215309、AN-216345、AN-215307、AN-216671)
* 分 [!UICONTROL 類ルールビルダーに関する複数の問題を修正しました]。 (AN-213826、AN-213550、AN-213095)
* デー [!UICONTROL タソース] 処理の問題を修正しました。 (AN-218083、AN-213604、AN-214102、AN-215485、AN-215339、AN-212911、AN)-217551、AN-217947、AN-219018、AN-214691、AN-218401)
* FTP接続の問題を修正しました。 （AN-115525）
* 複数の [!DNL Analytics][!UICONTROL データフィードの問題を修正しました] 。 (AN-176769、AN-160480、AN-211923、AN-204286、AN-212977、AN-214528、AN)-215080、AN-217784、AN-219093、AN-218817、AN-217798、AN-218267、AN-2182678382)
* Data Warehouseリク [!UICONTROL エストの問題を修正しました] 。 （AN-181836）
* PDFでダウンロードした [!UICONTROL Workspace] プロジェクトで、値が特殊文字に変換される問題を修正しました。 （AN-196153）
* [!UICONTROL 管理コンソールで] 製品プロファイル [!UICONTROL 権限をコピーできない問題を修正しました]。 （AN-211113）
* 計算指標の時間形式が負の値に対して機能しない問題を修正しました。 （AN-210900）
* 静的行指標のアトリビューションモデル  を変更できない問題を修正しました。 （AN-207872）
* 「 [!UICONTROL 予定レポート] ビルダー」が「キュー」のステータスのままになる問題を修正しました。 （AN-215317）
* ExactTargetデータコネクタ [!UICONTROL を修正]。 （AN-210794）
* 一括取り込みAPIの遅延の問題を修正 [!UICONTROL しました]。 （AN-210165）
* Federated IDを使用して [!UICONTROL Report Builderにログインできない問題を修正しました] 。 （AN-207750）
* [!UICONTROL 広告分析] で [!DNL Google AdWords] データが表示されない問題を修正しました。 （AN-213249）
* 「 [!UICONTROL Workspace][!UICONTROL Project Viewed] 」のイベントがログに表示されない問題を修正しました。 （AN-214134）
* [!UICONTROL Workspaceで日付範囲を変更し、「すべてのパネルに] 適用」を選択した場合に発生していた問題を修正しました ****。 一部のパネルで日付が変更されませんでした。 （AN-214944）
* アラートを作成または編集できない問題を修正しました。 （AN-215920）
* 週の最初の曜日が月曜日から日曜日に散発的に切り替わることが原因で、 [!UICONTROL Workspace] の動的日付範囲で誤った日付が表示される問題を修正しました。 （AN-218835）

#### Adobe Analyticsのその他の修正

AN-101871、AN-115525、 AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 分析ワークスペースの可用性に対する冗長性の向上 | 2020 年 5 月 22 日 | 分析ワークスペースの可用性を確保するために、冗長性を高めるためにセカンダリCDN(コンテンツ配信ネットワーク)を追加します。 必要なネットワークファイアウォールのホワイトリストには、次のURLを追加する必要があります。<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| [!UICONTROL Workspace] での[!UICONTROL 入口／出口]の計算方法の変更 | 2020 年 4 月 8 日 | 2020 年 3 月の時点で、[!UICONTROL Analysis Workspace] における「_なし_」の値と[!UICONTROL 入口／出口]との相互作用を変更しました。Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. 例えば、訪問の最初のヒットにeVarの値がなく、2番目のヒットに値がないとします。 In [!UICONTROL Reports &amp; Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
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
| [分析ワークスペースのトレーニングチュートリアルテンプレート](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | 「 [!UICONTROL 分析ワークスペース][!UICONTROL 」トレーニングチュートリアルでは、Workspaceでの最初のプロジェクトの構築に関する一般的な用語と手順について説明し]ます。 |
| [前月と年の比較をトレンドに追加](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | カスタム日付範囲を適用して、 [!UICONTROL 分析ワークスペースで任意の指標に対する月別および年別のトレンド比較を作成する方法を説明します]。 |
| [分析ワークスペース用ダークモード拡張](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Dark Reader Chrome拡張機能を有効にして、分析ワークスペースを暗くします。 |
| [カスタムパレットを定義するためのスポイト拡張機能のカラー](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | ColorPick EyeDropper Chrome拡張機能を使用して、 [!UICONTROL Workspace] プロジェクトでカスタムカラーパレットに必要な16進値を簡単に見つける方法を説明します。 |

#### Analytics ヘルプリソース

* [Adobe Analyticsチュートリアル](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics製品ドキュメント](https://docs.adobe.com/content/help/ja-JP/analytics/landing/home.html)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

オーディエンスマネージャの新機能、修正点、ドキュメントおよびチュートリアル。

### ユーザーインターフェイスの更新

オーディエンスマネージャーは、エクスペリエンスを向上させ、他のExperience Cloudアプリケーションと統合するため、ドメインとヘッダーバーの更新をリリースしています。

* 組織間または別のアプリケーション間の切り替えが容易になりました。
* ヘルプメニューの特集記事やコンテキスト関連ビデオなど、ユーザーヘルプが改善されました。
* エクスペリエンスプラットフォームとファイルサポートチケットに関するフィードバックを提供する機能。
* 新しい簡単なURLパターン。 ブックマークを新しいURLに更新する： `experience.adobe.com/audience-manager`.

これらの更新は、Adobe IDを使用してログインするユーザーのみが利用できます。 Adobe IDログインに切り替えるには、Experience Cloudユーザーと製品の [管理を参照してください](https://docs.adobe.com/content/help/ja-JP/core-services/interface/manage-users-and-products/admin-getting-started.html)。

### Adobeオーディエンスマネージャーの新機能および修正点

| 機能 | 説明 |
| -----------| ---------- |  
| [バルク管理ツール(BAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | 次の新しい一括管理ツールワークシートをアップロードしました。<br><br><ul><li>特性階層のサブフォルダーをリストできます。(AAM-51528)</li><li>CRM IDに関連付けられた特性（デバイス間ID）の入力を求められた場合に指標を取得します(AAM-52135)</li><li>韓国語文字の言語エンコードの問題を修正しました。(AAM-AAM-54006)</li></ul> |

**修正点**

* 特性の数が多いフォルダーでトレンドレポートがタイムアウトする問題を修正しました。 （AAM-54457）
* 特性の作成/編集ワークフローで、 [!UICONTROL 式ビルダーが表示されない問題を修正しました] 。 （AAM-54255）
* UIのエラーメッセージが短時間しか表示されず、ユーザーがエラーメッセージを読む機会がなくなる問題を修正しました。 この問題は、例えば、宛先にマッピングされたセグメントを削除しようとした場合に発生していました。 （AAM-54031）
* オーディエンスのMarketplaceを使用していない顧客が月次の [!UICONTROL 請求電子メールを受け取る問題を修正しました] 。 （AAM-54602）
* ユーザーがUIの他の場所から特定の特性をクリックすると、特性ではなく、壊れたリンクが表示される問題を修正しました。 （AAM-54768）
* 特性式の編集モードで、Enterキーを押すとページが更新され、特性式が失われる問題を修正しました。 （AAM-54210）
* インターフェイス全体で複数のアクセシビリティを改善しました。(AAM-47781、AAM-49075、AAM-49360、AAM-49361、AAM-49376、AAM-50432、AAM-52)550、AAM-54660)。

### 新しいオーディエンスマネージャのチュートリアル {#tutorials-aam}

| コンテンツ | 説明 |
| -----------| ---------- |  
| [オーディエンスマネージャーの基本用語と概念について](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | このビデオでは、シグナル、特性、セグメントなど、オーディエンスマネージャーで開始する基本的な用語と概念の一部を説明します。 |
| [オーディエンスマネージャーでのデータフローについて](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | このビデオでは、アプリケーションへのデータフロー、アプリケーションからのデータフロー、およびアプリケーションからのデータフローを説明することで、Adobeオーディエンスマネージャーの理解に役立ちます。 |
| [オーディエンスマネージャ — DMPの概要](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | チャネル間のパーソナライゼーションに関する主な課題と、Adobeオーディエンスマネージャーがお客様の遍歴を強化する方法を理解します。 また、オーディエンスマネージャーでオンボード可能なデータタイプを学習し、オーディエンスマネージャーと統合されたアドテクエコシステムパートナーを特定します。 |
| [オーディエンスマネージャの使用例](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | このビデオでは、4つの一般的なオーディエンスマネージャの使用例を識別し、それらに関連するベストプラクティスについて説明します。 |
| [オーディエンスマネージャーでのデバイス間指標について](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | このビデオでは、デバイスのプロファイルとデバイス間のプロファイルの違い、およびUIの数値がこれらの異なるプロファイルタイプと一致する場所を示します。 |
| [オーディエンスマネージャーでの予測オーディエンスについて](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | このビデオでは、オーディエンスマネージャーの予測オーディエンスの概要、その仕組みの詳細を示し、使用例を示します。 |
| [オーディエンスマネージャーでの予測オーディエンスの設定とレポート](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | このビデオでは、オーディエンスマネージャーインターフェイスでの予測オーディエンスの設定について説明します。 モデルの結果を示すレポートも表示されます。 |

## ![アイコン](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品のアップデート

* **AEM as a Cloud Service**

   * アセット処理の改善と修正。 アセットの再処理ダイアログボックスでは、ユーザーがより詳細に制御でき、特定の処理プロファイルを選択でき、後処理ワークフローをトリガーするかどうかを指定できます。
   * Dynamic Mediaアセット取り込みのパフォーマンスが向上しました。

### セルフサービス

* **Automated Forms Conversion Service — リリースAFC-2020.03.1**

   最新のコネクタをインストールすると、新しいオプションが使用できます。

   **[!UICONTROL 論理セクションの自動検出]**: 「 [!UICONTROL 論理セクションを自動検出] 」オプションを使用すると、ページレベルのパネル（ページ番号ベースのパネル）をドロップして、論理パネルのみを作成できます。 また、前の論理セクションを持つセクションに属しないフィールドと、隣接する2つのページにまたがる論理セクションのフィールドを1つの論理セクションにクラブします。 例えば、論理セクションの一部のフィールドがページ1の末尾にあり、一部のフィールドがページ2の開始にある場合、こうしたフィールドはすべて1つの論理セクションに分割されます。

* **ダイナミックメディアでサポートされていない画像形式**

   ダイナミックメディアでサポートされていないラスターイメージファイル形式のサブタイプに関する情報 [!UICONTROL です]。

   ダイナミックメディアでの [サポートされていないラスターイメージ形式を参照してください](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media)。

* **コンテンツフラグメント**

   AEM Assets HTTP APIでサポートされる [コンテンツフラグメントについて、コンテンツフラグメントの](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)カスタマイズと拡張、およびレンダリング用のコンポーネントの [設定と共に説明します](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)[](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html)。

* **AEM Experience Leagueコミュニティ**

   AEM Experience Leagueコミュニティに接続 [する](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): 学習者やAEMエキスパートとの間で質問を行い、スレッドを参照し、ヒントや専門知識を共有します。

* **AEMニュースレター**

   Experience LeagueのAEMニュースレター  は、AEMの使い方を把握し、開始が価値をすぐに実現できるように設計されています。 最新のニュースレターを示します。

   * [巻](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)30: Experience Managerは、クラウドサービスとして使用できるようになりました。
   * [Experience Insiderニュースレターを購読](https://adobeeventsonline.com/AEM/2017/NL/Optin/) 。
   * 表示版ニュースレターアーカイブは、Adobe Experience Manager 6.5の学習とサポートページの [AEMリソース](https://helpx.adobe.com/jp/support/experience-manager/6-5.html) セクションにあります。

### Experience Manager の新しいチュートリアル

| コンテンツ | 説明 |
| -----------| ---------- |  
| [ローカルAEM Runtimeの設定](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [AEM Assetsファーストステップガイド](https://video.tv.adobe.com/v/33624?captions=jpn) | ビジネスユーザー向けのAEM Assetsの概要に関する概要ビデオです。 |
| [メタデータフォルダーのスキーマ](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | メタデータフォルダスキーマを使用すると、アセット上で直接操作する代わりに、アセットフォルダ自体に関連付けられたメタデータを管理および確認することができます。 |
| [タグ付け](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | タグは、アセットのフォルダー階層全体でアセットを管理するための不可欠なツールです。 タグ付け分類の確立は、ユーザーがAEM内のアセットを検出して整理できるようにする上で重要です。 |
| [メタデータプロファイル](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | メタデータプロファイルを使用すると、初期設定のメタデータをアセットフォルダ内のアセットに自動的に適用できます。 これにより、AEMユーザーのメタデータ管理の負荷を軽減し、メタデータの一貫性を向上できます。 |
| [メタデータスキーマ](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | メタデータスキーマは、AEMでアセットメタデータを公開するインターフェイスを定義します。 このビデオでは、アセットの適用に使用する方法の組み合わせについて説明します。 |

### その他のリソース

* [クラウドサービスとしてのAEMのリリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM as a Cloud Service のドキュメント](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/jp/experience-manager/cloud-manager/user-guide.html)
* [AEM Cloud Managerリリースノート](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/jp/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/ja-JP/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://docs.adobe.com/content/help/ja-JP/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre リリースノート](https://docs.adobe.com/content/help/ja-JP/livefyre/using/release-notes/c-rn.html)

## ![アイコン](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### Campaign Standard

* [Adobe Campaign標準20.3リリース](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### キャンペーンコントロールパネル

| 機能 | 説明 |
| -----------| ---------- |  
| GPG キー管理 | キャンペーンから送信されるデータを暗号化し、受信データを復号化するには、マーケティングインスタンスに GPG キーをインストールまたは生成します。 |
| CNAME サブドメインの証明書管理 | コントロールパネルで、CNAME メソッドでデリゲートされたサブドメインの SSL 証明書を更新できるようになりました。 |

### 新しいキャンペーンチュートリアル

* 新しい Campaign Standard のチュートリアル

| コンテンツ | 説明 |
| -----------| ---------- |  
| [コントロールパネル — Google TXTレコード管理](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | キャンペーンコントロールパネルで、電子メールをGMAILアドレスに送信するために使用するすべてのサブドメインに、Google TXTサイト検証レコードを追加する方法を説明します。 |
| [External APIアクティビティを使用したワークフローの設定と実行](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | External APIアクティビティを使用して外部REST APIエンドポイントを呼び出す方法を説明します。 |
| [Android向けプッシュ通知の使用の手引き（チュートリアル）](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | このチュートリアルでは、Campaign StandardおよびAndroid Appでプッシュ通知を設定する手順について説明します。 |

* 新しいCampaign Classicチュートリアル

| コンテンツ | 説明 |
| -----------| ---------- |  
| [雪片の大データ管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Adobe Campaignクラシックの雪片コネクタを利用する方法を説明します。 |
| [コントロールパネル — Google TXTレコード管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | キャンペーンコントロールパネルで、電子メールをGMAILアドレスに送信するために使用するすべてのサブドメインに、Google TXTサイト検証レコードを追加する方法を説明します。 |

### キャンペーンのヘルプリソース

* Adobe Campaign標準： [ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/campaign-standard-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) — リリース計画 [](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html)[— 最新ドキュメントの更新](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaignクラシック： [ヘルプセンター](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/campaign-classic-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新のドキュメント更新](https://docs.adobe.com/content/help/ja-JP/campaign-classic/using/documentation-updates.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/control-panel/using/release-notes.html)

## ![アイコン](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Advertising Cloud DSPの新機能](#adcloud-dsp)
* [Advertising Cloud検索の新機能](#adcloud-search)

### Advertising Cloud DSPの新機能 {#adcloud-dsp}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL キャンペーンクラシック] &amp; [!UICONTROL キャンペーンベータ版] | IASの不正およびブランドの安全性の測定設定(オプションで各キャンペーンに設定可能)に、VASTおよびVPAIDインベントリでの測定オプションが追加されました。 |
| [!UICONTROL キャンペーンベータ版] | データの視覚化とページ読み込み時間が改善されました。 |
|  | すべてのページで、現在のフィルターと表示に基づくExcelレポートをダウンロードできるようになりました。 |
|  | （5月22日リリース）新しい指標には、全時間指標、現在の間隔配信、日付固有のOTSが含まれます。 |
| [!UICONTROL ブラックリスト] | 予測システムは、広告主またはアカウントレベルのブラックリストを自動的に使用するようになりました。 ユーザーは、ブラックリストを配置設定に貼り付ける必要はありません。 |
| [!UICONTROL 在庫掘り出し物] | （クローズドベータ版）シンプル化された新しいフォームを使用すると、Deal ID Inboxで利用できない案件のサプライサイドプラットフォーム(SSP)の設定、編集、トラブルシューティングをすばやく行うことができます。 |
|  | [案件ID]受信トレイでプログラム的に保証された案件のパッケージを受け入れると、各案件IDに対して既定の掲載場所を作成する必要があるという警告が表示されるようになりました。 |

### Advertising Cloud検索の新機能  {#adcloud-search}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL キャンペーン] | (Google広告アカウント； ベータサービス) 5月下旬より、Advertising Cloud Searchでは、Google GmailディスプレイキャンペーンおよびGoogle Smart Shoppingキャンペーンのデータを、トラッキングとレポートのためのGoogleコンバージョンと同期できるようになります。 また、このサービスでは、キャンペーンおよび広告グループの表示から、既存のキャンペーンのキャンペーン設定および広告グループ設定を編集することもできます。 サービスはオプションです。 サービスが一般に提供されると、追加料金が適用されます。<br>ベータ版のプログラムや今後の範囲など、本サービスの詳細については、アドビのアカウントマネージャーにお問い合わせください。 |

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

Magent リリースノートについては、以下を参照してください。

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![アイコン](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーの各ステージを通じてエンゲージメントをおこなうことで顧客体験を変えようとしているリード管理や B2B マーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

最新のリリース情報について詳しくは、 [!DNL Marketo][リリースノート](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) を参照してください。

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

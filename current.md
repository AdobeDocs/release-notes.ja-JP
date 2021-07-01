---
title: 最新のリリースノート
description: Experience Cloud 製品および サービスに関する最新のリリースノート、新機能および新規ドキュメントについて説明します。Experience Cloud、Creative Cloud エンタープライズ版および Document Cloud に関する新しいヘルプとチュートリアルをご覧ください。
doc-type: release notes
last-update: June 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 99885f10a13d7b51702ffac182362f1abd09f141
workflow-type: tm+mt
source-wordcount: '4984'
ht-degree: 99%

---

# Adobe Experience Cloud リリースノート - 2021 年 6 月

![バナー](assets/experience-cloud-banner-3.png)

Experience Cloud アプリケーションおよびサービスは毎月更新されます。このページには、[!DNL Experience Cloud] と [!DNL Experience Platform] の最新のリリースアップデート、ドキュメントおよびチュートリアルが集約されています。また、[!DNL Creative Cloud for Enterprise] と [!DNL Document Cloud] の新しいドキュメントも参照できます。

>[!NOTE]
>
>毎月[アドビの優先製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)をサブスクライブして、このページの更新に関する電子メール通知を受信します。 このページはひと月にわたって保持されるので、定期的にアクセスして、アドビのエンタープライズ製品と Experience League のドキュメントが更新されていないか確認してください。

最終更新日：**2021 年 6 月 14 日（PT）**

* [Experience Cloud の主要なインターフェイスコンポーネント](#ecloud)
* [Adobe システムステータス](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) および [Customer Journey Analytics](#cust-journey)
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud エンタープライズ版](#creative-cloud)

サポートが必要な場合は、[Adobe Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスし、製品および技術ドキュメント、アドビが運営するコース、ビデオチュートリアル、すばやい回答、コミュニティインサイト、講師によるトレーニングをお探しください。

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud 中央の UI コンポーネント {#ecloud}

Experience Cloud の中央インターフェイスコンポーネントには、セルフヘルプ、検索、ユーザーアカウントの環境設定など、統合された製品ヘッダーからアクセスできる、アップデートが含まれています。People、Places（場所）、および製品管理のアップデートについては、こちらを参照してください。

| 機能 | 日付 | 説明 |
| ------- | ------- | ------- |
| Adobe Federated ID のシングルサインオンサポート | 2021 年 6 月 17 日（PT） | Federated ID を使用すると、メールアドレスやパスワードを入力しなくても、Experience Cloud にログインできます。 この機能を使用するには、Experience Cloud の URLに **#/sso:@domain** を追加します。 <br><br>例えば、ドメイン **adobecustomer.com** を所有していて、Adobe Analytics にサインインしたい場合、URL は次のようになります。**https://experience.adobe.com/#/sso:@adobecustomer.com/analytics** |
| Experience League 検索 | 2021 年 6 月 1 日（PT） | Experience League ドキュメントの検索が改善されました。[Experience League](https://experienceleague.adobe.com/docs/?lang=ja) に移動し、「**[!UICONTROL 検索]**」フィールドを使用して、チュートリアル、ドキュメント、コースなどを検索します。 |

{style=&quot;table-layout:auto&quot;}

**その他のヘルプリソース**

* [中央インターフェイスコンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)およびユーザー管理の管理ヘルプ
* [Places - 位置情報サービス](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ja)のヘルプとリリースノート
* [People - 顧客属性とオーディエンスライブラリ](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ja)に関するヘルプ。

## ![アイコン](/assets/adobe.png) Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

Adobe System Status の最新の更新は、[Adobe System Status - 2020 年 5 月 21 日（PT）](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ja)で、最新のリリース情報を確認できます。

## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Experience Platform と Experience Platform Launch に関するリリース更新情報と新しいドキュメントが含まれます。

* **2021 年 5 月 26 日（PT）：** [Experience Platform リリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja)
* **2021 年 5 月 17 日（PT）：** [Experience Platform データ収集リリースノート](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=ja)（旧 Experience Platform Launch）

### Experience Platform チュートリアルおよびコース {#tutorials-platform}

Experience Platform およびサービス用に公開された新しいビデオ、チュートリアル、またはコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [クエリーサービスによるデータの準備](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html?lang=ja) | ビデオ | レポートやダッシュボーディングに Create Table AS（CTAS）関数と Spark SQL 関数を使用して、複数のデータセットのデータを消去、準備、組み合わせてデータセットを作成する方法を説明します。 |
| 2021 年 6 月 | [サンドボックス間でのスキーマのコピー](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html?lang=ja) | ビデオ | [!UICONTROL スキーマ API の書き出し／読み込み]を使用して、Adobe Experience Platform のサンドボックス間でスキーマをコピーする方法を説明します。 開発用サンドボックスでスキーマを作成してテストし、実稼動用にコピーします。 |
| 2021 年 6 月 | [スキーマの更新](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html?lang=ja) | ビデオ | Adobe Experience Platform の既存のスキーマを更新する際に注意すべき基本的な事項について説明します。 |
| 2021 年 6 月 | [スキーマ構築ブロック](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html?lang=ja) | ビデオ | フィールド、データタイプ、スキーマのフィールドグループ、クラス、動作など、エクスペリエンスデータモデル（XDM）スキーマの主要な構築ブロック要素について説明します。 |
| 2021 年 6 月 | [スキーマクラスの作成](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html?lang=ja) | ビデオ | エクスペリエンスデータモデル（XDM）スキーマに使用するクラスを、Adobe Experience Platform で作成する方法について説明します。 |
| 2021 年 6 月 | [スキーマ間の関係の設定](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html?lang=ja) | ビデオ | Adobe Experience Platform で 2 つのスキーマ間の関係を設定する方法について説明します。関係を使用すると、1 つのデータセットを別のデータセットのルックアップテーブルとして使用できます。 |
| 2021 年 6 月 | [スキーマデータタイプの作成](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html?lang=ja) | ビデオ | エクスペリエンスデータモデル（XDM）スキーマに使用する独自のデータタイプを、Adobe Experience Platform で作成する方法について説明します。 |
| 2021 年 6 月 | [データモデルからエクスペリエンスデータモデルへの変換](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html?lang=ja) | ビデオ | データアーキテクトが既存のトランザクションデータモデルを取得し、エクスペリエンスデータモデルに変換する方法について説明します。このビデオでは、エンティティ関係図を使用したモデリングアプローチの違いを示します。 |
| 2021 年 6 月 | [データモードの計画](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html?lang=ja) | ビデオ | Adobe Experience Platform でスキーマの構築を開始する前にすべきことについて説明します。ビジネスの使用例を文書化し、Platform ライセンスを理解、製品ガードレールを把握、取り込むデータを特定してからデータモデルを仕上げます。 |
| 2021 年 6 月 | [Tableau のクエリーサービスへの接続](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html?lang=ja) | ビデオ | `PostgreSQL` プロトコルをサポートする様々なデスクトップクライアントアプリケーションから[!UICONTROL クエリサービス]に接続する方法と、`PostgreSQL` ツールとドライバーを使用してクエリを接続し、書き込む方法について説明します。 |
| 2021 年 6 月 | [クエリーサービスでアドビが定義した関数](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html?lang=ja) | ビデオ | Adobe Experience Platform [!UICONTROL クエリサービス]の Adobe 定義関数を使用して、エクスペリエンスイベントデータに対して一般的なビジネス関連タスクを実行する方法について説明します。 |
| 2021 年 6 月 | [クエリーサービスによるデータ検索](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html?lang=ja) | ビデオ | SQL 関数を使用して、取り込んだデータを検証、データをプレビューし、データの統計的および分析的プロパティを調べる方法について説明します。 |
| 2021 年 6 月 | [クエリサービスの概要](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html?lang=ja) | ビデオ | Adobe Experience Platform のクエリサービスの概要、およびそれが顧客の行動を理解し、効果的なインサイトを生み出すのにどのように役立つかについて説明します。 |
| 2021 年 6 月 | [クエリーサービス UI の概要](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html?lang=ja) | ビデオ | Adobe Experience Platform クエリサービスで、クエリの書き込みと実行、以前に実行されたクエリの表示、IMS 組織内の他のユーザーが保存したクエリへのアクセスをおこなう方法について説明します。 |
| 2021 年 6 月 | [ クエリー API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html?lang=ja) | ビデオ | Adobe Experience Platform [!UICONTROL クエリサービス API] を使用して、クエリの記述と実行、スケジュールクエリの作成、およびクエリテンプレートの作成をおこなう方法について説明します。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Experience Platform を使用して、各個人のニーズをリアルタイムでインテリジェントに予測することで、エクスペリエンスチャネルをまたいでカスタマージャーニーを調整します。

* 更新：2021 年 6 月 - [Journey Orchestration リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ja)

**Journey Orchestration の追加リソース**

[ドキュメント](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] は、Adobe Experience Platform と統合されたアプリケーションサービスです。[!UICONTROL Offer Decisioning] を使用すると、すべてのタッチポイントにわたって適切なタイミングで最高のオファーとエクスペリエンスを顧客に提供できます。

* 更新：2021 年 4 月 - [Offer Decisioning リリースノート](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=ja#new)

**Offer Decisioning のその他のリソース**

[ドキュメント](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) - [ハウツービデオ](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=ja)

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

リリース日：**2021 年 6 月 17 日（PT）**

* [Adobe Analytics の新機能](#aa-features)
* [Customer Journey Analytics の新機能](#cust-journey)
* [Adobe Analytics の修正点](#aa-fixes)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [Analytics コースとチュートリアル](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics の新機能 {#aa-features}

| 機能 | [一般公開](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=ja) - ターゲット日 | 説明 |
| ----------- | ---------- | ------- |
| なし | なし |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics の新機能 {#cust-journey}

| 機能 | [一般公開](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - ターゲット日 | 説明 |
| ----------- | ---------- | ----- |
| なし | なし |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics の修正点 {#aa-fixes}

* 売上高リアルタイムレポートに間違った通貨が表示されていた問題を修正しました。（AN-254649）
* [レポートで eVar の大文字と小文字の区別](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html?lang=ja)に関するドキュメントを更新しました。（AN-246438）
* [データフィードの実装](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html?lang=ja)についての詳細な説明のドキュメントと[こちら](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html?lang=ja#BucketOwnerFullControl)を更新しました。（AN-219485）
* Data Warehouse レポートで一部のデータが送信されない問題を修正しました。（AN-259951; AN-259712; AN-260107; AN-259953）

#### Adobe Analytics または CJA のその他の修正点

AN-246344; AN-250035; AN-250354; AN-252482; AN-254661; AN-254965; AN-255424; AN-256515; AN-257232; AN-257572; AN-257893; AN-258393; AN-259203; AN-259513; AN-259614; AN-259665; AN-259931; AN-260074; AN-260085; AN-260147; AN-260190; AN-260198; AN-260290; AN-260306（CJA）; AN-260508; AN-260625; AN-260793; AN-260861; AN-260938; AN-260945; AN-261149; AN-261317

### [!DNL Analytics] 管理者向けの重要な注意事項  {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| ----------- | ---------- | ---------- |
| ブラウザーユーザーエージェントが macOS の誤ったオペレーティングシステムバージョンを表す | 2021 年 5 月 19 日（PT） | 現在、すべての主要なブラウザーは、macOS X 11 以降を使用している場合でも、ブラウザーのユーザーエージェント文字列に記録されているとおりに、macOS 10 を使用していると誤ってレポートします。Adobe Analytics のレポート機能は、オペレーティングシステムなどのデバイス情報を決定する際にユーザーエージェントを使用するので、この問題の影響を受けます。この不正確さが発生するのは、一部の ｗeb サイトの互換性の問題を防ぐためです。この [Bugzilla チケット](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454)を参考にしてください。この問題が修正される時期、また修正されるかどうかは明確ではありません。 <br>一部のブラウザーでは、当初から正しく macOS 11 が記録されていたので、この値と一致するトラフィックが発生する可能性があります。ただし、レポートが不正確なため、オペレーティングシステム macOS 11 用のフィルタリングは役に立ちません。<br>macOS 11 上の Safari 以降、Apple が CNAME 実装に適用するために ITP Cookie の有効期限制限を更新したので、この問題は重大です（[WebKit のブログ投稿](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)を参照）。<br>このアップデート以前は、これらの制限は、JavaScript を使用して設定されたクライアントサイド Cookie にのみ適用されていました。このような誤りにより、macOS 11 を使用しているトラフィックの量を評価しにくくなるので、ITP の変更の影響を受けるようになります。Cookie と Adobe Analytics について詳しくは、[こちら](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html?lang=ja#cookies)を参照してください。 |
| 3 つの Analytics API サービスの提供終了 | 2021 年 5 月 19 日（PT） | 2021 年 8 月 18 日（PT）に、次の Analytics レガシー API サービスがサポート終了となり、停止されました。これらのサービスを使用して現在構築されている統合は、その日以降機能しなくなります。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>アドビでは、お客様のご質問に対する回答や進め方に関するガイダンスを提供するために、[従来の API の EOL（サポート終了）に関する FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API のどちらにアクセスする場合にも使用できます。 |
| 2021 年 ISO 地域の更新 | 2021 年 5 月 13 日（PT） | 2021 年 5 月 21 日（PT）に、2021 年の ISO 地域の更新を実施します。このリリース以降、マイナーアップデートが提供される可能性があります。 |
| フル処理データソースののサポート終了 | 2021 年 4 月 12 日（PT） | アドビは、2021 年 7 月 31 日（PT）にフル処理データソースを非推奨にする予定です。 2021 年 3 月 25 日（PT）現在、このタイプの新規インポートは作成できなくなっています。 このタイプのデータをインポートするには、[一括データ挿入 API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) を使用してください。 |
| ログインして [!UICONTROL Report Builder] をアップデート | 2021 年 4 月 9 日（PT） | 2021 年 1 月 14 日（PT）、[!UICONTROL Report Builder] のサインインの更新により、従来のテクノロジーへの依存がなくなり、Experience Cloud のサインインプロセスと連携できるようになりました。Experience Cloud は Enterprise ID（電子メールとパスワード）を使用します。[!UICONTROL Report Builder] へのアクセスが中断されないようにするには、2021 年 7 月 22 日（PT）までに [!UICONTROL Report Builder] アドインをバージョン 5.6.47 以降にアップデートしてください。Report Builder バージョン 5.6.47 以降では、Experience Cloud のサインインのみをサポートし、シングルサインオンはサポートしません。 |
| データフィードと Data Warehouse の IP アドレスの変更 | 2021 年 4 月 6 日（PT） | 6 月 17 日（PT）より、アドビのデータセンター内でデータフィードおよび Data Warehouse 配信システムの再配置が行われます。そのため、表示される外部 IP アドレスが変更される可能性があります。レポートおよびフィードが提供されるデータセンターのすべての IP CIDR ブロックが、制御する宛先システムのファイアウォール内に存在することを確認しておくことを推奨します。 [ファイアウォールの許可リストに追加する IP アドレス範囲の完全なリストを以下に示します](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html?lang=ja#data-collection-and-ftp-ip-address-blocks)。 |
| 今後の Analytics メニューの変更に関するお知らせ | 2021 年 3 月 24 日（PT） | 2021 年 4 月 22 日（PT）に、パフォーマンスを向上させるために、**[!UICONTROL コンポーネント]**、 **[!UICONTROL ツール]**、**[!UICONTROL 管理]**&#x200B;のドロップダウンメニューを更新します。 これらのページはすべて、「**[!UICONTROL すべてのコンポーネント]**」、「**[!UICONTROL すべてのツール]**」および「**[!UICONTROL すべての管理者]**」リンクから引き続き使用できますが、ドロップダウンメニューからは削除されます。 ドロップダウンメニューから削除され、それぞれのリンクページに配置されるメニュー項目は次のとおりです。<br><br> [!UICONTROL コンポーネント]<ul><li>[!UICONTROL ブックマーク]</li><li>[!UICONTROL ダッシュボード]</li><li>[!UICONTROL ターゲット]</li><li>[!UICONTROL カレンダーイベント]</li><li>[!UICONTROL スケジュールされているレポート]</li><li>[!UICONTROL レポート設定]</li></ul>[!UICONTROL ツール]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL ユーザー管理]</li><li>[!UICONTROL 分類インポーター]</li><li>[!UICONTROL 分類ルールビルダー]</li><li>[!UICONTROL データソース]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL カンパニー設定]</li><li>[!UICONTROL ログ]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL コードマネージャー]</li><li>[!UICONTROL IP で除外]</li><li>[!UICONTROL トラフィック管理]</li></ul> |
| Same-as-SiteCatalyst VISTA 処理 = オン | 2021 年 3 月 17 日（PT） | 2021 年 6 月 17 日（PT）にすべてのレポートスイートがアップデートされ、[!UICONTROL Same-as-SiteCatalyst VISTA 処理]がオンに設定されます。この変更により、処理ルールに一致するようにデータが処理されるため、Data Warehouse のレポートに影響します。ご質問やご不明な点がある場合は、カスタマーケアにお問い合わせください。 |
| Reports &amp; Analytics のランディングページオプション | 2021 年 2 月 19 日（PT） | 2021 年 3 月 25 日（PT）に、新しい Reports &amp; Analytics ダッシュボードまたはその他のコンテンツを Adobe Analytics ランディングページとして設定するオプションが削除されました。 以前に Reports &amp; Analytics ページをカスタムランディングページとして設定していた場合、[!UICONTROL ユーザーの環境設定]でランディングページが変更されるまで、このページは引き続き機能します。 |
| Adobe Data Connectors のサポート終了 | 2020 年 7 月 13 日（PT） | Adobe [!UICONTROL Data Connectors] は、実行不可能またはサポート対象外のレガシーテクノロジーによって動作します。[Adobe Exchange パートナープログラム](https://partners.adobe.com/exchangeprogram/experiencecloud)で新しい標準が利用できます。 どの統合でも、その標準を使用して、引き続き提供およびサポートできます。 正式なサポート終了日は 2021 年 8 月 1 日（PT）です。 [詳細情報...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=ja) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

AppMeasurement リリースの最新の更新については、[AppMeasurement for JavaScript リリースノート](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja)を参照してください。

### 新しい Analytics コースとチュートリアル {#tutorials-analytics}

[!DNL Analytics] と [!UICONTROL Customer Journey Analytics] の新しいコース、チュートリアル、記事。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [Customer Journey Analytics を使い始める（管理者向け）](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1&amp;lang=ja) | コース | Customer Journey Analytics の設定、構成、管理方法について説明します。基礎を身に着けるための基本的な概念をいくつか学び、設定手順に進みます。 このコースでは、次に、計算指標およびセグメントを Adobe Analytics から Customer Journey Analytics に移行する際の推奨事項を紹介します。 |
| 2021 年 6 月 | [内部サイト検索レポートの設定](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=ja) | ビデオ | Analysis Workspace でフリーフォームテーブルを作成および設定して、サイトの内部検索機能を分析します。 |
| 2021 年 6 月 | [Web SDK 変数の Adobe Analytics へのマッピング](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=ja) | ビデオ | 処理ルールを使用して、Web SDK から Adobe Analytics に分析変数をマッピングする方法について説明します。 |
| 2021 年 6 月 | [Web SDK を使用した内部検索変数の実装](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=ja) | ビデオ | Web SDK を使用して、内部検索用語トラッキングのユースケースに Adobe Analytics 変数を実装する方法を説明します。ページから Experience Edge、そして Adobe Analytics へとデータが流れるのを確認します。 |
| 2021 年 6 月 | [AppMeasurement を使用した内部検索変数の実装](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=ja) | ビデオ | このビデオでは、検索語句、結果数など、Experience Platform データ収集／Launch を使用して Adobe Analytics の内部サイト検索変数を実装する手順を説明します。 |
| 2021 年 6 月 | [内部サイト検索のビジネス要件の定義](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=ja) | ビデオ | サイト上で内部検索を追跡することを決定する際には、まず、検索のどの側面を追跡したいのか、そして結果を分析することでどのようなアクションが取れるのかを決定することが重要です。このビデオでは、ビジネス要件の文書化について説明します。 |

{style=&quot;table-layout:auto&quot;}

### Analytics ヘルプリソース

* [Adobe Analytics 製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の修正点と改善点。

### 修正点および改善点 {#aam-fixes-and-improvements}

* [アクティビティ使用状況レポート](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=ja)の機能強化がリリースされ、1 年以上前のデータを確認できるようになりました。（AAM-58268）
* アドビは、Audience Manager のお客様に Audience Manager Amazon S3 バケットのユーザーアクセスキーを提供します。 セキュリティ上の理由から、100 日間操作されない場合、キーは自動的に無効化されます。 詳しくは、[データ収集および製品統合に関する FAQ](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=ja) のページ下部にある質問を参照してください。

## ![アイコン](/assets/aem.png) Experience Manager {#aem}

 Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

>[!NOTE]
>
>[Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することをお勧めします。

### Experience Manager 製品のアップデート

* **Experience Manager 6.5.9.0**

   Experience Manager 6.5、 Service Pack 9.0（6.5.9.0、2021年5月27日（PT）リリース）は、 2019年4月の AEM 6.5 の一般提供開始以降にリリースされた新機能、お客様から要望のあった主要な機能強化、パフォーマンス、安定性、セキュリティの向上を含む重要なアップデートです。

   * [リリースノート](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=ja)
   * [AEM Forms リリース成果物](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=ja)

### Experience Manager 製品リリース

* **Experience Manager as a Cloud Service**

   Adobe Experience Manager as a Cloud Service の新機能。

   >[!NOTE]
   >
   >Experience Managerは、Cloud Serviceの6月の機能リリースとして提供されます。 新機能を体験するには、少なくともExperience Manager2021.6.5561を使用していることを確認してください。

   * **Adobe Experience Manager as a Cloud Service の基盤**

      * [プレリリースチャネル](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=ja)：実稼動への移行の 1 か月前に予定されている機能のプレビュー
      * [API の廃止](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=ja)：最新の非推奨（廃止予定）API のリスト。
      * [Experience Manager as a Cloud Service SDK ビルド Analyzer Maven プラグイン](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=ja)：Maven プロジェクトを最新バージョンに更新します。 これには、非推奨（廃止予定）の Java™ API チェックやその他の改善を含みます。
   * **Experience Manager Sites as a Cloud Service**

      新しい[プレビュー層](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=ja)でコンテンツを検証して、パブリッシュ層と同じように、最終的なエクスペリエンスのルックアンドフィールをシミュレートできるようになりました。この新しい機能は、Experience Manager Sites Managed Publication ウィザードで有効になります。このウィザードでは、[!UICONTROL 公開]または[!UICONTROL プレビュー]のどちらかの公開先を選択できます。[!UICONTROL プレビュー]のエクスペリエンスには、専用 URL からアクセスできます。[!UICONTROL プレビュー]で検証した後、通常どおり、[!UICONTROL オーサー]から[!UICONTROL 公開]にコンテンツを公開できます。Experience Manager as a Cloud Service 環境での[!UICONTROL プレビュー]サービスの有効化は、今後数週間で徐々に展開されます。

   * **Experience Manager Assets as a Cloud Service**

      プレリリースチャネルの新機能：

      * メタデータスキーマは、フォルダーのプロパティに直接適用できます。
      * [!UICONTROL アセットの一括取得]ツールを使用すると、一括取得中にメタデータを追加できます。
      * ユーザーエクスペリエンスの機能強化では、フォルダー内に存在するアセットの数が表示されます。1 フォルダー内に 1000 個を超えるアセットがある場合、Experience Manager アセットに「1000+」と表示されます。

      [!UICONTROL Dynamic Media] の新機能：

      * スマートイメージングデバイスのピクセル比（DPR）とネットワーク帯域幅の最適化により、高解像度ディスプレイを搭載しネットワーク帯域幅が制限されたデバイス上で、最高品質の画像を効率的に配信できます。[スマートイメージングの FAQ](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=ja) を参照してください。



### **Experience Manager コミュニティ**

* [すべての Experience Manager ブログのワンストップショップ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [Experience Manager の新しいアイデアの送信に関するガイドライン](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [Dan Levy の Adobe Summit 2021 スニーク](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865)：エンジニアやデータサイエンティストから UX デザイナーやプロダクトマネージャーまで、すべてのアドビ従業員には、年に 1 度、ブランドと顧客のインタラクションを発展させる革新的なアイデアを共有する機会が与えられます。Adobe Sneaks に参加しましょう。ここでは、AI やローコードアプリなどの最新のテクノロジーを活用した、上位 7 つのプロジェクトを紹介します。

### Experience Manager リリース情報

Experience Manager のリリースノートはすべて次のページに記載されています。

* [Adobe Experience Manager as a Cloud Service リリース情報](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=ja)
* [Experience Manageras aCloud Serviceリリースノート](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=en)
* [Experience Manager Cloud Manager リリースノート](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=en)
* [自動フォーム変換サービスリリースノート](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=ja)
* [Experience Manager 6.5 Service Pack リリースノート](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Experience Manager 6.4 累積修正パックリリースノート](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ja)
* [Experience Manager Assets Dynamic Media リリースノート](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=ja)
* [Experience Manager Brand Portal リリースノート](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ja)
* [Experience Manager デスクトップアプリケーションリリースノート](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=ja)
* [Experience Manager Dispatcher リリースノート](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=ja)
* [Livefyre リリースノート](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=ja)

### 新しい Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [インターフェイスのメソッドの実装](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=ja) | 記事 | Document Cloud REST API を使用して PDF を作成するためのインターフェイスメソッドを実装する方法について説明します。 |
| 2021 年 6 月 | [サービスインターフェイスの作成](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html?lang=ja) | 記事 | インターフェイスで公開するメソッドを定義します。 |
| 2021 年 6 月 | [カスタム OSGi 設定の作成](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=ja) | 記事 | Adobe I/O プロジェクトの詳細を取得できるよう、カスタム OSGi 設定について説明します。 |
| 2021 年 6 月 | [Content Analyzer の作成](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=ja) | 記事 | PDF を作成 REST 呼び出しに対する入力パラメーターに関する情報を含む、JSON 部分の作成方法を説明します。 |
| 2021 年 6 月 | [カスタムプロセス手順の作成](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=ja) | 記事 | ネイティブファイルを変換して変換後の PDF に置き換える、カスタムプロセス手順の完全なコードを表示します。このカスタム手順では、ワークフローのプロセス引数として提供されたフォルダー名ですべての添付ファイルを検索します。 このカスタムプロセス手順では、カスタム `DocumentCloudSDKService` のメソッドを使用して PDF を作成します。 |
| 2021 年 6 月 | [GraphQL 永続クエリ](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=ja) | ビデオ | Experience Manager で永続クエリを有効化、作成、更新、および実行する方法を説明します。 |
| 2021 年 6 月 | [AEM Forms での最初のサーブレットの作成](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=ja) | 記事 | 最初のスリングサーブレットを作成し、データをフォームテンプレートにマージできるようにします。 |
| 2021 年 6 月 | [Experience Manager フォームを使用した最初の OSGi サービスの作成](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=ja) | 記事 | AEM Forms を使用して最初の OSGi サービスを構築し、データをテンプレートとマージして PDF を生成できるようにします。 |

{style=&quot;table-layout:auto&quot;}

### Experience Manager に関するその他のヘルプリソース

* [Adobe Experience Manager as a Cloud Service に関するガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=ja)
* [Experience Manager 6.5 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ja)
* [Experience Manager 6.4 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ja)
* [Experience Manager 6.3 のラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [Experience Manager 6.2 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja#previous-updates)
* [Experience Manager ドキュメントの以前のバージョン](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Cloud Manager ユーザガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=ja)
* [Dynamic Media Classic ヘルプホーム](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ja)
* [Experience Manager ドキュメント：最近の更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ja#aem-as-a-cloud-service)

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 最新の製品リリース

リリースされた最新の機能、機能強化、修正について詳しくは、以下を参照してください。

* **新しい Adobe Campaign v8** では、インフラストラクチャ、セキュリティ、配信品質、監視機能が大幅に強化されています。Adobe Campaign v8 は、その規模と速度を劇的に改善し、より多くの顧客プロファイルを管理する機能に加えて、1 時間あたりの配信率とトランザクションを大幅に向上させます。詳しくは、[Campaign v8 のドキュメント](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ja)を参照してください。

* **Adobe Campaign Classic v7 21.1.3 リリース：**&#x200B;詳しくは、[Campaign Classic v7 リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ja?lang=ja)を参照してください。

* **Adobe Campaign Standard 21.2 リリース：**&#x200B;詳しくは、[Campaign Standard リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ja)を参照してください。

### 新しい [!UICONTROL Campaign] コースとチュートリアル {#tutorials-campaign}

| 公開日 | 名前 | ソリューション | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [Campaign Standard と Analytics の統合によるメールマーケティングの最適化](https://experienceleague.adobe.com/?lang=ja#dashboard/learning) | Campaign Standard | （コース）Adobe Analytics と Campaign Standard を統合し、リアルタイムデータを使用してメールマーケティング戦略を最適化する方法について説明します。このコースでは、Adobe Analytics で Campaign Standard レポートを作成する方法を説明します。次に、Experience Cloud Triggersと Platform Launch を使用して、顧客のアクティビティに基づいてマーケティングメッセージとトランザクションメッセージを設定する方法を説明します。 |
| 2021 年 6 月 | [Adobe Campaign v8 チュートリアル](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html?lang=ja) | Campaign V8 | このユーザーガイドには、Adobe Campaign V8 の数々の特長や機能に関するビデオとチュートリアルが含まれています。 |
| 2021 年 6 月 | [電子メール配信の作成と設計](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html?lang=ja) | Campaign V8 | （ビデオ）メール配信を作成するプロセスと、メールコンテンツを設計およびパーソナライズする方法について説明します。 |
| 2021 年 6 月 | [配信品質を考慮した電子メールの設計](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html?lang=ja) | Campaign V8 | （ビデオ）配信品質のベストプラクティスをメール配信に適用する方法について説明します。 |
| 2021 年 6 月 | [タイポロジルールを使用した疲労管理](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html?lang=ja) | Campaign V8 | （ビデオ）タイポロジルールを活用して疲労管理を実装する方法について説明します。 |
| 2021 年 6 月 | [フィルターを使用した疲労管理の設定](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html?lang=ja) | Campaign Standard | （ビデオ）フィルターを使用して Adobe Campaign に疲労管理を実装する方法について説明します。 |

{style=&quot;table-layout:auto&quot;}

### Campaign ヘルプリソース

* Adobe Campaign Standard：[ヘルプセンター](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ja) - [リリース計画](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ja) - [最新ドキュメントの更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ja)
* Adobe Campaign Classic：[ヘルプセンター](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ja) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ja) - [最新ドキュメントの更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ja)
* Adobe Campaign コントロールパネル：[ドキュメント](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=ja) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ja) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ja) のハウツービデオ

## ![アイコン](/assets/advertising-cloud.png) 広告 {#adcloud}

リリースノート： [!DNL Adobe Advertising]

* [Advertising DSP の新機能](#adcloud-dsp)
* [Advertising Search の新機能](#adcloud-search)

### [!DNL Advertising DSP] の新機能  {#adcloud-dsp}

最終更新日：**2021 年 6 月 10 日（PT）（6 月 16 日（PT）リリース）**

| 機能 | 説明 |
| -----------| ---------- |
| キャンペーン管理 | （6 月 16 日リリース）予測は、プレースメントレベルのペースと予算で、標準のディスプレイ配置に使用できます。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Search] の新機能  {#adcloud-search}

最終更新日：**2021 年 5 月 19 日（PT）（5 月 18 日（PT）リリース）**

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL 通知センターベータ版] | [!UICONTROL 通知センターベータ版]は、すべてのユーザーが利用できます。これを使用すると、アカウント認証エラー、トリガーされるカスタムアラート、および生成する[!UICONTROL Advertising Insights] の完了に関するメールおよび ｗeb 通知をサブスクライブできます。<br>通知は、次のいずれかで確認できます。<ul><li>[!UICONTROL 通知]パネル。ページの右上にある通知リンクから開きます。</li><li>[!UICONTROL インサイトとレポート／通知センターベータ版]の[!UICONTROL 通知センター]。</li></ul><br><b>注意：</b>通知の保存方法が改善されたので、既存の通知はすべて消去されました。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

最新のリリース情報については、Magento Commerce および Open Source の[リリースノート](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)を参照してください。

## ![アイコン](/assets/target.png)[!DNL Target] {#target}

最新のリリース情報については、[[!DNL Target] リリースノート](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ja)を参照してください。

## ![アイコン](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーのすべてのステージにわたるエンゲージメントを通じてカスタマーエクスペリエンスを変革しようとしている経営陣や B2B マーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

最新のリリーススケジュール情報とリリースノートについては、[!DNL Marketo Engage] [リリーススケジュール](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ja)を参照してください。

## ![アイコン](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] は、アイデアの共有、コンテンツの作成、複雑なプロセスの管理、および最高の作業をおこなうための統合作業管理アプリケーションです。

すべての製品の最新情報のまとめについては、[[!DNL Workfront] リリース](https://one.workfront.com/s/product-releases)ページを参照してください。

## ![アイコン](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

新しく公開された Adobe Document Cloud ビデオ、チュートリアル、コース。

### Document Cloud のコースとチュートリアル {#tutorials-doc-cloud}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [Adobe Acrobat for Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html?lang=ja) | ビデオ | Google Drive アプリ内から、時間を節約できる PDF ツールや電子署名サインワークフローに直接アクセスできます。 |

{style=&quot;table-layout:auto&quot;}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud ラーニングとサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Creative Cloud エンタープライズ版 {#creative-cloud}

Creative Cloud エンタープライズ版で新しく公開されたビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 |
| ----------| --------- | --------- | --------- |
| 2021 年 6 月 | [iPad（および iPhone）で Fresco を使ってみる](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html?lang=ja) | ビデオ | 15 分間の実践ワークショップで Adobe Fresco を使用すると、デジタルドローイングとペインティングのまったく新しい世界を見つけることができます。ペイントとテクスチャをベースシェイプに合わせるために、レイヤーとクリッピングマスクを使用する方法について簡単に説明します。 |
| 2021 年 6 月 | [グラフィックフォーマットに関する様々な略語のデコード](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html?lang=ja) | ビデオ | PG、PNG、SVG、GIF、EPS ファイルはすべて、デザインで一般的に使用されます。Web ページで使用されるものあれば、プレゼンテーションや、パブリケーション、クリエイティブプロジェクトで使用されるものもあります。それらの意味や、どちらを選ぶべきかについては、この 15 分間の実践ワークショップでご確認ください。 |

{style=&quot;table-layout:auto&quot;}

最新のチュートリアルについては、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ja)を参照してください。

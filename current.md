---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: f2d6f3489e183db682d62766d13be958cad5692b

---


# Adobe Experience cloudリリースノート — 2020年1月

Adobe Experience Cloud の新機能および修正点です。

>[!NOTE]
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。リリース後に発表された新情報については、更新日と併せて追加公開します。

**リリース日：2020 年 1 月 17 日**

* [Adobe システムステータス](#status)
* [Experience Cloud インターフェイスとコアサービス](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services および Mobile SDK](#mobile)
* [!DNL Analytics](#analytics) (更&#x200B;**新日2020年1月21日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（ソリューションヘルプへのリンク）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（ソリューションヘルプへのリンク）
* [!DNL Advertising Cloud](#adcloud)

ヘルプホームをお探しの場合は、[Adobe Experience Cloud ドキュメント](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)を参照してください。

## Adobe システムステータス {#status}

[!UICONTROL Adobe System Status] は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

**最新情報**

* Adobe ID を使用し、製品、地域およびイベントの環境設定に基づいてイベント通知を購読できます。購読の環境設定をおこなうユーザーは、関連する製品のインシデントとメンテナンスイベントについてのみ、それらが開始、更新、または終了されるとすぐに通知されます。はじめに [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit) をご覧ください。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| プロアクティブなメール通知を購読する | <ul><li>Experience Cloud、Creative Cloud、Document Cloud、Adobe Experience Platform、および Adobe Servicesのサポート</li><li>地域とイベントタイプの環境設定のサポート</li></ul> |
| 通知設定の管理 | <ul><li>いつでも通知設定を編集および保存できる</li><li>いつでも通知を登録解除できる</li></ul> |
| パーソナライズされた迅速な電子メール配信の実現 | <ul><li>イベントが作成、更新、およびクローズされるとすぐにイベント通知が送信される</li><li>設定した環境設定と一致する関連イベント通知のみを受信する</li><li>アカウントの環境設定で設定された言語に基づいて、ローカライズされた通知を受信する</li></ul> |
| 製品内通知をパーソナライズする | <ul><li>通知設定および製品の資格と一致するイベントがお知らせパネルに表示されます</li></ul> |

## Experience Cloud インターフェイスとコアサービス{#ecloud}

Experience Cloud インターフェイスの新機能および修正点です。管理およびコアサービス（顧客属性、オーディエンス、トリガー、cookie など）が含まれます。

### 統合製品ドメイン

アドビでは、すべての Adobe Experience Cloud アプリケーションでエクスペリエンスを統合し、向上させるために、ドメインとインターフェイスのヘッダーを更新しています。これらの機能強化は、小規模ではあっても、重要な方法でエクスペリエンスをシンプルにするように設計されています。これらの機能強化では、現在のワークフローは変更されません。

更新内容は次のとおりです。

* 新しいソリューションURL: `experience.adobe.com/<application name>`:
   * 最終的に、すべての製品でこのURLパターンが採用されます。 1 ヶ月間にわたって効果的な新しい URL を探します。
   * ブラウザーのサポート：サポートされるブラウ [!DNL Microsoft Edge]ザーには、、、、、、およ [!DNL Google Chrome]び(最 [!DNL Firefox]新バージョン) [!DNL Safari][!DNL Opera] が含まれます。 **** 注意：Experience cloudインターフェイスはこれらのブラウザーをサポートしていますが、個々のソリューションがすべてのブラウザーをサポートしているわけではありません。 (例えば、 [Analyticsはサポートし](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) ません [!DNL Opera]。 [Targetはサポートしていま](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html)[!DNL Safari]せん。)
   * (の[!DNL Safari] み)ドメインの変更によって、でCookieの問題が発生する場合がありま [!DNL Safari]す。 Unchecking _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* 組織間または別のアプリケーション間の切り替えが容易になりました。
* 製品ヘルプの改善：ヘルプ検索にコミュニティフォーラムやビデオコンテンツの結果も含められるよう、[!UICONTROL Experience League] は製品に統合されています。この変更により、より多くのコンテンツへのアクセスが簡素化され、Experience Cloud を最大限に活用できるようになります。さらに、**[!UICONTROL ヘルプ]**／**[!UICONTROL &#x200B;フィードバック]**をクリックして問題を報告したり、アドビとアイデアを共有したりします。
* 通知の改善：[!UICONTROL 通知]ドロップダウンメニューに 2 つのタブが追加されました。1 つは独自の製品通知用、もう 1 つはグローバルな製品のお知らせ用です。

**メモ：**[!UICONTROL フィード]ページは、2020 年 1 月に廃止されます。製品内の廃止のお知らせを探してください。

製品ドキュメントについては、[Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) を参照してください。

### Experience Cloud の cookie

アドビは、Chrome 80（2020 年 2 月にリリース予定）で Chrome が予定している変更に備えて、cookie に関する `same-site` の設定を調整しています。

ファーストパーティのデータ収集に CNAME を使用し、複数のドメイン（わかりやすいサードパーティドメイン）でその CNAME を使用し、Experience Cloud（訪問者）IDサービスを使用していない限り、変更をおこなう必要はありません。Chrome 80 リリースでは、Chrome は Analytics 訪問者ID cookie に SameSite 値 `Lax,` を自動的に付与し、他のドメインでの使用を禁止します。ドメイン間で CNAME を引き続き使用する場合は、アドビカスタマーケアに連絡し、CNAME の SameSite 値を `None.` に変更してもらう必要があります。

Experience Cloud ID サービスを使用しているかどうかに関係なく、ドメインごとに個別の CNAME を使用することをお勧めします。

[詳細情報…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、ID サービスおよびセキュリティ速報のリリースノートです。

* [Experience Platform リリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html)（すべてのアドビ製品）

### Experience Platform Launch {#launch}

リリースノートおよび製品ドキュメントについては、[Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) を参照してください。

## Mobile Services および Mobile SDK{#mobile}

2020 年 1 月 17 日：バージョン 4.18.0

* 獲得 - [!DNL Google Play] によるリファラー API のインストールをサポートするため、新しい API `Analytics.processGooglePlayInstallReferrerUrl(final String url)` が追加されました。

リファラー API のインストールについて詳しくは、「[まだ InstallBroadcast を使用している場合は、2020 年 3 月 1 日までに再生リファラー API に切り替えてください](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html)」を参照してください。

## [!DNL Analytics] {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)     （更新日2020年1月21日）
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

製品ドキュメントについては、[Adobe Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

### Adobe Analytics の新機能、機能強化および修正点 {#aa-features}

| 機能 | 説明 |
| -----------| ---------- |
| Analysis Workspace — ユーザーインターフェイスの改善 | 2020年1月16日に、Analysis Workspaceは、数か月にわたるユーザーインターフェイスの改善を開始します。 これらの変更の目的は、アプリをユーザーに対してよりアクセスしやすくし、Adobe Experience cloud全体でより一貫したエクスペリエンスを提供することです。 |
| Analysis Workspace - フリーフォームテーブルビルダー | Table Builder を有効にすれば、多くのディメンション、分類、指標およびセグメントをドラッグ＆ドロップして、より複雑なビジネスの質問に回答するテーブルを作成できます。データはすぐには更新されません。代わりに、「**[!UICONTROL ビルド]**」をクリックした後に更新がおこなわれ、どのテーブルを作成したいかがわかると時間を節約することができます。さらに、この機能では次のことが可能です。<ul><li>**プレビュー**：時間をかけて実際のデータをレンダリングする前に表形式でプレビューできます。</li><li>**柔軟な行と分類の設定**：各ディメンション行に対して行と分類レベルを設定できます。以前は、Workspace で適用されたデフォルトは、データが返されるまで変更できませんでした。</li><li>**位置で分類**：ディメンション行を、_特定の項目_&#x200B;ではなく常に&#x200B;_位置で分類_（デフォルト）するように設定できます。</li><li>**手動の静的行の並べ替え**：静的な行を手動で並べ替え、必要に応じて表示できます。以前は、静的な行は指標の列またはアルファベット順でのみ並べ替えることができました。</li></ul>[詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/freeform-table.html). |
| クロスデバイス分析（CDA）の新しい[!UICONTROL 識別状態]ディメンション。 | CDA 仮想レポートスイートに、[!UICONTROL 識別状態]という新しいディメンションを追加します。ディメンションには、「_識別済み_」と「_未識別_」の 2 つの値があります「_識別済み_」は、その人物がデバイスグラフで識別されたことを意味します。「_未識別_」は、その人物がデバイスグラフで識別されていないことを意味します。<br>つまり、CDA ユーザーは仮想レポートスイート内のユーザーのうちデバイスグラフで把握できる人数を示す[!UICONTROL デバイスグラフの範囲]などの計算指標を作成できます。この指標は、CDA 圧縮率のトラブルシューティングに役立ちます。特定されたユーザーが少ない場合は、ステッチのレベルが低くなります。 |
| Data Warehouse API での VRS のサポート | Data Warehouse API から仮想レポートスイートを使用できるようになりました。以前は、Data Warehouse UI からしか使用できませんでした。Data Warehouse API を使用する場合、仮想レポートスイートを表示およびクエリできるようになりました（仮想レポートスイートに適用されたセグメントが Data Warehouse と互換性がある場合にのみ）。 |
| プライバシーサービス API：CCPA | カリフォルニア州消費者プライバシー法（CCPA）は、米国カリフォルニア州の居住者のプライバシー権と消費者保護を厳格化します。この法律は、2020 年 1 月 1 日に施行されます。<br><br/>CCPA は、カリフォルニア州の居住者に新しいプライバシー権を提供します。これには、自身の個人データにアクセスして削除する権利、自身の個人データが（誰に）販売または公開されているかどうかを知る権利、および自身の個人データの販売を拒否する権利が含まれます。<br><br/>プライバシーサービスは個人データの販売のオプトアウトに対するリクエストをサポートします。<br><br/>プライバシーサービス（旧 GDPR サービス）は、以前の機能をすべて保持し、CCPA をサポートするよう拡張されました。<br/><br/>[Analytics の CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[プライバシーの概要](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### 修正点

* エジプトの電話番号にアラート通知が送られない問題を修正しました。（AN-197079）
* [!DNL DFA Data Connector] に関する複数の問題を修正しまし た。（AN-193281、AN-193075、AN-193484、AN-193737）
* [!UICONTROL Reports &amp; Analytics]：製品コンバージョンファネルレポートが途切れ、数字がわかりにくい問題を修正しました。（AN-186901）
* 新しい分類アーキテクチャを使用して、レポートスイートに基づいた Workspace プロジェクトで、ユーザーがレポートスイートを切り替えられない問題を修正しました。（AN-199076）
* [!UICONTROL 計算指標]の[!UICONTROL 累積]関数が正しく機能しない問題を修正しました。（AN-184257）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 新しい Adobe Analytics ドメイン | 2019 年 12 月 19 日 | 2020 年 1 月 17 日に、Adobe Analytics は新しいドメインへの移行を開始します。`https://experience.adobe.com/analytics.`<br>**メモ&#x200B;**：この変更は、Adobe ID または Enterprise ID を使用して Analytics にアクセスするすべてのユーザーに適用されます。<ul><li>ドメインの変更により、Safari で Analytics を読み込む際に cookie の問題が発生する可能性があります。Safari のプライバシー設定で「_クロスサイト追跡を禁止する_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Analytics がこの新しい Adobe Experience Cloud ドメインで機能するようになります。この問題が影響するのは Safari ユーザーのみなので、ユーザーは問題なく他のブラウザーを使用できます。</li><li>ドメインの変更により、[ある特定のケースにおいて](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)、一部の顧客に対して [!UICONTROL Activity Map] が機能しなくなる場合があります。</li></ul> |
| 提供終了 - Analytics レガシー API | 2020 年 1 月 10 日 | 2020 年 11 月に、以下の Analytics レガシー API サービスが提供終了となり、シャットダウンされます。これらのサービスを使用して構築された現在の統合は機能しなくなります。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問に対する回答と進め方に関するガイダンスを提供するために、[従来の API EOL の FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| **[!UICONTROL アーカイブを表示]** オプションのサポート終了 | 2019 年 10 月 31 日 | 2020 年 1 月に、ダッシュボードマネージャー（**[!UICONTROL コンポーネント／ダッシュボード]**）の **[!UICONTROL &#x200B;アーカイブを表示]** オプションのサービスを終了することをお知らせします。 |
| **[!UICONTROL IP ログイン制限の適用]** オプションのサポート終了 | 2019 年 10 月 31 日 | 2020 年 1 月に、**[!UICONTROL 管理者／会社設定／セキュリティ]** メニューの IP ログインのホワイトリストへの追加（**[!UICONTROL  IP ログイン制限の実施]**）機能のサポートを終了することをお知らせします。 |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Analytics ユーザーの `createDate` フィールドに関する変更予定 | 2019 年 8 月 31 日 | 2019 年 10 月または 2019 年 11 月に、Analytics ユーザーの `createDate` フィールドが米国太平洋時刻から、タイムゾーン情報を反映した正しい形式に更新されました。（AN-183468） |

### [!DNL AppMeasurement] {#appm}

「[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)」を参照してください。

## Audience Manager {#aam}

Audience Manager に追加された修正点および機能です。

### Audience Manager の新機能、拡張機能および修正点です {#aam-features}

| 機能 | 説明 |
| -----------| ---------- |
| [カリフォルニア消費者プライバシー法（CCPA）のサポートとプライバシーに関するドキュメントの見直し](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | 2020 年 1 月 1 日に施行された[カリフォルニア消費者プライバシー法（CCPA）](https://www.caprivacy.org/about)は、カリフォルニア州在住者に対し、個人情報に関する新たな権利を提供し、カリフォルニア州で事業を行う特定の事業者に対してデータ保護責任を課します。<br><br>Audience Managerは、データアクセスや削除のリクエストをおこなう [Adobe Experience Platform プライバシーサービス](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html)などのプライバシーツールを使用して、ユーザーがプライバシー規制における義務を遵守できるよう支援します。<br><br>現在の[オプトアウト管理](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests)プロセスを更新し、宣言済み ID（CRM ID など）のオプトアウトを含めるようにしました。宣言済み ID によるオプトアウトの場合、宣言済み ID と最後にリンクされたデバイスは、Audience Manager のデータ収集から除外されます。また、オプトアウトリクエストでは、この機能（バッチとリアルタイムの両方）をサポートする[宛先パートナー](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation)に対して、セグメント解除リクエストも送信するようになりました。<br><br> さらに、[データセキュリティ](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html)、[データプライバシー](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html)、および[データガバナンス](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html)に関するドキュメントを作り直し、前述の規則に準拠するために必要な情報を見つけやすくしました。 |

### 修正点および改善点 {#aam-fixes-and-improvements}

* 「[!UICONTROL 宛先を作成]」ワークフローで、「**[!UICONTROL 統合プラットフォーム]**」を「[!UICONTROL カテゴリ]」として選択すると、「[!UICONTROL 基本情報]」セクションが表示されなくなり、ワークフローを完了できなくなる問題を修正しました。（AAM-52397、AAM-52414）
* Apple Safari および Mozilla Firefox ブラウザーで、宛先の[!UICONTROL 作成／編集]ページが読み込まれないバグを修正しました。（AAM-51784）

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品メンテナンス

* **AEM 6.5.3.0**
AEM 6.5、Service Pack 3.0 （2019 年 12 月 13 日にリリースされた 6.5.3.0 ）は重要なアップデートであり、2019 年 4 月の AEM 6.5 の一般リリース以降にリリースされたお客様向けの主要な修正が含まれています。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4 Service Pack 7.0（2019 年 12 月 13 日にリリースされた 6.4.7.0）は重要なアップデートであり、2018 年 4 月の AEM 6.4 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3 Service Pack 3 Cumulative Fix Pack 7（2019 年 12 月 12 日にリリースされた 6.3.3.7）は重要なアップデートであり、2017 年 4 月の AEM 6.3 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。
   * [リリースノート](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   AEM Desktop App 2.0.1.1 では、Okta を使用したシングルサインオンの更新と、一時ファイルの場所を環境設定で指定する機能が提供されています。このリリースでは、Desktop App 2.x に対する AEM 6.3.x のサポートが廃止されました。
   * [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1 は AEM 6.3.x のサポートを終了します**

   AEM 6.3.x のサポートは、2019 年 4 月以降、Adobe Asset Link で非推奨となりました。2020 年 1 月 13 日現在、Adobe Asset Link 1.1 は、AEM 6.3.x のサポートを削除しています。
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### 製品リリース

* **新規：クラウドサービスとしてのAEM**

   [Adobe Experience Manager](https://www.adobe.com/marketing/experience-manager.html) (AEM)がクラウドサービスとして利用できるようになりました。

   * [はじめに](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/overview/introduction.html)
   * [リリース情報](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
   * [ドキュメント](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)

* **自動フォーム変換サービス**

   PDF フォームを美しいモバイル対応 HTML フォームに自動変換するサービスである Automated Forms Conversion Service が、2019 年 12 月 13 日に一般向けにリリースされます。

   * [はじめに](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [サービスの設定](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [PDF フォームからアダプティブフォームへの変換](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### セルフサービス

* **3D アセットのプレビュー**

   AEM 6.5 は、オーサリングプロセスの一環として、3D アセットのアップロード、配信、およびインタラクティブプレビューをサポートします。インタラクティブ 3D ビューアは、AEM のアセットの詳細ページから利用できます。このビューアには、3D アセットをオービット、ズームおよびパンできるインタラクティブなカメラコントロールのコレクションが含まれます。詳しくは、[3D アセットのプレビュー](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)を参照してください。

* **コアコンポーネント**

   多数の修正が加えられたコンポーネント 2.8.0 が、[オーサリングドキュメント](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html)、[開発者の詳細、および GitHub で利用可能な開発者の詳細やプロジェクトのダウンロード](https://github.com/adobe/aem-core-wcm-components)と共にリリースされました。

* **AEM プロジェクトアーキタイプ**

   [AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) の [ui.frontend module](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html) は、AEM プロジェクトのフロントエンド開発をより簡単にする便利で柔軟なツールです。

### その他のリソース

* [クラウドサービスとしてのAEM](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### Campaign Classic 19.2

| 機能 | 説明 |
| ------------- | ----------- |
| カリフォルニア消費者プライバシー法（CCPA） | CCPA は 2020 年 1 月 1 日よりカリフォルニア州にて新しく施行されるプライバシー保護法律で、データ保護要件を現代の状況に調和し、近代化することを目的としています。CCPA は、カリフォルニアに居住しているデータ主体のデータを保有している Adobe Campaign の顧客に適用されます。<br>Adobe Campaign は、既に利用可能なプライバシー機能（同意管理、データ保持設定、ユーザーの役割を含む）に加えて、CCPA に備えるのに役立ちます。 <ul><li>_アクセス権_&#x200B;と&#x200B;_削除権_：GDPR 用に追加された機能を活用しています。[詳細情報](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>顧客が個人情報の販売をオプトアウトしたかどうかを追跡できます。この場合は、[!UICONTROL プロファイル]テーブルを拡張して、**[!UICONTROL CCPA のオプトアウト]**フィールドを追加する必要があります。[詳細情報](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)を参照してください。 |
| ワークフローのライブ監視 | 事前定義されたビューを使用して、インスタンス上のすべてのワークフローの実行ステータスを監視できるようになりました。<br>詳しくは、「[ステータスに従ったワークフローのフィルタリング](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status)」を参照してください。 |
| AMP を使用したインタラクティブコンテンツ | Adobe Campaign では、新しいインタラクティブな [AMP for Email](https://amp.dev/about/email/) を試すことができます。これにより、マーケターは、メッセージ内に AMP コンポーネントを含め、メッセージ自体で直接操作できるリッチで動的なインタラクティブなコンテンツを使用して、電子メールエクスペリエンスを強化できます。<br>この機能はパブリックベータ版としてリリースされています。<br>詳しくは、[詳細なドキュメント](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html)と[チュートリアルビデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)を参照してください。 |
| セキュアな SMS メッセージング（TLS） | 拡張された汎用 SMPP コネクタで、セキュアな SMS がサポートされるようになりました。これにより、プロバイダーに対する暗号化された接続が可能になります。<br> **警告**：この機能を使用するには、すべてのサーバーで最新の証明書が必要です。無効な証明書、失効した証明書、または期限切れの証明書を使用すると、SMS 送信機能全体に影響を与えるエラーが発生します。<br>詳しくは、[詳細ドキュメント](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)を参照してください。 |

修正点と機能改善については、[Adobe Campaign Classic リリースノート](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)を参照してください。

### Campaign Standard 19.4

| 機能 | 説明 |
| ------------- | ----------- |
| カリフォルニア消費者プライバシー法（CCPA） | CCPA は 2020 年 1 月 1 日よりカリフォルニア州にて新しく施行されるプライバシー保護法律で、データ保護要件を現代の状況に調和し、近代化することを目的としています。CCPA は、カリフォルニアに居住しているデータ主体のデータを保有している Adobe Campaign の顧客に適用されます。<br>Adobe Campaign には既にプライバシー機能（同意管理、データ保持設定、ユーザーの役割など）が用意されていますが、これを機会にお客様自身が CCPA に対応できるようにする追加機能を導入しました。 <ul><li> アクセス権と削除権：GDPR 用に追加された機能を活用しています。[詳細情報](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> プライバシーリクエストを作成する際のプライバシーコアサービスに、規制のタイプ（GDPR または CCPA）が追加されました。このメソッドは、すべてのアクセスリクエストと削除リクエストに使用する必要があります。アクセスおよび削除のリクエストに対する Campaign API とインターフェイスの使用は廃止されました。[廃止および削除された機能の記事](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)を参照してください。 </li><li> Adobe Campaign ユーザーが個人情報の販売をオプトアウトしたかどうかを追跡できるように、プロファイルリソースに「**CCPAオプトアウト**」フィールドが追加されました。[詳細情報](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)を参照してください。 |
| Microsoft Dynamics 365 との統合（GA） | Adobe Campaign Standard と Microsoft Dynamics 365 の統合が可能になりました。Dynamics 365 から Campaign に連絡先とカスタムエンティティレコードを転送し、Campaign から Dynamics 365 に電子メールイベントデータを戻して、販売／マーケティングの連携を向上させることができます。<br>[詳細なドキュメント](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html)を参照し、この統合を設定して[ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)を確認します。 |

修正点と機能改善については、[Adobe Campaign Standard リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)を参照してください。

### Adobe Campaign コントロールパネル

管理者ユーザーがサブドメインを委任し、コントロールパネルから SSL 証明書を更新する新しい機能が追加されました。

詳しくは、次のページを参照してください。

* 新しいサブドメインの設定 - [詳細情報](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* サブドメインの SSL 証明書の更新 — [詳細情報](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>これらの機能は、1 月末までにベータ版で提供され、予告なく頻繁に更新されたり変更されたりする場合があります。

### その他のリソース

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)- [リリース計画](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

2020 年 1 月 12 日リリース用に更新

| 表示 | 機能 |
|------|---------|
| コンバージョンの追跡 | Advertising Cloud のすべての cookie が更新され、2 月 4 日にリリースされる Google Chrome 80 の新しい cookie 制御要件を満たすようになりました。この変更は、訪問者指標に影響を与えることなく、既存の cookie を使用してアドビのサーバーから実装されました。広告主の更新は不要です。 |
| インサイト／アラートベータ、検索／キャンペーン | （検索アカウントのベータ版のみ）新しいアラートベータ版では、指定期間内に検索キャンペーン、広告グループ、キーワードまたは広告が特定の条件（パフォーマンス指標など）を満たすタイミングを識別し、アラートを生成するアラートテンプレートを作成できます。アラートは 1 人の広告主で使用できます。 |
| レポート | 商品リスト広告のデータが、ラベル分類、ラベル値、入札ルール、制約の各レポートに含まれるようになりました。 |

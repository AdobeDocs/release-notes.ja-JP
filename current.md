---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: e49bdb89cd3cf434a4932d1669d6f3a2df973769

---


# 先行アクセス — Adobe Experience cloudリリースノート — 2020年1月

Adobe Experience Cloud の新機能および修正点です。

>[!IMPORTANT]
>このページには、リリース前のコンテンツが含まれ、各製品のリリース前に変更される場合があります。

>[!NOTE]
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。リリース後に発表された新情報については、更新日と併せて追加公開します。

**リリース日：2020年1月17日**

* [アドビシステムステータス](#status)
* [Experience cloudインターフェイスとコアサービス](#ecloud)
* [Experience Platform](#platform)
* [Mobile ServicesとMobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（ソリューションヘルプへのリンク）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（ソリューションヘルプへのリンク）
* [!DNL Advertising Cloud](#adcloud)

ヘルプホームをお探しの場合は、[Adobe Experience Cloud ドキュメント](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)を参照してください。

## Adobe System Status {#status}

[!UICONTROL Adobe System Statusは] 、Adobeクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。 status.adobe.comで [確認します](https://status.adobe.com/)。

**最新情報**

* Adobe IDを使用して、製品、地域およびイベントの環境設定に基づいてイベント通知を購読できます。 購読の環境設定を行うユーザーは、製品のインシデントとメンテナンスイベントが開かれた、更新された、または閉じられたときに、関連する製品のイベントとメンテナンスイベントのみに通知されます。 はじめにstatus.adobe.com/subscriptionsを参照し [てください](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| プロアクティブな電子メール通知の購読 | <ul><li>Experience Cloud、Creative Cloud、Document Cloud、Adobe Experience PlatformおよびAdobe Servicesのサポート</li><li>地域とイベントタイプの環境設定のサポート</li></ul> |
| 通知設定の管理 | <ul><li>いつでも通知設定を編集および保存できる</li><li>いつでも通知を登録解除できる</li></ul> |
| パーソナライズされた迅速な電子メール配信 | <ul><li>イベント通知は、イベントが開かれた、更新された、または閉じられたときにすぐに送信されます</li><li>設定した環境設定と一致する関連イベント通知のみを受信する</li><li>アカウントの環境設定で設定した言語に基づいてローカライズされた通知を受信する</li></ul> |
| 製品内通知のパーソナライズ | <ul><li>通知設定と製品の権利に一致するイベントがお知らせパネルに表示されます</li></ul> |

## Experience Cloud interface and core services {#ecloud}

Experience cloudインターフェイスの新機能および修正点です。管理およびコアサービス（顧客属性、オーディエンス、トリガー、cookieなど）が含まれます。

### 統合製品ドメイン

アドビでは、すべてのExperience cloudアプリケーションでエクスペリエンスを統合し、向上させるために、ドメインとインターフェイスのヘッダーを更新しています。 これらの機能強化は、小規模で重要な方法でエクスペリエンスをシンプルにするように設計されています。 これらの機能強化によって、現在のワークフローは変更されません。

更新内容は次のとおりです。

* 新しいソリューションURL: `experience.adobe.com/<application name>`:
   * 最終的に、すべての製品でこのURLパターンが採用されます。 月を通じて有効になる新しいURLを探します。
   * ブラウザーのサポート：サポートされるブラウ [!DNL Microsoft Edge]ザーには、、、、、、およ [!DNL Google Chrome]び(最 [!DNL Firefox]新バージョン) [!DNL Safari][!DNL Opera] が含まれます。 **** 注意：Experience cloudインターフェイスはこれらのブラウザーをサポートしていますが、個々のソリューションがすべてのブラウザーをサポートしているわけではありません。 (例えば、 [Analyticsはサポートし](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) ません [!DNL Opera]。 [Targetはサポートしていま](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html)[!DNL Safari]せん。)
   * (の[!DNL Safari] み)ドメインの変更によって、でCookieの問題が発生する場合がありま [!DNL Safari]す。 Unchecking _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* 組織間または別のアプリケーション間の切り替えが容易になりました。
* 製品ヘルプの改善：Experience Leagueは  、コミュニティフォーラムやビデオコンテンツの結果も含めるために、製品に統合されています。 この変更により、より多くのコンテンツへのアクセスが簡素化され、Experience cloudを最大限に活用できるようになります。 さらに、ヘルプ/フ **[!UICONTROL ィードバ]**ック**[!UICONTROL (Feedback]** )をクリックして、問題を報告したり、アドビとアイデアを共有したりします。
* 通知の改善：「通知  」ドロップダウンメニューに2つのタブが追加され、1つは独自の製品通知用、もう1つはグローバル製品のお知らせ用です。

**** 注意：フィー [!UICONTROL ド] ページは、2020年1月に廃止されます。 製品内の廃止のお知らせを探してください。

製品ドキュメントについては、[Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) を参照してください。

### Experience Cloud の cookie

アドビは、Chrome 80で `same-site` Chromeが行う変更に備えて、Chromeのcookieの設定を調整しています（2020年2月にリリース予定）。

ファーストパーティのデータ収集にCNAMEを使用し、複数のドメイン（わかりやすいサードパーティドメイン）でそのCNAMEを使用し、Experience Cloud（訪問者）IDサービスを使用しない限り、変更を行う必要はありません。 Chrome 80リリースでは、Chromeは自動的にAnalytics訪問者ID cookieにSameSite値を付与し、他のドメインで `Lax,` の使用を禁止します。 ドメイン間でCNAMEを引き続き使用する場合は、アドビカスタマーケアに連絡し、CNAMEのSameSite値を `None.`

Experience Cloud IDサービスを使用しているかどうかに関係なく、ドメインごとに個別のCNAMEを使用することをお勧めします。

[詳細情報…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、ID サービスおよびセキュリティ速報のリリースノートです。

* [Experience Platform リリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html)（すべてのアドビ製品）

### Experience Platform Launch {#launch}

リリースノートおよび製品ドキュメントについては、[Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) を参照してください。

## Mobile Services and Mobile SDKs {#mobile}

2020年1月17日：バージョン4.18.0

* 獲得 — リファラーAPIのインストールをサポートす `Analytics.processGooglePlayInstallReferrerUrl(final String url)`る新しいAPIが追 [!DNL Google Play] 加されました。

リファラーAPIのインストールについて詳しくは、「InstallBroadcastを使用し [続けますか？ 2020年3月1日までにリファラーを再生APIに切り替えます](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

製品ドキュメントについては、[Adobe Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

### Adobe Analytics の新機能、機能強化および修正点 {#aa-features}

| 機能 | 説明 |
| -----------| ---------- | 
| Analysis Workspace — フリーフォームテーブルビルダー | 表ビルダーを有効にすると、多くのディメンション、分類、指標およびセグメントをドラッグ&amp;ドロップして、より複雑なビジネスの質問に答える表を作成できます。 データはすぐには更新されません。 代わりに、[ビルド]をクリックした後 **[!UICONTROL に更新が行われ]**、作成するテーブルがわかったら時間を節約できます。 さらに、この機能には次の機能があります。<ul><li>**プレビュー**:時間を費やす前に表の形式をプレビューして、実際のデータをレンダリングすることができます。</li><li>**柔軟な行と分類の設定**:各ディメンション行に対して行と分類レベルを設定できます。 以前は、Workspaceで適用されたデフォルトは、データが返されるまで変更できませんでした。</li><li>**位置で分類**:ディメンション行を、特定の項目ではなく _常に位置で分類_ (デ _フォルト)するように設定できます_ 。</li><li>**手動の静的行順序**:静的な行を手動で並べ替えて、必要に応じて表示できます。 以前は、静的な行は指標の列またはアルファベット順でのみ並べ替えることができました。</li></ul>関連ドキュメントは、この機能が1月後半にリリースされる際に公開されます。 |
| Cross- [!UICONTROL Device] Analytics(CDA)の新しいIdentified Stateディメンション | CDA仮想レポートスイートに、 [!UICONTROL Identified State] （識別状態）という新しいディメンションを追加します。 ディメンションには、 _Identified_ と _Unidentifiedの2つの値があります_。 _識別とは_ 、その人物がデバイスグラフで識別されたことを意味します。 _「未識別_ 」は、その人がデバイスグラフで識別されていないことを意味します。<br>つまり、CDAユーザーは [!UICONTROL Device Graph Coverage]（デバイスグラフ）などの計算指標を作成でき、仮想レポートスイート内の人数がデバイスグラフで知られていることを示します。 この指標は、CDA圧縮率のトラブルシューティングに役立ちます。 識別される人が少ない場合は、ステッチのレベルが低くなります。 |
| Data Warehouse APIでのVRSのサポート | 仮想レポートスイートがData Warehouse APIを介して使用できるようになりました。 以前は、Data Warehouse UIでのみ使用できました。 Data Warehouse APIを使用する場合、仮想レポートスイートの表示とクエリが可能になりましたが、仮想レポートスイートに適用されたセグメントがData Warehouseと互換性がある場合に限り表示とクエリが可能になりました。 |
| プライバシーサービス API：CCPA | カリフォルニア州消費者プライバシー法（CCPA）は、米国カリフォルニア州の居住者のプライバシー権と消費者保護を厳格化します。この法律は、平成十四年一月一日から施行する。<br><br/>CCPA は、カリフォルニア州の居住者に新しいプライバシー権を提供します。これには、自身の個人データにアクセスして削除する権利、自身の個人データが（誰に）販売または公開されているかどうかを知る権利、および自身の個人データの販売を拒否する権利が含まれます。<br><br/>プライバシーサービスは、個人データの販売を停止する要求をサポートしています。<br><br/>Privacy Serviceは、以前はGDPRサービスであり、以前のすべての機能を保持しています。現在は、CCPAをサポートするように拡張されています。<br/><br/>[Analytics の CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[プライバシーの概要](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### 修正点

* エジプトの電話番号にアラート通知が配信されない問題を修正しました。 （AN-197079）
* に関する複数の問題を修正しまし [!DNL DFA Data Connector]た。 （AN-193281、AN-193075、AN-193484、AN-193737）
* [!UICONTROL Reports &amp; Analytics]:製品コンバージョンファネルレポートで、数が不明確になって表示される問題を修正しました。 （AN-186901）
* 新しい分類アーキテクチャを使用したレポートスイートに基づくWorkspaceプロジェクトのレポートスイートをユーザーが切り替えられない問題を修正しました。 （AN-199076）
* 計算指標の累積関数が正し [!UICONTROL く機能し][!UICONTROL ない問題を修正しました] 。 （AN-184257）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 新しい Adobe Analytics ドメイン | 2019 年 12 月 19 日 | 2020年1月16日に、Adobe Analyticsは新しいドメインへの移行を開始します。注 `https://experience.adobe.com/analytics.`<br>**意&#x200B;**:この変更は、Adobe IDまたはEnterprise IDを使用してAnalyticsにアクセスするすべてのユーザーに適用されます。<ul><li>ドメインの変更により、SafariでAnalyticsを読み込む際にcookieの問題が発生する場合があります。 Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. Safariユーザーのみに影響するので、他のブラウザーも問題なく使用できます。</li><li>ドメインの変更により、特定の [!UICONTROL 場合に] 、一部の顧客に対してActivity mapが機能しなくな [る場合があります](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)。</li></ul> |
| 提供終了 — AnalyticsレガシーAPI | 2020 年 1 月 10 日 | 2020年11月に、以下のAnalyticsレガシーAPIサービスが提供終了となり、シャットダウンされます。 これらのサービスを使用して構築された現在の統合は動作を停止します。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP解析API</li><li>従来のOAuth認証（OAuthおよびJWT）</li></ul>ご質問に対する回答と進 [め方に関するガイダンスを提供するために、従来のAPI EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) （英語）を用意しています。 これらのサービスを使用するAPI統合は、 [1.4 Analytics REST APIまたは](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 2.0 Analytics APIに [移行できます](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。 従来のOAuthアカウントは、 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics統合アカウントに移行できます。このアカウントは、1.4 Analytics APIと2.0 Analytics APIの両方にアクセスするために使用できます。 |
| **[!UICONTROL アーカイブを表示]** オプションのサポート終了 | 2019 年 10 月 31 日 | 2020 年 1 月に、ダッシュボードマネージャー（**[!UICONTROL コンポーネント／ダッシュボード]**）の **[!UICONTROL &#x200B;アーカイブを表示]** オプションのサービスを終了することをお知らせします。 |
| **[!UICONTROL IP ログイン制限の適用]** オプションのサポート終了 | 2019 年 10 月 31 日 | 2020 年 1 月に、**[!UICONTROL 管理者／会社設定／セキュリティ]** メニューの IP ログインのホワイトリストへの追加（**[!UICONTROL  IP ログイン制限の実施]**）機能のサポートを終了することをお知らせします。 |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Analytics ユーザーの `createDate` フィールドに関する変更予定 | 2019 年 8 月 31 日 | In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.（AN-183468） |

### [!DNL AppMeasurement] {#appm}

「[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)」を参照してください。

## Audience Manager {#aam}

Audience Managerに追加された修正点および機能です。

### Audience Manager の新機能、拡張機能および修正点です {#aam-features}

| 機能 | 説明 |
| -----------| ---------- |
| [カリフォルニア消費者プライバシー法(CCPA)のサポートとプライバシーに関するドキュメントの見直し](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | 2020年1 [月1日に施行されたカリフォルニア消費者プライバシー法(CCPA)は](https://www.caprivacy.org/about)、カリフォルニア州在住者に対し、個人情報に関する新たな権利を提供し、カリフォルニア州で事業を行う特定の事業者に対してデータ保護責任を課します。 <br><br> Audience Managerは、 [Adobe Experience Platformプライバシーサービスなどのプライバシーツールを使用して、プライバシー規制に基づく義務を遵守し](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) 、データアクセスや削除のリクエストを行うのに役立ちます。 <br><br> 現在のオプトアウト [管理プロセスを更新し](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) 、宣言済みID（CRM IDなど）のオプトアウトを含めるようにしました。 宣言済みIDによるオプトアウトの場合、宣言済みIDと最後にリンクされたデバイスは、Audience Managerのデータ収集から除外されます。 また、オプトアウトリクエストは、この機能をサポートする宛先パ [ートナー](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) （バッチとリアルタイムの両方）に対して、セグメント解除リクエストを送信するようになりました。 <br><br> さらに、データセキュリティ、データプライバシー [、およびデータガバナンスに関するドキュメントを再設計し、](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html)[](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html)[](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) 前述の規則に準拠するために必要な情報を見つけやすくしました。 |

### 修正点および改善点 {#aam-fixes-and-improvements}

* 「宛先を作成」ワークフローで、「統合プラットフォーム  」を「カテゴリ」として選択すると **[!UICONTROL 、「基本情報」セクションが表示されなく]**なり、ワークフローを完了できなくなる問題を修正しました。 （AAM-52397、AAM-52414）
* We fixed a bug where the [!UICONTROL Create/edit] destinations page would not load in the Apple Safari and Mozilla Firefox browsers. （AAM-51784）

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品メンテナンス

* **AEM 6.5.3.0** AEM 6.5、Service Pack 3.0（2019年12月12日リリース）は、AEM 6.5のGA（2019年4月）以降にリリースされた主なお客様向け修正を含む重要なアップデートです。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4、Service Pack 7.0（2019年12月12日リリースの6.4.7.0）は、2018年4月のAEM 6.4の一般リリース(GA)以降にリリースされた主なお客様向け修正を含む重要なアップデートです。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3、Service Pack 3、Cumulative Fix Pack 7（2019年12月12日リリース）は、AEM 6.3のGA（2017年4月）以降にリリースされた主なお客様向け修正を含む重要なアップデートです。
   * [リリースノート](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   AEM Desktop App 2.0.1.1では、Oktaを使用したシングルサインオンの更新と、一時ファイルの場所を環境設定で指定する機能が提供されています。 AEM 6.3.xのサポートは、このリリースではDesktop App 2.xで廃止されました。
   * [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1はAEM 6.3.xのサポートを終了します。**

   AEM 6.3.xのサポートは、2019年4月以降、Adobe Asset linkで非推奨となりました。 Adobe Asset Link 1.1は、2020年1月13日現在、AEM 6.3.xのサポートを削除しました。
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### 製品リリース

* **新規：クラウドサービスとしてのAEM**

   [Adobe Experience Manager](https://www.adobe.com/marketing/experience-manager.html) (AEM)がクラウドサービスとして利用できるようになりました。

   * [はじめに](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/overview/introduction.html)
   * [リリース情報](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
   * [ドキュメント](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)

* **自動フォーム変換サービス**

   PDFフォームを美しいモバイル対応HTMLフォームに自動変換するサービスであるAutomated Forms Conversion Serviceが、2019年12月12日に一般消費で使用できるようになりました。

   * [はじめに](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [サービスの設定](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [PDFフォームからアダプティブフォームへの変換](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### セルフサービス

* **3Dアセットのプレビュー**

   AEM 6.5は、オーサリングプロセスの一環として、3Dアセットのアップロード、配信、およびインタラクティブプレビューをサポートします。 インタラクティブ3Dビューアは、AEMのアセットの詳細ページから利用できます。 ビューアには、3Dアセットのオービット、ズーム、パンを行うためのインタラクティブカメラコントロールのコレクションが含まれています。
詳しくは、 [3Dアセットのプレビューを参照してくださ](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)い。

* **コアコンポーネント**

   Core Components 2.8.0, with numerous fixes, is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM プロジェクトアーキタイプ**

   [AEM Project Archetypeの](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html) ui.frontendモジュールは [](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) 、AEMプロジェクトのフロントエンド開発をより簡単にする便利で柔軟なツールです。

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
| カリフォルニア消費者プライバシー法(CCPA) | CCPAは、2020年1月1日に施行されるデータ保護要件を調和させ、最新化するカリフォルニア州の新しいプライバシー法です。 CCPAは、カリフォルニアに居住するデータサブジェクトのデータを保持するAdobe Campaignのお客様に適用されます。 <br> Adobe Campaignは、既に利用可能なプライバシー機能（同意管理、データ保持設定、ユーザーの役割を含む）に加えて、CCPAの準備を容易にします。 <ul><li>__ アクセス権&#x200B;__&#x200B;と削除権：GDPR用に追加された機能を活用しています。 [詳細情報](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>顧客が個人情報の販売をオプトアウトしたかどうかを追跡できます。 この場合は、プロファイルテーブルを拡張し [!UICONTROL て] 、CCPAのオプトアウ **[!UICONTROL トフィールドを追加する必要があります]**。[詳細情報](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> ハウツービ [デオを参照](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)。 |
| ワークフローライブ監視 | 事前定義されたビューを使用して、インスタンス上のすべてのワークフローの実行ステータスを監視できるようになりました。 <br> 詳しくは、「ステータスに従ったワ [ークフローのフィルタリング」を参照してくださ](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status)い。 |
| AMPを使用したインタラクティブコンテンツ | Adobe Campaignでは、新しいEmail [Formatのインタラクティブ](https://amp.dev/about/email/) AMPを試すことができます。これにより、マーケターは、メッセージ内にAMPコンポーネントを含め、メッセージ自体に直接アクション可能なリッチで動的なインタラクティブなコンテンツを使用して、電子メールエクスペリエンスを強化できます。 <br> この機能はパブリックベータ版としてリリースされています。 <br> 詳しくは、詳細なドキュメントとチュート [リアルビデオ](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) （英語のみ）を参 [照してください](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)。 |
| セキュアな SMS メッセージング（TLS） | 拡張された汎用 SMPP コネクタで、セキュアな SMS がサポートされるようになりました。これにより、プロバイダーに対する暗号化された接続が可能になります。<br> **警告**:この機能を使用するには、すべてのサーバーで最新の証明書が必要です。 無効な証明書、失効した証明書、または期限切れの証明書は、SMS送信機能全体に影響を与えるエラーを生成します。 <br>詳しくは、[詳細ドキュメント](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)を参照してください。 |

修正点と機能改善については、[Adobe Campaign Classic リリースノート](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)を参照してください。

### Campaign Standard 19.4

| 機能 | 説明 |
| ------------- | ----------- |
| カリフォルニア消費者プライバシー法(CCPA) | CCPAは、2020年1月1日に施行されるデータ保護要件を調和させ、最新化するカリフォルニア州の新しいプライバシー法です。 CCPAは、カリフォルニアに居住するデータサブジェクトのデータを保持するAdobe Campaignのお客様に適用されます。 <br> Adobe Campaignで既に利用可能なプライバシー機能（同意管理、データ保持設定、ユーザーの役割など）に加え、CCPAの準備を促進するために、次のような追加機能を追加いたします。 <ul><li> アクセス権と削除権：GDPR用に追加された機能を活用しています。 [詳細情報](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> プライバシーリクエストを作成する際に、規制のタイプ（GDPRまたはCCPA）がプライバシーコアサービスに追加されました。 このメソッドは、すべてのアクセス要求と削除要求に使用する必要があるメソッドです。 アクセスおよび削除のリクエストに対するCampaign APIとインターフェイスの使用は廃止されました。 廃止および削 [除された機能の記事を参照してください](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)。 </li><li> Adobe Campaignユーザーが **個人情報の販売をオプトアウトしたかどうかを追跡できるように、プロファイルリソースに「** CCPAオプトアウト」フィールドが追加されました。 [詳細情報](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> ハウツービ [デオを参照](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)。 |
| Microsoft Dynamics 365統合(GA) | Adobe Campaign StandardとMicrosoft Dynamics 365の統合が可能になりました。 Dynamics 365からCampaignに連絡先とカスタムエンティティレコードを転送し、CampaignからDynamics 365に電子メールイベントデータを取得して、販売/マーケティングの連携を改善できます。 <br> 詳細なドキュメ [ントを参照し](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html) 、この統合を設定してハウツ [ービデオを確認します](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)。 |

See [Adobe Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) for fixes and improvements.

### Adobe Campaign コントロールパネル

管理者ユーザーがサブドメインを委任し、コントロールパネルからSSL証明書を更新するための新しい機能が追加されました。

詳しくは、次のページを参照してください。

* 新しいサブドメインの設定 — 詳 [細情報](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* サブドメインのSSL証明書の更新 — 詳 [細情報](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>これらの機能は、1月末までにベータ版で提供され、予告なく頻繁に更新されたり変更されたりする場合があります。

### その他のリソース

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)- [リリース計画](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaignコントロールパネル：ドキュメ [ント](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) — リ [リースノート](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

2020年1月11日リリース用に更新

| 表示 | 機能 |
|------|---------|
| コンバージョンの追跡 | Advertising cloudのすべてのcookieが更新され、Google Chrome 80の新しいcookie制御要件を満たすようになりました。この要件は2月4日にリリースされます。 この変更は、訪問者指標に影響を与えることなく、既存のcookieを使用してアドビのサーバーから実装されました。 広告主の更新は不要です。 |
| インサイト/アラートベータ、検索/キャンペーン | （検索アカウントのベータ版のみ）新しいアラートベータ版では、検索キャンペーン、広告グループ、キーワードまたは広告が特定の条件を満たすタイミングを識別するアラートテンプレートを作成できます。 パフォーマンス指標 — 指定した期間中にアラートを生成する必要があります。 アラートは1人の広告主で使用できます。 |
| レポート | 商品リスト広告のデータが、ラベル分類、ラベル値、入札ルール、制約の各レポートに含まれるようになりました。 |

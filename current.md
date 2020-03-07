---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: e9fdb1166b47f17256afeaa7bced60f884de8d16

---


# 先行アクセス — Adobe Experience Cloudリリースノート — 2020年3月

Adobe Experience Cloud の新機能および修正点です。

>[!IMPORTANT]
>このページに記載される内容は、リリース前の情報であり、リリース日の前後に変更される可能性があります。

>[!NOTE]
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。リリース後に発表された新情報には、更新の日付が明記されます。

**リリース日：3 月 2020 日**

（特定の製品のリリース日は変更される場合があります）

* [Adobe システムステータス](#status)
* [Experience Cloud インターフェイスとコアサービス](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services および Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Adobe Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（ソリューションヘルプへのリンク）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（ソリューションヘルプへのリンク）
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [新しいドキュメントとチュートリアル](#selfhelp)

ヘルプホームをお探しの場合は、[Adobe Experience Cloud ドキュメント](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)を参照してください。

## Adobe システムステータス {#status}

[!UICONTROL Adobe システムステータス] は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

**最新情報**

* Adobe IDを使用して、より精度の高いイベント通知を、製品の提供レベルやアドオンレベルまで登録できます。 Experience Cloud製品でこの新機能を探します。セルフサブスクリプションプロセスでは、サブスクリプション対象の製品およびサービスのサブオファーが表示されます。 この機能強化により、受信する通知の量が大幅に減り、通知が使用する製品や機能により適切に関連するようになります。  はじめに [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit) をご覧ください。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| 製品サブオファー別にパーソナライズされた自己購読 | <ul><li>Experience Cloud製品の製品オファーまたはアドオン別の自己購読。</li><li>受け取ったイベント通知は、製品と製品の好みに関連します。</li></ul> |
| ユーザーの好みに基づくパーソナライズされたエクスペリエンス | <ul><li>ブラウザーの設定に基づくタイムゾーンの設定は、電子メール通知で使用されます。</li><li>選択したすべての環境設定で、購読/登録解除時に電子メールの確認が送信されました。</li></ul> |
| イベントメッセージの配信の向上 | <ul><li>イベント履歴を時系列のイベントの更新に基づいて並べ替えました。</li><li>メジャー/マイナークローズド雑誌号に追加されたイベント解決のタイムスタンプ。</li></ul> |

## Experience Cloud インターフェイスとコアサービス {#ecloud}

Experience Cloud インターフェイスの新機能および修正点です。管理およびコアサービス（顧客属性、オーディエンス、トリガー、cookie など）が含まれます。

| 機能 | リリース日 | 説明 |
| ----|----|---- |
| 管理ツール - ユーザーの詳細を表示 | 2020年2月26日 | 管理者は、新しい管理ツールで、すべての Experience Cloud ユーザーとその詳細に関する、並べ替え可能でフィルタリング可能なリストを表示できます。ユーザーの詳細には、ユーザーの製品アクセス、ロール、最終アクセス日が含まれます。See [Experience Cloud Admin Tool](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) help for details. |

### 統合製品ドメイン

アドビでは、すべての Adobe Experience Cloud アプリケーションでエクスペリエンスを統合し、向上させるために、ドメインとインターフェイスのヘッダーを更新しています。これらの機能強化は、小規模ではあっても、重要な方法でエクスペリエンスをシンプルにするように設計されています。これらの機能強化では、現在のワークフローは変更されません。

更新内容は次のとおりです。

* 新しいソリューション URL：`experience.adobe.com/<application name>`：
   * すべての製品で、最終的にこの URL パターンが採用されます。1 ヶ月間にわたって効果的な新しい URL を探します。
   * ブラウザーのサポート：サポートされるブラウザーには、[!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari]、および [!DNL Opera]（最新バージョン）が含まれます。**メモ：** Experience Cloud インターフェイスはこれらのブラウザーをサポートしていますが、個々のソリューションがすべてのブラウザーに対応しているわけではありません（例えば、[Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) は [!DNL Opera] をサポートしておらず、[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) は [!DNL Safari] をサポートしていません）。
   * （[!DNL Safari] のみ）ドメインの変更によって、[!DNL Safari] で cookie の問題が発生する場合があります。[!DNL Safari] のプライバシー設定で「_サイト越えトラッキングを防ぐ_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Experience Cloud がこの新しいドメインで機能するようになります。
* 組織間または別のアプリケーション間の切り替えが容易になりました。
* 製品ヘルプの改善：ヘルプ検索にコミュニティフォーラムやビデオコンテンツの結果も含められるよう、[!UICONTROL Experience League] は製品に統合されています。この変更により、より多くのコンテンツへのアクセスが簡素化され、Experience Cloud を最大限に活用できるようになります。さらに、**[!UICONTROL ヘルプ]**／**[!UICONTROL フィードバック]**&#x200B;をクリックして問題を報告したり、アドビとアイデアを共有したりします。
* 通知の改善：[!UICONTROL 通知]ドロップダウンメニューに 2 つのタブが追加されました。1 つは独自の製品通知用、もう 1 つはグローバルな製品のお知らせ用です。

**注意：** フィー [!UICONTROL ドページは] 、2020年1月に廃止されました。 製品内の廃止のお知らせを探してください。

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## Experience Platform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.

* [Experience Platform リリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html)（すべてのアドビ製品）

### Experience Platform Launch {#launch}

リリースノートおよび製品ドキュメントについては、[Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) を参照してください。

## Mobile Services および Mobile SDK {#mobile}

**iOS v4.19.1**

* 一般 — [!UICONTROL Swift] Enumsがコール追跡のコンテキストデータに含まれる場合に発生する潜在的なクラッシュを解決しました。
* [!DNL Target] - Adobe Analytics [!DNL Target] に送信される内部 `a.target.sessionId` Analytics-for-Targetヒットに、セッションID  がコンテキストデータパラメーターとして追加されるようになりました。

**Android v4.18.1**

* [!DNL Target]  — セ [!DNL Target] ッションIDは、Adobe Analyticsに送信される内部 [!UICONTROL Analytics-for-Targetヒットに、コンテキストデータパラメーター「a.target.sessionId] 」として追加されます。

## [!DNL Analytics] {#analytics}

リリース日：**2020 年 3 月 12 日**

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

製品ドキュメントについては、[Adobe Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

### Adobe Analytics の新機能、機能強化および修正点 {#aa-features}

* **Analysis Workspaceの複数のレポー[!UICONTROL トスイート&#x200B;]**:複数のレポートスイートのデータを単一の[!UICONTROL Analysis Workspaceプロジェクトに取り込んで]、並べて表示できるようになりました。 この機能は、数週間の間にすべてのお客様に提供されます。[詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloudオーディエンスの最適化**:この機能を使用すると、以前の48時間の処理時間ではなく、8時間以内にセグメントをExperience Cloudに公開できます。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace — トレーニングチュートリアルテンプレート**:この新しい標準テンプレートでは、Workspaceで最初の分析を作成するための一般的な用語と手順を順を追って説明します。 これは、「新規プロジェクト」モーダルの標準テンプレートとして使用でき  、リストに他のプロジェクトを含まない新規ユーザー向けに、現在存在するサンプルプロジェクトを置き換えます。

#### 修正点

* Reports &amp; Analyticsで、レポートをダ [!UICONTROL ウンロードできない] 、問題を修正し `.xls` ました。（AN-206541、AN-204008）
* 新しいシェルの展開で、Experience Cloud組織の切り替えに関する顧客の問題がいくつか修正されました。（AN-200844、AN-186920）
* 分類の検索フィルターに「未指定（なし） ____ 」を含めずに「未指定（未指定）」の行項目（またはその他のレポート行項目）を分類しても、分類の結果が返されない問題を修正しました。
* 分類されたディメンションを使用する場合、入口指標または出口指標の合計が、分類の行項目の合計と一致しない問題を修正しました。
* アトリビューションIQのファーストタッチモデルとラストタッチモデルで、あらかじめ用意されているディメンションの一部の行項目のクレジットが正しく計算されない問題を修正しました。
* ある日付ディメンションを別の日付ディメンションで分類すると、誤った結果が返される問題を修正しました。
* 分類されたディメンションレポートで「未指定」に適用した場合に、入口指標または出口指標が正しくカウントされないことがある問題を修正しました。


### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| EOL of **[!UICONTROL Conversion Level]** setting | 2020年3月3日 | 管理ツール/レポートスイート [](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html)**[!UICONTROL /アカウン]** ト設定一般のUIが機能しないコンバージョンレベル設定は、2020年3月12日に削除されます。 |
| ダッシュボードアー **[!UICONTROL カイブのEOL]** | 2020年3月3日 | **** Reports &amp; Analyticsの「ダッシュボードを管理 **[!UICONTROL 」の「アーカイブを表示]** 」設定は、2020年3月12日から使用できなくなります。 |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| 新しい Adobe Analytics ドメイン | 2019 年 12 月 19 日 | 2020 年 1 月 17 日に、Adobe Analytics は新しいドメインへの移行を開始しました。`https://experience.adobe.com/analytics.`<br>**メモ&#x200B;**：この変更は、Adobe ID または Enterprise ID を使用して Analytics にアクセスするすべてのユーザーに適用されます。<ul><li>ドメインの変更により、Safari で Analytics を読み込む際に cookie の問題が発生する可能性があります。 のプライバシー設定で「_サイト越えトラッキングを防ぐ_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Analytics がこの新しい Adobe Experience Cloud ドメインで機能するようになります。[!DNL Safari]You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>ドメインの変更により、[ある特定のケースにおいて](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)、一部の顧客に対して [!UICONTROL Activity Map] が機能しなくなる場合があります。</li></ul> |
| 提供終了 - Analytics レガシー API | 2020 年 1 月 10 日 | 2020 年 11 月に、以下の Analytics レガシー API サービスが提供終了となり、シャットダウンされます。これらのサービスを使用して構築された現在の統合は機能しなくなります。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問に対する回答と進め方に関するガイダンスを提供するために、[従来の API EOL の FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

「[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)」を参照してください。バージョン2.20.0は、2020年3月5日にリリースされました。

## Audience Manager {#aam}

Audience Managerの新機能と更新点：

### Fixes and improvements {#aam-fixes-and-improvements}

* RBAC権限 [!UICONTROL VIEW_ALL_DESTINATIONSが見つからないため、顧客がセグメント名を更新できない問題を修正しました]。 セグメ [!UICONTROL ントを更新するために] 、VIEW_ALL_DESTINATIONS権限は不要です。 RBACの権限の詳細については、 [Administration (RBAC Controls)を参照してください](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions)。 （AAM-52760）
* データエクスプローラ [ーのシグナルに基づいて特性を作成する場合に](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) 、式ビルダーの基本情報の節と演算子にコンテンツが表示されない場合があるというデータエクスプローラーのバグを修正 [!UICONTROL しました] 。 （AAM-53130）
* 一部の顧客が [!UICONTROL Audience Marketplaceインターフェイスを読み込めなかったバグを修正しました] 。 （AAM-52070）
* セグメントAPIで、説明のない一部のセグメントが原因で  、ユーザーがこれらのセグメントにアクセスしようとするとインターフェイスがフリーズし、そのページから移動しないというバグを修正しました。 （AAM-53071）
* インターフェイス全体で複数のアクセシビリティの改善が行われました。 (AAM-48952、AAM-48969、AAM-48979、AAM-48993、AAM-49048、AAM-49057、AAM-49058,AAM-49392)

## Adobe Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品のアップデート

* **AEM 6.5.4.0** AEM 6.5、Service Pack 4.0（2020年3月5日リリース6.5.4.0）は、新機能、お客様向けの主な機能強化、パフォーマンス、安定性、セキュリティの向上を含む重要なアップデートです。2019年4月のAEM 6.5の一般リリース以降にリリースされます。
   * [Adobe Experience Manager 6.5、Service Pack 4の新機能](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Formsリリース成果物](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4、Service Pack 8.0（2020年3月5日リリース6.4.8.0）は、2018年4月のAEM 6.4の一般リリース以降にリリースされた主なお客様向け修正を含む重要なアップデートです。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3、Service Pack 3、Cumulative Fix Pack 8（2019年3月5日リリース）は、2017年4月のAEM 6.3の一般リリース以降にリリースされた主なお客様向け修正を含む重要なアップデートです。
   * [リリースノート](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4、Service Pack 6（2020年3月5日リリース）では、AEM AssetsがBrand Portalで設定される方法が変更さ [!UICONTROL れました。] また、このリリースには、その他の機能強化およびバグ修正が含まれています。
   * [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### セルフサービス

* **クラウドサービスとしてのAEM — ロールベースの権限**

   Cloud Managerには、適切な権限を持つ事前設定済みのロールがあります。 各ロールには、特定の権限、事前設定済みのタスクまたは権限が関連付けられています。 「ロー [ルベースの権限](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) 」のヘルプトピックでは、使用可能な機能と、それらを実行できる役割を特定します。

* **クラウドサービスとしてのAEM — ディスパッチャー**

   ディスパッ [チャー、CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) 、および [](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) Explicit Dispatcherキャッシュの無効化の各セクションが更新され、使用可能なオプションとその動作方法が明確になりました。

* **Brand PortalでのAEM Assetsの設定**

   AEM Assetsは、Adobe I/Oを通じて  Brand Portalで設定され、Brand Portalテナントの認証用にIMSトークンを調達するようになりました。 以前は、レガシーOAuth Gatewayを使用してClassicインターフェイスで設定さ [!UICONTROL れていました。]
Brand Portalで [のAEM Assetsの設定を参照してください](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html)。

* **クラウドサービスとしてのAEM — ダイナミックメディアでのスマート切り抜き**

   ダイナミックメディアコンポーネントでスマート切り抜きを使用する場合、AEMでクラウドサービスとして新しいオプションを使用できます。

   **縦横比の一致を有効にする** — 元の画像の縦横比に最も適したスマート切り抜きレンディションをダイナミックメディアで選択する場合は、このオプションを選択します。
スマート [切り抜きを使用する場合を参照してください](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop)。

### コミュニティ

* **AEM Skill Builderのウェビナー**

   * AEMサイト — 2020年3月17日より、コンテンツオーサリングの構成要素、およびAEMサイトの基本概念と操作について学習します。 [今すぐ登録](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register)。
   * AEM Assets - 2020年3月19日より、デジタルアセット管理に関する専門知識を習得できるほか、ブランドポータル、 [!UICONTROL Dynamic Media、][!UICONTROL Asset Linkなどの基本的な機能を習得できます] 。 [今すぐ登録](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register)。

### その他のリソース

* [クラウドサービスとしての AEM](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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

### その他のリソース

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)- [リリース計画](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

更新日：2020 年 2 月 11 日（2 月 9 日のリリース）:

| 表示 | 機能 |
|------|---------|
| [!UICONTROL ポートフォリオ] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. 広告グループ内のすべての広告に同じ入札が適用されます。日本ディスプレイネットワークキャンペーンのデータは、ポートフォリオのシミュレーションに含まれます。 |
| [!UICONTROL 検索] /一括 [!UICONTROL シート] | Bulksheets を使用して、Google レスポンシブ検索広告（RSA）を作成、編集、削除できるようになりました。以前は、標準キャンペーン管理インターフェイスの&#x200B;**[!UICONTROL 検索]**／**[!UICONTROL キャンペーンで]**&#x200B;のみサポートされていました。 |
| [!UICONTROL 検索] /キャ [!UICONTROL ンペーン、レポート] | Google 広告の掲載順位の指標「`Impr. (Top) %` および `Impr. (Abs. Top) %`」をすべての基本レポート、およびエンティティレベルのキャンペーン管理ビューで使用できるようになりました（ただし、買い物製品グループの場合や、[!UICONTROL Campaign Daily Impression Share] レポート、[!UICONTROL Keyword Daily Impression Share] レポート、およびラベルビューと制約ビューを除く）。 |

## [!DNL Magento] {#magento}

Magent リリースノートについては、以下を参照してください。

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーの各ステージを通じてエンゲージメントをおこなうことで顧客体験を変えようとしているリード管理や B2B マーケター向けの完全なソリューションです。

### Core Marketo Engage の更新

リリース日：2020 年 2 月 22 日

* **Microsoft Dynamics _Microsoft_ フローにおける所有者の変更アクション：** Marketo Engage から直接リードまたは連絡先所有者を変更します。
* **API 呼び出しの機能強化：**
   * ユーザー管理 API
   * カスタムオブジェクトスキーマ API
   * ランディングページリダイレクトルール API
* **フォーム記述子のキャッシュ：**&#x200B;ランディングページとフォームの改善を改善しました。

詳しくは、[2020 年 2 月](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)の [!DNL Marketo] リリースノートを参照してください。

### 予定されている機能

今四半期を通じて、次の機能がリリースされます。

| 機能 | 説明 |
|------|---------|
| [!DNL Bizible] | <ul><li>新しいアカウントベースのセグメント化</li><li>ダッシュボード固有のフィルターの保存</li><li>Bizbile ダッシュボードを PDF 形式で書き出し</li></ul> |
| Sales Connect | ウィンドウとコマンドセンターの構成の更新／機能強化 |

### 発表

**Marketo Engage サクセスセンター：** 2020 年 2 月に立ち上げ予定。サクセスセンターは製品内ヘルプセンターで、製品ドキュメントとコミュニティの検索、ハウツーガイドの起動、導入コンテンツへのアクセスなどをおこなうことができます。注意：この機能は ANZ でベータ版として開始され、四半期の後半に北米で公開予定です。

### 廃止

* **アセットAPI &quot;_method&quot; パラメーター：** 2020 年 9 月以降、アセット API エンドポイントでは、URI の長さ制限を回避するために、POST 本文にクエリパラメーターを渡す「_method」を使用できなくなります。
* **Internet Explorer のサポートの廃止：** 2020 年 7 月 31 日のリリース以降、Marketo Engage ユーザーインターフェイスは Internet Explorer でサポートされなくなります。

これまでのリリースノートと過去のリリースノートについては、[Marketo リリースノート](https://docs.marketo.com/x/CgA6Ag)を参照してください。

## 新しいドキュメントとチュートリアル {#selfhelp}

新しいおよび最近のセルフヘルプ記事とビデオ。 <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| ソリューション | コンテンツ | 説明 |
|----------| -----------| ---------- |  
| [!UICONTROL AEMコマース] | ビデオ — 複数の [カテゴリおよび製品ページの作成](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | CIFコアコンポーネントを使用して、最小限のAdobe Experience Manager(AEM)CIFプロジェクトをカスタマープロジェクトの出発点として作成する方法を説明します。 コンポーネントにテーマとCSSスタイルを適用し、アーキタイプによって生成された新しいAEM CIFプロジェクトを調査します。 また、CIFコアコンポーネントで使用されるCSSとJavaScriptの編成方法についても説明します。 |
| [!UICONTROL AEM Forms] | 記事 — OKTAを使 [用してAEM作成者を認証する](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | OKTAポータルでアプリを設定する方法と、新しいアプリを登録する際に一般的に使用する設定について説明します。 |
| [!UICONTROL AEMコマース] | チュートリアル — CIFコ [アコンポーネントのカスタマイズ](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | CIFコアコンポーネントおよびAEMが提供する一般的な拡張ポイントをいくつか確認します。 CIFコアコンポーネントは、Adobe Experience Manager(AEM)とMagentoソリューションを統合するプロジェクトの迅速化に使用できる、コマースの標準コンポーネントのセットを提供します。 |
| [!DNL Adobe Campaign]  — オーディエンスの宛先 | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Adobe [!UICONTROL Experience Platform Segment Builderを使用して、Campaign Standardでオーディエンスを作成します]。 この機能には、Adobe Campaign Standard内でオーディエンスモジュールを介して直接アク [!UICONTROL セスでき] ます。 |
| [!DNL Adobe Campaign]  — オーディエンスの宛先 | ビデオ — マーケテ [ィングワークフローでのAdobe Experience Platformオーディエンスのアクティブ化](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | オーディエンスを読み取るアクティビティを使用して [!UICONTROL 、ワークフロー内で] Data Services Query Audienceをアクティブにする方法につ [!UICONTROL いて説明します] 。 |
| [!DNL Adobe Campaign] | チュートリアル — Android [でのプッシュ通知](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | パーソナライズされたセグメント化されたプッシュ通知をiOSおよびAndroid携帯端末に送信します。 このチュートリアルでは、Adobe Campaignからプッシュ通知を送信し、Androidアプリでこれらの通知を受信する手順を説明します。 |
| [!DNL Adobe Campaign] | ビデオ — プ [ッシュ通知の作成](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Adobe Campaign Standardでプッシュ通知を作成します。 パーソナライズされたセグメント化されたプッシュ通知をiOSおよびAndroid携帯端末に送信できます。 |
| [!DNL Adobe Campaign] - AEPデータコネクタ | ビデオ — デ [ータ取り込みジョブのステータスの確認](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | データ取り込みジョブのステータスを確認する方法と、データがAdobe Campaign StandardからAdobe Experience Platformに取り込まれたかどうかを説明します。 |
| [!DNL Adobe Campaign] - AEPデータコネクタ | ビデオ — データマ [ッピングの変更](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | ステータスを確認し、データマッピングを変更する方法を説明します。 |
| [!DNL Adobe Campaign] - AEPデータコネクタ | ビデオ — エクスペリエ [ンスイベントのマッピング](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Adobe Experience Platformでエクスペリエンスイベントをマッピングする方法を説明します。 |
| [!DNL Adobe Campaign] - AEPデータコネクタ | ビデオ — カスタムリ [ソースのマッピング](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Adobe Campaign StandardとAdobe Experience Platformの間で異なるデータタイプをマッピングする方法を説明します。 |
| [!DNL Adobe Campaign] - AEPデータコネクタ | ビデオ — Adobe Experience Platform [Data Connectorについて](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | XTKデータ（Campaignで取り込んだデータ）をAdobe Experience Platformのエクスペリエンスデータモデル(XDM)データにマッピングして、データをAdobe Experience Platformで利用できるようにする方法を説明します。 |
| [!DNL Adobe Campaign] - AEPデータコネクタ | ビデオ — シードテ [ーブルデータのマッピング](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Adobe Experience Platformでシードデータ/テストプロファイルをマッピングする方法を説明します。 |
| [!DNL Adobe Campaign]— オーディエンスの宛先 | ビデオ — プラ [ットフォームオーディエンスの配信のターゲットディメンションを変更します。](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Adobe Campaign Standardのプライマリプロファイルテーブル以外で、プラットフォームオーディエンスの配信のターゲットディメンションを変更する方法について説明します。 |
| [!DNL Adobe Campaign] | ビデオ — Snowflake [のビッグデータ管理](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Adobe Campaign Classicの雪片コネクターを活用します。 |
| [!DNL Adobe Campaign]  — オーディエンスの宛先 | 記事 — オーデ [ィエンスの宛先（ベータ） — 概要](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Adobe Experience Platformの一元化された統合プロファイルデータを、Adobe Campaign Standardのマーケティングキャンペーンに活用する方法を説明します。 |
| [!DNL Adobe Target] - モバイル SDK | チュートリアル — Adobe Target [を使用してアプリのエクスペリエンスをパーソナライズする](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Adobe Targetを独自のAndroidアプリに実装します。 Mobile Services SDKの設定を検証し、コンテンツのプリフ [!DNL Target] ェッチ、リクエストのブロックなどのリクエストを実装します。 |
| Adobe Analytics | ビデオ — [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | 2019年サミットのハイテク「スーパーセッション」の厳選映像を見る。 |
| Adobe Analytics | ビデオ — 顧 [客の遍歴分析での計算指標の概要](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Customer Jureny Analyticsでの計算指標の作成に関する基本 [!UICONTROL 的な手順を] 、実 [!UICONTROL 際に説明します]。 |
| Adobe Analytics | ビデオ — [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | 2019年サミットの旅行と接客セッションで、厳選されたクリップを閲覧。 |
| Adobe Analytics | ビデオ — [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | 2019年Summitの小売セッションの厳選されたクリップを参照してください。 |
| Adobe Analytics | ビデオ — お [客様の使用例：販売促進のために顧客体験に投資するアクセントグループ](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | アクセントグループがAdobe Experience Cloudをどのように使用してシームレスなデジタルエクスペリエンスを作成するかをご覧ください。 |
| Adobe Analytics | ビデオ — お [客様の使用例：ServiceNowは、見込み客とつながる適切な洞察を得る](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | マーケティングチャ [!DNL ServiceNow] ネルから実用的なデータを取得し、Adobe Advertising CloudとAdobe Analyticsを使用した有料検索広告のROIを向上させる方法を説明します。 |
| Adobe Analytics | ビデオ — [Adobe Analytics - It&#39;s More More More More Data It&#39;s It&#39;s Customer Intelligence](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | データ主導型マーケティングについて、および分析の成熟度をデータからインサイト、行動に移す方法について説明します。 |
| Adobe Analytics | ビデオ — [Adobe SenseiおよびAdobe Analytics — 拡張バージョン](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Adobe Analytics Powered [!DNL Sensei,] Adobe Analytics Powered, Analysis, [!UICONTROL Intelligent Alerts,] Nomaly Alerts, [!UICONTROL Nomaly Alerts,] Nomaly Segment,Req [!UICONTROL Propentics Modelingを含む主な機能を表示します。] |
| Adobe Analytics | ビデオ — Adobe Analysis Workspace [によるビジネスの変更方法](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Analysis Workspaceを使用して、Ad Hoc Analysis、柔軟な分析、コホート分析およびフォールアウト分析を実行する方法につい [!UICONTROL て説明します]。 また、分析作業環境を社内の全員と共有でき、ドラッグ&amp;ドロップ機能を使用すると、全員がデータを簡単に分析し、インサイトを迅速に得ることができます。 |
| Adobe Analytics | ビデオ — お [客様の使用例：Home DepotがCustomer Experience Managementを革新](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | アドビのソリューショ [!DNL Home Depot] ンを使用して、カスタマイズされた買い物体験でブランドへの忠誠度と顧客満足度を得る方法を説明します。 |
| Adobe Analytics | プレゼンテーション — [顧客の遍歴分析について](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Adobeのアプリケーションサービスである [!UICONTROL Adobe Customer Jeurney]Analyticsが、 [!DNL Adobe Experience Platform]Analysis WorkspaceをExperience Platform  に組み込む方法を説明します。 この機能を使用すると、任意のデータセットに対するマルチチャネル分析を [!DNL Adobe Experience Platform] 有効にできます。 |
| Adobe Analytics | ビデオ — CJA [でのチャネル間アトリビューション](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | ビジュアライゼーションを使用して、Customer Jeurney Analyticsのチャネル間でアトリビューションを表示（クレジットを付与）する方 [!UICONTROL 法を説明します]。 |
| Adobe Analytics | 記事 — Adobe Analytics [の学習の遍歴を継続するための顧客のヒント](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Adobe Analyticsから最大の価値を得る方法に関するヒントやテクニックをお持ちのアドビの3人のお客様にお会いします。 |
| Adobe Analytics | ビデオ — CJAでの [チャネル間ビジュアライゼーションの作成](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | 顧客の遍歴分析 [!UICONTROL を使用すると] 、複数のチャネルにわたる複数のデータセットからのデータを含むビジュアライゼーション（訪問者あたりのデータの結合を含む）を作成できます。 |
| Adobe Analytics | ビデオ — 計 [算指標をAdobe Analyticsから顧客の遍歴分析に移動](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Analytics計算指標を再作成する際のヒ [!UICONTROLCントを] Customer Jeurney Analytics [!UICONTROL で確認します]。 |
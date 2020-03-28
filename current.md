---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: abf763ddf0ed4ae9d8df5b7dcef4e664db4cf682

---


# Adobe Experience Cloud リリースノート - 2020 年 3 月

![バナー](/assets/experience-cloud-banner-3.png)

[!DNL Adobe Experience Cloud] の新機能および修正点です。

>[!IMPORTANT]
>このページに記載される内容は、リリース前の情報であり、リリース日の前後に変更される可能性があります。

>[!NOTE]
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。リリース後に発表された新情報には、更新の日付が明記されます。

**リリース日：3 月 2020 日**

最終更新日：2020 年 3 月 11 日

* [Adobe システムステータス](#status)
* [Experience Cloud インターフェイスとコアサービス](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) - リリース日：**2020 年 3 月 12 日** （更新日2020年3月27日）
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（ソリューションヘルプへのリンク）
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（ソリューションヘルプへのリンク）
* [新しいドキュメントとチュートリアル](#selfhelp)

ヘルプホームをお探しの場合は、[Adobe Experience Cloud ドキュメント](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)を参照してください。

（特定の製品のリリース日は変更される場合があります）

## ![アイコン](/assets/adobe.png) Adobe システムステータス{#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

**最新情報**

* Adobe ID を使用して、製品オファーやアドオンレベルまで掘り下げた、より精度の高いイベント通知を登録できます。Experience Cloud 製品でこの新機能を探します。セルフサブスクリプションプロセスでは、サブスクリプション対象の製品およびサービスのサブオファーが表示されます。この機能強化により、受信する通知の量が大幅に減り、使用する製品や機能により関連した通知を受け取ることができます。はじめに [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit) をご覧ください。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| 製品サブオファー別にパーソナライズされたセルフサブスクリプション | <ul><li>Experience Cloud 製品のオファーまたはアドオン別のセルフサブスクリプション。</li><li>受け取ったイベント通知は、お客様の製品と製品の好みに関連付けられたものです。</li></ul> |
| ユーザーの好みに基づいてパーソナライズされたエクスペリエンス | <ul><li>電子メール通知では、ブラウザーの設定に基づいたタイムゾーン設定を使用します。</li><li>選択したすべての環境設定で、登録／登録解除時に電子メールの確認が送信されていました。</li></ul> |
| イベントメッセージの配信の向上 | <ul><li>時系列のイベントの更新に基づいてイベント履歴を並べ替えました。</li><li>大規模／小規模な解決済みの問題に、イベント解決のタイムスタンプを追加しました。</li></ul> |

## ![アイコン](/assets/experience-cloud.png) Experience Cloud インターフェイスとコアサービス{#ecloud}

Experience Cloud インターフェイスの新機能および修正点です。管理およびコアサービス（顧客属性、オーディエンス、トリガー、cookie など）が含まれます。

| 機能 | リリース日 | 説明 |
| ----|----|---- |
| 管理ツール - ユーザーの詳細を表示 | 2020 年 2 月 27 日 | 管理者は、新しい管理ツールで、すべての Experience Cloud ユーザーとその詳細に関する、並べ替え可能でフィルタリング可能なリストを表示できます。ユーザーの詳細には、ユーザーの製品アクセス、ロール、最終アクセス日が含まれます。詳しくは、[Experience Cloud 管理ツール](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html)のヘルプを参照してください。 |

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

**メモ：**[!UICONTROL フィード]ページは、2020 年 1 月に廃止されました。製品内の廃止のお知らせを探してください。

製品ドキュメントについては、[Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) のヘルプを参照してください。

## ![アイコン](/assets/platform.png) Experience Platform {#platform}

[!UICONTROL Experience Platform]、[!UICONTROL Experience Platform Launch]、[!UICONTROL ID サービス]、Journey Orchestration、Mobile Services およびセキュリティ速報のリリースノートです。

* [Experience Platform リリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [ジャーニーオーケストレーション](#journey)
* [Mobile Services および Mobile SDK](#mobile)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html)（すべてのアドビ製品）

### Experience Platform Launch {#launch}

リリースノートおよび製品ドキュメントについては、[Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) を参照してください。

### ジャーニーオーケストレーション {#journey}

Adobe Experience Platform を使用すると、それぞれの顧客のニーズをリアルタイムでインテリジェントに予測し、どのようなジャーニーをたどっていても、個別カスタマージャーニーをエクスペリエンスチャネル全体で大規模に編成することができます。

第 1 四半期のリリースが公開されました。[詳細を表示](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

#### Jargeny Orchestration の追加リソース

[ドキュメント](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services および Mobile SDK {#mobile}

**iOS v4.19.1**

* 一般 - コール追跡のコンテキストデータに [!UICONTROL Swift] Enum が含まれる場合に、クラッシュが発生する可能性があったを解決しました。
* [!DNL Target] - [!DNL Target] セッション ID は、Adobe Analytics に送信される内部 [!UICONTROL Analytics-for-Target] ヒットで、コンテキストデータパラメーター「`a.target.sessionId`」として追加されるようになりました。

**Android v4.18.1**

* [!DNL Target] - [!DNL Target] セッション ID は、Adobe Analytics に送信される内部 [!UICONTROL Analytics-for-Target] ヒットで、コンテキストデータパラメーター「a.target.sessionId」として追加されるようになりました。

## ![アイコン](/assets/analytics.png) [!DNL Analytics] {#analytics}

リリース日：**2020 年 3 月 12 日**

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices) （更新日2020年3月27日）
* [AppMeasurement](#appm)

製品ドキュメントについては、[Adobe Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

### Adobe Analytics の新機能、機能強化および修正点 {#aa-features}

* **[!UICONTROL Analysis Workspace ]** の複数のレポートスイート：複数のレポートスイートのデータを単一の [!UICONTROL Analysis Workspace] プロジェクトに取り込み、パネルを横に並べて表示できるようになりました。[詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud Audience Optimization**：この機能を使用すると、8 時間以内にセグメントを Experience Cloud に公開できます（以前は処理に 48 時間かかっていました）。[詳細情報...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace - トレーニングチュートリアルテンプレート**：この新しい標準テンプレートでは、Workspace で最初の分析を作成するための一般的な用語と手順を順に説明します。これは、「[!UICONTROL 新規プロジェクト]」モーダルの標準テンプレートとして使用でき、リストに他のプロジェクトがない新規ユーザー向けにある、サンプルプロジェクトを置き換えます。

#### 修正点

* [!UICONTROL Reports &amp; Analytics] で、`.xls` レポートをダウンロードできない問題を修正しました。この問題は、米ドルおよびユーロ以外の通貨を使用しているお客様に影響を与えました。（AN-206541、AN-204008）
* 新しいシェルのロールアウトにより、Experience Cloud 組織の切り替えに関するお客様の問題をいくつか修正しました。（AN-200844、AN-186920）
* 「_未指定（なし）_」の行項目（またはその他のレポート行項目）で分類を実行しても、分類の検索フィルターに「_未指定（未指定）_」を含めていない場合に、分類の結果が返されない問題を修正しました。
* 分類されたディメンションを使用する場合、入口指標または出口指標の合計が、分類の行項目の合計と一致しない問題を修正しました。
* Attribution IQ のファーストタッチモデルとラストタッチモデルで、すぐに使えるディメンションで一部の行項目のクレジットが正しく計算されない問題を修正しました。
* ある日付ディメンションを別の日付ディメンションで分類すると、誤った結果が返される問題を修正しました。
* 分類されたディメンションレポートで「未指定」に適用した場合に、入口指標または出口指標が正しくカウントされないことがある問題を修正しました。

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加または更新日 | 説明 |
| -----------| ---------- | ---------- |
| **[!UICONTROL コンバージョンレベル]**&#x200B;設定のサポート終了 | 2020 年 3 月 4 日 | **[!UICONTROL 管理ツール]／[!UICONTROL レポートスイート]／[!UICONTROL 一般的なアカウント設定]**&#x200B;で、機能しない[コンバージョンレベル](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html)設定は、2020 年 3 月 13 日に UI から削除されます。 |
| **[!UICONTROL ダッシュボードアーカイブ]**&#x200B;のサービス終了 | 2020 年 27 月 4 日 | **[!UICONTROL Reports &amp; Analyticsの「]** 表示を管理 **** 」の「ダッシュボードのアーカイブ」設定は、2020年10月以降は使用できなくなります。 |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| 新しい Adobe Analytics ドメイン | 2019 年 12 月 19 日 | 2020 年 1 月 17 日に、Adobe Analytics は新しいドメインへの移行を開始しました。`https://experience.adobe.com/analytics.`<br>**メモ&#x200B;**：この変更は、Adobe ID または Enterprise ID を使用して Analytics にアクセスするすべてのユーザーに適用されます。<ul><li>ドメインの変更により、Safari で Analytics を読み込む際に cookie の問題が発生する可能性があります。[!DNL Safari] のプライバシー設定で「_サイト越えトラッキングを防ぐ_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Analytics がこの新しい Adobe Experience Cloud ドメインで機能するようになります。この問題が影響するのは [!DNL Safari] ユーザーのみなので、ユーザーは問題なく他のブラウザーを使用できます。</li><li>ドメインの変更により、[ある特定のケースにおいて](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)、一部の顧客に対して [!UICONTROL Activity Map] が機能しなくなる場合があります。</li></ul> |
| 提供終了 - Analytics レガシー API | 2020 年 1 月 10 日 | 2020 年 11 月に、以下の Analytics レガシー API サービスが提供終了となり、シャットダウンされます。これらのサービスを使用して構築された現在の統合は機能しなくなります。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問に対する回答と進め方に関するガイダンスを提供するために、[従来の API EOL の FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis のサポート終了 | 2018 年 8 月 7 日 | アドビは Ad Hoc Analysis のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。詳しくは、[Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) を参照してください。 |

### [!DNL AppMeasurement] {#appm}

「[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)」を参照してください。バージョン 2.20.0 は 2020 年 3 月 6 日にリリースされました。

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager の新機能とアップデート：

| 機能 | 説明 |
| -----------| ---------- |
| [一括管理ツールワークシート](https://docs.adobe.com/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | 新しいバージョンのワークシートをご利用いただけます。このワークートでは、Windows 64 ビットオペレーティングシステムでアルゴリズムモデルを作成する際に一部のお客様で発生していた問題を修正しています。最新バージョンは[こちら](https://docs.adobe.com/help/en/audience-manager/user-guide/reference/bulk-management-tools/assets/BAAAM_V2_20200311.xlsm)からダウンロードしてください。 |

### 修正点および改善点 {#aam-fixes-and-improvements}

* RBAC 権限 [!UICONTROL VIEW_ALL_DESTINATIONS] が見つからず、顧客がセグメント名を更新できない問題を修正しました。セグメントを更新するためには、[!UICONTROL VIEW_ALL_DESTINATIONS] 権限は不要です。RBAC の権限の詳細については、[管理（RBAC コントロール）](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions)を参照してください。（AAM-52760）
* [!UICONTROL データエクスプローラー]のシグナルに基づいて特性を作成したときに、式ビルダーの基本情報セクションと演算子にコンテンツが表示されない場合がある[データエクスプローラー](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html)のバグを修正しました。（AAM-53130）
* 一部の顧客が [!UICONTROL Audience Marketplace] インターフェイスを読み込めないバグを修正しました。（AAM-52070）
* [!UICONTROL セグメント API] で、説明のない一部のセグメントが原因となり、ユーザーがこれらのセグメントにアクセスしようとするとインターフェイスがフリーズし、そのページから移動しないというバグを修正しました。（AAM-53071）
* インターフェイス全体で複数のアクセシビリティを改善しました。（AAM-48952、AAM-48969、AAM-48979、AAM-48993、AAM-49048、AAM-49057、AAM-49058、AAM-49392）

## ![Icon](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品のアップデート

* **AEM 6.5.4.0**
AEM 6.5、Service Pack 4.0（2020 年 3 月 5 日リリース 6.5.4.0）は、2019 年 4 月の AEM 6.5 の一般リリース以降にリリースされた新機能、お客様向けの主な機能強化、パフォーマンス、安定性、セキュリティの向上を含む重要なアップデートです。
   * [Adobe Experience Manager 6.5、Service Pack 4 の新機能](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms リリース成果物](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4 Service Pack 8.0（2020 年 3 月 5 日にリリースされた 6.4.8.0）は重要なアップデートであり、2018 年 4 月の AEM 6.4 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。
   * [リリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3 Service Pack 3 Cumulative Fix Pack 8（2019 年 3 月 5 日にリリースされた 6.3.3.8）は重要なアップデートであり、2017 年 4 月の AEM 6.3 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。
   * [リリースノート](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4、Service Pack 6（2020 年 3 月 6 日リリース）では、[!UICONTROL  Brand Portal での AEM Assets の設定方法を変更しました。] また、このリリースには、その他の機能強化とバグ修正が含まれています。
   * [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### セルフサービス

* **AEM as a Cloud Service – 役割ベースの権限**

   Cloud Manager には、適切な権限を持つ、事前設定済みのロールがあります。各ロールには、特定の権限、事前設定済みのタスクまたは権限が関連付けられています。「[役割ベースの権限](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html)」のヘルプトピックでは、使用可能な機能と、それらを実行できる役割を特定します。

* **AEM as a Cloud Service – Dispatcher**

   [Dispatcher と CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn)、および [Dispatcher キャッシュの無効化を手動で指定](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation)の節を更新し、使用可能なオプションとその動作方法を明確にしました。

* **AEM Assets と Brand Portal の設定**

   AEM Assets は、Adobe I/O を通じて [!UICONTROL Brand Portal] で設定され、Brand Portal テナントの認証用に IMS トークンを調達するようになりました。以前は、[!UICONTROL レガシー OAuth Gateway を使用して Classic インターフェイスで設定されていました。]
[AEM Assets と Brand Portal の設定](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html)を参照してください。

* **AEM as a Cloud Service - Dynamic Media でのスマート切り抜き**

   Dynamic Media コンポーネントでスマート切り抜きを使用する場合、AEM as a Cloud Service で新しいオプションを使用できます。

   **縦横比の一致を有効にする** - 元の画像の縦横比に最適なスマート切り抜きレンディションを Dynamic Media に選択させる場合は、このオプションを選択します。
[スマート切り抜きを使用する場合](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop)を参照してください。

### コミュニティ

* **AEM スキルビルダーウェビナー**

   * AEM Sites - 2020 年 3 月 18 日開始。コンテンツオーサリングの構成要素、および AEM Sites の基本概念と操作について学習します。[今すぐ登録](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register)。
   * AEM Assets - 2020 年 3 月 20 日開始。デジタルアセット管理に関する専門知識を磨くだけでなく、ブランドポータル、[!UICONTROL Dynamic Media]、[!UICONTROL Asset Link] などの基本的な機能を習得します。[今すぐ登録](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register)。

### その他のリソース

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![アイコン](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### Campaign Classic

* [Campaign Classic 19.1.4 の更新](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### その他のリソース

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)- [リリース計画](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

2020年3月20日、3月21日リリース用に更新：

| 表示 | 機能 |
|------|---------|
| [!UICONTROL ポートフォリオ] | COVID-19によるトラフィックの変化を考慮したポートフォリオの管理方法のガイドラインについては、担当のアカウントマネージャーにお問い合わせください。 |
| Google広告とMicrosoft広告のキャンペーン | 「入札調整値の自動最適化」オプションを使用して最適化されたポートフォリオで、Advertising Cloudは、拡張されたコストパークリック(eCPC)入札戦略を使用して、キャンペーンの入札調整設定を自動的に最適化しなくなりました。 検索エンジンは、オークション時のすべての入札調整を最適化します。 Advertising Cloudは、ベース入札を最適化し、 「キャンペーン予算制限を自動調整」オプションが有効な場合 — キャンペーン予算。 |
| [!UICONTROL アラートベータ版] | （ベータ版機能）ポートフォリオが特定の条件を満たす場合に識別するためのアラートテンプレートを作成できるようになりました。 （パフォーマンス指標など） 指定した期間中にアラートを生成した場合。 ポートフォリオレベルのアラートは、 **[!UICONTROL Optimization]** / **[!UICONTROL Portfoliosのインサイトから作成できますが、]** Optimization **[!UICONTROL /Portfoliosのインサイトからは作成]******&#x200B;できません。 **注意：** 1月に置き換えられた従来のバージョンのアラートベータ版から作成されたアラートは、使用できなくなりました。 |
| [!UICONTROL 管理者] /トランザク [!UICONTROL ションのプロパティ] | 新しい「プロパティID」列に、各トランザクションプロパティの固有のプロパティIDが表示されます。 列の値に含まれる任意の文字列を検索できます。 |

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

Magent リリースノートについては、以下を参照してください。

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![アイコン](/assets/marketo.png) [!DNL Marketo] {#marketo}

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

## ![アイコン](/assets/experience-cloud.png)新しいドキュメントとチュートリアル {#selfhelp}

新着および最近のセルフヘルプ記事とビデオ。<!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| ソリューション | コンテンツ | 説明 |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | ビデオ - [複数のカテゴリおよび製品ページの作成](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | CIF コアコンポーネントをカスタマープロジェクトの出発点として使用して、最小限の Adobe Experience Manager（AEM）CIF プロジェクトを作成する方法を説明します。コンポーネントにテーマと CSS スタイルを適用し、アーキタイプで生成された新しい AEM CIF プロジェクトを調べます。また、CIF コアコンポーネントで使用する CSS と JavaScript の編成方法についても説明します。 |
| [!UICONTROL AEM Forms] | 記事 - [OKTA を使用して AEM Author を認証する](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | OKTA ポータルでアプリケーションを設定する方法と、新しいアプリケーションの登録で一般的に使用する設定について説明します。 |
| [!UICONTROL AEM Commerce] | チュートリアル - [CIF コアコンポーネントのカスタマイズ](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | CIF コアコンポーネントおよび AEM が提供するさまざまな拡張ポイントを確認します。CIF コアコンポーネントは、Adobe Experience Manager（AEM）と Magento ソリューションを統合するプロジェクトを加速させることができる、コマースコンポーネントの標準セットを提供します。 |
| [!DNL Adobe Campaign] - オーディエンスの宛先 | ビデオ - [オーディエンスの作成...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Adobe [!UICONTROL Experience Platform Segment Builder] を使用して、Campaign Standard にオーディエンスを作成します。この機能には、Adobe Campaign Standard 内で [!UICONTROL Audiences] モジュールをから直接アクセスでき ます。 |
| [!DNL Adobe Campaign] - オーディエンスの宛先 | ビデオ - [マーケティングワークフローでの Adobe Experience Platform オーディエンスのアクティブ化](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | [!UICONTROL オーディエンス読み取り]アクティビティを使用して、ワークフロー内で[!UICONTROL データサービスクエリオーディエンス]を有効化する方法について説明します。 |
| [!DNL Adobe Campaign] | チュートリアル - [Android でのプッシュ通知](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | パーソナライズおよびセグメント化されたプッシュ通知を iOS および Android モバイルデバイスに送信します。このチュートリアルでは、Adobe Campaign からプッシュ通知を送信し、Android アプリケーションでこれらの通知を受信する手順を説明します。 |
| [!DNL Adobe Campaign] | ビデオ - [プッシュ通知の作成](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Adobe Campaign Standard でプッシュ通知を作成します。パーソナライズおよびセグメント化されたプッシュ通知を iOS および Android モバイルデバイスに送信できます。 |
| [!DNL Adobe Campaign] - AEP データコネクタ | ビデオ - [データ取り込みジョブのステータスの確認](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | データ取り込みジョブのステータスを確認する方法、およびデータが Adobe Campaign Standard から Adobe Experience Platform に取り込まれたかどうかを確認する方法説明します。 |
| [!DNL Adobe Campaign] - AEP データコネクタ | ビデオ - [データマッピングの変更](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | ステータスの確認方法、およびデータマッピングを変更する方法を説明します。 |
| [!DNL Adobe Campaign] - AEP データコネクタ | ビデオ - [エクスペリエンスイベントのマッピング](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Adobe Experience Platform でエクスペリエンスイベントをマッピングする方法を説明します。 |
| [!DNL Adobe Campaign] - AEP データコネクタ | ビデオ - [カスタムリソースのマッピング](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Adobe Campaign Standard と Adobe Experience Platform の間で異なるデータタイプをマッピングする方法について説明します。 |
| [!DNL Adobe Campaign] - AEP データコネクタ | ビデオ - [Adobe Experience Platform データコネクタについて](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | XTK データ（Campaign で取り込んだデータ）を Adobe Experience Platform のエクスペリエンスデータモデル（XDM）データにマッピングして、データをAdobe Experience Platform で利用できるようにする方法について説明します。 |
| [!DNL Adobe Campaign] - AEP データコネクタ | ビデオ - [シードテーブルデータのマッピング](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Adobe Experience Platform でシードデータ／テストプロファイルをマッピングする方法について説明します。 |
| [!DNL Adobe Campaign]- オーディエンスの宛先 | ビデオ - [プラットフォームオーディエンスの配信のターゲットディメンションを変更する](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Adobe Campaign Standard のプライマリプロファイルテーブル以外で、プラットフォームオーディエンスに対する配信のターゲティングディメンションを変更する方法について説明します。 |
| [!DNL Adobe Campaign] | ビデオ - [Snowflake のビッグデータ管理](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Adobe Campaign Classic の Snowflake コネクタを活用します。 |
| [!DNL Adobe Campaign] - オーディエンスの宛先 | 記事 - [オーディエンスの宛先（ベータ） - 概要](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Adobe Experience Platform の一元化された統合プロファイルデータを、Adobe Campaign Standard のマーケティングキャンペーンで活用する方法について説明します。 |
| [!DNL Adobe Target] - モバイル SDK | チュートリアル - [Adobe Target でパーソナライズされたアプリケーションエクスペリエンスを提供する](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Adobe Target を自身の Android アプリケーションに実装します。Mobile Services SDK の設定を検証し、コンテンツのプリフェッチ、リクエストのブロックなどの [!DNL Target] リクエストを実装します。 |
| Adobe Analytics | ビデオ - [Adobe Summit 2019 スーパーセッション](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Summit 2019 のハイテク「スーパーセッション」の厳選された映像を見る。 |
| Adobe Analytics | ビデオ - [Customer Journey Analytics における計算指標の概要](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | [!UICONTROL Customer Journey Analytics]における[!UICONTROL 計算指標]の作成の基本的な手順を説明します。 |
| Adobe Analytics | ビデオ - [Adobe Summit 2019 スーパーセッション](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Summit 2019 の旅行およびホスピタリティセッションの厳選された動画を見る。 |
| Adobe Analytics | ビデオ - [Adobe Summit 2019 スーパーセッション](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Summit 2019 の小売セッションの厳選された動画を見る。 |
| Adobe Analytics | ビデオ - [お客様の使用例：Accent Group が、販売促進のために顧客体験に投資](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Accent Group が、Adobe Experience Cloud をどのように使用してシームレスなデジタルエクスペリエンスを作成しているかをご覧ください。 |
| Adobe Analytics | ビデオ - [お客様の使用例：ServiceNow は、適切なインサイトを入手して見込み客とつながる](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | [!DNL ServiceNow] が Adobe Advertising Cloud と Adobe Analytics を使用して、どのようにしてマーケティングチャネルから実用的なデータを取得し、有料検索広告の ROI を向上させているかを説明します。 |
| Adobe Analytics | ビデオ - [Adobe Analytics - 単なるデータではない、顧客インテリジェンス](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | データドリブン型マーケティングについて、および分析の成熟度をデータからインサイト、行動に移す方法について説明します。 |
| Adobe Analytics | ビデオ - [Adobe Sensei と Adobe Analytics - 拡張バージョン](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Adobe [!DNL Sensei,] を活用した Adobe Analytics の主な機能（[!UICONTROL 以上値検出]、[!UICONTROL 貢献度分析、][!UICONTROL インテリジェントアラート、][!UICONTROL クラスタリング]、[!UICONTROL Segment IQ、]および[!UICONTROL 傾向モデル]）を見る |
| Adobe Analytics | ビデオ - [Adobe Analysis Workspace によってビジネスが変わる仕組み](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | [!UICONTROL Analysis Workspace] を使用して、Ad Hoc Analysis、柔軟な分析、コホート分析、およびフォールアウト分析を実行する方法について説明します。また、分析作業環境を社内の全員と共有でき、ドラッグ&amp;ドロップ機能を使用すると、全員がデータを簡単に分析し、インサイトを迅速に得ることができます。 |
| Adobe Analytics | ビデオ - [お客様の使用例：Home Depot が Customer Experience Management を使用して革新](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | [!DNL Home Depot] アドビのソリューションを使用して、パーソナライズされたカスタムのショッピングエクスペリエンスにより、ブランドのロイヤルティと顧客満足度を生み出した方法を説明します。 |
| Adobe Analytics | プレゼンテーション - [Customer Journey Analytics について](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | [!DNL Adobe Experience Platform] を元に構築された Adobe のアプリケーションサービスである [!UICONTROL Customer Journey Analytics] によって、Experience Platformに [!UICONTROL Analysis Workspace] を組み込む方法について説明します。この機能を使用すると、[!DNL Adobe Experience Platform] データセットでマルチチャネル分析を使用できるようになります。 |
| Adobe Analytics | ビデオ - [CJA でのクロスチャネルアトリビューション](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | ビジュアライゼーションを使用して、[!UICONTROL Customer Journey Analytics] のチャネル間でアトリビューションを表示する（クレジットを与える）方法について説明します。 |
| Adobe Analytics | 記事 - [Adobe Analytics のラーニングジャーニーを継続するためのお客様向けヒント](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Adobe Analytics を最大限活用する方法に関するヒントやテクニックをお持ちの、アドビの 3 人のお客様を紹介します。 |
| Adobe Analytics | ビデオ - [CJA でのクロスチャネルビジュアライゼーションの作成](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | [!UICONTROL Customer Journey Analytics] を使用すれば、複数のチャネルをまたいだ複数のデータセットのデータを含むビジュアライゼーション（訪問者あたりのデータの結合を含む）を作成できます。 |
| Adobe Analytics | ビデオ - [Adobe Analytics の計算指標を Customer Journey Analytics に移行する](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | [!UICONTROL Customer Journey Analytics] で Analytics [!UICONTROLC計算指標]を再作成する際のヒントを確認します。 |

---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: c62d85f09ce596482a019aa5d0f1d517bf2df9fe

---


# Adobe Experience cloudリリースノート — 2020年2月

Adobe Experience Cloud の新機能および修正点です。

>[!NOTE]
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。リリース後に発表された新情報には、更新の日付が明記されます。

**リリース日：2020年2月20日**

（特定の製品のリリース日は自社のみ）

最新の更新：2020年2月10日

* [Adobe System Status](#status)
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

ヘルプホームをお探しの場合は、[Adobe Experience Cloud ドキュメント](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)を参照してください。

## Adobe System Status {#status}

[!UICONTROL Adobe System Status] は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

**最新情報**

* Adobe IDを使用して、製品、地域、イベントおよび言語の環境設定に基づいてイベント通知を購読できます。 購読の環境設定を行うユーザーは、製品のインシデントとメンテナンスイベントが開かれた、更新された、または閉じられた直後に通知されます。 はじめに [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit) をご覧ください。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| 製品イベントの認識の高速化 | <ul><li>今後のサービスメンテナンスの30日前に通知を受けます。 この機能により、ビジネス運営に与える潜在的な影響を評価するためのより多くのリードタイムが得られ、必要に応じて緩和計画を実装できます。</li><li>高度な通知は、Web、モバイル、タブレットの各表面で、また電子メール通知を介して使用できます。</li></ul> |
| 好みの言語に基づいてエクスペリエンスをパーソナライズ | <ul><li>電子メール通知に使用する言語を選択します。 セルフサブスクリプション機能が19言語で使用できるようになりました。</li></ul> |
| 購読と通知のユーザーエクスペリエンスの改善 | <ul><li>購読するすべての製品に対して、1回のクリックで地域とイベントの環境設定を指定します。</li><li>潜在的な問題がマイナー _またはメジ_ ャー _（主要問題）に進_ 化したら _、通知_ を受け取ります。</li><li>製品またはイベントのステータスが更新されると、ブラウザーページが自動的に更新されます。</li></ul> |

## Experience Cloud インターフェイスとコアサービス{#ecloud}

Experience Cloud インターフェイスの新機能および修正点です。管理およびコアサービス（顧客属性、オーディエンス、トリガー、cookie など）が含まれます。

**修正点**

* **** 顧客属性：顧客属性UIに、Targetで同期されたプロファイルの追加のステータスが表示されるようになりました。 （MCUI-10231）
* **** Triggersコアサービス：使用不足により、中断タイプのトリガーを作成する際の傾向スコア「30日後に戻る可能性」が削除されました。 （MCUI-10056）

### 統合製品ドメイン

アドビでは、すべての Adobe Experience Cloud アプリケーションでエクスペリエンスを統合し、向上させるために、ドメインとインターフェイスのヘッダーを更新しています。これらの機能強化は、小規模ではあっても、重要な方法でエクスペリエンスをシンプルにするように設計されています。これらの機能強化では、現在のワークフローは変更されません。

更新内容は次のとおりです。

* 新しいソリューション URL：`experience.adobe.com/<application name>`：
   * すべての製品で、最終的にこの URL パターンが採用されます。1 ヶ月間にわたって効果的な新しい URL を探します。
   * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **メモ：** Experience Cloud インターフェイスはこれらのブラウザーをサポートしていますが、個々のソリューションがすべてのブラウザーに対応しているわけではありません（例えば、[Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) は [!DNL Opera] をサポートしておらず、[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) は [!DNL Safari] をサポートしていません）。
   * （[!DNL Safari] のみ）ドメインの変更によって、[!DNL Safari] で cookie の問題が発生する場合があります。Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* 組織間または別のアプリケーション間の切り替えが容易になりました。
* 製品ヘルプの改善：ヘルプ検索にコミュニティフォーラムやビデオコンテンツの結果も含められるよう、[!UICONTROL Experience League] は製品に統合されています。この変更により、より多くのコンテンツへのアクセスが簡素化され、Experience Cloud を最大限に活用できるようになります。さらに、**[!UICONTROL ヘルプ]**／**[!UICONTROL フィードバック]**&#x200B;をクリックして問題を報告したり、アドビとアイデアを共有したりします。
* 通知の改善：[!UICONTROL 通知]ドロップダウンメニューに 2 つのタブが追加されました。1 つは独自の製品通知用、もう 1 つはグローバルな製品のお知らせ用です。

**メモ：**[!UICONTROL フィード]ページは、2020 年 1 月に廃止されます。製品内の廃止のお知らせを探してください。

製品ドキュメントについては、[Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) を参照してください。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、ID サービスおよびセキュリティ速報のリリースノートです。

* [Experience Platform リリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html)（すべてのアドビ製品）

### Experience Platform Launch {#launch}

リリースノートおよび製品ドキュメントについては、[Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) を参照してください。

## Mobile Services および Mobile SDK{#mobile}

**2020 年 2 月 5 日：バージョン 4.19.0**

このリリースでは、次の更新が行われました。

**** ライフサイクル：一部の古いiOSデバイスから `pauseCollectingLifecycleData`報告されたセッションの長さの異常データを軽減するための新しいAPIが追加されました。

## [!DNL Analytics] {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)（更新日：2020 年 1 月 22 日）
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

製品ドキュメントについては、[Adobe Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

### Adobe Analytics の新機能、機能強化および修正点 {#aa-features}

<!--* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)-->
* **デバイス間**&#x200B;分析を使用する組織向けの新しいWorkspaceテンプレート：このテンプレートは、CDAが訪問をつなぎ合わせ、CDA専用のディメンションと指標に関する教育をどの程度効果的に行うかを示します。 CDAを使用するレポートスイートが必要です。 詳しく [は、デバイス間分析の設定を参照してください](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) 。
* **** プライベートグラフを使用する組織のCDAステッチの遅延が1日に短縮されました。プライベートグラフ機能が強化され、週別のバッチ処理から日別の更新されたグラフにグラフ生成の遅延が減少し、CDAのお客様は最新のIDグラフやリンクにより多くのアクセスできるようになりました。
* **** ラボ（テクノロジープレビュー）:この新しいAnalytics機能を使用すると、新しい機能のプロトタイプを実稼働環境でテストし、アドビに貴重なフィードバックを提供できます。 [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/tech-previews/overview.html)
* **Workspaceの新しいホットキー：**<ul><li>すべてのパネルを折りたたむ/展開する： `alt + m`</li><li>アクティブパネルを折りたたみ/展開： `alt + ctrl + m`</li><li>左側のレールを検索： `ctrl + /`</li><li>次のパネルに移動： `alt + Right Key`</li><li>前のパネルに移動： `alt + Left Key`</li></ul>[詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **その他のWorkspaceの機能強化：**<ul><li>パネルまたはビジュアライゼーションを [!UICONTROL Workspaceにドロップすると]、左側のレールがコンポーネントに自動的に切り替わり、よりシームレスなワークフローが実現します。</li><li>テンプレートコンポーネントをアクションできるようになりました（例：タグ付け、お気に入りに登録、承認済み）。</li><li>フィルター適用済みの指標およびセグメントリス `+` トでは、必要な項目が見つからない場合に新しいコンポーネントを追加するボタンが提供されます。</li></ul>
* Workspaceデバ **ッガーがヘルプメニューに追加され** 、Workspaceリクエストのデバッグに対してよりシームレスに有効にできるようになりました。 [詳細情報...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md)
* **** ChromiumベースのMicrosoft edgeブラウザ：このリリースには、レポート用にChromiumベースのMicrosoft edgeブラウザー（バージョン79以降）を認識するための変更が含まれています。

#### 修正点

* 実際にはマーケティングチャネルディメンションが [!UICONTROL Data Warehouse] と互換性があるというセグメントUIの問題を修正しました 。 今後、セグメントビルダ [!UICONTROL ーでは] 、これらのディメンションが [!UICONTROL Data Warehouseと互換性があるとして表示されなくなります] 。 （AN-202297）
* Analyticsで更新された公開済みセグメントの名前が、24時間以内にAudience Managerで更新されなかった問題を修正しました。 （AN-199974）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 新しい Adobe Analytics ドメイン | 2019 年 12 月 19 日 | `https://experience.adobe.com/analytics.`<br>** 2020年1月16日、Adobe Analyticsは新しいドメインに移行し始めまし **た。注意：この変更は、Adobe IDまたはEnterprise IDを使用してAnalyticsにアクセスするすべてのユーザーに適用されます。<ul><li>ドメインの変更により、Safari で Analytics を読み込む際に cookie の問題が発生する可能性があります。Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. この問題が影響するのは Safari ユーザーのみなので、ユーザーは問題なく他のブラウザーを使用できます。</li><li>ドメインの変更により、[ある特定のケースにおいて](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)、一部の顧客に対して [!UICONTROL Activity Map] が機能しなくなる場合があります。</li></ul> |
| 提供終了 - Analytics レガシー API | 2020 年 1 月 10 日 | 2020 年 11 月に、以下の Analytics レガシー API サービスが提供終了となり、シャットダウンされます。これらのサービスを使用して構築された現在の統合は機能しなくなります。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問に対する回答と進め方に関するガイダンスを提供するために、[従来の API EOL の FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| **[!UICONTROL アーカイブを表示]** オプションのサポート終了 | 2019 年 10 月 31 日 | 2020 年 1 月に、ダッシュボードマネージャー（**[!UICONTROL コンポーネント／ダッシュボード]**）の **[!UICONTROL アーカイブを表示]** オプションのサービスを終了することをお知らせします。 |
| **[!UICONTROL IP ログイン制限の適用]** オプションのサポート終了 | 2019 年 10 月 31 日 | 2020 年 1 月に、**[!UICONTROL 管理者／会社設定／セキュリティ]** メニューの IP ログインのホワイトリストへの追加（**[!UICONTROL IP ログイン制限の実施]**）機能のサポートを終了することをお知らせします。 |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Analytics ユーザーの `createDate` フィールドに関する変更予定 | 2019 年 8 月 31 日 | 2019 年 10 月または 2019 年 11 月に、Analytics ユーザーの `createDate` フィールドが米国太平洋時刻から、タイムゾーン情報を反映した正しい形式に更新されました。（AN-183468） |

### [!DNL AppMeasurement] {#appm}

「[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)」を参照してください。バージョン2.18.0は2020年2月13日にリリースされました。

## Audience Manager {#aam}

Audience Manager に追加された修正点および機能です。

### Audience Manager の新機能、拡張機能および修正点です {#aam-features}

| 機能 | 説明 |
|----|----|
| [アクティビティ使用状況レポート](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html) | アクテ [!UICONTROL ィビティの使用状況レポートは] 、Audience Managerインスタンスのアクティビティの使用状況を表示および追跡するのに役立ち、アクティビティの使用状況と契約上のコミットメントとの比較方法を明確に把握できます。 |

### 修正点および改善点 {#aam-fixes-and-improvements}

* 宛先作成フローで、統合アカウント選択のUIが壊れる問題を修正しました。(AAM-52414)
* アルゴリズムモデル作成フロー(AAM-37942)内を移動するとUIが壊れる問題を修正しました。
* Adobe Experience Platform統合(AAM-52814)を使用しているお客様に対して、新しい宛先または既存の宛先用にデータエクスポートコントロールを保存する際に、データエクスポートの選択が保存されない問題を修正しました。
* 名前にパイプ文字(AAM-51635)が含まれる特性に対して、サードパーティの特性レコメンデーションが正しく機能しない問題を修正しました。`|`
* UI全体で複数のアクセシビリティの改善が行われました。

## Adobe Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

* **Cloud Manager 2020.2.0**

   Cloud Manager 2020.2.0は、Adobe Experience Managerのサンドボックスをクラウドサービスとしてシンプルに管理するためのツールです。

   [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)を参照してください。

### セルフサービス

* **クラウドサービスとしてのAEMのチュートリアル**

   クラウドサービスとしてのAEM [のチュートリアルを簡単に始めます](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/overview.html)。

* **AEM Formsインタラクティブ通信バッチAPI**

   AEM Formsのインタラクティブ通信のBatch APIを使用すると、顧客は自動的にまたはオンデマンドで複数のインタラクティブ通信を作成できます。 印刷出力とWeb出力を同時に生成できます。
Batch APIを使 [用した複数のインタラクティブ通信の生成を参照してくださ](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html)い。

* **JEE上のAEM Formsでサポートされるプラットフォーム**

   JEE上のAEM Formsのお客様に対するOracle 19cのサポートを追加しました。
「JEE上のAEM Forms [でサポートされているプラットフォーム」を参照してください](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html)。

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

### Campaign Classic 19.2.3

修正点と機能改善については、[Adobe Campaign Classic リリースノート](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)を参照してください。

### Campaign Standard 20.1

修正点と機能改善については、[Adobe Campaign Standard リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)を参照してください。

### その他のリソース

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)- [リリース計画](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

更新日：2020 年 2 月 11 日（2 月 9 日のリリース）

| 表示 | 機能 |
|------|---------|
| ポートフォリオ | Yahoo! ディスプレイアドネットワーク（YDN）キャンペーンをポートフォリオに追加し、キャンペーンの予算や、広告のグループレベルの入札を最適化できるようになりました。広告グループ内のすべての広告に同じ入札が適用されます。YDN キャンペーンのデータは、ポートフォリオのシミュレーションに含まれています。 |
| Search／Bulksheets | Bulksheets を使用して、Google レスポンシブ検索広告（RSA）を作成、編集、削除できるようになりました。Previously, support was available only through the standard campaign management interface at **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| Search／Campaigns, Reports | The Google Ads prominence metrics `Impr. (Abs. Top) %` and `Impr. (Top) %` are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the [!UICONTROL Campaign Daily Impression Share] and [!UICONTROL Keyword Daily Impression Share] reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

Magentoのリリースノートについては、次を参照してください。

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

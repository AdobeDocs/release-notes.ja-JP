---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 14d29e8e2baf7f09929353acbb71466eee3b0de2

---


# Adobe Experience Cloudリリースノート — 2020年4月

![バナー](/assets/experience-cloud-banner-3.png)

[!DNL Adobe Experience Cloud] の新機能および修正点です。

>[!NOTE]
>
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。リリース後に発表された新情報には、更新の日付が明記されます。

**リリース日： 年 4 月 2020 日**

（特定のリリース日は私の変わります）。

* [Adobe システムステータス](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **（リリース日の変更 — 4月15日の更新を参照）**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/ja-JP/target/using/release-notes/target-release-notes.html) (ターゲットのヘルプページへのリンク)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/jp/primetime/user-guide.html) （Primetimeのヘルプページへのリンク）

ヘルプホームをお探しの場合は、[Adobe Experience Cloud ドキュメント](https://docs.adobe.com/content/help/ja-JP/experience-cloud/user-guides/home.html)を参照してください。

## ![アイコン](/assets/adobe.png) Adobe システムステータス{#status}

[!UICONTROL Adobe システムステータス]は、アドビクラウド製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/) でご確認ください。

**最新情報**

* Adobe ID を使用して、製品オファーやアドオンレベルまで掘り下げた、より精度の高いイベント通知を登録できます。さらに、最新のリリースでは、セルフ購読プロセスで、製品の使用権限に基づいた製品とサービスの選択が推奨されるようになりました。 これにより、購読の作成に必要な決定やクリックの数を減らし、購読プロセスを合理化し、最も重要なのは、インボックスにより関連性の高い通知を配信することです。 はじめに [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit) をご覧ください。

**現在利用可能な新機能と機能強化**

| 機能 | 説明 |
| -----------| ---------- |
| 権限に基づく購読のパーソナライズ | <ul><li>ユーザーのDX購読に基づいて事前に選択されたユーザーの推奨事項。</li><li>推奨購読は、すばやく視覚化するために、製品リストの上部にハイライト表示されます。</li><li>受け取った電子メール通知は、ユーザーの製品の権利付与に関連します。</li></ul> |
| 管理の容易化購読 | <ul><li>**[!UICONTROL 「購読の管理]** 」は、製品とイベントの両方の購読を管理する新しいユーザーエクスペリエンスです。</li><li>製品とイベントの表示と編集を個別に行う新しい購読。</li><li>「削除」 **[!UICONTROL オプションを使用すると]** 、製品またはイベント購読の購読を解除できます。</li><li>「すべてを購読解除」(Unsubscribe all **** )を1回クリックすると、製品購読で使用できます。</li><li>UXのサポートは、Web/モバイル/タブレットの表面と19言語のローカライゼーションで利用できます。</li></ul> |

## ![Icon](/assets/ec_appicon_24.png) Experience Cloudインターフェイス {#ecloud}

Experience Cloudインターフェイスの新機能および修正点：

* Experience Cloud [!UICONTROL Feed] (Experience Cloud Feed)ページは非推奨になりました。 (EXC-8505)
* 新しいブランド要素を反映して、Experience Cloudのログインページが更新されました。 (EXC-10747)

製品ドキュメントについては、[Experience Cloud](https://docs.adobe.com/content/help/ja-JP/core-services/interface/experience-cloud.html) のヘルプを参照してください。

### 統合製品ドメイン

アドビでは、すべての Adobe Experience Cloud アプリケーションでエクスペリエンスを統合し、向上させるために、ドメインとインターフェイスのヘッダーを更新しています。これらの機能強化は、小規模ではあっても、重要な方法でエクスペリエンスをシンプルにするように設計されています。これらの機能強化では、現在のワークフローは変更されません。

更新内容は次のとおりです。

* 新しいアプリケーションURL: `experience.adobe.com/<application name>`:
   * すべての製品で、最終的にこの URL パターンが採用されます。1 ヶ月間にわたって効果的な新しい URL を探します。
   * ブラウザーのサポート：サポートされるブラウザーには、[!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari]、および [!DNL Opera]（最新バージョン）が含まれます。**注意：** Experience Cloudインターフェイスはこれらのブラウザーをサポートしていますが、個々のアプリケーションがすべてのブラウザーをサポートしているとは限りません。 （例えば、[Analytics](https://docs.adobe.com/content/help/ja-JP/analytics/admin/sys-reqs.html) は [!DNL Opera] をサポートしておらず、[Target](https://docs.adobe.com/help/ja-JP/target/using/implement-target/before-implement/supported-browsers.html) は [!DNL Safari] をサポートしていません）。
   * （[!DNL Safari] のみ）ドメインの変更によって、[!DNL Safari] で cookie の問題が発生する場合があります。[!DNL Safari] のプライバシー設定で「_サイト越えトラッキングを防ぐ_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Experience Cloud がこの新しいドメインで機能するようになります。
* 組織間または別のアプリケーション間の切り替えが容易になりました。
* 製品ヘルプの改善：ヘルプ検索にコミュニティフォーラムやビデオコンテンツの結果も含められるよう、[!UICONTROL Experience League] は製品に統合されています。この変更により、より多くのコンテンツへのアクセスが簡素化され、Experience Cloud を最大限に活用できるようになります。さらに、**[!UICONTROL ヘルプ]** ／ **[!UICONTROL フィードバック]**&#x200B;をクリックして問題を報告したり、アドビとアイデアを共有したりします。

## ![アイコン](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Javerny Orchestration [!DNL Experience Platform,] 、People [!DNL Experience Platform Launch,] 、Pople、Places、Mobile Services、Security Bullinsを含むリリースノート [!UICONTROL を]参 照してください。

### ジャーニーオーケストレーション {#journey}

Adobe Experience Platform を使用すると、それぞれの顧客のニーズをリアルタイムでインテリジェントに予測し、どのようなジャーニーをたどっていても、個別カスタマージャーニーをエクスペリエンスチャネル全体で大規模に編成することができます。

* [ドキュメント](https://docs.adobe.com/content/help/ja-JP/journeys/using/journey-orchestration-home.html)
* [リリースノート](https://docs.adobe.com/content/help/ja-JP/journeys/using/release-notes/release-notes.html)
* [ハウツービデオ](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services および Mobile SDK {#mobile}

Android 4.18.2（2020年4月3日）:

* アプリ内メッセージ：セキュリティ上の理由から [!UICONTROL 、SDK] によって作成された `setAllowFileAccess` WebViewsは、プロパティを _falseに設定するようになりました_。

iOS 4.19.2（2020年3月24日）:

* 一般：コードの漏れを修正し [!DNL Target] ました。

Unity 4.19.0（2020年3月10日）:

* iOSのバ [!UICONTROL ージョン4.19.0および4.18.0またはを使用するようにUnity Pluginを更新しまし][!DNL Android]た。
* 新しい獲得方法が公開され、 [!DNL Android] 転送者APIが提供するURLの処理を可能に [!DNL Google Play] します。

### Experience Platformのその他のリリース情報

* [Experience Platform Launchリリースノート](https://docs.adobe.com/content/help/ja-JP/launch/using/intro/release-notes/current.html)。
* [Experience Platformリリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [セキュリティ速報および情報](https://helpx.adobe.com/jp/security.html)（すべてのアドビ製品）

## ![アイコン](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>Adobe Analyticsの4月のメンテナンスリリースは、2020年5月22日に移行されました。 Analyticsの最新のリリース情報について詳しくは、3月のリリースノ [ートを参照してください](c-legacy-releases/2020/03122020.md)

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Analytics管理者向けの重要な注意](#aa-notices) （更新日2020年4月7日）
* [AppMeasurement](#appm)
* [新しいAnalyticsチュートリアル](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| 機能 | 説明 |
| -----------| ---------- |
| [!UICONTROL 顧客の遍歴分析]:自動データセットのバックフィル | この新しいオプションを使用すると、 [!UICONTROL Customer Jeurney Analyticsの接続に関するすべての履歴データをインポートできます]。 [詳細情報](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html) |

<!--### New features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
 |[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace] | 2020 年 4 月 8 日 | [!UICONTROL 分析ワークスペース]（2020年3月現在）では、「なし」の値と入口 _/出口との相互作用方法を_ 変更しました 。 Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. 例えば、訪問の最初のヒットにeVarの値がなく、2番目のヒットにeVarの値がないとします。 [!UICONTROL Reports &amp; Analytics] (Reports &amp; Analytics _)ではエントリに対して「未指定」と表示されますが、_ 分析ワークスペースでは  2回目のヒットの値として表示されます。 |
| **[!UICONTROL コンバージョンレベル]**&#x200B;設定のサポート終了 | 2020 年 3 月 4 日 | The non-functioning [Conversion Level](https://docs.adobe.com/content/help/ja-JP/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020. |
| **[!UICONTROL ダッシュボードアーカイブ]**&#x200B;のサービス終了 | 2020 年 3 月 28 日 | [!UICONTROL Reports &amp; Analytics] の「**[!UICONTROL ダッシュボードを管理]**」の「**[!UICONTROL アーカイブを表示]**」設定は、2020 年 10 月から使用できなくなります。 |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| 新しい Adobe Analytics ドメイン | 2019 年 12 月 19 日 | 2020 年 1 月 17 日に、Adobe Analytics は新しいドメインへの移行を開始しました。`https://experience.adobe.com/analytics.`<br>**メモ&#x200B;**：この変更は、Adobe ID または Enterprise ID を使用して Analytics にアクセスするすべてのユーザーに適用されます。<ul><li>ドメインの変更により、Safari で Analytics を読み込む際に cookie の問題が発生する可能性があります。[!DNL Safari] のプライバシー設定で「_サイト越えトラッキングを防ぐ_」をオフにすると、ドメイン（およびすべてのクロスサイトエクスペリエンス）間で cookie が有効になり、Analytics がこの新しい Adobe Experience Cloud ドメインで機能するようになります。この問題が影響するのは [!DNL Safari] ユーザーのみなので、ユーザーは問題なく他のブラウザーを使用できます。</li><li>ドメインの変更により、[ある特定のケースにおいて](https://docs.adobe.com/content/help/ja-JP/analytics/analyze/activity-map/activity-map.html)、一部の顧客に対して [!UICONTROL Activity Map] が機能しなくなる場合があります。</li></ul> |
| 提供終了 - Analytics レガシー API | 2020 年 1 月 10 日 | 2020 年 11 月に、以下の Analytics レガシー API サービスが提供終了となり、シャットダウンされます。これらのサービスを使用して構築された現在の統合は機能しなくなります。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>従来の OAuth 認証（OAuth および JWT）</li></ul>ご質問に対する回答と進め方に関するガイダンスを提供するために、[従来の API EOL の FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) を用意しています。これらのサービスを使用する API 統合は、[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) または [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) に移行できます。従来の OAuth アカウントは、[Adobe IO](https://console.adobe.io/home?mv=email) Analytics 統合アカウントに移行できます。このアカウントは、1.4 Analytics API と 2.0 Analytics API の両方にアクセスするために使用できます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis のサポート終了 | 2018 年 8 月 7 日 | アドビは Ad Hoc Analysis のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。詳しくは、[Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) を参照してください。 |

### [!DNL AppMeasurement] {#appm}

「[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/appmeasurement-updates.html)」を参照してください。バージョン 2.20.0 は 2020 年 3 月 6 日にリリースされました。

### 新しいAnalyticsチュートリアル {#tutorials-analytics}

| コンテンツ | 説明 |
| -----------| ---------- |
| [Adobe Labs(テクノロジープレビュー)とAdobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs(テクノロジープレビュー)を使用すると、新しいテクノロジーとの関わり合い、貴重な洞察の発見、将来の機能の開発と優先 [!DNL Analytics] 順位への影響を実現できます。 |
| [Experience Cloudオーディエンスの投稿の改善](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Experience Cloudオーディエンスの公開 [!UICONTROL が改善されました]。 オーディエンス（セグメント）を公開し、6倍の速さで利用できるようになりました。 これにより、現在の待ち時間が48時間から約8時間に短縮され、トラフィックやセグメントのサイズに応じて、場合によっては速くなります。 |
| [分析ワークスペース内の複数のレポートスイート](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | パネルレベルでレポートスイートを選択することで、1つの [!UICONTROL Workspace] Projectで複数のレポートスイートを分析できます。 これにより、異なるデータセット間で並べてパネルの分析を行うことができます。 |

製品ドキュメ [ントについては、Adobe Analyticsヘルプホーム](https://docs.adobe.com/content/help/ja-JP/analytics/landing/home.html) （英語のみ）を参照してください。

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

Adobe Digital Managerの新機能および修正点：

| 機能 | 説明 |
| -----------| ---------- |  
| [最も多いカスタマーサポートの問題](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | ドキュメントポータルに新しいセクションを追加しました。このセクションには、カスタマーサポートチームが最も頻繁に寄せる質問に対する回答が含まれています。 |

* モバイルデバイスIDを含むセグメントのアドレス可能な [オーディエンスのレポート](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) が正しくない問題を修正しました。 この更新後、アドレス指定可能なオーディエンスが増える場合があ [ります](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html)。
* 「  重複テスト [!UICONTROL 」ボタンと「] 重複割り当て [!UICONTROL オーディエンス] 」ボタンが機能しない問題を修正しました。 （AAM-53388）
* 宛先がUUIDをエクスポートするように設定さ [!UICONTROL れている場合] 、「一致率」と「セグメントアドレス可能なオーディエンス  」が「0」と表示される問題を修正しました。 一致率 [!UICONTROL とセグメン] トアドレス可能なオーディエンス  (Match Rate)が100%と表示されるようになりました。 （AAM-51615）
* 特殊文字を含む特性名が2回HTMLエンコードされる問題を修正しました。 （AAM-54001）
* 一部のユーザーがユーザーインターフェイスから他のAdobe Experience Cloudアプリケーションに切り替えられない問題を修 [!DNL Audience Manager] 正しました。 （AAM-52917）
* 一部のユーザーがPeopleベースの宛先用にSHA256データソースを作成できない問題を修正しました。 （AAM-53525）
* インターフェイス全体で複数のアクセシビリティの改善。 （AAM-48986、AAM-49009、AAM-48984、AAM-48939、AAM-48940、AAM-48964、AAM-49032、AAM-49360）

## ![Icon](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### セルフサービス

* **AEMニュースレター**

   最新の [Adobe Experience Managerニュースレターを参照してください](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)。

* **AEMをクラウドサービスとして — ダイナミックメディアクラウドサービスの設定**

   ダイナミックメディアクラウドサービスを設定する際に、次の新しいオプションを使用できます。

   **一部のみの公開** — このオプションを選択すると、アセットは安全なプレビューのためにのみ自動公開され、公開ドメイン内の配信用にDMS7に公開することなく、AEMに明示的に公開できます。

   See [Configuring Dynamic Media Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **ダイナミックメディア — スマートイメージング**

   スマートイメージングのヘルプトピック全体が更新され、追加されたスマートイメージングの最適化を示す画像アセットの例を含む新しい情報が追加されました。

   スマートイメ [ージングを参照](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html)。

* **ダイナミックメディアの設定 — Scene7モード**

   新しい「すべてのコンテンツを同期」オプションが、ツール/クラウドサービスのダイナミックメディア設定ペ **[!UICONTROL ージで使用できるようになりました]**。

   ダイナミック [メディア設定の作成を参照してください](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)。

* **AEM Assets Brand Portalは、AEM Assetsをクラウドサービスとしてサポートします。**

   AEM AssetsからクラウドサービスとしてAEM Assets Brand Portalにアセットを公開できるようになりました。

   Brand PortalでのAEM [アセットの設定](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) 、Brand Portalでのアセ [ットの公開を参照してください](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html)。

* **Adobe Asset Link 2.0のリリース**

   Adobe Asset Link 2.0は、複数のAEM環境の操作をサポートし、AEMをクラウドサービスとしてサポートします。 AEMは、Adobe Asset Linkを使用してアセットをフォルダーにアップロードする場合、マーケターがアセット処理ワークフローの自動実行を設定する必要があることをサポートしています。

   See [Adobe Asset Link](https://helpx.adobe.com/jp/enterprise/using/adobe-asset-link.html).

### Experience Managerの新しいチュートリアル

| コンテンツ | 説明 |
| -----------| ---------- |  
| [ローカルディスパッチャーツールの設定](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | ディスパッチャーをローカルで設定、検証、シミュレーションする方法につ [!UICONTROL いて] 、説明します。 |
| [AEMプロジェクトの開発ツールの設定](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Adobe Experience Manager (AEM)の開発では、開発者用マシンに最低限の開発ツールのセットをインストールして設定する必要があります。 これらのツールは、AEMプロジェクトの開発と構築をサポートします。 |
| [ローカルAEMランタイムの設定](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager(AEM)は、AEMをクラウドサービスSDKの [!UICONTROL QuickStart Jarとして使用して、ローカルで実行できます]。 これにより、開発者は、カスタムコード、設定およびコンテンツをソース管理にコミットする前に、そのコード、設定およびコンテンツをデプロイおよびテストし、クラウドサービス環境としてAEMにデプロイできます。 |
| [ナビゲーション](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | AEM Assetsのナビゲーションの基本を学びます。 |
| [バージョン](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | AEMがアセットのバージョンを作成し、維持する方法を確認します。 |
| [AEM - [!DNL Magento] [!UICONTROL Commerce Integration Frameworkを使用した統合]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | このビデオでは、AEMとの統合の設定手順を説明します [!DNL Magento]。 |
| [AEMアーキテクチャスタックの概要](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIFプロジェクトのアーキタイプは、CIFコアコンポーネントを使用する顧客プロジェクトの出発点として、最小限のAdobe Experience Manager(AEM)CIFプロジェクトを作成します。 |
| [OSGiの概要](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Adobe Experience Managerの基盤となるJavaアプリケーション用の動的なモジュラーアーキテクチャであるOSGiの紹介です。 |
| [Java Content Repository(JCR)の概要](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Adobe Experience Managerで使用される[Java Content Repository(JCR)の概要です。 |
| [Slingの概要](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Adobe Experience Managerの基盤と [!DNL Sling]なるテクノロジースタックの一部である、オープンソースのRESTful Webフレームワークの紹介です。 |
| [作成者と公開層の概要](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Adobe Experience Managerのアーキテクチャ [!UICONTROL の一部と] して  、作成者層と発行層の概要を説明します。 |
| [ディスパッチャーの概要](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | AEMアーキテクチャの一部としてのディスパッチャーの機能と機能の紹介です。 |
| [コンポーネント開発の概要](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Adobe Experience Manager Sitesを使用したコンポーネントの開発の概要です。 ダイアログ、Slingモデル [!UICONTROL 、]HTLスクリプト [!UICONTROL 、および]Side Librariesクライアントの概要が含まれます。 |
| [AEM プロジェクトアーキタイプ](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | AEMプロジェクトには、実装のすべてのコードと設定が含まれています。 The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [コアコンポーネントについて](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEMコア [!UICONTROL コンポーネント] は、Adobe Experience Managerで使用する標準セットコンポーネントです。 |
| [AEM Quickstart Jarの使用](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | [!UICONTROL AEM Quickstart jarを使用して、Adobe Experience Managerのローカルインスタンスを数分でインストールし、実行する方法を説明します]。 |

### その他のヘルプリソース

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/ja-JP/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/jp/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/jp/experience-manager/cloud-manager/user-guide.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/jp/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/ja-JP/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://docs.adobe.com/content/help/ja-JP/livefyre/using/release-notes/c-rn.html)

## ![アイコン](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html)

### 新しいキャンペーン標準のチュートリアル {#tutorials-acs}

| コンテンツ | 説明 |
| -----------| ---------- |  
| [プロファイルの置き換え — ターゲットを設定したメッセージを使用した電子メールプロファイルのテスト](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | 電子メールメッセージの置き換え機能を使用してプロファイルをテストします。 |

### その他のキャンペーンヘルプリソース

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/jp/support/campaign/standard.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)- [リリース計画](https://helpx.adobe.com/jp/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/jp/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/ja-JP/RN.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign コントロールパネル：[ドキュメント](https://docs.adobe.com/content/help/ja-JP/control-panel/using/control-panel-home.html) - [リリースノート](https://docs.adobe.com/content/help/ja-JP/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![アイコン](/assets/magento.png) [!DNL Magento] {#magento}

Magent リリースノートについては、以下を参照してください。

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![アイコン](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] は、複雑な購入の遍歴のあらゆる段階を通じて顧客体験を変えようとしている、リード管理とB2Bマーケター向けの完全なアプリケーションです。

### Core Marketo Engage の更新

詳しくは、 [!DNL Marketo] リリ [ースノート](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) を参照してください。

### 予定されている機能

今四半期を通じて、次の機能がリリースされます。

| 機能 | 説明 |
|------|---------|
| [!DNL Bizible] | <ul><li>新しいアカウントベースのセグメント化</li><li>ダッシュボード固有のフィルターの保存</li><li>Bizbile ダッシュボードを PDF 形式で書き出し</li></ul> |
| Sales Connect | ウィンドウとコマンドセンターの構成の更新／機能強化 |

### 発表

**Marketo Engage サクセスセンター：** 2020 年 2 月に立ち上げ予定。サクセスセンターは製品内ヘルプセンターで、製品ドキュメントとコミュニティの検索、ハウツーガイドの起動、導入コンテンツへのアクセスなどをおこなうことができます。注意：この機能は ANZ でベータ版として開始され、四半期の後半に北米で公開予定です。

### 廃止

* **アセットAPI &quot;_method&quot;パラメータ：** 2020年9月以降、アセットAPIエンドポイントは、URIの長さ制限を回避す `_method` るために、POST本文でクエリパラメーターを渡すことを受け入れなくなります。
* **Internet Explorer のサポートの廃止：** 2020 年 7 月 31 日のリリース以降、Marketo Engage ユーザーインターフェイスは Internet Explorer でサポートされなくなります。

これまでのリリースノートと過去のリリースノートについては、[Marketo リリースノート](https://docs.marketo.com/x/CgA6Ag)を参照してください。

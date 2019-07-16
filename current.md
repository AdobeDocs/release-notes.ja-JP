---
title: Adobe Experience Cloud リリースノート
description: 2019年7月のExperience Cloudリリースノート
doc-type: リリースノート
last-update: 2019 年 7 月
author: mfrei
translation-type: tm+mt
source-git-commit: b4a91b853cfb5d228fc2195d65b4370e607475f2

---


# 早期アクセス - Adobe Experience Cloud のリリースノート

Adobe Experience Cloud の新機能および修正点です。

>[!IMPORTANT]
>
>このページに記載される内容は、リリース前のコンテンツに関するもので、リリース予定日の前に変更される可能性があります。

>[!NOTE]
>
>[Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。通知はリリースの 3～5 営業日前に届きます。リリース後に発表された新情報には、更新の日付が明記されます。

**リリース日：2019 年 7 月 18 日**

* [Experience Cloud コアサービスと管理](#experiencecloud)
* [!DNL Analytics](#analytics)**（更新日7月15日）**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard／Premium 19.6.1](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

[!UICONTROL Platform] コアサービスや製品管理など、Experience Cloud インターフェイスのリリースノートです。

* [Experience Cloud ID サービス](#ecid)
* [Mobile Services および Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [セキュリティ速報と情報](#security)

### Experience Cloud ID サービス {#ecid}

**修正点と更新点**

* `cookieDomain` config update: `cookieDomain` イン `initConfig` サイトが設定されていない場合、ライブラリは自動的にトップレベルのcookieドメインを割り当てます。（CORE-29223）
* `getVisitorValue` で `localVisitor`の問題を修正しました。（CORE-31287）
* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. （CORE-29719）
* jQuery3.2.1の脆弱性の問題を修正しました。（CORE-31183）
* Opt-in update: added `optIn.off` to unsubscribe from events.
* `setTimeout` 関数に関する問題を修正しました。（CORE-30623）

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services および Mobile SDK {#mobile}

iOSとAndroidは次のように更新されました。

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target:メモリリークを修正。
* Visitor ID Service: The `visitorAppendToURL` and `visitorGetUrlVariablesAsync` APIs no longer double-encode their return values. 二重エンコーディングでは、これらのAPIからの戻り値が特定のセキュリティレビューによってフラグ付けされていました。

**Android**

* ターゲット:すべてのリクエストに、URLクエリパラメーターにクライアントとsessionIdが含まれるようになりました。
* アプリ内メッセージ:空のクリックスルーURLでメッセージがトリガーされるとAndroidアプリがクラッシュする問題を修正しました。
* Visitor ID Service: The `Visitor.appendToURL` and `Visitor.getUrlVariablesAsync` APIs no longer double-encode their return values. 二重エンコーディングでは、これらのAPIからの戻り値が特定のセキュリティレビューによってフラグ付けされていました。

For product documentation, see [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

For more information about the Mobile SDKs, see: [Android SDK 4.x for Experience Solutions](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) and [iOS SDK 4.x for Experience Cloud
Solutions](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Adobe Analyticsの新機能および修正](#aa-features)**点（更新日15月15日）**
* [Analytics 管理者向けの重要な注意事項](#aa-notices)

###  の新機能：[!DNL Analytics]{#aa-features}

製品ドキュメントについては、[Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

| コンポーネント | 説明 |
| -----------| ---------- |   
| Analysis Workspace-コホート分析の強化 | 新しいコホート分析設定が追加されました。 <ul><li>%のみ表示</li><li>丸め%から最も近い整数</li><li>トップの平均%行を表示</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. 以前は、ルックバック期間は最大6か月でした。これにより、昨年から18か月前までのページやキャンペーンと比較しやすくなります。 |
| 新しいAnalysis Workspaceテンプレート | &quot;Magenting&quot;という新しいテンプレートを追加しました。マーケティングとコマース」を分析ワークスペースに追加します。これは、Magenting eコマースのお客様向けに設計されていますが、小売業者はこれを使用して、コマースアクティビティに対する独自のインサイトを得ることができます。 |

#### [!DNL Analysis Workspace] 修正点

* ディメンションを分類すると、マルチバイト文字が上下に表示される問題を修正しました。（AN-180112）
* ビジュアライゼーションエラーの問題を修正しました。ビジュアライゼーションエラーが発生したときに赤いエラーバーが表示されるようになりました。（AN-175542）
* ローカライズ環境でディメンション名が英語として表示される問題を修正しました。（AN-178695）

#### [!DNL Analytics] 修正点

* リアルタイムドリルダウンレポートの折れ線グラフが空白になる問題を修正しました。（AN-181690）
* 状況によって、データフィード履歴の一部が管理コンソールUIに表示されない問題を修正しました。（AN-176219）

### [!DNL Analytics] 管理者向けの重要な注意事項{#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 分類ルールビルダーの制限 | 追加日：2019 年 6 月 5 日 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| 新しいセグメント演算子の制限 | 追加日：2019 年 5 月 31 日 | 2019 年 7 月 18 日以降、セグメント演算子「次のいずれかを含む」、「次のいずれかを含まない」、「次のすべてを含む」および「次のすべてを含まない」は、入力フィールドあたり 100 語に制限されます。この制限は、この日以降、すべての新しいセグメントおよび変更されたセグメントに適用されます。制限を超過している既存のセグメントは、引き続きサポートされますが、入力フィールドが減らされるまで変更または保存できません。これらの制限は、クエリパフォーマンス向上のための継続的な取り組みの一環として適用されています。 |
| **[!UICONTROL 日付分類]** および **[!UICONTROL 数値 2 分類]** に関するサポートの変更予定 | 2019 年 5 月 28 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。この変更は 2019 年 7 月のメンテナンスリリースから有効になります。「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。<br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポートの合計_の計算に対して予定されている変更 | 更新日2019年7月9日 | On **June 18, 2019**, Adobe Analytics will make _Report Total_ calculations consistent across all dimensions and metrics. これにより、一部のレポート（通常、Prop または顧客属性レポート）の合計が変更されます。この変更以前は、レポートに_未指定_が表示されているかどうかにかかわらず、合計に_未指定_の行項目を含めるレポートと含めないレポートが混在していました。<br/>2019 年 6 月 18 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the &quot;Typed/Bookmarked&quot; line item for Referrer Type dimension or the &quot;Other&quot; line item for the Device Type dimension. この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| [!DNL Analysis Workspace] CSV ダウンロード機能の更新点 | 2019 年 4 月 10 日 | 2019 年 4 月 11 日以降、**[!UICONTROL CSV ダウンロード]** および **[!UICONTORL クリップボードへのコピー]**（[!DNL Analysis Workspace]）にいくつかの変更が加えられ、書き出されたデータから書式が削除されます。  <ul><li>桁区切り記号は含まれなくなりました。小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]** で定義された形式が適用されます。注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。パーセンテージは 10 進形式になります。例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| [!DNL Analysis Workspace] Debugger コマンドの変更 | 2019 年 4 月 4 日 | [!DNL Analysis Workspace] Debugger をオンにするためのコンソールコマンドは、**2019 年 6 月 13 日** に adobeTools.debug.includeOberonXml に変更されます。この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 7 日 | 2019 年 1 月 8 日より、モバイルブラウザーバージョン番号を 2 桁から 1 桁に変更しました。この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| [!DNL Ad Hoc Analysis] のサポート終了 | 2019 年 1 月 29 日 | 2018 年 8 月 7 日、アドビは [!DNL Ad Hoc Analysis] のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。<br/>サポート終了の予定や詳細については [Discover Workspace](https://adobe.ly/discoverworkspace) を参照してください。 |
| Short [!DNL Analytics] report links | 2019 年 1 月 14 日 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| TLS 1.0 のサポート終了 | 2019 年 1 月 10 日更新 | 2019 年 2 月 11 日現在、Adobe Analytics レポートで TLS（Transport Layer Security）1.0 の暗号化がサポートされなくなっています。この変更は、最高レベルのセキュリティ基準を維持して、お客様のデータの安全を確保するための継続的な取り組みの一環です。If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>[!DNL Analytics]2019 年 2 月 20 日以降、Adobe のデータ収集で TLS 1.0 がサポートされなくなりました。この変更により、TLS 1.1 以上をサポートしていない旧型のデバイスや Web ブラウザーを使用しているエンドユーザーの Analytics データは収集されなくなりました。この変更が、お客様の顧客のデータやレポートに大きな影響を及ぼすことはないと認識しています。（お客様の Web サイトが既に TLS 1.0 をサポートしていない場合、影響は一切ありません。）<br/>2019 年 4 月 11 日以降、Adobe Analytics レポート API は TLS 1.0 の暗号化をサポートしていません。API にアクセスするお客様は、この変更による影響の有無を確認してください。 <ul><li>デフォルト設定で Java 7 を使用している API クライアントは、[TLS 1.2](https://www.java.com/en/configure_crypto.html) をサポートするように変更してください（「_Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2_」を参照、ブラウザーの翻訳機能をお使いください）。 </li><li>Java 8 を使用している API クライアントは、デフォルト設定が TLS 1.2 なので、影響を受けません。</li><li> その他のフレームワークを使用している API クライアントは、TLS 1.2 のサポートについてベンダーにお問い合わせください。</li></ul> |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。この変更は、処理中に post_product_list に追加されるマーチャンダイジング eVar 値により、製品および売上高の値の切り捨てが発生しないようにします。post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 KB に達した時点で値を切り捨てるようにしてください。 |
| [!DNL Analytics Live Stream] エンドポイントの管理における変更点 | 2018 年 12 月 20 日 | 2019 年 2 月 1 日以降、顧客からのアクティブな接続が 90 日間なかった [!DNL Live Stream] エンドポイントが無効化される場合があります。使用中の [!DNL Live Stream] エンドポイントについてはサポートに問い合わせて確認でき、必要に応じて再度有効にすることができます。また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 7 日 | TLS 1.0 のサポート終了に伴い、[!DNL Report Builder] ユーザーの皆様には 2019 年 2 月までにバージョン 5.6.21 をダウンロードされることをお勧めします。この日以降、以前のバージョンの [!DNL Report Builder] は機能しなくなります。 |

### AppMeasurement {#appm}

2019年7月16日リリース

**JavaScript 2.15.0**

* AppMeasurememtにDIL7.2が追加されました。（AN-175142）
* Experience Cloud IDサービスのoptInがtrueに設定されていて、ページをリロードせずにs. t（）呼び出しでMIDが生成されなかった問題を修正しました。（CORE-30890）

See [AppMeasurement release history](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) for a release history of AppMeasurement on the following platforms:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone、Xbox、Silverlight および .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

### Data Workbench {#aa-dwb}

* [ログ（X、B）](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) 指標構文のドキュメントのヘルプ定義を更新しました。（AN-180527）

最新のリリース情報については、[Data Workbench リリースノート](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/)を参照してください。

## Audience Manager {#aam}

**修正点および機能強化**

* [!UICONTROL セグメントの概要] ページで、セグメントストレージフォルダーの幅が柔軟になりました。これにより、より長い名前でセグメントを区別できます。（AAM-48400）
* [!UICONTROL アルゴリズムモデル]で、リーチおよび正解率 **** スライダーを動かすとモデルのリーチまたは正解率に影響しなかった問題を修正しました。（AAM-47996）
* Analyticsの宛先で、データエクスポートコントロールやサードパーティのデータ共有ポリシーと競合するセグメントの. csvファイルをダウンロードするためのボタンが壊れていた問題を修正しました。（AAM-48100）
* Audience Managerユーザーインターフェイスにログインすると、ランダムな「アクセス拒否」エラーが表示される問題を修正しました。（AAM-47632）

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

次の製品の新機能情報。

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Cloud Manager 2019.6.0 のリリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### XMLドキュメント3.4

XML Documentation3.4ソリューションが利用できるようになりました。

***リリースノート***

* AEM6.5のサポートが追加されました。
* エディターの変更:
   * マップレベルのプレビュー
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * テーブル-列内の複数のセルを選択し、それらのセルを連結または結合するオプションが提供されます。
   * テーブル- Webエディターの作成者モードでテーブルの列プロパティを設定する方法を提供します。
   * テーブル-標準テーブルでの列の縦横比とサイズを調整できます。
   * テーブル-作成者ビューで行と列を選択します。
   * テーブル- Webエディターでテーブルセルの整列用にスタイルとプロパティ（整列、バビング）を有効にします。
   * コンテンツのコピー&amp;ドロップおよびドラッグ&amp;ドロップに関するバグを含む、フルタグ表示のバグ修正。
   * エディタータブでトピックタイトルを表示します。
   * Webエディターでパフォーマンスの問題を解決しました。
* 翻訳中の翻訳済みコンテンツにベースラインを転送します。
* 翻訳のワークフロー中のトランスファー条件プリセット。
* ベースラインからマップのすべての依存関係にラベルを適用する機能を追加しました。
* すべての依存関係をzipとしてダウンロードするためのボタンを提供しました。
* XHTMLからDITAへの変換の改善:
   * 生成されたDITAMAPの名前が、アップロードされたzipファイルの名前と同一になりました。
   * 追加のHTML要素および属性のサポートを追加しました。
   * 同時HTML- zipファイル取り込みのサポート。
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* 提供された監査ログを確認して、バージョンと理由に戻ります。
* AEMサイトの再生成:
   * サブマップの再生成を無効にします。
   * 再生成の使用に関するワークフローが有効になりました。
   * チャンクトピックの再生成オプションを無効にし、チャンク属性が適用されている親トピックでオプションを使用できるようにします。
* AEMアセット検索のANDロジックでDITA検索が機能するようになりました。
* 変換出力フォルダーに保存されている一時ファイルを表示しません。
* 「ベースライン」タブ:
   * ベースラインを開く際のパフォーマンスが改善されました。
   * クライアントのタイムスタンプで機能する日付でトピックを選択する。
* ラベルを削除するためのAPI。

#### 製品メンテナンス

**AEM 6.2 SP1-CFP20**

2019年6月6日リリースのAEM6.2Service Pack1-累積Fix Pack20（6.2.1.20）は、2016年12月1日のAEM6.2SP1の一般リリース以降にリリースされた主なお客様修正を含む重要なアップデートです。

* [リリースノート](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

2019年7月3日リリースのAEM6.3.3.5は、2017年4月4日のAEM6.3の一般リリース以降にリリースされた主なお客様修正を含む重要なアップデートです。

* [リリースノート](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

2019年7月3日リリースのAEM6.4.5.0は重要なアップデートであり、2018年4月のAEM6.4の一般リリース以降にリリースされた主なお客様向け修正を含む重要なアップデートです。

* [リリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

2019年7月3日リリースのAEM6.5.1.0は重要なアップデートであり、2019年4月のAEM6.5の一般リリース以降にリリースされた主なお客様向け修正を含む重要なアップデートです。

* [リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### セルフサービス

**AEMキャッシュの無効化の更新**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

### その他のリソース

* [AEM 6.5 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

リリースノートについては、以下を参照してください。

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

製品ドキュメントについては、以下を参照してください。

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 機能のビデオ](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 機能のビデオ](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

Magentce CommerceおよびMagenting Open Sourceリリースノートについては、以下を参照してください。

* [Magenting Open Source2.3.2リリースノート](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magenting Commerce2.3.2リリースノート](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)

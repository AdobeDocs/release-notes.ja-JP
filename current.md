---
title: Adobe Experience Cloud リリースノート
description: 2019 年 7 月 Experience Cloud リリースノート
doc-type: リリースノート
last-update: 2019 年 7 月
author: mfrei
translation-type: tm+mt
source-git-commit: c45b9f49e0732e52b01677c0acb8e6b12d155e77

---


# Adobe Experience Cloud リリースノート

Adobe Experience Cloud の新機能および修正点です。

>[!NOTE]
>
>[Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。通知はリリースの 3～5 営業日前に届きます。リリース後に発表された新情報には、更新の日付が明記されます。

**リリース日：2019 年 7 月 18 日**

* [Experience Cloud コアサービスと管理](#experiencecloud)
* [!DNL Analytics](#analytics) - **（更新日7月15日）**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard／Premium 19.6.1](#target)
* [Magento](#magento)

## Experience Cloud コアサービスと管理 {#experiencecloud}

[!UICONTROL Platform] コアサービスや製品管理など、Experience Cloud インターフェイスのリリースノートです。

* [Experience Cloud ID サービス](#ecid)
* [Mobile Services および Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](#security)

### Experience Cloud ID サービス {#ecid}

**修正点および更新**

* `cookieDomain` 設定の更新：`initConfig` の `cookieDomain` が設定されていない場合、トップレベル cookie ドメインを自動的に割り当てるようになりました。（CORE-29223）
* `localVisitor` の `getVisitorValue` に関する問題を修正しました。（CORE-31287）
* `getVisitorValue` メソッドによって得られる `MCOPTOUT` 値が ifame の親フレームと子フレームで一致しない問題を修正しました。（CORE-29719）
* jQuery 3.2.1 の脆弱性の問題を修正しました。（CORE-31183）
* オプトインの更新：イベントから登録解除するための `optIn.off` を追加しました。
* `setTimeout` に関する問題を修正しました。（CORE-30623）

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services および Mobile SDK {#mobile}

iOS および Android は次のように更新されました。

**iOS**

* Adobe Target：すべてのリクエストで、URL クエリパラメーターにクライアントおよび `sessionId` が含まれるようになりました。
* Adobe Target：メモリリークを修正しました。
* 訪問者 ID サービス：`visitorAppendToURL` および `visitorGetUrlVariablesAsync` API は、戻り値を二重エンコードしなくなりました。二重エンコードが原因で、API からの戻り値がセキュリティ診断によってリスクありと判断されることがありました。

**Android**

* Target：すべてのリクエストで、URL クエリパラメーターにクライアントおよび sessionId が含まれるようになりました。
* アプリ内メッセージ：空のクリックスルー URL でメッセージがトリガーされた場合に Android アプリがクラッシュする問題を修正しました。
* 訪問者 ID サービス：`Visitor.appendToURL` および `Visitor.getUrlVariablesAsync` API は、戻り値を二重エンコードしなくなりました。二重エンコードが原因で、API からの戻り値がセキュリティ診断によってリスクありと判断されることがありました。

For product documentation, see [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

For more information about the Mobile SDKs, see: [Android SDK 4.x for Experience Solutions](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) and [iOS SDK 4.x for Experience Cloud
Solutions](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### セキュリティ速報および情報 {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Adobe Analytics の新機能および修正点](#aa-features)**（更新日：7 月 15 日）**
* [Analytics 管理者向けの重要な注意事項](#aa-notices)

### [!DNL Analytics] の新機能 {#aa-features}

製品ドキュメントについては、[Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

| コンポーネント | 説明 |
| -----------| ---------- |   
| Analysis Workspace – コホート分析の機能強化 | [新しいコホート分析設定](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/cohort-table/t-cohort.html) が追加されました。 <ul><li>パーセントのみ表示</li><li>四捨五入率（最も近い整数）</li><li>平均パーセント行を表示</li></ul> |
| Analysis Workspace | 左側のレールに、_過去 18 ヶ月の項目を表示_&#x200B;するためのオプションが追加されました。以前は、ルックバック期間は最大 6 ヶ月でした。これにより、昨年のページやキャンペーンとの比較が簡単になります（最大 18 ヶ月前）。 |
| 新しい Analysis Workspace テンプレート | We added a new template called ["Magento: Marketing &amp; Commerce"](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html) to Analysis Workspace. Magento e コマースのお客様向けに特別に設計されたものですが、小売業者のお客様は独自のインサイトを業務に役立てることができます。 |

#### [!DNL Analysis Workspace] の修正点

* ディメンションを分類すると、マルチバイト文字が逆さまに表示される問題を修正しました。（AN-180112）
* ビジュアライゼーションエラー – ビジュアライゼーションのエラーが発生した場合、赤いエラーバーが表示されるようになりました。（AN-175542）
* 言語を英語以外に設定した場合でも、ディメンション名が英語で表示されることがある問題を修正しました。（AN-178695）

#### [!DNL Analytics] の修正点

* リアルタイムドリルダウンレポートの折れ線グラフが空になる問題を修正しました。（AN-181690）
* 状況によって、データフィード履歴の一部が Admin Console UI に表示されない問題を修正しました。（AN-176219）

### [!DNL Analytics] 管理者向けの重要な注意事項{#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 分類ルールビルダーの制限 | 追加日：2019 年 6 月 5 日 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| 新しいセグメント演算子の制限 | 追加日：2019 年 5 月 31 日 | 2019 年 7 月 18 日以降、セグメント演算子「次のいずれかを含む」、「次のいずれかを含まない」、「次のすべてを含む」および「次のすべてを含まない」は、入力フィールドあたり 100 語に制限されます。この制限は、この日以降、すべての新しいセグメントおよび変更されたセグメントに適用されます。制限を超過している既存のセグメントは、引き続きサポートされますが、入力フィールドが減らされるまで変更または保存できません。これらの制限は、クエリパフォーマンス向上のための継続的な取り組みの一環として適用されています。 |
| **[!UICONTROL 日付分類]**&#x200B;および&#x200B;**[!UICONTROL 数値 2 分類]**&#x200B;に関するサポートの変更予定 | 2019 年 5 月 28 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。この変更は 2019 年 7 月のメンテナンスリリースから有効になります。「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。<br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポートの合計_&#x200B;の計算に対して予定されている変更 | 更新日：2019 年 7 月 9 日 | **2019 年 6 月 18 日**&#x200B;に、_レポートの合計_&#x200B;値の算出方法をすべてのディメンションおよび指標で共通化します。これにより、一部のレポート（通常、Prop または顧客属性レポート）の合計が変更されます。この変更以前は、レポートに&#x200B;_未指定_&#x200B;が表示されているかどうかにかかわらず、合計に&#x200B;_未指定_&#x200B;の行項目を含めるレポートと含めないレポートが混在していました。<br/>2019 年 6 月 18 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。さらに、_存在する_&#x200B;または&#x200B;_存在しない_&#x200B;ロジックを使用するセグメントは、この変更後、一部のディメンションで異なる結果が表示される可能性があります（特に、_未指定_&#x200B;を特有な値としてレポートするディメンションに影響します。リファラータイプディメンションの「手動入力/ブックマーク」行項目やデバイスタイプディメンションの「その他」行項目が該当します）。この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| [!DNL Analysis Workspace] CSV ダウンロード機能の更新点 | 2019 年 4 月 10 日 | 2019 年 4 月 11 日以降、**[!UICONTROL CSV ダウンロード]**&#x200B;および&#x200B;**[!UICONTORL クリップボードへのコピー]**（[!DNL Analysis Workspace]）にいくつかの変更が加えられ、書き出されたデータから書式が削除されます。  <ul><li>桁区切り記号は含まれなくなりました。小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]**&#x200B;で定義された形式が適用されます。注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。パーセンテージは 10 進形式になります。例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| [!DNL Analysis Workspace] Debugger コマンドの変更 | 2019 年 4 月 4 日 | [!DNL Analysis Workspace] Debugger をオンにするためのコンソールコマンドは、**2019 年 6 月 13 日**&#x200B;に adobeTools.debug.includeOberonXml に変更されます。この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 7 日 | 2019 年 1 月 8 日より、モバイルブラウザーバージョン番号を 2 桁から 1 桁に変更しました。この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| [!DNL Ad Hoc Analysis] のサポート終了 | 2019 年 1 月 29 日 | 2018 年 8 月 7 日、アドビは [!DNL Ad Hoc Analysis] のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。<br/>サポート終了の予定や詳細については [Discover Workspace](https://adobe.ly/discoverworkspace) を参照してください。 |
| 短い [!DNL Analytics] レポートリンク | 2019 年 1 月 14 日 | 2019 年 1 月 17 日（木）以降、直近 1 年間に訪問されていない短い [!DNL Analytics] レポートリンクは、定期的に削除されるようになります。 |
| TLS 1.0 のサポート終了 | 2019 年 1 月 10 日更新 | 2019 年 2 月 11 日現在、Adobe Analytics レポートで TLS（Transport Layer Security）1.0 の暗号化がサポートされなくなっています。この変更は、最高レベルのセキュリティ基準を維持して、お客様のデータの安全を確保するための継続的な取り組みの一環です。If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>2019 年 2 月 20 日以降、Adobe Analytics のデータ収集で TLS 1.0 がサポートされなくなりました。この変更により、TLS 1.1 以上をサポートしていない旧型のデバイスや Web ブラウザーを使用しているエンドユーザーの [!DNL Analytics] データは収集されなくなりました。この変更が、お客様の顧客のデータやレポートに大きな影響を及ぼすことはないと認識しています。（お客様の Web サイトが既に TLS 1.0 をサポートしていない場合、影響は一切ありません。）<br/>2019 年 4 月 11 日以降、Adobe Analytics レポート API は TLS 1.0 の暗号化をサポートしていません。API にアクセスするお客様は、この変更による影響の有無を確認してください。 <ul><li>デフォルト設定で Java 7 を使用している API クライアントは、[TLS 1.2](https://www.java.com/en/configure_crypto.html) をサポートするように変更してください（「_Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2_」を参照、ブラウザーの翻訳機能をお使いください）。 </li><li>Java 8 を使用している API クライアントは、デフォルト設定が TLS 1.2 なので、影響を受けません。</li><li> その他のフレームワークを使用している API クライアントは、TLS 1.2 のサポートについてベンダーにお問い合わせください。</li></ul> |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。この変更は、処理中に post_product_list に追加されるマーチャンダイジング eVar 値により、製品および売上高の値の切り捨てが発生しないようにします。post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 KB に達した時点で値を切り捨てるようにしてください。 |
| [!DNL Analytics Live Stream] エンドポイントの管理における変更点 | 2018 年 12 月 20 日 | 2019 年 2 月 1 日以降、顧客からのアクティブな接続が 90 日間なかった [!DNL Live Stream] エンドポイントが無効化される場合があります。使用中の [!DNL Live Stream] エンドポイントについてはサポートに問い合わせて確認でき、必要に応じて再度有効にすることができます。また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 7 日 | TLS 1.0 のサポート終了に伴い、[!DNL Report Builder] ユーザーの皆様には 2019 年 2 月までにバージョン 5.6.21 をダウンロードされることをお勧めします。この日以降、以前のバージョンの [!DNL Report Builder] は機能しなくなります。 |

### AppMeasurement {#appm}

リリース日：2019 年 7 月 15 日:

**JavaScript版AppMeasurement2.15.0**

* Activity MapのスクロールリーチトラッキングがActivity Map拡張機能に追加されました。（AN-172949）
* AppMeasurementにDIL9.2が追加されました。（AN-182472）

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

* [!UICONTROL セグメントの概要]ページで、セグメントストレージフォルダーの幅が変更できるようになりました。これにより、長い名前のセグメント間を区別できます。（AAM-48400）
* [!UICONTROL アルゴリズムモデル]で、**リーチと精度を調整**&#x200B;スライダーがモデルのリーチや精度に影響しなかった問題を修正しました。（AAM-47996）
* Analytics の宛先で、データエクスポート制御やサードパーティデータ共有ポリシーと競合するセグメントの .csv ファイルをダウンロードするためのボタンが壊れていた問題を修正しました。（AAM-48100）
* Audience Manager ユーザーインターフェイスにログインする際に、ランダムな「アクセス拒否」エラーが表示されていた問題を修正しました。（AAM-47632）

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

次の製品に関する新機能情報：

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Cloud Manager 2019.6.0 のリリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### XML ドキュメント 3.4

XML ドキュメント 3.4 ソリューションが利用できるようになりました。

***リリースノート***

* AEM 6.5 のサポートが追加されました。
* エディターが次のように変更されます。
   * マップレベルプレビュー。
   * テーブル - コピー＆ペーストを使用してテーブル内の `entry` または `complete` 行をコピーするオプションが提供されます。
   * テーブル - 列の複数のセルを選択して結合するオプションが提供されます。
   * テーブル - Web エディターのオーサーモードでテーブル列プロパティを設定する方法が提供されます。
   * テーブル - 標準テーブルの列の縦横比およびサイズを調整する方法が提供されます。
   * テーブル - オーサー表示で行および節を選択できます。
   * テーブル - Web エディターでテーブルセルを整列するためのスタイルおよびプロパティ（align、valign）が使用できるようになりました。
   * すべてのタグを表示している場合にコンテンツのコピー＆ペーストおよびドラッグ＆ドロップで発生していたバグを修正しました。
   * エディターのタブにトピックタイトルが表示されます。
   * Web エディターのパフォーマンスの問題を解決しました。
* 翻訳時に、翻訳済みコンテンツのベースラインを転送します。
* 翻訳ワークフロー時に、条件プリセットを転送します。
* ペースラインからのマップのすべての依存にラベルを適用する機能が追加されました。
* すべての依存を含むマップを zip としてダウンロードするためのボタンが提供されます。
* XHTML から DITA への変換機能の改善：
   * 生成される DITAMAP は、アップロードされた zip ファイルの名前と同じになります。
   * 追加の HTML 要素および属性に対してサポートが追加されました。
   * html-zip ファイルの同時インジェストがサポートされます。
   * zip がアップロードされたサブフォルダー階層（*in h2d_io.xml として設定された入力パスの下*）は、生成された出力（*設定された出力パスの下*）で保持されます。
* 誰がどのバージョンに復帰したかとその理由を確認するための監査ログが提供されます。
* AEM Site の再生成：
   * サブマップの再生成が無効になります。
   * 再生成の事例用に、生成後のワークフローが有効になります。
   * まとまったトピックを再生成オプションが無効になり、まとまった属性が適用された親トピック用のオプションが使用できます。
* AEM Asset 検索の DITA 検索で、AND ロジックが機能するようになりました。 
* その結果、翻訳出力フォルダーに格納された一時ファイルが表示されなくなります。
* ベースラインタブ：
   * ベースラインを開く際のパフォーマンスが向上します。
   * 日付によるトピックの選択で、クライアントのタイムスタンプが機能します。
* ラベルを削除するための API。

#### 製品メンテナンス

**AEM 6.2 SP1-CFP20**

2019 年 6 月 6 日にリリースされた AEM 6.2 Service Pack 1–Cumulative Fix Pack 20（6.2.1.20）は重要なアップデートであり、2016 年 12 月の AEM 6.2 SP1 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。

* [リリースノート](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

2019 年 7 月 3 日にリリースされた AEM 6.3.3.5 は重要なアップデートであり、2017 年 4 月の AEM 6.3 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。

* [リリースノート](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

2019 年 7 月 3 日にリリースされた AEM 6.4.5.0 は重要なアップデートであり、2018 年 4 月の AEM 6.4 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。

* [リリースノート](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

2019 年 7 月 3 日にリリースされた AEM 6.5.1.0 は重要なアップデートであり、2019 年 4 月の AEM 6.2 の一般リリース以降にリリースされた主なお客様向けの修正が含まれています。

* [リリースノート](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [AEM Forms CFP リリース](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### セルフサービス

**AEM キャッシュの無効化の更新**

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

Magento Commerce および Magento Open Source のリリースノートについては、以下を参照してください。

* [Magenting Open Source2.3.2リリースノート](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magenting Commerce2.3.2リリースノート](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)

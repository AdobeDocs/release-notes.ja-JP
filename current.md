---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: リリースノート
last-update: 2019 年 11 月
author: mfrei
translation-type: tm+mt
source-git-commit: 4dbc8703a58261a57deae59effa22fc89faaad32

---


# Adobe Experience cloudリリースノート — 2019年11月

Adobe Experience Cloud の新機能および修正点です。

> [!NOTE] [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。リリース後に発表された新情報については、更新日と併せて追加公開します。

**リリース日：2019 年 31 月 11 日**

* [Experience Cloud インターフェイス](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)（ソリューションヘルプへのリンク）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html)（ソリューションヘルプへのリンク）
* [!DNL Advertising Cloud](#adcloud) （1月11日更新）

家で助けを探してる？ See [Experience Cloud Learn &amp; Support](https://helpx.adobe.com/support/experience-cloud.html).

## Experience Cloud インターフェイス {#ecloud}

Experience Cloud インターフェイスおよび製品管理のリリースノートです。

* フィードページは 2019 年 12 月に廃止予定です。製品内の廃止のお知らせを探してください。（MCUI-10039）
* アプリセレクターで Adobe Campaign の「[詳細](https://www.adobe.com/marketing/campaign.html)」リンクを更新しました。（MCUI-10034）
* Experience Cloud インターフェイスのコアプラットフォームの安定性と応答性が向上しました。（MCUI-6822）
* Experience Cloud UI のセキュリティの脆弱性を修正しました。（MCUI-9942）
* 一部の顧客のスキーマ検証がブロックされる顧客属性の重大な問題を修正しました。（MCUI-10024、MCUI-6479）
* オーディエンスライブラリを改善し、リアルタイムオーディエンスの作成がサポートされていないディメンションを削除しました。（MCUI-10046）

製品ドキュメントについては、[Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) を参照してください。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、ID サービスおよびセキュリティ速報のリリースノートです。

* [Experience Platform Launch](#launch)
* [セキュリティ速報および情報](https://helpx.adobe.com/security.html)（すべてのアドビ製品）

### Experience Platform Launch {#launch}

リリースノートおよび製品ドキュメントについては、[Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) を参照してください。

## [!DNL Analytics] {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

製品ドキュメントについては、[Adobe Analytics ヘルプホーム](https://docs.adobe.com/content/help/en/analytics/landing/home.html)を参照してください。

### Adobe Analytics の新機能、機能強化および修正点 {#aa-features}

| 機能 | 説明 |
| -----------| ---------- | 
| カスタマージャーニー分析 | 2019 年 11 月 22 日、Adobe Analytics に対するアドオンとして[カスタマージャーニー分析](https://www.adobe.com/analytics/customer-journey-analytics.html)を利用できるようになります。<br><br/>カスタマージャーニー分析を使用すれば、あらゆるチャネルから、オンラインとオフラインの両方ですべての顧客データを Adobe Experience Platform に取り込むことができます。その後、現在 Analysis Workspace を使用して、既存のデジタルデータを分析しているのと同じようにこのデータを分析できます。カスタマージャーニー分析には、共通の顧客 ID に基づいて、Analysis Workspace のオンラインデータとオフラインデータをどのように接続するかを制御し、最終的に Adobe Analytics の顧客データセット全体をまたいでアトリビューション、セグメント化、フロー、フォールアウトなどを実行できる機能が含まれます。<br><br/>Analytics Select、Prime および Ultimate のお客様は、このアドオン製品を購入できます。詳しくは、アドビのアカウントチームにお問い合わせください。 |
| プライバシーサービス API：CCPA | カリフォルニア州消費者プライバシー法（CCPA）は、米国カリフォルニア州の居住者のプライバシー権と消費者保護を厳格化します。この法律は、2020 年 1 月 1 日に施行されます。<br><br/>CCPA は、カリフォルニア州の居住者に新しいプライバシー権を提供します。これには、自身の個人データにアクセスして削除する権利、自身の個人データが（誰に）販売または公開されているかどうかを知る権利、および自身の個人データの販売を拒否する権利が含まれます。<br><br/>CCPA を見越し、プライバシーサービスは個人データの販売のオプトアウトに対するリクエストをサポートします。<br><br/>プライバシーサービス（旧 GDPR サービス）は、以前の機能をすべて保持し、CCPA をサポートするよう拡張されました。<br/><br/>[Analytics の CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[プライバシーの概要](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| プライバシーレポート：Analytics Admin Console | Analytics でプライバシーレポートを有効化すると、レポートスイートに一連の変数が追加されます。これらの変数は、消費者の同意データをヒットレベルで収集するためのものです。<br><br/>追加されるディメンション：<br/><ul><li>同意管理のオプトアウト</li><li>同意管理のオプトイン</li><li>[同意管理変数](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| オーディオとビデオの分析：プライバシーサポート | メディアコレクション API に 2 つの新しい変数が追加されました。<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>これらは、ヒット時の消費者の同意のステータスを取得するための変数です。<br/><br/>[メディアコレクション API ドキュメント](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>新しい Analytics Consent Management コンテキストデータ変数が Federated Analytics フォームに追加されました。これらの変数を、フェデレーションの「共有のオプトアウト」または「販売ヒット数」のフラグ付けに使用できるようになりました。<br/><br/>[フェデレーテッドフォームのダウンロード](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### 修正点

* 不明なユーザーが所有する日付範囲を削除しようとすると、エラーが発生する問題を修正しました。（AN-185540）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 「**[!UICONTROL アーカイブを表示]**」オプションのサポート終了 | 2019 年 10 月 31 日 | 2020 年 1 月に、ダッシュボードマネージャー（**[!UICONTROL コンポーネント／ダッシュボード]**）の「**[!UICONTROL アーカイブを表示]**」オプションのサービスを終了することをお知らせします。 |
| 「**[!UICONTROL IP ログイン制限の適用]**」オプションのサポート終了 | 2019 年 10 月 31 日 | 2020 年 1 月に、**[!UICONTROL 管理者／会社設定／セキュリティ]**&#x200B;メニューの IP ログインのホワイトリストへの追加（**[!UICONTROL IP ログイン制限の実施]**）機能のサポートを終了することをお知らせします。 |
| Cookie の SameSite 属性の処理を更新しました | 2019 年 10 月 16 日 | 2019 年 8 月に、アドビは、Analytics で設定されるすべての cookie に SameSite cookie 設定を追加したことを発表しました。ロジックの更新は次の場合に適用されます。<ul><li>Webkit ベースでないすべてのサードパーティ Cookie の SameSite属性が `none` に設定されている。</li><li>その他のすべての Cookie には、SameSite 属性は設定されていない。</li></ul> |
| TLS 1.1 のサポート終了 | 2019 年 10 月 4 日 | 2020 年 3 月 31 日までに、Adobe Analytics は TLS 1.1 のサポートを削除します。この変更は、最高のセキュリティ標準を維持し、顧客データの安全性を高めるアドビの継続的な取り組みの一環としておこなわれます。 |
| サンノゼ FTP 連携機能の終了 | 2020 年 7 月 | ロンドンおよびシンガポールデータセンターをご利用のお客様に対し、サンノゼデータセンター [ftp.omniture.com](ftp://ftp.omniture.com/) からロンドンまたはシンガポールへの、データ連携機能の提供を終了します。ftp.omniture.com をご利用中のお客様は、今後、次の FTP を使用してください。<br/><ul><li>ロンドンのお客様：[ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>シンガポールのお客様：[ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Analysis Workspace フリーフォームテーブルの合計を更新 | 2019 年 9 月 13 日 | 2019 年 10 月より、フリーフォームテーブルの合計行が、適用された[レポートフィルター](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)を考慮するようになります。これまでは、合計はセグメントのみが反映されていました。この変更により、出力された CSV や PDF データだけでなく、依存するビジュアライゼーション（例：リンクされた [!UICONTROL 概要番号]ビジュアライゼーションなど）も更新されます。 |
| Analytics ユーザーの `createDate` フィールドに関する変更予定 | 2019 年 8 月 31 日 | 2019 年 10 月または 2019 年 11 月に、Analytics ユーザーの `createDate` フィールドが米国太平洋時刻から、タイムゾーン情報を反映した正しい形式に更新されます。（AN-183468） |
| 履歴タイムゾーンオフセットのサポート | 2019 年 8 月 9 日 | Analytics は、タイムスタンプ付きのヒットに対して、タイムゾーンオフセットを自動的に処理するようになりました。この変更に従い、履歴処理用にデータで読み込むシステムは、データで送信する前にタイムゾーンオフセットを調整する必要がなくなりました。 |
| 分類ルールビルダーの制限 | 追加日：2019 年 6 月 6 日 | これらの制限は新しいものではありませんが、[こちら](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)のドキュメントに追加されました。 |
| 新しいセグメント演算子の制限 | 追加日：2019 年 6 月 1 日 | 2019 年 7 月 19 日以降、セグメント演算子「_次のいずれかを含む_」、「_次のいずれかを含まない_」、「_次のすべてを含む_」および「_次のすべてを含まない_」は、入力フィールドあたり 100 語に制限されます。この制限は、この日以降、すべての新しいセグメントおよび変更されたセグメントに適用されます。制限を超過している既存のセグメントは、引き続きサポートされますが、入力フィールドが減らされるまで変更または保存できません。これらの制限は、クエリパフォーマンス向上のための継続的な取り組みの一環として適用されています。 |
| **[!UICONTROL 日付分類]**&#x200B;および&#x200B;**[!UICONTROL 数値 2 分類]**&#x200B;に関するサポートの変更 | 2019 年 5 月 29 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。この変更は 2019 年 7 月のメンテナンスリリースから有効になりました。「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。<br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポートの合計_&#x200B;の計算に対する変更 | 更新日：2019 年 7 月 10 日 | **2019 年 6 月 19 日**&#x200B;に、Adobe Analytics では、_レポートの合計_&#x200B;値の算出方法をすべてのディメンションおよび指標で共通化しました。これにより、一部のレポート（通常、Prop または顧客属性レポート）の合計が変更されました。この変更以前は、レポートに&#x200B;_未指定_&#x200B;が表示されているかどうかにかかわらず、合計に&#x200B;_未指定_&#x200B;の行項目を含めるレポートと含めないレポートが混在していました。<br/>2019 年 6 月 19 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。さらに、_存在する_&#x200B;または&#x200B;_存在しない_&#x200B;ロジックを使用するセグメントは、この変更後、一部のディメンションで異なる結果が表示される可能性があります（特に、_未指定_&#x200B;を特有な値としてレポートするディメンションに影響します。リファラータイプディメンションの「手動入力/ブックマーク」行項目やデバイスタイプディメンションの「その他」行項目が該当します）。この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| Analysis Workspace CSV ダウンロード機能の更新点 | 2019 年 4 月 11 日 | 2019 年 4 月 12 日以降、Analysis Workspace からの **[!UICONTROL CSV ダウンロード]**（**[!UICONTORL クリップボードへのコピー]**）にいくつかの変更が加えられ、書き出されたデータから書式が削除されます。  <ul><li>桁区切り記号は含まれなくなりました。小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]**&#x200B;で定義された形式が適用されます。注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。パーセンテージは 10 進形式になります。例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| Analysis Workspace Debugger コマンドの変更 | 2019 年 4 月 5 日 | Analysis Workspace Debugger をオンにするためのコンソールコマンドは、**2019 年 6 月 14 日**、adobeTools.debug.includeOberonXml に変更されます。この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 8 日 | 2019 年 1 月 9 日より、モバイルブラウザーバージョン番号を 2 桁から 1 桁に変更しました。この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| [!DNL Ad Hoc Analysis] のサポート終了  | 2019 年 1 月 30 日 | 2018 年 8 月 7 日、アドビは [!DNL Ad Hoc Analysis] のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。<br/>サポート終了の予定や詳細については、[[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace) を参照してください。 |
| 短い [!DNL Analytics] レポートリンク | 2019 年 1 月 15 日 | 2019 年 1 月 18 日（金）以降、直近 1 年間に訪問されていない短い [!DNL Analytics] レポートリンクは、定期的に削除されるようになります。 |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 10 日 | 2019 年 2 月 8 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。この変更は、処理中に post_product_list に追加されるマーチャンダイジング eVar 値により、製品および売上高の値の切り捨てが発生しないようにします。post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 KB に達した時点で値を切り捨てるようにしてください。 |
| [!DNL Analytics Live Stream] エンドポイントの管理における変更点 | 2018 年 12 月 21 日 | 2019 年 2 月 2 日以降、顧客からのアクティブな接続が 90 日間なかった [!DNL Live Stream] エンドポイントが無効化される場合があります。使用中の [!DNL Live Stream] エンドポイントについてはサポートに問い合わせて確認でき、必要に応じて再度有効にすることができます。また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 8 日 | TLS 1.0 のサポート終了に伴い、[!DNL Report Builder] ユーザーの皆様には 2019 年 2 月までにバージョン 5.6.21 をダウンロードされることをお勧めします。この日以降、以前のバージョンの [!DNL Report Builder] は機能しなくなります。 |

### [!DNL AppMeasurement] {#appm}

「[JavaScript 版 AppMeasurement リリースノート](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)」を参照してください。

## Audience Manager {#aam}

Audience Manager の新機能、拡張機能および修正点です。

| 機能 | 説明 |
|--- |----|
| [プロファイル結合ルールの強化](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | [!UICONTROL プロファイル結合ルール]に関する一連の機能強化をリリースしました。 <ul><li>セグメント評価が、最大 100 台のデバイスに対してバッチでサポートされるようになりました。</li><li>特性とセグメント母集団のレポート精度が向上しました。</li><li>クロスデバイス ID を使用して生成されたバッチファイルの精度が向上しました。</li><li>各ルールの使用例をさらに詳しく説明し、ドキュメントを更新しました。詳しくは、「[プロファイル結合ルールの一般的な使用例](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)」、「[外部デバイスグラフの使用例](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)」、および「[プロファイルリンクデバイスグラフの使用例](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)」を参照してください。</li></ul> |
| [Audience Marketplaceデータに関するインテリジェントな推奨、Adobe Sensei](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/trait-recommendations.html) | 特性レコメンデーションを使用すると、 [Segment Builderでセグメントを作成または編集する際に、登録していない](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/segment-builder.html)Audience Marketplace  データフィードから、追加の特徴に関するレコメンデーションを取得できるようになりました。 対象者を増やすために、推奨された Trait をセグメントに追加します。<br>  さらに、 [!UICONTROL Marketplaceページのデザインを一新し] 、類似の特徴を見つけやすくし、データフィードをフィルターしやすくしました。 |
| [一括管理ツール](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | MacOS および Microsoft Windows オペレーティングシステムで動作し、Experience Cloud ログインをサポートする新しいバージョンの一括管理ワークシートがリリースされました。 |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | cookie のハイジャック攻撃やプロトコルダウングレード攻撃から保護する Web セキュリティポリシーである [!DNL HTTP Strict-Transport-Security] に対するサポートが追加されました。 |

**修正点および改善点**

* Audience Marketplace で、顧客が月別のセグメント使用状況を送信する際に UI からエラー 409 が返されるバグを修正しました。（AAM-50825）
* 派生シグナルで、短時間新しい派生シグナルを作成できないバグを修正しました。（AAM-50968）
* People-Based Destinations で、顧客が宛先の名前を変更できなかったバグを修正しました。（AAM-51025）
* 一部のユーザーが Audience Manager UI にログインする際にアカウントが重複していたバグを修正しました。これらのユーザーは、重複したアカウントに権限が関連付けられなかったことにより、UI の一部にアクセスして操作を実行できませんでした。（AAM-50818）
* 引き続き、Audience Manager UI のアクセシビリティを改善します。(AAM-48932、AAM-48997、AAM-49043、AAM-49054、AAM-49371、AAM-49375、AAM-51313)

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5 は、Brand Portal ユーザー（外部のエージェンシー／チーム）に対して、オーサー環境にアクセスせずに Brand Portal にコンテンツをアップロードし、AEM Assets に公開する機能を提供する機能リリースです。この機能は [Brand Portal でのアセットソーシング](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)と呼ばれ、世界中に分散した他の Brand Portal ユーザーとアセットを投稿および共有する双方向のメカニズムを提供し、顧客体験を向上させます。

   [AEM Assets Brand Portal の新機能](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html)を参照してください。

   [リリースノート](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)を参照してください。

* **AEM Forms 自動変換サービス**

   自動フォーム変換サービスは、PDF フォームをアダプティブフォームに自動変換することで、データ取得エクスペリエンスのデジタル化と最新化を促進します。Adobe Sensei を活用したサービスは、PDF フォームを、デバイスに対応した、レスポンシブで HTML5 ベースのアダプティブフォームに自動的に変換します。このサービスでは、PDF フォームと XFA に対する既存の投資を活用しながら、変換時、アダプティブフォームフィールドに適切な検証、スタイル設定、レイアウトも適用します。

   詳しくは、「[Adobe Experience Manager Forms 自動コンバージョンサービス](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)」を参照してください。

* **Cloud Manager 2019.10.0**

   Cloud Manager 2019.10.0 の一般的なリリースノートを利用できるようになりました。ノートには、デプロイメント手順と、maven プロジェクトバージョンのハンドリングに対する更新も記載されています。

   詳しくは、「[Cloud Manager 2019.10.0 リリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)」を参照してください。

### セルフサービス

* **Activity Map**

   Adobe Analytics API 内のセキュリティの変更により、AEM に含まれるバージョンの Activity Map を使用できなくなりました。詳しくは、「[Adobe Analytics への接続の設定](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics)」を参照してください。

   Adobe Analytics が提供する Chrome 、Firefox または Internet Explorer 用の [Activity Map ブラウザープラグイン](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html)を使用する必要があります。

* **AEM Screens プロジェクトのベストプラクティスガイド**

   新しい _AEM Screens のベストプラクティスガイド_&#x200B;は、デジタル署名の実装を想像、設計し、意図的な顧客体験をもたらすための、包括的なインサイトと実践的なアドバイスを提供します。また、AEM Screens にデジタル署名プロジェクトを展開しながら、ベストプラクティスを使用してビジネスに良い影響を与える方法についても説明します。

   「[AEM Screens プロジェクトのベストプラクティスガイド](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html)」を参照してください。

* **ヘッドレスエクスペリエンス管理**

   単一ページアプリケーションのサーバーサイドレンダリングに使用される[リモートコンテンツレンダラー](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848)の機能が、ドキュメントに記載されました。

* **SPA とサーバーサイドレンダリング**

   AEM 駆動型 SPA がサーバーサイドレンダリングに使用するリモートコンテンツレンダリングサービスを、ニーズに合わせて拡張およびカスタマイズできます。

   「[SPA とサーバサイドレンダリング](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer)」を参照してください。

* **AEM プロジェクトアーキタイプ**

   AEM プロジェクトのアーキタイプは、最小限のベストプラクティスベースの Adobe Experience Manager プロジェクトを独自の AEM プロジェクトの出発点として作成します。このアーキタイプを使用する場合に指定する必要があるプロパティを使用すると、このプロジェクトのすべての部分の名前を指定し、特定のオプション機能を制御できます。

   「[AEM プロジェクトアーキタイプ](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html)」を参照してください。

* **AEM のドキュメントの更新**

   過去 3 か月間の Adobe Experience Manager に関する重要なドキュメントの変更と更新についてお読みください。

   「[AEM ドキュメント：最近のドキュメントの更新](https://helpx.adobe.com/experience-manager/documentation-updates.html)」を参照してください。

### その他のリソース

* [AEM 6.5 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic ヘルプホーム](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### ドキュメントのリソース

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [リリース計画](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ハウツービデオ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

2019年11月2日リリース用に更新

| 表示 | 機能 |
|------|---------|
| コンバージョンの追跡 | Advertising Cloud javaScriptベースのコンバージョンマッピングタグで、Mozilla Firefoxバージョン69以降のクリックスルーの追跡がサポートされ、デフォルトでサードパーティcookieがブロックされるようになりました。 同じタグに既にApple Safariのサポートが含まれています。<br><br/>Advertising cloudコンバージョントラッキングを使用し、Advertising cloudコンバージョンマッピングタグをまだ導入していない場合は、すべてのランディングページに次のコードを導入し<br></br>`<script src="//www.everestjs.net/static/amo-conversion-mapper.js"></script>`<br></br>ます。注：このタグは、Advertising Cloud javaScript v2およびv3のコンバージョントラッキングタグをサポートし、画像トラッキングタグはサポートしません。 |
| ポートフォリオ | ポートフォリオオプションの「キャンペーンの最大支出%ターゲットを有効にする」が有効な場合、最大支出ターゲットを超えることはなくなりました。 以前は、最適な広告配信時にAdvertising cloudが最大支出目標を超えていました。 |
| オーディエンスの検索 | 検索/オーディエンス/ライブラリのオーディエンスライブラリに、Bing広告とGoogle広告から毎日入力される「オーディエンスのサイズ」列が自動的に含まれるようになりました。 オプションで、この列をデータフィルターとして使用できます。 |

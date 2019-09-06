---
title: Adobe Experience Cloud リリースノート
description: Experience Cloud リリースノートのテンプレート
doc-type: リリースノート
last-update: 2019年9月
author: mfrei
translation-type: tm+mt
source-git-commit: 2cf514449e70523a47b16dceb35d93ec7eff0824

---


# 先行アクセス-2019年9月- Experience Cloudリリースノート

Adobe Experience Cloud の新機能および修正点です。

>[!IMPORTANT]
>
>This page contains pre-release content and is subject to change prior to the September 12, 2019 release.

>[!NOTE]
>
>[[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) を参照してください。通知はリリースの 3～5 営業日前に届きます。リリース後に発表された新情報には、更新の日付が明記されます。

## リリース日：2019 年 9 月 12 日

* [Experience Cloud インターフェイス](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) （ソリューションヘルプへのリンク）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) （ソリューションヘルプへのリンク）

## Experience Cloud インターフェイス {#ecloud}

Experience Cloudインターフェイスおよび製品管理のリリースノートです。

* 推奨されるHTTPヘッダーを含めるセキュリティ脆弱性を修正しました。（MCUI-9942）
* Analyticsログイン会社間の切り替えの問題を修正しました。（MCUI-10049）

製品ドキュメントについては [、Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)を参照してください。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、IDサービスおよびセキュリティ速報のリリースノートです。

* [Experience Platform Launch](#launch)
* [Mobile Services および Mobile SDK](#mobile)
* [セキュリティ速報と情報](https://helpx.adobe.com/security.html) （すべてのアドビ製品）

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services および Mobile SDK {#mobile}

Release Date: **September 26th**

**iOS（4.18.8）**

* Analyticsの呼び出しごとにSDKデータがペアのWatchOSアプリケーションに同期されるバグを修正しました。
* プッシュクリックスルーペイロードをアプリ内メッセージの特性として使用できなかったバグを修正しました。
* iOS10以降で廃止されたUILocalNotification APIの代わりに、ユーザー通知フレームワークAPIに更新されました。
* iOS12以降で非推奨となったUIWebViewの代わりにWKWebViewに更新されました。

**Android4.17.10**

* OCR47言語タグのサポートを追加しました。

**Unity**

* Android版のプラグイン4.18.7、Android向け4.17.9に更新

## [!DNL Analytics] {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能、機能強化および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics の新機能、機能強化および修正点{#aa-features}

| 機能 | 説明 |
| -----------| ---------- |  
| **ジャーニーIQ:デバイス間分析** | 2019年9月に、Adobe Analyticsは、Analytics Ultimateのお客様向けに早期アクセスを紹介しています。この機能は、ジャーニーIQと呼ばれています。クロスデバイス分析を参照してください。クロスデバイス分析（CDA）は、人間中心の分析ツールを中心としたデバイスからAdobe Analyticsを変換します。CDAを使用すると、次のような質問に答えることができます。 <ul><li>ブランドと何人の人々が対話しているか。使用するデバイスの数と種類は何ですか。どのように重なりますか。</li><li>ユーザーは、モバイルデバイスでタスクを開始し、後でデスクトップPCに移動してタスクを完了しますか。あるデバイス上にあるキャンペーンクリックスルーは、別の場所でコンバージョンにつながるか。</li><li>クロスデバイスのジャーニーを考慮すると、キャンペーンの効果についてどのように理解しているか。ファネル分析の変更方法</li><li>ユーザーがあるデバイスから別のデバイスに移動する最も一般的なパスはどれか。どこからドロップアウトしますか。成功した場所はどこか。</li><li>複数のデバイスを持つユーザーの動作は、単一のデバイスを持つユーザーとは異なりますか。</li></ul><br/>詳しくは、訪問 `adobe.ly/aacda`を参照してください。 |
| **分類のアーキテクチャの更新** | 9月から、分類アーキテクチャの更新は、数か月の間に顧客に移行されます。9月のリリースには、初期の採用者数の移行が含まれています。<br/>更新により、アップロードに要する時間（ルールロジックを含む）が大幅に削減され、レポートの読み込みや取り込みが可能になります。 |

#### 修正点

* [!UICONTROL ユーザー] と [!UICONTROL オファー] コアサービスがメインのExperience Cloudメニューからアクセスできない問題を修正しました。（AN-184294）
* [!UICONTROL Analysis Workspace] の左側のレールにスクロールバーがあり、スクロールバーがないと、Fletchingエフェクトが発生する問題を修正しました。（AN-183904）
* エラーレポートの問題を修正しました。赤のエラーインジケーターだけでなく、より具体的なエラーメッセージが表示されます。特に、負荷が大きい場合、エラーによって発生する場合、または複雑すぎるレポートリクエストを作成することによって、問題が発生するタイミングを理解するのに役立ちます。（AN-184135） [詳細…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* 形式で `.pdf/.xls/.rtf` フォールアウトレポートを正常にダウンロードできない問題を修正しました。（AN-183165）
* Experience Cloud経由でログインし、別のExperience Cloudソリューションに切り替えたり、別のログイン会社に切り替えたりする問題を修正しました。（AN-183376）
* スケジュールされたプロジェクトのアセット転送が正しく機能しない問題を修正しました。グループは [!UICONTROL 管理コンソール] で管理されるので、アセットの移行時にユーザー間でコピーされることはありません。（AN-183751）
* 所有者が削除された予定レポートの削除の問題を修正しました。今後、スケジュールの所有者が存在しない場合に管理者（削除操作を実行した）に通知が送信されます。（AN-181000）

### [!DNL Analytics] 管理者向けの重要な注意事項 {#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| Analysis Workspaceフリーフォームテーブルの合計に更新 | 2019年9月13日 | 2019年10月に、フリーフォームテーブル合計行が適用され、適用された [レポートフィルター](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) の会計が開始されます。合計では、合計はセグメント化にのみ影響しています。この変更により、依存ビジュアライゼーションは、エクスポートされたCSVおよびPDFデータだけでなく、依存するビジュアライゼーション（リンク [!UICONTROL された概要番号] ビジュアライゼーションなど）も更新されます。 |
| Analyticsユーザーの `createDate` ためのフィールドに関する変更 | 2019 年 30 月 9 日 | 2019年10月または2019年11月に、Analyticsユーザーの `createDate` フィールドが米国太平洋時刻からタイムゾーン情報で正しい形式に更新されます。（AN-183468） |
| 履歴タイムゾーンオフセットのサポート | 2019 年 8 月 9 日 | Analytics は、タイムスタンプ付きのヒットに対して、タイムゾーンオフセットを自動的に処理するようになりました。8 月 8 日のこの変更に従い、履歴処理用にデータで読み込むシステムは、データで送信する前にタイムゾーンオフセットを調整する必要がなくなりました。 |
| 分類ルールビルダーの制限 | 追加日：2019 年 6 月 5 日 | これらの制限は新しいものではありませんが、ドキュメント [に追加](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)されました。 |
| 新しいセグメント演算子の制限 | 追加日：2019 年 5 月 31 日 | 2019 年 7 月 18 日以降、セグメント演算子「_次のいずれかを含む_」、「_次のいずれかを含まない_」、「_次のすべてを含む_」および「_次のすべてを含まない_」は、入力フィールドあたり 100 語に制限されます。この制限は、この日以降、すべての新しいセグメントおよび変更されたセグメントに適用されます。制限を超過している既存のセグメントは、引き続きサポートされますが、入力フィールドが減らされるまで変更または保存できません。これらの制限は、クエリパフォーマンス向上のための継続的な取り組みの一環として適用されています。 |
| **[!UICONTROL 日付対応]** および **[!UICONTROL 数値2分類のサポートの変更]** | 2019 年 5 月 28 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。この変更は2019年7月のメンテナンスリリースで有効になりました。「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。<br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポート合計_ 計算の変更 | 更新日：2019 年 7 月 9 日 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. これにより、一部のレポート（通常、propまたは顧客属性レポート）の合計が変更されました。この変更以前は、レポートに&#x200B;_未指定_&#x200B;が表示されているかどうかにかかわらず、合計に&#x200B;_未指定_&#x200B;の行項目を含めるレポートと含めないレポートが混在していました。<br/>2019 年 6 月 18 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。さらに、_存在する_&#x200B;または&#x200B;_存在しない_&#x200B;ロジックを使用するセグメントは、この変更後、一部のディメンションで異なる結果が表示される可能性があります（特に、_未指定_&#x200B;を特有な値としてレポートするディメンションに影響します。リファラータイプディメンションの「手動入力/ブックマーク」行項目やデバイスタイプディメンションの「その他」行項目が該当します）。この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| Analysis Workspace CSV ダウンロード機能の更新点 | 2019 年 4 月 10 日 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>桁区切り記号は含まれなくなりました。小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]**&#x200B;で定義された形式が適用されます。注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。パーセンテージは 10 進形式になります。例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| Analysis Workspace Debugger コマンドの変更 | 2019 年 4 月 4 日 | Analysis Workspace Debugger をオンにするためのコンソールコマンドは、**2019 年 6 月 13 日**&#x200B;に adobeTools.debug.includeOberonXml に変更されます。この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 7 日 | 2019 年 1 月 8 日より、モバイルブラウザーバージョン番号を 2 桁から 1 桁に変更しました。この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| [!DNL Ad Hoc Analysis]のサポート終了  | 2019 年 1 月 29 日 | 2018 年 8 月 6 日、アドビは [!DNL Ad Hoc Analysis] のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。<br/>この期間中のJavaのバージョンを含め、詳細について [は、[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace)を参照してください。 |
| 短い [!DNL Analytics] レポートリンク | 2019 年 1 月 14 日 | 2019 年 1 月 17 日（木）以降、直近 1 年間に訪問されていない短い [!DNL Analytics] レポートリンクは、定期的に削除されるようになります。 |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。この変更は、処理中に post_product_list に追加されるマーチャンダイジング eVar 値により、製品および売上高の値の切り捨てが発生しないようにします。post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 KB に達した時点で値を切り捨てるようにしてください。 |
| [!DNL Analytics Live Stream] エンドポイントの管理における変更点 | 2018 年 12 月 20 日 | 2019 年 2 月 1 日以降、顧客からのアクティブな接続が 90 日間なかった [!DNL Live Stream] エンドポイントが無効化される場合があります。使用中の [!DNL Live Stream] エンドポイントについてはサポートに問い合わせて確認でき、必要に応じて再度有効にすることができます。また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 7 日 |
| TLS 1.0 のサポート終了 | 2019 年 1 月 10 日更新 | TLS1.0は、 |

### [!DNL AppMeasurement] {#appm}

JavaScript版 [AppMeasurementリリースノート](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)を参照してください。

## Audience Manager {#aam}

Audience Managerの新機能、機能強化および修正点です。

### 新機能および機能強化 {#aam-features}

| 機能 | 説明 |
| -----------| ---------- |  
| **[人ベースの宛先](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNLPeポリ- based Destinations] は有料のAudience Managerアドオンであり、Facebookなどのユーザーベースの環境で、電子メールアドレスなどのハッシュされた識別子を使用して、ファーストパーティのオーディエンスセグメントをアクティブ化するのに役立ちます。 |
| **[Twitterをカスタマイズしたオーディエンスをセルフサービスデバイスベースの宛先として設定する](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | Twitter宛先をセルフサービス設定モデルに移行します。この記事では、移行後に作業を続行するために、既存のTwitter統合に対して実行する必要があることを説明します。 |
| **[Audience Marketplaceの請求例](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | 「大文字と小文字3"の新しい例を追加しました。この例では、アクティブ化とモデリングの使用例を使用して、セグメントに対する課金のしくみを説明しています。 |

**修正点および改善点**

* ユーザーがAdobe Analyticsの宛先を編集してセグメントを手動でマッピングできなかったバグを修正しました。（AAM-49323）
* Audience Marketplaceフィードが1つのデータソースIDから重複していたバグを修正しました。データソースと [!DNL Marketplace] フィードの間には1:1のマッピングが必要です。（AAM-48504）
* 特性およびセグメント作成ワークフローの機能強化を行いました。これで、データソースをフィルタリングして、Audience Manager以外のデータソース（例えば、Adobe Analyticsからのレポートスイートデータソース）を除外するように特性またはセグメントを保存できます。（AAM-35899）
* データソースAPIで、クエリパラメーター `ExcludeReportSuites=true` を設定してAdobe Analyticsからレポートスイートデータソースを除外しない問題を修正しました。（AAM-48545）
* Audience Managerユーザーインターフェイスのアクセシビリティに関するいくつかの改善を行いました。（AAM-49024）および（AAM-49031）

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

**Cloud Manager 2019.8.0**

Cloud Managerリリース2019.8.0では、様々なバグの修正、ビルドパフォーマンスの向上、選択したコンテンツパッケージの選択的なサポートが追加されました。

* [Cloud Manager 2019.8.0 のリリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 製品メンテナンス

**AEMメンテナンスリリースのロードマップ**

ここ [では、AEMメンテナンスリリースのロードマップを参照](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html)してください。

### セルフサービス

**Asset Link1.1プレリリース版**

* [Adobe Asset Linkプレリリースについて](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [プレリリース用のAdobe Asset LinkのためのAEMの設定](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

MAC版AEM Desktop App2.0は2019年8月30日にリリースされました。Windows版AEM Desktop App2.0は9月上旬にリリースされます。

ドキュメントおよびダウンロードについては [こちら](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html)を参照してください。

**アセットスマートタグ**

期限切れ [になった後に証明書を更新する方法について](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate)説明します。

**AEM6.5Screensユーザーガイド**

_Network Deployment Guidelines_ に関する新しいドキュメントが利用できるようになりました。[ ユーザーガイド](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html)を参照してください。

**自動化されたForms変換サービス**

AEM Forms自動変換サービスのドキュメントが利用できるようになりました。「 [Introduction to Automated Forms Conversion service](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html)」を参照してください。

### コミュニティ

**AEMスキルビルダーウェビナー**

* [Adobe Experience Manager Sites](https://forums.adobe.com/thread/2647742)

   | ウェビナー | 日付 |
   | -----------| ---------- |  
   | _Webエクスペリエンスのオーサリング_ | 2019年8月27日 |
   | _コンテンツの検索とナビゲート_ | 2019年9月9日 |
   | _すべての進化するコンテンツを容易に管理_ | 2019年9月10日 |
   | _可変エクスペリエンス_ | 2019年9月18日 |
   | _マルチ言語、多言語、多言語のデザインを作成して管理_ | 2019年9月24日 |

* [Adobe Experience Manager Assets](https://forums.adobe.com/thread/2647743)

   | ウェビナー | 日付 |
   | -----------| ---------- |  
   | _フォルダ構造と検索_ | 2019年8月29日 |
   | _メタデータ_ | 2019年9月5日 |
   | _Brand Portal_ | 2019年9月12日 |
   | _Dynamic Media_ | 2019年9月20日 |
   | _アセットリンク_ | 2019年9月26日 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | ウェビナー | 日付 |
   | -----------| ---------- |  
   | Forms 101_ | 2019年9月4日 |
   | _Formsへのフォームの接続、ワークフローの構築、およびE- Signaturesとの統合_ | 2019年9月11日 |
   | _モバイルレスポンシブWebおよび印刷対応のインタラクティブコミュニケーションの作成_ | 2019年9月25日 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | ウェビナー | 日付 |
   | -----------| ---------- |  
   | _ベストプラクティスのテスト- Cloud Managerでの実行、監視、監査およびインサイトの作成_ | 2019年9月18日 |
   | _Cloud Managerを使用したディスパッチャー設定_ | 2019年10月16日 |
   | _Cloud Managerおよびサードパーティツールによるワークフローの作成_ | 2019年11月13日 |

### その他のリソース

* [AEM 6.5 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [旧バージョンのAEMドキュメント](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classicヘルプホーム](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### 製品のサポート終了

[!DNL Digital Publishing Suite Classic] （DSC）は2019年8月31日に提供終了となります。詳しくは、DNL Digital Publishing Suite Classic]提供終了のFAQ[](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html)

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

### Adobe Campaign Classic

* [Campaign Classic19.1.4アップデート](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) -ビルド9032
* [キャンペーンClassic19.1.5アップデート](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) -ビルド9033

### Adobe Campaign [!UICONTROL Control Panel]

アドビでは、ドメインのSSL証明書の有効期限が切れる前に通知を受信するための新しい機能を追加しました。詳しくは、[詳細ドキュメント](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html)を参照してください。

さらに、管理者ユーザーはSFTPサーバーにアクセスするために追加されたSSHキーを削除できるようになりました。

[!UICONTROL コントロールパネル]は、AWS でホストされる Adobe Campaign Classic および Adobe Campaign Standard の両方のお客様が利用できます。[!UICONTROL コントロールパネル]にはアップグレードは必要ありません。

### その他のリソース

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

---
title: Adobe Experience Cloud リリースノート
description: 2019年6月のExperience Cloudリリースノート
doc-type: リリースノート
last-update: 2019年6月
author: mfrei
translation-type: tm+mt
source-git-commit: 0c4355bbb17d5b67a8f136a07b7fc2a682441a01

---


# Adobe Experience Cloud リリースノート

Adobe Experience Cloud の新機能および修正点です。

>[!NOTE]
>[Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) をご購読いただくと、今後のリリース予定が電子メールにて通知されます。通知はリリースの 3～5 営業日前に届きます。リリース後に発表された新情報には、更新の日付が明記されます。

**リリース日：2019 年 6 月 13 日**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard／Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform リリースノート

* エクスペリエンスプラットフォームの最新の更新については、Adobe. ioの [Experience Platformリリースノート](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) を参照してください。

### Experience Platform Launch

* 最新の情報については [、エクスペリエンスプラットフォームの起動](https://docs.adobelaunch.com/) を参照してください。

## Analytics {#analytics}

Adobe Analytics の新機能および修正点です。

* [Adobe Analytics の新機能および修正点](#aa-features)
* [Analytics 管理者向けの重要な注意事項](#aa-notices)

製品ドキュメントについては、[Analytics ヘルプホーム](https://marketing.adobe.com/resources/help/en_US/reference/)を参照してください。

### Adobe Analytics の新機能および修正点{#aa-features}

| 機能 | 説明 |
| -----------| ---------- |  
| **セグメント化** | セグメント化のディメンションの新しいアトリビューションモデル:<ul><li>繰り返し（デフォルト）:ディメンションに永続化された値を含めます。</li><li>インスタンス:ディメンションのインスタンスが含まれます。</li><li>非繰り返しインスタンス:ディメンションの一意のインスタンス（非繰り返し）が含まれます。</li></ul> [詳細情報](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) |
| **セグメント化** | 新しいセグメント演算子: **[!UICONTROL And Any of of]** And **[!UICONTROL Do Equal Any of of]**.[詳細情報...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segment-reference/seg-operators.html) |
| **デバッガー** | Adobe IDでログインすると、後処理されたヒットをExperience Cloudデバッガーで取得できるようになりました。処理後のヒットは、 [!UICONTROL 処理ルール] とVISTAルールを使用して完了した後で、 [!UICONTROL 処理ルール] とVISTAルールを検証できます。**注意**:A4T（SupplementalDataID）を使用している場合、後処理データには数分かかることがあります。 |
| **Analysis Workspace:** | 左側のレール検索に追加された新しいフィルターを追加しました。今日の表示（ディメンション、指標、承認済みなど）は、計算指標、顧客属性、eVar、Props、ビデオなどの新しいフィルターになります。が追加され、必要なコンポーネントを見つけやすくなりました。 |
| **Analysis Workspace** | セグメントをタッチポイントとして追加したときに表示されるフォールアウトビジュアライゼーションに警告を追加しました。無効なセグメントコンテナの組み合わせによって、フォールアウト図が無効になります。例えば、 <ul><li>訪問者ベースのセグメントを訪問者コンテキストのフォールアウトビジュアライゼーション内のタッチポイントとして使用する</li><li>訪問コンテキストのフォールアウトビジュアライゼーション内のタッチポイントとしての訪問者ベースのセグメントの使用</li><li>訪問ベースのセグメントを訪問コンテキストのフォールアウトビジュアライゼーション内のタッチポイントとして使用する</li></ul> <br> [詳細情報...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html)</br> |
| **Analyticsドキュメントの強化** | 解析ドキュメントが再編成され、コンテンツを改善できるコラボレーション機能が追加されました。ドキュメントに対して問題を記録し、編集を提案することができます。ドキュメントセットが [新しいドメインに移動](https://docs.adobe.com/content/help/en/analytics/landing/home.html)しました。リダイレクトする必要があります。 |
| **New ech Notesユーザーガイド** | [テクニカルノートのユーザーガイド](https://docs.adobe.com/content/help/en/analytics/technotes/home.html) が利用できるようになりました。現在、Googleアナリティクスのようなサードパーティの分析ツールを使用して、Adobe Analyticsについてより詳しい情報を提供することを目的としています。テクニカルノートのユーザーガイドは、今後数か月以内に拡張され、コンテンツを追加します。 |

**Analysis Workspace の修正点**

* ビジュアライゼーションの [!DNL Analysis Workspace] ローカライズされた日本語の日付情報の問題を修正しました。（AN-180114）
* ディメンション項目をコピーして貼り付けると発生していた問題を修正しました。その後、アイテム上の検索によってエラーが発生していました。（AN-177394）
* フリーフォームテーブル内のセグメントパネルに編集オプションが表示されない問題を修正しました。（AN-171703）
* 多数の受信者と共有すると「ランディングページとして **[!UICONTROL 設定」]** 機能が機能しない問題を修正しました。（AN-163922）
* リアルタイムレポートで文字列が縦にクリッピングされる問題を修正しました。（AN-175980）

**Analytics のその他の修正**

* 管理者ユーザーが成功イベントを有効 **[!UICONTROL にできない問題を修正]** しました。（AN-176689）
* **[!UICONTROL 出口率]** 指標でアラートを作成すると発生していた問題を修正しました。（AN-177476）

### Analytics 管理者向けの重要な注意事項{#aa-notices}

| 通知 | 追加日または更新日 | 説明 |
| -----------| ---------- | ---------- |
| 分類ルールビルダーの制限 | 2019年6月6日を追加 | これらの制限は新しいものではありませんが、ドキュメント [に追加](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html)されました。 |
| 新しいセグメント演算子の制限 | 2019年6月1日を追加 | 2019年7月18日から、セグメント演算子&quot;contains any of&quot;，&quot;does not contain any of&quot;，&quot;contains all of the&quot; and&quot;does not contain all of&quot;は、入力フィールドあたり100語に制限されます。制限は、この日以降、新しいセグメントおよび変更されたセグメントすべてに適用されます。制限を超える既存のセグメントは引き続きサポートされますが、入力フィールドが減少するまで変更または保存できません。これらの制限は、クエリパフォーマンスを向上させるために継続的な努力の一環として適用されています。 |
| **[!UICONTROL 日付分類]** および **[!UICONTROL 数値 2 分類]** に関するサポートの変更予定 | 2019 年 5 月 28 日更新 | 数値 2 分類および日付分類をインポートする機能が廃止されます。この変更は 2019 年 7 月のメンテナンスリリースから有効になります。「Numeric（数値）」列または「Date-Enabled（日付）」列がインポートファイルにある場合、それらの値は警告なく無視され、そのファイル内の他のすべてのデータは通常どおりインポートされます。<br/>インポート済みの既存の分類は、通常の分類ワークフローで引き続きエクスポートでき、レポートで使用できます。 |
| _レポートの合計_の計算に対して予定されている変更 | 2019 年 5 月 2 日更新 | **2019 年 6 月 14 日** に、_レポートの合計_値の算出方法をすべてのディメンションおよび指標で共通化します。これにより、一部のレポート（通常、Prop または顧客属性レポート）の合計が変更されます。この変更以前は、レポートに_未指定_が表示されているかどうかにかかわらず、合計に_未指定_の行項目を含めるレポートと含めないレポートが混在していました。<br/>2019 年 6 月 13 日以降は、レポートの項目に「_未指定_」と表示されなくても、レポートの合計値に常に含められるようになります。また、この変更によって、「_存在する_」または「_存在しない_」ロジックを使用しているセグメントでは、一部のディメンションで異なる結果が表示される場合があります。この変更は、Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder およびレポート API に影響します。 |
| [!DNL Analysis Workspace] CSV ダウンロード機能の更新点 | 2019 年 4 月 10 日 | 2019 年 4 月 11 日以降、**[!UICONTROL CSV ダウンロード]** および **[!UICONTORL クリップボードへのコピー]**（[!DNL Analysis Workspace]）にいくつかの変更が加えられ、書き出されたデータから書式が削除されます。  <ul><li>桁区切り記号は含まれなくなりました。小数点文字は引き続き表示され、**[!UICONTROL コンポーネント／レポート設定／桁区切り記号]** で定義された形式が適用されます。注意：小数点を小数点区切り記号として使用する数値は、書き出された CSV では引き続き引用されます。</li><li>通貨記号は表示されません。</li><li>パーセント記号は表示されません。パーセンテージは 10 進形式になります。例：75%は 0.75 と表示されます。</li><li>時間は秒単位で表示されます。</li><li>コホートテーブルでは、生の値のみが表示され、パーセント値は削除されます。</li><li>数値が無効な場合は、空のセルが表示されます。</li></ul> |
| [!DNL Analysis Workspace] Debugger コマンドの変更 | 2019 年 4 月 4 日 | [!DNL Analysis Workspace] Debugger をオンにするためのコンソールコマンドは、**2019 年 6 月 13 日** に adobeTools.debug.includeOberonXml に変更されます。この日以降、adobe.tools.debug.includeOberonXml は、機能しなくなります。 |
| モバイルブラウザーのバージョン番号 | 2019 年 2 月 7 日 | 2019 年 1 月 8 日より、モバイルブラウザーバージョン番号を 2 桁から 1 桁に変更しました。この日以降、バージョンは先頭の 2 レベルのみ表示されます（例：_Firefox 64.0.2_ は _Firefox 64.0_ と表記されるようになりました）。 |
| [!DNL Ad Hoc Analysis] のサポート終了 | 2019 年 1 月 29 日 | 2018 年 8 月 7 日、アドビは [!DNL Ad Hoc Analysis] のサポート終了の意向を表明しました。サポート終了日については確定次第お知らせします。<br/>サポート終了の予定や詳細については [Discover Workspace](https://adobe.ly/discoverworkspace) を参照してください。 |
| Analytics レポートリンク | 2019 年 1 月 14 日 | 2019 年 1 月 17 日（木）以降、定期的なスケジュールで、直近 1 年間に訪問されていない短い Analytics レポートリンクは、削除されるようになります。 |
| TLS 1.0 のサポート終了 | 2019 年 1 月 10 日更新 | 2019 年 2 月 11 日現在、Adobe Analytics レポートで TLS（Transport Layer Security）1.0 の暗号化がサポートされなくなっています。この変更は、最高レベルのセキュリティ基準を維持して、お客様のデータの安全を確保するための継続的な取り組みの一環です。2019年2月11日以降にAdobe Analyticsレポートに接続できない場合は、ブラウザーを [最新バージョンにアップグレードする必要](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)があります。<br/>2019 年 2 月 20 日以降、Adobe Analytics のデータ収集で TLS 1.0 がサポートされなくなりました。この変更により、TLS 1.1 以上をサポートしていない旧型のデバイスや Web ブラウザーを使用しているエンドユーザーの Analytics データは収集されなくなりました。この変更が、お客様の顧客のデータやレポートに大きな影響を及ぼすことはないと認識しています。（お客様の Web サイトが既に TLS 1.0 をサポートしていない場合、影響は一切ありません。）<br/>2019 年 4 月 11 日以降、Adobe Analytics レポート API は TLS 1.0 の暗号化をサポートしていません。API にアクセスするお客様は、この変更による影響の有無を確認してください。 <ul><li>デフォルト設定で Java 7 を使用している API クライアントは、[TLS 1.2](https://www.java.com/en/configure_crypto.html) をサポートするように変更してください（「_Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2_」を参照、ブラウザーの翻訳機能をお使いください）。 </li><li>Java 8 を使用している API クライアントは、デフォルト設定が TLS 1.2 なので、影響を受けません。</li><li> その他のフレームワークを使用している API クライアントは、TLS 1.2 のサポートについてベンダーにお問い合わせください。</li></ul> |
| データフィード：post_product_list 列 - サイズ変更 | 2019 年 1 月 9 日 | 2019 年 2 月 7 日、post_product_list 列のサイズを 64 KB から 16 MB に拡張されました。この変更は、処理中に post_product_list に追加されるマーチャンダイジング eVar 値により、製品および売上高の値の切り捨てが発生しないようにします。post_product_list の値を取得する処理を実行する場合、これらの処理が最大 16 MB の値に対応できるようにしてください。またはデータ取得の失敗を避けるために、値が 16 MB に達した時点で値を切り捨てるようにしてください。 |
| [!DNL Analytics Live Stream] エンドポイントの管理における変更点 | 2018 年 12 月 20 日 | 2019 年 2 月 1 日以降、顧客からのアクティブな接続が 90 日間なかった [!DNL Live Stream] エンドポイントが無効化される場合があります。使用中の [!DNL Live Stream] エンドポイントについてはサポートに問い合わせて確認でき、必要に応じて再度有効にすることができます。また、サービス規定に従って顧客のプロセスで永続的な接続が維持されるように注意し、接続が切断されたり中断されたりしたときには再接続するように実装してください。 |
| TLS 1.0 のサポート終了に伴う Adobe [!DNL Report Builder] の更新 | 2018 年 9 月 7 日 | TLS 1.0 のサポート終了に伴い、[!DNL Report Builder] ユーザーの皆様には 2019 年 2 月までにバージョン 5.6.21 をダウンロードされることをお勧めします。この日以降、以前のバージョンの [!DNL Report Builder] は機能しなくなります。 |

## Audience Manager {#aam}

**修正点、機能強化および廃止された機能**

* Audience Managerでは、使用制限に対してアクティブなアルゴリズムモデルのみがカウントされるようになりました。
* 対応するモデルを使用する特性でアルゴリズムモデルのリーチが表示されない問題を解決しました。
* 特性フォルダーのコンテンツが表示されない問題を解決しました。
* 特徴タイプを1つのみ選択すると特性並べ替えが失敗する問題を解決しました。
* 新しいサブフォルダーを作成または更新するたびに、特性フォルダーツリーが [!UICONTROL すべての特性] ビューに折りたたむ問題を解決しました。
* パートナーを削除しようとする際にVIEW_ DATICTIDATM権限が必要になる問題を解決しました。
* セグメントページの [!UICONTROL 「検索」] ボックスで、選択した [!UICONTROL 項目で] はなくすべてのフォルダーを検索する問題を解決しました。
* 新しいアルゴリズムモデルを作成する際に、「特性 [!UICONTROL ] を除外」テーブルをヘッダーコントロールを通して並べ替えることができない問題を解決しました。
* 空の間隔の日付を含むレポートを実行するとAudience Managerがクラッシュする問題を解決しました。

## Experience Manager {#aem}

Adobe Experience Manager（AEM）の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

### 製品リリース

**Cloud Manager 2019.5.0**

最新のCloud Managerリリース（2019.5.0）には、いくつかのバグ修正が含まれていますが、機能的な変更は含まれていません。

* [Cloud Manager 2019.5.0 のリリースノート](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**AEM 向け XML ドキュメント**

XMLドキュメントソリューションの3.3リリースが利用できるようになりました。次のリリースノートを参照してください。

***高度なマップ機能***
* リポジトリビューから、または横棒グラフと要素カタログを使用して、トピック参照を追加します。
* トピック参照、チャンク、ナビゲーションタイトル、書式、スコープなどのメタデータを追加します。
* トピックの参照をクリックすると、エディターでトピックが開きます（チェックアウトしていない場合はプレビューモード、チェックアウトで編集を無効にするには、プレビューモードを有効にします）。
* トピックヘッドとトピックグループの追加を参照してください。
* バーマップ（トピック、はじめに、書籍リスト、通知など）とバックアイテム（トピック、付録、用語集など）を追加します。
* 作成者モードでは、壊れたリンクが強調表示され、パンくずリストが表示され、フルタグビューが使用可能になります。
* マップレベルの属性を設定できます。
* タイトル/ブックマークの設定機能。
* 再テーブルのサポート、relヘッダーおよびrepositoryからrelテーブルへのトピックのドラッグ&amp;ドロップ、リンクのリンク、スコープ、その他のパラメーターの設定、リンクのリンク、スコープ、その他のパラメーターの設定、セル内のリンクの再設定。
* ツールバーウィジェットを挿入する前に挿入し、要素の後に挿入して挿入します。
* トピックに条件が適用されている場合にハイライトします。
* 一度に複数のマップを編集できます（各マップが同じブラウザ上のタブとして開きます）。
* マップパネルとリポジトリビューのhover-トピックのフルトピックとファイル名を表示します。

***フルタグ表示***

* 2つの要素間に新しいタグを挿入します。
* タグをコピー&amp;ペーストします。
* ファイル内で許可されている位置と許可されていないタグをドラッグ&amp;ドロップします。
* タグを展開して折りたたみます。

***DITA固有の検索機能の強化***

* 選択したコンテンツを再インデックス化するためのシリアル化ツールが提供されました
* ユーザーは、検索を使用 `contains``exact match` できます。また、次のパラメーターを使用して検索することもできます。:
   * アセットメタデータを参照してください。例えば、顧客 `file name`に `title`よって定義されたカスタムメタデータなどがあります。
   * DITA属性名とその値。`platform=winOS`例えば、.
   * DITAエレメント名とその値。`author = Joe Smith`例えば、.
   * DITAエレメント名と適用される属性。例えば、product= spaceBase属性名/値のペアが適用されているテーブル。
   * DITAトピックとマップメタデータ。
   * DITA情報タイプ。試験[pull、map、topic、conceptなど）
   * アセットが存在するルートフォルダーパス。
   * ドキュメント状態。
   * チェックアウトステータス。
   * 日付範囲が変更されました。
   * CQタグ
* 上記の検索パラメーターを1つ以上組み合わせることで、複雑なクエリを作成できます。

***レビュー機能の変更***

* レビュー担当者のヒント:
   * すべてのコメントを読み込み、3.3ビルドにアップグレードする前に、オン進行中のレビューに変更を組み込みます。
   * エディターで複数のタブが開かれていないことを確認します。
   * フルタグ表示が有効になっていないことを確認します。
   * レビューが進行中の間は、作成者モードとソースモードを切り替えないでください。
* レビュー対象のコンテンツのバージョンを指定できます。
* ベースライン、日付、ラベルまたは現在アクティブなバージョンに基づいて選択したトピックのバージョンを選択するか、レビューの作成時に各トピックのバージョンを指定することができます。
* 複数回レビューするために同じトピック/マップを送信したり、エディターのレビューパネルのすべてのレビューに作成者がアクセスしたりできます。
* 開始者として、レビュー担当者向けの後のバージョンのコンテンツをプッシュできます。新しいコンテンツがレビュー用にプッシュされると、レビュアーは通知を受け取ります。
* 作成者は、ユーザーはエディターのレビューパネルでコンテンツのすべてのバージョンに対するレビューコメントを表示できます。作成者は、バージョン番号ごとにコメントをフィルターできます。
* 作成者のユーザーは、レビューの下のエディターで、古いバージョンのコンテンツのコメントを表示して読み込むことができます。

***その他***

* リポジトリビューから新しいフォルダー、トピックまたはマップを作成します。
* アセットのUIで表示-「アセットのUIで表示」の両方のフォルダとトピックのメニューオプションを追加します。このオプションを選択すると、アセットのUIが開き、左側にあるコンテンツツリーがすべて表示され、一番上にあるすべてのアセットメニューが表示されます。
* レビューダッシュボードが、レビュー担当者レベルおよびレビュータスクレベルのレビューを追跡するDITAプロジェクト上でタイルとして利用できるようになりました。
* IDMLをDITAに変換する機能を追加しました。
* 指定したすべてのバージョンに、指定したラベルをベースラインで適用するAPIを指定します。
* XHTML/DOCXからDITAへの変換が完了した後にイベントを有効にします。このイベントを使用して、変換されたコンテンツに特殊化された属性を追加したり、実装する必要のある他のカスタムロジックに追加したりできます。
* ベースラインパフォーマンスタブの改善が行われました。ユーザーは、既存のすべてのベースラインでスクリプトを実行する必要があります。
* XHTMLからDITAへの変換が強化されました。
* DITA- OTオフロードの最適化を参照してください。
* リスト表示のタイプ列の並べ替えを修正しました。
* WordからDITAへの変換でカスケードスタイルを処理できるようになりました。

### コミュニティ

**[Cloud Managerスキルビルダーのウェビナーシリーズ](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

devOpsの処理によって、クラウド内のAdobe Experience Manager Managementの毎日のアクティビティを簡単に処理できます。Cloud Managerは、組織がdevOps変換を開始しているか、既存のdevOpsプロセスを補強する戦略を探しているかにかかわらず、クラウドの俊敏性を実現するAdobe Experience Managerのクラウドネイティブ機能を提供します。

[この毎月のシリーズ](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)では、クラウドマネージャー機能を使用して、クラウド内のAdobe Experience Manager Managementをシンプルにする方法について、アドビの製品チームから直接学習できます。

以下について学習します。
* Cloud Managerの起動方法とCI/CDパイプラインのセットアップ方法
* 自動拡大/縮小サービスと透明サービス配信の仕組み、およびクラウド内のAdobe Experience Manager環境管理を簡素化する
* Cloud Manager APIと既存のdevOpsプロセスの統合方法

### その他のリソース

* [AEM 6.5 ラーニングとサポートホーム](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 ラーニングとサポートのホーム](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager ユーザーガイド](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [AEM ドキュメントの以前のバージョン](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System リリースノート](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre リリースノート](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Campaign {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### Campaign Classic19.1Springリリース

| 機能 | 説明 |
| ------------- | ----------- |
| コントロールパネル | 管理者ユーザーとして作業効率を向上させるには、ストレージ、ホワイトリスト登録IPアドレス、各インスタンスにSSHキーをインストールして、SFTPサーバーの設定を管理します。コントロールパネルは、今日の時点ではAWSでホストされているお客様のみ利用できます。[Experience Cloudを使用してログイン](https://experiencecloud.adobe.com/campaign/controlpanel/)します。<br> 詳しくは、 [詳細ドキュメント](https://helpx.adobe.com/campaign/kb/control-panel.html) とハウツービデオ [](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html)を参照してください。 |
| 監査証跡 | 管理者として、Adobe Campaign Classicインスタンス内で行われた変更を監視および管理することにより、生産性を向上させます。監査証跡は、ソーススキーマ、ワークフローおよびオプションで行われたアクションを記録します。要素が作成、変更または削除されたかどうかをすばやく確認できます。<br>詳しくは、 [詳細ドキュメント](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) とハウツービデオ [](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html)を参照してください。 |
| Guardrail、堅牢性およびスケーラビリティ | キャンペーンClassicに一連の改善が加えられました。Guarddlail、堅牢性およびスケーラビリティの改善については [、キャンペーンClassicリリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html)を参照してください。 |
| セキュアSMSメッセージング（TLS） | 拡張された汎用SMPP Connectorを通じて、保護されたSMSがサポートされるようになりました。これにより、プロバイダーへの暗号化された接続が可能になります。<br>詳しくは、[詳細ドキュメント](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)を参照してください。 |
| 互換性マトリックスの更新 | この新しいバージョンでは、Adobe Campaignで以下のデータベースシステムがサポートされるようになりました。互換性マトリックスを参照し [てください](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle18c</li><li>MySQL5.7（FDA）</li><li>SQL Server2017</li><li>Teradata16（FDA）</li><li>PostgreSQL11</li></ul> |

修正点と機能改善については、[Adobe Campaign Classic リリースノート](http://docs.campaign.adobe.com/doc/AC/en/RN.html)を参照してください。

### Campaign Standard19.2Springリリース

| 機能 | 説明 |
| ------------- | ----------- |
| コントロールパネル | 管理者ユーザーとして作業効率を向上させるために、容量を容易に監視し、インスタンスの設定を管理できます（SFTPサーバー管理から開始）。<br> 詳しくは、 [詳細ドキュメント](https://helpx.adobe.com/campaign/kb/control-panel.html) とハウツービデオ [](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html)を参照してください。 |
| ローカル通知 | ローカル通知メッセージを使用すると、インターネットやモバイルアプリケーションにアクセスしなくても、モバイルアプリケーション内で新しいデータが利用可能になったときにユーザーに通知できます。ローカル通知は、特定の時間に、およびイベントに応じてモバイルアプリケーションによってトリガーされます。<br>詳しくは、[詳細ドキュメント](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type)を参照してください。 |
| ワークフローの機能強化-外部シグナルアクティビティへのペイロードの追加 | 定義された条件が別のワークフローから正常に満たされた場合、または外部システムと統合するREST API呼び出しが正常に完了した場合に、ペイロードを使用してワークフローを開始します。これには、この機能でテストを実行できる新しいテストアクティビティも含まれています。<br>詳しくは、 [詳細ドキュメント](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) とハウツービデオ [](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html)を参照してください。 |
| ランディングページの機能強化- Google reCAPTCHA | Google reCaptchAを利用して、顧客からの行動を起こさずにランディングページでスパムを防ぐことができます。<br>詳しくは、[詳細ドキュメント](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha)を参照してください。 |

製品ドキュメントについては、以下を参照してください。

* Adobe Campaign Standard：[ドキュメント](https://helpx.adobe.com/support/campaign/standard.html) - [リリースノート](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 機能のビデオ](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic：[ドキュメント](https://helpx.adobe.com/support/campaign/classic.html) - [リリースノート](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 機能のビデオ](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* TLS1.0は、すべてのAdobeサーバーで無効になっています。Android4. xデバイスがSSL経由でアドビのサービスに接続するために、ハンドシェイクの確立時にSDKがTLS1.1/TLS1.2を強制するようになりました。

## Advertising Cloud {#adcloud}

5 月 8 日のリリースに向けて 2019 年 6 月 6 日に更新。

| 製品 | 機能 | 説明 |
| -----------| ---------- | ----------  |
| キャンペーン、ラベルの分類および制約の検索 | キーボードショートカット | <b>Shiftキーを押しながらクリック</b> して複数の連続した行を選択し、 <b>Ctrlキーを押しながらクリック</b> して連続しない複数の行を選択できるようになりました。 |
|  | すべてを選択します。ページ上のすべて選択 | データテーブルでは、すべての行を選択するために上部のチェックボックスを選択すると、そのページのすべての行が選択されます（行、行、行、100行、200行、連続スクロールのいずれを表示しているかに基づきます）。すべての行を選択できるオプションがあります。 |
| デフォルトビュー、カスタムビュー、スタンドアロンの列のカスタマイズ設定 | 列の並べ替え | 新しい上下ボタンを使用すると、列の順序を変更できます。以前のように、列をドラッグ&amp;ドロップして並べ替えることができます。 |

## Target Standard/Premium19.6.1（2019年6月26日） {#target}

最新のリリース情報についてはAdobe Target リリースノートを参照してください。

[Target リリースノート（プレリリース）](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Target リリースノート（現行）](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

Magento は、柔軟なショッピングカートを備えたオンラインマーチャントを提供し、オンラインストアの外観、コンテンツ、機能を制御できる E コマースプラットフォームです。Magento には、オープンソースのバージョンとフル機能コマースバージョンがあります。

Magento Commerce は、Adobe Commerce Cloud に含まれており、エンタープライズ向けのパワー、無制限のスケーラビリティ、および B2C / B2B エクスペリエンス向けのオープンソースの柔軟性を備えた e コマースソリューションを提供します.

オープンソースとコマースの両方のエディションのリリースノートは [、リリース情報](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) ページで確認できます。

## Primetime {#primetime}

Adobe Primetime は、メディア企業に適したマルチスクリーン TV プラットフォームです。ユーザーの心をつかむパーソナライズ可能な視聴体験を提供し、収益化できます。

[Primetime リリースノート](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime ヘルプのホーム](http://help.adobe.com/en_US/primetime/)

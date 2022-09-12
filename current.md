---
title: 最新のリリースノート
description: Adobe [!DNL Experience Cloud] 製品とサービス。 今後のイベントおよびイベントに関する新しいドキュメントについてExperience Leagueします。 の最新のチュートリアルとコースを見つける [!DNL Experience Cloud] アプリケーション。
doc-type: release notes
last-update: September 2022
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: 3dade77ca8f59fbe80c96442b26bb9998dd0d381
workflow-type: tm+mt
source-wordcount: '6560'
ht-degree: 41%

---

# Adobe Experience Cloud リリースノート - 2022年9月

![バナー](assets/experience-cloud-banner-3.png)

Experience Maker として成功するための道のりは、[Experience League](https://experienceleague.adobe.com/?lang=ja#home) から始まります。膨大なハウツードキュメントのライブラリ、セルフガイドのチュートリアル、ハウツービデオ、あらゆるレベルや役割に対応したコース、仲間とのオンラインコミュニティ、必要な時には専門家によるサポートを利用できます。

>[!NOTE]
>
>このページの更新に関するメール通知を毎月受け取るには、[Adobe Priority 製品アップデート](https://www.adobe.com/subscription/priority-product-update.html)を購読してください。Experience League の最新情報を把握できるよう、頻繁にチェックしてください。

最終更新日：**2022年9月12日（PT）**

* [[!DNL Experience League] イベント](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - 主要なインターフェイスコンポーネントと管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem) ( 更新済み **9 月 13 日**)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [デジタルエクスペリエンスブループリント - チュートリアル](#blueprints)

サポートが必要な場合[Experience League](https://experienceleague.adobe.com/?lang=ja#home) にアクセスして、製品および技術ドキュメント、アドビがキュレートしたコース、ビデオチュートリアル、クイックアンサー、コミュニティインサイト、インストラクター主導のトレーニングをご覧ください。

## ![アイコン](/assets/experience-league.png) [!DNL Experience League] イベント {#events}

Experience League イベントでは、アドビの製品エキスパートから学び、やり取りし、回答を得ることができます。2022年7月の最新情報について詳しくは、Experience League の[イベント](https://experienceleague.adobe.com/events/?lang=ja)を参照してください。

更新済み **2022 年 9 月 10 日**

| 製品/イベント名 | タイプ | 説明 |
| -----------|---------- | ----|
| **Experience Leagueショーケース** | コンテスト | AdobeにExperience Cloud製品を統合し、革新的でパーソナライズされた顧客体験を作成する方法を伝えます。 ストーリーを提出し、Adobeによって認識される！ **9 月 9 日～29 日のエントリ許可** - [詳細](https://experienceleaguecommunities.adobe.com/t5/experience-league-showcase-2022/con-p/exl-showcase-2022?sdid=3NQZB6J7&amp;mv=email) |
| **[!DNL Adobe Workfront]** | ワークショップ | 他のお客様とつながり、話し合う機会を探しています [!DNL Workfront] 機能？ CS Connections シリーズにご参加ください。 他のお客様と連絡を取り、組織のホットトピックについて話し合う月 1 回の機会。<p>**日付：** 9 月 12 日@ MT 午前 7 時 ) [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,frxd5xOTA0WDD-QNQbG9Ww,N0rLVNiX1EKbZDmYfMbfKg,mwypq4e8M0qTYr1PjHWlgg?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Experience Cloud]** | ウェビナー | _Experience Makers ライブ_ - Sara Blakely、Peyton Manning、Eli Manning のキーノートを含む無料イベント。<p>**日付：** 9月13〜14日（PT）- [詳細と登録](https://business.adobe.com/events/experience-makers-live.html?lang=ja) |
| **[!DNL Adobe Campaign]** （Classic と Standard） | ウェビナー | クロスチャネルマーケター向けのホリデーシーズンと最も忙しい時間が近づいています。 計画は進行中です。 この [!DNL Adobe Campaign] Insider セッションでは、E メールの配信品質を支援するトピックについて説明しています。 [!DNL Adobe Campaign] パフォーマンスの調整、ワークフローおよび配信のベストプラクティスを追加し、ピーク時のアクティビティに合わせてインスタンスが適切に構成されるようにします。<p>**日付：** 9 月 15 日@午前 8 時（太平洋標準時） [詳細と登録](https://adobe-campaign-insider.dxfieldmarketing.adobeevents.com/) |
| **[!DNL Adobe Workfront]** | ワークショップ | 図ワークフロー — 顧客サクセスチームに参加して、ライブディスカッションや図ワークフローのウォークスルー（取り込みから完了まで）をおこない、効果的な作業管理慣行の基盤を確立する方法を理解します。 <p>**日付：** 9月20〜日（PT）- [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,8IgA8CD5yEyKFei9pwlDJA,iACjdG_hK0m1uoTTaMinZA,TEaHrWBF3USQb49XCqymTg?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | ウェビナー | _システム管理の基本事項：リソース管理の概要_ -Adobeを使用 [!DNL Workfront] リソースを管理するのは DREAM（実行する必要がある作業、アクセスできるリソースを把握し、使用可能な状況に基づいて割り当てる）です。 ぜひご参加ください。<p>**日付：** 9 月 21 日@英国午前 8 時 ) [詳細と登録](https://webinars.on24.com/adobe_workfront/AdminEssentialsRM?partnerref=exl) |
| **[!DNL Adobe Workfront]** | ワークショップ | _値実現シリーズ：プロジェクトテンプレートの例を作成する_ .....に関する議論に参加して下さい。 [!UICONTROL プロジェクトテンプレート] そして、組織に価値を与え、効率性を高めるさまざまな方法を提供しています。 キャンペーン別、成果物別など、様々なテンプレート構造化方法でプロジェクトをサポートする方法についてブレインストーミングを行います。 お気に入りのデモを行い、最新の設計図を確認します。 <p>**日付：** 9 月 21 日@午後 12 時半 MT [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,fir0yEdzREq77VYkVxk2kw,W3nJ9w4q-U69PVqUTk7D6Q,zs6GtWtgRkyikfMUMzBEmw?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | ワークショップ | _10 人のコミュニケーションに関するヒント（ユーザーとユーザーの追跡を維持するため）_  — 効果的なコミュニケーションは、お客様、ユーザー、そして最終的には、企業の成功に不可欠な要素です。 このワークショップでは、10 のヒントを提供します。 [!DNL Workfront]  — パフォーマンスの向上、生産性の向上、不要な問題のリスクの軽減に役立ちます。 <p>**日付：** 9 月 22 日@午後 7 時 MT [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,PiX3iDTmREqs2eOICcUIoA,5KJVGb6S_Uiiki7ErNALgw,Jcg3aU0zf0uG9pB-_vmCUg,pdnZcB-mqk2_nMKUQEQnsA,xYRXQWa6OU6_tvNTp_vuFQ?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Campaign Classic]** および **[!DNL Adobe Campaign Standard]** | ワークショップ | _コミュニティ Q&amp;A コーヒーブレーク_ - Tamara Wulf と Earl Ross に参加して、 [!DNL Adobe Campaign] Insider のオンラインセミナ _休日・四季折々の成功チェックリスト_. <p>**日付：** 9 月 22 日@午後 8 時 MT [詳細と登録](https://adobe.ly/3KHrGpl) |
| **[!DNL Adobe Workfront]** | ワークショップ | _ダッシュボードによる採用の促進：プランナー_ - [!DNL Adobe Workfront] ペルソナ。 このセッションでは、多くの場合、プロジェクトまたはイニシアチブ管理の役割で機能するプランナーに焦点を当てます。 活動の認知と説明責任のための、積極的でチーム指向の空間を構築する方法を学びます。 <p>**日付：** 9 月 27 日@ MT 午前 9 時 ) [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,Y1He1usOwUaIvlln-RiUCw,PbQY6cwRBkiHr0Uxk8YBow,2QMMEWx0e0C65kbQ1d4cIA?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | ワークショップ | _値実現シリーズ：Workfrontジャーニーのロードマッピング_ —Workfrontジャーニーの次の機能 お客様の組織でAdobe Workfront向けの独自のロードマップを作成する方法について、お問い合わせください。 お気に入りのマイルストーンに関するアイデアをいくつか紹介し、ロードマップに加えて、以前のシステム管理者と同様に、アドビの経験を追加します。<p>**日付：** 10 月 4 日@午後 12 時半 MT [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,Bx3LyyABjkC6f0LfiHlHgw,F_Tenijn5UulPjqprok8eg,7lni6LpvlEWagR1OIDfosA?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | ワークショップ | _CS 接続：戦略的ベストプラクティスの共有_  — 他のお客様とつながり、Workfrontの機能について話し合う機会をお探しですか？ CS Connections シリーズにご参加ください。  他のお客様と連絡を取り、組織のホットトピックについて話し合う月 1 回の機会。 課題の解決、アイデアの共有、ベストプラクティスについて話し合うために、システム管理者と共にブレインストーミングをおこないます。 <p>**日付：** 10 月 10 日@午前 7 時 (MT) [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,gw8sK1IYp0qugO85lvn9HA,1hAkk731fE2cuzI1JCe2Aw,Lox5X4bDSUC_HaF3SDUy7A?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | ワークショップ | _ユーザー管理による導入の促進_ —Workfrontを使い始めたとき、エンドユーザーに関連する設定機能をより深く知りたいと思っていますか？ レポートやダッシュボードの実践例を確認し、ユーザー管理を成功に導く基盤を設定し、有用で有益なエンドユーザーエクスペリエンスを作成する際に、カスタマーサクセスチームに参加します。<p>**日付：** 10 月 18 日@ MT 午前 9 時 ) [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,lJV3sMGDTE2CpLxcuzZQXg,KGHthDBZ80q9JJ-wzHyqBQ,mY-6BCClJkmc_bRvqGebtQ?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | ワークショップ | _採用シリーズ：Workfrontを楽しむ（前）!_ アイデアの採用が必要な場合 持ってる！ 当社のチームは、ユーザーの採用状況の高さと低さを経験し、楽しみに焦点を当てることが成功の鍵です。 私たちは、私たちのために働いたいくつかの事を通じてチャットし、他のお客様とアイデアを共有するオープンなディスカッションの時間を十分提供します。<p>**日付：** 10 月 20 日@午後 12 時半 MT [詳細と登録](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,0qiSuEYEcUSxTibSYXD-jA,8QGOKlkyJE25EiBggDF6Ng,WmVegsyV2E6ZDPSMCifdVw?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |

{style=&quot;table-layout:auto&quot;}

今後のイベントと過去のエピソードについて詳しくは、Experience League の[イベント](https://experienceleague.adobe.com/events/?lang=en)を参照してください。

## ![アイコン](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] は、アドビ製品とサービスの停止、中断、メンテナンスイベントに関する詳細情報、ステータス更新、電子メール通知を提供します。[status.adobe.com](https://status.adobe.com/ja) でご確認ください。

最新のリリース情報については、Adobe System Status の[リリースノート](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=ja#status)を参照してください。

## ![アイコン](/assets/ec_appicon_24.png) Experience Cloud - 主要なインターフェイスコンポーネントと管理 {#ecloud}

Experience Cloud の[主要な UI コンポーネント](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ja)には、ホームページで使用できる機能と、永続的な製品ヘッダーが含まれます。これらの機能には、ユーザープロファイル設定、環境設定、検索などが含まれます。また、ユーザーと製品の管理、顧客属性、Experience Cloud Audiences に関するヘルプも参照できます。

### プロビジョニングの更新

>[!IMPORTANT]
>
>管理者の皆様は、Experience Cloud のプロビジョニングに関するこの[重要な通知](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=ja#july---2022)（2022年7月に公開）をお見逃しなく。

## ![アイコン](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] と [!UICONTROL Mobile SDK] の最新リリース情報および新規ドキュメント：

リリース予定日： **2022 年 9 月 29 日**

* [Experience Platformリリースノート](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ja) - （2022 年 8 月 25 日）

### [!DNL Adobe Mobile] SDK

更新： **2022 年 9 月 2 日**  — 詳しくは、 [リリースノートと変更ログ](https://aep-sdks.gitbook.io/docs/release-notes) (Adobe Experience Platform Mobile SDK 用 )

## ![アイコン](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

次期リリース： **2022 年 9 月 15 日**

最終更新日： **2022 年 9 月 7 日**

* Adobe Analytics [リリースノート](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=ja)
* Adobe Analytics [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/analytics.html?lang=ja)

### AppMeasurement {#appm}

リリースバージョン：**2.22.4**

* [JavaScript 版 AppMeasurement リリースノート](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ja)

### 新しい [!DNL Analytics] のチュートリアルとコース {#tutorials-analytics}

Adobe Analytics 用に公開された新しいビデオチュートリアル、記事およびコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年9月 | [フロービジュアライゼーションの作成](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-visualization.html?lang=en) | ビデオ | フロービジュアライゼーションを使用して、顧客のブランドに関する正確なジャーニーを調査する方法を説明します。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

最終更新日：**2022年9月6日（PT）**

* Customer Journey Analytics [リリースノート](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=ja)
* Customer Journey Analytics [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=ja)

### 新しい Customer Journey Analytics チュートリアルとコース {#tutorials-cja}

CJA 用に公開された新しいビデオ、チュートリアル、またはコース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年9月 | [Customer Journey Analytics 向けのオーディエンスの公開](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/audiences/audience-publishing-for-cja.html) | ビデオ | Customer Journey Analyticsを使用し、Adobe Real-time Customer Data PlatformまたはAdobe Journey Optimizerを使用して、分析から発見したオーディエンスをAdobe Experience Platformリアルタイム顧客プロファイルに公開し、セグメントのアクティベーションに利用する方法を説明します。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

最終更新日：**2022年3月23日（PT）**

* [!DNL Streaming Media Analytics] [リリースノート](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=ja)
* [!DNL Streaming Media Analytics] [製品ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=ja)

## ![アイコン](/assets/audience-manager.png) Audience Manager {#aam}

未更新

セルフヘルプリソースについては、Experience League の [Audience Manager ドキュメントとチュートリアル](https://experienceleague.adobe.com/docs/audience-manager.html?lang=ja)を参照してください。

## ![アイコン](/assets/aem.png) Adobe Experience Manager {#aem}

 Experience Manager の新機能、修正点および更新です。安定性、セキュリティ、パフォーマンスを高めるために、オンプレミス環境のお客様には最新のパッチをデプロイすることをお勧めします。

<!-- See [Current Release Notes for Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html) -->

[Experience Manager リリースのアップデートとロードマップ](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ja)ページにアクセスして、リリース情報に関する最新情報を入手することをお勧めします。

### 製品アップデートビデオ

次を監視： [2022 年 8 月リリースの概要ビデオ](https://video.tv.adobe.com/v/345409/?quality=12) 2022.8.0（2022 年 8 月）リリースに追加された機能の概要。 <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

* [2022 年 7 月リリースの概要ビデオ](https://video.tv.adobe.com/v/345409/?quality=12)
* [2022年6月リリースの概要ビデオ](https://video.tv.adobe.com/v/344308/?quality=12)
* [2022年5月リリースの概要ビデオ](https://video.tv.adobe.com/v/343321/?quality=12)
* [2022年4月リリースの概要ビデオ](https://video.tv.adobe.com/v/342612?quality=12)
* [2022年3月リリースの概要ビデオ](https://video.tv.adobe.com/v/341465)
* [2022年1月リリースの概要ビデオ](https://video.tv.adobe.com/v/340120)
* [2021年12月リリースの概要ビデオ](https://video.tv.adobe.com/v/339278)
* [2021年10月リリースの概要ビデオ](https://video.tv.adobe.com/v/338253)
* [2021年9月リリースの概要ビデオ](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Assets] as a [!DNL Cloud Service]

_新機能_

* デジタルアセットをリンクとして共有する場合、ユーザーは URL をクリップボードにすぐにコピーできます。この機能強化により、アセットをより速く、より便利な方法で共有できます。この機能により、迅速で便利なアセット共有が可能になります。
* TXT ファイルをアップロードすると、アセットマイクロサービスによって自動的にサムネールが生成されます。PNG サムネールは、ユーザーがファイルを開かなくても、コンテンツやファイルをある程度識別するのに役立つ TXT ファイルのレンディションです。この機能は設定を必要とせず、デフォルトで機能します。

_プレリリースチャネルで利用できる新機能_

* 検索結果に表示されるアセットを、ユーザーが列表示およびカード表示で並べ替えることができるようになりました。並べ替えは、名前、作成済み、変更済み、またはなしの列で機能します。

### Experience Manager [!DNL Forms] as a [!DNL Cloud Service]

_新機能_

* Forms as a Cloud ServiceのAEMアーキタイププロジェクトに、が含まれるようになりました。 [Microsoft® Dynamics および Salesforce.com のフォームデータモデル](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/setup-environment/setup-local-development-environment.html?lang=en#forms-cloud-service-local-development-environment).
* Acroform ベースのレコードのドキュメント：Experience Manager Formsas a Cloud Serviceサポート [Adobe Acrobat FormPDF(AcroformPDF)](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/generate-document-of-record-for-non-xfa-based-adaptive-forms.html) XFA ベースのフォームテンプレート以外のレコードのドキュメントのテンプレートとして。
* Microsoft® Azure データストアコネクタ：次の操作を実行できます。 [フォームデータモデルをMicrosoft® Azure ストレージに接続する](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/configure-azure-storage.html). これにより、アダプティブフォームのデータを取得し、BLOB としてMicrosoft® Azure ストレージに保存することができます。

_Forms のベータ機能_

* **統合ストレージコネクタ**  — 統合ストレージコネクタを使用して、顧客管理リポジトリ内の処理中のデータを外部化します。 例えば、次のことができます。
   * Forms Portal の保存と再開機能を有効にし、顧客が管理するデータリポジトリにアダプティブフォームのドラフトを保存します。
   * 顧客が管理するリポジトリに、機密個人Experience Manager(SPD) を含むインプロセス・データ (Experience Manager・ワークフロー変数データ ) を格納します。
* **Experience Manager Formsas a Cloud Service、通信** - [通信 API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html) は、XDP テンプレートと XML データを組み合わせて、様々な形式の印刷ドキュメントを生成する場合に役立ちます。 このサービスを使用すると、同期モードでドキュメントを生成できます。API を使用すると、次の操作を可能にするアプリケーションを作成できます。
   * テンプレートファイルに XML データを入力してドキュメントを生成します。
   * 非インタラクティブ PDF 印刷ストリームを含む様々な形式で出力フォームを生成します。
   * XFA フォーム PDF および Adobe Acrobat フォームから印刷用 PDF ファイルを生成します。[formscsbeta@adobe.com](mailto:formscsbeta@adobe.com) に書き込んで、ベータ版プログラムに新規登録できます。

_プレリリースチャネルで利用できる新機能_

* **アダプティブフォームでのAdobe Signの役割の使用** - Adobe Sign for business and enterprise service levels では、契約受信者の役割を署名者だけでなく拡張して、ワークフロー要件に合わせることができます。 [同意書の各受信者がアダプティブフォーム](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/use-adobe-sign/working-with-adobe-sign.html?lang=en#addsignerstoanadaptiveform) で自分の役割を設定できるようになりました。署名者 はデフォルトの役割です。
* **Analytics for Adaptive Forms** - Adobe Analyticsを介してエンドユーザーの行動をキャプチャおよび追跡し、アダプティブFormsでエンドユーザーのインサイトを収集できるようになりました。 データに基づく情報に基づく意思決定をおこない、エンドユーザーエクスペリエンスを向上させるのに役立ちます。
* **Experience Manager FormsをMicrosoft® Dynamics および Salesforce.com に簡単に接続**  — このサービスは、標準のデータソース設定と、Microsoft® Dynamics および [Salesforce.com](https://www.salesforce.com/jp/?bc=DF). この能力が有る [開発者がMicrosoft® Dynamics 365 と Salesforce クラウドサービスをアダプティブフォーム用にすばやく簡単に設定できる](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/configure-msdynamics-salesforce.html).

### Experience Manager Screens as a Cloud Service

_新機能_

* Screens as a Cloud Service で、基本的な再生モニタリングがサポートされるようになりました。各 ping で様々な再生指標がレポートされるようになりました（デフォルトは 30 秒）。 指標に基づいて、様々なエッジケース（動きのないエクスペリエンス、空白の画面、スケジュールの問題など）を検出できます。この機能を使用すると、プレーヤーがコンテンツを適切に再生しているかどうかをチームがリモートで監視できます。また、フィールド内の空白の画面や壊れたエクスペリエンスに対する反応性が向上し、壊れたエクスペリエンスがエンドユーザーに表示されるリスクが低くなります。
詳しくは、[基本的な再生モニタリング](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/screens-as-cloud-service/manage-player-registration/installing-screens-cloud-player.html?lang=en#playback-monitoring)を参照してください。
* ビデオのサムネールが Screens as a Cloud Service でサポートされるようになりました。コンテンツ作成者は、画像をプレースホルダーとして使用できるように、ビデオのサムネールを定義できます。 適切なチームによって実際のビデオに関する最終決定が下される間に、コンテンツの再生とターゲティングのテストを適切におこなうことができます。ビデオの再生に失敗した場合にも、画像を使用できます。
詳しくは、[ビデオのサムネールサポート](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/screens-as-cloud-service/core-product-features/thumbnail-support-videos.html)を参照してください。

### [!DNL Cloud Manager]

_新機能_

* Cloud Manager で使用されるAEM Archetype プロジェクトのバージョンが、バージョン 30 に更新されました。
* これで、Cloud Manager ランディングページのプログラムカードと関連するエクスペリエンスが更新されます。
* コード品質ステップログ に、OakPal スキャンプロセスの詳細なログ情報が含まれるようになりました。
* アクティビティページのメニューオプションに、コードジェネレーターの完了時にログをダウンロードするオプションが追加されました。 これを選択すると、ビルド手順のログがダウンロードされます。
* プログラムカードを直接クリックすると、 Cloud Manager の概要ページに移動するようになりました。
* Cloud Serviceのお客様は、Cloud Manager で SLA(Service Level Agreement) レポートを表示できるようになりました。 この機能は、今後数か月間、徐々に使用可能になっていきます。
詳しくは、[SLA レポート](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/sla-reporting.html)を参照してください。
* IndexType および IndexDamAssetLucene 品質ルールのタイプと重大度が変更されました。 これらは両方とも致命的な重大度のバグとなりました。
* 非同期および Tika 設定に対応する新しい Oak インデックス品質ルールが導入されました。
* プログラムごとの SSL 証明書の最大数を 50 に増やします。
* ユーザーが Cloud Manager ユーザーインターフェイスを介して複数のリポジトリを作成および管理できるセルフサービス機能。
* SonarQube が Git 履歴データを不必要に読み取っていました。大規模なコードベースでは、これにより、ビルドパフォーマンスが不必要に低下することがありました。
* パイプラインごとに Maven 依存関係キャッシュを無効にする API が追加されました。
* Cloud Manager で使用されるAEM Archetype プロジェクトのバージョンが、バージョン 29 に更新されました。

### コミュニティ

* 以下の包括的なリスト [Experience Leagueの最新のExperience Managerの内容は、こちらをご覧ください](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/421751?profile.language=ja#M29908).
* [Adobe Experience Cloud](https://www.linkedin.com/company/adobe-experience-cloud/) コミュニティとは、ユーザーが顧客に対してゲームを変えるデジタルエクスペリエンスを作り出せるように、連携し、惹きつけ、力を与えるハートビートです。
すべてのコミュニティアドバイザのリストを確認するには、次を参照してください [Adobeブログ](https://blog.adobe.com/en/publish/2021/09/02/introducing-the-2021-adobe-community-advisors#gs.a6braz).
* 新機能リクエストまたは提案をExperience Managerに送信する方法
   * Experience Manager機能リクエストを送信する新しいプロセスが公開されました。 [アイデアの作成](https://experienceleaguecommunities.adobe.com/t5/forums/postpage/board-id/adobe-experience-manager-ideas?profile.language=ja). |
   * 詳しくは、 [詳細はこちら](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-the-new-process-to-submit-experience-manager-feature/td-p/380425?profile.language=ja).
   * [新しいアイデアの送信に関するExperience Manager](https://experienceleaguecommunities.adobe.com:443/t5/adobe-experience-manager-blogs/guidelines-for-submitting-a-new-experience-manager-aem-idea/ba-p/382376).

### 新しい Adobe Experience Manager コースとチュートリアル {#tutorials-aem}

以下は、過去 1 か月間に公開された新しいビデオ、チュートリアル、コースです。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022年9月 | [AEM as a Cloud Service 2022.8.0 リリースの更新](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2022/2022-8-0.html?lang=ja) | ビデオ | AEM製品チームから連絡を受け、Adobe Experience Managerの最新リリースの機能とイノベーションについて学びます [!DNL Assets], [!DNL Assets Essentials], [!DNL Sites]，コマース統合フレームワーク， [!DNL Forms]、および [!DNL Cloud Manager]. | AEM |
| 2022年9月 | [Web に最適化された画像配信](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/components/web-optimized-image-delivery.html?lang=en) | ビデオ | AEMコアコンポーネントを使用して、AEMas a Cloud Serviceのサイトで Web に最適化された画像配信を有効にする方法について説明します。 | AEM Sites |
| 2022年9月 | [Microsoft® Power Automate との統合](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-and-power-automate/integrate-formscs-power-automate.html?lang=en) | ビデオ | アダプティブフォームの送信時に自動フローを起動します。Forms CS を設定し、Microsoft® Power Automate と統合する手順について説明します。 送信されたフォームデータを解析し、DoR を電子メールの添付ファイルとして送信します。 | AEM Forms CS |
| 2022年9月 | [Adobeコンテンツ管理フォーラムイベントシリーズ — 2022 年](https://experienceleague.adobe.com/docs/adobe-content-management-forum-events/events/2022/welcome.html?lang=en) | ビデオ | ウェルカムアドレスを見て、AEMの概要（Elliot Sedegah 著）をご覧ください。 また、コンテンツ速度の力の解放などについても説明します。 | AEM CS |
| 2022年9月 | [スキル交換 — デベロッパートラック — Experience Makers Spotlight](https://experienceleague.adobe.com/docs/skill-exchange-events/events/aem/aug2022/developer-track/spotlight.html?lang=en) | ビデオ | 2 人のエキスパートAEMユーザーに注目してください。 それぞれが、最高のAEMのヒントまたはトリックを共有します。 | AEM CS |
| 2022年9月 | [スキル交換 — マーケター/Web パブリッシャー](https://experienceleague.adobe.com/docs/skill-exchange-events/events/aem/aug2022/marketer/reusability.html?lang=en) | ビデオ | エクスペリエンスフラグメントを利用して、エコシステム全体での再利用と効率化を推進する方法を説明します。 これは ROI とドライブ速度に影響を与えます。 | AEM CS |
| 2022年9月 | [AEM React 編集可能コンポーネント v2 の使用方法](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/spa-editor/how-to/react-core-components-v2.html?lang=en) | ビデオ | AEM React 編集可能コンポーネントの使用方法を説明します。 AEMは、AEM SPA Editor を使用してコンテキスト内のコンポーネントの編集をサポートする、React コンポーネントの作成を可能にする Node.js ベースの SDK である、AEM React Editable Components v2 を提供します。 | AEM CS |

{style=&quot;table-layout:auto&quot;}

### Adobe Experience Manager リリース情報

Experience Manager のリリースノートはすべて以下のページに記載されています。

* [Adobe Experience Manager as a Cloud Service リリース情報](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=ja)
* [Adobe Experience Manager Cloud Manager リリースノート](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=ja)
* [自動フォーム変換サービスリリースノート](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=ja)
* [Adobe Experience Manager 6.5 Service Pack リリースノート](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=ja)
* [Adobe Experience Manager 6.4 累積修正パックリリースノート](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ja)
* [Adobe Experience Manager Assets Dynamic Media リリースノート](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=ja)
* [Adobe Experience Manager Brand Portal リリースノート](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ja)
* [Adobe Experience Manager デスクトップアプリケーションリリースノート](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=ja)
* [Adobe Experience Manager Dispatcher リリースノート](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=ja)
* [Adobe Primetime リリースノート](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=ja)
* [Livefyre リリースノート](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=ja)

### Experience Manager に関するその他のヘルプリソース

* [Adobe Experience Manager as a Cloud Service に関するガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=ja)
* [Cloud Manager ユーザガイド](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=ja)
* [Adobe Experience Manager 6.5 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ja)
* [Adobe Experience Manager 6.4 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ja)
* [Adobe Experience Manager 6.3 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja)
* [Adobe Experience Manager 6.2 のラーニングとサポートのホーム](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ja#previous-updates)
* [Adobe Experience Manager ドキュメントの以前のバージョン](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic ヘルプホーム](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ja)
* [Adobe Experience Manager ドキュメント：最近の更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ja#aem-as-a-cloud-service)

## ![アイコン](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] は、AEM にデプロイされたアプリケーションです。Adobe Experience Manager でのネイティブ DITA サポートを可能にし、AEM が DITA ベースのコンテンツの作成と配信を処理できる、強力なエンタープライズグレードのコンポーネントコンテンツ管理ソリューション（CCMS）です。

詳しくは、[[!DNL Experience Manager Guides]](https://www.adobe.com/jp/products/xml-documentation-for-experience-manager/features.html)を参照してください。

### その他のリソース

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=ja) - Experience League のチュートリアル
* [[!DNL Experience Manager Guides] ラーニングとサポート](https://helpx.adobe.com/jp/support/xml-documentation-for-experience-manager.html) - 製品ドキュメント

## ![アイコン](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Adobe Commerce リリースノートについては、以下のリンクを参照してください。

* [Adobe Commerce および Magento Open Source 2.4.x リリースノート](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite のリリースノート](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)
* [支払いサービスのリリースノート](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/release-notes.html)
* [製品Recommendationsのリリースノート](https://experienceleague.adobe.com/docs/commerce-merchant-services/product-recommendations/release-notes.html)
* [ライブ検索のリリースノート](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/release-notes.html)
* [ストアの達成に関するリリースノート](https://experienceleague.adobe.com/docs/commerce-merchant-services/store-fulfillment/release-notes.html)
* [AmazonSales Channelのリリースノート](https://experienceleague.adobe.com/docs/commerce-channels/amazon/release-notes.html)

>[!NOTE]
>
>[!DNL Adobe Search&Promote] サービス終了が次の日付でスケジュールされています： **2022 年 9 月 2 日**. 製品およびコマース検索の場合、 [ライブ検索](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/overview.html?lang=en) はAdobeの検索アプリケーションです。 詳しくは、 [提供終了のお知らせ](https://experienceleague.adobe.com/docs/search-promote/using/sp-eol.html?lang=en) を参照してください。

### 新しい Adobe Commerce のチュートリアルとドキュメント {#tutorials-commerce}

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年9月 | [Adobe Experience Manager でヘッドレスエクスペリエンスを提供](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=ja) | ビデオ | 機能強化された最新の Experience Manager コンテンツフラグメントおよびヘッドレスコンテンツ配信のための新しい GraphQL API を使用したヘッドレスエクスペリエンス管理について説明します。 |
| 2022年9月 | [Adobe Commerce Catalog Management ガイド](https://experienceleague.adobe.com/docs/commerce-admin/catalog/guide-overview.html) | ビデオ | 建物の基本的なコンテンツコンポーネントを含む、コンテンツとデザイン機能に関する詳細情報を取得します。 |
| 2022年9月 | [複数のコマースシステムの設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/administering/multiple-commerce-systems-setup.html) | ビデオ | 複数のコマース環境を使用したAEMのAdobe方法を説明します。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/target.png) [!DNL Adobe Target] {#target}

最終更新日： **2022 年 9 月 7 日**

* プレリリース情報については、[Adobe Target プレリリース](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ja)を参照
* 現在の情報については、[Adobe Target リリースノート](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=ja)を参照

## ![アイコン](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign は、オンラインおよびオフラインのマーケティングチャネルにわたって 1 対 1 のメッセージを届けるために直感的で自動化された方法を提供します。顧客の習慣や好みによって特定されたエクスペリエンスを利用して、顧客が欲しいものを予測できるようになりました。

### 最新の Campaign 製品リリース

最新の機能、改善点、修正点について詳しくは、[Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ja)、[Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=ja) および [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ja) リリースノートを参照してください。

### 新しい [!DNL Campaign] のチュートリアルとコース {#tutorials-campaign}

新しく公開された Adobe Campaign ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年9月 | [Adobe Campaign の SMS の設定](https://experienceleague.adobe.com/?recommended=Campaign-A-1-2022.classic.setupsms) | コース | Campaign インスタンスを SMTP プロバイダーに接続する方法と、設定を分析し、トラブルシューティングする方法について説明します。 | Campaign Classic v7 |
| 2022年9月 | [Adobe Campaign の SMS の設定](https://experienceleaguecommunities.adobe.com/t5/adobe-campaign-classic/course-discussion-set-up-sms-for-adobe-campaign/m-p/542687#M2301) | コース | Campaign インスタンスを SMTP プロバイダーに接続する方法と、設定を分析し、トラブルシューティングする方法について説明します。 | Campaign v8 |
| 2022年9月 | [SMPP プロトコルの詳細とトラブルシューティング](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/smpp-deep-dive-and-troubleshooting.html?lang=ja) | ビデオ | SMPP 接続が確立される方法、および SMPP が PDU を介してデータを交換する方法について説明します。 接続のトラブルシューティング方法を説明します。 | Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Campaign ヘルプリソース

* Adobe Campaign v8：[ドキュメント](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [実装ガイド](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ja)
* Adobe Campaign Standard：[Campaign Standard ドキュメント](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ja) - [リリース計画](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ja)
* Adobe Campaign Classic：[Campaign Classic v7 ドキュメント](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ja) - [最新のドキュメント更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ja)
* Adobe Campaign コントロールパネル：[ドキュメント](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=ja) - [ハウツービデオ](https://experienceleague.adobe.com/docs/control-panel-learn/tutorials/control-panel-overview.html?lang=en) のハウツービデオ

## ![アイコン](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

を使用 [!DNL Journey Optimizer]を使用すると、1 つのアプリケーションから数百万人の顧客に対して、スケジュールされたオムニチャネルキャンペーンと 1 対 1 の瞬間を管理でき、インテリジェントな判定とインサイトを使用してジャーニー全体を最適化できます。

### 最新の Journey Optimizer 製品リリース

最新の機能、改善点および修正点について詳しくは、[Journey Optimizer リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ja)を参照してください。

### 新しい Journey Optimizer のチュートリアルとコース {#tutorials-ajo}

新しく公開されたAdobe用ビデオ、チュートリアル、コース [!DNL Journey Optimizer].

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年9月 | [マーケター向けの決定管理の概要](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | ビデオ | Adobe Journey Optimizerの意思決定管理機能について説明します。 このコースは、顧客に最適なオファーを提供することで売上高、顧客体験、ロイヤルティを向上させたいマーケター向けに設計されています |
| 2022年9月 | [キャンペーンの作成](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-campaigns/create-a-campaign.html?lang=en) | ビデオ | アクションを直ちに実行するか、指定したスケジュールで実行して、特定のオーディエンスに 1 回限りのコンテンツを配信する方法を説明します。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] のその他のリソース

* [Journey Optimizer ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ja)
* [意思決定管理ドキュメント](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioning/get-started-decision/starting-offer-decisioning.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=ja) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=ja)

## ![アイコン](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Experience Platform を使用すると、各個人のニーズをリアルタイムでインテリジェントに予測することで、様々なエクスペリエンスチャネルにわたる大規模なカスタマージャーニーを調整できます。

### 最新の [!DNL Journey Orchestration] 製品リリース

最新の機能、改善点、修正点について詳しくは、[[!DNL Journey Orchestration] リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ja)を参照してください。

#### [!DNL Journey Orchestration] のその他のリソース

* [Journey Orchestration ドキュメント](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja) - [リリースノート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [ハウツービデオ](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ja) - [最新のドキュメントアップデート](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ja)

## ![アイコン](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] は、複雑な購入ジャーニーのすべてのステージにわたるエンゲージメントを通じてカスタマーエクスペリエンスを変革しようとしている経営陣や B2B マーケター向けの完全なアプリケーションです。

### コア Marketo Engage の更新

最新のリリーススケジュール情報とリリースノートについては、[!DNL Marketo Engage] [リリーススケジュール](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ja)を参照してください。

### 新しい Marketo チュートリアルとコース {#tutorials-marketo}

新しく公開された Adobe Marketo ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年8月 | [Marketo Engage チュートリアル](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) | ビデオ | Marketo Engage の過去および最新のチュートリアルについて、Experience League の [Marketo Engage チュートリアルホーム](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en)を参照してください。 |

{style=&quot;table-layout:auto&quot;}

最新の製品ドキュメントについて詳しくは、[Marketo 製品ドキュメント](https://experienceleague.adobe.com/docs/marketo/using/home.html?lang=en)ホームを参照してください。

## ![アイコン](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] は、アイデアの共有、コンテンツの作成、複雑なプロセスの管理、および最高の作業を行うための統合作業管理アプリケーションです。

### 新しい Adobe Workfront コースとチュートリアル {#tutorials-workfront}

新しいWorkfrontコースとExperience Leagueに関するチュートリアルのコレクション。

**注意：** すべてのWorkfrontチュートリアルと製品ドキュメントのExperience Leagueに関する翻訳は、近日中に提供されます。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年9月 | [Workfrontコース](https://experienceleague.adobe.com/?recommended=Workfront-A-1-2022.1.admin&amp;lang=ja) | コース | Experience League版Workfrontで利用可能な新しいコースを参照します。 |
| 2022年9月 | [ベストプラクティス](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/best-practices/agile-bp.html?lang=en) | 記事 | 内部および外部の両方からのベストプラクティスを学ぶ [!DNL Workfront] 使用方法に関する専門家 [!DNL Workfront] 作業プロセスを強化するツール |
| 2022年9月 | [ボード](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/boards/add-and-edit-column-settings-on-a-board.html?lang=en) | ビデオ | 新しいボードツールを現在の機能で使用する方法を示す新しいチュートリアルをご覧ください。 |
| 2022年9月 | [アジャイル：スクラム](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/scrum/create-a-scrum-agile-team.html?lang=en) | ビデオ | アジャイルチームを作成し、スクラム手法を選択し、スクラムチームの設定を決定する方法を説明します。 次のチュートリアルを移行した視聴 [!DNL Workfront One] スクラムアジャイルの手法を [!DNL Workfront]. |
| 2022年9月 | [アジャイル：かんばん](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/kanban/create-a-kanban-team.html?lang=en) | ビデオ | 次のチュートリアルを移行した視聴 [!DNL Workfront One] 以下の中でかんばんアジャイル手法を行う方法を示す [!DNL Workfront] |
| 2022年9月 | [個人のタイムオフカレンダー](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-resources/personal-time-off-calendar/how-time-off-affects-project-timelines.html?lang=en) | 記事 | 個人のタイムオフが重要な理由と、それをWorkfront内でリソース管理に簡単に追加する方法を示すチュートリアルを表示します。 |
| 2022年9月 | [Workfront Fusion トレーニング](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/welcome-to-workfront-fusion/workfront-fusion-overview.html?lang=en) | ビデオ | 各Workfront Fusion セクションには、次のチュートリアルに進む前に理解しておく必要のある概念を示す、複数のチュートリアルが含まれています。 チュートリアルの演習を使用すると、ほとんどの概念を習得できます。 |

{style=&quot;table-layout:auto&quot;}

すべての製品の最新情報の総まとめについては、[[!DNL Workfront] 製品リリース](https://experienceleague.adobe.com/docs/workfront/using/product-announcements/product-releases/product-releases.html?lang=ja)ページを参照してください。

## ![アイコン](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

リリースノート：[!DNL Adobe Advertising Cloud]

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [ [!DNL Advertising Cloud DSP] の新機能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] の新機能](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **August 9, 2022**

| Feature | Description |
| ------- | ----------- |
| Integration with [!DNL Adobe Analytics] | (August 6 release) Improvements to the data feed that Advertising Cloud sends to [!DNL Analytics] result in fewer mismatches between click/cost/impression data from the search engines and related conversion data in [!DNL Analytics]. |

{style="table-layout:auto"}
  
-->

### [!DNL Advertising Cloud DSP] の新機能 {#adcloud-dsp}

最終更新日： **2022 年 9 月 13 日**

| 機能 | 説明 |
| ------- | ----------- |
| [!UICONTROL パッケージと配置のペーシング] | （9 月 12 日リリース）フライトぺーシングと日中ペーシングに別々のぺーシング制御を利用できるようになりました。 以前は、1 つの戦略で両方が制御されていました。 既存のパッケージおよび配置の設定は、次のようにマッピングされました。<ul><li>レガシー **[!UICONTROL ペーシングフィル戦略]**=*[!UICONTROL 偶数]*  — 現在は次のように設定されています： **[!UICONTROL フライトぺーシング]**=*[!UICONTROL 偶数]* および **[!UICONTROL 日中ペーシング]**=*[!UICONTROL 偶数]*</li><li>レガシー **[!UICONTROL ペーシングフィル戦略]**=*[!UICONTROL 少し前に]*  — 現在は次のように設定されています： **[!UICONTROL フライトぺーシング]**=*[!UICONTROL 少し前に]* および **[!UICONTROL 日中ペーシング]**=*[!UICONTROL 偶数]*</li><li>レガシー **[!UICONTROL ペーシングフィル戦略]**=*[!UICONTROL Frontload]*  — 現在は次のように設定されています： **[!UICONTROL フライトぺーシング]**=*[!UICONTROL Frontload]* および **[!UICONTROL 日中ペーシング]**=*[!UICONTROL ASAP]*</li><li>レガシー **[!UICONTROL ペーシングフィル戦略]**=*[!UICONTROL 積極的な最前面負荷]*  — 現在は次のように設定されています： **[!UICONTROL フライトぺーシング]**=*[!UICONTROL 積極的な最前面負荷]* および **[!UICONTROL 日中ペーシング]**=*[!UICONTROL ASAP]*</li></ul> |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] の新機能 {#adcloud-search}

最終更新日： **2022 年 9 月 10 日** 9 月 10 日リリース向け

| 機能 | 説明 |
| ------- | ----------- |
| [!UICONTROL キャンペーン] | ([!DNL Google Ads] アカウントベータ版機能 ) を作成および管理できるようになりました。 [!DNL Google Ads] パフォーマンス最大キャンペーン：を使用して、複数のチャネルにわたる広告のコンバージョンを表示し、最適化します。 [!DNL Google Ads] スマート入札、使用 [!UICONTROL キャンペーンタイプ] &quot;[!UICONTROL 最大パフォーマンス].&quot; |
|  | ([!DNL Google Ads] アカウント ) Campaigns /広告ビューに、オプションの [!UICONTROL 広告の強さ] 列。各レスポンシブ検索広告 (RSA) がどの程度従うかを示します。 [!DNL Google Ads] パフォーマンスのベストプラクティス。<br><br>[!DNL Microsoft® Advertising] では、まだ API を介して同様のサポートを有効にしていません。 |
|  | ([!DNL Microsoft® Advertising] アカウント ) の同期、読み取り専用、およびレポート（ビュースルーデータを含む）のサポートが、 [!DNL Microsoft® Audience Network]を含む [!DNL Microsoft®] オーディエンス広告。 |
| [!UICONTROL キャンペーン], [!UICONTROL レポート] | パブリッシャーのインプレッション共有指標の数が増えると、次の週に、キャンペーン管理のビューとレポートの列として使用できるようになります。 |
| [!UICONTROL コンバージョン値のルール] | ([!DNL Google Ads accounts];ベータ版機能を使用 ) 既存のコンバージョン値ルールを [!UICONTROL 最適化] > [!UICONTROL コンバージョン値のルール]. 次を持つ広告主 [!DNL Google Ads] 個々のアカウントレベル以下でのコンバージョントラッキングでも、ルールの作成と管理が可能です。<br><br>コンバージョン値ルールの自動最適化は、今後のリリースで利用できるようになります。 |
| [!UICONTROL ポートフォリオ] | ( オプトインベータ版機能。 [!DNL Google Ads] アカウント ) [!DNL YouTube] キャンペーン [!UICONTROL コンバージョンを最大化] ハイブリッドポートフォリオの入札戦略が、カスタムシミュレーションの結果に含まれるようになりました。 ハイブリッドポートフォリオには、次のみを含める必要があります [!DNL YouTube] キャンペーン。<br><br>ベータ版プログラムに参加するには、アカウントチームにお問い合わせください。 |
| [!UICONTROL 広告インサイト] | この [!UICONTROL 広告インサイト] パフォーマンスと信頼性を向上させる新しいインフラストラクチャに基づいて、ビューは新しい外観とワークフローを備えています。 インサイト名をクリックし、設定を選択または入力して、「 [!UICONTROL Insight を生成].<br><br>一時的にレガシービューに戻るには、を有効にします。 [!UICONTROL 古い UI に切り替え] を右上に表示します。 従来のビューは 9 月末に削除されます。 |
|  | この [!UICONTROL クエリクロスマッチングベータ] 分析が利用できるようになりました。 |
| [!UICONTROL レポート ] | ([!DNL Google Ads] アカウントのみ ) 新しい専門レポート [!UICONTROL RSA Assets レポート] 各アセット ([!UICONTROL クリエイティブタイトル] または [!UICONTROL 説明]) 1 つ以上のポートフォリオ内のレスポンシブ検索広告 (RSA)、または 1 つ以上のアカウント、キャンペーン、広告グループ用。 デフォルトでは、レポート期間中にアセットが無効（削除）になった場合でも、指定したデータ範囲で少なくとも 1 つのインプレッションを受け取ったアセットごとに 1 つの行がデータに含まれます。 **注意：** 「[!UICONTROL パフォーマンスデータのない行を含める]「 」というエラーが発生した場合でも、データを受信したことのないアセットのデータは含まれません。 |
|  | レスポンシブ検索広告 (RSA) の追加サポートは、 [!UICONTROL 広告バリエーションレポート]:<ul><ul>([!DNL Google Ads] アカウントのみ ) [!UICONTROL 列] 設定、新しい[!UICONTROL 広告の強さ]「 」列は、RSA がどの程度従うかを示します。 [!DNL Google Ads] パフォーマンスのベストプラクティス。 同じ列を [!UICONTROL キャンペーン] > [!UICONTROL 広告] 表示 [!DNL Microsoft® Advertising] では、まだ API を介して同様のサポートを有効にしていません。</li><li>内 [!UICONTROL 列] 設定を使用すると、レポート結果を [!UICONTROL クリエイティブタイトル] および [!UICONTROL 説明].</li><li>内 [!UICONTROL 詳細フィルター] 設定では、 [!UICONTROL 広告テキスト] 両方に適用されるフィールド [!UICONTROL クリエイティブタイトル] および [!UICONTROL 説明].</li></ul> |
| [!UICONTROL 推奨事項] | ([!DNL Google Ads] アカウントベータ版機能 ) 内 [!UICONTROL インサイトとレポート] > [!UICONTROL Recommendations Beta]を使用すると、次のことができます。<ul><li>以前に処理されていないレコメンデーションを一目で確認する [!DNL Google Ads] アカウント</li><li>アカウントのレコメンデーションを適用および却下します。</li><li>アカウントに適用された各レコメンデーションのログを表示します。</li></ul> |
| [!UICONTROL キャンペーンのインポート] | （ベータ版機能） [!DNL Google Display Network] 広告画像を含むキャンペーンを [!DNL Microsoft® Advertising] オーディエンスキャンペーン [!DNL Microsoft® Audience Network] から [!UICONTROL ツール] > [!UICONTROL キャンペーンのインポート]. キャンペーンをインポートすると、インポートジョブのステータスの確認、エラーログの確認、インポートスケジュールの編集、一時停止、削除ができます。 |

{style=&quot;table-layout:auto&quot;}

## ![アイコン](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Adobe Document Cloud向けに公開された新しいチュートリアルとコース（以下を含む） [!DNL Document Services] および [!DNL Acrobat Sign].

| 公開日 | 名前 | タイプ | 説明 | アプリケーション |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022年9月 | [デベロッパーアカウントへの新規登録](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/sign-up-developer-account.html?lang=en) | ビデオ | パート 1 の _Acrobat Sign Embed クイックスタートガイド_ Acrobat Sign API 開発者アカウントへの新規登録方法について説明します。 新しい開発者アカウントは、Sign と API の機能を完全に有効にします。 | ドキュメントサービス |
| 2022年9月 | [アプリケーションの作成](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-your-application.html?lang=en) | ビデオ | のパート 2 _Acrobat Sign Embed クイックスタートガイド_ Acrobat Sign API を使用してアプリケーションを作成する方法を説明します。 | ドキュメントサービス |
| 2022年9月 | [埋め込みリンクの作成](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-an-embed-link.html?lang=en) | ビデオ | パート 3 の _Acrobat Sign Embed クイックスタートガイド_&#x200B;では、OAuth 用の埋め込みリンクを作成する方法を説明します。 アプリケーションは、この OAuth メソッドを使用するユーザーに対する権限を取得します。 | ドキュメントサービス |
| 2022年9月 | [アクセストークンの生成](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/generating-an-access-token.html?lang=en) | ビデオ | パート 4 の _Acrobat Sign Embed クイックスタートガイド_&#x200B;では、Acrobat Sign API で使用できるアクセストークンの生成方法について説明します。 | ドキュメントサービス |
| 2022年9月 | [一時的なドキュメントの作成](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-a-transient-document.html?lang=en) | ビデオ | パート 5 の _Acrobat Sign Embed クイックスタートガイド_&#x200B;を参照し、一時的なドキュメントを作成する方法を説明します。 | ドキュメントサービス |
| 2022年9月 | [レイアウトを自動調整](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/auto-adjust-layout.html?lang=en) | ビデオ | コンテンツをリフローし、PDF内のページ間でレイアウトを自動調整する新しい編集モードについて説明します。 | Acrobat |
| 2022年9月 | [カスタムページを追加](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/add-custom-page.html) | ビデオ | 統合Adobe Expressアプリを使用して、何千ものテンプレートから選択できるPDFにカスタムページを追加する方法を説明します。 | Acrobat |
| 2022年9月 | [既存の Web フォームの変更](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/modify-webform.html?lang=en) | ビデオ | 既存の Web フォームを無効にする、編集する、および再度有効にする方法を説明します。 | Acrobat Sign |
| 2022年9月 | [レポートの作成](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/creating-a-report.html?lang=en) | ビデオ | 独自のレポートを作成して、ドキュメント署名プロセスを可視化する方法、または個々のグループやユーザーの行動を確認する方法について説明します。 | Acrobat Sign |
| 2022年9月 | [レポートのグラフの作成](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-a-report.html?lang=en) | ビデオ（更新） | 新しいレポート機能を使用して、パーソナライズされたビューで独自のカスタムレポートおよびデータエクスポートを作成、保存、管理する方法について説明します。 | Acrobat Sign |
| 2022年9月 | [カスタムワークフローの作成](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/building-a-custom-workflow.html?lang=en) | ビデオ（更新） | 電子署名を取得し、フォームデータを収集し、重要なドキュメントの配信を確認して、ワークフロー管理を合理化するためのドキュメントワークフローの調整および自動化方法を説明します。 | Acrobat Sign |
| 2022年9月 | [署名用に送信するMicrosoft Teams](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/adobe-sign-teams-mortgage.html?lang=en) | ビデオ（更新） | 署名の契約を送信する方法、契約のステータスを確認する方法、およびMicrosoft Teams内からすべてのリマインダーを送信する方法について説明します。 | Acrobat Sign |
| 2022年9月 | [ドキュメントへのフィールドの追加](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/adding-fields.html?lang=en) | ビデオ（更新） | ドキュメントにフィールドを自動的に配置する方法、またはAcrobat Sign内のドラッグ&amp;ドロップオーサリング環境を使用する方法について説明します。 | Acrobat Sign |
| 2022年9月 | [送信オプションを設定](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/sending-options.html?lang=en) | ビデオ（更新） | ドキュメントを署名用に送信する際に、様々なオプションを設定する方法を説明します。 | Acrobat Sign |

{style=&quot;table-layout:auto&quot;}

Document Cloud ヘルプについては、以下を参照してください。

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ja)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ja)
* [Document Cloud 学習とサポート](https://helpx.adobe.com/jp/support/document-cloud.html)

## ![アイコン](/assets/creative-cloud-24.png) Adobe Creative Cloud エンタープライズ版 {#creative-cloud}

新しく公開された Adobe Campaign ビデオ、チュートリアル、コース。

| 公開日 | 名前 | タイプ | 説明 |
| -----------| ---------- | ---------- | ---------- |
| 2022年9月 | [Adobe Fontsでフォント不安を調整 ](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/assets/TamingTypeAnxiety.pdf?lang=en) | PDF | Adobe Fontsの動作の仕組みについては、実践チュートリアルを参照してください。 |
| 2022年9月 | [Adobe Acrobat for Content Creators](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/assets/AcrobatforContentCreators.pdf?lang=en) | PDF | コンテンツ作成者は、おそらくPDFを生成し、Adobe AcrobatでそれらのPDFファイルを定期的に表示します。 ただし、Acrobatには、一般的なクリエイティブワークフローを効率化するのに役立つ多くのツールも含まれています。 次の 2 つの特定のツールについて説明します。 [!UICONTROL 他のユーザーとの共有] および [!UICONTROL 保護]. |

{style=&quot;table-layout:auto&quot;}

最新のチュートリアルについては、[Creative Cloud エンタープライズ版チュートリアル](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) を参照してください。

## ![アイコン](/assets/experience-league.png) Customer Data Management - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=ja) は、顧客データ管理の技術およびマーケティングプラクティスのリーダーやスペシャリストのためのページです。このチュートリアルのコレクションには、同僚から話を聞き、インスピレーションを得て、MarTech の開発について学ぶためのリソースが一箇所に集められています。登録は不要です。クリックで視聴できます。

## ![アイコン](/assets/experience-league.png) デジタルエクスペリエンスブループリント {#blueprints}

[デジタルエクスペリエンスブループリント](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=ja)は、戦略に取り組み、確立されたビジネス上の問題を解決するための反復可能な実装です。各ブループリントは、価値の高いビジネス上の問題、アーキテクチャ、実装手順、技術的な考慮事項、および関連ドキュメントへのリンクを説明する一連の成果物を提供します。

[トップ](#events)

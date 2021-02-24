---
title: "Laws_Governing_Identity_Systems"
tags: ""
---

消費者のためのプライバシーとコンプライアンス入門
====================================================

クレア・ネルソン

2020 IDPro, クレア・ネルソン

_**免責事項**_

この記事は、法律上のアドバイスと考えるべきではありません。基本的人権としてのデータ保護とプライバシーをサポートするアイデンティティ・プログラムは、複雑で高度な技術的なものである。世界各国のデータ保護およびプライバシーに関する法律の多くは進化しており、解釈の余地があります。お客様の法域に適した具体的なアドバイスについては、お客様の組織の顧問弁護士にご相談ください。

IDPro知識体系の関連セクション
===============================================

IDPro Body of Knowledge_ [1](#fn1)の他のセクションを参照してください。

* セクション4.3.1.2 GDPRのIAMへの影響
    
* 4.5.8項 「用語」を参照してください。
    
* セクション4.5.8.3 セキュリティとプライバシー - アイデンティティ管理のためのフレームワーク - パート1：用語と概念
    

消費者のためのプライバシーとコンプライアンス入門
====================================================

エンタープライズ・ソリューション・アーキテクト、マーケティングに携わるデータ・サイエンティスト、プライバシーの専門家、プロダクト・マネージャー、データ・ブローカーのストラテジストなど、アイデンティティの専門家には、消費者向けアプリケーションのプライバシーとデータ保護規制や法律へのコンプライアンスを改善する絶好の機会があります。いくつかの重要な問題が改善の必要性を後押ししています。

1. 消費者のような自然人を一意に識別することは、これまで以上に容易になっている。デジタル排気、身体的行動、または属性のわずかな断片を収集し、機械学習を介して相関付けを行い、分析することで、十分な確率で固有の消費者または世帯を識別することができます。
    
2.  同意が破られる。プライバシー通知の複雑さと、ほとんど読まれないプライバシーポリシーの長さは、効果がない、選択の錯覚、消費者への負担、そして制限がないかもしれない、あるいは制限された、あるいは曖昧な通知だけで将来いつでも変更される可能性のある広範な条件に最終的に同意するというパターンにつながっています。プライバシーと法律の専門家であるダニエル・ソロヴェは、「個人にプライバシーを管理するためのタスクを増やしても、効果的なプライバシー保護にはならない」と述べています。2](#fn2) プライバシー法は、データの管理責任を消費者ではなく、データ管理者および/またはデータ処理者の責任にすべきであるという認識が高まっています。
    
3. データプライバシー法は技術革新から数年遅れており、そのギャップは拡大している。個人情報保護法は技術の進歩に追いつくことができず、あらゆるタッチポイントで個人データを収集する4,000社のデータブローカーや分析会社に追いつくのに何年も遅れています。多くのマーケティング企業や世界最大級の組織が、現行のプライバシー法の狭義のガイドラインの中で消費者を識別し続けるために、サードパーティ製のクッキーに代わるものを求めています。

4.  匿名性は存在せず、仮名化は保護が弱い
    
    1.  例えば、ジオロケーションだけに基づいて匿名性が存在しないことを研究者が証明している。3](#fn3)
        
    2.  同様に、研究者は、人を再識別することが容易になってきていると主張している。
        
        1. 一度公開されたデータは取り返すことができない。時間が経つにつれ、データ分析技術が向上し、元のデータに関する情報を明らかにできる追加のデータセットが公開されるようになる。公開されたデータは、証明可能なプライバシー特性を持つ方法がデータ公開に使用されていない限り、再識別に対してますます脆弱になるだろう。4](#fn4)
            
    3.  _Communications of the ACM_は最近、匿名性に関する論文を発表し、多くの数学者が常に知っていたことを確認しました、匿名データにはまだパターンがあり、それを脱匿名化する方法があります。5](#fn5)
        
        1.  "匿名化されたデータを完全に匿名化することは決してできない: 匿名化は、欧州の一般データ保護規則やカリフォルニア州の消費者プライバシー法などの法律との抵触を避けるために、民間企業にとっては十分ではない。" 6](#fn6)        

GDPRが「自然人」と呼ぶもののプライバシーの範囲は拡大し続けています。なぜならば、オンラインやオフラインでの行動のほんのわずかなデジタルの排気や痕跡で人間を一意に識別できる能力が拡大し続けているからです。ランチを食べた場所、カーソルを見つけるためのマウスの動かし方、「この通話は品質向上のために録音されることがあります」という警告を受けて電話でサービス担当者に話した内容、オンラインで購入したもの、デバイスとそれに関連するすべての属性、あるいはガスを購入した場所などが、自然人を特定するのに十分かもしれません。名前、住所、社会保障番号、生年月日だけが唯一の識別材料であった時代はもう終わりました。これからは、消費者にプライバシーを提供するために、大量の個人情報や関連データを保護する必要があります。

用語と略語
------------------------

* 同意 - 何かが起こることへの許可、または何かをすることへの同意。
    
* GDPR - 一般データ保護規則[7](#fn7)
    
* CCPA - カリフォルニア州消費者プライバシー法 [8](#fn8)
    
* 自然人 - 個々の人間
    
* NY SHIELD Act - New York "Stop Hacks and Improve Electronic Data Security" Act [9](#fn9)
    
* プライバシー - 抽象的な概念であり、単一の共通の定義はありません。

範囲
=====

消費者のプライバシーとコンプライアンスに関するこのセクションの高尚な目標は、グローバルな視点を提示することです。しかし、このセクションの初期リリースでは、GDPR、CCPA、およびNY SHIELD法に焦点を当て、中国やその他の国を軽く取り上げています。以下の「リソース」のセクションで述べたように、国際プライバシー専門家協会（IAPP）は、即時に最新の包括的な世界的なカバレージを提供するための優れた情報源です。

この IDPro 知識体系の第 4 章「_法律、規制、および基準」では、データ保護とプライバシーの規制が世界中でどのように増加しているかを説明しています。3月21日にNY SHIELD法が施行され、中国ではプライバシー法の更新に取り組んでいます。ほとんどの方がGDPRやCCPAをご存知だと思います。[10](#fn10) 下の図は、世界の規制と施行を「重い」「堅牢」「中程度」「限定的」のいずれかにハイライトしています。

! [地理的・政治的マップでは、各国のプライバシー規制と施行の範囲を、重い、堅牢、中程度、限定的に色分けしています。アメリカ、カナダ、中国、オーストラリア、ヨーロッパのほとんどの国が「重い」、ロシア、トルコ、エジプト、メキシコ、ブラジルなどが「中程度」となっています。画像1.png

図1 - 世界のプライバシー規制は重いものから限定的なものまで様々 [11](#fn11)

グローバルな範囲に加えて、本セクションでは、オンラインサービスやアプリを含むデジタルアイデンティティだけでなく、物理的なインタラクション（例：顧客が店舗やサービス施設に入ること）も対象としています。

このセクションでは、クッキー、電子通信（インターネット、電子メール、メッセージング、アプリ）、Wi-Fi、電話、Internet-of-Things（IoT）など、さまざまなメカニズムを介して取得、保存、追跡される個人データを考慮します。これらのデータはすべて、個人を特定するために使用される可能性があり、基本的人権として保護を必要とする個人情報とみなされる可能性があります。GDPRの第一項では、[欧州連合基本権憲章](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:12012P/TXT)および[欧州連合機能条約(TEFU)](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A12012E%2FTXT)によれば、データ保護は基本的人権であるとしている。12](#fn12) , [13](#fn13) 国連は1948年に[世界人権宣言](https://www.un.org/en/universal-declaration-human-rights/)を採択したが、これは第17条に明記されたプライバシーに関する世界的な義務である： [14](#fn14)

> 何人も、自己のプライバシー、家族、家庭、通信手段に対する恣意的な干渉を受けたり、自己の名誉及び名誉に対する攻撃を受けたりしてはならない。すべての人は、このような干渉や攻撃に対して法の保護を受ける権利を有しています。

EUのGDPR

EU eプライバシー指令

US CCPA, NY **SHIELD** , その他

カリフォルニア州、オレゴン州 IoTセキュリティ法、シンガポール、他

世界の残りの部分

何が含まれているか？

個人情報、クッキーの同意

クッキー、インターネット、電子メール、メッセージング、電話、トラッキングメカニズム、守秘義務の権利

個人データ、CCPAの家計データ

IP アドレスまたは Bluetooth アドレスを持つ、接続されたデバイス。

China - none; APEC - Personal Information

表1. GDPRを超えて。個人データにはクッキー、電話、IoTが含まれる

\*アジア太平洋経済協力(APEC)プライバシーフレームワーク](https://www.apec.org/Press/Features/2006/0101_APEC_Privacy_Framework_Facilitating_Business_and_Protecting_Consumers_Across_the_Asia-Pacific)によれば、個人情報とは、個人を特定できる情報をいいます。15](#fn15)

GDPRはePrivacy指令と密接に関係しています。ePrivacy指令は間もなくePrivacy Regulationに置き換えられます。GDPRとePrivacy RegulationはともにEUにおけるデータ保護改革の一部であり、重複する部分がある場合には、特にクッキーと電子通信に関しては、ePrivacy RegulationがGDPRより優先される。16](#fn16)

IoT法は以下で取り上げます。新興の法律は、まず、埋め込まれたパスワードやハードコードされたパスワードを排除しようとしていることに注意してください。IoTデバイスが製造元からすでにインストールされているパスワードで出荷されている場合、プライバシーを侵害するだけでなく、ボットネット・マルウェアを作成することも容易になります。

舞台設定
=================

Hartzog、Zuboff、Schneier、Malerなどの学者やプライバシーの専門家が、これらのトピックとその先を検討するための舞台を用意しています。

ハルツオック
-------

Woodrow Hartzogは、ノースイースタン大学の法とコンピュータサイエンスの教授であり、他の役割の中では、スタンフォード・ロースクールのインターネットと社会のための客員研究員でもあります。2019年4月、Hartzogはニール・リチャーズと共著で[__The Pathologies of Digital Consent__](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3370433)を執筆しており、ここでは同意モデルが被ることができる欠陥について議論しています。17](#fn17)

* 知らず知らずのうちに同意している
    
* 強制的な同意
    
* 無能力者の同意
    

これらの同意の欠陥は、知っていて自発的な同意の_黄金の標準から遠く離れています。HartzogとRichardsは結論づけている。

デジタルの文脈での同意の過剰な使用と、同意の十分性に関する限られた法的な取り締まりとの組み合わせは、個人データを基にして大金を生み出すことを可能にしてきたが、それはまた、消費者をデータ侵害、個人情報の盗難、そして人類史上前例のない監視経済にさらしてきた。

より根本的には、同意の病理を悪用して同意を製造することで、より良い未来に向けての鍵となるデジタル環境への信頼を低下させているのです。私たちはより良いものを作ることができますが、そのためには、同意の病理を認識し、同意が最も正当化される文脈に限定する必要があります。今後は、持続可能で倫理的で進歩的な方法で情報経済の恩恵を受けようとするならば、情報経済のリスクと害を最小限に抑えるために、作り話的、製造的、または強制的な同意以外の戦略に頼らなければなりません。

これらの同意の問題については、病的な同意モデルに過度に依存することが増えていることに代わる解決策として提案されている「消費者信頼の理論」を含めて、後続のセクションでさらに議論されます。

ズボフ
------

彼女の最近の受賞歴のある本『_監視資本主義の時代。ハーバード大学のショシャナ・ズボフは、我々が_監視資本主義の状態に住んでいるという彼女のよく研究された主張を明確に明確に説明しています。

"監視資本主義は一方的に人間の経験を行動データへの翻訳のための自由な原料として主張している。

* これらのデータの一部はサービス改善に応用されるが、残りは独自の行動的余剰物として宣言され、「マシン・インテリジェンス」として知られる高度な製造プロセスに投入され、あなたが今、すぐ、そして後で何をするかを予測する予測製品に加工される。
    
* 最後に、これらの予測商品は、私が行動先物市場と呼んでいる新種の市場で取引される。
    
* 監視資本家はこれらの取引から莫大な富を得ている。多くの企業が我々の将来の行動に賭けをしているからだ。[18](#fn18)
    

シュナイア
--------

監視資本主義に関するズボフの2019年の本は、ブルース・シュナイアーの2015年の本、_データとゴリアテを作ります。あなたのデータを収集し、あなたの世界を制御するための隠された戦い、_比較して淡い。シュナイアはどこまで監視と行動剰余金の収集が進んだかについてのゾッとするような詳細を提供していないので、消費者は、 "なぜそれがそんなに悪いことを私に言わなかったのか？"と疑問に思ったままになっています。ズボフの言葉は、「データ保護」の大手ベンダーのマーケティング・メッセージにさえ反映されている。"プライバシーとは、個人が招かれざる監視から自由になる権利のことである。" [19](#fn19)

マラー
-----

2018年の Identiverse の講演「_Don't Pave Privacy Cow Paths: Retool Consent_(https://www.youtube.com/watch?v=eP5U2sA6EFk) for the New Mobility」では、ForgeRock の CTO、当時イノベーションおよび新興技術担当副社長であった Eve Maler 氏が、「モバイルデバイスやアプリケーションはおろか、電子メール、ラップトップ、ブラウザの要件にもコンセントが対応できない」理由を説明しています。

* コネクテッド・ビークルが消費者の生活の一部となり、あらゆる産業にとって重要な統合ポイントとなっていく中で、状況はどれほど悪化していくのでしょうか？Malerは、"信頼に対する消費者の要求、プライバシーに対する規制上の要求、同意体験と同意管理がどのように適応しなければならないか、そしてこれらの課題にどのようにして対応し始めることができるかを検討するための重要なシナリオとして、ニューモビリティを確立している "としています。20](#fn20)
    

GDPR準拠のための同意の実装を急ぐ中で、多くの企業が牛の道を敷いてしまったため、Maler氏の言葉は予知に満ちたものでした。彼女の講演では、非同期性、自動化、抽象化に対する今日のアーキテクチャ要件に対応するために、同意をリファクタリングする方法について説明しています。

プライバシーとは？
================

プライバシーは抽象的な概念であり、定義は無数にあります。

基本的人権としてのプライバシー
------------------------------------

個人データの保護とは、多くの場合、自分のデータに対する自律性と制御を意味します。この自律性と制御のレベルは、文脈によって異なります。一般的に、プライバシーの定義は国によって、あるいは州によって異なります。米国は、世界人権宣言の採択に投票した国連48カ国のうちの1カ国であるにもかかわらず、米国は、基本的人権としてのプライバシーをEUと同じように受け入れているわけではありません。

* EUでは、人間の尊厳が絶対的な基本的権利として認められている。
    
* この尊厳の概念では、プライバシー、つまり私生活を送る権利が重要な役割を果たしています。プライバシーは個人の権利であると同時に、社会的価値でもある。
    
* 世界人権宣言（第12条）、欧州人権条約（第8条）、欧州基本権憲章（第7条）には、プライバシーや私生活の権利が謳われています。21](#fn21)
    

**ウェスティン**. 1960年代には、プライバシーのパイオニアであるアラン・ウェスティンは、プライバシーを「個人、グループ、または機関が、自分に関する情報がいつ、どのように、どの程度他人に伝達されるかを自分自身で決定することを主張すること」と定義しています。[22](#fn22)

**1989年、米国最高裁判所は、「プライバシーのコモンローと文字通りの理解の両方が、個人が自分の個人に関する情報をコントロールすることを包含している」と書いた。23](#fn23)

**中国** . 中華人民共和国（PRC）では、複雑な法律が個人データとプライバシーを管理しており、将来的には包括的な規制に取って代わられることになっています。この傾向は、「個人が民間部門で重要なデータ保護の権利を獲得しているが、国家政府によって行われたプライバシーの侵害に対する救済措置を請求できない」ことを示しています。24](#fn24) 今日では、金融サービス、電子商取引、電気通信、インターネットサービス、コンテンツプロバイダー、ヘルスケアなど、セクターに応じて様々な法律が適用されています。

**アジア太平洋経済協力（APEC）** . アジア太平洋経済協力(APEC)プライバシーフレームワーク_](https://www.apec.org/Publications/2005/12/APEC-Privacy-Framework) は、ダウンロード可能です。APECプライバシーフレームワークは、経済の内外でプライバシーを保護し、消費者、企業、政府に利益をもたらす個人情報の地域間移動を可能にします。このフレームワークは、APEC 国境を越えたプライバシー規則（CBPR）制度の基礎として使用されている。フレームワークの対象国と参加国には、以下の地図の国が含まれています。

APEC越境個人情報保護規則制度に参加する国を示す地政学地図](image2.png)

図 2 - APEC 国境を越えたプライバシールール（CBPR）制度の枠組み国と参加者の地図 [25](#fn25)

プライバシーモデル
--------------

イェール大学ロースクール、ポール・ツァイ中国センター上級研究員のサーム・サックス氏によると、プライバシーの基本的なモデルは2つあるという。1）中国、2）GDPRである。彼女は、ベトナム、ケニア、インドは中国のモデルとより密接に一致していることを示しています。中国のプライバシー法はGDPRの影響を受けているとはいえ、細部（例えば、中国は暗黙の同意を支持しているのに対し、GDPRは明示的な同意を要求している）と精神（一般的には国家の権利が個人の権利に優先する）の両方で著しく異なっている。中国におけるプライバシーの二分法は、政府による監視が強化される中で、仁仁や他の中国のFacebookのようなテクノロジー企業からの消費者保護が強化されていることからも証明されています。

プライバシー法を超えて、組織はさまざまな方法で消費者のプライバシーにアプローチしている。ID 専門家の役割は、まず、プライバシー、セキュリティ、およびリスクに関する組織の姿勢を理解することである。

プライバシー分類法
----------------

プライバシー法に関する世界的な専門家の一人に、ジョージ・ワシントン大学ロースクールのジョン・マーシャル・ハーラン研究教授であるダニエル・ソロヴ氏がいる。下記のSoloveの[privacy taxonomy](https://www.law.upenn.edu/journals/lawreview/articles/volume154/issue3/Solove154U.Pa.L.Rev.477(2006).pdf)に描かれているように、プライバシーには主に2つの当事者がいます。

* データ主体、または消費者
    
* データ保持者、またはデータ処理者とコントローラ
    

プライバシーの分類法における4つの主要なプロセスは、以下のように構成されています。

* 情報収集
    
* 情報処理
    
* 情報発信
    
* 侵略
    

4つのプロセスは、情報収集に始まり、侵入に終わるという順番で見ることができます。データ対象者に関するデータの情報収集は、GDPRの用語で言えば、データ所有者、またはデータ処理者とコントローラによって行われます。データ対象者または個人に関するデータの収集は、他の個人、企業、政府、または外部組織によって、監視や尋問を介して行われることがあります。情報処理には、データの保存と、さらに価値を引き出すためにソフトウェアアルゴリズムのようなものを適用するために行われる追加的なステップが含まれます。不安とは、セキュリティの欠如を意味します。情報の普及には、機密保持違反、開示、暴露、脅迫、歪曲などの望ましくない行為のリストの一部である場合に、結果として起こりうる多くの有害なものが含まれる。侵入には侵入と意思決定干渉が含まれ、Soloveは「データ対象者の私事に関する意思決定への政府の侵入」と説明している。[27](#fn27)

ダニエル・ソロヴ氏が説明したプライバシー分類法のグラフィックで、侵入からデータ対象者、情報収集と情報処理（データ保有者とマークされている）、そして情報発信までの道筋を示しています。

図3 - Soloveによるプライバシー分類

"Permission received from author to use this graphic" "Permission received from author to use this graphic

デザインによるプライバシー
-----------------

プライバシー・バイ・デザインは、世界有数のプライバシー専門家の一人であるアン・カブーキアン氏の発案によるもので、元カナダ・オンタリオ州情報・プライバシーコミッショナー、元ライアソン大学客員教授で、ライアソンのプライバシー・ビッグデータ研究所のエグゼクティブ・ディレクターを務め、[Global Privacy and Security by Design Centre](https://gpsbydesign.org/)の創設者でもあります。2009年に発表された「プライバシー・バイ・デザイン原則」(https://www.ipc.on.ca/wp-content/uploads/Resources/7foundationalprinciples.pdf) は、GDPRとそれに続くGDPRの影響を受けた個人情報保護法の不可欠な部分です。プライバシー・バイ・デザインは、全体的なシステム工学的アプローチをとり、規制を遵守するだけでは十分ではないことを明確にしています。

Privacy by Designは、プライバシーの将来は、規制の枠組みを遵守するだけでは保証されない、むしろ、プライバシーの保証は理想的には組織のデフォルトの運用モードにならなければならない、という見解を進めています。[28](#fn28)

下の「プライバシー・バイ・デザイン」の図では、_privacy by default_が7つの原則の1つであることに注意してください。文化的な期待の急激なコントラストは、一部の人にとっては驚くべきことかもしれません。大雑把に言えば、EUではデフォルトでプライバシーを守るのが当たり前なのに対し、アメリカではデフォルトでプライバシーを守るのは稀な例外です。

Ann Coaoukianによって記述されているプライバシー・バイ・デザインの7つの基礎原則を示すグラフィック、次のものを含む。プライバシーをデザインに組み込む; ユーザーのプライバシーを尊重する - ユーザー中心に保つ; 可視性と透明性; 完全な機能性 - ゼロサムではなくポジティブサム; エンドツーエンドのセキュリティ - ライフサイクルを完全に保護する; プライバシーをデフォルト設定にする; 反応的ではなく積極的である; 予防的ではなく救済的である](image4.png)

図4 - デザインによるプライバシー、7つの基本原則[29](#fn29)

Cavoukianは、その後の文書[_7 Laws of Identity, The Case for Privacy-Embedded Laws of Identity in the Digital Age_](https://collections.ola.org/mon/15000/267376.pdf)で、プライバシーの公正な情報をプライバシー・バイ・デザインの原則にマッピングして、"Privacy-embedded Laws of Identity "を作成している。[30](#fn30) 彼女は警告している。

> 普遍的な ID システムは、人々のデジタル ID とそれに関連するデバイスが個人情報を構成するため、プライバシーに重大な影響を及ぼすことになる。相互運用可能な ID システムが普遍的な監視のインフラストラクチャにならないよう、細心の注意を払わなければならない。

コンプライアンスは必要だが十分ではない
------------------------------------------

限定的な範囲ではあるが、個人情報保護法はデータ保護を強制するものである。このセクションでは、プライバシー法の進歩に拍手を送るとともに、同意の問題、タイムラグ、法律が現在の革新に追いつけないための消極的な姿勢、およびハーバード大学のショシャナ・ズボフが言うところのGoogleやFacebookなどの非対称的な権力のしがらみなど、プライバシー法の欠陥、欠陥、および欠点のいくつかを探っています。

* アイデンティティの専門家として、準拠しているからといって、組織が要求する（または顧客が期待する）プライバシーとセキュリティの適切なレベルを達成したことを意味するわけではないことを覚えておいてください。
    
* ハーバード大学法学部の特別研究員であるVivek Wadha氏は、「個人情報保護法の格差は指数関数的に拡大している」と説明しています。このような規制の格差は、法律が技術の進歩に追いついていないために存在しています。技術の進歩が急速に進むにつれ、格差はますます拡大しています。" 31](#fn31)
    

プライバシーとコンプライアンスの機能は、あらゆる CIAM（Consumer Identity & Access Management）プログラムの基盤となるものであり、組織のプライバシー、セキュリ ティ、およびリスク管理ポリシーに沿ったコンプライアンスのガイドラインを定義することで、消費者の個人データを保護すると同時に組織を保護するからである。組織が遵守しない場合、以下のような多くの負の結果が発生します。

* 罰金（GDPR の場合、最高 2,000 万ユーロまたは年間売上高の 4%のいずれか高い方）。
    
* 評判やブランドの毀損
    
* 顧客の損失、忠誠心の浸食
    
* 訴訟
    
* CEOが個人的に責任を負う可能性があります。
    

ID 専門家として、消費者のプライバシーとコンプライアンスの一部またはすべての側面を担当するチームの一員となる可能性がある。このセクションでは、組織全体の管轄権、同意、およびデータ保護についての基本的な理解を持ち、貢献することができます。GDPR や CCPA のコンプライアンスについては、下図に示すように、人事、プロダクトエンジニアリング、セキュリティ、マーケティング、IT、法務、カスタマーサポート、調達、その他の部門と関わることができます。

図5 - データプライバシープログラムの管理を開始する方法、例[32](#fn32)

消費者サービスには異なるプライバシーとコンプライアンス戦略が必要な理由
----------------------------------------------------------------------

ワークフォース IAM のためのプライバシーとコンプライアンス戦略は、CIAM といくつか重複していますが、CIAM はいくつかの重要な点で異なります。この理由から、単にワークフォースのプライバシーとコンプライアンスをCIAMプロジェクトに適用することは最適ではないかもしれません。以下に、ワークフォースとCIAMプロジェクトのプライバシーとコンプライアンス戦略の間の主な違いをいくつか挙げる。

* スケール：CIAM のスケールは、大規模な消費者人口と、より予測可能な従業員や労働者の数が少ないことを反映して、桁違いに大きくなることが多い。
    
* 顧客体験（CUSTOMER EXPERIENCE）。消費者に対する CX の要求は、より厳しくなっている。IAPP 社のメンバー向けに、GDPR を中心としたドキュメントである _The UX Guide for Getting Consent:_ を提供している。
    
    * 同意は、データ保護とプライバシーの中心であり、重要ではあるが、プライバシー・プログラムのすべてであり、最終的なものではない。例えば、階層化された、またはインテリジェントなプライバシー通知戦略は、プライバシーの相互作用をより煩雑にしないようにするのに役立ちます。
        
    * データ対象者は、個人データがどのように収集、使用、共有、破棄されるかについて発言権を持たなければならない。
        
    * データ主体は、個人データがどのように収集され、使用され、共有され、破棄されるかについて、発言権を持たなければならない。[33](#fn33)
        
* 法律。法域によっては、IAMとCIAMではプライバシー法が異なる場合がある。
    
* 自動化：自動化の適切なレベルは、消費者の需要を満たすために異なる。
    
* 広告。特にオンライン行動広告、および一般的な広告は、一般的には労働者ではなく消費者を対象としている。
    
* 機械学習とプロファイリング：GDPRがプロファイリング（個人についての特定の事柄を評価するための個人データの自動処理）を含む "自動化された処理 "として言及しているもの、プラス、機械学習はしばしば労働力対消費者のための異なる目的のために消費者データに適用されます。

セキュリティが重要
--------------------

アイデンティティの専門家は、セキュリティとプライバシーに関する組織のリスク管理ポリシーを理解し、それらのポリ シーを作成する同僚やポリシーの実施責任者と協力して作業する必要がある。セキュリティポリシーは、プライバシーポリシーを成功させるために必要な依存関係にある。プライバシーがなくてもセキュリティは確保できるが、セキュリティがなくてもプライバシーは確保できない」ということわざがある。[34](#fn34) セキュリティやサイバーセキュリティは、互換性を持って使われることがある。また、情報セキュリティという言葉を使う人もいます。NISTプライバシーフレームワークの下の図では、サイバーセキュリティリスクとプライバシーリスクの関係を見ると、サイバーセキュリティリスクを管理することはプライバシーリスクの軽減に役立つかもしれないが、プライバシーリスクはサイバーセキュリティインシデントの領域外のインシデントから生じる可能性があるため、それだけでは十分ではないことが明らかになっている。例えば、スマートメーターやスマートサーモスタットは、意図した通りに動作しているにもかかわらず、個人データを収集・記録し、プライバシーリスクをもたらす可能性があります。

2つの円のベン図。サイバーリスク（機密性、完全性、または可用性の損失から生じるサイバーセキュリティインシデントに関連する）とプライバシーリスク（データ処理から生じるプライバシーイベントに関連する）。重なり合っているのは、サイバーセキュリティ関連のプライバシーイベントです。

図6 - サイバーセキュリティリスクとプライバシーリスクの関係[35](#fn35)

個人情報保護方針は経営判断
-------------------------------------

組織のポリシーを深く理解することで、消費者のプライバシーとコンプライアンスにおける ID 専門家の役割が明確になる。例えば、場合によっては、マーケティング部門が大規模な個人データを収集する必要がある場合があり、組織のプライバシー・ポリシーがこれを許す場合がある。他のケースでは、組織のビジネスが個人データの信頼性と機密性に依存している場合があり、消費者のためのデータ保護を目に見える形、透明性、および堅牢な方法で確保するための十分な予算があるかもしれない。

データ処理から生じる問題から始まり、個人が直接影響を受ける（例：恥ずかしさ、差別、経済的損失）、最後に組織が影響を受ける（例：顧客の離脱、コンプライアンス違反のコスト、評判や社内文化への害）の3つの部分からなるイメージ](image7.png)

図7 - プライバシーリスクと組織リスクの関係[36](#fn36)

組織が消費者のプライバシーと関連するリスクにどのように対処するかは、ビジネス上の意思決定であり、リスクを軽減、移転、回避、または受け入れるかどうかは、プライバシーポリシーの策定と同時に、または後で決定されます。

* リスクを軽減すること（例えば、リスクを軽減すること）は、プライバシーポリシーの策定に合わせて、または後から行うことができます。リスクを軽減すること（例えば、組織は、リスクを許容できる程度に最小化するために、システム、製品、またはサービスに技術的および/またはポリシー上の措置を適用することができるかもしれません）。
    
* **譲渡** . リスクを移転または共有すること（例：契約はリスクを他の組織に移転または共有する手段であり、プライバシー通知や同意メカニズムは個人にリスクを共有する手段である）。
    
* **避ける** 。リスクを回避すること（例えば、組織はリスクが利益を上回ると判断し、データ処理を見送るか終了することがある）。
    
* リスクを受け入れること（例：消費者にとっての問題は最小限または発生する可能性が低いと組織が判断する場合がある。リスクを受け入れる（例えば、組織は、消費者にとっての問題が最小限であるか、または発生する可能性が低いと判断することができる; したがって、利益はリスクを上回り、緩和にリソースを投資する必要はない）。[37](#fn37)
    

プライバシーは競争上の優位性か？
-----------------------------------

上述のように、法律や規制は一般的に革新的な製品やサービスの提供に遅れをとっています。現在および今後の個人情報保護法への準拠は、ほんの始まりに過ぎません。プライバシーが競争上の優位性になるかどうかは、あなたの組織とその消費者次第です。それは、あなたの組織とその消費者によって異なります。2010年、データ保護のパイオニアであり専門家でもあるアラン・ウェスティンは、"プライバシーをビジネス上の優位性として利用できるという考えは死んでおり、プライバシー管理は消費者にとって複雑すぎて理解できず、認証文化の方が効果的だろう "と言い換えています。[38](#fn38) 他の人は反論しています。組織は、多くの消費者が自分のデータに対するより大きなコントロールを享受していることを認識している。消費者にとってのプライバシーは、信頼を築く機会である。中でも、アカマイの GDPR および CCPA に関する論文では、"規制遵守と ID ガバナンスを通じて顧客の信頼を構築するためのヒント" が提供されています。[39](#fn39)
  

GDPRを超えて：ePrivacyと欧州のデータ新戦略
------------------------------------------------------------

まもなく規制となるePrivacy指令については後述する。2020年2月、EUは "A European Strategy for Data "を発表した。データ保護における継続的な進歩と実証済みのEUのリーダーシップは、世界の他の地域を牽引する原動力となっています。

「データのための欧州戦略」は、ヘルスケアなどのセクター別に定められており、以下のことを規定しています。

* データはEU内で、またセクターを超えて流れることができる。
    
* 個人情報保護、消費者保護法、競争法をはじめとする欧州の規則や価値観が十分に尊重されていること。
    
* データへのアクセスおよびデータの利用に関する規則は、公正で実用的かつ明確であり、明確で信頼できるデータガバナンスの仕組みが整備されている。[40](#fn40)
    

**欧州データ戦略には、ブロックチェーン技術の評価が含まれています。

* ブロックチェーンのような新しい分散型デジタル技術は、個人の自由な選択と自己決定に基づいて、個人と企業の両方がデータの流れと利用を管理するための更なる可能性を提供します。そのような技術は、個人と企業のために、様々な補償モデルとともに、リアルタイムでの動的なデータのポータビリティを可能にするだろう。[41](#fn41)
    

さらに、フランスのデータ保護当局である[情報と自由に関する国家委員会(CNIL)](https://www.cnil.fr/en/home)は、「個人データの文脈でのブロックチェーンの責任ある利用」と、技術に内在する潜在的なプライバシーリスクについての作業を主導しています。

人権や基本的自由の遵守という点でブロックチェーンが提起する課題は、必然的に欧州レベルでの対応を必要としています。CNILは、この問題に公式に取り組んだ最初の当局の1つであり、**強力で調和のとれたアプローチを提案するために、欧州のカウンターパートと協力していきます。**

結論
==========

プライバシーを定義することは難しいかもしれませんが、上記の図5に示されているプライバシー・バイ・デザインの基本原則は、_Privacy and Compliance for Consumers_ を理解し、実施するための明確な基礎を作ります。これが、Privacy by Design が GDPR および CCPA に含まれ、その後のプライバシー規制および法律に大きな影響を与えてきた理由である。これまでに、ID の専門家は、ID、プライバシー、およびセキュリティの間の相互にリンクした依存関係を明確に理解しています。セキュリティはデータを保護し、プライバシーがどのように提供されるかは、ビジネスおよびリスク・ポリシーに基づいています。消費者のためにプライバシーとコンプライアンスを実装するという困難な作業に明るい兆しがあるのは、それが競争上の優位性とみなされ、余分な努力をする価値が十分にあるということである。

著者バイオ
----------

![筆者の写真](image8.png) クレア・ネルソン（CISSP, CIPP/E, AWS Certified Cloud Practitioner）は、事業開発と製品戦略を専門とするクリアマーク・コンサルティングのCEO。それ以前は、アイデンティティガバナンスとクラウド特権アクセス管理のリーダーであるSaviyntのテクノロジーアライアンス＆チャネルセールス担当副社長として、AWSとGoogle Cloudのパートナーシップを担当していました。クレアのサイバーセキュリティに対する情熱には、アイデンティティとプライバシーの専門分野が含まれています。MFA、IGA、PAM、アイデンティティプルーフ、ZKPに基づくプライバシー保護認証、アイデンティティ盗難、AML/KYC、GDPRなど。Clareは、Novell、EMC2、Dell、AllClear IDでリーダーシップを発揮してきました。また、C1ph3r\_Qu33nsの共同設立者でもあり、サイバーセキュリティ分野における女性のキャリアを育成し、支援することを目的とした組織でもあります。Clare は、2 世のヨギとテクノロジストであり、タフツ大学で数学の学位を取得しています。

* * *

1.  “IDPro Body of Knowledge,” IDPro, [https://www.idpro.org/body-of-knowledge/](https://www.idpro.org/body-of-knowledge/) . [↩](#fnref1)
    
2.  Solove, D., “The Myth of the Privacy Paradox,” SSRN e-Library, 24 February 2020, [https://papers.ssrn.com/sol3/papers.cfm?abstract\_id=3536265](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3536265) . [↩](#fnref2)
    
3.  Narayanan, Arvind, and Vitaly Shmatikov, “Robust De-anonymization of Large Sparse Datasets,” The University of Texas at Austin, n.d., [https://www.cs.utexas.edu/~shmat/shmat\_oak08netflix.pdf](https://www.cs.utexas.edu/~shmat/shmat_oak08netflix.pdf) _._ [↩](#fnref3)
    
4.  Narayanan, Arvind, Joanna Huey, and Edward W. Felton, “A Precautionary Approach to Big Data Privacy,” 19 March 2015, [https://www.cs.princeton.edu/~arvindn/publications/precautionary.pdf](https://www.cs.princeton.edu/~arvindn/publications/precautionary.pdf) . [↩](#fnref4)
    
5.  “’Anonymized’ Data Can Never Be Totally Anonymous, says Study,” The Guardian, 24 July 2019, [https://cacm.acm.org/news/238352-anonymized-data-can-never-be-totally-anonymous-says-study/fulltext](https://cacm.acm.org/news/238352-anonymized-data-can-never-be-totally-anonymous-says-study/fulltext) . [↩](#fnref5)
    
6.  Ibid [↩](#fnref6)
    
7.  “Complete guide to GDPR compliance,” Horizon 2020 Framework Programme of the European Union, [https://gdpr.eu/](https://gdpr.eu/) . [↩](#fnref7)
    
8.  “California Consumer Privacy Act (CCPA),” Office of the Attorney General, California Department of Justice, [https://oag.ca.gov/privacy/ccpa](https://oag.ca.gov/privacy/ccpa) . [↩](#fnref8)
    
9.  “An act to amend the general business law and the state technology law, in relation to notification of a security breach,” Senate Bill S5575B, The New York State Senate, 7 May 2019, [https://www.nysenate.gov/legislation/bills/2019/s5575](https://www.nysenate.gov/legislation/bills/2019/s5575) . [↩](#fnref9)
    
10.  “The California Consumer Privacy Act of 2018,” Assembly Bill No. 375, Chapter 55, California State Legislature, 29 June 2018, [https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill\_id=201720180AB375](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=201720180AB375) . [↩](#fnref10)
    
11.  “Data Protection Laws of the World,” map, DLA Piper Intelligence, [_https://www.dlapiperdataprotection.com/_](https://www.dlapiperdataprotection.com/) [↩](#fnref11)
    
12.  “Charter of Fundamental Rights of the European Union,” Official Journal of the European Union, C 392/391, 26 October 2012, [http://data.europa.eu/eli/treaty/char\_2012/oj](http://data.europa.eu/eli/treaty/char_2012/oj) . [↩](#fnref12)
    
13.  “Treaty on the Functioning of the European Union,” Official Journal of the European Union, C 326, 26 October 2012, [ttp://data.europa.eu/eli/treaty/tfeu\_2012/oj](http://data.europa.eu/eli/treaty/tfeu_2012/oj) . [↩](#fnref13)
    
14.  United Nations, “The Universal Declaration of Human Rights,” 1948, [https://www.un.org/en/universal-declaration-human-rights/](https://www.un.org/en/universal-declaration-human-rights/) . [↩](#fnref14)
    
15.  “APEC Privacy Framework,” International Association of Privacy Professionals (IAPP), n.d., [https://iapp.org/resources/article/apec-privacy-framework/](https://iapp.org/resources/article/apec-privacy-framework/) . [↩](#fnref15)
    
16.  “The new EU ePrivacy Regulation: what you need to know,” i-SCOOP, n.d., [https://www.i-scoop.eu/gdpr/eu-eprivacy-regulation/](https://www.i-scoop.eu/gdpr/eu-eprivacy-regulation/) . [↩](#fnref16)
    
17.  “Richards, Neil, and Woodrow Hartzog, “The Pathologies of Digital Consent,” SSRN e-Library, 11 November 2019, [https://papers.ssrn.com/sol3/papers.cfm?abstract\_id=3370433](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3370433) . [↩](#fnref17)
    
18.  Naughton, John, “’The goal is to automate us’: welcome to the age of surveillance capitalism,” The Guardian, 20 January 2020, [https://www.theguardian.com/technology/2019/jan/20/shoshana-zuboff-age-of-surveillance-capitalism-google-facebook](https://www.theguardian.com/technology/2019/jan/20/shoshana-zuboff-age-of-surveillance-capitalism-google-facebook) _._ [↩](#fnref18)
    
19.  Petters, Jeff, “Data Privacy Guide: Definitions, Explanations and Legislations,” Varonis, 29 March 2020, [https://www.varonis.com/blog/data-privacy/](https://www.varonis.com/blog/data-privacy/) _._ [↩](#fnref19)
    
20.  Maler, Eve, “Don’t Pave Privacy Cow Paths: Retool Consent for the New Mobility” (video), Identiverse 2018, 26 June 2018, [https://www.youtube.com/watch?v=eP5U2sA6EFk&t=254s](https://www.youtube.com/watch?v=eP5U2sA6EFk&t=254s) _._ [↩](#fnref20)
    
21.  “Data Protection,” European Data Protection Supervisor, n.d., [https://edps.europa.eu/data-protection/data-protection\_en](https://edps.europa.eu/data-protection/data-protection_en) [↩](#fnref21)
    
22.  Westin, Alan F. "Privacy and freedom." Washington and Lee Law Review 25, no. 1 (1968): 166. [↩](#fnref22)
    
23.  Cate, Fred H., Beth E. Cate, “The Supreme Court and information privacy,” International Data Privacy Law, Volume 2, Issue 4, November 2012, p 255-267, [https://doi.org/10.1093/idpl/ips024](https://doi.org/10.1093/idpl/ips024) . [↩](#fnref23)
    
24.  Pernot-Leplay, Emmanuel, “Data Privacy Law in China: Comparison with the EU and U.S. Approaches,” (blog post), 27 March 2020, _[https://epernot.com/data-privacy-law-china-comparison-europe-usa/](https://epernot.com/data-privacy-law-china-comparison-europe-usa/) ._ [↩](#fnref24)
    
25.  Member Economies map, Asia-Pacific Economic Cooperation, [https://www.apec.org/About-Us/About-APEC/Member-Economies](https://www.apec.org/About-Us/About-APEC/Member-Economies) . [↩](#fnref25)
    
26.  Sacks, Samm. "China’s Emerging Data Privacy System and GDPR." _Washington, DC: Center for Strategic and International Studies_ (2018). [↩](#fnref26)
    
27.  Solove, Daniel J, “A Taxonomy of Privacy,” University of Pennsylvania Law Review, Vol. 154, No. 3, January 2006, [https://www.law.upenn.edu/journals/lawreview/articles/volume154/issue3/Solove154U.Pa.L.Rev.477(2006).pdf](https://www.law.upenn.edu/journals/lawreview/articles/volume154/issue3/Solove154U.Pa.L.Rev.477(2006).pdf) . [↩](#fnref27)
    
28.  Cavoukian, Ann, “Privacy by Design: The 7 Foundational Principles,” [www.privacybydesign.ca](http://www.privacybydesign.ca) , n.d., [https://www.ipc.on.ca/wp-content/uploads/Resources/7foundationalprinciples.pdf](https://www.ipc.on.ca/wp-content/uploads/Resources/7foundationalprinciples.pdf) . [↩](#fnref28)
    
29.  “Privacy By Design,” graphic, Aristi Ninja, n.d., _[https://aristininja.com/privacy-by-design/](https://aristininja.com/privacy-by-design/) ._ [↩](#fnref29)
    
30.  Cavoukian, Ann, “7 Laws of Identity: The Case for Privacy-Embedded Laws of Identity in the Digital Age,” Information and Privacy Commission of Ontario, n.d., [https://collections.ola.org/mon/15000/267376.pdf](https://collections.ola.org/mon/15000/267376.pdf) . [↩](#fnref30)
    
31.  Wadhwa, Vivek, “Laws and Ethics Can’t Keep Pace with Technology,” MIT Technology Review, 15 April 2014, _[https://www.technologyreview.com/s/526401/laws-and-ethics-cant-keep-pace-with-technology/](https://www.technologyreview.com/s/526401/laws-and-ethics-cant-keep-pace-with-technology/) ._ [↩](#fnref31)
    
32.  ISACA webinar, Robotic Process Automation (RPA) and Audit, March 19, 2020, [_https://www.isaca.org/education/online-events/lms\_w031920_](https://www.isaca.org/education/online-events/lms_w031920) [↩](#fnref32)
    
33.  “The UX Guide for Getting Consent,” IAPP, n.d., [https://iapp.org/store/books/a191a000002FUZKAA4/](https://iapp.org/store/books/a191a000002FUZKAA4/) . [↩](#fnref33)
    
34.  Schwartz, Karen D., “Data Privacy and Data Security: What’s the Difference?” ITPro Today, 2 May 2019, [https://www.itprotoday.com/security/data-privacy-and-data-security-what-s-difference](https://www.itprotoday.com/security/data-privacy-and-data-security-what-s-difference) . [↩](#fnref34)
    
35.  “NIST Privacy Framework: A Tool for Improving Privacy Through Enterprise Risk Management, Version 1.0,” National Institute of Standards and Technology, U.S. Department of Commerce, 16 January 2020, [https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.01162020.pdf](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.01162020.pdf) . [↩](#fnref35)
    
36.  Ibid [↩](#fnref36)
    
37.  “NIST Privacy Framework: A Tool For Improving Privacy Through Enterprise Risk Management,” Preliminary Draft, National Institute of Standards and Technology, U.S. Department of Commerce, 6 September 2019, [https://www.nist.gov/system/files/documents/2019/09/09/nist\_privacy\_framework\_preliminary\_draft.pdf](https://www.nist.gov/system/files/documents/2019/09/09/nist_privacy_framework_preliminary_draft.pdf) _._ [↩](#fnref37)
    
38.  “The Privacy Advisor,” IAPP, Vol. 10, No. 10, December 2010, [https://iapp.org/media/pdf/publications/Advisor\_12-10\_print.pdf](https://iapp.org/media/pdf/publications/Advisor_12-10_print.pdf) . [↩](#fnref38)
    
39.  “White Paper: GDPR, CCPA, and Beyond: How to Comply with Data Privacy Laws and Improve Customer Trust,” Akamai, n.d., [https://www.akamai.com/us/en/campaign/assets/whitepapers/gdpr-ccpa-and-beyond-wp.jsp](https://www.akamai.com/us/en/campaign/assets/whitepapers/gdpr-ccpa-and-beyond-wp.jsp) . [↩](#fnref39)
    
40.  “Communication from the Commission to the European Parliament, the Council, the European Economic and Social Committee and the Committee of the Regions,” European Commission, COM(2020) 66 final, 19 February 2020
    
    [https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52020DC0066&from=EN](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52020DC0066&from=EN) . [↩](#fnref40)
    
41.  Ibid [↩](#fnref41)
    
42.  “Blockchain and the GDPR: Solutions for a responsible use of the blockchain in the context of personal data,” CNIL, 6 November 2018,
    
    [https://www.cnil.fr/en/blockchain-and-gdpr-solutions-responsible-use-blockchain-context-personal-data](https://www.cnil.fr/en/blockchain-and-gdpr-solutions-responsible-use-blockchain-context-personal-data) . [↩](#fnref42)

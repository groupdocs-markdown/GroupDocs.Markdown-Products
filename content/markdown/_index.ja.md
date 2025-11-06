---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "ドキュメントをMarkdownにエクスポート | GroupDocs"
head_description: "GroupDocs.Markdownは、PDF、Word、Excel、その他の形式をMarkdownにエクスポートし、生成AIエコシステムとのシームレスな統合を実現するドキュメント処理SDKです。"

############################# Header ##########################

title: "ドキュメントをAI対応にする"
description: |
  さまざまなドキュメントタイプをクリーンでセマンティックなMarkdownにエクスポートするMarkdown SDK。

  ドキュメント構造、見出し、リスト、テーブル、リンク、画像を保持します

  画像を埋め込むか外部リソースとして保存することで、画像を制御します。

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "プラットフォームを選択"
  title: "対応プラットフォーム"
  description: "GroupDocs.Markdownは以下のオペレーティングシステムとフレームワークをサポートしています。"
  details_link_title: "詳細を見る"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Markdown for .NET"
      color: "blue"
      tag: "net"
      link: "/markdown/net/"
      features_link: "https://docs.groupdocs.com/markdown/net/system-requirements/"
      features:
        # features loop
        - content: ".NET 6+  <br> .NET Framework 4.6.2+  "
          rows: "2"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "30以上のファイル形式"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Markdownの機能セット"
  description: "当ソリューションの特徴は以下の通りです。"

  items:
    # feature loop
    - icon: "convert"
      title: "ドキュメントをMarkdownにエクスポート"
      content: "PDF、Word、Excel、eBook、テキストをMarkdownにエクスポートして、LLM対応にします。"

    # feature loop
    - icon: "structure"
      title: "ドキュメント構造を保持"
      content: "ドキュメント構造、見出し、リスト、テーブル、リンク、画像を保持します。"

    # feature loop
    - icon: "image"
      title: "画像を制御"
      content: "画像を埋め込むか外部リソースとして保存します。変換プロセス中に画像を置き換えることも可能です。"
    
    # feature loop
    - icon: "settings"
      title: "ドキュメント全体または特定ページを変換"
      content: "必要に応じてドキュメント全体を変換するか、特定のページやワークシートに変換を限定できます。"


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Markdownコードサンプル"
  description: "ドキュメントをMarkdownにエクスポートする一般的な使用シナリオです。環境で製品をテストするために、[無料の一時ライセンス](https://purchase.groupdocs.com/temporary-license)をリクエストできます。"
  items:
    # code sample loop
    - title: "PDFをMarkdownにエクスポート"
      content: |
       数行のコードでPDFファイルからクリーンなMarkdownファイルを取得します。デフォルトでは、画像は出力ファイルに埋め込まれます。
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 名前空間をインポート
            using GroupDocs.Markdown;

            // ライセンスを設定
            License.Set("GroupDocs.Markdown.lic");

            // コンバータをインスタンス化
            var converter = new MarkdownConverter("business-plan.pdf");

            // 変換して出力をファイルに保存
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "画像をフォルダーに保存"
      content: |
       このコードサンプルは、DOCX ファイルを Markdown に変換し、画像を別フォルダーに保存する方法を示しています。
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 名前空間をインポートする
            using GroupDocs.Markdown;

            // ライセンスを設定する
            License.Set("GroupDocs.Markdown.lic");

            // コンバータをインスタンス化する
            var converter = new MarkdownConverter("annual-report.docx");

            // 画像エクスポート戦略と出力フォルダーを設定する
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // 変換し、出力をファイルに保存する
            converter.Convert("annual-report.md", convertOptions);
            ```

############################# Formats ############################

formats:
  enable: true
  title:  "30 以上のファイル形式に対応"
  description: "以下のファイル形式は、Markdown へのエクスポートがサポートされています。"
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "詳細な指標と統計インサイト"
  description: "当社の主要指標の詳細な内訳に深く入り込み、成果、影響、成長に関する包括的な指標と統計インサイトを提供します。"

  items:
    # metrics loop
    - number: "180+"
      title: "サポートされている形式"
      content: "PDF、Word、Excel、電子書籍など数十の文書・テキスト形式から Markdown へ変換し、gen AI エコシステムとのシームレスな統合を実現します。"
    # metrics loop
    - number: "1.0M"
      title: "開発者に信頼されています"
      content: "当社のソリューションは開発者コミュニティで信頼され、広く採用されており、プロジェクトへのシームレスな統合を提供します。"

    # metrics loop
    - number: "15+"
      title: "製品"
      content: "15 以上の文書処理 SDK を提供し、統合をスムーズにします。私たちが処理するので、安心してください。"
    
    # metrics loop
    - number: "100+"
      title: "満足した顧客"
      content: "世界中の最も象徴的なブランドにサービスを提供しています。多くの人が GroupDocs 製品を愛用する理由を発見してください！今すぐご参加を！"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "当社の満足した顧客"
  description: "GroupDocs ライブラリは、世界中で著名かつ卓越したブランドに採用されています。"

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"

############################# Actions ############################

actions:
  enable: true
  title: "すぐに始めますか？"
  description: "対象プラットフォームを選択して、製品の詳細をご確認ください。"

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "一般的な質問と懸念事項"
  description: "FAQ セクションで一般的な問い合わせへの回答を見つけ、質問や懸念に迅速に対応してください。"

  items:
    #  loop
    - question: "購入前に GroupDocs 製品を評価できますか？"
      answer: |
        はい！すべての GroupDocs 製品にはリスクフリーの評価版があります。開発者の皆様には、購入前に API をダウンロードして試し、ニーズを 100% 満たすことを強く推奨します。
    #  loop
    - question: "GroupDocs は製品デモを行っていますか？"
      answer: |
        いいえ、私たちの重点は API と、可能な限り機能的かつ安定した製品の提供です。製品を自分でテストできるよう、[一時ライセンス](https://purchase.groupdocs.com/temporary-license/)形式の完全機能の無料トライアルをご提供しています。
    #  loop
    - question: "製品はどこからダウンロードできますか？"
      answer: |
        すべての製品は NuGet または GroupDocs Releases の[ウェブサイト](https://releases.groupdocs.com)からダウンロードできます。    
    #  loop
    - question: "GroupDocs 開発者ライセンスはユーザー単位ですか、それとも指名ユーザー単位ですか？"
      answer: |
        GroupDocs Developer ライセンスはユーザー単位であり、指名ユーザー単位ではありません。コーディングチームのメンバーは時間とともに変わることがあり、そのたびにライセンスを更新するのは実務的でないことを理解しています。
    #  loop
    - question: "技術サポートは提供していますか？"
      answer: |
        はい、プロダクトチームが提供する無料の技術サポートを、[無料サポートフォーラム](https://forum.groupdocs.com/c/markdown) と [有料サポートヘルプデスク](https://helpdesk.groupdocs.com/) で提供し、円滑な体験を確保します。

############################# Cloud ############################

cloud_links:
  enable: false
  title: "GroupDocs Cloud API"
  description: "クラウドベースの REST API を使用して、任意のアプリケーションでドキュメントから Markdown への変換を高速化します。"

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "cURL の RESTful API を使用して、アプリケーション内で Microsoft Office、PDF、その他の形式を Markdown に変換します。"

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: ".NET Cloud SDK を使用して、設定可能なオプションでプログラムからドキュメントを Markdown に変換します。"
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "Java Cloud SDK を使用して、Java アプリケーションにドキュメントから Markdown への変換を統合します。"

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs Online アプリ"
  description: "ブラウザー上で、一般的なファイル形式を Markdown に変換できるオンラインアプリケーションです。"

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "さまざまなファイル形式を直接 Markdown (.md) に変換できる無料のオンラインアプリケーションをご利用ください。"

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "デバイスを問わず Microsoft Word ファイルを Markdown に変換できるウェブベースのツールです。"

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "無料の PDF から Markdown へのアプリを使用して、オンラインで PDF ファイルを Markdown に変換します。"
---

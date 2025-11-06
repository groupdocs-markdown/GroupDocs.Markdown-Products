---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ja
product: "Markdown"
product_tag: "markdown"
platform: ".NET"
platform_tag: "net"

############################# Drop-down ############################

supported_platforms:
  enable: false
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"

############################# Head ############################

head_title: ".NET でドキュメントを Markdown にエクスポート | GroupDocs"
head_description: "GroupDocs.Markdown for .NET は、PDF、Word、Excel などのフォーマットを Markdown にエクスポートし、ジェネレーティブ AI エコシステムとのシームレスな統合を実現するドキュメント処理 API です。"

############################# Header ##########################

title: "ドキュメントを Markdown にエクスポート<br>.NET API を使用して"
description: "一般的なドキュメントフォーマットをクリーンな Markdown にエクスポートし、完全に制御できる Markdown 変換 API。"
words:
  for: "for"

actions:
  main: "無料 NuGet ダウンロード"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "開始する準備はできましたか？"
  description: "GroupDocs.Markdown の機能を無料でお試しいただくか、ライセンスをリクエストしてください"

release:
  hidden: false
  title: "バージョン {0}&nbsp;がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "C# で PDF を Markdown にエクスポート"
  more: "その他の例"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // 名前空間をインポート
    using GroupDocs.Markdown;

    // ライセンスを設定
    License.Set("GroupDocs.Markdown.lic");

    // コンバータをインスタンス化
    var converter = new MarkdownConverter("business-plan.pdf");

    // 変換し、出力 Markdown ファイルを保存
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown の概要"
  description: ".NET アプリケーションでドキュメントを解析し、Markdown にエクスポートする API。"
  features:
    # feature loop
    - title: "正確かつ信頼性の高い変換"
      content: "サポートされているフォーマットを構造の完全性を保ちつつ、効率的に Markdown に変換します。.NET Framework 4.6.2 以降および .NET 6.0 を Windows と Linux でサポートしています。"

    # feature loop
    - title: "一般的なフォーマットに対応"
      content: "PDF、Word、Excel、eBook、Web、プレーンテキストファイルをパスワード保護されたドキュメントも含めて Markdown にエクスポートします。"

    # feature loop
    - title: "ローカルマシンで実行"
      content: "データはお客様が管理します - 当社はクラウドやインターネット接続を必要としないオンプレミス API を提供しています。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォームのサポート"
  description: "以下のオペレーティングシステム、フレームワーク、パッケージマネージャーがサポートされています。"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "サポートされているファイル形式"
  description: |
    Markdown へのエクスポートでサポートされるファイル形式は以下の通りです。
  groups:
    # group loop
    - color: "red"
      content: |
        ### PDF
        * Digital PDFs, PDF/A, PDF/E, PDF/X and PDF/UA
        * Encrypted and Signed PDFs
    # group loop
    - color: "blue"
      content: |
        ### Word と Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### その他   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Markdown の機能"
  description: "当社製品を際立たせる機能です。"

  items:
    # feature loop
    - icon: "multi_doc"
      title: "複数の文書形式をエクスポート"
      content: "最も一般的な文書形式を Markdown に変換します（PDF、DOCX、XLSX、EPUB など）。"

    # feature loop
    - icon: "advanced_formatting"
      title: "高度な Markdown 書式設定"
      content: "見出し、段落、リスト、表、リンク、画像、ブロッククオート、そしてコードブロックは、適切なMarkdown構文にエクスポートされます。"

    # feature loop
    - icon: "control_over_images"
      title: "画像の完全な制御"
      content: "画像をエクスポートするか、出力Markdownファイルに埋め込むことで、画像を完全に制御できます。"

    # feature loop
    - icon: "secure"
      title: "ローカルマシンで実行"
      content: "クラウドやインターネット接続は不要です。すべての処理はローカルマシン上で行われます。"

    # feature loop
    - icon: "intuitive"
      title: "直感的なパブリックAPI"
      content: "開発者のために、開発者が愛情を込めて設計したシンプルで直感的なパブリックAPIです。"

    # feature loop
    - icon: "cross_platform"
      title: "Windows と Linux で動作"
      content: ".NET および .NET Framework アセンブリは NuGet パッケージ内に含まれています。"


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "コードサンプル"
  description: ".NET アプリケーションで文書を Markdown にエクスポートする最も一般的な使用シナリオ。"
  items:
    # code sample loop
    - title: "DOCX を Markdown にエクスポート"
      content: "このコードサンプルは、DOCX ファイルを Markdown に変換し、出力をファイルに保存する方法を示しています。画像は出力ファイルに埋め込まれます。"
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
            var converter = new MarkdownConverter("annual-review.docx");

            // 変換して出力をファイルに保存する
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // 名前空間をインポートする  
            open GroupDocs.Markdown

            // ライセンスを設定する
            License.Set("GroupDocs.Markdown.lic")

            // コンバータをインスタンス化する
            let converter = new MarkdownConverter("annual-review.docx")

            // 変換して出力をファイルに保存する
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' 名前空間をインポートする  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' ライセンスを設定する
                    License.Set("GroupDocs.Markdown.lic")

                    ' コンバータをインスタンス化する
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' 変換して出力をファイルに保存する
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "画像をフォルダーに保存する"
      content: "このコードサンプルは、DOCX ファイルを Markdown に変換し、画像を別のフォルダーに保存する方法を示しています。"
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

            // 変換して出力をファイルに保存する
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // 名前空間をインポートする
            open GroupDocs.Markdown

            // ライセンスを設定する
            License.Set("GroupDocs.Markdown.lic")

            // コンバータをインスタンス化する
            let converter = new MarkdownConverter("annual-report.docx")

            // 画像エクスポート戦略と出力フォルダーを設定する
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // 変換して出力をファイルに保存する
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' 名前空間をインポートする  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' ライセンスを設定する
                    License.Set("GroupDocs.Markdown.lic")

                    ' コンバータをインスタンス化する
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' 画像エクスポート戦略と出力フォルダーを設定する
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' 変換して出力をファイルに保存する
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 製品レビュー"
# description: "私たちの言葉だけでなく、他の開発者が当社の API について何と言っているかをご確認ください。"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "優れたサービスと優れた製品です。GroupDocs.Markdown for .NET の導入プロセス中、非常に協力的で迅速に対応してくれました。これ以上のおすすめはできません。"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "プロジェクトで GroupDocs.Markdown for .NET を実装・使用したところ、非常にうまく機能しています。多数のドキュメントでテストしましたが、今のところ問題ありません。Markdown の出力はクリーンで、ソース間でも一貫しています。"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

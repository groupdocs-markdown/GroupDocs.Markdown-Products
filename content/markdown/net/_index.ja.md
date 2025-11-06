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

head_title: ".NET ã§ãƒ‰ã‚­ãƒ¥ãƒ¡ãƒ³ãƒˆã‚’ Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆ | GroupDocs"
head_description: "GroupDocs.Markdown for .NET ã¯ã€PDFã€Wordã€Excel ãªã©ã®ãƒ•ã‚©ãƒ¼ãƒžãƒƒãƒˆã‚’ Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆã—ã€ã‚¸ã‚§ãƒãƒ¬ãƒ¼ãƒ†ã‚£ãƒ– AI ã‚¨ã‚³ã‚·ã‚¹ãƒ†ãƒ ã¨ã®ã‚·ãƒ¼ãƒ ãƒ¬ã‚¹ãªçµ±åˆã‚’å®Ÿç¾ã™ã‚‹ãƒ‰ã‚­ãƒ¥ãƒ¡ãƒ³ãƒˆå‡¦ç† API ã§ã™ã€‚"

############################# Header ##########################

title: "ãƒ‰ã‚­ãƒ¥ãƒ¡ãƒ³ãƒˆã‚’ Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆ<br>.NET API ã‚’ä½¿ç”¨ã—ã¦"
description: "ä¸€èˆ¬çš„ãªãƒ‰ã‚­ãƒ¥ãƒ¡ãƒ³ãƒˆãƒ•ã‚©ãƒ¼ãƒžãƒƒãƒˆã‚’ã‚¯ãƒªãƒ¼ãƒ³ãª Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆã—ã€å®Œå…¨ã«åˆ¶å¾¡ã§ãã‚‹ Markdown å¤‰æ› APIã€‚"
words:
  for: "for"

actions:
  main: "ç„¡æ–™ NuGet ãƒ€ã‚¦ãƒ³ãƒ­ãƒ¼ãƒ‰"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "ãƒ©ã‚¤ã‚»ãƒ³ã‚¹"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "é–‹å§‹ã™ã‚‹æº–å‚™ã¯ã§ãã¾ã—ãŸã‹ï¼Ÿ"
  description: "GroupDocs.Markdown ã®æ©Ÿèƒ½ã‚’ç„¡æ–™ã§ãŠè©¦ã—ã„ãŸã ãã‹ã€ãƒ©ã‚¤ã‚»ãƒ³ã‚¹ã‚’ãƒªã‚¯ã‚¨ã‚¹ãƒˆã—ã¦ãã ã•ã„"

release:
  hidden: false
  title: "ãƒãƒ¼ã‚¸ãƒ§ãƒ³ {0}&nbsp;ãŒãƒªãƒªãƒ¼ã‚¹ã•ã‚Œã¾ã—ãŸ"
  notes: "æ–°æ©Ÿèƒ½ã‚’è¦‹ã‚‹"
  downloads: "ãƒ€ã‚¦ãƒ³ãƒ­ãƒ¼ãƒ‰"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "C# ã§ PDF ã‚’ Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆ"
  more: "ãã®ä»–ã®ä¾‹"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // åå‰ç©ºé–“ã‚’ã‚¤ãƒ³ãƒãƒ¼ãƒˆ
    using GroupDocs.Markdown;

    // ãƒ©ã‚¤ã‚»ãƒ³ã‚¹ã‚’è¨­å®š
    License.Set("GroupDocs.Markdown.lic");

    // ã‚³ãƒ³ãƒãƒ¼ã‚¿ã‚’ã‚¤ãƒ³ã‚¹ã‚¿ãƒ³ã‚¹åŒ–
    var converter = new MarkdownConverter("business-plan.pdf");

    // å¤‰æ›ã—ã€å‡ºåŠ› Markdown ãƒ•ã‚¡ã‚¤ãƒ«ã‚’ä¿å­˜
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown ã®æ¦‚è¦"
  description: ".NET ã‚¢ãƒ—ãƒªã‚±ãƒ¼ã‚·ãƒ§ãƒ³ã§ãƒ‰ã‚­ãƒ¥ãƒ¡ãƒ³ãƒˆã‚’è§£æžã—ã€Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆã™ã‚‹ APIã€‚"
  features:
    # feature loop
    - title: "æ­£ç¢ºã‹ã¤ä¿¡é ¼æ€§ã®é«˜ã„å¤‰æ›"
      content: "ã‚µãƒãƒ¼ãƒˆã•ã‚Œã¦ã„ã‚‹ãƒ•ã‚©ãƒ¼ãƒžãƒƒãƒˆã‚’æ§‹é€ ã®å®Œå…¨æ€§ã‚’ä¿ã¡ã¤ã¤ã€åŠ¹çŽ‡çš„ã« Markdown ã«å¤‰æ›ã—ã¾ã™ã€‚.NET Framework 4.6.2 ä»¥é™ãŠã‚ˆã³ .NET 6.0 ã‚’ Windows ã¨ Linux ã§ã‚µãƒãƒ¼ãƒˆã—ã¦ã„ã¾ã™ã€‚"

    # feature loop
    - title: "ä¸€èˆ¬çš„ãªãƒ•ã‚©ãƒ¼ãƒžãƒƒãƒˆã«å¯¾å¿œ"
      content: "PDFã€Wordã€Excelã€eBookã€Webã€ãƒ—ãƒ¬ãƒ¼ãƒ³ãƒ†ã‚­ã‚¹ãƒˆãƒ•ã‚¡ã‚¤ãƒ«ã‚’ãƒ‘ã‚¹ãƒ¯ãƒ¼ãƒ‰ä¿è­·ã•ã‚ŒãŸãƒ‰ã‚­ãƒ¥ãƒ¡ãƒ³ãƒˆã‚‚å«ã‚ã¦ Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆã—ã¾ã™ã€‚"

    # feature loop
    - title: "ãƒ­ãƒ¼ã‚«ãƒ«ãƒžã‚·ãƒ³ã§å®Ÿè¡Œ"
      content: "ãƒ‡ãƒ¼ã‚¿ã¯ãŠå®¢æ§˜ãŒç®¡ç†ã—ã¾ã™ - å½“ç¤¾ã¯ã‚¯ãƒ©ã‚¦ãƒ‰ã‚„ã‚¤ãƒ³ã‚¿ãƒ¼ãƒãƒƒãƒˆæŽ¥ç¶šã‚’å¿…è¦ã¨ã—ãªã„ã‚ªãƒ³ãƒ—ãƒ¬ãƒŸã‚¹ API ã‚’æä¾›ã—ã¦ã„ã¾ã™ã€‚"

############################# Platforms ############################
platforms:
  enable: true
  title: "ãƒ—ãƒ©ãƒƒãƒˆãƒ•ã‚©ãƒ¼ãƒ ã®ã‚µãƒãƒ¼ãƒˆ"
  description: "ä»¥ä¸‹ã®ã‚ªãƒšãƒ¬ãƒ¼ãƒ†ã‚£ãƒ³ã‚°ã‚·ã‚¹ãƒ†ãƒ ã€ãƒ•ãƒ¬ãƒ¼ãƒ ãƒ¯ãƒ¼ã‚¯ã€ãƒ‘ãƒƒã‚±ãƒ¼ã‚¸ãƒžãƒãƒ¼ã‚¸ãƒ£ãƒ¼ãŒã‚µãƒãƒ¼ãƒˆã•ã‚Œã¦ã„ã¾ã™ã€‚"
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
  title: "ã‚µãƒãƒ¼ãƒˆã•ã‚Œã¦ã„ã‚‹ãƒ•ã‚¡ã‚¤ãƒ«å½¢å¼"
  description: |
    Markdown ã¸ã®ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆã§ã‚µãƒãƒ¼ãƒˆã•ã‚Œã‚‹ãƒ•ã‚¡ã‚¤ãƒ«å½¢å¼ã¯ä»¥ä¸‹ã®é€šã‚Šã§ã™ã€‚
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
        ### Word ã¨ Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### ãã®ä»–   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Markdown ã®æ©Ÿèƒ½"
  description: "å½“ç¤¾è£½å“ã‚’éš›ç«‹ãŸã›ã‚‹æ©Ÿèƒ½ã§ã™ã€‚"

  items:
    # feature loop
    - icon: "multi_doc"
      title: "è¤‡æ•°ã®æ–‡æ›¸å½¢å¼ã‚’ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆ"
      content: "æœ€ã‚‚ä¸€èˆ¬çš„ãªæ–‡æ›¸å½¢å¼ã‚’ Markdown ã«å¤‰æ›ã—ã¾ã™ï¼ˆPDFã€DOCXã€XLSXã€EPUB ãªã©ï¼‰ã€‚"

    # feature loop
    - icon: "advanced_formatting"
      title: "é«˜åº¦ãª Markdown æ›¸å¼è¨­å®š"
      content: "è¦‹å‡ºã—ã€æ®µè½ã€ãƒªã‚¹ãƒˆã€è¡¨ã€ãƒªãƒ³ã‚¯ã€ç”»åƒã€ãƒ–ãƒ­ãƒƒã‚¯ã‚¯ã‚ªãƒ¼ãƒˆã€ãã—ã¦ã‚³ãƒ¼ãƒ‰ãƒ–ãƒ­ãƒƒã‚¯ã¯ã€é©åˆ‡ãªMarkdownæ§‹æ–‡ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆã•ã‚Œã¾ã™ã€‚"

    # feature loop
    - icon: "control_over_images"
      title: "ç”»åƒã®å®Œå…¨ãªåˆ¶å¾¡"
      content: "ç”»åƒã‚’ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆã™ã‚‹ã‹ã€å‡ºåŠ›Markdownãƒ•ã‚¡ã‚¤ãƒ«ã«åŸ‹ã‚è¾¼ã‚€ã“ã¨ã§ã€ç”»åƒã‚’å®Œå…¨ã«åˆ¶å¾¡ã§ãã¾ã™ã€‚"

    # feature loop
    - icon: "secure"
      title: "ãƒ­ãƒ¼ã‚«ãƒ«ãƒžã‚·ãƒ³ã§å®Ÿè¡Œ"
      content: "ã‚¯ãƒ©ã‚¦ãƒ‰ã‚„ã‚¤ãƒ³ã‚¿ãƒ¼ãƒãƒƒãƒˆæŽ¥ç¶šã¯ä¸è¦ã§ã™ã€‚ã™ã¹ã¦ã®å‡¦ç†ã¯ãƒ­ãƒ¼ã‚«ãƒ«ãƒžã‚·ãƒ³ä¸Šã§è¡Œã‚ã‚Œã¾ã™ã€‚"

    # feature loop
    - icon: "intuitive"
      title: "ç›´æ„Ÿçš„ãªãƒ‘ãƒ–ãƒªãƒƒã‚¯API"
      content: "é–‹ç™ºè€…ã®ãŸã‚ã«ã€é–‹ç™ºè€…ãŒæ„›æƒ…ã‚’è¾¼ã‚ã¦è¨­è¨ˆã—ãŸã‚·ãƒ³ãƒ—ãƒ«ã§ç›´æ„Ÿçš„ãªãƒ‘ãƒ–ãƒªãƒƒã‚¯APIã§ã™ã€‚"

    # feature loop
    - icon: "cross_platform"
      title: "Windows ã¨ Linux ã§å‹•ä½œ"
      content: ".NET ãŠã‚ˆã³ .NET Framework ã‚¢ã‚»ãƒ³ãƒ–ãƒªã¯ NuGet ãƒ‘ãƒƒã‚±ãƒ¼ã‚¸å†…ã«å«ã¾ã‚Œã¦ã„ã¾ã™ã€‚"


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "ã‚³ãƒ¼ãƒ‰ã‚µãƒ³ãƒ—ãƒ«"
  description: ".NET ã‚¢ãƒ—ãƒªã‚±ãƒ¼ã‚·ãƒ§ãƒ³ã§æ–‡æ›¸ã‚’ Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆã™ã‚‹æœ€ã‚‚ä¸€èˆ¬çš„ãªä½¿ç”¨ã‚·ãƒŠãƒªã‚ªã€‚"
  items:
    # code sample loop
    - title: "DOCX ã‚’ Markdown ã«ã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆ"
      content: "ã“ã®ã‚³ãƒ¼ãƒ‰ã‚µãƒ³ãƒ—ãƒ«ã¯ã€DOCX ãƒ•ã‚¡ã‚¤ãƒ«ã‚’ Markdown ã«å¤‰æ›ã—ã€å‡ºåŠ›ã‚’ãƒ•ã‚¡ã‚¤ãƒ«ã«ä¿å­˜ã™ã‚‹æ–¹æ³•ã‚’ç¤ºã—ã¦ã„ã¾ã™ã€‚ç”»åƒã¯å‡ºåŠ›ãƒ•ã‚¡ã‚¤ãƒ«ã«åŸ‹ã‚è¾¼ã¾ã‚Œã¾ã™ã€‚"
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // åå‰ç©ºé–“ã‚’ã‚¤ãƒ³ãƒãƒ¼ãƒˆã™ã‚‹
            using GroupDocs.Markdown;

            // ãƒ©ã‚¤ã‚»ãƒ³ã‚¹ã‚’è¨­å®šã™ã‚‹
            License.Set("GroupDocs.Markdown.lic");

            // ã‚³ãƒ³ãƒãƒ¼ã‚¿ã‚’ã‚¤ãƒ³ã‚¹ã‚¿ãƒ³ã‚¹åŒ–ã™ã‚‹
            var converter = new MarkdownConverter("annual-review.docx");

            // å¤‰æ›ã—ã¦å‡ºåŠ›ã‚’ãƒ•ã‚¡ã‚¤ãƒ«ã«ä¿å­˜ã™ã‚‹
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // åå‰ç©ºé–“ã‚’ã‚¤ãƒ³ãƒãƒ¼ãƒˆã™ã‚‹  
            open GroupDocs.Markdown

            // ãƒ©ã‚¤ã‚»ãƒ³ã‚¹ã‚’è¨­å®šã™ã‚‹
            License.Set("GroupDocs.Markdown.lic")

            // ã‚³ãƒ³ãƒãƒ¼ã‚¿ã‚’ã‚¤ãƒ³ã‚¹ã‚¿ãƒ³ã‚¹åŒ–ã™ã‚‹
            let converter = new MarkdownConverter("annual-review.docx")

            // å¤‰æ›ã—ã¦å‡ºåŠ›ã‚’ãƒ•ã‚¡ã‚¤ãƒ«ã«ä¿å­˜ã™ã‚‹
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' åå‰ç©ºé–“ã‚’ã‚¤ãƒ³ãƒãƒ¼ãƒˆã™ã‚‹  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' ãƒ©ã‚¤ã‚»ãƒ³ã‚¹ã‚’è¨­å®šã™ã‚‹
                    License.Set("GroupDocs.Markdown.lic")

                    ' ã‚³ãƒ³ãƒãƒ¼ã‚¿ã‚’ã‚¤ãƒ³ã‚¹ã‚¿ãƒ³ã‚¹åŒ–ã™ã‚‹
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' å¤‰æ›ã—ã¦å‡ºåŠ›ã‚’ãƒ•ã‚¡ã‚¤ãƒ«ã«ä¿å­˜ã™ã‚‹
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "ç”»åƒã‚’ãƒ•ã‚©ãƒ«ãƒ€ãƒ¼ã«ä¿å­˜ã™ã‚‹"
      content: "ã“ã®ã‚³ãƒ¼ãƒ‰ã‚µãƒ³ãƒ—ãƒ«ã¯ã€DOCX ãƒ•ã‚¡ã‚¤ãƒ«ã‚’ Markdown ã«å¤‰æ›ã—ã€ç”»åƒã‚’åˆ¥ã®ãƒ•ã‚©ãƒ«ãƒ€ãƒ¼ã«ä¿å­˜ã™ã‚‹æ–¹æ³•ã‚’ç¤ºã—ã¦ã„ã¾ã™ã€‚"
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // åå‰ç©ºé–“ã‚’ã‚¤ãƒ³ãƒãƒ¼ãƒˆã™ã‚‹
            using GroupDocs.Markdown;

            // ãƒ©ã‚¤ã‚»ãƒ³ã‚¹ã‚’è¨­å®šã™ã‚‹
            License.Set("GroupDocs.Markdown.lic");

            // ã‚³ãƒ³ãƒãƒ¼ã‚¿ã‚’ã‚¤ãƒ³ã‚¹ã‚¿ãƒ³ã‚¹åŒ–ã™ã‚‹
            var converter = new MarkdownConverter("annual-report.docx");

            // ç”»åƒã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆæˆ¦ç•¥ã¨å‡ºåŠ›ãƒ•ã‚©ãƒ«ãƒ€ãƒ¼ã‚’è¨­å®šã™ã‚‹
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // å¤‰æ›ã—ã¦å‡ºåŠ›ã‚’ãƒ•ã‚¡ã‚¤ãƒ«ã«ä¿å­˜ã™ã‚‹
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // åå‰ç©ºé–“ã‚’ã‚¤ãƒ³ãƒãƒ¼ãƒˆã™ã‚‹
            open GroupDocs.Markdown

            // ãƒ©ã‚¤ã‚»ãƒ³ã‚¹ã‚’è¨­å®šã™ã‚‹
            License.Set("GroupDocs.Markdown.lic")

            // ã‚³ãƒ³ãƒãƒ¼ã‚¿ã‚’ã‚¤ãƒ³ã‚¹ã‚¿ãƒ³ã‚¹åŒ–ã™ã‚‹
            let converter = new MarkdownConverter("annual-report.docx")

            // ç”»åƒã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆæˆ¦ç•¥ã¨å‡ºåŠ›ãƒ•ã‚©ãƒ«ãƒ€ãƒ¼ã‚’è¨­å®šã™ã‚‹
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // å¤‰æ›ã—ã¦å‡ºåŠ›ã‚’ãƒ•ã‚¡ã‚¤ãƒ«ã«ä¿å­˜ã™ã‚‹
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' åå‰ç©ºé–“ã‚’ã‚¤ãƒ³ãƒãƒ¼ãƒˆã™ã‚‹  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' ãƒ©ã‚¤ã‚»ãƒ³ã‚¹ã‚’è¨­å®šã™ã‚‹
                    License.Set("GroupDocs.Markdown.lic")

                    ' ã‚³ãƒ³ãƒãƒ¼ã‚¿ã‚’ã‚¤ãƒ³ã‚¹ã‚¿ãƒ³ã‚¹åŒ–ã™ã‚‹
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' ç”»åƒã‚¨ã‚¯ã‚¹ãƒãƒ¼ãƒˆæˆ¦ç•¥ã¨å‡ºåŠ›ãƒ•ã‚©ãƒ«ãƒ€ãƒ¼ã‚’è¨­å®šã™ã‚‹
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' å¤‰æ›ã—ã¦å‡ºåŠ›ã‚’ãƒ•ã‚¡ã‚¤ãƒ«ã«ä¿å­˜ã™ã‚‹
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs è£½å“ãƒ¬ãƒ“ãƒ¥ãƒ¼"
# description: "ç§ãŸã¡ã®è¨€è‘‰ã ã‘ã§ãªãã€ä»–ã®é–‹ç™ºè€…ãŒå½“ç¤¾ã® API ã«ã¤ã„ã¦ä½•ã¨è¨€ã£ã¦ã„ã‚‹ã‹ã‚’ã”ç¢ºèªãã ã•ã„ã€‚"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "å„ªã‚ŒãŸã‚µãƒ¼ãƒ“ã‚¹ã¨å„ªã‚ŒãŸè£½å“ã§ã™ã€‚GroupDocs.Markdown for .NET ã®å°Žå…¥ãƒ—ãƒ­ã‚»ã‚¹ä¸­ã€éžå¸¸ã«å”åŠ›çš„ã§è¿…é€Ÿã«å¯¾å¿œã—ã¦ãã‚Œã¾ã—ãŸã€‚ã“ã‚Œä»¥ä¸Šã®ãŠã™ã™ã‚ã¯ã§ãã¾ã›ã‚“ã€‚"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "ãƒ—ãƒ­ã‚¸ã‚§ã‚¯ãƒˆã§ GroupDocs.Markdown for .NET ã‚’å®Ÿè£…ãƒ»ä½¿ç”¨ã—ãŸã¨ã“ã‚ã€éžå¸¸ã«ã†ã¾ãæ©Ÿèƒ½ã—ã¦ã„ã¾ã™ã€‚å¤šæ•°ã®ãƒ‰ã‚­ãƒ¥ãƒ¡ãƒ³ãƒˆã§ãƒ†ã‚¹ãƒˆã—ã¾ã—ãŸãŒã€ä»Šã®ã¨ã“ã‚å•é¡Œã‚ã‚Šã¾ã›ã‚“ã€‚Markdown ã®å‡ºåŠ›ã¯ã‚¯ãƒªãƒ¼ãƒ³ã§ã€ã‚½ãƒ¼ã‚¹é–“ã§ã‚‚ä¸€è²«ã—ã¦ã„ã¾ã™ã€‚"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

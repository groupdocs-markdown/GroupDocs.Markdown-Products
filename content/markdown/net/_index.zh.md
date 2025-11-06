---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: zh
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

head_title: ".NET ä¸­å°†æ–‡æ¡£å¯¼å‡ºä¸º Markdown | GroupDocs"
head_description: "GroupDocs.Markdown for .NET æ˜¯ä¸€æ¬¾æ–‡æ¡£å¤„ç† APIï¼Œå¯å°† PDFã€Wordã€Excel ç­‰æ ¼å¼å¯¼å‡ºä¸º Markdownï¼Œå®žçŽ°ä¸Žç”Ÿæˆå¼ AI ç”Ÿæ€ç³»ç»Ÿçš„æ— ç¼é›†æˆã€‚"

############################# Header ##########################

title: "å°†æ–‡æ¡£å¯¼å‡ºä¸º Markdown<br>ä½¿ç”¨ .NET API"
description: "Markdown è½¬æ¢ APIï¼Œå¯å°†æµè¡Œæ–‡æ¡£æ ¼å¼å¯¼å‡ºä¸ºå¹²å‡€çš„ Markdownï¼Œæä¾›å®Œæ•´æŽ§åˆ¶ã€‚"
words:
  for: "for"

actions:
  main: "å…è´¹ NuGet ä¸‹è½½"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "æŽˆæƒ"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "å‡†å¤‡å¥½å¼€å§‹äº†å—ï¼Ÿ"
  description: "å…è´¹è¯•ç”¨ GroupDocs.Markdown åŠŸèƒ½æˆ–ç”³è¯·æŽˆæƒã€‚"

release:
  hidden: false
  title: "ç‰ˆæœ¬ {0}&nbsp;å·²å‘å¸ƒ"
  notes: "æŸ¥çœ‹æ›´æ–°å†…å®¹"
  downloads: "ä¸‹è½½"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "åœ¨ C# ä¸­å°† PDF å¯¼å‡ºä¸º Markdown"
  more: "æ›´å¤šç¤ºä¾‹"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // å¯¼å…¥å‘½åç©ºé—´
    using GroupDocs.Markdown;

    // è®¾ç½®è®¸å¯è¯
    License.Set("GroupDocs.Markdown.lic");

    // å®žä¾‹åŒ–è½¬æ¢å™¨
    var converter = new MarkdownConverter("business-plan.pdf");

    // è½¬æ¢å¹¶ä¿å­˜è¾“å‡ºçš„ Markdown æ–‡ä»¶
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown ä¸€è§ˆ"
  description: "åœ¨ .NET åº”ç”¨ç¨‹åºä¸­è§£æžå¹¶å¯¼å‡ºæ–‡æ¡£ä¸º Markdown çš„ APIã€‚"
  features:
    # feature loop
    - title: "å‡†ç¡®ä¸”å¯é çš„è½¬æ¢"
      content: "é«˜æ•ˆåœ°å°†å—æ”¯æŒçš„æ ¼å¼è½¬æ¢ä¸º Markdownï¼ŒåŒæ—¶ä¿æŒç»“æž„å®Œæ•´æ€§ã€‚æ”¯æŒ Windows å’Œ Linux ä¸Šçš„ .NET Framework 4.6.2+ ä¸Ž .NET 6.0ã€‚"

    # feature loop
    - title: "æ”¯æŒçš„æµè¡Œæ ¼å¼"
      content: "å°† PDFã€Wordã€Excelã€ç”µå­ä¹¦ã€ç½‘é¡µå’Œçº¯æ–‡æœ¬æ–‡ä»¶å¯¼å‡ºä¸º Markdownï¼ŒåŒ…æ‹¬å—å¯†ç ä¿æŠ¤çš„æ–‡æ¡£ã€‚"

    # feature loop
    - title: "åœ¨æœ¬åœ°æœºå™¨ä¸Šè¿è¡Œ"
      content: "æ‚¨æŽŒæŽ§æ‚¨çš„æ•°æ®â€”â€”æˆ‘ä»¬æä¾›çš„æœ¬åœ° API æ— éœ€ä»»ä½•äº‘æœåŠ¡æˆ–äº’è”ç½‘è¿žæŽ¥ã€‚"

############################# Platforms ############################
platforms:
  enable: true
  title: "å¹³å°æ”¯æŒ"
  description: "æ”¯æŒä»¥ä¸‹æ“ä½œç³»ç»Ÿã€æ¡†æž¶å’ŒåŒ…ç®¡ç†å™¨ã€‚"
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
  title: "æ”¯æŒçš„æ–‡ä»¶æ ¼å¼"
  description: |
    æ”¯æŒä»¥ä¸‹æ–‡ä»¶æ ¼å¼å¯¼å‡ºä¸º Markdownã€‚
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
        ### Word ä¸Ž Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### å…¶ä»–   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Markdown åŠŸèƒ½"
  description: "è¿™äº›åŠŸèƒ½ä½¿æˆ‘ä»¬çš„äº§å“è„±é¢–è€Œå‡ºã€‚"

  items:
    # feature loop
    - icon: "multi_doc"
      title: "å¯¼å‡ºå¤šç§æ–‡æ¡£æ ¼å¼"
      content: "å°†æœ€æµè¡Œçš„æ–‡æ¡£æ ¼å¼è½¬æ¢ä¸º Markdownï¼ˆPDFã€DOCXã€XLSXã€EPUB ç­‰ï¼‰ã€‚"

    # feature loop
    - icon: "advanced_formatting"
      title: "é«˜çº§ Markdown æ ¼å¼åŒ–"
      content: "æ ‡é¢˜ã€æ®µè½ã€åˆ—è¡¨ã€è¡¨æ ¼ã€é“¾æŽ¥ã€å›¾åƒã€å—å¼•ç”¨å’Œä»£ç å—ä¼šå¯¼å‡ºä¸ºç›¸åº”çš„ Markdown è¯­æ³•ã€‚"

    # feature loop
    - icon: "control_over_images"
      title: "å¯¹å›¾åƒçš„å®Œæ•´æŽ§åˆ¶"
      content: "é€šè¿‡å¯¼å‡ºå›¾åƒæˆ–åµŒå…¥åˆ°è¾“å‡ºçš„ Markdown æ–‡ä»¶ä¸­æ¥æŽ§åˆ¶å›¾åƒã€‚"

    # feature loop
    - icon: "secure"
      title: "åœ¨æœ¬åœ°æœºå™¨ä¸Šè¿è¡Œ"
      content: "æ— éœ€äº‘æˆ–äº’è”ç½‘è¿žæŽ¥ï¼Œæ‰€æœ‰å¤„ç†å‡åœ¨æœ¬åœ°æœºå™¨ä¸Šå®Œæˆã€‚"

    # feature loop
    - icon: "intuitive"
      title: "ç›´è§‚çš„å…¬å…± API"
      content: "ç”±å¼€å‘è€…ä¸ºå¼€å‘è€…è®¾è®¡çš„ç®€æ´ç›´è§‚çš„å…¬å…± APIï¼Œå……æ»¡çƒ­æƒ…ã€‚"

    # feature loop
    - icon: "cross_platform"
      title: "æ”¯æŒ Windows å’Œ Linux"
      content: ".NET å’Œ .NET Framework ç¨‹åºé›†å·²éš NuGet åŒ…æä¾›ã€‚"


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "ä»£ç ç¤ºä¾‹"
  description: "åœ¨ .NET åº”ç”¨ç¨‹åºä¸­å°†æ–‡æ¡£å¯¼å‡ºä¸º Markdown çš„æœ€å¸¸è§ä½¿ç”¨åœºæ™¯ã€‚"
  items:
    # code sample loop
    - title: "å°† DOCX å¯¼å‡ºä¸º Markdown"
      content: "æ­¤ä»£ç ç¤ºä¾‹å±•ç¤ºäº†å¦‚ä½•å°† DOCX æ–‡ä»¶è½¬æ¢ä¸º Markdown å¹¶å°†è¾“å‡ºä¿å­˜åˆ°æ–‡ä»¶ä¸­ã€‚å›¾åƒåµŒå…¥åœ¨è¾“å‡ºæ–‡ä»¶ä¸­ã€‚"
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // å¯¼å…¥å‘½åç©ºé—´
            using GroupDocs.Markdown;

            // è®¾ç½®è®¸å¯è¯
            License.Set("GroupDocs.Markdown.lic");

            // å®žä¾‹åŒ–è½¬æ¢å™¨
            var converter = new MarkdownConverter("annual-review.docx");

            // è½¬æ¢å¹¶å°†è¾“å‡ºä¿å­˜åˆ°æ–‡ä»¶
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // å¯¼å…¥å‘½åç©ºé—´  
            open GroupDocs.Markdown

            // è®¾ç½®è®¸å¯è¯
            License.Set("GroupDocs.Markdown.lic")

            // å®žä¾‹åŒ–è½¬æ¢å™¨
            let converter = new MarkdownConverter("annual-review.docx")

            // è½¬æ¢å¹¶å°†è¾“å‡ºä¿å­˜åˆ°æ–‡ä»¶
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' å¯¼å…¥å‘½åç©ºé—´  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' è®¾ç½®è®¸å¯è¯
                    License.Set("GroupDocs.Markdown.lic")

                    ' å®žä¾‹åŒ–è½¬æ¢å™¨
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' è½¬æ¢å¹¶å°†è¾“å‡ºä¿å­˜åˆ°æ–‡ä»¶
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "å°†å›¾åƒä¿å­˜åˆ°æ–‡ä»¶å¤¹"
      content: "æ­¤ä»£ç ç¤ºä¾‹å±•ç¤ºäº†å¦‚ä½•å°† DOCX æ–‡ä»¶è½¬æ¢ä¸º Markdown å¹¶å°†å›¾åƒä¿å­˜åˆ°å•ç‹¬çš„æ–‡ä»¶å¤¹ã€‚"
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // å¯¼å…¥å‘½åç©ºé—´
            using GroupDocs.Markdown;

            // è®¾ç½®è®¸å¯è¯
            License.Set("GroupDocs.Markdown.lic");

            // å®žä¾‹åŒ–è½¬æ¢å™¨
            var converter = new MarkdownConverter("annual-report.docx");

            // è®¾ç½®å›¾åƒå¯¼å‡ºç­–ç•¥å’Œè¾“å‡ºæ–‡ä»¶å¤¹
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // è½¬æ¢å¹¶å°†è¾“å‡ºä¿å­˜åˆ°æ–‡ä»¶
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // å¯¼å…¥å‘½åç©ºé—´
            open GroupDocs.Markdown

            // è®¾ç½®è®¸å¯è¯
            License.Set("GroupDocs.Markdown.lic")

            // å®žä¾‹åŒ–è½¬æ¢å™¨
            let converter = new MarkdownConverter("annual-report.docx")

            // è®¾ç½®å›¾åƒå¯¼å‡ºç­–ç•¥å’Œè¾“å‡ºæ–‡ä»¶å¤¹
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // è½¬æ¢å¹¶å°†è¾“å‡ºä¿å­˜åˆ°æ–‡ä»¶
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' å¯¼å…¥å‘½åç©ºé—´  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' è®¾ç½®è®¸å¯è¯
                    License.Set("GroupDocs.Markdown.lic")

                    ' å®žä¾‹åŒ–è½¬æ¢å™¨
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' è®¾ç½®å›¾åƒå¯¼å‡ºç­–ç•¥å’Œè¾“å‡ºæ–‡ä»¶å¤¹
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' è½¬æ¢å¹¶å°†è¾“å‡ºä¿å­˜åˆ°æ–‡ä»¶
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs äº§å“è¯„ä»·"
# description: "ä¸ä»…ä»…å¬æˆ‘ä»¬è¯´ï¼Œçœ‹çœ‹å…¶ä»–å¼€å‘è€…å¯¹æˆ‘ä»¬ API çš„è¯„ä»·ã€‚"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "ä¼˜ç§€çš„æœåŠ¡å’Œå“è¶Šçš„äº§å“ã€‚åœ¨ GroupDocs.Markdown for .NET å®žæ–½è¿‡ç¨‹ä¸­ï¼Œä»–ä»¬æä¾›äº†æžå¤§çš„å¸®åŠ©å’Œå“åº”ï¼Œæˆ‘å¯¹ä»–ä»¬èµžä¸ç»å£ã€‚"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "åœ¨é¡¹ç›®ä¸­å®žçŽ°å¹¶ä½¿ç”¨ GroupDocs.Markdown for .NET åŽï¼Œæ•ˆæžœéžå¸¸å¥½ã€‚æˆ‘å·²ä½¿ç”¨å¤§é‡æ–‡æ¡£è¿›è¡Œæµ‹è¯•ï¼Œè¿„ä»Šä¸ºæ­¢è¡¨çŽ°è‰¯å¥½ã€‚Markdown è¾“å‡ºå¹²å‡€ä¸”åœ¨å„ç§æ¥æºé—´ä¿æŒä¸€è‡´ã€‚"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

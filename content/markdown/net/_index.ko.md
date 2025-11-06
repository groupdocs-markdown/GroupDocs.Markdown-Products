---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ko
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

head_title: ".NETì—ì„œ ë¬¸ì„œë¥¼ Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ê¸° | GroupDocs"
head_description: "GroupDocs.Markdown for .NETì€ PDF, Word, Excel ë“± ë‹¤ì–‘í•œ í˜•ì‹ì„ Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ì–´ ìƒì„± AI ìƒíƒœê³„ì™€ ì›í™œížˆ í†µí•©í•  ìˆ˜ ìžˆëŠ” ë¬¸ì„œ ì²˜ë¦¬ APIìž…ë‹ˆë‹¤."

############################# Header ##########################

title: "ë¬¸ì„œë¥¼ Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ê¸°<br>.NET API ì‚¬ìš©"
description: "ì¸ê¸° ë¬¸ì„œ í˜•ì‹ì„ ê¹”ë”í•œ Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ê³  ì™„ì „í•œ ì œì–´ë¥¼ ì œê³µí•˜ëŠ” Markdown ë³€í™˜ API."
words:
  for: "for"

actions:
  main: "ë¬´ë£Œ NuGet ë‹¤ìš´ë¡œë“œ"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "ë¼ì´ì„ ìŠ¤"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "ì‹œìž‘í•  ì¤€ë¹„ê°€ ë˜ì…¨ë‚˜ìš”?"
  description: "GroupDocs.Markdown ê¸°ëŠ¥ì„ ë¬´ë£Œë¡œ ì‚¬ìš©í•´ ë³´ê±°ë‚˜ ë¼ì´ì„ ìŠ¤ë¥¼ ìš”ì²­í•˜ì„¸ìš”"

release:
  hidden: false
  title: "ë²„ì „ {0}&nbsp;ì¶œì‹œ"
  notes: "ìƒˆë¡œìš´ ê¸°ëŠ¥ ë³´ê¸°"
  downloads: "ë‹¤ìš´ë¡œë“œ"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "C#ì—ì„œ PDFë¥¼ Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ê¸°"
  more: "ì¶”ê°€ ì˜ˆì œ"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // ë„¤ìž„ìŠ¤íŽ˜ì´ìŠ¤ ê°€ì ¸ì˜¤ê¸°
    using GroupDocs.Markdown;

    // ë¼ì´ì„ ìŠ¤ ì„¤ì •
    License.Set("GroupDocs.Markdown.lic");

    // ì»¨ë²„í„° ì¸ìŠ¤í„´ìŠ¤í™”
    var converter = new MarkdownConverter("business-plan.pdf");

    // ë³€í™˜í•˜ê³  ì¶œë ¥ Markdown íŒŒì¼ ì €ìž¥
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown í•œëˆˆì— ë³´ê¸°"
  description: ".NET ì• í”Œë¦¬ì¼€ì´ì…˜ì—ì„œ ë¬¸ì„œë¥¼ íŒŒì‹±í•˜ê³  Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ëŠ” API."
  features:
    # feature loop
    - title: "ì •í™•í•˜ê³  ì‹ ë¢°í•  ìˆ˜ ìžˆëŠ” ë³€í™˜"
      content: "êµ¬ì¡°ì  ë¬´ê²°ì„±ì„ ìœ ì§€í•˜ë©´ì„œ ì§€ì›ë˜ëŠ” í˜•ì‹ì„ íš¨ìœ¨ì ìœ¼ë¡œ Markdownìœ¼ë¡œ ë³€í™˜í•©ë‹ˆë‹¤. Windowsì™€ Linuxì—ì„œ .NET Framework 4.6.2+ ë° .NET 6.0ì„ ì§€ì›í•©ë‹ˆë‹¤."

    # feature loop
    - title: "ì§€ì›ë˜ëŠ” ì¸ê¸° í˜•ì‹"
      content: "PDF, Word, Excel, ì „ìžì±…, ì›¹ ë° ì¼ë°˜ í…ìŠ¤íŠ¸ íŒŒì¼ì„ í¬í•¨í•´ ì•”í˜¸ ë³´í˜¸ëœ ë¬¸ì„œê¹Œì§€ Markdownìœ¼ë¡œ ë‚´ë³´ëƒ…ë‹ˆë‹¤."

    # feature loop
    - title: "ë¡œì»¬ ë¨¸ì‹ ì—ì„œ ì‹¤í–‰ë©ë‹ˆë‹¤"
      content: "ë°ì´í„°ë¥¼ ì§ì ‘ ì œì–´í•©ë‹ˆë‹¤ - í´ë¼ìš°ë“œë‚˜ ì¸í„°ë„· ì—°ê²°ì´ í•„ìš” ì—†ëŠ” ì˜¨í”„ë ˆë¯¸ìŠ¤ APIë¥¼ ì œê³µí•©ë‹ˆë‹¤."

############################# Platforms ############################
platforms:
  enable: true
  title: "í”Œëž«í¼ ì§€ì›"
  description: "ë‹¤ìŒ ìš´ì˜ ì²´ì œ, í”„ë ˆìž„ì›Œí¬ ë° íŒ¨í‚¤ì§€ ê´€ë¦¬ìžë¥¼ ì§€ì›í•©ë‹ˆë‹¤."
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
  title: "ì§€ì› íŒŒì¼ í˜•ì‹"
  description: |
    ë‹¤ìŒ íŒŒì¼ í˜•ì‹ì€ Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ê¸°ë¥¼ ì§€ì›í•©ë‹ˆë‹¤.
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
        ### Word ë° Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### ê¸°íƒ€   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Markdown ê¸°ëŠ¥"
  description: "ìš°ë¦¬ ì œí’ˆì„ ë‹ë³´ì´ê²Œ í•˜ëŠ” ê¸°ëŠ¥ë“¤ìž…ë‹ˆë‹¤."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "ì—¬ëŸ¬ ë¬¸ì„œ í˜•ì‹ ë‚´ë³´ë‚´ê¸°"
      content: "ê°€ìž¥ ë§Žì´ ì‚¬ìš©ë˜ëŠ” ë¬¸ì„œ í˜•ì‹ì„ Markdownìœ¼ë¡œ ë³€í™˜í•©ë‹ˆë‹¤(PDF, DOCX, XLSX, EPUB ë“±)."

    # feature loop
    - icon: "advanced_formatting"
      title: "ê³ ê¸‰ Markdown ì„œì‹"
      content: "ì œëª©, ë‹¨ë½, ëª©ë¡, í‘œ, ë§í¬, ì´ë¯¸ì§€, ì¸ìš©ë¬¸ ë° ì½”ë“œ ë¸”ë¡ì´ ì ì ˆí•œ Markdown êµ¬ë¬¸ìœ¼ë¡œ ë‚´ë³´ë‚´ì§‘ë‹ˆë‹¤."

    # feature loop
    - icon: "control_over_images"
      title: "ì´ë¯¸ì§€ì— ëŒ€í•œ ì™„ì „í•œ ì œì–´"
      content: "ì´ë¯¸ì§€ë¥¼ ë‚´ë³´ë‚´ê±°ë‚˜ ì¶œë ¥ Markdown íŒŒì¼ì— ì‚½ìž…í•˜ì—¬ ì œì–´í•˜ì‹­ì‹œì˜¤."

    # feature loop
    - icon: "secure"
      title: "ë¡œì»¬ ë¨¸ì‹ ì—ì„œ ì‹¤í–‰ë©ë‹ˆë‹¤"
      content: "í´ë¼ìš°ë“œë‚˜ ì¸í„°ë„· ì—°ê²°ì´ í•„ìš”í•˜ì§€ ì•ŠìŠµë‹ˆë‹¤. ëª¨ë“  ì²˜ë¦¬ëŠ” ë¡œì»¬ ë¨¸ì‹ ì—ì„œ ìˆ˜í–‰ë©ë‹ˆë‹¤."

    # feature loop
    - icon: "intuitive"
      title: "ì§ê´€ì ì¸ ê³µê°œ API"
      content: "ê°œë°œìžë¥¼ ìœ„í•´ ê°œë°œìžê°€ ì‚¬ëž‘ì„ ë‹´ì•„ ì„¤ê³„í•œ ê°„ë‹¨í•˜ê³  ì§ê´€ì ì¸ ê³µê°œ API."

    # feature loop
    - icon: "cross_platform"
      title: "Windowsì™€ Linuxì—ì„œ ë™ìž‘"
      content: ".NET ë° .NET Framework ì–´ì…ˆë¸”ë¦¬ëŠ” NuGet íŒ¨í‚¤ì§€ ë‚´ì— í¬í•¨ë˜ì–´ ìžˆìŠµë‹ˆë‹¤."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "ì½”ë“œ ìƒ˜í”Œ"
  description: ".NET ì• í”Œë¦¬ì¼€ì´ì…˜ì—ì„œ ë¬¸ì„œë¥¼ Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ëŠ” ê°€ìž¥ ì¼ë°˜ì ì¸ ì‚¬ìš© ì‹œë‚˜ë¦¬ì˜¤ìž…ë‹ˆë‹¤."
  items:
    # code sample loop
    - title: "DOCXë¥¼ Markdownìœ¼ë¡œ ë‚´ë³´ë‚´ê¸°"
      content: "ì´ ì½”ë“œ ìƒ˜í”Œì€ DOCX íŒŒì¼ì„ Markdownìœ¼ë¡œ ë³€í™˜í•˜ê³  ì¶œë ¥ë¬¼ì„ íŒŒì¼ì— ì €ìž¥í•˜ëŠ” ë°©ë²•ì„ ë³´ì—¬ì¤ë‹ˆë‹¤. ì´ë¯¸ì§€ê°€ ì¶œë ¥ íŒŒì¼ì— í¬í•¨ë©ë‹ˆë‹¤."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // ë„¤ìž„ìŠ¤íŽ˜ì´ìŠ¤ ê°€ì ¸ì˜¤ê¸°
            using GroupDocs.Markdown;

            // ë¼ì´ì„ ìŠ¤ ì„¤ì •
            License.Set("GroupDocs.Markdown.lic");

            // ì»¨ë²„í„° ì¸ìŠ¤í„´ìŠ¤í™”
            var converter = new MarkdownConverter("annual-review.docx");

            // ë³€í™˜í•˜ê³  ì¶œë ¥ë¬¼ì„ íŒŒì¼ì— ì €ìž¥
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // ë„¤ìž„ìŠ¤íŽ˜ì´ìŠ¤ ê°€ì ¸ì˜¤ê¸°  
            open GroupDocs.Markdown

            // ë¼ì´ì„ ìŠ¤ ì„¤ì •
            License.Set("GroupDocs.Markdown.lic")

            // ì»¨ë²„í„° ì¸ìŠ¤í„´ìŠ¤í™”
            let converter = new MarkdownConverter("annual-review.docx")

            // ë³€í™˜í•˜ê³  ì¶œë ¥ë¬¼ì„ íŒŒì¼ì— ì €ìž¥
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' ë„¤ìž„ìŠ¤íŽ˜ì´ìŠ¤ ê°€ì ¸ì˜¤ê¸°  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' ë¼ì´ì„ ìŠ¤ ì„¤ì •
                    License.Set("GroupDocs.Markdown.lic")

                    ' ì»¨ë²„í„° ì¸ìŠ¤í„´ìŠ¤í™”
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' ë³€í™˜í•˜ê³  ì¶œë ¥ë¬¼ì„ íŒŒì¼ì— ì €ìž¥
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "ì´ë¯¸ì§€ë¥¼ í´ë”ì— ì €ìž¥"
      content: "ì´ ì½”ë“œ ìƒ˜í”Œì€ DOCX íŒŒì¼ì„ Markdownìœ¼ë¡œ ë³€í™˜í•˜ê³  ì´ë¯¸ì§€ë¥¼ ë³„ë„ì˜ í´ë”ì— ì €ìž¥í•˜ëŠ” ë°©ë²•ì„ ë³´ì—¬ì¤ë‹ˆë‹¤."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // ë„¤ìž„ìŠ¤íŽ˜ì´ìŠ¤ ê°€ì ¸ì˜¤ê¸°
            using GroupDocs.Markdown;

            // ë¼ì´ì„ ìŠ¤ ì„¤ì •
            License.Set("GroupDocs.Markdown.lic");

            // ì»¨ë²„í„° ì¸ìŠ¤í„´ìŠ¤í™”
            var converter = new MarkdownConverter("annual-report.docx");

            // ì´ë¯¸ì§€ ë‚´ë³´ë‚´ê¸° ì „ëžµ ë° ì¶œë ¥ í´ë” ì„¤ì •
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // ë³€í™˜í•˜ê³  ì¶œë ¥ë¬¼ì„ íŒŒì¼ì— ì €ìž¥
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // ë„¤ìž„ìŠ¤íŽ˜ì´ìŠ¤ ê°€ì ¸ì˜¤ê¸°
            open GroupDocs.Markdown

            // ë¼ì´ì„ ìŠ¤ ì„¤ì •
            License.Set("GroupDocs.Markdown.lic")

            // ì»¨ë²„í„° ì¸ìŠ¤í„´ìŠ¤í™”
            let converter = new MarkdownConverter("annual-report.docx")

            // ì´ë¯¸ì§€ ë‚´ë³´ë‚´ê¸° ì „ëžµ ë° ì¶œë ¥ í´ë” ì„¤ì •
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // ë³€í™˜í•˜ê³  ì¶œë ¥ë¬¼ì„ íŒŒì¼ì— ì €ìž¥
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' ë„¤ìž„ìŠ¤íŽ˜ì´ìŠ¤ ê°€ì ¸ì˜¤ê¸°  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' ë¼ì´ì„ ìŠ¤ ì„¤ì •
                    License.Set("GroupDocs.Markdown.lic")

                    ' ì»¨ë²„í„° ì¸ìŠ¤í„´ìŠ¤í™”
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' ì´ë¯¸ì§€ ë‚´ë³´ë‚´ê¸° ì „ëžµ ë° ì¶œë ¥ í´ë” ì„¤ì •
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' ë³€í™˜í•˜ê³  ì¶œë ¥ë¬¼ì„ íŒŒì¼ì— ì €ìž¥
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs ì œí’ˆ ë¦¬ë·°"
# description: "ìš°ë¦¬ì˜ ë§ë§Œ ë¯¿ì§€ ë§ˆì„¸ìš”. ë‹¤ë¥¸ ê°œë°œìžë“¤ì´ ìš°ë¦¬ APIì— ëŒ€í•´ ì–´ë–»ê²Œ ë§í•˜ëŠ”ì§€ í™•ì¸í•´ ë³´ì„¸ìš”."

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "ìš°ìˆ˜í•œ ì„œë¹„ìŠ¤ì™€ ë›°ì–´ë‚œ ì œí’ˆ. GroupDocs.Markdown for .NET êµ¬í˜„ ê³¼ì •ì—ì„œ ë§¤ìš° ë„ì›€ì´ ë˜ì—ˆê³  ë¹ ë¥´ê²Œ ëŒ€ì‘í•´ ì£¼ì—ˆìœ¼ë©°, ê°•ë ¥ížˆ ì¶”ì²œí•©ë‹ˆë‹¤."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "í”„ë¡œì íŠ¸ì— GroupDocs.Markdown for .NETì„ êµ¬í˜„í•˜ê³  ì‚¬ìš©í•œ ê²°ê³¼, ë§¤ìš° ìž˜ ë™ìž‘í•˜ëŠ” ê²ƒìœ¼ë¡œ ë³´ìž…ë‹ˆë‹¤. ë§Žì€ ë¬¸ì„œë¡œ í…ŒìŠ¤íŠ¸í–ˆìœ¼ë©° í˜„ìž¬ê¹Œì§€ ë§Œì¡±ìŠ¤ëŸ½ìŠµë‹ˆë‹¤. Markdown ì¶œë ¥ì€ ê¹”ë”í•˜ê³  ì†ŒìŠ¤ ê°„ì— ì¼ê´€ë©ë‹ˆë‹¤."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

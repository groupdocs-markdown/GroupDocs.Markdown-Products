---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: vi
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

head_title: "Xuáº¥t tÃ i liá»‡u sang Markdown trong .NET | GroupDocs"
head_description: "GroupDocs.Markdown cho .NET lÃ  API xá»­ lÃ½ tÃ i liá»‡u, xuáº¥t PDF, Word, Excel vÃ  cÃ¡c Ä‘á»‹nh dáº¡ng khÃ¡c sang Markdown Ä‘á»ƒ tÃ­ch há»£p liá»n máº¡ch vá»›i há»‡ sinh thÃ¡i AI táº¡o sinh."

############################# Header ##########################

title: "Xuáº¥t tÃ i liá»‡u sang Markdown<br>sá»­ dá»¥ng API .NET"
description: "API chuyá»ƒn Ä‘á»•i Markdown Ä‘á»ƒ xuáº¥t cÃ¡c Ä‘á»‹nh dáº¡ng tÃ i liá»‡u phá»• biáº¿n sang Markdown sáº¡ch sáº½ vá»›i kiá»ƒm soÃ¡t toÃ n diá»‡n."
words:
  for: "for"

actions:
  main: "Táº£i NuGet miá»…n phÃ­"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Cáº¥p phÃ©p"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Sáºµn sÃ ng báº¯t Ä‘áº§u?"
  description: "DÃ¹ng thá»­ cÃ¡c tÃ­nh nÄƒng cá»§a GroupDocs.Markdown miá»…n phÃ­ hoáº·c yÃªu cáº§u giáº¥y phÃ©p"

release:
  hidden: false
  title: "PhiÃªn báº£n {0}&nbsp;Ä‘Ã£ phÃ¡t hÃ nh"
  notes: "Xem nhá»¯ng gÃ¬ má»›i"
  downloads: "Táº£i xuá»‘ng"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Xuáº¥t PDF sang Markdown trong C#"
  more: "ThÃªm vÃ­ dá»¥"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Nháº­p namespace
    using GroupDocs.Markdown;

    // Thiáº¿t láº­p giáº¥y phÃ©p
    License.Set("GroupDocs.Markdown.lic");

    // Khá»Ÿi táº¡o bá»™ chuyá»ƒn Ä‘á»•i
    var converter = new MarkdownConverter("business-plan.pdf");

    // Chuyá»ƒn Ä‘á»•i vÃ  lÆ°u tá»‡p Markdown Ä‘áº§u ra
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown tá»•ng quan"
  description: "API Ä‘á»ƒ phÃ¢n tÃ­ch vÃ  xuáº¥t tÃ i liá»‡u sang Markdown trong cÃ¡c á»©ng dá»¥ng .NET."
  features:
    # feature loop
    - title: "Chuyá»ƒn Ä‘á»•i chÃ­nh xÃ¡c vÃ  Ä‘Ã¡ng tin cáº­y"
      content: "Chuyá»ƒn Ä‘á»•i cÃ¡c Ä‘á»‹nh dáº¡ng há»— trá»£ sang Markdown má»™t cÃ¡ch hiá»‡u quáº£ trong khi duy trÃ¬ tÃ­nh toÃ n váº¹n cáº¥u trÃºc. Há»— trá»£ .NET Framework 4.6.2+ vÃ  .NET 6.0 trÃªn Windows vÃ  Linux."

    # feature loop
    - title: "CÃ¡c Ä‘á»‹nh dáº¡ng phá»• biáº¿n Ä‘Æ°á»£c há»— trá»£"
      content: "Xuáº¥t PDF, Word, Excel, eBooks, Web vÃ  cÃ¡c tá»‡p vÄƒn báº£n thuáº§n sang Markdown, bao gá»“m cÃ¡c tÃ i liá»‡u Ä‘Æ°á»£c báº£o máº­t báº±ng máº­t kháº©u."

    # feature loop
    - title: "Cháº¡y trÃªn mÃ¡y cá»¥c bá»™ cá»§a báº¡n"
      content: "Báº¡n kiá»ƒm soÃ¡t dá»¯ liá»‡u cá»§a mÃ¬nh - chÃºng tÃ´i cung cáº¥p má»™t API on-premise khÃ´ng yÃªu cáº§u báº¥t ká»³ Ä‘Ã¡m mÃ¢y hoáº·c káº¿t ná»‘i internet nÃ o."

############################# Platforms ############################
platforms:
  enable: true
  title: "Há»— trá»£ ná»n táº£ng"
  description: "CÃ¡c há»‡ Ä‘iá»u hÃ nh, framework vÃ  trÃ¬nh quáº£n lÃ½ gÃ³i sau Ä‘Æ°á»£c há»— trá»£."
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
  title: "CÃ¡c Ä‘á»‹nh dáº¡ng tá»‡p Ä‘Æ°á»£c há»— trá»£"
  description: |
    CÃ¡c Ä‘á»‹nh dáº¡ng tá»‡p sau Ä‘Æ°á»£c há»— trá»£ Ä‘á»ƒ xuáº¥t sang Markdown.
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
        ### Word & Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### KhÃ¡c   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "TÃ­nh nÄƒng cá»§a GroupDocs.Markdown"
  description: "ÄÃ¢y lÃ  cÃ¡c tÃ­nh nÄƒng lÃ m cho sáº£n pháº©m cá»§a chÃºng tÃ´i ná»•i báº­t."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Xuáº¥t Ä‘a dáº¡ng Ä‘á»‹nh dáº¡ng tÃ i liá»‡u"
      content: "Chuyá»ƒn Ä‘á»•i háº§u háº¿t cÃ¡c Ä‘á»‹nh dáº¡ng tÃ i liá»‡u phá»• biáº¿n sang Markdown (PDF, DOCX, XLSX, EPUB vÃ  hÆ¡n ná»¯a)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Äá»‹nh dáº¡ng Markdown nÃ¢ng cao"
      content: "TiÃªu Ä‘á», Ä‘oáº¡n vÄƒn, danh sÃ¡ch, báº£ng, liÃªn káº¿t, hÃ¬nh áº£nh, trÃ­ch dáº«n khá»‘i vÃ  khá»‘i mÃ£ Ä‘Æ°á»£c xuáº¥t ra cÃº phÃ¡p Markdown thÃ­ch há»£p."

    # feature loop
    - icon: "control_over_images"
      title: "Kiá»ƒm soÃ¡t toÃ n diá»‡n hÃ¬nh áº£nh"
      content: "Kiá»ƒm soÃ¡t hÃ¬nh áº£nh báº±ng cÃ¡ch xuáº¥t chÃºng hoáº·c nhÃºng vÃ o tá»‡p Markdown Ä‘áº§u ra."

    # feature loop
    - icon: "secure"
      title: "Cháº¡y trÃªn mÃ¡y cá»¥c bá»™ cá»§a báº¡n"
      content: "KhÃ´ng cáº§n káº¿t ná»‘i Ä‘Ã¡m mÃ¢y hoáº·c Internet. Táº¥t cáº£ quÃ¡ trÃ¬nh xá»­ lÃ½ Ä‘á»u Ä‘Æ°á»£c thá»±c hiá»‡n trÃªn mÃ¡y cá»¥c bá»™ cá»§a báº¡n."

    # feature loop
    - icon: "intuitive"
      title: "API cÃ´ng khai trá»±c quan"
      content: "API cÃ´ng khai Ä‘Æ¡n giáº£n vÃ  trá»±c quan, Ä‘Æ°á»£c thiáº¿t káº¿ bá»Ÿi cÃ¡c nhÃ  phÃ¡t triá»ƒn vÃ¬ cÃ¡c nhÃ  phÃ¡t triá»ƒn, vá»›i tÃ¢m huyáº¿t."

    # feature loop
    - icon: "cross_platform"
      title: "Hoáº¡t Ä‘á»™ng trÃªn Windows vÃ  Linux"
      content: ".NET vÃ  cÃ¡c assembly cá»§a .NET Framework Ä‘Æ°á»£c cung cáº¥p trong gÃ³i NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "MÃ£ máº«u"
  description: "CÃ¡c ká»‹ch báº£n sá»­ dá»¥ng phá»• biáº¿n nháº¥t Ä‘á»ƒ xuáº¥t tÃ i liá»‡u sang Markdown trong cÃ¡c á»©ng dá»¥ng .NET."
  items:
    # code sample loop
    - title: "Xuáº¥t DOCX sang Markdown"
      content: "Máº«u mÃ£ nÃ y cho tháº¥y cÃ¡ch chuyá»ƒn Ä‘á»•i tá»‡p DOCX sang Markdown vÃ  lÆ°u káº¿t quáº£ ra tá»‡p. CÃ¡c hÃ¬nh áº£nh Ä‘Æ°á»£c nhÃºng trong tá»‡p káº¿t quáº£."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Nháº­p khÃ´ng gian tÃªn
            using GroupDocs.Markdown;

            // CÃ i Ä‘áº·t giáº¥y phÃ©p
            License.Set("GroupDocs.Markdown.lic");

            // Táº¡o Ä‘á»‘i tÆ°á»£ng chuyá»ƒn Ä‘á»•i
            var converter = new MarkdownConverter("annual-review.docx");

            // Chuyá»ƒn Ä‘á»•i vÃ  lÆ°u káº¿t quáº£ ra tá»‡p
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Nháº­p khÃ´ng gian tÃªn  
            open GroupDocs.Markdown

            // CÃ i Ä‘áº·t giáº¥y phÃ©p
            License.Set("GroupDocs.Markdown.lic")

            // Táº¡o Ä‘á»‘i tÆ°á»£ng chuyá»ƒn Ä‘á»•i
            let converter = new MarkdownConverter("annual-review.docx")

            // Chuyá»ƒn Ä‘á»•i vÃ  lÆ°u káº¿t quáº£ ra tá»‡p
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Nháº­p khÃ´ng gian tÃªn  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' CÃ i Ä‘áº·t giáº¥y phÃ©p
                    License.Set("GroupDocs.Markdown.lic")

                    ' Táº¡o Ä‘á»‘i tÆ°á»£ng chuyá»ƒn Ä‘á»•i
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Chuyá»ƒn Ä‘á»•i vÃ  lÆ°u káº¿t quáº£ ra tá»‡p
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "LÆ°u hÃ¬nh áº£nh vÃ o thÆ° má»¥c"
      content: "Máº«u mÃ£ nÃ y cho tháº¥y cÃ¡ch chuyá»ƒn Ä‘á»•i tá»‡p DOCX sang Markdown vÃ  lÆ°u hÃ¬nh áº£nh vÃ o má»™t thÆ° má»¥c riÃªng."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Nháº­p khÃ´ng gian tÃªn
            using GroupDocs.Markdown;

            // CÃ i Ä‘áº·t giáº¥y phÃ©p
            License.Set("GroupDocs.Markdown.lic");

            // Táº¡o Ä‘á»‘i tÆ°á»£ng chuyá»ƒn Ä‘á»•i
            var converter = new MarkdownConverter("annual-report.docx");

            // CÃ i Ä‘áº·t chiáº¿n lÆ°á»£c xuáº¥t hÃ¬nh áº£nh vÃ  thÆ° má»¥c Ä‘áº§u ra
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Chuyá»ƒn Ä‘á»•i vÃ  lÆ°u káº¿t quáº£ ra tá»‡p
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Nháº­p khÃ´ng gian tÃªn
            open GroupDocs.Markdown

            // CÃ i Ä‘áº·t giáº¥y phÃ©p
            License.Set("GroupDocs.Markdown.lic")

            // Táº¡o Ä‘á»‘i tÆ°á»£ng chuyá»ƒn Ä‘á»•i
            let converter = new MarkdownConverter("annual-report.docx")

            // CÃ i Ä‘áº·t chiáº¿n lÆ°á»£c xuáº¥t hÃ¬nh áº£nh vÃ  thÆ° má»¥c Ä‘áº§u ra
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Chuyá»ƒn Ä‘á»•i vÃ  lÆ°u káº¿t quáº£ ra tá»‡p
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Nháº­p khÃ´ng gian tÃªn  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' CÃ i Ä‘áº·t giáº¥y phÃ©p
                    License.Set("GroupDocs.Markdown.lic")

                    ' Táº¡o Ä‘á»‘i tÆ°á»£ng chuyá»ƒn Ä‘á»•i
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' CÃ i Ä‘áº·t chiáº¿n lÆ°á»£c xuáº¥t hÃ¬nh áº£nh vÃ  thÆ° má»¥c Ä‘áº§u ra
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Chuyá»ƒn Ä‘á»•i vÃ  lÆ°u káº¿t quáº£ ra tá»‡p
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "ÄÃ¡nh giÃ¡ sáº£n pháº©m GroupDocs"
# description: "Äá»«ng chá»‰ tin lá»i chÃºng tÃ´i. HÃ£y xem nhá»¯ng gÃ¬ cÃ¡c nhÃ  phÃ¡t triá»ƒn khÃ¡c nÃ³i vá» cÃ¡c API cá»§a chÃºng tÃ´i"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Dá»‹ch vá»¥ vÃ  sáº£n pháº©m xuáº¥t sáº¯c. Há» Ä‘Ã£ vÃ´ cÃ¹ng há»¯u Ã­ch vÃ  pháº£n há»“i nhanh chÃ³ng trong quÃ¡ trÃ¬nh triá»ƒn khai GroupDocs.Markdown cho .NET, khÃ´ng thá»ƒ khen ngá»£i há» Ä‘á»§ má»©c."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Sau khi triá»ƒn khai vÃ  sá»­ dá»¥ng GroupDocs.Markdown cho .NET trong dá»± Ã¡n, nÃ³ hoáº¡t Ä‘á»™ng ráº¥t tá»‘t. TÃ´i Ä‘Ã£ kiá»ƒm tra vá»›i ráº¥t nhiá»u tÃ i liá»‡u vÃ  cho Ä‘áº¿n nay má»i thá»© Ä‘á»u á»•n. Äáº§u ra Markdown sáº¡ch sáº½ vÃ  nháº¥t quÃ¡n trÃªn má»i nguá»“n."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

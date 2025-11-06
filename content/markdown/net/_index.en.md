---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: en
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

head_title: "Export Documents to Markdown in .NET | GroupDocs"
head_description: "GroupDocs.Markdown for .NET is a document processing API that exports PDF, Word, Excel, and other formats to Markdown for seamless integration with the generative AI ecosystem."

############################# Header ##########################

title: "Export documents to Markdown<br>using .NET API"
description: "Markdown conversion API to export popular document formats to clean Markdown with full control."
words:
  for: "for"

actions:
  main: "Free NuGet Download"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Ready to get started?"
  description: "Try GroupDocs.Markdown features for free or request a license"

release:
  hidden: false
  title: "Version {0}&nbsp;released"
  notes: "See what's new"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Export PDF to Markdown in C#"
  more: "More examples"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Import the namespace
    using GroupDocs.Markdown;

    // Set the license
    License.Set("GroupDocs.Markdown.lic");

    // Instantiate converter
    var converter = new MarkdownConverter("business-plan.pdf");

    // Convert and save output Markdown file
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown at a glance"
  description: "API to parse and export documents to Markdown in .NET applications."
  features:
    # feature loop
    - title: "Accurate and reliable conversion"
      content: "Efficiently convert supported formats to Markdown while maintaining structure integrity. Supports .NET Framework 4.6.2+ and .NET 6.0 on Windows and Linux."

    # feature loop
    - title: "Popular formats supported"
      content: "Export PDF, Word, Excel, eBooks, Web and plain text files to Markdown, including password-protected documents."

    # feature loop
    - title: "Runs on your local machine"
      content: "You control your data - we provide an on-premise API that does not require any cloud or internet connection."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platforms support"
  description: "The following operating systems, frameworks and package managers are supported."
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
  title: "Supported file formats"
  description: |
    The following file formats are supported for export to Markdown.
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
        ### Other   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Markdown features"
  description: "These are the features that make our product stand out."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Export multiple document formats"
      content: "Convert most popular document formats to Markdown (PDF, DOCX, XLSX, EPUB and more)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Advanced Markdown formatting"
      content: "Headings, paragraphs, lists, tables, links, images, blockquotes and code blocks are exported to the appropriate Markdown syntax."

    # feature loop
    - icon: "control_over_images"
      title: "Full control over images"
      content: "Take control over images by exporting them or embedding into the output Markdown file."

    # feature loop
    - icon: "secure"
      title: "Runs on your local machine"
      content: "No cloud or Internet connection required. All processing is done on your local machine."

    # feature loop
    - icon: "intuitive"
      title: "Intuitive public API"
      content: "Simple and intuitive public API designed by developers for developers with love."

    # feature loop
    - icon: "cross_platform"
      title: "Works on Windows and Linux"
      content: ".NET and .NET Framework assemblies are provided within the NuGet package."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Code samples"
  description: "The most common usage scenarios for exporting documents to Markdown in .NET applications."
  items:
    # code sample loop
    - title: "Export DOCX to Markdown"
      content: "This code sample shows how to convert a DOCX file to Markdown and save output to file. The images are embedded in the output file."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Import the namespace
            using GroupDocs.Markdown;

            // Set the license
            License.Set("GroupDocs.Markdown.lic");

            // Instantiate converter
            var converter = new MarkdownConverter("annual-review.docx");

            // Convert and save output to file
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Import the namespace  
            open GroupDocs.Markdown

            // Set the license
            License.Set("GroupDocs.Markdown.lic")

            // Instantiate converter
            let converter = new MarkdownConverter("annual-review.docx")

            // Convert and save output to file
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Import the namespace  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Set the license
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instantiate converter
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Convert and save output to file
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Save images to a folder"
      content: "This code sample shows how to convert a DOCX file to Markdown and save images to a separate folder."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Import the namespace
            using GroupDocs.Markdown;

            // Set the license
            License.Set("GroupDocs.Markdown.lic");

            // Instantiate converter
            var converter = new MarkdownConverter("annual-report.docx");

            // Set image export strategy and output folder
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Convert and save output to file
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Import the namespace
            open GroupDocs.Markdown

            // Set the license
            License.Set("GroupDocs.Markdown.lic")

            // Instantiate converter
            let converter = new MarkdownConverter("annual-report.docx")

            // Set image export strategy and output folder
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Convert and save output to file
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Import the namespace  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Set the license
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instantiate converter
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Set image export strategy and output folder
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Convert and save output to file
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs product reviews"
# description: "Don't just take our word for it. See what other developers say about our APIs"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Excellent service and excellent products. They were extremely helpful and responsive during the GroupDocs.Markdown for .NET implementation process, can’t recommend them highly enough."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "After implementing and using GroupDocs.Markdown for .NET in the project it looks to be working very well. I have tested with a lot of documents and so far so good. The Markdown output is clean and consistent across sources."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

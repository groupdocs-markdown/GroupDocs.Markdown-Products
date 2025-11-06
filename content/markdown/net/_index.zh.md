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

head_title: ".NET 中将文档导出为 Markdown | GroupDocs"
head_description: "GroupDocs.Markdown for .NET 是一款文档处理 API，可将 PDF、Word、Excel 等格式导出为 Markdown，实现与生成式 AI 生态系统的无缝集成。"

############################# Header ##########################

title: "将文档导出为 Markdown<br>使用 .NET API"
description: "Markdown 转换 API，可将流行文档格式导出为干净的 Markdown，提供完整控制。"
words:
  for: "for"

actions:
  main: "免费 NuGet 下载"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "授权"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Markdown 功能或申请授权。"

release:
  hidden: false
  title: "版本 {0}&nbsp;已发布"
  notes: "查看更新内容"
  downloads: "下载"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "在 C# 中将 PDF 导出为 Markdown"
  more: "更多示例"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // 导入命名空间
    using GroupDocs.Markdown;

    // 设置许可证
    License.Set("GroupDocs.Markdown.lic");

    // 实例化转换器
    var converter = new MarkdownConverter("business-plan.pdf");

    // 转换并保存输出的 Markdown 文件
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown 一览"
  description: "在 .NET 应用程序中解析并导出文档为 Markdown 的 API。"
  features:
    # feature loop
    - title: "准确且可靠的转换"
      content: "高效地将受支持的格式转换为 Markdown，同时保持结构完整性。支持 Windows 和 Linux 上的 .NET Framework 4.6.2+ 与 .NET 6.0。"

    # feature loop
    - title: "支持的流行格式"
      content: "将 PDF、Word、Excel、电子书、网页和纯文本文件导出为 Markdown，包括受密码保护的文档。"

    # feature loop
    - title: "在本地机器上运行"
      content: "您掌控您的数据——我们提供的本地 API 无需任何云服务或互联网连接。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台支持"
  description: "支持以下操作系统、框架和包管理器。"
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
  title: "支持的文件格式"
  description: |
    支持以下文件格式导出为 Markdown。
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
        ### Word 与 Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### 其他   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Markdown 功能"
  description: "这些功能使我们的产品脱颖而出。"

  items:
    # feature loop
    - icon: "multi_doc"
      title: "导出多种文档格式"
      content: "将最流行的文档格式转换为 Markdown（PDF、DOCX、XLSX、EPUB 等）。"

    # feature loop
    - icon: "advanced_formatting"
      title: "高级 Markdown 格式化"
      content: "标题、段落、列表、表格、链接、图像、块引用和代码块会导出为相应的 Markdown 语法。"

    # feature loop
    - icon: "control_over_images"
      title: "对图像的完整控制"
      content: "通过导出图像或嵌入到输出的 Markdown 文件中来控制图像。"

    # feature loop
    - icon: "secure"
      title: "在本地机器上运行"
      content: "无需云或互联网连接，所有处理均在本地机器上完成。"

    # feature loop
    - icon: "intuitive"
      title: "直观的公共 API"
      content: "由开发者为开发者设计的简洁直观的公共 API，充满热情。"

    # feature loop
    - icon: "cross_platform"
      title: "支持 Windows 和 Linux"
      content: ".NET 和 .NET Framework 程序集已随 NuGet 包提供。"


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "代码示例"
  description: "在 .NET 应用程序中将文档导出为 Markdown 的最常见使用场景。"
  items:
    # code sample loop
    - title: "将 DOCX 导出为 Markdown"
      content: "此代码示例展示了如何将 DOCX 文件转换为 Markdown 并将输出保存到文件中。图像嵌入在输出文件中。"
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 导入命名空间
            using GroupDocs.Markdown;

            // 设置许可证
            License.Set("GroupDocs.Markdown.lic");

            // 实例化转换器
            var converter = new MarkdownConverter("annual-review.docx");

            // 转换并将输出保存到文件
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // 导入命名空间  
            open GroupDocs.Markdown

            // 设置许可证
            License.Set("GroupDocs.Markdown.lic")

            // 实例化转换器
            let converter = new MarkdownConverter("annual-review.docx")

            // 转换并将输出保存到文件
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' 导入命名空间  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' 设置许可证
                    License.Set("GroupDocs.Markdown.lic")

                    ' 实例化转换器
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' 转换并将输出保存到文件
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "将图像保存到文件夹"
      content: "此代码示例展示了如何将 DOCX 文件转换为 Markdown 并将图像保存到单独的文件夹。"
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 导入命名空间
            using GroupDocs.Markdown;

            // 设置许可证
            License.Set("GroupDocs.Markdown.lic");

            // 实例化转换器
            var converter = new MarkdownConverter("annual-report.docx");

            // 设置图像导出策略和输出文件夹
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // 转换并将输出保存到文件
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // 导入命名空间
            open GroupDocs.Markdown

            // 设置许可证
            License.Set("GroupDocs.Markdown.lic")

            // 实例化转换器
            let converter = new MarkdownConverter("annual-report.docx")

            // 设置图像导出策略和输出文件夹
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // 转换并将输出保存到文件
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' 导入命名空间  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' 设置许可证
                    License.Set("GroupDocs.Markdown.lic")

                    ' 实例化转换器
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' 设置图像导出策略和输出文件夹
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' 转换并将输出保存到文件
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 产品评价"
# description: "不仅仅听我们说，看看其他开发者对我们 API 的评价。"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "优秀的服务和卓越的产品。在 GroupDocs.Markdown for .NET 实施过程中，他们提供了极大的帮助和响应，我对他们赞不绝口。"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "在项目中实现并使用 GroupDocs.Markdown for .NET 后，效果非常好。我已使用大量文档进行测试，迄今为止表现良好。Markdown 输出干净且在各种来源间保持一致。"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

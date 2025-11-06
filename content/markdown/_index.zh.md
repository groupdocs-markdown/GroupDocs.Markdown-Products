---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "导出文档为 Markdown | GroupDocs"
head_description: "GroupDocs.Markdown 是一个文档处理 SDK，可将 PDF、Word、Excel 等格式导出为 Markdown，以便在生成式 AI 生态系统中无缝集成。"

############################# Header ##########################

title: "让您的文档准备好 AI"
description: |
  Markdown SDK，可将各种文档类型导出为清晰、语义化的 Markdown。

  保留文档结构、标题、列表、表格、链接和图像

  通过嵌入图像或保存为外部资源来控制图像。

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "选择您的平台"
  title: "受支持的平台"
  description: "GroupDocs.Markdown 支持以下操作系统和框架。"
  details_link_title: "了解更多"
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
        - content: "30 多种文件格式"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Markdown 功能集"
  description: "这些功能使我们的解决方案脱颖而出。"

  items:
    # feature loop
    - icon: "convert"
      title: "导出文档为 Markdown"
      content: "通过将 PDF、Word、Excel、电子书和文本导出为 Markdown，使其具备 LLM 就绪能力。"

    # feature loop
    - icon: "structure"
      title: "保持文档结构"
      content: "保留文档结构、标题、列表、表格、链接和图像。"

    # feature loop
    - icon: "image"
      title: "控制图像"
      content: "嵌入图像或将其保存为外部资源。在转换过程中替换图像。"
    
    # feature loop
    - icon: "settings"
      title: "转换完整文档或特定页面"
      content: "根据需要转换整个文档或将转换限制为特定页面或工作表。"


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Markdown 代码示例"
  description: "导出文档为 Markdown 的常见使用场景。您可以请求一个[免费临时许可证](https://purchase.groupdocs.com/temporary-license)来在您的环境中测试该产品。"
  items:
    # code sample loop
    - title: "将 PDF 导出为 Markdown"
      content: |
       仅需几行代码，即可从 PDF 文件获取干净的 Markdown 文件。默认情况下，图像会嵌入到输出文件中。
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
            var converter = new MarkdownConverter("business-plan.pdf");

            // 转换并将输出保存到文件
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "将图像保存到文件夹"
      content: |
       此代码示例展示了如何将 DOCX 文件转换为 Markdown，并将图像保存到单独的文件夹。
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

############################# Formats ############################

formats:
  enable: true
  title:  "支持 30 多种文件格式"
  description: "以下文件格式支持导出为 Markdown。"
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "深入的指标和统计洞察"
  description: "深入了解我们关键数据的详细拆解，提供对成就、影响和增长的全面指标和统计洞察。"

  items:
    # metrics loop
    - number: "180+"
      title: "支持的格式"
      content: "将包括 PDF、Word、Excel 和电子书在内的数十种文档和文本格式转换为 Markdown，实现与生成式 AI 生态系统的无缝集成。"
    # metrics loop
    - number: "1.0M"
      title: "受到开发者信赖"
      content: "我们的解决方案已在开发者社区中获得广泛信任和采用，为您的项目提供无缝集成。"

    # metrics loop
    - number: "15+"
      title: "产品"
      content: "我们提供超过 15 种文档处理 SDK，为您的集成带来流畅体验。我们负责处理，让您省心。"
    
    # metrics loop
    - number: "100+"
      title: "满意的客户"
      content: "为全球最具标志性的品牌提供服务。了解为何数百人热爱 GroupDocs 产品！立即加入！"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "我们的满意客户"
  description: "GroupDocs 库被全球知名且卓越的品牌所采用。"

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
  title: "准备好开始了吗？"
  description: "选择您的目标平台，了解更多产品信息。"

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "常见问题与关注点"
  description: "在我们的 FAQ 部分查找常见问题的答案，快速解决您的疑问和关注点。"

  items:
    #  loop
    - question: "我可以在购买前评估 GroupDocs 产品吗？"
      answer: |
        是的！所有 GroupDocs 产品均提供无风险的评估版。我们强烈建议开发者在购买前下载并试用我们的 API，以确保它们能百分百满足您的需求。
    #  loop
    - question: "GroupDocs 是否提供产品演示？"
      answer: |
        不，我们专注于 API 并致力于打造功能最全、最稳定的产品。我们提供完整功能的免费试用，以[临时许可证](https://purchase.groupdocs.com/temporary-license/)的形式，让您自行测试产品。
    #  loop
    - question: "我可以从哪里下载产品？"
      answer: |
        所有产品均可从 NuGet 或 GroupDocs Releases [网站](https://releases.groupdocs.com)下载。    
    #  loop
    - question: "GroupDocs 开发者许可证是按用户计费，还是按指定用户计费？"
      answer: |
        GroupDocs 开发者许可证按用户计费，而不是按指定用户计费。我们理解编程团队成员会随时间变化，且每次更换都更新许可证并不现实。
    #  loop
    - question: "您提供技术支持吗？"
      answer: |
        是的，我们通过产品团队在[免费支持论坛](https://forum.groupdocs.com/c/markdown)和[付费支持服务台](https://helpdesk.groupdocs.com/)提供免费技术支持，以确保您的使用体验顺畅。

############################# Cloud ############################

cloud_links:
  enable: false
  title: "GroupDocs 云 API"
  description: "通过我们的基于云的 REST API，加速任意应用中的文档到 Markdown 的转换。"

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "在您的应用中使用 cURL RESTful API 将 Microsoft Office、PDF 等格式转换为 Markdown。"

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: ".NET 云 SDK，用于通过可配置选项以编程方式将文档转换为 Markdown。"
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "Java 云 SDK，将文档转换为 Markdown 集成到 Java 应用中。"

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs 在线应用"
  description: "在线应用，允许您在浏览器中将常用文件格式转换为 Markdown。"

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "探索免费在线应用，直接将各种文件格式转换为 Markdown（.md）。"

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "基于网页的工具，可在多设备上将 Microsoft Word 文件转换为 Markdown。"

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "使用免费 PDF 转 Markdown 应用在线将 PDF 文件转换为 Markdown。"
---

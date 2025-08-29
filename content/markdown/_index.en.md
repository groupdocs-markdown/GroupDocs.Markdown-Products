---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "Export Documents to Markdown | GroupDocs"
head_description: "GroupDocs.Markdown is a document processing SDK that exports PDF, Word, Excel, and other formats to Markdown for seamless integration with the generative AI ecosystem."

############################# Header ##########################

title: "Make Your Documents AI-Ready"
description: |
  Markdown SDK to export various document types into clean, semantic Markdown.

  Preserve document structure, headings, lists, tables, links, and images

  Take control over images by embedding them or saving as external resources.

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "Choose your platform"
  title: "Supported platforms"
  description: "GroupDocs.Markdown supports the following operating systems and frameworks."
  details_link_title: "Learn more"
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
        - content: "30+ file formats"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Markdown feature set"
  description: "These are the features that make our solution stand out."

  items:
    # feature loop
    - icon: "convert"
      title: "Export documents to Markdown"
      content: "Make your PDF, Word, Excel, eBook and Text LLM-ready by exporting them to Markdown."

    # feature loop
    - icon: "structure"
      title: "Keep document structure"
      content: "Preserve document structure, headings, lists, tables, links, and images."

    # feature loop
    - icon: "image"
      title: "Take control over images"
      content: "Embed images or save them as external resources. Replace images during the conversion process."
    
    # feature loop
    - icon: "settings"
      title: "Convert whole documents or specific pages"
      content: "Convert entire documents or limit conversion to specific pages or worksheets as needed."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Markdown code samples"
  description: "The most common usage scenarios for exporting documents to Markdown. You can request a [free temporary license](https://purchase.groupdocs.com/temporary-license) to test the product in your environment."
  items:
    # code sample loop
    - title: "Export PDF to Markdown"
      content: |
       Get a clean Markdown file from a PDF file in a few lines of code. By default, images are embedded in the output file.
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
            var converter = new MarkdownConverter("business-plan.pdf");

            // Convert and save output to file
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "Save images to a folder"
      content: |
       This code sample shows how to convert a DOCX file to Markdown and save images to a separate folder.
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
            converter.Convert("annual-report.md");
            ```

############################# Formats ############################

formats:
  enable: true
  title:  "30+ file formats supported"
  description: "The following file formats are supported for export to Markdown."
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "In-depth metrics and statistical insights"
  description: "Dive into a detailed breakdown of our key figures, providing comprehensive metrics and statistical insights into our achievements, impact, and growth."

  items:
    # metrics loop
    - number: "180+"
      title: "Supported formats"
      content: "Convert from dozens of document and text formats including PDF, Word, Excel and eBooks to Markdown providing seamless integrations with the gen AI ecosystem."
    # metrics loop
    - number: "1.0M"
      title: "Trusted by developers"
      content: "Our solutions have become trusted and widely adopted in the developer community, providing seamless integration for your projects."

    # metrics loop
    - number: "15+"
      title: "Products"
      content: "We provide more than 15 document processing SDKs, offering smooth experience for your integrations. We process so you can relax."
    
    # metrics loop
    - number: "100+"
      title: "Happy customers"
      content: "Serving the most iconic brands around the globe. Discover why hundreds love GroupDocs products! Join now!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Our happy customers"
  description: "GroupDocs libraries are employed by globally renowned and distinguished brands across the world."

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
  title: "Ready to get started?"
  description: "Choose your targeting platform to learn more about the product."

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "Common questions and concerns"
  description: "Find answers to common inquiries in our FAQ section to quickly address your queries and concerns."

  items:
    #  loop
    - question: "Can I evaluate GroupDocs products prior to purchasing?"
      answer: |
        Yes! All GroupDocs products have a risk-free, evaluation version available. We strongly encourage developers to download and try our APIs before purchasing to ensure that they will fulfill your needs 100%.
    #  loop
    - question: "Does GroupDocs do product demonstrations?"
      answer: |
        No, our focus is on our APIs and making the most functional and stable products possible. We do offer fully functional and free trials in the form of a [temporary license](https://purchase.groupdocs.com/temporary-license/) so you can test out the product for yourself.
    #  loop
    - question: "Where can I download the product?"
      answer: |
        All products are available to download from NuGet or GroupDocs Releases [website](https://releases.groupdocs.com).    
    #  loop
    - question: "Are GroupDocs developer licenses per user, or per named user?"
      answer: |
        GroupDocs Developer licenses are per user, not per named user. We understand that members of a coding team may change over time and that it is not practical to have to update licensing each time that occurs.
    #  loop
    - question: "Do you provide technical support?"
      answer: |
        Yes, we provide free technical support by the product teams at [Free Support Forum](https://forum.groupdocs.com/c/markdown) and [Paid Support Helpdesk](https://helpdesk.groupdocs.com/) to ensure your experience is smooth.

############################# Cloud ############################

cloud_links:
  enable: false
  title: "GroupDocs Cloud APIs"
  description: "Accelerate document-to-Markdown conversion in any application with our cloud-based REST API"

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "Use the cURL RESTful API to convert Microsoft Office, PDF and other formats to Markdown in your applications."

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: ".NET Cloud SDK for programmatic document-to-Markdown conversion with configurable options."
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "Java Cloud SDK to integrate document conversion to Markdown into Java applications."

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs Online Apps"
  description: "Online application allowing you to convert popular file formats to Markdown in a browser."

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "Explore a free online application to convert various file formats directly to Markdown (.md)."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "Web-based tool for converting Microsoft Word files to Markdown across devices."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "Convert PDF files to Markdown online with a free PDF-to-Markdown app."
---

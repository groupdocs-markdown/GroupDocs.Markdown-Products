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

head_title: "Xuất tài liệu sang Markdown trong .NET | GroupDocs"
head_description: "GroupDocs.Markdown cho .NET là API xử lý tài liệu, xuất PDF, Word, Excel và các định dạng khác sang Markdown để tích hợp liền mạch với hệ sinh thái AI tạo sinh."

############################# Header ##########################

title: "Xuất tài liệu sang Markdown<br>sử dụng API .NET"
description: "API chuyển đổi Markdown để xuất các định dạng tài liệu phổ biến sang Markdown sạch sẽ với kiểm soát toàn diện."
words:
  for: "for"

actions:
  main: "Tải NuGet miễn phí"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Sẵn sàng bắt đầu?"
  description: "Dùng thử các tính năng của GroupDocs.Markdown miễn phí hoặc yêu cầu giấy phép"

release:
  hidden: false
  title: "Phiên bản {0}&nbsp;đã phát hành"
  notes: "Xem những gì mới"
  downloads: "Tải xuống"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Xuất PDF sang Markdown trong C#"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Nhập namespace
    using GroupDocs.Markdown;

    // Thiết lập giấy phép
    License.Set("GroupDocs.Markdown.lic");

    // Khởi tạo bộ chuyển đổi
    var converter = new MarkdownConverter("business-plan.pdf");

    // Chuyển đổi và lưu tệp Markdown đầu ra
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown tổng quan"
  description: "API để phân tích và xuất tài liệu sang Markdown trong các ứng dụng .NET."
  features:
    # feature loop
    - title: "Chuyển đổi chính xác và đáng tin cậy"
      content: "Chuyển đổi các định dạng hỗ trợ sang Markdown một cách hiệu quả trong khi duy trì tính toàn vẹn cấu trúc. Hỗ trợ .NET Framework 4.6.2+ và .NET 6.0 trên Windows và Linux."

    # feature loop
    - title: "Các định dạng phổ biến được hỗ trợ"
      content: "Xuất PDF, Word, Excel, eBooks, Web và các tệp văn bản thuần sang Markdown, bao gồm các tài liệu được bảo mật bằng mật khẩu."

    # feature loop
    - title: "Chạy trên máy cục bộ của bạn"
      content: "Bạn kiểm soát dữ liệu của mình - chúng tôi cung cấp một API on-premise không yêu cầu bất kỳ đám mây hoặc kết nối internet nào."

############################# Platforms ############################
platforms:
  enable: true
  title: "Hỗ trợ nền tảng"
  description: "Các hệ điều hành, framework và trình quản lý gói sau được hỗ trợ."
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
  title: "Các định dạng tệp được hỗ trợ"
  description: |
    Các định dạng tệp sau được hỗ trợ để xuất sang Markdown.
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
        ### Khác   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "Tính năng của GroupDocs.Markdown"
  description: "Đây là các tính năng làm cho sản phẩm của chúng tôi nổi bật."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Xuất đa dạng định dạng tài liệu"
      content: "Chuyển đổi hầu hết các định dạng tài liệu phổ biến sang Markdown (PDF, DOCX, XLSX, EPUB và hơn nữa)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Định dạng Markdown nâng cao"
      content: "Tiêu đề, đoạn văn, danh sách, bảng, liên kết, hình ảnh, trích dẫn khối và khối mã được xuất ra cú pháp Markdown thích hợp."

    # feature loop
    - icon: "control_over_images"
      title: "Kiểm soát toàn diện hình ảnh"
      content: "Kiểm soát hình ảnh bằng cách xuất chúng hoặc nhúng vào tệp Markdown đầu ra."

    # feature loop
    - icon: "secure"
      title: "Chạy trên máy cục bộ của bạn"
      content: "Không cần kết nối đám mây hoặc Internet. Tất cả quá trình xử lý đều được thực hiện trên máy cục bộ của bạn."

    # feature loop
    - icon: "intuitive"
      title: "API công khai trực quan"
      content: "API công khai đơn giản và trực quan, được thiết kế bởi các nhà phát triển vì các nhà phát triển, với tâm huyết."

    # feature loop
    - icon: "cross_platform"
      title: "Hoạt động trên Windows và Linux"
      content: ".NET và các assembly của .NET Framework được cung cấp trong gói NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Mã mẫu"
  description: "Các kịch bản sử dụng phổ biến nhất để xuất tài liệu sang Markdown trong các ứng dụng .NET."
  items:
    # code sample loop
    - title: "Xuất DOCX sang Markdown"
      content: "Mẫu mã này cho thấy cách chuyển đổi tệp DOCX sang Markdown và lưu kết quả ra tệp. Các hình ảnh được nhúng trong tệp kết quả."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Nhập không gian tên
            using GroupDocs.Markdown;

            // Cài đặt giấy phép
            License.Set("GroupDocs.Markdown.lic");

            // Tạo đối tượng chuyển đổi
            var converter = new MarkdownConverter("annual-review.docx");

            // Chuyển đổi và lưu kết quả ra tệp
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Nhập không gian tên  
            open GroupDocs.Markdown

            // Cài đặt giấy phép
            License.Set("GroupDocs.Markdown.lic")

            // Tạo đối tượng chuyển đổi
            let converter = new MarkdownConverter("annual-review.docx")

            // Chuyển đổi và lưu kết quả ra tệp
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Nhập không gian tên  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Cài đặt giấy phép
                    License.Set("GroupDocs.Markdown.lic")

                    ' Tạo đối tượng chuyển đổi
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Chuyển đổi và lưu kết quả ra tệp
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Lưu hình ảnh vào thư mục"
      content: "Mẫu mã này cho thấy cách chuyển đổi tệp DOCX sang Markdown và lưu hình ảnh vào một thư mục riêng."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Nhập không gian tên
            using GroupDocs.Markdown;

            // Cài đặt giấy phép
            License.Set("GroupDocs.Markdown.lic");

            // Tạo đối tượng chuyển đổi
            var converter = new MarkdownConverter("annual-report.docx");

            // Cài đặt chiến lược xuất hình ảnh và thư mục đầu ra
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Chuyển đổi và lưu kết quả ra tệp
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Nhập không gian tên
            open GroupDocs.Markdown

            // Cài đặt giấy phép
            License.Set("GroupDocs.Markdown.lic")

            // Tạo đối tượng chuyển đổi
            let converter = new MarkdownConverter("annual-report.docx")

            // Cài đặt chiến lược xuất hình ảnh và thư mục đầu ra
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Chuyển đổi và lưu kết quả ra tệp
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Nhập không gian tên  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Cài đặt giấy phép
                    License.Set("GroupDocs.Markdown.lic")

                    ' Tạo đối tượng chuyển đổi
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Cài đặt chiến lược xuất hình ảnh và thư mục đầu ra
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Chuyển đổi và lưu kết quả ra tệp
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "Đánh giá sản phẩm GroupDocs"
# description: "Đừng chỉ tin lời chúng tôi. Hãy xem những gì các nhà phát triển khác nói về các API của chúng tôi"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Dịch vụ và sản phẩm xuất sắc. Họ đã vô cùng hữu ích và phản hồi nhanh chóng trong quá trình triển khai GroupDocs.Markdown cho .NET, không thể khen ngợi họ đủ mức."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Sau khi triển khai và sử dụng GroupDocs.Markdown cho .NET trong dự án, nó hoạt động rất tốt. Tôi đã kiểm tra với rất nhiều tài liệu và cho đến nay mọi thứ đều ổn. Đầu ra Markdown sạch sẽ và nhất quán trên mọi nguồn."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "Xuất tài liệu sang Markdown | GroupDocs"
head_description: "GroupDocs.Markdown là SDK xử lý tài liệu cho phép xuất PDF, Word, Excel và các định dạng khác sang Markdown để tích hợp liền mạch với hệ sinh thái AI sinh tạo."

############################# Header ##########################

title: "Chuẩn bị tài liệu của bạn cho AI"
description: |
  SDK Markdown để xuất các loại tài liệu khác nhau thành Markdown sạch, có ngữ nghĩa.

  Bảo tồn cấu trúc tài liệu, tiêu đề, danh sách, bảng, liên kết và hình ảnh

  Kiểm soát hình ảnh bằng cách nhúng chúng hoặc lưu dưới dạng tài nguyên bên ngoài.

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "Chọn nền tảng của bạn"
  title: "Các nền tảng được hỗ trợ"
  description: "GroupDocs.Markdown hỗ trợ các hệ điều hành và framework sau."
  details_link_title: "Tìm hiểu thêm"
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
        - content: "Hơn 30 định dạng tệp"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "Bộ tính năng của GroupDocs.Markdown"
  description: "Đây là những tính năng khiến giải pháp của chúng tôi nổi bật."

  items:
    # feature loop
    - icon: "convert"
      title: "Xuất tài liệu sang Markdown"
      content: "Chuẩn bị PDF, Word, Excel, eBook và văn bản của bạn cho LLM bằng cách xuất chúng sang Markdown."

    # feature loop
    - icon: "structure"
      title: "Giữ cấu trúc tài liệu"
      content: "Bảo tồn cấu trúc tài liệu, tiêu đề, danh sách, bảng, liên kết và hình ảnh."

    # feature loop
    - icon: "image"
      title: "Kiểm soát hình ảnh"
      content: "Nhúng hình ảnh hoặc lưu chúng dưới dạng tài nguyên bên ngoài. Thay thế hình ảnh trong quá trình chuyển đổi."
    
    # feature loop
    - icon: "settings"
      title: "Chuyển đổi toàn bộ tài liệu hoặc các trang cụ thể"
      content: "Chuyển đổi toàn bộ tài liệu hoặc giới hạn chuyển đổi chỉ các trang hoặc bảng tính cụ thể theo nhu cầu."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã GroupDocs.Markdown"
  description: "Các kịch bản sử dụng phổ biến nhất để xuất tài liệu sang Markdown. Bạn có thể yêu cầu một [giấy phép tạm thời miễn phí](https://purchase.groupdocs.com/temporary-license) để thử sản phẩm trong môi trường của mình."
  items:
    # code sample loop
    - title: "Xuất PDF sang Markdown"
      content: |
       Tạo tệp Markdown sạch từ tệp PDF chỉ trong vài dòng mã. Theo mặc định, hình ảnh được nhúng trong tệp đầu ra.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Nhập namespace
            using GroupDocs.Markdown;

            // Đặt giấy phép
            License.Set("GroupDocs.Markdown.lic");

            // Khởi tạo bộ chuyển đổi
            var converter = new MarkdownConverter("business-plan.pdf");

            // Chuyển đổi và lưu đầu ra vào tệp
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "Lưu hình ảnh vào thư mục"
      content: |
       Mẫu mã này cho thấy cách chuyển đổi tệp DOCX sang Markdown và lưu hình ảnh vào một thư mục riêng.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Nhập không gian tên
            using GroupDocs.Markdown;

            // Thiết lập giấy phép
            License.Set("GroupDocs.Markdown.lic");

            // Khởi tạo bộ chuyển đổi
            var converter = new MarkdownConverter("annual-report.docx");

            // Thiết lập chiến lược xuất hình ảnh và thư mục đầu ra
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Chuyển đổi và lưu kết quả vào tệp
            converter.Convert("annual-report.md", convertOptions);
            ```

############################# Formats ############################

formats:
  enable: true
  title:  "Hơn 30 định dạng tệp được hỗ trợ"
  description: "Các định dạng tệp sau được hỗ trợ để xuất sang Markdown."
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "Số liệu chi tiết và những hiểu biết thống kê"
  description: "Khám phá phân tích chi tiết các chỉ số chính của chúng tôi, cung cấp số liệu toàn diện và những hiểu biết thống kê về thành tựu, tác động và sự tăng trưởng."

  items:
    # metrics loop
    - number: "180+"
      title: "Định dạng được hỗ trợ"
      content: "Chuyển đổi từ hàng chục định dạng tài liệu và văn bản, bao gồm PDF, Word, Excel và eBook, sang Markdown, cung cấp tích hợp liền mạch với hệ sinh thái gen AI."
    # metrics loop
    - number: "1.0M"
      title: "Được các nhà phát triển tin tưởng"
      content: "Các giải pháp của chúng tôi đã trở nên đáng tin cậy và được cộng đồng nhà phát triển áp dụng rộng rãi, mang lại tích hợp liền mạch cho dự án của bạn."

    # metrics loop
    - number: "15+"
      title: "Sản phẩm"
      content: "Chúng tôi cung cấp hơn 15 SDK xử lý tài liệu, mang lại trải nghiệm mượt mà cho việc tích hợp của bạn. Chúng tôi xử lý, bạn cứ yên tâm."
    
    # metrics loop
    - number: "100+"
      title: "Khách hàng hài lòng"
      content: "Phục vụ những thương hiệu mang tính biểu tượng nhất trên toàn cầu. Khám phá lý do hàng trăm người yêu thích sản phẩm của GroupDocs! Tham gia ngay!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Khách hàng hài lòng của chúng tôi"
  description: "Các thư viện GroupDocs được các thương hiệu danh tiếng và nổi bật trên toàn thế giới sử dụng."

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
  title: "Sẵn sàng bắt đầu?"
  description: "Chọn nền tảng mục tiêu của bạn để tìm hiểu thêm về sản phẩm."

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "Câu hỏi và quan ngại thường gặp"
  description: "Tìm câu trả lời cho các thắc mắc thường gặp trong mục FAQ của chúng tôi để nhanh chóng giải quyết câu hỏi và lo ngại của bạn."

  items:
    #  loop
    - question: "Tôi có thể đánh giá sản phẩm GroupDocs trước khi mua không?"
      answer: |
        Có! Tất cả sản phẩm của GroupDocs đều có phiên bản đánh giá không rủi ro có sẵn. Chúng tôi khuyến khích các nhà phát triển tải xuống và thử nghiệm API của chúng tôi trước khi mua để đảm bảo chúng đáp ứng đầy đủ nhu cầu của bạn 100%.
    #  loop
    - question: "GroupDocs có thực hiện demo sản phẩm không?"
      answer: |
        Không, chúng tôi tập trung vào API và tạo ra các sản phẩm chức năng và ổn định nhất có thể. Chúng tôi cung cấp các bản dùng thử đầy đủ chức năng và miễn phí dưới dạng một [giấy phép tạm thời](https://purchase.groupdocs.com/temporary-license/) để bạn tự mình kiểm tra sản phẩm.
    #  loop
    - question: "Tôi có thể tải sản phẩm ở đâu?"
      answer: |
        Tất cả các sản phẩm đều có thể tải xuống từ NuGet hoặc GroupDocs Releases [trang web](https://releases.groupdocs.com).    
    #  loop
    - question: "Giấy phép cho nhà phát triển GroupDocs tính theo người dùng hay theo người dùng được đặt tên?"
      answer: |
        Giấy phép nhà phát triển GroupDocs được tính theo người dùng, không phải theo người dùng được đặt tên. Chúng tôi hiểu rằng các thành viên trong nhóm lập trình có thể thay đổi theo thời gian và việc phải cập nhật giấy phép mỗi khi điều đó xảy ra là không thực tế.
    #  loop
    - question: "Bạn có cung cấp hỗ trợ kỹ thuật không?"
      answer: |
        Có, chúng tôi cung cấp hỗ trợ kỹ thuật miễn phí bởi các nhóm sản phẩm tại [Diễn đàn Hỗ trợ Miễn phí](https://forum.groupdocs.com/c/markdown) và [Bàn trợ giúp Hỗ trợ Trả phí](https://helpdesk.groupdocs.com/) để đảm bảo trải nghiệm của bạn luôn suôn sẻ.

############################# Cloud ############################

cloud_links:
  enable: false
  title: "API Đám mây GroupDocs"
  description: "Tăng tốc chuyển đổi tài liệu sang Markdown trong bất kỳ ứng dụng nào với API REST dựa trên đám mây của chúng tôi."

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "Sử dụng API RESTful cURL để chuyển đổi Microsoft Office, PDF và các định dạng khác sang Markdown trong ứng dụng của bạn."

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: "SDK Đám mây .NET để chuyển đổi tài liệu sang Markdown một cách lập trình với các tùy chọn có thể cấu hình."
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "SDK Đám mây Java để tích hợp chuyển đổi tài liệu sang Markdown vào các ứng dụng Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Ứng dụng Trực tuyến GroupDocs"
  description: "Ứng dụng trực tuyến cho phép bạn chuyển đổi các định dạng tệp phổ biến sang Markdown trong trình duyệt."

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "Khám phá ứng dụng trực tuyến miễn phí để chuyển đổi nhiều định dạng tệp trực tiếp sang Markdown (.md)."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "Công cụ dựa trên web để chuyển đổi tệp Microsoft Word sang Markdown trên mọi thiết bị."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "Chuyển đổi tệp PDF sang Markdown trực tuyến với ứng dụng PDF-to-Markdown miễn phí."
---

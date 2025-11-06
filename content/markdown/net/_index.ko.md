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

head_title: ".NET에서 문서를 Markdown으로 내보내기 | GroupDocs"
head_description: "GroupDocs.Markdown for .NET은 PDF, Word, Excel 등 다양한 형식을 Markdown으로 내보내어 생성 AI 생태계와 원활히 통합할 수 있는 문서 처리 API입니다."

############################# Header ##########################

title: "문서를 Markdown으로 내보내기<br>.NET API 사용"
description: "인기 문서 형식을 깔끔한 Markdown으로 내보내고 완전한 제어를 제공하는 Markdown 변환 API."
words:
  for: "for"

actions:
  main: "무료 NuGet 다운로드"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "라이선스"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Markdown 기능을 무료로 사용해 보거나 라이선스를 요청하세요"

release:
  hidden: false
  title: "버전 {0}&nbsp;출시"
  notes: "새로운 기능 보기"
  downloads: "다운로드"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "C#에서 PDF를 Markdown으로 내보내기"
  more: "추가 예제"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // 네임스페이스 가져오기
    using GroupDocs.Markdown;

    // 라이선스 설정
    License.Set("GroupDocs.Markdown.lic");

    // 컨버터 인스턴스화
    var converter = new MarkdownConverter("business-plan.pdf");

    // 변환하고 출력 Markdown 파일 저장
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown 한눈에 보기"
  description: ".NET 애플리케이션에서 문서를 파싱하고 Markdown으로 내보내는 API."
  features:
    # feature loop
    - title: "정확하고 신뢰할 수 있는 변환"
      content: "구조적 무결성을 유지하면서 지원되는 형식을 효율적으로 Markdown으로 변환합니다. Windows와 Linux에서 .NET Framework 4.6.2+ 및 .NET 6.0을 지원합니다."

    # feature loop
    - title: "지원되는 인기 형식"
      content: "PDF, Word, Excel, 전자책, 웹 및 일반 텍스트 파일을 포함해 암호 보호된 문서까지 Markdown으로 내보냅니다."

    # feature loop
    - title: "로컬 머신에서 실행됩니다"
      content: "데이터를 직접 제어합니다 - 클라우드나 인터넷 연결이 필요 없는 온프레미스 API를 제공합니다."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 지원"
  description: "다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다."
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
  title: "지원 파일 형식"
  description: |
    다음 파일 형식은 Markdown으로 내보내기를 지원합니다.
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
        ### Word 및 Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### 기타   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Markdown 기능"
  description: "우리 제품을 돋보이게 하는 기능들입니다."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "여러 문서 형식 내보내기"
      content: "가장 많이 사용되는 문서 형식을 Markdown으로 변환합니다(PDF, DOCX, XLSX, EPUB 등)."

    # feature loop
    - icon: "advanced_formatting"
      title: "고급 Markdown 서식"
      content: "제목, 단락, 목록, 표, 링크, 이미지, 인용문 및 코드 블록이 적절한 Markdown 구문으로 내보내집니다."

    # feature loop
    - icon: "control_over_images"
      title: "이미지에 대한 완전한 제어"
      content: "이미지를 내보내거나 출력 Markdown 파일에 삽입하여 제어하십시오."

    # feature loop
    - icon: "secure"
      title: "로컬 머신에서 실행됩니다"
      content: "클라우드나 인터넷 연결이 필요하지 않습니다. 모든 처리는 로컬 머신에서 수행됩니다."

    # feature loop
    - icon: "intuitive"
      title: "직관적인 공개 API"
      content: "개발자를 위해 개발자가 사랑을 담아 설계한 간단하고 직관적인 공개 API."

    # feature loop
    - icon: "cross_platform"
      title: "Windows와 Linux에서 동작"
      content: ".NET 및 .NET Framework 어셈블리는 NuGet 패키지 내에 포함되어 있습니다."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "코드 샘플"
  description: ".NET 애플리케이션에서 문서를 Markdown으로 내보내는 가장 일반적인 사용 시나리오입니다."
  items:
    # code sample loop
    - title: "DOCX를 Markdown으로 내보내기"
      content: "이 코드 샘플은 DOCX 파일을 Markdown으로 변환하고 출력물을 파일에 저장하는 방법을 보여줍니다. 이미지가 출력 파일에 포함됩니다."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 네임스페이스 가져오기
            using GroupDocs.Markdown;

            // 라이선스 설정
            License.Set("GroupDocs.Markdown.lic");

            // 컨버터 인스턴스화
            var converter = new MarkdownConverter("annual-review.docx");

            // 변환하고 출력물을 파일에 저장
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // 네임스페이스 가져오기  
            open GroupDocs.Markdown

            // 라이선스 설정
            License.Set("GroupDocs.Markdown.lic")

            // 컨버터 인스턴스화
            let converter = new MarkdownConverter("annual-review.docx")

            // 변환하고 출력물을 파일에 저장
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' 네임스페이스 가져오기  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' 라이선스 설정
                    License.Set("GroupDocs.Markdown.lic")

                    ' 컨버터 인스턴스화
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' 변환하고 출력물을 파일에 저장
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "이미지를 폴더에 저장"
      content: "이 코드 샘플은 DOCX 파일을 Markdown으로 변환하고 이미지를 별도의 폴더에 저장하는 방법을 보여줍니다."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 네임스페이스 가져오기
            using GroupDocs.Markdown;

            // 라이선스 설정
            License.Set("GroupDocs.Markdown.lic");

            // 컨버터 인스턴스화
            var converter = new MarkdownConverter("annual-report.docx");

            // 이미지 내보내기 전략 및 출력 폴더 설정
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // 변환하고 출력물을 파일에 저장
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // 네임스페이스 가져오기
            open GroupDocs.Markdown

            // 라이선스 설정
            License.Set("GroupDocs.Markdown.lic")

            // 컨버터 인스턴스화
            let converter = new MarkdownConverter("annual-report.docx")

            // 이미지 내보내기 전략 및 출력 폴더 설정
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // 변환하고 출력물을 파일에 저장
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' 네임스페이스 가져오기  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' 라이선스 설정
                    License.Set("GroupDocs.Markdown.lic")

                    ' 컨버터 인스턴스화
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' 이미지 내보내기 전략 및 출력 폴더 설정
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' 변환하고 출력물을 파일에 저장
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 제품 리뷰"
# description: "우리의 말만 믿지 마세요. 다른 개발자들이 우리 API에 대해 어떻게 말하는지 확인해 보세요."

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "우수한 서비스와 뛰어난 제품. GroupDocs.Markdown for .NET 구현 과정에서 매우 도움이 되었고 빠르게 대응해 주었으며, 강력히 추천합니다."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "프로젝트에 GroupDocs.Markdown for .NET을 구현하고 사용한 결과, 매우 잘 동작하는 것으로 보입니다. 많은 문서로 테스트했으며 현재까지 만족스럽습니다. Markdown 출력은 깔끔하고 소스 간에 일관됩니다."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

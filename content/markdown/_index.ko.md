---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "문서를 Markdown으로 내보내기 | GroupDocs"
head_description: "GroupDocs.Markdown은 PDF, Word, Excel 및 기타 형식을 Markdown으로 내보내어 생성 AI 생태계와 원활하게 통합할 수 있는 문서 처리 SDK입니다."

############################# Header ##########################

title: "문서를 AI 준비 상태로 만들기"
description: |
  다양한 문서 유형을 깔끔하고 의미론적인 Markdown으로 내보내는 Markdown SDK.

  문서 구조, 제목, 목록, 표, 링크 및 이미지를 보존합니다

  이미지를 임베드하거나 외부 리소스로 저장하여 제어합니다.

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "플랫폼 선택"
  title: "지원되는 플랫폼"
  description: "GroupDocs.Markdown은 다음 운영 체제 및 프레임워크를 지원합니다."
  details_link_title: "자세히 알아보기"
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
        - content: "30개 이상의 파일 형식"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Markdown 기능 세트"
  description: "우리 솔루션을 돋보이게 하는 기능들입니다."

  items:
    # feature loop
    - icon: "convert"
      title: "문서를 Markdown으로 내보내기"
      content: "PDF, Word, Excel, 전자책 및 텍스트를 Markdown으로 내보내 LLM 준비 상태로 만드세요."

    # feature loop
    - icon: "structure"
      title: "문서 구조 유지"
      content: "문서 구조, 제목, 목록, 표, 링크 및 이미지를 보존합니다."

    # feature loop
    - icon: "image"
      title: "이미지 제어"
      content: "이미지를 임베드하거나 외부 리소스로 저장합니다. 변환 과정에서 이미지를 교체할 수 있습니다."
    
    # feature loop
    - icon: "settings"
      title: "전체 문서 혹은 특정 페이지 변환"
      content: "전체 문서를 변환하거나 필요에 따라 특정 페이지 또는 워크시트로 변환 범위를 제한합니다."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Markdown 코드 샘플"
  description: "문서를 Markdown으로 내보내는 가장 일반적인 사용 시나리오입니다. 환경에서 제품을 테스트하려면 [무료 임시 라이선스](https://purchase.groupdocs.com/temporary-license)를 요청할 수 있습니다."
  items:
    # code sample loop
    - title: "PDF를 Markdown으로 내보내기"
      content: |
       몇 줄의 코드로 PDF 파일에서 깔끔한 Markdown 파일을 얻을 수 있습니다. 기본적으로 이미지는 출력 파일에 임베드됩니다.
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
            var converter = new MarkdownConverter("business-plan.pdf");

            // 변환하고 출력을 파일에 저장
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "이미지를 폴더에 저장"
      content: |
       이 코드 샘플은 DOCX 파일을 Markdown으로 변환하고 이미지를 별도의 폴더에 저장하는 방법을 보여줍니다.
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

            // 변환하고 출력을 파일에 저장
            converter.Convert("annual-report.md", convertOptions);
            ```

############################# Formats ############################

formats:
  enable: true
  title:  "30개 이상의 파일 형식 지원"
  description: "다음 파일 형식은 Markdown으로 내보내기를 지원합니다."
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "심층 메트릭 및 통계 인사이트"
  description: "우리의 주요 수치를 상세히 분석하여 성과, 영향 및 성장에 대한 포괄적인 메트릭과 통계 인사이트를 제공합니다."

  items:
    # metrics loop
    - number: "180+"
      title: "지원되는 형식"
      content: "PDF, Word, Excel 및 eBook을 포함한 수십 개의 문서 및 텍스트 형식에서 Markdown으로 변환하여 gen AI 생태계와 원활하게 통합합니다."
    # metrics loop
    - number: "1.0M"
      title: "개발자에게 신뢰받는"
      content: "당사의 솔루션은 개발자 커뮤니티에서 신뢰받으며 널리 채택되어 프로젝트에 원활한 통합을 제공합니다."

    # metrics loop
    - number: "15+"
      title: "제품"
      content: "우리는 15개 이상의 문서 처리 SDK를 제공하여 통합 시 원활한 경험을 제공합니다. 우리가 처리하니 안심하세요."
    
    # metrics loop
    - number: "100+"
      title: "만족하는 고객"
      content: "전 세계 최고의 아이코닉 브랜드에 서비스를 제공하고 있습니다. 수백 명이 GroupDocs 제품을 사랑하는 이유를 확인해 보세요! 지금 가입하세요!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "우리의 만족하는 고객"
  description: "GroupDocs 라이브러리는 전 세계적으로 유명하고 뛰어난 브랜드에서 사용되고 있습니다."

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
  title: "시작할 준비가 되셨나요?"
  description: "대상 플랫폼을 선택하여 제품에 대해 자세히 알아보세요."

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "자주 묻는 질문 및 우려사항"
  description: "FAQ 섹션에서 일반적인 문의에 대한 답변을 찾아 빠르게 질문과 우려를 해결하세요."

  items:
    #  loop
    - question: "구매 전에 GroupDocs 제품을 평가할 수 있나요?"
      answer: |
        네! 모든 GroupDocs 제품은 위험이 없는 평가 버전을 제공합니다. 개발자들이 구매 전에 API를 다운로드하고 직접 사용해 보며 요구 사항을 100% 충족하는지 확인하시길 강력히 권장합니다.
    #  loop
    - question: "GroupDocs가 제품 데모를 제공하나요?"
      answer: |
        아니요, 우리의 초점은 API와 가능한 가장 기능적이고 안정적인 제품을 만드는 것입니다. 우리는 제품을 직접 테스트해볼 수 있도록 [임시 라이선스](https://purchase.groupdocs.com/temporary-license/) 형태의 완전 기능 무료 체험을 제공합니다.
    #  loop
    - question: "제품을 어디서 다운로드할 수 있나요?"
      answer: |
        모든 제품은 NuGet 또는 GroupDocs Releases [웹사이트](https://releases.groupdocs.com)에서 다운로드할 수 있습니다.    
    #  loop
    - question: "GroupDocs 개발자 라이선스는 사용자당인가요, 아니면 지정 사용자당인가요?"
      answer: |
        GroupDocs 개발자 라이선스는 사용자당이며, 지정 사용자당이 아닙니다. 코딩 팀의 구성원이 시간이 지나면서 변할 수 있음을 이해하며, 매번 라이선스를 업데이트하는 것이 현실적이지 않다는 점을 고려합니다.
    #  loop
    - question: "기술 지원을 제공합니까?"
      answer: |
        예, 제품 팀이 [무료 지원 포럼](https://forum.groupdocs.com/c/markdown) 및 [유료 지원 헬프데스크](https://helpdesk.groupdocs.com/)를 통해 무료 기술 지원을 제공하여 원활한 경험을 보장합니다.

############################# Cloud ############################

cloud_links:
  enable: false
  title: "GroupDocs Cloud API"
  description: "클라우드 기반 REST API를 사용하여 모든 애플리케이션에서 문서를 Markdown으로 변환하는 속도를 높입니다."

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "cURL RESTful API를 사용하여 Microsoft Office, PDF 및 기타 형식을 애플리케이션에서 Markdown으로 변환합니다."

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: ".NET Cloud SDK를 사용하여 구성 가능한 옵션으로 프로그래밍 방식 문서를 Markdown으로 변환합니다."
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "Java Cloud SDK를 사용하여 Java 애플리케이션에 문서 변환을 Markdown으로 통합합니다."

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs 온라인 앱"
  description: "브라우저에서 인기 있는 파일 형식을 Markdown으로 변환할 수 있는 온라인 애플리케이션입니다."

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "다양한 파일 형식을 직접 Markdown(.md)으로 변환하는 무료 온라인 애플리케이션을 살펴보세요."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "다양한 디바이스에서 Microsoft Word 파일을 Markdown으로 변환하는 웹 기반 도구입니다."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "무료 PDF-to-Markdown 앱으로 PDF 파일을 온라인에서 Markdown으로 변환합니다."
---

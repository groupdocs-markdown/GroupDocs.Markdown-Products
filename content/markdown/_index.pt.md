---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "Exportar documentos para Markdown | GroupDocs"
head_description: "GroupDocs.Markdown Ã© um SDK de processamento de documentos que exporta PDF, Word, Excel e outros formatos para Markdown, permitindo integraÃ§Ã£o perfeita com o ecossistema de IA generativa."

############################# Header ##########################

title: "Prepare seus documentos para IA"
description: |
  SDK Markdown para exportar vÃ¡rios tipos de documentos em Markdown limpo e semÃ¢ntico.

  Preserve a estrutura do documento, tÃ­tulos, listas, tabelas, links e imagens

  Tenha controle sobre as imagens incorporando-as ou salvando-as como recursos externos.

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "Escolha sua plataforma"
  title: "Plataformas suportadas"
  description: "GroupDocs.Markdown suporta os seguintes sistemas operacionais e frameworks."
  details_link_title: "Saiba mais"
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
        - content: "Mais de 30 formatos de arquivo"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "Conjunto de recursos do GroupDocs.Markdown"
  description: "Estes sÃ£o os recursos que fazem nossa soluÃ§Ã£o se destacar."

  items:
    # feature loop
    - icon: "convert"
      title: "Exportar documentos para Markdown"
      content: "Prepare seus PDFs, Word, Excel, eBooks e textos para LLM exportando-os para Markdown."

    # feature loop
    - icon: "structure"
      title: "Manter a estrutura do documento"
      content: "Preserve a estrutura do documento, tÃ­tulos, listas, tabelas, links e imagens."

    # feature loop
    - icon: "image"
      title: "Tenha controle sobre as imagens"
      content: "Incorpore imagens ou salve-as como recursos externos. Substitua imagens durante o processo de conversÃ£o."
    
    # feature loop
    - icon: "settings"
      title: "Converter documentos inteiros ou pÃ¡ginas especÃ­ficas"
      content: "Converta documentos inteiros ou limite a conversÃ£o a pÃ¡ginas ou planilhas especÃ­ficas, conforme necessÃ¡rio."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemplos de cÃ³digo do GroupDocs.Markdown"
  description: "Os cenÃ¡rios de uso mais comuns para exportar documentos para Markdown. VocÃª pode solicitar uma [licenÃ§a temporÃ¡ria gratuita](https://purchase.groupdocs.com/temporary-license) para testar o produto em seu ambiente."
  items:
    # code sample loop
    - title: "Exportar PDF para Markdown"
      content: |
       Obtenha um arquivo Markdown limpo a partir de um PDF em poucas linhas de cÃ³digo. Por padrÃ£o, as imagens sÃ£o incorporadas no arquivo de saÃ­da.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importar o namespace
            using GroupDocs.Markdown;

            // Definir a licenÃ§a
            License.Set("GroupDocs.Markdown.lic");

            // Instanciar o conversor
            var converter = new MarkdownConverter("business-plan.pdf");

            // Converter e salvar a saÃ­da em um arquivo
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "Salvar imagens em uma pasta"
      content: |
       Esta amostra de cÃ³digo mostra como converter um arquivo DOCX para Markdown e salvar imagens em uma pasta separada.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importe o namespace
            using GroupDocs.Markdown;

            // Defina a licenÃ§a
            License.Set("GroupDocs.Markdown.lic");

            // Instancie o conversor
            var converter = new MarkdownConverter("annual-report.docx");

            // Defina a estratÃ©gia de exportaÃ§Ã£o de imagens e a pasta de saÃ­da
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Converta e salve a saÃ­da em um arquivo
            converter.Convert("annual-report.md", convertOptions);
            ```

############################# Formats ############################

formats:
  enable: true
  title:  "Mais de 30 formatos de arquivo suportados"
  description: "Os seguintes formatos de arquivo sÃ£o suportados para exportaÃ§Ã£o para Markdown."
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "MÃ©tricas aprofundadas e insights estatÃ­sticos"
  description: "Mergulhe em uma anÃ¡lise detalhada de nossos principais nÃºmeros, fornecendo mÃ©tricas abrangentes e insights estatÃ­sticos sobre nossas conquistas, impacto e crescimento."

  items:
    # metrics loop
    - number: "180+"
      title: "Formatos suportados"
      content: "Converta de dezenas de formatos de documentos e textos, incluindo PDF, Word, Excel e eBooks para Markdown, proporcionando integraÃ§Ãµes perfeitas com o ecossistema de IA generativa."
    # metrics loop
    - number: "1.0M"
      title: "Confiado por desenvolvedores"
      content: "Nossas soluÃ§Ãµes tornaram-se confiÃ¡veis e amplamente adotadas na comunidade de desenvolvedores, fornecendo integraÃ§Ã£o perfeita para seus projetos."

    # metrics loop
    - number: "15+"
      title: "Produtos"
      content: "Oferecemos mais de 15 SDKs de processamento de documentos, proporcionando uma experiÃªncia fluida para suas integraÃ§Ãµes. Processamos para que vocÃª possa relaxar."
    
    # metrics loop
    - number: "100+"
      title: "Clientes satisfeitos"
      content: "Atendendo Ã s marcas mais icÃ´nicas ao redor do mundo. Descubra por que centenas adoram os produtos GroupDocs! Junte-se agora!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nossos clientes satisfeitos"
  description: "As bibliotecas GroupDocs sÃ£o utilizadas por marcas mundialmente renomadas e distintas."

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
  title: "Pronto para comeÃ§ar?"
  description: "Escolha a plataforma de destino para saber mais sobre o produto."

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "Perguntas e dÃºvidas comuns"
  description: "Encontre respostas para perguntas comuns em nossa seÃ§Ã£o de FAQ para atender rapidamente Ã s suas dÃºvidas e preocupaÃ§Ãµes."

  items:
    #  loop
    - question: "Posso avaliar os produtos GroupDocs antes de comprar?"
      answer: |
        Sim! Todos os produtos GroupDocs tÃªm uma versÃ£o de avaliaÃ§Ã£o sem risco disponÃ­vel. Incentivamos fortemente os desenvolvedores a baixar e experimentar nossas APIs antes de comprar, para garantir que elas atenderÃ£o Ã s suas necessidades 100%.
    #  loop
    - question: "A GroupDocs realiza demonstraÃ§Ãµes de produtos?"
      answer: |
        NÃ£o, nosso foco estÃ¡ em nossas APIs e em criar os produtos mais funcionais e estÃ¡veis possÃ­veis. Oferecemos testes totalmente funcionais e gratuitos na forma de uma [licenÃ§a temporÃ¡ria](https://purchase.groupdocs.com/temporary-license/) para que vocÃª possa testar o produto por conta prÃ³pria.
    #  loop
    - question: "Onde posso baixar o produto?"
      answer: |
        Todos os produtos estÃ£o disponÃ­veis para download via NuGet ou GroupDocs Releases [site](https://releases.groupdocs.com).    
    #  loop
    - question: "As licenÃ§as de desenvolvedor do GroupDocs sÃ£o por usuÃ¡rio ou por usuÃ¡rio nomeado?"
      answer: |
        As licenÃ§as de desenvolvedor do GroupDocs sÃ£o por usuÃ¡rio, nÃ£o por usuÃ¡rio nomeado. Entendemos que os membros de uma equipe de desenvolvimento podem mudar ao longo do tempo e que nÃ£o Ã© prÃ¡tico ter que atualizar a licenÃ§a toda vez que isso ocorre.
    #  loop
    - question: "VocÃª fornece suporte tÃ©cnico?"
      answer: |
        Sim, oferecemos suporte tÃ©cnico gratuito pelas equipes de produto no [FÃ³rum de Suporte Gratuito](https://forum.groupdocs.com/c/markdown) e no [Helpdesk de Suporte Pago](https://helpdesk.groupdocs.com/) para garantir que sua experiÃªncia seja tranquila.

############################# Cloud ############################

cloud_links:
  enable: false
  title: "APIs do GroupDocs Cloud"
  description: "Acelere a conversÃ£o de documento para Markdown em qualquer aplicaÃ§Ã£o com nossa API REST baseada em nuvem"

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "Use a API RESTful cURL para converter Microsoft Office, PDF e outros formatos para Markdown em suas aplicaÃ§Ãµes."

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: "SDK Cloud .NET para conversÃ£o programÃ¡tica de documento para Markdown com opÃ§Ãµes configurÃ¡veis."
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "SDK Cloud Java para integrar a conversÃ£o de documentos para Markdown em aplicaÃ§Ãµes Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplicativos Online do GroupDocs"
  description: "AplicaÃ§Ã£o online que permite converter formatos de arquivo populares para Markdown em um navegador."

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "Explore um aplicativo online gratuito para converter vÃ¡rios formatos de arquivo diretamente para Markdown (.md)."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "Ferramenta baseada na web para converter arquivos Microsoft Word para Markdown em vÃ¡rios dispositivos."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "Converta arquivos PDF para Markdown online com um aplicativo gratuito de PDF para Markdown."
---

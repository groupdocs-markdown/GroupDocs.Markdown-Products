---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "Exportar documentos para Markdown | GroupDocs"
head_description: "GroupDocs.Markdown é um SDK de processamento de documentos que exporta PDF, Word, Excel e outros formatos para Markdown, permitindo integração perfeita com o ecossistema de IA generativa."

############################# Header ##########################

title: "Prepare seus documentos para IA"
description: |
  SDK Markdown para exportar vários tipos de documentos em Markdown limpo e semântico.

  Preserve a estrutura do documento, títulos, listas, tabelas, links e imagens

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
  description: "Estes são os recursos que fazem nossa solução se destacar."

  items:
    # feature loop
    - icon: "convert"
      title: "Exportar documentos para Markdown"
      content: "Prepare seus PDFs, Word, Excel, eBooks e textos para LLM exportando-os para Markdown."

    # feature loop
    - icon: "structure"
      title: "Manter a estrutura do documento"
      content: "Preserve a estrutura do documento, títulos, listas, tabelas, links e imagens."

    # feature loop
    - icon: "image"
      title: "Tenha controle sobre as imagens"
      content: "Incorpore imagens ou salve-as como recursos externos. Substitua imagens durante o processo de conversão."
    
    # feature loop
    - icon: "settings"
      title: "Converter documentos inteiros ou páginas específicas"
      content: "Converta documentos inteiros ou limite a conversão a páginas ou planilhas específicas, conforme necessário."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemplos de código do GroupDocs.Markdown"
  description: "Os cenários de uso mais comuns para exportar documentos para Markdown. Você pode solicitar uma [licença temporária gratuita](https://purchase.groupdocs.com/temporary-license) para testar o produto em seu ambiente."
  items:
    # code sample loop
    - title: "Exportar PDF para Markdown"
      content: |
       Obtenha um arquivo Markdown limpo a partir de um PDF em poucas linhas de código. Por padrão, as imagens são incorporadas no arquivo de saída.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importar o namespace
            using GroupDocs.Markdown;

            // Definir a licença
            License.Set("GroupDocs.Markdown.lic");

            // Instanciar o conversor
            var converter = new MarkdownConverter("business-plan.pdf");

            // Converter e salvar a saída em um arquivo
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "Salvar imagens em uma pasta"
      content: |
       Esta amostra de código mostra como converter um arquivo DOCX para Markdown e salvar imagens em uma pasta separada.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importe o namespace
            using GroupDocs.Markdown;

            // Defina a licença
            License.Set("GroupDocs.Markdown.lic");

            // Instancie o conversor
            var converter = new MarkdownConverter("annual-report.docx");

            // Defina a estratégia de exportação de imagens e a pasta de saída
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Converta e salve a saída em um arquivo
            converter.Convert("annual-report.md", convertOptions);
            ```

############################# Formats ############################

formats:
  enable: true
  title:  "Mais de 30 formatos de arquivo suportados"
  description: "Os seguintes formatos de arquivo são suportados para exportação para Markdown."
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "Métricas aprofundadas e insights estatísticos"
  description: "Mergulhe em uma análise detalhada de nossos principais números, fornecendo métricas abrangentes e insights estatísticos sobre nossas conquistas, impacto e crescimento."

  items:
    # metrics loop
    - number: "180+"
      title: "Formatos suportados"
      content: "Converta de dezenas de formatos de documentos e textos, incluindo PDF, Word, Excel e eBooks para Markdown, proporcionando integrações perfeitas com o ecossistema de IA generativa."
    # metrics loop
    - number: "1.0M"
      title: "Confiado por desenvolvedores"
      content: "Nossas soluções tornaram-se confiáveis e amplamente adotadas na comunidade de desenvolvedores, fornecendo integração perfeita para seus projetos."

    # metrics loop
    - number: "15+"
      title: "Produtos"
      content: "Oferecemos mais de 15 SDKs de processamento de documentos, proporcionando uma experiência fluida para suas integrações. Processamos para que você possa relaxar."
    
    # metrics loop
    - number: "100+"
      title: "Clientes satisfeitos"
      content: "Atendendo às marcas mais icônicas ao redor do mundo. Descubra por que centenas adoram os produtos GroupDocs! Junte-se agora!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nossos clientes satisfeitos"
  description: "As bibliotecas GroupDocs são utilizadas por marcas mundialmente renomadas e distintas."

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
  title: "Pronto para começar?"
  description: "Escolha a plataforma de destino para saber mais sobre o produto."

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "Perguntas e dúvidas comuns"
  description: "Encontre respostas para perguntas comuns em nossa seção de FAQ para atender rapidamente às suas dúvidas e preocupações."

  items:
    #  loop
    - question: "Posso avaliar os produtos GroupDocs antes de comprar?"
      answer: |
        Sim! Todos os produtos GroupDocs têm uma versão de avaliação sem risco disponível. Incentivamos fortemente os desenvolvedores a baixar e experimentar nossas APIs antes de comprar, para garantir que elas atenderão às suas necessidades 100%.
    #  loop
    - question: "A GroupDocs realiza demonstrações de produtos?"
      answer: |
        Não, nosso foco está em nossas APIs e em criar os produtos mais funcionais e estáveis possíveis. Oferecemos testes totalmente funcionais e gratuitos na forma de uma [licença temporária](https://purchase.groupdocs.com/temporary-license/) para que você possa testar o produto por conta própria.
    #  loop
    - question: "Onde posso baixar o produto?"
      answer: |
        Todos os produtos estão disponíveis para download via NuGet ou GroupDocs Releases [site](https://releases.groupdocs.com).    
    #  loop
    - question: "As licenças de desenvolvedor do GroupDocs são por usuário ou por usuário nomeado?"
      answer: |
        As licenças de desenvolvedor do GroupDocs são por usuário, não por usuário nomeado. Entendemos que os membros de uma equipe de desenvolvimento podem mudar ao longo do tempo e que não é prático ter que atualizar a licença toda vez que isso ocorre.
    #  loop
    - question: "Você fornece suporte técnico?"
      answer: |
        Sim, oferecemos suporte técnico gratuito pelas equipes de produto no [Fórum de Suporte Gratuito](https://forum.groupdocs.com/c/markdown) e no [Helpdesk de Suporte Pago](https://helpdesk.groupdocs.com/) para garantir que sua experiência seja tranquila.

############################# Cloud ############################

cloud_links:
  enable: false
  title: "APIs do GroupDocs Cloud"
  description: "Acelere a conversão de documento para Markdown em qualquer aplicação com nossa API REST baseada em nuvem"

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "Use a API RESTful cURL para converter Microsoft Office, PDF e outros formatos para Markdown em suas aplicações."

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: "SDK Cloud .NET para conversão programática de documento para Markdown com opções configuráveis."
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "SDK Cloud Java para integrar a conversão de documentos para Markdown em aplicações Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplicativos Online do GroupDocs"
  description: "Aplicação online que permite converter formatos de arquivo populares para Markdown em um navegador."

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "Explore um aplicativo online gratuito para converter vários formatos de arquivo diretamente para Markdown (.md)."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "Ferramenta baseada na web para converter arquivos Microsoft Word para Markdown em vários dispositivos."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "Converta arquivos PDF para Markdown online com um aplicativo gratuito de PDF para Markdown."
---

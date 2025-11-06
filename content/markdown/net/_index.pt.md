---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: pt
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

head_title: "Exportar documentos para Markdown em .NET | GroupDocs"
head_description: "GroupDocs.Markdown para .NET é uma API de processamento de documentos que exporta PDF, Word, Excel e outros formatos para Markdown para integração perfeita com o ecossistema de IA generativa."

############################# Header ##########################

title: "Exportar documentos para Markdown<br>usando a API .NET"
description: "API de conversão de Markdown para exportar formatos de documentos populares para Markdown limpo com controle total."
words:
  for: "for"

actions:
  main: "Download gratuito do NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Markdown gratuitamente ou solicite uma licença"

release:
  hidden: false
  title: "Versão {0}&nbsp;lançada"
  notes: "Veja o que há de novo"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Exportar PDF para Markdown em C#"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Importar o namespace
    using GroupDocs.Markdown;

    // Definir a licença
    License.Set("GroupDocs.Markdown.lic");

    // Instanciar o conversor
    var converter = new MarkdownConverter("business-plan.pdf");

    // Converter e salvar o arquivo Markdown de saída
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown em foco"
  description: "API para analisar e exportar documentos para Markdown em aplicações .NET."
  features:
    # feature loop
    - title: "Conversão precisa e confiável"
      content: "Converta formatos suportados para Markdown de forma eficiente, mantendo a integridade da estrutura. Suporta .NET Framework 4.6.2+ e .NET 6.0 no Windows e Linux."

    # feature loop
    - title: "Formatos populares suportados"
      content: "Exporte arquivos PDF, Word, Excel, eBooks, Web e texto simples para Markdown, inclusive documentos protegidos por senha."

    # feature loop
    - title: "Funciona na sua máquina local"
      content: "Você controla seus dados – fornecemos uma API on‑premise que não requer nenhuma nuvem ou conexão com a internet."

############################# Platforms ############################
platforms:
  enable: true
  title: "Suporte a plataformas"
  description: "Os seguintes sistemas operacionais, frameworks e gerenciadores de pacotes são suportados."
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
  title: "Formatos de arquivo suportados"
  description: |
    Os seguintes formatos de arquivo são suportados para exportação para Markdown.
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
        ### Word e Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### Outros   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "Recursos do GroupDocs.Markdown"
  description: "Estes são os recursos que destacam nosso produto."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Exportar múltiplos formatos de documento"
      content: "Converta os formatos de documento mais populares para Markdown (PDF, DOCX, XLSX, EPUB e mais)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Formatação avançada de Markdown"
      content: "Cabeçalhos, parágrafos, listas, tabelas, links, imagens, citações em bloco e blocos de código são exportados para a sintaxe Markdown apropriada."

    # feature loop
    - icon: "control_over_images"
      title: "Controle total sobre imagens"
      content: "Controle as imagens exportando-as ou incorporando-as no arquivo Markdown de saída."

    # feature loop
    - icon: "secure"
      title: "Funciona na sua máquina local"
      content: "Nenhuma nuvem ou conexão com a Internet é necessária. Todo o processamento é feito na sua máquina local."

    # feature loop
    - icon: "intuitive"
      title: "API pública intuitiva"
      content: "API pública simples e intuitiva, projetada por desenvolvedores para desenvolvedores com carinho."

    # feature loop
    - icon: "cross_platform"
      title: "Funciona no Windows e Linux"
      content: ".NET e assemblies do .NET Framework são fornecidos dentro do pacote NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Exemplos de código"
  description: "Os cenários de uso mais comuns para exportar documentos para Markdown em aplicações .NET."
  items:
    # code sample loop
    - title: "Exportar DOCX para Markdown"
      content: "Este exemplo de código demonstra como converter um arquivo DOCX para Markdown e salvar a saída em um arquivo. As imagens são incorporadas no arquivo de saída."
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
            var converter = new MarkdownConverter("annual-review.docx");

            // Converter e salvar a saída em um arquivo
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Importar o namespace  
            open GroupDocs.Markdown

            // Definir a licença
            License.Set("GroupDocs.Markdown.lic")

            // Instanciar o conversor
            let converter = new MarkdownConverter("annual-review.docx")

            // Converter e salvar a saída em um arquivo
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Importar o namespace  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Definir a licença
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instanciar o conversor
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Converter e salvar a saída em um arquivo
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Salvar imagens em uma pasta"
      content: "Este exemplo de código demonstra como converter um arquivo DOCX para Markdown e salvar as imagens em uma pasta separada."
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
            var converter = new MarkdownConverter("annual-report.docx");

            // Definir a estratégia de exportação de imagens e a pasta de saída
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Converter e salvar a saída em um arquivo
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Importar o namespace
            open GroupDocs.Markdown

            // Definir a licença
            License.Set("GroupDocs.Markdown.lic")

            // Instanciar o conversor
            let converter = new MarkdownConverter("annual-report.docx")

            // Definir a estratégia de exportação de imagens e a pasta de saída
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Converter e salvar a saída em um arquivo
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Importar o namespace  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Definir a licença
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instanciar o conversor
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Definir a estratégia de exportação de imagens e a pasta de saída
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Converter e salvar a saída em um arquivo
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "Avaliações de produtos GroupDocs"
# description: "Não acredite apenas na nossa palavra. Veja o que outros desenvolvedores dizem sobre nossas APIs"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Serviço excelente e produtos excelentes. Eles foram extremamente úteis e responsivos durante o processo de implementação do GroupDocs.Markdown para .NET, não consigo recomendá-los o suficiente."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Depois de implementar e usar o GroupDocs.Markdown para .NET no projeto, ele parece estar funcionando muito bem. Testei com muitos documentos e até agora tudo certo. A saída Markdown está limpa e consistente entre as fontes."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

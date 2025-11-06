---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: it
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

head_title: "Esporta documenti in Markdown in .NET | GroupDocs"
head_description: "GroupDocs.Markdown per .NET Ã¨ un'API di elaborazione documenti che esporta PDF, Word, Excel e altri formati in Markdown per un'integrazione fluida con l'ecosistema di IA generativa."

############################# Header ##########################

title: "Esporta documenti in Markdown<br>utilizzando l'API .NET"
description: "API di conversione Markdown per esportare i formati di documento piÃ¹ diffusi in Markdown pulito con pieno controllo."
words:
  for: "for"

actions:
  main: "Download NuGet gratuito"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Licenze"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Pronto per iniziare?"
  description: "Prova le funzionalitÃ  di GroupDocs.Markdown gratuitamente o richiedi una licenza"

release:
  hidden: false
  title: "Versione {0}&nbsp;rilasciata"
  notes: "Scopri le novitÃ "
  downloads: "Download"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Esporta PDF in Markdown in C#"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Importa lo spazio dei nomi
    using GroupDocs.Markdown;

    // Imposta la licenza
    License.Set("GroupDocs.Markdown.lic");

    // Istanzia il convertitore
    var converter = new MarkdownConverter("business-plan.pdf");

    // Converti e salva il file Markdown di output
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown in sintesi"
  description: "API per analizzare ed esportare documenti in Markdown nelle applicazioni .NET."
  features:
    # feature loop
    - title: "Conversione accurata e affidabile"
      content: "Converti in modo efficiente i formati supportati in Markdown mantenendo l'integritÃ  della struttura. Supporta .NET Framework 4.6.2+ e .NET 6.0 su Windows e Linux."

    # feature loop
    - title: "Formati popolari supportati"
      content: "Esporta PDF, Word, Excel, eBook, file Web e di testo semplice in Markdown, inclusi i documenti protetti da password."

    # feature loop
    - title: "Funziona sulla tua macchina locale"
      content: "Controlli i tuoi dati â€“ forniamo un'API on-premise che non richiede alcun cloud o connessione internet."

############################# Platforms ############################
platforms:
  enable: true
  title: "Supporto piattaforme"
  description: "Sono supportati i seguenti sistemi operativi, framework e gestori di pacchetti."
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
  title: "Formati di file supportati"
  description: |
    I seguenti formati file sono supportati per l'esportazione in Markdown.
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
        ### Word ed Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### Altro   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "FunzionalitÃ  di GroupDocs.Markdown"
  description: "Queste sono le funzionalitÃ  che distinguono il nostro prodotto."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Esporta piÃ¹ formati di documento"
      content: "Converti i formati di documento piÃ¹ popolari in Markdown (PDF, DOCX, XLSX, EPUB e altro)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Formattazione avanzata di Markdown"
      content: "Intestazioni, paragrafi, elenchi, tabelle, collegamenti, immagini, citazioni a blocco e blocchi di codice vengono esportati nella sintassi Markdown appropriata."

    # feature loop
    - icon: "control_over_images"
      title: "Controllo completo sulle immagini"
      content: "Gestisci le immagini esportandole o incorporandole nel file Markdown di output."

    # feature loop
    - icon: "secure"
      title: "Funziona sulla tua macchina locale"
      content: "Non Ã¨ necessaria alcuna connessione cloud o Internet. Tutto l'elaborazione avviene sulla tua macchina locale."

    # feature loop
    - icon: "intuitive"
      title: "API pubblica intuitiva"
      content: "API pubblica semplice e intuitiva, progettata da sviluppatori per sviluppatori con passione."

    # feature loop
    - icon: "cross_platform"
      title: "Funziona su Windows e Linux"
      content: "Le assembly .NET e .NET Framework sono fornite nel pacchetto NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Esempi di codice"
  description: "Gli scenari d'uso piÃ¹ comuni per esportare documenti in Markdown nelle applicazioni .NET."
  items:
    # code sample loop
    - title: "Esporta DOCX in Markdown"
      content: "Questo esempio di codice mostra come convertire un file DOCX in Markdown e salvare l'output su file. Le immagini sono incorporate nel file di output."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importa lo spazio dei nomi
            using GroupDocs.Markdown;

            // Imposta la licenza
            License.Set("GroupDocs.Markdown.lic");

            // Istanzia il convertitore
            var converter = new MarkdownConverter("annual-review.docx");

            // Converti e salva l'output su file
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Importa lo spazio dei nomi  
            open GroupDocs.Markdown

            // Imposta la licenza
            License.Set("GroupDocs.Markdown.lic")

            // Istanzia il convertitore
            let converter = new MarkdownConverter("annual-review.docx")

            // Converti e salva l'output su file
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Importa lo spazio dei nomi  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Imposta la licenza
                    License.Set("GroupDocs.Markdown.lic")

                    ' Istanzia il convertitore
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Converti e salva l'output su file
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Salva le immagini in una cartella"
      content: "Questo esempio di codice mostra come convertire un file DOCX in Markdown e salvare le immagini in una cartella separata."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importa lo spazio dei nomi
            using GroupDocs.Markdown;

            // Imposta la licenza
            License.Set("GroupDocs.Markdown.lic");

            // Istanzia il convertitore
            var converter = new MarkdownConverter("annual-report.docx");

            // Imposta la strategia di esportazione delle immagini e la cartella di output
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Converti e salva l'output su file
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Importa lo spazio dei nomi
            open GroupDocs.Markdown

            // Imposta la licenza
            License.Set("GroupDocs.Markdown.lic")

            // Istanzia il convertitore
            let converter = new MarkdownConverter("annual-report.docx")

            // Imposta la strategia di esportazione delle immagini e la cartella di output
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Converti e salva l'output su file
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Importa lo spazio dei nomi  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Imposta la licenza
                    License.Set("GroupDocs.Markdown.lic")

                    ' Istanzia il convertitore
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Imposta la strategia di esportazione delle immagini e la cartella di output
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Converti e salva l'output su file
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "Recensioni dei prodotti GroupDocs"
# description: "Non limitarti a crederci. Scopri cosa dicono gli altri sviluppatori delle nostre API"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Servizio eccellente e prodotti eccellenti. Sono stati estremamente disponibili e reattivi durante il processo di implementazione di GroupDocs.Markdown per .NET, non posso raccomandarli abbastanza."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Dopo aver implementato e utilizzato GroupDocs.Markdown per .NET nel progetto, sembra funzionare molto bene. Ho testato con molti documenti e finora tutto ok. L'output Markdown Ã¨ pulito e coerente tra le varie fonti."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

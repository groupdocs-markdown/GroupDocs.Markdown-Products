---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: de
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

head_title: "Dokumente in Markdown exportieren in .NET | GroupDocs"
head_description: "GroupDocs.Markdown fÃ¼r .NET ist eine Dokumentenverarbeitungsâ€‘API, die PDF, Word, Excel und andere Formate nach Markdown exportiert, um eine nahtlose Integration in das generative KIâ€‘Ã–kosystem zu ermÃ¶glichen."

############################# Header ##########################

title: "Dokumente nach Markdown exportieren<br>mit .NETâ€‘API"
description: "Markdownâ€‘Konvertierungsâ€‘API zum Export beliebter Dokumentformate in sauberes Markdown mit voller Kontrolle."
words:
  for: "for"

actions:
  main: "Kostenloser NuGetâ€‘Download"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Bereit, loszulegen?"
  description: "Testen Sie GroupDocs.Markdown-Funktionen kostenlos oder fordern Sie eine Lizenz an."

release:
  hidden: false
  title: "Version {0}&nbsp;verÃ¶ffentlicht"
  notes: "Neuigkeiten ansehen"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "PDF nach Markdown exportieren in C#"
  more: "Weitere Beispiele"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Namespace importieren
    using GroupDocs.Markdown;

    // Lizenz festlegen
    License.Set("GroupDocs.Markdown.lic");

    // Konverter instanziieren
    var converter = new MarkdownConverter("business-plan.pdf");

    // Konvertieren und Ausgabedatei Markdown speichern
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown auf einen Blick"
  description: "API zum Parsen und Exportieren von Dokumenten nach Markdown in .NETâ€‘Anwendungen."
  features:
    # feature loop
    - title: "PrÃ¤zise und zuverlÃ¤ssige Konvertierung"
      content: "UnterstÃ¼tzte Formate effizient nach Markdown konvertieren und dabei die StrukturintegritÃ¤t bewahren. UnterstÃ¼tzt .NET Framework 4.6.2+ und .NET 6.0 unter Windows und Linux."

    # feature loop
    - title: "UnterstÃ¼tzte gÃ¤ngige Formate"
      content: "Exportieren Sie PDF-, Word-, Excel-, eBook-, Web- und Nurâ€‘Textâ€‘Dateien nach Markdown, einschlieÃŸlich passwortgeschÃ¼tzter Dokumente."

    # feature loop
    - title: "LÃ¤uft auf Ihrem lokalen Rechner"
      content: "Sie kontrollieren Ihre Daten â€“ wir bieten eine On-Premise-API, die keine Cloud- oder Internetverbindung erfordert."

############################# Platforms ############################
platforms:
  enable: true
  title: "PlattformunterstÃ¼tzung"
  description: "Die folgenden Betriebssysteme, Frameworks und Paketmanager werden unterstÃ¼tzt."
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
  title: "UnterstÃ¼tzte Dateiformate"
  description: |
    Die folgenden Dateiformate werden fÃ¼r den Export nach Markdown unterstÃ¼tzt.
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
        ### Andere   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Markdown-Funktionen"
  description: "Dies sind die Funktionen, die unser Produkt auszeichnen."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Export mehrerer Dokumentformate"
      content: "Konvertieren Sie die gÃ¤ngigsten Dokumentformate zu Markdown (PDF, DOCX, XLSX, EPUB und mehr)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Erweiterte Markdown-Formatierung"
      content: "Ãœberschriften, AbsÃ¤tze, Listen, Tabellen, Links, Bilder, Blockzitate und CodeblÃ¶cke werden in die entsprechende Markdownâ€‘Syntax exportiert."

    # feature loop
    - icon: "control_over_images"
      title: "VollstÃ¤ndige Kontrolle Ã¼ber Bilder"
      content: "Ãœbernehmen Sie die Kontrolle Ã¼ber Bilder, indem Sie sie exportieren oder in die Ausgabedatei Markdown einbetten."

    # feature loop
    - icon: "secure"
      title: "LÃ¤uft auf Ihrem lokalen Rechner"
      content: "Keine Cloud- oder Internetverbindung erforderlich. Die gesamte Verarbeitung erfolgt auf Ihrem lokalen Rechner."

    # feature loop
    - icon: "intuitive"
      title: "Intuitive Ã¶ffentliche API"
      content: "Einfache und intuitive Ã¶ffentliche API, von Entwicklern fÃ¼r Entwickler mit Leidenschaft."

    # feature loop
    - icon: "cross_platform"
      title: "Funktioniert unter Windows und Linux"
      content: ".NET- und .NETâ€‘Frameworkâ€‘Assemblies werden im NuGetâ€‘Paket bereitgestellt."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Codebeispiele"
  description: "Die hÃ¤ufigsten AnwendungsfÃ¤lle fÃ¼r den Export von Dokumenten nach Markdown in .NET-Anwendungen."
  items:
    # code sample loop
    - title: "Exportieren von DOCX nach Markdown"
      content: "Dieses Codebeispiel zeigt, wie eine DOCX-Datei nach Markdown konvertiert und die Ausgabe in eine Datei gespeichert wird. Die Bilder sind in die Ausgabedatei eingebettet."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Namespace importieren
            using GroupDocs.Markdown;

            // Lizenz festlegen
            License.Set("GroupDocs.Markdown.lic");

            // Konverter instanziieren
            var converter = new MarkdownConverter("annual-review.docx");

            // Konvertieren und Ausgabe in Datei speichern
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Namespace importieren  
            open GroupDocs.Markdown

            // Lizenz festlegen
            License.Set("GroupDocs.Markdown.lic")

            // Konverter instanziieren
            let converter = new MarkdownConverter("annual-review.docx")

            // Konvertieren und Ausgabe in Datei speichern
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Namespace importieren  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Lizenz festlegen
                    License.Set("GroupDocs.Markdown.lic")

                    ' Konverter instanziieren
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Konvertieren und Ausgabe in Datei speichern
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Bilder in einen Ordner speichern"
      content: "Dieses Codebeispiel zeigt, wie eine DOCX-Datei nach Markdown konvertiert und Bilder in einen separaten Ordner gespeichert werden."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Namespace importieren
            using GroupDocs.Markdown;

            // Lizenz festlegen
            License.Set("GroupDocs.Markdown.lic");

            // Konverter instanziieren
            var converter = new MarkdownConverter("annual-report.docx");

            // Bildexportstrategie und Ausgabeverzeichnis festlegen
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Konvertieren und Ausgabe in Datei speichern
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Namespace importieren
            open GroupDocs.Markdown

            // Lizenz festlegen
            License.Set("GroupDocs.Markdown.lic")

            // Konverter instanziieren
            let converter = new MarkdownConverter("annual-report.docx")

            // Bildexportstrategie und Ausgabeverzeichnis festlegen
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Konvertieren und Ausgabe in Datei speichern
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Namespace importieren  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Lizenz festlegen
                    License.Set("GroupDocs.Markdown.lic")

                    ' Konverter instanziieren
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Bildexportstrategie und Ausgabeverzeichnis festlegen
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Konvertieren und Ausgabe in Datei speichern
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs Produktbewertungen"
# description: "Nehmen Sie uns nicht nur beim Wort. Sehen Sie, was andere Entwickler Ã¼ber unsere APIs sagen."

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Ausgezeichneter Service und hervorragende Produkte. Sie waren wÃ¤hrend des Implementierungsprozesses von GroupDocs.Markdown fÃ¼r .NET Ã¤uÃŸerst hilfsbereit und reaktionsschnell, ich kann sie nicht genug empfehlen."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Nachdem GroupDocs.Markdown fÃ¼r .NET im Projekt implementiert und verwendet wurde, scheint es sehr gut zu funktionieren. Ich habe mit vielen Dokumenten getestet und bisher ist alles in Ordnung. Die Markdownâ€‘Ausgabe ist sauber und konsistent Ã¼ber alle Quellen hinweg."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

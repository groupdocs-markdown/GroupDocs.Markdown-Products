---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fr
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

head_title: "Exporter des documents en Markdown avec .NET | GroupDocs"
head_description: "GroupDocs.Markdown for .NET est une API de traitement de documents qui exporte PDF, Word, Excel et dâ€™autres formats vers Markdown pour une intÃ©gration transparente avec lâ€™Ã©cosystÃ¨me dâ€™IA gÃ©nÃ©rative."

############################# Header ##########################

title: "Exporter des documents en Markdown<br>en utilisant lâ€™API .NET"
description: "API de conversion Markdown pour exporter les formats de documents populaires vers du Markdown propre avec un contrÃ´le total."
words:
  for: "for"

actions:
  main: "TÃ©lÃ©chargement NuGet gratuit"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Licence"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "PrÃªt Ã  commencerâ€¯?"
  description: "Essayez les fonctionnalitÃ©s de GroupDocs.Markdown gratuitement ou demandez une licence."

release:
  hidden: false
  title: "Version {0}&nbsp;publiÃ©e"
  notes: "Voir les nouveautÃ©s"
  downloads: "TÃ©lÃ©chargements"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Exporter PDF en Markdown avec C#"
  more: "Plus d'exemples"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Importer lâ€™espace de noms
    using GroupDocs.Markdown;

    // DÃ©finir la licence
    License.Set("GroupDocs.Markdown.lic");

    // Instancier le convertisseur
    var converter = new MarkdownConverter("business-plan.pdf");

    // Convertir et enregistrer le fichier Markdown de sortie
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown en un coup dâ€™Å“il"
  description: "API pour analyser et exporter des documents en Markdown dans les applications .NET."
  features:
    # feature loop
    - title: "Conversion prÃ©cise et fiable"
      content: "Convertissez efficacement les formats pris en charge en Markdown tout en prÃ©servant lâ€™intÃ©gritÃ© de la structure. Prend en charge .NET Framework 4.6.2+ et .NET 6.0 sous Windows et Linux."

    # feature loop
    - title: "Formats populaires pris en charge"
      content: "Exportez les fichiers PDF, Word, Excel, eBooks, Web et texte brut en Markdown, y compris les documents protÃ©gÃ©s par mot de passe."

    # feature loop
    - title: "Fonctionne sur votre machine locale"
      content: "Vous contrÃ´lez vos donnÃ©es - nous fournissons une API locale qui ne nÃ©cessite aucun cloud ni connexion Internet."

############################# Platforms ############################
platforms:
  enable: true
  title: "Prise en charge des plateformes"
  description: "Les systÃ¨mes d'exploitation, frameworks et gestionnaires de paquets suivants sont pris en charge."
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
  title: "Formats de fichiers pris en charge"
  description: |
    Les formats de fichier suivants sont pris en charge pour l'exportation vers Markdown.
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
        ### Autre   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "FonctionnalitÃ©s de GroupDocs.Markdown"
  description: "Voici les fonctionnalitÃ©s qui distinguent notre produit."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Exporter plusieurs formats de documents"
      content: "Convertissez les formats de documents les plus populaires en Markdown (PDF, DOCX, XLSX, EPUB et plus)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Mise en forme Markdown avancÃ©e"
      content: "Les enâ€‘tÃªtes, paragraphes, listes, tableaux, liens, images, citations en bloc et blocs de code sont exportÃ©s vers la syntaxe Markdown appropriÃ©e."

    # feature loop
    - icon: "control_over_images"
      title: "ContrÃ´le total sur les images"
      content: "Prenez le contrÃ´le des images en les exportant ou en les incorporant dans le fichier Markdown de sortie."

    # feature loop
    - icon: "secure"
      title: "Fonctionne sur votre machine locale"
      content: "Aucun cloud ni connexion Internet requis. Tout le traitement est effectuÃ© sur votre machine locale."

    # feature loop
    - icon: "intuitive"
      title: "API publique intuitive"
      content: "API publique simple et intuitive, conÃ§ue par des dÃ©veloppeurs pour des dÃ©veloppeurs avec passion."

    # feature loop
    - icon: "cross_platform"
      title: "Fonctionne sous Windows et Linux"
      content: "Les assemblages .NET et .NET Framework sont fournis dans le package NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Exemples de code"
  description: "Les scÃ©narios d'utilisation les plus courants pour l'exportation de documents vers Markdown dans les applications .NET."
  items:
    # code sample loop
    - title: "Exporter DOCX vers Markdown"
      content: "Cet exemple de code montre comment convertir un fichier DOCX en Markdown et enregistrer la sortie dans un fichier. Les images sont intÃ©grÃ©es dans le fichier de sortie."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importer l'espace de noms
            using GroupDocs.Markdown;

            // DÃ©finir la licence
            License.Set("GroupDocs.Markdown.lic");

            // Instancier le convertisseur
            var converter = new MarkdownConverter("annual-review.docx");

            // Convertir et enregistrer la sortie dans un fichier
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Importer l'espace de noms  
            open GroupDocs.Markdown

            // DÃ©finir la licence
            License.Set("GroupDocs.Markdown.lic")

            // Instancier le convertisseur
            let converter = new MarkdownConverter("annual-review.docx")

            // Convertir et enregistrer la sortie dans un fichier
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Importer l'espace de noms  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' DÃ©finir la licence
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instancier le convertisseur
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Convertir et enregistrer la sortie dans un fichier
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Enregistrer les images dans un dossier"
      content: "Cet exemple de code montre comment convertir un fichier DOCX en Markdown et enregistrer les images dans un dossier sÃ©parÃ©."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importer l'espace de noms
            using GroupDocs.Markdown;

            // DÃ©finir la licence
            License.Set("GroupDocs.Markdown.lic");

            // Instancier le convertisseur
            var converter = new MarkdownConverter("annual-report.docx");

            // DÃ©finir la stratÃ©gie d'exportation des images et le dossier de sortie
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Convertir et enregistrer la sortie dans un fichier
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Importer l'espace de noms
            open GroupDocs.Markdown

            // DÃ©finir la licence
            License.Set("GroupDocs.Markdown.lic")

            // Instancier le convertisseur
            let converter = new MarkdownConverter("annual-report.docx")

            // DÃ©finir la stratÃ©gie d'exportation des images et le dossier de sortie
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Convertir et enregistrer la sortie dans un fichier
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Importer l'espace de noms  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' DÃ©finir la licence
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instancier le convertisseur
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' DÃ©finir la stratÃ©gie d'exportation des images et le dossier de sortie
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Convertir et enregistrer la sortie dans un fichier
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "Avis sur les produits GroupDocs"
# description: "Ne vous fiez pas quâ€™Ã  nos paroles. DÃ©couvrez ce que dâ€™autres dÃ©veloppeurs disent de nos API."

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Service et produits excellents. Ils ont Ã©tÃ© extrÃªmement utiles et rÃ©actifs pendant le processus dâ€™implÃ©mentation de GroupDocs.Markdown for .NET, nous ne pouvons pas les recommander suffisamment."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "AprÃ¨s avoir implÃ©mentÃ© et utilisÃ© GroupDocs.Markdown for .NET dans le projet, il semble trÃ¨s performant. Jâ€™ai testÃ© avec de nombreux documents et jusquâ€™Ã  prÃ©sent tout fonctionne bien. La sortie Markdown est propre et cohÃ©rente sur toutes les sources."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

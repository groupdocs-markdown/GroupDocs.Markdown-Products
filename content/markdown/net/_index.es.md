---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: es
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

head_title: "Exportar documentos a Markdown en .NET | GroupDocs"
head_description: "GroupDocs.Markdown for .NET es una API de procesamiento de documentos que exporta PDF, Word, Excel y otros formatos a Markdown para una integración perfecta con el ecosistema de IA generativa."

############################# Header ##########################

title: "Exportar documentos a Markdown<br>usando la API .NET"
description: "API de conversión Markdown para exportar formatos de documentos populares a Markdown limpio con control total."
words:
  for: "for"

actions:
  main: "Descarga gratuita de NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Licencias"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "¿Listo para comenzar?"
  description: "Pruebe las funciones de GroupDocs.Markdown de forma gratuita o solicite una licencia"

release:
  hidden: false
  title: "Versión {0}&nbsp;publicada"
  notes: "Ver lo nuevo"
  downloads: "Descargas"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Exportar PDF a Markdown en C#"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Importar el espacio de nombres
    using GroupDocs.Markdown;

    // Establecer la licencia
    License.Set("GroupDocs.Markdown.lic");

    // Instanciar el convertidor
    var converter = new MarkdownConverter("business-plan.pdf");

    // Convertir y guardar el archivo Markdown de salida
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown de un vistazo"
  description: "API para analizar y exportar documentos a Markdown en aplicaciones .NET."
  features:
    # feature loop
    - title: "Conversión precisa y fiable"
      content: "Convierte de manera eficiente los formatos compatibles a Markdown manteniendo la integridad de la estructura. Compatible con .NET Framework 4.6.2+ y .NET 6.0 en Windows y Linux."

    # feature loop
    - title: "Formatos populares soportados"
      content: "Exporta archivos PDF, Word, Excel, libros electrónicos, web y texto plano a Markdown, incluidos documentos protegidos con contraseña."

    # feature loop
    - title: "Se ejecuta en tu máquina local"
      content: "Usted controla sus datos: le ofrecemos una API on‑premise que no requiere ninguna nube ni conexión a Internet."

############################# Platforms ############################
platforms:
  enable: true
  title: "Compatibilidad de plataformas"
  description: "Se admiten los siguientes sistemas operativos, frameworks y gestores de paquetes."
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
  title: "Formatos de archivo compatibles"
  description: |
    Los siguientes formatos de archivo son compatibles para la exportación a Markdown.
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
        ### Word y Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### Otros   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "Funciones de GroupDocs.Markdown"
  description: "Estas son las funciones que hacen que nuestro producto se destaque."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Exportar varios formatos de documento"
      content: "Convertir los formatos de documento más populares a Markdown (PDF, DOCX, XLSX, EPUB y más)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Formato avanzado de Markdown"
      content: "Los encabezados, párrafos, listas, tablas, enlaces, imágenes, citas en bloque y bloques de código se exportan a la sintaxis Markdown adecuada."

    # feature loop
    - icon: "control_over_images"
      title: "Control total sobre imágenes"
      content: "Toma el control de las imágenes exportándolas o incrustándolas en el archivo Markdown de salida."

    # feature loop
    - icon: "secure"
      title: "Se ejecuta en tu máquina local"
      content: "No se requiere nube ni conexión a Internet. Todo el procesamiento se realiza en tu máquina local."

    # feature loop
    - icon: "intuitive"
      title: "API pública intuitiva"
      content: "API pública simple e intuitiva diseñada por desarrolladores para desarrolladores con pasión."

    # feature loop
    - icon: "cross_platform"
      title: "Funciona en Windows y Linux"
      content: "Los ensamblados .NET y .NET Framework se incluyen en el paquete NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Ejemplos de código"
  description: "Los escenarios de uso más comunes para exportar documentos a Markdown en aplicaciones .NET."
  items:
    # code sample loop
    - title: "Exportar DOCX a Markdown"
      content: "Este ejemplo de código muestra cómo convertir un archivo DOCX a Markdown y guardar la salida en un archivo. Las imágenes están incrustadas en el archivo de salida."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importar el espacio de nombres
            using GroupDocs.Markdown;

            // Establecer la licencia
            License.Set("GroupDocs.Markdown.lic");

            // Instanciar el conversor
            var converter = new MarkdownConverter("annual-review.docx");

            // Convertir y guardar la salida en un archivo
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Importar el espacio de nombres  
            open GroupDocs.Markdown

            // Establecer la licencia
            License.Set("GroupDocs.Markdown.lic")

            // Instanciar el conversor
            let converter = new MarkdownConverter("annual-review.docx")

            // Convertir y guardar la salida en un archivo
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Importar el espacio de nombres  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Establecer la licencia
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instanciar el conversor
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Convertir y guardar la salida en un archivo
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Guardar imágenes en una carpeta"
      content: "Este ejemplo de código muestra cómo convertir un archivo DOCX a Markdown y guardar las imágenes en una carpeta separada."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importar el espacio de nombres
            using GroupDocs.Markdown;

            // Establecer la licencia
            License.Set("GroupDocs.Markdown.lic");

            // Instanciar el conversor
            var converter = new MarkdownConverter("annual-report.docx");

            // Establecer la estrategia de exportación de imágenes y la carpeta de salida
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Convertir y guardar la salida en un archivo
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Importar el espacio de nombres
            open GroupDocs.Markdown

            // Establecer la licencia
            License.Set("GroupDocs.Markdown.lic")

            // Instanciar el conversor
            let converter = new MarkdownConverter("annual-report.docx")

            // Establecer la estrategia de exportación de imágenes y la carpeta de salida
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Convertir y guardar la salida en un archivo
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Importar el espacio de nombres  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Establecer la licencia
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instanciar el conversor
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Establecer la estrategia de exportación de imágenes y la carpeta de salida
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Convertir y guardar la salida en un archivo
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "Reseñas de productos de GroupDocs"
# description: "No te quedes solo con nuestra palabra. Mira lo que otros desarrolladores dicen sobre nuestras API"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Servicio excelente y productos excelentes. Fueron extremadamente serviciales y receptivos durante el proceso de implementación de GroupDocs.Markdown for .NET, no podríamos recomendarlos lo suficiente."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Después de implementar y usar GroupDocs.Markdown for .NET en el proyecto, parece funcionar muy bien. He probado con muchos documentos y hasta ahora todo bien. La salida Markdown es limpia y coherente en todas las fuentes."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

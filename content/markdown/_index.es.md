---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "Exportar documentos a Markdown | GroupDocs"
head_description: "GroupDocs.Markdown es un SDK de procesamiento de documentos que exporta PDF, Word, Excel y otros formatos a Markdown para una integraciÃ³n fluida con el ecosistema de IA generativa."

############################# Header ##########################

title: "Prepare sus documentos para IA"
description: |
  SDK de Markdown para exportar varios tipos de documentos a Markdown limpio y semÃ¡ntico.

  Conserve la estructura del documento, encabezados, listas, tablas, enlaces e imÃ¡genes

  Tome el control de las imÃ¡genes incrustÃ¡ndolas o guardÃ¡ndolas como recursos externos.

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "Elija su plataforma"
  title: "Plataformas compatibles"
  description: "GroupDocs.Markdown admite los siguientes sistemas operativos y marcos."
  details_link_title: "MÃ¡s informaciÃ³n"
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
        - content: "MÃ¡s de 30 formatos de archivo"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "Conjunto de caracterÃ­sticas de GroupDocs.Markdown"
  description: "Estas son las caracterÃ­sticas que hacen que nuestra soluciÃ³n se destaque."

  items:
    # feature loop
    - icon: "convert"
      title: "Exportar documentos a Markdown"
      content: "Prepare su PDF, Word, Excel, eBook y Texto para LLM exportÃ¡ndolos a Markdown."

    # feature loop
    - icon: "structure"
      title: "Conservar la estructura del documento"
      content: "Conserve la estructura del documento, encabezados, listas, tablas, enlaces e imÃ¡genes."

    # feature loop
    - icon: "image"
      title: "Tome el control de las imÃ¡genes"
      content: "Incruste imÃ¡genes o guÃ¡rdelas como recursos externos. Reemplace imÃ¡genes durante el proceso de conversiÃ³n."
    
    # feature loop
    - icon: "settings"
      title: "Convertir documentos completos o pÃ¡ginas especÃ­ficas"
      content: "Convertir documentos completos o limitar la conversiÃ³n a pÃ¡ginas o hojas de cÃ¡lculo especÃ­ficas segÃºn sea necesario."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de cÃ³digo de GroupDocs.Markdown"
  description: "Los escenarios de uso mÃ¡s comunes para exportar documentos a Markdown. Puede solicitar una [licencia temporal gratuita](https://purchase.groupdocs.com/temporary-license) para probar el producto en su entorno."
  items:
    # code sample loop
    - title: "Exportar PDF a Markdown"
      content: |
       Obtenga un archivo Markdown limpio a partir de un archivo PDF en pocas lÃ­neas de cÃ³digo. Por defecto, las imÃ¡genes se incrustan en el archivo de salida.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Importar el espacio de nombres
            using GroupDocs.Markdown;

            // Establecer la licencia
            License.Set("GroupDocs.Markdown.lic");

            // Instanciar el convertidor
            var converter = new MarkdownConverter("business-plan.pdf");

            // Convertir y guardar la salida en un archivo
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "Guardar imÃ¡genes en una carpeta"
      content: |
       Este ejemplo de cÃ³digo muestra cÃ³mo convertir un archivo DOCX a Markdown y guardar las imÃ¡genes en una carpeta separada.
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

            // Establecer la estrategia de exportaciÃ³n de imÃ¡genes y la carpeta de salida
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Convertir y guardar la salida en un archivo
            converter.Convert("annual-report.md", convertOptions);
            ```

############################# Formats ############################

formats:
  enable: true
  title:  "MÃ¡s de 30 formatos de archivo compatibles"
  description: "Los siguientes formatos de archivo son compatibles para exportar a Markdown."
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "MÃ©tricas exhaustivas e informaciÃ³n estadÃ­stica"
  description: "SumÃ©rjase en un desglose detallado de nuestras cifras clave, que ofrece mÃ©tricas completas e informaciÃ³n estadÃ­stica sobre nuestros logros, impacto y crecimiento."

  items:
    # metrics loop
    - number: "180+"
      title: "Formatos compatibles"
      content: "Convierta desde docenas de formatos de documentos y texto, incluidos PDF, Word, Excel y eBooks, a Markdown, proporcionando integraciones sin interrupciones con el ecosistema de IA generativa."
    # metrics loop
    - number: "1.0M"
      title: "Con la confianza de los desarrolladores"
      content: "Nuestras soluciones se han ganado la confianza y son ampliamente adoptadas en la comunidad de desarrolladores, ofreciendo una integraciÃ³n sin problemas para sus proyectos."

    # metrics loop
    - number: "15+"
      title: "Productos"
      content: "Ofrecemos mÃ¡s de 15 SDKs de procesamiento de documentos, brindando una experiencia fluida para sus integraciones. Nosotros procesamos, usted se relaja."
    
    # metrics loop
    - number: "100+"
      title: "Clientes satisfechos"
      content: "Atendiendo a las marcas mÃ¡s icÃ³nicas en todo el mundo. Â¡Descubra por quÃ© cientos adoran los productos de GroupDocs! Â¡Ãšnase ahora!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nuestros clientes satisfechos"
  description: "Las bibliotecas de GroupDocs son utilizadas por marcas reconocidas y distinguidas a nivel mundial."

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
  title: "Â¿Listo para comenzar?"
  description: "Elija la plataforma objetivo para obtener mÃ¡s informaciÃ³n sobre el producto."

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "Preguntas y dudas frecuentes"
  description: "Encuentre respuestas a preguntas frecuentes en nuestra secciÃ³n de FAQ para abordar rÃ¡pidamente sus consultas y dudas."

  items:
    #  loop
    - question: "Â¿Puedo evaluar los productos de GroupDocs antes de comprarlos?"
      answer: |
        Â¡SÃ­! Todos los productos de GroupDocs disponen de una versiÃ³n de evaluaciÃ³n sin riesgo. Recomendamos encarecidamente a los desarrolladores descargar y probar nuestras API antes de comprar, para asegurarse de que satisfarÃ¡n sus necesidades al 100%.
    #  loop
    - question: "Â¿GroupDocs realiza demostraciones de productos?"
      answer: |
        No, nuestro enfoque estÃ¡ en nuestras API y en crear los productos mÃ¡s funcionales y estables posibles. Ofrecemos pruebas gratuitas y totalmente funcionales en forma de una [licencia temporal](https://purchase.groupdocs.com/temporary-license/) para que pueda probar el producto por sÃ­ mismo.
    #  loop
    - question: "Â¿DÃ³nde puedo descargar el producto?"
      answer: |
        Todos los productos estÃ¡n disponibles para descargar desde NuGet o GroupDocs Releases [sitio web](https://releases.groupdocs.com).    
    #  loop
    - question: "Â¿Las licencias de desarrollador de GroupDocs son por usuario o por usuario nombrado?"
      answer: |
        Las licencias de desarrollador de GroupDocs son por usuario, no por usuario nombrado. Entendemos que los miembros de un equipo de desarrollo pueden cambiar con el tiempo y que no es prÃ¡ctico tener que actualizar la licencia cada vez que ocurre.
    #  loop
    - question: "Â¿Proporciona soporte tÃ©cnico?"
      answer: |
        SÃ­, ofrecemos soporte tÃ©cnico gratuito por parte de los equipos de producto en el [Foro de Soporte Gratuito](https://forum.groupdocs.com/c/markdown) y el [Helpdesk de Soporte de Pago](https://helpdesk.groupdocs.com/) para garantizar que su experiencia sea fluida.

############################# Cloud ############################

cloud_links:
  enable: false
  title: "APIs de GroupDocs Cloud"
  description: "Acelere la conversiÃ³n de documentos a Markdown en cualquier aplicaciÃ³n con nuestra API REST basada en la nube"

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "Utilice la API RESTful cURL para convertir Microsoft Office, PDF y otros formatos a Markdown en sus aplicaciones."

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: "SDK Cloud .NET para la conversiÃ³n programÃ¡tica de documentos a Markdown con opciones configurables."
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "SDK Cloud Java para integrar la conversiÃ³n de documentos a Markdown en aplicaciones Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplicaciones en lÃ­nea de GroupDocs"
  description: "AplicaciÃ³n en lÃ­nea que le permite convertir formatos de archivo populares a Markdown en un navegador."

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "Explore una aplicaciÃ³n en lÃ­nea gratuita para convertir varios formatos de archivo directamente a Markdown (.md)."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "Herramienta basada en web para convertir archivos Microsoft Word a Markdown en varios dispositivos."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "Convierta archivos PDF a Markdown en lÃ­nea con una aplicaciÃ³n gratuita de PDF a Markdown."
---

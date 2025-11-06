---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "Exportar documentos a Markdown | GroupDocs"
head_description: "GroupDocs.Markdown es un SDK de procesamiento de documentos que exporta PDF, Word, Excel y otros formatos a Markdown para una integración fluida con el ecosistema de IA generativa."

############################# Header ##########################

title: "Prepare sus documentos para IA"
description: |
  SDK de Markdown para exportar varios tipos de documentos a Markdown limpio y semántico.

  Conserve la estructura del documento, encabezados, listas, tablas, enlaces e imágenes

  Tome el control de las imágenes incrustándolas o guardándolas como recursos externos.

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "Elija su plataforma"
  title: "Plataformas compatibles"
  description: "GroupDocs.Markdown admite los siguientes sistemas operativos y marcos."
  details_link_title: "Más información"
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
        - content: "Más de 30 formatos de archivo"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "Conjunto de características de GroupDocs.Markdown"
  description: "Estas son las características que hacen que nuestra solución se destaque."

  items:
    # feature loop
    - icon: "convert"
      title: "Exportar documentos a Markdown"
      content: "Prepare su PDF, Word, Excel, eBook y Texto para LLM exportándolos a Markdown."

    # feature loop
    - icon: "structure"
      title: "Conservar la estructura del documento"
      content: "Conserve la estructura del documento, encabezados, listas, tablas, enlaces e imágenes."

    # feature loop
    - icon: "image"
      title: "Tome el control de las imágenes"
      content: "Incruste imágenes o guárdelas como recursos externos. Reemplace imágenes durante el proceso de conversión."
    
    # feature loop
    - icon: "settings"
      title: "Convertir documentos completos o páginas específicas"
      content: "Convertir documentos completos o limitar la conversión a páginas o hojas de cálculo específicas según sea necesario."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código de GroupDocs.Markdown"
  description: "Los escenarios de uso más comunes para exportar documentos a Markdown. Puede solicitar una [licencia temporal gratuita](https://purchase.groupdocs.com/temporary-license) para probar el producto en su entorno."
  items:
    # code sample loop
    - title: "Exportar PDF a Markdown"
      content: |
       Obtenga un archivo Markdown limpio a partir de un archivo PDF en pocas líneas de código. Por defecto, las imágenes se incrustan en el archivo de salida.
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
    - title: "Guardar imágenes en una carpeta"
      content: |
       Este ejemplo de código muestra cómo convertir un archivo DOCX a Markdown y guardar las imágenes en una carpeta separada.
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

############################# Formats ############################

formats:
  enable: true
  title:  "Más de 30 formatos de archivo compatibles"
  description: "Los siguientes formatos de archivo son compatibles para exportar a Markdown."
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "Métricas exhaustivas e información estadística"
  description: "Sumérjase en un desglose detallado de nuestras cifras clave, que ofrece métricas completas e información estadística sobre nuestros logros, impacto y crecimiento."

  items:
    # metrics loop
    - number: "180+"
      title: "Formatos compatibles"
      content: "Convierta desde docenas de formatos de documentos y texto, incluidos PDF, Word, Excel y eBooks, a Markdown, proporcionando integraciones sin interrupciones con el ecosistema de IA generativa."
    # metrics loop
    - number: "1.0M"
      title: "Con la confianza de los desarrolladores"
      content: "Nuestras soluciones se han ganado la confianza y son ampliamente adoptadas en la comunidad de desarrolladores, ofreciendo una integración sin problemas para sus proyectos."

    # metrics loop
    - number: "15+"
      title: "Productos"
      content: "Ofrecemos más de 15 SDKs de procesamiento de documentos, brindando una experiencia fluida para sus integraciones. Nosotros procesamos, usted se relaja."
    
    # metrics loop
    - number: "100+"
      title: "Clientes satisfechos"
      content: "Atendiendo a las marcas más icónicas en todo el mundo. ¡Descubra por qué cientos adoran los productos de GroupDocs! ¡Únase ahora!"


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
  title: "¿Listo para comenzar?"
  description: "Elija la plataforma objetivo para obtener más información sobre el producto."

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "Preguntas y dudas frecuentes"
  description: "Encuentre respuestas a preguntas frecuentes en nuestra sección de FAQ para abordar rápidamente sus consultas y dudas."

  items:
    #  loop
    - question: "¿Puedo evaluar los productos de GroupDocs antes de comprarlos?"
      answer: |
        ¡Sí! Todos los productos de GroupDocs disponen de una versión de evaluación sin riesgo. Recomendamos encarecidamente a los desarrolladores descargar y probar nuestras API antes de comprar, para asegurarse de que satisfarán sus necesidades al 100%.
    #  loop
    - question: "¿GroupDocs realiza demostraciones de productos?"
      answer: |
        No, nuestro enfoque está en nuestras API y en crear los productos más funcionales y estables posibles. Ofrecemos pruebas gratuitas y totalmente funcionales en forma de una [licencia temporal](https://purchase.groupdocs.com/temporary-license/) para que pueda probar el producto por sí mismo.
    #  loop
    - question: "¿Dónde puedo descargar el producto?"
      answer: |
        Todos los productos están disponibles para descargar desde NuGet o GroupDocs Releases [sitio web](https://releases.groupdocs.com).    
    #  loop
    - question: "¿Las licencias de desarrollador de GroupDocs son por usuario o por usuario nombrado?"
      answer: |
        Las licencias de desarrollador de GroupDocs son por usuario, no por usuario nombrado. Entendemos que los miembros de un equipo de desarrollo pueden cambiar con el tiempo y que no es práctico tener que actualizar la licencia cada vez que ocurre.
    #  loop
    - question: "¿Proporciona soporte técnico?"
      answer: |
        Sí, ofrecemos soporte técnico gratuito por parte de los equipos de producto en el [Foro de Soporte Gratuito](https://forum.groupdocs.com/c/markdown) y el [Helpdesk de Soporte de Pago](https://helpdesk.groupdocs.com/) para garantizar que su experiencia sea fluida.

############################# Cloud ############################

cloud_links:
  enable: false
  title: "APIs de GroupDocs Cloud"
  description: "Acelere la conversión de documentos a Markdown en cualquier aplicación con nuestra API REST basada en la nube"

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
      content: "SDK Cloud .NET para la conversión programática de documentos a Markdown con opciones configurables."
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "SDK Cloud Java para integrar la conversión de documentos a Markdown en aplicaciones Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplicaciones en línea de GroupDocs"
  description: "Aplicación en línea que le permite convertir formatos de archivo populares a Markdown en un navegador."

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "Explore una aplicación en línea gratuita para convertir varios formatos de archivo directamente a Markdown (.md)."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "Herramienta basada en web para convertir archivos Microsoft Word a Markdown en varios dispositivos."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "Convierta archivos PDF a Markdown en línea con una aplicación gratuita de PDF a Markdown."
---

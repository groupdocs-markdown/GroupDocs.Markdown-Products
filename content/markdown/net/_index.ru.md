---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ru
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

head_title: "Экспорт документов в Markdown в .NET | GroupDocs"
head_description: "GroupDocs.Markdown для .NET — это API обработки документов, который экспортирует PDF, Word, Excel и другие форматы в Markdown для бесшовной интеграции с экосистемой генеративного ИИ."

############################# Header ##########################

title: "Экспортируйте документы в Markdown<br>с помощью .NET API"
description: "API конвертации Markdown для экспорта популярных форматов документов в чистый Markdown с полным контролем."
words:
  for: "for"

actions:
  main: "Бесплатная загрузка NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Markdown бесплатно или запросите лицензию"

release:
  hidden: false
  title: "Версия {0}&nbsp;выпущена"
  notes: "Смотрите, что нового"
  downloads: "Загрузки"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Экспорт PDF в Markdown на C#"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Импортировать пространство имен
    using GroupDocs.Markdown;

    // Установить лицензию
    License.Set("GroupDocs.Markdown.lic");

    // Создать экземпляр конвертера
    var converter = new MarkdownConverter("business-plan.pdf");

    // Конвертировать и сохранить выходной файл Markdown
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown в одном взгляде"
  description: "API для разбора и экспорта документов в Markdown в приложениях .NET."
  features:
    # feature loop
    - title: "Точная и надёжная конвертация"
      content: "Эффективно конвертируйте поддерживаемые форматы в Markdown, сохраняя целостность структуры. Поддерживает .NET Framework 4.6.2+ и .NET 6.0 на Windows и Linux."

    # feature loop
    - title: "Поддержка популярных форматов"
      content: "Экспортируйте PDF, Word, Excel, электронные книги, веб‑страницы и обычные текстовые файлы в Markdown, включая документы, защищённые паролем."

    # feature loop
    - title: "Работает на вашем локальном компьютере"
      content: "Вы контролируете свои данные — мы предоставляем локальное API, которое не требует облака или интернет‑соединения."

############################# Platforms ############################
platforms:
  enable: true
  title: "Поддержка платформ"
  description: "Поддерживаются следующие операционные системы, фреймворки и менеджеры пакетов."
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
  title: "Поддерживаемые форматы файлов"
  description: |
    Для экспорта в Markdown поддерживаются следующие форматы файлов.
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
        ### Word и Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### Другие   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "Функции GroupDocs.Markdown"
  description: "Это функции, которые выделяют наш продукт."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Экспорт нескольких форматов документов"
      content: "Преобразуйте наиболее популярные форматы документов в Markdown (PDF, DOCX, XLSX, EPUB и другие)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Продвинутое форматирование Markdown"
      content: "Заголовки, абзацы, списки, таблицы, ссылки, изображения, блоки цитат и блоки кода экспортируются в соответствующий синтаксис Markdown."

    # feature loop
    - icon: "control_over_images"
      title: "Полный контроль над изображениями"
      content: "Получите контроль над изображениями, экспортируя их или внедряя в выходной файл Markdown."

    # feature loop
    - icon: "secure"
      title: "Работает на вашем локальном компьютере"
      content: "Не требуется облако или подключение к Интернету. Вся обработка выполняется на вашем локальном компьютере."

    # feature loop
    - icon: "intuitive"
      title: "Интуитивный публичный API"
      content: "Простой и интуитивный публичный API, созданный разработчиками для разработчиков с любовью."

    # feature loop
    - icon: "cross_platform"
      title: "Работает на Windows и Linux"
      content: ".NET и .NET Framework сборки предоставляются в пакете NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Примеры кода"
  description: "Наиболее распространённые сценарии экспорта документов в Markdown в приложениях .NET."
  items:
    # code sample loop
    - title: "Экспорт DOCX в Markdown"
      content: "Этот пример кода показывает, как конвертировать файл DOCX в Markdown и сохранить результат в файл. Изображения встроены в выходной файл."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Подключите пространство имён
            using GroupDocs.Markdown;

            // Установите лицензию
            License.Set("GroupDocs.Markdown.lic");

            // Создайте экземпляр конвертера
            var converter = new MarkdownConverter("annual-review.docx");

            // Выполните конвертацию и сохраните результат в файл
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Подключите пространство имён  
            open GroupDocs.Markdown

            // Установите лицензию
            License.Set("GroupDocs.Markdown.lic")

            // Создайте экземпляр конвертера
            let converter = new MarkdownConverter("annual-review.docx")

            // Выполните конвертацию и сохраните результат в файл
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Подключите пространство имён  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Установите лицензию
                    License.Set("GroupDocs.Markdown.lic")

                    ' Создайте экземпляр конвертера
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Выполните конвертацию и сохраните результат в файл
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Сохранить изображения в папку"
      content: "Этот пример кода показывает, как конвертировать файл DOCX в Markdown и сохранить изображения в отдельную папку."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Подключите пространство имён
            using GroupDocs.Markdown;

            // Установите лицензию
            License.Set("GroupDocs.Markdown.lic");

            // Создайте экземпляр конвертера
            var converter = new MarkdownConverter("annual-report.docx");

            // Установите стратегию экспорта изображений и папку вывода
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Выполните конвертацию и сохраните результат в файл
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Подключите пространство имён
            open GroupDocs.Markdown

            // Установите лицензию
            License.Set("GroupDocs.Markdown.lic")

            // Создайте экземпляр конвертера
            let converter = new MarkdownConverter("annual-report.docx")

            // Установите стратегию экспорта изображений и папку вывода
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Выполните конвертацию и сохраните результат в файл
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Подключите пространство имён  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Установите лицензию
                    License.Set("GroupDocs.Markdown.lic")

                    ' Создайте экземпляр конвертера
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Установите стратегию экспорта изображений и папку вывода
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Выполните конвертацию и сохраните результат в файл
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "Отзывы о продуктах GroupDocs"
# description: "Не просто полагайтесь на наши слова. Посмотрите, что говорят другие разработчики о наших API."

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Отличный сервис и отличные продукты. Они были чрезвычайно полезны и оперативны во время процесса внедрения GroupDocs.Markdown for .NET, не могу рекомендовать их достаточно."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "После внедрения и использования GroupDocs.Markdown for .NET в проекте, он работает очень хорошо. Я протестировал его на множестве документов, и пока всё в порядке. Вывод в формате Markdown чистый и согласованный во всех источниках."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

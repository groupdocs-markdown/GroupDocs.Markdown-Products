---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: uk
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

head_title: "Експорт документів у Markdown у .NET | GroupDocs"
head_description: "GroupDocs.Markdown для .NET — це API обробки документів, який експортує PDF, Word, Excel та інші формати у Markdown для безперешкодної інтеграції з екосистемою генеративного ШІ."

############################# Header ##########################

title: "Експортуйте документи у Markdown<br>за допомогою .NET API"
description: "API конвертації Markdown для експорту популярних форматів документів у чистий Markdown з повним контролем."
words:
  for: "for"

actions:
  main: "Безкоштовне завантаження NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Готові розпочати?"
  description: "Спробуйте функції GroupDocs.Markdown безкоштовно або запросіть ліцензію"

release:
  hidden: false
  title: "Випущено версію {0}&nbsp;"
  notes: "Дивіться, що нового"
  downloads: "Завантаження"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Експорт PDF у Markdown на C#"
  more: "Більше прикладів"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Імпортуйте простір імен
    using GroupDocs.Markdown;

    // Встановіть ліцензію
    License.Set("GroupDocs.Markdown.lic");

    // Створіть екземпляр конвертера
    var converter = new MarkdownConverter("business-plan.pdf");

    // Конвертуйте та збережіть вихідний файл Markdown
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown в одному погляді"
  description: "API для розбору та експорту документів у Markdown у .NET застосунках."
  features:
    # feature loop
    - title: "Точна та надійна конвертація"
      content: "Ефективно конвертуйте підтримувані формати у Markdown, зберігаючи цілісність структури. Підтримує .NET Framework 4.6.2+ та .NET 6.0 на Windows і Linux."

    # feature loop
    - title: "Підтримуються популярні формати"
      content: "Експортуйте PDF, Word, Excel, електронні книги, веб та прості текстові файли у Markdown, включаючи документи, захищені паролем."

    # feature loop
    - title: "Працює на вашій локальній машині"
      content: "Ви контролюєте свої дані — ми надаємо локальне API, яке не вимагає жодного підключення до хмари або інтернету."

############################# Platforms ############################
platforms:
  enable: true
  title: "Підтримка платформ"
  description: "Підтримуються наступні операційні системи, фреймворки та менеджери пакетів."
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
  title: "Підтримувані формати файлів"
  description: |
    Наступні формати файлів підтримуються для експорту в Markdown.
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
        ### Word та Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### Інші   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "Функції GroupDocs.Markdown"
  description: "Це функції, які виділяють наш продукт."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Експорт декількох форматів документів"
      content: "Перетворюйте найпопулярніші формати документів у Markdown (PDF, DOCX, XLSX, EPUB та інші)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Розширене форматування Markdown"
      content: "Заголовки, абзаци, списки, таблиці, посилання, зображення, блоки цитат та блоки коду експортуються у відповідний синтаксис Markdown."

    # feature loop
    - icon: "control_over_images"
      title: "Повний контроль над зображеннями"
      content: "Отримайте контроль над зображеннями, експортуючи їх або вбудовуючи у вихідний файл Markdown."

    # feature loop
    - icon: "secure"
      title: "Працює на вашій локальній машині"
      content: "Не потрібні хмара або підключення до Інтернету. Уся обробка виконується на вашій локальній машині."

    # feature loop
    - icon: "intuitive"
      title: "Інтуїтивний публічний API"
      content: "Простий та інтуїтивний публічний API, створений розробниками для розробників з любов'ю."

    # feature loop
    - icon: "cross_platform"
      title: "Працює на Windows і Linux"
      content: ".NET та .NET Framework збірки постачаються у пакеті NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Приклади коду"
  description: "Найпоширеніші сценарії використання експорту документів у Markdown у застосунках .NET."
  items:
    # code sample loop
    - title: "Експортувати DOCX у Markdown"
      content: "Цей приклад коду показує, як конвертувати файл DOCX у Markdown та зберегти результат у файл. Зображення вбудовані у вихідний файл."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Імпортувати простір імен
            using GroupDocs.Markdown;

            // Встановити ліцензію
            License.Set("GroupDocs.Markdown.lic");

            // Створити екземпляр конвертера
            var converter = new MarkdownConverter("annual-review.docx");

            // Конвертувати та зберегти результат у файл
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Імпортувати простір імен  
            open GroupDocs.Markdown

            // Встановити ліцензію
            License.Set("GroupDocs.Markdown.lic")

            // Створити екземпляр конвертера
            let converter = new MarkdownConverter("annual-review.docx")

            // Конвертувати та зберегти результат у файл
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Імпортувати простір імен  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Встановити ліцензію
                    License.Set("GroupDocs.Markdown.lic")

                    ' Створити екземпляр конвертера
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Конвертувати та зберегти результат у файл
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Зберегти зображення у папку"
      content: "Цей приклад коду показує, як конвертувати файл DOCX у Markdown та зберегти зображення у окрему папку."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Імпортувати простір імен
            using GroupDocs.Markdown;

            // Встановити ліцензію
            License.Set("GroupDocs.Markdown.lic");

            // Створити екземпляр конвертера
            var converter = new MarkdownConverter("annual-report.docx");

            // Встановити стратегію експорту зображень та папку виводу
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Конвертувати та зберегти результат у файл
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Імпортувати простір імен
            open GroupDocs.Markdown

            // Встановити ліцензію
            License.Set("GroupDocs.Markdown.lic")

            // Створити екземпляр конвертера
            let converter = new MarkdownConverter("annual-report.docx")

            // Встановити стратегію експорту зображень та папку виводу
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Конвертувати та зберегти результат у файл
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Імпортувати простір імен  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Встановити ліцензію
                    License.Set("GroupDocs.Markdown.lic")

                    ' Створити екземпляр конвертера
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Встановити стратегію експорту зображень та папку виводу
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Конвертувати та зберегти результат у файл
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "Відгуки про продукти GroupDocs"
# description: "Не лише вірте нам на слово. Дізнайтеся, що інші розробники говорять про наші API"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Відмінний сервіс і чудові продукти. Вони були надзвичайно корисними та оперативними під час процесу впровадження GroupDocs.Markdown для .NET, не можу їх достатньо порекомендувати."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Після впровадження та використання GroupDocs.Markdown для .NET у проекті, здається, все працює дуже добре. Я протестував багато документів і поки що все в порядку. Вивід у Markdown чистий і послідовний у всіх джерелах."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

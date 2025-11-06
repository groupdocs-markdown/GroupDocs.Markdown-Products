---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fa
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

head_title: "صادرات اسناد به Markdown در .NET | GroupDocs"
head_description: "GroupDocs.Markdown برای .NET یک API پردازش اسناد است که PDF، Word، Excel و سایر فرمت‌ها را به Markdown صادر می‌کند تا یکپارچه‌سازی بی‌دردسر با اکوسیستم هوش مصنوعی ژنراتور فراهم شود."

############################# Header ##########################

title: "صادرات اسناد به Markdown<br>با استفاده از API .NET"
description: "API تبدیل Markdown برای صادرات فرمت‌های محبوب اسناد به Markdown تمیز با کنترل کامل."
words:
  for: "for"

actions:
  main: "دانلود رایگان NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "مجوزدهی"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "آماده‌اید که شروع کنید؟"
  description: "ویژگی‌های GroupDocs.Markdown را به‌صورت رایگان امتحان کنید یا درخواست یک لایسنس کنید"

release:
  hidden: false
  title: "نسخه {0}&nbsp;منتشر شد"
  notes: "جدیدها را ببینید"
  downloads: "دانلودها"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "صادرات PDF به Markdown در C#"
  more: "مثال‌های بیشتر"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // وارد کردن فضای نام
    using GroupDocs.Markdown;

    // تنظیم مجوز
    License.Set("GroupDocs.Markdown.lic");

    // ایجاد نمونه مبدل
    var converter = new MarkdownConverter("business-plan.pdf");

    // تبدیل و ذخیره‌سازی فایل خروجی Markdown
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "نگاهی کلی به GroupDocs.Markdown"
  description: "API برای تجزیه و صادرات اسناد به Markdown در برنامه‌های .NET."
  features:
    # feature loop
    - title: "تبدیل دقیق و قابل اعتماد"
      content: "به‌صورت کارآمد فرمت‌های پشتیبانی‌شده را به Markdown تبدیل می‌کند در حالی که یکپارچگی ساختار را حفظ می‌کند. از .NET Framework 4.6.2+ و .NET 6.0 روی ویندوز و لینوکس پشتیبانی می‌کند."

    # feature loop
    - title: "فرمت‌های محبوب پشتیبانی‌شده"
      content: "PDF، Word، Excel، eBooks، وب و فایل‌های متنی ساده را به Markdown صادر می‌کند، از جمله اسناد محافظت‌شده با رمز عبور."

    # feature loop
    - title: "در ماشین محلی شما اجرا می‌شود"
      content: "شما کنترل داده‌های خود را دارید - ما یک API در محل ارائه می‌دهیم که نیازی به فضای ابری یا اتصال به اینترنت ندارد."

############################# Platforms ############################
platforms:
  enable: true
  title: "پشتیبانی از پلتفرم‌ها"
  description: "سیستم‌عامل‌ها، چارچوب‌ها و مدیریت‌کننده‌های بسته زیر پشتیبانی می‌شوند."
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
  title: "فرمت‌های فایل پشتیبانی‌شده"
  description: |
    قالب‌های فایل زیر برای صادرات به Markdown پشتیبانی می‌شوند.
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
        ### Word و Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### سایر   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "ویژگی‌های GroupDocs.Markdown"
  description: "این‌ها ویژگی‌هایی هستند که محصول ما را متمایز می‌کنند."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "صادرات چندین فرمت سند"
      content: "اکثریت فرمت‌های سند محبوب را به Markdown تبدیل کنید (PDF، DOCX، XLSX، EPUB و دیگران)."

    # feature loop
    - icon: "advanced_formatting"
      title: "قالب‌بندی پیشرفتهٔ Markdown"
      content: "سرعنوان‌ها، پاراگراف‌ها، فهرست‌ها، جدول‌ها، لینک‌ها، تصاویر، نقل‌قول‌های بلوکی و بلاک‌های کد به نحو مناسب Markdown صادر می‌شوند."

    # feature loop
    - icon: "control_over_images"
      title: "کنترل کامل بر تصاویر"
      content: "با صادرات تصاویر یا جاسازی آن‌ها در فایل خروجی Markdown، کنترل را بر تصاویر به دست بگیرید."

    # feature loop
    - icon: "secure"
      title: "در ماشین محلی شما اجرا می‌شود"
      content: "نیاز به ابر یا اتصال به اینترنت نیست. تمام پردازش‌ها در ماشین محلی شما انجام می‌شود."

    # feature loop
    - icon: "intuitive"
      title: "API عمومی شهودی"
      content: "API عمومی ساده و شهودی که توسط توسعه‌دهندگان برای توسعه‌دهندگان و با عشق طراحی شده است."

    # feature loop
    - icon: "cross_platform"
      title: "در ویندوز و لینوکس کار می‌کند"
      content: "اسمبلی‌های .NET و .NET Framework درون بسته NuGet فراهم شده‌اند."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "نمونه‌های کد"
  description: "متداول‌ترین سناریوهای استفاده برای صادرات اسناد به Markdown در برنامه‌های .NET."
  items:
    # code sample loop
    - title: "صادرات DOCX به Markdown"
      content: "این نمونه کد نشان می‌دهد چگونه یک فایل DOCX را به Markdown تبدیل کرده و خروجی را در یک فایل ذخیره کنید. تصاویر در فایل خروجی جاسازی می‌شوند."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // وارد کردن فضای نام
            using GroupDocs.Markdown;

            // تنظیم لایسنس
            License.Set("GroupDocs.Markdown.lic");

            // ایجاد نمونه‌ی مبدل
            var converter = new MarkdownConverter("annual-review.docx");

            // تبدیل و ذخیره خروجی در فایل
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // وارد کردن فضای نام  
            open GroupDocs.Markdown

            // تنظیم لایسنس
            License.Set("GroupDocs.Markdown.lic")

            // ایجاد نمونه‌ی مبدل
            let converter = new MarkdownConverter("annual-review.docx")

            // تبدیل و ذخیره خروجی در فایل
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' وارد کردن فضای نام  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' تنظیم لایسنس
                    License.Set("GroupDocs.Markdown.lic")

                    ' ایجاد نمونه‌ی مبدل
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' تبدیل و ذخیره خروجی در فایل
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "ذخیره تصاویر در یک پوشه"
      content: "این نمونه کد نشان می‌دهد چگونه یک فایل DOCX را به Markdown تبدیل کرده و تصاویر را در یک پوشه جداگانه ذخیره کنید."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // وارد کردن فضای نام
            using GroupDocs.Markdown;

            // تنظیم لایسنس
            License.Set("GroupDocs.Markdown.lic");

            // ایجاد نمونه‌ی مبدل
            var converter = new MarkdownConverter("annual-report.docx");

            // تنظیم استراتژی صادرات تصویر و پوشه خروجی
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // تبدیل و ذخیره خروجی در فایل
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // وارد کردن فضای نام
            open GroupDocs.Markdown

            // تنظیم لایسنس
            License.Set("GroupDocs.Markdown.lic")

            // ایجاد نمونه‌ی مبدل
            let converter = new MarkdownConverter("annual-report.docx")

            // تنظیم استراتژی صادرات تصویر و پوشه خروجی
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // تبدیل و ذخیره خروجی در فایل
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' وارد کردن فضای نام  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' تنظیم لایسنس
                    License.Set("GroupDocs.Markdown.lic")

                    ' ایجاد نمونه‌ی مبدل
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' تنظیم استراتژی صادرات تصویر و پوشه خروجی
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' تبدیل و ذخیره خروجی در فایل
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "نقد و بررسی‌های محصولات GroupDocs"
# description: "فقط به حرف ما اکتفا نکنید. ببینید دیگر توسعه‌دهندگان درباره APIهای ما چه می‌گویند"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "سرویس عالی و محصولات فوق‌العاده. آن‌ها در فرآیند پیاده‌سازی GroupDocs.Markdown برای .NET بسیار کمک‌کننده و پاسخگو بودند، نمی‌توان آن‌ها را به اندازه کافی توصیه کرد."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "پس از پیاده‌سازی و استفاده از GroupDocs.Markdown برای .NET در پروژه، به نظر می‌رسد که بسیار خوب کار می‌کند. من با تعداد زیادی سند تست کرده‌ام و تا به حال همه چیز خوب است. خروجی Markdown تمیز و سازگار در تمام منابع است."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

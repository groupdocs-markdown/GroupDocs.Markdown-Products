---
############################# Static ##########################

layout: "family"
date: 2025-08-21T00:00:00
draft: false

product: "Markdown"
product_tag: "markdown"

############################# Head ############################

head_title: "صادرات اسناد به Markdown | GroupDocs"
head_description: "GroupDocs.Markdown یک SDK پردازش سند است که PDF، Word، Excel و سایر قالب‌ها را به Markdown صادر می‌کند برای یکپارچگی بی‌نقص با اکوسیستم هوش مصنوعی مولد."

############################# Header ##########################

title: "اسناد خود را برای هوش مصنوعی آماده کنید"
description: |
  SDK Markdown برای صادرات انواع اسناد به Markdown تمیز و معنایی.

  ساختار سند، سرفصل‌ها، فهرست‌ها، جداول، پیوندها و تصاویر را حفظ کنید

  کنترل تصاویر را در دست بگیرید؛ آنها را جاسازی کنید یا به عنوان منابع خارجی ذخیره کنید.

############################# Platforms ############################

supported_platforms:
  enable: true  
  head_title: "پلتفرم خود را انتخاب کنید"
  title: "پلتفرم‌های پشتیبانی‌شده"
  description: "GroupDocs.Markdown از سیستم‌عامل‌ها و فریم‌ورک‌های زیر پشتیبانی می‌کند."
  details_link_title: "بیشتر بخوانید"
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
        - content: "بیش از ۳۰ قالب فایل"
          rows: "1"

############################# Features ############################

features:
  enable: true
  title: "مجموعه ویژگی‌های GroupDocs.Markdown"
  description: "این‌ها ویژگی‌هایی هستند که راه‌حل ما را متمایز می‌کند."

  items:
    # feature loop
    - icon: "convert"
      title: "صادرات اسناد به Markdown"
      content: "اسناد PDF، Word، Excel، eBook و Text خود را با صادرات به Markdown برای LLM آماده کنید."

    # feature loop
    - icon: "structure"
      title: "ساختار سند را حفظ کنید"
      content: "ساختار سند، سرفصل‌ها، فهرست‌ها، جداول، پیوندها و تصاویر را حفظ کنید."

    # feature loop
    - icon: "image"
      title: "کنترل تصاویر را به دست بگیرید"
      content: "تصاویر را جاسازی کنید یا به عنوان منابع خارجی ذخیره کنید. تصاویر را در طول فرایند تبدیل جایگزین کنید."
    
    # feature loop
    - icon: "settings"
      title: "تبدیل کل اسناد یا صفحات خاص"
      content: "کل اسناد را تبدیل کنید یا تبدیل را به صفحات یا کاربرگ‌های خاص محدود کنید."


############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه‌های کد GroupDocs.Markdown"
  description: "متداول‌ترین سناریوهای استفاده برای صادرات اسناد به Markdown. می‌توانید یک [مجوز موقت رایگان](https://purchase.groupdocs.com/temporary-license) درخواست کنید تا محصول را در محیط خود آزمایش کنید."
  items:
    # code sample loop
    - title: "صادرات PDF به Markdown"
      content: |
       فایلی تمیز از نوع Markdown را از یک فایل PDF با چند خط کد دریافت کنید. به‌طور پیش‌فرض، تصاویر در فایل خروجی جاسازی می‌شوند.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // وارد کردن فضای نام
            using GroupDocs.Markdown;

            // تنظیم مجوز
            License.Set("GroupDocs.Markdown.lic");

            // ایجاد نمونه مبدل
            var converter = new MarkdownConverter("business-plan.pdf");

            // تبدیل و ذخیره خروجی به فایل
            converter.Convert("business-plan.md");
            ```
    # code sample loop
    - title: "ذخیره تصاویر در یک پوشه"
      content: |
       این نمونه کد نشان می‌دهد چگونه یک فایل DOCX را به Markdown تبدیل کنید و تصاویر را در یک پوشه جداگانه ذخیره کنید.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // وارد کردن فضای نام
            using GroupDocs.Markdown;

            // مجوز را تنظیم کنید
            License.Set("GroupDocs.Markdown.lic");

            // ایجاد نمونه مبدل
            var converter = new MarkdownConverter("annual-report.docx");

            // استراتژی صادرات تصویر و پوشه خروجی را تنظیم کنید
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // تبدیل کنید و خروجی را در فایل ذخیره کنید
            converter.Convert("annual-report.md", convertOptions);
            ```

############################# Formats ############################

formats:
  enable: true
  title:  "پشتیبانی از بیش از 30 فرمت فایل"
  description: "فرمت‌های فایل زیر برای خروجی به Markdown پشتیبانی می‌شوند."
  formats_img: "markdown"

############################# Metrics ############################

metrics:
  enable: true
  title: "متریک‌ها و بینش‌های آماری دقیق"
  description: "به تجزیه و تحلیل دقیق از ارقام کلیدی ما پرداخته و متریک‌ها و بینش‌های آماری جامع درباره دستاوردها، تأثیر و رشد ما ارائه می‌دهیم."

  items:
    # metrics loop
    - number: "180+"
      title: "فرمت‌های پشتیبانی‌شده"
      content: "از ده‌ها فرمت سند و متن شامل PDF، Word، Excel و کتاب‌های الکترونیکی به Markdown تبدیل کنید و یکپارچگی بی‌وقفه با اکوسیستم gen AI را فراهم می‌آورد."
    # metrics loop
    - number: "1.0M"
      title: "قابل اعتماد توسط توسعه‌دهندگان"
      content: "راه‌حل‌های ما به‌عنوان گزینه‌ای قابل اعتماد و به‌ طور گسترده در جامعه توسعه‌دهندگان پذیرفته شده‌اند و یکپارچگی بی‌وقفه‌ای برای پروژه‌های شما فراهم می‌کنند."

    # metrics loop
    - number: "15+"
      title: "محصولات"
      content: "بیش از 15 SDK پردازش سند ارائه می‌دهیم که تجربهٔ یکپارچه‌ای برای ادغام‌های شما فراهم می‌کند. ما پردازش را انجام می‌دهیم تا شما آرام باشید."
    
    # metrics loop
    - number: "100+"
      title: "مشتریان راضی"
      content: "در خدمت برترین برندهای شناخته‌شده در سراسر جهان. کشف کنید چرا صدها نفر محصولات GroupDocs را دوست دارند! هم‌اکنون بپیوندید!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "مشتریان راضی ما"
  description: "کتابخانه‌های GroupDocs توسط برندهای مشهور و برجستهٔ جهانی در سراسر دنیا به‌کار گرفته می‌شوند."

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
  title: "آماده‌اید تا شروع کنید؟"
  description: "پلتفرم هدف خود را انتخاب کنید تا اطلاعات بیشتری درباره محصول کسب کنید."

  items:
    #  loop
    - title: ".NET"
      link: "/markdown/net/"
      color: "blue"

############################# Faq ############################

faq:
  enable: true
  title: "سوالات و نگرانی‌های رایج"
  description: "پاسخ سؤالات متداول را در بخش FAQ ما پیدا کنید تا به‌سرعت به پرسش‌ها و نگرانی‌های خود رسیدگی کنید."

  items:
    #  loop
    - question: "آیا می‌توانم محصولات GroupDocs را پیش از خرید ارزیابی کنم؟"
      answer: |
        بله! تمام محصولات GroupDocs نسخهٔ ارزیابی بدون ریسک دارند. ما به شدت توسعه‌دهندگان را تشویق می‌کنیم تا قبل از خرید، API‌های ما را دانلود و امتحان کنند تا اطمینان حاصل شود که 100٪ نیازهای شما را برآورده می‌کنند.
    #  loop
    - question: "آیا GroupDocs نمایش‌های محصول ارائه می‌دهد؟"
      answer: |
        خیر، تمرکز ما بر روی APIها و ساختن کارآمدترین و پایدارترین محصولات است. ما نسخه‌های آزمایشی کاملاً عملکردی و رایگان را به شکل یک [مجوز موقت](https://purchase.groupdocs.com/temporary-license/) ارائه می‌دهیم تا خودتان محصول را امتحان کنید.
    #  loop
    - question: "از کجا می‌توانم محصول را دانلود کنم؟"
      answer: |
        تمام محصولات می‌توانند از NuGet یا وب‌سایت GroupDocs Releases [وب‌سایت](https://releases.groupdocs.com) دانلود شوند.    
    #  loop
    - question: "آیا لایسنس‌های توسعه‌دهنده GroupDocs به‌صورت کاربر-محور هستند یا به‌صورت کاربر نام‌گذاری شده؟"
      answer: |
        لایسنس‌های توسعه‌دهنده GroupDocs به‌صورت کاربر-محور هستند، نه به‌صورت کاربر نام‌گذاری شده. ما می‌دانیم که اعضای تیم برنامه‌نویسی ممکن است به‌مرور زمان تغییر کنند و به‌روزرسانی مداوم لایسنس‌ها در هر بار این تغییر عملی نیست.
    #  loop
    - question: "آیا پشتیبانی فنی ارائه می‌دهید؟"
      answer: |
        بله، ما پشتیبانی فنی رایگان توسط تیم‌های محصول در [Free Support Forum](https://forum.groupdocs.com/c/markdown) و [Paid Support Helpdesk](https://helpdesk.groupdocs.com/) ارائه می‌دهیم تا تجربهٔ شما روان باشد.

############################# Cloud ############################

cloud_links:
  enable: false
  title: "APIهای ابری GroupDocs"
  description: "تبدیل سند به Markdown را در هر برنامه‌ای با API REST مبتنی بر ابر ما شتاب دهید"

  items:
    #  loop
    - icon: "groupdocs_markdown-for-curl"
      title: "GroupDocs.Markdown Cloud for cURL"
      link: "https://products.groupdocs.cloud/markdown/curl"
      content: "از API RESTful cURL برای تبدیل Microsoft Office، PDF و سایر فرمت‌ها به Markdown در برنامه‌های خود استفاده کنید."

    #  loop
    - icon: "groupdocs_markdown-for-net"
      title: "GroupDocs.Markdown Cloud for .NET"
      link: "https://products.groupdocs.cloud/markdown/net"
      content: "SDK ابری .NET برای تبدیل برنامه‌ای سند به Markdown با گزینه‌های قابل پیکربندی."
    #  loop
    - icon: "groupdocs_markdown-for-java"
      title: "GroupDocs.Markdown Cloud for Java"
      link: "https://products.groupdocs.cloud/markdown/java"
      content: "SDK ابری Java برای یکپارچه‌سازی تبدیل سند به Markdown در برنامه‌های Java."

############################# Apps ############################

app_links:
  enable: true
  title: "برنامه‌های آنلاین GroupDocs"
  description: "برنامهٔ آنلاین که امکان تبدیل فرمت‌های محبوب فایل به Markdown را در مرورگر فراهم می‌کند."

  items:
    #  loop
    - icon: "groupdocs_conversion-app"
      title: "GroupDocs.Conversion Total"
      link: "https://products.groupdocs.app/conversion/total"
      content: "یک برنامهٔ آنلاین رایگان را بررسی کنید تا فرمت‌های مختلف فایل را مستقیماً به Markdown (.md) تبدیل کنید."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion DOCX"
      link: "https://products.groupdocs.app/conversion/docx"
      content: "ابزار وب برای تبدیل فایل‌های Microsoft Word به Markdown در تمام دستگاه‌ها."

    #  loop
    - icon: "groupdocs_conversion-app"
      title:  "GroupDocs.Conversion PDF"
      link: "https://products.groupdocs.app/markdown/pdf"
      content: "فایل‌های PDF را به‌صورت آنلاین به Markdown تبدیل کنید با برنامهٔ رایگان PDF‑to‑Markdown."
---

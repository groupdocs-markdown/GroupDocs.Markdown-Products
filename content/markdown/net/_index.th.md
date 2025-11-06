---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: th
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

head_title: "ส่งออกเอกสารเป็น Markdown ใน .NET | GroupDocs"
head_description: "GroupDocs.Markdown สำหรับ .NET คือ API การประมวลผลเอกสารที่ส่งออก PDF, Word, Excel และรูปแบบอื่น ๆ ไปเป็น Markdown เพื่อการบูรณาการอย่างราบรื่นกับระบบนิเวศ AI ที่สร้างสรรค์."

############################# Header ##########################

title: "ส่งออกเอกสารเป็น Markdown<br>โดยใช้ .NET API"
description: "API การแปลง Markdown เพื่อส่งออกรูปแบบเอกสารยอดนิยมเป็น Markdown ที่สะอาดด้วยการควบคุมเต็มรูปแบบ."
words:
  for: "for"

actions:
  main: "ดาวน์โหลด NuGet ฟรี"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "การให้สิทธิ์ใช้งาน"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "พร้อมเริ่มใช้งานหรือยัง?"
  description: "ทดลองใช้คุณสมบัติของ GroupDocs.Markdown ฟรีหรือขอรับใบอนุญาต"

release:
  hidden: false
  title: "รุ่น {0}&nbsp;เปิดตัวแล้ว"
  notes: "ดูสิ่งใหม่ๆ"
  downloads: "ดาวน์โหลด"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "ส่งออก PDF ไปเป็น Markdown ด้วย C#"
  more: "ตัวอย่างเพิ่มเติม"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // นำเข้า namespace
    using GroupDocs.Markdown;

    // ตั้งค่าลิขสิทธิ์
    License.Set("GroupDocs.Markdown.lic");

    // สร้างอินสแตนซ์คอนเวอร์เตอร์
    var converter = new MarkdownConverter("business-plan.pdf");

    // แปลงและบันทึกไฟล์ Markdown ผลลัพธ์
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown อย่างรวดเร็ว"
  description: "API เพื่อวิเคราะห์และส่งออกเอกสารเป็น Markdown ในแอปพลิเคชัน .NET"
  features:
    # feature loop
    - title: "การแปลงที่แม่นยำและน่าเชื่อถือ"
      content: "แปลงรูปแบบที่รองรับเป็น Markdown อย่างมีประสิทธิภาพพร้อมรักษาโครงสร้างไม่เสียหาย รองรับ .NET Framework 4.6.2+ และ .NET 6.0 บน Windows และ Linux."

    # feature loop
    - title: "รูปแบบยอดนิยมที่รองรับ"
      content: "ส่งออก PDF, Word, Excel, eBooks, เว็บและไฟล์ข้อความธรรมดาเป็น Markdown รวมถึงเอกสารที่มีการป้องกันด้วยรหัสผ่าน."

    # feature loop
    - title: "ทำงานบนเครื่องของคุณ"
      content: "คุณควบคุมข้อมูลของคุณเอง - เรามี API แบบออนพรีมิสซึ่งไม่ต้องการคลาวด์หรือการเชื่อมต่ออินเทอร์เน็ต"

############################# Platforms ############################
platforms:
  enable: true
  title: "การสนับสนุนแพลตฟอร์ม"
  description: "ระบบปฏิบัติการ เฟรมเวิร์ก และตัวจัดการแพ็คเกจต่อไปนี้ได้รับการสนับสนุน"
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
  title: "รูปแบบไฟล์ที่รองรับ"
  description: |
    รูปแบบไฟล์ต่อไปนี้ได้รับการสนับสนุนสำหรับการส่งออกไปยัง Markdown
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
        ### Word และ Excel
        * **Word:** DOCX, DOC, RTF, DOCM, DOTX, DOTM, DOT, ODT, OTT
        * **Excel:** XLSX, XLS, CSV, XLSM, XLSB, ODS, TSV, NUMBERS, XLTX, XLTM, XLAM, FODS, SXC, OTS, XLT
      # group loop
    - color: "green"
      content: |
        ### อื่นๆ   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "คุณสมบัติของ GroupDocs.Markdown"
  description: "นี่คือคุณสมบัติที่ทำให้ผลิตภัณฑ์ของเราโดดเด่น"

  items:
    # feature loop
    - icon: "multi_doc"
      title: "ส่งออกหลายรูปแบบเอกสาร"
      content: "แปลงรูปแบบเอกสารที่นิยมมากที่สุดเป็น Markdown (PDF, DOCX, XLSX, EPUB และอื่นๆ)"

    # feature loop
    - icon: "advanced_formatting"
      title: "การจัดรูปแบบ Markdown ขั้นสูง"
      content: "หัวข้อ, ย่อหน้า, รายการ, ตาราง, ลิงก์, รูปภาพ, blockquotes และ code blocks จะถูกส่งออกเป็นไวยากรณ์ Markdown ที่เหมาะสม."

    # feature loop
    - icon: "control_over_images"
      title: "การควบคุมรูปภาพอย่างเต็มรูปแบบ"
      content: "ควบคุมรูปภาพได้โดยการส่งออกหรือฝังลงในไฟล์ Markdown ผลลัพธ์."

    # feature loop
    - icon: "secure"
      title: "ทำงานบนเครื่องของคุณ"
      content: "ไม่จำเป็นต้องใช้คลาวด์หรือการเชื่อมต่ออินเทอร์เน็ต การประมวลผลทั้งหมดทำบนเครื่องของคุณ."

    # feature loop
    - icon: "intuitive"
      title: "API สาธารณะที่ใช้งานง่าย"
      content: "API สาธารณะที่เรียบง่ายและใช้งานง่ายออกแบบโดยนักพัฒนาเพื่อให้นักพัฒนารักกัน."

    # feature loop
    - icon: "cross_platform"
      title: "ทำงานบน Windows และ Linux"
      content: ".NET และ .NET Framework assemblies มีให้ในแพ็คเกจ NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "ตัวอย่างโค้ด"
  description: "สถานการณ์การใช้งานที่พบบ่อยที่สุดสำหรับการส่งออกเอกสารเป็น Markdown ในแอปพลิเคชัน .NET"
  items:
    # code sample loop
    - title: "ส่งออก DOCX ไปยัง Markdown"
      content: "ตัวอย่างโค้ดนี้แสดงวิธีแปลงไฟล์ DOCX เป็น Markdown และบันทึกผลลัพธ์ลงไฟล์ รูปภาพจะถูกฝังในไฟล์ผลลัพธ์"
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // นำเข้า namespace
            using GroupDocs.Markdown;

            // ตั้งค่าไลเซนส์
            License.Set("GroupDocs.Markdown.lic");

            // สร้างอินสแตนซ์ของตัวแปลง
            var converter = new MarkdownConverter("annual-review.docx");

            // แปลงและบันทึกผลลัพธ์ลงไฟล์
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // นำเข้า namespace  
            open GroupDocs.Markdown

            // ตั้งค่าไลเซนส์
            License.Set("GroupDocs.Markdown.lic")

            // สร้างอินสแตนซ์ของตัวแปลง
            let converter = new MarkdownConverter("annual-review.docx")

            // แปลงและบันทึกผลลัพธ์ลงไฟล์
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' นำเข้า namespace  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' ตั้งค่าไลเซนส์
                    License.Set("GroupDocs.Markdown.lic")

                    ' สร้างอินสแตนซ์ของตัวแปลง
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' แปลงและบันทึกผลลัพธ์ลงไฟล์
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "บันทึกรูปภาพลงโฟลเดอร์"
      content: "ตัวอย่างโค้ดนี้แสดงวิธีแปลงไฟล์ DOCX เป็น Markdown และบันทึกรูปภาพลงในโฟลเดอร์แยกต่างหาก"
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // นำเข้า namespace
            using GroupDocs.Markdown;

            // ตั้งค่าไลเซนส์
            License.Set("GroupDocs.Markdown.lic");

            // สร้างอินสแตนซ์ของตัวแปลง
            var converter = new MarkdownConverter("annual-report.docx");

            // ตั้งกลยุทธ์การส่งออกภาพและโฟลเดอร์ผลลัพธ์
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // แปลงและบันทึกผลลัพธ์ลงไฟล์
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // นำเข้า namespace
            open GroupDocs.Markdown

            // ตั้งค่าไลเซนส์
            License.Set("GroupDocs.Markdown.lic")

            // สร้างอินสแตนซ์ของตัวแปลง
            let converter = new MarkdownConverter("annual-report.docx")

            // ตั้งกลยุทธ์การส่งออกภาพและโฟลเดอร์ผลลัพธ์
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // แปลงและบันทึกผลลัพธ์ลงไฟล์
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' นำเข้า namespace  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' ตั้งค่าไลเซนส์
                    License.Set("GroupDocs.Markdown.lic")

                    ' สร้างอินสแตนซ์ของตัวแปลง
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' ตั้งกลยุทธ์การส่งออกภาพและโฟลเดอร์ผลลัพธ์
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' แปลงและบันทึกผลลัพธ์ลงไฟล์
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "รีวิวผลิตภัณฑ์ของ GroupDocs"
# description: "อย่าแค่เชื่อจากคำพูดของเรา มาดูว่านักพัฒนาอื่น ๆ พูดอย่างไรเกี่ยวกับ API ของเรา"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "บริการและผลิตภัณฑ์ยอดเยี่ยม พวกเขาช่วยเหลือและตอบสนองอย่างดีมากในกระบวนการใช้งาน GroupDocs.Markdown สำหรับ .NET ไม่สามารถแนะนำได้เพียงพอ."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "หลังจากนำ GroupDocs.Markdown สำหรับ .NET ไปใช้งานในโครงการ ดูเหมือนทำงานได้ดีมาก ฉันทดสอบกับเอกสารจำนวนมากและจนถึงตอนนี้ผลลัพธ์ดีไปแล้ว ผลลัพธ์ Markdown มีความสะอาดและสอดคล้องกันในทุกแหล่ง."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

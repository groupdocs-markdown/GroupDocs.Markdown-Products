---
############################# Static ##########################

layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: id
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

head_title: "Ekspor Dokumen ke Markdown dalam .NET | GroupDocs"
head_description: "GroupDocs.Markdown untuk .NET adalah API pemrosesan dokumen yang mengekspor PDF, Word, Excel, dan format lain ke Markdown untuk integrasi mulus dengan ekosistem AI generatif."

############################# Header ##########################

title: "Ekspor dokumen ke Markdown<br>menggunakan API .NET"
description: "API konversi Markdown untuk mengekspor format dokumen populer ke Markdown bersih dengan kontrol penuh."
words:
  for: "for"

actions:
  main: "Unduhan NuGet Gratis"
  main_link: "https://www.nuget.org/packages/GroupDocs.Markdown"
  alt: "Lisensi"
  alt_link: "https://purchase.groupdocs.com/pricing/markdown/net"
  title: "Siap memulai?"
  description: "Coba fitur GroupDocs.Markdown secara gratis atau minta lisensi"

release:
  hidden: false
  title: "Versi {0}&nbsp;dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"
  link: "https://releases.groupdocs.com/markdown/net/release-notes/latest/"

code:
  title: "Ekspor PDF ke Markdown dalam C#"
  more: "Contoh lainnya"
  more_link: "https://github.com/groupdocs-markdown/GroupDocs.Markdown-for-.NET"
  install: "dotnet add package GroupDocs.Markdown"
  content: |
    ```csharp {style=abap}   
    // Impor namespace
    using GroupDocs.Markdown;

    // Atur lisensi
    License.Set("GroupDocs.Markdown.lic");

    // Instansiasi konverter
    var converter = new MarkdownConverter("business-plan.pdf");

    // Konversi dan simpan file Markdown hasil
    converter.Convert("business-plan.md");
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Markdown sekilas"
  description: "API untuk parsing dan mengekspor dokumen ke Markdown dalam aplikasi .NET."
  features:
    # feature loop
    - title: "Konversi yang akurat dan dapat diandalkan"
      content: "Konversi format yang didukung ke Markdown secara efisien sambil mempertahankan integritas struktur. Mendukung .NET Framework 4.6.2+ dan .NET 6.0 di Windows dan Linux."

    # feature loop
    - title: "Format populer yang didukung"
      content: "Ekspor PDF, Word, Excel, eBook, Web, dan file teks biasa ke Markdown, termasuk dokumen yang dilindungi kata sandi."

    # feature loop
    - title: "Berjalan di mesin lokal Anda"
      content: "Anda mengontrol data Anda - kami menyediakan API on-premise yang tidak memerlukan cloud atau koneksi internet."

############################# Platforms ############################
platforms:
  enable: true
  title: "Dukungan platform"
  description: "Sistem operasi, kerangka kerja, dan manajer paket berikut didukung."
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
  title: "Format file yang didukung"
  description: |
    Format file berikut didukung untuk ekspor ke Markdown.
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
        ### Lainnya   
        * **e-Books:** EPUB, MOBI, AZW3   
        * **Text:** TXT, XML
        * **Web:** CHM


############################# Features ############################
features:
  enable: true
  title: "Fitur GroupDocs.Markdown"
  description: "Berikut adalah fitur-fitur yang membuat produk kami menonjol."

  items:
    # feature loop
    - icon: "multi_doc"
      title: "Ekspor banyak format dokumen"
      content: "Konversi format dokumen paling populer ke Markdown (PDF, DOCX, XLSX, EPUB, dan lainnya)."

    # feature loop
    - icon: "advanced_formatting"
      title: "Pemformatan Markdown lanjutan"
      content: "Judul, paragraf, daftar, tabel, tautan, gambar, kutipan blok, dan blok kode diekspor ke sintaks Markdown yang sesuai."

    # feature loop
    - icon: "control_over_images"
      title: "Kontrol penuh atas gambar"
      content: "Kendalikan gambar dengan mengekspor atau menyematkannya ke dalam file Markdown output."

    # feature loop
    - icon: "secure"
      title: "Berjalan di mesin lokal Anda"
      content: "Tidak memerlukan cloud atau koneksi Internet. Semua pemrosesan dilakukan di mesin lokal Anda."

    # feature loop
    - icon: "intuitive"
      title: "API publik yang intuitif"
      content: "API publik yang sederhana dan intuitif, dirancang oleh pengembang untuk pengembang dengan penuh semangat."

    # feature loop
    - icon: "cross_platform"
      title: "Bekerja di Windows dan Linux"
      content: ".NET dan assembly .NET Framework disediakan dalam paket NuGet."


############################# Code samples ############################
code_samples_tabs:
  enable: true
  title: "Contoh kode"
  description: "Skenario penggunaan paling umum untuk mengekspor dokumen ke Markdown dalam aplikasi .NET."
  items:
    # code sample loop
    - title: "Ekspor DOCX ke Markdown"
      content: "Contoh kode ini menunjukkan cara mengonversi file DOCX ke Markdown dan menyimpan hasilnya ke file. Gambar-gambar disematkan dalam file output."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Impor namespace
            using GroupDocs.Markdown;

            // Atur lisensi
            License.Set("GroupDocs.Markdown.lic");

            // Instansiasi konverter
            var converter = new MarkdownConverter("annual-review.docx");

            // Konversi dan simpan hasil ke file
            converter.Convert("annual-review.md");
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Impor namespace  
            open GroupDocs.Markdown

            // Atur lisensi
            License.Set("GroupDocs.Markdown.lic")

            // Instansiasi konverter
            let converter = new MarkdownConverter("annual-review.docx")

            // Konversi dan simpan hasil ke file
            converter.Convert("annual-review.md")
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Impor namespace  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Atur lisensi
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instansiasi konverter
                    Dim converter As New MarkdownConverter("annual-review.docx")

                    ' Konversi dan simpan hasil ke file
                    converter.Convert("annual-review.md")
                End Sub
            End Module
            ```
    # code sample loop
    - title: "Simpan gambar ke folder"
      content: "Contoh kode ini menunjukkan cara mengonversi file DOCX ke Markdown dan menyimpan gambar ke folder terpisah."
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Impor namespace
            using GroupDocs.Markdown;

            // Atur lisensi
            License.Set("GroupDocs.Markdown.lic");

            // Instansiasi konverter
            var converter = new MarkdownConverter("annual-report.docx");

            // Atur strategi ekspor gambar dan folder output
            var convertOptions = new DocumentConverterOptions();
            convertOptions.ImageExportStrategy = new ExportImagesToFileSystemStrategy("./images");

            // Konversi dan simpan hasil ke file
            converter.Convert("annual-report.md", convertOptions);
            ```
        - language: "F#"
          color: "red"
          content: |
            ```fsharp {style=abap} 
            // Impor namespace
            open GroupDocs.Markdown

            // Atur lisensi
            License.Set("GroupDocs.Markdown.lic")

            // Instansiasi konverter
            let converter = new MarkdownConverter("annual-report.docx")

            // Atur strategi ekspor gambar dan folder output
            let convertOptions = new DocumentConverterOptions()
            convertOptions.ImageExportStrategy <- new ExportImagesToFileSystemStrategy("./images")

            // Konversi dan simpan hasil ke file
            converter.Convert("annual-report.md", convertOptions)
            ```
        - language: "VB.NET"
          color: "green"
          content: |
            ```vb {style=abap}   
            ' Impor namespace  
            Imports GroupDocs.Markdown

            Module Program
                Sub Main()
                    ' Atur lisensi
                    License.Set("GroupDocs.Markdown.lic")

                    ' Instansiasi konverter
                    Dim converter As New MarkdownConverter("annual-report.docx")

                    ' Atur strategi ekspor gambar dan folder output
                    Dim convertOptions As New DocumentConverterOptions()
                    convertOptions.ImageExportStrategy = New ExportImagesToFileSystemStrategy("./images")

                    ' Konversi dan simpan hasil ke file
                    converter.Convert("annual-report.md", convertOptions)
                End Sub
            End Module

            ```

############################# Reviews ############################
# reviews:
# enable: true
# title: "Ulasan produk GroupDocs"
# description: "Jangan hanya mempercayai kata kami. Lihat apa yang dikatakan pengembang lain tentang API kami"

# items:
#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Layanan dan produk yang luar biasa. Mereka sangat membantu dan responsif selama proses implementasi GroupDocs.Markdown untuk .NET, tidak dapat merekomendasikan mereka lebih tinggi lagi."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Markdown"
#     content: "Setelah mengimplementasikan dan menggunakan GroupDocs.Markdown untuk .NET dalam proyek, terlihat berfungsi dengan sangat baik. Saya telah menguji dengan banyak dokumen dan sejauh ini semuanya baik. Output Markdown bersih dan konsisten di semua sumber."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---

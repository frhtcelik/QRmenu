<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white" alt="Google Sheets" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
</p>

<br />

<p align="center">
  <h1 align="center">🍔 Lale Döner - Dynamic Digital QR Menu</h1>
  <p align="center">
    An elegant, high-performance, and serverless digital QR menu system that fetches live menu and pricing data directly from Google Sheets.
    <br />
    <a href="https://laledoner.com.tr"><strong>Explore the Live Site »</strong></a>
  </p>
</p>

<hr />

<h3 align="center">📱 Application Screenshots / Uygulama Ekran Görüntüleri</h3>
<p align="center">
  <table align="center">
    <tr>
      <td align="center" width="33%">
        <img  src="https://github.com/user-attachments/assets/4f5b8311-0044-43b5-bbb6-ffdd9b74fba8" width="100%" alt="Welcome Screen" />
        <br />
        <sub><b>Welcome & Info</b></sub>
      </td>
      <td align="center" width="33%">
        <img src="https://github.com/user-attachments/assets/e778a961-b746-44e1-b52c-be4dfa14e57f" width="100%" alt="Categories Screen" />
        <br />
        <sub><b>Category Navigation</b></sub>
      </td>
      <td align="center" width="33%">
        <img src="https://github.com/user-attachments/assets/321a5627-e7b2-47ff-a9d1-0c0fb5be66cd" width="100%" alt="Dynamic Menu List" />
        <br />
        <sub><b>Live Google Sheets Menu</b></sub>
      </td>
    </tr>
  </table>
</p>

<hr />

## 🇺🇸 ENGLISH

### 📝 Project Overview
This project is an ultra-fast, modern, and zero-maintenance digital QR menu system designed for **Lale Döner** restaurant. Instead of hardcoding prices or maintaining expensive databases, this application leverages Google Sheets as a headless CMS. 

When the business owner updates prices on their phone via the Google Sheets app, the changes instantly reflect on the customer-facing website without requiring any code deployment.

### 🌟 Key Features
- **Zero-Maintenance CMS:** Business owners can manage products, prices, and descriptions on Google Sheets without needing a developer.
- **Vanilla Fetch Architecture:** Built with native, lightweight JavaScript Fetch API (`opensheet` proxy) ensuring sub-second load times.
- **Smart Working Hours Status:** Evaluates and displays whether the restaurant is currently `Open` or `Closed` dynamically, based on local operating hours (`10:30 AM - 11:00 PM`).
- **Premium Dark UI:** Designed with a modern, high-contrast dark aesthetic, complete with blur backdrop filters, custom accent glows, and smooth page transitions.
- **Category Anchors:** Vertical navigation button cards allow users to jump directly to specific menu blocks with fluid scroll behavior.

### 🛠️ Built With
- **Frontend:** HTML5, CSS3 (Custom Variables, Flexbox, Keyframes)
- **Scripting:** Vanilla JavaScript (ES6+, Async/Await)
- **Database / CMS:** Google Sheets (Spreadsheet API via `opensheet.elk.sh`)
- **Hosting & Deployment:** Vercel (Continuous Integration / Continuous Deployment)

---

## 🇹🇷 TÜRKÇE

### 📝 Proje Hakkında
Bu proje, **Lale Döner** işletmesi için özel olarak geliştirilmiş; aşırı hızlı, modern ve sıfır yönetim maliyetli bir dinamik dijital QR menü uygulamasıdır. Fiyatları kod içerisine gömmek veya pahalı veritabanı sunucuları kiralamak yerine, bu sistem Google E-Tablolar'ı (Google Sheets) bir "Headless CMS" (İçerik Yönetim Sistemi) gibi kullanır.

İşletme sahibi cep telefonundaki Google E-Tablolar uygulamasından bir fiyatı güncellediği anda, yapılan değişiklik hiçbir kod güncellemesi veya derleme gerektirmeden saniyeler içinde müşterilerin ekranına yansır.

### 🌟 Temel Özellikler
- **Sıfır Maliyetli CMS:** İşletme sahibi; ürünleri, fiyatları ve açıklamaları yazılımcıya ihtiyaç duymadan doğrudan Google E-Tablo üzerinden yönetir.
- **Vanilla Fetch Mimarisi:** Saf ve hafif JavaScript Fetch API mimarisi sayesinde menü verileri milisaniyeler içinde çekilir ve yüklenir.
- **Akıllı Çalışma Saati Kontrolü:** Restoranın açık veya kapalı olma durumunu, tanımlanan çalışma saatlerine (`10:30 - 23:00`) göre anlık olarak hesaplar ve dinamik etiketlerle gösterir.
- **Premium Gece Teması:** Arka plan bulanıklık efektleri (backdrop-filter), özel parlama efektleri (accent glows) ve akıcı geçişlerle donatılmış lüks bir tasarıma sahiptir.
- **Kategori Navigasyonu:** Kullanıcıların dikey yönlendirme kartlarına tıklayarak istedikleri menü grubuna pürüzsüzce kaymasını sağlayan akıllı anchor yapısı mevcuttur.

### 🛠️ Kullanılan Teknolojiler
- **Arayüz:** HTML5, CSS3 (Özel Değişkenler, Flexbox, Animasyonlar)
- **Programlama:** Vanilla JavaScript (ES6+, Async/Await)
- **Veritabanı / Yönetim:** Google Sheets (Opensheet API üzerinden JSON dönüşümü)
- **Barındırma ve Dağıtım:** Vercel (GitHub entegrasyonlu anlık canlıya alma)

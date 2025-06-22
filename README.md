# JAW Dimsum Serang - Website Resmi

![JAW Dimsum Banner](https://img.shields.io/badge/JAW%20Dimsum-Serang-orange?style=for-the-badge&logo=restaurant)

Website modern dan responsif untuk JAW Dimsum Serang - Street food berkualitas sejak 2023.

## 🍜 Tentang Proyek

Website statis yang dibangun untuk JAW Dimsum Serang, sebuah gerai jajanan kaki lima yang didirikan oleh 2 wanita hebat sejak 2023. Website ini menampilkan menu lengkap, informasi lokasi, dan memudahkan pelanggan untuk memesan online.

## ✨ Fitur Utama

### 🎨 **Desain & UI/UX**
- Design modern dengan tema street food premium
- Color scheme: Putih (#FFFFFF) & Kuning Gold Soft (#F4D03F)
- Accent colors: Warm orange tones
- Typography yang food-friendly dan mudah dibaca
- Layout clean dan minimalist

### 📱 **Responsive Design**
- **Mobile First Approach** (320px - 768px)
- **Tablet Optimization** (768px - 1024px)  
- **Desktop Enhancement** (1024px+)
- Touch-friendly interface untuk mobile users
- Hamburger menu dengan smooth animation

### 🎪 **Animasi & Interaksi**
- Smooth scroll navigation
- Fade-in animations saat scroll (Intersection Observer API)
- Hover effects pada menu items dan buttons
- Loading animations yang smooth
- Parallax effects pada hero section
- Smooth transitions untuk semua elemen interaktif

### 🍽️ **Menu Management**
- **Kategori Lengkap:**
  - Dimsum (12 varian)
  - Platter (2 varian)
  - Snacks (3 varian)
- Filter berdasarkan kategori
- Search functionality real-time
- Card design dengan pricing yang jelas
- Grid layout responsif

### 📞 **Integrasi Online Ordering**
- **WhatsApp** - Quick order (087863177362)
- **GoFood** - Integration button
- **GrabFood** - Integration button
- WhatsApp floating button dengan pulse animation

### 📍 **Informasi Lokasi**
- Google Maps integration ready
- Alamat lengkap: Jl. Highland Park, Sumurpecung, Kec. Serang
- Landmark: Depan Gapura Kota Serang Baru
- Jam operasional: Setiap hari 13.00 - 22.00 WIB

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| HTML5 | Latest | Semantic structure |
| CSS3 | Latest | Styling & animations |
| JavaScript | Vanilla ES6+ | Interactivity |
| Intersection Observer API | Native | Scroll animations |
| CSS Grid & Flexbox | Native | Responsive layout |

## 📁 Struktur Proyek

```
jaw-dimsum-website/
│
├── index.html              # File utama website
├── README.md              # Dokumentasi proyek
└── assets/               # (Optional - untuk file tambahan)
    ├── images/           # Gambar produk
    ├── icons/            # Icon dan logo
    └── docs/             # Dokumentasi tambahan
```

## 🚀 Cara Menjalankan

### Prerequisites
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, dll.)
- (Optional) Live Server extension untuk development

### Installation & Setup

1. **Clone atau Download**
   ```bash
   # Clone repository (jika menggunakan Git)
   git clone [repository-url]
   
   # Atau download ZIP file dan extract
   ```

2. **Buka Project**
   ```bash
   cd jaw-dimsum-website
   ```

3. **Jalankan Website**
   - **Metode 1:** Double-click file `index.html`
   - **Metode 2:** Menggunakan Live Server
     ```bash
     # Jika menggunakan VS Code dengan Live Server extension
     # Klik kanan pada index.html → Open with Live Server
     ```
   - **Metode 3:** Menggunakan Python Server
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     
     # Buka browser: http://localhost:8000
     ```

## 📝 Menu Items Database

### 🥟 Kategori Dimsum
| Item | 4pcs | 6pcs |
|------|------|------|
| Dimsum Ori | Rp 15.000 | - |
| Dimsum Moza Parut | Rp 18.000 | Rp 25.000 |
| Dimsum Bakar Ori | Rp 17.000 | Rp 24.000 |
| Dimsum Mentai | Rp 20.000 | Rp 28.000 |
| Dimsum Bakar Mentai | Rp 23.000 | Rp 33.000 |
| Mentai Moza Parut | Rp 25.000 | Rp 36.000 |
| Mentai Moza Slice | Rp 26.000 | Rp 36.000 |
| Dimsum Saus Keju | Rp 17.000 | Rp 25.000 |
| Dimsum Spicy Lava | Rp 17.000 | Rp 25.000 |
| Dimsum Saus Tartar | Rp 20.000 | Rp 25.000 |
| Dimsum Saus Brulee Ori | Rp 23.000 | Rp 30.000 |
| Dimsum Saus Brulee Spicy | Rp 25.000 | Rp 32.000 |

### 🍽️ Kategori Platter & Lainnya
| Item | Harga |
|------|-------|
| Mix Platter isi 6 | Menyesuaikan varian |
| Mix Platter isi 16 | Menyesuaikan varian |
| Cireng Isi (4pcs) | Rp 10.000 |
| Bakso Bakar (3 Tusuk) | Rp 10.000 |
| Macaroni Schotel Kecil | Rp 20.000 |
| Macaroni Schotel Sedang | Rp 27.000 |

## 🎯 Fitur JavaScript

### Core Functions
- **Mobile Navigation Toggle**
- **Header Scroll Effect** (background blur)
- **Menu Filter System** (kategori)
- **Search Functionality** (real-time)
- **Smooth Scrolling** (navigation)
- **Scroll Animations** (Intersection Observer)
- **WhatsApp Integration**
- **Loading Animations**

### Advanced Features
- **Parallax Hero Effect**
- **Typing Animation** (hero title)
- **Staggered Menu Cards Animation**
- **Gallery Lightbox Effect**
- **Touch-Friendly Interactions**

## 🎨 CSS Features

### Layout System
- **CSS Grid** - Menu cards & footer layout
- **Flexbox** - Navigation & content alignment
- **CSS Variables** - Consistent color scheme
- **Media Queries** - Responsive breakpoints

### Animations
- **CSS Transitions** - Smooth hover effects
- **CSS Animations** - Loading & floating effects
- **Transform 3D** - Hardware acceleration
- **Intersection Observer** - Scroll-triggered animations

## 📱 Responsive Breakpoints

```css
/* Mobile First */
.container {
  padding: 0 15px;
}

/* Tablet */
@media (min-width: 768px) {
  .container {
    padding: 0 20px;
  }
}

/* Desktop */
@media (min-width: 1024px) {
  .container {
    max-width: 1200px;
    margin: 0 auto;
  }
}
```

## 🔧 Customization Guide

### Mengubah Warna Theme
```css
:root {
  --primary-white: #FFFFFF;
  --primary-gold: #F4D03F;
  --warm-orange: #FF8C42;
  --warm-orange-light: #FFA366;
  --warm-orange-dark: #E67329;
}
```

### Menambah Menu Item Baru
```html
<div class="menu-card" data-category="dimsum">
  <div class="menu-card-image">🥟</div>
  <div class="menu-card-content">
    <h3>Nama Menu Baru</h3>
    <div class="menu-card-prices">
      <span class="price-tag">4pcs - Rp XX.000</span>
    </div>
  </div>
</div>
```

### Mengubah Informasi Kontak
```html
<!-- WhatsApp Number -->
<a href="https://wa.me/628XXXXXXXXX">

<!-- Instagram -->
<a href="https://www.instagram.com/username_baru">
```

## 🚀 Deployment Options

### 1. GitHub Pages
```bash
# Push ke GitHub repository
git add .
git commit -m "Initial commit"
git push origin main

# Enable GitHub Pages di repository settings
```

### 2. Netlify
1. Drag & drop folder ke netlify.com
2. Atau connect dengan GitHub repository
3. Website otomatis online

### 3. Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

### 4. Traditional Web Hosting
- Upload file `index.html` ke public_html
- Pastikan web hosting support HTML5

## 📊 Performance Optimization

### ✅ Sudah Dioptimasi
- **Vanilla JavaScript** - No framework overhead
- **CSS3 Animations** - Hardware accelerated
- **Semantic HTML** - Better SEO
- **Compressed CSS** - Minified styling
- **Efficient Selectors** - Fast rendering

### 🎯 Rekomendasi Tambahan
- **Image Optimization** - Compress gambar produk
- **CDN Implementation** - Faster global loading
- **Service Worker** - Offline functionality
- **Progressive Web App** - Mobile app experience

## 🔍 SEO Features

### ✅ Sudah Diimplementasi
```html
<meta name="description" content="JAW Dimsum Serang - Street food berkualitas sejak 2023">
<meta name="keywords" content="dimsum, serang, street food, makanan, jajanan">
<title>JAW Dimsum Serang - Street Food Berkualitas</title>
```

### 🎯 Rekomendasi Tambahan
- **Schema Markup** - Local business
- **Open Graph** - Social media sharing
- **Google My Business** - Local SEO
- **Google Analytics** - Traffic tracking

## 🛡️ Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 60+ | ✅ Full Support |
| Firefox | 55+ | ✅ Full Support |
| Safari | 12+ | ✅ Full Support |
| Edge | 79+ | ✅ Full Support |
| IE | 11 | ⚠️ Limited Support |

## 📞 Informasi Kontak

### JAW Dimsum Serang
- **WhatsApp:** 087863177362
- **Instagram:** [@jajanan.jaw](https://www.instagram.com/jajanan.jaw)
- **Alamat:** Jl. Highland Park, Sumurpecung, Kec. Serang, Kota Serang, Banten 42118
- **Landmark:** Depan Gapura Kota Serang Baru
- **Jam Operasional:** Setiap hari 13.00 - 22.00 WIB

## 📝 Changelog

### Version 1.0.0 (2025)
- ✅ Initial website release
- ✅ Complete menu integration
- ✅ Responsive design implementation
- ✅ Online ordering integration
- ✅ Location & contact information
- ✅ Performance optimization

## 🤝 Contributing

Jika Anda ingin berkontribusi untuk mengembangkan website ini:

1. Fork repository
2. Buat feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📄 License

Website ini dibuat khusus untuk JAW Dimsum Serang. Semua hak cipta dilindungi.

## 🙏 Acknowledgments

- **Design Inspiration:** Modern street food websites
- **Icons:** Emoji untuk placeholder
- **Fonts:** System fonts untuk performance
- **Colors:** Warm palette untuk food industry

---

**Dibuat dengan ❤️ untuk JAW Dimsum Serang**

*Website siap pakai dengan semua fitur modern untuk bisnis street food.*

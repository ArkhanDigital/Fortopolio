# 🚀 Portfolio Website

Portfolio website modern dan responsif yang dibangun dengan HTML5, CSS3, dan JavaScript vanilla. Menampilkan desain contemporary dengan animasi yang smooth dan user experience yang optimal.

## ✨ Features

- **Modern Design**: Desain gelap dengan gradien yang menarik dan typography yang clean
- **Fully Responsive**: Optimal di semua device (desktop, tablet, mobile)
- **Smooth Animations**: Loading animations, hover effects, dan scroll animations
- **Interactive Elements**: Particle background, scroll progress indicator, typing effect
- **Contact Form**: Form kontak yang functional dengan validasi
- **Portfolio Showcase**: Grid layout untuk menampilkan projects dengan detail
- **Social Media Links**: Integration dengan platform media sosial
- **Performance Optimized**: Fast loading dan smooth interactions

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling dengan CSS Grid dan Flexbox
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome** - Icon library
- **CSS Animations** - Custom animations dan transitions

## 📱 Responsive Design

Website ini telah dioptimalkan untuk berbagai ukuran layar:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px

## 🚀 Deployment ke GitHub Pages

### 1. Fork atau Clone Repository

```bash
git clone https://github.com/username/portfolio-website.git
cd portfolio-website
```

### 2. Customize Content

Edit file `index.html` untuk menyesuaikan dengan informasi pribadi Anda:

- Ganti nama dan title di bagian hero section
- Update informasi about section dengan pengalaman Anda
- Tambahkan project-project Anda di portfolio section
- Update informasi kontak (email, phone, location)
- Ganti link social media dengan profile Anda

### 3. Upload ke GitHub

```bash
git add .
git commit -m "Initial portfolio setup"
git push origin main
```

### 4. Enable GitHub Pages

1. Buka repository di GitHub
2. Klik tab **Settings**
3. Scroll ke bagian **Pages**
4. Di **Source**, pilih **Deploy from a branch**
5. Pilih branch **main** dan folder **/ (root)**
6. Klik **Save**

Website Anda akan tersedia di: `https://username.github.io/repository-name`

## 📂 File Structure

```
portfolio-website/
│
├── index.html          # Main HTML file
├── README.md           # Documentation
└── assets/            # (Optional folder untuk assets tambahan)
    ├── images/        # Profile images, project screenshots
    ├── css/           # Additional CSS files (jika diperlukan)
    └── js/            # Additional JS files (jika diperlukan)
```

## 🎨 Customization

### Colors
Ubah color scheme di CSS variables:

```css
:root {
    --primary-color: #6366f1;    /* Warna utama */
    --secondary-color: #8b5cf6;  /* Warna sekunder */
    --accent-color: #06b6d4;     /* Warna aksen */
    --dark-bg: #0f172a;          /* Background gelap */
    --card-bg: #1e293b;          /* Background card */
}
```

### Typography
Font family dapat diubah di:

```css
body {
    font-family: 'Your-Font-Name', sans-serif;
}
```

### Content Sections

1. **Hero Section**: Update nama, title, dan deskripsi
2. **About Section**: Tambahkan pengalaman dan skills
3. **Projects Section**: Showcase portfolio projects
4. **Contact Section**: Update informasi kontak

## 📧 Contact Form

Form kontak menggunakan JavaScript untuk validasi dasar. Untuk functionality penuh, Anda bisa integrate dengan:

- **Formspree**: Service gratis untuk form handling
- **Netlify Forms**: Jika deploy di Netlify
- **EmailJS**: Send email directly dari frontend
- **Custom Backend**: Node.js/PHP backend untuk processing

### Setup Formspree:

1. Daftar di [formspree.io](https://formspree.io)
2. Ganti action form dengan endpoint Formspree Anda:

```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
```

## 🔧 Advanced Features

### Adding Blog Section

Untuk menambahkan blog, tambahkan section baru:

```html
<section id="blog" class="section">
    <div class="container">
        <h2 class="section-title">Blog</h2>
        <!-- Blog posts grid -->
    </div>
</section>
```

### Adding Testimonials

```html
<section id="testimonials" class="section">
    <div class="container">
        <h2 class="section-title">Testimonials</h2>
        <!-- Testimonials slider -->
    </div>
</section>
```

### SEO Optimization

Tambahkan meta tags di `<head>`:

```html
<meta name="description" content="Portfolio - Full Stack Developer">
<meta name="keywords" content="web developer, portfolio, react, javascript">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Full Stack Developer Portfolio">
<meta property="og:image" content="https://yourdomain.com/og-image.jpg">
```

## 🐛 Troubleshooting

### Common Issues:

1. **Images not loading**: Pastikan path image benar dan file exists
2. **Animations not working**: Check browser compatibility untuk CSS animations
3. **Form not submitting**: Setup form handler service (Formspree, etc.)
4. **Mobile layout broken**: Test responsive design di berbagai device

### Browser Support:

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📈 Performance Tips

1. **Optimize Images**: Compress images dan gunakan WebP format
2. **Minimize CSS/JS**: Minify files untuk production
3. **Use CDN**: Untuk external libraries (Font Awesome, etc.)
4. **Enable Compression**: Setup gzip compression di server

## 🤝 Contributing

Jika Anda ingin berkontribusi:

1. Fork repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- Design inspiration dari modern portfolio trends
- Icons dari [Font Awesome](https://fontawesome.com/)
- Typography menggunakan system fonts untuk performance optimal

## 📞 Support

Jika Anda memiliki pertanyaan atau butuh bantuan:

- Email: developer@email.com
- GitHub Issues: [Create New Issue](https://github.com/username/portfolio-website/issues)

---

⭐ **Don't forget to star this repository if you found it helpful!**

Made with ❤️ by [Your Name]

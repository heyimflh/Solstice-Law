# ☀️ Solstice Law

> **Premium Legal Company Profile Website**  
> Clarity at every turning point.

[![Built with Astro](https://img.shields.io/badge/Built%20with-Astro-FF5139?style=flat&logo=astro)](https://astro.build)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

---

## 📋 Daftar Isi

- [Tentang Solstice Law](#tentang-solstice-law)
- [Fitur Utama](#fitur-utama)
- [Tech Stack](#tech-stack)
- [Persiapan Awal](#persiapan-awal)
- [Panduan Instalasi](#panduan-instalasi)
- [Struktur Proyek](#struktur-proyek)
- [Konfigurasi Penting](#konfigurasi-penting)
- [Panduan Pengembangan](#panduan-pengembangan)
- [Deploy](#deploy)
- [Panduan Konten](#panduan-konten)
- [SEO & Performa](#seo--performa)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)

---

## 📖 Tentang Solstice Law

**Solstice Law** adalah website company profile modern untuk firma hukum premium yang menampilkan citra **tenang, matang, strategis, dan berwibawa**.

### Visi
Menjadi website firma hukum premium yang membantu calon klien menemukan kejelasan, rasa aman, dan pendampingan hukum strategis melalui pengalaman digital yang elegan, cepat, dan mudah digunakan.

### Misi
- Menampilkan Solstice Law sebagai firma hukum yang kredibel, strategis, dan berorientasi pada klien
- Menyederhanakan pemahaman calon klien terhadap bidang layanan hukum
- Mendorong calon klien untuk melakukan konsultasi melalui jalur kontak yang jelas
- Menciptakan pengalaman digital yang responsif, cepat, aman, dan SEO-friendly
- Menyediakan struktur konten yang mudah dikelola dan dikembangkan

### Target Pengguna
- 👨‍💼 Founder, Startup, dan Pemilik Bisnis
- 🏢 Perusahaan dan Institusi
- 👤 Individu Profesional
- 🤝 Mitra Profesional

---

## ✨ Fitur Utama

### Halaman & Konten
- ✅ **Beranda** - Hero yang kuat dengan trust indicators dan service snapshot
- ✅ **Tentang Firma** - Cerita, visi, misi, dan prinsip kerja
- ✅ **Layanan Hukum** - 9 area layanan dengan deskripsi detail
- ✅ **Pendekatan Kerja** - Proses konsultasi 5 tahap
- ✅ **Tim** - Profil profesional dengan expertise
- ✅ **Kontak** - Form konsultasi dan informasi kantor

### Teknologi & Performa
- ⚡ **Static Site Generation** - Loading cepat dan performa optimal
- 📱 **Responsive Design** - Mobile-first dengan design system konsisten
- 🎨 **Design System Premium** - Warna, tipografi, dan komponen terstandar
- ♿ **Accessibility** - WCAG compliance dan keyboard navigation
- 🔍 **SEO Optimized** - Meta tags, sitemap, schema, dan Open Graph

### Formulir & Integrasi
- ✅ **Consultation Form** - Validasi client-side dengan user experience optimal
- 📧 **Email Integration** - Netlify Forms atau Formspree
- 🗺️ **Google Maps Embed** - Lokasi kantor yang interaktif
- 📞 **Multi-channel Contact** - Email, telepon, WhatsApp

### Developer Experience
- 📝 **TypeScript** - Type-safe code dan better maintainability
- 🎯 **Centralized Data** - Services, team, dan site config tersentralisasi
- 🎨 **Tailwind CSS** - Utility-first styling yang konsisten
- 🔧 **Easy to Customize** - Modular components dan clear documentation

---

## 🛠 Tech Stack

| Kategori | Teknologi | Alasan |
|----------|-----------|--------|
| **Framework** | [Astro.js](https://astro.build) | Ringan, cepat, cocok untuk website statis dengan kebutuhan SEO tinggi |
| **Styling** | [Tailwind CSS](https://tailwindcss.com) | Memudahkan konsistensi design system dan responsive layout |
| **Bahasa** | [TypeScript](https://www.typescriptlang.org) | Type-safe, maintainable, better developer experience |
| **Fonts** | Playfair Display + Inter | Playfair untuk editorial premium, Inter untuk keterbacaan |
| **Icons** | Inline SVG | Ringan, scalable, mudah dikustomisasi |
| **Form** | Netlify Forms / Formspree | Serverless, cepat dipasang, tanpa backend custom |
| **Images** | Astro Image | Format modern, lazy loading, optimization otomatis |
| **Deployment** | Vercel / Netlify | CI/CD mudah, cocok untuk static site |
| **Version Control** | GitHub | Kolaborasi, review, deployment otomatis |

---

## 📦 Persiapan Awal

### Prerequisites
- Node.js 18.x atau lebih tinggi
- npm atau pnpm package manager
- Git untuk version control

### Tools yang Direkomendasikan
- **Code Editor**: VS Code dengan extension Astro
- **Browser DevTools**: Chrome DevTools untuk debugging
- **Git Client**: GitHub Desktop atau command line

### Kredensi & API Keys (Opsional)
- Netlify Forms atau Formspree untuk form submission
- Google Maps API key untuk embed peta
- Optional: Vercel atau Netlify account untuk deployment

---

## 🚀 Panduan Instalasi

### 1. Clone Repository
```bash
git clone https://github.com/heyimflh/Solstice-Law.git
cd Solstice-Law
```

### 2. Setup Environment
```bash
# Install dependencies
npm install
# atau
pnpm install
```

### 3. Konfigurasi Environment Variables (Opsional)
Buat file `.env.local` jika ada integrasi eksternal:
```env
# Contoh untuk Formspree
PUBLIC_FORMSPREE_ID=your_formspree_id

# Contoh untuk Google Maps
PUBLIC_GOOGLE_MAPS_API_KEY=your_maps_api_key
```

### 4. Development Server
```bash
npm run dev
```

Server akan berjalan di `http://localhost:3000`

### 5. Build untuk Production
```bash
npm run build
```

Output akan berada di folder `dist/`

### 6. Preview Production Build
```bash
npm run preview
```

---

## 📁 Struktur Proyek

```
solstice-law/
├── 📂 public/
│   ├── 📂 fonts/               # Font files (Playfair Display, Inter)
│   ├── 📂 images/
│   │   ├── brand/              # Logo dan brand assets
│   │   ├── team/               # Foto tim
│   │   ├── office/             # Foto kantor
│   │   └── og/                 # Open Graph images
│   ├── favicon.svg
│   ├── robots.txt
│   └── sitemap.xml
│
├── 📂 src/
│   ├── 📂 components/
│   │   ├── 📂 ui/              # UI components (Button, Card, Input, etc.)
│   │   ├── 📂 layout/          # Layout components (Header, Footer, SEO)
│   │   └── 📂 sections/        # Section components (Hero, ServiceCard, etc.)
│   │
│   ├── 📂 data/                # Centralized data
│   │   ├── services.ts         # Layanan hukum
│   │   ├── team.ts             # Data tim
│   │   ├── approach.ts         # Pendekatan kerja
│   │   └── siteConfig.ts       # Konfigurasi site
│   │
│   ├── 📂 layouts/
│   │   └── BaseLayout.astro    # Layout base untuk semua halaman
│   │
│   ├── 📂 pages/               # Halaman (auto-routing)
│   │   ├── index.astro         # Beranda
│   │   ├── firm.astro          # Tentang Firma
│   │   ├── services.astro      # Layanan Hukum
│   │   ├── approach.astro      # Pendekatan Kami
│   │   ├── team.astro          # Tim Solstice Law
│   │   └── contact.astro       # Kontak
│   │
│   └── 📂 styles/
│       └── global.css          # Global styles & Tailwind directives
│
├── astro.config.mjs            # Astro configuration
├── tailwind.config.mjs         # Tailwind configuration
├── tsconfig.json               # TypeScript configuration
├── package.json
├── README.md                   # File ini
└── PRD.md                      # Product Requirements Document
```

---

## ⚙️ Konfigurasi Penting

### Site Configuration (`src/data/siteConfig.ts`)

```typescript
export const siteConfig = {
  name: "Solstice Law",
  tagline: "Strategic Legal Counsel",
  description: "Premium legal company profile website for Solstice Law",
  baseUrl: "https://solsticelaw.id",
  defaultOgImage: "/images/og/default.png",
  navigation: [
    { label: "Beranda", href: "/" },
    { label: "Tentang Firma", href: "/firm" },
    { label: "Layanan", href: "/services" },
    { label: "Pendekatan", href: "/approach" },
    { label: "Tim", href: "/team" },
    { label: "Kontak", href: "/contact" },
  ],
};
```

### Tailwind Configuration
Warana premium brand sudah dikonfigurasi di `tailwind.config.mjs`:

```typescript
colors: {
  midnight: "#0B1020",
  navy: "#111827",
  gold: "#C9943A",
  ivory: "#FAF7F0",
  stone: "#F3EEE4",
  slate: "#334155",
  // ... dan lainnya
}
```

### Astro Configuration
Integrasi optimasi gambar, sitemap, dan RSS sudah tersedia di `astro.config.mjs`.

---

## 👨‍💻 Panduan Pengembangan

### Menambah Halaman Baru

1. Buat file `.astro` di `src/pages/`
2. Gunakan `BaseLayout` sebagai wrapper
3. Pastikan metadata SEO unik

```astro
---
import BaseLayout from "../layouts/BaseLayout.astro";

const pageTitle = "Page Title";
const pageDescription = "Page description for SEO";
---

<BaseLayout title={pageTitle} description={pageDescription}>
  <!-- Konten halaman -->
</BaseLayout>
```

### Membuat Component Baru

1. Buat file di folder yang sesuai (`components/ui`, `components/sections`, dll)
2. Export sebagai `.astro` component
3. Gunakan TypeScript untuk props

```astro
---
interface Props {
  title: string;
  description: string;
}

const { title, description } = Astro.props;
---

<div class="space-y-4">
  <h2 class="text-2xl font-bold">{title}</h2>
  <p>{description}</p>
</div>
```

### Menambah Layanan Hukum

Edit `src/data/services.ts`:

```typescript
export const services: ServiceArea[] = [
  {
    title: "New Service Area",
    slug: "new-service",
    summary: "Ringkasan singkat",
    description: "Deskripsi detail layanan",
    suitableFor: ["Bisnis", "Individu"],
    icon: "icon-name",
  },
  // ...
];
```

### Menambah Anggota Tim

Edit `src/data/team.ts`:

```typescript
export const teamMembers: TeamMember[] = [
  {
    name: "Nama Lengkap, S.H., LL.M.",
    role: "Posisi",
    degree: "Gelar akademik",
    expertise: ["Expertise 1", "Expertise 2"],
    bio: "Biografi singkat",
    image: "/images/team/nama.webp",
    linkedin: "https://linkedin.com/in/username",
  },
  // ...
];
```

### Styling dengan Tailwind CSS

Website menggunakan Tailwind CSS dengan custom color tokens:

```html
<!-- Contoh button primary -->
<button class="bg-gold-600 text-navy-900 hover:bg-gold-400 px-6 py-3 rounded-lg">
  Jadwalkan Konsultasi
</button>

<!-- Contoh card -->
<div class="bg-white border border-gold-600/18 rounded-2xl shadow-lg hover:shadow-xl transition-shadow">
  Konten card
</div>
```

---

## 🚀 Deploy

### Deploy ke Vercel

1. **Push ke GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Connect di Vercel**
   - Kunjungi [vercel.com](https://vercel.com)
   - Import repository GitHub
   - Vercel akan auto-detect Astro project
   - Deploy otomatis

3. **Custom Domain**
   - Di Vercel dashboard, tambahkan domain custom
   - Update DNS records sesuai instruksi Vercel

### Deploy ke Netlify

1. **Push ke GitHub**

2. **Connect di Netlify**
   - Kunjungi [netlify.com](https://netlify.com)
   - "New site from Git"
   - Select repository
   - Build command: `npm run build`
   - Publish directory: `dist`
   - Deploy

3. **Form Handling**
   - Enable Netlify Forms di `netlify.toml`
   - Form attributes: `netlify` dan unique `name`

---

## 📝 Panduan Konten

### Tone of Voice

Copy harus:
- ✅ Profesional namun humanis
- ✅ Tenang dan meyakinkan
- ✅ Hindari jargon hukum berlebihan
- ✅ Fokus pada kejelasan dan strategi
- ✅ Membangun rasa percaya
- ❌ Jangan buat klaim hasil hukum spesifik

### Copywriting Best Practices

```markdown
❌ SALAH:
"Layanan litigasi komersial kami menggunakan metodologi advanced litigation 
support dengan pendekatan strategis untuk memenangkan perkara Anda."

✅ BENAR:
"Kami membantu menyelesaikan sengketa bisnis melalui negosiasi, mediasi, 
atau litigasi dengan strategi yang terukur dan fokus pada kepentingan terbaik Anda."
```

### CTA (Call to Action)

Gunakan CTA yang konsisten:
- Jadwalkan Konsultasi
- Hubungi Solstice Law
- Pelajari Layanan Kami
- Temukan Arah Hukum Anda

---

## 🔍 SEO & Performa

### SEO Checklist

- ✅ Unique meta description per halaman
- ✅ Semantic HTML headings (h1, h2, h3)
- ✅ Image alt text deskriptif
- ✅ Internal linking strategis
- ✅ Open Graph metadata
- ✅ Twitter Card metadata
- ✅ JSON-LD structured data
- ✅ Sitemap auto-generated
- ✅ Robots.txt dikonfigurasi

### Performance Optimization

- ⚡ Images dioptimasi dengan Astro Image
- ⚡ Lazy loading untuk images & maps
- ⚡ CSS & JS minified otomatis
- ⚡ Static generation = fast serving
- ⚡ CDN delivery via Vercel/Netlify

### Monitoring

```bash
# Cek performance dengan Lighthouse
npm run build
npm run preview
# Open DevTools > Lighthouse, run audit
```

---

## 🤝 Kontribusi

### Development Workflow

1. **Create Branch**
   ```bash
   git checkout -b feature/nama-fitur
   ```

2. **Make Changes**
   - Edit files sesuai kebutuhan
   - Follow code style yang ada
   - Test dengan `npm run dev`

3. **Commit dengan Message Jelas**
   ```bash
   git commit -m "feat: add new service area"
   ```

4. **Push & Create Pull Request**
   ```bash
   git push origin feature/nama-fitur
   ```

### Code Style

- Gunakan TypeScript types
- Follow Astro conventions
- Consistent indentation (2 spaces)
- Descriptive variable names
- Comment untuk logic kompleks

---

## 📚 Referensi & Resources

### Dokumentasi
- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [TypeScript Handbook](https://www.typescriptlang.org/docs)

### Tools & Utilities
- [Astro Components](https://astro.build/integrations)
- [Tailwind UI](https://tailwindui.com)
- [Tabler Icons](https://tabler-icons.io)

### Performance & SEO
- [Google PageSpeed Insights](https://pagespeed.web.dev)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
- [Schema.org](https://schema.org)

---

## 📄 Lisensi

Repository ini bersifat private untuk Solstice Law. 

Untuk pertanyaan atau collaboration, hubungi tim development.

---

## 📞 Kontak & Support

**Solstice Law**
- 📧 Email: contact@solsticelaw.id
- 📱 WhatsApp: +62 811 9000 2727
- 🌍 Website: [solsticelaw.id](https://solsticelaw.id)
- 🌐 Live demo: [https://solstice-law.netlify.app/](https://solstice-law.netlify.app/)
- 📍 Lokasi: District 8 Treasury Tower, Jakarta Selatan

---

<div align="center">

**Clarity at every turning point.**

Dibuat dengan ☀️ oleh [@heyimflh](https://github.com/heyimflh) — pembuat repo dan website.

</div>

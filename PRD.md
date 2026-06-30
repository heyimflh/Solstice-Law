# PRD — Solstice Law: Premium Legal Company Profile Website

<aside>
☀️

PRD ini menjadi **single source of truth** untuk pengembangan website company profile premium **Solstice Law**. Arah utama produk: menghadirkan citra firma hukum yang tenang, strategis, elegan, humanis, dan terpercaya; sekaligus memudahkan calon klien memahami layanan, menilai kredibilitas, dan menghubungi firma dengan cepat.

</aside>

---

## Ringkasan Dokumen

| Informasi | Detail |
| --- | --- |
| Nama Produk | Solstice Law |
| Jenis Produk | Website Company Profile Firma Hukum Premium |
| Versi Dokumen | 1.0 |
| Tanggal | 29 Juni 2026 |
| Platform | Responsive Web Application |
| Target Perangkat | Desktop, Tablet, Mobile |
| Pendekatan Teknologi | Static Site Generation |
| Status Dokumen | Draft Pengembangan |
| Target Rilis MVP | 14 Hari Kerja |
| Bahasa Utama | Indonesia |
| Target Brand Feel | Premium, calm authority, strategic counsel, modern legal elegance |

---

## 1. Pendahuluan

### 1.1 Tujuan Dokumen

Dokumen ini mendefinisikan kebutuhan produk, arsitektur informasi, kebutuhan fungsional, kebutuhan non-fungsional, konten, desain visual, standar teknis, acceptance criteria, rencana testing, timeline implementasi, serta Definition of Done untuk website company profile **Solstice Law**.

PRD ini digunakan sebagai acuan utama bagi:

- Product owner
- UI/UX designer
- Frontend engineer
- Content strategist
- Copywriter
- Quality assurance
- Stakeholder firma hukum
- Tim deployment dan maintenance

Tujuan utamanya adalah memastikan seluruh pihak memiliki pemahaman yang sama tentang:

- Arah positioning brand Solstice Law.
- Struktur halaman dan kebutuhan konten.
- Fitur yang harus tersedia pada versi awal.
- Standar kualitas visual, performa, SEO, aksesibilitas, dan keamanan.
- Kriteria selesai yang dapat diuji secara objektif.

### 1.2 Ringkasan Produk

**Solstice Law** adalah website company profile modern untuk firma hukum yang menampilkan citra **tenang, matang, strategis, dan berwibawa**. Website ini dirancang untuk membantu individu, pemilik bisnis, startup, perusahaan, dan institusi menemukan pendampingan hukum yang tepat melalui pengalaman digital yang jelas dan profesional.

Berbeda dari konsep firma hukum yang terlalu kaku atau terlalu teknis, Solstice Law menempatkan dirinya sebagai **strategic legal partner**: firma yang tidak hanya menjawab persoalan hukum, tetapi juga membantu klien membaca risiko, menyusun strategi, dan mengambil keputusan dengan percaya diri.

Website ini berfungsi sebagai:

- **Digital front office** untuk calon klien.
- **Credibility hub** yang memperlihatkan profil, layanan, pendekatan kerja, dan tim.
- **Lead generation channel** melalui CTA dan formulir konsultasi.
- **Brand presence** untuk membangun kesan premium dan terpercaya.
- **SEO landing asset** untuk pencarian layanan hukum profesional.

### 1.3 Latar Belakang

Calon klien hukum sering menghadapi hambatan ketika ingin memilih firma hukum:

1. Sulit memahami layanan hukum yang relevan dengan masalahnya.
2. Website firma hukum sering terasa terlalu formal dan tidak ramah pengguna.
3. Informasi tim, pengalaman, dan pendekatan kerja tidak disampaikan secara meyakinkan.
4. Proses menghubungi firma sering tidak jelas.
5. Desain digital yang usang dapat menurunkan persepsi profesionalisme.

Solstice Law ingin menghadirkan pengalaman yang berbeda: **website hukum yang terasa premium, rapi, mudah dipahami, dan berfokus pada ketenangan klien**. Nama “Solstice” memberi asosiasi pada titik balik, arah baru, clarity, dan keseimbangan. Konsep ini diterjemahkan ke dalam website yang memadukan:

- Nuansa visual hangat dan elegan.
- Struktur konten yang mudah dipindai.
- Bahasa yang profesional namun tidak membingungkan.
- CTA yang jelas tanpa terasa agresif.
- Performa dan aksesibilitas yang kuat.

### 1.4 Visi Produk

Menjadi website firma hukum premium yang membantu calon klien menemukan kejelasan, rasa aman, dan pendampingan hukum strategis melalui pengalaman digital yang elegan, cepat, dan mudah digunakan.

### 1.5 Misi Produk

- Menampilkan Solstice Law sebagai firma hukum yang kredibel, strategis, dan berorientasi pada klien.
- Menyederhanakan pemahaman calon klien terhadap bidang layanan hukum.
- Mendorong calon klien untuk melakukan konsultasi melalui jalur kontak yang jelas.
- Menciptakan pengalaman digital yang responsif, cepat, aman, dan SEO-friendly.
- Menyediakan struktur konten yang mudah dikelola dan dikembangkan pada fase berikutnya.

### 1.6 Tujuan Bisnis

| Tujuan | Penjelasan | Indikator Keberhasilan |
| --- | --- | --- |
| Meningkatkan kredibilitas digital | Menampilkan profil firma, pendekatan kerja, layanan, dan tim secara meyakinkan. | Pengunjung memahami positioning firma dalam waktu kurang dari 30 detik. |
| Meningkatkan konversi konsultasi | Mengarahkan pengunjung ke halaman kontak melalui CTA strategis. | CTA utama terlihat di hero, section layanan, dan final CTA. |
| Memperjelas layanan hukum | Menyusun bidang praktik dalam kategori yang mudah dipahami. | Setiap layanan memiliki deskripsi singkat, manfaat, dan konteks kebutuhan klien. |
| Membangun brand premium | Menggunakan visual direction yang elegan, calm, dan modern. | Desain konsisten pada warna, tipografi, spacing, card, dan komponen. |
| Mendukung SEO profesional | Mengoptimalkan halaman utama untuk pencarian layanan hukum. | Setiap halaman memiliki metadata unik, heading semantik, sitemap, dan schema. |

### 1.7 Target Pengguna

#### A. Founder, Startup, dan Pemilik Bisnis

Pengguna yang membutuhkan bantuan hukum terkait pendirian usaha, kontrak bisnis, kepatuhan, investasi, partnership, atau perlindungan aset intelektual.

**Kebutuhan utama:**

- Memahami layanan hukum bisnis secara sederhana.
- Menilai apakah firma memahami konteks bisnis modern.
- Mendapatkan jalur konsultasi yang cepat.
- Melihat firma sebagai mitra strategis, bukan sekadar penyedia jasa hukum.

#### B. Perusahaan dan Institusi

Pengguna dari perusahaan, organisasi, yayasan, atau institusi yang membutuhkan pendampingan hukum berkelanjutan.

**Kebutuhan utama:**

- Menilai kredibilitas firma dan ruang lingkup layanan.
- Melihat pengalaman tim dan pendekatan kerja.
- Memastikan firma mampu menjaga kerahasiaan dan profesionalisme.
- Menghubungi firma melalui kanal resmi.

#### C. Individu Profesional

Pengguna individu yang membutuhkan pendampingan untuk masalah perdata, keluarga, waris, ketenagakerjaan, atau sengketa.

**Kebutuhan utama:**

- Mendapat penjelasan yang tidak terlalu teknis.
- Merasa aman untuk menghubungi firma.
- Menemukan layanan yang sesuai dengan masalahnya.
- Melihat proses konsultasi yang jelas.

#### D. Mitra Profesional

Konsultan bisnis, notaris, firma lain, akuntan, investor, atau pihak eksternal yang ingin mengenal Solstice Law.

**Kebutuhan utama:**

- Memahami profil firma dan spesialisasi.
- Melihat potensi kerja sama.
- Mengakses informasi kontak resmi.
- Menilai kesesuaian nilai profesional.

---

## 2. Positioning, Brand, dan Diferensiasi

### 2.1 Positioning Statement

**Solstice Law adalah firma hukum modern yang membantu klien melewati titik penting dalam keputusan hukum dan bisnis dengan pendampingan yang strategis, tenang, dan terpercaya.**

### 2.2 Brand Promise

> **Clarity at every turning point.**
> 

Makna:

- Solstice Law hadir pada momen penting ketika klien membutuhkan arah.
- Firma tidak hanya memberikan jawaban hukum, tetapi juga memberikan kejelasan strategi.
- Pengalaman klien harus terasa tenang, terarah, dan profesional.

### 2.3 Brand Personality

Solstice Law harus terasa:

- Tenang
- Strategis
- Premium
- Terpercaya
- Berwibawa
- Humanis
- Terstruktur
- Modern
- Bijaksana
- Tidak agresif

Website tidak boleh terasa:

- Terlalu ramai
- Terlalu eksperimental
- Terlalu generik
- Terlalu “template”
- Terlalu dingin atau sulit didekati
- Menggunakan visual hukum klise secara berlebihan

### 2.4 Diferensiasi dari LawConnect

| Aspek | LawConnect | Solstice Law |
| --- | --- | --- |
| Nuansa utama | Modern legal platform, tech-forward, akses cepat. | Premium legal counsel, calm authority, strategic clarity. |
| Warna dominan | Indigo dan violet modern. | Midnight navy, warm gold, ivory, dan stone gray. |
| Bahasa brand | Menghubungkan calon klien dengan layanan hukum. | Memberikan kejelasan pada titik keputusan hukum penting. |
| Target feel | Digital, cepat, accessible. | Elegan, matang, konsultatif, premium. |
| CTA tone | “Konsultasi Sekarang”, “Lihat Layanan”. | “Jadwalkan Konsultasi”, “Temukan Arah Hukum Anda”. |

---

## 3. Ruang Lingkup Produk

### 3.1 In Scope MVP

Fitur dan halaman yang termasuk dalam versi awal:

- Halaman Beranda
- Halaman Tentang Firma
- Halaman Layanan Hukum
- Halaman Pendekatan Kerja
- Halaman Tim
- Halaman Kontak
- Header responsif
- Mobile navigation
- Footer informatif
- CTA global
- Formulir konsultasi
- Validasi form client-side
- Integrasi Formspree atau Netlify Forms
- Google Maps embed
- Data layanan tersentralisasi
- Data tim tersentralisasi
- SEO dasar per halaman
- Open Graph metadata
- Twitter Card metadata
- JSON-LD schema
- Sitemap
- Robots.txt
- Optimasi gambar
- Deployment ke Vercel atau Netlify

### 3.2 Out of Scope MVP

Fitur yang tidak termasuk dalam versi awal:

- Sistem login klien
- Dashboard admin
- CMS custom
- Blog dinamis
- Portal dokumen klien
- Payment gateway
- Booking kalender otomatis
- Live chat real-time
- Multi-language support
- Case study detail dinamis
- Newsletter
- Otomasi CRM
- Area anggota atau client portal

Fitur-fitur tersebut dapat dipertimbangkan pada fase lanjutan setelah MVP stabil.

### 3.3 Future Scope

Rekomendasi pengembangan lanjutan:

1. Blog insight hukum bisnis.
2. Halaman detail untuk setiap layanan.
3. Booking konsultasi dengan integrasi kalender.
4. Integrasi WhatsApp Business.
5. CMS headless untuk konten.
6. Testimonial dan anonymized case highlights.
7. Newsletter legal update.
8. Multi-language Indonesia/English.
9. Downloadable legal checklist.
10. Client intake form yang lebih detail.

---

## 4. Arsitektur Sistem dan Teknologi

### 4.1 Pendekatan Arsitektur

Website dikembangkan dengan pendekatan **Static Site Generation** agar cepat, aman, dan mudah dikelola. Untuk company profile firma hukum, SSG sangat sesuai karena mayoritas konten bersifat informatif dan tidak memerlukan backend kompleks.

Keuntungan:

- Performa tinggi.
- Risiko keamanan lebih rendah.
- SEO-friendly.
- Hosting hemat biaya.
- Deployment sederhana.
- Maintenance ringan.
- Cocok untuk konten marketing dan company profile.

### 4.2 Tech Stack Utama

| Kategori | Teknologi | Alasan Pemilihan |
| --- | --- | --- |
| Framework | Astro.js | Ringan, cepat, cocok untuk website statis dengan kebutuhan SEO tinggi. |
| Styling | Tailwind CSS | Memudahkan konsistensi design system dan responsive layout. |
| Bahasa | TypeScript | Struktur data lebih aman dan maintainable. |
| Font | Playfair Display + Inter | Playfair untuk kesan editorial premium, Inter untuk keterbacaan modern. |
| Icon | Inline SVG | Ringan, scalable, dan mudah dikustomisasi. |
| Form Handling | Netlify Forms atau Formspree | Serverless, cepat dipasang, tanpa backend custom. |
| Image Optimization | Astro Image | Mendukung format modern dan lazy loading. |
| Deployment | Vercel atau Netlify | CI/CD mudah dan cocok untuk static site. |
| Version Control | GitHub | Kolaborasi, review, dan deployment otomatis. |

### 4.3 Struktur Direktori Rekomendasi

```
solstice-law/
├── public/
│   ├── fonts/
│   ├── images/
│   │   ├── brand/
│   │   ├── team/
│   │   ├── office/
│   │   └── og/
│   ├── favicon.svg
│   ├── robots.txt
│   └── sitemap.xml
├── src/
│   ├── components/
│   │   ├── ui/
│   │   │   ├── Button.astro
│   │   │   ├── Card.astro
│   │   │   ├── Input.astro
│   │   │   ├── Badge.astro
│   │   │   └── SectionHeader.astro
│   │   ├── layout/
│   │   │   ├── Header.astro
│   │   │   ├── Footer.astro
│   │   │   └── SEO.astro
│   │   └── sections/
│   │       ├── Hero.astro
│   │       ├── TrustBar.astro
│   │       ├── ServiceCard.astro
│   │       ├── ApproachSteps.astro
│   │       ├── TeamCard.astro
│   │       └── ConsultationForm.astro
│   ├── data/
│   │   ├── services.ts
│   │   ├── team.ts
│   │   ├── approach.ts
│   │   └── siteConfig.ts
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── firm.astro
│   │   ├── services.astro
│   │   ├── approach.astro
│   │   ├── team.astro
│   │   └── contact.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── tailwind.config.mjs
├── package.json
└── README.md
```

---

## 5. Brand dan Design System

### 5.1 Visual Direction

Konsep visual utama:

> **Premium legal counsel with calm authority and warm strategic clarity.**
> 

Website harus terlihat seperti firma hukum modern kelas atas: rapi, luas, elegan, dan tidak berlebihan. Gunakan whitespace besar, tipografi editorial, warna gelap yang stabil, dan aksen emas hangat.

### 5.2 Palet Warna

| Token | Warna | Hex | Fungsi |
| --- | --- | --- | --- |
| Midnight 950 | Deep Midnight Navy | `#0B1020` | Hero, header gelap, footer, teks utama di section premium. |
| Navy 900 | Executive Navy | `#111827` | Background gelap, heading kuat, elemen brand. |
| Gold 600 | Solstice Gold | `#C9943A` | CTA, highlight, divider dekoratif, ikon penting. |
| Gold 400 | Warm Gold | `#E6B85C` | Hover, accent ringan, ornament. |
| Ivory 50 | Soft Ivory | `#FAF7F0` | Background halaman terang. |
| Stone 100 | Legal Paper | `#F3EEE4` | Section alternatif dan card lembut. |
| Slate 700 | Professional Slate | `#334155` | Teks body gelap. |
| Slate 500 | Muted Slate | `#64748B` | Teks sekunder. |
| White | Pure White | `#FFFFFF` | Surface utama dan teks di background gelap. |
| Success | Emerald | `#059669` | State sukses. |
| Error | Crimson | `#B91C1C` | State error. |

### 5.3 Tipografi

| Elemen | Font | Weight | Ukuran Rekomendasi |
| --- | --- | --- | --- |
| Display / Hero | Playfair Display | 700 | 56–72px desktop, 40–48px mobile |
| H1 | Playfair Display | 700 | 48–64px desktop, 36–44px mobile |
| H2 | Playfair Display | 700 | 36–48px desktop, 30–36px mobile |
| H3 | Inter | 700 | 22–28px |
| Body | Inter | 400/500 | 16–18px |
| Caption | Inter | 400 | 13–14px |
| Button | Inter | 700 | 15–16px |

Ketentuan:

- Body text menggunakan `line-height` minimal 1.65.
- Heading editorial tidak boleh terlalu rapat.
- Maksimal panjang paragraf 70–80 karakter per baris.
- Gunakan uppercase kecil hanya untuk eyebrow label, bukan body text panjang.
- Font harus di-host lokal jika memungkinkan.

### 5.4 Komponen UI

#### Button

Varian:

| Varian | Fungsi | Style |
| --- | --- | --- |
| Primary Gold | CTA utama seperti “Jadwalkan Konsultasi”. | Gold background, navy text, hover lebih terang. |
| Secondary Dark | CTA alternatif pada background terang. | Navy background, white text. |
| Outline | CTA sekunder pada hero atau section gelap. | Border gold atau white, transparent background. |
| Ghost | Link navigasi ringan. | Transparent dengan hover underline. |

State wajib:

- Default
- Hover
- Active
- Focus-visible
- Disabled
- Loading

#### Card

Digunakan untuk:

- Service cards
- Principle cards
- Team cards
- Process cards
- Trust metrics

Karakteristik:

- Border `1px solid rgba(201, 148, 58, 0.18)`
- Border radius 16px
- Background ivory/white
- Shadow halus dengan warna navy transparan
- Hover `translateY(-4px)`
- Transition 200–300ms ease
- Tidak menggunakan shadow terlalu dramatis

#### Input Field

Field harus memiliki:

- Label eksplisit
- Placeholder jelas
- Helper text bila diperlukan
- State focus dengan ring gold
- State error dengan pesan spesifik
- Tap target minimal 44px
- Autocomplete sesuai field
- Kompatibilitas keyboard mobile

---

## 6. Struktur Halaman dan Kebutuhan Fungsional

### 6.1 Global Layout

Setiap halaman menggunakan struktur:

1. Header
2. Main content
3. Footer

Ketentuan:

- Header konsisten di semua halaman.
- Footer memuat informasi penting dan CTA ringan.
- Layout memiliki max-width konsisten.
- Section spacing luas agar terasa premium.
- Semua halaman menggunakan metadata SEO unik.

### 6.2 Header

Header harus berisi:

- Logo Solstice Law
- Menu navigasi
- CTA “Konsultasi”
- Hamburger menu pada mobile

Menu navigasi:

| Label | URL |
| --- | --- |
| Beranda | `/` |
| Tentang Firma | `/firm` |
| Layanan | `/services` |
| Pendekatan | `/approach` |
| Tim | `/team` |
| Kontak | `/contact` |

Behavior:

- Header sticky.
- Saat scroll, header berubah menjadi background solid dengan blur ringan.
- Active menu state terlihat jelas.
- Mobile menu dapat ditutup dengan tombol close, klik link, klik overlay, atau tombol Escape.
- Focus trap aktif saat mobile menu terbuka.
- CTA header mengarah ke `/contact`.

### 6.3 Footer

Footer harus berisi:

- Logo Solstice Law
- Deskripsi singkat firma
- Quick links
- Layanan utama
- Informasi kontak
- Alamat kantor
- Jam operasional
- Copyright
- Link kebijakan privasi jika tersedia

Struktur:

```
Footer
├── Brand Summary
├── Navigation
├── Legal Services
├── Contact Information
└── Copyright & Policy Links
```

---

## 7. Detail Halaman

### 7.1 Halaman Beranda — `index.astro`

#### Tujuan Halaman

Memberikan kesan pertama yang kuat, memperkenalkan positioning Solstice Law, menampilkan layanan utama, membangun kepercayaan, dan mengarahkan pengunjung menuju konsultasi.

#### Hero Section

Konten:

- Eyebrow: **Strategic Legal Counsel**
- Headline: **“Kejelasan Hukum untuk Setiap Titik Keputusan”**
- Sub-headline: “Solstice Law mendampingi individu, pelaku bisnis, dan organisasi dalam mengambil keputusan hukum yang strategis, terukur, dan terpercaya.”
- CTA utama: **Jadwalkan Konsultasi**
- CTA sekunder: **Pelajari Layanan Kami**
- Visual: foto kantor premium, abstraksi cahaya matahari, atau komposisi editorial hukum modern.

Acceptance criteria:

- H1 hanya satu.
- CTA utama mengarah ke `/contact`.
- CTA sekunder mengarah ke `/services`.
- Visual memiliki alt text deskriptif.
- Layout dua kolom pada desktop dan satu kolom pada mobile.
- Hero tetap terbaca pada viewport 320px.

#### Trust Indicators

| Metric | Label |
| --- | --- |
| 12+ | Tahun pengalaman kolektif |
| 150+ | Perkara dan konsultasi ditangani |
| 9 | Area layanan hukum |
| 24 Jam | Estimasi respon awal |

Catatan: angka dapat disesuaikan dengan data aktual firma.

#### Signature Services Snapshot

Menampilkan 4 layanan utama:

- Corporate & Commercial Advisory
- Dispute Resolution
- Employment & Industrial Relations
- Intellectual Property Protection

Setiap card memuat:

- Ikon SVG
- Nama layanan
- Deskripsi 1–2 kalimat
- Link “Lihat Detail”
- Hover state

#### Why Solstice Law

Poin utama:

- Pendekatan strategis, bukan hanya administratif.
- Komunikasi jelas tanpa jargon berlebihan.
- Analisis risiko yang terukur.
- Kerahasiaan klien sebagai prioritas.
- Pengalaman digital yang memudahkan konsultasi.
- Tim yang memahami kebutuhan bisnis dan individu.

#### Client Journey Preview

Menjelaskan proses singkat:

1. Ceritakan kebutuhan hukum.
2. Tim melakukan review awal.
3. Jadwalkan konsultasi.
4. Terima rekomendasi langkah berikutnya.

#### Final CTA

Headline:

> **Saat keputusan hukum terasa kompleks, Solstice Law membantu menemukan arah.**
> 

CTA:

- Jadwalkan Konsultasi
- Hubungi Tim Kami

### 7.2 Halaman Tentang Firma — `firm.astro`

#### Tujuan Halaman

Membangun kredibilitas melalui cerita firma, filosofi, visi, misi, dan prinsip kerja.

#### Page Hero

- Title: “Tentang Solstice Law”
- Subtitle: “Firma hukum modern yang menghadirkan ketenangan, kejelasan, dan strategi pada setiap keputusan hukum penting.”

#### Firm Story

Rekomendasi copy:

> Solstice Law berdiri dari keyakinan bahwa persoalan hukum tidak seharusnya membuat klien kehilangan arah. Kami hadir untuk membantu individu, bisnis, dan organisasi memahami risiko, melihat pilihan yang tersedia, dan mengambil keputusan dengan dasar hukum yang kuat.
> 

Desain:

- Layout editorial dua kolom.
- Paragraf rapi.
- Highlight quote.
- Foto kantor atau visual abstrak.
- Ornament garis emas minimal.

#### Visi dan Misi

| Visi | Misi |
| --- | --- |
| Menjadi firma hukum terpercaya yang memberikan kejelasan strategis pada momen-momen penting klien. | Menyediakan layanan hukum yang profesional, komunikatif, rahasia, dan berorientasi pada solusi jangka panjang. |

#### Prinsip Firma

- **Clarity** — setiap rekomendasi harus dapat dipahami.
- **Discretion** — kerahasiaan dan kehati-hatian menjadi fondasi.
- **Strategy** — solusi hukum harus mempertimbangkan tujuan klien.
- **Integrity** — keputusan profesional berlandaskan etika.
- **Responsiveness** — komunikasi harus tepat waktu dan relevan.

#### Brand Promise

> Kami membantu klien melihat persoalan hukum dengan lebih jernih, memilih langkah dengan lebih percaya diri, dan bergerak maju dengan strategi yang terukur.
> 

### 7.3 Halaman Layanan Hukum — `services.astro`

#### Tujuan Halaman

Menjelaskan layanan hukum Solstice Law secara jelas, terstruktur, dan mudah dipahami oleh calon klien.

#### Page Hero

- Title: “Layanan Hukum”
- Subtitle: “Pendampingan hukum strategis untuk bisnis, organisasi, dan individu.”

#### Service Areas Grid

| Layanan | Deskripsi Singkat |
| --- | --- |
| Corporate & Commercial Advisory | Pendampingan untuk pendirian usaha, struktur bisnis, kontrak komersial, dan kepatuhan perusahaan. |
| Contract Drafting & Review | Penyusunan dan peninjauan perjanjian agar risiko, kewajiban, dan hak para pihak tersusun jelas. |
| Dispute Resolution | Strategi penyelesaian sengketa melalui negosiasi, mediasi, arbitrase, maupun litigasi. |
| Employment & Industrial Relations | Konsultasi hubungan kerja, peraturan perusahaan, kontrak kerja, dan perselisihan ketenagakerjaan. |
| Intellectual Property Protection | Perlindungan merek, hak cipta, lisensi, dan aset kreatif atau teknologi. |
| Family & Estate Matters | Pendampingan untuk urusan keluarga, waris, perjanjian, dan penyelesaian konflik pribadi. |
| Regulatory Compliance | Review kepatuhan terhadap regulasi dan risiko operasional bisnis. |
| Real Estate & Property | Pendampingan transaksi properti, sewa, jual beli, dan review dokumen pertanahan. |
| Legal Risk Assessment | Analisis risiko hukum untuk keputusan bisnis, transaksi, kerja sama, atau ekspansi. |

Spesifikasi card:

- Ikon SVG sederhana.
- Nama layanan.
- Deskripsi 1–2 kalimat.
- Poin “Cocok untuk” maksimal 3 item.
- Link “Konsultasikan Layanan Ini”.
- Hover animation halus.

Responsivitas:

| Breakpoint | Layout |
| --- | --- |
| Mobile | 1 kolom |
| Tablet | 2 kolom |
| Desktop | 3 kolom |

### 7.4 Halaman Pendekatan — `approach.astro`

#### Tujuan Halaman

Menjelaskan cara kerja Solstice Law agar calon klien memahami proses konsultasi dan ekspektasi layanan.

#### Page Hero

- Title: “Pendekatan Kami”
- Subtitle: “Setiap persoalan hukum ditangani dengan proses yang terstruktur, rahasia, dan berorientasi pada hasil.”

#### Process Steps

| Tahap | Nama | Deskripsi |
| --- | --- | --- |
| 01 | Initial Understanding | Memahami kebutuhan, konteks, dokumen awal, dan tujuan klien. |
| 02 | Legal Mapping | Mengidentifikasi isu hukum, risiko, peluang, dan opsi penyelesaian. |
| 03 | Strategic Recommendation | Menyusun rekomendasi langkah yang jelas, realistis, dan dapat dieksekusi. |
| 04 | Execution Support | Mendampingi proses negosiasi, drafting, review, korespondensi, atau tindakan hukum. |
| 05 | Review & Continuity | Melakukan evaluasi lanjutan dan memastikan langkah hukum tetap selaras dengan tujuan klien. |

#### Service Principles

- Setiap rekomendasi harus memiliki alasan hukum yang jelas.
- Klien mendapat gambaran risiko sebelum mengambil keputusan.
- Komunikasi dibuat ringkas, sopan, dan mudah dipahami.
- Dokumen dan informasi klien dijaga secara rahasia.
- Solusi harus mempertimbangkan konteks bisnis atau pribadi klien.

### 7.5 Halaman Tim — `team.astro`

#### Tujuan Halaman

Menampilkan kredibilitas profesional tim Solstice Law.

#### Page Hero

- Title: “Tim Solstice Law”
- Subtitle: “Didukung oleh profesional hukum yang menggabungkan ketelitian, strategi, dan komitmen pada kepentingan klien.”

#### Team Grid

Setiap profil memuat:

| Field | Keterangan |
| --- | --- |
| Foto | Rasio 3:4 atau 4:5 |
| Nama Lengkap | Nama profesional hukum |
| Gelar | Gelar akademik/profesional |
| Jabatan | Managing Partner, Partner, Senior Associate, Associate |
| Spesialisasi | Bidang hukum utama |
| Bio Singkat | 2–3 kalimat |
| LinkedIn | Opsional |
| Email | Opsional |

Contoh data:

```tsx
export const teamMembers = [
  {
    name: "Raka Mahendra, S.H., LL.M.",
    role: "Managing Partner",
    expertise: ["Corporate Advisory", "Commercial Disputes", "Regulatory Compliance"],
    image: "/images/team/raka-mahendra.webp",
    linkedin: "https://linkedin.com",
  },
  {
    name: "Elena Prameswari, S.H., M.Kn.",
    role: "Partner",
    expertise: ["Property Law", "Contract Drafting", "Estate Matters"],
    image: "/images/team/elena-prameswari.webp",
    linkedin: "https://linkedin.com",
  },
  {
    name: "Dimas Aryasatya, S.H.",
    role: "Senior Associate",
    expertise: ["Employment Law", "Intellectual Property", "Legal Risk Assessment"],
    image: "/images/team/dimas-aryasatya.webp",
  },
];
```

Interaction:

- Hover pada foto menampilkan overlay tipis.
- Ikon LinkedIn muncul jika data tersedia.
- Card dapat diakses dengan keyboard.
- Jika foto belum tersedia, gunakan placeholder konsisten.
- Jangan menampilkan email personal jika belum dikonfirmasi.

### 7.6 Halaman Kontak — `contact.astro`

#### Tujuan Halaman

Memudahkan calon klien menghubungi Solstice Law dan mengirim permintaan konsultasi.

#### Page Hero

- Title: “Hubungi Solstice Law”
- Subtitle: “Ceritakan kebutuhan hukum Anda. Tim kami akan meninjau dan menghubungi Anda untuk langkah berikutnya.”

#### Informasi Kontak

| Informasi | Contoh |
| --- | --- |
| Alamat | District 8 Treasury Tower, Jakarta Selatan |
| Email | [contact@solsticelaw.id](mailto:contact@solsticelaw.id) |
| Telepon | +62 21 5089 1122 |
| WhatsApp | +62 811 9000 2727 |
| Jam Operasional | Senin–Jumat, 09.00–18.00 WIB |

#### Consultation Form

| Field | Type | Required | Validasi |
| --- | --- | --- | --- |
| Nama Lengkap | Text | Ya | Minimal 2 karakter |
| Email | Email | Ya | Format email valid |
| Nomor Telepon | Tel | Tidak | Angka, spasi, dan simbol telepon |
| Jenis Klien | Select | Ya | Individu, Bisnis, Perusahaan, Institusi, Mitra Profesional |
| Kategori Layanan | Select | Ya | Harus memilih satu kategori |
| Ringkasan Kebutuhan | Textarea | Ya | Minimal 30 karakter |
| Preferensi Kontak | Radio | Tidak | Email, Telepon, WhatsApp |

Pilihan kategori layanan:

- Corporate & Commercial Advisory
- Contract Drafting & Review
- Dispute Resolution
- Employment & Industrial Relations
- Intellectual Property Protection
- Family & Estate Matters
- Regulatory Compliance
- Real Estate & Property
- Legal Risk Assessment
- Lainnya

#### Form State

| State | Behavior |
| --- | --- |
| Default | Form siap diisi. |
| Loading | Button berubah menjadi “Mengirim permintaan...” |
| Success | Menampilkan pesan berhasil dan instruksi menunggu balasan. |
| Error | Menampilkan pesan gagal tanpa error teknis mentah. |
| Validation Error | Menampilkan pesan pada field terkait. |

Pesan sukses:

> Terima kasih. Permintaan konsultasi Anda telah diterima. Tim Solstice Law akan menghubungi Anda dalam estimasi 1×24 jam kerja.
> 

Pesan error:

> Maaf, permintaan belum dapat dikirim. Silakan coba lagi atau hubungi kami melalui email resmi.
> 

#### Google Maps Embed

Ketentuan:

- Menggunakan iframe.
- Memiliki atribut `loading="lazy"`.
- Memiliki title deskriptif.
- Tidak menjadi elemen LCP utama.
- Diletakkan setelah informasi kontak dan form.

---

## 8. Content Requirements

### 8.1 Tone of Voice

Gaya bahasa:

- Profesional
- Tenang
- Meyakinkan
- Humanis
- Tidak terlalu kaku
- Tidak menggunakan jargon hukum berlebihan
- Fokus pada kejelasan, strategi, dan rasa aman
- Menghindari klaim berlebihan

### 8.2 Prinsip Copywriting

Setiap copy harus:

- Menjelaskan manfaat bagi klien.
- Menggunakan kalimat singkat.
- Menghindari istilah hukum kompleks tanpa konteks.
- Memiliki CTA jelas.
- Membangun rasa percaya.
- Tidak menjanjikan hasil hukum tertentu.
- Menjaga kesan premium dan etis.

### 8.3 CTA Utama

CTA yang digunakan secara konsisten:

- Jadwalkan Konsultasi
- Hubungi Solstice Law
- Pelajari Layanan Kami
- Temukan Arah Hukum Anda
- Konsultasikan Kebutuhan Anda

### 8.4 Contoh Microcopy

| Konteks | Microcopy |
| --- | --- |
| Hero | Kejelasan hukum dimulai dari percakapan yang tepat. |
| Form helper | Ceritakan ringkasan kebutuhan Anda. Jangan mencantumkan data sensitif yang tidak diperlukan. |
| Privacy note | Informasi yang Anda kirimkan akan diperlakukan secara rahasia. |
| Service CTA | Konsultasikan layanan ini. |
| Final CTA | Ambil langkah hukum berikutnya dengan lebih percaya diri. |

---

## 9. Data Requirements

### 9.1 Data Layanan

```tsx
export type ServiceArea = {
  title: string;
  slug: string;
  summary: string;
  description: string;
  suitableFor: string[];
  icon: string;
};
```

### 9.2 Data Tim

```tsx
export type TeamMember = {
  name: string;
  role: string;
  degree?: string;
  expertise: string[];
  bio: string;
  image: string;
  linkedin?: string;
  email?: string;
};
```

### 9.3 Data Kontak

```tsx
export type ContactInfo = {
  address: string;
  email: string;
  phone: string;
  whatsapp: string;
  operationalHours: string;
  mapsEmbedUrl: string;
};
```

### 9.4 Site Config

```tsx
export type SiteConfig = {
  name: string;
  tagline: string;
  description: string;
  baseUrl: string;
  defaultOgImage: string;
  navigation: {
    label: string;
    href: string;
  }[];
};
```

---

## 10. User Flow

### 10.1 Flow Konsultasi dari Beranda

```
User membuka Home
→ Membaca hero dan positioning
→ Klik “Jadwalkan Konsultasi”
→ Masuk ke halaman Contact
→ Mengisi form konsultasi
→ Submit
→ Melihat pesan sukses
```

### 10.2 Flow Mencari Layanan

```
User membuka Home
→ Melihat Signature Services
→ Klik “Pelajari Layanan Kami”
→ Masuk ke Services
→ Membaca layanan yang relevan
→ Klik “Konsultasikan Layanan Ini”
→ Masuk ke Contact
```

### 10.3 Flow Menilai Kredibilitas Firma

```
User membuka website
→ Membuka Tentang Firma
→ Membaca filosofi dan prinsip kerja
→ Membuka Tim
→ Melihat profil profesional
→ Menghubungi firma
```

### 10.4 Flow Memahami Proses Kerja

```
User membuka Services
→ Merasa butuh informasi proses
→ Membuka Pendekatan
→ Membaca langkah kerja
→ Klik CTA konsultasi
```

---

## 11. Non-Functional Requirements

### 11.1 Performance

| Metrik | Target |
| --- | --- |
| Lighthouse Performance | 90+ |
| Largest Contentful Paint | ≤ 1,8 detik |
| First Contentful Paint | ≤ 1 detik |
| Cumulative Layout Shift | ≤ 0,1 |
| Total Blocking Time | ≤ 150ms |
| JavaScript Bundle | Seminimal mungkin |

Ketentuan:

- Hindari library JavaScript besar.
- Gunakan Astro island hanya bila diperlukan.
- Gunakan gambar WebP/AVIF.
- Font di-host lokal.
- Gunakan `font-display: swap`.
- Lazy load gambar non-kritis.
- Preload font utama jika berdampak pada LCP.
- Minifikasi CSS dan JS aktif saat build.

### 11.2 SEO

Setiap halaman wajib memiliki:

- Title tag unik.
- Meta description unik.
- Canonical URL.
- Open Graph title.
- Open Graph description.
- Open Graph image.
- Twitter Card.
- Struktur heading semantik.
- Alt text pada gambar.
- Sitemap.
- Robots.txt.

Contoh title:

| Halaman | Title |
| --- | --- |
| Home | Solstice Law — Strategic Legal Counsel |
| Firm | Tentang Solstice Law — Firma Hukum Strategis |
| Services | Layanan Hukum — Solstice Law |
| Approach | Pendekatan Hukum Strategis — Solstice Law |
| Team | Tim Profesional — Solstice Law |
| Contact | Hubungi Solstice Law — Konsultasi Hukum |

### 11.3 Schema Markup

#### Home Page — `LegalService`

```json
{
  "@context": "https://schema.org",
  "@type": "LegalService",
  "name": "Solstice Law",
  "description": "Firma hukum modern yang menyediakan pendampingan hukum strategis untuk individu, bisnis, dan organisasi.",
  "url": "https://solsticelaw.id",
  "telephone": "+62-811-9000-2727",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "District 8 Treasury Tower",
    "addressLocality": "Jakarta Selatan",
    "addressCountry": "ID"
  }
}
```

#### Team Page — `Person`

Halaman tim menggunakan schema `Person` untuk setiap anggota tim.

### 11.4 Accessibility

Website harus mengikuti **WCAG 2.1 Level AA**.

Ketentuan:

- Kontras teks minimal 4.5:1.
- Semua tombol memiliki label jelas.
- Semua gambar informatif memiliki alt.
- Form memiliki label yang terhubung dengan input.
- Navigasi dapat digunakan dengan keyboard.
- Focus-visible terlihat jelas.
- Tidak menggunakan warna sebagai satu-satunya indikator.
- Mobile menu dapat ditutup dengan keyboard.
- Heading tersusun semantik.
- Link memiliki teks bermakna.
- Error form terbaca oleh screen reader.

### 11.5 Security dan Privacy

Ketentuan dasar:

- Website menggunakan HTTPS.
- Form tidak menyimpan data sensitif di sisi client.
- Endpoint form tidak mengekspos secret.
- API key disimpan sebagai environment variable.
- Tambahkan honeypot anti-spam.
- Validasi input dilakukan sebelum submit.
- Jangan menampilkan error teknis mentah.
- Tambahkan privacy note pada form.
- Hindari menampilkan data klien atau kasus nyata tanpa izin.

### 11.6 Browser Compatibility

Website harus berjalan baik pada:

- Google Chrome versi terbaru
- Microsoft Edge versi terbaru
- Mozilla Firefox versi terbaru
- Safari versi terbaru
- Mobile Chrome
- Mobile Safari

---

## 12. Acceptance Criteria

### 12.1 General Acceptance Criteria

Website dianggap selesai jika:

1. Semua halaman utama berhasil dibuat.
2. Semua link navigasi berfungsi.
3. Website responsif pada lebar 320px hingga 1920px.
4. Tidak ada horizontal overflow.
5. Tidak ada layout shift signifikan.
6. Semua CTA mengarah ke halaman yang benar.
7. Semua gambar memiliki alt text.
8. Form kontak dapat dikirim.
9. Validasi form berjalan.
10. Metadata SEO lengkap.
11. Schema markup terpasang.
12. Build production berhasil tanpa error.
13. Lighthouse minimal 90 untuk Performance, Accessibility, Best Practices, dan SEO.

### 12.2 Page-Level Acceptance Criteria

| Halaman | Kriteria Selesai |
| --- | --- |
| Home | Hero, trust indicators, layanan ringkas, why section, process preview, dan CTA akhir tersedia. |
| Firm | Story, visi-misi, prinsip firma, dan brand promise tersedia. |
| Services | Grid layanan responsif berisi 9 layanan dengan deskripsi dan CTA. |
| Approach | Process steps dan prinsip layanan tersedia. |
| Team | Profil tim tampil dalam grid responsif dengan foto, spesialisasi, dan bio. |
| Contact | Informasi kontak, form konsultasi, validasi, state submit, privacy note, dan maps tersedia. |

### 12.3 Form Acceptance Criteria

Form dianggap selesai jika:

- Field required tidak dapat dikirim kosong.
- Email harus valid.
- Ringkasan kebutuhan terlalu pendek menampilkan error.
- Saat submit, button menampilkan loading state.
- Jika berhasil, muncul pesan sukses.
- Jika gagal, muncul pesan error.
- Halaman tidak refresh saat submit.
- Data terkirim ke Formspree atau Netlify Forms.
- Honeypot anti-spam tersedia.
- Privacy note tampil di dekat form.

---

## 13. Testing Plan

### 13.1 Functional Testing

Checklist:

- [ ]  Navigasi desktop berfungsi.
- [ ]  Navigasi mobile berfungsi.
- [ ]  Hamburger menu dapat dibuka dan ditutup.
- [ ]  Tombol Escape menutup mobile menu.
- [ ]  Semua CTA berfungsi.
- [ ]  Semua halaman dapat diakses.
- [ ]  Form dapat dikirim.
- [ ]  Validasi form berjalan.
- [ ]  Pesan sukses dan error tampil.
- [ ]  Google Maps tampil.
- [ ]  Link eksternal membuka tab baru jika diperlukan.

### 13.2 Responsive Testing

| Device | Width |
| --- | --- |
| Small Mobile | 320px |
| Mobile | 375px |
| Large Mobile | 425px |
| Tablet | 768px |
| Laptop | 1024px |
| Desktop | 1440px |
| Large Desktop | 1920px |

### 13.3 Accessibility Testing

Checklist:

- [ ]  Navigasi keyboard berjalan.
- [ ]  Focus state terlihat.
- [ ]  Semua input memiliki label.
- [ ]  Error form terbaca screen reader.
- [ ]  Semua gambar memiliki alt.
- [ ]  Heading tersusun benar.
- [ ]  Kontras warna memenuhi standar.
- [ ]  Mobile menu memiliki aria attributes yang sesuai.
- [ ]  Link memiliki teks bermakna.

### 13.4 Performance Testing

Tools:

- Lighthouse
- PageSpeed Insights
- WebPageTest
- Chrome DevTools

Checklist:

- [ ]  Tidak ada gambar berukuran berlebihan.
- [ ]  Tidak ada JavaScript tidak perlu.
- [ ]  Font tidak menyebabkan render blocking besar.
- [ ]  LCP element teroptimasi.
- [ ]  Tidak ada layout shift besar.
- [ ]  CSS production sudah ter-minify.
- [ ]  Asset menggunakan caching yang sesuai.

---

## 14. Timeline Implementasi

### Sprint 1 — Foundation & Architecture

**Durasi:** Hari 1–3

Deliverables:

- Setup repository GitHub.
- Setup Astro project.
- Setup Tailwind CSS.
- Setup struktur folder.
- Setup font lokal.
- Setup global style.
- Setup layout utama.
- Komponen Header.
- Komponen Footer.
- Komponen SEO.
- Konfigurasi sitemap dan metadata dasar.

### Sprint 2 — Design System & Components

**Durasi:** Hari 4–6

Deliverables:

- Button component.
- Card component.
- Input component.
- Badge component.
- SectionHeader component.
- ServiceCard component.
- TeamCard component.
- ConsultationForm component.
- Token warna dan typography.
- Responsive container system.

### Sprint 3 — Core Pages

**Durasi:** Hari 7–10

Deliverables:

- Home page.
- Firm page.
- Services page.
- Approach page.
- Team page.
- Data file layanan dan tim.
- Responsive layout.
- Hover state dan micro-interaction.

### Sprint 4 — Contact, SEO, Optimization & Deployment

**Durasi:** Hari 11–14

Deliverables:

- Contact page.
- Form integration.
- Google Maps embed.
- Form validation.
- SEO per halaman.
- Open Graph metadata.
- JSON-LD schema.
- Lighthouse audit.
- Accessibility improvement.
- Deployment production.
- README singkat.

---

## 15. Risiko dan Mitigasi

| Risiko | Dampak | Mitigasi |
| --- | --- | --- |
| Data firma belum final | Konten terasa placeholder atau kurang kredibel. | Gunakan placeholder terstruktur dan tandai bagian yang perlu diganti. |
| Foto tim belum tersedia | Team page kurang premium. | Gunakan placeholder konsisten dengan rasio 4:5 dan warna brand. |
| Copy terlalu mirip website sebelumnya | Brand Solstice Law tidak terasa unik. | Gunakan positioning “clarity, strategic counsel, calm authority” dan tone premium. |
| Visual terlalu gelap | Keterbacaan menurun. | Seimbangkan navy dengan ivory, white space, dan kontras AA. |
| Form service bermasalah | Lead tidak terkirim. | Siapkan fallback email link dan provider alternatif. |
| Animasi berlebihan | Performa dan kesan profesional menurun. | Batasi animasi pada hover dan transition halus. |
| Informasi kontak berubah | Pengunjung mendapat data tidak akurat. | Simpan data kontak di `siteConfig.ts`. |

---

## 16. Definition of Done

Proyek dinyatakan selesai jika:

- [ ]  Semua halaman sesuai PRD.
- [ ]  Semua komponen reusable sudah dibuat.
- [ ]  Semua konten utama tersedia.
- [ ]  Website responsif pada mobile, tablet, dan desktop.
- [ ]  Tidak ada broken link.
- [ ]  Form konsultasi berfungsi.
- [ ]  Validasi form lengkap.
- [ ]  Metadata SEO lengkap.
- [ ]  Schema markup terpasang.
- [ ]  Lighthouse score minimal 90.
- [ ]  Build production berhasil.
- [ ]  Website berhasil di-deploy.
- [ ]  README berisi setup, script, struktur folder, dan deployment notes.
- [ ]  Konten Solstice Law memiliki positioning dan copy yang berbeda dari LawConnect.

---

## 17. Ringkasan Eksekutif

Solstice Law adalah website company profile firma hukum premium yang menekankan **kejelasan, strategi, ketenangan, dan kepercayaan**. Website ini dirancang untuk membantu calon klien memahami layanan hukum, mengenal pendekatan firma, menilai kredibilitas tim, dan mengirim permintaan konsultasi secara mudah.

Versi awal mencakup enam halaman utama:

- Beranda
- Tentang Firma
- Layanan Hukum
- Pendekatan
- Tim
- Kontak

Website dibangun menggunakan **Astro.js** dan **Tailwind CSS** dengan pendekatan **Static Site Generation** agar cepat, aman, SEO-friendly, mudah dikelola, dan cocok untuk company profile firma hukum. Keberhasilan proyek diukur melalui kelengkapan halaman, performa Lighthouse 90+, aksesibilitas WCAG 2.1 AA, form konsultasi yang berfungsi, SEO lengkap, dan deployment production yang stabil.
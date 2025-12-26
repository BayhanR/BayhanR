<div align="center">
  
# Merhaba, Ben Furkan Bayhan

### Full Stack Developer | Next.js & TypeScript Enthusiast

[![GitHub followers](https://img.shields.io/github/followers/yourusername?style=social)](https://github.com/yourusername)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://twitter.com/yourusername)

</div>

---

## Hakkımda

Modern web teknolojileri ile **premium SaaS uygulamaları** geliştiren bir Full Stack Developer'ım. Özellikle **Next.js**, **TypeScript**, ve **Prisma** ile **ölçeklenebilir** ve **performanslı** sistemler tasarlıyorum.

---

## Projelerim

### BPMS - Bayhan Project Management System

<div align="center">
  
![BPMS Logo](https://img.shields.io/badge/BPMS-Project%20Management-FF1E56?style=for-the-badge&logo=trello&logoColor=white)

</div>

**Ultra premium proje yönetim SaaS'ı** - Apple Vision Pro + Linear 2025 + Arc browser tarzı tasarım.

#### Teknoloji Stack
- **Next.js 15** - App Router ile modern React geliştirme
- **TypeScript** - Tip güvenliği
- **Prisma** - ORM ve veritabanı yönetimi
- **Tailwind CSS** - Utility-first styling
- **shadcn/ui** - Premium UI componentler
- **Framer Motion** - Akıcı animasyonlar
- **NextAuth.js** - Authentication sistemi

#### Çalışma Mantığı

BPMS, **subscription (abonelik) tabanlı** bir SaaS platformudur:

1. **Multi-Tenant Architecture**
   - Her kullanıcı kendi workspace'lerini oluşturabilir
   - Workspace bazlı proje ve görev yönetimi
   - Rol tabanlı erişim kontrolü (RBAC)

2. **Proje Yönetimi**
   - Kanban board ile görev takibi
   - Takvim entegrasyonu (iCal export)
   - Tekrarlayan görevler (recurring tasks)
   - Proje şablonları ile hızlı başlangıç

3. **Ödeme Sistemi**
   - **Free Plan**: 1 workspace, 3 proje, 10 task/proje
   - **Pro Plan**: 99₺/ay - Sınırsız proje ve görev
   - **Enterprise Plan**: 299₺/ay - Gelişmiş özellikler
   - İyzico entegrasyonu ile otomatik yenileme

4. **Premium UI/UX**
   - Glassmorphism 2.0 tasarım sistemi
   - 3D stacked cards ile interaktif proje görünümü
   - Smooth scroll (Lenis) ile premium deneyim
   - Dark/Light mode desteği

#### Özellikler
- Workspace ve proje yönetimi
- Kanban board ile görev takibi
- Takvim entegrasyonu
- Ekip yönetimi ve davet sistemi
- Subscription yönetimi
- API erişimi (Pro+ planlar)

---

### BayhanTech - Multi-Tenant Portal Sistemi

<div align="center">
  
![BayhanTech Logo](https://img.shields.io/badge/BayhanTech-Multi%20Tenant-FF006E?style=for-the-badge&logo=code&logoColor=white)

</div>

**Çoklu şirket yönetim sistemi** - Her şirket kendi dashboard'una sahip, kendi içeriklerini yönetir.

#### Teknoloji Stack
- **Next.js 15** - App Router
- **TypeScript** - Tip güvenliği
- **Supabase** - Backend as a Service
  - PostgreSQL veritabanı
  - Authentication
  - Storage (Object Storage)
- **Prisma** - ORM
- **Tailwind CSS** - Styling
- **shadcn/ui** - UI components

#### Çalışma Mantığı

BayhanTech, **multi-tenant (çok kiracılı)** bir portal sistemidir:

1. **Portal Giriş Sistemi**
   ```
   Kullanıcı → Şirket logosu seçer → Login → Şirkete özel dashboard
   ```

2. **Şirket Bazlı Dashboard'lar**
   - **Brew Gayrimenkul** (`brew`): Emlak ilanları yönetimi
     - İnşaat projeleri (biten/devam eden)
     - Fotoğraf yükleme
     - İl/İlçe, yıl, ilerleme yüzdesi bilgileri
   
   - **Tezerperde.com** (`perdeci`): Perde ürün galerisi
     - Otomatik ürün oluşturma (fotoğraf yükleme ile)
     - Ürün yönetimi
     - Galeri görünümü

3. **Fotoğraf Yönetim Sistemi**
   - **Supabase Storage** ile dosya yönetimi
   - Her ürün/emlak için ayrı klasör yapısı
   - Public URL'ler ile hızlı erişim
   - Veritabanında URL kayıtları

4. **Veri Yapısı**
   ```sql
   profiles (kullanıcı profilleri + kategori)
   ├── properties (emlak ilanları)
   │   └── property_images (fotoğraflar)
   └── products (ürünler)
       └── product_images (fotoğraflar)
   ```

5. **Güvenlik**
   - Row Level Security (RLS) ile veri izolasyonu
   - Kullanıcılar sadece kendi verilerine erişir
   - Storage policies ile güvenli dosya erişimi

#### Özellikler
- Çoklu şirket desteği
- Şirket bazlı dashboard'lar
- Fotoğraf yükleme ve yönetimi
- Public API ile veri paylaşımı
- Abonelik yönetimi
- Responsive tasarım

---

## Teknoloji Stack

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=flat&logo=Prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-181818?style=flat&logo=supabase&logoColor=white)

### Tools & Services
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## GitHub İstatistikleri

<div align="center">
  
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF1E56&icon_color=FF006E)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF1E56)

![GitHub Streak](https://github-readme-streak-stats.demolab.com/?user=yourusername&theme=radical&hide_border=true&background=0D1117&ring=FF1E56&fire=FF006E&currStreakLabel=FF1E56)

</div>

---

## Tasarım Felsefesi

- **Premium UI/UX**: Glassmorphism, 3D effects, smooth animations
- **Performance First**: Optimize edilmiş bundle size, lazy loading
- **Type Safety**: TypeScript ile güvenli kod yazımı
- **Scalability**: Multi-tenant architecture, microservices-ready
- **Developer Experience**: Clean code, comprehensive documentation

---

## Blog & İçerik

- [BPMS Teknik Dokümantasyon](https://github.com/yourusername/BPMS)
- [BayhanTech Portal Rehberi](https://github.com/yourusername/BayhanTech)
- [Next.js Best Practices](https://github.com/yourusername)

---

## İletişim

<div align="center">
  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](bayhan.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/bayhan1606)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF1E56?style=for-the-badge&logo=vercel&logoColor=white)](https://bayhan.tech)

</div>

---

<div align="center">

Projelerimi beğendiyseniz yıldız vermeyi unutmayın!

</div>


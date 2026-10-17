# 🛠️ AI-Crafted Micro Tools | Yapay Zeka Destekli Mikro Araçlar

[🇬🇧 English](#-english) | [🇹🇷 Türkçe](#-türkçe)

---

## 🇬🇧 English

A curated monorepo of **zero-dependency, single-file micro web applications** designed to solve everyday practical problems—architected by a human, generated in collaboration with Artificial Intelligence (LLMs).

> **🤖 AI Transparency Note:**  
> All system requirements, user experience flows, and functional architectures in this repository are directed and validated by me through iterative prompt engineering, while the underlying HTML/CSS/JS source code is synthesized using Generative AI models.

### 🎯 Core Architecture Principles
- **Single-File & Zero-Build:** Every utility runs out-of-the-box from a single `index.html` file without requiring `npm`, bundlers, or backend servers.
- **Privacy & Offline-First:** 100% client-side execution. All user data stays strictly in your browser's `localStorage`—nothing is ever sent to an external server.
- **Mobile & PWA Ready:** Designed with responsive layouts that can be installed directly onto mobile devices (Add to Home Screen) or wrapped into standalone `.apk` binaries.

### 🚀 Available Micro Tools

| # | Tool Name | Category | Description | Source Code | Live App |
|---|-----------|----------|-------------|-------------|----------|
| 01 | **Budget & Debt Payoff Tracker** | Finance | Manage salary, income, fixed expenses, credit cards, overdrafts (KMH), and loans with remaining month/payoff date calculations and an early-payoff simulator. | [Code](./tools/para-programlama/) | [Launch App](./tools/para-programlama/index.html) |

### 📱 How to Use as a Mobile App (PWA / APK)
1. **Direct Web / PWA:** Open the **Launch App** link via GitHub Pages on your phone -> Tap **"Add to Home Screen"** in your mobile browser menu.
2. **Standalone APK:** Wrap any tool's `index.html` using **Capacitor** or online WebView builders (e.g., WebIntoApp) to generate an offline Android `.apk`.

---

## 🇹🇷 Türkçe

Günlük hayattaki spesifik problemleri ve hesaplama ihtiyaçlarını çözmek amacıyla **insan mimarisi ve Yapay Zeka (LLM) iş birliğiyle** geliştirilmiş, dış bağımlılığı olmayan (Zero-Dependency), tek dosyadan çalışan mikro web uygulamaları koleksiyonu.

> **🤖 Yapay Zeka Şeffaflık Notu:**  
> Bu depoda yer alan araçların problem tanımları, algoritma/akış kurgusu, yönlendirmeleri (prompt engineering) ve test süreçleri tarafımdan yürütülmüş; arayüz (HTML/CSS) ve iş mantığı (JavaScript) kodları üretken yapay zeka modelleri kullanılarak oluşturulmuştur.

### 🎯 Temel Mimari Prensipler
- **Tek Dosya & Kurulumsuz (Zero-Build):** Her araç tek bir `index.html` dosyası içinde çalışır; ek paket kurulumu, derleme veya sunucu gerektirmez.
- **Tam Gizlilik & Çevrimdışı Çalışma:** Tüm veriler yalnızca cihazınızın yerel tarayıcı hafızasında (`localStorage`) saklanır; hiçbir veri dış sunuculara aktarılmaz.
- **Mobil ve APK Uyumlu:** Telefon, tablet ve bilgisayarda duyarlı (responsive) olarak çalışır; ana ekrana kısayol (PWA) olarak eklenebilir veya `.apk` dosyasına dönüştürülebilir.

### 🚀 Mevcut Araçlar Listesi

| # | Araç Adı | Kategori | Açıklama | Kaynak Kod | Canlı Uygulama |
|---|----------|----------|----------|------------|----------------|
| 01 | **Para Programlama & Borç Takip** | Finans | Maaş, ek gelir, sabit gider, kredi kartı, ek hesap (KMH) ve kredi borçlarının kalan ay / bitiş tarihi hesaplayıcısı ve erken kapama simülatörü. | [Kod](./tools/para-programlama/) | [Uygulamayı Aç](./tools/para-programlama/index.html) |

### 📱 Telefona Uygulama Olarak Kurulum (PWA / APK)
1. **GitHub Pages (PWA):** Telefonunuzdan tablodaki **Uygulamayı Aç** bağlantısına tıklayın -> Tarayıcı menüsünden **"Ana Ekrana Ekle"** seçeneğine dokunun.
2. **APK Olarak Derleme:** İlgili aracın `index.html` dosyasını **Capacitor** veya WebIntoApp gibi araçlarla sararak doğrudan kurulabilir `.apk` dosyası elde edebilirsiniz.

---

## 📄 License / Lisans
MIT License
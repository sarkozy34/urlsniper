# ⚡ UrlSniper - Ultimate Discord Vanity URL Sniper

<p align="center">
  <img src="https://sniper.sarkozy.xyz/favicon.png" alt="UrlSniper Logo" width="120" style="border-radius: 20%;" />
</p>

<p align="center">
  <strong>Zero VDS Cost, Maximum Speed. Claim Discord vanity URLs in under 15ms.</strong><br>
  <em>Sıfır VDS Ücreti, Maksimum Hız. Discord vanity kodlarınızı 15ms altında anında yakalayın.</em>
</p>

<p align="center">
  <a href="https://sniper.sarkozy.xyz/"><img src="https://img.shields.io/badge/Live_Console-sniper.sarkozy.xyz-7c3aed?style=for-the-badge&logo=discord&logoColor=white" alt="Live Console" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/VDS_Cost-Zero_($0)-emerald?style=flat-square" alt="VDS Cost" />
  <img src="https://img.shields.io/badge/Claim_Delay-0ms-blue?style=flat-square" alt="Delay" />
  <img src="https://img.shields.io/badge/Engine-HTTP%2F2_Multiplex-orange?style=flat-square" alt="Engine" />
  <img src="https://img.shields.io/badge/Security-AES--256--GCM-red?style=flat-square" alt="Security" />
</p>

---

## 🇬🇧 English Description

### 🚀 Why UrlSniper?

Normally, running a Discord vanity sniper requires renting a VDS (Virtual Dedicated Server) costing **$5 - $20/month**, setting up terminal environments, and keeping it running 24/7. 

**UrlSniper eliminates all VDS costs and technical struggles:**

- **Zero VDS Cost:** We host the sniper engine for you on our high-speed servers 24/7. Just log into our web panel and configure your target URL. No VDS rental required!
- **Extreme Speed (HTTP/2):** Built with persistent HTTP/2 connection pooling and preflight request technology directly linked to the closest Discord API endpoints. Claims vanity codes in **under 15ms**.
- **7/24 Web Control Center:** Manage multiple runners, view live websocket logs, and update target configurations instantly from any desktop or mobile browser.

👉 **Start Sniping Now:** [https://sniper.sarkozy.xyz/](https://sniper.sarkozy.xyz/)

---

### ✨ Features

- **⚡ Ultra-Low Latency:** Uses HTTP/2 connection multiplexing and local DNS caching to achieve sub-15ms claim times.
- **🔑 Automated MFA/2FA Bypass:** Automatically generates and applies 2FA TOTP tokens precisely at the moment of claim, bypassing authorization delays.
- **🔒 AES-256 Encrypted Storage:** All Discord tokens and credentials are encrypted at rest using AES-256-GCM prior to database storage.
- **💬 Real-Time Console Stream:** View active bot runner statuses and gateway connections live via WebSockets.

---

### 📊 Plans & Pricing

Save VDS costs and enjoy instant claiming with our optimized tiers:

| Tier | Price | Features |
| :--- | :--- | :--- |
| **Free Trial** | **$0 / 24h** | 1 Active Sniper Slot, 1000ms Artificial Delay, WebSocket Live Terminal, Standard Support |
| **Standard Plan** | **$10 / Month** | 5 Active Sniper Slots, **0ms Instant Claim**, Preflight HTTP/2 Warmups, Live 2FA Indicator, Priority Tickets |
| **Source Code (Developer)** | **$50 / One-Time** | **Full Project Source Code (Backend + Frontend)**, Self-Hosting Guide, Unlimited Slots, Theme Customization, Lifetime Updates |

---

### ⚙️ Performance Architecture

```
[Discord Gateway] ──(WS Event: GUILD_UPDATE)──> [UrlSniper Engine]
                                                        │ (Fastest DNS IP)
                                                        ▼
[Discord API] <───(Fires Payload in <15ms)───── [Preflighted HTTP/2 Channel]
```

1. **Connection Pooling:** Keeps active HTTP/2 multiplexed streams alive, bypassing connection handshake delay on claim.
2. **DNS Probing:** Resolves and caches the fastest responding Discord API IP address dynamically.
3. **Preflight Header Warmup:** Sends request headers beforehand so that only the small body payload travels during the claim event.

---

### 💻 Dashboard Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/dexycan/dreamsandrealities/main/preview.png" alt="UrlSniper Web Control Panel" width="90%" style="border-radius: 8px; border: 1px solid #2d3139;" />
</p>

---

### 🔗 Quick Start

1. Go to [https://sniper.sarkozy.xyz/](https://sniper.sarkozy.xyz/)
2. Log in securely with Discord OAuth.
3. Add your Server ID and target Vanity URL.
4. Turn the runner switch ON and watch it run 24/7 without paying VDS fees!

---

<br>

## 🇹🇷 Türkçe Açıklama

### 🚀 Neden UrlSniper?

Geleneksel Discord sniper yazılımlarını çalıştırmak için aylık **$5 - $20** arası VDS (Sanal Sunucu) kiralamanız, terminal komutlarıyla uğraşmanız ve sunucuyu 7/24 açık tutmanız gerekir. 

**UrlSniper ile tüm bu masraf ve uğraş geride kalıyor!**

- **Sıfır VDS Ücreti:** Kendi sunucumuzu 7/24 sizin için çalıştırıyoruz. Web paneline girip bilgilerinizi yazmanız yeterli. VDS kiralamanıza gerek yok!
- **Olağanüstü Hız (HTTP/2):** Klasik yavaş HTTP/1.1 kütüphaneleri yerine, doğrudan en yakın Discord sunucularına açık tutulan aktif HTTP/2 tünelleri ve ön-sorgu (preflighting) teknolojisini kullanıyoruz. Kodun claim hızı **15ms** altındadır.
- **7/24 Web Kontrol Paneli:** Telefonunuzdan veya bilgisayarınızdan tek tıkla web paneline girip sniper ajanlarınızı yönetebilir, logları canlı akışla izleyebilirsiniz.

👉 **Hemen Başlayın:** [https://sniper.sarkozy.xyz/](https://sniper.sarkozy.xyz/)

---

### ✨ Özellikler

- **⚡ Ultra-Düşük Gecikme:** HTTP/2 bağlantı havuzlama ve yerel DNS önbelleği sayesinde gecikmeleri tamamen sıfırlar.
- **🔑 Otomatik 2FA (MFA) Yönetimi:** Hesabınızda 2FA koruması açık olsa bile, sistem arka planda milisaniyeler içinde TOTP kodu üreterek claim işlemini gecikmesiz tamamlar.
- **🔒 AES-256 Kriptolu Depolama:** Tokenleriniz ve 2FA anahtarlarınız sunucumuzda AES-256-GCM algoritmalarıyla tamamen şifrelenmiş olarak saklanır.
- **💬 Canlı Terminal Logları:** WebSocket entegrasyonu sayesinde sniper botunuzun durumunu canlı olarak web konsolundan takip edebilirsiniz.

---

### 📊 Abonelik ve Fiyatlandırma

Her ihtiyaca ve bütçeye uygun paketlerimizle VDS masrafından kurtulun:

| Paket Türü | Fiyat | Özellikler |
| :--- | :--- | :--- |
| **Free Trial (Deneme)** | **$0 / 24 Saat** | 1 Aktif Sniper Slotu, 1000ms Yapay Gecikme, Canlı WebSocket Terminali, Standart Destek |
| **Standard Plan** | **$10 / Aylık** | 5 Aktif Sniper Slotu, **0ms Anında Claim (Gecikmesiz)**, Sıcak HTTP/2 Warmup, Canlı 2FA Göstergesi, Öncelikli Destek |
| **Source Code (Geliştirici)** | **$50 / Tek Seferlik** | **Tüm Proje Kaynak Kodları (Backend + Frontend)**, Kendi Sunucunu Kurma Rehberi, Sınırsız Slot, Tema Özelleştirme, Ömür Boyu Güncellemeler |

---

### ⚙️ Performans Mimarisi (Neden En Hızlısı?)

```
[Discord Sunucuları] ──(Değişiklik Algılandı)──> [UrlSniper Engine]
                                                        │ (En Hızlı IP Üzerinden)
                                                        ▼
[Discord API] <───(Fires Payload in <15ms)───── [Hazırda Bekleyen HTTP/2 Tüneli]
```

1. **Bağlantı Havuzlama (Connection Pooling):** Claim isteği geldiğinde yeni bir bağlantı kurulmaz. Bağlantılar arka planda dama açık ve "sıcak" tutulur.
2. **DNS Probing:** Discord'un en hızlı yanıt veren sunucu IP'si algılanıp önbelleğe alınır.
3. **Ön Hazırlıklı İstek (Preflighting):** Başlıklar önceden gönderilir; URL boşa çıktığı salisede sadece gövde (payload) fırlatılır.

---

### 💻 Panel Görüntüsü

<p align="center">
  <img src="https://raw.githubusercontent.com/dexycan/dreamsandrealities/main/preview.png" alt="UrlSniper Web Kontrol Paneli" width="90%" style="border-radius: 8px; border: 1px solid #2d3139;" />
</p>

---

### 🔗 Hızlı Kurulum ve Başlangıç

1. **[https://sniper.sarkozy.xyz/](https://sniper.sarkozy.xyz/)** adresine gidin.
2. Discord hesabınızla güvenli bir şekilde giriş yapın.
3. Sniper ayarlarından Server ID'nizi ve yakalamak istediğiniz Vanity URL'yi girin.
4. Botu aktif edin ve VDS masrafı ödemeden 7/24 çalışmasını izleyin!

---

<p align="center">
  UrlSniper Ekibi tarafından ❤️ ile geliştirilmiştir. Değerli Discord linklerinizi güvenceye alın.
</p>

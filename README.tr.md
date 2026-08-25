<div align="center">

<img src="onepage/assets/logo.png" alt="NULLOG" width="120" height="120"/>

<br/>

# NULLOG

### Android için Kurumsal, Cihaz-Üstü Gizlilik Güvenlik Duvarı

[![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-3DDC84?style=flat-square&logo=android&logoColor=white)](#)
[![Sürüm](https://img.shields.io/badge/Sürüm-v2.4-10B981?style=flat-square)](#)
[![Motor](https://img.shields.io/badge/Motor-%25100%20Cihaz%20Üstü-0E1524?style=flat-square)](#)
[![DNS](https://img.shields.io/badge/DNS-DoH%20%2F%20DoT-6366F1?style=flat-square)](#)
[![Log](https://img.shields.io/badge/Log-Sıfır-10B981?style=flat-square)](#)

**Sıfır bulut yönlendirmesi. Sıfır kayıt. Sıfır uzlaşma.**

[⬇️ APK İndir](#kurulum) · [🌐 Ürün Sayfası](onepage/index.html) · [💬 Telegram](https://t.me/e3x6v)

<br/>

> *NULLOG; reklamları, takipçileri ve arka plan casus yazılımlarını ağ katmanında, telefonunuzdaki tüm uygulamalarda aynı anda engeller. Root gerekmez.*

<br/>

---

</div>

## NULLOG Nedir?

NULLOG, Android için tamamen cihazınız üzerinde çalışan **sistem genelinde bir ağ güvenlik duvarıdır**. Yalnızca tarayıcıda çalışan geleneksel reklam engelleyicilerinden veya tüm trafiğinizi uzak bir sunucudan geçiren bulut VPN'lerinden farklı olarak, NULLOG DNS trafiğini yerel olarak — cihaz belleğinde — herhangi bir istek internete ulaşmadan önce inceleyip filtreler.

Hesap gerekmez. İsteyene kadar abonelik yok. Sadece yükle, dokun ve rahat bir nefes al.

---

## ✨ Özellikler

<br/>

### 🛡️ Sistem Genelinde Reklam & Takipçi Engelleme
Reklamları ve takipçileri sadece tarayıcında değil, **cihazdaki her uygulamada** engelle. Oyunlar, sosyal medya, haber uygulamaları, araçlar — hepsi tek bir birleşik motor üzerinden filtrelenir.

- Alt milisaniye alan eşlemesi (`< 0.4 ms`)
- EasyList, EasyPrivacy ve Peter Lowe'un Reklam & Takipçi listesiyle güçlendirildi
- Uygulama bazlı ayrıntılı kurallar — her uygulamayı ayrı ayrı izin ver veya engelle
- Giriş sorunlarını önlemek için bankacılık uygulamaları otomatik olarak beyaz listeye alındı

<br/>

### 🕵️ Arka Plan Casus Yazılım Radarı
Çoğu casus yazılım reklam göstermez — telefon ekranın kapalıyken sessizce ana sunucularını arar. NULLOG onları gerçek zamanlı olarak yakalar ve engeller.

| Tespit Edilen SDK | Engellenen Alan Adı | Kategori |
|:---|:---|:---|
| **Firebase Analytics** | `firebaselogging-pa.googleapis.com` | Google Telemetrisi |
| **Meta / Facebook** | `graph.facebook.com` | Sosyal Takip |
| **AppsFlyer** | `t.appsflyer.com` | Attribution SDK |
| **TikTok / ByteDance** | `log.musical.ly` | Davranışsal Takip |
| **Yandex AppMetrica** | `appmetrica.yandex.com` | Analitik SDK |
| **Adjust** | `app.adjust.com` | Attribution SDK |

<br/>

### ☕ Sessiz Pazar Özeti
Bildirim spam'i yok. NULLOG hafta boyunca tamamen sessiz çalışır ve her **Pazar saat 20:00'da** tek bir konsolide gizlilik raporu sunar — senin adına nelerin engellendiğine dair temiz bir genel bakış.

<br/>

### 🔐 Şifreli DNS (DoH / DoT)
NULLOG üzerinden geçen her DNS sorgusu, İSS'inize ulaşmadan önce şifrelenir — gözetleme, ortadaki adam saldırıları ve bölgesel alan adı engelleme önlenir.

| Çözümleyici | Protokol | Durum |
|:---|:---|:---|
| Cloudflare 1.1.1.1 | DNS-over-HTTPS | ✅ Aktif |
| Quad9 9.9.9.9 | DNS-over-TLS | ✅ Hazır |
| AdGuard DNS | DNS-over-HTTPS | ✅ Hazır |
| Özel Uç Nokta | DoH / DoT | ✅ Yapılandırılabilir |

<br/>

### 🔑 Donanım Bağlı Lisanslama
Pro lisanslar cihaz donanımına kriptografik olarak bağlıdır — hiçbir zaman hesap, e-posta veya kredi kartı gerekmez. Telegram üzerinden etkinleştir, sonsuza kadar kullan.

---

## 📊 NULLOG Diğerleriyle Nasıl Karşılaştırılır?

| | NULLOG | Bulut VPN | Tarayıcı Uzantısı |
|:---|:---:|:---:|:---:|
| Tüm uygulamalarda çalışır | ✅ | ✅ | ❌ Sadece tarayıcı |
| Sıfır log garantisi | ✅ Cihaz üstü | ⚠️ Güven gerekir | ⚠️ Uzantı telemetrisi |
| Batarya tüketimi | ✅ %1'den az | ❌ Yüksek | ✅ Düşük |
| Eklenen gecikme | ✅ < 0.4 ms | ❌ 50–150 ms | ✅ İhmal edilebilir |
| Arka plan casus engeli | ✅ | ❌ | ❌ |
| DNS şifrelemesi | ✅ DoH / DoT | ⚠️ Değişir | ❌ Yok |
| Hesap gerektirmez | ✅ | ❌ | ✅ |

---

## ⬇️ Kurulum

**Android 8.0+ · ARM64 / x86 Evrensel · 13.5 MB**

👉 [**APK İndir (v2.4)**](onepage/assets/app-release.apk)

### Yan Yükleme Adımları
1. APK'yı Android cihazınıza indirin.
2. **Ayarlar → Güvenlik → Bilinmeyen Kaynaklardan Yükle** seçeneğini tarayıcınız veya dosya yöneticiniz için etkinleştirin.
3. APK dosyasına dokunun ve yükleyin.
4. NULLOG'u açın, kalkan simgesine dokunun ve tek seferlik yerel VPN iznini kabul edin.

> NULLOG, **yalnızca yerel paket inceleme soketi** oluşturmak için Android'in `VpnService` API'sini kullanır. Verileriniz hiçbir zaman NULLOG aracılığıyla cihazı terk etmez.

### 🚀 İlk Açılış Bonusu
Her yeni kurulum otomatik olarak **90 gün Pro** alır — aktivasyon gerekmez.

---

## 💬 Destek & Lisanslama

| | |
|:---|:---|
| **Telegram** | [@e3x6v](https://t.me/e3x6v) |
| **Pro Lisans** | Telegram üzerinden ömür boyu satın al |
| **Ürün Sayfası** | [nullog.app](onepage/index.html) |

---

## 🔒 Gizlilik Taahhüdü

- **Hiçbir veri asla toplanmaz** — anonimleştirilmiş analitik bile yok
- Paket incelemesinde **uzak sunucu kullanılmaz**
- Hiçbir noktada **hesap gerekmez**
- Tüm istatistikler (engelleme sayısı, tasarruf edilen veri) **yalnızca cihazınızda** istediğiniz zaman silebileceğiniz yerel bir veritabanında saklanır

---

<div align="center">

**© 2026 NULLOG Security Core. Tüm hakları saklıdır.**

*Telefonunun ne yaptığını gerçekten önemseyen insanlar için yapıldı.*

</div>

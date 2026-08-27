# Geri Bildirim Sitesi

Kullanıcılardan geri bildirim alan basit bir web uygulaması.

## 🚀 Özellikler

- Ana sayfa: Geri bildirim formu
- Admin paneli: Alınan geri bildirimleri görüntüleme
- Modern ve göz alıcı tasarım
- Supabase entegrasyonu

## 📋 Kurulum

### Gereklilikler
- Supabase hesabı
- Web tarayıcısı

### Adımlar

1. **Supabase Ayarları**
   - Supabase'den yeni bir proje oluştur
   - API keys'i kopyala (Publishable key)

2. **Ortam Değişkenleri**
   - `.env.example` dosyasından `.env` kopyala
   - Supabase credentials'ı `.env` dosyasına ekle

3. **Siteyi Çalıştır**
   - `index.html` açarak geri bildirim formunu görebilirsin
   - `admin.html` ile admin paneline erişebilirsin

## 🔐 Güvenlik Notu

- Supabase API keys bu repository'de **hard-coded** olarak saklanmıştır
- Production için environment variables veya backend API kullanılması önerilir
- Repository public olduğu için sensitive bilgilere dikkat et

## 📝 Lisans

MIT

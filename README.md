# Vendora – Global B2B Talep Bazlı Toptan Ticaret Platformu (MVP)
Vendora, farklı ülkelerdeki tedarikçi ve alıcıları;
**talep bazlı teklif sistemi** ve **platform içi korumalı ödeme modeli**
ile bir araya getiren global bir B2B toptan ticaret platformudur.
Bu repo, Vendora’nın web tabanlı MVP sürümünü içerir.
## 🎯 Projenin Amacı
- Global alıcı ve tedarikçileri tek bir platformda buluşturmak
- Ürün taleplerini merkezi ve şeffaf şekilde toplamak
- Talep → teklif → ödeme sürecini platform içinde tutmak
- Ülkeler arası B2B ticareti güvenli ve kontrol edilebilir hale getirmek
- Komisyon bazlı sürdürülebilir bir gelir modeli oluşturmak
## 👥 Kullanıcı Tipleri
### 🅰️ Alıcı (Buyer)
- Firma hesabı ile kayıt olur
- Ürün talebi oluşturur
- Gelen teklifleri karşılaştırır
- Bir teklifi seçer
- Ödemeyi platform üzerinden yapar
### 🅱️ Tedarikçi (Supplier)
- Firma hesabı ile kayıt olur
- Ürünlerini fiyat belirtmeden listeler
- Gelen talepleri görür
- Talep bazlı teklif verir
### 🅾️ Admin
- Tüm sistemi izler ve yönetir
- Kullanıcıları onaylar veya pasif yapar
- Talep, teklif ve ödeme akışlarını kontrol eder
- Ülke bazlı komisyon oranlarını belirler
- Ödeme süreçlerini onaylar veya durdurur
> ⚠️ MVP aşamasında bazı operasyonlar manuel olarak admin kontrolündedir.
## 🏭 Desteklenen Sektörler (MVP)
1. Ambalaj & Sarf
2. Temizlik
3. Gıda (Paketli)
4. Endüstriyel Sarf & İş Güvenliği
5. Rulman
## 🔁 Sistem Akışı (Özet)
1. Tedarikçi ürün ekler (fiyat yok)
2. Alıcı ürün talebi oluşturur
3. İlgili tedarikçiler talebi görür
4. Tedarikçiler teklif verir
5. Alıcı bir teklifi seçer
6. Ödeme platformda tutulur
7. Admin onayı sonrası ödeme tedarikçiye aktarılır
8. Komisyon otomatik kesilir
## 💰 Komisyon Modeli
- %5 – %10 arası (admin belirler)
- Sadece başarılı işlemlerden alınır
- Talep iptal edilirse ödeme iade edilir
## 🌍 Dil & Para Birimi
**Dil**
- Türkçe
- İngilizce
**Para Birimi**
- Çoklu para birimi desteği (ülke bazlı)
## 🧩 MVP Kapsamı
### ✅ Var
- Web tabanlı platform
- Talep & teklif sistemi
- Admin kontrollü ödeme akışı
- Rol bazlı yetkilendirme
- Global uyumlu mimari
### ❌ Yok (MVP bilinçli kısıtlar)
- Mobil uygulama
- Chat / mesajlaşma
- Otomatik lojistik
- Tam otomatik escrow
## 🚀 Geliştirme Durumu
Bu repo aktif olarak geliştirilmektedir.
İlk hedef: global vizyona sahip, çalışır bir MVP







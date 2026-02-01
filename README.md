# Vendora – B2B Talep Bazlı Toptan Ticaret Platformu (MVP)
Vendora, farklı ülkelerdeki tedarikçi ve alıcıları;  
**talep bazlı teklif sistemi** ve **platform içi korumalı ödeme modeli**,  
ile bir araya getiren global bir B2B toptan ticaret platformudur.
Bu repo, Vendora’nın **web tabanlı MVP sürümünü** içerir.
## 🎯 Projenin Amacı
- Global alıcı ve tedarikçileri tek bir platformda buluşturmak
- Ürün taleplerini merkezi ve şeffaf şekilde toplamak
- Platform üzerinden **komisyon bazlı gelir modeli** oluşturmak
## 👥 Kullanıcı Tipleri
### 🅰️ Alıcı (Buyer)
- Firma hesabı ile kayıt olur
- Ürün talebi oluşturur
- Gelen teklifleri listeler ve karşılaştırır
- Talep → teklif → ödeme sürecini platform içinde tutmak 
- Bir teklifi seçer
- Ödemeyi platform üzerinden yapar
### 🅱️ Tedarikçi (Supplier – Türkiye)
- Sadece Türkiye merkezli firmalar
- Ürünlerini fiyat belirtmeden listeler
- Gelen talepleri görür
- Talep bazlı teklif verir
### 🅾️ Admin
- Tüm sistemi kontrol eder
- Kullanıcıları onaylar / pasif yapar
- Talep, teklif ve ödemeleri izler
- Komisyon oranlarını belirler
- Ödeme akışını onaylar veya durdurur
> ⚠️ Admin onayı olmadan sistem ilerlemez (MVP güven modeli)
## 🏭 Desteklenen Sektörler (MVP – Sabit)
1. Ambalaj & Sarf
2. Temizlik
3. Gıda (Paketli)
4. Endüstriyel Sarf & İş Güvenliği
5. Rulman
## 🔁 Sistem Akışı (Özet)
1. Tedarikçi ürün ekler (fiyat yok)
2. Alıcı talep oluşturur
3. İlgili tedarikçiler talebi görür
4. Tedarikçiler teklif verir
5. Alıcı bir teklifi seçer
6. Ödeme platformda tutulur
7. Admin onayı sonrası ödeme tedarikçiye aktarılır
8. Komisyon otomatik kesilir
## 💰 Komisyon Modeli
- %5 – %10 arası (admin belirler)
- Sadece başarılı işlemlerden alınır
- Talep iptal edilirse → ödeme iade edilir
## 🌍 Dil & Para Birimi
**Dil**
- Türkçe
- İngilizce
**Para Birimi**
- Türkiye: TRY
- Global: EUR / USD
## 🧩 MVP Kapsamı
### ✅ Var
- Web tabanlı yapı
- Talep & teklif sistemi
- Admin kontrollü ödeme akışı
- Rol bazlı yetkilendirme
- Ölçeklenebilir altyapı
### ❌ Yok (Bilinçli)
- Mobil uygulama
- Chat / mesajlaşma
- Otomatik lojistik
- Global tedarikçi
- Tedarikçi–alıcı doğrudan iletişim
## 🛠️ Teknik Stack (Planlanan)
**Frontend**
- Next.js
- TailwindCSS
**Backend**
- NestJS
- REST API
**Database**
- PostgreSQL
- Prisma ORM
**Auth**
- JWT
- Role-based access control
## 🚀 Geliştirme Durumu
Bu repo aktif olarak geliştirilmektedir.  
İlk hedef: **çalışır, admin kontrollü MVP**.
## 📌 Lisans
Tüm hakları saklıdır.  
Bu repo MVP geliştirme amaçlıdır.

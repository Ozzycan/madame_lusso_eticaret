# Madame Lusso E-Ticaret Platformu

Lüks takı dünyasının en seçkin parçalarını sunan modern e-ticaret platformu.

## 🌟 Özellikler

### 🛍️ Müşteri Özellikleri
- **Ürün Kataloğu**: Kategorilere göre organize edilmiş takı koleksiyonu
- **Gelişmiş Arama**: Ürün adı, açıklama ve SKU'ya göre arama
- **Sepet Yönetimi**: Güvenli alışveriş sepeti
- **Sipariş Takibi**: Gerçek zamanlı sipariş durumu
- **Müşteri Paneli**: Profil yönetimi ve sipariş geçmişi
- **Responsive Tasarım**: Tüm cihazlarda mükemmel görünüm

### 👑 Admin Özellikleri
- **Ürün Yönetimi**: Ürün ekleme, düzenleme, silme
- **Kategori Yönetimi**: Kategori organizasyonu
- **Sipariş Yönetimi**: Sipariş durumu güncelleme ve takip
- **Müşteri Yönetimi**: Müşteri bilgileri ve sipariş geçmişi
- **Stok Takibi**: Gerçek zamanlı stok yönetimi
- **Raporlama**: Satış, müşteri ve ürün raporları
- **Platform Entegrasyonu**: E-ticaret platformları ile senkronizasyon

### 🔐 Güvenlik
- **Rol Tabanlı Erişim**: Admin ve müşteri ayrımı
- **CSRF Koruması**: Güvenli form işlemleri
- **Şifreli Oturum**: Güvenli kullanıcı oturumları
- **Admin Middleware**: Yetkisiz erişim engelleme

## 🛠️ Teknolojiler

- **Backend**: Laravel 11 (PHP 8.2+)
- **Frontend**: Blade Templates, Tailwind CSS
- **Veritabanı**: SQLite (geliştirme), MySQL/PostgreSQL (production)
- **JavaScript**: Vanilla JS, Alpine.js
- **Harita**: OpenStreetMap (Leaflet)
- **İkonlar**: Font Awesome 6

## 📋 Gereksinimler

- PHP 8.2 veya üzeri
- Composer
- Node.js & NPM
- Git

## 🚀 Kurulum

### 1. Repository'yi Klonlayın
```bash
git clone https://github.com/KULLANICI_ADINIZ/madame-lusso-ecommerce.git
cd madame-lusso-ecommerce
```

### 2. Bağımlılıkları Yükleyin
```bash
composer install
npm install
```

### 3. Environment Dosyasını Oluşturun
```bash
cp .env.example .env
php artisan key:generate
```

### 4. Veritabanını Kurun
```bash
php artisan migrate
php artisan db:seed
```

### 5. Storage Linkini Oluşturun
```bash
php artisan storage:link
```

### 6. Asset'leri Derleyin
```bash
npm run build
```

### 7. Sunucuyu Başlatın
```bash
php artisan serve
```

## 🌐 Erişim

- **Ana Sayfa**: `http://localhost:8000`
- **Admin Panel**: `http://localhost:8000/admin`
- **Müşteri Girişi**: `http://localhost:8000/login`
- **Admin Girişi**: `http://localhost:8000/admin/login`

## 👤 Varsayılan Kullanıcılar

### Admin Kullanıcı
- **Email**: admin@madamelusso.com
- **Şifre**: password

### Test Müşteri
- **Email**: customer@madamelusso.com
- **Şifre**: password

## 📁 Proje Yapısı

```
madame-lusso-ecommerce/
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   ├── Middleware/
│   │   └── Requests/
│   ├── Models/
│   └── Services/
├── database/
│   ├── migrations/
│   └── seeders/
├── resources/
│   ├── views/
│   ├── css/
│   └── js/
├── routes/
└── public/
```

## 🔧 Özelleştirme

### Logo Değiştirme
`public/images/logo.svg` dosyasını kendi logonuzla değiştirin.

### Renk Teması
`resources/css/app.css` dosyasında CSS değişkenlerini düzenleyin.

### Ürün Kategorileri
`database/seeders/CategorySeeder.php` dosyasında kategorileri güncelleyin.

## 📱 Responsive Tasarım

- **Mobile First** yaklaşım
- **Tailwind CSS** ile modern tasarım
- **Flexbox** ve **Grid** layout sistemleri
- **Touch-friendly** arayüz

## 🗺️ Harita Entegrasyonu

- **OpenStreetMap** ile ücretsiz harita servisi
- **Leaflet.js** ile interaktif haritalar
- **Konum bazlı** mağaza bilgileri
- **Yol tarifi** ve **uydu görünümü** linkleri

## 📊 Raporlama

- **Satış Raporları**: Günlük, haftalık, aylık
- **Müşteri Analizi**: Demografik bilgiler ve davranış
- **Ürün Performansı**: En çok satan ürünler
- **Stok Analizi**: Stok seviyeleri ve uyarılar

## 🔄 Platform Entegrasyonu

- **Beymen** entegrasyonu
- **WhatsApp** destek sistemi
- **Kargo takip** entegrasyonu
- **Çoklu platform** senkronizasyonu

## 📞 Destek

- **Email**: info@madamelusso.com
- **Telefon**: +90 850 346 5948
- **Adres**: Fethiye, Muğla, Türkiye

## 📄 Lisans

Bu proje özel kullanım için geliştirilmiştir.

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Commit yapın (`git commit -m 'Add some AmazingFeature'`)
4. Branch'i push edin (`git push origin feature/AmazingFeature`)
5. Pull Request oluşturun

## 📈 Gelecek Planları

- [ ] Mobil uygulama
- [ ] Çoklu dil desteği
- [ ] Gelişmiş analitik
- [ ] AI destekli ürün önerileri
- [ ] Sosyal medya entegrasyonu
- [ ] Live chat desteği

---

**Madame Lusso** - Zarafet bir damladır. İnci gibi parlayan siz olun. ✨

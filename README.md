# 📚 Üniversite Kütüphane Sistemi API

Bu proje, OpenAPI 3.0.3 spesifikasyonuna uygun olarak hazırlanmış bir RESTful API tanımıdır. API, bir üniversite kütüphanesi için kitap, öğrenci ve ödünç işlemlerini yönetmek amacıyla tasarlanmıştır.

## 📁 Dosyalar

- `openapi.yaml` → API'nin teknik tanımı
- `README.md` → Proje açıklama dosyası
- `DELIVERY.md` → Teslim dosyası (Google Classroom’a yüklenecek)

## 🔗 Kullanım

YAML dosyasını Swagger Editor (https://editor.swagger.io) üzerinden yükleyerek inceleyebilir ve test edebilirsiniz.

## 🧱 İçerdiği Bileşenler

- **books**: Kitap CRUD işlemleri
- **students**: Öğrenci CRUD işlemleri
- **loans**: Kitap ödünç alma ve iade işlemleri

## 🧪 Özellikler

- OpenAPI 3.0.3 standardına uygundur.
- UUID, email, ISBN-13, date gibi formatlar kullanılmaktadır.
- Sayfalama (`page`, `size`) desteklenmektedir.
- 200, 201, 400, 404, 500 gibi cevaplar tanımlanmıştır.
- `example`, `enum`, `required`, `nullable` gibi gelişmiş özellikler mevcuttur.

## 👤 Geliştirici

- Ad Soyad: Muhammed Emin Solakoğlu
- Öğrenci No: 170422053

# OpenAPI Tasarımı Ödevi Teslim Raporu

## 👤 Öğrenci Bilgileri
- **Ad Soyad**: Muhammed Emin Solakoğlu
- **Öğrenci Numarası**: 170422053

---

## 📂 OpenAPI YAML Dosyası

- OpenAPI dosyası bu repoda `openapi.yaml` olarak yer almaktadır.

### 🔗 GitHub Repo Linki
https://github.com/Eminsolakoglu/OpenAPI-ile-REST-API-Tasar-m-.git
---

## 📝 API Açıklaması

- **Varlıklar**: `books`, `students`, `loans`
- Tüm CRUD işlemleri OpenAPI içinde tanımlanmıştır.
- `components/schemas` içinde veri modelleri yer almaktadır.
- `parameters` ile path ve query parametreleri (örneğin `id`, `page`, `size`) desteklenmektedir.
- `requestBody` kısmında `required`, `enum`, `format` gibi kurallar uygulanmıştır.
- `responses` kısmında 200, 201, 400, 404 ve 500 gibi örnek durumlar tanımlanmıştır.
- `GET /books` endpointi sayfalama (`page`, `size`) desteklemektedir.
- Tüm endpointler açıklayıcı `summary`, `description` ve `tags` içerir.

---

## 🧪 Test Notları (Opsiyonel)

- `GET /books` çağrısı kitapların listesini döner, örnek şema tanımlanmıştır.
- `POST /students` için e-posta ve uuid formatları doğrulanmaktadır.
- Geçersiz veri gönderildiğinde `400` yanıtı ile açıklama döner.

---

## 📌 Ek Açıklamalar

- `PATCH /loans/{id}/return` endpointi ile kitap iade işlemi yapılabilmektedir.
- Swagger Editor üzerinde test edilerek doğrulanmıştır.

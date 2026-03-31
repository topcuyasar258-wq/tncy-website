# TNCY Website — Kurulum Rehberi

## Admin Paneline Giriş

1. Netlify'da **Identity** servisini aktif et:
   - Site ayarları → Identity → Enable Identity
   - Registration → Invite only seç
   - Git Gateway → Enable Git Gateway

2. Kendini davet et:
   - Identity sekmesi → Invite users → kendi e-postanı gir

3. E-postana gelen linke tıkla, şifre belirle.

4. `tncys.com/admin` adresine git → giriş yap.

## Ürün Eklemek

- Admin panelde **Ürünler** → **Yeni Ürün**
- Fotoğrafı yükle, fiyatı gir, kaydet
- Otomatik siteye yansır

## config.yml Ayarı

`admin/config.yml` dosyasında şu satırı kendi GitHub kullanıcı adınla değiştir:

```
repo: GITHUB_KULLANICI_ADIN/tncy-website
```

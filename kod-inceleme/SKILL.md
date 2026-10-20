---
name: kod-inceleme
description: Değişen kodu hata ve güvenlik açısından inceler. Kullanıcı "kodu incele", "review yap", "yayınlamadan önce kontrol et" dediğinde ya da bir pull request hazırlanırken kullan.
---

# Kod inceleme

Sadece değişen satırlara odaklan (`git diff`). Aşağıdakileri kontrol et:

- Koda gömülü şifre, API anahtarı ya da token
- Kullanıcı girdisinin doğrulanmadan kullanılması (SQL sorgusu, HTML, terminal komutu)
- Hatası yakalanmayan ağ ve dosya işlemleri
- Yeni eklenen paketler: paket adının gerçekten var olduğunu ve doğru kaynaktan geldiğini doğrula (uydurma paket riski)
- Kullanılmayan kod ve gereksiz tekrarlar

Her bulguyu `dosya:satır` ile birlikte, önem sırasına göre yaz:

- **Kritik:** yayından önce mutlaka düzeltilmeli
- **Önemli:** yakında düzeltilmeli
- **Öneri:** kodu iyileştirir

Hiç sorun bulamazsan bunu açıkça söyle. Kodu kendin değiştirme, önce raporla ve onay bekle.

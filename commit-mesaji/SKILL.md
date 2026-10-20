---
name: commit-mesaji
description: Git'teki değişikliklerden kısa ve anlaşılır bir commit mesajı yazar. Kullanıcı "commit mesajı yaz", "commit at" ya da "ne değişti?" dediğinde kullan.
---

# Commit mesajı

1. `git diff --staged` ile commit'e hazırlanmış değişiklikleri incele. Çıktı boşsa `git diff` kullan ve kullanıcıya henüz hiçbir dosyanın stage edilmediğini söyle.
2. Mesajı Conventional Commits biçiminde yaz: `tür(kapsam): özet`
   - Türler: feat, fix, refactor, docs, test, chore
3. Özet satırı en fazla 72 karakter olsun ve emir kipiyle yazılsın ("ekle", "düzelt", "kaldır").
4. Gerekirse altına 2–4 maddelik bir açıklama ekle: ne değişti ve neden.
5. Commit'i kendin atma. Mesajı göster ve kullanıcıdan onay iste.

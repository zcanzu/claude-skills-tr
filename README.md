# DevCan Hazır Skill Paketi

Claude için kullanıma hazır 3 skill ve kendi skill'ini yazman için boş bir şablon.

| Klasör | Ne yapar? |
|---|---|
| `commit-mesaji` | Değişikliklerinden düzgün bir commit mesajı yazar |
| `kod-inceleme` | Değişen kodu hata ve güvenlik açısından inceler |
| `app-store-metni` | App Store adı, alt başlık, anahtar kelime ve açıklama yazar |
| `sablon` | Kendi skill'in için boş şablon |

## Kurulum

### Claude Code
Klasörleri şuraya kopyala:

- Tüm projelerinde kullanmak için: `~/.claude/skills/`
- Sadece bir projede kullanmak için: projendeki `.claude/skills/`

Sonra Claude Code'u yeniden başlat. Skill'ler ihtiyaç olunca kendiliğinden devreye girer. İstersen adını yazarak kendin de çağırabilirsin: `/commit-mesaji`

### Claude.ai
Her skill klasörünü ayrı ayrı zip'le ve Ayarlar'daki Skills bölümünden yükle. (Pro, Max, Team ve Enterprise planlarında, kod çalıştırma özelliği açıkken çalışır.)

## Güvenlik
Skill'ler Claude'a talimat verir ve kod çalıştırabilir. Bu paket dahil, kurmadan önce her dosyayı oku. Sadece güvendiğin kaynaklardan skill kur.

---
Daha fazlası için: Instagram **@devcan.dev** · devcan.dev

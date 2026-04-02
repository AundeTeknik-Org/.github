# AundeTeknik - Repository Standartları

## Yeni Repo Oluşturma Kuralları

1. İsimlendirme formatına uy: `şirket-platform-dil-projeadi` veya grup varsa `şirket-platform-dil-grup-projeadi`
2. Visibility: **Private** (aksi belirtilmedikçe)
3. **ZORUNLU:** Template olarak `template-default` seçilerek oluşturulmalı
4. **README.md** dosyasına proje açıklamasını yaz
5. Repo → **Settings** → **Collaborators and teams** → **Add teams**:
   - `Developer` ekle → **Write** yetkisi ver
   - `Viewer` ekle → **Read** yetkisi ver

## Repo İsimlendirme Kuralı

**Format:** `şirket-platform-dil-projeadı`
**Grup varsa:** `şirket-platform-dil-grup-projeadı`

**Örnek:** `sb-desktop-cs-DetayDikimKilit`, `dm-api-ts-StokServis`, `sb-desktop-cs-Dikim-Kilit`

## Kısaltma Tabloları

<table>
<tr>
<td valign="top">

### Şirket / Lokasyon

| Kısaltma | Anlamı |
|----------|--------|
| `org` | Organizasyon geneli |
| `sb` | Serbest Bölge |
| `km` | Kumaş |
| `is` | İsri Demirtaş |
| `dm` | Aunde Üst Yapı |
| `ro` | Romanya Aunde |
| `hu` | Macaristan Aunde |
| `de` | Almanya Aunde |

</td>
<td valign="top">

### Platform

| Kısaltma | Anlamı |
|----------|--------|
| `desktop` | Masaüstü |
| `svc` | Service |
| `web` | Web uygulaması |
| `api` | API |
| `wince` | Windows CE / El terminali |
| `mobile` | Mobil |
| `iot` | IoT / Embedded |
| `console` | Konsol uygulaması |
| `lib` | Ortak kütüphane / Class Library |
| `db` | Veritabanı projesi |
| `test` | Test projesi |
| `docs` | Döküman / Şablon / Kaynak |

</td>
<td valign="top">

### Dil

| Kısaltma | Anlamı |
|----------|--------|
| `cs` | C# |
| `vb` | Visual Basic |
| `py` | Python |
| `java` | Java |
| `swift` | Swift |
| `c` | C |
| `php` | PHP |
| `sql` | SQL |
| `xamarin` | Xamarin |
| `maui` | .NET MAUI |

</td>
</tr>
</table>

## Takım Yapısı

| Takım | Yetki | Açıklama |
|-------|-------|----------|
| **Developer** | Write | Kod yazma, push, PR oluşturma |
| **Viewer** | Read | Sadece okuma |

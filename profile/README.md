# AundeTeknik - Repository Standartları

## Yeni Repo Oluşturma Kuralları

1. İsimlendirme formatına uy: `şirket-platform-dil-projeadi`
2. Visibility: **Private** (aksi belirtilmedikçe)
3. **ZORUNLU:** Template olarak `template-default` seçilerek oluşturulmalı
4. **README.md** dosyasına proje açıklamasını yaz
5. Repo → **Settings** → **Collaborators and teams** → **Add teams**:
   - `Developer` ekle → **Write** yetkisi ver
   - `Viewer` ekle → **Read** yetkisi ver

## Repo İsimlendirme Kuralı

**Format:** `şirket-platform-dil-projeadı`

**Örnek:** `sb-desktop-cs-DetayDikimKilit`, `dm-api-ts-StokServis`

## Kısaltma Tabloları

<table>
<tr>
<td valign="top">

### Şirket / Lokasyon

| Kısaltma | Anlamı |
|----------|--------|
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
| `desktop` | Masaüstü (WinForms, WPF, MAUI vb.) |
| `winsvc` | Windows Service |
| `web` | Web uygulaması |
| `api` | API |
| `blazor` | Blazor uygulaması |
| `wince` | Windows CE / El terminali |
| `mobile` | Mobil (Xamarin, MAUI vb.) |
| `iot` | IoT / Embedded |
| `console` | Konsol uygulaması |
| `lib` | Ortak kütüphane / Class Library |
| `db` | Veritabanı projesi (SSDT vb.) |
| `test` | Test projesi |
| `docs` | Döküman / Şablon / Kaynak |

</td>
<td valign="top">

### Dil

| Kısaltma | Anlamı |
|----------|--------|
| `cs` | C# |
| `vb` | Visual Basic |
| `js` | JavaScript |
| `ts` | TypeScript |
| `py` | Python |
| `java` | Java |
| `kt` | Kotlin |
| `swift` | Swift |
| `go` | Go |
| `rs` | Rust |
| `cpp` | C++ |
| `c` | C |
| `php` | PHP |
| `rb` | Ruby |
| `dart` | Dart (Flutter) |
| `sql` | SQL |

</td>
</tr>
</table>

## Takım Yapısı

| Takım | Yetki | Açıklama |
|-------|-------|----------|
| **Developer** | Write | Kod yazma, push, PR oluşturma |
| **Viewer** | Read | Sadece okuma |

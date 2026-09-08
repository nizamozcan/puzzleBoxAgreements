# Puzzle Box — destek ve gizlilik sayfaları

App Store ve Google Play'in zorunlu tuttuğu iki sayfa. Uygulamanın kaynak kodu
ayrı ve private bir depoda; burada yalnızca statik HTML var, böylece GitHub
Pages ücretsiz planda çalışabiliyor.

| Dosya | Kullanım |
|---|---|
| `index.html` | Support URL — iletişim ve sık sorulanlar |
| `privacy.html` | Privacy Policy URL |

İkisi de Türkçe ve İngilizce.

## Yayınlamak

Settings → Pages → Source: **Deploy from a branch** → Branch **main**, klasör **/ (root)**.

```
https://nizamozcan.github.io/puzzleBoxAgreements/
https://nizamozcan.github.io/puzzleBoxAgreements/privacy.html
```

`.nojekyll` bilerek duruyor: Jekyll alt çizgiyle başlayan dosyaları yok sayar.

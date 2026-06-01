# Epidemiyologlar İçin GitHub Rehberi

[![Site](https://img.shields.io/badge/site-canl%C4%B1-success)](https://drmuammer.github.io/githubRehber/)
[![Quarto](https://img.shields.io/badge/Quarto-published-75AADB?logo=quarto)](https://quarto.org)
[![Lisans](https://img.shields.io/badge/lisans-MIT-blue)](LICENSE)

Kod yazan ama GitHub kullanmamış sağlık ve epidemiyoloji araştırmacıları için hazırlanmış, sıfırdan uygulamalı bir GitHub rehberi. Amaç GitHub'ı bir yazılımcı gibi değil, bir araştırmacı gibi kullanmak: analiz kodunu güvende tutmak, sürümlerini takip etmek, ekiple çalışmak ve sonuçları yayınlamak.

## 🌐 Canlı site

Rehberin tamamı şu adreste yayında:

**<https://drmuammer.github.io/githubRehber/>**

## İçindekiler

Rehber her iş için iki yol gösterir — 🟢 **kolay yol** (tarayıcı + GitHub Desktop, kod yazmadan) ve 🔵 **ileri yol** (terminal / Git komutları):

- Git ve GitHub farkı, neden araştırma için önemli olduğu
- Hesap oluşturma ve temel sözlük
- Web arayüzü, GitHub Desktop ve terminal ile çalışma
- README süsleme (Markdown, rozetler, tablolar)
- Issue açma ve fork → pull request ile katkı
- GitHub Pages + Quarto ile web sitesi yayınlama
- Repo yönetimi: işbirlikçi, dal koruma, release/DOI, lisans
- Sık karşılaşılan sorunlar (SSS)

## Bu depoda ne var

| Dosya | Açıklama |
|-------|----------|
| `index.qmd` | Rehberin Quarto kaynak dosyası |
| `styles.css` | Site için sade özelleştirmeler |
| `LICENSE` | MIT lisansı |

## Yerelde derleme

[Quarto](https://quarto.org/docs/get-started/) kurulu olmalı. Repoyu klonladıktan sonra:

```bash
# Yerelde önizleme
quarto preview

# Tek seferlik render
quarto render

# GitHub Pages'e yayınlama
quarto publish gh-pages
```

## Katkı

Bir eksik veya hata görürsen bir [issue](https://github.com/drmuammer/githubRehber/issues) aç ya da bir pull request gönder. Rehber sürekli geliştirilebilir.

## Lisans

Bu çalışma [MIT Lisansı](LICENSE) ile sunulmaktadır. Atıfla birlikte serbestçe kullanabilir, değiştirebilir ve dağıtabilirsiniz.

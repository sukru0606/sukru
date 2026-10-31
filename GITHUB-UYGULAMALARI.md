# İşime Yarayacak GitHub Uygulamaları

Fen Bilimleri / LGS soru yazımı, fasikül ve deneme hazırlama, PDF çapraz okuma,
bağlam (kaynak) tarama ve "Müfredatın Sınırları" sosyal medya serisi için seçildi.

> Tarama tarihi: 31 Ekim 2026. Yıldız sayıları ve "son güncelleme" GitHub'dan alındı.
> Bilgisayara kurulum gerektirenler ⚙️, tarayıcıdan / tek tıkla kullanılabilenler 🌐 ile işaretli.

---

## 1. En çok işime yarayacak 5 araç (önce bunlara bak)

| # | Uygulama | Ne işe yarar | Neden benim için |
|---|----------|--------------|------------------|
| 1 | [Stirling-Tools/Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) 🌐⚙️ | PDF birleştir, böl, sayfa sırala, filigran, sıkıştır, OCR, imzala | Fasikül/deneme PDF'lerinin tüm baskı öncesi işleri tek yerden. ~95 bin ★, aktif |
| 2 | [vslavik/diff-pdf](https://github.com/vslavik/diff-pdf) ⚙️ | İki PDF'yi görsel olarak karşılaştırır, farkları kırmızıyla gösterir | Çapraz okumada "dizgici düzeltmeyi yaptı mı?" kontrolü için birebir |
| 3 | [ocrmypdf/OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) ⚙️ | Taranmış PDF'ye aranabilir metin katmanı ekler (Türkçe destekli: `-l tur`) | Eski taranmış kitaplardan, çıkmış sorulardan metin çekmek için |
| 4 | [blader/humanizer](https://github.com/blader/humanizer) ⚙️ | Claude için "yapay zekâ yazmış gibi okunmayı" temizleyen skill | "İnsan kalemi" kurallarımla aynı amaç; fikir/kural kaynağı olarak kullanılabilir |
| 5 | [excalidraw/excalidraw](https://github.com/excalidraw/excalidraw) 🌐 | El çizimi görünümlü şema/diyagram aracı ([excalidraw.com](https://excalidraw.com)) | Soru görselleri, deney düzenekleri, gönderi çizimleri; kurulum yok |

---

## 2. PDF ve doküman işleri (fasikül, deneme, çapraz okuma)

| Uygulama | Ne işe yarar | Not |
|----------|--------------|-----|
| [datalab-to/marker](https://github.com/datalab-to/marker) ⚙️ | PDF'yi Markdown/JSON'a çevirir; tablo, formül, görsel korunur | Yayınevi PDF'lerini Claude'a temiz metin olarak vermek için |
| [opendatalab/MinerU](https://github.com/opendatalab/MinerU) ⚙️ | Karmaşık sayfa düzenli PDF'leri (çok sütunlu, görselli) metne çevirir | Fasikül gibi karışık düzenlerde marker'a alternatif |
| [docling-project/docling](https://github.com/docling-project/docling) ⚙️ | PDF, Word, PowerPoint → yapay zekâya hazır metin (IBM) | MIT lisanslı, çok aktif |
| [ssibb/PDF-Diff-Viewer](https://github.com/ssibb/PDF-Diff-Viewer) ⚙️ | Yan yana, senkron kaydırmalı PDF karşılaştırma | diff-pdf'nin daha görsel alternatifi |
| [breezedeus/Pix2Text](https://github.com/breezedeus/Pix2Text) ⚙️ | Görselden metin + formül (LaTeX) + tablo okur | Mathpix'in ücretsiz alternatifi; formüllü fen soruları için |
| [jgm/pandoc](https://github.com/jgm/pandoc) ⚙️ | Markdown ↔ Word ↔ PDF ↔ HTML dönüştürücü | Soru dosyalarını farklı formatlara aktarmak için |

## 3. Soru ve sınav hazırlama

| Uygulama | Ne işe yarar | Not |
|----------|--------------|-----|
| [MatheSchool/typst-g-exam](https://github.com/MatheSchool/typst-g-exam) ⚙️ | Typst ile sınav şablonu (puan, cevap anahtarı otomatik) | Word'e alternatif, temiz dizgi |
| [Abdulhadialayoub/lgs-soru-generasyonu](https://github.com/Abdulhadialayoub/lgs-soru-generasyonu) ⚙️ | Yapay zekâ ile LGS soru üretimi denemesi | Küçük proje; fikir için incelenebilir |
| [AbdullahEmirOner/SoruMind](https://github.com/AbdullahEmirOner/SoruMind) | LGS soru sınıflandırma ve zorluk analizi platformu | Soru zorluğu etiketleme fikri için |
| [huseyintemizkan-jpg/maarif-fen](https://github.com/huseyintemizkan-jpg/maarif-fen) | Maarif Modeli fen soru bankası (9-10. sınıf) | Lise düzeyi ama Maarif Modeli formatı açısından bakılabilir |
| [hasanesenn/tymm-ders-etkinlik-tasarimcisi](https://github.com/hasanesenn/tymm-ders-etkinlik-tasarimcisi) | TYMM kazanımlarına göre ders/etkinlik tasarlayıcı | Müfredat (öğrenme çıktısı) eşleme fikri için |

> Türkçe LGS/Maarif projeleri küçük, az yıldızlı ve lisanssız olabilir; **kod veya soru kopyalamadan önce
> lisansa bak**, telif riskine karşı yalnızca fikir kaynağı olarak kullan.

## 4. Görsel, şema, simülasyon (soru görselleri ve ders)

| Uygulama | Ne işe yarar | Not |
|----------|--------------|-----|
| [excalidraw/excalidraw-mcp](https://github.com/excalidraw/excalidraw-mcp) ⚙️ | Claude'un doğrudan Excalidraw çizimi üretmesini sağlar | Soru görseli tarifini çizime dönüştürmek için |
| [janosh/diagrams](https://github.com/janosh/diagrams) 🌐 | Yüzlerce hazır fizik/kimya kavram diyagramı (kaynak kodlu) | Görsel fikri ve şablon olarak; MIT lisanslı |
| [mermaid-js/mermaid](https://github.com/mermaid-js/mermaid) 🌐 | Yazıdan akış şeması/kavram haritası çizer | Ünite kavram haritaları için |
| [openzim/phet](https://github.com/openzim/phet) ⚙️ | PhET simülasyonlarını **internetsiz** kullanılacak şekilde indirir | İnternetin zayıf olduğu sınıflar için |
| [ManimCommunity/manim](https://github.com/ManimCommunity/manim) ⚙️ | Animasyonlu bilim/matematik videoları (3Blue1Brown tarzı) | Sosyal medya için kısa anlatım videoları |
| [geogebra/geogebra](https://github.com/geogebra/geogebra) 🌐 | Grafik, geometri, deney verisi grafiği | [geogebra.org](https://www.geogebra.org) üzerinden kurulumsuz |

## 5. Sosyal medya ve sunum ("Müfredatın Sınırları" serisi)

| Uygulama | Ne işe yarar | Not |
|----------|--------------|-----|
| [dean9703111/ig-card-generator](https://github.com/dean9703111/ig-card-generator) ⚙️ | Metni Instagram kaydırmalı (carousel) 1080×1350 görsellere çevirir (Claude skill) | Seri gönderilerini şablonlaştırmak için; MIT |
| [marp-team/marp-cli](https://github.com/marp-team/marp-cli) ⚙️ | Markdown'dan slayt/PDF/PNG üretir | Gönderi kartı ve ders sunumu için hızlı yol |

## 6. Claude'u güçlendiren skill ve eklenti listeleri

| Uygulama | Ne işe yarar |
|----------|--------------|
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Anthropic'in resmî Claude eklenti dizini |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Topluluğun derlediği Claude skill listesi (doküman, PDF, tasarım vb.) |

## 7. Öğrenci tarafı (tekrar ve çeviri)

| Uygulama | Ne işe yarar |
|----------|--------------|
| [ankitects/anki](https://github.com/ankitects/anki) 🌐 | Aralıklı tekrar kartları; kavram/terim ezberi için öğrencilere önerilebilir |
| [PDFMathTranslate/PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) ⚙️ | İngilizce bilimsel PDF'leri düzeni bozmadan Türkçeye çevirir — yabancı kaynaktan bağlam bulurken işe yarar |

---

## Önerilen başlangıç sırası

1. **Bugün, kurulumsuz:** excalidraw.com ve geogebra.org'u dene.
2. **Bu hafta:** Stirling-PDF (Docker ile tek komut) + diff-pdf → çapraz okuma iş akışına ekle.
3. **Sonra:** marker veya MinerU ile eski PDF arşivini metne çevir; bağlam arşivini zenginleştir.
4. **İstersen:** Bu araçlardan birini Claude skill'lerine (soru-yaz, çapraz okuma) bağlamak için birlikte çalışabiliriz.

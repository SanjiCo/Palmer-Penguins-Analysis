# Palmer Penguins Size Analysis

Bu proje, Palmer Penguins veri setini kullanarak penguen türleri (Adélie, Chinstrap, Gentoo) ve cinsiyetler arasındaki beden ölçü farklarını analiz eder. R programlama diliyle hazırlanmış ve Google Data Analytics Certificate kapsamında bir uygulamadır. Veri temizleme, istatistiksel analiz ve görselleştirme teknikleri kullanılarak penguenlerin bill length, flipper length ve body mass ölçümleri incelenmiştir.

## İçerik
- **Veri Keşfi ve Temizleme:** Eksik verilerin kaldırılması ve analiz için gerekli sütunların seçilmesi (`dplyr`).
- **İstatistiksel Analiz:** Tür ve cinsiyete göre ortalama ölçülerin hesaplanması ve t-testlerle anlamlılık testi.
- **Görselleştirme:** Tür ve cinsiyet farklarını gösteren grafikler (`ggplot2` ile scatter plot, box plot ve facet plot).

## Raporu Görüntüle
Analizin tam raporuna aşağıdaki linkten ulaşabilirsiniz:  
[**Palmer Penguins Size Analysis Raporu**](https://sanjico.github.io/Palmer-Penguins-Analysis/)

## Kullanılan Veri Seti
- **Palmer Penguins:** Horst AM, Hill AP, Gorman KB (2020). *palmerpenguins: Palmer Archipelago (Antarctica) penguin data*. R paketi, versiyon 0.1.0.  
  Daha fazla bilgi için: [palmerpenguins R paketi](https://allisonhorst.github.io/palmerpenguins/).

## Gereksinimler
Raporu yerel olarak çalıştırmak veya `.Rmd` dosyasını knit etmek isterseniz aşağıdaki R paketlerine ihtiyacınız olacak:
- `palmerpenguins`
- `dplyr`
- `ggplot2`
- `stats` (standart R paketi, genellikle zaten yüklüdür)

## Kurulum ve Çalıştırma
1. Gerekli paketleri R’da yükleyin:
   ```R
   install.packages(c("palmerpenguins", "dplyr", "ggplot2"))
   ```
2. Repository’den `Palmer_Penguins_Analysis.Rmd` dosyasını indirin.
3. RStudio’da dosyayı açın ve “Knit” butonuna tıklayarak HTML çıktısını oluşturun.

## Dosya Yapısı
- `Palmer_Penguins_Analysis.html`: Tam analiz raporu (GitHub Pages’de barındırılıyor).
- `Palmer_Penguins_Analysis.Rmd`: R Markdown kaynak dosyası (kod ve açıklamalar).
- `README.md`: Bu dosya.

## Tarih
Mart 2025

## Yazar
İsmail Çakıl  
GitHub: [sanjico](https://github.com/sanjico)

## Lisans
Bu proje [MIT Lisansı](LICENSE) altında paylaşılmıştır. Detaylar için `LICENSE` dosyasına bakabilirsiniz.

## Teşekkür
Bu çalışma, Google Data Analytics Certificate programı kapsamında geliştirilmiştir. Veri setini sağlayan Allison Horst ve ekibine teşekkürler!

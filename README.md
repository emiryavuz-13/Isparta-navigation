
# Köyler Arası Ağ Analizi Projesi

Bu proje, köyler arası mesafeleri temsil eden bir grafın analizi ve görselleştirilmesini gerçekleştirmektedir. Veriler bir CSV dosyasında tutulmakta ve NetworkX kütüphanesi ile işlenmektedir. Çalışma, Colab ortamında yürütülmek üzere tasarlanmıştır.

## Özellikler

- **Graf Yapısı Oluşturma**: Köyler arası mesafelerle bir ağ grafı oluşturulur.
- **Görselleştirme**: Grafın bağlantı bileşenleri görselleştirilir.
- **Topluluk Algılama**: Modülarite optimizasyonu ile topluluklar tespit edilir.
- **Kısa Yol Analizi**: İki köy arasındaki en kısa yol hesaplanır.
- **Merkeziyet Analizleri**:
  - Derece merkeziyeti
  - Yakınlık merkeziyeti
  - Ortadalık merkeziyeti
  - Özvektör merkeziyeti
- **Grafın Temel Özellikleri**:
  - Toplam düğüm sayısı
  - Toplam kenar sayısı
  - Ortalama düğüm derecesi

## Gereksinimler

- Python 3.7+
- Aşağıdaki Python kütüphanelerinin yüklü olması gerekir:
  - pandas
  - networkx
  - matplotlib
  - google.colab (Colab ortamı için)

## Kurulum

1. Google Colab'de yeni bir notebook oluşturun.
2. Bu projedeki Python kodunu notebook'un hücrelerine kopyalayın.
3. `edgesIsparta.csv` dosyasını yükleyerek analizleri başlatabilirsiniz.

## Kullanım

1. Proje kodunu çalıştırmadan önce, köyler arasındaki mesafeleri içeren `edgesIsparta.csv` dosyasını yükleyin.
2. Kod, graf yapısını oluşturup analizleri gerçekleştirecek ve sonuçları ekranda gösterecektir.

### Örnek CSV Dosyası Formatı

```
Köy1;Köy2;Mesafe
KöyA;KöyB;5
KöyB;KöyC;7
KöyA;KöyC;10
```

## Çıktılar

- **Graf Görselleştirmesi**: Köyler arasındaki bağlantılar bir ağ grafiği ile görselleştirilir.
- **Topluluklar**: Köylerin topluluklara ayrılmış hali konsolda listelenir.
- **Kısa Yol Analizleri**: İki köy arasındaki en kısa yol ve tüm kısa yolların uzunlukları hesaplanır.
- **Merkeziyet Analizleri**: Köylerin merkeziyet ölçütlerine göre sıralanmış listeleri konsolda görüntülenir.

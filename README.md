🏥 Windkessel Model & VAD Impact Analysis

Bu proje, kardiyovasküler sistemdeki arteriyel kan basıncı ve akışını modellemek için Üç Elemanlı Windkessel Modeli'ni kullanır. Çalışma, kalp yetmezliği senaryolarını simüle etmek ve Ventriküler Destek Cihazlarının (VAD) hemodinamik parametreler üzerindeki tedavi edici etkilerini değerlendirmek amacıyla geliştirilmiştir.

📋 Proje İçeriği

Bu Jupyter Notebook, teorik modellemeden istatistiksel analize kadar uzanan kapsamlı bir akış sunar:

Matematiksel Modelleme: Arteriyel hemodinamikleri tanımlayan diferansiyel denklemler.

Pompa Modelleri: Fizyolojik kalp atışı (Pump) ve mekanik destek (VADPump) sınıfları.

Nümerik Çözücüler: Euler ve Runge-Kutta 4 (RK4) yöntemleri ile sistem çözümü.

Fizyolojik Metrikler: MAP (Ortalama Arteriyel Basınç), Sistolik/Diyastolik basınç ve Atım Hacmi hesaplamaları.

Duyarlılık Analizi: SV ve HR gibi parametrelerin sistem üzerindeki etkilerinin incelenmesi.

🚀 Teknik Mimari ve Analizler

1. Simülasyon Senaryoları
2. 
Model üç ana durum üzerinde karşılaştırmalı analiz yapar:

Normal Fizyoloji: Sağlıklı bir bireyin basınç ve akış dinamikleri.

Kalp Yetmezliği (HF): Düşük debi ve bozulmuş basınç eğrileri.

VAD Destekli HF: Mekanik desteğin hemodinamik stabilizasyon üzerindeki etkisi.

2. Görselleştirme ve Doğrulama
3. 
Proje, verileri anlamlandırmak için şu grafikleri üretir:

📈 Basınç Dalga Formları: Farklı senaryoların zaman serisi karşılaştırması.

📉 Nümerik Hata Analizi: Euler vs RK4 yöntemlerinin doğruluk kıyası.

📊 Parametrik Etki: Değişkenlerin (HR, SV) model çıktılarına etkisi.

🛠️ Kurulum ve Kullanım
Gereksinimler
Not defteri standart veri bilimi kütüphanelerini kullanır:

numpy

matplotlib

Pillow (Görsel işleme için)

Çalıştırma
# Notebook'u Google Colab veya Jupyter üzerinden açın
# Tüm hücreleri sırayla (Run All) çalıştırın.

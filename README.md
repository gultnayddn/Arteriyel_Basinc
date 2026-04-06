Windkessel Model ve VAD Etki Analizi
Bu not defteri, kardiyovasküler sistemdeki arteriyel kan basıncı ve akışını modellemek için üç elemanlı Windkessel modelini (WindkesselModel sınıfı) kullanır. Kalp yetmezliği senaryolarını simüle eder ve Ventriküler Destek Cihazlarının (VAD) tedavi edici etkilerini değerlendirir.

Not Defterinin İçeriği
Windkessel Modeli Tanımı: Arteriyel hemodinamikleri modelleyen temel matematiksel çerçeve.
Kalp Pompası ve VAD Modelleri: Fizyolojik kalp atışını (Pump) ve VAD desteğini (VADPump) simüle eden sınıflar.
Çözücü Sınıfı ve Metrikler: Windkessel modelinin diferansiyel denklemlerini nümerik olarak çözen (Solver) ve sistolik/diyastolik basınç, Ortalama Arteriyel Basınç (MAP) gibi fizyolojik metrikleri hesaplayan fonksiyonlar.
Ana Simülasyon Betiği ve Analiz: Normal, kalp yetmezliği ve VAD destekli kalp yetmezliği senaryolarını çalıştıran, sonuçları analiz eden ve karşılaştıran ana bölüm.
Basınç Dalga Formları Karşılaştırması Grafiği: Simülasyon sonuçlarının görselleştirilmesi.
Euler-RK4 Nümerik Hata Grafiği: Kullanılan nümerik yöntemler arasındaki hata karşılaştırması.
Referans Aort Basınç Dalga Formu ile Karşılaştırma: Simüle edilmiş dalga formlarının fizyolojik referanslarla doğrulanması.
Parametrik Duyarlılık Analizi: Atım Hacmi (SV) ve Kalp Atım Hızı (HR) gibi parametrelerin model çıktıları üzerindeki etkisinin incelenmesi.
Sentetik Popülasyon Üzerinde VAD Etki Analizi: VAD'nin çeşitli fizyolojik profillere sahip bir popülasyon üzerindeki etkisinin istatistiksel değerlendirmesi.
Kurulum
Bu not defteri temel Python kütüphaneleri olan numpy, matplotlib ve Pillow kullanır. Google Colab ortamında bu kütüphaneler genellikle önceden yüklü gelir.

Kullanım
Not defterini yukarıdan aşağıya doğru sırayla çalıştırmanız önerilir. Her bölüm, ilgili modelleri tanımlar, simülasyonları gerçekleştirir, sonuçları analiz eder ve görselleştirir.

Temel Sonuçlar
Windkessel modeli, farklı fizyolojik durumlar altında arteriyel basınç dinamiklerini başarıyla simüle eder.
VAD desteği, kalp yetmezliği durumunda MAP ve diğer hemodinamik parametreleri normale yaklaştırarak iyileşme sağlar.
Nümerik çözücüler (Euler ve RK4) arasındaki hata analizleri, modelin doğruluğu hakkında bilgi verir.
Parametrik duyarlılık analizleri, modelin fizyolojik değişimlere nasıl tepki verdiğini gösterir.
Bu proje, kardiyovasküler hastalıkların modellenmesi ve tedavi stratejilerinin değerlendirilmesi için basit ama güçlü bir araç sunmaktadır.

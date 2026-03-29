A.F.E.T. : Afet Yönetimi ve Operasyonel Komuta Terminali
📌 Proje Özeti
A.F.E.T. (Advanced Framework for Emergency Tracking), afet sonrası kritik dakikalarda karar vericilere (operasyonel komuta merkezleri) yüksek doğruluklu görsel veri sunmak amacıyla geliştirilmiş bir Karar Destek Sistemidir (DSS). İstanbul odaklı Marmara Bölgesi için optimize edilen bu terminal; lojistik hat analizi, enkaz bölgeleme ve güvenli alan koordinasyonu özelliklerini tek bir düşük gecikmeli arayüzde birleştirir.

🛠 Teknik Mimari ve Teknolojiler
Proje, kritik durumlarda donanım kaynaklarını minimum düzeyde kullanarak maksimum performansı hedefleyen bir Thin-Client mimarisi üzerine kurulmuştur.

Harita Motoru: Leaflet.js (Hafif ve genişletilebilir yapısı nedeniyle tercih edilmiştir).

Coğrafi Veri Katmanı: ArcGIS World Imagery (Gerçek zamanlı uydu verisi entegrasyonu).

Veri Görselleştirme: Dinamik poligon ve polyline algoritmaları ile zonlama (Zoning) ve rota planlama.

Arayüz (UI/UX): * Karanlık Mod: Göz yorgunluğunu minimize eden ve enerji tasarrufu sağlayan düşük fotonlu renk paleti.

Tipografi: Operasyonel okunabilirliği yüksek Orbitron ve Rajdhani font sistemleri.

🛡 Temel Fonksiyonel Özellikler
1. Senkronize Çift Panel Sistemi
Sol panelde Bölgesel Hasar Analizi katmanı, sağ panelde ise Operasyonel Rota ve Lojistik katmanı yer alır. Panellerden birinde yapılan hareket (kaydırma/zoom), diğer panele anlık olarak aktarılır. Bu durum, hasar ve müdahale hattı arasındaki korelasyonu hızlandırır.

2. Akıllı Lojistik Katmanları
Ana İkmall Hatları (Blue Route): Ağır vasıta ve yardım tırları için belirlenmiş yüksek kapasiteli yollar.

Acil Müdahale Hatları (Green Route): Sadece ambulans ve kurtarma ekiplerine özel, dar ama optimize edilmiş geçiş rotaları.

3. Kritik Bölge Analizi (Zonlama)
Kırmızı Bölge (Critical Zone): Enkaz yoğunluğu ve ikincil afet riski (yangın, gaz sızıntısı) taşıyan yüksek riskli poligonlar.

Yeşil Bölge (Safe Zone): Coğrafi olarak güvenli, altyapısı sağlam ve toplanmaya uygun alanlar.

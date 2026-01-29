# Projenin Amacı
Bu proje, öğrencilerin final notlarının çeşitli değişkenlerle ne kadar ilişkili olduğunu gösterir.
- Aile eğitim düzeyi öğrencilerin notlarını etkiler mi?
- Romantik ilişkisi olan öğrencilerin final notlarında düşüş olmuş mudur?
- Alkol tüketimi fazla olan öğrencilerin final notları nasıldır?
- İki farklı okuldan hangi okula giden öprencilerin final notları daha yüksektir?

Gibi soruların cevaplarını, çeşitli analiz yöntemleri, grafikler vs. kullanarak açıkladığım bir projedir.

# Projede Kullanılan Yöntemler
- Tek değişkenli analiz
- İki değişkenli analiz
- Çok değişkenli analiz
- Veri görselleştirme
- Tanımlayıcı istatistikler
# Veri İçeriklerinin Açıklamaları
school – Öğrencinin okulu

sex – Öğrencinin cinsiyeti

- F → Kadın
- M → Erkek

age – Öğrencinin yaşı (sayısal: 15–22 arası)

address – Öğrencinin ev adresi türü

- U → Kentsel (urban)
- R → Kırsal (rural)

famsize – Aile büyüklüğü

- LE3 → 3 veya daha az kişi
- GT3 → 3’ten fazla kişi

Pstatus – Ebeveynlerin birlikte yaşama durumu

- T → Birlikte yaşıyor
- A → Ayrı yaşıyor

Medu – Annenin eğitim düzeyi

0 → Eğitim yok

1 → İlkokul (4. sınıf)

2 → Ortaokul (5–9. sınıf)

3 → Lise

4 → Üniversite

Fedu – Babanın eğitim düzeyi

0 → Eğitim yok

1 → İlkokul (4. sınıf)

2 → Ortaokul (5–9. sınıf)

3 → Lise

4 → Üniversite

Mjob – Annenin mesleği

- teacher → Öğretmen
- health → Sağlık sektörü
- services → Kamu hizmetleri (örn. memur, polis)
- at_home → Ev hanımı
- other → Diğer

Fjob – Babanın mesleği
(Aynı kodlar Mjob ile)

reason – Bu okulun seçilme nedeni

- home → Eve yakın
- reputation → Okulun itibarı
- course → İstenilen ders/alan
- other → Diğer neden

guardian – Öğrencinin yasal velisi

- mother → Anne
- father → Baba
- other → Diğer

traveltime – Eve-okul arası yolculuk süresi

1 → 15 dakikadan az

2 → 15–30 dakika

3 → 30 dakika–1 saat

4 → 1 saatten fazla

studytime – Haftalık ders çalışma süresi

1 → 2 saatten az

2 → 2–5 saat

3 → 5–10 saat

4 → 10 saatten fazla

failures – Geçmiş dönemlerdeki başarısız ders sayısı

0–3 → Başarısız olunan ders sayısı

4 → 3 veya daha fazla

schoolsup – Okul tarafından verilen ek eğitim desteği

- yes → Evet
- no → Hayır

famsup – Aile tarafından sağlanan eğitim desteği

- yes → Evet
- no → Hayır

paid – Ek ücretli özel ders (matematik/portekizce)

- yes → Evet
- no → Hayır

activities – Okul dışı etkinliklere katılım

- yes → Evet
- no → Hayır

nursery – Anaokuluna gitmiş mi

- yes → Evet
- no → Hayır

higher – Yükseköğrenim (üniversite) isteği

- yes → Evet
- no → Hayır

internet – Evde internet erişimi var mı

- yes → Evet
- no → Hayır

romantic – Romantik bir ilişkisi var mı

- yes → Evet
- no → Hayır

famrel – Aile ilişkilerinin kalitesi (1–5)

freetime – Okul sonrası boş zaman düzeyi (1–5)

goout – Arkadaşlarla dışarı çıkma sıklığı (1–5)

Dalc – Hafta içi alkol tüketimi (1–5)

Walc – Hafta sonu alkol tüketimi (1–5)

health – Güncel sağlık durumu (1–5)

absences – Okul devamsızlık sayısı (0–93)

G1 – 1. dönem notu (0–20 arası)

G2 – 2. dönem notu (0–20 arası)

G3 – Final notu (0–20 arası)

- Not: Bu veriseti Kaggle'dan alınmıştır.(student-mat.csv) 

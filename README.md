# Kod-Asistan v0.1

## Proje Yazarı: Salih Toksoy[span_1](start_span)[span_1](end_span)
## Proje Adı: Kod-Asistanı v0.1
## Projenin Amacı Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı olacak bir dijital asistan tasarlamak[span_2](start_span)[span_2](end_span).
## Projenin Hedefleri: 
  * v0.2 sürümünde Akıllı Menü ve temel selamlama özellikleri sunulacaktır[span_3](start_span)[span_3](end_span).
  * v0.3 sürümünde Veri Saklama ve kullanıcı tercihleri kaydı yapılacaktır[span_4](start_span)[span_4](end_span).

## Projenin Kapsamı (Kritik Eşik Mantığı)

```text
BAŞLA
    KULLANICI_GIRDISINI_AL(girdiDegeri)
    KRITIK_ESIK = 10 
    
    EĞER girdiDegeri >= KRITIK_ESIK İSE
        YAZDIR("Kritik eşik aşıldı, ana işlemler başlatılıyor.")
        ANA_ISLEMI_BASLAT()
    DEĞİLSE
        YAZDIR("Hata: Değer kritik eşiğin altında kaldığı için işlem iptal edildi.")
    BİTİR_EĞER
BİTİR

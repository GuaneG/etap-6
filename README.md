# Etap 6 — Warehouse Tasarımı (Kavramsal Derinlik)

> Yol haritamın 6. etabı (Etap 5 ile paralel). Araçların altındaki kavramlar: dimensional modeling, star schema, ETL vs ELT. Çıktı: kağıt üstünde bir star schema tasarımı.

## Kaynaklar
- [dbt Fundamentals](https://learn.getdbt.com) (ücretsiz kurs + rozet)
- [Kimball: Dimensional Modeling Techniques](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/kimball-techniques/dimensional-modeling-techniques/)
- *Fundamentals of Data Engineering* — Reis & Housley (O'Reilly)

## Tasarım çıktısı
Bir senaryo (e-ticaret / futbol ligi) için star schema:
- **Fact tablosu:** <!-- TODO: hangi olay + grain -->
- **Dimension tabloları:** <!-- TODO: en az 4 -->
- **SCD Tip 2 uygulanan dimension:** <!-- TODO: hangisi + neden -->

> Tasarım dokümanı ve şema diyagramı bu repoda (`tasarim.md` + diyagram).

## Notlar
<!-- TODO: fact/dimension, grain, SCD Tip 1/2, ETL vs ELT notları -->

## ✅ Etap 6 Bitiş Kontrol Listesi
- [ ] Fact ve dimension ayrımını ve grain kavramını açıklayabiliyorum
- [ ] SCD Tip 1 ve Tip 2 farkını örnekle anlatabiliyorum
- [ ] ETL ve ELT arasında ne zaman hangisini seçeceğimi söyleyebiliyorum
- [ ] dbt Fundamentals rozetini aldım
- [ ] Bir iş problemi için star schema tasarlayabiliyorum

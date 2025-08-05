Öğretmen Maaşı Tahmini Projesi:
Veri Analizi ve Makine Öğrenmesi Modelleri

Bu çalışmada öğretmen maaş verilerini analiz ederek gelecekteki maaş beklentilerini tahmin etmek için makine öğrenmesi modelleri kıyaslanarak en iyi model kullanıldı. Veriler 'İstanbul Öğretmenleri' adlı https://t.me/+rI_ypeTTrC1hMTI0 telegram sayfasında anketlerle oluşturuşup resim, pdf dosyası biçiminde paylaşımıştır. Paylaşımlar excele dönüştürülerek kullanılabilir verisetine dönüştürülmüştür. Çalışmam aşağıdaki adımları içermektedir:

Veri Yükleme ve Hazırlık: Maaş verilerini içeren Excel dosyası (maas.xlsx) yüklenmiş ve analiz için gerekli sütunlar seçilerek eksik değerler temizlenmiştir.

Makine Öğrenmesi Modellerinin Eğitimi: Farklı regresyon modelleri (Karar Ağacı, Random Forest, KNN Regressor, Doğrusal Regresyon) belirlenen özellikler (mevcut maaş ortalaması, 12 Aylık Ortalamalara Göre Haziran Ayı Tüfe Oranı %, MEB Temmuz Ayı 1/4 Kademe Öğretmen Haftanın Bir Günü Maaşı) kullanılarak gelecek yılın toplam ortalama maaş beklentisini tahmin etmek üzere eğitilmiş ve performansları değerlendirilmiştir.

Gelecek Yıl Maaşlarının Tahmini: Eğitilen modellerden biri (Doğrusal Regresyon), 2022'den 2026'ya kadar olan yıllar için branş bazında tahmini maaşları hesaplamak üzere kullanılmıştır. Bu tahminler özet bir tabloda sunulmuştur.

Branş Bazında Maaş Değişiminin Görselleştirilmesi: Belirli branşlar (örneğin, Matematik Lise) için yıllara göre mevcut maaş, bir sonraki yılın beklenen maaşı ve modelin tahmin ettiği maaş arasındaki değişimi gösteren çizgi grafikleri oluşturulmuştur.

Bu çalışma, mevcut verilere dayanarak öğretmen maaşlarındaki eğilimleri anlamak ve geleceğe yönelik olası senaryolar hakkında fikir edinmek için bir başlangıç noktası sunmaktadır.

ÖZET - SONUÇ

Bu çalışmada İstanbulda özel kurumlarda öğretmenlik yapan öğretmenlerin telegram gruplarında 2021 - 2025 yılları arası kendi aralarında yaptıkları anketler sonucu birleştirilerek bir veriseti oluşturuldu. Verilerimiz 10 yıl öncesi tecrübeli ve 10 yıl üstü tecrübeli öğretmenlerin sayıları ve maaşları ortalamaları alınarak oluşturulduğundan bu veriler ortalama 10 yıllık tecrübeye sahip öğretmenlerin maaş tahmini yaptığını düşünmeliyiz.

Verisetimizde düzenlemeler yapılarak veriler, makine öğrenmesi modellerini karşılaştırarak en iyi performansı gösteren modeller belirlendi. Özellikle Random Forest ve KNN Regressor modellerinin yüksek R² skoru, modelin maaşlardaki değişimi iyi bir şekilde yakalayabildiği görülmektedir. Çalışmamda Random Forest modeli kullanarak gelecekteki öğretmen maaşlarını tahmin edildi. Elde edilen tablo ve grafikler, branş bazında maaş trendleri ve gelecek beklentileri hakkında değerli bilgiler sunmaktadır.

Grafiklerde 2023 yılında beklenen maaş ile tahmini maaş tutarlı olduğu halde mevcut maaşın genel itibariyle yüksek olması, pandemi sürecinde nedeniyle oluşan yüksek enflansyondan dolayı öngörülenin dışında maaşlara 6 ayda bir zam yapılmıştır. Fakat anketler yapılmadığından verisetine yansımamıştır. Bu veri eksikliğinde dolayı 2023 yılı mevcut maaşlar, bir önceki senenin beklentilerinden ve tahminlerinden yüksek olmuştur.

Genel olarak diğer yılların beklentileri ve tahminleri tutarlıdır. Bu sonuçlar ortalama 10 yıllık tecrübeye sahip öğretmenlerin 2026 yılı için özel öğretim kursları ve kurumları ile yapacağı maaş anlaşmalarında çok iyi bir referans olacaktır.

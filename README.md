# KULABUZ

Kişiselleştirilmiş öğrenci rehberliği web uygulaması. Sistemde iki türlü kullanıcı mevcuttur; Öğrenci ve Rehber Öğretmen. Kullanıcılar sisteme kayıt olarak öğrenci hesaplarını aktifleştirebilirler. 

## Aktif hesaba sahip olan öğrenciler;
1. Müfredat seçebilir.
2. Daha önce çözdüğü deneme sınavlarının sonuçlarını sisteme ekleyebilir.
3. Daha önce çözdüğü testlerin sonuçlarını sisteme ekleyebilir.
4. Sistem üzerinden kısa sınav oluşturabilir.
5. Oluşturduğu kısa sınavları sistem üzerinden çözebilir.
6. Ders programı ekleyebilir.
7. Öğrencinin sisteme eklediği ve sistem üzerinde öğrenci için oluşturulan veriler kullanılarak öğrencinin istatistikleri oluşturulur, oluşturulan istatistikler kullanılarak öğrencinin durumunu görselleştirebilmek amacı ile grafikler çizilir.
8. Öğrenci, rehber öğretmenin yayınladığı ilanlardan kendine uygun bir ilan seçerek teklif götürebilir, ilana yapılan teklifleri rehber öğretmen inceledikten sonra kabul edebilir ya da reddedebilir. Kabul edilen ilanların ödemesi yapıldıktan sonra rehber öğretmen, öğrenciye bir ay süreyle rehberlik yapacaktır.
9. Öğrenci, çözemediği soruları ya da kafasına takılan problemleri bir blog yardımı ile sistemdeki kullanıcıların görebileceği şekilde gönderi yayınlayabilir. Yayınlanan gönderilere rehber öğretmen ya da öğrenci yorum yapabilir, gönderiyi beğenebilir, gönderiyi kaydedebilir.
10. Öğrenci sistem üzerinden rehber öğretmenler ile mesajlaşabilir. Ayrıca öğrenci, rehberlik hizmeti aldığı öğretmenleri puanlayabilir.

## Aktif hesaba sahip olan rehber öğretmenler;
1. Rehberlik verdiği öğrencilerin istatistiklerini inceleyebilir.
2. Öğrenci için ders programları oluşturabilir.
3. Öğrenci ile mesajlaşabilir.
4. Sertifika ya da mezuniyet diploması belgelerini ve ders notları ekleyerek öğrenciler arasında popülerliğini arttırabilir.
5. Rehber öğretmen, ilan yayınlayarak daha çok öğrenciye ulaşabilir, öğrencilere rehberlik hizmetini sunabilir.

## Website
Web uygulamasının arka ucu Node.js çerçevesi kullanılarak geliştirildi. Veri tabanı olarak PostgreSQL kullanılmaktadır.
Web uygulamasının ön ucu ise Angular çerçevesi kullanılarak geliştirildi.

```bash
# KULABUZ website
www.kulabuz.com.tr
```

## Uygulamaya Ait Ekran Görüntüleri

### Ana Sayfa
<img width="1680" alt="Screenshot 2023-12-19 at 20 28 25" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/92074746-8e38-4c99-85a0-6b5044b0b5ef">
<img width="1680" alt="Screenshot 2023-12-19 at 20 28 32" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/29d5b407-0916-4b80-984a-4a63bf5743e9">

### Öğrenci Yönetim Paneli
<img width="1680" alt="Screenshot 2023-12-31 at 17 40 13" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/278f4a04-5098-4639-9f23-5a951fcdc234">
<img width="1680" alt="Screenshot 2023-12-31 at 17 39 50" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/14180690-4621-4942-a52d-cb19a1e607fe">
<img width="1680" alt="Screenshot 2023-12-31 at 17 40 03" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/d3ff6107-8f45-4763-b48b-21b86f09f53e">
<img width="1680" alt="Screenshot 2023-12-31 at 17 47 17" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/26588286-26b7-473c-8751-891045b86d03">
<img width="1680" alt="Screenshot 2023-12-31 at 17 40 41" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/446368c4-fd90-4513-946a-9c95989d34d9">
<img width="1679" alt="Screenshot 2023-12-19 at 20 28 09" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/2e3a7077-2111-41af-ab59-b3a93588070f">
<img width="1680" alt="Screenshot 2023-12-19 at 20 28 16" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/b92fff70-895c-4450-ad94-20c574dc9d55">

### Rehber Öğretmen Yönetim Paneli
<img width="1680" alt="Screenshot 2023-12-31 at 17 51 44" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/8bc053f1-56db-4d81-83ee-8a703bf3960f">
<img width="1680" alt="Screenshot 2023-12-31 at 17 51 51" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/2d8d3aa1-7483-43f0-8fdb-39f24462e876">
<img width="1680" alt="Screenshot 2023-12-31 at 17 52 48" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/454630dd-4a61-49a1-8089-aa539d305dbf">
<img width="1680" alt="Screenshot 2023-12-31 at 17 52 55" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/bd3969ae-0b2c-4371-ae2d-7a3f237258a3">
<img width="1679" alt="Screenshot 2023-12-31 at 17 53 02" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/f0b3c7c9-86d7-413f-83fb-ae3e587ca12e">
<img width="1680" alt="Screenshot 2023-12-31 at 17 53 08" src="https://github.com/halilsenaydin/kulabuz/assets/70847361/7025efa6-f811-44fe-a9b8-40765d2772f8">


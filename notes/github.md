Github'ın kazandırdıkları:
Kodları commit etme,
Proje geliştirme,
Branch açma,
Pull request pratiği,
Reviewer olarak kod okuma,
CI/CD (Github Actions) ekleyip pipeline kurma (Hedeflerden biri, test otomasyonu için hazırladığımız automation framework’ümüzü CI/CD pipeline’a entegre edip her push için testlerin otomatik çalışmasını sağlamak.)


1) CI → Continuous Integration (Sürekli Entegrasyon)
Bu aşama şunu yapar:
“Kodun GitHub’a her push edildiğinde otomatik olarak test et, derle, kalite kontrolünden geçir.”
Yani:
Kodunu push ediyorsun
GitHub Actions otomatik olarak tetikleniyor
Senin belirlediğin testler çalışıyor
Kodun sağlıklı mı, bozuk mu sana bildiriyor
Bu, günlük iş hayatında kodun bozulmasını engelleyen bir güvenlik sistemi gibi.

2) CD → Continuous Delivery / Deployment (Sürekli Yayınlama / Dağıtım)
Bu aşama şu:
“Kod güvenliyse otomatik olarak staging ortamına veya production’a dağıt.”
Yani:
Test geçti
Kod merge edildi
GitHub Actions otomatik olarak uygulamayı bir sunucuya deploy eder
Sen hiçbir şey yapmazsın, sistem kendisi yapar.


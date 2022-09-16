# Arduino Akıllı Ev Sistemi

Bu projenin amacı, Arduino üzerinde çalışan bir akıllı ev simülasyonu yapmaktır.

Sistem içerisinde;
- Yangın alarmı,
- Hareket algılayan ışık sistemi,
- Dijital termometre,
- Kilit sistemi bulunmaktadır.


## Proje Özellikleri

1. Arduino kartı olarak Arduino Mega 2560 kullanımıştır.
2. Projede yangın sensörü ve buzzer kullanılmıştır. Yangın tespit edildiğinde alarm çalması
sağlanmaktadır.
3. Projede hareket sensörü ve lamba kullanılmıştırr. Hareket tespit edildiğinde lamba yanması
sağlanmaktadır.
4. Projede sıcaklık sensörü ve LCD ekran kullanılmıştır. Algılanan sıcaklığın devamlı olarak
LCD ekranda gösterilmesi sağlanmaktadır. Sıcaklık 20 C’nin altına düştüğünde ekrana
“Sıcaklık düştü”, 30 C’nin üstüne çıktığında “Sıcaklık yükseldi” yazdırılmaktadır.
5. Projede tuş takımı (keypad), kırmızı ve yeşil led kullanımıştır. Keypad ile girilecek 4
haneli bir şifre belirlenmektedir. Şifre yanlış girildiğinde kırmızı, doğru girildiğinde yeşil
ledin yanması sağlanmaktadır.

# Chiprate

Chiprate, bulunduğun dizindeki tüm MP3 dosyalarının hızını ve pitch değerini aynı anda değiştiren basit bir komut satırı aracıdır. ffmpeg tabanlıdır ve ek yapılandırma gerektirmeden hızlı şekilde çalışır.

## Özellikler

- Pitch ve hız aynı anda değişir.
- Bulunulan dizindeki tüm `.mp3` dosyalarını otomatik olarak işler.
- Boşluk içeren dosya adlarını sorunsuz işler.
- Çıktıları `out_<oran>/` adlı klasöre kaydeder.
- Tek komutla kullanım sağlar.

## Kullanım

Bulunduğun klasörde çalıştır:

chiprate 1.25


Tüm MP3 dosyaları işlenir ve şu şekilde kaydedilir:



out_1.25/
Parca_1.25.mp3
Muzik_1.25.mp3


Yavaşlatmak için:



chiprate 0.75


## Kurulum

Linux üzerinde kurulumu:



sudo wget -O /usr/local/bin/chiprate https://raw.githubusercontent.com/Hasannccelik/Chiprate/main/chiprate

sudo chmod +x /usr/local/bin/chiprate


## Bağımlılıklar

- ffmpeg

Ubuntu/Debian için:



sudo apt install ffmpeg


Arch Linux için:



sudo pacman -S ffmpeg


## Lisans

Bu proje MIT Lisansı altında dağıtılmaktadır.

# Underwater Robotics Research

Bu proje, su altı robotik alanında ROV (Remote Operated Vehicle) ve AUV (Autonomous Underwater Vehicle) için yapılan araştırma ve geliştirme çalışmalarını kapsamaktadır. Projede her iki araç türü için de yazılım, algoritmalar, mekanik ve elektronik entegrasyonlar yer almaktadır.

## İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [ROV Çalışmaları](#rov-çalışmaları)
- [AUV Çalışmaları](#auv-çalışmaları)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)

## Proje Hakkında

Bu proje, su altı robotik alanında ROV ve AUV için yapılan kapsamlı çalışmaları içermektedir. Bu çalışmalarda su altı görüntü işleme, mekanik ve elektronik entegrasyon, su altı tarama ve yol bulma algoritmaları gibi çeşitli konular ele alınmaktadır.

## ROV Çalışmaları

ROV, operatör tarafından uzaktan kontrol edilen bir su altı aracıdır. Bu bölümde, ROV için yapılan çalışmalar yer almaktadır:

- **Görüntü İşleme**: OpenCV kullanarak su altı nesne algılama ve işaretleme.
- **Mekanik ve Elektronik Entegrasyon**: Gyro sensör, motor kontrol ve diğer bileşenlerin yönetimi.
- **Otonom Görevler**: Kullanıcı tarafından verilen komutlarla otonom hareketler.

Daha fazla bilgi için [ROV Belgelerine](docs/rov/overview.md) göz atabilirsiniz.

## AUV Çalışmaları

AUV, otonom olarak hareket eden bir su altı aracıdır. Bu bölümde, AUV için yapılan çalışmalar yer almaktadır:

- **Yol Bulma ve Tarama**: Gelişmiş algoritmalar kullanarak su altı tarama ve yol bulma.
- **Su Altı Navigasyon**: Su altı ortamında güvenli ve etkili navigasyon.
- **Sensör Entegrasyonu**: Çeşitli sensörler kullanarak çevresel veri toplama ve işleme.

Daha fazla bilgi için [AUV Belgelerine](docs/auv/overview.md) göz atabilirsiniz.

## Kurulum

Projenin çalışabilmesi için aşağıdaki adımları izleyin:

### Gereksinimler

- Python 3.x
- OpenCV
- Raspberry Pi 4 (isteğe bağlı)

### Adımlar

1. Projeyi klonlayın:
   ```sh
   git clone https://github.com/username/Underwater_Robotics.git
   cd Underwater_Robotics


Gereksinimleri yükleyin:
pip install -r requirements.txt

Ayar dosyasını düzenleyin:
cp config/rov_settings.example.yaml config/rov_settings.yaml
cp config/auv_settings.example.yaml config/auv_settings.yaml
nano config/rov_settings.yaml
nano config/auv_settings.yaml

Daha fazla bilgi için ROV Belgelerine ve AUV Belgelerine göz atabilirsiniz.

### Katkıda Bulunma

Katkıda bulunmak isterseniz, lütfen katkı yönergelerimizi okuyun ve bir pull request gönderin.

### Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakın.

Herhangi bir sorunuz varsa, lütfen bizimle iletişime geçin: ersozberk@gmail.com
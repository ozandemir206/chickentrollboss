# ChickenTrollBoss

ChickenTrollBoss, ChickenNetwork sunucusu için hazırlanmış, Minecraft 26.2 ile uyumlu TrollBoss sürümüdür. Orijinal eklenti 26.x sürümlerinde açılışta hata verip kapandığı için kodu güncelledik; eklenti artık yeni sürümlerde de sorunsuz çalışıyor.

## Neler değişti

- Sunucu sürümünü okuyan kod, "26.2" gibi iki parçalı sürüm numaralarında hata verip eklentiyi kapatıyordu. Bu kontrol kaldırıldı.
- Void trolü, kırılacak blok sayısını artık sürüm numarasına göre değil, dünyanın en alt yüksekliğine göre hesaplıyor.
- Eklenti Paper 26.2 API'si ile derleniyor ve Java 21 ve üstünde çalışıyor.

## Kurulum

1. `TrollBoss-7.2.jar` dosyasını indir.
2. Sunucunun `plugins` klasörüne at.
3. Sunucuyu yeniden başlat.

Komutlar ve yetkiler orijinal eklentiyle aynı; ana komut `/troll`.

## Derleme

JDK 25 ve Maven gerekir:

```bash
mvn clean package
```

Jar dosyası `target/` klasöründe oluşur.

## Lisans

Bu proje, Minesuchtiiii'nin [TrollBoss](https://github.com/minesuchtiiii/troll-boss) eklentisinin Kasım 2026'da değiştirilmiş halidir ve GPL-3.0 lisansıyla dağıtılır. Ayrıntılar için [LICENSE](LICENSE) dosyasına bak.

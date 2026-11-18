MOOM 6.2.1 - SILAH SESLERI EKLENMIS SURUM

Bu paket MOOM 6.1 M249 kaynak kodunu temel alir ve kullanicinin yukledigi uc ses kaydini silahlara baglar.

SILAH SESLERI
- 1. yuklenen ses kaydi: Cift tabanca
- 2. yuklenen ses kaydi: M249
- 3. yuklenen ses kaydi: Pompalı tufek

NASIL CALISIR
- X veya Kare ile ates edildiginde secili silahin kendi sesi calar.
- R1 ile silah degistirme duzeni korunur: Pompalı -> Cift Tabanca -> M249.
- Onceki zombi olum sesi de korunmustur.
- Sesler 22050 Hz, mono PCM olarak main.c icine gomulmustur; ayri ses dosyasi gerektirmez.

DIGER OZELLIKLER
- 7 bolum.
- Zombi dusme animasyonu ve yerde siyah ceset gorunumu.
- Cift tabanca ve M249 icin 3D silah modelleri.
- Ortak mermi sayaci.

DERLEME
main.c ve Makefile dosyalarini PSP SDK projenize koyup PSPSDK / GitHub Actions ile EBOOT.PBP derleyin.

DOGRULAMA NOTU
Bu ortamda PSP SDK bulunmadigindan derleme ve PPSSPP testi yapilmadi.
Seslerin dogru calismasi hedeflenerek kaynak koda eklendi; gercek calisma PSP SDK ile derlendikten sonra PPSSPP'de test edilmelidir.

DUZELTME 6.2.1
- Silah sesi PCM ornek sayisi makrolarindaki isim uyusmazligi duzeltildi.
- Pistol, M249 ve shotgun sesleri ilgili silaha bagli kalir.

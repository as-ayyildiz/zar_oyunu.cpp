Zar Oyunu (C++)

Bu proje, C++ programlama dilinin temel yapılarını uygulamalı olarak pekiştirmek için geliştirilmiş basit bir zar simülasyonudur. Rastgele sayı üretimi, kontrol akışı ve temel giriş/çıkış işlemlerinin kullanılması üzerine kuruludur. GitHub üzerinde paylaştığım ilk C++ projesidir.

Projenin Amacı

C++ dilinin temellerini pratikte uygulamak

rand() ve srand() fonksiyonlarıyla rastgele sayı üretimini öğrenmek

Standart kütüphanelerin (iostream, cstdlib, ctime) kullanımını kavramak

Basit bir program yapısı oluşturarak algoritma mantığını geliştirmek

Çalışma Mantığı

Program başlatıldığında:

srand(time(NULL)) ile rastgelelik tohumlanır.

1 ile 6 arasında iki sayı üretilir.

Zar sonuçları kullanıcıya konsol üzerinden gösterilir.

Kod yalnızca temel seviyede hazırlanmış olup, anlaşılabilirlik ve sadelik ön planda tutulmuştur.

Derleme ve Çalıştırma

GCC veya MinGW kullanarak çalıştırabilirsiniz:

g++ zar_oyunu.cpp -o zar_oyunu
./zar_oyunu

Dosya Yapısı

zar_oyunu.cpp – Uygulamanın kaynak kodu

Not

Bu proje, C++ diline giriş sürecimin bir parçası olarak oluşturulmuştur. İlerleyen aşamalarda daha kapsamlı ve modüler C++ projeleri eklemeyi hedefliyorum.

# ATU-WEB
ilk olarak proje kopyalmalı, terminal'da şöyle yazılacak
----------------------------------------------------------------------
git clone https://github.com/ATUUYGULAMA/ATU-WEB.git

projeyi kopyaladıktan sonra onu webstorm ile açın
note: o işlem bir kare yapılıyor

ATU-WEB projesi çalıştırmak adımları
----------------------------------------------------------------------
1- ATU-WEB webstorm ile açın, https://www.jetbrains.com/webstorm/download/#section=windows </br>
2- terminal'da=> npm install  yazın
</br>not: kendi bilgisayarını node.js indirmezseniz, hata verecek bunun için
https://nodejs.org/en/download/ girerek node.js windows versiyonu indirin.</br>
3- npm install işlemleri bittikten sonra tüm kütüphaneleri indirmiş olacak
sonra terminal'da=> node app yazıp server çalıştırmış olacaksınız.
</br>not: projeyi http://127.0.0.1:3000/ çalıştıracak ona göre tasarımlar test edeceksiniz.


ATU - Önemli Kurallar
-------------------------
1- Projenin Klasörleri anlamanız gerekir
* /views klasörde tüm tasarlayacağımız dosyalar vardır
  </br>örnek: home.html kaydetmek istiyorsanız /views içinde olacak.
  /public klasörde içinde /css /assets /js klasörler vardır
  örnek: eğer javascript dosyası kaydetmek istiyorsanız /public/js içinde olacak.
  ve böylece mantığı kuruldu.</br>
  not: geri kalan klasörler ve dosyalar backend işidir bakmanızı gerek yok.</br>
  2- dosyalar uzantası .html olmayacak onun yerini, .ejs olacaktır.</br>
  ornek: home.html yanlış => home.ejs doğrudur </br>


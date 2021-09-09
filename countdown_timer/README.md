# Countdown Timer
## Projenin Amacı

HTML, CSS ve Javascript kullanarak belli bir tarih ve saate göre geri sayım uygulaması geliştirme

Kazanımlar:
- setInterval() Metodu: Milisaniye cinsinden belirli aralıklarla bir kodu ya da fonksiyonu çağırır. setInterval metodu clearInterval() metodu çağrılana veya pencere kapatılıncaya kadar fonksiyonu çağırmaya devam eder. (1 saniye = 1000 milisaniye)
    ```sh 
        setInterval(function,miliseconds);
        setInterval(function(){
        alert("İyi günler...");},3000);
        
Yukarıdaki örnekte tarayıcımız 3 saniyede bir İyi günler uyarısı verecektir.
       
- setTimeout() Metodu: Belirli bir milisaniye sonra bir fonksiyonu sadece 1 kere çağırır. setTimeout’un fonksiyonu çağırmasını durdurmak için clearTimeout() metodu kullanılır.
    ```sh
       setTimeout(function,miliseconds);
       setTimeout(function(){
       alert("İyi akşamlar...");},2000);

Bu örneğimizde ise tarayıcımız belgemizi yükledikten 2 saniye sonra İyi akşamlar uyarısı vereceketir.

[Live Demo](https://mustafadurmaz.github.io/projects/javascript/countdown_timer/)

![Uygulama görseli](https://mustafadurmaz.github.io/projects/javascript/countdown_timer/screen.JPG)

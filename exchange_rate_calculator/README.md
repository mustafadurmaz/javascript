# Exchange Rate Calculator
## Projenin Amacı

HTML, CSS ve Javascript kullanarak güncel döviz kurları API ile çekerek döviz hesaplama uygulaması geliştime

Kazanımlar:
- Fetch API ile JSON verisi çekme
    > function get ExternalAPI(){
    > fetch("https://api.exchangerate-api.com/v4/latest/usd")
    > .then(response=>response.json())
    > .then(data=>console.log(data))
    > .catch(err=>console.log(err));
    > }
- toFixed(): Kendisine parametre olarak verilen değer ile sayının ondalık hanesinde kaç basamak olacağını belirler.
    >let test=213.73145;
    >document.write(test.toFixed(2));
    >Output: 213.73

[Live Demo](https://mustafadurmaz.github.io/projects/javascript/exchange_rate_calculator/)

![Uygulama görseli](https://mustafadurmaz.github.io/projects/javascript/exchange_rate_calculator/screen.jpg)

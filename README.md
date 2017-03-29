# React Testleri: Karma, Enzyme ve Mocha

Bu örnek projede basit bir React uygulaması için Karma aracı kullanılarak JavaScript testlerinin çalıştırılması gösterilmiştir. Karma, testleri sahte DOM yerine gerçek bir tarayıcı üzerinde çalıştırdığı için tercih edilebilmektedir. Bu araç bize sadece testlerin çalışacağı ortamı sunmaktadır. Testlerin kendisini yazmak için Enzyme ve Mocha kullanıldı.

#### Çalıştırma:
* Testleri çalıştırmak için `npm run karma` komutu kullanılabilir. npm ve Node.js hakkında detaylı bilgi için bkz: https://nodejs.org

#### Kütüphaneler:
* Enzyme, React uygulamalarını test etmek için kullanılan başarılı bir kütüphanedir. React elementlerini DOM ortamında çalıştırıp ortaya çıkardığı HTML'i test edebilmektedir.

* Mocha, React'a özgü olmayıp, JavaScript testlerinde kullanılan bir kütüphanedir. Testlerin genel yapısını tanımlamayı sağlar. Basitçe, testlerde kullanılan `describe`, `it` gibi metodlar mocha'ya aittir.

* Mocha ile birlikte kullanılan `expect` metodları ise Chai kütüphanesinin bir parçası olup Java'daki `assert`'in yaptığı işi yapar.

React testleri genelde bu üç kütüphane bir arada kullanılarak hazırlanmaktadır. Burada dileyenler için Enzyme yerine Jest kütüphanesini, Mocha ve Chai yerine de Jasmine kütüphanesini kullanmak mümkündür. Bunları kendi sitelerinden inceleyebilirsiniz.

Proje react-testing-example projesi üzerine karma ayarları eklenerek hazırlanmıştır. Bkz. https://github.com/htekgulds/react-testing-example
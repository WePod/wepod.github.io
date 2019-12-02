---
title: EcmaScript6 ile gelen değişiklikler
date: 2019-12-01 22:14:56
tags: stunali
---
Bu yazıda EcmaScript6 ile gelen değişiklikler üzerinde duruldu
<!-- more -->


## EcmaScript Nedir ?

Zaman içerisinde JavaScript birçok evrim geçirdi.İlk zamanlarda Javascript EcmaScript ismini almıştı.Artık EcmaScript JavaScript'in kurallarını belirleyen standart haline geldi.EcmaScript6 Haziran 2015`te yayınlandı
EcmaScript6 ile birlikte kod yazmayı kolaylaştıran birçok yenilik geldi.




**Const ve Let**

EcmaScript2015 `te değişkenleri sadece var ile tanımlayabiliyorduk.EcmaScript6 ile gelen yenilikler ile const ve let aracılığı ile değişkenlerimizi tanımlayabiliriz.

    const PI = 3.141593 
    let name="Serdar"
    

 **Block Scope and Variables and  Functions** 

EcmaScript6'den önce değişkenler fonksiyon scoped`tu.EcmaScript6 ile birlikte gelen güncelleme ile let ve const ile tanımlanan değişkenler blok scope oldu.

    

 **Arrow Functions**

EcmaScript6 ile birlikte fonksiyon tanımına yeni bir sözdizimi getirildi.Artık daha kısa bir sözdizimi ile fonksiyon tanımlayabiliriz.

`hello = () => {  
return  "Hello World!";  
} `

		

 **Varsayılan Fonksiyon Parametleri**

EcmaScript6 ile gelen özelliklerden bir taneside artık fonksiyonlarda varsayılan parametler kullanabiliriz.

    function multiply(a, b = 1) {
      return a * b;
    }
    
    console.log(multiply(5, 2));
    // expected output: 10
    
    console.log(multiply(5));
    // expected output: 5




**Class sözdizimi**

ES6 ile gelen yeniliklerden bir taneside class sözdizimi.Java , C++ , C# dillerinde olduğu gibi class anahtar kelimesini kullanarak sınıf oluşturabiliyoruz.

    class Polygon {
      constructor(height, width) {
        this.area = height * width;
      }
    }
    
    console.log(new Polygon(4,3).area);
    // expected output: 12


**Kalıtım**

EcmaScript6 ile gelen yenilikle birlikte diğer dillerde olduğu gibi (Java,C#,C++) extends anahtar kelimesi kullanılarak kalıtım yapılabilir.

    class Animal { 
      constructor(name) {
        this.name = name;
      }
      
      speak() {
        console.log(this.name + ' makes a noise.');
      }
    }
    
    class Dog extends Animal {
      speak() {
        console.log(this.name + ' barks.');
      }
    }


**Promise** 

JavaScript asenkron çalışan bir programlama dilidir.EcmaScript6dan önce callback fonksiyonları ile asenkron fonksiyonları yönetiyorduk.EcmaScript6 ile birlikte asenkron fonksiyonlar promise sözdizimi ile yönetilmeye başladı.

    new Promise(function(resolve, reject) { ... });

 **Destructing**
EcmaScript6 ile birlikte Destructing özelliğide gelmiştir.Destructing sayesinde dizileri ve objeleri daha kolay bir şekilde parçalara ayırabiliyoruz.Bu sayede daha okunabilir kod yazabiliriz.

    var a, b, rest;
    [a, b] = [10, 20];
    
    console.log(a);
    // expected output: 10
    
    console.log(b);
    // expected output: 20
    
    [a, b, ...rest] = [10, 20, 30, 40, 50];
    
    console.log(rest);
    // expected output: [30,40,50]

**Template Literal**

Template literals stringleri deklarasyon etmek için yeni bir yol sağlıyor.`` (backstick) içersine yazdığınız ${} sayesinde stringler üzerinde istediğiniz işlemleri yapabilirsiniz.

    `string text`
    
    `string text line 1
     string text line 2`
    
    `string text ${expression} string text`
    
    tag `string text ${expression} string text`



**Find()**
Array.Find()  methodu test fonksiyonunu karşılayan ilk elamanı döndürür.


    const array1 = [5, 12, 8, 130, 44];
    
    const found = array1.find(element => element > 10);
    
    

 **findIndex()**
Array.FindIndex()  methodu test fonksiyonunu karşılayan ilk elamanının index değerini döndürür.

    arr.findIndex(callback[, thisArg])



Kaynaklar : [JavaScript - MDN - Mozilla](https://developer.mozilla.org/tr/docs/Web/JavaScript)
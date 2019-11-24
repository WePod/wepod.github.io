---
title: Node.Js
date: 2019-09-30 21:49:49
tags: stunali
---
Bu yazıda Node.js, npm ve node modülleri üzerinde duruldu.
<!-- more -->

Node.js JavaScript ekosisteminin en çok kullanılan frameworklerinden biridir.
Node.js'in gelmesi ile birlikte artık JavaScript yazarak backend geliştirme olanağına sahip olduk.
Bundan önce JavaScript kodlarını sadece tarayıcı tarafında çalıştırabiliyorduk.
Node.js "Chrome'un v8 JavaScript Engine" kullanarak server-side tarafında JavaScript kodlarımızı çalıştırır.
Bu engine JavaScript kodlarımızı alır ve makine koduna dönüştürür. 

## Neden Node.js

Node.js olaya dayalı, asenkron fonksiyonlar kullanır ve bu onu hızlı ve verimli yapar.
Node.js dünyanın en büyük açık kaynak kodlu (npm) paketlerine sahiptir. Bu bize modülerlik sağlar.

## npm

Npm bir paket yöneticisidir. Bu paket yöneticisini kullanarak problemlerinizi çözebilirsiniz. Açık kaynak yazılımdır.
Bu paket yöneticisi hızlı ve verimli kod yazmayı sağlar.

## Node modülleri

Node modülleri, başka kodu etkilemeyen, yeniden kullanılabilir kod bloklarıdır.
Kendi modüllerinizi yazabilir ve çeşitli uygulamalarda kullanabilirsiniz. Node.js, daha fazla kurulum yapmadan kullanabileceğiniz bir dizi yerleşik modüle sahiptir.
Bir node modülü çıkartmak için yapmanız gereken tek şey `module.exports` kullanmaktır. 
Bu kodu, farklı bir projede veye kod bloğunda `require` yardımıyla çalıştırabilirsiniz.
Bu sistem projede modülerlik sağlar, projenin maliyetini düşürür ve daha hızlı çalışmanıza olanak tanır.

Günümüzde Linkedin Node.js teknolojisine geçmiştir. Node.js'e geçişten sonra sunucu maaliyeti 1/10 düşmüştür.
Node.js kullanan bir başka firma da PayPal'dır. 

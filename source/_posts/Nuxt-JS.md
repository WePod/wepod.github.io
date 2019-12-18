---
title: NuxtJS
date: 2019-12-17 15:21:33
tags: stunali
---

NuxtJS Nedir?, Nasıl Çalışır?

<!-- more -->

## NuxtJS Nedir ?

> NuxtJS VueJS, BabelJS, Webpack, NodeJS tabanlı web uygulamaları geliştirmek için kullanılan progressive bir frameworktür.

NuxtJS , VueJS geliştiricileri için kolay ve hızlı web uygulamaları geliştirmek için altyapı oluşturmayı hedefler. **Universal Vue Application** (Sunucu Taraflı Rendering) üretmemize imkan tanır. Dosya ve klasör yapısını kullanarak konfigürasyon yapar.

VueJS çok performanslı bir frameworktür. NuxtJS , kullanıcı ile sunucu aransındaki **Asynchronous Data**, **Middleware**, **Layouts** vb. gibi geliştirmelerinizde, size yardımcı olan bir çok özelliği barındırır. NuxtJS , VueJS uygulamalarımızı daha **kolay** ve **esnek** inşa etmemizi sağlar.

## Server Side Rendering Nedir ?

VueJS , istemci tabanlı rendering yapan bir Javascript frameworküdür. İstemci tabanlı rendering olayının avantajlı yanları olduğu gibi dezavantajlı yanları da vardır.
**SEO** (Arama Motoru Optimizasyonu) ilk akla gelen avantajlarından biridir. NuxtJS sunucu taraflı rendering yaparak hem SEO açısından hem de arayüzümüzün daha hızlı açılması açısından bize avantaj sağlar.

## Çalışma Yapısı

Aşağıdaki resimde bir kullanıcı uygulamamızda gezerken NuxtJS`in çalışma yapısını anlatılıyor.

![NuxtJS Çalışma Yapısı](./Nuxt-JS/NuxtJS.png "NuxtJS Çalışma Yapısı")

## Nuxt Js ile geliştirebileceğimiz Uygulamalar

- **Universal App :** En basit haliyle, **client** tarafında yazdığımız kodun, **sunucu** tarafında işlenerek sunulması diyebiliriz.
- **Single Page App :** **Single Page Application** yönlendirme işleminin sunucu tarafından yapılmayıp Javascript ile **istemci** tarafında yapılmasıdır.
- **Static App (Pre-render View) :** Uygulamızı oluştururken yönlendiricilerimizin her biri için HTML oluşturur ve dosyada saklar.

## Özellikleri

-Sunucu taraflı rendering
-Güçlü routing sistemi
-Statik VueJS dosyası
-Kod ayırma sistemi

#### Nasıl Çalışır?

NuxtJS aşağıdaki paketleri içerir;

-Vue 2
-Vue Router
-Vuex
-Vue Server Renderer
-Vue Meta

Kaynaklar : [NuxtJS](https://nuxtjs.org/guide), [oguzhanaslan](https://oguzhan.in/nuxt-js-universal-vue-js-applications/)

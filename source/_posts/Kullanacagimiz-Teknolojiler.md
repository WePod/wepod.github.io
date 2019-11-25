---
title: Kullanacağımız Teknolojiler
date: 2019-11-25 21:41:19
tags: oguzturker8
---

Teknoloji Seçimi, Ön Yüz, Sunucu Tarafı, Teknolojiler Hakkında

<!-- more -->

#### Teknoloji Seçimi

Projemiz, bir web projesi olduğundan ön yüz tarafında kullanılabilecek teknolojiler sınırlı. Arka yüz tarafında ise sadece kullanıcı bilgileri tutulacağından, kompleks frameworkler yerine daha basit frameworkler kullanmayı planlıyoruz. Projemizin **PWA** olması gerektiğini düşünüyoruz. Projemizin tek bir dil üzerinden yazılması ile kodun, hangi yüzde çalışıldığına bakmadan, tüm proje üyeleri tarafından kolayca anlaşılacağını düşünüyoruz.

#### Ön Yüz için

- **HTML** (Hyper Text Markup Language),
- **CSS** (Cascading Style Sheets),
- **Vue.js** (sunucu tarafında render etmek için **Nuxt.js**)

#### Sunucu Tarafı İçin

- **Node.js**,
- **MongoDB**

#### Kullanıcı Deneyimi İçin

- **PWA** (Progressive Web Apps),
- **Betik Dili**,
- **Adobe Illustrator**,
  teknolojilerini kullanmaya karar verdik.

#### Kullanılacak Teknolojiler Hakkında

- Her tarayıcının okuyup anlayabildiği HTML standardı ile **platform bağımsız** bir uygulama geliştireceğiz. Böylelikle hangi tarayıcıdan veya hangi platformdan girdiğinize bakmadan, Chrome, Yandex Browser, Firefox, Opera,Safari gibi web tarayıcılarının okuyup anladığı bir uygulama tasarlayacağız.
- CSS bir siteyi renklendirmeyi ve biçimlendirmeyi sağlar. HTML iskeletinin üzerine giydirilen bir kıyafet gibi düşünülebilir.
- Vue.js kullanıcı arayüzleri ve tek sayfa uygulamalar inşa etmek için kullanılan **MVC modeli** açık kaynak Javascript framework'üdür. Bu çıktıyı sunucu tarafında çalıştırmak (render etmek) için Nuxt.js kullanacağız.
- Ayrıca projemizi PWA yapacağız. Böylelikle projemiz her platformda (telefon, bilgisayar, tablet) kullanabilir olacak ve **internet gerektirmeyecektir**. Aynı bir uygulama gibi bilgisayarınıza indirebildiğiniz, ya da web üzerinden oynayabildiğiniz bir uygulama olacak.
- Arka yüzde ise Node.js (Chrome v8 Javascript Engine) kullanarak **server-side** tarafında yine Javascript kodlarımızı çalıştıracağız. Böylece hem ön yüzde, hem de arka yüzde Javascript yazarak birden fazla dil karmaşıklığının önüne geçeceğiz.
- Veritabanı olarak MongoDB kullanacağız. MongoDB, 2009 yılında geliştirilmiş açık kaynak kodlu bir **NoSQL** veritabanıdır.
- Projeyi gerçekleştirirken kendi sözdizimi yapımızı oluşturacağız. Böylece kodu kopyalama, paylaşma gibi işlevler yapılmasının yanı sıra, satır satır yorumlayarak **her aşamayı ekranda gösterebileceğiz**.
- Bölümleri, ekranları tasarlamak için Adobe Illustrator kullanıyoruz. Bu program, tasarladığımız bölümleri ve görselleri **SVG** formatında çıktı veriyor. Böylece hangi cihazda çalıştırıldığına bakmadan, görselleri yeniden boyutlandırdığımızda bulanık gözükmüyor ve görselleri eklerken sorun yaşamıyoruz.

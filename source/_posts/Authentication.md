---
title: Ana Ekran Tasarımı
date: 2020-04-09 20:23:13
tags:
  - atagulalan
  - oguzturker8
  - stunali
---

Frontend Authentication , Backend Authentication

<!-- more -->

#### Frontend Authentication

Kullanıcının authentication işlemleri için gerekli sayfaları oluşturduk. Hesap girişi, kayıt olma ve şifre sıfırlama ekranları oluşturduk. Bu ekranları ana sayfa ile birleştirdik. _Modal’i_ elle çizilmiş gibi yaparak tasarımın temiz, ancak doğal gözükmesini amaçladık.

![Authentication](./Authentication/Authentication.jpg "Authentication")

#### Backend Authentication

Bu hafta kullanıcının authentication işlemlerini gerçekleştirmek için gereken altyapı işlemlerini tanımladık. Öncelikle kullanıcının _veritabanı modeli_ oluşturuldu. Daha sonra;

- login,
- logout,
- register,
- resetPassword

_router_ tanımları yapıldı.

Router tanımları yapıldıktan sonra _controller_ tanımları yapıldı. Controller tanımlarında her bir işlem için ayrı fonksiyonlar içinde gerekli tanımlamalar yapıldı.

> Kullanıcı authentication işlemlerini yönetmek için JWT standardı kullanıldı.

Kullanıcı giriş yaptıktan sonra üretilen *token*i kontrol edip _API_’lere erişebilmesi için gerekli olan _middleware_ yapısı oluşturuldu.

- Kullanıcının güvenliği için girdiği şifreyi *hash*leme ve _salt_ işlemlerini yapacak kütüphane projeye entegre edildi.
- Kullanıcının şifresini unutması durumunda şifresini değiştirmesi için e-posta ile şifre yenileme mekanizması geliştirildi.
- Şifre yenileme ekranında API işlemlerini yönetmek için token yapısı kullanıldı.
- Oyunda oluşabilecek hataları yönetmek için merkezi bir hata mekanizması oluşturuldu.
- Veritabanını bulut ortamında kullanmak için gerekli ayarlar yapıldı.

---
title: Authentication
date: 2020-04-09 20:23:13
tags:
  - atagulalan
  - oguzturker8
  - stunali
---

Frontend Authentication , Backend Authentication

<!-- more -->

#### Frontend Authentication

Kullanıcının authentication işlemleri için gerekli sayfaları oluşturduk. Hesap girişi, kayıt olma ve şifre sıfırlama ekranları oluşturduk. Bu ekranları ana sayfa ile birleştirdik. **Modal’i** elle çizilmiş gibi yaparak tasarımın temiz, ancak doğal gözükmesini amaçladık.

![Authentication](./Authentication/Authentication.jpg "Authentication")

#### Backend Authentication

Bu hafta kullanıcının authentication işlemlerini gerçekleştirmek için gereken altyapı işlemlerini tanımladık. Öncelikle kullanıcının **veritabanı modeli** oluşturuldu. Daha sonra;

- login,
- logout,
- register,
- resetPassword

**router** tanımları yapıldı.

Router tanımları yapıldıktan sonra **controller** tanımları yapıldı. Controller tanımlarında her bir işlem için ayrı fonksiyonlar içinde gerekli tanımlamalar yapıldı.

> Kullanıcı authentication işlemlerini yönetmek için JWT standardı kullanıldı.

Kullanıcı giriş yaptıktan sonra üretilen **token**i kontrol edip **API**’lere erişebilmesi için gerekli olan **middleware** yapısı oluşturuldu.

- Kullanıcının güvenliği için girdiği şifreyi **hash**leme ve **salt** işlemlerini yapacak kütüphane projeye entegre edildi.
- Kullanıcının şifresini unutması durumunda şifresini değiştirmesi için e-posta ile şifre yenileme mekanizması geliştirildi.
- Şifre yenileme ekranında API işlemlerini yönetmek için token yapısı kullanıldı.
- Oyunda oluşabilecek hataları yönetmek için merkezi bir hata mekanizması oluşturuldu.
- Veritabanını bulut ortamında kullanmak için gerekli ayarlar yapıldı.

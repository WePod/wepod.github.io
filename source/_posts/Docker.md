---
title: Docker
date: 2020-01-18 19:03:22
tags: stunali
---

Docker Nedir?, Klasik Sanal Makine vs Docker

<!-- more -->

#### Docker Nedir

Docker 2013 yılında DotCloud şirketi tarafından çıkarılmıştır. Açık kaynak kodlu bir projedir. Docker, konteyner teknolojisi kullanarak uygulama oluşturma, dağıtma ve çalıştırma işlemlerini kolaylaştırmak için tasarlanmış bir araçtır. Geliştiriciler ve DevOps mühendisleri tarafından kullanılabilir. Konteyner teknolojisi yeni gelişmiş bir teknoloji olmayıp 2008`de ortaya çıkmıştır. LXC yapısı Linux’a eklenmiştir. Docker bu teknolojiye dayanır. Docker LXC ile yapılan işlemleri daha kolay, hızlı bir şekilde yapmamızı sağlar. Oracle VM VirtualBox, VMWare gibi sanallaştırma teknolojilerinden farkı akıllı kaynak yönetimi, daha kolay yönetilebilir, daha güvenli bir teknoloji sağlamasıdır (Şekil 3.1). Bulut sistemleri ile uyumlu bir şekilde çalışılabilir ve yönetilebilir. İzole edilmiş yapıları sayesinde güvenlik bakımından da diğer teknolojilere göre avantajları vardır.

![Docker Yapısı](./Docker/docker-yapisi.png)

#### Klasik Sanal Makine vs Docker

VM’ler her bir çalışan örneği için full bir işletim sistemine sahiptir. Docker ise hem full işletim sistemi yerine boyut olarak küçültülmüş imajları kullanır hem de konak işletim sistemi kütüphanelerini paylaşımlı olarak kullanır. Fakat bu durum, Docker’i sistem kaynak tüketim dostu yaparken, izolasyon seviyesini ise düşürmektedir. Bunlarla birlikte aşağıdaki karşılaştırmaları yapabiliriz.

![Sanal  Makine vs Docker](./Docker/sanal-makine-vs-docker.png)

Docker Hypervisor ve tam yüklü bir işletim sistemi kullanmadığından maliyet kazancı çok büyüktür. Bir diğeri ise versiyonlamaya yatkınlığı. Docker’ın en vurucu özelliklerinden biride versiyonlanabilme özelliği. Docker, kullandığı işletim sistemi imajlarının farklı hallerini kayıt altında tutmamıza olanak sağlar.

---
title: Styled Components
date: 2019-11-25 23:27:22
tags: oguzturker8
---

Styled Components Nedir?, Styled Components Oluşturma, Biz Neden Tercih Ettik?

<!-- more -->

#### Styled Components Nedir?

Styled Components bizi uzun ve gittikçe karışan CSS kodlarından kurtaran, HTML elementlerini fonksiyonel stillendirmemizi sağlayan ve en önemlisi içerisinde JavaScript kodları kullanmamızı sağlayan bir teknolojidir. Geleneksel stil yazma metodunun dışına çıkarak, temasal ve işlevsel stil bileşenleri (components) oluşturmamızı sağlar.

#### Styled Components Oluşturma

Bileşen oluşturmak çok basittir. Önce Styled Components'i yüklememiz gerekiyor. Aşağıdaki şekilde yüklüyoruz.

```
npm install styled-components@beta
```

Ardından bir stilli bileşen oluşturmak aşağıdaki kod parçası kadar kolay.

```
import stil from 'styled-components';

const Title = stil.h1`
  color: red;
`;
```

Bu şekilde Title adında kırmızı bir h1 bileşeni oluşturmuş olduk.

JavaScript kodlarını aşağıdaki gibi kolaylıkla CSS içine ekleyebiliyoruz.

```
const Button = stil.button`
  color: ${props => props.theme.fg};
  border: 2px solid ${props => props.theme.fg};
  background: ${props => props.theme.bg};

  font-size: 1em;
  margin: 1em;
  padding: 0.25em 1em;
  border-radius: 3px;
`;
```

Bu şekilde Props'lara bağlı dinamik bir bileşen yapısını CSS içinde oluşturmuş olduk.

#### Biz Neden Styled-Components Kullanmayı Tercih Ettik?

Cevabı çok basit; kolaylık ve rahatlık. CSS içerisinde JavaScript kodu yazabilmemiz ve server-side rendering özelliğini desteklemesi nedeniyle, bu yöntemi projemizde kullanmayı tercih ediyoruz. Styled-Components, stylesheet rehydration ile eşzamanlı server-side rendering'i destekler. Aşağıdaki kıyaslama görseli de seçimimizin ne kadar doğru olduğunu kanıtlar niteliktedir.
![Styled Components Vs Others](./Styled-Components/styledcomponents.jpeg "Styled Components Kıyaslaması")

Kaynaklar : [styled-components](https://www.styled-components.com/)

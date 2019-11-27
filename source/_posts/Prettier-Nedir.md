---
title: Prettier Nedir?
date: 2019-11-27 11:40:44
tags: atagulalan
---

Prettier nedir? Standartın önemi nedir? Temiz kod yaklaşımı.

<!-- more -->

### Prettier Nedir?

Prettier, aşağıdakileri destekleyen bir kod formatlayıcısıdır:

- JavaScript, including ES2017
- JSX
- Angular
- Vue
- Flow
- TypeScript
- CSS, Less, and SCSS
- HTML
- JSON
- GraphQL
- Markdown, including GFM and MDX
- YAML

> Prettier, Tüm orijinal stilleri kaldırır ve gönderilen tüm kodların tutarlı bir stilde uyumlu olmasını sağlar. Yani kodunuzu alır, satır uzunluğunu hesaba katarak sıfırdan yazdırır.

Örneğin aşağıdaki kod bloğunu inceleyelim:
```
foo(arg1, arg2, arg3, arg4);
```

Bu blok, tek bir satırda okunabilir. Bu yüzden stillendirmeye ihtiyacı yok. Ancak aşağıdaki kodda bu ihtiyacın doğduğunu görüyoruz:

```
foo(reallyLongArg(), omgSoManyParameters(), IShouldRefactorThis(), isThereSeriouslyAnotherOne());
```

Bu blok çok uzun olduğundan bunu ayırmamız gerekiyor. Prettier, sizin için bu şekilde yeniden yazıyor:
```
foo(
  reallyLongArg(),
  omgSoManyParameters(),
  IShouldRefactorThis(),
  isThereSeriouslyAnotherOne()
);
```

Prettier, kod tabanınızın tamamında tutarlı bir kod stili (örn. AST'yi etkilemeyecek kod formatı) uygular.

### Standartın Önemi

Standartın önemini bir örnek ile açıklayabilirim:

<iframe style="width:100%;height: 630px;" height="630" scrolling="no" title="Standard-agnostic clock" src="https://codepen.io/siddhant-k-code/embed/OJJGNLJ?height=627&theme-id=light&default-tab=result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/siddhant-k-code/pen/OJJGNLJ'>Standard-agnostic clock</a> by Siddhant Khare
  (<a href='https://codepen.io/siddhant-k-code'>@siddhant-k-code</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Gördüğünüz gibi, saat okumak gibi basit bir iş, standart olmadığında bir eziyete dönüşüyor. Kod için de aynı, başka birinin standartlara uymayan kodunu okuduğunuz zaman, buna alışmak zaman alıyor. Zaman ise, bildiğiniz gibi, projelerdeki en önemli kavram.

### Özgürlük

Prettier, aslında istediğiniz şekilde kod yazmayı kolaylaştırıyor, çünkü daha sonra anında doğru bir şekilde formatlıyor. Böylece takımınızla birlikte, birleşik bir kod yazabiliyorsunuz.

Noktalı virgül yazmayı umursamıyor musunuz? Aşağıdakini yazın, Prettier sizin için zaten formatlıyor.

```
function foo() {
  var x = 5
  var y = 6
  var z = 7
  return x + y + z
}
```

Bir takımda çalışırken sürtünmeyi azaltmak çok önemli. Bu sorun, özellikle büyük takımlarda gerçekleşiyor. Tamamen sürtünmeden kaçınmak imkansız, ancak daha iyi çalışmayı kolaylaştırmak için Prettier gibi araçlardan faydalanabilirsiniz.

Kaynaklar: [Prettier Docs](https://prettier.io/docs/en/index.html) [James Long](https://jlongster.com/A-Prettier-Formatter) [Siddhant Khare](https://codepen.io/siddhant-k-code/pen/OJJGNLJ)
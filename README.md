
## VUE.JS EĞİTİM NOTLARI

### VUE’nin Özellikleri Nelerdir?

* Kolay ve hızlı öğrenme
* Çok yönlü ve sürdürülebilir olması
* Mevcut kütüphaneye entegre edilebilme
* Açık kaynaklı ve ücretsiz  olması
* Reactive yapısı
* İhtiyaç duyulan özellikler pluginler ile eklenebilmesi
* Virtual DOM sayesinde yüksek performans
* Kendi Componentlerinizi oluşturabilme
* Chrome developer eklentisi
* Test edilebilir olması

Reusable component yapısına sahiptir. Yani kendi içerisinde html,css ve javascriptleri barındıran ufak uygulamalara sahiptir. Örneğin sitenizde bulunan header, product alanı veya footer kısmınızını sadece bir kerelik component olarak tanımlayabilir ve istediğiniz yerde tekrardan kod yazmadan kullanabilirsiniz.

![alt text](image/reusable-component.png)

## Vue, React, Angular Hangisini Seçmeliyim ?


-  Anlaşılabilir basit Syntax
   * Vue.js 'in diğer framwork'lere göre oldukça kolay bir Syntax'ının olması Bu sayede kolay kolay proje geliştirmeni sağlayacak bir framework.
-  Component Yapısı ve Render Süreçleri
   * Diğer 2 framwork'de de Component yapısı mevcut. Bu yüzden bu çok farklı bir durum olarak karşımıza çıkmıyor. React'a göre Component'lerin Render edilme süreçleri **Vue.js** içinde **çok daha pratik ve hızlı!**
- Javascript, Html ve Css
   * Angular ve Vue.js Framework'ler uygulama geliştirirken, development süreçlerine HTML ve CSS kodlarını dahil ederek oldukça hızlı ve rahat bir şekilde tasarım yapabiliyoruz. 
 - Virtual Dom
   *  Vue.js Virtual Dom Nedir ?
   <br>
        Vue.js kendi yapısında virtual dom (document object model) barındırmaktadır. Virtual Dom’un çalışma mantığını özetleyecek olursak, sizin modelinizde bir değişiklik olduğundan gerçek DOM yapısında değişiklik olmaz. Bunun yerine, değişiklikler sanal bir DOM yapısında gerçekleşir.Daha sonra gerçek DOM ile sanal DOM arasındaki farka bakılarak sadece değişen kısımlar algılanır ve gerçek DOM üzerinde bu değişen kısımlar güncellenir. Değişmeyen kısımlar boş yere güncellenmez. Buda bizim performansımızı artırır. Aşağıdaki şemada bunu görsel olarakta inceleyebilirsiniz.

![alt text](image/dom.png)



* [Başlangıç](https://github.com/ozllmozdmrr/vuejs-note/blob/main/vue.js-Baslangıç/index.html) 

* [VueJS Template yapısını kavrayalım](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index.html)

* [VueJS Template Syntax ve Vue instance birlikte nasıl çalışır?](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index1.html)

* [Vue instance içerisindeki data property bilgilerine ulaşmak](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index2.html)
  
* [Attribute Bind Işlemi](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index3.html)

* [Directive Kullanımı](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index4.html)

* [v-once ile re-render işlemini engellemek](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index5.html)

* [HTML kodlarını Vue.js üzerinden ekrana basmak](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index6.html)

* [VueJS ile Event Dinlemek](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index7.html)

* [Event Objesinden Event verisini almak](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index8.html)

* [ Event İçerisinde Argüman Göndermek](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index9.html)

* [ Event Modifier](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index10.html)

* [ Klavye Event'ler](https://github.com/ozllmozdmrr/vuejs-note/blob/main/Dom-Etkileşimleri/index11.html)



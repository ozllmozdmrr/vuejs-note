
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
[resim]: image/dom.png"Virtual Dom"


  

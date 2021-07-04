# Android Görünümü Güzelleştirme
## En yukarıdaki kısım status-bar olarak geçmektedir.<br>
## Onun aşağısında bulunan kısım actionbar olarak geçmektedir.<br>
## <b>res/themes</b> kısmındaki renkleri değiştirirsek istediğimiz görünümü elde edebiliriz.Eğer actionbar yerine toolbar kullanırsak kendisi geri tuşunu ekleyecektir. Ama actionbar varsa kendimiz ekleyeceğiz.
<h1>Aşağıdaki resimde isimleri verilmiştir.</h1><br>

![info](https://github.com/isilay-subasi/android-status-bar/blob/main/images/info.png)



## Action-Barı Özelleştirmek için
- İlk adım olarak menu oluşturup içerisine main adında .xml ekliyoruz.
- Bu xml içerisine barda kullanacağımız itemları ekliyoruz.
- Ve onları tanımlarken aşağıdaki özellikleri vermek zorundayız.
<br>
<b>android:title</b>Kullanıcı bu öğeyi uygulamada tıklayıp tuttuğunda görüntülenecek olan menü öğesinin başlığını içerir.
android:id: Tüm uygulama dosyalarında herhangi bir yere erişmek için kullanılacak menü öğesi için benzersiz bir kimlik

<b>android:orderInCategory:</b>Bu özelliğin değeri, öğenin ActionBar'daki konumunu belirtir. Farklı menü öğelerinin konumunu tanımlamanın iki yolu vardır. Birincisi, tüm öğeler için bu özniteliğin aynı değerini sağlamaktır ve pozisyon, kodda bildirildiği sırayla tanımlanacaktır. İkinci yol, tüm öğeler için farklı bir sayısal değer sağlamaktır ve ardından öğeler kendilerini bu özelliğin değerinin artan sırasına göre konumlandıracaktır.

<b>app:showAsAction:</b> Bu özellik, öğenin eylem çubuğunda nasıl bulunacağını tanımlar

<b>a. always:</b> Öğeyi her zaman ActionBar'da görüntülemek için.<br>
<b>b. ifRoom: </b>Boş alan varsa öğeyi tutmak için.<br>
<b>c. never:</b>Bu bayrakla, öğe ActionBar'da bir simge olarak görüntülenmez, ancak taşma menüsünde bulunur.<br>
<b>d. withText:</b>Bir öğeyi hem simge hem de başlık olarak temsil etmek için, bu bayrak her zaman veya ifRoom bayrağıyla (always|withText veya ifRoom|withText) eklenebilir.<br>

<b>android:icon:</b> The icon of an item is referenced in the drawable directories through this attribute.<br>


# Custom Action Bar

![show](https://github.com/isilay-subasi/android-status-bar/blob/main/images/show-1.PNG)
  







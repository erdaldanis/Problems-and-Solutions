### Merhabalar

Devespress ve türevlerini projede kullanabilmek için indiriyoruz. İstisnai olarak yüklemesini tamamladığımız devexpress in Visual Studio 2017 ve diğer sürümlerinde toolbox'da componentleri görünmüyor. Bunun için şu yolu izleyebilir, toolbox'ta görünmesini sağlayabilirsiniz.

<ol> 
<li> Visual Studio herhangi bir sürümü açıksa kapatınız. </li>
  <li> Yönetici olarak CMD komut editörünü çalıştırınız </li>
  <li> Toolbox Genarator'un bulunduğu dizini bulup komut satırından o dizine erişiniz.
    <pre> <code> Örnek :  cd  \Program Files (x86)\DevExpress\Components\Tools </code> </pre>
  </li> 
  <li> Komut editöründe bu kurulumu sağlamak için şu komutu yazınız. 
    <pre> <code>ToolboxCreator.exe /INI:toolboxcreator.ini </code> </pre> </li>
</ol>

<h4> Bu adımlardan sonra Visual Studio yu tekrar başlatıp, toolboxta devexpress compenetlerini görebilirsiniz. </h4>

İyi Çalışmalar
Kolay Gelsin 

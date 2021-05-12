
### Selamlar 

Git de kronik olarak yaşadığımız zaman zaman aklımıza çok nadir gelen bir hata .ssh hatası, bunun için şu adımları hazırladım. Umarım senin için yararlı olur 

 <p> Eğer bu hatayı alıyorsan <b>"Permission Denied (publickey)' error when I push!</b> Öncelikle hatanın %99 .ssh ile olduğunu düşünelim.
  
  1) Git bash'ı açın veya Mac Terminalini açın. Herhangi bir * nix tabanlı komut istemini kullanabilirsiniz (ancak varsayılan Windows Komut İstemi'ni kullanamazsınız!)

  2) Aşağıdaki şekilde ilk komutu yazın. Bu sizi Git'in kök dizinine götürecektir (Windows'ta C:\Users\[SİZİN-KULLANICI-ADINIZ]\.Ssh\) 
      <pre> <code> cd ~ / .ssh </code> </pre> 
      
  3) .Ssh klasörü içinde şu iki dosya bulunmalıdır: id_rsa ve id_rsa.pub. Bunlar, bilgisayarınıza GitHub,BitBucket veya başka bir Git tabanlı hizmetle nasıl iletişim 
      kuracağını söyleyen dosyalardır. Dizinde bulunan dosyaları görmek için aşağıdaki komutu yazın
      <pre> <code> ls  </code> </pre> 
      <b style="color:red"> NOT: </b> Git, GitHub ve BitBucket'ın varsayılan olarak tanıması için SSH anahtarlarınız id_rsa ve id_rsa.pub olarak adlandırılmalıdır.
      
  4) SSH anahtarları oluşturmak için aşağıdaki komutu girin. Bu hem id_rsa hem de id_rsa.pub dosyalarını oluşturacaktır.
      <pre> <code> ssh-keygen -t rsa -c "email@example.com" </code> </pre> 
  
  5) Şimdi notepad++ veya herhangi bir metin düzenleyicinizde id_rsa.pub dosyasını açın. İd_rsa.pub'ın içeriğini tam olarak göründüğü gibi, fazladan boşluk veya satır
     olmadan kopyalayın  GitHub ve/veya BitBucket' ta Hesap Ayarları> SSH Anahtarları altındaki alana yeni bir ssh oluşturup onun açıklama alanına yapıştırın. 
     
  6) Artık ssh anahtarınızı Github ve / veya BitBucket'e eklediğinize göre, git push'u tekrar deneyin ve çalışıp çalışmadığını görebilirsiniz


Kolay gelsin. Sonra tekrar görüşürüz 😄 👋

     


### Merhabalar

Bu hata farklı senayolarla karşımıza çıkıyor. Bu hata ile meydana gelen benzer hata çıktıları şu şekildedir. 

<ul> <li> <pre> <code> npm ERR! Error: EPERM: operation not permitted, rename C:\projects******\node_modules\react-async-script' -> 'C:\projects*******\node_modules.react-async-script.DELETE' </code> </pre> </li> 
  <li> <pre> <code> ./node_modules/axios/lib/helpers/cookies.js Error: EPERM: operation not permitted, read </code> </pre> </li></ol>
  
  Bu hataların çözümü için şu yolları izlemek istisnai durumlar haricinde genellikle problemi gidermektedir.
  
  
 ### 1. Çözüm 
 <ol> 
  <li>Önceliklikle projenizin bulunduğu derleyici komple kapatın</li>
  <li>Node.js komut editörünü yönetici olarak çalıştırın veya yeni bir VSCode terminal açıp önbelleği temizleyin. Şu komutu yazabilirsiniz
    <pre> <code> npm cache clean --force </code> </pre> </li>
  <li> Şimdi yapmamız gereken npm'in en son sürümünü yüklemek. Bunun için aşağıdaki yolu izleyebilirsin.  <pre> <code> npm install -g npm@latest --force </code> </pre> </li>
  <li> Tekrar önbelleği temizleyerek projemizi build edelim. <pre> <code> npm cache clean --force </code> </pre> </li>
  
  </ol>
  
   ### 2. Çözüm 
 <ol> 
  <li >1.Çözümde olduğu gibi projenizin bulunduğu derleyici komple kapatın</li>
  <li> 1. Çözümde oldugğu gibi Node.js komut editörünü yönetici olarak çalıştırın veya yeni bir VSCode terminal açıp önbelleği temizleyin. Ve npm i tekrar zorlayarak kurun.Bunun için şu komutu yazabilirsiniz.
    <pre> <code> npm install --force </code> </pre> </li>
  <li> Node_modules'in salt okunur dosya olarak ayarlanmadığı kontrol edin. Eğer salt okunur halde ise kaldırın. Ve /node_modules klasörünü silin </li>
  <li> Projenizi yeniden başlatın. </li>
  
  
  </ol>
  



  
 ### Umarım bu 2 çözüm sorununuzu giderir. 
### Kolay gelsin 👨‍💻

  ![](https://komarev.com/ghpvc/?username=your-github-erdaldanis&label=PROFILE+VIEWS)
  
  

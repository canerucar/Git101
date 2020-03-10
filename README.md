<img src="https://user-images.githubusercontent.com/25962055/76292248-eba5ab00-62bf-11ea-8218-d537bacef7ff.png" height="100" width="100"> 

# Git - Terminal - Github

Versiyon kontrol sistemleri en basit anlamda dosyalarınızda ki değişikliklerin tarihçesini takip edip kayıt altında tutan sistemlerdir.

**1 -** git config --global user.name “adsoyad”	    **- Git hesabına kendimizi tanıtıp ismimizi ekledik <br/>**
**2 -** git config --global user.email “emailimiz”	**- Git hesabına email adresimizi ekledik <br/>**
**3 -** git config --global user.name			          **- Adımızı Gösterdi <br/>**
**4 -** git config --global user.email			        **- Email adresimizi görmemizi sağladı <br/>**

**5 -** pwd	  **- Terminal üstünde bulunduğumuz mevcut dizinin tam adresini gösterir <br/>**
**6 -** ls		**- Listelemek. bulunduğumuz konumda mevcut olan dosyaları gösterir <br/>**
**7 -** cd		**- Dizin değiştirmek için kullanılır <br/>**

**8 -** cd ..	       **- Bir önceki dizine gider <br/>**
**9 -** clear        **- Terminali temizler <br/>**
**10 -** git init    **- Proje dosyasına gittikten sonra bu komutu yazıp dosyayı bir git projesi haline getiriyoruz <br/>**

*NOT :  Bash Terminalinde projenin kök dizini içerisinde rm -rf .git yazarsanız .git klasörünü silerek, projenin git ile olan ilişkisini kesebilirsiniz.*

**11 -** git add .    **- Git deposuna dosyamızı ekledik fakat tek başına yeterli değil, şuan staging areada <br/>**
**13 -** git add *    **- Tüm dosyalar staging areada <br/>**
**14 -** git commit -m “ilk commit” **- Sonra bu komutu yazıp bir string giriyoruz <br/>**
**15 -** git log      **- Girdiğimiz versiyonları listelemek için <br/>**

**16 -** git status          **- Projede herhangi bir değişiklik yapmışsak değişiklikleri görürüz <br/>**
**17 -** git add cikarma.txt **- Projeye dosya ekledik <br/>**
**18 -** git commit -m “Cikarma methodu eklendi” <br/>

**19 -** git diff          **- Dosya içinde yapılan değişiklikleri görmemize yarıyor <br/>**
**20 -** git rm carpma.txt **- Dosyayı sildik <br/>**

**21 -** git rm -r silinecekler  **- Dosya adını verdiğimiz kısım silinecektir <br/>**

**22 -** git mv deneme123 deneme321 **- Dosya adını değiştirdik <br/>
**23 -** git mv deneme321 dosyalar/ **- Diğer bir görevi olarak dosyayı taşıyor <br/>**

**24 -** git checkout --dosyaadi   **- dosya içi değişikliğini eski haline getirir <br/>**
**25 -** git reset HEAD dosyaadi   **- yapılan değişikliği geri alma <br/>**

**26 -** git checkout “gitmek istediğimiz versiyonun kodu” <br/>

**25 -** git remote add origin “repo adres linki ekle” <br/>
**26 -** git remote **- bağlantı eklendi mi eklenmedi mi <br/>**
**27 -** git push -u origin master **- projeyi repoya gönderdik <br/>**

**28 -** cat .gitignore 		**- gizli dosya oluşturup içine bir şey ler yazıyoruz <br/>**
**29 -** gedit .gitignore 	**- dosyayı açıyor <br/>**

**30 -** git pull 		**- GitHub dan bilgisayarda ki dosyanıza dosyaları çeker <br/>**
**31 -** git branch 	**- GitHub da ki dallarımızı listeliyor <br/>**

**32 -** git branch --all 		  **- Uzak bilgisayarımızdaki brancleri listeliyor <br/>**
**33 -** git branch yandal1 	  **- Yeni dal oluşturuldu <br/>**
**34 -** git checkout yandal1 	**- Yandal1 deyiz şuan <br/>**

**35 -** git diff master yandal1 **- Bu iki dal arasında ki farkları görmemize yarıyor <br/>**
**36 -** git merge yandal2 	 **- İki dalı birleştiriyoruz. zaten master dalında olduğumuz için belirtmemize gerek yok <br/>**

**37 -** README SAYFASI İÇİN:
       kalın başlık için:  #Burası Başlık : Başına tek kare <br/>
       bir alt kalın başlık: ## Alt Başlık : Başına iki kare <br/>
       ** Kalın Kelime ** <br/> Başına ve sonuna iki yıldız <br/>
       *italik kelime* : başına ve sonuna tek yıldız <br/>

        link vermek için: [Google Linki](http://www.google.com) <br/>
        resim eklemek için: ![Banner Resmi](resmin githubda ki tam adresini gir) <br>
        
**38 -** git --version 	 	**- Bilgisayarınızda ki git sürümünü öğrenmeniz için <br/>**
**39 -** git log                   **- Commitler ile ilgili ayrıntılı bilgi <br/>
**40 -** git log --oneline.    	**- Yapılan commitleri kısaltılmış olarak gösterir <br/>
**41 -** git log -p 	        	**- Daha ayrıntılı bilgi <br/>**
**42 -** git status 	        	**- Hangi branchte olduğumuzu görebiliriz <br/>**

**43 -** git clone            	**- Projeyi bilgisayarınıza indirir <br/>**
**44 -** git branch - v		**- Branchle ilgili ayrıntılı bilgi görmemiz için <br/>**

**44 -** git stasht                **- Commitlemeden önce geçici kayıt altına almak istediğimizde kullanırız <br/>**

**45 -** git stash list		**- Geçici değişikliklerimizi görmemiz için <br/>**
**46 -** git stash pop		**- Değişikliğin en üsttekini geri yüklenecek ve bunu listeden silecek <br/> **
**47 -** git stash apply	**- İstediğimiz değişikliği geri yükleyebiliriz <br/>**
**48 -** git stash drop		**- Herhangi bir değişikliği listeden silmek için kullanılır <br/>**

**49 -** git checkout master			**- Branch geçişi <br/>**
**50 -** git checkout commitiDsiyazılacak	       **- İstediğimiz commite gider <br/>**
**51 -** git branch loginsorunu                  **- Yeni bir branch oluşturduk <br/>**
**53 -** git merge loginsorunu                   **- Yeni açılan branchi ana master branchimizle bağladık <br/>**

**54 -** git clone --bare " "	**- Localde ki projeyi , remote repositorye atmak için <br/>**
**55 -** git init --bare	**- Boş remote repository oluşturmak için <br/>

**57 -** git remote -v	**- Remote repositorymiz ile ilgili bilgileri görüyoruz <br/>

**58 -** fetch             **- Remote repositryde yapılacak olan okuma işlemleri <br/>**
**59 -** push             **- Remote  repositoryde yazma işlemleri olarak kullanılır <br/>**

**60 -** git branch -va    **- Remotede ki değişikliklere baktık <br/>**
**61 -** git fetch		- Remote ile ilgili localdeki diskte tuttuğu bilgileri güncellemesini sağladık

**62 -** git checkout --track **- Remote branch ile aynı isimde local bir branch oluşturulur <br/>**

**63 -** git fetch	**- remote branchteki değişiklikleri indirmek için kullanıyoruz <br/>**
**64 -** git pull	**- local branchimize entegre etmek istediğimizde (çok fazla kullanılmaz) <br/>**

**65 -** git diff    **- Remote ve local arasındaki farkları inceler <br/>**

**66 -** git branch -d superyeniozellik          **- Localdeki branch siler <br/>**
**67 -** git branch -dr superyeniozellik         **- Remotedekini siler <br/>**

**68 -** git commit --amend		**- Son commit işlemini yeniden yapmak için <br/>**
**69 -** git commit --amend -m	**- Commit mesajını değiştirmek için <br/>**

**70 -** git checkout --dosya1md 	**- Değişiklik yaptığımız branchin son commit haline getiririz <br/>**
**71 -** git reset —hard 		**- Tüm dosyalarda yaptığımız değişiklikleri geri almak istiyorsak <br/>**

**72 -** git revert 			**- Commit edilen herhangi bir değişikliği geri almak için kullanılır <br/>**
**73 -** git diff —staged 		**- Sadece staging Area’ya commit edilmek üzere eklenen çıkarılanları görmek için <br/>**

**74 -** git log -p             		       **- Dosyaların içeriğindeki farkları görmek için <br/>**
**75 -** git diff master..superyeniozellik 	**- İki branchi karşılaştırmak için kullanılır <br/>**

**76 -** git merge --abort 			**- Merge işlemini geri alma <br/>**

*Sourcegear DiffMerge - Çakışmaları daha rahat görmemiz için uygulama*

## Github Projeye Destek Sağlamak

Github Fork - Github üzerindeki bir projeyi kendi hesabımıza klonlamaktır

#referans brach’imizi seçelim.
$ git checkout master 
#yeni branch açalım
$ git checkout -b yeni-branch-adi

Değişiklikleri commit’ledikten sonra artık pushlayabiliriz.

$ git push origin yeni-branch-adi

Projeyi güncel tutmak için aşağıdaki komutları uygulamanız yeterli olacaktır.

#referans brach’imizi seçelim.
$ git checkout master
#orijinal projeden değişiklikleri çekelim. && forkladığımız yere push'layalım.
$ git pull upstream master && git push origin master

Sonuç olarak

	- Projeyi forkla ve bilgisayarına indir.
	- Başlamadan önce, projeyi orijinali ile senkronize tutmak için “remote upstream” oluştur.
	- Yapacağın işle ilgili branch oluştur.
	- Değişiklikleri yap, commit mesajını yaz ve “CONTRIBUTING.md” dosyası varsa oku.
	- Forkladığın projeye push’la
	- Yeni bir PR oluştur.
	- Katkıda bulunmanın tadını çıkar ve açtığın PR (Pull Request)'i takip etmeyi unutma.

$ git branch -d Yenidal oluşturulan yeni dalı siler (Yerelde). <br/>
$ git branch -dr Yenidal oluşturulan yeni dalı siler (Yerelde ve GitHub’da). <br/>
*(Silme işlemlerini yaparken master dalında olduğunuzdan emin olun.)* <br/>

# Watch, Star ve Fork

**Watch  :**  Github'ta bir projeyi takip etmeye yarar. <br/>
**Star   :** Projeyi beğendiğiniz anlamına gelir ve sonradan yıldızladığınız projeyeleri inceleyebilirisiniz. <br/>
**Fork.  :** Projenin bir kopyasını hesabınıza almak istediğinizde kullanılır. <br/>
**Issues :** Problemler <br/>

*NOT : Projenizle ilgili oluşan sorun, öneri vs. gibi diğer kişilerden yardım, öneri, çözüm almak için kullanılır. Projenizle ilgili bir issues oluşturmak için issues sekmesinde new issues butonunu kullanabiliriz. İstenilen bilgileri girdikten sonra issues yayınlayabilir ve sonuca ulaştığınızda kapatabilirsiniz.*

# Versiyon Değiştirmek

Git projesinde almış olduğumuz versiyonlara geri dönmek istediğimizde aşağıdaki şekilde bir komut yazarız: <br/>
git checkout 95a6e33d877afbfe6e43419996cda613bdd4936a -- . <br/>

buradaki girmiş olduğunuz uzun sayıya bir kimlik belirtmektedir. Bu kimliğe git log komutu ile ulaşırız. Komutun sonundaki nokta ise o versiyona ait tüm dosyaları geri almak istediğimizi belirtir. Eğer belirli bir dosyayı geri almak istersek nokta yerine o dosyanın isimini yazmamız gerekir. Bu komutu çalıştırdığımızda işlemlerin geçerli olması için commit etmek gerektiğini unutmayın. <br/>

**git branch --all :** Komutuyla dalları listeleriz. Uzak depodaki dalları görüntülemek istersek bu komutu kullanırız. <br/>

## Diff aracı ayarları : 
Bir dosyanın Tx anındaki içeriği ile Ty anındaki içeriğinin arasındaki farkları tespit etme ve gösterme işlemidir. <br/> İngilizcede difference (fark) kelimesinin kısaltması olan diff şeklide kullanılır. <br/

- Eğer proje githubda ise clone ile bilgisayarımıza indirip bağlantı yapıyoruz <br/>
- Proje artık yerelde olduğuna göre. Üzerinde çalışmaya başlayabiliriz. İlk önce cd projeadi komutu ile terminalde projenin içine giriyoruz. Bu işlemden sonra kimin yaptığını bildirmek için isim ve mail adresi giriyoruz.

Henüz versiyon kontrolünde olmayan bir projeniz varsa *git init komutu ile projenizi tüm klasör ve dosyaları ile birlikte versiyon kontrolüne alabilirsiniz

Projeniz uzaktaki veya şirket ağınızdaki bir Git sunucusunda versiyon kontrolü altında tutuluyorsa projeyi kendi bilgisayarınıza git clone komutu ile indirebilirsiniz.

Fakat, commit işlemi öncesinde dosyalarınızda yaptığınız değişikliklerin bir özetini görmek isteyebilirsiniz. git status komutu ile hangi dosyaları değiştirdiğinizi, sildiğinizi veya hangi dosyaları eklediğinizi kolayca görebilirsiniz.

Bir sonraki aşamada değişen dosyalarınızdan hangilerinin commit'e dahil olduğunu belirlemeniz gerekiyor. Bu adımda commit'e dahil etmek istediğiniz dosyaları staging area denilen ara bir alana alırız.

Dosyaların içeriğinin değiştirilmiş olması, silinmesi veya yeni dosya eklenmesi bu dosyaların otomatik olarak staging area'ya eklenmesini sağlamaz. Bu işlemi ilgili dosyaları seçerek sizin yapmanız gerekir.

Local (Yerel) & Remote (Uzak) Repository'ler <br/>
Local repository, kendi bilgisayarınızda proje klasörünüzün altında bulunan .git klasörüdür. Bu repository üzerinde sadece siz çalışabilirsiniz ve değişiklikler yerel diskinize kaydedilir.

Remote repository'ler ise genellikle uzaktaki bir sunucuda yer alırlar ve bu sunucudaki .git klasöründen ibarettirler. Takım çalışması söz konusu ise takımdaki kişiler değişikliklerini bu uzaktaki repository üzerinden paylaşırlar. <br/>

**ls -la :** komutu ile proje klasörünüz altındaki dosyaları listelediğinizde klasörün içinde .git isimli gizli bir klasörün olduğunu göreceksiniz. <br/>

Git ile versiyon kontrolü yapılan bir projeye dahil olduğunuzda size verilecek ilk bilgiler projenin Git adresi (URL) ve projeye erişim için kullanacağınız kullanıcı adı ve şifrenizdir. Uzaktaki bir repository'nin (URL) adresi aşağıdaki formatlardan birinde olacaktır <br/>

- **ssh://user@server/git-repo.git <br/>**
- **kullanıcıadı@sunucuadı:git-repo.git <br/>**
- **http://example.com/git-repo.git <br/>**
- **https://example.com/git-repo.git <br/>**
- **git://example.com/git-repo.git <br/>**

Bu adres formatlarından ilk iki tanesi SSH (Secure Shell) protokolüne karşılık gelir. http:// ve https:// protokolleri ise normal internet erişimi için de kullanılan protokollerdir. Son format ise git'in kendi protokolüne karşılık gelir. <br/> 

**Staging Area :** Kısaca Staging Area'yı açıklamak gerekirse, ancak git'de değişikliklerinizin kayıt altına alındığı üçüncü bir alan daha vardır ki buna Staging Area denir ve git'in en temel kavramlarından birisidir. Staging Area'yı, proje dosyalarımızdaki bir dizi değişikliği remote repository'ye göndermeden önce kayıt altında tuttuğunuz veri tabanı/alan olarak tanımlayabiliriz. <br/>

Benzer şekilde aşağıdaki **git rm** komutu ile **ornek2.md** dosyasının bir sonraki commit’imizde yer almayacağını belirtebiliriz. <br/>
$ git rm ornek2.md <br/>

*Gitflow, Forking ve Pull Request adı verilen alternatif iş akışları ile ilgili arama yaparak farklı yaklaşımları kendiniz inceleyebilirsiniz.*

**Remote branchdeki değişikliklerin bilgilerini indirmek için kullanılan fetch (türkçe anlamı getirmek) ve bu değişiklikleri entegre etmek için kullanılan pull (türkçe anlamı çekmek) ifadelerinin birbirine yakın anlamları olduğu için karıştırabilirsiniz. Bu karışıklığın önüne geçmek için yapacağınız en güzel şey git pull komutunu hiç kullanmamak olacaktır. <br/>**

**Git pull komutu aslında arka arkaya iki şey yapmanızı sağlar <br/>**

Remote branch'deki değişiklikler ile ilgili bilgileri indirmek, yani **git fetch** <br/>
Remote branch'deki değişiklikleri local branch'inize entegre etmek yani **git merge** <br/>
**git fetch :** remote'dan güncelleme bilgilerini indir <br/>
**git diff :** remote ve local arasındaki farkları incele <br/>
**git merge :** değişiklikleri otomatik merge et çakışma varsa bir sonraki adıma geçin <br/>

## Dipnot

Remote branch'i **git branch -dr** komutu ile sildiğiniz halde remote repository'ye erişip branchleri kontrol ederseniz **superyeniozellik** isimli branch'in sunucuda hala durduğunuz göreceksiniz. Bunun nedeni **git branch -dr** komutundaki seçeneklerden **r** seçeneğinin sunucudaki branch'i değil yerel bilgisayarınızda remote branch bilgilerini siler. Bu değişikliğin sunucuda da geçerli olması için yani sunucudaki branch'i de silmek için **git push origin :superyeniozellik** komutu ile değişikliği bir anlamda remote repositry'de yayınlamanız gerekiyor. <br/>

**git revert** komutu commit ettiğiniz herhangi bir değişikliği geri almak için kullanılır. Bu komut ile commit işleminizin kendisi veya bilgileri silinmez sadece commit işleminizdeki değişiklik geri alınır. Örneğin eklediğiniz bir satırı kaldırmak isterseniz **git revert** komutu ile bunu yapabilirsiniz. <br/>

Dosyanızın merge işlemine başlamadan önceki haline istediğiniz zaman geri dönebilirsiniz. Bunun için yapmanız gereken tek şey **git merge --abort** komutunu çalıştırmak.

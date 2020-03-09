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

44 - git stasht                  - Commitlemeden önce geçici kayıt altına almak istediğimizde kullanırız

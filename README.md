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

# planlamauygulamasi
1-> Programda en üstte bulunan 2 adet radioButton vardır. 
    Bunlar yeni bir planlamamı yapılacağını yoksa yapılmış bir planlamada güncelleme mi yapılacağını ayırt etmek için eklenmiştir.
2-> Yeni planlama seçili ise planlama yapacak kişi adını soyadını girecektir. Açıklama kısmına diğer kullanıcılara iletmek istediği mesajı yazabilir. 
    Ardından sol tarafta bulunan takvimden en az bir tane tarih seçilmiş olmalıdır.
3-> Bu şekilde yapılan planlama için Kaydet ve Gönder tuşuna basılmalı ve dosya locale kaydedilip sunucuya gönderilmelidir. 
    Kayıt işlemi başarılı ise dosya adı panoya otomatik kopyalanmaktadır.
	Kopyalanan dosya adı anlık mesajlaşma uygulamaları veya mail yoluyla güncellenmesi istenilen kişilerle paylaşılabilir.
4-> Bu Kayıt işleminde bir json dosyası oluşturulup içerisine;
    Oluşturan Kişinin adı ve Oluşturma Tarihi,
	Güncelleyen Kişinin adı ve Güncelleme Tarihi (Bu kısım ilk oluştuma için Oluşturma bilgileri ile aynıdır)
	Oluşturma dahil kaç kere güncellediği bilgisi
	Planlama için gerçeli tarhilerin bulunduğu bilgiler koyulmuştur.
5-> Dosya adını alan kişiler 2. seçenek olan Planlama Al radioButtonu seçerek açılan textbox a dosya adını yazıp dosyanın indilip okunmasını sağlayabilir.
6-> Dosya okunduğunda açıklama kısmı ve planlamada kullanılan gerçeli tarihler ekrana yansımaktadır.
7-> Güncelleyen kişi adını Ad soyad kısmına girerek son güncelleyen kişi olarak dosyaya kendini kaydettirir.
8-> Açıklama kısmına da her güncelleyen kendi ismini ekleyerek güncelleyenlerin listesi oluşturulabilir.
9-> Dosya açıldığında Kaydet ve Gönder butonu üzerindeki Labellara Oluşturma ve Güncelleme bilgileride yansıtılmaktadır.
10-> Dosya sunucuya FTP bağlantısı ile gönderilmektedir. Aynı zamanda güncelleme esnasında sunucudaki dosya FTP bağlantısı ile silinmekte ve güncellenmiş dosya sunucuya gönderilir.
     Dosya için tüm oluşturma, indirme ve güncelleme işlemleri FTP bağlantısı ile yapılır.
11-> Dosyada en son planlamadaki ilk tarihe kadar ilk tarih dahil değişklik yapılabilir aksi halde değişikliğiğe izin verilmez.
12-> Sunucu ücretsiz olarak hizmet veren bir siteden alınmıştır. Herhangi zararlı bir yazılım içermemektedir. Sunucu sadece dosyaların depolanması için kullanılmaktadır.
13-> Program Planlama yapma ve güncelleme işlemi için tek bir arayüz kullanılması programın daha efektif olmasını sağlamıştır.
14-> Planlamada en fazla 14 gün seçilebilir.
15-> Dosyalara oluşturma ve güncellme işlemi web üzerinden http://fuxien.wuaze.com/planlama.php  adresinden gerçekleştirilebilir.


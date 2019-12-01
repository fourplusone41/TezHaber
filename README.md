# TezHaber
Turkish News Aggregator &amp; Summarizer

## Hedefimiz

Projedeki amacımız çeşitli kaynaklarda bulunan aynı bilgileri bir araya toplayıp bunları özetleyerek zaman kaybı ve yanlış bilgi edinimini engellemeyi amaçladık. Örneğin haber kaynakları, twitterdaki konular, eğitim kaynakları gibi. Bu çalışmada amacımıza yönelik olarak haber kaynaklarından aynı haberi bahseden siteleri bir araya toparlayıp özetleme işlemi gerçekleştirdik. 

## Çalışma Mimarimiz

- Çeşitli haber kaynaklarının RSS lerinden haberler çekilerek, json dosyası oluşturuldu
- Oluşturulan json dosyasındaki haberler düzenlenmek üzere Zemberek işlemine sokuldu
- Zemberek ile düzenlenen metinler sınıflandırılarak aynı haberler tespit edildi
- Bulunan benzer haber metinlerindeki haberler özetlendi
- Web ve mobil arayüzünde sunuldu



## Faydalanılan Kaynaklar
### Ortamlar

	-VSCode, Android Studio
	-Python 3.8
	-Ubuntu Linux, Windows, MacOS

### Kütüphaneler


### Döküman ve Makaleler
* [http://zembereknlp.blogspot.com/](http://zembereknlp.blogspot.com/)
* [https://www.aclweb.org/anthology/W17-1003/](https://www.aclweb.org/anthology/W17-1003/)

### Repository
* [https://github.com/ozturkberkay/Zemberek-Python-Examples](https://github.com/ozturkberkay/Zemberek-Python-Examples)
* [https://github.com/gaetangate/text-summarizer/tree/master/text_summarizer](https://github.com/gaetangate/text-summarizer/tree/master/text_summarizer)
* [https://holwech.github.io/blog/Automatic-news-scraper/](https://holwech.github.io/blog/Automatic-news-scraper/)
[https://github.com/holwech/NewsScraper](https://github.com/holwech/NewsScraper)

# TezHaber
Türkçe Haber Toplayıcı ve Özetleyici | Turkish News Aggregator &amp; Summarizer

## Hedefimiz

Projedeki amacımız çeşitli kaynaklarda bulunan aynı bilgileri bir araya toplayıp bunları özetleyerek zaman kaybı ve yanlış bilgi edinimini engellemeyi amaçladık. Örneğin haber kaynakları, twitterdaki konular, eğitim kaynakları gibi. Bu çalışmada amacımıza yönelik olarak haber kaynaklarından aynı haberi bahseden siteleri bir araya toparlayıp özetleme işlemi gerçekleştirdik. 

## Çalışma Mimarimiz

- Çeşitli haber kaynaklarının RSS lerinden haberler çekilerek, json dosyası oluşturuldu
- Oluşturulan json dosyasındaki haberler düzenlenmek üzere Zemberek işlemine sokuldu
- Zemberek ile düzenlenen metinler sınıflandırılarak aynı haberler tespit edildi
- Bulunan benzer haber metinlerindeki haberler özetlendi
- Web ve mobil arayüzünde sunuldu



## Kullanım

	virtualenv -m python3 env
	source env/bin/activate
	pip install requirements.txt
	cd TezHaber-Core
	python main.py

### Kütüphaneler


### Referanslar

* Centroid-based Text Summarization through Compositionality of Word Embeddings
```
	@inproceedings{rossiello-etal-2017-centroid,
    title = "Centroid-based Text Summarization through Compositionality of Word Embeddings",
    author = "Rossiello, Gaetano  and
      Basile, Pierpaolo  and
      Semeraro, Giovanni",
    booktitle = "Proceedings of the {M}ulti{L}ing 2017 Workshop on Summarization and Summary Evaluation Across Source Types and Genres",
    month = apr,
    year = "2017",
    address = "Valencia, Spain",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W17-1003",
    doi = "10.18653/v1/W17-1003",
    pages = "12--21",
    abstract = "The textual similarity is a crucial aspect for many extractive text summarization methods. A bag-of-words 	  representation does not allow to grasp the semantic relationships between concepts when comparing strongly related sentences with no words in common. To overcome this issue, in this paper we propose a centroid-based method for text summarization that exploits the compositional capabilities of word embeddings. The evaluations on multi-document and multilingual datasets prove the effectiveness of the continuous vector representation of words compared to the bag-of-words model. Despite its simplicity, our method achieves good performance even in comparison to more complex deep learning models. Our method is unsupervised and it can be adopted in other summarization tasks.",
     }
```

* [Zemberek-Python-Examples](https://github.com/ozturkberkay/Zemberek-Python-Examples)
* [text-summarizer](https://github.com/gaetangate/text-summarizer)
* NewsScraper](https://github.com/holwech/NewsScraper)

## Lisanslar
GPL-3.0

### kullandığımız açık kaynak kodları
* [zemberek-nlp](https://github.com/ahmetaa/zemberek-nlp): Apache-2.0
* [text-summarizer9](https://github.com/gaetangate/text-summarizer): GPL-3.0
* [gensim](https://github.com/RaRe-Technologies/gensim): LGPL-2.1

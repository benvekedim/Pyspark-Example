## Pyspark-Example

### Kurulum:

[Anaconda'yı indirin](https://anaconda.com/ )

### Kurulumu doğru yaptığımızı kontrol etmek için
```
conda --version
```
### Versiyonu yazdırır veya hata veririr.Kurulumda bir hata vardır.


### Java kurulumunu yapmalıyız.Bunun için aşağıdaki kodu terminale yazıyoruz:

```
conda install openjdk
```

### Pyspark kurulumu yapalım:

```
conda install pyspark
```

### Jupyter Notebook'ta Pyspark'ı çalıştıracağımız için FindSpark'ı kurmalıyız.

```
conda install -c conda-forge findspark
```

#### Kurulumu yaparken biraz beklemeliyiz.

### Anaconda.Navigator'ı bilgisiyardan açmalıyız.Jupyter Notebook'ı açmak için Launch'a basıyoruz.

### localhost'a notebook açıldıktan sonra: New -> Python ile Python notebook oluşturuyoruz.

### Notebook'a şu kodları yazalım:

```
import findspark
findspark.init()
findspark.find()

```
### SparkSession oluşturup çalışmamıza başlayabiliriz.

#### Okuduğunuz için teşekkürler.





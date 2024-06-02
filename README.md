## Göreceli Bağlantılar

Okuyucuların depodaki diğer dosyalara geçiş yapmasına yardımcı olmak için oluşturulan dosyalarda göreceli bağlantılar ve görüntü yolları tanımlayabilirsiniz.

Bir göreceli bağlantı, mevcut dosyaya göre göreli olan bir bağlantıdır. Örneğin, depo kökünde bir README dosyanız varsa ve `docs/CONTRIBUTING.md` adında başka bir dosyanız varsa, README'deki CONTRIBUTING.md'ye göreceli bağlantı şöyle görünebilir:

[Proje için katkı kuralları](docs/CONTRIBUTING.md)

GitHub, göreceli bağlantınızı veya görüntü yolunuzu otomatik olarak, mevcut olduğunuz dal temel alarak dönüştürecektir, böylece bağlantı veya yol her zaman çalışır durumda olacaktır. Bağlantının yolu, mevcut dosyaya göre göreli olacaktır. `/` ile başlayan bağlantılar, depo köküne göre göreceli olacaktır. `./` ve `../` gibi tüm göreceli bağlantı operatörlerini kullanabilirsiniz.

Bağlantı metninizi tek bir satırda olmalıdır. Aşağıdaki örnek işe yaramayacaktır.

[Proje için katkı 
kuralları](docs/CONTRIBUTING.md)

Göreceli bağlantılar, depoyu klonlayan kullanıcılar için daha kolaydır. Mutlak bağlantılar, depoyu klonlarınca çalışmayabilir - bu nedenle, depo içindeki diğer dosyalara referans vermek için göreceli bağlantıları kullanmanızı öneririz.

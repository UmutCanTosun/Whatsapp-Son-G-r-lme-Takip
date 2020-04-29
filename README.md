# Whatsapp Son Görülme Takip
Python aracılığıyla Web Whatsapp üzerinden Whatsapp'ta seçilen kişinin istenen aralıklarda belirtilen zaman boyunca son görülmesini takip etmeye yarayan bir koddur.

# Gereksinimler
- Python3 ve versiyonlarının bilgisayarınzda yüklü olması gerekmektedir.
- Selenium kütüphanesinin yüklü olması gerekmektedir(Windows için cmd ye "pip install selenium" komutunu girmeniz, mac ve linux için shell e girip "pip3 install selenium" yazmanız yeterlidir.).
- ChromeDriverManager'ın yüklü olması gerekmektedir(Windows için cmd ye "pip install webdriver_manager" komutunu girmeniz, mac ve linux için shell e girip "pip3 install webdriver_manager" yazmanız yeterlidir.

# Bazı Önemli Noktalar
- Önce barkodu okutmanız, ardından takip etmek istedğiniz kişinin ismini sohbetlerde kayıtlı olduğu haliyle girmeniz gerekiyor.
- Bu kod, sohbetlerinizde olmayan kişileri göstermez.
- Kodun yazımında kullanılan pythondaki fonksiyonlardan kaynaklı saniye bazlı hatalar olabilir.
- Girdiğiniz takip süresi bitince otomatik olarak Web Whatsapp kapanacaktır. Eğer kapanmasını istemiyorsanız driver.close() satırını yorum haline getirin.


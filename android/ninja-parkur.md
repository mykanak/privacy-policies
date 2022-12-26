## Ninja Parkur: Gizlilik Politikası

Google Play Store'da yayınlanan Ninja Parkur oyununun gizlilik sözleşmesini görüntülemektesiniz.

Bu, Anahtar Fikir tarafından geliştirilen bir Android uygulamasıdır.

İmtiyaz sahibi (Mehmet Yasin Kanak) olarak, bu uygulamayı herhangi bir kişisel veri toplamak için programlamadığımı beyan ederim. Siz (kullanıcı) tarafından oluşturulan tüm veriler, yalnızca cihazınızda saklanır ve uygulamanın verilerini temizleyerek veya uygulamayı kaldırarak kolayca silinebilir. Bunun dışında tercihinize bağlı olarak kişiselleştirilmiş reklamlar görmeyi seçebilirsiniz. Bu reklamların gösteriminde kullanılmak üzere toplanan kişisel veriler, bizlerden bağımsız olarak reklam ağları tarafından işlenmektedir. Uygulamayı yüklediğinizde karşınıza ilk çıkan panelden kişiselleştirilmiş reklamlar özelliğini kullanmak isteyip istemediğinizi belirleyebilirsiniz.

### Uygulamada istenen izinlerin açıklaması

"AndroidManifest.xml" dosyasında istenen izinlerin listesi:

<br/>

| İzinler | Ne için gerekli? |
| :---: | --- |
| `android.permission.INTERNET` | Uygulamanın ağ soketleri oluşturmasına ve özel ağ protokolleri kullanmasına izin verir. Kısaca, uygulamadaki ağ işlevlerini gerçekleştirmek için gerekli izindir. |
| `com.android.vending.BILLING` | Google Play servisini kullanarak potansiyel uygulama İçi ödeme istekleri göndermek ve uygulama içi ödeme işlemlerini yönetmek için gerekli izindir. |
| `com.google.android.gms.permission.AD_ID` | Reklam kimliği, reklam izleme sınırı ayarlarını ve yönetimini içeren izin. |
| `android.permission.ACCESS_NETWORK_STATE` | Uygulamanın; hangi ağların mevcut olduğunu ve bağlı olduğu ağ bağlantıları hakkındaki bilgileri görüntülemesini sağlayan izin. |
| `android.permission.ACCESS_WIFI_STATE` | Uygulamanın; kablosuz ağın etkin olup olmadığı, bağlı Wi-Fi cihazlarının adı ve mevcut Wi-Fi ağı hakkındaki bilgilerin görüntülenmesini sağlayan izindir. |
| `android.permission.ACCESS_COARSE_LOCATION` | Uygulamanın yaklaşık konumunuzu belirlemesini sağlar. Bu konum, baz istasyonları ve Wi-Fi gibi ağ bazlı konumlama kaynaklarını kullanan konum hizmetleri tarafından türetilir. Uygulamanın bunları kullanabilmesi için bu konum servislerinin cihazınızda açık ve kullanılabilir olması gerekir. Uygulamalar bunu yaklaşık olarak nerede olduğunuzu belirlemek için kullanabilir. |
| `android.permission.WRITE_EXTERNAL_STORAGE` | Uygulamanın SD karta veri yazmasına izin verir. |
| `android.permission.READ_EXTERNAL_STORAGE` | Uygulamanın SD karttan veri okumasına izin verir. |

 <hr style="border:1px solid gray">

Bir güvenlik açığı bulursanız veya uygulamanın gizliliğinizi nasıl koruduğuyla ilgili herhangi bir sorunuz varsa, lütfen bana bir e-posta gönderin.

Saygılarımla,  
Mehmet Yasin Kanak  
Antalya, Türkiye

Mail: anahtarfikir@icloud.com

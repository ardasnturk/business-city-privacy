---
title: Gizlilik Politikası
lang: tr
---

[English](./)

# Gizlilik Politikası — Pocket Business City

**Son güncelleme:** 29 Ekim 2026

## Kısa özet

Pocket Business City'de üyelik ve reklam yoktur; oyunun kendisi tamamen
cihazında oynanır — çalışmak için bağlantıya ihtiyaç duymaz ve kayıtlı şirketin
ile şehirlerin telefonundan hiç çıkmaz.

Bununla birlikte oyun, kaç kişinin oynadığını, nereye kadar ilerlediğini ve
neyin bozuk olduğunu görebilmemiz için kullanım ve çökme bilgilerini bir Google
hizmeti olan Firebase'e gönderir. Ayrıca oyun dengesi ayarlarını Firebase'den
alır ve — yalnızca hatırlatmaları açtıysan — duyuru alabilir. Bu sayfa bunun tam
olarak ne anlama geldiğini anlatır.

Oyunun hiçbir yerinde kişisel adın, e-posta adresin, telefon numaran, kişilerin,
konumun, fotoğrafın veya ödeme yöntemin için bir alan yoktur. Seçtiğin şirket
adı gerçek adını istemez; yalnızca oyun içi bir etikettir.

## Cihazında kalanlar

Cihazının uygulamaya özel depolama alanına yazılır. Yalnızca bu uygulama
tarafından okunabilir, hiçbir yere yüklenmez, oyunu kaldırdığında birlikte
silinir.

| Ne                                                                                                             | Neden                                        |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| Kayıtlı şirketin ve şehir yolculukların — şirket adı, şehirler, para, işletmeler, çalışanlar, krediler ve saat | Oyunun kaldığın yerden devam etmesi için     |
| Tercihlerin — seçtiğin dil, bildirim izni, ses ve titreşim tercihi                                             | Oyunun senin ayarladığın gibi çalışması için |

**Sıralamaya katılmadıkça şirket adın cihazdan çıkmaz.** Oyunda kendi yazdığın
tek metin odur ve aşağıda anlatılan hiçbir gönderime bilerek dâhil edilmez —
tek istisnası, senin katılmayı seçmen gereken ve yayınlamadan önce adı sana
gösteren sıralamadır.

## Firebase'e gönderilenler

Firebase Google tarafından işletilir. Google bizim veri işleyicimizdir ve bu
bilgileri ülkenin dışındaki sunucularda işleyebilir. Google'ın bunları nasıl ele
aldığı [Firebase gizlilik
belgelerinde](https://firebase.google.com/support/privacy) ve [Google gizlilik
politikasında](https://policies.google.com/privacy) açıklanmıştır.

### Kullanım analitiği

Yirmi adlandırılmış olay, başka bir şey değil. Her biri oyun içindeki bir
eylemdir ve içlerindeki her değer oyunun kendi seçtiği bir tanımlayıcıdır —
işletme türü, tema, semt — asla senin yazdığın bir şey değil:

`city_created`, `city_restarted`, `business_built`, `business_sold`,
`upgrade_purchased`, `renovation_started`, `renovation_finished`, `level_up`,
`loan_taken`, `loan_repaid`, `task_resolved`, `disaster_struck`,
`theme_changed`, `live_event_applied`, `push_opened`, `leaderboard_joined`,
`leaderboard_left`, `leaderboard_viewed`, `tutorial_begin`, `tutorial_complete`.

Bunların yanında, sayıların tek tek oyuncular yerine gruplar hâlinde
okunabilmesi için nasıl oynadığına dair altı bilgi: seviyen, kabaca kaç
işletmen olduğu, seçtiğin tema, uygulama dilin, ödenmemiş kredin olup olmadığı
ve hangi sürüm denge ayarlarını aldığın.

Firebase ayrıca bizim seçmediğimiz standart bir küme toplar: uygulama-örneği
tanımlayıcısı, cihaz modelin ve işletim sistemi sürümün, uygulama sürümü,
uygulama dilin ve IP adresinden türetilen yaklaşık ülke bilgisi. Google IP
adresinin kendisini saklamaz. Bu tanımlayıcı yalnızca bu cihazdaki bu uygulamaya
özeldir; reklam kimliğin değildir ve oyun reklam kimliğini (IDFA / AAID) hiçbir
zaman okumaz.

### Çökme raporları

Oyun çöktüğünde Firebase Crashlytics; hata yığınını, o andaki cihaz durumunu ve
bir Crashlytics kurulum tanımlayıcısını, hangi durumun buna yol açtığını
anlayabilmemiz için yukarıdaki altı bilgiyle birlikte gönderir. Kayıt verisi ve
şirket adı eklenmez.

### Oyun dengesi ayarları

Oyun, açılışta ve öne her dönüşünde Firebase Remote Config'den ayarları ister —
bir etkinliğin ne kadar güçlü olduğu, afetlerin ne sıklıkta olduğu. İstek,
uygulama-örneği tanımlayıcısını ve hangi ayarları alman gerektiğine karar vermek
için kullanılan üç değeri taşır: uygulama dilin, seviyen ve kabaca kaç işletmen
olduğu.

**Bu, oynamak için hiçbir zaman gerekli değildir.** Her uzak ayar varsayılanı 1
olan bir çarpandır, oyun cihazda hâlihazırda ne varsa onu okur ve Firebase'e hiç
ulaşmayan bir cihaz, ulaşanla birebir aynı şekilde oynanır.

### Duyurular

Yalnızca Ayarlar'dan hatırlatmaları açtıysan. Firebase Cloud Messaging o zaman
bu kurulum için bir kayıt jetonu üretir ve seçtiğin dile ait bir konuya abone
eder; böylece kimsenin kimin hangi dili konuştuğunu tutan bir listesi olmadan
duyuru okuduğun dilde gönderilebilir. Hatırlatmaları kapatmak bunu durdurur.

### Sıralama

Yalnızca katılırsan; katılmak kendi ekranı olan ayrı bir adımdır. Aşağıdakilerin
hiçbiri sen onaylamadan olmaz ve o ana kadar hiçbir şey oluşturulmaz — hesap
yok, kayıt yok, istek yok.

Katılmak **anonim bir hesap** oluşturur: bu kurulum için rastgele bir
tanımlayıcı; e-posta, şifre veya profil yoktur. Uygulamayı kaldırınca kalmaz,
yani yeniden kurarsan listede baştan başlarsın.

Herkese açık olan tam olarak iki şeydir: **seçtiğin ad** ve **bu hafta ne
kazandığın**. Ekran adı şirketinkinden doldurur, çünkü onu zaten sen seçtin, ve
yayınlanmadan önce değiştirmene izin verir — yukarıdaki sözün "şirket adın, sen
katılmayı seçmedikçe cihazdan çıkmaz" olmasının sebebi budur. Şehrinle ilgili
başka hiçbir şey gönderilmez: kaydın da, işletmelerin de, bakiyen de.

İstediğin an Ayarlar'dan ayrılabilirsin; ayrılmak kaydını siler.

**Bildirme ve gizleme.** Başka bir oyuncunun adına dokunarak onu listenden
gizleyebilir veya bildirebilirsin. Gizleme cihazında kalır. Bildirim; bildirilen
adı, onun anonim tanımlayıcısını ve haftayı — listede zaten görünen bilgileri —
gönderir, seninle ilgili hiçbir şey göndermez; katılmadan çalışır ve hesap
oluşturmaz. Bildirimleri inceler, kurallara aykırı adları kaldırırız.

## Cihaz izinleri

| İzin                               | Ne zaman istenir                                                  | Ne için kullanılır                                                        |
| ---------------------------------- | ----------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Bildirimler (`POST_NOTIFICATIONS`) | Yalnızca Ayarlar'dan hatırlatmaları açtığında — ilk açılışta asla | İşletmelerinin ilgi beklediğini söyleyen yerel hatırlatmalar ve duyurular |
| Titreşim (`VIBRATE`)               | Sorulmaz; Android otomatik verir                                  | Ayarlar'dan kapatabileceğin kısa dokunsal geri bildirim                   |

Bildirim iznini reddetmen veya geri alman oyunun geri kalanını etkilemez.

## Oyunun hâlâ yapmadıkları

- **Sıralamaya katılmadıkça üyelik veya giriş yok** — o da anonimdir; kaydolunacak
  ve giriş yapılacak bir şey yoktur.
- **Reklam ve reklam kimliği yok.** Oyun reklam kimliğini okumaz, reklamverenler
  veya veri simsarlarıyla hiçbir şey paylaşmaz.
- **Satın alma yok.** Uygulama içi satın alma ve ödeme işleme yoktur.
- **Veri satışı veya paylaşımı yok.** Toplananların hiçbiri satılmaz ve yukarıda
  anlatılan işleyici sıfatıyla Google dışında kimseyle paylaşılmaz.
- **Bağlantıya bağlı oynanış yok.** Simülasyon, ekonomi ve kaydın tamamen
  yereldir. Uçak modu oyunla ilgili hiçbir şeyi değiştirmez.

## Çocuklar

Oyun her yaşa uygundur ve 13 yaş altına yönelik değildir. Çocuklar dâhil hiç
kimseden kişisel bilgi toplamaz: gönderdiği hiçbir şey bir kişiyi tanımlamaz ve
tanımlayabilecek bir şey girmenin yolu yoktur.

## Saklama süresi

Analitik verisi, Firebase konsolumuzda ayarlanan saklama süresi boyunca tutulur
ve sonrasında otomatik olarak silinir; Google'ın sunduğu seçenekler 2 ay ve 14
aydır. Çökme raporları 90 gün tutulur.

## Haklarınız ve seçenekleriniz

Toplananların hiçbiri seni tanımlamaz, dolayısıyla erişilecek, düzeltilecek veya
dışa aktarılacak bir hesap yoktur. Yapabileceklerin:

1. **Hatırlatmaları kapat** — duyuruları durdurur ve mesajlaşma jetonunu kaldırır.
2. **Kaydını sil** — Ayarlar → Kaydı sil, oyunun cihazında tuttuğu her şeyi siler.
3. **Uygulamayı kaldır** — depolamasını kaldırır ve tüm toplamayı durdurur.
4. **Bize yaz** — bu politikayla ilgili her soru için aşağıdaki adres.

Erişim veya silme talebi hakkında: toplananlarda ad, hesap veya iletişim bilgisi
yoktur, bu yüzden çoğu durumda "senin" diye ayırabileceğimiz bir şey bulunmaz.
Uygulamayı kaldırmak tüm toplamayı durdurur ve gönderilmiş olanlar yukarıdaki
süreler içinde kendiliğinden silinir. Yine de sormak istersen yaz — ne bulup ne
bulamadığımızı dürüstçe söyleriz.

AB veya Birleşik Krallık'taysan: yukarıda anlatılan analitik ve çökme
raporlamasının hukuki dayanağı meşru menfaattir — oyunun nasıl kullanıldığını
anlamak ve bozulanı düzeltmek — ve bunların hiçbiri senin profilini çıkarmak
veya reklam hedeflemek için kullanılmaz.

## Bu politikadaki değişiklikler

Yeni bir şey toplayan her oyun sürümünde bu belge, o sürüm yayımlanmadan önce
güncellenir ve değişiklik uygulamanın sürüm notlarında anlatılır.

## İletişim

Bu politikayla ilgili sorular: **ardasnturk@gmail.com**

# IK Web Projesi

Bu proje, şirketlerin insan kaynakları süreçlerini dijitalleştirmek ve verimliliği artırmak amacıyla geliştirilmiş entegre bir insan kaynakları yönetim platformudur. Kullanıcı dostu tasarımı, detaylı veri yönetimi, dinamik filtreleme seçenekleri ve otomatik süreçleriyle, personel yönetiminden izin ve görevlendirme takibine kadar geniş bir yelpazede ihtiyaçlara çözüm sunar.


## Projenin Temel Özellikleri
- **Personel Kartları Yönetimi:** Tüm personellere ait özlük bilgilerinin güvenli ve kolay yönetimi.
- **Dinamik Filtreleme:** Kullanıcıların çeşitli kriterlere göre personel verilerine erişimini sağlayan güçlü bir filtreleme sistemi.
- **İzin ve Yardım Yönetimi:** Alacak izinlerin, gıda yardımlarının ve yıllık izinlerin kolayca takibi ve yönetimi.
- **Otomatik Süreçler:** Yıllık izin hak edişlerinin gece yarısı otomatik olarak hesaplanması ve güncellenmesi.
- **Dashboard Raporlama:** Cinsiyet ve eğitim durumu dağılım grafikleri, eksik gün raporları ve izin durumlarının görselleştirilmesi.
- **İki Aşamalı İzin Onayı:** İnsan Kaynakları ve Genel Müdür onayıyla iki aşamalı kontrol süreçleri.
- **Eksik Gün Takibi:** Eksik günlerin kolay takibi ve raporlanması. 
- **Görevlendirme Yönetimi:** Personellerin şube ve ünvan değişiklikleri için nakil tarihi bilgileriyle birlikte geçmiş görevlendirmelerin takibi ve raporlanması. 

Bu proje, insan kaynakları süreçlerini daha verimli, şeffaf ve kullanıcı dostu hale getirerek işletmelere önemli ölçüde zaman kazandırır ve süreçleri sadeleştirir.

## Dashboard

Projenin merkezi yönetim ekranı olan **Dashboard**, insan kaynakları süreçlerini kolayca takip ve analiz etmek için tasarlanmıştır. Kullanıcı dostu arayüzü ile şirket personel verileri, izin durumları, eksik gün raporları ve diğer önemli metrikler görselleştirilmiştir. 

### Özellikler

- **Genel Veriler:**
  Dashboard'un üst kısmında, şirketin personel yapısını temsil eden özet bilgiler yer alır:
  - Aktif Personel Sayısı
  - Şube Sayısı
  - Ünvan Sayısı
  - Maaş Gideri
  - Gıda Yardım Maliyeti

- **Kümülatif Raporlar:**
  - Onay bekleyen ve tamamlanan raporlar, kullanıcıya hızlı bir şekilde sunulur. Bu sayede, geciken veya işlem yapılması gereken durumlar anında fark edilir.
  - Personel ilgili seneye ait yıllık izinlerini sıfırlaması halinde bu alana bildirim düşmektedir.

- **Eksik Gün ve Yaklaşan İzinler:**
  - Eksik gün raporlarının detaylı takibi ve yaklaşan izin bildirimleri, kullanıcıya hızlı erişim sağlar.
  - Önemli tarihler ve hatırlatmalar ile süreçlerin aksaması önlenir.
- **Yaklaşan Doğum Günleri:**
  - Dashboard'da yer alan **Yaklaşan Doğum Günleri** bölümü, çalışanların doğum günlerini takip etmeyi kolaylaştırır. Tarih ve gün bazlı hatırlatmalar sunarak hiçbir doğum gününün unutulmamasını sağlar ve çalışan memnuniyetini artırır.

- **İş Gücü Verileri**
  - **İş Gücü Verileri** bölümü, SSK ve benzeri kurumların belirli aralıklarla talep ettiği çalışan sayısı, işe alım ve işten ayrılma bilgilerini düzenli bir şekilde sunar. Bu yapı, raporlama süreçlerini hızlandırır ve eksiksiz veri akışı sağlar.


- **Cinsiyet ve Eğitim Durumu Dağılımı:**
  Dashboard’da görsel olarak sunulan iki grafik, personel cinsiyet oranlarını ve eğitim durumu yüzdeliklerini analiz etmeyi kolaylaştırır. 
  - **Cinsiyet Dağılımı Grafiği:** Şirketin cinsiyet dengesini gösterir.
  - **Eğitim Durumu Grafiği:** Çalışanların eğitim seviyelerine göre yüzdelik dağılımlarını sunar.

### Görseller

#### Genel Dashboard Görünümü - Görsel
![dashboard1](https://github.com/user-attachments/assets/f38499bb-5ca7-4659-861f-beb2f771ade3)


#### Grafikler ve Detaylı Bilgiler - Görsel
![dashboard2](https://github.com/user-attachments/assets/f704b503-22f0-4207-93ce-14be4f86cd5b)


---

Bu Dashboard, tüm şirket verilerinin tek bir yerden yönetilmesini ve analiz edilmesini sağlar. İnsan kaynakları uzmanları, raporlar ve hatırlatmalarla operasyonel süreçleri daha verimli bir şekilde yönetebilir.

## Personeller

**Personeller** bölümü, şirket çalışanlarının yönetimini kolaylaştırmak için iki ana kısımdan oluşur: **Aktif Personeller** ve **Çıkarılan Personeller**. Bu bölümler, personel bilgilerini listeleme ve yönetme işlemlerini hızlı ve etkili bir şekilde gerçekleştirmenizi sağlar.

### Özellikler

1. **Personel Listeleri:**
   - **Aktif Personeller:** Şirket bünyesinde hâlâ aktif olarak çalışan personellerin listesini içerir.
   - **Çıkarılan Personeller:** İşten ayrılmış ya da çıkarılmış personellerin kaydını içerir.
   - Her iki liste de kullanıcı tarafından kolayca görüntülenebilir ve detaylı filtreleme seçenekleri ile aranabilir.

2. **Excel İndirme:**
   - Her iki listede de, personel bilgileri **Excel formatında** indirilebilir. Bu özellik, kullanıcıların verileri hızlı bir şekilde dışa aktarmasına ve raporlama süreçlerini hızlandırmasına olanak tanır.

3. **Personel Ekleme (Yalnızca Aktif Personeller):**
   - Aktif personel listesinde, yeni personel ekleme işlemi iki aşamalı bir süreçle gerçekleştirilir:
     1. **Zorunlu Alanlar:** İlk aşamada, personelin temel bilgileri (ad, soyad, TC kimlik numarası, doğum tarihi, işe giriş tarihi gibi) alınır. Bu alanlar, kaydın tamamlanması için gereklidir.
     2. **İsteğe Bağlı Alanlar:** İkinci aşamada, adres, telefon numarası, eğitim durumu gibi isteğe bağlı bilgiler girilebilir. Bu bilgiler, personel yönetim sürecini daha detaylı hale getirmek için kullanılabilir.

   - **Emeklilik Durumu:** Eğer personelin emekli olduğu belirtilirse, yıllık izin hesaplamalarının buna uygun şekilde düzenlenmesi için bir seçim alanı sunulur. Bu seçim yapıldığında, yıllık izinler **20 gün üzerinden** yenilenir.

   - **Geçmişe Dönük İşe Giriş:** İşe giriş tarihi olarak geçmiş bir tarih girildiğinde (örneğin 10 yıl önce), sistem bu tarihe göre gerekli hesaplamaları yapar ve personelin kümülatif tablolarını otomatik olarak oluşturur.


### Görseller ve Video

#### Aktif Personeller Listesi - Görsel
![personeller](https://github.com/user-attachments/assets/0fdb8c89-d4b8-47d8-bbeb-8cdd261e9c74)


#### Çıkarılan Personeller Listesi - Görsel
![çıkarılan personeller liste](https://github.com/user-attachments/assets/9ede9d7e-54f7-4863-8b49-9b2cd8acbf5c)

#### Personel Ekleme - Video

https://github.com/user-attachments/assets/d2d7c729-63fe-4cad-bd3e-5e3d3e7b0b71


---

Bu alanlar, personel yönetimi süreçlerini optimize etmek için tasarlanmıştır ve kullanıcı dostu bir deneyim sunar.

## Personel Kartları

**Personel Kartları**, her bir çalışan için detaylı veri yönetimi sağlayan kapsamlı bir modüldür. Bu alan, personel bilgilerinin düzenlenmesi ve takibi için kullanıcı dostu ve işlevsel bir tasarıma sahiptir. Modül, altı temel bölümden oluşmaktadır: **Personel Detayları**, **İzinler**, **Eksik Gün**, **Görevlendirmeler**, **İşten Çıkarma** ve **İşe Geri Alma**.

### 1. Personel Detayları

**Personel Detayları** bölümü, personelin temel ve detaylı bilgilerinin yönetildiği, kullanıcıların ilk karşılaştığı ekrandır. Bu ekran, sezgisel bir tasarım ve kapsamlı bir bilgi yapısı sunar.

#### Üst Bilgi Alanı
Personelin özet bilgileri, ekranın üst bölümünde yer alır ve aşağıdaki verileri içerir:
- **Alacak İzin Sayısı:** Personele tanımlı olan alacak izinlerin sayısı (Alacak izinler sistem üzerinde saat bazlı tutulmaktadır. Bu alanda 8 saatlik bir alacak izin 1 güne tekabül etmektedir.).
- **Gıda Yardımı Miktarı:** Personele sağlanan gıda yardımı tutarı.
- **Hak Edilen Toplam Yıllık İzin Miktarı:** Personele ait toplam hak edilen yıllık izin gün sayısı.
- **Kullanılan Toplam Yıllık İzin Miktarı:** Personele ait toplam kullanılan izin toplamı.
- **Kalan Yıllık İzin Miktarı:** Güncel olarak kullanılabilir yıllık izin sayısı.
- **Kalan Yıllık İzin Detay Butonu:** Kalan izin miktarının hemen yanında bulunan **Detay** butonuna tıklanıldığında yıllara göre kalan yıllık izin miktarlarını listeleyen bir açılır pencere (tooltip) sunar. Bu özellik, geçmişe dönük yıllık izin yönetimini daha pratik hale getirir.

#### Sekme Yapısı
Personel Detayları ekranının devamında, bilgilerin düzenlenmesi için bir **Sekme** yapısı bulunmaktadır. Her sekme, farklı bir bilgi grubunu temsil eder:

1. **Kişisel Bilgiler:**  
   Personel ekleme sürecinde alınan zorunlu bilgilerin görüntülendiği ve düzenlenebildiği alan. Bu bölüm, temel bilgilerin hızlıca erişilebilmesini sağlar.

2. **Diğer Bilgiler:**  
   Personel ekleme sürecinde alınan isteğe bağlı bilgilerin yer aldığı sekme. Burada adres, iletişim bilgileri ve eğitim durumu gibi detaylar yönetilebilir.

3. **Yıllık İzin Kümülatif Bilgileri:**  
   Bu sekme, personelin her yıl için hak ettiği ve kalan yıllık izinlerinin ayrıntılı bir listesini sunar. Bölümün detayları:
   - **Yıllık İzin Bilgileri:** Hak edilen ve kalan yıllık izinler için düzenlenebilir input alanları.
   - **Kontrol Alanları:**
     - **"İzin Föyü İmzalandı mı?" Checkbox:** Bu alan, personelin ilgili yıldaki tüm yıllık izinlerini tüketmesi durumunda, izin föyü imzalama sürecinin yönetilmesini kolaylaştırır. İnsan kaynaklarının bu süreci takip etmesini sağlamak amacıyla bir checkbox üzerinden kontrol edilir.

     - **"Bildirim Açık mı?" Checkbox:** Bu checkbox, izin föyü ile ilgili bir hatırlatma sistemini tetikler. Personelin belirli bir yıla ait tüm yıllık izinlerini sıfırlaması durumunda, sistem bu alanı otomatik olarak işaretler ve dashboard ekranına ilgili kümülatif raporun detaylarını ekler. Böylece insan kaynaklarına, ilgili yıl için izin föyü imzalatılması gerektiği hatırlatılır.

     - **Erken Tarihli Yıllık İzin Tanımlama:**  
  Bu özellik, henüz yıllık izin hak ediş tarihi gelmeyen personeller için esnek bir çözüm sunar. Normal şartlarda, bulunduğumuz yıl için personelin yıllık izin yenilenme tarihi gelmediyse burada ilgili yıla ait bir kümülatif alanı bulunmamaktadır.Bu alan aracılığıyla isteğe bağlı manuel izin tanımlanabilir. Böylece, yıl içerisinde acil ihtiyaçlar doğrultusunda esneklik sağlanır. Manuel olarak tanımlanan yıllık izinler, sistemin otomatik izin yenileme süreçlerinden muaf tutulur böylece personele fazladan yıllık izin verilmesinin önüne geçilir.
 
      

4. **Yıllık İzin, Alacak İzin ve Gıda Yardımı Ayarları:**  
   - Personele alacak izin ekleme veya çıkarma işlemleri.  
   - Gıda yardım miktarı ve yenilenme tarihinin düzenlenmesi.  
   - Yıllık izin yenilenirken, emeklilik durumuna göre yenilenmesi istendiği takdirde bu seçeneğin açılması ile kontrol sağlanabilir. (Bu seçenek seçilmesi halinde personelin yıllık izinleri sabit olarak 20 günden yenilenecektir.)

#### Personel Silme Alanı
Sayfanın en alt kısmında, ilgili personel kaydının sistemden kaldırılmasını sağlayan bir **Personel Silme** butonu bulunmaktadır. Bu işlem, yetkilendirme gereklilikleri ile kontrol edilir.

### Personel Detayları - Video

https://github.com/user-attachments/assets/5d7a8fca-8be8-4bf8-aa5e-636f3401cf66

### 2. Personel Ait İzinler
**Personele Ait İzinler** bölümü, ilgili personelin geçmişte almış olduğu tüm onaylanmış izinlerin detaylı bir listesini sunar. Bu liste, izin yönetimi ve raporlama süreçlerini kolaylaştırmak için kullanıcı dostu bir yapıda tasarlanmıştır.

#### Özellikler

1. **Onaylanan Tüm İzinlerin Listesi:**  
   Personele ait tüm geçmiş izinler, liste halinde sunulur. Bu liste, detaylı bilgilere kolayca erişim sağlar.

2. **Excel Dışa Aktarma:**  
   Kullanıcılar, ihtiyaç duyduklarında izin listesini **Excel formatında** dışa aktarabilir. Bu özellik, raporlama ve arşivleme süreçlerini hızlandırır.

3. **Sayfalama:**  
   Çok sayıda izin kaydının düzenli bir şekilde görüntülenmesi için liste, sayfalama yapısı ile tutulur.

4. **İzin Satırı Detayları:**  
   Her bir izin satırı, aşağıdaki bilgileri içerir:
   - **PDF Butonu:** İzin belgesini PDF formatında görüntüleme ve indirme seçeneği.
   - **Başlangıç ve Bitiş Tarihleri:** İznin başladığı ve sona erdiği tarih bilgisi.
   - **Toplam İzin Gün Sayısı:** İzin süresinin toplam gün olarak gösterimi.
   - **İzin Açıklaması:** İznin amacı veya detaylarını belirten açıklama alanı.
   - **Detaylı İzin Alanı:** 
     - Bir buton üzerinden erişilir ve hover yapıldığında iznin hangi izin türünden kaç gün verildiği bilgisi gösterilir.
   - **Onaylanma Tarihi:** İznin onaylandığı tarih bilgisi.
   - **Güncelle ve İptal Et Butonları:** Kullanıcı, izin kaydını düzenleyebilir veya iptal edebilir.

### Personele Ait İzinler - Görsel

![personelDetay İzinler](https://github.com/user-attachments/assets/039ae511-5913-4fc6-a48c-58f633e70397)

### 3. Personel Kartı Eksik Gün
**Personel Kartı Eksik Gün** bölümü, personelin işe gelmediği veya eksik çalıştığı günlerin detaylı bir şekilde yönetildiği alandır. Bu alan, hem geçmiş kayıtlara erişim sağlar hem de eksik gün ekleme ve silme işlemlerini kolaylaştırır.

#### Özellikler

1. **Eksik Gün Listesi:**  
   - Personelin geçmiş eksik gün kayıtları listelenir.
   - Liste, **Tarih Bazlı Filtreleme** özelliği ile belirli yıl veya ay seçimine göre daraltılabilir.
   - Tüm eksik gün kayıtları sayfalama yapısı ile düzenlenmiştir.

2. **Eksik Gün Verileri:**  
   Her bir eksik gün kaydı aşağıdaki bilgileri içerir:
   - **Adı Soyadı ve TC Kimlik:** Personelin kimlik bilgileri.
   - **Şube:** Eksik günün bağlı olduğu çalışma alanı.
   - **İzin Başlangıç ve Bitiş Tarihleri:** Eksik günün başlangıç ve bitiş tarihleri.
   - **İşe Başlama Tarihi:** Personelin eksik gün sonrası işe başladığı tarih.
   - **Sebep:** Eksik günün nedeni (örn. İstirahat).
   - **Oluşturulma Tarihi:** Eksik gün kaydının sisteme eklendiği tarih.

3. **Eksik Gün Ekleme ve Silme:**  
   - **Eksik Gün Ekle Butonu:** Yeni bir eksik gün kaydı eklemek için kullanılır.
   - **Sil Butonu:** Mevcut bir eksik gün kaydını kaldırmak için her kayıt satırında yer alır.

4. **Excel Dışa Aktarma:**  
   Eksik gün listesi, Excel formatında dışa aktarılabilir. Bu, raporlama süreçlerini hızlandırır ve eksik gün verilerinin arşivlenmesini kolaylaştırır.

### Personel Kartı Eksik Gün - Görsel

![personel detay eksik gün](https://github.com/user-attachments/assets/ade6b3cb-7c1f-4f94-bf63-6a50ec086359)

### 4. Personel Kartı Görevlendirmeler

**Görevlendirmeler** bölümü, personelin geçmişteki şube veya unvan değişikliklerinin detaylı bir şekilde listelendiği ve yönetildiği bir alandır. Bu bölüm, nakil işlemleri ve görevlendirme süreçlerinin kayıt altına alınmasını ve takibini kolaylaştırır.

#### Özellikler

1. **Görevlendirme Listesi:**  
   - Personelin daha önce gerçekleşmiş tüm nakil ve görevlendirme işlemleri listelenir.
   - Liste, belirli bir yıl veya aya göre daraltılabilir ve **Filtreleme** özelliği ile kullanıcıya esneklik sağlar.

2. **Görevlendirme Verileri:**  
   Her bir görevlendirme kaydı aşağıdaki bilgileri içerir:
   - **Adı Soyadı:** Görevlendirilen personelin adı ve soyadı.
   - **Eski Şube ve Yeni Şube:** Personelin nakil edildiği şube bilgileri.
   - **Eski Ünvan ve Yeni Ünvan:** Personelin önceki ve yeni unvan bilgileri.
   - **Nakil Tarihi:** Görevlendirme işleminin gerçekleştiği tarih bilgisi.

3. **Görevlendirme Yönetimi:**  
   - **Sil Butonu:** Kullanıcı, gereklilik durumunda bir görevlendirme kaydını sistemden kaldırabilir.

4. **Excel Dışa Aktarma:**  
   Görevlendirme listesi, Excel formatında dışa aktarılabilir. Bu özellik, görevlendirme kayıtlarının arşivlenmesini ve raporlanmasını kolaylaştırır.

### Personel Kartı Görevlendirmeler - Görsel

![personel detay görevlendirmeler](https://github.com/user-attachments/assets/048daf69-0464-4909-b41b-118c532a50ba)

### 5. Personel İşten Çıkarma
**Personel İşten Çıkarma** bölümü, bir personelin işten ayrılış sürecinin yönetildiği ve sistemde kayıt altına alındığı alandır. Bu alan, kullanıcı dostu bir modal penceresi ile işten çıkarma işlemini kolay ve hızlı bir şekilde gerçekleştirmenizi sağlar.
#### Özellikler
- İşten çıkar butonuna tıklandıktan sonra bir modal(popup) penceresi açılır ve burada kullanıcıdan personelin işten çıkış tarihi girilmesi istenmektedir.
- Personel işten çıkarılır ise personelin durumu aktiften pasif hale alınır ve çıkarılan personeller sekmesine taşınır böylece yönetilebilirlik sağlanmıştır.

### Personel İşten Çıkarma - Görsel

![personel detay işten çıkarma modal](https://github.com/user-attachments/assets/b3f87398-da89-4ab5-a1c9-db37121514a2)

### 6. Personel Geri İşe Alma
**Personel Geri İşe Alma**, işten çıkarılmış bir personelin tekrar aktif personel listesine eklenmesini sağlayan bir işlemdir. İnsan kaynakları kullanıcıları, bu özellik sayesinde personelin geçmiş kayıtlarına bağlı olarak yeni bir giriş oluşturabilir.

#### Özellikler

1. **İşe Geri Alma Butonu:**  
   - İşten çıkarılan personeller için bir **"İşe Geri Al"** butonu bulunur.
   - Bu butona tıklandığında bir modal açılır ve geri alma işlemi bu modal üzerinden gerçekleştirilir.

2. **Modal İçeriği:**  
   Modal üzerinde, personelin geri işe alınması için gerekli bilgiler ve tercihler yer alır:
   - **İşe Giriş Tarihi:** Personelin yeni işe giriş tarih bilgisi zorunlu olarak alınır.
   - **Checkbox Seçenekleri:** 
     - **Yıllık İzin Sayılarını Koru:** İşaretlenirse, personelin önceki kartındaki hak edilen, kullanılan ve kalan yıllık izin sayıları korunarak yeni karta aktarılır.
     - **Alacak İzin Sayısını Koru:** İşaretlenirse, önceki karttaki alacak izin miktarı yeni karta taşınır.
     - **Gıda Yardım Miktarını Koru:** İşaretlenirse, personelin önceki karttaki gıda yardım miktarı korunarak yeni karta eklenir.
   - **Gıda Yardım Yenilenme Tarihi:**  
     - İsteğe bağlı bir alan olarak yer alır. Eğer bu alan boş bırakılırsa, gıda yardımı yenilenme tarihi, işe giriş tarihi baz alınarak otomatik işlenir.

3. **İşlem Sonucu:**  
   - Personel geri işe alındığında, eski kartın bir kopyası oluşturulur ve aktif personel listesine eklenir. Bu işlem, checkbox seçimlerine göre ilgili verilerin yeni karta taşınmasıyla tamamlanır.

### Personel Geri İşe Alma - Video

https://github.com/user-attachments/assets/77d1b792-4421-486f-9c94-a5ba8028b6ef

---

Bu yapı, personel yönetiminde ihtiyaç duyulan tüm süreçleri kapsamlı bir şekilde karşılar. Kullanıcı dostu tasarımı ve esnek düzenleme seçenekleri ile operasyonel süreçlerin hızlandırılmasını ve kolaylaştırılmasını sağlar.

## Şubeler

**Şubeler** bölümü, tüm şubelerin detaylı bir şekilde yönetildiği alandır. Bu bölüm, şubelerin eklenmesi, düzenlenmesi ve gerektiğinde silinmesi gibi işlemleri kolaylaştırır. Ayrıca şube listesi, sayfalama yapısıyla düzenlenmiş ve kullanıcı dostu bir şekilde sunulmuştur.

### Özellikler

1. **Şube Listesi:**  
   - Tüm şubeler sayfa yapısıyla listelenir. Şubelerin adları, durumları, oluşturulma ve güncellenme tarihleri gibi detaylar görüntülenir.

2. **Excel Dışa Aktarma:**  
   - Şube listesi, ihtiyaç duyulduğunda **Excel formatında** dışa aktarılabilir. Bu özellik, raporlama süreçlerini kolaylaştırır.

3. **Yeni Şube Ekleme:**  
   - Kullanıcılar, **Şube Ekle** butonunu kullanarak sisteme yeni bir şube ekleyebilir.

4. **Şube Güncelleme ve Silme:**  
   - **Düzenle Butonu:** Var olan bir şube üzerinde değişiklik yapmayı sağlar.
   - **Sil Butonu:** Şubeyi sistemden kaldırır. Ancak:
     - Eğer şube ile ilişkilendirilmiş aktif personeller varsa, sistem bu şubenin silinmesine izin vermez.
     - Öncelikle şubede bulunan personellerin görev yerlerinin değiştirilmesi gerektiği belirtilir.

5. **Toplam Şube Sayısı:**  
   - Listenin üst kısmında, toplam şube sayısını özetleyen bir alan bulunur. Bu, kullanıcıya hızlı bir genel bakış sağlar.

### Şubeler - Görsel

![şube](https://github.com/user-attachments/assets/9da7e14a-930a-4d3c-a586-6cf036efa405)

---

Bu özellikler, şubelerin etkili bir şekilde yönetilmesini ve operasyonel süreçlerin düzenli bir şekilde yürütülmesini sağlar. Kullanıcılar, şube ekleme, düzenleme ve silme işlemlerini basit ve güvenilir bir şekilde gerçekleştirebilir.

## Ünvanlar

**Ünvanlar** bölümü, sistemdeki tüm personel unvanlarının yönetildiği bir alandır. Bu bölüm, unvan ekleme, düzenleme ve silme işlemlerinin kolayca gerçekleştirilmesini sağlar. Ayrıca, tüm unvanlar kullanıcı dostu bir sayfalama yapısı ile listelenmiştir.

### Özellikler

1. **Unvan Listesi:**  
   - Tüm unvanlar sayfa yapısıyla düzenlenmiş bir şekilde listelenir. Her unvanın adı, durumu, oluşturulma ve güncellenme tarihleri görüntülenir.

2. **Excel Dışa Aktarma:**  
   - Unvan listesi, **Excel formatında** dışa aktarılabilir. Bu özellik, raporlama ve veri analizi süreçlerini hızlandırır.

3. **Yeni Unvan Ekleme:**  
   - Kullanıcılar, **Unvan Ekle** butonunu kullanarak sisteme yeni bir unvan ekleyebilir.

4. **Unvan Güncelleme ve Silme:**  
   - **Düzenle Butonu:** Mevcut bir unvanın bilgilerinde değişiklik yapmayı sağlar.
   - **Sil Butonu:** İlgili unvanı sistemden kaldırmayı sağlar.

5. **Toplam Unvan Sayısı:**  
   - Listenin üst kısmında, toplam unvan sayısını özetleyen bir alan yer alır. Bu, kullanıcıya genel bir bakış sunar.

### Ünvanlar - Görsel

![ünvan](https://github.com/user-attachments/assets/2b47817e-29b1-4fb2-9cba-0fc207cf3d55)

---

Bu özellikler, unvan yönetiminde ihtiyaç duyulan tüm işlemleri hızlı ve etkili bir şekilde gerçekleştirmenize olanak tanır.

## İzinler

### 1. Bekleyen İzinler

**Bekleyen İzinler**, şube sorumlularının oluşturduğu izin taleplerinin insan kaynakları ve genel müdürler tarafından değerlendirilip onaylandığı veya reddedildiği bölümdür. Bu bölüm, izin taleplerinin düzenli bir şekilde yönetilmesi için kullanıcı dostu bir yapı sunar.

#### İşleyiş

1. **İzin Talebi Oluşturma:**  
   - Şube sorumluları tarafından oluşturulan izin talepleri, ilk olarak insan kaynaklarının **Bekleyen İzinler** listesine düşer.
   - Bu işlemden sonra insan kaynakları personellerine bilgilendirme maili gönderilir.

2. **İnsan Kaynakları Onayı:**  
   İnsan kaynakları, izin talebini inceledikten sonra:
   - **Onayla Butonu:** İzin talebini onaylayarak genel müdür onayı aşamasına taşır ardından personele bağlı olan genel müdüre bilgilendirme maili gönderilir.
   - **Reddet Butonu:** İzin talebini reddeder ve bu talep **Reddedilen İzinler** listesine kaydedilir.

3. **Düzenleme:**  
   Şube sorumluları tarafından yanlış oluşturulan talepler, insan kaynakları tarafından **Düzenle** butonu ile düzeltilebilir. Düzenleme sonrasında onay süreci devam ettirilir.

4. **Genel Müdür Onayı:**  
   Genel Müdür, izin talebini inceledikten sonra:
   - **Onayla Butonu:** İzin talebini onaylayarak izinin onaylanma süreci tamamlanmış olur ve izin **Onaylanan İzinler** sekmesine düşer.
   - **Reddet Butonu:** İzin talebini reddeder ve bu talep **Reddedilen İzinler** listesine kaydedilir.
---

#### Liste Özellikleri

**Bekleyen İzinler** listesinde her bir izin talebi için aşağıdaki detaylar görüntülenir:

- **Onayla ve Reddet Butonları:** Talebi onaylama veya reddetme işlemleri için kullanılır.
- **Adı Soyadı:** İzin talebinde bulunan personelin adı ve soyadı.
- **Şube ve Ünvan:** Personelin görev yaptığı şube ve ünvan bilgisi.
- **İzin Başlangıç ve Bitiş Tarihleri:** İzin talebinin planlanan tarih aralığı.
- **Toplam İzin Gün Sayısı:** İzin föyünde talep edilen toplam gün sayısı.
- **Detaylı Görüntüle Butonu:**  
  Buton üzerine gelindiğinde şu detaylar açılır:
  - Hangi izin türünden kaç gün talep edildiği.
  - İzin açıklaması.
- **Formun Oluşturulma Tarihi:** İzin talebinin sisteme kaydedildiği tarih.
- **Düzenleme Butonu:** İzin talebini düzenlemek için kullanılır.

---

#### Bekleyen İzinler Mail - Görsel
![personel izin onayı mail](https://github.com/user-attachments/assets/e233da8b-79ff-4ad2-aa02-9da759a9588f)

#### Bekleyen İzinler Listesi - Görsel
![bekleyen izinler liste](https://github.com/user-attachments/assets/4a5531ba-1118-46fc-a8ef-4c1064c4a771)


#### Bekleyen İzin Düzenleme - Görsel
![bekleyen izin düzenleme](https://github.com/user-attachments/assets/d5fdd6ca-4dbb-419e-84ad-62555879a5e0)

### 2. Onaylanan İzinler

**Onaylanan İzinler**, iki aşamalı onay sürecinden (insan kaynakları ve genel müdür) geçen izin taleplerinin listelendiği bölümdür. Bu alan, izin sürecinin tamamlanmasından sonra izin verilerinin düzenlenmesi ve raporlanması için kullanılır.

#### İşleyiş

1. **İzin Kartı Güncellemesi:**  
   - İnsan kaynakları ve genel müdür onayından geçmiş izinler bu alanda listelenir.
   - Eğer onaylanan izin talebinde **Yıllık İzin** veya **Alacak İzin** alanları var ise ilgili personelin yıllık veya alacak izin gün sayılarından gerekli düşüş işlemleri otomatik olarak yapılır.

2. **PDF Oluşturma:**  
   - Her onaylanan izin için sistem tarafından bir PDF formu oluşturulur.(PDF dosyası fiziksel olarak oluşturulmamaktadır.PDF butonuna basılması durumunda pdf olarak oluşturulur ve otomatik olarak indirilir) Bu form içerisinde:
     - Personel adı, soyadı, TC kimlik numarası, unvanı, şubesi, sicil numarası gibi bilgiler yer alır.
     - İzin türü (ücretli veya ücretsiz) ve alınan izin detayları bulunur.
     - İzin açıklaması için ayrılmış bir alan mevcuttur.
     - Personelin imza atabileceği bir bölüm ve izini onaylayan insan kaynakları ile genel müdür kullanıcılarının isimleri ve imza alanları yer alır.
   - PDF, **İzin Formu** butonu ile indirilebilir ve çıktısı alınarak dosyalama işlemleri hızlı bir şekilde tamamlanır.

---
#### Liste Özellikleri

**Onaylanan İzinler** listesinde her bir izin talebi için aşağıdaki detaylar görüntülenir:

- **Döküman Numarası ve PDF Butonu:**  
  Her izin için bir döküman numarası bulunur ve PDF butonuna tıklayarak ilgili izin formunu indirilebilir.

- **Personel Detayları:**  
  Personelin adı, soyadı, şubesi ve unvanı görüntülenir.

- **Tarih Bilgileri:**  
  İzin başlangıç ve bitiş tarihleri.

- **Toplam Alınan İzin Gün Sayısı:**  
  Onaylanan izin süresinin toplam gün olarak hesaplanmış hali.

- **Detaylı Görüntüle Butonu:**  
  Buton üzerine gelindiğinde izin türleri, gün sayıları ve izin açıklaması görüntülenir.

- **Oluşturulma Tarihi:**  
  İzin talebinin sisteme kaydedildiği tarih bilgisi.
- **Düzenle ve İptal Et Butonları**
  - **Güncelle Butonu:** Onaylanan izin bilgilerini düzenlemek için kullanılır.
  - **İptal Et Butonu** Onaylanan izinin geri çekilmesi durumunda ilgili izini iptal etmek için kullanılır. (İzin alan personelin izin türlerinde alacak veya yıllık izin türü bulunuyorsa bu izinler personele geri iade edilir.)
---

#### Onaylanan İzin Listesi - Görsel 1
![onaylanan izinler 1](https://github.com/user-attachments/assets/352b7e59-d814-4825-b6db-2476b4a54ece)

#### Onaylanan İzin Listesi - Görsel 2
![onaylanan izinler 2](https://github.com/user-attachments/assets/893951b3-31da-472c-b06b-7052b5dbd640)

#### Onaylanan İzin Güncelleme - Görsel
![onaylanan izin güncelleme](https://github.com/user-attachments/assets/d2ffdf40-453a-495a-acb5-58bc42f8d14c)

#### Onaylanan İzin PDF Formu - Görsel
![onaylanan izin pdf](https://github.com/user-attachments/assets/4f5988f8-5944-4a42-8172-45631980256c)

### 3. Reddedilen İzinler ve İptal Edilen İzinler
**Reddedilen İzinler**, insan kaynakları veya genel müdürlük tarafından reddedilmiş izin taleplerinin listelendiği bölümdür. Bu alan, reddedilen izinlerin kayıt altına alınmasını ve gerektiğinde incelenmesini sağlar.

**İptal Edilen İzinler**, insan kaynakları veya genel müdürlük tarafından iptal edilmiş izin taleplerinin listelendiği bölümdür. Bu alan, iptal edilen izinlerin kayıt altına alınmasını ve gerektiğinde incelenmesini sağlar.

---

Bu yapı, izin taleplerinin doğru ve hızlı bir şekilde yönetilmesini sağlar. İnsan kaynakları ve genel müdürlük arasında etkin bir süreç yönetimi sunar.

## Görevlendirmeler

**Görevlendirmeler** bölümü, tüm personel görevlendirme işlemlerinin detaylı bir şekilde listelendiği ve yönetildiği bir alandır. Bu alan, personelin şube ve ünvan değişikliklerinin kayıt altında tutulmasını sağlar.

- **Görevlendirmeler** bölümünde görevlendirme ekle alanı bulunmamaktadır. Personel kartları üzerinden ünvan veya şube değişikliği yapılması durumunda otomatik olarak bu listeye görevlendirme durumu eklenmektedir.

### Liste Özellikleri

Görevlendirmeler listesinde, her bir işlem için şu detaylar yer alır:

- **Adı Soyadı:** Görevlendirilen personelin adı ve soyadı.
- **Eski Şube ve Yeni Şube:** Personelin nakil işlemi sırasında görev yaptığı eski ve yeni şube bilgileri.
- **Eski Ünvan ve Yeni Ünvan:** Personelin görev değişikliği sırasında sahip olduğu önceki ve yeni unvan bilgileri.
- **Nakil Tarihi:** Görevlendirmenin gerçekleştirildiği tarih ve saat.
- **Sil Butonu:** Gerektiğinde ilgili görevlendirme kaydını sistemden kaldırmayı sağlar.

### Excel Dışa Aktarma

Görevlendirme listesi, **Excel formatında** dışa aktarılabilir. Bu özellik, görevlendirme kayıtlarının raporlanmasını ve arşivlenmesini kolaylaştırır.

### Görevlendirmeler - Görsel
![görevlendirmeler](https://github.com/user-attachments/assets/91b46cfc-c315-4444-b62f-e16cc06a816c)

---

Bu alan, personel görevlendirme işlemlerinin düzenli bir şekilde kayıt altına alınmasını sağlar. Özellikle şube ve unvan değişikliklerinin şeffaf bir şekilde takip edilmesi için tasarlanmıştır.

## Eksik Günler

**Eksik Günler**, tüm personellerin eksik gün kayıtlarının listelendiği ve yönetildiği bir bölümdür. Bu alan, eksik gün bilgilerinin kolayca takip edilmesini ve gerektiğinde düzenlenmesini sağlar.

### Özellikler

1. **Eksik Gün Listesi:**
   - Tüm personellere ait eksik günler, detaylı bir şekilde listelenir.
   - Kayıtlar tarih, şube ve eksik gün nedeni gibi kriterlere göre filtrelenebilir.

2. **Eksik Gün Ekle:**  
   - Yeni eksik gün kayıtları, **Eksik Gün Ekle** butonu ile sisteme eklenebilir.

3. **Excel Dışa Aktarma:**  
   - Eksik gün listesi, ihtiyaç halinde **Excel formatında** dışa aktarılabilir. Bu, raporlama süreçlerini kolaylaştırır.

4. **Filtreleme:**
   - **Tarih Filtreleme:** Belirli bir tarih aralığına ait eksik gün kayıtları görüntülenebilir.
   - **Neden Filtreleme:** Eksik gün nedeni baz alınarak kayıtlar daraltılabilir.
   - **Şube Filtreleme** Belirli bir şubeye göre filtreleme işlemleri ile kayıtlar daraltılabilir.

### Eksik Günler - Görsel
![eksikgün genel](https://github.com/user-attachments/assets/de4cb4a6-8b2d-4c03-b2db-7175d36b2113)

### Eksik Günler Ekleme - Video
https://github.com/user-attachments/assets/b408e7b8-4949-4bf9-9855-2dcaa0a2036f

---

Bu bölüm, personellerin eksik günlerinin kayıt altına alınmasını ve raporlanmasını kolaylaştırır. İnsan kaynakları süreçlerinde düzenli bir kayıt yönetimi sağlar.

## Detaylı Filtre

**Detaylı Filtre** bölümü, personel tablosu üzerinde istenilen filtrelerin oluşturulması ve seçilen kolonlara göre dinamik bir tablo oluşturulmasını sağlar. Kullanıcılar, bu alan sayesinde detaylı veri analizleri yapabilir ve özelleştirilmiş veriler elde edebilir.

### Çalışma Mantığı

1. **Filtreleme:**  
   - Kullanıcılar, belirledikleri filtre kriterlerine göre tablo verisini daraltabilir.
   - Filtre kriterleri 8 farklı kolon çeşidinden oluşmaktadır:
     - **Metin Bazlı Kolonlar:** Girilen metne göre filtreleme yapılır.
     - **Liste Kolonları:** Seçilen kolonla ilgili bir liste sunulur ve kullanıcı, listeden seçim yapabilir.
     - **Sayı Kolonları:** Kullanıcıdan karşılaştırma türü (büyük, küçük, eşit, arasında vb.) seçmesi ve değer girmesi beklenir.
     - **Ondalıklı Sayı Kolonları:** Sayı kolonlarıyla aynı şekilde çalışır; ondalıklı sayı girişine izin verir.
     - **Tarih Kolonları:** Kullanıcı, karşılaştırma türünü seçerek ve ardından istenilen tarihi girerek tarih bazlı arama yapabilir.
     - **Seçimli Kolonlar:** İki seçenek (örneğin: emekli, normal) sunulur ve kullanıcı birini seçebilir.
     - **Şube Kolonları:** Şube adına veya durumuna (aktif, pasif, silinmiş) göre filtreleme yapılabilir.
     - **Ünvan Kolonları:** Şube kolonlarıyla aynı şekilde çalışır.

2. **Getirilecek Özellikler Seçimi:**  
   - Filtreleme işlemlerinden sonra tabloda yer alacak kolonlar kullanıcı tarafından seçilir. Böylece, sadece ihtiyaç duyulan veriler görüntülenir.
   - Bu alan üzerinde personellere ait her türlü kolon verisi seçilebilir.
   - Bu bölümde personellerin yıllara göre hak edilen veya kullanılan yıllık izin kümülatif bilgileri de istek doğrultusunda seçilebilir.
   - Getirilecek özelliklerin sırasına göre dinamik tablo oluşturulmaktadır. Kullanıcı sürükleme işlemi yaparak kolonların sırasını değiştirebilir.

3. **Tablo Özellikleri:**  
   - Dinamik olarak oluşturulan tablo, sayfalama yapısı ile sunulur.
   - Tablo verisi **Excel formatında** dışa aktarılabilir.

### Detaylı Filtre - Video

https://github.com/user-attachments/assets/81e7c24a-7906-4d4d-8e39-f019e4bf3a87


---

Bu alan, özelleştirilmiş veri analizi yapmak ve rapor oluşturmak isteyen kullanıcılar için tasarlanmıştır. Kullanıcılar, ihtiyaç duydukları verilere kolayca ulaşabilir ve bu veriler üzerinde detaylı incelemeler yapabilir.

## Toplu İşlemler

**Toplu İşlemler** bölümü, birden fazla personelin aynı anda sisteme eklenmesini sağlayan bir bölümdür. Bu özellik, özellikle büyük ölçekli personel girişleri için zaman kazandıran bir çözüm sunar.

### Çalışma Mantığı

1. **Excel Şablonu Kullanımı:**  
   - Sisteme toplu personel eklemek için bir **Excel şablonu** kullanılır ve kullanıcıdan ilk olarak bu şablonun indirilmesi istenir.
   - **İndirilen Excel şablonu**, sisteme doğru veri girişini kolaylaştırmak amacıyla şu özellikleri içerir:
     - **Şube ve Ünvan Kodları:** Sistemde tanımlı olan şubelerin ve unvanların kodları şablonda yer alır. Kullanıcılar, bu kodları kullanarak doğru şube ve unvan eşleştirmelerini yapabilir.
     - **Statik Alanlar:** Kan grubu, beden ölçüleri gibi sabit değerlere sahip alanlar için hazır listeler şablonda sunulur. Kullanıcılar, bu listelerden seçim yaparak verileri doldurabilir.
   - Kullanıcılar, şablondaki yönergeleri takip ederek zorunlu ve zorunlu olmayan alanları eksiksiz bir şekilde doldurabilir.

2. **Dosya Yükleme:**  
   - Hazırlanan Excel dosyası sisteme yüklenir.
   - Sistem, yüklenen dosyada yer alan bilgileri doğrular ve eksik ya da hatalı veriler için kullanıcıyı bilgilendirir.

3. **Hata Yönetimi:**  
   - Hatalı satırlar için detaylı geri bildirim sağlanır, böylece kullanıcı hatalı verileri düzeltebilir.

4. **Veri İşleme:**  
   - Hatalı kayıtlar düzeltildikten sonra dosya tekrar yüklenir.
   - Doğru formatta olan tüm personel bilgileri sisteme toplu bir şekilde eklenir.

### Toplu İşlemler - Görsel
![toplu personel ekleme](https://github.com/user-attachments/assets/35b65b62-8874-42ab-9585-231690d9c10b)

---
Bu alan, çok sayıda personel ekleme işlemini hızlı ve sorunsuz bir şekilde gerçekleştirmek için tasarlanmıştır. İnsan kaynakları süreçlerinde zaman kazandırır ve manuel veri giriş hatalarını en aza indirir.

## Günlük Otomasyon Takip

**Günlük Otomasyon Takip**, her gece saat 01:30'da çalışan Hangfire Cron Job'ları ile yenilenen yıllık izin ve gıda yardımı verilerinin son 50 kaydını listeler. Bu alan, sistemde yapılan otomatik işlemleri izlemek ve kontrol etmek amacıyla tasarlanmıştır.

### Çalışma Mantığı

#### **Yıllık İzin Yenileme Süreci**
- **Zamanlama:** Her gece 01:30'da Hangfire Cron Job'ları çalışır.
- **Kontrol Kriterleri:** 
  - Yıllık izini yenilenmesi gereken personeller tespit edilir.
  - Tespit edilen personeller için aşağıdaki kriterlere göre izin yenilemesi yapılır:

| **Çalışma Süresi**         | **Eklenen İzin Gün Sayısı**   |
|----------------------------|------------------------------|
| 0 - 1 yıl                 | İzin eklenmez               |
| 1 - 5 yıl                 | 14 gün                      |
| 6 - 15 yıl                | 20 gün                      |
| 15+ yıl                   | 26 gün                      |

- **Özel Durumlar:**
  - **18 yaşından küçük personeller:** 20 gün eklenir.
  - **Emeklilik durumu ile yenilenen izinler:** 20 gün eklenir.
  - **50 yaşına eşit veya büyük personeller:** 
    - **Çalışma yılı < 15:** 20 gün eklenir.
    - **Çalışma yılı ≥ 15:** 26 gün eklenir.

#### **Gıda Yardımı Eklenme Süreci**
- **Kontrol Kriterleri:**
  - Çalışma yılı 3 yıl ise: 60 TL gıda yardımı eklenir.
  - Çalışma yılı > 3 yıl ise: 20 TL gıda yardımı eklenir.
  - Bu iki durum dışında herhangi bir gıda yardımı eklenmez.

### Ekran Özellikleri

- **Son 50 Kayıt:** Yıllık izin ve gıda yardımı yenilenmesine dair son 50 işlem listelenir.
- **Log Detayları:** 
  - İşlem zamanı,
  - Etkilenen personelin adı soyadı,
  - Yenilenen yıllık izin ya da eklenen gıda yardımı miktarı açıkça belirtilir.

### Günlük Otomasyon Takip - Görsel

![günlük loglar](https://github.com/user-attachments/assets/0561266e-64fa-4190-9dbe-d6444a346f67)

---

Bu alan, sistemde yapılan otomatik işlemlerin şeffaf bir şekilde izlenmesini sağlar ve insan kaynakları kullanıcılarının işlem kontrolü yapmasına olanak tanır. Otomasyonun düzenli çalışıp çalışmadığını doğrulamak için etkili bir araçtır.

## Kullanıcı İşlemleri

Kullanıcı İşlemleri bölümü, uygulamayı kullanan kullanıcıların yönetimi için tasarlanmıştır. Bu bölümde yeni kullanıcılar eklenebilir, mevcut kullanıcı bilgileri düzenlenebilir, silinebilir ve kullanıcıların listesi görüntülenebilir.

### Kullanıcı Listesi

Kullanıcıların yönetimi için bir liste görüntülenir. Liste üzerinde aşağıdaki bilgiler ve işlemler bulunur:

- **Ad-Soyad**: Kullanıcının adı ve soyadı.
- **Mail Adresi**: Kullanıcının e-posta adresi.
- **Şifre Durumu**: Bu alan kullanıcı sisteme eklendikten sonra hesap aktivasyonu yapıp yapmadığını izlemek için oluşturulmuştur. Burdaki şifre değiikliğinden kasıt kullanıcının kendi şifresini belirlemesi durumudur.
- **Rol**: Kullanıcının rolü (İnsan Kaynakları, Genel Müdür, Şube Sorumlusu).
- **Atanan Şubeler**: Rol gereği kullanıcıya atanmış olan şubeler. Genel Müdür rollerinde birden fazla şube bulunabildiği için atanan şubeler adı altında bir buton bulunur ve butona hover işlemi yapılırsa ilgili şubeler görüntülenebilir.
- **Durumu**: Kullanıcının aktif veya pasif durumu.
- **Düzenle ve Sil İşlemleri**: Kullanıcı bilgilerinin düzenlenmesi veya kullanıcının silinmesi için ilgili butonlar.

### Sistem Uyarıları

Liste ekranında, **şube sorumlusu atanmamış şubeler** veya **genel müdür atanması yapılmamış şubeler** varsa, ekranın üst kısmında kırmızı bir uyarı mesajı ile gösterilir. Örnek uyarı:
-  Şube Sorumlusu Atanmamış Şubeler Mevcut (Çarşı Dinar, Halife Sultan)

### Kullanıcı Listesi - Görsel 1
![kullanıcıişlemleri1](https://github.com/user-attachments/assets/1ec98131-e679-4e7d-8581-164a5a520a81)


### Kullanıcı Listesi - Görsel 2
![kullanıcıişlemleri2](https://github.com/user-attachments/assets/c09395d1-3694-4247-a745-bbf5f2d38fe6)


### Kullanıcı Ekleme

Yeni kullanıcı eklemek için kullanıcı ekleme ekranı kullanılır. Aşağıdaki bilgiler istenir:

1. **Ad-Soyad**: Kullanıcının adı ve soyadı.
2. **Mail Adresi**: Kullanıcının e-posta adresi. Bu adres üzerinden aktivasyon bağlantısı gönderilir.
3. **Rol Seçimi**: Kullanıcının sistemdeki rolü:
   - **İnsan Kaynakları**
   - **Genel Müdür**
   - **Şube Sorumlusu**
4. **Şube Ataması**:
   - **Genel Müdür** için birden fazla şube atanabilir.
   - **Şube Sorumlusu** için yalnızca bir şube atanabilir.
      - **Atama Kısıtlaması**: Bu bölümde sadece atanması yapılmamış şubeler gösterilir. Böylece kullanıcı eklemesi yapılırken bir şubeye birden fazla kullanıcı ataması yapılabilmesinin önüne geçilmiştir.

#### Şifre Yönetimi

- Kullanıcı eklenirken şifre belirlenmez.
- Kullanıcının mail adresine bir **aktivasyon bağlantısı** gönderilir. Kullanıcı, bu bağlantı aracılığıyla sisteme giriş yapmadan önce şifresini oluşturur.

### Kullanıcı Ekleme - Görsel
![kullanıcıekleme](https://github.com/user-attachments/assets/43df8caf-0c88-4315-b13b-8977e832f491)



### Kullanıcı Düzenleme

Mevcut kullanıcı bilgileri düzenlenebilir. Düzenleme ekranında aşağıdaki işlemler yapılabilir:

1. **Ad-Soyad Düzenleme**: Kullanıcının adı ve soyadı değiştirilebilir.
2. **Durum Değiştirme**: Kullanıcının aktif veya pasif durumu değiştirilebilir.
3. **Rol Değiştirme ve Şube Ataması**:
   - Rol değiştirilirken yeni role uygun şubeler atanabilir.
   - Genel Müdür ve Şube Sorumlusu rollerinde, şube atamaları düzenleme ekranında yeniden seçilebilir.

### Kullanıcı Düzenleme - Görsel
![kullanıcıdüzenleme](https://github.com/user-attachments/assets/a5d1d2f3-0473-4bda-a6f7-53b249270919)


---
Bu bölüm, kullanıcıların merkezi bir şekilde yönetilmesini sağlar. Eksik atanmış roller hızlıca tespit edilerek, sistemin düzgün çalışması sağlanır.

## Kullanıcı İşlemleri

Kullanıcı İşlemleri bölümü, sistem üzerindeki tüm kullanıcı işlemlerinin arka planda tutulduğu belirli log kayıtlarını yönetmek ve görüntülemek için tasarlanmıştır. Aynı zamanda sisteme giriş yapan kullanıcıların hangi işlemleri yaptığı bu ekran üzerinden takip edilebilmektedir.

### Özellikler

- **Log Listesi**:
  - Sisteme giriş yapmış her kullanıcının gerçekleştirdiği işlemler bu listede detaylı bir şekilde görüntülenir.
  - İşlemler kullanıcı adı, işlem türü, işlem zamanı ve işlem detayları gibi bilgilerle kayıt altına alınır.

- **Filtreleme**:
  - **İşlem Türüne Göre Filtreleme**: Belirli bir işlem türüne (örneğin: "Giriş", "Silme", "Ekleme") göre kayıtlar filtrelenebilir.
  - **Tarih Bazlı Filtreleme**: İşlem kayıtları ay ve yıl bazında filtrelenerek istenen dönemlerdeki kayıtlar hızlıca bulunabilir.

### Kullanım Senaryoları

- **İzleme ve Denetleme**:
  - Sistem üzerindeki kullanıcı aktivitelerini takip ederek denetleme işlemleri yapılabilir.
  - Kritik işlemleri gerçekleştiren kullanıcılar tespit edilebilir.

## Kullanıcı İşlemleri - Görsel 1 
![kullanıcılogları1](https://github.com/user-attachments/assets/a38c8584-d506-4e1c-9099-d67de8722d37)


## Kullanıcı İşlemleri - Görsel 2 
![kullanıcılogları2](https://github.com/user-attachments/assets/6d641922-3a0c-487c-bf01-0c7ec158fd65)

---

Bu bölüm, sistem üzerinde kullanıcı aktivitelerinin şeffaf ve düzenli bir şekilde kayıt altına alınmasını ve gerektiğinde analiz edilmesini sağlar.

## Şube Sorumluları Ekranı ve İzin Talep Formu

Şube sorumlularının sisteme giriş yaptığında karşılaştığı ekran, görevleri gereği özelleştirilmiş bir kullanıcı deneyimi sunar. Şube sorumluları, sistemdeki diğer sayfalara erişim hakkına sahip değildir ve yalnızca kendi şubelerine yönelik izin taleplerini yönetebilirler. Sisteme giriş yapıldığında, şube sorumlularını doğrudan **İzin Giriş Formu** karşılar. Bu form aracılığıyla şube sorumluları, şubelerinde çalışan personeller için izin taleplerini oluşturabilirler.

### İzin Giriş Formunun Özellikleri

1. **Personel Seçimi:**
   - Formun üst kısmında yer alan "Personelin Adı Soyadı" alanından, izin talebi yapılacak personel seçimi gerçekleştirilir.
   - Personel seçimi yapıldıktan sonra, seçilen personele ait **şube** ve **ünvan** bilgileri ekranda otomatik olarak gösterilir.

2. **Mevcut İzin Bilgileri:**
   - **Alacak İzin Miktarı:** Seçilen personele ait gün ve saat cinsinden mevcut alacak izin miktarı gösterilir.
   - **Yıllık İzin Miktarı:** Personele ait mevcut yıllık izin miktarı kullanıcıya sunulur.

3. **İzin Tarihleri:**
   - Talep edilecek izin için **izin başlangıç tarihi** ve **izin bitiş tarihi** bilgileri girilmesi gereken input alanları bulunmaktadır.

4. **İzin Açıklaması:**
   - İsteğe bağlı olarak izin talebiyle ilgili açıklama girilebilecek bir metin alanı bulunmaktadır.

5. **İzin Detayları:**
   - İzin detaylarının bulunduğu alanda aşağıdaki izin türleri için talep oluşturulabilir:
     - **Yıllık İzin** *(Personele ait yıllık izin hakkı bulunmuyorsa bu alan seçilemez duruma getirilir. İlgili izinlerin fazla girilmesi durumlarında kullanıcıya uyarı mesajları ile dönüş yapılır.)*
     - **Haftalık İzin**
     - **Alacak İzin**
     - **Resmi İzin**
     - **Ücretsiz İzin**
     - **Seyahat İzni**
     - **Babalık İzni (5 Gün)** *(Sabit bir değer olarak atanır)*
     - **Evlenme İzni (3 Gün)** *(Sabit bir değer olarak atanır)*
     - **Ölüm İzni (3 Gün)** *(Sabit bir değer olarak atanır)*

### İzin Talep Süreci

- Kullanıcı, uygun izin türü için gerekli bilgileri doldurup "İzin Tanımla" butonuna tıklayarak talebi oluşturabilir.
- İzin talebi başarıyla oluşturulduktan sonra, sistem otomatik olarak **İnsan Kaynakları personellerine e-posta gönderimi** gerçekleştirir.
- Talep, insan kaynaklarının değerlendirmesi için **Bekleyen İzinler** sayfasına düşer.

## Şube Sorumluları Ekranı ve İzin Talep Formu - Video

https://github.com/user-attachments/assets/0581eff5-3c04-48a4-aa1b-4c8ea0c0265a


---

Bu ekran, şube sorumlularının kendi personelleri için hızlı ve etkili bir şekilde izin talebi oluşturmasını sağlarken, diğer gereksiz sistem özelliklerine erişimi kısıtlayarak daha güvenli ve odaklı bir kullanıcı deneyimi sunar.


## Şifremi Unuttum

Sistemdeki kullanıcılar, giriş yapamadıkları durumlarda **Şifremi Unuttum** özelliğini kullanarak hesaplarına yeniden erişim sağlayabilir.

### İşleyiş

1. **Şifre Sıfırlama Talebi**:
   - Giriş ekranında yer alan "Şifremi Unuttum" butonu aracılığıyla kullanıcılar şifre sıfırlama talebinde bulunabilir.
   - Talep sırasında kullanıcının kayıtlı e-posta adresi girilmelidir.

2. **E-Posta Gönderimi**:
   - Kullanıcının sisteme kayıtlı e-posta adresine şifre sıfırlama bağlantısı gönderilir.
   - Bu bağlantı, güvenlik nedeniyle belirli bir süre içinde kullanılmalıdır.

3. **Yeni Şifre Belirleme**:
   - Kullanıcı, gönderilen bağlantıya tıklayarak yeni şifre belirleme ekranına yönlendirilir.
   - Şifre belirledikten sonra kullanıcı hesabı yeniden aktif hale gelir.

### Notlar
- Şifre sıfırlama bağlantısı bir kez kullanılabilir ve süre aşımı durumunda tekrar talep edilmesi gerekmektedir.
- Şifre sıfırlama işlemi yalnızca kayıtlı e-posta adresi üzerinden yapılabilir.

## Şifremi Unuttum - Video

https://github.com/user-attachments/assets/0739db2e-be4a-4201-8271-b41067f8e5ec

--- 




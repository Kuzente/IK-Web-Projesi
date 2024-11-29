# IK Web Projesi

Bu proje, insan kaynakları yönetim süreçlerini modernize etmek ve optimize etmek amacıyla geliştirilmiş kapsamlı bir web uygulamasıdır. Kullanıcı dostu arayüzü, dinamik özellikleri ve otomasyon süreçleri ile şirketlerin personel yönetiminden izin takibine kadar çeşitli ihtiyaçlarını karşılamayı hedefler.

## Projenin Temel Özellikleri
- **Personel Kartları Yönetimi:** Tüm personellere ait özlük bilgilerinin güvenli ve kolay yönetimi.
- **Dinamik Filtreleme:** Kullanıcıların çeşitli kriterlere göre personel verilerine erişimini sağlayan güçlü bir filtreleme sistemi.
- **İzin ve Yardım Yönetimi:** Alacak izinlerin, gıda yardımlarının ve yıllık izinlerin kolayca takibi ve yönetimi.
- **Otomatik Süreçler:** Yıllık izin hak edişlerinin gece yarısı otomatik olarak hesaplanması ve güncellenmesi.
- **Dashboard Raporlama:** Cinsiyet ve eğitim durumu dağılım grafikleri, eksik gün raporları ve izin durumlarının görselleştirilmesi.
- **İki Aşamalı İzin Onayı:** İnsan Kaynakları ve Genel Müdür onayıyla iki aşamalı kontrol süreçleri.
- **Eksik Gün Takibi:** Eksik günlerin kolay takibi ve raporlanması.

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

#### Genel Dashboard Görünümü
![dashboard1](https://github.com/user-attachments/assets/f38499bb-5ca7-4659-861f-beb2f771ade3)


#### Grafikler ve Detaylı Bilgiler
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

#### Aktif Personeller Listesi
![personeller](https://github.com/user-attachments/assets/0fdb8c89-d4b8-47d8-bbeb-8cdd261e9c74)


#### Çıkarılan Personeller Listesi
![çıkarılan personeller liste](https://github.com/user-attachments/assets/9ede9d7e-54f7-4863-8b49-9b2cd8acbf5c)

#### Personel Ekleme (Video)
Bir personel ekleme işleminin nasıl yapıldığını adım adım gösteren kısa bir video:

https://github.com/user-attachments/assets/d2d7c729-63fe-4cad-bd3e-5e3d3e7b0b71


---

Bu alanlar, personel yönetimi süreçlerini optimize etmek için tasarlanmıştır ve kullanıcı dostu bir deneyim sunar.

## Personel Kartları

**Personel Kartları**, her bir çalışan için detaylı veri yönetimi sağlayan kapsamlı bir modüldür. Bu alan, personel bilgilerinin düzenlenmesi ve takibi için kullanıcı dostu ve işlevsel bir tasarıma sahiptir. Modül, dört temel bölümden oluşmaktadır: **Personel Detayları**, **İzinler**, **Eksik Gün**, ve **Görevlendirmeler**.

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

### Personel Detayları Video

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

### Personele Ait İzinler Görsel


---

Bu yapı, personel yönetiminde ihtiyaç duyulan tüm süreçleri kapsamlı bir şekilde karşılar. Kullanıcı dostu tasarımı ve esnek düzenleme seçenekleri ile operasyonel süreçlerin hızlandırılmasını ve kolaylaştırılmasını sağlar.

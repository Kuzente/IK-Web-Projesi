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


---

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





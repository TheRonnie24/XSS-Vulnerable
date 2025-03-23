# XSS-Vulnerable
XSS Güvenlik Açığı Gösterimi

------------------------------------------------------------------------------------------------------------------------------------------
Açıklama

Bu repository, bir Cross-Site Scripting (XSS) güvenlik açığının ve güvenli düzeltmesinin bir örneğini içerir.

------------------------------------------------------------------------------------------------------------------------------------------
Nasıl Kullanılır

1. Güvenlik açığı olan sayfayı açın.
2. Aşağıdaki betiği yorum olarak girin:
<script>alert('XSS Güvenlik Açığı Kullanıldı!');</script>
3. Yorumu gönderin.
4. JavaScript kodu tarayıcıda yürütülerek XSS güvenlik açığını gösterir.

-------------------------------------------------------------------------------------------------------------------------------------------
Düzeltilmiş Sürüm
Düzeltilmiş sürümde, kullanıcı girişi XSS saldırılarını önlemek için `document.createTextNode()` kullanılarak temizlenir.

OWASP Kategorisi
- A7:2017 - Siteler Arası Komut Dosyası (XSS)
- A03:2021 - Enjeksiyon

CVSS Puanı
- 6.1 (Orta)
- Saldırı Vektörü: `AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N`

Bu video, XSS güvenlik açığının nasıl istismar edilebileceğini ve güvenli sürümün bunu nasıl engellediğini göstermektedir.
Videoyu repository ekinden bulup izleyebilirsiniz.

-------------------------------------------------------------------------------------------------------------------------------------------
Nasıl Çalıştırılır
1. Bir tarayıcıda `index.html`yi açın.
2. Güvenlik açığı olan sürümü test edin.
3. Güvenli sürümle değiştirin ve tekrar test edin.
   

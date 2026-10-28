# 📐 Klavyeden Girilen Üçgenin Alanını Hesaplama (Python & Web)

Bu proje, **Algoritma ve Programlamaya Giriş** dersi kapsamında geliştirilmiş; klavyeden taban ve yükseklik değerleri alınan bir üçgenin alanını hesaplayan Python algoritması ve canlı interaktif web uygulamasıdır.

🚀 **Canlı Web Uygulaması:** [ademkaleli.github.io/ucgen-alani-hesaplama](https://ademkaleli.github.io/ucgen-alani-hesaplama/)

---

## 👤 Öğrenci Bilgileri

* **Adı Soyadı:** Adem Kaleli
* **Öğrenci No:** 2615501083
* **Ders:** Algoritma ve Programlamaya Giriş
* **Konu:** Temel Girdi/Çıktı İşlemleri, Mantıksal Doğrulama ve Canlı Görselleştirme

---

## 🧠 Algoritma ve Mantıksal Akış (IPO Model)

Program **Input-Process-Output (Girdi-İşlem-Çıktı)** prensibine uygun olarak tasarlanmıştır:

1. **GİRDİ (Input):** Kullanıcıdan klavye/arayüz aracılığıyla `taban` ($a$) ve `yükseklik` ($h$) değerleri alınır.
2. **DOĞRULAMA (Validation):** 
   * Girilen değerlerin $0$'dan büyük olup olmadığı kontrol edilir ($a > 0 \land h > 0$).
   * Kullanıcının harf veya geçersiz metin girmesi ihtimaline karşı `try-except` (`ValueError`) hata yönetimi bloğu çalıştırılır.
3. **İŞLEM (Process):** Üçgen alan formülü uygulanır:
   $$\text{Alan} = \frac{\text{Taban} \times \text{Yükseklik}}{2}$$
4. **ÇIKTI (Output):** Hesaplanan alan değeri virgülden sonra 2 basamak olacak şekilde (`:.2f`) ekrana formatlı biçimde basılır ve web arayüzünde 2D canvas üzerinde üçgen canlı olarak çizdirilir.

---

## ✨ Proje İçeriği ve Özellikler

* 🐍 **`ucgen_alani_hesapla.py`**: Terminal/Komut satırında çalışan orijinal Python algoritma kodu.
* 🌐 **`index.html`**: Tarayıcı üzerinden çalışan, girilen taban ve yüksekliğe göre ölçeklenerek üçgeni canlı çizen interaktif web uygulaması.
* 📱 **Tam Mobil Uyumluluk:** Responsive tasarım sayesinde akıllı telefonlarda ve tabletlerde sorunsuz çalışma.

---

## 💻 Python Kodunu Yerel Olarak Çalıştırma

Bilgisayarınızda Python 3 yüklü ise terminal veya komut satırından şu komutla çalıştırabilirsiniz:

```bash
python ucgen_alani_hesapla.py

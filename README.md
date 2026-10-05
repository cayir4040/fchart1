# Kullanıcı Giriş Akışı — Algoritma Diyagramı

## Projenin Amacı
[Bu algoritmanın neyi modellediğini 2-3 cümleyle açıklayın.]

## İş Kuralları
- Hesabın kilitli olup olmadığı kontrol edilir.
- Boş e-posta veya şifre alanı için uyarı gösterilir.
- Doğru bilgilerde başarılı giriş sonucu gösterilir.
- Yanlış girişte sayaç artırılır.
- Üç başarısız denemede hesap kilitlenir.

## Akış Diyagramı
![Kullanıcı giriş akış diyagramı](flowchart.png)

## Test Senaryoları
| Senaryo | Beklenen sonuç |
|---|---|
| Hesap kilitli | Giriş engellenir |
| E-posta veya şifre boş | Uyarı gösterilir, sayaç artmaz |
| Bilgiler doğru | Başarılı giriş |
| Üçüncü yanlış deneme | Hesap kilitlenir |

## Tasarım Kararları
[Karar noktalarını, sayaç mantığını ve önemli varsayımlarınızı açıklayın.]

## Öğrenci Bilgisi
- Ad Soyad: [Adınız Soyadınız]
- Ödev: Algoritma Tasarımı ve Akış Diyagramı


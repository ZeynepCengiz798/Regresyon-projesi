# 📊 Regresyon Analizi Projesi - İST366



Bu proje, Hacettepe Üniversitesi İstatistik Bölümü'nde alınan **İST366 - Regresyon Çözümlemesi** dersi kapsamında, R programlama dili kullanılarak gerçekleştirilmiştir. Projede çoklu doğrusal regresyon modeli kurulmuş ve varsayım kontrolleriyle birlikte modelin uygunluğu detaylı şekilde incelenmiştir.







 🔍 Proje Özeti



- **Bağımlı değişken:** `y`

- **Bağımsız değişkenler:**

 - `x1`, `x2`, `x3` (nicel)

 - `x4` (nitel - faktör)



### Uygulanan Adımlar:



- Veri yükleme ve ön işleme (`.txt` veri dosyası üzerinden)

- Çoklu doğrusal regresyon modeli kurulumu (`lm()` fonksiyonu ile)

- Logaritmik dönüşüm ve yeniden modelleme

- Varsayım kontrolleri:

 - Artıkların normalliği (QQ plot, Shapiro-Wilk testi)

 - Varyans homojenliği (Breusch-Pagan testi)

 - Otokorelasyon (Durbin-Watson testi)

 - Çoklu doğrusal bağlantı (VIF)

- Aykırı / uç / etkili gözlemlerin belirlenmesi (Cook’s distance, leverage, DFFITS)

- Model iyileştirme ve sadeleştirme

- Ridge regresyon uygulaması (`glmnet` paketi ile)



---



## 🧰 Kullanılan Araçlar



- R 4.x

- RStudio

- Paketler:

 - `ggplot2`, `car`, `MASS`, `lmtest`, `glmnet`, `psych`



---



## 📁 Dosya Yapısı



Regresyon_projesi

│

├── Zeynep Cengiz.txt # Veri seti (.txt formatında)

├── Zeynep Cengiz .R # R Markdown dosyası (analiz süreci)

├── Zeynep Cengiz.docx # Otomatik oluşturulan proje raporu

└── README.md # Bu tanıtım dosyası











---



## 🧑‍💻 Hazırlayan



**Zeynep Cengiz**  

Hacettepe Üniversitesi - İstatistik  

Mail: zeyneppcengiz14@gmail.com



---


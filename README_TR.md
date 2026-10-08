# S.A Conception — Site dosyaları

Bu, Fransızca varsayılan dil ile açılan; Türkçe ve İngilizceye geçiş yapabilen, mobil uyumlu statik şirket tanıtım sitesidir.

## Dosyalar
- `index.html` — sayfa içeriği ve bölümler
- `style.css` — renkler, görünüm ve mobil düzen
- `script.js` — dil değiştirme, mobil menü, galeri büyütme ve teklif formu
- `assets/` — görsel dosyaları

## Önemli bilgiler
- Telefon: +32 472 74 33 74
- E-posta: saprojectsrl@gmail.com
- WhatsApp: bu numaraya bağlı bağlantı
- Fiyatlar: sabit fiyat uydurulmadı; “talep üzerine teklif” gösterilir.
- Müşteri yorumları: gerçek yorum verilmediği için sahte yorum eklenmedi.
- Galeri fotoğrafları örnek görsellerdir; gerçek şirket projelerini temsil ettiği iddia edilmez.
- Teklif formu bir sunucuya veri göndermez. Ziyaretçinin e-posta uygulamasını açarak önceden doldurulmuş e-posta hazırlar. Otomatik gönderim veya kayıt yoktur.
- Logo alanı şu an metin tabanlı SA+ yer tutucusudur. Daha sonra logoyu değiştirebilirsiniz.

## Düzenleme
Metinleri `index.html` ve `script.js` dosyalarında düzenleyin. Renk ve görünümü `style.css` dosyasından değiştirin. Fotoğrafları `assets/` klasöründeki aynı isimli dosyalarla değiştirirseniz tasarımda yolları değiştirmeniz gerekmez.

## Ücretsiz yayınlama: GitHub Pages
1. GitHub hesabı açın veya giriş yapın: https://github.com
2. Yeni bir **public** repository oluşturun; örneğin `sa-conception-site`.
3. Bu ZIP içindeki dosyaları çıkarın ve tüm dosyaları/`assets` klasörünü repository'nin kök dizinine yükleyin. `index.html` kök dizinde olmalı.
4. Repository içinde **Settings → Pages** bölümüne gidin.
5. **Build and deployment** altında **Deploy from a branch** seçin. Branch olarak `main`, klasör olarak `/ (root)` seçip kaydedin.
6. Birkaç dakika sonra GitHub Pages bir adres verir: `https://KULLANICI-ADIN.github.io/sa-conception-site/`
7. Sonraki değişikliklerde dosyaları repository'ye tekrar yükleyin veya GitHub'da düzenleyin.

GitHub Pages, GitHub Free planında public repository için ücretsiz statik site barındırır. Kendi alan adını da bağlamak mümkündür. Ayrıntılar:
https://docs.github.com/en/pages/getting-started-with-github-pages

## Kendi .be alan adını bağlama
Özel alan adı ücretsiz değildir ve yıllık yenileme ücreti vardır. 30 €/yıl bütçede, uygun fiyatlı bir `.be` alan adı + GitHub Pages barındırma hedeflenebilir; kayıt sırasında KDV, promosyon ve yenileme ücretlerini kontrol edin.
1. Bir alan adı kayıt şirketinden kullanılabilir bir ad satın alın.
2. GitHub repository → **Settings → Pages → Custom domain** alanına alan adını girip kaydedin.
3. Kayıt şirketinin DNS panelinde GitHub'ın güncel yönergelerine göre DNS kayıtlarını girin. `www` için CNAME gerekebilir; kök alan adı için GitHub'ın belirttiği A kayıtları kullanılır.
4. DNS değişikliklerinin yayılması 24 saate kadar sürebilir. HTTPS seçeneğini açın.
5. DNS kayıtlarını ayarlamadan önce GitHub Pages tarafına alan adını ekleyin; yanlış sıralama güvenlik riskleri oluşturabilir.

GitHub'ın resmi özel alan adı rehberi:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Yayınlamadan önce kontrol listesi
- [ ] Gerçek şirket logosunu ekleyin.
- [ ] Galeri görsellerini kendi projelerinizle değiştirin veya örnek olduklarını açıkça koruyun.
- [ ] Hizmet kapsamı, lisanslar ve 7/24 müsaitlik ifadelerini doğrulayın.
- [ ] İşletme adresi, şirket kayıt numarası/KDV numarası gibi gerekli yasal bilgileri ve gizlilik/çerez gereksinimlerini gerekirse ekleyin. Bu bilgiler verilmediği için siteye uydurma bilgi konmadı.
- [ ] Formu telefonda ve bilgisayarda test edin. Form yalnızca ziyaretçinin e-posta uygulamasını açar.
- [ ] Kendi alan adını almadan önce adın uygunluğunu ve yenileme ücretini kontrol edin.

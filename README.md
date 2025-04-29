# 🛒 Alışveriş Listesi Uygulaması

Bu proje, kullanıcıların alışveriş listelerini kolayca yönetebilecekleri modern ve kullanıcı dostu bir web uygulamasıdır.

## 🌟 Özellikler

- **Öğe Ekleme**: Tek tıklamayla yeni alışveriş öğeleri ekleyebilirsiniz
- **Düzenleme**: Öğeleri tıklayarak anında düzenleyebilirsiniz
- **Tamamlama İşaretleme**: Alınan öğeleri işaretleyebilirsiniz
- **Filtreleme Seçenekleri**: 
  - Tüm öğeleri görüntüleme
  - Sadece tamamlanmamış öğeleri görüntüleme
  - Sadece tamamlanmış öğeleri görüntüleme
- **Yerel Depolama**: Listeniz tarayıcınızda otomatik olarak kaydedilir
- **Silme**: Tek öğe silme veya tüm listeyi temizleme seçenekleri

## 🛠️ Kullanılan Teknolojiler

- **HTML5**: Sayfa yapısı için
- **CSS3**: Özelleştirilmiş stil ve animasyonlar için
- **JavaScript**: Dinamik işlevsellik için
- **Bootstrap 5.3.3**: Modern ve responsive tasarım için
- **Bootstrap Icons 1.11.3**: Şık ikonlar için
- **LocalStorage API**: Veri depolama için

## 🚀 Kurulum

1. Projeyi bilgisayarınıza klonlayın:
```bash
git clone [https://github.com/keremzytn/Shopping-List.git]
cd shopping-list
```

2. `index.html` dosyasını bir web tarayıcısında açın

## 💡 Kullanım

1. Yeni öğe eklemek için üst kısımdaki input alanına öğe adını yazın ve '+' butonuna tıklayın
2. Öğeyi düzenlemek için öğe metnine tıklayın
3. Öğeyi tamamlandı olarak işaretlemek için checkbox'ı işaretleyin
4. Öğeyi silmek için üzerine geldiğinizde görünen çarpı (×) ikonuna tıklayın
5. Listeyi filtrelemek için üst kısımdaki filtreleme butonlarını kullanın
6. Tüm listeyi temizlemek için 'Clear' butonunu kullanın

## 🔒 Veri Saklama

Uygulama, alışveriş listenizi tarayıcınızın LocalStorage'inde saklar. Bu sayede:
- Tarayıcıyı kapattığınızda verileriniz kaybolmaz
- Herhangi bir sunucu veya veritabanı gerektirmez
- Verileriniz sadece sizin cihazınızda kalır

## 🎨 Özelleştirme

Uygulamanın görünümünü `style.css` dosyasından özelleştirebilirsiniz:
- Renk şeması
- Yazı tipleri
- Boşluklar ve kenar yumuşatmaları
- Animasyonlar

## 📱 Responsive Tasarım

Uygulama, Bootstrap grid sistemi sayesinde tüm ekran boyutlarında düzgün çalışır:
- Mobil cihazlar
- Tabletler
- Masaüstü bilgisayarlar
🚀 Öne Çıkan Özellikler
✨ İnteraktif 3D Arka Plan: Fare hareketlerinize tepki veren, Three.js ile hazırlanmış göz alıcı parçacık animasyonu.

📱 %100 Mobil Uyumlu (Responsive): Telefondan masaüstüne kadar tüm cihazlarda kusursuz bir deneyim sunar.

🍔 Fonksiyonel Mobil Menü: Küçük ekranlar için şık ve kullanışlı bir "hamburger" menü.

📜 Akıcı Kaydırma Animasyonları: Sayfa kaydırıldıkça beliren zarif animasyonlarla dinamik bir görünüm.

🎨 Kolay Özelleştirme: CSS değişkenleri ve iyi organize edilmiş kod yapısı sayesinde renkleri, metinleri ve komutları kolayca değiştirin.

🔍 Canlı Komut Arama: Kullanıcıların komutlarınızı anında bulmasını sağlayan interaktif arama çubuğu.

🧩 Hazır Bölümler: Özellikler, Üyelik Paketleri, Sıkça Sorulan Sorular ve detaylı Footer gibi tüm gerekli bölümler hazır gelir.

⚙️ Hafif ve Hızlı: Gereksiz kütüphaneler olmadan, saf HTML, CSS ve JavaScript ile yüksek performans sunar.

🛠️ Kullanılan Teknolojiler
HTML5: Web sitesinin temel yapısı.

Tailwind CSS: Modern ve mobil uyumlu tasarım için CSS çatısı.

JavaScript (ES6+): Animasyonlar, komut arama ve mobil menü gibi interaktif özellikler için.

Three.js: Arka plandaki 3D parçacık animasyonu için JavaScript kütüphanesi.

🔧 Kurulum ve Kullanım
Bu şablonu kullanmak son derece basittir. Herhangi bir derleme veya kurulum işlemi gerektirmez.

Bu repoyu klonlayın veya ZIP olarak indirin:

Bash

git clone https://github.com/vkaiber/botsites1
index.html dosyasını favori kod düzenleyicinizde (örn: VS Code) açın.

Metinleri, başlıkları, komut listesini ve bağlantıları kendi projenize göre düzenleyin.

Dosyaları herhangi bir statik web sunucusuna (Netlify, Vercel, GitHub Pages veya kendi hostinginiz) yükleyin.

Hepsi bu kadar! Web siteniz artık yayında.

🎨 Özelleştirme
Şablonu kendi markanıza uyacak şekilde kolayca özelleştirebilirsiniz.

Renkler: Ana renkleri değiştirmek için index.html dosyasının <style> etiketi içindeki :root bölümünü düzenleyin:

CSS

:root {
    --primary-color: #38bdf8; /* Ana Renk */
    --secondary-color: #34d399; /* İkincil Renk */
    /* ... diğer renkler */
}

  - **Metinler ve Başlıklar:** Tüm metinler doğrudan `index.html` dosyası içinde bulunmaktadır.
  - **Komutlar:** Komut listesini ve arama fonksiyonunu düzenlemek için `index.html` dosyasının en altındaki `<script>` etiketi içinde bulunan `commands` dizisini güncelleyin:
    ```javascript
    const commands = [
        { name: '/yeni-komut', desc: 'Bu yeni bir komuttur.', category: 'GENEL', premium: false },
        // ... diğer komutlar
    ];
    ```

-----

## 🤝 Katkıda Bulunma

Katkılarınız projeyi daha da iyi hale getirecektir\! Lütfen bir "Pull Request" göndermekten veya "Issue" açmaktan çekinmeyin.

1.  Projeyi Fork'layın.
2.  Yeni bir özellik dalı oluşturun (`git checkout -b ozellik/yeni-bir-ozellik`).
3.  Değişikliklerinizi Commit'leyin (`git commit -m 'Yeni bir özellik eklendi'`).
4.  Dalınızı Push'layın (`git push origin ozellik/yeni-bir-ozellik`).
5.  Bir Pull Request açın.

-----

## 📄 Lisans

Bu proje **MIT Lisansı** altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına göz atın.

-----

## ✉️ İletişim

Burak – www.linkedin.com/in/burakacr – burakabdacr@gmail.com

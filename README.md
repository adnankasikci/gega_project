## GEGA Movie Web Site with Tailwind

Tailwind yaklaşımlarına aşinalık ve tailwind teknolojisini anlama. https://tailwind-batman.netlify.app/


#### Proje Amacı
---

Bu projede tailwind konularına daha iyi hakim olabilmek için farklı örnekleri de görebilme adına hazırlanmış bir web sitedir.

- Teknoloji yapısını iyi anlamak
- Kullanılan yapılara aşina olmak
- Tailwind folder structure ile çalışma mantığını anlamak
- Tailwind tema desteği ile çalışmak
- Tailwind.config.js pratikleri ile işleyiş mantığı


#### Kullanılanlar
---

- Hover visited active focus hareketleri ile çalışma
- Değişkenlerle çalışma ve first mobile class yapıları ile çalışma
- Tailwind ve kütüphanelerin iç içe kullanımı
- Responsive uyumlu tasarım

## Kurulum

Projenin kurulumu için aşağıdaki adımları izleyin:

1. Proje dosyalarını bilgisayarınıza indirin veya klonlayın.
2. Terminali açın ve proje dizinine gidin: `cd proje-klasoru`.
3. Gerekli bağımlılıkları yüklemek için `npm install` komutunu çalıştırın.
4. Projeyi çalıştırmak için `npm start` komutunu kullanın.
5. Tarayıcınızda `http://localhost:3000` adresine gidin ve projeyi görüntüleyin.

## Kullanım

Proje kullanımıyla ilgili aşağıdaki detayları göz önünde bulundurun:

- Proje ana sayfasında mevcut olan örnekleri inceleyebilirsiniz.
- Proje yapısını ve kullandığımız tailwind tekniklerini inceleyerek çalışma mantığını anlayabilirsiniz.
- Açıklamaları takip edin ve kavrayın.
- Proje dosyalarında `tailwind.config.js` ile projeyi yönetin  `npm run watch` ile projeyi çalıştırın.

```json
>>package.json

//Kullanımı

"scripts": {
    "watch": "npx tailwindcss -i ./input.css -o ./public/css/style.css --watch"
},

```

## Katkıda Bulunma

Eğer projeye katkıda bulunmak isterseniz, lütfen aşağıdaki adımları takip edin:

1. Bu projeyi fork edin.
2. Yeni bir dal oluşturun: `git checkout -b feature/yeni-ozellik`.
3. Yaptığınız değişiklikleri işleyin: `git commit -am 'Yeni özellik ekle'`.
4. Dalınıza itme yapın: `git push origin feature/yeni-ozellik`.
5. Pull Request göndermek için GitHub üzerinden talep oluşturun.

## İletişim

Herhangi bir sorunuz, öneriniz veya geri bildiriminiz varsa, lütfen göndermekten çekinmeyin.:relieved:

Daha fazla bilgi için [proje dokümantasyonunu](https://github.com/ad0pa/talwindfirst) ziyaret edin.

Teşekkür ederiz!

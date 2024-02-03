# Laravel Projesi README

Bu README dosyası, Laravel projesini başlatmak ve temel adımları gerçekleştirmek için bir rehber sunmaktadır.

## Başlangıç

1. **Gereksinimler:**
   - PHP 7.4 veya daha üstü
   - Composer (https://getcomposer.org/)
   - Node.js ve NPM (https://nodejs.org/)
   
Before creating your first Laravel project, make sure that your local machine has PHP and Composer installed. If you are developing on macOS, PHP and Composer can be installed in minutes via Laravel Herd. In addition, we recommend installing Node and NPM.

2. **Proje Klonlama:**
 ```
 composer create-project laravel/laravel example-app
 ```

3. **Composer Bağımlılıklarını Yükleme:**

5. **Uygulama Anahtarını Oluşturma:**

10. **Sunucuyu Başlatma:**
 ```
 cd example-app
 php artisan serve
 ```

## Kullanım

Projeniz başarıyla başladıktan sonra tarayıcınızda `http://localhost:8000` adresine giderek uygulamanızı görebilirsiniz.

## Controller Ekleme
 ```
 php artisan make:controller PageController
 ```
CRUD, ingilizce Create(Oluştur)-Read(Oku)-Update(Güncelle)-Delete/Destroy(Sil) Methodlarıyla beraber oluştur.
 ```
 php artisan make:controller PageController --resource
 ```
Controller ve Modeli Birlikte Oluşturma.
 ```
 php artisan make:controller PageController --resource --model=PageModel
 ```


## Katkıda Bulunma

Eğer projeye katkıda bulunmak istiyorsanız lütfen [CONTRIBUTING.md](CONTRIBUTING.md) dosyasını inceleyin.

## Lisans

Bu proje [MIT lisansı](LICENSE) altında lisanslanmıştır. Detaylı bilgi için lütfen lisans dosyasını inceleyin.

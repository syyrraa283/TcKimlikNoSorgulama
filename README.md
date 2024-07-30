# TcKimlikNoSorgulama
Php için T.C. Kimlik No Sorgulama API

Kullanımı:

```php
<?php
require_once("TcKimlikNoSorgula.php");

if (TcKimlikNoSorgula::tcKimlikNo ('Geçersiz')
    ->ad ('Batuhan')
    ->soyad('Akpınar')
    ->dogumYili('2008')
    ->sorgula()) {
    echo 'Doğrulandı';
} else {
    echo 'Geçersiz';
}
```

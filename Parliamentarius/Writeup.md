1. Проверяем порты и службы на данном хосте ![Безымянный](https://user-images.githubusercontent.com/91682600/155879995-f70bbf73-4a6d-4d8d-9d1e-5edd01aa5992.png)
2. Попробуем подключиться к ftp. Замечаем, что развернут ProFTPD версии 1.3.5![2022-02-26_19-39-13](https://user-images.githubusercontent.com/91682600/155880064-5abaad88-eee1-4573-90f0-821d1c42b26a.png)
3. Чекаем уязвимости ![2022-02-27_14-14-40](https://user-images.githubusercontent.com/91682600/155880230-aa01263d-3c22-4df0-bb81-3dd22f7d181b.png)
4. Изучем материал http://www.proftpd.org/docs/contrib/mod_copy.html
5. Учитывая необходимость получения ssh key для последующей организации ssh подключения, пытаемся скопировать файл, хранящий нужное нам (зная стандартную файловую стркутуру linux)![2022-02-26_19-39-13](https://user-images.githubusercontent.com/91682600/155880326-64d19698-dba4-4704-9fbd-4d1e7606e368.png)
6. Примонтируем  /var/tmp 

![2022-02-26_19-43-29](https://user-images.githubusercontent.com/91682600/155880459-365a6db1-773c-4ba0-a7ba-8f97e7237b21.png)

7. Копируем к примонтированному образу файл и ключом ssh и выдаем разрешения. Подключаемся! 
![2022-02-26_19-45-03](https://user-images.githubusercontent.com/91682600/155880491-99e54d81-de57-4b0f-9d8a-4ffb7fc53d95.png)

9. Дело техники 

![2022-02-26_19-46-00](https://user-images.githubusercontent.com/91682600/155880498-78530d4f-5456-4798-8226-8ec9c9cba09d.png)

Бежим шантажировать kenobi)

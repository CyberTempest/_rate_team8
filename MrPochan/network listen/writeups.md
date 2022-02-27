Для решения таска открывает файл pcap в wireshark
![image](https://user-images.githubusercontent.com/91623411/139254475-7296d6d7-d08f-4356-9724-a297e633f295.png)
Затем смотри все потоки в Статистика - Диалоги - TCP
![image](https://user-images.githubusercontent.com/91623411/139254532-e5d5b0ae-a9b4-4663-9aa0-3d57fef0c220.png)
Находим самый подозрительный поток (самый большой по размеру)
![image](https://user-images.githubusercontent.com/91623411/139254630-e1fee602-078c-4867-a5f4-d60ceb3aefd0.png)
Отслеживаем весь поток
![image](https://user-images.githubusercontent.com/91623411/139254697-b0edd875-400f-4d82-a794-28517bcf749a.png)
Видими, что это торрент файл, и что-то про флаг. Это нам и надо. Сохраняем данный поток, чтобы он был как файл .torrent и запускаем через любой торрент.
![image](https://user-images.githubusercontent.com/91623411/139254751-d3d3c9f4-dd94-4439-be72-f4de5b878c9c.png)
А вот и флаг!
![image](https://user-images.githubusercontent.com/91623411/139254915-19ae31c0-c14f-407e-8579-d992255889e4.png)

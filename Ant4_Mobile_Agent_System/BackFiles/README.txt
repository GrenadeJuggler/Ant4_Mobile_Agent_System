Для пользования Софтом на установке необходимо в файле JetServer_v16.py 
1)в методе DefaultCamera сменить Cam.Sourse с 1 на 0
2)запустить программу
3)настроить адрес камер в соответствующем разделе настроек "Camera settings"
4)при надобности изменить адрес файла с настройкой
5)убрать всех роботов с полигона и лишние объекты. надать кнопку на главной странице "Remember plate without bots"
5)добавить необходимое количество роботов JetBot в разделе настройки роботов "Robot settings"
6)запустить на роботах программу App_Bot_Part.py, предварительно настроив в программе ip адрес компьютера и порт, к которому будет производиться подключение.
7)после загрузки программ ввести в компьютере в разделе "Robot settings" адреса роботов и номер их ArUco-меток.
8)переместить роботов на полигон
9)в разделе "Goal settings" изменить точки следования роботов
10)выбрать режим движения роботов на главной странице
11)нажать Start

Перечень материалов:
 
JetServer_v16.py - программное обеспечение серверной части для натурной реализации системы

App_Bot_Part.py - программное обеспечение мобильного робота Jetbot для натурной реализации системы

App_PhotoAndCalibrate.py - вспомогательная программа для установки параметров обработки изображения камеры на серверной части системы

Calibrate720_new.npy - файл, содержащий матрицу преобразования для обработки изображения 1, 2 и 3 камеры

Calibrate720_new_4.npy - файл, содержащий матрицу преобразования для обработки изображения 4 камеры

Cut720_new_1.txt; Cut720_new_2.txt; Cut720_new_3.txt; Cut720_new_4.txt - файлы, содержащие параметры обработки изображений камер, соответствующей номеру

Chess_Photo.jpg - пример фотографии шахматной доски для создания матрицы преобразования изображения.

Подключение к мобильному роботу для запуска программы на нём возможно реализовать при помощи протокола удалённого доступа SSH
IP-адреса для подключения к камерам: 192.168.0.91 - 192.168.0.94, порт чаще всего используется 8008
Формат адреса для ввода в программу: http://192.168.0.94:8008

Контакты разработчика: 
Почта. big-max@inbox.ru
Контактный телефон. +7(916)390-42-00
Vkontakte. https://vk.com/funny_pangolin
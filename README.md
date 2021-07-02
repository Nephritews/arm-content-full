### Документ для автоматизированной системы «АРМ контент-менеджера»
# Создание и редактирование инфоблока.
* Дерево разделов http://172.16.31.17/#/login.

### Информационные блоки - модуль, позволяющий каталогизировать и управлять различными типами (блоками) однородной информации. С помощью информационных блоков может быть реализована публикация различных типов динамической информации на сайте.
#  1. Создание и редактирование инфоблока.
Описание структуры инфоблоков ARM. Создание инфоблока. Заполнение основной информации инфоблока. Для добавления нового инфоблока нажмите на оранжевую кнопку с плюсом. После чего в появившемся окне необходимо заполнить основные поля. По умолчанию открывается вкладка с базовой настройкой. 

* 1.1 Откройте страницу, инфоблоки в левом углу в оранжевом круге кнопка плюс (нажмите на кнопку плюс, добавить новый раздел).  
![123](https://user-images.githubusercontent.com/85296765/120967252-f0ca0200-c76f-11eb-8fca-a0d27f01c2c6.png)
* 1.2 Заполните поля формы редактирования инфоблока (см. далее).
* 1.3 > Настройка 2 > Seo 3 > Свойства 4 > Свойства разделов 5 > Свойства элементов > Элементы
![234](https://user-images.githubusercontent.com/85296765/120969954-6e434180-c773-11eb-98b3-22da86695dab.png)
# 2.0 Настройки
Настройка - базовая настройка инфоблока. Название - данное поле является основным названием для инфоблока и используется для его идентификации. Код - генерируется автоматически на основе названия и использует латинские символы (обязательны для заполнения). Предназначено для идентификации инфоблока и формирования роутинга. Родительский элемент - список родительских инфоблоков, предназначенная для организации древовидной структуры разделов и подразделов. Также имеются дополнительные вкладки для заполнения, такие как: "SEO", "Свойства", "Cвойства разделов", "Свойство элементов". В них находится основная информация как о инфоблоке, так и об элементах, которые в нем располагаются.
* 2.1 Настройки > Ввод названия.
![120975463-ec0a4b80-c779-11eb-8561-8bd1af0f26ef](https://user-images.githubusercontent.com/85296765/122352276-09040300-cf60-11eb-8ab4-aa10ed3aaa78.png)
* 2.2 Настройки > Сгенерировать > Код.  Код - генерируется автоматически на основе названия и использует латинские символы (обязательны для заполнения).
![сгенерировать](https://user-images.githubusercontent.com/85296765/120984543-6db2a700-c783-11eb-84e4-37ab8589f663.png)
* 2.3. Настройки > Родительский контроль > При указании каталога дочерним он будет использовать свойства каталога.  
![родительский контроль](https://user-images.githubusercontent.com/85296765/120984358-43f98000-c783-11eb-91a5-1ac40fe05151.png)
* 2.4 Родительский контроль описание кнопок (при выборе пропадают вкладки свойства, свойства разделов, свойства элементов). Дочерний элемент использует свойства разделов элементов родительского каталога. Родительский элемент, указывается при отсутствии элементов у каталога.
![suk](https://user-images.githubusercontent.com/85296765/121004799-c55b0d80-c797-11eb-8165-3a44629ef772.png)
# 3.0 SEO
SEO- 3 поля принимают в себя значения для последующего отображения на тег <head> области сайта. Вкладка "SEO" имеет следующие параметры для заполнения:
Title - свойство раздела отображаемое в метатегах. При отсутствии заполнения данного свойства будет отображено либо title родительского элемента, либо title по умолчанию.
Keywords и Description использует аналогичную с title механику. Все SEO свойства являюся независисмыми. При необходимости можно заполнить только одно из них, которое будет использоваться на сайте. Остальные свойства будут взяты из родительского элемента, либо глобальное, используемое по умолчанию. Данные вводятся, используя только латинские символы.
* 3.1 SEO > Title > Заглавие > Keywords > Ключевые слова > Description > Описание
![23](https://user-images.githubusercontent.com/85296765/121013804-fc362100-c7a1-11eb-964c-7e6926f5a34e.png)
# 4.0 Свойства
Свойства — значения каждого элемента. Во вкладке свойства представлены заполняемые значения свойств, принадлежащие разделам. Данные свойства создаются во вкладке свойства разделов. В свойствах содержится информация заполняемая для каждого раздела отдельно. Данные вводятся, используя только латинские символы.
* 4.1 Название: ID > Тип: Число > Значение
![23](https://user-images.githubusercontent.com/85296765/121012283-3b637280-c7a0-11eb-912f-b46ca71c0311.png)
# 5.0 Свойства разделов
Свойства разделов - это вкладка с созданием свойств. Во вкладке свойства разделов предоставлен функционал по созданию свойств с присвоением типов. Название - это уникальный код, привязанный к свойству. Название свойства повторяться не должно. Для добавления нового свойства необходимо нажать на оранжевую кнопку с плюсом и заполнить данные нового свойства. Данные вводятся, используя только латинские символы.
* 5.1 Название: ID > Тип: Число, Строка > Оранжевая кнопка с плюсом, добавить новый раздел.
![23](https://user-images.githubusercontent.com/85296765/121014412-9eee9f80-c7a2-11eb-8c5d-22a5ac98b43b.png)
# 6.0 Свойства элементов
Свойства элементов - значение каждого раздела, которые создали (заполнение тех. свойств). Во вкладке свойства элементов предоставлен функционал по созданию свойств для новых и уже существующих элементов с присвоением типов. Название свойств элементов является ключевым и не должно повторяться. Для добавления нового свойства необходимо нажать на оранжевую кнопку с плюсом и заполнить с последующим присвоением типа свойства. 
* 6.1 Оранжевая кнопка с плюсом, добавить новый раздел.
![свойства элементов +](https://user-images.githubusercontent.com/85296765/120997680-1404a980-c790-11eb-926e-d0b35d2ff73c.png)
* 6.2 Название: ID > Тип: Число, Строка 
![23](https://user-images.githubusercontent.com/85296765/121011199-04409180-c79f-11eb-9a18-21c83eb54ae8.png)
# 7.0 Элементы
Элементы - товары в поисковой строке: настройка и свойства (базовая информация об элементах). Во вкладке элементы - оранжевая кнопка с плюсом. При нажатии всплывает вкладка новый элемент в ней вкладка настройки с названием и кодом элемента. Название - данное поле является основным названием для инфоблока и используется для его идентификации. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (код генерируется на основе названия). Вкладка свойства берёт информацию от первого родителя.
* 7.1 Оранжевая кнопка с плюсом, добавить новый раздел.
![оранд](https://user-images.githubusercontent.com/85296765/120998556-de13f500-c790-11eb-8f03-86c343d5eaf3.png)
* 7.2 Новый элемент
![оранд2](https://user-images.githubusercontent.com/85296765/120998822-1ca9af80-c791-11eb-9bd6-b87ec5fcbf90.png)
* 7.3 Настройки
![оранд3](https://user-images.githubusercontent.com/85296765/120998981-46fb6d00-c791-11eb-9734-ed9e2b066895.png)
* 7.4 Название
![23](https://user-images.githubusercontent.com/85296765/123255913-69b3b280-d501-11eb-81e7-981fbf4c4bed.png)
* 7.5 Сгенери́руйте код (код генерируется на основе названия).
![24](https://user-images.githubusercontent.com/85296765/123255940-720bed80-d501-11eb-8b23-a330f40a7d5d.png)
* 7.6 Введите свойства. Имеется два типа свойств: Приоритет (PRIORITY) (работает с лева на право) и Ссылка (LINK) (берёт информацию от первого родителя). Значение — заполните при потребности.
![25](https://user-images.githubusercontent.com/85296765/123255965-76d0a180-d501-11eb-9b45-257e6f8b3caf.png)
## 8.0 Обновление данных.
Обновление вкладок инфоблока.
* 8.1 При изменение каталогов элементов появляется иконка, указывающая о изменение.
![MicrosoftTeams-image (2)](https://user-images.githubusercontent.com/85296765/122168014-cc1b0c00-ce8c-11eb-8f92-3c94dca705b5.png)
* 8.2 При переходе на новую страницу обновления не будут сохранены.
![обнова 23](https://user-images.githubusercontent.com/85296765/122167531-2cf61480-ce8c-11eb-8edf-f24b994207c9.png)
## 9.0 Удаление данных.
* 9.1 Удаление инфоблока. Во вкладке элементы обязательно удалить элемент и только после этого переходить к удалению инфоблока (стоит защита).
![Безымянный11](https://user-images.githubusercontent.com/85296765/124229304-739b6e00-db1e-11eb-8dfc-332a068bc50e.png)
![Безымянный11](https://user-images.githubusercontent.com/85296765/124248702-2a561900-db34-11eb-804b-f31394d03a1c.png)





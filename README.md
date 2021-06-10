Инструкция
для автоматизированной системы
«АРМ контент-менеджера»
# Создание и редактирование инфоблока.
* Дерево разделов http://172.16.31.16/#/sections
## Содержание
# 1. Создание и редактирование инфоблока.
1.1 Создание нового раздела в инфоблоках.  
1.2 Заполнение полей, форм редактирования инфоблока (см. далее).  
1.3 1> Настройка 2> Seo 3> Свойства 4> Свойства разделов 5> Свойства элементов> Элементы   
# 2.0 Настройки  
2.1 Настройки > Ввод названия  
2.2 Настройки > Сгенерировать > Код
2.3. Настройки > Родительский контроль > При указании каталога дочерним он будет использовать свойства каталога.  
2.4 Родительский контроль описание кнопок.  
# 3.0 SEO  
3.1 SEO > Title > Заглавие > Keywords > Ключевые слова > Description > Описание  
# 4.0 Свойства  
4.1 Название: ID > Тип: Число > Значение  
# 5.0 Свойства разделов  
5.1 Название: ID > Тип: Число, Строка > Оранжевая кнопка с плюсом, добавить новый раздел.  
# 6.0 Свойства элементов  
6.1 Оранжевая кнопка с плюсом, добавить новый раздел.  
6.2 Название: ID > Тип: Число, Строка  
# 7.0 Элементы  
7.1 Оранжевая кнопка с плюсом, добавить новый раздел.
7.2 Новый элемент  
7.3 Настройки  
7.4 Название  
7.5 Сгенерировать код  
7.6 Свойства  
# 8.0 Товары в поисковой строке  
8.1 1 > Настройка 2 > Seo 3 > Свойства 4 > Свойства разделов 5 > Свойства элементов 6 > Элементы  
8.2 Настройка  
8.3 SEO  
8.4 Свойства разделов  
8.5 Свойства элементов  
8.6 Элементы  
8.7 Флюкостат  
8.8 Свойства  
#  1. Создание и редактирование инфоблока.
Описание структуры инфоблоков ARM. Создание инфоблока. Заполнение основной информации инфоблока. Для добавления нового инфоблока нажмите на оранжевую кнопку с плюсом. После чего в появившемся окне необходимо заполнить основные поля. По умолчанию открывается вкладка с базовой настройкой.  

* 1.1 Откройте страницу, инфоблоки в левом углу в оранжевом круге кнопка плюс (нажмите на кнопку плюс, добавить новый раздел).  
![123](https://user-images.githubusercontent.com/85296765/120967252-f0ca0200-c76f-11eb-8fca-a0d27f01c2c6.png)
* 1.2 Заполните поля формы редактирования инфоблока (см. далее).
* 1.3 > Настройка 2 > Seo 3 > Свойства 4 > Свойства разделов 5 > Свойства элементов > Элементы
![234](https://user-images.githubusercontent.com/85296765/120969954-6e434180-c773-11eb-98b3-22da86695dab.png)
# 2.0 Настройки
Настройка - базовая настройка инфоблока. Название - данное поле является основным названием для инфоблока и используется для его идентификации. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы. Предназначено для идентификации инфоблока и формирования роутинга. Родительский элемент - список родительских инфоблоков, предназначенная для организации древовидной структуры разделов и подразделов. Также имеются дополнительные вкладки для заполнения,, такие как: "SEO", "Свойства", "Cвойства разделов", "Свойство элементов". В них находится основная информация как о инфоблоке, так и об элементах, которые в нем располагаются.
* 2.1 Настройки > Ввод названия 
![название](https://user-images.githubusercontent.com/85296765/120975463-ec0a4b80-c779-11eb-8561-8bd1af0f26ef.png)
* 2.2 Настройки > Сгенерировать > Код Код генерируется на основе названия.
![сгенерировать](https://user-images.githubusercontent.com/85296765/120984543-6db2a700-c783-11eb-84e4-37ab8589f663.png)
* 2.3. Настройки > Родительский контроль > При указании каталога дочерним он будет использовать свойства каталога.
![родительский контроль](https://user-images.githubusercontent.com/85296765/120984358-43f98000-c783-11eb-91a5-1ac40fe05151.png)
* 2.4 Родительский контроль описание кнопок (при выборе пропадают вкладки свойства, свойства разделов, свойства элементов). Дочерний элемент использует свойства разделов элементов родительского каталога. Родительский элемент, указывается при отсутствии элементов у каталога.
![suk](https://user-images.githubusercontent.com/85296765/121004799-c55b0d80-c797-11eb-8165-3a44629ef772.png)
# 3.0 SEO
SEO- 3 поля принимают в себя значения для последующего отображения на HEAD области сайта. Вкладка "SEO" имеет следующие параметры для заполнения:
Title - свойство раздела отображаемое в метатегах. При отсутствии заполнения данного свойства будет отображено либо title родительского элемента, либо title по умолчанию.
Keywords и Description использует аналогичную с title механику.
Все SEO свойства являюся независисмыми, При необходимости можно заполнить только одно из них которое будет использоваться на сайте, остальные свойства будут взяты из родительского элемента, либо глобальное, используемое по умолчанию.
* 3.1 SEO > Title > Заглавие > Keywords > Ключевые слова > Description > Описание
![23](https://user-images.githubusercontent.com/85296765/121013804-fc362100-c7a1-11eb-964c-7e6926f5a34e.png)
# 4.0 Свойства
Свойства — значения каждого элемента.
* 4.1 Название: ID > Тип: Число > Значение
![23](https://user-images.githubusercontent.com/85296765/121012283-3b637280-c7a0-11eb-912f-b46ca71c0311.png)
# 5.0 Свойства разделов
Свойства разделов - это вкладка с созданием свойств.
* 5.1 Название: ID > Тип: Число, Строка > Оранжевая кнопка с плюсом, добавить новый раздел.
![23](https://user-images.githubusercontent.com/85296765/121014412-9eee9f80-c7a2-11eb-8c5d-22a5ac98b43b.png)
# 6.0 Свойства элементов
Свойства элементов - значение каждого раздела которые создали (заполнение тех.свойств).
* 6.1 Оранжевая кнопка с плюсом, добавить новый раздел.
![свойства элементов +](https://user-images.githubusercontent.com/85296765/120997680-1404a980-c790-11eb-926e-d0b35d2ff73c.png)
* 6.2 Название: ID > Тип: Число, Строка 
![23](https://user-images.githubusercontent.com/85296765/121011199-04409180-c79f-11eb-9a18-21c83eb54ae8.png)
# 7.0 Элементы
Элементы - товары в поисковой строке настройка и свойства (базовая информация об элементах).
* 7.1 Оранжевая кнопка с плюсом, добавить новый раздел.
![оранд](https://user-images.githubusercontent.com/85296765/120998556-de13f500-c790-11eb-8f03-86c343d5eaf3.png)
* 7.2 Новый элемент
![оранд2](https://user-images.githubusercontent.com/85296765/120998822-1ca9af80-c791-11eb-9bd6-b87ec5fcbf90.png)
* 7.3 Настройки
![оранд3](https://user-images.githubusercontent.com/85296765/120998981-46fb6d00-c791-11eb-9734-ed9e2b066895.png)
* 7.4 Название
![орандж4](https://user-images.githubusercontent.com/85296765/120999116-6befe000-c791-11eb-8601-0e0577064ff9.png)
* 7.5 Сгенерировать код (код генерируется на основе названия)
![орандж5](https://user-images.githubusercontent.com/85296765/120999279-9cd01500-c791-11eb-8618-d07a8ee9d3df.png)
* 7.6 Свойства
![oranj](https://user-images.githubusercontent.com/85296765/121000481-f127c480-c792-11eb-9a95-71791b0a9f38.png)
## 8.0 Товары в поисковой строке
* 8.1 1 > Настройка 2 > Seo 3 > Свойства 4 > Свойства разделов 5 > Свойства элементов 6 > Элементы 
![234](https://user-images.githubusercontent.com/85296765/121192889-075a8100-c876-11eb-9f85-6ea4dc4fd0bc.png)
* 8.2 Настройка
![23](https://user-images.githubusercontent.com/85296765/121021814-710d5900-c7aa-11eb-82b0-af10da5513d6.png)
* 8.3 SEO
![23](https://user-images.githubusercontent.com/85296765/121022417-fb55bd00-c7aa-11eb-9149-8b9f6564cf7a.png)
* 8.4 Свойства разделов
![23](https://user-images.githubusercontent.com/85296765/121022607-250ee400-c7ab-11eb-8c53-511946cfa053.png)
* 8.5 Свойства элементов
![23](https://user-images.githubusercontent.com/85296765/121022948-7cad4f80-c7ab-11eb-8fbb-fd2b0211a972.png)
* 8.6 Элементы
![Безымянный](https://user-images.githubusercontent.com/85296765/121023090-9d75a500-c7ab-11eb-9703-834c148433dc.png)  
* 8.7 Флюкостат
![флюкостат](https://user-images.githubusercontent.com/85296765/121024042-84212880-c7ac-11eb-9aa7-a6b0a49974c8.png)  
* 8.8 Свойства
![флюкостат](https://user-images.githubusercontent.com/85296765/121026335-b2076c80-c7ae-11eb-9919-20a8b7d2eede.png)













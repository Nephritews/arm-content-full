# Пользовательская инструкция предназначена для контент-менеджеров сайта https://vitaexpress.ru (Вита-сайт). Инструкция описывает создание и редактирование инфоблоков «АРМ контент-менеджера» и регламентирует порядок действий, необходимых для решения задач по созданию, редактированию, обновлению, удалению инфоблока и его элементов на сайте. 

### Информационные блоки - модуль, позволяющий каталогизировать и управлять различными типами (блоками) однородной информации. С помощью информационных блоков может быть реализована публикация различных типов динамической информации на сайте.

# 1.0 Создание и редактирование инфоблока. Создание и редактирование инфоблока на сайте.

Описание структуры инфоблоков ARM. Создание инфоблока. Заполнение основной информации инфоблока. Для добавления нового инфоблока нажмите на оранжевую кнопку с плюсом. После чего в появившемся окне необходимо заполнить основные поля. По умолчанию открывается вкладка с базовой настройкой. 
* 1.1 Откройте страницу, инфоблоки в левом углу в оранжевом круге кнопка плюс (нажмите на кнопку плюс, добавить новый раздел).  
![123](https://user-images.githubusercontent.com/85296765/120967252-f0ca0200-c76f-11eb-8fca-a0d27f01c2c6.png)
* 1.2 Заполните поля формы редактирования инфоблока (см. далее).
* 1.3 > Настройка 2 > Seo 3 > Свойства 4 > Свойства разделов 5 > Свойства элементов > Элементы.
![234](https://user-images.githubusercontent.com/85296765/120969954-6e434180-c773-11eb-98b3-22da86695dab.png)
# 2.0 Настройки. Настройка базовых данных инфоблока на сайте.

Настройка - базовая настройка инфоблока. Название - данное поле является основным названием для инфоблока и используется для его идентификации. Код - генерируется автоматически на основе названия и использует латинские символы (обязательны для заполнения). Предназначено для идентификации инфоблока и формирования роутинга. Родительский элемент - список родительских инфоблоков, предназначенная для организации древовидной структуры разделов и подразделов. Также имеются дополнительные вкладки для заполнения, такие как: "SEO", "Свойства", "Cвойства разделов", "Свойство элементов". В них находится основная информация как о инфоблоке, так и об элементах, которые в нем располагаются.
* 2.1 Настройки > Ввод названия.
![120975463-ec0a4b80-c779-11eb-8561-8bd1af0f26ef](https://user-images.githubusercontent.com/85296765/122352276-09040300-cf60-11eb-8ab4-aa10ed3aaa78.png)
* 2.2 Настройки > Сгенерировать > Код.  Код - генерируется автоматически на основе названия и использует латинские символы (обязательны для заполнения).
![сгенерировать](https://user-images.githubusercontent.com/85296765/120984543-6db2a700-c783-11eb-84e4-37ab8589f663.png)
* 2.3. Настройки > Родительский контроль. При указании каталога дочерним он будет использовать свойства каталога.  
![родительский контроль](https://user-images.githubusercontent.com/85296765/120984358-43f98000-c783-11eb-91a5-1ac40fe05151.png)
* 2.4 Родительский контроль описание кнопок (при выборе пропадают вкладки свойства, свойства разделов, свойства элементов). Дочерний элемент использует свойства разделов элементов родительского каталога. Родительский элемент, указывается при отсутствии элементов у каталога.
![suk](https://user-images.githubusercontent.com/85296765/121004799-c55b0d80-c797-11eb-8165-3a44629ef772.png)
# 3.0 SEO. Вкладка для SEO специалистов.

SEO- 3 поля принимают в себя значения для последующего отображения на тег <head> области сайта. Вкладка "SEO" имеет следующие параметры для заполнения:
Title - свойство раздела отображаемое в метатегах. При отсутствии заполнения данного свойства будет отображено либо title родительского элемента, либо title по умолчанию.
Keywords и Description использует аналогичную с title механику. Все SEO свойства являюся независисмыми. При необходимости можно заполнить только одно из них, которое будет использоваться на сайте. Остальные свойства будут взяты из родительского элемента, либо глобальное, используемое по умолчанию. Данные вводятся, используя только латинские символы.
* 3.1 SEO > Title > Заглавие > Keywords > Ключевые слова > Description > Описание.
![23](https://user-images.githubusercontent.com/85296765/121013804-fc362100-c7a1-11eb-964c-7e6926f5a34e.png)
# 4.0 Свойства. Свойства инфоблоков на сайте.
	
Свойства — значения каждого элемента. Во вкладке свойства представлены заполняемые значения свойств, принадлежащие разделам. Данные свойства создаются во вкладке свойства разделов. В свойствах содержится информация заполняемая для каждого раздела отдельно. Данные вводятся, используя только латинские символы.
* 4.1 Название: ID > Тип: Число > Значение.
![23](https://user-images.githubusercontent.com/85296765/121012283-3b637280-c7a0-11eb-912f-b46ca71c0311.png)
# 5.0 Свойства разделов.
	
Свойства разделов - это вкладка с созданием свойств. Во вкладке свойства разделов предоставлен функционал по созданию свойств с присвоением типов. Название - это уникальный код, привязанный к свойству. Название свойств повторяться не должно. Для добавления нового свойства необходимо нажать на оранжевую кнопку с плюсом и заполнить данные нового свойства. Данные вводятся, используя только латинские символы.
* 5.1 Название: ID > Тип: Число, Строка > Оранжевая кнопка с плюсом, добавить новый раздел.
![23](https://user-images.githubusercontent.com/85296765/121014412-9eee9f80-c7a2-11eb-8c5d-22a5ac98b43b.png)
# 6.0 Свойства элементов. Значение каждого раздела на сайте.
	
Свойства элементов - значение каждого раздела, которые создали (заполнение тех. свойств). Во вкладке свойства элементов предоставлен функционал по созданию свойств для новых и уже существующих элементов с присвоением типов. Название свойств элементов является ключевым и не должно повторяться. Для добавления нового свойства необходимо нажать на оранжевую кнопку с плюсом и заполнить с последующим присвоением типа свойства. 
* 6.1 Оранжевая кнопка с плюсом, добавить новый раздел.
![свойства элементов +](https://user-images.githubusercontent.com/85296765/120997680-1404a980-c790-11eb-926e-d0b35d2ff73c.png)
* 6.2 Название: ID > Тип: Строка, Число, Текст , Файл, Дата, Изображение.
![23](https://user-images.githubusercontent.com/85296765/121011199-04409180-c79f-11eb-9a18-21c83eb54ae8.png)
# 7.0 Элементы. Создание элементов на сайте.
	
Элементы - товары в поисковой строке: настройка и свойства (базовая информация об элементах). Во вкладке элементы - оранжевая кнопка с плюсом. При нажатии всплывает вкладка новый элемент в ней вкладка настройки с названием и кодом элемента. Название - данное поле является основным названием для инфоблока и используется для его идентификации. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (код генерируется на основе названия). Вкладка свойства берёт информацию от первого родителя.
* 7.1 Оранжевая кнопка с плюсом, добавить новый раздел.
![оранд](https://user-images.githubusercontent.com/85296765/120998556-de13f500-c790-11eb-8f03-86c343d5eaf3.png)
* 7.2 При нажатии на новый элемент откроется окно с новым элементом.
![оранд2](https://user-images.githubusercontent.com/85296765/120998822-1ca9af80-c791-11eb-9bd6-b87ec5fcbf90.png)
* 7.3 Настройки.
![оранд3](https://user-images.githubusercontent.com/85296765/120998981-46fb6d00-c791-11eb-9734-ed9e2b066895.png)
* 7.4 Название.
![23](https://user-images.githubusercontent.com/85296765/123255913-69b3b280-d501-11eb-81e7-981fbf4c4bed.png)
* 7.5 Сгенерируйте код (код генерируется на основе названия) (обязательны для заполнения).
![24](https://user-images.githubusercontent.com/85296765/123255940-720bed80-d501-11eb-8b23-a330f40a7d5d.png)
* 7.6 Введите свойства. Имеется два типа свойств: Приоритет (PRIORITY) (работает с лева на право) и Ссылка (LINK) (берёт информацию от первого родителя). Значение — заполните при потребности.
![25](https://user-images.githubusercontent.com/85296765/123255965-76d0a180-d501-11eb-9b45-257e6f8b3caf.png) 
* 7.7 Нажмите сохранить
![123256949-97e5c200-d502-11eb-8b51-1c361be8d3b2](https://user-images.githubusercontent.com/85296765/124872706-a63dde80-dfd6-11eb-812b-adda7e671a22.png)
* 7.8 Поиск элемента. Навигация по списку элементов. Для поиска введите названия элемента в строку поиска (например, некст).
![Безымянный13](https://user-images.githubusercontent.com/85296765/125917600-dfdea83e-7405-483f-a63a-4345f5df868e.png)
* 8.0 Вкладка настройка.
![56](https://user-images.githubusercontent.com/85296765/123396897-e5ba0300-d5b2-11eb-9a38-257eb71d784a.png)
* 8.1 Вкладка элементы.
![Безымянный12](https://user-images.githubusercontent.com/85296765/125931157-1e07e099-3433-49ec-899c-18958b4f0742.png)
* 8.2 Для того чтобы элемент или раздел отображался на сайте задайте ему временной диапазон.
![Безымянный11](https://user-images.githubusercontent.com/85296765/124233764-3cc85680-db24-11eb-9460-d4b59f5a910f.png)
![Безымянный11](https://user-images.githubusercontent.com/85296765/124234910-b280f200-db25-11eb-8bc4-17a6eef38ff1.png)
* 8.3 Если поля даты и времени будут пустыми, элемент по умолчанию будет показываться.
![Безымянный11](https://user-images.githubusercontent.com/85296765/124233995-84e77900-db24-11eb-93ca-8bad98ad437a.png)
* 8.4 Если не доступен сам ифоблок, то всё вложенные в него элементы тоже, вне зависимости от активности внутренних элементов.
# 9.0 Обновление данных. Обновление вкладок инфоблока. Обновление вкладок инфоблока на сайте.
  Для изменения свойств элемента перейдите во вкладку раздела "Элементы". Далее, выбрав элемент из списка, необходимо на него нажать, после появления элемента в модальном окне, изменить данные во вкладке "Свойства". На примере раздела "Товары в поисковой строке" заполняемыми свойствами являются 2 свойства: Приоритет (PRIORITY) (работает с лева на право) и Ссылка (LINK) (берёт информацию от первого родителя). Приоритетность отвечает за место расположения в поисковой строке. Ссылка формируется от корня сайта: vitaexpress.ru/LINK. Переход на сторонние под домены не предусматривается данным функционалом.
* 9.1 Для навигации по списку элементов предусмотрена пагинация и поиск элементов.
  ![Безымянный54](https://user-images.githubusercontent.com/85296765/124459004-bd928700-dd9e-11eb-9691-590608fd47ca.png)
* 9.2 При изменение каталогов элементов появляется иконка, указывающая о изменение.
 ![Безымянный24](https://user-images.githubusercontent.com/85296765/124458555-2af1e800-dd9e-11eb-8101-67501871d03c.png)
* 9.3 При редактировании одного и более элементов перед переходом на новую страницу необходимо сохранить все текущие изменения, как показано на рисунке ниже. 
  ![Безымянный23](https://user-images.githubusercontent.com/85296765/124459396-21b54b00-dd9f-11eb-87b9-4574c34ef877.png)
*  9.4 При обновлении списка несохраненные изменения будут потеряны, продолжить? Если хотите сохранить данные нажмите "Отмена" либо не сохранять данные нажмите "ОК".
![Безымянный23](https://user-images.githubusercontent.com/85296765/124457583-01848c80-dd9d-11eb-9fa1-3bd57e1394b9.png)
# 10.0 Удаление данных. Удаление данных на сайте.
* 10.1 Удаление инфоблока. Элементы удаляются по отдельности. Для удаления элемента нужно нажать на иконку корзины с правой стороны от элемента и подтвердить удаление во всплывающем окне.
![Безымянный11](https://user-images.githubusercontent.com/85296765/124229304-739b6e00-db1e-11eb-8dfc-332a068bc50e.png)
* 10.2 При попытках удалить каталог изначально нужно удалить вложенные дочерние элементы.
![Безымянный11](https://user-images.githubusercontent.com/85296765/124248702-2a561900-db34-11eb-804b-f31394d03a1c.png)
  
  




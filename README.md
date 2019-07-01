# Программа обучения Android-разработчика
###### Туториал по изучению теоретических материалов:
Обозначение    | Уровень важности
--------|-------------------------------------------------------------------------------
**(\*\*\*\*)**   | Без изучения этого материала невозможно успешное прохождение темы
**(\*\*\*)**     | Материал, без которого сложно успешно завершить изучение темы
**(\*\*)**       | Важный материал, рекомендуемый к изучению
**(\*)**         | Полезная литература, улучшающая навыки

---
## Правила логирования времени и прохождения программы обучения
---
### Логирование времени
Для ментора первостепенно понимать, сколько именно времени тратится на ту или иную задачу. Поэтому логирование времени осуществяется следующим образом.

1. Логируем в саму задачу:
+ Время, затраченное на выполнение практического задания;
+ Время на прочтение теории, необходимой для выполнения практического задания;

2. Логируем в Разработка/Прочая активность/Другое:
+ Время, затраченное на ожидание проверки выполненного задания ментором;
+ Время на прочтение прочей учебной литературы (список рекомендуемой литературы представлен в конце);

### Прохождение программы обучения
 Программа обучения разделена на секции. Каждая секция состоит из
 + Теоретической части;
 + Базовой части (опционально)
 + Практической части;
 + Теста;

 Для каждой секции выполняется практическое задание. Теоретический материал изучается по мере необходимости для выполнения практики. После завершения практического задания необходимо в gitlab создать merge request на ментора, чтобы он смог проверить задание. Если задание выполнено успешно, то ментор предоставляет тест по пройденной секции. Для успешного прохождения теста в большинстве случаев достаточно знаний, полученных в ходе выполнения практического задания и прочтения необходимой для него теории.
 Если присутствует задание на реализацию методов, их можно проверять Unit тестами на правильность выполнения, до отправки на проверку ментору.

 Стоит отметить, что ментор в силу различных обстоятельств не всегда может оперативно проверять merge request'ы и предоставлять тесты. Поэтому, если ментор вам говорит, что сможет проверить задание/предоставить тест только через несколько часов - приступайте к выполнению следующей секции программы обучения.
 **Важно** одновременно непроверенным может быть не более одной секции программы обучения. То есть, чтобы приступить к 5ой секции, Ваше практическое задание по 3ей секции должно быть одобрено, а тест пройден.


 В случае возникновения вопросов во время выполнения практического задания, можно просить помощи у ментора. Однако не стоит подходить к ментору с недекомпозированной задачей из разряда "Я не понимаю, как сверстать экран". Декомпозируйте задачу, чтобы задать ментору более конкретный вопрос. Также не стоит сразу же спрашивать ментора, как только возникла трудность. Для начала попробуйте самостоятельно найти ответ на свой вопрос в интернете.

---
## I. Основные принципы разработки. Git. Flow проектов
---
### Теоретическая часть

**1. ООП**
+ [Основные принципы](https://javarush.ru/groups/posts/principy-oop)  **(\*\*\*\*)**

**2. Работа с Git, gitflow**
+ [Основные команды](https://git-scm.com/book/ru/v2) : init, clone, add, status, stash, commit (-m, -am, --amend), fetch, pull, push, branch, checkout, merge **(\*\*\*\*)**
+ Что такое [git flow](http://kb.simbirsoft/gitflow-method-overview/) **(\*\*\*)**
+ [Первоначальная настройка](https://git-scm.com/book/ru/v1/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-Git): конфигурация username и email **(\*\*\*)**

**3. Ведение проектов**
+  [Flow проекта, ведение в Power Steering](http://kb.simbirsoft/tasktracker/) **(\*\*\*)**

**4. Создание проекта, среда разработки Android Studio**
+ [Установка Android Studio](https://developer.android.com/studio) **(\*\*\*\*)**
+ [Создание нового проекта](https://developer.android.com/training/basics/firstapp/index.html) **(\*\*\*\*)**
+ [Основы интерфейса Android Studio](https://developer.android.com/studio/intro/index.html) **(\*\*\*\*)**
+ [Горячие клавиши Android Studio](https://developer.android.com/studio/intro/keyboard-shortcuts) **(\*\*)**
+ [Горячие клавиши Android Studio, повышение производительности](https://habr.com/ru/post/359376/) **(\*\*\*)**

**5. Gradle**
+ [Gradle](https://developer.android.com/studio/build/index.html) **(\*\*\*)**


### Практическое задание
1. При старте работ над практическим заданием, необходимо получить доступ к issue в системе [PS](https://ps.simbirsoft.com). Создать task с названием "I. Основные принципы разработки. Git. Flow проектов" и обновить статус задачи на "В процессе".
2. В [корпоративном gitlab](http://gitlab.simbirsoft/) создать новый репозиторий и следуя инструкциям, склонировать его к себе на компьютер. В настройках репозитория дать доступ ментору и руководителю отдела.
3.  В глобальных конфигурациях git прописать корректное имя пользователя и e-mail, которые будут использоваться для подписи коммитов.
4. Добавить `.gitignore`. Содержание файла можно взять с ресурса: https://www.gitignore.io/api/androidstudio. Cделать коммит и запушить изменения на remote-сервер в `master` ветку
5. Переключиться на новую ветку `develop`.
6. Создать новый android-проект (Phone and Tablet -> Empty Activity).
7. Добавить в gradle-файл библиотеку retrofit http://square.github.io/retrofit/
8. Запустить проект на симуляторе
9. Запустить проект на телефоне
10. Сделать коммит и запушить изменения на remote-сервер в `develop` ветку
11. После завершения работ над заданием перевести задачу в PS в статус "Завершен" и залогировать затраченное время.

---
## II. Java. Часть 1
---
### Теоретическая часть

**Основы**  
+ [Java-платформа](https://docs.oracle.com/javase/tutorial/getStarted/intro/definition.html) **(\*\*)**
+ [Типы данных и переменные](https://metanit.com/java/tutorial/2.1.php) **(\*\*\*\*)**
+ [Преобразования базовых типов данных](https://metanit.com/java/tutorial/2.2.php) **(\*\*\*\*)**
+ [Операции языка Java](https://metanit.com/java/tutorial/2.3.php) **(\*\*\*\*)**
+ [Массивы](https://metanit.com/java/tutorial/2.4.php) **(\*\*\*\*)**
+ [Условные конструкции](https://metanit.com/java/tutorial/2.5.php) **(\*\*\*\*)**
+ [Циклы](https://metanit.com/java/tutorial/2.6.php) **(\*\*\*\*)**
+ [Методы](https://metanit.com/java/tutorial/2.7.php) **(\*\*\*\*)**
+ [Рекурсивные функции](https://metanit.com/java/tutorial/2.8.php) **(\*\*\*)**
+ [Введение в обработку исключений](https://metanit.com/java/tutorial/2.10.php) **(\*\*)**
+ [Java Code Conventions - Oracle](http://www.oracle.com/technetwork/java/codeconventions-150003.pdf) **(\*\*\*\*)**

**Отладка** 
+ [Android Studio Debugging: Базовые понятия](https://medium.com/@artem_shevchenko/android-studio-debugging-%D0%B1%D0%B0%D0%B7%D0%BE%D0%B2%D1%8B%D0%B5-%D0%BF%D0%BE%D0%BD%D1%8F%D1%82%D0%B8%D1%8F-%D0%B8-%D0%B2%D0%BE%D0%B7%D0%BC%D0%BE%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8-658ee6dcc641) **(\*\*\*)**
+ [Android Studio Debugging: Продвинутый уровень](https://medium.com/@artem_shevchenko/android-studio-debugging-%D0%BF%D1%80%D0%BE%D0%B4%D0%B2%D0%B8%D0%BD%D1%83%D1%82%D1%8B%D0%B9-%D1%83%D1%80%D0%BE%D0%B2%D0%B5%D0%BD%D1%8C-e05dac22439f) **(\*\*\*)**


### Практическое задание
Все задачи должны быть выполнены в указанном репозитории в отдельной ветке, вида training/lastname_firstname_date. После выполнения должен быть создан merge request на ментора.

***Важно! Весь код должен быть написан по предоставленному Java Code Conventions***

1. Создать task в PS с заголовком "II. Java. Часть 1" и взять ее в работу.
2. [Работа с примитивными типами](http://gitlab.simbirsoft/aleksey.gusykov/javacoreTraining/blob/master/app/src/main/java/com/example/user/javacoretraining/training/ElementaryTraining.java)
3. [Работа со строками](http://gitlab.simbirsoft/aleksey.gusykov/javacoreTraining/blob/master/app/src/main/java/com/example/user/javacoretraining/training/StringsTraining.java)
4. [Работа с массивами](http://gitlab.simbirsoft/aleksey.gusykov/javacoreTraining/blob/master/app/src/main/java/com/example/user/javacoretraining/training/ArraysTraining.java)
5. Завершить task в PS и залогировать затраченное время

---
## III. Java. Часть 2
---
### Теоретическая часть

**1. Классы**
+ [Классы и объекты](https://metanit.com/java/tutorial/3.1.php)  **(\*\*\*\*)**
+ [Пакеты](https://metanit.com/java/tutorial/3.2.php)  **(\*\*\*\*)**
+ [Модификаторы доступа и инкапсуляция](https://metanit.com/java/tutorial/3.3.php)  **(\*\*\*\*)**
+ [Статические члены и модификатор static](https://metanit.com/java/tutorial/3.4.php)  **(\*\*\*\*)**
+ [Объекты как параметры методов](https://metanit.com/java/tutorial/3.14.php)  **(\*\*\*\*)**
+ [Наследование, полиморфизм и ключевое слово super](https://metanit.com/java/tutorial/3.5.php)  **(\*\*\*\*)**
+ [Абстрактные классы](https://metanit.com/java/tutorial/3.6.php)  **(\*\*\*\*)**
+ [Иерархия наследования и преобразование типов](https://metanit.com/java/tutorial/3.10.php)  **(\*\*\*\*)**
+ [Внутренние классы](https://metanit.com/java/tutorial/3.12.php)  **(\*\*\*\*)**
+ [Интерфейсы](https://metanit.com/java/tutorial/3.7.php)  **(\*\*\*\*)**
+ [Интерфейсы в механизме обратного вызова](https://metanit.com/java/tutorial/3.16.php)  **(\*\*\*)**
+ [Перечисления enum](https://metanit.com/java/tutorial/3.8.php)  **(\*\*\*\*)**
+ [Класс Object и его методы](https://habrahabr.ru/post/168195/)  **(\*\*\*)**
+ [Обобщенные типы и методы](https://metanit.com/java/tutorial/3.11.php)  **(\*\*\*)**
+ [Наследование и обобщения](https://metanit.com/java/tutorial/3.15.php)  **(\*\*\*)**
+ [Типы ссылок](https://javadevblog.com/tipy-ssy-lok-v-java-strongreference-weakreference-softreference-i-phantomreference.html)  **(\*\*\*)**
+ [Ссылочные типы и клонирование объектов](https://metanit.com/java/tutorial/3.13.php) **(\*\*\*)**

**2. Обработка исключений**  
+ [Оператор throws](https://metanit.com/java/tutorial/4.1.php) **(\*\*\*\*)**
+ [Классы исключений](https://metanit.com/java/tutorial/4.2.php) **(\*\*\*\*)**
+ [try-with-resources](https://docs.oracle.com/javase/tutorial/essential/exceptions/tryResourceClose.html) **(\*\*\*\*)**
+ [Создание своих классов исключений](https://metanit.com/java/tutorial/4.3.php) **(\*\*)**

**3. Коллекции**  
+ [Введение в коллекции в Java](https://metanit.com/java/tutorial/5.1.php) **(\*\*\*\*)**
+ [Класс ArrayList и интерфейс List](https://metanit.com/java/tutorial/5.2.php) **(\*\*\*\*)**
+ [Структуры данных в картинках. ArrayList](https://habr.com/en/post/128269/) **(\*\*\*\*)**
+ [Класс LinkedList](https://metanit.com/java/tutorial/5.3.php) **(\*\*)**
+ [Структуры данных в картинках. LinkedList](https://habr.com/en/post/127864/) **(\*\*)**
+ [Класс HashSet](https://metanit.com/java/tutorial/5.4.php) **(\*\*\*\*)**
+ [Класс TreeSet](https://metanit.com/java/tutorial/5.5.php) **(\*\*\*)**
+ [Интерфейсы Comparable и Comporator. Сортировка](https://metanit.com/java/tutorial/5.6.php) **(\*\*\*)**
+ [Очереди и класс ArrayDeque](https://metanit.com/java/tutorial/5.7.php) **(\*\*)**
+ [Отображения и класс HashMap](https://metanit.com/java/tutorial/5.8.php) **(\*\*\*\*)**
+ [Структуры данных в картинках. HashMap](https://habr.com/en/post/128017/) **(\*\*\*\*)**
+ [Класс TreeMap](https://metanit.com/java/tutorial/5.9.php) **(\*\*)**
+ [Итераторы](https://metanit.com/java/tutorial/5.10.php) **(\*\*)**

**4. Работа со строками**  
+ [Введение в строки. Класс String](https://metanit.com/java/tutorial/7.1.php) **(\*\*\*\*)**
+ [Основные операции со строками](https://metanit.com/java/tutorial/7.2.php) **(\*\*\*\*)**
+ [StringBuffer и StringBuilder](https://metanit.com/java/tutorial/7.3.php) **(\*\*\*)**
+ [Регулярные выражения](https://metanit.com/java/tutorial/7.4.php) **(\*\*)**

**5. Лямбда-выражения**  
+ [Введение в лямбда-выражения](https://metanit.com/java/tutorial/9.1.php) **(\*\*\*\*)**
+ [Лямбды как параметры методов и ссылки на методы](https://metanit.com/java/tutorial/9.2.php) **(\*\*\*\*)**
+ [Встроенные функциональные интерфейсы](https://metanit.com/java/tutorial/9.3.php) **(\*\*)**
  
  
### Базовое задание
Все задачи должны быть выполнены в указанном репозитории в отдельной ветке, вида training/lastname_firstname_date. После выполнения должен быть создан merge request на ментора.

1. [Работа со списками](http://gitlab.simbirsoft/aleksey.gusykov/javacoreTraining/blob/master/app/src/main/java/com/example/user/javacoretraining/collections/CollectionsBlock.java)
2. [Работа с классами](http://gitlab.simbirsoft/aleksey.gusykov/javacoreTraining/blob/master/app/src/main/java/com/example/user/javacoretraining/classes/ClassesBlock.java)


### Практическое задание
Все задачи должны быть реализованы в одном файле и разделены комментариями, указывающими на номер или текст задания.

**Важно! Весь код должен быть написан по предоставленному Java Code Conventions**
1. Создать task в PS с заголовком "II. Java. Часть 2" и взять ее в работу.
2. Настроить проект для [java 8](https://developer.android.com/studio/write/java8-support.html?utm_source=android-studio)
3. Написать простое лямбда-выражение в переменной `myClosure`, лямбда-выражение должно выводить в консоль фразу "I love Java". Вызвать это лямбда-выражение. Далее написать функцию, которая будет запускать заданное лямбда-выражение заданное количество раз. Объявить функцию так: `public void repeatTask (int times, Runnable task)`. Функция должна запускать `times` раз лямбда-выражение `task` . Используйте эту функцию для печати "I love Java" 10 раз.
4. Условия: есть начальная позиция на двумерной плоскости, можно осуществлять последовательность шагов по четырем направлениям up, down, left, right. Размерность каждого шага равна 1. Задание: 
  - Создать enum `Directions` с возможными направлениями движения
  - Создать метод, принимающий координаты и одно из направлений и возвращающий координату после перехода по направлению
  - Создать метод, осуществляющий несколько переходов от первоначальной координаты и выводящий координату после каждого перехода. Для этого внутри метода следует определить переменную `location` с начальными координатами (0,0) и  массив направлений, содержащий элементы [up, up, left, down, left, down, down, right, right, down, right], и програмно вычислить какие будут координаты у переменной `location` после выполнения этой последовательности шагов. Для вычисленеия результата каждого перемещения следует использовать созданный ранее метод перемещения на один шаг.
5. Создать интерфейс Shape с двумя методами perimeter и area, выводящими периметр и площадь фигуры соответственно, после чего реализовать и использовать для вывода периметра и площади следующие классы, реализующие интерфейс Shape:
  - `Rectangle` - прямоугольник с двумя свойствами: ширина и длина
  - `Square` - квадрат с одним свойством: длина стороны
  - `Circle` - круг с одним свойством: диаметр круга
6. Завершить task в PS и залогировать затраченное время

---
## IV. Верстка
---
### Теоретическая часть

В случае если по ссылке встречается пошаговый гайд - рекомендуется его выполнить в отдельном проекте.

**1. Начало разработки под Android**
+ [Начало разаработки](https://developer.android.com/training/index.html) **(\*\*\*\*)**

**2. Верстка**
+ [Уроки верстки из курсов](http://startandroid.ru/ru/uroki/vse-uroki-spiskom.html) **(\*\*)**
+ [Создание макетов в XML и View groups](https://developer.android.com/guide/topics/ui/declaring-layout.html) **(\*\*\*)**

**3. Типы layout'ов**
+ [Frame Layout](http://developer.alexanderklimov.ru/android/layout/framelayout.php) **(\*\*\*\*)**
+ [Linear Layout](https://developer.android.com/guide/topics/ui/layout/linear.html) **(\*\*\*\*)**
+ [Relative Layout](https://developer.android.com/guide/topics/ui/layout/relative.html) **(\*\*\*\*)**

**4. Splash Screen**
+ [Как правильно реализовать](https://habr.com/ru/post/345380/) **(\*\*\*\*)**

**4. BottomNavigationView**
+ [Обзор](https://developer.android.com/reference/android/support/design/widget/BottomNavigationView.html) **(\*\*\*\*)**

**5. App Bar**
+ [Обзор](https://developer.android.com/training/appbar) **(\*\*\*\*)**

**6. Constraint Layout**
+ [Документация](https://developer.android.com/reference/android/support/constraint/ConstraintLayout.html) **(\*\*\*\*)**
+ [Работа с различными свойствами](https://habrahabr.ru/company/touchinstinct/blog/326814/) **(\*\*\*\*)**

**7. Ресурсы**
+ [Обзор](https://developer.android.com/guide/topics/resources/providing-resources) **(\*\*\*\*)**
+ [Локализация](https://developer.android.com/guide/topics/resources/localization) **(\*\*)**
+ [Типы ресурсов](https://developer.android.com/guide/topics/resources/available-resources) **(\*\*)**
+ [Шрифты в XML](https://developer.android.com/guide/topics/ui/look-and-feel/fonts-in-xml.html) **(\*\*)**
+ [Загружаемые шрифты](https://developer.android.com/guide/topics/ui/look-and-feel/downloadable-fonts.html) **(\*\*)**
+ [Поддержка разных экранов](https://developer.android.com/guide/practices/screens_support.html) **(\*\*)**
+ [Zeplin](https://habrahabr.ru/company/uteam/blog/315542/) **(\*\*\*)**

**Важно** В компании при разработке любого мобильного приложения считается правилом хорошего тона придерживаться нефункциональных требований, описанных в [данной статье](http://kb.simbirsoft/nonfunctional-support/)

### Практическое задание
Работа должна производится в созданном ранее проекте.

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключится на ветку `layouts` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style. В системе PS также необходимо создать созвучную задачу, в которую после завершения будет залогировано время.

1. Создать task в PS с заголовком "IV. Верстка" и взять ее в работу.
2. Сделать так, чтобы на домашнем экране Android отображалась иконка и название приложения "Хочу помочь". Ресурсы иконок [тут](https://zpl.io/2jkoMOp).
3. Реализовать Splash Screen согласно [макету](https://zpl.io/2jlk3Mm).
4. Реализовать экран "Профиль" согласно [макету](https://zpl.io/b6lQpZq).
 - Экран "Профиль" необходимо отображать после Splash Screen. По нажатию стрелки назад, приложение закрывается.
 - Необходимо реализовать нижний элемент навигации с помощью стандартного `BottomNavigationView`. Пункт "Помочь" визуально не должен отличаться от остальных четырех.
 - В нижнем меню навигации по-умолчанию должен быть выбран пункт "Профиль".
 - Верстка должна быть реализована в xml.
 - Верстка должна быть выполнена с учетом "pixel perfect" - когда все элементы дизайна расположены и имеют размеры абсолютно идентичные макету для экрана с теми же размерами, что и макет, и адекватно масштабироваться для других размеров и разрешений.
 - Все переиспользуемые размеры в xml должны быть вынесены в dimes, цвета в colors, а строки в strings.
 - Никаких "магических чисел", все должно иметь понятные названия.
5. Завершить task в PS и залогировать затраченное время 

---
## V. Android OS. Activity. Fragments
---
### Теоретическая часть

**1. Android OS** 
+ [История Android](https://www.android.com/history/#/marshmallow) **(\*\*)**
+ [Архитектура Android](https://source.android.com/devices/architecture/) **(\*\*)**

**2. Application**  
+ [Application](https://developer.android.com/reference/android/app/Application.html)  **(\*\*\*)**
+ [Context](https://possiblemobile.com/2013/06/context/)  **(\*\*\*)**
+ [Файл Manifest](https://developer.android.com/guide/topics/manifest/manifest-intro.html) **(\*\*\*\*)**

**3. Activity**  
+ [Activity - основы](https://developer.android.com/guide/components/activities/intro-activities) **(\*\*\*\*)**
+ [Управление жизненным циклом Activity](https://developer.android.com/guide/components/activities/activity-lifecycle) **(\*\*\*\*)**
+ [Обработка изменений конфигурации экрана](https://developer.android.com/guide/topics/resources/runtime-changes.html) **(\*\*\*\*)**
+ [Task и Back Stack](https://habrahabr.ru/post/186434/) **(\*\*)**
+ [Передача данных между Activity. Обзор](https://developer.android.com/guide/components/activities/parcelables-and-bundles.html) **(\*\*\*\*)**
+ [Передача данных между Activity. Интерфейс Parcelable](https://metanit.com/java/android/2.13.php) **(\*\*\*\*)**

**4. Fragment**  
+ [Fragment - основы](https://developer.android.com/guide/components/fragments.html) **(\*\*\*\*)**
+ [Диалоговые окна](https://developer.android.com/guide/topics/ui/dialogs.html) **(\*\*\*\*)**
+ [Передача данных между Fragment](https://developer.android.com/training/basics/fragments/communicating) **(\*\*\*\*)**
+ [Target fragment](https://habrahabr.ru/post/259805/) **(\*\*)**

**5. SearchView**
+ [Обзор](https://developer.android.com/guide/topics/search) **(\*\*\*\*)**

**6. ViewPager**
+ [Обзор](https://developer.android.com/training/implementing-navigation/lateral.html) **(\*\*\*\*)**

**7. Списки**
+ [ListView](http://developer.alexanderklimov.ru/android/views/listview.php) **(\*\*)**
+ [RecyclerView и Adapter](https://developer.android.com/training/material/lists-cards.html) **(\*\*\*\*)**

**8. Работа со сторонними приложениями и permissions**  
+ [Run-time permissions](https://developer.android.com/training/permissions/requesting.html)**(\*\*\*\*)**
+ [Intent и фильтры](https://developer.android.com/guide/components/intents-filters.html?hl=ru)**(\*\*\*\*)**
+ [Взаимодействие с другими приложениями](https://developer.android.com/training/basics/intents/index.html)**(\*\*\*\*)**
+ [Получение фото с камеры](https://developer.android.com/training/camera/photobasics)**(\*\*\*\*)**

**9. BroadcastReceiver**  
+ [BroadcastReceiver - основы](http://codetheory.in/android-broadcast-receivers/) **(\*\*\*\*)**
+ [Изменения работы с BroadcastReceiver с Android 8.0](https://developer.android.com/guide/components/broadcast-exceptions.html) **(\*\*)**

### Практическое задание
Работа должна производится в созданном ранее проекте.

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключится на ветку `fragments` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style.

1. Создать task в PS с заголовком "V. Фрагменты" и взять ее в работу.
2. Реализовать диалог согласно [макету](https://zpl.io/brkmRYX)
 - Диалог необходимо открывать при нажатии на изображение пользователя на экране "Профиль". 
 - По нажатию на кнопку "Выбрать фото" не должно ничего происходить.
 - По нажатию на кнопку "Сделать снимок" необходимо запускать камеру устройства. Сделанное фото должно заменять текущее на экране профиля
 - По нажатию на кнопку "Удалить" необходимо удалять текущее изображение пользователя на экране профиля
3. Реализовать экран "Категории помощи" приложения согласно [макету](https://zpl.io/b6lYE9d).
 - Экран "Категории помощи" необходимо отображать после Splash Screen. По нажатию стрелки назад, приложение закрывается. Переход на экран профиля теперь происходит при выборе пункта "Профиль" в нижнем меню.
 - В нижнем меню навигации по-умолчанию должен быть выбран пункт "Помочь".
 - Экран должен представлять из себя activity с `RecyclerView`.
4. Реализовать экран "Поиск" согласно [макету](https://zpl.io/bAGAPj8). Переход на этот экран осуществляется при выборе пункта "Поиск" в нижнем меню
 - Экран необходимо построить с использованием `SearchView`,`ViewPager` и фрагментов.
 - У `SearchView` необходимо реализовать только верстку без логики.
 - Необходимо реализовать возможность изменять выбранную вкладку перелистыванием с плавной анимацией. 
 - В качестве названий для результатов необходимо использовать произвольные случайные строки.
 - Данные для отображения результата необходимо генерировать случайным образом при каждом перелистывании `ViewPager`.
5. Завершить task в PS и залогировать затраченное время 

---
## VI. Структуры данных. Работа с файлами
---
### Теоретическая часть

**1. Работа с файлами в java. Сериализация**  
+ [Потоки ввода-вывода](https://metanit.com/java/tutorial/6.1.php)  **(\*\*\*\*)**
+ [Закрытие потоков](https://metanit.com/java/tutorial/6.2.php)  **(\*\*\*\*)**
+ [Чтение и запись файлов. FileInputStream и FileOutputStream](https://metanit.com/java/tutorial/6.3.php)  **(\*\*\*\*)**
+ [Классы ByteArrayInputStream и ByteArrayOutputStream](https://metanit.com/java/tutorial/6.4.php)  **(\*\*)**
+ [Буферизуемые потоки. Классы BufferedInputStream и BufferedOuputStream](https://metanit.com/java/tutorial/6.5.php)  **(\*\*\*\*)**
+ [Чтение и запись текстовых файлов. FileReader и FileWriter](https://metanit.com/java/tutorial/6.8.php)  **(\*\*)**
+ [Буферизируемые символьные потоки. BufferedReader и BufferedWriter](https://metanit.com/java/tutorial/6.9.php)  **(\*\*)**
+ [Сериализация объектов](https://metanit.com/java/tutorial/6.10.php)  **(\*\*)**
+ [Класс File. Работа с файлами и каталогами](https://metanit.com/java/tutorial/6.11.php)  **(\*\*\*\*)**
+ [Работа с ZIP-архивами](https://metanit.com/java/tutorial/6.12.php)  **(\*\*)**

**2. JSON**
+ [Понятие](https://ru.wikipedia.org/wiki/JSON)  **(\*\*\*\*)**
+ [Парсинг в Android](https://metanit.com/java/android/13.3.php)  **(\*\*\*\*)**
+ [Gson](https://habrahabr.ru/company/naumen/blog/228279/) **(\*\*\*\*)**

**3. Работа с файловой системой Android**  
+ [SharedPreferences](https://developer.android.com/training/basics/data-storage/shared-preferences.html?hl=ru#GetSharedPreferences) **(\*\*\*\*)**
+ [Настройки через Preferences](https://developer.android.com/guide/topics/ui/settings.html) **(\*\*)**
+ [Android data storage](https://developer.android.com/training/basics/data-storage/files.html) **(\*\*\*\*)**
+ [FileProvider](https://developer.android.com/reference/android/support/v4/content/FileProvider.html) **(\*\*\*)**

**4. Работа с датой и временем**  
+ [Date, Calendar](http://developer.alexanderklimov.ru/android/java/date.php) **(\*\*\*\*)**
+ [Date в Java 8](http://www.baeldung.com/java-8-date-time-intro) **(\*\*\*\*)**
+ [Работа со временем в java ](https://habrahabr.ru/post/274811/) **(\*\*)**

**5. DiffUtils**
+ [Обзор](https://medium.com/@iammert/using-diffutil-in-android-recyclerview-bdca8e4fbb00) **(\*\*\*\*)**

### Практическое задание
Работа должна производится в созданном ранее проекте.

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключится на ветку `data_structures` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style. Верстка экранов должна быть выполнена по принципу pixel-perfect.

1. Создать task в PS с заголовком "VI. Структуры данных" и взять ее в работу.
2. Доработать логику диалога на экране "Профиль".
 - По нажатию на кнопку "Выбрать фото" необходимо открывать галерею устройства. Выбранное в галерее фото должно заменять текущее на экране профиля
3. Подключить к проекту [ThreeTenABP](https://github.com/JakeWharton/ThreeTenABP). Все операции с датой и временем должны быть реализованы через классы данной библиотеки.
4. Сверстать экран "Новости" согласно [макету](https://zpl.io/brkm3we). Переход на этот экран осуществляется при выборе пункта "Новости" в нижнем меню. Экран содержит список благотворительных событий, относящихся к выбранным категориям.
 - Одно событие может относиться сразу к нескольких категориям помощи.
5. Сверстать экран "Фильтр" согласно [макету](https://zpl.io/2ZxPMeG). Переход на этот экран осуществляется при клике на иконку в правом верхнем углу экрана "Новости".
 - На экране вместо фразы "Как вы хотите помочь?" необходимо отображать "Категории помощи" и ниже список всех возможных категорий.
 - При смене категорий в фильтре обновлять список на экране "Новости" обязательно при помощи DiffUtils.
6. Сверстать экран "Детальное описание события" согласно [макету](https://zpl.io/adA93Z5). Переход на этот экран осуществляется при выборе любого события из списка. Данный экран должен получить информацию о том, какое событие было выбрано на предыдущем шаге.
7. Необходимо создать два json'а. Содержащих в себе массивы категорий и благотворительных событий. Информация об объектах должна быть достаточной для формирования отображений на экранах, а также для корректного разделения по категориям помощи. Каждый объект должен обладать уникальным (среди объектов своего типа) идентификатором. Проверить корректность созданных json-ов через [online-parser](http://json.parser.online.fr/). Записать их в 2 файла и поместить в папку assets проекта.
8. Необходимо создать сущности соответствующие понятиям Категория и Событие.
9. Создать класс, который будет читать созданные json из файлов, парсить их и преобразовывать в массивы.
10. Наполнить экраны полученными данными.
11. Завершить task в PS и залогировать затраченное время

---
## VII. Многопоточность
---
### Теоретическая часть

**1. Базовые понятия**
+ [Многопоточность. Определение](https://ru.wikipedia.org/wiki/%D0%9C%D0%BD%D0%BE%D0%B3%D0%BE%D0%BF%D0%BE%D1%82%D0%BE%D1%87%D0%BD%D0%BE%D1%81%D1%82%D1%8C)  **(\*\*\*\*)**
+ [Мьютекс](https://ru.wikipedia.org/wiki/%D0%9C%D1%8C%D1%8E%D1%82%D0%B5%D0%BA%D1%81)  **(\*\*)**
+ [Семафор](https://ru.wikipedia.org/wiki/%D0%A1%D0%B5%D0%BC%D0%B0%D1%84%D0%BE%D1%80_(%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B0))  **(\*\*)**
+ [Дэдлок](https://ru.wikipedia.org/wiki/Взаимная_блокировка)  **(\*\*\*)**
+ [Starvation and Livelock](https://docs.oracle.com/javase/tutorial/essential/concurrency/starvelive.html)  **(\*\*\*)**
+ [Атомарные операции](https://ru.wikipedia.org/wiki/%D0%90%D1%82%D0%BE%D0%BC%D0%B0%D1%80%D0%BD%D0%B0%D1%8F_%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D1%8F)  **(\*\*\*)**
+ [Atomic типы](http://java-online.ru/concurrent-atomic.xhtml)  **(\*\*\*)**

**2. Многопоточность в java**
+ [Thread](https://habrahabr.ru/post/164487/) **(\*\*\*\*)**
+ [Синхронизация потоков. Оператор synchronized](https://metanit.com/java/tutorial/8.3.php) **(\*\*\*\*)**
+ [Синхронизированные коллекции](https://habrahabr.ru/company/luxoft/blog/157273/)  **(\*\*\*)**
+ [Executors](http://winterbe.com/posts/2015/04/07/java8-concurrency-tutorial-thread-executor-examples/) **(\*\*\*\*)**

**3. Фоновая работа в Android**
+ [Looper, Handler, and HandlerThread](https://blog.mindorks.com/android-core-looper-handler-and-handlerthread-bd54d69fe91a). [Видео](https://www.youtube.com/watch?v=gDvjU8HSuYE)  **(\*\*\*)**
+ [Loader](https://habrahabr.ru/company/e-Legion/blog/265405/) **(\*\*)**
+ [AsyncTask](https://developer.android.com/reference/android/os/AsyncTask.html)  **(\*\*\*)**
		
**4. Service**
+ [Service - основы](https://developer.android.com/guide/components/services.html)  **(\*\*\*\*)**
+ [IntentService](http://developer.alexanderklimov.ru/android/theory/intentservice.php)  **(\*\*\*\*)**
+ [Job Scheduler](http://ticketmastermobilestudio.com/blog/how-to-use-androids-job-scheduler) **(\*\*\*\*)**
+ [Background Execution Limits Android 8.0+](https://developer.android.com/about/versions/oreo/background.html) **(\*\*)**


### Практическое задание
Работа должна производится в созданном ранее проекте.

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключится на ветку `concurrency` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style.

1. Создать task в PS с заголовком "VII. Многопоточность" и взять ее в работу.
2. В рамках предыдущего задания было реализовано чтение из файла. Реализовать чтение из файла и парсинг в background-потоке каждым из предложенных способов. С помощью AsyncTask, Executor, IntentService. При повороте экрана не должно происходить повторное чтение из файла.
3. Перед отправкой данных остановить рабочий background-поток (Thread.sleep(5000)), для показательного отображения Progress Indicator (имитация запроса к сети).
4. Реализовать Progress Indicator на экранах "Категории помощи" и "Новости". Индикатор должен показываться с момента запроса данных до момента их отображения на экране. **Внимание!** Все действия c UI должны совершаться в главном потоке. 
5. Для сохранения и восстановления данных при смене конфигурации использовать savedInstanceState.
4. Завершить task в PS и залогировать затраченное время

---
## VIII. Реактивное программирование
---
### Теоретическая часть

**1. Понятие реактивности**
+ [Концепция](https://habrahabr.ru/post/279715/)  **(\*\*\*\*)**
+ [RxMarbles](http://rxmarbles.com/)  **(\*\*\*)**

**2. RxJava**
+ [RxJava](https://github.com/ReactiveX/RxJava)  **(\*\*\*\*)**
+ [reactivex](http://reactivex.io/)  **(\*\*)**
+ [Введение в RxJava: Почему Rx?](https://habrahabr.ru/post/269417/)  **(\*\*)**

**3. Android расширения**
+ [RxAndroid (позволяет легко переключаться на main поток)](https://github.com/ReactiveX/RxAndroid)  **(\*\*\*)**
+ [RxBinding](https://github.com/JakeWharton/RxBinding)  **(\*\*\*)**
+ [Использование RxJava совместно с RxBinding](https://github.com/codepath/android_guides/wiki/RxJava-and-RxBinding)  **(\*\*\*)**


### Практическое задание
Работа должна производится в созданном ранее проекте.

**Важно! Для пункта 2 используется отдельный проект, указанный в задании**

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключиться на ветку `rx_java` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style. В системе PS также необходимо создать созвучную задачу, в которую после завершения будет залогировано время.

1. Создать task в PS с заголовком "X. Реактивное программирование" и взять ее в работу.
2. Клонировать [проект](http://gitlab.simbirsoft/artur.korchagin/rxtraining) и реализовать все методы так, чтобы тесты проходили.
 - Все методы должны быть реализованы в указанном репозитории в отдельной ветке, вида training/lastname_firstname_date. После выполнения должен быть создан merge request на ментора.
3. Подключить фреймворк `RxJava`, а так же библиотеки `RxAndroid` и `RxBinding`.
4. Создать экран "Авторизация" согласно [макету](https://zpl.io/25ge5Z3).
 - Кнопка "Войти" активна только в момент, когда в поля логин и пароль введено по 6 или более символов. В противном случае кнопка неактивна. Реализовать данное поведение с помощью `RxJava`.
 - В неактивном состоянии кнопка "Войти" имеет серый фон вместо зеленого.
 - При повороте экрана данные, введенные в поля ввода, должны сохраняться.
 - Экран "Авторизация" необходимо отображать после Splash Screen. По нажатию стрелки назад, приложение закрывается. Переход на экран "Категории помощи" происходит при нажатии на активную кнопку "Войти".
5. Доработать вкладку "По мероприятиям" экрана "Поиск"
 - Реализовать логику работы `SearchView`. Поиск происходит в тот момент, когда пользователь 500 мс ничего не вводил в строку и не удалял из нее. То есть, если пользователь быстро вводит слово в строку поиска, поиск отрабатывает только 1 раз для всего слова целиком. Реализовать данное поведение с помощью `RxJava`.
 - Данные для отображения результата необходимо брать из событий из созданных ранее json файлов.
 - Если в строку поиска ничего не ввели, то вместо результатов поиска отображаем заглушку как на [макете](https://zpl.io/2jlkOZp).
 - Если введенная в поиск строка не соответствует названию ни одного события, то отображаем пустой список результатов.
 - При повороте экрана, а также при перелистывании `ViewPager` на вкладку "По НКО" и обратно строка, введенная в поиске, список результатов и позиция списка должны сохраняться.
6. Завершить task в PS и залогировать затраченное время

---
## IX. Работа с сетью
---
### Теоретическая часть
**1. Базовые понятия**
+ [HTTP](https://ru.wikipedia.org/wiki/HTTP) **(\*\*\*)**
+ [HTTP codes](https://ru.wikipedia.org/wiki/Список_кодов_состояния_HTTP/) **(\*\*\*)**
+ [RESTful](https://habrahabr.ru/company/hexlet/blog/274675/) **(\*\*\*)**
+ [RESTful API — ложь](https://habrahabr.ru/post/265845/) **(\*)**
+ [WebSocket](https://stfalcon.com/ru/blog/post/android-websocket) **(\*\*)**
+ [Handling API calls using Retrofit 2 and RxJava 2](https://medium.com/3xplore/handling-api-calls-using-retrofit-2-and-rxjava-2-1871c891b6ae) **(\*)**

**2. Библиотеки**
+ [OkHttp](http://square.github.io/okhttp/) **(\*\*\*\*)**
+ [Retrofit](http://square.github.io/retrofit/) **(\*\*\*\*)**
+ [OkHttp. Interceptors](https://github.com/square/okhttp/wiki/Interceptors) **(\*\*\*)**
+ [OkHttp which ignores all SSL errors](https://gist.github.com/chalup/8706740) **(\*\*\*)**
+ [Logging interceptor for okhttp](https://github.com/square/okhttp/tree/master/okhttp-logging-interceptor)

**3. Firebase**
+ [Документация](https://firebase.google.com/docs/android/setup)  **(\*\*\*\*)**

**4. Отладка. Перехват и подмена трафика мобильных устройств**
+ [Postman](https://habr.com/ru/company/kolesa/blog/351250/)  **(\*\*)**
+ [Fiddler](https://learn.javascript.ru/fiddler)  **(\*\*)**
+ [Charles](http://wormiks.ru/faq_po_programmam_wormix/11-charles_instrukcija_polzovatelja_i_faq.html)  **(\*\*)**
+ [Перехват и подмена трафика мобильных устройств](http://kb.simbirsoft/traffic-sniffers/)  **(\*)**

### Практическое задание
Работа должна производится в созданном ранее проекте.

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключится на ветку `networking
` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style.

1. Создать task в PS с заголовком "IX. Работа с сетью" и взять ее в работу.
2. Необходимо реализовать транспортный слой приложения, который будет осуществалять загрузку данных с сервера. Для этого требуется использовать firebase. Документация по работе с firebase [тут](https://firebase.google.com/docs/android/setup).
 - Все "тяжелые" операции должны быть реализованы в фоновом потоке
 - На время выполнения фоновых операций пользователю должен быть показан Activity Indicator
3. Заменить загрузку из файла на старте приложения на загрузку с сервера. В случае если ответ от сервера ошибочен - загрузить данные из файла.
 - Все "тяжелые" операции должны быть реализованы в фоновом потоке
 - На время выполнения фоновых операций пользователю должен быть показан Activity Indicator
4. Завершить task в PS и залогировать затраченное время

---
## X. Базы данных. Content Provider
---
### Теоретическая часть

**1. Android SQLite**
+ [Работа с SQLite средствами Android SDK](https://developer.android.com/training/data-storage/sqlite.html)  **(\*\*)**
+ [ORM](https://habrahabr.ru/company/yotadevices/blog/242559/)  **(\*\*)**

**2. Основы Realm**
+ [Документация по Realm](https://realm.io/docs/java/latest/)  **(\*\*\*\*)**
+ [DatabaseProvider в androidbase](http://gitlab.simbirsoft/mobile/AndroidBase/blob/master/app/src/main/java/com/simbirsoft/baseplatform/data/db/DatabaseProvider.java)  **(\*\*)**

**3. Основы Room**
+ [Документация по Room](https://developer.android.com/topic/libraries/architecture/room)  **(\*\*\*\*)**
+ [Codelab по Room Java](https://codelabs.developers.google.com/codelabs/android-room-with-a-view/index.html?index=..%2F..index#0) **(\*\*\*)**
+ [Codelab по Room Kotlin](https://codelabs.developers.google.com/codelabs/android-room-with-a-view-kotlin/index.html?index=..%2F..index#0)  **(\*\*\*)**
+ [Room и Rx](https://medium.com/androiddevelopers/room-rxjava-acb0cd4f3757)  **(\*\*\*\*)**

**4. Content Provider**
+ [Основы](https://developer.android.com/guide/topics/providers/content-provider-basics.html?hl=ru) **(\*\*)**

### Практическое задание
Работа должна производится в созданном ранее проекте.

Все изменения должны быть закоммичены, а названия коммитов должны коротко и исчерпывающе описывать содержащие изменения. Каждый коммит должен быть рабочим, отправка некомпилирующегося кода недопустима. Для работы над этим заданием необходимо переключится на ветку `data_base` и все изменения пушить в нее. После завершения работы над задачей в gitlab необходимо создать merge request в ветку `develop`.
Код должен быть читабельным и написан согласно code-style. В системе PS также необходимо создать созвучную задачу, в которую после завершения будет залогировано время.

1. Создать task в PS с заголовком "VIII. Базы данных" и взять ее в работу.
2. Необходимо создать базу данных с использованием Room для хранения сущностей Категории и Благотворительных событий.
3. При первом получении данных для сущностей Категории и Благотворительные события, сохранять данные в базе данных, и дальнейшее получение производить из нее. Обновление данных должно происходить только для новой сессии.
 - Чтение и запись должны быть реализованы в фоновом потоке
 - На время выполнения фоновых операций пользователю должен быть показан Activity Indicator
4. Наполнение экранов Категории и Благотворительных событий должно происходить из созданной базы данных
 - Все "тяжелые" операции должны быть реализованы в фоновом потоке
 - На время выполнения фоновых операций пользователю должен быть показан Activity Indicator
5. Завершить task в PS и залогировать затраченное время

---
## XI. Архитектура приложений. Практика в рамках продуктового проекта.
---
### Теоретическая часть

**1. Архитектура**
+ [Принципы SOLID](https://blog.byndyu.ru/2009/10/solid.html)  **(\*\*\*\*)**
+ [MVC, MVP, MVVM](https://habrahabr.ru/company/mobileup/blog/313538/) **(\*\*)**
+ [Moxy - ссылка на библиотеку](https://github.com/Arello-Mobile/Moxy )**(\*\*\*\*)**
+ [Moxy — статья о том, как она работает](https://habrahabr.ru/post/276189/) **(\*\*\*\*)**

**2. Clean Architecture**
+ [Статья самого Дядюшки Боба](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html) **(\*\*\*\*)**
+ [Хороший цикл статей](https://five.agency/android-architecture-part-1-every-new-beginning-is-hard/) **(\*\*\*\*)**
+ [Видео-доклад "Чистая архитектура. Погружение"](https://www.youtube.com/watch?v=JePQFYb5WJI&feature=youtu.be) **(\*\*\*\*)**
+ [Пример использования архитектуры](https://github.com/android10/Android-CleanArchitecture) **(\*\*\*)**
+ [Заблуждения Clean Architecture](https://habr.com/ru/company/mobileup/blog/335382/) **(\*\*\*)**
+ [Руководство по применению чистой архитектуры в Android проектах](https://github.com/AndroidArchitecture/AndroidArchitectureBook) **(\*\*)**

**3. DI**
+ [Dagger 2 - ссылка на библиотеку](https://github.com/google/dagger)  **(\*\*\*\*)**
+ [Dagger 2 - хороший цикл статей](https://habr.com/ru/post/343248/)  **(\*\*\*\*)**
+ [Dagger 2 - еще один хороший цикл статей](https://habr.com/post/279125/)  **(\*\*\*\*)**
+ [Toothpick](https://github.com/stephanenicolas/toothpick) **(\*\*)**

**4. Многомодульность**
+ [Многомодульность](https://habr.com/ru/company/kaspersky/blog/422555/) **(\*\*)**

### Практическое задание
Переписать свое приложение, применяя архитектурный подход Clean Architecture. В реализации presentation слоя применить архитектурный паттерн MVP с использованием библиотеки Moxy. Для предоставления зависимостей в соотвествии с техникой DI использовать библиотеку Dagger 2. Для работы с базой данных использовать библиотеку Room.

---
## Рекомендуемая литература и ресурсы
---

**Материал для подготовки к собеседованиям**
+ [Записи собеседований коллег](https://cloud.simbirsoft1.com/index.php/s/mElVi7Hwp1aLcWH) Пароль: mobile **(\*\*)**
+ [Вопросы, задаваемые на собеседованиях](https://docs.google.com/document/d/1DZVWwjCPM_9QxdI7sRqMuxYppysK_R7Gu57KBci1FGs/edit?usp=sharing) **(\*\*)**
+ [Список полезных ссылок на материалы по разным темам](https://docs.google.com/document/d/1IpQC02KiaTkJkwAE4WAdn8eIXCq-qjnIyD33zZkBLI8/edit?usp=sharing) **(\*\*)**

**Система грейдов одной из компаний**
+ [Документ](https://drive.google.com/file/d/0Bzy6VkH4IrCCWlhOaXBRdVJnMGs/view?usp=sharing) **(\*\*)**

**Как доставлять сборки до QA**
+ [Инструкция по использованию TestFairy](https://docs.google.com/document/d/1huCrAUIqpoJe4sUYqgvRkozQVM2-D55rVz6_CTklfTU/edit?usp=sharing) **(\*\*)**

**Java**
+  Философия java Брюс Эккель **(\*\*)**
+  Effective Java **(\*\*)**
+  Герберт Шилдт "Java. Полное руководство" **(\*)**
+  http://kb.simbirsoft/java-education-core/ **(\*)**

**Паттерны проектирования**
+ [обзор всех паттернов и их классификация](https://refactoring.guru/ru/design-patterns) **(\*)**

**Методологии [Agile](https://habrahabr.ru/company/edison/blog/313410/)**
+ [scrum](https://habrahabr.ru/post/247319/) **(\*\*)**
+ [kanban](https://habrahabr.ru/post/64997/) **(\*\*)**

**Порталы, подкасты и дайджесты**
+ [YouTube канал Android Developers](https://www.youtube.com/channel/UCVHFbqXqoYvEWM1Ddxl0QDg) **(\*\*\*)**
+ [Подкаст про разработку](http://androiddev.apptractor.ru/) **(\*\*\*)**
+ [Статьи Хабра про Android разработку](https://habrahabr.ru/hub/android_dev/) **(\*\*\*)**
+ [Пример дайджеста, бывает много интересного](https://habrahabr.ru/company/everydaytools/blog/352580/) **(\*\*\*)**
+ [Hannes Dorfmann](http://hannesdorfmann.com/) **(\*\*)**
+ [Stfalcon](https://stfalcon.com/ru/blog) **(\*\*)**

**Телеграм**
+ [Канал андроида](https://telegram.me/android_ru) **(\*\*)**
+ [Канал подкаста](https://t.me/androiddevpodcast) **(\*\*)**
+ [Канал архитектуры](https://t.me/Android_Architecture) **(\*)**

**Прочие ресурсы**
+ [Склад библиотек](https://android-arsenal.com/) **(\*)**
+ [Иконки](https://material.io/icons/) **(\*)**

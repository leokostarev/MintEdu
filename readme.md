#  MINT.EDU
[github](https://github.com/BadCatSet/YalWeb2022)
***
**mint.edu** - бесплатный сервис для свободного
создания и прохождения обучающих тестов.

### Общее описание системы

- поддержка разнообразных типов заданий в рамках каждого теста
- авторизация в системе для указания авторства при создании
теста и верификации тестируемого для прохождения теста;
- интерфейс для создания тестов в текстовой форме, включающий;
    1. условие теста;
    2. правильный ответ;
- интерфейс для прохождения тестов, имеющий несколько вариантов;
   1. ввод ответа в текстовой или числовой форме;
   2. выбор из нескольких вариантов ответа;
   3. выбор нескольких вариантов из списка;
   4. *заполнение пропусков в тексте;
   5. *заполнение пропусков в тексте выбором из нескольких вариантов;
   6. *соответствие одной группы элементов другой;
   7. *упорядочивание элементов;
- автоматическая проверка решения путем сравнения его с вариантом
ответа, указанным создателем теста;

Каждый тест может включать в себя несколько заданий различных типов.

Доступ к прохождению теста осуществляется по ссылке, которую создатель
отсылает тестируемому.

###Используемые технологии

- база данных sqlite3 для хранения информации о пользователях и тестах;
- сервер flask в качестве основы приложения;
- flask-wtf для создания веб-форм;
- flask_login для авторизации пользователей и нахождения в системе;
- logging для логирования процесса работы приложения;
- bootstrap для библиотеки стилей;

ссылка на heroku:
    https://mint-edu-yalweb2022.herokuapp.com/

---

*функции запланированные, но пока не реализованные.

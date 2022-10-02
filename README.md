Данный проект - это финальное задание по курсу "Тестировщик-автоматизатор на Python (QAP) на онлайн-платформе "Skillfactory" Содержание задания: написать 50-70 автоматизированных тестов с использованием PyTest и Selenium для тестирования интернет-магазина.

Проект разработан для тестирования сайта интернет-магазина "Ozon" (https://www.ozon.ru/)

В файле "config" прописаны тестовые данные для выполнения тестов,как проверки их успешного прохождения, так и выполнения тестов, так же информация о базовом URL

В файле conftest.py содержится фикстура для используемого вебдрайвера Chrome. В проекте уже имеется драйвер для него.

Папка pages содержит : Base_page содержить базовый класс BasePage,c методами используемыми для выполнения тестов. Main_page содержить все локаторы , для выполнения тестов

Файл requirements.txt содержит перечень необходимых библиотек для работы проекта.

Команды для запуска всех тесто pytest tests

Автоматизировать тестирование авторизации сайта невозможно, так как вход на сайт осуществляется по коду, который приходит на мобильный телефон. Тестирование авторизации возможно только мануально.

Тесты проверяют видимость кнопок на главной странице сайта, их кликабельность , корректность названия кнопок , соответствие разделов , куда ведет клик по кнопке .

Попытки с помощью ActionChains написать тесты для тестирования субменю кнопки "Каталог" не увенчались успехом .


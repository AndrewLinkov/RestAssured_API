Данный проект реализует Арі тесты для Rest Assured на JUnit по следующим тестовым случаям

ТК 1 

Реализуем метод Get
Используя сервис https://reqres.in/ получить список пользователей со второй
(2) страницы:
1. Убедиться что имена файлов-аватаров пользоваталей совпадают;
2. Убедиться, что email пользователей имеет окончание reqres.in;


ТК 2

Реализуем метод Post
Используя сервис https://reqres.in/ протестировать регистрацию пользователя в системе:
1. Реализация ТК с успешной регистрацией;
2. Реализация ТК с НЕуспешной регистрацией (отсутствует пароль);

ТК 3

Используя сервис https://reqres.in/ убедиться, что операция LIST<RESOURCE>
возвращает данные, отсортированные по годам.

ТК 4

Используя сервис https://reqres.in/ попробовать удалить второго 
пользователя и сравнить статус-код.

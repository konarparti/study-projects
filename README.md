# Notes
### [PartyInvites](https://github.com/konarparti/notes/tree/master/PartyInvites)
Цель проекта: изучение основ ASP.NET Core с использованием технологии MVC
- Небольшое веб-приложение, представляющее собой:  
  - Главный экран с сообщением о предстоящей вечеринке и приглашением 
  - Форму, с помощью которой можно принять приглашение или отказаться от нешл  
  - Экран завершения опроса с предложением посмотреть, кто уже заполнил форму и будет на вечеринке  
  - Таблица с теми, кто прошел "опрос" и выразил согласие прийти  
  
  
Хранение данных о посетителях осуществляется в обычной коллекции, что для учебного проекта допустимо, однако лучше использовать БД.  

Также для данного проекта созданы [модульные тесты](https://github.com/konarparti/notes/tree/master/PartyInvites.Tests) как с [использованием собственных имитационных моделей](https://github.com/konarparti/notes/commit/ff74c9703421753dea0348ee9f8423030754608b#diff-0a534eb3bad169a943bc0f6cacceee241f33b8c5317002a01028d3d6ddf786b5), так и с [применением технологии Moq](https://github.com/konarparti/notes/commit/a36438ec66c962eda76ce9e6bffeb547119b4d9b#diff-0a534eb3bad169a943bc0f6cacceee241f33b8c5317002a01028d3d6ddf786b5)  

---
### [Store](https://github.com/konarparti/notes/tree/master/Store)
Цель проекта: изучение основ ASP.NET Core с использованием технологий MVC, EntityFramework, Moq, ...
- Небольшое веб-приложение интернет магазина. Основные моменты:  
  - Главный экран с боковой панелью (пока не заполнена) и основным контентом
  - Контент представляет собой 3 каталог товаров с названием, описанием и ценой
  - Каталог разделен на 3 страницы, для перемещения по ним реализована страничная форма представления
  - В проекте используется Microsoft SQL Server для хранения информации о продукции
  - Проект содержит [модульные тесты](https://github.com/konarparti/notes/tree/master/Store.Tests) для проверки работоспособности контроллеров и класса вспомогательной функции дескриптора PageLinkTagHelper
  - (upd 5.02.22)
  - На главном экране появилась навигационная панель для выборки и отображения конктретной категории товаров
  - У каждого товара есть кнопка "Добавить в корзину"
  - Формируется корзина товаров с подсчетом общей стоимости покупки
  - Навигационная панель и работа с корзиной покрыты модульными тестами
 ---   
 

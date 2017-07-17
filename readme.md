# Тестовое задание на курс React

Создать игру найди 2 одинаковые картинки:

Загружается поле, на котором лежат перевернутые карты(изображения)
При нажатии на карту, данная карта становится видимой на ~1.5 секунды, при нажатии на другую карту, она так же становится видимой.

Одновременно может быть открыто только 2 карты.

Если у двух карт изображения совпадают, данные карты снимаются с экрана и становятся недоступными для нажатия

## Существую следующие ограничения

- css минимален.
- запрещено использовать любые библиотеки

## Server endpoints

`GET /api/v1/items`

Ответ:
```ts
{ width:number, height:number }
```

`GET /api/v1/pictures`

Ответ:
```ts
{ pictures: ['static/1.jpg', 'static/2.jpg', ...] }
```

Данные адреса необходимо использовать для генерации поля с картинками

---

После выполнения задания разместите ваше решение в [github]() репозитории и отправьте ссылку на решение на почту oleg.lustenko@gmail.com c темой письма: <strong>Тестовое задание: базовый курс React</strong>

Если у вас остались вопросы по выполнению задания, указывайте тему письма: <strong>Вопрос Тестовое задание React</strong>

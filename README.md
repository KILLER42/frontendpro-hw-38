# ДЗ 38. Функція Зміни Параметрів URL

Функція Зміни Параметрів URL:

- Створіть функцію updateQueryString(url, key, value), яка змінює або додає параметр запиту в URL.
- Функція повинна повертати новий URL з оновленим або доданим параметром запиту.
Параметр запиту в URL

`queryParams` в контексті веб-розробки або API є частиною URL, яка використовується для передачі додаткових параметрів або інструкцій серверу. Вони дозволяють внести більше гнучкості та специфіки в HTTP запит.

Зазвичай `queryParams` розташовуються після знака питання (?) у URL-адресі. Кожен параметр має ключ (ім'я параметра) та значення, розділені знаком рівності (=). Різні параметри відділяються один від одного за допомогою амперсанду (&).

```javascript
https://example.com/search?q=query&sort=ascending&page=2


```
У цьому URL:

- `q=query` - це `queryParams`, де `q` - ключ, а `query` - значення, яке визначає пошуковий запит.

- `sort=ascending` та `page=2` - інші `queryParams`, що визначають порядок сортування і номер сторінки відповідно.

`queryParams` використовуються для передачі даних, які змінюють поведінку або результати запиту, не змінюючи URI ресурсу, до якого звертаються.

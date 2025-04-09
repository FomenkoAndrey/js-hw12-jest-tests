# ДЗ #12

## 1. Завантажуємо репозиторій та розгортаємо проект

`npm install`

або

`yarn`

_yarn повинен бути встановлений глобально, це можна зробити командой:_

`npm i -g yarn`

## 2. Виконуємо задачі для .js файлів

Ви можете реалізувати власний код у файлі `main.js` та розробити для нього тести.
Складність коду і тестів, а також їх кількість не регламентуються.

Вимоги до тестів:

- Тести повинні містити блоки `describe`
- Тести повинні містити блоки `test` або `it`
- Тести повинні успішно виконуватись

Метатест (`supertest.test.js`) перевірятиме правильність структури ваших тестів та їх успішне виконання.

## 3. Запускаємо тести

`yarn test`

або

`npm test`

Для запуску метатесту використовуйте:

`npx vitest run supertest.test.js`

## 4. Перевіряємо результат

Якщо **тести не пройдені**

- Аналізуйте результати тестів, ідентифікуйте та виправляйте помилки у коді.

Якщо **тести пройдені**:

1. Зробіть скріншот пройдених тестів та відправте його як доказ виконання завдання.
2. Завантажте ваш проект на GitHub.
3. Надайте пряме посилання на файл (або файли) JavaScript (або TypeScript) у вашому проекті.

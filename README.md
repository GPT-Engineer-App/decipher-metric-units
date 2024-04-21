# decipher-metric-units

Коли робот Алгоритміус називає якусь відстань, пло- щу або об'єм, він використовує безліч приставок Між- народної системи одиниць (SI). Кожна приставка си- стеми SI множить одиницю виміру на деякий сту- пінь десяти. Наприклад, Алгоритміус може сказати <<<<megananokilogigamicrometer», що відповідатиме 103 метрам (106 10-9103109 10-6). Якщо йдеться про об'єм, то він може сказати «millimeter^3», що відпові- датиме 10-9 метрам кубічним.
Алгоритміус використовує тільки такі приставки:
• tera 1012
• giga 109
• mega 106
• kilo - 103
• deci 10-1
• centi 10-2
• milli 10-3
micro10-6
• nano
10-9
Правила застосування префіксів до квадратних і кубічних величин також є стандартними. На- приклад, один кубічний метр дорівнює 106 кубічним сантиметрам.
Напишіть програму, яка буде «розшифровувати» те, що сказав Алгоритміус, тобто переводити названу одиницю виміру в метри, метри квадратні або метри кубічні, залежно від розрядності вихід- ної одиниці виміру. Нескладно показати, що у вас вийде величина, що дорівнює 10" (метрів, метрів квадратних або метрів кубічних), де х ціле число.
Формат входных данных
Вхідні дані містять єдиний рядок слово, сказане Алгоритміусом. Довжина слова не перевищує 105. Гарантується, що слово було отримано послідовним приписуванням кількох префіксів з таблиці до «meter», «meter^2» або «meter^3».
Формат выходных данных
Виведіть ціле число х, таке що якщо перевести одиницю виміру, названу Алгоритміусом, у метри, метри квадратні або метри кубічні відповідно, то вийде 102.
Примеры
тест
meter
ответ
0
тест
kilometer
ответ
3

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/decipher-metric-units.git
cd decipher-metric-units
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

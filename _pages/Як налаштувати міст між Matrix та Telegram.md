---
layout: page
title: Як налаштувати міст між Matrix та Telegram?
---
## Мости для чатів Telegram

Міст між кімнатою Matrix та чатом Telegram можна налаштувати за допомогою бота [t2bot](https://t2bot.io/). Для цього необхідно мати права запрошувати користувачів в Telegram-чат та Matrix-кімнату та писати там повідомлення.

1. В Matrix запрошуємо **@telegram:t2bot.io** в кімнату та чекаємо поки він приєднається.
2. В Telegram запрошуємо **@matrix_t2bot** в чат та чекаємо поки він приєднається. Пишемо команду `/run` і у відповідь бот має написати ID чату.
3. Повертаємось у Matrix і пишемо боту `!tg bridge <ID чату Telegram>`. Бот має запитати підтвердження.
4. Міст налаштований. Для модерації кімнати чи чату необхідно дати відповідні права боту.

## Мости для каналів Telegram (дзеркала)

На відміну від звичайних чатів, канали не дають можливість користувачам спілкуватись, а лише публікують пости. Дзеркала для каналів дають можливість читати канали Telegram в Matrix без акаунта Telegram.

### RSS-дзеркало

Для налаштування дзеркала цим способом повідомлення каналу Telegram будуть транслюватись в кімнаті Matrix через RSS за допомогою сервісу [RSSHub](https://rsshub.app/). Цей спосіб доволі повільний і повідомлення можуть пересилатись зі зламаним форматуванням. Також повідомлення не будуть містити фото і відео.

1. Дізнаємось назву каналу. Наприклад, для `https://telegram.me/V_Zelenskiy_official` вона буде **@V_Zelenskiy_official**.
2. Запрошуємо в кімнату Matrix будь якого RSS-бота (вбудований бот не підходить бо він налаштовується через меню, а не командами).
3. Даємо RSS-боту команду !rss subscribe `https://rsshub.app/telegram/channel/%назва каналу%`. Наприклад, для **@V_Zelenskiy_official** комадна буде виглядати як `https://rsshub.app/telegram/channel/V_Zelenskiy_official`. Якщо все пройшло успішно, бот поверне ID підписки.
4. Задаємо формат повідомлень в Matrix-кімнаті. Даємо комадну боту:
   ```sh
   !rss template %ID підписки%
   $summary
   ```
5. Дзеркало налаштоване.


Переклад інструкції зі сторінки [Connecting your Telegram community](https://t2bot.io/telegram/)

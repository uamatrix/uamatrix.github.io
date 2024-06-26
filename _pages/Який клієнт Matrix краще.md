---
layout: page
title: Який клієнт Matrix краще?
---

## Порівняння клієнтів Matrix

Протокол Matrix має багато клієнтів різного ступеню готовності і активності. Найкращим для ознайомлення з месенджером є [Element](#element). Якщо досвіду користування Matrix немає зовсім, далі можна не читати і сміливо встановлювати цей клієнт на всі пристрої. Якщо ж певний досвід вже є і Element чимось не влаштовує або ж хочеться спробувати новий клієнт, знайти клієнт під певну задачу чи дізнатись який додатковий функціонал може бути присутній в клієнтах Matrix, їх порівняння далі може бути цікавим. 

В порівнянні присутні як активні так і закинуті проекти. В його основі лежить інформація зі сторінки [delightful matrix](https://codeberg.org/yarmo/delightful-matrix#clients). Назви клієнтів в таблицях посилаються на їх опис нижче.

### Функції

Функціонал клієнтів може сильно відрізнятись. Вони можуть бути мінімалістичними і зосереджені навколо певної моделі використання (наприклад, консольні клієнти) та мати сильно урізаний функціонал, або ж пропонувати додаткові можливості, які відсутні в [Element](#element), чи намагаються запропонувати однаковий досвід взаємодії на різних платформах.

| Бали | Назва                                     | E2ee | Простори | Voip 1на1 | Voip Jitsi | Гілки | Sso | Мультиаккаунт | Багатомовність |
|:----:|-------------------------------------------|:----:|:--------:|:---------:|:----------:|:-----:|-----|:-------------:|:--------------:|
|  7   | [SchildiChat](#schildichat)               |  ✅  |    ✅    |    ✅     |     ✅     |  ✅   | ✅  |      ✅       |       ❌       |
|  7   | [FluffyChat](#fluffychat)                 |  ✅  |    ✅    |    ✅     |     ✅     |  ❌   | ✅  |      ✅       |       ✅       |
|  7   | [Element](#element)                       |  ✅  |    ✅    |    ✅     |     ✅     |  ✅   | ✅  |      ❌       |       ✅       |
|  6   | [Nheko](#nheko)                           |  ✅  |    ✅    |    ✅     |     ❌     |  ✅   | ✅  |      ❌       |       ✅       |
|  6   | [Hydrogen](#hydrogen)                     |  ✅  |    ❌    |    ✅     |     ✅     |  ❌   | ✅  |      ✅       |       ✅       |
|  5   | [iamb](#iamb)                             |  ✅  |    ✅    |    ❌     |     ❌     |  ✅   | ✅  |      ✅       |       ❌       |
|  5   | [NeoChat](#neochat)                       |  ✅  |    ✅    |    ❌     |     ❌     |       | ✅  |      ✅       |       ✅       |
|  4   | [Thunderbird](#thunderbird)               |  ✅  |    ❌    |    ❌     |     ❌     |       | ✅  |      ✅       |       ✅       |
|  4   | [Syphon](#syphon)                         |  ✅  |    ❌    |    ❌     |     ❌     |       | ✅  |      ✅       |       ✅       |
|  4   | [Fractal](#fractal)                       |  ✅  |    ❌    |    ❌     |     ❌     |  ❌   | ✅  |      ✅       |       ✅       |
|  3   | [gotktrix](#gotktrix)                     |  ❌  |    ✅    |    ❌     |     ❌     |  ❌   | ✅  |      ✅       |       ❌       |
|  3   | [Commet](#commet)                         |  ✅  |    ✅    |    ❌     |     ❌     |  ❌   | ❌  |      ✅       |       ❌       |
|  3   | [Cinny](#cinny)                           |  ✅  |    ✅    |    ❌     |     ❌     |  ❌   | ✅  |      ❌       |       ❌       |
|  2   | [matrix-commander](#matrix-commander)     |  ✅  |    ❌    |    ❌     |     ❌     |       | ✅  |      ❌       |       ❌       |
|  2   | [kazv](#kazv)                             |  ✅  |    ❌    |    ❌     |     ❌     |  ❌   | ❌  |      ❌       |       ✅       |
|  2   | [Quaternion](#quaternion)                 |  ❌  |    ❌    |    ❌     |     ❌     |  ❌   | ✅  |      ✅       |       ❌       |
|  2   | [Element X](#element-x)                   |  ✅  |    ❌    |    ❌     |     ❌     |  ❌   | ❌  |      ❌       |       ✅       |
|  1   | [gomuks](#gomuks)                         |  ❌  |    ❌    |    ❌     |     ❌     |  ❌   | ✅  |      ❌       |       ❌       |
|  0   | [mnotify](#mnotify)                       |  ❌  |    ❌    |    ❌     |     ❌     |  ❌   | ❌  |      ❌       |       ❌       |
|  0   | [Quadrix](#quadrix)                       |  ❌  |    ❌    |    ❌     |     ❌     |  ❌   | ❌  |      ❌       |       ❌       |

Раніше подібна таблиця порівняння клієнтів була на сайті [Matrix](https://matrix.org/ecosystem/clients/) але наразі там тільки список клієнтів. Що і спонукало створити порівняльну таблицю самостійно.

Окрім цього може бути цікава [таблиця](https://privacydev.net/communication_tools.html) порівняння функціоналу Element з іншими програмами обміну повідомленнями.

### Платформи

| Бали | Назва                                 | Android | iOS | Linux | macOS | watchOS | Web | Windows |
|:----:|---------------------------------------|:-------:|:---:|:-----:|:-----:|:-------:|:---:|:-------:|
|  6   | [Element](#element)                   |   ✅    | ✅  |  ✅   |  ✅   |   ❌    | ✅  |   ✅    |
|  3   | [Thunderbird](#thunderbird)           |   ❌    | ❌  |  ✅   |  ✅   |   ❌    | ❌  |   ✅    |
|  3   | [Ditto](#ditto)                       |   ✅    | ✅  |       |       |   ❌    | ✅  |         |
|  3   | [Commet](#commet)                     |   ✅    |     |  ✅   |       |   ❌    |     |   ✅    |
|  2   | [Syphon](#syphon)                     |   ✅    | ✅  |  ❌   |  ❌   |   ❌    | ❌  |   ❌    |
|  2   | [Element X](#element-x)               |   ✅    | ✅  |  ❌   |  ❌   |   ❌    | ❌  |   ❌    |
|  2   | [Continuum](#continuum)               |         |     |  ✅   |  ✅   |   ❌    |     |         |
|  1   | [Watch The Matrix](#watch-the-matrix) |   ❌    | ❌  |  ❌   |  ❌   |   ✅    | ❌  |   ❌    |
|  1   | [Cinny](#cinny)                       |   ❌    | ❌  |  ❌   |  ❌   |   ❌    | ✅  |   ❌    |
|      | [AgentSmith](#agentsmith)             |         |     |       |       |   ❌    |     |         |

### Трекери і дозволи

При встановленні клієнту Matrix на мобільні пристрої може бути важливим до яких датчиків пристрою просить доступ клієнт і які дані збирає трекерами. Можливо клієнт буде працювати взагалі без дозволів. В порівнянні враховується тільки загальна кількість трекерів і дозволів. Для порівняння використовувався сервіс [εxodus](https://reports.exodus-privacy.eu.org/en/).

| Бали | Назва                       | Трекери | Дозволи |
|:----:|-----------------------------|:-------:|:-------:|
|  07  | [Ditto](#ditto)             |    0    |    7    |
|  10  | [Syphon](#syphon)           |    0    |   10    |
|  18  | [Element X](#element-x)     |    1    |   17    |
|  18  | [Quadrix](#quadrix)         |    1    |   17    |
|  29  | [Element](#element)         |    1    |   28    |
|  29  | [SchildiChat](#schildichat) |    1    |   28    |
|  40  | [FluffyChat](#fluffychat)   |    1    |   39    |

### Популярність у користувачів

Для визначення популярності клієнтів Matrix було проведено опитування користувачів в кімнаті [Вільне ПЗ Україна](https://matrix.to/#/!QFgiqoAkggMqmfsyEc:matrix.org/$cn7n2WJnj87os4VJuljAnO3pZ3HvbvgAXSir3OdIFkI?via=matrix.org&via=matrix.kyiv.dcomm.net.ua&via=matrix.lviv.dcomm.net.ua).

| Голоси | Назва                       |
|:------:|-----------------------------|
|   11   | [Element](#element)         |
|   8    | [SchildiChat](#schildichat) |
|   4    | [Element X](#element-x)     |
|   3    | [Fractal](#fractal)         |
|   1    | [Nheko](#nheko)             |
|   1    | [Cinny](#cinny)             |

Результати отримані на підставі 28 голосів.

## Опис клієнтів Matrix та відгуки про їх використання

### AgentSmith

![AgentSmith](/images/AgentSmith.png)

**Опис**

Дозволяє спілкуватись в Matrix за допомогою улюбленого IRC-клієнта.

[Початковий код AgentSmith](https://github.com/nilsding/AgentSmith)

### chat

**Опис**

Простий веб-застосунок Matrix для мобільних пристроїв і комп’ютерів, написаний за допомогою Vue у JavaScript.

[Початковий код chat](https://git.cybre.town/adb/matrix-chat)

### Cinny

![Cinny](/images/Cinny.png)

**Опис**

Клієнт Matrix, зосереджений на простому, елегантному та безпечному інтерфейсі. Головна мета — створити зручну для людей програму обміну миттєвими повідомленнями, яка має сучасний вигляд.

**Відгук**

Cinny вибирають через приємний вигляд інтерфейсу, функції спойлера, ніліпок, швидкого доступу до пошуку.

[Сайт](https://cinny.in/)

[Початковий код Cinny](https://github.com/cinnyapp/cinny)

### Commet

![Commet](/images/Commet.png)

**Опис**

Клієнт для Matrix, орієнтований на надання багатофункціонального досвіду при збереженні простого інтерфейсу. Мета полягає в тому, щоб створити безпечний додаток, який поважає конфіденційність, без шкоди для функцій, які ви звикли очікувати від сучасного чат-клієнта.

[Початковий код Commet](https://github.com/commetchat/commet)

### Continuum

**Опис**

Клієнт Matrix написаний на Kotlin.

[Початковий код Continuum](https://github.com/koma-im/continuum-desktop)

### Ditto

[Початковий код Ditto](https://gitlab.com/ditto-chat/ditto)

### Element

![Element](/images/Element.png)

**Опис**

"Еталонний" клієнт Matrix, що підтримує всі базові функції, зосереджений на продуктивності та зручності. Краще інших підходить для новачків.

**Відгук**

Використовувати Element Nightly на десктопі варто бо він має красивий інтерфейс, доволі функціональний та має прийнятну швидкість роботи. Web-версія Element на десктопі теж дивно трохи виглядає.

[Сайт](https://element.io/)

[Початковий код Element](https://github.com/element-hq)

### Element X

![Element X](/images/Element X.png)

**Опис**

Абсолютно новий - найшвидший в історії - додаток для спілкування на основі Matrix.

**Відгук**

Вам варто використовувати Element X, якщо Element для вас повільний. Хоча в цьому клієнті не вистачає деяких функцій Element. Інтерфейс програми вже виглядає професійно, але Element X поступається функціоналом іншим клієнтам. Як тільки в ньому з'являться маркер прочитаних повідомлень, перехід по цитатам, простори та треди, програму можна буде рекомендувати до використання всім.

[Початковий код Element X](https://github.com/element-hq)

### FluffyChat

![FluffyChat](/images/FluffyChat.png)

**Опис**

Це відкритий, некомерційний і симпатичний клієнт Matrix з відкритим вихідним кодом, написаний на Flutter. Мета програми - створити простий у використанні месенджер з відкритим вихідним кодом, доступний для всіх.

**Відгук**

Fluffy красивий і повільний. Особливо все погано в стільничній версії. Є підтримка просторів, колись дзвінки були дивним чином зроблені. Інтерфейс програми може бути не на 100% інтуїтивний для пересічного користувача.

[Початковий код FluffyChat](https://github.com/krille-chan/fluffychat)

### Fractal

![Fractal](/images/Fractal.png)

**Опис**

Програма для обміну повідомленнями за протоколом Matrix для GNOME, написана на Rust. Її інтерфейс оптимізовано для
співпраці у великих групах, таких як проекти вільного програмного забезпечення, і підходить для всіх екранів, великих і малих.

**Відгук**

Користувачі вибирають Fractal, бо:

- GTK (гарно, вписується в Linux систему);
- вилизаний UI/UX;
- достатня підтримка специфікації, аби не наверталися сльози;

«Фрактал» розвивається, тож недоліки (сподіваюсь) поступово усуватимуться. Натепер є наступні:

- відсутність спелчекера;
- не можна мишкою скопіпастити фрагмент повідомлення: є лише опція меню «Скопіювати текст» (повністю);
- цитування у відповідях не обрізається: якщо там «простирадло», то воно буде й у відповіді;
- індикатори активності (маленькі аватарки, що позначають, де зупинився відвідувач) не оверлейні, як в «Елементі», а займають місце між повідомленнями, через що стрічка смикається;
- поки що не видно наліпок, голосувалок, можливо, якихось інших нових фіч;
- чимало дрібних баґів і недоліків (наприклад іноді глючить покажчик непрочитаних повідомлень).

Іноді доводиться бігати в «Елемент», та загалом нормальний клієнт.

[Початковий код Fractal](https://gitlab.gnome.org/World/fractal)

### gomuks

![gomuks](/images/gomuks.png)

**Опис**

Термінальний клієнт Matrix, написаний на Go.

[Початковий код gomuks](https://github.com/tulir/gomuks)

### gotktrix

![gotktrix](/images/gotktrix.png)

**Опис**

Матричний клієнт на Go та GTK4.

[Початковий код gotktrix](https://github.com/diamondburned/gotktrix)

### Hydrogen

![Hydrogen](/images/Hydrogen.png)

**Опис**

Мінімалістичний клієнт Matrix, зосереджений на продуктивності, офлайн-функціональності та широкій підтримці браузерів.

[Початковий код Hydrogen](https://github.com/element-hq/hydrogen-web)

### iamb

![iamb](/images/iamb.png)

**Опис**

[Початковий код iamb](https://github.com/ulyssa/iamb)

### kazv

![kazv](/images/kazv.png)

**Опис**

[Початковий код kazv](https://lily-is.land/kazv/kazv)

### Matrix IRCd

**Опис**

[Початковий код Matrix IRCd](https://github.com/matrix-org/matrix-ircd)

### Matrix Static

**Опис**

[Початковий код Matrix Static](https://github.com/matrix-org/matrix-static)

### matrix-client el

![matrix-client.el](/images/matrix-client.el.png)

**Опис**

[Початковий код matrix-client.el](https://github.com/alphapapa/matrix-client.el)

### matrix-commander

**Опис**

[Початковий код matrix-commander](https://github.com/8go/matrix-commander)

### matrixcli

**Опис**

[Початковий код matrixcli](https://github.com/saadjsct/matrixcli)

### Mirage

![Mirage](/images/Mirage.png)

**Опис**

[Початковий код Mirage](https://github.com/mirukana/mirage)

### mnotify

**Опис**

[Початковий код mnotify](https://github.com/rumpelsepp/mnotify/)

### NeoChat

![NeoChat](/images/NeoChat.png)

**Опис**

**Відгук**

Поки що програма не працює настільки стабільно, щоб нею можна було користуватись кожен день. 

[Початковий код NeoChat](https://invent.kde.org/network/neochat)

### Nheko

![Nheko](/images/Nheko.png)

**Опис**

[Початковий код Nheko](https://github.com/Nheko-Reborn/nheko)

### Nio

![Nio](/images/Nio.png)

**Опис**

[Початковий код Nio](https://github.com/niochat/nio)

### Quadrix

![Quadrix](/images/Quadrix.png)

**Опис**

[Початковий код Quadrix](https://github.com/alariej/quadrix)

### Quaternion

![Quaternion](/images/Quaternion.png)

**Опис**

[Початковий код Quaternion](https://github.com/quotient-im/Quaternion) 

### quickmedia

![quickmedia](/images/quickmedia.png)

**Опис**

[Початковий код quickmedia](https://git.dec05eba.com/QuickMedia/about/)

### Rambox CE

![Rambox CE](/images/Rambox CE.png)

**Опис**

[Початковий код Rambox CE](https://github.com/ramboxapp/community-edition)

### SchildiChat

![SchildiChat](/images/SchildiChat.png)

**Опис**

Той же Element, але з оптимізованим кодом тому працює трохи швидше. Підтримує всі функції Element. Також рекомендований новачкам.

**Відгук**

Користуюсь ShcildiChat на телефоні й компʼютері. Основна перевага над Element це можливість відкривати чат на моменті останнього повідомлення. Ще, здається, стиль самих повідомлень тут трохи змінений. Також є перевагою, що для довгих повідомлень відпові відображаються не повністю, а скорочено з можливістю швидко до них повернутись.

Стількиковий варіант має мало переваг перед Element, але версія SchildiChat Next для мобільних пристроїв наразі функціональніша за Element X бо вже має, наприклад, підтримку просторів.

[Початковий код SchildiChat](https://github.com/SchildiChat)

### Scylla

![Scylla](/images/Scylla.png)

**Опис**

[Початковий код Scylla](https://github.com/DanilaFe/Scylla)

### Spectral

![Spectral](/images/Spectral.png)

**Опис**

[Початковий код Spectral](https://gitlab.com/spectral-im/spectral)

### Syphon

![Syphon](/images/Syphon.png)

**Опис**

[Початковий код Syphon](https://github.com/syphon-org/syphon)

### Thunderbird

![Thunderbird](/images/Thunderbird.png)

**Опис**

[Сайт](https://www.thunderbird.net/uk/)

[Початковий код Thunderbird](https://hg.mozilla.org/comm-central)

### Watch The Matrix

**Опис**

Matrix-клієнт для watchOS.

[Початковий код Watch The Matrix](https://github.com/pixlwave/Watch-The-Matrix)

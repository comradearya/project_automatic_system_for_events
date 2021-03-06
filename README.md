# project_automatic_system_for_events

Система створюється для автоматизації пошуку бігових подій, реєстрації на них та здійснення благодійних внесків (зазвичай усі бігові події є благодійними). Виглядає вона у формі десктопного додатку, у який користувач може зайти, зареєструватись, переглянути події, занесенї до БД, вибрати ту, в якій хоче приймати участь, ознайомитись з інформацією про подію та сплатити, за необхідністю, членський внесок. Після кожного внеску, здійсненого за допомогою системи «SEApp», на рахунок організації начисляється комісія, знята з внеску, у розмірі 5% від всього пожертвування. Решта коштів надходить на карточку засновника події. Система реєстрації розробляється під користувача, та користувача з правами на створення подій.

## Вимоги до функціональності:
Підсистема перегляду має містити у собі:
- вікно “Вхід” (з двома текстовими полями для логіну на паролю, кнопками “Вхід” та “Реєстрація”);
- вікно “Реєстрація”, яке відкривається у випадку натиснення на відповідну кнопку у минулому вікні, та яке містить поля для вводу інформації про користувача;
головну сторінку (на ній будуть загальні відомості про забіги “SEApp” (натиснувши на строку з подією буде зявлятися вікно  “Зареєструватись?”, де користувач має змогу натиснути “Так”, “Ні”), кнопки пошуку та фільтрації забігів, та кнопка “Додати подію”;
-сторінку для перегляду кабінету користувача (де буде виводитись інформація введена при реєстрації).
- сторінку для створення події, яка активна лише за умови, якщо користувач має на це привілегію.

## Здійснення стартового внеску має бути доступне лише авторизованим у системі
користувачам. Дані користувача (ПІБ, номер телефону,вік, логін та пароль) при реєстрації зберігаються у базу даних клієнтів.
Адміністратори веб-сайту мають контролювати справність роботи системи,
оновлювати інформацію про забіги, надавати їм опис, загалом,
модифікувати вже існуючі події

## Вимоги до видів забезпечення.
Для роботи системи потрібен сервер БД, для зберігання бази клієнтів
та їх транзакцій, а також подій та інформацій про них.


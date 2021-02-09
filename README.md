# Где МКС

Serverless [навык Алисы](https://dialogs.yandex.ru/store/skills/8039a055-polyus-holod) на Node.js. Сообщает погоду (температуру) на Северном и Южном полюсах?

### Как это работает?

Пользователь говорит: «*Алиса, запусти навык полюс холода*»;

Алиса отвечает приветственным сообщением навыка: «*cпросите какой полюс холоднее, северный или южный?*»;

На любую следующую фразу происходит:
* Поход в [OpenWeather API](https://openweathermap.org/api) за текущей погодой на полюсах;
* Определяется на каком полюсе холоднее и сообщается температура.

Деплой происходит через [Функцию в Яндекс.Облаке](https://yandex.ru/dev/dialogs/alice/doc/deploy-ycloud-function-docpage/).

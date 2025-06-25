# 🌗 My Vue.js App

![Светлая тема](./screenshots/light.png)
![Тёмная тема](./screenshots/dark.png)

## About Enviroment

🖥️ Проект разработан и протестирован на macOS для Chrome (Рекомендованная ширина экрана: 1440px)

⚙️ Node.js: 22.17.0

📦 npm: 11.4.2

❗ Поддержка Windows/Linux не гарантируется

##### Но Вы можете попробовать его запустить на своей операционной системе.

##### Для этого удалите поле "os" в package.json или измените на значение ниже:

```json
{
  "os": ["darwin", "linux", "win32"]
}
```

##### В поле "engines" в package.json также содержатся подробности о поддерживаемых версиях NodeJS и npm

## How to sign in (данные для входа)

- email: 'some.user@automation.testing'
- password: '123456'

### Project Setup & Compile and Hot-Reload for Development

```sh
npm start
```

###### Перед `"start"` npm запустит `npm clean-install`

### Project Setup & Type-Check, Compile and Minify for Production

```sh
npm run build
```

###### Перед `"build"` npm запустит `npm clean-install`

###### Есть honeypot-утечка .env в проекте, чисто ради фана. Но при этом всё по уму и безопасно.

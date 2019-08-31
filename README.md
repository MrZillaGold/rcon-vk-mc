# Rcon для ВКонтакте

![Sample](https://sun9-2.userapi.com/c855136/v855136899/d95d4/kdaMzaVumkE.jpg)

***

Бота можно использовать для всех серверов и игр с поддержкой Rcon!

Перед работой установите пакеты: `npm i`.

Откройте файл index.js через любой редактор и измените значения первых 5 строк на свои данные:
```js
const token = "Токен от группы ВКонтакте";
const id = 175914098; // Например: https://vk.com/public175914098, ID = 175914098. (БУКВЕННЫЙ ID НЕ РАБОТАЕТ).
const ip = "127.0.0.1"; // IP-Адрес сервера.
const rconPort = 25566; // Rcon порт.
const password = "пароль"; // Rcon пароль.
const users = [233731786, 2, 3, 4, 5];
// ID пользователей ВКонтакте (через запятую) кто сможет взаимодействовать с ботом, всем остальным запрещено.
// Например: https://vk.com/id233731786, ID = 233731786
```
**Как получить токен группы?**:
- Переходим в настройки группы
- Открываем раздел `Работа с API`
- Нажимаем `Создать ключ`
- Отмечаем все галочки и нажимаем `создать`.
- Копируем ключ после его создания и вставляем в строку token.
- Нажимаем `Long Poll API`
- Включаем `Long Poll API`
- Открываем раздел `Сообщения`
- Включаем `Сообщения сообщества`

***
* [by MrZillaGold](https://vk.com/egorlisss) - по всем вопросам

[modern-rcon](https://github.com/levrik/node-modern-rcon) - подключение к Rcon /
 [vk-io](https://github.com/negezor/vk-io) - соединение с ВКонтакте

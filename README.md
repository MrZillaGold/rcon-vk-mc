<p align="center"><b>RconVK</b></p>
<p align="center">Удаленное управление сервером через <b>RCON</b> для <b>VK.COM</b></p>
<p align="center">
  <a href="https://vk.com/id233731786">По всем вопросам</a>
</p>

<p align="center">
  Перед началом работы настройте <b>config.json</b>!
  <br/>
  Скрипт запускается командой <b>npm start</b>!
</p>

```js
{
  "token": "Токен от группы ВКонтакте",
  "servers": [ // Объекты с информацией о серверах, через запятую. Можете использовать несколько серверов с разными префиксами.
    {
      "rcon": {
        "ip": "127.0.0.1", // IP-Адрес сервера
        "port": 25576, // Rcon-порт сервера
        "password": "password" // Rcon-пароль сервера
      },
      "commands": {
        "whitelist": [], // Разрешеные команды, оставьте пустым если хотите разрешить все команды.
        "blacklist": ["op", "deop MrZillaGold"], // Запрещёные команды, оставьте пустым если не хотите использовать.
        "access": [233731786, 2, 3], // ID-Пользователей ВКонтакте, которые смогут отправлять команды на данный сервер. Оставьте пустым, чтобы разрешить всем.
        "prefix": "!" // Префикс для отправки команды, например !help. Бот отправит ответ сервера на команду help.
      }
    },
    {
      "rcon"...
    }
  ]
}
```
<p align="center"><img src="https://sun9-2.userapi.com/c855136/v855136899/d95d4/kdaMzaVumkE.jpg"></p>

***

<p align="center">
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Лицензия Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br/><b>RconVK</b> доступен по <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">лицензии Creative Commons «Attribution-NonCommercial-ShareAlike» («Атрибуция —  Некоммерческое использование — На тех же условиях») 4.0 Всемирная</a>.
</p>

Привет! Это мой плагин ChatEmojiPlugin для Minecraft 1.20.1

Этот плагин добавляет кастомные эмодзи в чат. Пишешь :D_jokerge: — и в чате появляется картинка Pepe. Всего 12 эмодзи, они уже настроены.

Как установить:

1. Проверь версию сервера
   - Плагин работает на Minecraft 1.20.1 с ядром Paper.
   - Если у тебя Paper 1.20.1 — всё ок. Если нет, скачай Paper 1.20.1 тут: https://papermc.io/downloads/paper (выбери 1.20.1, например, build 196).
   - Если у тебя не Paper, а другое ядро (например, Spigot), плагин может не запуститься. Напиши мне, я помогу пересобрать его.

2. Распакуй архив
   - Внутри ChatEmojiPlugin_for_friend.zip:
     - ChatEmojiPlugin-1.0-SNAPSHOT.jar (сам плагин)
     - Папка images (картинки для эмодзи)
     - Файл config.yml (настройки)

3. Установи плагин
   - Положи ChatEmojiPlugin-1.0-SNAPSHOT.jar в папку plugins твоего сервера (например, C:\MinecraftServer\plugins\).
   - Запусти сервер один раз (java -jar paper-1.20.1.jar), чтобы появилась папка plugins/ChatEmojiPlugin.

4. Добавь картинки и настройки
   - Скопируй папку images в plugins/ChatEmojiPlugin (должно быть plugins/ChatEmojiPlugin/images).
   - Скопируй config.yml в plugins/ChatEmojiPlugin (замени старый, если он есть).

5. Настрой Dropbox
   - Плагин загружает ресурспак на Dropbox, нужен токен.
   - Зайди сюда: https://www.dropbox.com/developers/apps
   - Нажми "Create app", выбери "Scoped access", "Full Dropbox", дай имя.
   - Включи права: files.content.write и sharing.write (поставь галочки, нажми Submit).
   - Найди "Generated access token", нажми "Generate", скопируй токен (он выглядит как sl.B12345...).
   - Нужно вставить токен в плагин. Открой ChatEmojiPlugin-1.0-SNAPSHOT.jar в WinRAR, найди com/yourname/ChatEmojiPlugin.class. Если не знаешь, как вставить токен, напиши мне, я помогу.

6. Запусти сервер
   - Запусти: java -jar paper-1.20.1.jar
   - Плагин создаст EmojiPack.zip и загрузит его на Dropbox. Ссылка добавится в server.properties.

7. Проверь в игре
   - Зайди на сервер (например, localhost).
   - Напиши в чат:
     :D_jokerge: :A_smeyalsya: :B_fear: :B_boyni: :A_glypi: :B_temno: :AB_cherh: :C_stare: :A_kruti: :D_saj: :D_smoke:
   - Должно быть:
     <ТвойНик> [D_jokerge] [A_smeyalsya] [B_fear] [B_boyni] [A_glypi] [B_temno] [AB_cherh] [C_stare] [A_kruti] [D_saj] [D_smoke]

Если не работает:
- Убедись, что у тебя Paper 1.20.1.
- Проверь, вставил ли ты токен Dropbox.
- Скинь мне файл latest.log (из папки logs), я помогу.

Если хочешь добавить свои эмодзи:
- Открой config.yml, добавь новые (смотри, как сделаны текущие).
- Положи новые картинки (16x16) в папку images.
- Перезапусти сервер.

Если нужна другая версия Minecraft:
- Напиши мне, я помогу пересобрать плагин.

Пиши, если что-то не так!

[napisano with help neyronka =D]
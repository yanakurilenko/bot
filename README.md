# quest_bot
# Бот-квест "Загадка пещеры"

Телеграм бот для интерактивной текстовой игры "Загадка пещеры".


## Описание

Игра представляет собой текстовый квест, 
в котором игроку предстоит добраться до дома, 
выбирая различные варианты развития событий.

## Инструкции по использованию
- Начало приключения:
  - Найди бота в Telegram: @dungeon_mystery_bot
  - Запусти бота командой /start.
  - Начните игру командой /go
- Принимай Решения:
  - Бот будет предлагать тебе сценарии и принимать решения.
  - Кликай на кнопки на клавиатуре, чтобы двигаться дальше. 
- Следи за Сюжетом:
  - Твои решения влияют на развитие сюжета. 
  - Открывай новые локации.

## Твой выбор может спасти тебя или поставить в опасность.

## Сюжет игры
Пользователь использует команду /start для запуска бота, бот приветствует пользователя: 
- Привет! Добро пожаловать в игру "Загадка подземелья"! Нажмите /go, чтобы начать игру.'
Затем пользователь использует команду /go, бот отправляет сообщение о начале игры:
- 'Привет! еееетт! еет! Ого какое эхо! хооо! оо! Буду говорить тише, чтобы не напугать летучих мышей. В общем, друг, как ты уже понял, ты попал в подземелье. Чтобы выбраться тебе нужно сделать выбор куда идти. Так что выбирай, пока не наступила ночь.'
Далее перед пользователем появляется выбор, в какую сторону пойти, ввиде двух кнопок: 
- первая: 'Лево мне больше нравится...'
- вторая: 'Пожалуй-ка я пойду направо...'
Рассмотрим два варианты развития сюжета:
Первый: если пользователь выбирает пойти на лево, то бот отправляет ему сообщение с информацией о новой локации:
- 'Выбранная тобой дорога привела тебя к яблоне с красными, наливными яблочками. Ты очень голоден, а яблоки выглядят такими вкусными Но все же выбор за тобой: съесть или пойти дальше?'
И у пользователя появляется выбор:
- первый: 'Я очень голоден, не могу удержаться...'
- второй: 'Потерплю до дома, хотя так хочется'
После этого выбора игра завершается, и пользователь узнает свой результат.
Если выбор был - съесть яблоко, то выводится следущее сообщение и предложение начать игру заново:
- 'Увы, ты проиграл. Яблоки оказались отравленными, ты превратился в козленка('
- 'Чтобы заново пройти игру используй /go'
Если же пользователь воздержался и не съел, то бот отправит другое сообщение:
- 'Поздравляю, ты выиграл! Оказалось, что до дома было совсем не далеко, и ты дошел'
- 'Чтобы заново пройти игру используй /go'
Это был первый вариант развития событий.
Второй: если пользователь выбирает пойти на право, то бот отправляет ему сообщение с информацией о новой локации:
-  'Наконец-то ты выбрался! Оо перед тобой огромный океан, что же делать? Выбор остается за тобой: плыть или ждать помощи?'
И у пользователя появляется выбор:
- 'Будь что будет, поплыву...'
- 'Буду надеяться на лучшее, а лучше разведу огонь'
После этого выбора игра завершается, и пользователь узнает свой результат.
Если выбор был - плыть, то выводится следущее сообщение и предложение начать игру заново:
- 'Увы, ты проиграл. Оказалось, что океан был полон акул - тебя съели'
- 'Чтобы заново пройти игру используй /go'
Если же пользователь остался на берегу, то бот отправит другое сообщение:
- 'Поздравляю, ты выиграл! На корабле заметили твой костер и отвезли тебя домой)'
- 'Чтобы заново пройти игру используй /go'
На этом игра завершается, так же следует сказать, что после каждого выбора пользователя бот оправляет 1-2 картинки, чтобы игра было интереснее.
## Ссылки на изображения
В проекте использовались изображения, сгенерированные нейросетью Kandisky.

Все изображения можно найти по ссылке на [Яндекс.Диск](https://disk.yandex.ru/d/eZlYitKUYF_OJQ).

## Контакты
Для связи с разработчиками можно использовать следующие контакты:

- [Telegram](@kurilenko_yana)
- [Номер](+7 993 285 5838)


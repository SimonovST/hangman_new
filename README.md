## **game_hangman**

Написано на ruby 2.7.0р0

**Описание игры**

Игра Виселица (hangman) это классическая популярная во всем мире игра,
в которой вам необходимо отгадать скрытое слово по буквам.
Непосредственно перед игрой компьютер выбирает слово, которое вампредстоит отгадатью

**Правила игры**

Компьютер выбирает слово (из списка в файле `data/words.txt`) и показывает,
сколько в нем букв. Игрок отгадывает буквы по одной набирая.
Если буква есть в слове, компьютер показывает, сколько раз она она
в нём встречается и на каких местах.
Если буквы нет, компьютер засчитывает ошибку(Допускается ошибится 7 раз).
Если слово отгадано полностью, то игрок победил. После каждой ошибки
дорисовывается фрагмент виселицы, отображающий оставшиеся попытки игрока.

**Запуск игры**

1.Скачайте данный репозиторий;
2.Для запуска программы у вас должен стоять gem bundler;
3.Запустите на вашем устройстве терминал или консоль;
4.Если у вас не установленн gem bundler, выполните команду в консоли

```gem install bundler```

5.Зайдите в директорию с файлом main.rb;
6.Выполните команду

```bundle```

которая установит необходимые гемы для работы программы;

7.Теперь вы можете запустить саму программу с помощью команды

```ruby main.rb```



**Добавление новых слов или изменение словарного запаса игры.**

Добавьте слово в верхнем регистре отдельной строкой в `data/words.txt`

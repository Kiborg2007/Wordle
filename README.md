# Wordle
Simple Wordle game on python

Этот проект посвящен написанию простой игры Wordle на русском языке.

Проект содержит несколько скриптов (в данном случае я не стал их объединять в один, для большей нагляности):
  - Первый скрипт `"GetSlovarOzhegova.ipynb"` собирает слова из онлайн словаря и записывает их в excel файл;
  - Второй скрипт `"GetFiveLetterWords.ipynb"` обрабатывает все слова, полученные ранее (удаляет лишние пробелы, цифры и лишние знаки из слов) и записывает в файл только слова, состоящие из 5 букв;
  - Файл `"Wordle.ipynb"` является игрой Wordle для угадывания слов на русском языке.

Все данные в файлах excel находятся в папке data.
При необходимости можно поменять длину угадываемых слов и количество попыток в коде.

Если необходимость в сборе слов для игры отсутствует (все слова из словаря записаны в файле Wordle/data/slovarozhegova.xlsx, а слова для игры в файле Wordle/data/df_5_letters.xlsx), то запускать файлы `GetSlovarOzhegova` и `GetFiveLetterWords` не нужно.

Для изменения длины угадываемых слов в игре нужно изменить код `GetFiveLetterWords.ipynb`\
Для изменения количества попыток - `Wordle.ipynb`

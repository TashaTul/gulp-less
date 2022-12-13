b# Простая сборка gulp

## Структура каталогов для размещения файлов стилей и скриптов:
>./src/styles/\*\*/\*.less </br>
>./src/scripts/\*\*/\*.js

## Инструкция:
1. Скачать файлы в любую директорию
2. Ввести в терминале команду: npm i (должен быть установлен node.js)
3. Выполнить команду gulp (запуск таска default) и можно писать код 

## Установленные npm пакеты
"del": "^6.1.1", Удаление каталогов и файлов
"gulp": "^4.0.2", Сборщик gulp
"gulp-babel": "^8.0.0", ПРеобразует js в старый стандарт
"gulp-clean-css": "^4.3.0", Минификация и оптимизация css  файлов
"gulp-concat": "^2.6.1", Объединение нескольких файлов в один 
"gulp-less": "^5.0.0", Компиляция less файлов
"gulp-rename": "^2.0.0", Переименовывает файлы
"gulp-uglify": "^3.0.2", Сжимает и оптимизирует js код 

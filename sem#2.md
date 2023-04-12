# Создание туториала по Git

## Как создать репозиторий

**Чтобы создать локальный репозиторий, напишите следующую команду в терминал:**
```fix
git init
```

## Как добавить файл на отслеживание

**Что-бы добавить файл на отслеживание, вам будет необхлдимо сделать следующее :**

- Прописать команду git add . 

## Как создать коммит

**Чтобы создать коммит, необходимо выполнить команду:**
```fix
git comit
```
## Как посмотреть состояние репозитория

**Что-бы посмотреть состояние репозитория, необходимо выполнить команду:**
- git status

# Руководство по MarkDawn


## Раздел первый - Заголовки




## Раздел второй - Списки




## Раздел третий - Исходный код


В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода.
 Также можно указать язык исходного
кода.
```html
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
 <span class="comment-count">0
комментариев</span>
 <span class="comment-countplaceholder">Комментарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logout">
 <a href="#" class="dropdown-toggle" datatoggle="dropdown">
<span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности


| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.

| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.

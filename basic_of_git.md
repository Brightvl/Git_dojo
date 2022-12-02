# All of GIT and Markdown

 
## Git 
*Это система контроля ваерсий, позволяющая эффективно управлять историей исходного кода. 
Любые изменения которые ты вносишь в проект могут быть сохранены с помощью Git. 
Ты можешь вернуться к любым ранее сохраненным версиям. 
Без Git пришлось бы создавать копии проекта, что было бы проблемой при увеличении объема кода в приложении*

### 1. Основныее команды git
* **git init** - Позволяет проинициализировать репозиторий в текущей папке
* **git status** - Показывает текущий статус
* **git add** - Отслеживает изменения файлов
* **git add index.html** — добавляет index.html
* **git add .** — добавляет все файлы
* **git commit** - Сохраняет изменения в коммит
* **git commit -m 'commit message'** — создает коммит с сообщением

### 2. Работа с ветками в репозитории
* **git branch** — показывает список веток
* **git branch branch-name** — создает новую ветку branch-name
* **git branch -D branch-name** — удаляет ветку branch-name
* **git checkout** - Переключается на другую ветку
* **git checkout branch-name** — переключается на последний коммит в ветке branch-name
* **git checkout -b branch-name** — создает и переключается на ветку branch-name
* **git merge** - Совмещает текущую ветку с выбранной
* **git merge branch-name** — совмещает текущую ветку с branch-name

### 3. Git настройки
* **git config** - Конфигурация и параметры git
* **git config --global user.name** — Показывает имя пользователя
* **git config --global user.name 'new user'** — Изменяет имя пользователя
* **git config --global user.email** — Показывает email пользователя
* **git config --global user.email 'test@mail.ru'** — Изменяет email пользователя

### 4. *GitHub* share
* **git push** - Заливает текущие локальные коммиты в удаленный репозиторий
* **git pull** - Забирает изменения с удаленного репозитория в локальный
* **git clone** - Клонирует проект с удаленного репозитория

## Markdown
*Это простой язык разметки, используемый для создания форматированного текста (например, HTML) с помощью текстового редактора. Он позволяет добавлять к тексту базовое форматирование, используя символы, известные и доступные на всех клавиатурах. Размер шрифта, цвет и другие расширенные параметры недоступны в Markdown.*

### Использование Markdown
Оформление текста

| Cbynfrcbc| Результат |
|------|--------------------|
| *Курсив* |	*Курсив* |
| Жирный   |	Жирный |
~~Зачеркнутый~~	Зачеркнутый
[Link](https://vivaldi.com/)	Ссылка
Столбец 1 | Столбец 2 | Столбец 3 |
:——- | :——: | ——: |
Слева | По центру | Справа |	
Столбец 1	Столбец 2	Столбец 3
Слева	По центру	Справа
# Заголовок 1
## Заголовок 2

### Заголовок 3

Заголовок 1
Заголовок 2
Заголовок 3
Изображение
[Vivaldi logo](https://vivaldi.com/wp-content/themes/vivaldicom-theme/img/press/icons/viv_icon.png)

Логотип Vivaldi
Неупорядоченный список
* Пункт 1
* Пункт 2
* Пункт 3

Упорядоченный список

1. Пункт 1
2. Пункт 2
3. Пункт 3

Неупорядоченный список
Пункт 1
Пункт 2
Пункт 3
Упорядоченный список

Пункт 1
Пункт 2
Пункт 3
`Встроенный код` с одинарными обратными кавычками	Inline code с одинарными обратными кавычками
Блок кода
(используйте три обратных кавычки без пробелов)
` ` `
<!DOCTYPE html>
<html>
<body><h1>Мой первый заголовок</h1>
<p>Мой первый абзац.</p></body>
</html>
` ` `

<!DOCTYPE html>

<html>

<body><h1>My First Heading</h1>

<p>My first paragraph.</p></body>

</html>
Цитата блока
> Lorem ipsum dolor sit amet, conctetur adipiscing elit. Integer eget porta sapien, eget pellentesque sapien. Duis in aliquam elit. Mauris lacinia magna quis nibh commodo, sed elementum quam elementum.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eget porta sapien, eget pellentesque sapien. Duis in aliquam elit. Mauris lacinia magna quis nibh commodo, sed elementum quam elementum.

Горизонтальная линия
— — —


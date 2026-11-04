# Изменения

Формат: [Keep a Changelog](https://keepachangelog.com/ru/1.1.0/), версии по [SemVer](https://semver.org/lang/ru/).
Последняя версия: https://github.com/SunsetSH/off-axis-releases/releases/latest

## [Unreleased]

## [1.4.0] — 2026-11-04

### Исправлено

- Телефон: в переключателе режимов виден весь текст, в «Быстром расчёте» шаги идут по порядку 1, 2, 3, шапка занимает три ряда вместо четырёх (единицы и язык перенесены в настройки), меню не выходят за край экрана, кнопки готовых установок стоят двумя рядами, закреплённая плашка вердикта стала ниже
- Компьютер: шапка умещается в один ряд от 1280 px, подписи сцены больше не закрывают панели сцены, меню и плашку вердикта, на ширине до 1279 px сцена получила больше места, а её панели не перекрывают картинку, в «Быстром расчёте» сцена не обрезается снизу, подписи в плитках показываются полностью, левая колонка выровнена по верху сцены

### English

- Phone: the mode switch shows whole labels, Quick calc goes through steps 1, 2, 3 in order, the header takes three rows instead of four (units and language moved to the settings), menus stay on the screen, install presets sit in two rows, the stuck verdict bar is shorter
- Desktop: the header keeps one row from 1280 px, scene labels no longer cover the scene toolbars, menus and the verdict bar, up to 1279 px the scene has more room and its toolbars leave the picture, the Quick calc scene is no longer cut at the bottom, tile labels are shown in full, the left column lines up with the top of the scene

## [1.3.0] — 2026-11-03

### Добавлено

- Три режима интерфейса: «Быстрый расчёт», «Новичок» и «Эксперт». Переключатель стоит первым в шапке, выбор запоминается; при первом заходе открывается окно «Что вы хотите узнать?». Ссылка `?mode=simple|advanced|expert` открывает нужный режим
- «Быстрый расчёт»: допустимое расстояние до экрана, диапазон диагоналей для выбранного расстояния, допустимая высота линзы, проекционное отношение. Расстояние можно двигать ползунком в допустимых пределах, а при смене экрана или проектора оно само подстраивается. Значение, введённое вручную за пределами диапазона, подсвечивается ошибкой. Выбор «на столе / полу» или «под потолком», упрощённая 3D-сцена (только вращение) на всю ширину
- «Новичок»: сдвиг объектива ползунками с отмеченной допустимой зоной, подписи простыми словами
- Окно «Характеристики» с заполненными данными проектора и окно «Найти по параметрам»: фильтр по яркости (любой стандарт), разрешению и наличию сдвига. Проекторы без значения остаются в списке: название оранжевое, рядом «?» с пояснением
- Цель Метрики для выбора режима

### Изменено

- Стартовая страница: индикатор загрузки и читаемый текст, пока приложение запускается
- Необязательные панели и настройки скрыты в «Быстром расчёте» и «Новичке», в «Эксперте» всё осталось как было. Тем, у кого уже есть сохранённые настройки, открывается «Эксперт»

### English

- Three interface modes: Quick calc, Beginner and Expert. The switch is the first control in the header and the choice is remembered; a first visit opens a "What do you want to find out?" dialog. The link `?mode=simple|advanced|expert` opens a given mode
- Quick calc: the allowed distance to the screen, the range of screen sizes for a chosen distance, the allowed lens height and the throw ratio. A slider moves the distance within the allowed range, and it adjusts itself when the screen or the projector changes. A value typed outside the range is flagged as an error. Table / floor or ceiling mount, and a simplified full-width 3D scene (rotate only)
- Beginner: lens shift with sliders that mark the allowed zone, plain wording
- A "Specifications" dialog with the projector's filled-in data and a "Find by specs" dialog: filter by brightness (any standard), resolution and lens shift. Projectors that lack a value stay in the list: the name is orange with a "?" that explains why
- A Metrika goal for the mode choice
- Changed: a start page with a loading indicator and readable text while the app starts; optional panels and settings are hidden in Quick calc and Beginner, Expert keeps everything as before. Visitors with saved settings open in Expert

## [1.2.0] — 2026-10-30

### Добавлено

- Статья «Как установить и настроить проектор» (`/ustanovka-proektora/`) со схемами, фильтром по типу проектора и ссылкой «Инструкция» в шапке и справке
- Статья: шкалы яркости и угла обзора с порогами калькулятора, графики расстояния и задержки ввода, проценты сдвига у разных брендов; оглавление следует за чтением, на телефоне таблицы показываются карточками; скриншоты калькулятора в тёмной теме с пометками
- Английская версия статьи: `/en/projector-setup-guide/`, ссылка «Setup guide» в английском интерфейсе

## [1.1.0] — 2026-10-23

### Добавлено

- Плашка «Нет нужного?» у выбора проектора: как попросить добавить модель через тему на 4PDA
- Яркость для трёх типов комнаты (тёмная, полутёмная, светлая) с цветной шкалой оценки по ориентирам SMPTE, DCI и Digital Projection
- Таблица «сколько света нужно кадру»: нужные люмены для каждой комнаты и самая широкая картинка, которую осветит выбранный проектор
- Политика конфиденциальности `/privacy/` и `/en/privacy/`, ссылка в справке
- Страница 404 для несуществующих адресов
- Заметки о данных проектора простыми словами; полный текст исследования открывается отдельно
- Английские подписи вариантов проекторов

### Изменено

- На компьютере панели слева и сцена доходят до плашки вердикта, правая колонка с карточкой поддержки или рекламой раскладывается отдельно
- Сцены с прежним режимом «С засветкой» открываются как полутёмная комната; в отчёте у яркости указаны комната и оценка
- Ответ FAQ о каталоге: сколько моделей, сколько сверено с официальной спецификацией и когда обновлён каталог
- Сайт быстрее стартует: подбор проектора считается только при открытой панели, 3D-сцена загружается заранее и не сдвигает страницу на телефоне
- На телефонах и планшетах крупнее кнопки и подписи
- Английская версия: «spec» вместо «passport»
- Сервер: HTTP/2, предварительно сжатые файлы, заголовки безопасности, один адрес на страницу (www и `index.html` ведут на основной)

## [1.0.0] — 2026-10-21

Первый публичный выпуск: сайт https://offaxis.ru (и английская версия https://offaxis.ru/en/), приложение для Windows и Android.

### Возможности

- Расчёт установки проектора без трапеции: расстояние до экрана, высота, вертикальный и горизонтальный сдвиг объектива с учётом их взаимозависимости (круг изображения объектива)
- 3D-сцена комнаты с зоной допустимых положений, Lens View, диаграмма допустимых сдвигов, вид сбоку с размерами C, C1, C2, H
- Каталог проекторов (Hisense / Vidda, XGIMI, Dangbei, JMGO, Epson) с источниками характеристик, свои проекторы и варианты
- Яркость, угол обзора, ограничения установки, подбор проектора под комнату, сравнение двух моделей
- Отчёт для монтажа в PDF и PNG с чертежами и размерами
- Шаринг сцены ссылкой и JSON, undo/redo, RU/EN, см/м/дюймы, светлая и тёмная тема, офлайн-режим (PWA)
- Айдентика OffAxis, справка в модальном окне, языковые страницы для поисковиков (ADR-0007)

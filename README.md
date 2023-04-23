# words

# Слова и сокращения в CSS-классах

## Крупные блоки/элементы

### `page`

Cтраница (обычно, корневой элемент). <br>
Сокращение: нет <br>
Пример: `page`

### `container`

Контейнер, обёртка. <br>
Сокращение: нет <br>
Пример: `container`

### `grid`

Сетка (для раскладки блоков по модульной сетке). <br>
Сокращение: нет <br>
Пример: <br>
`grid` (элемент, внутри которого будет модульная сетка)

### `row`

Обёртка для ячеек модульной сетки. <br>
Сокращение: нет <br>
Пример: <br>
`grid__row` (одна или несколько «строк» модульной сетки)

### `column`

Ячейка модульной сетки. <br>
Сокращение: `col` <br>
Пример: <br>
`grid__col-md-6` (ячейка, занимающая 6 колонок на MD-ширине)

### `wrapper`

Обёртка чего-либо. <br>
Сокращение: `wrap` <br>
Пример: <br>
`contacts__wrapper` (обёртка вокруг контента блока контактов)

### `inner`

Внутренняя обёртка чего-либо (чаще всего — для ограничения ширины и выравнивания по центру). <br>
Сокращение: нет <br>
Пример: <br>
`promo__inner` (внутренняя обертка промо-блока)

### `navigation`

Навигация. <br>
Сокращение: `nav` <br>
Пример: <br>
`main-nav` (главная навигация)

### `promo`

Внутренняя реклама, какое-то введение. <br>
Сокращение: нет <br>
Пример: `promo` <br>

### `features`

Особенности, преимущества. <br>
Сокращение: нет <br>
Пример: <br>
`features` (блок с описанием свойств и преимуществ)

### `cart`

Корзина в магазине. <br>
Сокращение: нет <br>
Пример: <br>
`cart` (блок корзины на странице корзины)

### `sidebar`, `aside`

Дополнительная информация (часто — узкая колонка на блоговой странице). <br>
Сокращение: нет <br>
Пример: `sidebar`, `aside` <br>

## Мелкие блоки/элементы

### `item`, `element`, `part`

Часть, элемент, отдельная «единица». Универсальное слово, если не удаётся придумать что-то специфическое. <br>
Сокращение: `element` → `el` <br>
Пример: <br>
`main-nav__list-item` (пункт в списке в главной навигации, вероятно, `li`), <br>
`filter__part` (типовая часть фильтра)

### `widget`

Виджет. <br>
Сокращение: нет <br>
Пример: <br>
`aside__widget` (виджет в блоке дополнительной информации)

### `logo`

Логотип. <br>
Сокращение: нет <br>
Пример: <br>
`logo` (вы не поверите...)
`.partner__logo` (логотип партнёра)

### `field`

Поле формы. <br>
Сокращение: нет <br>
Пример: <br>
`field-text` (универсальный блок для набора форм), <br>
`field-radio` (универсальный блок для набора форм), <br>
`field-checkbox` (универсальный блок для набора форм), <br>
`field-select` (универсальный блок для набора форм), <br>
`field-file` (универсальный блок для набора форм)

### `pagination`

Навигация по нескольким страницам (1 2 3 ...). <br>
Сокращение: нет <br>
Пример: `pagination` <br>

### `breadcrumbs`

«Хлебные крошки» (Главная > Каталог > Товар). <br>
Сокращение: нет <br>
Пример: `breadcrumbs` <br>

### `modal`

Модальное окно. <br>
Сокращение: нет <br>
Пример: `modal` <br>

### `popup`

Всплывающий блок (обычно, по клику на чем-либо). <br>
Сокращение: нет <br>
Пример: `popup` <br>

### `tooltip`

Всплывающая подсказка, небольшой блок (обычно, по наведению на что-либо). <br>
Сокращение: нет <br>
Пример: `tooltip` <br>

### `copyright`

Копирайт. <br>
Сокращение: нет <br>
Пример: `copyright` <br>

### `button`

Кнопка/кнопки. Сама по себе кнопка — всегда [БЭМ-блок](http://nicothin.github.io/idiomatic-pre-CSS/#bem-block). Может иметь миксование с БЭМ-элементами. Слово может использоваться в классах-обёртках (см. пример). <br>
Сокращение: `btn` <br>
Пример: <br>
`btn` (отдельная кнопка), <br>
`.promo__btns` (обёртка для кнопок в промо-блоке)

### `title`, `heading`, `caption`

Заголовок (часто применяется на заголовочных тегах, но не обязательно на них). <br>
Сокращение: нет <br>
Пример: <br>
`promo__title` (заголовок промо-блока)

### `subtitle`

Подзаголовок. <br>
Сокращение: нет <br>
Пример: <br>
`post__subtitle` (подзаголовок записи в блоге)

### `name`

Название. <br>
Сокращение: нет <br>
Пример: `product__name` <br>

### `slogan`

Слоган. <br>
Сокращение: нет <br>
Пример: <br>
`logo__slogan` (слоган в блоке логотипа)

### `user`

Пользователь. <br>
Сокращение: нет <br>
Пример: <br>
`user` (блок авторизованного/неавторизованного посетителя, к примеру, в шапке)

### `label`, `tag`

Метка, тег. <br>
Сокращение: нет <br>
Пример: <br>
`label` (лейбл), <br>
`post__tags-list` (список меток записи в блоге)

### `category`

Рубрика(и). <br>
Сокращение: `cat` <br>
Пример: <br>
`post__cats` (рубрики записи в блоге)

### `dropdown`

Выпадающий элемент (направление выпадения не имеет значения). <br>
Сокращение: `drop` <br>
Пример: <br>
`filter__drop` (выпадающий по клику блок в фильтре)

### `search`

Поиск. <br>
Сокращение: нет <br>
Пример: <br>
`search-form` (блок быстрого поиска, возможно, в «шапке»)

### `socials`

Социальные сети (иконки, обычно). <br>
Сокращение: нет <br>
Пример: <br>
`socials__list` (список с соц. ссылками)

### `carousel`, `slider`

Карусель, слайдер (несколько сменяющих друг друга слайдов). <br>
Сокращение: нет <br>
Пример: <br>
`promo__slider` (карусель в промо-блоке)

### `header`

Верхняя часть, «шапка». <br>
Сокращение: нет <br>
Пример: <br>
`page-header` («шапка» страницы), <br>
`post__header` («шапка» записи в блоге)

### `footer`

Нижняя часть, «подвал». <br>
Сокращение: нет <br>
Пример: <br>
`page-footer` («подвал» страницы), <br>
`post__footer` («подвал» записи в блоге)

### `additional`

Добавление чего-либо. <br>
Сокращение: `add` <br>
Пример: <br>
`location__btn-add` (кнопка добавления в блоке какого-то места)

### `info`, `meta`

Информация о какой-либо сущности. <br>
Сокращение: нет <br>
Пример: <br>
`post__info` (информация о записи в блоге)

### `body`

Главная контентная часть чего-либо. <br>
Сокращение: нет <br>
Пример: <br>
`post__body` (основной текстовой фрагмент записи в блоге)

### `content`

Содержимое чего-либо. <br>
Сокращение: нет <br>
Пример: <br>
`post__content` (основной текстовой фрагмент записи в блоге)

### `section`

Крупный раздел чего-либо. <br>
Сокращение: нет <br>
Пример: <br>
`promo__section` (большой раздел промо-блока)

### `icon`

Иконка. <br>
Сокращение: нет <br>
Пример: <br>
`icon--twitter` (иконка соц. сети (модификатор))

### `link`

Cсылка. <br>
Сокращение: нет <br>
Пример: <br>
`product__more-link` (ссылка «Далее» в блоке продукта)

### `list`

Cписок. <br>
Сокращение: нет <br>
Пример: <br>
`features__list` (список преимуществ)

### `description`

Описание какой-либо сущности <br>
Сокращение: `descr` <br>
Пример: <br>
`product__descr` (описание продукта)

### `image`

Изображение. <br>
Сокращение: `img` <br>
Пример: <br>
`promo__img` (изображение в промо-блоке)

### `picture`

Изображение. <br>
Сокращение: `pict`, `pic` <br>
Пример: <br>
`promo__pict` (картинка в промо-блоке)

### `toggle`

Переключение, тумблер. Часто — «гамбургер», переключающий показ/сокрытие главного меню (на медиа-условии, при котором меню скрывается под «гамбургером»). <br>
Сокращение: нет <br>
Пример: <br>
`main-nav__toggle` (переключатель видимости гл. меню)

### `tab`

Вкладка. <br>
Сокращение: нет <br>
Пример: <br>
`tabs` (вкладки), <br>
`promo__tab` (вкладка в промо-блоке)

### `thumbnail`

Миниатюра (обычно, в какой-либо галерее). <br>
Сокращение: `thumb` <br>
Пример: <br>
`photo__thumb` (миниатюра в фотогалерее)

### `avatar`

Аватарка, маленькая картинка пользователя. <br>
Сокращение: нет <br>
Пример: <br>
`user__avatar` (аватарка пользователя в блоке пользователя в шапке)

### `text`

Текстовой фрагмент (обычно, выводимый из CMS). <br>
Сокращение: нет <br>
Пример: <br>
`about__text` (текст «о нас», вероятно обертка вокруг нескольких параграфов)

### `author`

Автор. <br>
Сокращение: нет <br>
Пример: <br>
`post__author` (имя/ник автора записи в блоге)

### `more`

«далее», «подробнее». <br>
Сокращение: нет <br>
Пример: <br>
`product__more-link` (кнопка или ссылка в промо-блоке, предлагающая ознакомиться подробнее)

## Модификации, состояния

### `active`, `current`

Активный элемент (пункт навигации, активный таб). <br>
Сокращение: нет <br>
Пример: <br>
`main-nav__item--active` (модификатор на пункте гл. навигации, соответствущем странице, на которой пребывает посетитель)

### `hidden`

Скрытое. <br>
Сокращение: нет <br>
Пример: <br>
`product--hidden` (модификатор, скрывающий блок продукта)

### `shown`

Показанное. <br>
Сокращение: нет <br>
Пример: <br>
`product--shown` (модификатор, показывающий продукт)

### `error`

Состояние ошибки. <br>
Сокращение: нет <br>
Пример: <br>
`field-text--error` (модификатор, помечающий блок текстового поля как ошибочное)

### `success`

Состояние успеха. <br>
Сокращение: нет <br>
Пример: <br>
`field-text--success`

### `warning`

Предупреждение. <br>
Сокращение: нет <br>
Пример: <br>
`btn--warning` (модификатор, меняющий вид кнопки)

### `pending`

Ожидание чего-либо (к примеру, ответа севера после асинхронной отправки формы). <br>
Сокращение: нет <br>
Пример: <br>
`btn--pending` (модификатор, меняющий вид кнопки)

## Размеры

### `extra small`

Очень маленький. <br>
Сокращение: `xs` <br>
Пример: <br>
`grid__col-xs-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xs` (имя переменной с соотв. шириной вьюпорта в значении)

### `small`

Маленький. <br>
Сокращение: `sm` <br>
Пример: <br>
`grid__col-sm-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-sm` (имя переменной с соотв. шириной вьюпорта в значении)

### `medium`

Средний. <br>
Сокращение: `md` <br>
Пример: <br>
`grid__col-md-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-md` (имя переменной с соотв. шириной вьюпорта в значении)

### `large`

Большой. <br>
Сокращение: `lg` <br>
Пример: <br>
`grid__col-lg-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-lg` (имя переменной с соотв. шириной вьюпорта в значении)

### `extra large`

Очень большой. <br>
Сокращение: `xl` <br>
Пример: <br>
`grid__col-xl-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xl` (имя переменной с соотв. шириной вьюпорта в значении)

### `extra extra large`

Сафсэм балшой. <br>
Сокращение: `xxl` <br>
Пример: <br>
`grid__col-xxl-6` (ячейка, занимающая 6 колонок модульной сетки на соотв. ширине), <br>
`screen-xxl` (имя переменной с соотв. шириной вьюпорта в значении)

### `narrow`

Узкий. <br>
Сокращение: нет <br>
Пример: <br>
`btn--narrow` (модификатор, делающий кнопку узкой)

### `wide`

Широкий. <br>
Сокращение: нет <br>
Пример: <br>
`btn--wide` (модификатор, делающий кнопку широкой)

### `phone`, `mobile`

Мобильные устройства (телефоны до 5 дюймов). <br>
Сокращение: нет <br>
Пример: <br>
`promo--phone` (модификация промо-блока для соотв. устройств)

### `tablet`

Планшеты (ориентировочно до 12 дюймов). <br>
Сокращение: нет <br>
Пример: <br>
`promo--tablet` (модификация промо-блока для соотв. устройств)

### `notebook`, `laptop`

Ноутбуки. <br>
Сокращение: нет <br>
Пример: <br>
`promo--laptop` (модификация промо-блока для соотв. устройств)

### `desktop`

Настольные компьютеры. <br>
Сокращение: нет <br>
Пример: <br>
`promo--desktop` (модификация промо-блока для соотв. устройств)

## Прочее

### `previous`

Предыдущее (часто - ссылка/кнопка). <br>
Сокращение: `prev` <br>
Пример: <br>
`slider__prev` (кнопка/стрелка на слайдере)

### `next`

Следущее (часто - ссылка/кнопка). <br>
Сокращение: нет <br>
Пример: <br>
`slider__next` (кнопка/стрелка на слайдере)

### `advertisement`

Рекламный фрагмент (осторожно, может вырезаться баннерорезками). <br>
Сокращение: `adv` <br>
Пример: <br>
`aside__adv` (рекламный блок в сайдбаре)

### `background`

Фон (чаще — какое-то изменение фонового цвета блока). <br>
Сокращение: `bg` <br>
Пример: <br>
`top-rated--bg-gray` (модификация фонового цвета блока самых рейтинговых товаров/услуг)

### `number`

Число. <br>
Сокращение: `num` <br>
Пример: <br>
`field-text--num` (модификатор для текстового поля, позволяющий иначе оформить числовые поля)

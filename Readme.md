# Проект главного сайта ГК "Форум"


*Особенности:*

- Использование webgl-библиотеки [THREE.JS](https://threejs.org/) для анимации логотипа
- Использование localstorage для хранения объекта координат секций
- Плагин [Masonry](https://masonry.desandro.com/) в галерее, и расширение функциональности lazyLoading
- Продвинутая pug-шаблонизация странциц
- Сетка bootstrap4 для адаптивности страниц
- Использование отзывчивых шрифтов размера calc(1vw + 1vh) 
- Прoдвинутое использование API Яндекс карт - подгрузка своей карты страницы 
- Использование самостоятельно сделанного jquery-плагина стрелки прокрутки вверх
- Оптимизаци прокрутки через throttle
- Технология <area> для интерактивной карты объектов
- Graceful degradation для адаптации сайта к IE + полифиллы
- JSDoc документация кода
- PHPMailer для отправки писем
- gulp сборка проекта
- Линтинг

!!! Файл logo.js в стадии работы, код не струтурирован. С логотипом выявлены сложности рендеринга на некоторых компьютерах.

**Важно**

Внесены изменения в модуле bootstrap
./node_modules/bootstrap/scss/_variables.scss -  $grid-breakpoints добавить xxl: 1800px, $container-max-widths: добавить xxl: 1740px
./node_modules/bootstrap/scss/_reboot.scss - body{font-size: calc(1vw + 1vh)}



**Как установить и запустить проект **

1. git clone https://github.com/davegahn/FORUM.git FORUM
2. cd FORUM
3. yarn install
4. gulp

___
Инструменты:

\#sublime-text3 \#cmder \#chrome \#gulp \#stackoverflow \#photoshop

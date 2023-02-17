# Проект: Путешествие по России
![russian-travel](./images/lead-polka.jpg)
***
#### - Введение:
***
В последние годы значительно возрос интерес к путешествиям по России. Мировые события только способствуют этому. Путешествуя по странам мира, мы даже не подозревали, какие красоты таит НАША огромная страна.
Проект "Путешествия по России" лишь приоткрывает завесу тайны и знакомит читателя с некоторыми знаковыми местами. И этим способствует пробуждению интереса к изучению и открытию все новых и новых мест.
***
#### - Применение:
***
1. Одностраничный сайт создан при помощи HTML и CSS. Макет проекта был взят из Figma.
2. Проект выполнен адаптивной версткой с использованием flex- и grid-контейнеров и элементов.
3. Проект адаптирован под дисплеи разных устройств при помощи медиа-запросов. От экранов смартфонов в 320px до стандартных мониторов пк и больше.
4. Все ссылки в проекте кликабельны, им задано состояние при наведении указателя мыши :hover. Ссылки блока place переводят на страницы с описанием места.
5.  Состояние :hover в блоке cover реализовано при помощи псевдоэлемента before.

```css

.cover__link:before {
  width: 100%;
  height: 100%;
  content: '';
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  background-color: #000;
  opacity: 0.25;
  z-index: -1;
  transition: opacity 0.5s ease-in-out;
}

.cover__link:hover:before {
  opacity: 0.8;
}
```
6. Выполнена оптимизация шрифтов под устройства с различными разрешениями.
7. В коде проекта создана Nested файловая структура.
***
####  Познакомиться с проектом можно на GitHab https://liubov-m.github.io/russian-travel/
***
Приятного просмотра :)

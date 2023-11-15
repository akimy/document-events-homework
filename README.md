# Домашнее задание по взаимодействию со страницей

## Первое задание:
Используйте кнопки в header, чтобы переместить пользователя к нужному контенту внутри страницы.
Header должен прилипать к верху страницы при скролле.

![header-buttons](assets/header.png?raw=true "header-buttons")

## Второе задание:
Используйте кнопки под заголовком "Work Experience" чтобы менять основной текстовый контент внутри блока.
По умолчанию должна быть выбрана первая кнопка "Apple". Может быть выбрана только 1 кнопка. 

- Новый текст придумайте самостоятельно (на усмотрение), или положите "рыбу" главное чтобы текст отличался  
- Кнопки меняют визуальное состояние, активные – более затемнённые
- Проследите чтобы не было багов при повторных нажатиях активных кнопок

![block-scrolling](assets/block-scrolling.png?raw=true "block-scrolling")

## Третье задание:
В блоке "Skills" требуется оживить форму для добавления новых навыков.

Форма состоит из двух полей: "Skill name" и "Skill proficiency", в которые можно ввести данные по навыку и его уровень владения от 1 до 100.
Обработчик на крестике должен быть на общем родительском блоке.

Какое поведение должно быть:
- При нажатии на кнопку "Add" - визуально добавится новый навык (в столбец с наименьшим кол-вом навыков)
- При наведении на карточку навыка и нажатия на кнопку крестика – удалить навык из списка
- Очищать форму при успешной обработке нажатия кнопки Add
- Использовать всплытие событий. Чтобы создать единый обработчик всех событий
- Не принимать форму если во второе поле введено нечисловое значение или значение меньше 1 или больше 100
- Оповестить пользователя о ошибке (через alert() ) если второе поле заполнено некорректно

![skills-editing](assets/skills-editing.png?raw=true "skills-editing")

## Четвертое задание:
Изменять текущие значения имеющихся навыков путем клика мыши по полосе навыка  
- Проследить, что для новых навыков данная функциональность так же работает.
- Использовать единый обработчик на блоке навыков (всплытие событий)

## Дополнительное задание
![header-buttons](assets/header2.png?raw=true "header-buttons")
- При скролле контента и попадании заголовка блока во viewport пользователя, активной становится соответствующая контенту кнопка навигации.
  Если во viewport попадает больше 1 блока, нужно подсвечивать название первого блока.

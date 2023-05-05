# marks
Import marks from Google Classrom to NZ.UA

Просте перенесення оцінок з журналу Google Classrom в журнал Нові знання nz.ua

За основу взято сніпети з сайту https://teacher-typ.blogspot.com/2023/03/google-nzua.html - Імпорт оцінок з Google-класу до електронного журналу NZ.UA 
Відео про роботу https://youtu.be/_ys04PYvmVc

В представлених сніпетах реалізовано наступний функціонал:
 - додавання кнопок над кожним стовпцем в журналі Classroom для копіювання оцінок;
 - додавання кнопок над кожним стовпцем в журналі NZ.UA для вставки оцінок.
 
ВАРІАНТИ ВИКОРИСТАННЯ:

1 варіант - запуск через консоль (зручний для ознайомлення з функціоналом):

    - скопіювати код файлу snippet-classroom.js
    - відкрити сторінку Оцінки в Classroom
    - відкрити консоль браузера F12
    - вставити за запустити код 
    * над стовпчиками в журналі Classroom через 10 секунд з'являться кнопки
    - написнути на кнопку для копіювання оцінок в буфер обміну
    * в консолі відобразиться список скопійованих оцінок

    - скопіювати код файлу snippet-nz.js
    - відкрити сторінку журналу НЗ nz.ua
    - відкрити консоль браузера F12
    - вставити за запустити код 
    * над стовпчиками в журналі НЗ з'являться кнопки
    - написнути на кнопку для вставки оцінок з буферу обміну
    * оцінки додадуться до відповідних прізвищ, в консолі відобразиться номер натиснутого стовпця

При виборі іншого класу ці дії потрібно буде повторити і це створює незручності.  

2 варіант - додавання сніпетів в браузер:
    - відкрити консоль браузера F12
    - перейти на вкладку Sources
    - вибрати Snippet
    - додати новий сніпет та назвати його Classroom
    - скопіювати код з файлу snippet-classroom.js в створений сніпет
    - зберегти сніпет Ctrl + S
    - додати новий сніпет та назвати його NZ
    - скопіювати код з файлу snippet-nz.js в створений сніпет
    - зберегти сніпет Ctrl + S

    після цього запускати відповідний сніпет на потрібному сайті

Недоліком даного способу є необхідність постійного відкриття консолі для роботи.

3 варіант - використання розширення для автоматичного запуску JavaScript коду на потрібному сайті

    - встановити розширення Custom JavaScript for Websites 2 https://chrome.google.com/webstore/detail/custom-javascript-for-web/ddbjnfjiigjmcpcpkmhogomapikjbjdk 
    - зпустити розширення C/S та вставити код з файлів snippet-classroom.js та snippet-nz.js у відповідні вікна
    - при переході на сторінку розширення C/S буде запускати код і кнопку будуть з'являтися автоматично

МОЖЛИВІ ПРОБЛЕМИ
    - на сторінці з журналом Classroom можуть з першого разу не з'являтись кнопки через велику кількість учнів та оцінок. НЕОБХІДНО перезавантажити сторінку
    - на сторінці з журналом Classroom можуть зникати кнопки при прокурутці журналу вправо через підвантаження оцінок. НЕОБХІДНО спочатку дочекатись завантаження всіх оцінок або збільшити параметр pauseTime
 
 Відео по налаштуванню буде додане пізніше
 

 

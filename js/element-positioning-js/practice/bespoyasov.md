<aside>

☝️ Всегда старайтесь стилизовать элементы с помощью CSS-классов. Если анимацию можно сделать с помощью смены классов, описывайте стили в них.

</aside>

Менять стили элементов напрямую может быть полезно, когда вы пишете анимацию, напрямую зависящую от действий пользователя, а их нельзя предсказать.

В примере ниже мы используем [Прокрутчик](https://bespoyasov.ru/scroller/), чтобы таскать блоки мышью и крутить их с инерцией:

<iframe title="Галерея с прокрутчиком (scroller) — Позиционирование элементов с помощью JS — Дока" src="../demos/scroller/" height="220"></iframe>

Мы позиционируем элементы с помощью скриптов, потому что не знаем, когда и как пользователь захочет прокрутить ленту с блоками.

Старайтесь анимировать свойства [`transform`](/css/transform) и [`opacity`](/css/opacity), чтобы сделать сайт или приложение более отзывчивыми. [Как браузер рисует страницы](/js/how-the-browser-creates-pages)

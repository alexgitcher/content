🛠 Для выравнивания положения текста часто советуют использовать атрибут `align`, но он исключён из современной спецификации, а привычные CSS-правила, например, с `text-align: center` с `<legend>` работать не будут, т. к. у него блочный контекст, но уникальная строчно-блочная контекстная модель содержимого, которая и создаёт неповторимую обводку от `<fieldset>`. Поэтому для выравнивания `<legend>` относительно ширины `<fieldset>` нужно использовать… внезапно [`margin`](/css/margin)!

<iframe title="Выравнивание легенды по разным краям" src="../demos/legend-align/" height="150"></iframe>

За счёт особой формы обтекания рамкой текста, это можно использовать для характерной стилизации блока и заголовка:

<iframe title="Стилизованная легенда" src="../demos/legend-style/" height="350"></iframe>


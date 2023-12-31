### Задание №2. Архитектура

<u>***Уровни веб-приложения***</u>

- 1. Уровень представления (PL)

Уровень представления
PL отображает пользовательский интерфейс и упрощает взаимодействие с пользователем. Уровень представления имеет компоненты пользовательского интерфейса, которые визуализируют и показывают данные для пользователей. Также существуют компоненты пользовательского процесса, которые задают взаимодействие с пользователем. PL предоставляет всю необходимую информацию клиентской стороне. Основная цель уровня представления - получить входные данные, обработать запросы пользователей, отправить их в службу данных и показать результаты

- 2. Уровень обслуживания данных (DSL)

DSL передает данные, обработанные уровнем бизнес-логики, на уровень представления. Этот уровень гарантирует безопасность данных, изолируя бизнес-логику со стороны клиента.


- 3. Уровень бизнес-логики (BLL)

BLL несет ответственность за надлежащий обмен данными. Этот уровень определяет логику бизнес-операций и правил. Вход на сайт - это пример уровня бизнес-логики.

- 4. Уровень доступа к данным (DAL)

Уровень доступа к данным
DAL предлагает упрощенный доступ к данным, хранящимся в постоянных хранилищах, таких как двоичные файлы и файлы XML. Уровень доступа к данным также управляет операциями CRUD - создание, чтение, обновление, удаление


---

- Монолитная архитектура:

это традиционная модель программного обеспечения, которая представляет собой единый модуль, работающий автономно и независимо от других приложений. Монолитом часто называют нечто большое и неповоротливое, и эти два слова хорошо описывают монолитную архитектуру для проектирования ПО. Монолитная архитектура — это отдельная большая вычислительная сеть с единой базой кода, в которой объединены все бизнес-задачи. Чтобы внести изменения в такое приложение, необходимо обновить весь стек через базу кода, а также создать и развернуть обновленную версию интерфейса, находящегося на стороне службы. Это ограничивает работу с обновлениями и требует много времени

Монолиты удобно использовать на начальных этапах проектов, чтобы облегчить развертывание и не тратить слишком много умственных усилий при управлении кодом. Это позволяет сразу выпускать все, что есть в монолитном приложении

![Изображение](https://media.proglib.io/posts/2019/09/18/379a434eb170516211ee253dfc607075.png)

- Микросервисная архитектура: 

относится к распределенным системам. Согласно определению, распределенная система — это набор компьютерных программ, которые используют вычислительные ресурсы нескольких отдельных вычислительных узлов для достижения общей цели. Распределенные системы помогают повысить надежность и производительность и упрощают масштабирование системы.

Узлы в распределенной системе обеспечивают резервирование, поскольку при отказе любого узла его заменят другими. Каждый узел можно масштабировать по горизонтали и вертикали, чтобы повысить производительность. В случае большой нагрузки на систему можно добавить дополнительные узлы, которые помогут с ней справиться

**- Плюсы и минусы (различия):**

| Монолитная | Микросервисная |
| ----------- | ----------- |
|Можно быстрее разработать MVP   | Расширенная функциональность  |
| Проще развернуть   | Повышенная функциональность   |
| Удобнее в поддержке  |  Можно обновлять по частям |
|  Ошибка может замедлить или разрушить все приложение | Проблемы одного модуля меньше сказываются на работе всего приложения   |
| Труднее масштабировать   | Легче перестраивать и масштабировать  |
| Труднее изменить или переформатировать   | Требовательность к ресурсам   |
|Можно быстрее разработать MVP   | Сложнее в использовании  |
|    | Дороже накладные расходы   |
|    | Разработчики должны иметь одинаковый опыт и уметь работать с различными языками программирования   |


---

- Почему не все приложения построены на микросервисной архитектуре?

Сложная распределенная система. Наличие множества отдельных модулей влечет за собой дополнительную сложность в организационном и архитектурном плане. То есть усложняется контроль над различными командами разработчиков, а также само развертывание программного продукта.

**Особенности тестирования монолитных и микросервисных веб-приложений:**

Функционал, который реализуется на «стороне» клиента; Проверка правильности отображения графических элементов web-приложения; Интерактивность веб-приложения и др. Проверка обязательности заполнения полей с учетом их маркировки; Проверка отправки форм на соответствие ожидаемому результату; Проверка использования чит-листов для тестирования форм;

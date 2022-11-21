# UML

**Унифицированный язык моделирования** (UML) в настоящий момент является стандартом де-факто при описании (документирования) результатов проектирования и разработки объектно-ориентированных систем. Начало разработки UML было положено в 1994 г. Гради Бучем и Джеймсом Рамбо, работавшим в компании Rational Software. Осенью 1995 г. к ним присоединился Ивар Якобсон и в октябре того же года была выпущена предварительная версия 0.8 унифицированного метода. С этого времени было выпущено несколько версий спецификации UML.

## Нотация UML

Нотация представляет собой графическую интерпретацию семантики для ее визуального представления.

В UML определено три **типа сущностей**:

- структурная – абстракция, являющаяся отражением концептуального или физического объекта;
- группирующая – элемент, используемый для некоторого смыслового объединения элементов диаграммы;
- поясняющая (аннотационная) – комментарий к элементу диаграммы.

**Диаграмма** представляет собой группировку элементов нотации для отображения некоторого аспекта разрабатываемой информационной системы. Диаграммы представляют собой, как правило, связный граф, в котором сущности являются вершинами, а отношения – дугами. В следующей таблице дана краткая характеристика диаграмм UML:

Диаграмма | Назначение
----------|-----------
[Вариантов использования](../articles/5_1_1_10_uml_use_case.md)<br/>(use case) | Отображает функции системы, взаимодействие между актерами и функциями
[Классов](../articles/uml_class.md)<br/>(class) | Отображает набор классов, интерфейсов и отношений между ними
Пакетов<br/>(package) | Отображает набор пакетов и отношений между ними
Автоматов<br/>(state machine) | Отображает состояния сущности и переходы между ними в процессе ее жизненного цикла
[Деятельности](../articles/uml_activity.md)<br/>(activity) | Отображает бизнес-процессы в системе (описание алгоритмов поведения)
[Последовательности](../articles/uml_sequence.md)<br/>(sequence) | Отображает последовательность передачи сообщений между объектами и актерами
[Коммуникации](../articles/uml_communication.md)<br/>(communication) | Аналогична диаграмме последовательности, но основной акцент делается на структуру взаимодействия между объектами
Компонентов<br/>(component) | Отображает компоненты системы (программы, библиотеки, таблицы и т.д.) и связи между ними
Развертывания<br/>(deployment) | Отображает размещение компонентов по узлам сети, а также ее конфигурацию

<!-- диаграммы состояний,  -->


Часть диаграмм после их построения требует развития и уточнения в рамках разработки следующей модели (технологического процесса). Так, например, диаграммы вариантов использования должны быть уточнены при разработке модели анализа. В моделях вариантов использования и анализа разрабатывается и уточняется диаграмма классов анализа, а в модели проектирования – итоговая детализированная диаграмма классов. Как правило, диаграмма классов анализа и диаграмма классов существуют независимо.

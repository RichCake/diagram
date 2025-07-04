# Вопросы

1.     **Понятия требований, классификация.**

**Требования** — это зафиксированные потребности или условия, которым должно соответствовать разрабатываемое программное обеспечение для решения задачи или достижения цели. 

**Классификация** требований: по характеру и по уровням. По характеру требования бывают функциональные (что система должна делать) и нефункциональные (как система должна это делать – производительность, безопасность, удобство использования и т.д.), а по уровню бизнес-требования, пользовательские требования и функциональные требования.

2.     **Уровни требований.**

- **Бизнес-требования:** цели и задачи бизнеса, которые должна решить система.
- **Пользовательские требования:** что пользователи смогут делать с системой.
- **Функциональные требования:** конкретные функции, которые должна выполнять система.

По уровням требования образует дерево где на каждое бизнес-требование появляется несколько пользовательских требования и тд. 

3.     **==Методологии и стандарты, регламентирующие работу с требованиями.==**

**Методологии:** Agile (Scrum, Kanban) — итеративный подход с гибким изменением требований; Waterfall — последовательный подход с фиксацией требований на начальном этапе.

**Стандарты:** ISO/IEC/IEEE 29148 (стандарт для процессов жизненного цикла требований). Из отечественных стандартов требования к проектируемой системе в форме ТЗ регламентируют ГОСТ 34.602-89 «Техническое задание на создание автоматизированной системы» и «Техническое задание, требования к содержанию и оформлению».

4.     **Современные принципы и методы разработки программных приложений.**

**Принципы:** DRY (Don't Repeat Yourself), KISS (Keep It Simple, Stupid), YAGNI (You Aren't Gonna Need It), SOLID (принципы ООП). 

**Методы:** Agile (Scrum, Kanban), DevOps, микросервисная архитектура, Test-Driven Development (TDD), Behavior-Driven Development (BDD), Continuous Integration/Continuous Delivery (CI/CD).

5.     **Методы организации работы в команде разработчиков.**

- **Agile-подходы:** Scrum (короткие итерации - спринты, ежедневные стендапы, роли: Product Owner, Scrum Master, Development Team), Kanban (визуализация рабочего процесса, ограничение WIP).
- **DevOps:** культура сотрудничества между разработкой и эксплуатацией.
- **Парное программирование:** два разработчика работают над одним кодом на одном компьютере.
- **Code Review:** взаимная проверка кода.

6.     **Системы контроля версий.**

**Системы контроля версий (VCS)** — это программное обеспечение для отслеживания изменений в файлах и управления различными версиями проекта. Позволяют нескольким разработчикам совместно работать над одним проектом, откатывать изменения, объединять ветки.

7.     **Основные подходы к интегрированию программных модулей.**

- **Сверху вниз:** сначала интегрируются модули верхнего уровня, затем постепенно добавляются модули нижних уровней.
- **Снизу вверх:** сначала интегрируются наименьшие, независимые модули, затем они объединяются в более крупные компоненты.
- **Инкрементальный:** модули интегрируются постепенно, по мере их готовности.
- **"Большой взрыв":** все модули разрабатываются отдельно, а затем интегрируются одновременно.

8.     **Стандарты кодирования.**

**Стандарты кодирования** — это набор правил и рекомендаций для написания исходного кода, направленный на улучшение читаемости, поддерживаемости и качества кода. Включают правила именования переменных, форматирования, комментариев, структуры кода. 

**Преимущества** соблюдения стандартов кодирования:

- Повышение эффективности разработки. Упрощает поддержку и обслуживание кода благодаря единому стилю написания. Сокращает время на понимание кода новыми участниками проекта.

- Улучшение качества кода. Снижает количество ошибок за счёт проверенных практик. Облегчает код-ревью благодаря унификации стиля.

**Примеры:** PSR (PHP Standard Recommendations), Google Java Style Guide, PEP 8 (Python).

9.     **Описание требований: унифицированный язык моделирования - краткий словарь.**

**Унифицированный язык моделирования (UML)** — это графический язык для визуализации, спецификации, конструирования и документирования артефактов программных систем. 

**Краткий словарь:**
- **Класс:** шаблон для создания объектов, описывающий их состояние (атрибуты) и поведение (операции).
- **Объект:** экземпляр класса.
- **Атрибут:** свойство объекта или класса.
- **Операция (Метод):** действие, которое может выполнять объект или класс.
- **Ассоциация:** отношение между двумя классами.
- **Наследование:** отношение, при котором один класс (потомок) наследует свойства и методы другого класса (родителя).
- **Зависимость:** отношение, при котором изменение одного элемента влияет на другой.

10.  **==Диаграммы UML.**==

**Диаграммы UML** — графические представления различных аспектов системы. **Основные типы:**
- **Структурные диаграммы:**
    - **Диаграмма классов:** показывает классы, их атрибуты, операции и отношения.
    - **Диаграмма компонентов:** показывает структуру компонентов системы и их взаимосвязи.
    - **Диаграмма развёртывания:** показывает физическое развёртывание программных артефактов на узлах.
- **Поведенческие диаграммы:**
    - **Диаграмма вариантов использования:** показывает функциональность системы с точки зрения пользователей (акторов).
    - **Диаграмма последовательности:** показывает взаимодействие объектов во времени.
    - **Диаграмма деятельности (активности):** показывает потоки работ или действий.
    - **Диаграмма состояний:** показывает возможные состояния объекта и переходы между ними.

11.  **==Описание и оформление требований (спецификация).==**

**Спецификация требований** — это формальный документ, детально описывающий все функции, ограничения и характеристики разрабатываемой системы. Должна быть полной, непротиворечивой, однозначной, проверяемой и измеримой. 

**Оформление:** обычно включает разделы: введение, описание функций, нефункциональные требования, пользовательский интерфейс, данные, ограничения, глоссарий. Используются стандарты (например, IEEE 830).

12.  **==Анализ требований и стратегии выбора решения==**

**Анализ требований** — процесс изучения собранных требований для их понимания, выявления противоречий, неполноты, неоднозначности и определения их приоритетов. 

**Стратегии выбора решения:**
- **Cost-Benefit Analysis:** оценка затрат и выгод различных вариантов.
- **Risk Analysis:** оценка рисков, связанных с каждым вариантом.
- **Prioritization:** ранжирование требований по важности и срочности (например, MoSCoW: Must, Should, Could, Won't).
- **Prototyping:** создание прототипов для оценки жизнеспособности идей.

13.  **Цели и задачи, и виды тестирования.**

**Цели тестирования:**
- Выявление дефектов и ошибок.
- Проверка соответствия ПО требованиям.
- Оценка качества ПО.
- Снижение рисков. 

**Задачи:** планирование тестов, разработка тестовых случаев, выполнение тестов, анализ результатов. 

**Виды тестирования:**    
- **По уровням:** модульное, интеграционное, системное, приемочное.
- **По видам:** функциональное, нефункциональное (производительность, безопасность, юзабилити), регрессионное, дымовое, смоук-тестирование, нагрузочное, стресс-тестирование

14.  **==Стандарты качества программной документации.==**

**Стандарты качества программной документации** обеспечивают единообразие, полноту, точность и поддерживаемость документов. 

**Международные стандарты:**
2. ISO/IEC/IEEE 26515: регулирует: пользовательскую документацию (руководства, справки).
3. ISO/IEC 12207: регулирует: документацию на всех этапах жизненного цикла ПО.
4. IEEE 830: регулирует: структуру спецификации требований (SRS).

**Российские стандарты (ГОСТ):**
1. ГОСТ 34.201-89: регулирует: виды и комплектность документов для автоматизированных систем (АС).
2. ГОСТ Р 56939-2016: регулирует: документацию для критических систем (медицинское ПО, промышленные системы).
3. ЕСПД: комплекс гос. Стандартов, устанавливающие правила разработки, оформления программ и документации

15.  **Меры и метрики.**

**Меры** — это количественные показатели, используемые для оценки характеристик программного обеспечения или процесса разработки.

**Метрики** — это стандартизированные способы измерения этих характеристик, часто выражаемые как отношение двух мер. 

**Примеры:**
- **Меры:** количество строк кода (LOC), количество дефектов, время выполнения теста.
- **Метрики:** плотность дефектов (дефектов на LOC), процент тестового покрытия, среднее время отклика.

16.  **Тестовое покрытие.**

**Тестовое покрытие** (Test Coverage) — это метрика, которая указывает степень, в которой исходный код программы был выполнен во время выполнения тестовых сценариев. Высокое тестовое покрытие обычно коррелирует с меньшим количеством ошибок. 

**Виды покрытия:** покрытие строк кода, покрытие ветвей, покрытие функций.

17.  **Тестовый сценарий.**

**Тестовый сценарий (Test Case)** — это набор действий, условий и ожидаемых результатов, используемый для проверки определенной функциональности или части системы. Он определяет, что именно нужно протестировать, как это сделать, и какой результат ожидается.

18.  **Тестовый пакет.**

**Тестовый пакет (Test Suite)** — это коллекция логически сгруппированных тестовых сценариев, которые предназначены для тестирования конкретной функциональности, модуля или всей системы. Тестовый пакет может быть выполнен полностью для проверки общей работоспособности.

Структура:
- План тестирования - цели и стратегия тестирования
- Тестовые случаи
- Тестовые данные
- Тестовые среды

19.  **Анализ спецификаций.**

**Анализ спецификаций** — это процесс критической оценки документации с требованиями (спецификаций) для выявления любых неточностей, неполноты, неоднозначностей, противоречий или избыточности. Цель — убедиться, что требования ясны, полны и могут быть реализованы.

20.  **Верификация и аттестация программного обеспечения.**

- **Верификация (Verification):** Процесс проверки того, что ПО разрабатывается **правильно** ("делаем продукт правильно"). Это проверка соответствия каждого этапа разработки его спецификациям. Включает инспекции, обзоры кода, тестирование.

- **Аттестация (Validation):** Процесс проверки того, что разрабатывается **правильный продукт** ("делаем правильный продукт"). Это проверка соответствия конечного продукта потребностям пользователя и бизнес-целям. Обычно включает приемочное тестирование.

21.  **Жизненный цикл программного обеспечения. Краткая характеристика каждого этапа.**

**Жизненный цикл программного обеспечения (SDLC)** — это структурированный процесс, описывающий все этапы разработки ПО.

**Этапы (типично):**
1. **Планирование:** Определение целей, масштаба, ресурсов и рисков проекта.
2. **Анализ требований:** Сбор, документирование и анализ потребностей пользователей и системы.
3. **Проектирование (Дизайн):** Разработка архитектуры системы, структуры данных, пользовательского интерфейса.
4. **Реализация (Кодирование):** Написание исходного кода программы.
5. **Тестирование:** Выявление дефектов и проверка соответствия требованиям.
6. **Развертывание (Внедрение):** Установка и настройка ПО в рабочей среде.
7. **Сопровождение (Эксплуатация):** Поддержка, исправление ошибок, внесение улучшений после развертывания.

22.  **Разработка пользовательских интерфейсов. Типы пользовательских интерфейсов и этапы их разработки.**

**Разработка пользовательских интерфейсов (UI/UX)** — процесс проектирования взаимодействия пользователя с системой.

**Типы пользовательских интерфейсов:**
- **GUI (Graphical User Interface):** Графический интерфейс пользователя (окна, кнопки, иконки).
- **CLI (Command Line Interface):** Интерфейс командной строки.
- **NUI (Natural User Interface):** Естественный пользовательский интерфейс (голосовые, жестовые).
- **Web UI:** Интерфейс на основе веб-браузера.
- **Mobile UI:** Интерфейс для мобильных устройств. 

**Этапы разработки:**
1. **Исследование и анализ:** Понимание потребностей и поведения пользователей.
2. **Проектирование пользовательского опыта (UX):** Создание пользовательских сценариев, вайрфреймов, прототипов.
3. **Проектирование пользовательского интерфейса (UI):** Разработка визуального дизайна, компоновки элементов, выбор цветов, шрифтов.
4. **Реализация:** Кодирование интерфейса.
5. **Тестирование и итерации:** Тестирование юзабилити, сбор обратной связи, внесение улучшений.

23.  **Техническое задание. Разделы, входящие в техническое задание.**

**Техническое задание (ТЗ)** — это основной документ, определяющий цели, задачи, требования к разрабатываемому продукту или системе, а также порядок его создания и приемки. 

**Типичные разделы ТЗ (по ГОСТ 34.602-89):**
1. **Общие положения:** Наименование, заказчик, исполнитель, цель создания.
2. **Назначение и цели создания системы:** Для чего создается, какие проблемы решает.
3. **Характеристика объекта автоматизации:** Описание предметной области.
4. **Требования к системе:** Функциональные, нефункциональные (надежность, производительность, безопасность), требования к интерфейсу, эргономике.
5. **Состав и содержание работ по созданию системы:** Этапы, сроки.
6. **Порядок контроля и приемки системы:** Виды испытаний, критерии приемки.
7. **Требования к подготовке объекта автоматизации к вводу системы в действие**
8. **Требования к составу и содержанию документации:** Перечень документов.
9. **Источники разработки:** Нормативные документы, стандарты.

24.  **Использование языка UML при проектировании сложных программных систем.**

**Используется для:**
- Диаграмм классов, последовательностей, состояний.
- Описания взаимодействия компонентов.
- Документирования системы.

**Помогает:**
- Снижать риски за счет проработки архитектуры до написания кода
- Снизить риски недопонимания между заказчиками, аналитиками и разработчиками
- Документировать архитектуру

25.  **Диаграмма вариантов использования, ее назначение. Правила построения диаграммы вариантов использования.**

**Диаграмма вариантов использования (Use Case Diagram)** — это поведенческая диаграмма UML, показывающая функциональность системы с точки зрения взаимодействия с внешними сущностями (акторами).

**Назначение:** Определить границы системы, показать, кто (акторы) будет взаимодействовать с системой, и что (варианты использования) они будут делать. Помогает на этапе сбора и анализа требований. 

**Правила построения:**
- **Акторы:** Представляются "человечками", взаимодействующими с системой.
- **Варианты использования:** Представляются овалами внутри границы системы. Описывают конкретную функцию или цель актора.
- **Система:** Прямоугольник, обозначающий границы программной системы.
- **Связи:**
    - **Ассоциация:** Линия между актором и вариантом использования, обозначает взаимодействие.
    - **<** Отношение, когда один вариант использования обязательно включает функциональность другого.
    - **<** Отношение, когда один вариант использования расширяет функциональность другого при определенных условиях.
    - **Обобщение (наследование):** Стрелка от более специфического актора/варианта использования к более общему.

26.  **Понятие класса и объекта. Атрибут и операция.**

- **Класс (Class):** Это шаблон или чертеж для создания объектов. Он определяет свойства (атрибуты) и поведение (операции/методы), общие для всех объектов этого класса.

- **Объект (Object):** Это конкретный экземпляр класса. У каждого объекта есть свои уникальные значения для атрибутов, но он использует операции, определенные в его классе.

- **Атрибут (Attribute):** Это характеристика или свойство класса/объекта, описывающее его состояние (например, для класса "Автомобиль" атрибутами могут быть "цвет", "модель", "скорость").

- **Операция (Operation) / Метод (Method):** Это действие или поведение, которое может выполнять класс/объект (например, для класса "Автомобиль" операциями могут быть "завести", "остановить", "ускориться").

27.  **Диаграмма потоков данных. Основное назначение.**

**Диаграмма потоков данных (DFD - Data Flow Diagram)** — это графическое представление движения данных в системе. Она показывает, как данные входят в систему, где они хранятся, как обрабатываются и куда выводятся. 

**Основное назначение:** Визуализировать и анализировать потоки информации в системе или бизнес-процессе, независимо от физической реализации. Помогает понять, какие данные используются, кто ими оперирует, и какие преобразования они проходят.

28.  **Основные принципы структурной методологии. Особенности структурных программ. Цели структурного программирования.**

**Структурная методология** — это подход к разработке ПО, основанный на декомпозиции системы на иерархические, взаимосвязанные модули с использованием ограниченного набора управляющих структур.

**Основные принципы:**
- **Декомпозиция:** Разделение большой задачи на более мелкие, управляемые подзадачи.
- **Иерархия:** Организация модулей в иерархическую структуру.
- **Ограничение управляющих структур:** Использование только трех основных управляющих структур: последовательность, ветвление (if/else), циклы (for/while). Отказ от оператора `goto`.

**Особенности структурных программ:** 
- **Повышенная читаемость:** Благодаря четкой структуре.
- **Легкость отладки:** Ошибки локализуются в отдельных модулях.
- **Улучшенная поддерживаемость:** Изменения в одном модуле меньше влияют на другие.
- **Модульность:** Программа состоит из независимых, многократно используемых блоков. 

**Цели структурного программирования:**
- Улучшение качества программного обеспечения.
- Снижение сложности разработки и сопровождения.
- Повышение производительности разработчиков.
- Обеспечение надежности и ясности кода.

29.  **Модульное программирование (определение). Цели модульного программирования. Достоинства модульного программирования.**

**Модульное программирование** — это парадигма программирования, при которой программа делится на отдельные, независимые, функционально завершенные блоки (модули). Каждый модуль выполняет определенную задачу и взаимодействует с другими модулями через четко определенные интерфейсы.

**Цели модульного программирования:**
- **Управление сложностью:** Разделение большой задачи на подзадачи.
- **Повторное использование кода:** Модули могут быть использованы в других частях программы или в других проектах.
- **Разделение труда:** Разные разработчики могут работать над разными модулями одновременно.
- **Улучшение поддерживаемости и отладки:** Изменения и ошибки локализуются в конкретных модулях. **Достоинства модульного программирования:**
- **Гибкость:** Легко изменять или заменять отдельные модули.
- **Надежность:** Ограничение влияния ошибок на другие части системы.
- **Тестируемость:** Модули могут быть протестированы независимо.
- **Эффективность:** Ускорение разработки и снижения затрат на сопровождение.

30.  **Объектно-ориентированное программирование. Основные понятия: объект, свойство объекта, метод обработки, событие, класс объектов. Метод объектно-ориентированной декомпозиции, метод абстрактных типов данных, метод пересылки сообщений.**

**Объектно-ориентированное программирование (ООП)** — это парадигма программирования, основанная на концепции "объектов", которые могут содержать данные (свойства/атрибуты) и код (методы/операции), управляющие этими данными. 

**Основные понятия:**
- **Объект:** Экземпляр класса, сущность в программе, которая обладает состоянием (данными) и поведением (функциями).
- **Свойство объекта (Атрибут):** Характеристика или данные, описывающие состояние объекта.   
- **Метод обработки (Метод):** Функция или процедура, принадлежащая объекту, которая определяет его поведение и может манипулировать его свойствами.
- **Событие:** Сигнал, который отправляется объектом при наступлении определенного условия или действия (например, нажатие кнопки).
- **Класс объектов:** Шаблон или чертеж, по которому создаются объекты. Определяет общие свойства и методы для группы объектов.

**Методы ООП:**
- **Метод объектно-ориентированной декомпозиции:** Разложение сложной системы на набор взаимодействующих объектов.
- **Метод абстрактных типов данных (Абстракция данных):** Скрытие внутренней реализации данных и предоставление только интерфейса для работы с ними. Объекты инкапсулируют данные и операции.
- **Метод пересылки сообщений:** Объекты взаимодействуют друг с другом, отправляя и получая "сообщения" (вызовы методов). Это обеспечивает слабую связанность между объектами.

31. **Надежность программного изделия. Работоспособность программного изделия. Основные количественные показатели надежности программного изделия.**

**Надежность программного изделия** — это способность программного обеспечения выполнять требуемые функции в заданных условиях в течение заданного периода времени без сбоев.

**Работоспособность программного изделия** — это способность программного обеспечения выполнять свои функции в соответствии с требованиями. Надежность является частью общей работоспособности.

**Основные количественные показатели надежности:**
- **MTBF (Mean Time Between Failures):** Среднее время наработки на отказ. Чем выше, тем надежнее.
- **MTTF (Mean Time To Failure):** Среднее время до отказа (для невосстанавливаемых систем).
- **MTTR (Mean Time To Restore):** Среднее время восстановления после отказа. Чем ниже, тем быстрее система восстанавливается.
- **Плотность дефектов:** Количество дефектов на единицу размера кода (например, на 1000 строк кода).
- **Коэффициент готовности (Availability):** Процент времени, в течение которого система доступна и работоспособна.

32. **Определение тестирования и отладки. Особенности и объекты тестирования. Автономное и комплексное тестирование.**

- **Тестирование:** Процесс выявления дефектов и проверки соответствия программного обеспечения заданным требованиям. Цель — найти ошибки.

- **Отладка (Debugging):** Процесс поиска, локализации и устранения выявленных в ходе тестирования дефектов. Цель — исправить ошибки. 

**Особенности тестирования:**    
- Запланированный процесс (тест-план).
- Применение ручных и автоматизированных подходов.
- Не может гарантировать отсутствие ошибок, только их наличие.

**Объекты тестирования:**    
- Модули, компоненты, подсистемы.
- Интеграции между компонентами.
- Вся система целиком.
- Документация, пользовательские интерфейсы, производительность.

**Автономное (Unit/Module) тестирование:** Тестирование отдельных, наименьших тестируемых частей программы (модулей, функций, классов) в изоляции.

**Комплексное (Integration) тестирование:** Тестирование взаимодействия между двумя или более интегрированными модулями или компонентами системы.

33. **Управление разработкой программных средств. Средства управления проектами. Основная цель управления жизненным циклом программных средств.**

**Управление разработкой программных средств (Project Management)** — это планирование, организация, мотивация и контроль ресурсов для достижения всех целей проекта в рамках установленных ограничений по времени, бюджету и качеству. 

**Средства управления проектами:**
- **Jira, Trello, Asana, Monday.com:** Для отслеживания задач, управления бэклогом, спринтами.
- **Microsoft Project, GanttProject:** Для построения диаграмм Ганта, управления расписанием.
- **Confluence, SharePoint:** Для управления документацией и знаниями.
- **GitLab, GitHub, Bitbucket:** Для управления репозиториями кода и CI/CD. 

**Основная цель управления жизненным циклом программных средств:** Обеспечить создание высококачественного программного обеспечения, которое соответствует требованиям пользователя и бизнеса, в рамках бюджета и в установленные сроки, а также обеспечить его эффективное сопровождение и развитие.

34. **Инструментальные средства разработки программ. Инструментальные среды программирования. Средства автоматизации разработки программ (CASE-средства). Интегрированные среды.**

**Инструментальные средства разработки программ:** Это любое программное обеспечение, помогающее в процессе разработки (компиляторы, отладчики, редакторы). 

**Инструментальные среды программирования:** Набор взаимосвязанных инструментов, облегчающих написание, отладку и тестирование кода. 

**Средства автоматизации разработки программ (CASE-средства - Computer-Aided Software Engineering):** Программные инструменты, автоматизирующие различные этапы жизненного цикла ПО, от анализа требований до тестирования и сопровождения.
- **Upper CASE:** Поддерживают начальные этапы (анализ, проектирование) - например, инструменты для моделирования UML.
- **Lower CASE:** Поддерживают этапы реализации и тестирования - например, генераторы кода, отладчики.
- **Integrated CASE:** Интегрируют функциональность Upper и Lower CASE.

**Интегрированные среды разработки (IDE - Integrated Development Environment):** Комплексное программное обеспечение, объединяющее в себе редактор кода, компилятор/интерпретатор, отладчик, средства автоматизации сборки и другие инструменты для удобной разработки. 
**Примеры IDE:** Visual Studio Code, IntelliJ IDEA, Eclipse, PyCharm.

35. **Оценка качества программного обеспечения. Методы оценки свойств программного обеспечения.**

**Оценка качества программного обеспечения** — это процесс определения степени, в которой ПО соответствует требованиям и ожиданиям пользователя. 

**Методы оценки свойств ПО:**
- **Обзоры и инспекции кода:** Систематический анализ кода экспертами для выявления дефектов и нарушения стандартов.
- **Тестирование:** Различные виды тестирования (функциональное, нефункциональное) для выявления ошибок и проверки соответствия требованиям.
- **Метрики качества:** Использование количественных показателей (см. вопрос 15) для измерения характеристик кода (сложность, размер, плотность дефектов).
- **Анализ рисков:** Оценка потенциальных проблем и их влияния на качество.
- **Аудиты качества:** Проверка соответствия процессов разработки установленным стандартам и процедурам.
- **Модели качества:** Использование стандартов (например, ISO/IEC 25010) для структурированной оценки функциональной пригодности, надежности, удобства использования, эффективности, сопровождаемости, переносимости.

36. **Внедрение программного комплекса. Подготовка тестовых данных. Анализ результатов испытаний.**

**Внедрение программного комплекса** — это процесс установки, настройки и ввода в эксплуатацию программного обеспечения в рабочей среде пользователя. Включает планирование развертывания, миграцию данных, обучение пользователей и переход на новую систему. 

**Подготовка тестовых данных:** Создание или сбор данных, которые будут использоваться при выполнении тестовых сценариев. Данные должны быть репрезентативными, разнообразными, включать как корректные, так и некорректные значения, а также граничные условия, чтобы максимально проверить функциональность системы.

**Анализ результатов испытаний:** Процесс оценки результатов выполнения тестовых сценариев. Включает:
- **Сравнение фактических результатов с ожидаемыми:** Выявление расхождений (дефектов).
- **Документирование дефектов:** Фиксация информации об ошибках (описание, шаги воспроизведения, серьезность, приоритет).
- **Анализ корневых причин:** Поиск причин возникновения дефектов.
- **Формирование отчетов:** Предоставление информации о состоянии тестирования, количестве найденных дефектов, покрытии тестами и общем качестве ПО.
- **Принятие решений:** На основе анализа результатов принимаются решения о готовности продукта к релизу или необходимости доработки.

# Практика

## **Диаграмма активностей (деятельности) UML**

### 1. Что это

Диаграмма активности это поток использования или бизнес-процесса. 

Такую диаграмму можно составить просто из действий (пользователь сделал то, бухгалтер сделал сё) и условий (если счет не просрочен то это иначе другое), плюс можно добавить комментарии.

| Символ                                                                                                           | Имя                             | Использовать                                                                                          |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------- | ----------------------------------------------------------------------------------------------------- |
| ![Начать](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Start.png)                                       | Пуск/ начальный узел            | Используется для представления отправной точки или начального состояния деятельности                  |
| ![Деятельность](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Activity.png)                              | Действие / Состояние действия   | Используется для представления деятельности процесса                                                  |
| ![Действие](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Action.png)                                    | Действие                        | Используется для представления исполняемых подрайонов деятельности                                    |
| ![Поток управления](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Control-flow.png)                      | Поток управления / Край         | Используется для представления потока управления от одного действия к другому                         |
| ![Поток объекта](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Object-flow.png)                          | Поток объекта / края управления | Используется для отображения пути движения объектов по активности                                     |
| ![Конечный узел активности](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Final-node.png)                | Конечный узел активности        | Используется для обозначения конца всех контрольных потоков в рамках деятельности                     |
| ![Конечный узел потока](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Flow-final-node.png)               | Поток конечный узел             | Используется для обозначения конца одного потока управления                                           |
| ![Узел принятия решений](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Decision-node-and-merge-node.png) | Узел принятия решений           | Используется для представления условной точки ответвления с одним входом и несколькими выходами       |
| ![Узел Слияния](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Decision-node-and-merge-node-1.png)        | Узел слияния                    | Используется для представления слияния потоков. Он имеет несколько входов, но один выход.             |
| ![Вилка](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Fork.png)                                         | Вилка                           | Используется для представления потока, который может разветвляться на два и более параллельных потока |
| ![Слияние](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Merge.png)                                      | Слияние                         | Используется для представления двух входов, которые объединяются в один выход                         |
| ![Отправка сигнала](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Signal-sending.png)                    | Отправка сигнала                | Используется для представления действия по отправке сигнала на приемную деятельность                  |
| ![Получение сигнала](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Signal-receipt.png)                   | Получение сигнала               | Используется для обозначения того, что сигнал получен                                                 |
| ![Примечание или комментарий](https://d3n817fwly711g.cloudfront.net/uploads/2018/08/Note-or-comment.png)         | Примечание/комментарий          | Используется для добавления соответствующих комментариев к элементам                                  |

### 2. Как нарисовать диаграмму деятельности

- Шаг 1: Определите шаги действия по сценарию использования
- Шаг 2: Определите участвующих субъектов
- Шаг 3: Найти поток среди мероприятий
- Шаг 4: Добавить дорожки

![[activity.png]]

## Диаграмма классов UML

### 1. Что это

Эта диаграмма определяет классы и отношения между ними.

### 2. Класс

Класс состоит из трех полей:
- имя класса 
- атрибуты (`+|- attr: Type`)
- методы (`+|- meth([arg1: Type, ...]): return Type`)
![[Pasted image 20250630112908.png]]
### 3. Отношения

1. **Ассоциация**
Аналогично связям, соединяющим объекты, ассоциации соединяют классы. Для того, чтобы между объектами была связь, между ними должна быть ассоциация.
![[Pasted image 20250630113142.png]]
2. **Наследование**
![[Pasted image 20250630113215.png]]
3. **Зависимость**  
  
![](https://habrastorage.org/r/w1560/webt/b5/ay/zf/b5ayzflsuhktk-pdeqwkp2xbjfo.png)  
  
Объект одного класса может использовать объект другого класса в своем методе.  
Если объект не хранится в поле класса, то такой вид межклассовых отношений моделируется как зависимость.
4. **Композиция**  
![](https://habrastorage.org/r/w1560/webt/a4/t_/7v/a4t_7vdsxzhcrokm2laiytvnmoq.jpeg)

## Диаграмма компонентов

### 1. Что это

Диаграмма описывает взаимодействие компонентов системы. 

Компонентами могут быть база данных, пользовательский интерфейс и тд.

### 2. Компонент

Существует три способа использования символа компонента.

1) ![Стереотип компонента](https://d3n817fwly711g.cloudfront.net/uploads/2018/09/Component-stereotype.png)

2) ![Компонент](https://d3n817fwly711g.cloudfront.net/uploads/2018/09/Component-icon-1.png)

3) ![Компонент](https://d3n817fwly711g.cloudfront.net/uploads/2018/09/Component-2.png)

### 3. Предоставляемый интерфейс и требуемый интерфейс

![Предоставляемый интерфейс и необходимый интерфейс](https://d3n817fwly711g.cloudfront.net/uploads/2018/09/Assembly-Connector.png)

Это показывает, что один компонент предоставляет услугу, которая требуется другому (с право на лево).

## **Диаграмма последовательности**



## Диаграмма состояний

## Диаграмма развертывания

## **Функциональная схема**

## **Диаграмма прецедентов**

## **Диаграмма потоков данных**

## **ER диаграмма**

## Диаграмма вариантов использования

## Диаграмма кооперации




# Теория кодирования

Подготовительные билеты к собеседование/экзамену по лекционным материалам курса **Теория кодирования** (7 семестр).

| Build Type        | Status                                                                                                                      |
|:------------------|:----------------------------------------------------------------------------------------------------------------------------|
| Push              | [![TC](../../actions/workflows/build.yml/badge.svg?branch=main&event=push)](../../actions/workflows/build.yml)              |
| Workflow Dispatch | [![TC](../../actions/workflows/build.yml/badge.svg?branch=main&event=workflow_dispatch)](../../actions/workflows/build.yml) |

> [!WARNING]
> В билетах встречаются ошибки и недосказанности, а также имеются проблемы с согласованностью общего стиля ввиду разного виденья мира разных летописцев.

## Структура проекта

В [`src`](src/) хранится материал как к экзамену, так и к собеседованию.

## Материал

Все билеты написаны в формате [Markdown](https://en.wikipedia.org/wiki/Markdown), которые можно скомпилировать в PDF формат с помощью [`pandoc`](https://github.com/jgm/pandoc). Через двоеточие указан автор.

> [!WARNING]
> Из-за специфических свойств $\LaTeX$ через браузерную версию GitHub все математические формулы поломаны и никаким образом не могут быть нормально отображены. Рекомендуется собирать через `pandoc`.

### Билеты

Здесь составлен список на основе экзамена *2023* года, так как нынешний список вопросов кажется подозрительным...

* [Структура систем передачи информации. Простейшие методы модуляции. Критерии идеального наблюдателя и максимума правдоподобия. Вероятность ошибки сигналов 2-АМ в случае канала с АБГШ. Отношение сигнал/шум на бит и на символ](src/T1.md): TBA.
* [Блоковые коды и их параметры. Критерии декодирования и метрики. Границы Хемминга и Варшамова-Гилберта](src/T2.md): TBA.
* [Линейные коды. Границы Синглтона, Варшамова-Гилберта и Грайсмера. Вероятность ошибки декодирования и необнаружения ошибки](src/T3.md): TBA.
* [Декодирование линейных кодов. Таблица стандартной расстановки. Код Хемминга. Стирания](src/T4.md): TBA.
* [Декодирование по информационным совокупностям](src/T5.md): TBA.
* [Дуальные коды. Весовой спектр кода. Тождество Мак-Вильямс и его доказательство](src/T6.md): TBA.
* [Критерии мягкого декодирования. Метод порядковых статистик](src/T7.md): TBA.
* [Минимальная решетка линейного блокового кода и способы ее построения. Алгоритм Витерби](src/T8.md): TBA.
* [Декодирование с мягким выходом. Алгоритм БКЕ](src/T9.md): TBA.
* [Сверточные коды. Способы представления. Катастрофические порождающие матрицы](src/T10.md): TBA.
* [Производящая функция сверточных кодов. Вероятность ошибки декодирования сверточных кодов с помощью алгоритма Витерби](src/T11.md): TBA.
* [Конструкция Плоткина. Коды Рида-Маллера. Прямое произведение кодов. Обобщенные каскадные коды](src/T12.md): TBA.
* [Укорочение, выкалывание и расширение кодов. Турбо-коды](src/T13.md): TBA.
* [Параметр Бхаттачарьи. Поляризация канала. Полярные коды. Сложность кодирования](src/T14.md): TBA.
* [Алгоритм последовательного исключения и декодер Тала-Варди](src/T15.md): TBA.
* [Построение полярных кодов. Полярные коды с CRC, полярные подкоды](src/T16.md): TBA.
* [Циклические коды. Порождающий и проверочный многочлены. Кодирование](src/T17.md): TBA.
* [Идеалы, факторкольца и поля](src/T18.md): TBA.
* [Конечные поля. Характеристика поля. Число элементов в поле Галуа и его примитивный элемент. Основные свойства](src/T19.md): TBA.
* [Минимальные многочлены](src/T20.md): TBA.
* [Проверочная матрица циклического кода над расширенным полем. Коды БЧХ. Граница БЧХ. Свойства](src/T21.md): TBA.
* [Коды Рида-Соломона и обобщенные коды Рида-Соломона](src/T22.md): TBA.
* [Алгоритм Питерсона-Горенстайна-Цирлера декодирования кодов БЧХ](src/T23.md): TBA.
* [Ключевое уравнение декодирования кодов БЧХ. Алгоритм Форни. Декодирование с помощью алгоритма Евклида](src/T24.md): TBA.
* [Альтернантные коды. Коды Гоппы. Криптосистема Мак-Элиса](src/T25.md): TBA.
* [Низкоплотностные коды. Основные характеристики. Конструкции низкоплотностных кодов](src/T26.md): TBA.
* [Декодирование низкоплотностных кодов](src/T27.md): TBA.
* [Эволюция плотностей и порог итеративного декодирования низкоплотностных кодов](src/T28.md): TBA.
* [Кодирование в стирающих каналах. Цифровой фонтан. LT-коды и хищные коды](src/T29.md): TBA.
* [Битоперемеженная кодовая модуляция. Многоуровневые коды](src/T30.md): TBA.

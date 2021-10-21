# Kicadoc
asodjfhas;jdhgfa;sljdhf;ajshdf;ahjsdf
asdfljhasd;gjlnhadsg
asdg
asd
gasd
gad
fhadfhadfh
у разными обозначениями (ПЭ3)
empty rows between diff ref = 1
######  # Разделить группы по стандартам
separate group for each doc = no
######  # Зарезервировать номера позиций
reserve position numbers = no
######  # Нумеровать строки только для компонентов (ВП)
only components have position numbers = no
######  # Обрабатывать повторяющиеся значения (ВП)
process repeated values = no
######  # Разделы спецификации
[sections]
######  # 1. Документация
documentation = yes
######  # Схема электрическая принципиальная
schematic = yes
######  # Перечень элементов
index = yes
######  # Ведомость покупных изделий
bom = yes
######  # Ведомость документов на носителях данных
docsheet = yes
######  # Информационно-удостоверяющий лист
certsheet = yes
######  # Карты рабочих режимов
opmodemaps = yes
######  # Сборочный чертеж
assembly drawing = yes
######  # 2. Сборочные единицы
assembly units = no
######  # 3. Детали
details = yes
######  # Плата печатная
pcb = yes
######  # 4. Стандартные изделия
standard parts = no
######  # 5. Прочие изделия
other parts = yes
######  # 6. Материалы
materials = no
######  # Поля таблиц
[fields]
######  # Тип (группа компонентов)
type = Группа
######  # Наименование
name = ${|Марка|}${ |Значение|}${ |Класс точности|}${-|Тип|}
######  # Стандарт
doc = Стандарт
######  # Примечание
comment = Примечание
######  # Регулируемый компонент
adjustable = Подбирают при регулировании
######  # Код продукции
code = 
######  # Поставщик
dealer = 
######  # Куда входит (обозначение)
for what =
######  # Исключенный компонент
excluded = Исключён из ПЭ
######  # Основная надпись
[stamp]
######  # Обработать наименование документа
convert doc title = yes
######  # Обработать обозначение документа
convert doc id = yes
######  # Заполнить Перв. примен. (графа 25)
fill first usage = yes
######  # Поместить обозначение в заголовок таблицы (для групповых документов)
place doc id to table title = yes
######  # Псевдонимы
[aliases]
Значение = Номинал
######  # Настройки модулей вывода
[output]
######  # Путь к стилевым пакетам
latex_path = latex/
######  # Файл шаблона LaTeX
latex_template = latex/template.tex
######  # Разделитель в файлах CSV
csv_delimiter = \t
######  # Формат экспорта по умолчанию
default_type = pdf

# TZ
Министерство образования Калининградской области
государственное бюджетное учреждение Калининградской области
профессиональная образовательная организация 
«Колледж информационных технологий и строительства»
(ГБУ КО ПОО «КИТиС»)






Отчет по учебной практике
УП.01 Разработка модулей программного обеспечения для компьютерных систем
по ПМ.01 Разработка модулей программного обеспечения для компьютерных систем

Специальность09.02.07 «Информационные системы и программирование»

Сроки прохождения практики:
с «12» октября 2022 г. по «01» ноября 2022 г. 

Место практикиГБУ КО ПОО «КИТиС»


Выполнил:	Студентка 4 курса, 
группы ИСп19-2к
Прокофьева Алина Сергеевна
_________________
            (подпись)
Проверила:	Большакова-Стрекалова Анна Викторовна
_________________
            (оценка)
_________________
      (подпись, дата)



Калининград, 2022
































Техническое задание
Выполнела Прокофьева Алина ИСп19-2к 4 курс
Вариант 18 "Издательство"



























Содержание
Введение
1. umbrella
2. Осноование для разработки
3. НАЗНАЧЕНИЕ РАЗРАБОТКИ
4. Требования к программе или программному изделию
5. Требования к программной документации
6. Технико-экономические показатели
7. Стадии и этапы разработки
8 Порядок контроля и приемки
8.1 Виды испытаниея
8.2 Этапы внедрения
8.3 Общие сведение 
8.4 НАЗНАЧЕНИЕ И ЦЕЛИ СОЗДАНИЯ (РАЗВИТИЯ) СИСТЕМЫ
8.5 требование к системе 
8.6 ХАРАКТЕРИСТИКИ ОБЪЕКТА АВТОМАТИЗАЦИИ
8.7  ТРЕБОВАНИЯ К СИСТЕМЕ
9. Приложения к техническому заданию
10. заключение
11 Список литературы













Введение
издательство — предприятие (государственное, общественное, кооперативное или частное) — медиакомпания, которая работает в области литературы, искусства, музыки или науки, и продукция которой может воспроизводиться и распространяться. Распространение издательской продукции может осуществляться через каналы торговли, интернет, а также непосредственно самим издателем. Распространение может быть как платным, так и бесплатным, в зависимости от целей существования издательства и от его бизнес-модели.[1]

Издательство «Эксмо́» — российская издательская компания, основанная в 1991 году Александром Красовицким, Олегом Новиковым и Андреем Гредасовым (бренд Эксмо появился в 1993 году). Бизнес начинался с оптовой торговли книгами, позже у Эксмо появились свои типографии и розничные сети. Благодаря изданию отечественных детективов (в первую очередь романов Данила Корецкого и Александры Марининой) в конце 1990-х годов Эксмо значительно увеличило продажи и стало основой крупного холдинга, в который вошли типографии, книготорговая сеть «Буквоед», издательства «Манн, Иванов и Фербер», «Вентана-Граф», «Дрофа» и др. В 2010-е годы Олег Новиков купил и издательство АСТ, которое, правда, осталось формально независимой структурой. «Эксмо» является крупнейшим издательством России, одним из крупнейших издательств Европы, входит в мировой топ-50. Оно выпускает книги во всех основных жанрах (детективы, фантастика, фэнтези, отечественная и зарубежная классика, современная литература, поэзия, книги для детей, non-fiction, учебники), сотрудничает со множеством популярных авторов (в их числе Александра Маринина, Татьяна Устинова, Дарья Донцова, Вадим Панов, Виктор Пелевин). Среди серий издательства — «Иронический детектив», «Чёрный котёнок», «Золотая серия поэзии» и др.

1. umbrella
Umbrello — среда UML-моделирования. Это приложение является свободным программным обеспечением, предназначенным для построения UML диаграмм на платформе Unix. Является CASE инструментом. Umbrello входит в пакет kdesdk оконного менеджера KDE, но также хорошо работает и с другими оконными менеджерами. Пользовательский интерфейс программы прост и функционален. [2]

Umbrello поддерживает все стандартные типы UML-диаграмм. Также поддерживается импорт из C++, IDL, Pascal/Delphi, Ada, Python, Java, Perl (с помощью внешнего инструмента, доступного на uml.sourceforge.net) и экспорт диаграмм в различные языки программирования. Формат файла, используемый при хранении диаграмм, основан на XMI.

Umbrello позволяет хранить данные модели в форматах DocBook и XHTML. Это было сделано с целью поддержки модели совместной разработки, когда не все разработчики имеют доступ к Umbrello. Эта возможность также незаменима при необходимости размещения контента модели на web-сайте.










2. Основание для разработки
Поступила жалоба от клиентов и сотрудников








 3. НАЗНАЧЕНИЕ РАЗРАБОТКИ
Для удобства пользования данной программы
Сохранения всех данных книг, клиентов и сотрудников  и передача в архив





4. Требования к программе или программному изделию
Данное программное изделие может  дабавлять постоянных клиентах в список, какую скидку они получают на дданую продукцию
Может изменять эту скидку на более высокую , если клиент часто покупает книги
Удаляет данные книни, если ее продавать больше не будут
Также сохраняються все жанные этой книги и передаються в архив

5. Требования к программной документации


Доументация  на программное обеспечение — печатные руководства пользователя, диалоговая (оперативная) документация и справочный текст, описывающие, как пользоваться программным продуктом.

Документ — элемент документации: целевая информация, предназначенная для конкретной аудитории, размещенная на конкретном носителе (например, в книге, на диске, в краткой справочной карте) в заданном формате.

Программная документация — документы, содержащие в зависимости от назначения данные, необходимые для разработки, производства, эксплуатации, сопровождения программы или программного средства. [3]



6. Технико-экономические показатели

№                             Показатели                                             Ед изм                              Кол-во
 1         Строительный бьект всего здания                   м^3                                        26000

2      Общая прощадь здания                                               м^2                                      4700

3           Продолжительность строительства                    дней                                      70
                   
4      общая трудоёмкость                                              чел-дн                                       160
 
5          Максимально кол-во рабочих                            чел                                          12
6  ср кол-во рабочих                                                           чел                                           6















7. Стадии и этапы разработки



Этапы работ

Содержание работ

Обоснование необходимости разработки программы

Постановка задачи. Сбор исходных материалов. Выбор и обоснование критериев эффективности и качества разрабатываемой программы. Обоснование необходимости проведения научно-исследовательских работ

Научно-исследовательские работы

Определение структуры входных и выходных данных. Предварительный выбор методов решения задач. Обоснование целесообразности применения ранее разработанных программ. Определение требований к техническим средствам. Обоснование принципиальной возможности решения поставленной задачи

Разработка и утверждение технического задания

Определение требований к программе. Разработка технико-экономического обоснования разработки программы. Определение стадий, этапов и сроков разработки программы и документации на нее. Выбор языков программирования

Разработка и утверждение технического задания

Определение необходимости проведения научно-исследовательских работ на последующих стадиях. Согласование и утверждение технического задания [4]



















8 Порядок контроля и приемки



8.1Виды испытаний

Проверка документации программы осуществляется самим заказчиком с привлечением сторонних экспертов, способных засвидетельствовать факт соответствия созданного программного продукта всем пунктам технической документации, включая техническое задание и технический проект.

Испытания и тестирование программы должны проводиться в процессе создания программы самим разработчиком:

1. C использованием контрольных тестов, позволяющих добиться проверки правильности работоспособности и взаимной совместимости максимального числа функций и операторов программы или модуля при минимальных затратах временных и финансовых ресурсов.

2. Путем пошагового исполнения программы или модуля (и непрерывного контроля значений переменных) в соответствии с набором тестовых примеров и сравнения полученных в процессе тестирования значений с контрольными значениями тестовых примеров.


3. С привлечением сторонних неофициальных бета-тестеров, которые в процессе тестирования программного продукта должны сообщать разработчику все найденные ошибки и неточности в работе программы.

Испытания и тестирование программы должны проводиться после завершения создания программы заказчиком:

1. С использованием проверочных тестов, составляемых заказчиком заблаговременно.

2. В процессе начального этапа внедрения программы, путем тестирования программы в организации заказчика в рабочих условиях на протяжении срока в 1 неделю.

3. В организации заказчика с привлечением сторонних экспертов.

6.2 Общие требования к приёмке

Приёмка программы должна осуществляться заказчиком. Программа должна считаться годной, если она удовлетворяет всем пунктам данного технического задания, что должно быть засвидетельствовано сторонними экспертами.

 

8.3 ЭТАПЫ ВНЕДРЕНИЯ

Срок внедрения зависит от сложности внедряемого программного обеспечения. Для большинства программных изделий продолжительность стандартного внедрения составляет от двух дней до двух недель. В состав типового проекта внедрения входят следующие этапы:

- установка программного продукта у клиента;

- настройка программного продукта под индивидуальные характеристики заказчика;

- перенос накопленных массивов информации;

- проверка логической целостности базы данных (технический аудит);

- заведение дополнительной нормативно-справочной информации;

- проведение пробных пусков;

- обучение персонала.

 8.4 ОБЩИЕ СВЕДЕНИЯ
1.1 полное наименование системы и ее условное обозначение;

1.2. шифр темы или шифр (номер) договора;

1.3. наименование предприятий (объединений) разработчика и заказчика (пользователя) системы и их реквизиты;

1.4. перечень документов, на основании которых создается система, кем и когда утверждены эти документы;

1.5. плановые сроки начала и окончания работы по созданию системы;

1.6. сведения об источниках и порядке финансирования работ;

1.7. порядок оформления и предъявления заказчику результатов работ по созданию системы (ее частей), по изготовлению и наладке отдельных средств (технических, программных, информационных) и программно-технических (программно-методических) комплексов системы.

8.5 НАЗНАЧЕНИЕ И ЦЕЛИ СОЗДАНИЯ (РАЗВИТИЯ) СИСТЕМЫ

2.1 Назначение системы

2.2 Цели создания системы

8.6 ХАРАКТЕРИСТИКИ ОБЪЕКТА АВТОМАТИЗАЦИИ

3.1. Краткие сведения об объекте автоматизации или ссылки на документы, содержащие такую информацию;

3.2. Сведения об условиях эксплуатации объекта автоматизации и характеристиках окружающей среды.

8.7 ТРЕБОВАНИЯ К СИСТЕМЕ

4.1. Требования к системе в целом;

4.2. Требования к функциям (задачам), выполняемым системой;

4.3. Требования к видам обеспечения.

8.6 СОСТАВ И СОДЕРЖАНИЕ РАБОТ ПО СОЗДАНИЮ (РАЗВИТИЮ) СИСТЕМЫ

5.1.Перечень стадий и этапов работ по созданию системы в соответствии с ГОСТ 24.601

5.2. Сроки их выполнения

5.3. Перечень организаций - исполнителей работ, ссылки на документы, подтверждающие согласие этих организаций на участие в создании системы, или запись, определяющую ответственного (заказчик или разработчик) за проведение этих работ.

5.4. Перечень документов, по ГОСТ 34.201, предъявляемых по окончании соответствующих стадий и этапов работ;

5.5. Вид и порядок проведения экспертизы технической документации (стадия, этап, объем проверяемой документации, организация-эксперт); [5]






9. Приложения к техническому заданию



 
10. заключение
Компания занимает 20% российского книжного рынка и располагает крупнейшим в России авторским портфелем из 8000 имен. «ЭКСМО» – лидер по тиражу издаваемых книг по данным Российской книжной палаты, ведущее издательство на рынке художественной, развлекательной, прикладной и детской литературы.

Издательство имеет развитую дистрибуторскую сеть, включающую восемь региональных центров. Особое внимание уделяется оперативности поставок новинок в магазины – через два-пять дней с момента выхода книги.


11. Список литературы
1 Википедия " Издательство"
2 Википедия "Umbrello"
3 lektsii.org
4 Википедия " стадиия этапы и разработки"
5 Вкипедия " ребования к программному обеспечени"

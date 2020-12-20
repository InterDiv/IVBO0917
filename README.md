
СОГЛАСОВАНО
Руководитель НИИАА	УТВЕРЖДАЮ
Начальник управления

Личная 
подпись	Расшифровка
подписи	Личная 
подпись	Расшифровка
подписи

09.10.20	09.10.20

УТИЛИТА FIND КОМАНДНОЙ СТРОКИ CMD
Техническое задание
ЛИСТ УТВЕРЖДЕНИЯ
A.B.00001-01 33 01-1-ЛУ
Листов 2

	Подп. и дата		СОГЛАСОВАНО	Представители
предприятия-разработчика

		Руководитель ВЦ	Главный инженер
НИИавтоматики
Инф. № дубл.
		Личная 
подпись	Расшифровка
подписи	Личная 
подпись	Расшифровка
подписи
		09.10.20	09.10.20
		Главный инженер завода	Начальник отдела
		Личная 
подпись	Расшифровка
подписи	Личная 
подпись	Расшифровка
подписи
Взам. Инв. №		09.10.20	09.10.20
			Руководитель разработки
				Личная 
подпись	Расшифровка
подписи
			09.10.20
Подп. и дата			Исполнитель
				Личная 
подпись	Расшифровка
подписи
				09.10.20
			Нормоконтролер
Инв. № подп.				Личная 
подпись	Расшифровка
подписи
				09.10.20

УТВЕРЖДЕН
A.B.00001-01 33 01-1-ЛУ

	
			
	

УТИЛИТА FIND КОМАНДНОЙ СТРОКИ CMD
Техническое задание
ЛИСТ УТВЕРЖДЕНИЯ
A.B.00001-01 33 01-1-ЛУ
Листов 15

Подп. и дата	
Инф. № дубл.	
Взам. Инв. №	
Подп. и дата	
Инв. № подп.	

СОДЕРЖАНИЕ
1. введение	5
1.1. Наименование программы	5
1.2. Краткая характеристика области применения программы	5
2. Основание для разработки	5
2.1. Основание для проведения разработки	5
2.2. Наименование и условное обозначение темы разработки	5
3. Назначение разработки	6
3.1. Функциональное назначение программы	6
3.2. Эксплуатационное назначение программы	6
4. Требования к программе	7
4.1. Требования к функциональным характеристикам	7
4.1.1. Требования к составу выполняемых функций	7
4.1.2. Требования к организации входных и выходных данных	7
4.1.3. Требования к временным характеристикам	8
4.2. Требования к надежности	8
4.2.1. Требования к обеспечению надежного (устойчивого) функционирования программы	8
4.2.2. Контроль входной и выходной информации	8
4.2.3. Время восстановления после отказа	8
4.3. Условия эксплуатации	8
4.3.1. Климатические условия эксплуатации	8
4.3.2. Требования к видам обслуживания	8
4.3.3. Требования к численности и квалификации персонала	9
4.4. Требования к составу и параметрам технических средств	9
4.5. Требования к информационной и программной совместимости	9
4.5.1. Требования к информационным структурам и методам решения	9
4.5.2. Требования к исходным кодам и языкам программирования	9
4.5.3. Требования к программным средствам, используемым программой	9
4.5.4. Требования к защите информации и программ	10
4.6. Требования к маркировке и упаковке	10
4.7. Требования к транспортированию и хранению	10
4.8. Специальные требования	10
5. Требования к программной документации	11
5.1. Предварительный состав программной документации	11
5.2. Специальные требования к программной документации	11
6. Технико-экономические показатели	12
6.1. Ориентировочная экономическая эффективность	12
6.2. Предполагаемая годовая потребность	12
6.3. Экономические преимущества разработки	12
7. Стадии и этапы разработки	13
7.1. Стадии разработки	13
7.2. Этапы разработки	13
7.3. Содержание работ по этапам	13
8. Порядок контроля и приемки	15
8.1. Виды испытаний	15
8.2. Общие требования к приемке работы	15

1. введение
1.1.Наименование программы
Наименование – «Утилита FIND командной строки CMD»
1.2.Краткая характеристика области применения программы
FIND – это небольшая системная утилита вашей операционной системы, которая позволяет выполнять операции по поиску файлов и каталогов по определенным критериям, а также совершать операции над файлами.
2.Основание для разработки
2.1.Основание для проведения разработки
Основанием для проведения разработки является лабораторная работа №1 по дисциплине «Технология разработки ПО АСОИУ». Лабораторная работа утверждена Сувальским А.А., в дальнейшем именуемым Заказчиком. Дата утверждения – 03.09.2020.
2.2.Наименование и условное обозначение темы разработки
Наименование темы разработки – «Разработка утилиты».
Условное обозначение темы разработки – «A.B.00001».


3.Назначение разработки
3.1.Функциональное назначение программы
Команда FIND дает возможность пользователю осуществлять поиск и операции над файлами и каталогами. Также распространена практика применения команды FIND для поиска строки в результатах выводов в других программах или , например, для определения доступности сетевого узла с помощью команды PING.
3.2.Эксплуатационное назначение программы
Утилита FIND должна эксплуатироваться в интерпретаторе командной строки CMD.


4.Требования к программе
4.1.Требования к функциональным характеристикам
4.1.1.Требования к составу выполняемых функций
Утилита FIND должна обеспечивать возможность выполнения перечисленных ниже функций:
1)функции выполнения команды для каждого элемента;
2)функции выполнения команды для устранения неполадок.
4.1.2.Требования к организации входных и выходных данных
Утилита FIND.
Стандартные инструменты find, интегрированные в графический интерфейс пользователя (GUI), позволяют выполнять несколько общих задач с найденными файлами: их можно выбрать для вырезания, вставки, копирования; эти файлы можно переместить в новый каталог; можно открыть их программой, при помощи которой эти файлы были созданы. Эти операции состоят из двух и более шагов и не являются автоматическими – сначала выполняется поиск файлов, затем, с использованием GUI-интерфейса, эти файлы помечаются для выполнения следующей операции. Этот подход хорошо подходит для многих пользователей, но исследователь хочет большего.
Команда find может удалять, копировать, перемещать и выполнять найденные файлы. Дополнительно, с параметром -exec, find может автоматически прогонять файлы через любую нужную последовательность команд UNIX. find может даже запросить подтверждение перед выполнением подобных операций с любым файлом.
Синтаксис утилиты FIND:
find [/v] [/c] [/n] [/i] "строка" [[диск:][путь]ИмяФайла[...]]
 Параметры утилита FIND:
/v - Выводит все строки, не содержащие строку, заданную параметром строка
/c - Подсчет строк, содержащих строку, указанную параметром строка, и отображение общего количества
/n – Выводит номера строк перед самими строками
/i - Задает поиск без различия строчных и заглавных букв
4.1.3.Требования к временным характеристикам
Требования к временным характеристикам программы не предъявляются.
4.2.Требования к надежности
4.2.1.Требования к обеспечению надежного (устойчивого) функционирования программы
Надежное (устойчивое) функционирование программы должно быть обеспечено выполнением совокупности организационно-технических мероприятий:
1)организацией бесперебойного питания технических средств;
2)выполнением рекомендаций Министерства труда и социального развития РФ, изложенных в Постановлении от 23 июля 1998 г. «Об утверждении межотраслевых типовых норм времени на работы по сервисному обслуживанию ПЭВМ и оргтехники и сопровождению программных средств»;
3)выполнением требований ГОСТ 51188-98. Защита информации. Испытания программных средств на наличие компьютерных вирусов;
4)необходимым уровнем квалификации сотрудников профильных подразделений.
4.2.2.Контроль входной и выходной информации
В случае неправильного ввода команды FIND, командная строка должна вывести сообщение.
4.2.3.Время восстановления после отказа
Время восстановления после отказа должно не превышать 30 мин.
4.3.Условия эксплуатации
4.3.1.Климатические условия эксплуатации
Программа должна работать в закрытых помещениях, при нормальных климатических условиях.
Температура окружающего воздуха должна быть в диапазоне 20-25 градусов, относительная влажность на уровне 40-60%.
4.3.2.Требования к видам обслуживания
Проводится периодическое тестирование программы, раз в полгода.
4.3.3.Требования к численности и квалификации персонала
Минимальное количество персонала, требуемого для работы программы, должно составлять не менее двух штатных единиц – системный программист и конечный пользователь программы – оператор.
Системный программист должен иметь минимум среднее техническое образование. В перечень задач, выполняемых системным программистом, должны входить:
1)задача поддержания работоспособности технических средств;
2)задача установки (инсталляции) и поддержания работоспособности системного программного средства - операционной системы;
3)задача установки (инсталляции) программы.
Конечный пользователь программы (оператор) должен обладать практическими навыками работы с графическим пользовательским интерфейсом операционной системы.
4.4.Требования к составу и параметрам технических средств
B состав технических средств должен входить IBM-совместимый персональный компьютер (ПЭВМ), включающий в себя:
1)процессор Pentium – 4 с тактовой частотой не менее 300 МГц;
2)оперативную память объемом не менее 128 Мб;
3)жесткий диск объемом 1.5 Гб и выше.
4.5.Требования к информационной и программной совместимости
4.5.1.Требования к информационным структурам и методам решения
Требования к информационным структурам на входе и выходе, а также к методам решения не предъявляются.
4.5.2.Требования к исходным кодам и языкам программирования
Исходные коды программы должны быть реализованы в пакетном файле или непосредственно в интерпретаторе командной строки CMD.
4.5.3.Требования к программным средствам, используемым программой
Должна использоваться командная строка, встроенная в операционную систему Windows.
4.5.4.Требования к защите информации и программ
Требования к защите информации и программ не предъявляются.
4.6.Требования к маркировке и упаковке
Требования к маркировке и упаковке не предъявляются.
4.7.Требования к транспортированию и хранению
Требования к транспортированию и хранению не предъявляются.
4.8.Специальные требования
Специальные требования к программе не предъявляются.


5.Требования к программной документации
5.1.Предварительный состав программной документации
Состав программной документации должен включать в себя:
1)техническое задание;
2)спецификация;
3)текст программы;
4)описание программы;
5)программу и методики испытаний;
6)пояснительную записку;
7)ведомость эксплуатационных документов;
8)формуляр;
9)описание применения;
10)руководство системного программиста;
11)руководство программиста;
12)руководство оператора.
5.2.Специальные требования к программной документации
Специальные требования к программной документации не предъявляются.


6.Технико-экономические показатели
6.1.Ориентировочная экономическая эффективность
Ориентировочная экономическая эффективность не рассчитывается.
6.2.Предполагаемая годовая потребность
Предполагаемая годовая потребность не рассчитывается.
6.3.Экономические преимущества разработки
Экономические преимущества разработки не рассчитываются.


7.Стадии и этапы разработки
7.1.Стадии разработки
Разработка должна быть проведена в три стадии:
1)разработка технического задания;
2)рабочее проектирование;
3)внедрение.
7.2.Этапы разработки
На стадии разработки технического задания должен быть выполнен этап разработки, согласования и утверждения между Заказчиком и Исполнителем настоящего технического задания.
На стадии рабочего проектирования должны быть выполнены следующие этапы работ:
1)разработка программы;
2)разработка программной документации;
3)испытания программы.
На стадии внедрения должен быть выполнен этап разработки – подготовка и передача программы.
7.3.Содержание работ по этапам
На этапе разработки технического задания должны быть выполнены следующие виды работ:
1)постановка задачи;
2)определение и уточнение требований к техническим средствам;
3)определение требований к программе;
4)определение стадий, этапов и сроков разработки программы и документации на неё;
5)выбор языков программирования;
6)согласование и утверждение технического задания.
На этапе разработки программы должна быть выполнена работа по программированию и отладке программы.
На этапе разработки программной документации должна быть выполнена разработка программных документов в соответствии с требованиями ГОСТ 19. 101-77 и требованием п. «Предварительный состав программной документации» настоящего технического задания.
На этапе испытаний программы должны быть выполнены следующие виды работ:
1)разработка, согласование и утверждение программы и методики испытаний;
2)проведение приемо-сдаточных испытаний;
3)корректировка программы и программной документации по результатам испытаний.
На этапе подготовки и передачи программы должна быть выполнена работа по подготовке и передаче программы и программной документации в эксплуатацию на объектах Заказчика.

8.Порядок контроля и приемки
8.1.Виды испытаний
Приемо-сдаточные испытания программы должны проводиться согласно разработанной Исполнителем и согласованной Заказчиком «Программы и методики испытаний».
Ход проведения приемо-сдаточных испытаний документируется Заказчиком и Исполнителем в Протоколе проведения испытаний.
8.2.Общие требования к приемке работы
После проведения испытаний в полном объеме, на основании «Протокола испытаний» утверждают «Свидетельство о приемке» и производят запись в программном документе «Формуляр».

# 🐍 30 днів з Python 

| № дня |                                                  Теми                                                   |
|-------|:-------------------------------------------------------------------------------------------------------:|
| 01    |                                          [Вступ](./readme.md)                                           |
| 02    | [Variables, Built-in Functions](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md) |
| 03    |                            [Operators](../03_Day_Operators/03_operators.md)                             |
| 04    |                               [Strings](../04_Day_Strings/04_strings.md)                                |
| 05    |                                  [Lists](../05_Day_Lists/05_lists.md)                                   |
| 06    |                                 [Tuples](../06_Day_Tuples/06_tuples.md)                                 |
| 07    |                                    [Sets](../07_Day_Sets/07_sets.md)                                    |
| 08    |                        [Dictionaries](../08_Day_Dictionaries/08_dictionaries.md)                        |
| 09    |                        [Conditionals](../09_Day_Conditionals/09_conditionals.md)                        |
| 10    |                                  [Loops](../10_Day_Loops/10_loops.md)                                   |
| 11    |                            [Functions](../11_Day_Functions/11_functions.md)                             |
| 12    |                               [Modules](../12_Day_Modules/12_modules.md)                                |
| 13    |               [List Comprehension](../13_Day_List_comprehension/13_list_comprehension.md)               |
| 14    |         [Higher Order Functions](../14_Day_Higher_order_functions/14_higher_order_functions.md)         |     
| 15    |               [Python Type Errors](../15_Day_Python_type_errors/15_python_type_errors.md)               | 
| 16    |                  [Python Date time](../16_Day_Python_date_time/16_python_datetime.md)                   |     
| 17    |               [Exception Handling](../17_Day_Exception_handling/17_exception_handling.md)               |    
| 18    |             [Regular Expressions](../18_Day_Regular_expressions/18_regular_expressions.md)              |    
| 19    |                      [File Handling](../19_Day_File_handling/19_file_handling.md)                       |
| 20    |         [Python Package Manager](../20_Day_Python_package_manager/20_python_package_manager.md)         |
| 21    |             [Classes and Objects](../21_Day_Classes_and_objects/21_classes_and_objects.md)              |
| 22    |                        [Web Scraping](../22_Day_Web_scraping/22_web_scraping.md)                        |
| 23    |             [Virtual Environment](../23_Day_Virtual_environment/23_virtual_environment.md)              |
| 24    |                           [Statistics](../24_Day_Statistics/24_statistics.md)                           |
| 25    |                                 [Pandas](../25_Day_Pandas/25_pandas.md)                                 |
| 26    |                           [Python web](../26_Day_Python_web/26_python_web.md)                           |
| 27    |             [Python with MongoDB](../27_Day_Python_with_mongodb/27_python_with_mongodb.md)              |
| 28    |                                     [API](../28_Day_API/28_API.md)                                      |
| 29    |                        [Building API](../29_Day_Building_API/29_building_API.md)                        |
| 30    |                         [Conclusions](../30_Day_Conclusions/30_conclusions.md)                          |

🧡🧡🧡 ЩАСЛИВОГО ПРОГРАМУВАННЯ 🧡🧡🧡

<div>
<small>Підтримайте <strong>автора</strong>, щобм він створював більше навчальних матеріалів</small> <br />  
<a href = "https://www.paypal.me/asabeneh"><img src='../images/paypal_lg.png' alt='Paypal Logo' style="width:10%"/></a>
</div>

<div align="center">
  <h1> 30 днів Python: День 1 - Вступ</h1>  
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social" alt="">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

  <sub>Автор:
  <a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
  <small> Друге видання: Липень, 2021</small>
  </sub>
</div>


[День 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)

![30 днів з Python](../images/30DaysOfPython_banner3@2x.png)

- [🐍 30 днів Python](#-30-days-of-python)
- [📘 День 1](#-день-1)
  - [Ласкаво просимо](#ласкаво-просимо)
  - [Вступ](#вступ)
  - [Чому Python ?](#чому-python-)
  - [Налаштування середовища](#налаштування-середовища)
    - [Установлення Python](#установлення-python)
    - [Оболонка Python](#оболонка-python)
    - [Установлення Visual Studio Code](#установлення-visual-studio-code)
      - [Як використовувати Visual studio code](#як-використовувати-visual-studio-code)
  - [Початковий Python](#початковий-python)
    - [Синтаксис у Python](#синтаксис-у-python)
    - [Відступи у Python](#відступи-у-python)
    - [Коментарі](#коментарі)
    - [Типи даних](#типи-даних)
      - [Number (числовий)](#number--число-)
      - [String (рядок)](#string--рядок-)
      - [Booleans (логічний двійковий)](#booleans--логічний-тип-даних-)
      - [List (список)](#list--список-)
      - [Dictionary (словник)](#dictionary--словник-)
      - [Tuple (кортеж)](#tuple--кортеж-)
      - [Set (набір)](#set--набір-)
    - [Перевірка типів даних](#перевірка-типів-даних)
    - [Файл Python](#файл-python)
  - [💻 Вправи - День 1](#-вправи---день-1)
    - [Вправи: Рівень 1](#вправи--рівень-1)
    - [Вправи: Рівень 2](#вправи--рівень-2)
    - [Вправи: Рівень 3](#вправи--рівень-3)

# 📘 День 1

## Ласкаво просимо

**Вітаємо** з прийняттям рішення про участь у 30-денному випробуванні з програмування на Python _(30DaysOfPython challenge). У цьому випробуванні ви дізнаєтеся все, що вам потрібно для того, щоб стати програмістом на python, і всю концепцію програмування. У кінці цього випробування ви отримаєте сертифікат про проходження випробування з програмування _30DaysOfPython_.

Якщо ви бажаєте активно долучитися до випробуванні, ви можете приєднатися до групи у Telegram [30DaysOfPython challenge](https://t.me/ThirtyDaysOfPython).  

## Вступ

Python - це мова програмування високого рівня для програмування загального призначення. Це об'єктноорієнтована мова програмування з відкритим вихідним кодом, що інтерпретується. Python була створена голландським програмістом Гвідо ван Россумом. Назва мови програмування Python походить від британського скетч-комедійного серіалу "Летючий цирк Монті Пайтона". Перша версія була випущена 20 лютого 1991 року. Це 30-денне випробування з Python допоможе вам крок за кроком вивчити останню версію Python, Python 3. Теми розбиті на 30 днів, де кожен день містить кілька тем з простими для розуміння поясненнями, реальними прикладами, безліччю практичних вправ і проектів.

Це випробування призначене для початківців та професіоналів, які хочуть вивчити мову програмування Python. На проходження випробування може знадобитися від 30 до 100 днів, люди, які беруть активну участь у телеграм-групі, мають високу ймовірність завершити випробування.
Якщо ви навчаєтесь з використанням візуальних засобів або віддаєте перевагу відео, ви можете почати з цього [відео з Python для абсолютних новачків (англійською)](https://www.youtube.com/watch?v=11OYpBrhdyM).

## Чому Python ?

Це мова програмування, яка дуже близька до людської мови, і тому її легко вивчати та використовувати.
Python використовується різними галузями та компаніями (включаючи Google). Її використовують для розробки вебзастосунків, настільних застосунків, системного адміністрування та бібліотек машинного навчання. Python дуже популярна мова у спільноті, що займається наукою про дані та машинним навчанням. Сподіваюся, цього достатньо, щоби переконати вас почати вивчати Python. Python поглинає світ, а ви вбиваєте його до того, як він з'їсть вас.

## Налаштування середовища

### Установлення Python

Для запуску скрипту на Python, вам потрібно встановити Python. Нумо [завантажимо](https://www.python.org/) Python.
Якщо ви є користувачем Windows. Натисніть кнопку, обведену червоним кольором.

[![установлення на Windows](../images/installing_on_windows.png)](https://www.python.org/)

Якщо ви є користувачем MacOS. Натисніть кнопку, обведену червоним кольором.

[![установлення на Windows](../images/installing_on_macOS.png)](https://www.python.org/)

Щоб перевірити, чи встановлено Python, напишіть наступну команду у терміналі вашого пристрою.

```shell
python --version
```

![Версія Python](../images/python_versio.png)

Як ви можете бачити з термінала, наразі я використовую версію _Python 3.7.5_. Ваша версія Python може відрізнятися від моєї, але вона має бути 3.6 або вище. Вам вдалося побачити версію Python? Чудова робота, Python встановлено на вашому комп'ютері. Перейдіть до наступного розділу.

### Оболонка Python

Python - це інтерпретована скриптова мова, тому її не потрібно компілювати. Це означає, що вона виконує код рядок за рядком. Python постачається з _Python Shell (Python Interactive Shell)_. Вона використовується для виконання однієї команди Python і отримання результату.

Python Shell чекає на код Python від користувача. Коли ви вводите код, вона інтерпретує його і показує результат у наступному рядку.
Відкрийте термінал або командний рядок (cmd) і напишіть:

```shell
python
```

![Скриптова оболонка Python](../images/opening_python_shell.png)

Відкриється інтерактивна оболонка Python, яка чекає на написання коду на Python (скрипт Python). Ви напишете свій скрипт Python поруч з цими символами >>>, а потім натиснете Enter.
Гайда напишемо наш перший скрипт у скриптовій оболонці Python.

![Python script on Python shell](../images/adding_on_python_shell.png)

Чудово, ви написали свій перший Python-скрипт в інтерактивній оболонці Python. Як закрити інтерактивну оболонку Python?
Щоби закрити оболонку, поруч з цим символом >> напишіть команду **exit()** і натисніть Enter.

![Вихід з оболонки Python](../images/exit_from_shell.png)

Тепер ви знаєте, як відкрити інтерактивну оболонку Python і як вийти з неї.

Python дасть вам результати, якщо ви напишете скрипти, які розуміє Python, якщо ні - він поверне помилки. Зробімо навмисну помилку і подивимося, що поверне Python.

![Неправильний синтаксис](../images/invalid_syntax_error.png)

Як ви можете бачити з повернутої помилки, Python настільки розумний, що знає, якої помилки ми припустилися і яка була _ Syntax Error: invalid syntax (Синтаксична помилка: невірний синтаксис)_. Використання x як множника у Python є синтаксичною помилкою, оскільки (x) не є допустимим синтаксисом у Python. Замість (**x**) ми використовуємо зірочку (*) для множення. Повернута помилка чітко показує, що потрібно виправити.

Процес виявлення та усунення помилок у програмі називається *зневадженням (англ. debugging)*. Гайда розберемось з помилками, підставивши * замість **x**.

![Виправлення синтаксичної помилки](../images/fixing_syntax_error.png)

Наша помилка була виправлена, код запустився і ми отримали очікуваний результат. Як програміст, ви будете бачити подібні помилки щодня. Корисно знати, як їх зневаджувати. Щоб добре зневаджувати, ви повинні розуміти, з якими типами помилок ви стикаєтесь. Деякі з помилок Python, з якими ви можете зіткнутися:  *SyntaxError*, *IndexError*, *NameError*, *ModuleNotFoundError*, *KeyError*, *ImportError*, *AttributeError*, *TypeError*, *ValueError*, *ZeroDivisionError* тощо. Ми побачимо більше про різні типи **_помилок_** у Python у наступних розділах.

Попрактикуймось у використанні інтерактивної оболонки Python. Перейдіть до свого термінала або командного рядка і напишіть слово **python**.

![Скриптова оболонка Python](../images/opening_python_shell.png)

Відкрито інтерактивну оболонку Python. Виконаємо деякі базові математичні операції (додавання, віднімання, множення, ділення, піднесення до степеня, показник степеня).

Перш ніж писати код на Python, спочатку зробімо деякі розрахунки:

- 2 + 3 = 5
- 3 - 2 = 1
- 3 \* 2 = 6
- 3 / 2 = 1.5
- 3 ^ 2 = 3 x 3 = 9

У Python ми маємо наступні додаткові операції:

- 3 % 2 = 1 => що означає знаходження залишку
- 3 // 2 = 1 => що означає видалення залишку

Змінимо наведені вище математичні вирази на код Python. Відкриємо оболонку Python і напишемо коментар на самому початку оболонки.

_Коментар_ - це частина коду, яка не виконується Python. Таким чином, ми можемо залишити деякий текст у нашому коді, щоби зробити його більш читабельним. Python не виконує частину коментаря. Коментар у Python починається з символу hash(#).
Ось як можна написати коментар у Python

```shell
 # comment starts with hash (коментарі починаються з решітки)
 # this is a Python comment, because it starts with a (#) symbol (це коментар Python, оскільки він починається з символу (#))
```

![Математика у Python Shell](../images/maths_on_python_shell.png)

Перш ніж ми перейдемо до наступного розділу, попрактикуймось в інтерактивній оболонці Python. Закрийте відкриту оболонку, написавши у ній _exit()_, і знову відкрийте її, щоб попрактикуватися у написанні тексту в оболонці Python.

![Написання рядка Python Shell](../images/writing_string_on_shell.png)

### Установлення Visual Studio Code

Інтерактивна оболонка Python добре підходить для тестування невеликих скриптових кодів, але вона не підійде для великого проєкту. У реальному робочому середовищі розробники використовують різні редактори коду для написання коду. У цьому 30-денному випробуванні з програмування на Python ми будемо використовувати Visual Studio Code. Visual Studio Code - це дуже популярний текстовий редактор з відкритим вихідним кодом. Я є прихильником vscode і рекомендую [завантажити](https://code.visualstudio.com/) Visual Studio Code, але якщо ви віддаєте перевагу іншим редакторам, не соромтеся користуватися тим, що у вас є.

[![Visual Studio Code](../images/vscode.png)](https://code.visualstudio.com/)

Якщо ви встановили Visual Studio Code, подивімося, як ним користуватися.
Якщо ви віддаєте перевагу відео, ви можете слідувати за цим [відео-посібнком](https://www.youtube.com/watch?v=bn7Cx4z-vSo)

#### Як використовувати Visual Studio Code

Відкрийте Visual Studio Code, двічі натиснувши на іконці Visual Studio Code. Коли ви відкриєте її, ви отримаєте такий інтерфейс. Спробуйте взаємодіяти з підписаними іконками.

![Visual Studio Code](../images/vscode_ui.png)

Створіть теку з назваю 30DaysOfPython на вашому робочому столі. Потім відкрийте її за допомогою Visual Studio Code.

![Відкриття проєкту у Visual studio](../images/how_to_open_project_on_vscode.png)

![Відкриття проєкту](../images/opening_project.png)

Відкривши його, ви побачите ярлики для створення файлів і тек всередині каталогу проєкту 30DaysOfPython. Як ви можете бачити нижче, я створив перший файл, helloworld.py. Ви можете зробити те ж саме.

![Створення Python-файлу](../images/helloworld.png)

Після довгого дня кодування ви хочете закрити редактор коду, чи не так? Саме так ви закриєте відкритий проєкт.

![Закриття проєкту](../images/closing_opened_project.png)

Вітаємо, ви завершили налаштування середовища розробки. Почнімо кодування.

## Початковий Python

### Синтаксис у Python

Скрипт на Python можна написати в інтерактивній оболонці Python або в редакторі коду. Файл Python має розширення .py.

### Відступи у Python

Відступ - це пробіл у тексті. Відступ у багатьох мовах використовується для покращення читабельності коду, однак у Python відступ використовується для створення блоків коду. В інших мовах програмування для створення блоків коду замість відступів використовуються фігурні дужки. Однією з поширених помилок при написанні коду на Python є неправильний відступ.

![Помилка з відступом](../images/indentation.png)

### Коментарі

Коментарі дуже важливі для того, щоби зробити код більш читабельним і залишати зауваження в нашому коді. Python не виконує коментовані частини нашого коду.
Будь-який текст, що починається з решітки(#) у Python, є коментарем.

**Приклад: однорядковий коментар**

```shell
    # This is the first comment (це перший коментар)
    # This is the second comment (це другий коментар)
    # Python is eating the world (Python поглинає світ)
```

**Приклад: багаторядковий коментар**

Потрійні лапки можна використовувати для багаторядкового коментаря, якщо вони не присвоєні змінній

```shell
"""This is multiline comment (це багаторядковий коментар)
multiline comment takes multiple lines. (багаторядковий коментар займає багато рядків)
Python is eating the world (Python поглинає світ)
"""
```

### Типи даних
У Python існує декілька типів даних. Почнімо з найпоширеніших. Детально різні типи даних будуть розглянуті в інших розділах. Наразі, давайте просто пройдемося по різних типах даних і познайомимося з ними. Вам не обов'язково мати чітке розуміння зараз.

#### Number (число)

- Integer (цілі числа): Integer(негативні, нуль та позитивні) числа
    Приклад:
  ... -3, -2, -1, 0, 1, 2, 3 ...
- Float (числа з рухомою комою): десяткове число
    Приклад:
    ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- Complex numbers (уявні числа)
    Приклад:
    1 + j, 2 + 4j

#### String (рядок)

Набір з одного або більше символів, взятих в одинарні або подвійні лапки. Якщо рядок складається з більш ніж одного речення, ми використовуємо потрійні лапки.

**Приклад:**

```py
'Asabeneh'
'Finland'
'Python'
'I love teaching'
'I hope you are enjoying the first day of 30DaysOfPython Challenge'
```

#### Booleans (логічний тип даних)

Логічний тип даних - це значення True або False. T і F завжди повинні бути великими літерами.

**Приклад:**

```python
    True  #  Чи увімкнене світло? Якщо увімкнене, то значення True (істинне)
    False # Чи увімкнене світло? Якщо вимкнене, то значення False (хибне)
```

#### List (список)

Список у Python - це впорядкована колекція, яка дозволяє зберігати елементи різних типів даних. Список схожий на масив у JavaScript.

**Приклад:**

```py
[0, 1, 2, 3, 4, 5]  # всі мають однаковий тип даних - список чисел
['Banana', 'Orange', 'Mango', 'Avocado'] # однакові типи даних - список рядків (фруктів)
['Finland','Estonia', 'Sweden','Norway'] # однакові типи даних - список рядків (країн)
['Banana', 10, False, 9.81] # різні типи даних у списку - string (рядок), integer (цілі числа), boolean (логічний) та float (числа з рухомою комою)
```

#### Dictionary (словник)

Об'єкт словника Python - це невпорядкований набір даних у форматі пари ключ-значення. 

**Приклад:**

```py
{
'first_name':'Asabeneh',
'last_name':'Yetayeh',
'country':'Finland', 
'age':250, 
'is_married':True,
'skills':['JS', 'React', 'Node', 'Python']
}
```

#### Tuple (кортеж)

Кортеж - це впорядкована колекція різних типів даних, таких як список, але кортежі не можуть бути змінені після їх створення. Вони є незмінними.

**Приклад:**

```py
('Asabeneh', 'Pawel', 'Brook', 'Abraham', 'Lidiya') # Імена
```

```py
('Earth', 'Jupiter', 'Neptune', 'Mars', 'Venus', 'Saturn', 'Uranus', 'Mercury') # планети
```

#### Set (набір)

Набір - це набір типів даних, подібних до списку та кортежу. На відміну від списку та кортежу, множина не є впорядкованою колекцією елементів. Як і в математиці, множина у Python зберігає лише унікальні елементи.

У наступних розділах ми детально розглянемо кожен тип даних у Python.

**Приклад:**

```py
{2, 4, 3, 5}
{3.14, 9.81, 2.7} # порядок у наборі не важливий
```

### Перевірка типів даних

Для перевірки типу даних певних даних/змінних ми використовуємо функцію **type**. У наведеному нижче терміналі ви побачите різні типи даних Python:

![Перевірка типів даних](../images/checking_data_types.png)

### Файл Python

По-перше, відкрийте свою теку з проєктому 30DaysOfPython. Якщо ви не маєте цієї теки, то створіть її з назвою 30DaysOfPython. Усередині цієї теки, створіть файл з назвою helloworld.py. Тепер зробімо те, що ми робили в інтерактивній оболонці Python, використовуючи Visual Studio Code.

Інтерактивна оболонка Python виконувала друк без використання **print**, але у коді візуальної студії, щоб побачити результат, ми повинні використати вбудовану функцію *print()*. Вбудована функція *print()* приймає один або декілька аргументів у вигляді *print('аргумент1', 'аргумент2', 'аргумент3')*. Дивіться приклади нижче.

**Приклад:**

Назва файлу: helloworld.py

```py
# День 1 з випробування 30DaysOfPython

print(2 + 3)             # додавання(+)
print(3 - 1)             # віднімання(-)
print(2 * 3)             # множення(*)
print(3 / 2)             # ділення(/)
print(3 ** 2)            # взяття в ступіні(**)
print(3 % 2)             # взяття залишку з ділення(%)
print(3 // 2)            # взяття цілого числа з ділення(//)

# Перевірка типів даних
print(type(10))          # Int (цілочисельний)
print(type(3.14))        # Float (числа з рухомою комою)
print(type(1 + 3j))      # Complex number (уявне число)
print(type('Asabeneh'))  # String (рядок)
print(type([1, 2, 3]))   # List (список)
print(type({'name':'Asabeneh'})) # Dictionary (словник)
print(type({9.8, 3.14, 2.7}))    # Set (набір)
print(type((9.8, 3.14, 2.7)))    # Tuple (кортеж)
```

Для запуску Python-файл перевірте зображення нижче. Ви можете запустити файл Python, натиснувши зелену кнопку на Visual Studio Code або ввівши *python helloworld.py* в терміналі.

![Запуск Python-скрипту](../images/running_python_script.png)

🌕  Ви дивовижні. Ви щойно виконали завдання першого дня і вже на шляху до величі. Тепер виконайте кілька вправ для мозку та м'язів.

## 💻 Вправи - день 1

### Вправи: рівень 1

1. Перевірте версію Python, яку ви використовуєте
2. Відкрийте інтерактивну оболонку Python і виконайте наступні дії. Параметрами є числа 3 та 4.
   - додавання(+)
   - віднімання(-)
   - множення(\*)
   - залишок від числа(%)
   - ділення(/)
   - показник(\*\*)
   - ціла частина від числа(//)
3. Напишіть рядки в інтерактивній оболонці Python. Рядки подано наступним чином:
   - Ваше ім'я
   - Ваше прізвище
   - Ваша країна
   - Я насолоджуюся 30 днями з Python
4. Перевірте типи наступних даних:
   - 10
   - 9.8
   - 3.14
   - 4 - 4j
   - ['Asabeneh', 'Python', 'Finland']
   - Ваше ім'я
   - Ваше прізвище
   - Ваша країна

### Вправи: рівень 2

1. Створіть теку з назвою day_1 всередині теки 30DaysOfPython. Усередині теки day_1, створити Python-файл helloworld.py і повторіть питання 1, 2, 3 та 4. Пам'ятайте використовувати _print()_, коли ви працюєте над Python-файлом. Перейдіть до теки, куди ви зберегли файл, і запустіть його.

### Вправи: рівень 3

1. Напишіть приклад для різних типів даних Python, як-от Number(Integer, Float, Complex), String, Boolean, List, Tuple, Set та Dictionary.
2. Знайдіть [Евклідову відстань](https://uk.wikipedia.org/wiki/%D0%95%D0%B2%D0%BA%D0%BB%D1%96%D0%B4%D0%BE%D0%B2%D0%B0_%D0%B2%D1%96%D0%B4%D1%81%D1%82%D0%B0%D0%BD%D1%8C) між (2, 3) та (10, 8)

🎉 ВІТАННЯ ! 🎉

[День 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)
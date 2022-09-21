# Урок 21
Для начала работы скопируйте репозиторий на локальную машину:
c помощью команды в терминале

`https://github.com/skypro-008/lesson21-and-tests.git`

Откройте склонированный репозиторий в PyCharm.

### Cоздайте виртуальное окружение:

#### Простой вариант:
Pycharm может предложить вам сделать это после того, как вы откроете папку с проектом.
В этом случае после открытия папки с проектом в PyCharm
Появляется всплывающее окно, Creating virtuan envrironment c тремя полями.
В первом поле выбираем размещение папки с вирутальным окружением, как правило это папка venv
в корне проекта
Во втором поле выбираем устанавливаемый интерпритатор по умолчанию (можно оставить без изменений)
В 3 поле выбираем список зависимостей (должен быть выбран фаил requirements.txt, находящийся в корне папки проекта)

#### Если этого не произошло, тогда следует выполнить следующие действия вручную:
#### Установка виртуального окружения:
1. Во вкладке File выберите пункт Settings
2. В открывшемся окне, с левой стороны найдите вкладку с именем
вашего репозитория (Project: lesson21-and-tests)
3. В выбранной вкладке откройте настройку Python Interpreter
4. В открывшейся настройке кликните на значек ⚙ (шестеренки) 
расположенный сверху справа и выберите опцию Add
5. В открывшемся окне слева выберите Virtualenv Environment, 
а справа выберите New Environment и нажмите ОК

#### Установка зависимостей:
Для этого можно воспользоваться графическим интерфейсом PyCharm,
который вам предложит сделать это как только вы откроете файл с заданием.

Или же вы можете сделать это вручную, выполнив следующую команду в терминале:
`pip install -r requirements.txt`

#### Настройка виртуального окружения завершена!

### Порядок выполнения заданий

- part2/store
- part2/magic
- part2/wallet

Задачи описаны в комментариях в файле main.py
В текущих заданиях вы будете учиться основам ООП в Python, и применять его для
решения простых задач. После того, как Вы выполнили  задание, 
попробуйте запустить фаил main.py.
Вы можете это сделать, кликнув на него правой кнопкой мыши в окне проекта.


*Обращаем ваше внимание, что для каждого задания предусмотрены свои тесты
и запускать нужно именно те тесты, которые находятся в папке с заданием*


*При этом в текущем уроке к сожалению при запуске тестов в PyCharm может возникнуть ошибка
связанная с настройками Pycharm (здесь нам приходися одновременно использоваьь несколько библиотек 
для тестирования). Если Наши тесты у Вас не работают просим Вас
запускать их через терминал, для этого*:
1. В терминале Pycharm переходим в папку с заданием.
2. Запускаем тесты командой python -m unittest 

*Если не работают тесты pytest, то также через терминал
переходите в папку с заданием и выполните команду pytest*

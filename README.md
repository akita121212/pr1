# README для Планировщика задач

## Описание
Планировщик задач - это простое приложение для управления задачами, написанное на Python с использованием библиотеки Tkinter. Оно позволяет добавлять, завершать и удалять задачи, а также очищать список выполненных задач. Все задачи сохраняются в JSON-файле для постоянного хранения.
## Требования
- Python 3.x
- Библиотека Tkinter (обычно поставляется с Python)
- Нет дополнительных библиотек, необходимых для работы
## Установка
1. Скачайте или клонируйте репозиторий на свой компьютер.
2. Убедитесь, что у вас установлен Python 3.x.
3. Запустите файл tasks.py с помощью следующей команды:
   
   python tasks.py
   ## Использование
- После запуска вы увидите окно приложения.
- Добавить задачу: Нажмите кнопку "Добавить задачу", чтобы ввести название новой задачи.
- Завершить задачу: Выберите задачу из списка и нажмите «Завершить задачу», чтобы пометить её как выполненную.
- Удалить задачу: Выберите задачу и нажмите «Удалить задачу», чтобы удалить её из списка.
- Очистить выполненные задачи: Нажмите на кнопку «Очистить выполненные задачи», чтобы удалить все завершенные задачи из списка.
## Структура кода
Основные компоненты кода:
- load_tasks(): Функция для загрузки задач из JSON-файла.
- save_tasks(tasks): Функция для сохранения задач в JSON-файл.
- Класс TaskPlannerApp: Основной класс, который обрабатывает интерфейс и логику приложения.
  - __init__(self, root): Инициализация интерфейса.
  - load_tasks_into_tree(self): Загружает задачи в таблицу.
  - add_task(self): Добавляет новую задачу.
  - complete_task(self): Помечает задачу как выполненную.
  - delete_task(self): Удаляет выбранную задачу.
  - clear_completed_tasks(self): Удаляет все выполненные задачи.
## Запуск приложения
Для запуска приложения убедитесь, что вы находитесь в каталоге, где расположен файл tasks.py, и запустите следующую команду в терминале:
python tasks.py

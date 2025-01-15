NoteApp
NoteApp — это приложение для создания и управления заметками с поддержкой категорий и хранения данных в формате JSON. Приложение использует Tkinter для создания графического интерфейса, позволяя пользователю легко добавлять, редактировать и удалять заметки.

Функции
Добавление заметки: Создавайте новые заметки с указанием названия, категории и содержания.
Редактирование заметки: Изменяйте название, категорию и содержание уже существующих заметок.
Удаление заметки: Удаляйте выбранные заметки.
Категории заметок: Каждая заметка может быть отнесена к одной из категорий, таких как Работа, Дом, Здоровье, Люди, Документы, Финансы и Разное.
Сохранение и загрузка данных: Все данные сохраняются в файл на вашем устройстве в формате JSON, что позволяет восстанавливать проект после перезагрузки приложения.
Простой и интуитивно понятный интерфейс: Управление заметками через удобный список и панель инструментов.
Структура кода
NoteCategory (Enum): Перечисление, определяющее категории заметок.
Note: Класс для представления заметки, включающий поля для названия, категории, содержания и времени создания/обновления.
Project: Класс для управления списком заметок.
ProjectManager: Класс для сохранения и загрузки проекта в/из файла.
NoteApp: Главный класс приложения, который инициализирует графический интерфейс и связывает все функциональные части программы.
Как запустить
Установите Python на вашем компьютере.
Убедитесь, что у вас установлен пакет Tkinter (обычно он уже установлен с Python).
Скачайте или склонируйте репозиторий.
Запустите файл app.py:
bash
Копировать код
python app.py
Использование
Добавление заметки: Нажмите "Add Note", чтобы открыть окно для создания новой заметки.
Редактирование заметки: Выберите заметку из списка и нажмите "Edit Note".
Удаление заметки: Выберите заметку и нажмите "Remove Note", чтобы удалить её.
Все изменения сохраняются автоматически в файл и восстанавливаются при следующем запуске приложения.
Зависимости
Python 3.x
Tkinter (включен в стандартную библиотеку Python)

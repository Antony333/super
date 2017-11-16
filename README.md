**Правила оформления кода:**

1. Где не нужны объекты - класс не создаем, достаточно функций.

2. Возвращаемые значения: response, model (где есть).

3. Сравниваем объект сгенерированной модели и объект модели из get-запроса.

4. Не хардкодим в методах api url и статус-коды, а берем их из конфига.

5. Если есть метод во фреймворке для вашей задачи - используем его, а не нативный.

6. Работа с данными в кейворде не должна быть скрыта, т.е. должны быть входные параметры.

7. Методы называем в стиле lower_case_with_underscores.

8. Модули именуются как и классы в стиле CapWords. Называем везде.

9. Имена классов называем в стиле CapWords.

10. Файлы со степами должны иметь постфикс steps, а с моделями - model. Например: calendar_steps, events_model.

11. Пользуемся форматированием в PyCharm, а также pylint, flake8 и т.д.


**Чтобы в логе были**
1. Шаги
2. Детали по шагам:
значения переменных на каком то шаге
3. Детали по запросам и ответам: headers, content, url (на уровне call builders)
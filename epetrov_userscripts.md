# Егор Петров - "Дневник садовода - ДС- 1"
# Пользовательские сценарии

### Группа: 10 - C - 4
### Электронная почта: marshalbulka@gmail.com
### VK: https://vk.com/id1043068290

### [ Сценарий 1 - Регистрация пользователя ]

1. Пользователь вводит логин, с которым он будет заходить в систему
2. Пользователь вводит пароль, с которым он будет заходить в систему
3. Пользователь вводит адрес электронной почты, который будет использоваться в системе
4. Если выбранный логин уже существует в системе, то пользователю сообщается об этом и предлагается придумать новый логин
5. Если введённый адрес электронной почты не соответствует формату, то система выводит сообщение об ошибке и просит ввести адрес ещё раз
6. Если все введённые данные соответствуют требованиям регистрации, то система отправляет на почту письмо для подтверждения почты
7. После подтверждения имейла система приветствует пользователя и сообщает о готовности к использовании

Сценарий 2: Планирование периодической обработки  
1. Пользователь в календаре выбирает 15 апреля → нажимает "+"  
2. Выбирает сад "Моя дача в Рощино" → растение "Сосна обыкновенная"  
3. В поле "Препарат" вводит "Кли" → система предлагает "Клипер"  
4. Выбирает тип обработки: "Инсектицид (короед)"  
5. Нажимает "Повторить" → выбирает интервалы: 30, 60, 90 дней  
6. Активирует "Напомнить" → выбирает "За 2 дня до события"  
7. Добавляет второе растение "Ель голубая" с теми же параметрами  
8. Нажимает "Сохранить" → в календаре появляются задачи на 15.04, 15.05, 14.06, 13.07  

---

Сценарий 3: Отслеживание выполненных обработок  
1. 10 июня пользователь получает уведомление: "Завтра обработка роз Биотлином"  
2. Открывает приложение 11 июня → видит задачу "Розы: Биотлин (тля)"  
3. Нажимает на задачу → выбирает "Отметить выполненным"  
4. Вводит комментарий: "Обработал 20 кустов, расход 3 л"  
5. Прикрепляет фото обработанных роз  
6. Переходит в карточку растения "Розы" → вкладка "История"  
7. Видит запись: "11.06.2024: Биотлин. Фото. Коммент: 20 кустов..."  
8. Следующая задача автоматически переносится на 16 июня (повтор через 5 дней)  

---

Сценарий 4: Экспорт/импорт данных сада  
1. В разделе "Мои сады" пользователь нажимает ⋮ рядом с "Моя дача в Рощино"  
2. Выбирает "Экспортировать сад" → формат CSV  
3. Система сохраняет файл Моя_дача_в_Рощино_20240616.csv  
4. Пользователь устанавливает приложение на планшет → логинится  
5. В "Мои сады" нажимает "Импортировать сад"  
6. Выбирает CSV-файл из облачного хранилища  
7. Подтверждает импорт: 2 сада, 8 растений, 15 запланированных обработок  
8. В календаре видны все перенесённые события  

---

Сценарий 5: Создание комплексного плана обработок  
1. Пользователь открывает карточку растения "Яблоня Антоновка"  
2. Переходит в "План обработок" → нажимает "+"  
3. Создает план "Защита от плодожорки":  
   - Препарат: "Лепидоцид"  
   - Первая обработка: 4 мая  
   - Периодичность: каждые 7 дней  
   - Количество: 4 обработки  
4. Добавляет второй этап плана:  
   - Препарат: "Бордоская смесь"  
   - Старт: 20 мая  
   - Периодичность: 14 дней  
5. Активирует автонапоминания за 1 день  
6. Сохраняет план → система создает 8 задач в календаре  
7. Проверяет расписание: 4,11,18,25 мая - Лепидоцид; 20 мая, 3,17 июня - Бордоская смесь  

---

Сценарий 6: Массовое добавление препаратов  
1. Пользователь выбирает 15 мая в календаре → "+"  
2. Выбирает сад → режим "Несколько растений"  
3. Отмечает: "Смородина чёрная", "Крыжовник", "Малина"  
4. В поле "Препараты" нажимает "Добавить" → вводит "Экофус" (новый)  
5. Заполняет свойства: тип "Удобрение", назначение "Листовая подкормка"  
6. Добавляет ещё два препарата из базы: "Циркон", "Феровит"  
7. Задаёт повторение через 10 дней  
8. Сохраняет → в календаре 15 мая: "3 растения: Экофус+Циркон+Феровит"  

---

Сценарий 7: Корректировка графика обработок  
1. Пользователь видит в календаре 4 мая задачу: "Яблоня: Лепидоцид"  
2. Нажимает на задачу → "Перенести"  
3. Выбирает новую дату: 6 мая (из-за прогноза дождя)  
4. Подтверждает "Перенести всю серию"  
5. Система автоматически сдвигает все 4 обработки на +2 дня  
6. Открывает "История изменений": видит запись "Перенос с 04.05 на 06.05"  
7. Проверяет новые даты: 6,13,20,27 мая  
8. Для следующей обработки получает уведомление 12 мая: "Напомнить за 1 день"  

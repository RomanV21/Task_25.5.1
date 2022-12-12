Практическое задание: 25.3.1 и 25.5.1 
Написать тест, который проверяет, что на странице: (https://petfriends.skillfactory.ru/my_pets) со списком питомцев пользователя:

1. Присутствуют все питомцы.
2. Хотя бы у половины питомцев есть фото.
3. У всех питомцев есть имя, возраст и порода.
4. У всех питомцев разные имена.
5. В списке нет повторяющихся питомцев. (Сложное задание).
6. В написанном тесте (проверка карточек питомцев) добавьте неявные ожидания всех элементов (фото, имя питомца, его возраст).
7. В написанном тесте (проверка таблицы питомцев) добавьте явные ожидания элементов страницы.


В директории /tests располагаются файлы с тестами

В файле conftest.py находятся 2 фикстуры:
Фикстура с драйвером и переходом на страницу авторизации
Фикстура для перехода на страницу мои питомцы

В файле settings.py находятся данные о емейле и пароле.
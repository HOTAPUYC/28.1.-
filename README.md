28.1.- Итоговый проект по автоматизации тестирования

Итоговый проект по автоматизации тестирования
В рамках выполнения дипломного проекта вам предстоит протестировать новый интерфейс авторизации в личном кабинете от заказчика Ростелеком Информационные Технологии. Вам предоставили требования к сайту, внимательно ознакомьтесь с ними перед началом работы. 

Требования по проекту представлены в документе  - Требования по проекту (.doc)
Объект тестирования: https://b2c.passport.rt.ru

Заказчик передал вам следующее задание:

Протестировать требования.
Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
Провести автоматизированное тестирование продукта (не менее 20 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.
Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов).

Тестирование личного кабинета Ростелеком - https://docs.google.com/spreadsheets/d/1Q4B1g63uDPtK367CUzYVEGN7WLbj35Uh/edit?usp=sharing&ouid=116361238025038691816&rtpof=true&sd=true

Для составления и написания тест-кейсов использовались такие техники тест-дизайна как: классы эквивалентности, анализ граничных значений, предугадывание ошибок.
Тестирование было осуществеленно как ручное, так и автоматизированное.
base.py - базовые классы, процедуры, функции и локаторы для автотестов
settings.py - регистрационные данные для позитивных тестов авторизации
autotest.py - собственно набор автотестов, нумерация соответствует номеру тест-кейса
запуск автотестов (драйвер в одной папке с тест-скриптом)

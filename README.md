# domashka
domashka 1
# Задание №1
# Давай представим, что мы пишем бэкенд
# для сайта ветеринарной клиники. Нам нужно написать программу,
# которая будет запрашивать у пользователя вид питомца,
# его возраст и кличку, а потом выведет все эти данные в одно предложение. Например:
# Это желторотый питон по кличке "Каа". Возраст: 34 года.
pitom=str(input("напиши вид питомца"))
vozr=str(input("введи его возраст"))
klich=str(input("введи имя питомца"))
print(f"Это {pitom} по кличке {klich}.Возраст: {vozr}")
# Задание №2

# А теперь мы с тобой напишем форму
# ввода ответа на тест по биологии для студентов.
# Он должен запрашивать по порядку этапы развития человека (проверим твое умение гуглить, что тоже очень важно для программиста. )
# и в конце вывести все стадии, разделенные знаком =>, что
# будет означать постепенный переход от одного к другому.
# В следующих уроках мы дополним эту форму до полноценного теста, который будет проверять
# правильность ответов, а пока - начнем с малого. Напоминаем, что разделить эти данные тебе
# поможет команда sep внутри команды print, например, чтобы разделить переменные знаком + нужно ввести:
# print(a1, a2, a3, sep='+')
# Подсказка: последняя стадия развития - Homo sapiens sapiens.


# дриопитек – рамапитек – австралопитек –
# человек умелый – человек прямоходящий – неандертальский человек (палеоантроп) – неоантроп (это уже человек современного типа
driop=str(input())
raam=str(input())
abstr=str(input())
chel_ym=str(input())
chel_prym=str(input())
neandertal=str(input())
neantrop=str(input())

print(driop,raam,abstr,chel_ym,neandertal,neantrop,sep="=>")

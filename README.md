# Предприятия общественного питания г.Москва

Суть проекта заключается в переобразовании датасета и небольшом его анализе.
Для этого используется датасет, который содержит данные о стационарных предприятиях общественного питания, расположенных в пределах установленных границ города Москвы. Данные обновляются ежеквартально и последний раз обновлялись 08.10.2024.

Источник: Портал открытых данных правительства Москвы. 

Ссылка на датасет: https://data.mos.ru/opendata/1903?pageSize=10&pageIndex=0&isDynamic=false&version=1&release=197

### Что содержит датасет?
- ID
- Name - название заведения
- IsNetObject - является ли заведение сетевым
- TypeObject - тип заведения
- AdmArea - в каком административном округе находится
- District - в каком районе находится
- Address - полный адрес заведения
- SeatsCount - сколько посадочных мест есть в заведении
- SocialPrivileges - есть ли какие-то социальные льготы в заведении
## Задачи проекта:
1. Создать словарь, в котором будет храниться информация о заведениях.
2. Узнать общее количество заведений общественного питания
3. Выяснить в каких административных округах больше (меньше) всего точек общественного питания
4. Выяснить каких типов заведений больше всего
5. Написать функцию, которая выдает информацию обо всех местах общественного питания в зависомости от района (т.е. вы вводите название района и получаете список заведений с информацией о них).
6. Написать функцию, которая выдает информацию о заведениях, при вводе названия.

## Автор проекта

Рыбакова Вита Александровна

НИУ ВШЭ, ФГиГТ, 2 курс, группа БГЕО232

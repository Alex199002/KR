# KR

Итоговая аттестациия. Практиическое задание
Задание
Необходимо организовать систему учета для питомника, в котором живут домашние и вьючные животные.

Используя команду cat в терминале операционной системы Linux, создать два фаи?ла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного фаи?ла. Переименовать фаи?л, дав ему новое имя (Друзья человека).

Создать директорию, переместить файл туда.

Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.

Установить и удалить deb-пакет с помощью dpkg.

Выложить историю команд в терминале ubuntu

Нарисовать диаграмму, в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные войдут: Лошади, верблюды и ослы).

В подключенном MySQL репозитории создать базу данных “Друзья человека”

Создать таблицы с иерархией из диаграммы в БД

Заполнить низкоуровневые таблицы именами(животных), командами которые они выполняют и датами рождения

Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой питомник на зимовку. Объединить таблицы лошади, и ослы в одну таблицу.

Создать новую таблицу “молодые животные” в которую попадут все животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью до месяца подсчитать возраст животных в новой таблице

Объединить все таблицы в одну, при этом сохраняя поля, указывающие на прошлую принадлежность к старым таблицам.

Создать класс с Инкапсуляцией методов и наследованием по диаграмме.

Написать программу, имитирующую работу реестра домашних животных. В программе должен быть реализован следующий функционал:

14.1 Завести новое животное

14.2 определять животное в правильный класс

14.3 увидеть список команд, которое выполняет животное

14.4 обучить животное новым командам

14.5 Реализовать навигацию по меню

Создаи?те класс Счетчик, у которого есть метод add(), увеличивающий? значение внутренней? int переменной? на 1 при нажатии “Завести новое животное” Сделайте так, чтобы с объектом такого типа можно было работать в блоке try-with-resources. Нужно бросить исключение, если работа с объектом типа счетчик была не в ресурсном try и/или ресурс остался открыт. Значение считать в ресурсе try, если при заведении животного заполнены все поля.

Итог
Используя команду cat в терминале операционной системы Linux, создать два фаи?ла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного фаи?ла. Переименовать фаи?л, дав ему новое имя (Друзья человека).

Выполнениие команды:

cat > "Домашние животные.txt"
cat > "Вьючные животные.txt"
cat "Домашние животные.txt" "Вьючные животные.txt" > "Друзья человека.txt"
cat "Друзья человека.txt"
Создать директорию, переместить файл туда.

Выполнениие команды:

mkdir > "Питомниик"
mv "Друзья человека.txt" /home/mv/Питомник
![image](https://github.com/Alex199002/KR/assets/139108344/512b5989-af0b-428e-b16e-1c6f4a766071)
Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.

Выполнениие команды:

wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb
sudo dpkg - i mysql-apt-config_0.8.24-1_all.deb
sudo apt-get update
sudo apt-get install mysql-workbbench-community
![image](https://github.com/Alex199002/KR/assets/139108344/7e5e0907-9cd7-4971-8067-54a81ba747b4)
![image](https://github.com/Alex199002/KR/assets/139108344/a24c1aca-429c-4e49-b4dd-11cbc4e09fa2)
![image](https://github.com/Alex199002/KR/assets/139108344/735d8609-e393-45d6-ba83-df66ccadbb60)
Установить и удалить deb-пакет с помощью dpkg.

Выполнениие команды:

wget http://archive.ubuntu.com/ubuntu/pool/universe/m/mc/mc_4.8.24-2ubuntu1_amd64.deb
sudo dpkg -i mc_4.8.27-1_amd64.deb
sudo apt install -f
mc
sudo dpkg -r mc
![image](https://github.com/Alex199002/KR/assets/139108344/9df29c6b-3830-4aad-97cb-ec1ccac0a8b9)
![image](https://github.com/Alex199002/KR/assets/139108344/e2fb5fb1-37ef-4d1c-a0d5-6a2eff854399)
![image](https://github.com/Alex199002/KR/assets/139108344/94912d25-e291-4cd5-bf3c-4c3c5aa184a4)
Выложить историю команд в терминале ubuntu
![image](https://github.com/Alex199002/KR/assets/139108344/099ddf00-3ca6-4073-ad88-72ffbfe2a812)
Нарисовать диаграмму, в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные войдут: Лошади, верблюды и ослы).

Диаграмма находится https://github.com/Alex199002/KR/blob/master/Diagram%20Class.drawio
12. Работа с Mysql

Отчет по пунктам 7-12 см.
15. Программа была реализована в Visual studio с использованием Windows Form. Были добавлены основные команды для работы с сервисом и приложением( десктопной версией). Добавление команды, изменение животного и удаление животного реализовано отдельной клавишей в главной форме и в контекстном меню. В конце был добавлен таймер для обновления формы раз в 5 сек.









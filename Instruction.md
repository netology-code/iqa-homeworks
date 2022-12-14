# JMeter
## Windows
1. Устанавливаем Java по [инструкции](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md).
 Обратите внимание, что инструкция по работе с терминалом есть в конце этой страницы, а версия Java должна быть 11, но не обязательно точно 11.0.5. 11.0.7 и другие, которые начинаются на 11, тоже подойдут.

**Если при установке или вводе команды Java version возникает ошибка в терминале, вам нужно скопировать её и поискать решение конкретной проблемы для вашей операционной системы в Google.**

2. Устанавливаем JMeter. Переходим на страницу https://jmeter.apache.org/download_jmeter.cgi.
3. Выбираем файл Binaries (zip или tgz) для загрузки, как показано на рисунке ниже.
<img width="519" alt="Screenshot at Mar 24 17-54-39" src="https://user-images.githubusercontent.com/43470121/112331545-0def4880-8cca-11eb-8643-803da1ae4647.png">

4. Распаковываем папку с JMeter в директорию без пробелов в имени (то есть точно не Program Files). Лучше создать специальную папку. Почитать о распаковке можно [здесь](https://open-file.ru/types/tgz) или [здесь](https://open-file.ru/types/zip). После распаковки будет примерно такой результат:
<img width="639" alt="Screenshot at Mar 24 17-55-52" src="https://user-images.githubusercontent.com/43470121/112331703-35461580-8cca-11eb-9056-07e59a46b1a7.png">

 - / bin : содержит файл сценария JMeter для запуска JMeter;
 - / docs : файлы документации JMeter;
 - / extras : дополнительные файлы, связанные с ant;
 - / lib / : содержит необходимую библиотеку Java для JMeter;
 - / lib / ext : содержит основные файлы JAR для JMeter и протоколы;
 - / lib / junit : библиотека JUnit, используемая для JMeter;
 - / printable_docs :
 
5. Запускаем файл /bin/jmeter.bat, чтобы запустить JMeter в режиме графического интерфейса. В некоторых системах он будет в интерфейсе без расширения, вам нужен пакетный файл.
<img width="649" alt="Screenshot at Mar 24 17-56-23" src="https://www.seleniumeasy.com/sites/default/files/pictures/jmeter/JMeter_batch_file.jpg">

<img width="649" alt="Screenshot at Mar 24 17-56-23" src="https://user-images.githubusercontent.com/43470121/112331773-4858e580-8cca-11eb-965e-ae3c023e2f3e.png">


 
## Для macOS


1. Устанавливаем Java по [инструкции](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md).
2. Устанавливаем JMeter. Для этого переходим на [страницу для загрузки](https://jmeter.apache.org/download_jmeter.cgi).
3. Выбираем файл Binaries (zip или tgz) для загрузки, как показано на рисунке ниже.
<img width="660" alt="Screenshot at Mar 24 17-57-30" src="https://user-images.githubusercontent.com/43470121/112331980-6cb4c200-8cca-11eb-8c1b-9a8313004fa5.png">

4. Распаковываем папку с JMeter в директорию без пробелов в имени. Лучше создать специальную папку. После распаковки будет примерно такой результат:
<img width="625" alt="Screenshot at Mar 24 17-57-57" src="https://user-images.githubusercontent.com/43470121/112332073-7e966500-8cca-11eb-863a-dbae66eaa69f.png">

5. Заходим  в папку Bin, там  находим файл с именем «JMeter», это исполняемый файл. Щёлкните правой кнопкой мыши по нему и выберите «Открыть с помощью терминала». JMeter должен открыться в виде десктоп-приложения. Если будут возникать вопросы при запуске, разрешайте открытие.


# BlazeMeter 
Это расширение нужно нам для упрощения работы с JMeter.
1. Устанавливаем Google Chrome.
2. Заходим в Меню -> Дополнительные инструменты -> Расширения.
3. Ищем и устанавливаем BlazeMeter, не забываем переключить в режим отображения в панели браузера, на скриншоте справа снизу.
<img width="439" alt="Screenshot at Mar 24 17-59-09" src="https://user-images.githubusercontent.com/43470121/112332338-b56c7b00-8cca-11eb-9a1b-0fc21753a48c.png">
4. **Авторизовываемся в расширении.
<img width="282" alt="Screenshot at Mar 24 17-59-54" src="https://user-images.githubusercontent.com/43470121/112332400-c2896a00-8cca-11eb-97ac-123d59883693.png">

5. Проверяем, что авторизация прошла успешно и что при сохранении есть возможность сохранения в формате JMX.
 
 
# Postman
Для установки Postman нужно всего лишь перейти на официальную страницу, скачать последнюю версию десктоп-приложения и установить её. 
При возникновении проблем можно обратиться к странице поддержки при установке.


### Terminal
О том, что такое Terminal (или командная строка) и как его запустить, можно почитать [здесь](https://windows-school.ru/blog/kak_otkryt_komandnuju_stroku/2018-11-29-245).
 

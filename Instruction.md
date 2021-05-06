# Jmeter
## Windows
1. Устанавливаем Java по инструкции отсюда: https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md
2. Устанавливаем Jmeter. Переходим на страницу https://jmeter.apache.org/download_jmeter.cgi .
3. Выбираем файл Binaries (zip или tgz) для загрузки, как показано на рисунке ниже.
<img width="519" alt="Screenshot at Mar 24 17-54-39" src="https://user-images.githubusercontent.com/43470121/112331545-0def4880-8cca-11eb-8643-803da1ae4647.png">

4. Распаковываем папку с JMeter в директорию без пробелов в имени (т.е. точно не Program Files). Лучше прямо создать специальную папку. После распаковки будет примерно такой результат:
<img width="639" alt="Screenshot at Mar 24 17-55-52" src="https://user-images.githubusercontent.com/43470121/112331703-35461580-8cca-11eb-9056-07e59a46b1a7.png">

 - / bin : содержит файл сценария JMeter для запуска JMeter
 - / docs : файлы документации JMeter
 - / extras : дополнительные файлы, связанные с ant
 - / lib /: содержит необходимую библиотеку Java для JMeter
 - / lib / ext : содержит основные файлы jar для JMeter и протоколы
 - / lib / junit : библиотека Junit, используемая для JMeter
 - / printable_docs :
 
5. Для запуска запустите файл /bin/jmeter.bat, чтобы запустить JMeter в режиме графического интерфейса.

<img width="649" alt="Screenshot at Mar 24 17-56-23" src="https://user-images.githubusercontent.com/43470121/112331773-4858e580-8cca-11eb-965e-ae3c023e2f3e.png">


 
## Для MacOS


1. Устанавливаем Java по инструкции отсюда. https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md
2. Устанавливаем Jmeter. Для этого переходим на страницу для загрузки. https://jmeter.apache.org/download_jmeter.cgi .
3. Выбираем файл Binaries (zip или tgz) для загрузки, как показано на рисунке ниже.
<img width="660" alt="Screenshot at Mar 24 17-57-30" src="https://user-images.githubusercontent.com/43470121/112331980-6cb4c200-8cca-11eb-8c1b-9a8313004fa5.png">

4. Распаковываем папку с JMeter в директорию без пробелов в имени). Лучше прямо создать специальную папку. После распаковки будет примерно такой результат:
<img width="625" alt="Screenshot at Mar 24 17-57-57" src="https://user-images.githubusercontent.com/43470121/112332073-7e966500-8cca-11eb-863a-dbae66eaa69f.png">

5. Заходим  в папку bin, там  находите файл с именем jmeter, это исполняемый файл. Щелкните правой кнопкой мыши по нему, выберите “открыть с помощью терминала”. Jmeter должен открыться в виде десктоп-приложения. Если будут возникать вопросы при запуске, разрешайте открытие.


# BlazeMeter 
Данный экстеншен нужен нам для упрощения работы с Jmeter.
1. Устанавливаем Google Chrome
2. Заходим в меню -> дополнительные инструменты -> расширения
3. Ищем и устанавливаем BlazeMeter (не забываем переключить в режим отображения в панели браузера, на скриншоте справа снизу)
<img width="439" alt="Screenshot at Mar 24 17-59-09" src="https://user-images.githubusercontent.com/43470121/112332338-b56c7b00-8cca-11eb-9a1b-0fc21753a48c.png">
4. **Авторизовываемся в расширении:
<img width="282" alt="Screenshot at Mar 24 17-59-54" src="https://user-images.githubusercontent.com/43470121/112332400-c2896a00-8cca-11eb-97ac-123d59883693.png">

5. Проверяем, что авторизация прошла успешно и что при сохранении есть возможность сохранения в формате JMX.
 
 
# Postman
Для установки постман нужно всего лишь перейти на официальную страницу, скачать последнюю версию десктоп-приложения и установить ее. 
При возникновении проблем можно обратиться к странице поддержки при установке.


### Terminal
Если возникают вопросы о том, что такое терминал и как его запустить - об этом можно почитать [тут](http://students.njay.ru/article/Rabota-v-terminale-v-Windows-Linux-i-MacOS-cli-shell-bash-cmd)
 

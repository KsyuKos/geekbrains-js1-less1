## Установка программного обеспечения
1. В первую очередь необходимо установить набор Java разработчика aka Java Development Kit (JDK), установщик которого можно скачать с официально сайта oracle по ссылке: http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html  
JDK включает в себя Java Runtime Environment (JRE) и Java Virtual Machine (JVM), необходимую для запуска Java приложений
1. После того, как вы установили JDK, можно поставить любую удобную вам среду разработки  
Я сам пользуюсь и рекомендую NetBeans IDE, установщик которой доступен по ссылке https://netbeans.org/downloads/  
_Ближе к концу установки вас спросят, нужен ли дополнительно JUnit. Нужно ответить 'Да'_

## Работа с проектами в NetBeans IDE
После того, как вы установили и запустили NetBeans, вы можете приступать к работе.

### Можно создать новый проект для Java приложения

1. Выбрать пункт New Project в меню File  
![New Project menu](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_project_menu.png)
1. В открывшемся диалоговом окне выбираем Java Application в категории Java или в категории Maven, в случае выбора Maven потребуется подключение к сети Internet, чтобы скачать необходимые модули. Преимуществом Maven проектов является возможность работы с ними в любой IDE (к примеру, Eclipse и IDEA), в то время как обычные Java проекты NetBeans можно открыть только в самом NetBeans.  
![Select project type: Java Application](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_simple_java_app.png)
![Select project type: Maven Java project](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_maven_java_app.png)
1. Выбрав вид проекта, нажимаем кнопку Next и задаем параметры проекта (имя, корневой пакет ...)  
![Java project parameters](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_simple_java_app_params.png)
![Maven Java project parameters](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_maven_java_app_params.png)

### Или можно открыть существующий проект

1. Выбираем пункт Open Project в меню File  
![Open Project](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_open_project_menu.png)
1. В открывшемся диалоговом окне находим папку с нужным проектом и выбираем её (если NetBeans распознает свой проект в папке, то эта папка отображается с соответствующим значком)  
![Open project dialog](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_open_project_dialog.png)

Иногда, чтобы NetBeans начал распознавать папки с maven проектами, надо сделать небольшой трюк:

1. Открыть диалог создания нового проекта через меню File > New Project и выбрать пункт Project with Existing POM в категории Maven  
![Open project with existing POM](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_project_with_existing_pom.png)
1. После нажатия кнопок Next и Finish откроется диалоговое окно для выбора проекта на файловой системе

### Открыв или создав проект, можно в нем работать
К примеру, можно добавить новый класс:

1. В дереве проекта, доступном в панели слева выбираем пакет и в контекстном меню выбираем пункт New > Java Class  
![New class menu](https://raw2.github.com/andreiled/mipt-cs-4sem/8ebe059af7d489d7b17cf89c4b80ffe6f7cf9d67/wiki/images/nb_add_new_class.png)
1. В открывшемся диалоговом окне вводим имя класса и нажимаем Finish  
![Specify class name](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_new_class_dialog.png)
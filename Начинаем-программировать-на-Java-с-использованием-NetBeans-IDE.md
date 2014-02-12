## Установка программного обеспечения
1. В первую очередь необходимо установить набор разработчика Java aka Java Development Kit (JDK), установщик которого можно скачать с официально сайта oracle по ссылке: http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html  
JDK включает в себя Java Runtime Environment (JRE) и Java Virtual Machine (JVM), необходимую для запуска Java приложений
1. После того, как вы установили JDK, можно поставить любую удобную вам среду разработки  
Я сам пользуюсь и рекомендую NetBeans IDE, установщик которой доступен по ссылке https://netbeans.org/downloads/  
_Ближе к концу установки вас спросят, нужен ли дополнительно JUnit. Нужно ответить 'Да'_

## Работа с проектами в NetBeans IDE
После того, как вы установили и запустили NetBeans, вы можете создавать новые проекты или открывать существующие.

К примеру, чтобы создать новый проект для простого Java приложения:

1. Выбрать пункт New Project в меню File  
![New Project menu](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_project_menu.png)
1. В открывшемся диалоговом окне выбираем Java Application в категории Java или в категории Maven, в случае выбора Maven потребуется подключение к сети Internet, чтобы скачать необходимые модули. Преимуществом Maven проектов является возможность работы с ними в любой IDE (к примеру, Eclipse и IDEA), в то время как обычные Java проекты NetBeans можно открыть только в самом NetBeans.  
![Select project type: Java Application](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_simple_java_app.png)
![Select project type: Maven Java project](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_maven_java_app.png)
1. Выбрав вид проекта, нажимаем кнопку Next и задаем параметры проекта (имя, корневой пакет ...)  
![Java project parameters](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_simple_java_app_params.png)
![Maven Java project parameters](https://raw2.github.com/andreiled/mipt-cs-4sem/master/wiki/images/nb_create_new_maven_java_app_params.png)
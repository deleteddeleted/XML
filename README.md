# XML
21. Создать внешний репозиторий c названием XML.  
На вэбе Repositories --> New --> Repository name:XML --> Check "Add a README file" --> "Create repository"

 22. Клонировать репозиторий XML на локальный компьютер.  
git clone https://github.com/deleteddeleted/XML.git

 23. Внутри локального XML создать файл “new.xml”.  
cd XML  
touch new.xml 

 24. Добавить файл под гит.  
git add .  
git status

 25. Закоммитить файл.  
git commit -m "Файл добавлен на внешний репозиторий"

 26. Отправить файл на внешний GitHub репозиторий.  
git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
vim new.xml  
i   
<?xml version="1.0" encoding="UTF-8"?>  
<root>  
   <NSF>  
   	<name> Nastya </name>  
   	<surname>Vinogradova</surname>  
   	<age>25</age>  
   	<pets>1</pets>  
   	<salary>250000</salary>  
   </NSF>  
</root>  
esc :wq enter 
 
 28. Отправить изменения на внешний репозиторий.
git add .
git status
git commit -m "Отредактировано содержание файла"
git push

 29. Создать файл preferences.xml
touch preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
vim preferences.xml
i
<?xml version="1.0" encoding="UTF-8"?>
<preferences>
        <Favorite_movie>The Book Thief</Favorite_movie>
	<Favorite_TV_series>13 Reasons Why</Favorite_TV_series>
	<Favorite_food>pizza</Favorite_food>
	<Favorite_seasons>summer</Favorite_seasons>
	<Country>Norway</Country>
</preferences>
esc :wq enter
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
vim skills.xml
i
<?xml version="1.0" encoding="UTF-8"?>
<Skills_I_Will_Learn>
        <Skill1>Terminal</Skill1>
	<Skill2>GitBash</Skill2>
        <Skill3>API</Skill3>
        <Skill4>Postman</Skill4>
        <Skill4>Test case</Skill4>
</Skills_I_Will_Learn>
esc :wq enter

 32. Сделать коммит в одну строку.
git add . && git commit -m "Коммит в одну строку"

 33. Отправить сразу 2 файла на внешний репозиторий.
git push

 34. На веб интерфейсе создать файл bug_report.xml.
Add file --> Create new file --> Name: bug_report.xml

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit New File

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
<?xml version="1.0" encoding="UTF-8"?>
<bug_report>
    <ID>1</ID>
    <Summary>Не работает кнопка отправки заказа</Summary>
    <Steps to Reproduce>
      <Step1>Пролистать до поля</Step1>
      <Step2>Ввести значение в поле</Step2>
      <Step3>Ввести значение в поле</Step3>
    </Steps to Reproduce>
    <Actual_Result>кнопка неактивна</Actual_Result>
    <Expected_Result>кнопка нажимается, можно сделать заказ</Expected_Result>
    <Attachments>...</Attachments>
</bug_report>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes

 38. Синхронизировать внешний и локальный репозиторий XML
git pull

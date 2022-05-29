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

 28. Отправить изменения на внешний репозиторий.  
git add .  
git status  
git commit -m "Отредактировано содержание файла"  
git push  

 29. Создать файл preferences.xml  
touch preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
vim preferences.xml  

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
vim skills.xml  

 32. Сделать коммит в одну строку.  
git add . && git commit -m "Коммит в одну строку"  

 33. Отправить сразу 2 файла на внешний репозиторий.  
git push  

 34. На веб интерфейсе создать файл bug_report.xml.  
Add file --> Create new file --> Name: bug_report.xml  

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
Commit New File  

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
Choose bug_report.xml --> Edit this file

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
Commit changes  

 38. Синхронизировать внешний и локальный репозиторий XML  
git pull  

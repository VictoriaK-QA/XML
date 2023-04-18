# XML
### GIT   HW#1_XML
 1. Создать внешний репозиторий c названием XML 
 
 <b>GitHub</b> <code> <b>+ New repository</b> </code>

 - [X] Public
 - [X] Add a README file

 <code> <b>Create repository</b> </code>

 2. Клонировать репозиторий XML на локальный компьютер 

 <code> <b>git clone git@github.com:VictoriaK-QA/XML.git</b> </code>

 3. Внутри локального XML создать файл “new.xml” 

 <code> <b>cd XML/</b> </code>  <code> <b>touch new.xml</b> </code>

 4. Добавить файл под гит 
 
 <code> <b>git add .</b> </code>

 5. Закоммитить файл 
 
 <code> <b>git commit -m "new file"</b> </code>

 6. Отправить файл на внешний GitHub репозиторий 
 
 <code> <b>git push</b> </code>

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML 
 
 <code> <b>vim new.xml</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 
 ```xml
 <info>
  <name>Виктория</name>
  <age>28</age>
  <pet>1</pet>
  <salary>300</salary>
  </info>
 ```
 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>

 8. Отправить изменения на внешний репозиторий 
 
 <code> <b>git commit -am "new file"</b> </code> 
 
 <code> <b>git push</b> </code>

 9. Создать файл preferences.xml 
 
 <code> <b>touch preferences.xml</b> </code>
 
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML 
 
 <code> <b>vim preferences.xml</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 ```xml
 <root>
  <favorite_movie>The Godfather</favorite_movie>
  <favorite_sitcom>Friends</favorite_sitcom>
  <favorite_food>pasta</favorite_food>
  <favorite_season>autumn</favorite_season>
  <country_to_travel>Italy</country_to_travel>
  </root>
  ```
 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>
 
 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML 
 
  <code> <b>touch skills.xml</b> </code>

  <code> <b>vim skills.xml</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 ```xml
 <root>
  <skills>Testing Theory</skills>
  <skills>Client server</skills>
  <skills>SQL</skills>
  <skills>Postman</skills>
  <skills>Charles Fiddler Sniffing</skills>
  <skills>Web Services</skills>
  <skills>Git Linux Terminal</skills>
  <skills>DevTools</skills>
  <skills>Mobile Testing</skills>
  <skills>Web Testing</skills>
  <skills>Load testing</skills>
  </root> 
 ```

 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>
 
 12. Сделать коммит в одну строку 

 <code> <b>git add .</b> </code>

 <code> <b>git commit -m "info about skills and preferences"</b> </code>
 
 13. Отправить сразу 2 файла на внешний репозиторий 
 
 <code> <b>git push</b> </code>

 14. На веб интерфейсе создать файл bug_report.xml 
 
 <b>Нажать</b> <code> <b>Add file</b> </code> + <code> <b>Create new file</b> </code> 

 <b>Имя файла bug_report.xml</b>

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе 
 
 <b>Нажать</b> <code> <b>Commit new file</b> </code> 
 
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML 
 
 <b>Нажать</b> <code> <b>Edit this file</b> </code>

 ```xml
 <root>
  <ID>BR-14</ID>
  <Title>What?Where?When?</Title>
  <Severity>Minor</Severity>
  <Priority>Medium</Priority>
  <Precondition>Preparation steps</Precondition>
  <Environment>Devices</Environment>
  <STR>Steps to restore</STR>
  <ER>Expected result</ER>
  <AR>Actual Result</AR>
  <Attachment>link</Attachment>
  </root>
 ```

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе 
 
 <b>Нажать</b> <code> <b>Commit changes</b> </code>

 18. Синхронизировать внешний и локальный репозиторий XML 
 
  <code> <b>git pull</b> </code>
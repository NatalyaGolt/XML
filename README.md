# XML
### 1. Создать внешний публичный репозиторий c названием XML
- Перейти в [профиль github](https://github.com/NatalyaGolt, "NatalyaGolt github profile")
  
- Перейти на вкладку репозиториев

  |Repositories|
  |------------|
  
- Создать новый репозиторий
  
  |New|
  |---|
  
- Ввести имя репозитория
   
  |XML :white_check_mark:|
  |----------------------|
 
- Добавить Readme.md файл

  |:ballot_box_with_check: Add README file|
  |---------------------------------------|

- Создать репозиторий
  
  |Create repository|
  |-----------------|

### 2. Клонировать репозиторий XML на локальный компьютер
    git clone https://github.com/NatalyaGolt/XML.git
### 3. Внутри локального XML создать файл “new.xml”
    touch XML/new.xml
### 4. Добавить файл под гит
    cd XML && git add new.xml
### 5. Закоммитить файл
    git commit -m "add new.xml"
### 6. Отправить файл на внешний GitHub репозиторий
    git push
### 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML
    cat >> new.xml
    <me>
    <name>Natalya</name>
    <age>30</age>
    <pets>0</pets>
    <salary>2000$</salary>
    </me>

_ctrl+C - для выхода из режима редактирования_

### 8. Отправить изменения на внешний репозиторий
    git add . && git commit -m "change new.xml" && git push
### 9. Создать файл preferences.xml
    cat >> preferences.xml
### 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате XML
    <preferences>
    <movie>The prestige</movie>
    <series>Friends</series>
    <food>Borsch</food>
    <season>Summer</season>
    <country>Iceland</country>
    </preferences>

_ctrl+C - для выхода из режима редактирования_
    
### 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
    vim skills.xml

_i - для редактирования файла_

        <skills>
                <skill1>Linux terminal/Gitbash</skill1>
                <skill2>JavaScript</skill2>
                <skill3>Autotests in Postman</skill3>
        </skills>

_esc - выход из режима редактирования_

    :wq - возврат к командной строке
### 12. Сделать коммит в одну строку
    git add . && git commit -m "add two files"
### 13. Отправить сразу 2 файла на внешний репозиторий
    git push
### 14. На веб интерфейсе создать файл bug_report.xml
Находясь во внешнем репозитории XML
- Нажать на кнопку Добавить файл
  
  |Add file|
  |--------|

- Нажать Создать новый файл
  
  |Create new file|
  |---------------|

- Ввести имя и расширение файла
  
  |XML/bug_report.xml|
  |--------------------|

### 15. Сделать Commit на веб интерфейсе
Нажать кнопку Закоммитить новый файл

  |Commit new file|
  |---------------|

### 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
- На внешнем репозитории выбрать файл bug_report.xml 
  
  |bug_report.txt|
  |---------------|

- Нажать кнопку редактирования файла

  |:pencil2:|
  |---------|

- Написать баг репорт в формате xml

      <bug_report>
          <id>001</id>
          <summary>Can't send the email. Button 'send' is inactive</summary>
          <environment>PC Windows 10, Google Chrome v 101.0.4951.41</environment>
          <precondisions>autorisation in email</precondisions>
          <steps>
            <step1>Push button 'write'</step1>
            <step2>Insert receiver email in 'whom' field</step2>
            <step3>Write the message</step3>
            <step4>Push button 'send'</step4>
          <expected_result>
            <1>Letter window is opened</1>
            <2>Can add an adress</2>
            <3>Can write the message</3>
            <4>The letter sent sucsessfully. Window shows the message 'sent'</4>
          </expected_result>
          <actual_result>
            <1>Letter window is opened</1>
            <2>Can add an adress</2>
            <3>Can write the message</3>
            <4>Can't send the email. Button 'send' is inactive</4>
          </actual_result>
          <priority>P1</priority>
          <severity>S1</severity>
          <assign>Email developer</assign>
        </bug_report>


### 17.  Сделать Commit changes (сохранить) изменения на веб интерфейсе
Нажать кнопку Закоммитить изменения

|Commit changes|
|--------------|

### 18. Синхронизировать внешний и локальный репозиторий XML
    git pull

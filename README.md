### postman - HOMEWORK 1
### Создать запросы в Postman
### Protocol: http
### IP: 162.55.220.72
### Port: 5005
---
___
Подготовка:
- Создать новую коллекцию: 
   нажать + во вкладке коллекций
  
    |Collections|+  |
    |:---------:|:-:|

- Переименовать коллекцию в Homework_1: ctrl+E
---
### EP_1
### Method: GET
### EndPoint: /get_method
### Request url params: 
### name: str
### age: int
- Добавить новый запрос в коллекцию (по умолчанию выбран метод GET):
  
  В коллекции Homework_1 нажать ... -> Add request
- Переименовать запрос в "EP_1": ctrl+E
- В поле Request URL ввести протокол, ip, порт, эндпоинт:
  
      http://162.55.220.72:5005/get_method
- Во вкладке Params ввести ключи и значения:
  
    |key |value  |
    |:--:|:-----:|
    |name|Natalya|
    |age |30     |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
 ### Response:
    ["Natalya","30"]
___
### EP_2
### Method: POST
### EndPoint: /user_info_3
### request form data: 
### name: str
### age: int
### salary: int
- Скопировать запрос: ctrl+d
- Переименовать запрос в "EP_2": ctrl+E
- Изменить метод на POST:
  
  |POST|
  |----|
- В поле Request URL ввести:
  
      http://162.55.220.72:5005/user_info_3
- Во вкладке Body -> form-data ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |salary|2000   |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response: 
    {"age": "30",
     "family": {"children": [["Alex",24],["Kate",12]],
                "u_salary_1_5_year": 8000},
     "name": "Natalya",
     "salary": 2000}
---
### EP_3
### Method: GET
### EndPoint: /object_info_1
### Request url params: 
### name: str
### age: int
### weight: int
- Скопировать существующий GET запрос: ctrl+d
- Переименовать запрос в "EP_3": ctrl+E
- В поле Request URL изменить эндпоинт на /object_info_1:
  
      http://162.55.220.72:5005/object_info_1
- Во вкладке Params ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |weight|51     |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response:
    {"age": 30,
     "daily_food": 0.612,
     "daily_sleep": 127.5,
     "name": "Natalya"}
___
### EP_4
### Method: GET
### EndPoint: /object_info_2
### Request url params: 
### name: str
### age: int
### salary: int
- Скопировать существующий GET запрос: ctrl+d
- Переименовать запрос в "EP_4": ctrl+E
- В поле Request URL изменить эндпоинт на /object_info_2:
  
      http://162.55.220.72:5005/object_info_2
- Во вкладке Params ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |salary|2000   |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response:
    {"person": {"u_age": 30,
                "u_name": ["Natalya",2000,30],
                "u_salary_5_years": 8400.0},
     "qa_salary_after_1.5_year": 6600.0,
     "qa_salary_after_12_months": 5400.0,
     "qa_salary_after_3.5_years": 7600.0,
     "qa_salary_after_6_months": 4000,
     "start_qa_salary": 2000}
---
### EP_5
### Method: GET
### EndPoint: /object_info_3
### Request url params: 
### name: str
### age: int
### salary: int
- Скопировать существующий GET запрос: ctrl+d
- Переименовать запрос в "EP_5": ctrl+E
- В поле Request URL изменить эндпоинт на /object_info_3:
  
      http://162.55.220.72:5005/object_info_3
- Во вкладке Params ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |salary|2000   |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response:
    {"age": "30",
     "family": {"children": [["Alex",24],
                            ["Kate",12]],
                "pets": {"cat": {"age": 3,
                                 "name": "Sunny"},
                         "dog": {"age": 4,"name": "Luky"}},
     "u_salary_1_5_year": 8000},
     "name": "Natalya",
     "salary": 2000}
---
### EP_6
### Method: GET
### EndPoint: /object_info_4
### Request url params: 
### name: str
### age: int
### salary: int
- Скопировать существующий GET запрос: ctrl+d
- Переименовать запрос в "EP_6": ctrl+E
- В поле Request URL изменить эндпоинт на /object_info_4:
  
      http://162.55.220.72:5005/object_info_4
- Во вкладке Params ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |salary|2000   |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response:
    {"age": 30,
     "name": "Natalya",
     "salary": [2000,"4000","6000"]}
---
### EP_7
### Method: POST
### EndPoint: /user_info_2
### Request url params: 
### name: str
### age: int
### salary: int
- Скопировать существующий POST запрос: ctrl+d
- Переименовать запрос в "EP_7": ctrl+E
- В поле Request URL изменить эндпоинт на /user_info_2:
  
      http://162.55.220.72:5005/user_info_2
- Во вкладке Body -> form-data ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |salary|2000   |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response:
    {"person": {"u_age": 30,
                "u_name": ["Natalya",2000,30],
                "u_salary_5_years": 8400.0},
     "qa_salary_after_1.5_year": 6600.0,
     "qa_salary_after_12_months": 5400.0,
     "qa_salary_after_3.5_years": 7600.0,
     "qa_salary_after_6_months": 4000,
     "start_qa_salary": 2000}
___
___
### postman - HOMEWORK 2
___
___

Подготовка: Создать новую коллекцию Homework_2
___
### 1. http://162.55.220.72:5005/first
### 1.1 Отправить запрос
- Cоздать запрос GET
- Переименовать запрос в "1": ctrl+E
- В поле Request URL ввести протокол, ip, порт, эндпоинт: http://162.55.220.72:5005/first
- ctrl+s
- ctrl+Enter
  
### Response:  

    This is the first responce from server!
### 1.2 Статус код 200
- Перейти на вкладку Tests
- Выбрать сниппет "Status code: Code is 200":
  
      pm.test("Status code is 200", function ()
      {pm.response.to.have.status(200);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Status code is 200
### 1.3 Проверить, что в body приходит правильный string
- Выбрать сниппет "Response body: Contains string":

      pm.test("Body matches string", function ()
      {pm.expect(pm.response.text()).to.include("This is the first responce from server!");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Body matches string
___
### 2. http://162.55.220.72:5005/user_info_3
### 2.1 Отправить запрос
- Cоздать запрос POST
- Переименовать запрос в "2": ctrl+E
- В поле Request URL ввести протокол, ip, порт, эндпоинт: http://162.55.220.72:5005/user_info_3
- Во вкладке Body -> form-data ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |salary|2000   |
- ctrl+s
- ctrl+Enter
  
### Response: 
    {"age": "30",
     "family": {"children": [["Alex",24],["Kate",12]],
                "u_salary_1_5_year": 8000},
     "name": "Natalya",
     "salary": 2000}
### 2.2 Статус код 200
- Перейти на вкладку Tests
- Выбрать сниппет "Status code: Code is 200":
  
      pm.test("Status code is 200", function ()
      {pm.response.to.have.status(200);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Status code is 200
### 2.3 Спарсить response body в json
- Из сниппета "Response body: JSON value check" выбрать строку, отредактировав название переменной:
    
      let responseData = pm.response.json();

- Вывести результат в консоль:
  
      console.log(responseData)
- ctrl+s
- ctrl+Enter
### Console:

    {age: "30", family: {…}, name: "Natalya"…}
        age: "30"
        family: {…}
            children: [2]
                0: [2]
                    0: "Alex"
                    1: 24
                1: [2]
                    0: "Kate"
                    1: 12
            u_salary_1_5_year: 8000
        name: "Natalya"
        salary: 2000
### 2.4 Проверить, что name в ответе равно name в request (name вбить руками)
- Из сниппета "Response body: JSON value check" выбрать строки и отредактировать название теста, название и предполагаемое значение параметра:
  
      pm.test("Name checking", function ()
      {pm.expect(responseData.name).to.eql("Natalya");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Name checking
### 2.5 Проверить, что age в ответе равно age в request (age вбить руками)
- Из сниппета "Response body: JSON value check" выбрать строки и отредактировать название теста, название и предполагаемое значение параметра:
  
      pm.test("Age checking", function ()
      {pm.expect(responseData.age).to.eql("30");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Age checking
### 2.6 Проверить, что salary в ответе равно salary в request (salary вбить руками)
- Из сниппета "Response body: JSON value check" выбрать строки и отредактировать название теста, название и предполагаемое значение параметра:
  
      pm.test("Salary checking", function ()
      {pm.expect(responseData.salary).to.eql(2000);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Salary checking
### 2.7 Спарсить request
    let requestData = request.data;
    console.log(requestData)
- ctrl+s
- ctrl+Enter
### Console:
    {name: "Natalya", age: "30", salary: "2000"}
        name: "Natalya"
        age: "30"
        salary: "2000"
### 2.8 Проверить, что name в ответе равно name в request (name забрать из request)
    pm.test("Name from response equals name from request", function ()
    {pm.expect(responseData.name).to.eql(requestData.name);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Name from response equals name from request
### 2.9 Проверить, что age в ответе равно age в request (age забрать из request)
    pm.test("Age from response equals age from request", function ()
    {pm.expect(responseData.age).to.eql(requestData.age);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Age from response equals age from request
### 2.10 Проверить, что salary в ответе равно salary в request (salary забрать из request)
    pm.test("Salary from response equals salary from request", function ()
    {pm.expect(responseData.salary).to.eql(+requestData.salary);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Salary from response equals salary from request
### 2.11 Вывести в консоль параметр family из response
    console.log(responseData.family)
- ctrl+s
- ctrl+Enter
### Console:
     
    {children: [2], u_salary_1_5_year: 8000}
        children: [2]
            0: [2]
                0: "Alex"
                1: 24
            1: [2]
                0: "Kate"
                1: 12
        u_salary_1_5_year: 8000
### 2.12 Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)
    pm.test("Salary after 1.5 years from response equals salary*4 from request", function ()
    {pm.expect(responseData.family.u_salary_1_5_year).to.eql(requestData.salary*4);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Salary after 1.5 years from response equals salary*4 from request
___
### http://162.55.220.72:5005/object_info_3
### 3.1 Отправить запрос
- Cоздать запрос GET
- Переименовать запрос в "3": ctrl+E
- В поле Request URL ввести протокол, ip, порт, эндпоинт: http://162.55.220.72:5005/object_info_3
- Во вкладке Params ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |salary|2000   |
- ctrl+s
- ctrl+Enter
  
### Response:
    {"age": "30",
     "family": {"children": [["Alex",24],
                            ["Kate",12]],
                "pets": {"cat": {"age": 3,
                                 "name": "Sunny"},
                         "dog": {"age": 4,"name": "Luky"}},
     "u_salary_1_5_year": 8000},
     "name": "Natalya",
     "salary": 2000}
### 3.2 Статус код 200
- Перейти на вкладку Tests
- Выбрать сниппет "Status code: Code is 200":
  
      pm.test("Status code is 200", function ()
      {pm.response.to.have.status(200);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Status code is 200
### 3.3 Спарсить response body в json
- Из сниппета "Response body: JSON value check" выбрать строку, отредактировав название переменной:
    
      let responseData = pm.response.json();

- Вывести результат в консоль:
  
      console.log(responseData)
- ctrl+s
- ctrl+Enter
### Console:
    {age: "30", family: {…}, name: "Natalya"…}
        age: "30"
        family: {…}
            children: [2]
                0: [2]
                    0: "Alex"
                    1: 24
                1: [2]
                    0: "Kate"
                    1: 12
            pets: {…}
                cat: {…}
                    age: 3
                    name: "Sunny"
                dog: {…}
                    age: 4
                    name: "Luky"
        u_salary_1_5_year: 8000
        name: "Natalya"
        salary: 2000
### 3.4 Спарсить request
    let requestData = pm.request.url.query.toObject()
    console.log(requestData)
- ctrl+s
- ctrl+Enter
### Console:
 
    {name: "Natalya", age: "30", salary: "2000"}
        name: "Natalya"
        age: "30"
        salary: "2000"    
    
### 3.5 Проверить, что name в ответе равно name в request (name забрать из request)
    pm.test("Name from response equals name from request", function ()
    {pm.expect(responseData.name).to.eql(requestData.name);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Name from response equals name from request
### 3.6 Проверить, что age в ответе равно age в request (age забрать из request)
    pm.test("Age from response equals age from request", function ()
    {pm.expect(responseData.age).to.eql(requestData.age);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Age from response equals age from request
### 3.7 Проверить, что salary в ответе равно salary в request (salary забрать из request)
    pm.test("Salary from response equals salary from request", function ()
    {pm.expect(responseData.salary).to.eql(+requestData.salary);});
- ctrl+s
- ctrl+Enter

### Перейти во вкладку Test Results:
    PASS Salary from response equals salary from request
### 3.8 Вывести в консоль параметр family из response
    console.log(responseData.family)
- ctrl+s
- ctrl+Enter
### Console:
    {children: [2], pets: {…}, u_salary_1_5_year: 8000}
        children: [2]
            0: [2]
                0: "Alex"
                1: 24
            1: [2]
                0: "Kate"
                1: 12
        pets: {…}
            cat: {…}
                age: 3
                name: "Sunny"
            dog: {…}
                age: 4
                name: "Luky"
        u_salary_1_5_year: 8000
### 3.9 Проверить, что у параметра dog есть параметр name
    pm.test("Dog has name", function()
    {pm.expect(responseData.family.pets.dog).to.have.property("name");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Dog has name    
### 3.10 Проверить, что у параметра dog есть параметр age
    pm.test("Dog has age", function()
    {pm.expect(responseData.family.pets.dog).to.have.property("age");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Dog has age    
### 3.11 Проверить, что параметр name имеет значение Luky
- Из сниппета "Response body: JSON value check" выбрать строки и отредактировать название теста, название и предполагаемое значение параметра:
  
      pm.test("Dog's name is Luky", function ()
      {pm.expect(responseData.family.pets.dog.name).to.eql("Luky");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Dog's name is Luky   
### 3.12 Проверить, что параметр age имеет значение 4
- Из сниппета "Response body: JSON value check" выбрать строки и отредактировать название теста, название и предполагаемое значение параметра:
  
      pm.test("Dog's age is 4", function ()
      {pm.expect(responseData.family.pets.dog.age).to.eql(4);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Dog's age is 4    
___
### http://162.55.220.72:5005/object_info_4
### 4.1 Отправить запрос
- Cоздать запрос GET
- Переименовать запрос в "4": ctrl+E
- В поле Request URL ввести протокол, ip, порт, эндпоинт: http://162.55.220.72:5005/object_info_4
- Во вкладке Params ввести ключи и значения:
  
    |key   |value  |
    |:----:|:-----:|
    |name  |Natalya|
    |age   |30     |
    |salary|2000   |
- ctrl+s
- ctrl+Enter
  
### Response:
    {"age": 30,
     "name": "Natalya",
     "salary": [2000,"4000","6000"]}
### 4.2 Статус код 200
- Перейти на вкладку Tests
- Выбрать сниппет "Status code: Code is 200":
  
      pm.test("Status code is 200", function ()
      {pm.response.to.have.status(200);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Status code is 200
### 4.3 Спарсить response body в json
- Из сниппета "Response body: JSON value check" выбрать строку, отредактировав название переменной:
    
      let responseData = pm.response.json();

- Вывести результат в консоль:
  
      console.log(responseData)
- ctrl+s
- ctrl+Enter
### Console:
    {age: 30, name: "Natalya", salary: [3]}
        age: 30
        name: "Natalya"
        salary: [3]
            0: 2000
            1: "4000"
            2: "6000"
### 4.4 Спарсить request
    let requestData = pm.request.url.query.toObject() 
    console.log(requestData)
- ctrl+s
- ctrl+Enter
### Console:
    {name: "Natalya", age: "30", salary: "2000"}
        name: "Natalya"
        age: "30"
        salary: "2000"    
### 4.5 Проверить, что name в ответе равно name в request (name забрать из request)
    pm.test("Name from response equals name from request", function ()
    {pm.expect(responseData.name).to.eql(requestData.name);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Name from response equals name from request
### 4.6 Проверить, что age в ответе равно age из request (age забрать из request)
    pm.test("Age from response equals age from request", function ()
    {pm.expect(responseData.age).to.eql(+requestData.age);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Age from response equals age from request
### 4.7 Вывести в консоль параметр salary из request
    console.log(requestData.salary)
### Console:
     
    "2000"
### 4.8 Вывести в консоль параметр salary из response
    console.log(responseData.salary)
### Console:
      
    (3) [2000, "4000", "6000"]    
### 4.9 Вывести в консоль 0-й элемент параметра salary из response
    console.log(responseData.salary[0])
### Console:
 
    2000
### 4.10 Вывести в консоль 1-й элемент параметра salary параметр salary из response
    console.log(responseData.salary[1])
### Console:
 
    "4000"
### 4.11 Вывести в консоль 2-й элемент параметра salary параметр salary из response
    console.log(responseData.salary[2])
### Console:
 
    "6000"
### 4.12 Проверить, что 0-й элемент параметра salary равен salary из request (salary забрать из request)
    pm.test("Salary[0] from response equals salary from request", function ()
    {pm.expect(responseData.salary[0]).to.eql(+requestData.salary);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Salary[0] from response equals salary from request
### 4.13 Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request)
    pm.test("Salary[1] from response equals salary*2 from request", function ()
    {pm.expect(+responseData.salary[1]).to.eql(requestData.salary*2);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Salary[1] from response equals salary*2 from request
### 4.14 Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary забрать из request)
    pm.test("Salary[2] from response equals salary*3 from request", function ()
    {pm.expect(+responseData.salary[2]).to.eql(requestData.salary*3);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Salary[2] from response equals salary*3 from request
### 4.15 Создать в окружении переменную name
- В левом меню перейти на вкладку Enviroments
- Нажать +
- Переименовать окружение в Homework_2

|Variable|
|:------:|
|name    |
### 4.16 Создать в окружении переменную age
|Variable|
|:------:|
|age     |
### 4.17 Создать в окружении переменную salary
|Variable|
|:------:|
|salary  |
### 4.18 Передать в окружение переменную name
- ctrl+s
- В правом верхнем углу нажать :arrow_down_small: и выбрать созданное окружение Homework_2 (Слева напротив выбранного окружения появляется галочка)
- В левом меню перейти во вкладку Collections -> Homework_2 -> 4
- Выбрать сниппет "Get an enviroment variable", изменить variable name (название variable из окружения), variable value (параметр из ответа запроса):
  
      let name_response = responseData.name
      pm.environment.set("name", name_response);
- ctrl+s
- ctrl+Enter
### Результат во вкладке Enviroments:
  
|Variable|Current Value|
|:------:|:-----------:|
|name    |Natalya      |
### 4.19 Передать в окружение переменную age
- Выбрать сниппет "Get an enviroment variable", изменить variable name (название variable из окружения), variable value (параметр из ответа запроса):
  
      let age_response = responseData.age
      pm.environment.set("age", age_response);
- ctrl+s
- ctrl+Enter
### Результат во вкладке Enviroments:
  
|Variable|Current Value|
|:------:|:-----------:|
|age     |30           |
### 4.20 Передать в окружение переменную salary
- Выбрать сниппет "Get an enviroment variable", изменить variable name (название variable из окружения), variable value (параметр из ответа запроса):
  
      let salary_response = responseData.salary[0]
      pm.environment.set("salary", salary_response);
- ctrl+s
- ctrl+Enter
### Результат во вкладке Enviroments:
  
|Variable|Current Value|
|:------:|:-----------:|
|salary  |2000         |
### 4.21 Написать цикл который выведет в консоль по порядку элементы списка из параметра salary
    let salary_data = responseData.salary
    let salary_length = salary_data.length
    let start = 0
        while(start < salary_length)
            {console.log(salary_data[start])
            start++}
### Console:
 
    2000
    "4000"
    "6000"
___
### http://162.55.220.72:5005/user_info_2
- Cоздать запрос POST
- Переименовать запрос в "2": ctrl+E
- В поле Request URL ввести протокол, ip, порт, эндпоинт: http://162.55.220.72:5005/user_info_2
- Во вкладке Body -> form-data ввести ключи:

|Key   |
|:----:|
|name  |
|age   |
|salary|

Выбрано окружение Homework_2
### 5.1 Вставить параметр salary из окружения в request
|Value     |
|:--------:|
|{{salary}}|
### 5.2 Вставить параметр age из окружения в age
|Value  |
|:-----:|
|{{age}}|
### 5.3 Вставить параметр name из окружения в name
|Value   |
|:------:|
|{{name}}|
### 5.4 Отправить запрос
- ctrl+s
- ctrl+Enter
### Response: 
    {"person": {"u_age": 30,
                "u_name": ["Natalya",2000,30],
                "u_salary_5_years": 8400.0},
     "qa_salary_after_1.5_year": 6600.0,
     "qa_salary_after_12_months": 5400.0,
     "qa_salary_after_3.5_years": 7600.0,
     "qa_salary_after_6_months": 4000,
     "start_qa_salary": 2000}
### 5.5 Статус код 200
- Перейти на вкладку Tests
- Выбрать сниппет "Status code: Code is 200":
  
      pm.test("Status code is 200", function ()
      {pm.response.to.have.status(200);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Status code is 200
### 5.6 Спарсить response body в json
- Из сниппета "Response body: JSON value check" выбрать строку, отредактировав название переменной:
    
      let responseData = pm.response.json();

- Вывести результат в консоль:
  
      console.log(responseData)
- ctrl+s
- ctrl+Enter
### Console:
    
    {person: {…}, qa_salary_after_1.5_year: 6600, qa_salary_after_12_months: 5400…}
        person: {…}
        u_age: 30
        u_name: [3]
            0: "Natalya"
            1: 2000
            2: 30
        u_salary_5_years: 8400
        qa_salary_after_1.5_year: 6600
        qa_salary_after_12_months: 5400
        qa_salary_after_3.5_years: 7600
        qa_salary_after_6_months: 4000
        start_qa_salary: 2000
### 5.7 Спарсить request
    let requestData = request.data;
    console.log(requestData)
- ctrl+s
- ctrl+Enter
### Console:
    {name: "Natalya", age: "30", salary: "2000"}
        name: "Natalya"
        age: "30"
        salary: "2000"
### 5.8 Проверить, что json response имеет параметр start_qa_salary
    pm.test("Response has start_qa_salary", function()
    {pm.expect(responseData).to.have.property("start_qa_salary");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Response has start_qa_salary
### 5.9 Проверить, что json response имеет параметр qa_salary_after_6_months
    pm.test("Response has qa_salary_after_6_months", function()
    {pm.expect(responseData).to.have.property("qa_salary_after_6_months");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Response has qa_salary_after_6_months
### 5.10 Проверить, что json response имеет параметр qa_salary_after_12_months
    pm.test("Response has qa_salary_after_12_months", function()
    {pm.expect(responseData).to.have.property("qa_salary_after_12_months");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Response has qa_salary_after_12_months
### 5.11 Проверить, что json response имеет параметр qa_salary_after_1.5_year
    pm.test("Response has qa_salary_after_1.5_year", function()
    {pm.expect(responseData).to.have.property("qa_salary_after_1.5_year");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Response has qa_salary_after_1.5_year
### 5.12 Проверить, что json response имеет параметр qa_salary_after_3.5_years
    pm.test("Response has qa_salary_after_3.5_years", function()
    {pm.expect(responseData).to.have.property("qa_salary_after_3.5_years");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Response has qa_salary_after_3.5_years
### 5.13 Проверить, что json response имеет параметр person
    pm.test("Response has person", function()
    {pm.expect(responseData).to.have.property("person");});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Response has person
### 5.14 Проверить, что параметр start_qa_salary равен salary из request (salary забрать из request)
    pm.test("Start_qa_salary from response equals salary from request", function ()
    {pm.expect(responseData.start_qa_salary).to.eql(+requestData.salary);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Start_qa_salary from response equals salary from request
### 5.15 Проверить, что параметр qa_salary_after_6_months равен salary*2 из request (salary забрать из request)
    pm.test("Qa_salary_after_6_months from response equals salary*2 from request", function ()
    {pm.expect(responseData.qa_salary_after_6_months).to.eql(requestData.salary*2);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Qa_salary_after_6_months from response equals salary*2 from request
### 5.16 Проверить, что параметр qa_salary_after_12_months равен salary*2.7 из request (salary забрать из request)
    pm.test("Qa_salary_after_12_months from response equals salary*2.7 from request", function ()
    {pm.expect(responseData.qa_salary_after_12_months).to.eql(requestData.salary*2.7);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Qa_salary_after_12_months from response equals salary*2.7 from request
### 5.17 Проверить, что параметр qa_salary_after_1.5_year равен salary*3.3 из request (salary забрать из request)
    pm.test("Qa_salary_after_1.5_year from response equals salary*3.3 from request", function ()
    {pm.expect(responseData["qa_salary_after_1.5_year"]).to.eql(requestData.salary*3.3);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Qa_salary_after_1.5_year from response equals salary*3.3 from request
### 5.18 Проверить, что параметр qa_salary_after_3.5_years равен salary*3.8 из request (salary забрать из request)
    pm.test("Qa_salary_after_3.5_years from response equals salary*3.8 from request", function ()
    {pm.expect(responseData["qa_salary_after_3.5_years"]).to.eql(requestData.salary*3.8);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Qa_salary_after_3.5_years from response equals salary*3.8 from request
### 5.19 Проверить, что в параметре person, 1-й элемент из u_name равен salary из request (salary забрать из request)
    pm.test("Person's u_name[1] from response equals salary from request", function ()
    {pm.expect(responseData.person.u_name[1]).to.eql(+requestData.salary);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Person's u_name[1] from response equals salary from request
### 5.20 Проверить, что что параметр u_age равен age из request (age забрать из request)
    pm.test("Person's u_name from response equals salary from request", function ()
    {pm.expect(responseData.person.u_age).to.eql(requestData.age);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Person's u_name from response equals salary from request
### 5.21 Проверить, что параметр u_salary_5_years равен salary*4.2 из request (salary забрать из request)
    pm.test("Person's u_salary_5_years from response equals salary*4.2 from request", function ()
    {pm.expect(responseData.person.u_salary_5_years).to.eql(requestData.salary*4.2);});
- ctrl+s
- ctrl+Enter
### Перейти во вкладку Test Results:
    PASS Person's u_salary_5_years from response equals salary*4.2 from request




### 5.22 Написать цикл который выведет в консоль по порядку элементы списка из параметра person


### Console:


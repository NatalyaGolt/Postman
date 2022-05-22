# postman - HOMEWORK 1
## Создать запросы в Postman
## Protocol: http
## IP: 162.55.220.72
## Port: 5005
---
Подготовка:
- Создать новую коллекцию: 
   нажать + во вкладке коллекций
  
    |Collections|+|
    |-----------|-|

- Переименовать коллекцию в Homework_1: ctrl+E
---
## EP_1
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
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
 ### Response:
    ["Natalya","30"]
___
## EP_2
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
  
    |key |value  |
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
    |salary |2000     |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response: 
    {"age": "30",
     "family": {"children": [["Alex",24],["Kate",12]],
                "u_salary_1_5_year": 8000},
     "name": "Natalya",
     "salary": 2000}
---
## EP_3
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
  
    |key |value  |
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
    |weight |51     |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response:
    {"age": 30,
     "daily_food": 0.612,
     "daily_sleep": 127.5,
     "name": "Natalya"}
___
## EP_4
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
  
    |key |value  |
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
    |salary |2000     |
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
## EP_5
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
  
    |key   |value|
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
    |salary|2000|
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
## EP_6
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
  
    |key |value  |
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
    |salary |2000     |
- Сохранить запрос: ctrl+s
- Отправить запрос: ctrl+Enter
### Response:
    {"age": 30,
     "name": "Natalya",
     "salary": [2000,"4000","6000"]}
---
## EP_7
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
  
    |key |value  |
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
    |salary |2000     |
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
# postman - HOMEWORK 2

Подготовка: Создать новую коллекцию Homework_2
___
## 1. http://162.55.220.72:5005/first
### 1.1 Отправить запрос
- Cоздать запрос GET
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
- В поле Request URL ввести протокол, ip, порт, эндпоинт: http://162.55.220.72:5005/user_info_3
- Во вкладке Body -> form-data ввести ключи и значения:
  
    |key |value  |
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
    |salary |2000     |
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
## http://162.55.220.72:5005/object_info_3
### 3.1 Отправить запрос
- Cоздать запрос GET
- В поле Request URL ввести протокол, ip, порт, эндпоинт: http://162.55.220.72:5005/object_info_3
- Во вкладке Params ввести ключи и значения:
  
    |key |value  |
    |:----:|:-------:|
    |name|Natalya|
    |age |30     |
    |salary |2000     |
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
### 3.9 Проверить, что у параметра dog есть параметры name

### 3.10 Проверить, что у параметра dog есть параметры age
### 3.11 Проверить, что параметр name имеет значение Luky
### 3.12 Проверить, что параметр age имеет значение 4
___
## http://162.55.220.72:5005/object_info_4
### 1. Отправить запрос
### 2. Статус код 200
### 3. Спарсить response body в json
### 4. Спарсить request
### 5. Проверить, что name в ответе равно name в request (name забрать из request)
### 6. Проверить, что age в ответе равно age из request (age забрать из request)
### 7. Вывести в консоль параметр salary из request
### 8. Вывести в консоль параметр salary из response
### 9. Вывести в консоль 0-й элемент параметра salary из response
### 10. Вывести в консоль 1-й элемент параметра salary параметр salary из response
### 11. Вывести в консоль 2-й элемент параметра salary параметр salary из response
### 12. Проверить, что 0-й элемент параметра salary равен salary из request (salary забрать из request)
### 13. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request)
### 14. Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary забрать из request)
### 15. Создать в окружении переменную name
### 16. Создать в окружении переменную age
### 17. Создать в окружении переменную salary
### 18. Передать в окружение переменную name
### 19. Передать в окружение переменную age
### 20. Передать в окружение переменную salary
### 21. Написать цикл который выведет в консоль по порядку элементы списка из параметра salary
___
## http://162.55.220.72:5005/user_info_2
### 1. Вставить параметр salary из окружения в request
### 2. Вставить параметр age из окружения в age
### 3. Вставить параметр name из окружения в name
### 4. Отправить запрос
### 5. Статус код 200
### 6. Спарсить response body в json
### 7. Спарсить request
### 8. Проверить, что json response имеет параметр start_qa_salary
### 9. Проверить, что json response имеет параметр qa_salary_after_6_months
### 10. Проверить, что json response имеет параметр qa_salary_after_12_months
### 11. Проверить, что json response имеет параметр qa_salary_after_1.5_year
### 12. Проверить, что json response имеет параметр qa_salary_after_3.5_years
### 13. Проверить, что json response имеет параметр person
### 14. Проверить, что параметр start_qa_salary равен salary из request (salary забрать из request)
### 15. Проверить, что параметр qa_salary_after_6_months равен salary*2 из request (salary забрать из request)
### 16. Проверить, что параметр qa_salary_after_12_months равен salary*2.7 из request (salary забрать из request)
### 17. Проверить, что параметр qa_salary_after_1.5_year равен salary*3.3 из request (salary забрать из request)
### 18. Проверить, что параметр qa_salary_after_3.5_years равен salary*3.8 из request (salary забрать из request)
### 19. Проверить, что в параметре person, 1-й элемент из u_name равен salary из request (salary забрать из request)
### 20. Проверить, что что параметр u_age равен age из request (age забрать из request)
### 21. Проверить, что параметр u_salary_5_years равен salary*4.2 из request (salary забрать из request)
### 22. ***Написать цикл который выведет в консоль по порядку элементы списка из параметра person

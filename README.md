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
- Добавить новый запрос в коллекцию (по умолчанию выбран метод GET): В коллекции Homework_1 нажать 
    
    ... -> Add request
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
- Во вкладке Body ввести ключи и значения:
  
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
- Во вкладке Body ввести ключи и значения:
  
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
# postman - HOMEWORK 2
Подготовка:
- Создать новую коллекцию: 
   нажать + во вкладке коллекций
  
    |Collections|+|
    |-----------|-|

- Переименовать коллекцию в Homework_2: ctrl+E
---
## http://162.55.220.72:5005/first
## 1. Отправить запрос
- Cоздать запрос GET
- В поле Request URL ввести протокол, ip, порт, эндпоинт: http://162.55.220.72:5005/first
- ctrl+s
- ctrl+Enter
  
## Ответ:  

    This is the first responce from server!
## 2. Статус код 200
- зайти на вкладку Tests
- выбрать сниппет Status code: Code is 200
  
        pm.test("Status code is 200", function () {
        pm.response.to.have.status(200);
        });
- ctrl+s
- ctrl+Enter
## Перейти во вкладку Test Results:
    Status code is 200
## 3. Проверить, что в body приходит правильный string
- выбрать сниппет Response body: Contains string

        pm.test("Body matches string", function () {
        pm.expect(pm.response.text()).to.include("This is the first responce from server!");
        });
- ctrl+s
- ctrl+Enter
## Перейти во вкладку Test Results:
    Body matches string
___
## http://162.55.220.72:5005/user_info_3
## 1. Отправить запрос
## 2. Статус код 200
## 3. Спарсить response body в json
## 4. Проверить, что name в ответе равно name s request (name вбить руками)
## 5. Проверить, что age в ответе равно age s request (age вбить руками)
## 6. Проверить, что salary в ответе равно salary s request (salary вбить руками)
## 7. Спарсить request
## 8. Проверить, что name в ответе равно name s request (name забрать из request)
## 9. Проверить, что age в ответе равно age s request (age забрать из request)
## 10. Проверить, что salary в ответе равно salary s request (salary забрать из request)
## 11. Вывести в консоль параметр family из response
## 12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)

# Fiddler
![Logo_Fiddler](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Fiddler-Logo.png)

## HomeWork
### Ex_0: Отфильтровать выдачу запросов по нужному ip

Protocol: http
IP: 162.55.220.72
Port: 5005
![Ex0](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex0.png)

### Ex_1: 
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int

response: 
[
    “Str”,
    “Str”
]

Task:
Сделать правила:
 ⁃ Подменить url в чтобы в запросе поменялся name которые вы вписали в Postman.
 - Подменить url в чтобы в запросе поменялся age которые вы вписали в Postman. 

![Ex1](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex1.png)

### Ex_2:
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}

Task:
Сделать правила:
 ⁃ Подменить тело запроса чтобы поменялся name которые вы вписали в Postman.!
 - Подменить тело запроса чтобы поменялся age которые вы вписали в Postman. !
 - Подменить тело запроса чтобы поменялся salary которые вы вписали в Postman. !
 - Подменить тело запроса чтобы удалился age которые вы вписали в Postman.  (Получить 500 код) !
 - В ответе поменять children на neighbors. !
 - В ответе поменять значение зарплаты u_salary_1_5_year на другую цифру. !
 - В ответе удалить параметр salary. 

![Ex2](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex2.png)
![Ex2(1)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex2(1).png)
![Ex2(2)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex2(2).png)

### Ex_3:
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}

Task:
Сделать правила:
 ⁃ Подменить url в чтобы в запросе поменялся name которые вы вписали в Postman.
 - Подменить url в чтобы в запросе поменялся age которые вы вписали в Postman. 
 - Подменить url в чтобы в запросе поменялся weight которые вы вписали в Postman. 
 - Подменить url в чтобы в запросе удалился weight которые вы вписали в Postman.
 - В ответе удалить параметр  daily_food.
 - В ответе поменять значение параметра daily_food на другую цифру. 
 - В ответе переименовать daily_sleep на sleep
 - В ответе поменять значение параметра daily_sleep на другую цифру. 

![Ex3](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex3.png)
![Ex3(1)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex3(1).png)
![Ex3(2)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex3(2).png)
![Ex3(3)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex3(3).png)

### Ex_4:
Method: GET
EndPoint: /object_info_3
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }

Task:
Сделать правила:
 ⁃ Подменить url в чтобы в запросе поменялся name которые вы вписали в Postman.
 - Подменить url в чтобы в запросе поменялся age которые вы вписали в Postman. 
 - Подменить url в чтобы в запросе удалился name которые вы вписали в Postman.
 - В ответе удалить параметр  salary.
 - В ответе поменять значение параметра cat на другой json. 
 - Получить 405 код

![Ex4](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex4.png)
![Ex4(1)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex4(1).png)
![Ex4(2)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex4(2).png)


### Ex_5:
Method: GET
EndPoint: /object_info_4
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}


Task:
 ⁃ Подменить url в чтобы в запросе поменялся name которые вы вписали в Postman.
 - Подменить url в чтобы в запросе поменялся age которые вы вписали в Postman. 
 - Подменить url в чтобы в запросе удалился salary которые вы вписали в Postman.
 - В ответе удалить параметр  salary.
 - В ответе поменять значение параметра salary на значение текстового типа. 
 - Получить 405 код

![Ex5](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex5.png)
![Ex5(1)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex5(1).png)
![Ex5(2)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex5(2).png)


### Ex_6:
Method: POST
EndPoint: /user_info_2
request form data: 
 name: str
 age: int
 salary: int
response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }


Task:
Сделать правила:
 - Подменить тело запроса чтобы поменялся age которые вы вписали в Postman. 
 - Подменить тело запроса чтобы поменялся salary которые вы вписали в Postman. 
 - Подменить тело запроса чтобы удалился salary которые вы вписали в Postman.
 - В ответе поменять qa_salary_after_6_months на qa_salary_after_10_months. 
 - В ответе поменять значение зарплаты qa_salary_after_1.5_year на другую цифру. 
 - В ответе удалить параметр person. 
 - В ответе поменять значение параметр person с json на xml. 

![Ex6](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex6.png)
![Ex6(1)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex6(1).png)
![Ex6(2)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex6(2).png)
![Ex6(3)](https://github.com/SereJaPWNZ/Fiddler/blob/master/assert/Ex6(3).png)

### Все настройки правил Fiddler выгрузить в GitHub

[Link Fiddler Settings](https://github.com/SereJaPWNZ/Fiddler/blob/master/)

## 📫 How to reach me
[![Telegram](https://img.shields.io/badge/-Telegram-000000?style=for-the-badge&logo=telegram&logoColor=00ff88)](https://t.me/res1stpwnz)
[![Email](https://img.shields.io/badge/-gmail-000000?style=for-the-badge&logo=gmail&logoColor=red)](mailto:oofatherxomgoo@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-linkedin-000000?style=for-the-badge&logo=linkedin&logoColor=3955a8)](https://linkedin.com/in/morkovkinsergey)
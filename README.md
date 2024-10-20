Робота з HTTP протоколом, запитами та публічними API. ЛБ2

Завдання
[Easy] Встановити python веб фреймворк та запустити веб сервер на порту 8000. 

Flask

На рис. 1 та 2 продемонстрован код та запуск

![1](https://github.com/user-attachments/assets/1734d0f1-7f39-4f51-ab11-002365ca1977)
                             Рисунок 1 - Код для запуску

![2](https://github.com/user-attachments/assets/1ad5236a-79b9-4b88-acd7-0035a2ef721f)
                        Рисунок 2 - Запуск веб сервер на порту 8000

Bottle

На рис. 3 та 4 продемонстрован код та запуск веб сервера

![3](https://github.com/user-attachments/assets/08237a39-7290-4e17-a7f5-c29db46b6b4e)
Рисунок 3 - Код для запуску Bottle
![4](https://github.com/user-attachments/assets/dc4514ed-4d3f-4bc1-9bd8-ab37b8b8b195)
Рисунок 4 - Запуск веб сервер на порту 8000 Bottle

[Easy] Написати просту обробку запиту метода GET сервером. На “Hello World!” 

На рис. 5, 6, 7 та 8 продемонтрован код та запуск веб сервера методом GET 

Flask

![5](https://github.com/user-attachments/assets/8597fb0d-9eb1-491c-be71-708cea019c14)
Рисунок 5 - Код для запуску Flask

![image](https://github.com/user-attachments/assets/2c9414aa-fe8e-42e9-b4bc-9d0eda8f924d)

Рисунок 6 - Запуск веб сервера Flask

Bottle

![7](https://github.com/user-attachments/assets/1dbe95dc-c047-41ef-a408-907252849b17)
Рисунок 7 - Код для запуску Bottle

![image](https://github.com/user-attachments/assets/928e7aae-c912-4ff3-9622-933b4d07bea8)
Рисунок 8 - Запуск веб сервера Bottle


[Easy-Medium] Написати просту обробку запиту метода GET сервером зі шляхом та параметрами в URL, наприклад http://127.0.0.1:8000/currency?today. Повертати статичне значення курса валют, наприклад “USD - 41,5”.  Для flask отримати параметри запиту за допомогою request.args.get(), для bottle -  request.query()   

На рис. 9-12 продемостровано код та обробка запиту метода GET сервером зі шляхом та параметрами в URL

Flask

![9](https://github.com/user-attachments/assets/10e6a955-b36a-4f2d-80cb-fd5b5a695ecb)
Рисунок 9 - Код для запуску

![image](https://github.com/user-attachments/assets/924f8c76-3d5e-4925-b363-3b7fe1696e26)
Рисунок 10 - Вивід в Postman

Bottle

![11](https://github.com/user-attachments/assets/3ad4b5dc-c180-48de-bf98-b25aecd7bc20)
Рисунок 11 - Код для запуску

![image](https://github.com/user-attachments/assets/e4643acc-86d0-4341-9b4d-f45b81089ce1)
Рисунок 12 - Вивід в Postman

[Medium] Обробка заголовків запиту. В залежності від значення параметру заголовку “Content-Type” (application/json чи application/xml) повертати json чи xml документ. У разі відсутності - повертати звичайний текст. Для flask отримати заголовки за допомогою request.headers.get, для bottle - request.get_header[]. 

На рис. 13-16 продемострован код та json чи xml документ.

Flask

![13](https://github.com/user-attachments/assets/556f1981-68a3-4056-bfe4-26eb437c899d)
Рисунок 13 - Код для запуску

![image](https://github.com/user-attachments/assets/c1da95f9-7a15-423a-a646-f82e219fda02)
Рисунок 14 - json

![image](https://github.com/user-attachments/assets/da90dabd-b74b-4884-a7a3-e9d653c1c95b)
Рисунок 15 - xml

Bottle

![17](https://github.com/user-attachments/assets/726030e8-5c21-4922-857e-3a1fa6af8fff)
Рисунок 16 - Код для запуску

![14](https://github.com/user-attachments/assets/0ee0a23d-4179-4867-90cb-ee1661ebe6ee)
Рисунок 17 - xml

![15](https://github.com/user-attachments/assets/31c3a427-bd40-4adc-b095-4fa3061c107c)
Рисунок 18 - json





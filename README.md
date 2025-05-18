# task9
1)  Часть 1 <br>
  Создать EC2 инстанс и s3 bucket c именем mybucket. Сделать так чтоб доступ был к ведру mybucket был через IAM роль.
  Когда вводим aws s3 ls мы должны увидеть список ведер <br>
  1. Создание бакета <br>
  ![image](https://github.com/user-attachments/assets/c435ae38-af62-4c63-a082-33e9d4a4cf2a) <br>
  
  2. Создание ROLE <br>
  ![image](https://github.com/user-attachments/assets/b0327a75-7fbf-4df9-a47a-82fd638795ca) <br>

  3. Создание Instance <br>
  ![image](https://github.com/user-attachments/assets/216009a4-ae43-43a2-8d3e-db38da686ee4) <br>
  
  4. Итог <br>
  ![image](https://github.com/user-attachments/assets/0ed28026-f4b8-44da-bf2e-8ae481b654c5) <br>

______________________________________________________________________________________________________________________

2)  Часть 2 <br>
  Создать в IAM пользователя Petr и предоставить емуConsole access. Cоздать группу just_users. Добавить пользователя в группу just_users. Дать 
  права группе на только на полный доступ к EC2. Попробовать из этого пользователя Petr создать новый инстанс в любом регионе и создать vpc в любом 
  регионе. Рассказать о результах

  1. Создание юзера <br>
  ![image](https://github.com/user-attachments/assets/f185b2b9-5fbc-4135-8127-053a40827632) <br>

  2. Создание группы, добавление пермишена, добавление туда юзера <br>
  ![image](https://github.com/user-attachments/assets/b1fb5a8d-013b-44fb-a468-24c952782fbd) <br>
  ![image](https://github.com/user-attachments/assets/cfe2dfcb-0653-4d01-a79b-088267d8a572) <br>
  
  3. Проверка <br>
   3.1 Создание виртуалки: <br>
    ![image](https://github.com/user-attachments/assets/babcc089-2fc4-471c-82b6-79809b910fc5) <br>
     <br>
    3.2 Создание VPC <br>
     ![image](https://github.com/user-attachments/assets/7114728a-81b5-41bc-977d-f14dff8da756)

    
  

     


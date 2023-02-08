Державний вищий навчальний заклад Ужгородський національний університет Факультет інформаційних технологій

ЛАБОРАТОРНА РОБОТА №5 Тема: Деплой проекту на AWS EC2

Виконав студент ІIІ курсу Напрям: ІПЗ-2.2 Цар Сергій Михайлович


Ужгород-2022 Хід роботи Спочатку ми зареєструвалися на AWS. Після чого створюємо інстанс EC2
![image](https://user-images.githubusercontent.com/75271497/217419231-ae90672c-2271-4cfa-8c8b-2580b6df3783.png)

![image](https://user-images.githubusercontent.com/75271497/217419279-85efde33-a932-4bc4-b5ab-a10768a6ec7f.png)
![image](https://user-images.githubusercontent.com/75271497/217419325-a764c021-e05d-4540-bdb1-08e7ca63e735.png)

Натиснувши на кнопку Connect бачу інструкцію для деплою проекту

![image](https://user-images.githubusercontent.com/75271497/217419378-dc4c2520-e491-46a3-97be-e41c343c5903.png)

Виконуємо команду chmod 400 maskerano.pem для того щоб запевнитися що наш ключ не є загально доступним Підключаємося до EC2 за допомогою ssh -i "sonic.pem"
![image](https://user-images.githubusercontent.com/75271497/217419633-a9baff0b-9014-4f59-bba9-c02acf7135c1.png)

Запускаємо сервіс systemctl start httpd.service
![image](https://user-images.githubusercontent.com/75271497/217419696-41e1f2af-2cb2-4bd4-81b9-d82cf45d2081.png)

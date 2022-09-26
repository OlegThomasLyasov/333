# My project
## Список эмоций
* злость
* любовь :kissing_heart:
* радость :smiley:
* гнев :persevere:
* счастье
* умиротворение
* энтузиазм
* восхищение
* мотивированность :grinning:


![картинка](https://berez.org/uploads/posts/2020-03/1584418352_s1200.jpg)

# Видео
[![спокойная музыка](https://www.shkolazhizni.ru/img/content/i187/187867_or.jpg)](https://www.youtube.com/watch?v=S7U8ExhCK50)

---
## Использование HTML тегов
### **Я пошел <br> гулять**

---

# Решение заданий на Pethon

1. Задача «Шеренга»

'''python

    people = [int(n) for n in input().split()]

    Petya = int(input())

    for i in range(len(people)):

    if Petya <= people[i]:

        if i == len(people)-1:
            print(i+2)
        else:
            continue
    else:

        print(i+1)
        break

2. Задача «Количество элементов, равных максимуму»

'''python

    number = int(input())

    max = 0 

    quantity = 0

    while (number != 0):

        if ( number > max):
            max = number
            quantity = 1
        elif ( number == max):
            quantity += 1
        number = int(input())
    print (quantity)



3. Задача «Степень двойки»

'''python

    n = int(input())
    number = 1
    power = 0
    while number*2 <= n:
        number *= 2
        power += 1
    print(power, number)    

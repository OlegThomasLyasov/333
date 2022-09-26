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

# Решение задач

Задача «Шеренга»

```python
array = [int(n) for n in input().split()]
k = int(input())
for i in range(len(array)):
  if k <= array[i]:
    if i == len(array)-1:
        print(i+2)
    else:
        continue
  else:
    print(i+1)
    break
```

Задача «Степень двойки»

```python
n = int(input())
number = 1
power = 0
while number*2 <= n:
  number *= 2
  power += 1
print(power, number)
```

Задача «Количество элементов, равных максимуму»

```python
a = int(input())
max = 0
amount = 0
while a != 0:
  if a > max:
    max = a
    amount = 1
  elif a == max:
    amount += 1 
  a = int(input())
print(amount)
```
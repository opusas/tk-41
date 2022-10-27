# Звіт до роботи
## Тема: _Основи Python_
### Мета роботи: _Опанувати основи Phyton_
---
### Виконання роботи
- Результати виконання завдання *1...N*;
    1. Познайомився з основними типами даних
    1. Вивів вбудовані константи
    Отримано наступні результати:
     Перша константа False
     Друга константа True
    1. Вивів результат роботи вбудованих функцій
    Отримано наступні результати:
    45.4 рівне 45.4
    34.7 рівне 34.7
    1. Познайомився з циклами
    Отримано наступні результати:
    Під номером 0 є буква a
    Під номером 1 є буква b
    Під номером 2 є буква c
    Під номером 3 є буква d
    Під номером 4 є буква e
    Під номером 5 є буква f
    1. Познайомився з розгалуженнями
    Отримано наступні результати:
    Значить А=True
    Значить B=False
    1. Ознайомився з конструкцією try-> except-> finally.
    Отримано наступні результати:
    Ділимо довільне число на змінну А 2.0
    Поділили
    1.Ознайомився з контекст-менеджером with.
    Програма вивела значення:# tk-41 For Bogdan Bugyl
    1. Познайомився з лямбда-виразом
    Програма вивела значення:
    функція: <function <lambda> at 0x0000020E9ABA3E20>
    Отримано наступні результати:
    виклик функції: Улюблена домашня тварина: Кіт рижий

- вставлені рисунки (скріншоти екрана або фотографії виконаного завдання у зошиті);
https://github.com/opusas/tk-41/blob/main/lab2/pictures/picture2.PNG
https://github.com/opusas/tk-41/blob/main/lab2/pictures/picture3.PNG
https://github.com/opusas/tk-41/blob/main/lab2/pictures/picture4.PNG
https://github.com/opusas/tk-41/blob/main/lab2/pictures/picture5.PNG
https://github.com/opusas/tk-41/blob/main/lab2/pictures/picture6.PNG
https://github.com/opusas/tk-41/blob/main/lab2/pictures/picture7.PNG
https://github.com/opusas/tk-41/blob/main/lab2/pictures/picture8.PNG
https://github.com/opusas/tk-41/blob/main/lab2/pictures/picture9.PNG



- вставлений код / текстовий або числовий результат / інші результати:
```python
a = "Текстова змінна"
b = 2  # числова Змінна
c = ["a", 2, 3.32, "Слово"] # List
d = {"a": "Слово", "b": 2} # Dict
e = ("a", ) # Tuple
f = {"ss", } # Set

print("Перша константа",False)
print("Друга константа",True)

print(abs(-45.4), f"рівне {abs(45.4)}")
print(abs(-34.7), f"рівне {abs(34.7)}")

letters = ["a", "b", "c","d", "e", "f"]
for i in range(len(letters)):
    print(f"Під номером {i} є буква {letters[i]}")

    A = True
B = False
print("Значить А=True" if A else "Значить А=False")
print("Значить B=True" if B else "Значить B=False")

A = 5
try:
    print("Ділимо довільне число на змінну А", 10/A, )
except Exception as e:
    print(e)
finally:
    print("Поділили")

with open("README.md", "r") as f:
    for line in f:
        print(line)

this_is_lambda = lambda first, last: f'Улюблена домашня тварина: {first} {last}'
print("функція:", this_is_lambda)
print("виклик функції:", this_is_lambda('Кіт', 'рижий'))
```
### Висновок: 
> у висновку потрібно відповісти на запитання:
- :question: Що зроблено в роботі; - програми на пайтон
- :question: Чи досягнуто мети роботи; - Досягнуто
- :question: Які нові знання отримано; - Робота з Github та Python
- :question: Чи вдалось відповісти на всі питання задані в ході роботи; - так
- :question: Чи вдалося виконати всі завдання; - так
- :question: Чи виникли складності у виконанні завдання; - ні
- :question: Чи подобається такий формат здачі роботи (Feedback); - так
- :question: Побажання для покращення (Suggestions); - немає
---
# Звіт до роботи
## Тема: _Робота у віртуальних середовищах_
### Мета роботи: _Отримати навички роботи з віртуальними середовищами_
---
### Виконання роботи
- Результати виконання завдання *1...N*;
- Основи роботи зі сторонніми бібліотеками
1. Команди вивели такі значення:
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/1.pip_v.PNG "скрін 1")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/2.install_request.PNG "скрін 2")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/3.python.PNG "скрін 3")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/4.pip%20show%20requests.PNG "скрін 4")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/5.%20pip%20install%20reqests.PNG "скрін 5")
- Робота у віртуальному середовищі 
1. Команди вивели таке значення:
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/6.source.PNG "скрін 6")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/7.source.PNG "скрін 7")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/8.source.PNG "скрін 8")

2. Остання команди вивела:

![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/8.source.PNG "скрін 9")

- Робота з Pipenv
1. Команди вивели такі значення:

![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/9.install%20pipnv.PNG "скрін 10")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/10.pipnv%20help.PNG "скрін 11")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/11.pipnv%20help%202.PNG "скрін 12")
![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/12.pipnv%20python.PNG "скрін 13")
    
2. Створив файл пайтон та записав в нього наступну програму:
```python
import requests

response = requests.get('https://httpbin.org/')
for line in response.iter_lines():
    print(line)
```
3. Програма вивела таке значення:

![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/13.code.PNG "скрін 14")
8. Змінив Python інтерпретатор. 

- Робота зі змінними середовища:
1. Створив файл .env та виконав код:

![alt text](https://github.com/opusas/tk-41/blob/main/lab4/pictures/14.env%20code.PNG "скрін 15")
2. Буде помилка
- вставлений код / текстовий або числовий результат / інші результати:
```python
import requests

response = requests.get('https://httpbin.org/')
for line in response.iter_lines():
    print(line)


    import os
os.environ['HELLO']
```
### Висновок: 
> у висновку потрібно відповісти на запитання:
- :question: Що зроблено в роботі; - програми на пайтон
- :question: Чи досягнуто мети роботи; - Досягнуто
- :question: Які нові знання отримано; - Робота з Github та Python, віртуальними середовищами
- :question: Чи вдалось відповісти на всі питання задані в ході роботи; - так
- :question: Чи вдалося виконати всі завдання; - так
- :question: Чи виникли складності у виконанні завдання; - ні
- :question: Чи подобається такий формат здачі роботи (Feedback); - так
- :question: Побажання для покращення (Suggestions); - немає
---    
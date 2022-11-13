# Звіт до роботи
## Тема: _Основи ООП_
### Мета роботи: _Опанувати основи ООП_
---
### Виконання роботи
- Результати виконання завдання *1...N*;
    1. Створив перший class
    1. Створив два пайтон файли
    1. Скопіював пайтон код наведений внизу у мої файли та виконав їх
    1. програма вивела таке значення:
![alt text]( "скрін 1")
   1. Модифікував програму додавши свої імена в список
    1. Програма вивела таке значення:
![alt text]( "скрін 2")
   1. Відповіді на питання:
    1.  Чому коли передаємо значення None створюється обєкт з іменем Anonymous?  
    Бо так написано конструкторі
    2. - Як змінити текст привітання при виклику методу say_hello()? Допишіть цю частину коду.  
    
    python
    say_hello("Hello World!")
    

- вставлений код / текстовий або числовий результат / інші результати:
```python
class MyName:
    """Опис класу / Документація
    """
    total_names = 0 #Class Variable

    def __init__(self, name=None) -> None:
        self.name = name if name is not None else self.anonymous_user().name #Class attributes / Instance variables
        MyName.total_names += 1 #modify class variable
        self.my_id = self.total_names

    @property
    def whoami(self): 
        """Class property
        return: повертаємо імя 
        """
        return f"My name is {self.name}"
    
    @property
    def my_email(self) -> str:
        """Class property
        return: повертаємо емейл
        """
        return self.create_email()
    
    def create_email(self) -> str:
        """Instance method
        """
        return f"{self.name}@itcollege.lviv.ua"

    @classmethod
    def anonymous_user(cls):
        """Classs method
        """
        return cls("Anonymous")
    
    @staticmethod
    def say_hello(message="Hello to everyone!"):
        """Static method
        """
        return f"You say: {message}"


print("Let's Start!")

names = ("Ostap", "Oleksandr", "Andriy", None)
all_names = {name: MyName(name) for name in names}

for name, me in all_names.items():
    print(f"""{">*<"*20}
This is object: {me} 
This is object attribute: {me.name} / {me.my_id}
This is {type(MyName.whoami)}: {me.whoami} / {me.my_email}
This is {type(me.create_email)} call: {me.create_email()}
This is static {type(MyName.say_hello)} with defaults: {me.say_hello()} 
This is class variable {type(MyName.total_names)}: from class {MyName.total_names} / from object {me.total_names}
{"<*>"*20}""")

print(f"We are done. We create {me.total_names} names! ??? Why {MyName.total_names}?")
```
### Висновок: 
> у висновку потрібно відповісти на запитання:
- :question: Що зроблено в роботі; - програми на пайтон
- :question: Чи досягнуто мети роботи; - Досягнуто
- :question: Які нові знання отримано; - Робота з Github та Python class
- :question: Чи вдалось відповісти на всі питання задані в ході роботи; - так
- :question: Чи вдалося виконати всі завдання; - так
- :question: Чи виникли складності у виконанні завдання; - ні
- :question: Чи подобається такий формат здачі роботи (Feedback); - так
- :question: Побажання для покращення (Suggestions); - немає
---
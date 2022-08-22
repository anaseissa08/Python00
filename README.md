# Python00
py

numbers = [5,2,5,2,2]
for item in numbers:
    print("*"*item)
    
    names = ["ahmed","sultan","omer","eissa"]
print(names[2])


numbers = [3,6,20,8,4,10]
max = numbers[0]
for number in numbers:
    if number > max:
        max = number
print(max)

matrix = [
    [1,2,3],
    [4,5,6],
    [7,8,9]
]
for row in matrix:
    for item in row:
        print(item)
        
        numbers = [5,2,1,5,7,4]
numbers.sort()
numbers2 = numbers.append(2)
print(numbers)
print(numbers2)

message = input(">")
words = message.split(' ')
print(words)
emojis = {
    ":)":""
}

def greet ():
    print("hi there")
    print('welcome')

print("start")
greet()

def greet (name):
    name = "anas"
    print(f"hi there{name}")
    print('welcome')

print("start")
greet("anas")


def name (fname , lname):
    print(f"hi {fname}  {lname}")
    print("wellcome")

print("start")
name("anas","eissa")

def calc(total,shipping,discount):
    print(total+shipping+discount)

calc(1,1,1)

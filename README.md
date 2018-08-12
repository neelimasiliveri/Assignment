# Assignment
Python-1 Assignment
# # first question
def fib(nterms):
n1 = 0
n2 = 1
count = 0
    while count < nterms:
       print(n1,end=' , ')
       nth = n1 + n2
       n1 = n2
       n2 = nth
       count += 1
    return
a = lambda nterms: fib(nterms)
print(a(6))
print('\n')

# #second question
num = eval(input("enter a value: "))
print(type(num))

print('\n')

# # third question
Xnum = input("enter a number: ")
num = int(Xnum)
if num >= 0:
    while True:
        print("I Love You")
else:
    print("Dude!!!, you have entered a negative number")

print('\n')

# # fourth question

num=1
for i in range(2,22,2):
    num*=i
print(num)


print('\n')

# # fifth question

string = 'innovationwithpython'
x = slice(0,20,2)
print(string[x])

print('\n')

# # sixth question

my = []
for i in range(1,50):
    if i % (2 and 6) == 0:
        my.append(str(i))

y = list(map(int, my))
a = y[-3:]
print(a)
b =sum(a)
print(b)

print('\n')

# # seventh question

x = []
for i in range(1,61,2):
     x.append(str(i))

y = list(map(int, x))
b =sum(y)
print(b)

print('\n')

# # Eight question
new_list = [1,2,3,4,5,6,["Riyaz","UI","Haque",7],8,9,10]
print(new_list[-4]) - ['Riyaz', 'UI', 'Haque', 7]
print(new_list[4]) - 5
print(new_list[6][1]) - UI
new_list.append(["new"])
print(new_list) - [1, 2, 3, 4, 5, 6, ['Riyaz', 'UI', 'Haque', 7], 8, 9, 10, ['new']]

# # Tenth Question
Negative Indexing: A negative index accesses elements from the end of the list counting backwards. That means it starts traversing from right to left. Such that array[-1] will be the right most element and array[-2] will be the second last element.

Packing and Unpacking : When we don’t know how many arguments need to be passed to a python function, we can use Packing to pack all arguments in a tuple. We can use * to unpack the list so that all elements of it can be passed as different parameters.

Mutable and Immutable: A mutable object can be changed after it is created, and an immutable object can't. Objects of built-in types like (int, float, bool, str, tuple, unicode) are immutable. Objects of built-in types like (list, set, dict) are mutable. Custom classes are generally mutable.

Append and Extend: Append adds its argument as a single element to the end of a list. The length of the list itself will increase by one. Extend iterates over its argument adding each element to the list, extending the list. The length of the list will increase by however many elements were in the iterable argument. In simple words, Append adds an element to a list, and extend concatenates the first list with another list.

Pickling and Unpickling: These are used for serializing and de-serializing a Python object structure. Pickling  "serialises" the object first before writing it to file. Pickling is a way to convert a python object (list, dict, etc.) into a character stream. The idea is that this character stream contains all the information necessary to reconstruct the object in another python script. Unpickling means it "de-serialises" the object.

# # Eleventh  question
import valueone,valuetwo, value3
d = valueone*valuetwo*value3
print(d)

# # twelfth  question

i=dict()
n = eval(input("enter a end value for a range:"))
for x in range(1,n):
    i[x]=x*x
print(i)

print('\n')
# # Thirteenth Question
Split Function: Split function is used to break a large string into small strings which exactly acts opposite to concatenation. After breaking the large string it adds the data to the smaller strings using a defined seperator, if there is no seperator defined in the function, whitespace will be used by default.

# # Fourteenth question

values = input("Input some comma seprated numbers : ")
x = values.split(",")
y = tuple(x)
print(x)
print(y)

print('\n')

# # fifteen question

x = input("enter any word of your choice: ")
print(x)
y = x[::-1]
print(y)

print('\n')

# # sixteen question

Xx = input("Enter first word of your choice:")
x =set(Xx)
Yy = input("Enter second word of your choice:")
y =set(Yy)

a = y.intersection(x)
print(a)

print('\n')

# # seventeen question


sen = input("enter a sentence of your choice:")
x = [len(x) for x in sen.split()]
print(x)

print('\n')

# # Eighteen question


dic1 = {1:'a', 2:'b'}
dic2 = {3:'c', 4:'d'}
dic3 = {5:'e', 6:'f'}

dic1.update(dic2)
x = dic1
x.update(dic3)
print(x)

print('\n')

# # Ninteen question

Memory management involves a private heap containing all Python objects and data structures. The management of this private heap is ensured internally by the Python memory manager. The Python memory manager has different components which deal with various dynamic storage management aspects, like sharing, segmentation, preallocation or caching.

# # Twentieth Question
Difference between Range and XRange: The only difference is that range returns a Python list object and xrange returns an xrange object. It means that xrange doesn't actually generate a static list at run-time like range does. It creates the values as you need them with a special technique called yielding.

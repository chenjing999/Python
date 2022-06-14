### Complete the code to return the output

def make_dict(a,b):
def make_dict(**kwargs):
    return kwargs

make_dict(a = 1, b = 2)

Expected Output

{'a': 1, 'b': 2}


### The function sample has been written using a for loop, as shown below. Using a list comprehension, create a more efficient version of this function.

def sample(n):
    x = []
    for i in range(n):
        x.append(random.random())
    return x
Complete the code to return the output
import random
random.seed(2427)

def efficient_sample(n):
  x = [x for x in n]
  x = [random.random() for i in range(n)]
  return x

efficient_sample(20)


### Complete the statement using a list comprehension such that it matches the output.
Complete the code to return the output
[i for i in range(5) print(i)]
[i for i in range(5) if i > 2]

Expected Output

[3, 4]


### Add the following item to the book dictionary:

format: paperback
Complete the code to return the output
book = {
    'title': 'The Giver',
    'author': 'Lois Lowry',
    'rating': 4.13
}

book.add{'format',paperback}
book['format'] = 'paperback'

book['format']

Expected Output

'paperback'


### Complete the code to return the output
g = lambda : x + y
g = lambda x, y: x + y

g(2,3)

Expected Output

5


### Access the docstrings of the factorial() function.

Complete the code to return the output
def factorial(n):
    """returns n!"""
    return 1 if n < 2 else n * factorial(n-1)

factorial.__doc__

Expected Output

'returns n!'


### Complete the code to return the output
w = 'python'

w_iterator = iter(w)

char(w_iterator)
next(w_iterator)

Expected Output

'p'

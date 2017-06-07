```# AI2-2017
String1.py

donuts
 OK  got: 'Number of donuts: 4' expected: 'Number of donuts: 4'
 OK  got: 'Number of donuts: 9' expected: 'Number of donuts: 9'
 OK  got: 'Number of donuts: many' expected: 'Number of donuts: many'
 OK  got: 'Number of donuts: many' expected: 'Number of donuts: many'
both_ends
 OK  got: 'spng' expected: 'spng'
 OK  got: 'Helo' expected: 'Helo'
 OK  got: '' expected: ''
 OK  got: 'xyyz' expected: 'xyyz'
fix_start
 OK  got: 'ba**le' expected: 'ba**le'
 OK  got: 'a*rdv*rk' expected: 'a*rdv*rk'
 OK  got: 'goo*le' expected: 'goo*le'
 OK  got: 'donut' expected: 'donut'
mix_up
 OK  got: 'pox mid' expected: 'pox mid'
 OK  got: 'dig donner' expected: 'dig donner'
 OK  got: 'spash gnort' expected: 'spash gnort'
 OK  got: 'fizzy perm' expected: 'fizzy perm'
>>> 

String2.py
verbing
 OK  got: 'hailing' expected: 'hailing'
 OK  got: 'swimingly' expected: 'swimingly'
 OK  got: 'do' expected: 'do'
not_bad
 OK  got: 'This movie is good' expected: 'This movie is good'
 OK  got: 'This dinner is good!' expected: 'This dinner is good!'
 OK  got: 'This tea is not hot' expected: 'This tea is not hot'
 OK  got: "It's bad yet not" expected: "It's bad yet not"
front_back
 OK  got: 'abxcdy' expected: 'abxcdy'
 OK  got: 'abcxydez' expected: 'abcxydez'
 OK  got: 'KitDontenut' expected: 'KitDontenut'
>>> 

List1.py
match_ends
 OK  got: 3 expected: 3
 OK  got: 2 expected: 2
 OK  got: 1 expected: 1
front_x
 OK  got: ['xaa', 'xzz', 'axx', 'bbb', 'ccc'] expected: ['xaa', 'xzz', 'axx', 'bbb', 'ccc']
 OK  got: ['xaa', 'xcc', 'aaa', 'bbb', 'ccc'] expected: ['xaa', 'xcc', 'aaa', 'bbb', 'ccc']
 OK  got: ['xanadu', 'xyz', 'aardvark', 'apple', 'mix'] expected: ['xanadu', 'xyz', 'aardvark', 'apple', 'mix']
sort_last
 OK  got: [(2, 1), (3, 2), (1, 3)] expected: [(2, 1), (3, 2), (1, 3)]
 OK  got: [(3, 1), (1, 2), (2, 3)] expected: [(3, 1), (1, 2), (2, 3)]
 OK  got: [(2, 2), (1, 3), (3, 4, 5), (1, 7)] expected: [(2, 2), (1, 3), (3, 4, 5), (1, 7)]
>>> 

List2.py
remove_adjacent
 OK  got: [1, 2, 3] expected: [1, 2, 3]
 OK  got: [2, 3] expected: [2, 3]
 OK  got: [] expected: []
linear_merge
  OK  got: ['aa', 'bb', 'cc', 'xx', 'zz'] expected: ['aa', 'bb', 'cc', 'xx', 'zz']
  OK  got: ['aa', 'bb', 'cc', 'xx', 'zz'] expected: ['aa', 'bb', 'cc', 'xx', 'zz']
  OK  got: ['aa', 'aa', 'aa', 'bb', 'bb'] expected: ['aa', 'aa', 'aa', 'bb', 'bb']
>>> 

Lab2.py
>>> helloWorld()
Hello, World!
>>> ticTac()
   |  |   
 --------
   |  |   
 --------
   |  |  
>>> superTicTac()
  |  |  H  |  |  H  |  |
--+--+--H--+--+--H--+--+--
  |  |  H  |  |  H  |  |
--+--+--H--+--+--H--+--+--
  |  |  H  |  |  H  |  |
========+========+========
  |  |  H  |  |  H  |  |
--+--+--H--+--+--H--+--+--
  |  |  H  |  |  H  |  |
--+--+--H--+--+--H--+--+--
  |  |  H  |  |  H  |  |
========+========+========
  |  |  H  |  |  H  |  |
--+--+--H--+--+--H--+--+--
  |  |  H  |  |  H  |  |
--+--+--H--+--+--H--+--+--
  |  |  H  |  |  H  |  |  
>>> fizz()
234168
>>> collatz(13)
10
>>> converter()
Temperatura F? 212
100.0 stopni Celsjusza
>>> lists()
[1, 0, 0]
['a', '', '']
[[1], [1], [1]]
>>> lists2()
[1, 0, 0]
['a', '', '']
[[1], [], []]
>>> gcd(8,32)
8
>>> flip_dict({"CA": "US", "NY": "US", "ON": "CA"})
{'CA': ['ON'], 'US': ['CA', 'NY']}
>>> comprehensions_read()
[None, None, None]
[[3, 2, 1, 12], ['a', 'b', 'c', 'aaaa'], [('do',), ['re'], 'mi', ('do', 'do', 'do', 'do')]]
['Y', 'O', 'N']
{8, 2, 3, 5}
>>> comprehensions_write()
2*x +1
[0, 1, 2, 3]
[1, 3, 5, 7]


Podzielniki 3
[3, 5, 9, 8]
[True, False, True, False]


Zaczyna się na TA
['TA_sam', 'TA_guido', 'student_poohbear', 'student_htiek']
['sam', 'guido']


Duże pierwsze litery
['apple', 'orange', 'pear']
['A', 'O', 'P']


Jeżeli jest litera 'p'
['apple', 'orange', 'pear']
['apple', 'pear']


Owoc z jego długością krotka
['apple', 'orange', 'pear']
[('apple', 5), ('orange', 6), ('pear', 4)]


Owoc z jego długością (słownik)
['pear', 'orange', 'apple']
{'apple': 5, 'pear': 4, 'orange': 6}

I love Python!
Keyword arguments are great!!!!
I guess Java is okay...
LET'S GO STANFORD!!
Average of first 10 primes is 12.9
=========================
| shirt_color |    pink |
| last_name   | Redmond |
| first_name  |     Sam |
=========================
==================================
|           album |     1989     |
| artist_fullname | Taylor $wift |
|            song |    Style     |
==================================


def print_two(a,b):
    print("Arguments: {0} and {1}".format(a,b))

    print_two() => brakuje dwóch argumentów
    print_two(4,1) => Arguments: 4 and 1
    print_two(41) => brak argumentu b
    print_two(a=4, 1) => błąd
    print_two(4, a=1) => podwójny argument a
    print_two(4, 1, 1) => za dużo argumentów
    print_two(b=4, 1) => błąd
    print_two(a=4, b=1) => Arguments: 4 and 1
    print_two(b=1, a=4) => Arguments: 4 and 1
    print_two(1, a=1) => podwójnie zadeklarowany argument a
    print_two(4, 1, b=1) => podwójnie zadeklarowany argument b

def keyword_args(a, b=1, c='X', d=None):
    print("a:", a)
    print("b:", b)
    print("c:", c)
    print("d:", d)

    keyword_args(5)
    a: 5
    b: 1
    c: X
    d: None
    keyword_args(a=5)
    a: 5
    b: 1
    c: X
    d: None
    keyword_args(5,8)
    a: 5
    b: 8
    c: X
    d: None
    keyword_args(5,2,c=4)
    a: 5
    b: 2
    c: 4
    d: None
    keyword_args(5,0,1)
    a: 5
    b: 0
    c: 1
    d: None
    keyword_args(5,2,d=8,c=4)
    a: 5
    b: 2
    c: 4
    d: 8
    keyword_args(5,2,0,1,"") => BŁĄD - za dużo argumentów
    keyword_args(c=7,1) => BŁĄD - positional argument follows keyword argument
    keyword_args(c=7,a=1)
    a: 1
    b: 1
    c: 7
    d: None
    keyword_args(5,2,[],5)
    a: 5
    b: 2
    c: []
    d: 5
    keyword_args(1,7,e=6) => BŁĄD - argument e nie istnieje
    keyword_args(1,c=7)
    a: 1
    b: 1
    c: 7
    d: None
    keyword_args(5,2,b=4) => BŁĄD - podwójna deklaracja argumentu b

def variadic(*args, **kwargs):
    print("Positional:", args)
    print("Keyword:", kwargs)
    
    variadic(2,3,5,7)
    Positional: (2, 3, 5, 7)
    Keyword: {}
    variadic(1,1,n=1)
    Positional: (1, 1)
    Keyword: {'n': 1}
    variadic(n=1,2,3) => BŁĄD - liczba pozycyjna umiejscowiona za słowem kluczowym
    variadic()
    Positional: ()
    Keyword: {}
    variadic(cs="Computer Science", pd="Product Design")
    Positional: ()
    Keyword: {'pd': 'Product Design', 'cs': 'Computer Science'}
    variadic(cs="Computer Science", cs="CompSci", cs="CS") => BŁĄD - powtarzanie argumentów
    variadic(5,8,k=1,swap=2)
    Positional: (5, 8)
    Keyword: {'swap': 2, 'k': 1}
    variadic(8, *[3, 4, 5], k=1, **{'a':5, 'b':'x'})
    Positional: (8, 3, 4, 5)
    Keyword: {'a': 5, 'b': 'x', 'k': 1}
    variadic(*[8, 3], *[4, 5], k=1, **{'a':5, 'b':'x'})
    Positional: (8, 3, 4, 5)
    Keyword: {'a': 5, 'b': 'x', 'k': 1}
    variadic(*[3, 4, 5], 8, *(4, 1), k=1, **{'a':5, 'b':'x'})
    Positional: (3, 4, 5, 8, 4, 1)
    Keyword: {'a': 5, 'b': 'x', 'k': 1}
    variadic({'a':5, 'b':'x'}, *{'a':5, 'b':'x'}, **{'a':5, 'b':'x'})
    Positional: ({'a': 5, 'b': 'x'}, 'a', 'b')
    Keyword: {'a': 5, 'b': 'x'}
    
def speak_excitedly(a,b=1, c=False):
    a += '!' * b
    if (c==True):
        print(a.upper())
    else:
        print(a)
        
    speak_excitedly("Tymek", 2, True) => TYMEK!!

def average(*a):
    if not a:
        print(None)
    else:
        print(sum(a)/len(a))
   
    average() => None
    average(1,76,23,5) => 26.25

def say_hello():
    print("Hello!")

    print(say_hello()) => Hello!

def echo(arg=None):
    print("arg:", arg)
    return arg

    print(echo()) => None
    print(echo(5)) => arg: None

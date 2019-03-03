
# Print with .format() (Varianta pentru smecheri)
# 
# 
# 

# Old
print '%s %s' % ('one', 'two')

# New
print('{} {}'.format('one', 'two'))

# Old
print '%d %d' % (1, 2)

# New
print('{} {}'.format(1, 2))
#
#
#
# Rulati comenzile si observati, pe rand, diferentele:
print("{1} {0}".format("one", "two"))

print('{:>10}'.format('test'))


# Challenge
- Construiti un triunghi de "*" de dimensiune n, folosind trucurile de mai sus.

#
#
#
# Sa luam decizii bune cu if-uri

x = 1
if x == 1:
    print("Merge")
# 
if x is 1:
    print("Merge si asa")
# 
if x is "1":
    print("Cum de merge?")
# 
# Bonus pentru if
#
if 1 == x:
    print("Merge?")
    
if x = 1:
    print("Merge in Python?")

# 
# Challenge-uri
- Construiti o functie recursiva care calculeaza factorialul unui numar n, dat de la tastatura.
- Creati o functie care sa returneze, recursiv, elementul n, dat de la tastatura, din sirul lui Fibonacci.
# 
#
#
# Viata e ca o Lista de treburi..
#
specialistii_python = ["Andrei", "Bogdan", "David", "Robert", "Stelarian", "Tudor"]

print("Cine-o sa fie specialisti in Python?", specialistii_python)


# Task-uri:
- Incercati sa printati doar numele vostru.
- Schimbati numele vostru din lista, cu ziua de nastere si afisati.
- Cum adaugam un element nou in lista? de exemplu, numele fraierului care preda la tabla.
- Putem verifica daca n-am uitat pe cineva in lista, iar daca nu e sa-l adaugam?
- Putem sa ne clonam? 
- Putem adauga in incaperea in care sutem o noua lista de oameni ce vor sa devina specialisti Python? ( 2 modalitati)
- De curiozitate, cati oameni sunt in incaperea aceasta?
#
#
# 
task_de_term = [ ]
print("Ce task-uri mai aveti?: ", task_de_term)
#
# If-uri, loop-uri, bool-uri, liste, adaptere, sololearn, completare quizz de sfarsit
#
#
#

# Quizz:
#
#
#
Quizz 1:

- spam = "7
- spam += "0"
- eggs = int(spam) + 3
- print(float(eggs))

#
#
#
Quizz 2:

- word = input("Enter a word: ")
- print("word" + "candy_shop")
#
#
#
Quizz 3:

- x = 5
- y = x + 3
- y = int(str(y) + "2")
- print(y)
#
#
#
Quizz 4:

- x = 3
- num = 17
- print(num % x)
#
#
#
Quizz 5: Care din numele de variabile de mai jos sunt/este valide/a in Python?

- a variable name
- A_VARIABLE_NAME
- a-vaiable_name
- a+variable+name
#
#
#
Quizz 6:

- print( 8.7 <= 8.70 )
#
#
#
Quizz 7:
- nums = [1, 2, 3]
- print(not 4 in nums)
- print(4 not in nums)
- print(not 3 in nums)
- print(3 not in nums)
#
#
#
Quizz 8:
- letters = ['p', 'q', 'r', 's', 'p', 'u']
- print(letters.index('r'))
- print(letters.index('p'))
- print(letters.index('z'))









number = 154
print(bin(number))
print(hex(number))
print(oct(number))


print(ord(" "))


a = []
print(bool([]))
a.append(5)
print(bool(set()))
print(bool(dict()))

vowels = 'aeiou'
letter = "a"
if letter in vowels : print('야호')


import random

limits =20
tweet = "pass" * random.randint(1, 10)
diff = limits-len(tweet)
if diff >= 0:
    print(tweet)
else: print(f'글자수 {abs(diff)}초과')



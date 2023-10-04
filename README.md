# assignmeen
def last(n):
    return n[-1]  
  
def sort(tuples):
    return sorted(tuples, key=last)
  
a=[(1, 3), (3, 2), (2, 1)]
print("Sorted:")
print(sort(a))


asciidict = dict()

for i in range(97,123):

asciidict[chr(i)]=i

key = asciidict.keys()

value = asciidict.values()

print(‘ASCII Dict:’, asciidict)

n = str(input(‘enter the key—>’))

print(‘key:’, n)

print(value:, asciidict[n])

#1.Converting an integer to a decimals
import decimal
integer = 10
print(decimal.Decimal(integer))
print(type(decimal.Decimal(10.0)))




#2.Converting a string of integers into a decimals
import decimal
string = '12345'
print(decimal.Decimal(string))
print(type(decimal.Decimal(string)))




#3.Reverse a string using an Extended slicing technique 
string = "Python Programming"
print(string[::-1])



#4.Counting VOWELS in a Given word
vowel = ['a', 'e', 'i', 'o', 'u']
word = "Programming"
count = 0
for character in word:
    if character in vowel:
        count += 1
        print(count)
      


#5.Counting CONSONANTS in a given word
vowel = ['a', 'e', 'i', 'o', 'u']
word = "Programming"
count = 0
for character in word:
    if character not in vowel:
        count += 1
        print(count)
        
      
        
#6.Counting the number of occurances of a character in a string 
word = "Programming"
character = 'g'
count = 0
for i in word:
    if i  == character:
        count+=1
print(count)        
        
        
        
        
#7.Writing Fibonacci series
fib = [0,1]
#Range starts from 0 by default
n=5
for i in range(n):
    fib.append(fib[-1]+fib[-2])
#Converting the list of integers to string
print(','.join(str(e)for e in fib))



#8.Finding the maximum number in a list
numberList = [12, 3, 55, 23, 6, 78, 33, 4]
max = numberList[0]
for num in numberList:
    if max < num:
        max = num
print(max)        




#9.Finding the minimum number in a list
numberList = [12, 3, 55, 23, 6, 78, 33, 4]
min = numberList[0]
for num in numberList:
    if min > num:
        min = num
print(min)




#10.Finding the middle element in a list
numList = [12, 3, 55, 23, 6, 78, 33, 5]
midElement = int((len(numList)/2))
print(numList[midElement])




#11.Converting a list into a string
list = ["P", "Y", "T", "H", "O", "N"]
string = "".join(list)

print(string)
print(type(string))



#12.Adding two list elements together
lst1 = [1,2,3]
lst2 = [4,5,6]
res_lst  = []
for i in range(0, len(lst1)):
    res_lst.append(lst1[i] + lst2[i])
print(res_lst)        
        
        

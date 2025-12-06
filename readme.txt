1.What should your program print to the output?
my_string = "Hello, World!"
print(my_string)
output:
Hello, World!




2.What output should be printed for the given number based on the Weird/Not Weird rules?
n = int(input())
if n % 2 != 0:
    print("Weird")
elif 2 <= n <= 5:
    print("Not Weird")
elif 6 <= n <= 20:
    print("Weird")
else:  # n is even and > 20
    print("Not Weird")
output:24
Not Weird


3.Print the sum, difference, and product of the two integers provided as input

if __name__ == '__main__':
    a = int(input())
    b = int(input())
    print(a+b)
    print(a-b)
    print(a*b)

output: 3
 2
5
1
6


4.Print a // b and a / b for the given integers
if __name__ == '__main__':
    a = int(input())
    b = int(input())
    print(a//b)
    print(a/b)

output: 4
 3
1
1.3333333333333333



5.Print the square of each integer i for all i from 0 to n-1
if __name__ == '__main__':
    n = int(input())
    for i in range(n):
      print(i*i)


output: 5
0
1
4
9
16


6.Does the given year satisfy the leap-year rules: divisible by 4, not divisible by 100 unless also divisible by 400?
def is_leap(year):
    leap = False
    if (year%400==0) or (year%4==0 and year%100!=0):
        return True
    else:
        return leap

year = int(input())
print(is_leap(year))

output:1990
False


7.Print Consecutive Numbers as a String
if __name__ == '__main__':
    n = int(input())
    string=''
    for i in range(1,n+1):
      string=string+str(i)
    print(string)

output:3
123


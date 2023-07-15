# Assignment-7-placement-JPR
# 1. Display N prime numbers from X. Input N=3, X=10 Output: 11 13 17


# 2. Find the sum of the array of N elements input: 6   10 12 8 20 30 20 Output: 100

list=[10,45,78,36]
sum=0
for i in list:
    sum+=i
print(sum)
                                                            (OR)
list=[]
n=int(input())
for i in range(0,n):
    t=int(input())
    list.append(t)
sum=0
for j in list:
    sum+=j
print(sum)


# 3. Find the index of first occurrence of X in the array of N elements input:6 10 12 7 12 20 30 12 Output 1

list=[]
n=int(input())
for i in range(0,n):
    t=int(input())
    list.append(t)
m=int(input("position of the element: "))
print(list.index(m))

# 4.Find the index of last occurrence of X in the array of N elements
Input:6
12 7 12 20 30
12
Output
3

def array(arr,n,x):
    if n==0:
        return [-1,-1]
    l=[]
    for i in range(0,n):
        if arr[i]==x:
            l.append(i)
    if len(l)==0:
        return [-1,-1]
    return [l[0], l[-1]]
arr=[10,12,20,20,40]
n=5
x=20
print(array(arr,n,x))

# 5 .Count how many times X is present in the array of N elements 6
20 2 7 12 20 30
20
Output
2
def count(arr,n,x):
    count=0
    for i in arr:
        if i==x:
           count+=1
    print(count)
arr=[20 2 7 12 20 30]
n=6
x=20
print(count(arr,n,x))

# 6. Find the minimum value in the given array of N elements
def getMinMax(arr):
    arr.sort()
    minmax = {"min": arr[0], "max": arr[-1]}
    return minmax
arr = [1000, 11, 445, 1, 330, 3000]
minmax=getMinMax(arr)
print("minimum value is:", minmax["min"])
print("maximum value is:", minmax["max"])


# 7. Find the sum of first X elements and sum of remaining elements in the given N elements array ( X < = N)
6
20 3 7 12 20 30
4
Output: Sum of first 4 elements :42 Sum of remaining elements:50


Here after use function
Practice Functions
Pass the necessary value to the function
and return the result
# 8. Find factorial for a number X and print the result.


# 9. Display N prime number from X .Write and Use findprime(int) function. (refer Q No 1)

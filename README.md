- 👋 Hi, I’m @munni-1
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
munni-1/munni-1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#PROGRAM TO PRINT COUNT OF N PRIME NUMBERS
def isprime(n):
    for i in range (2,n):
        if n%i==0:
            return False
        return True 
n=int(input('enter n:'))
count=0
for i in range(2,n+1):
    if isprime(i):
        count=count+1
        print(i,end=' ')
        print(count)

OUTPUT:
enter n:10
3    1
5    2
7    3
9    4

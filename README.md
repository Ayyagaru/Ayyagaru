### Hi there 👋

<!--
**Ayyagaru/Ayyagaru** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
def isprime(n):
    for i in range(2,n):
        if n%i==0:
            return False
    return True

a=int(input("enter a number")) 
for i in range(a):
          n=int(input('    '))
          s=int(input('    '))
          c=0
          for i in range(n,s+1):
              if n>1:
                  if isprime(i):
                      c=c+1
              else:
                  n=2
          print("prime numbers count",c)

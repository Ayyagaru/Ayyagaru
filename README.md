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
    
n=int(input('enter a number'))
k=97
for i in range(1,n+1):
    for j in range(1,n+1):
        print(chr(k),end=' ')
        k+=1
    print('\n')

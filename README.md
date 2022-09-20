- 👋 Hi, I’m @202201617
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
202201617/202201617 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#202201617 박혜주

#문제1번
a=1
b=2
print (a+b)

#문제3번
A = int(input("숫자를 입력하세요 >> "))                      

if (A > 0):
  if (A <= 30):
    for i in range(1, A+1):
      for j in range(1,i+1):
        print(j, end="")
      print()
  elif (A > 30):
    print("너무 많습니다.")

#문제4번
A = input("숫자를 입력하세요 >> ")
if A.isdecimal():
  A = int(A)
  if (A > 0):
    if (A <= 30):
      for i in range(1, A+1):
        for j in range(1,i+1):
          print(j, end="")
        print()
    elif (A > 30):
      print("너무 많습니다.")
else:
  print("정수로 입력하세요.")

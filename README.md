# 중간고사 프로젝트

>지하철 혼잡도 앱

지하철 혼잡도를 가시적으로 표현하게 만드는 것은 중요하다.
이를 위해선
1. 지하철의 위치를 실시간으로 파악
2. 지하철의 혼잡도를 명확하게 정의할 기준
등이 필요하다.
--------------------------
'''
def add(x, y):
    return x + y
 def subtract(x, y):
    return x - y
 def multiply(x, y):
    return x * y
 def divide(x, y):
    return x / y
 print("사칙연산을 선택 하세요.")
 print("1.더하기")
 print("2.빼기")
 print("3.곱하기")
 print("4.나누기")
 choice = input("선택 하세요(1/2/3/4):")
 num1 = int(input("첫번째 숫자 : "))
 num2 = int(input("두번째 숫자 : "))
 if choice == '1':
    print(num1,"+",num2,"=", add(num1,num2))
 elif choice == '2':
    print(num1,"-",num2,"=", subtract(num1,num2))
 elif choice == '3':
    print(num1,"*",num2,"=", multiply(num1,num2))
 elif choice == '4':
    print(num1,"/",num2,"=", divide(num1,num2))
 else:
    print("잘못된 선택")
    '''
    



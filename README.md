# eos_coding_test
eos coding test for GXC x Decenter.b


- background


1. ethereum smart contract 


2. 이오스 코어가 c++로 작성되어서 블록체인 TPS의 유의미한 개선을 가질 수 있다고 생각하는가? 그렇게 생각한 이유는?

3. 

- Coding test.


1. 다음을 푸시오.

https://programmers.co.kr/learn/courses/30/lessons/12973

2. 
```
#include <iostream>

using namespace std;

typedef int (*ifunc)(int, int);

int process(int a, int b, ifunc f)
{
   return f(a, b);
}

int main()
{
   int a = 10;
   int b = 20;

   // ???를 완성하여 a와 b의 합을 출력하시오
   cout << process(a, b, ???) << endl;
}
```

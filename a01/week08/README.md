# Midterm Exam

## Theory

### 1. `unsigned char`는 ____ bit data type이고 ____ 가지를 나타낼 수 있다.

### 2. `char`의 범위는 ____부터 ____까지이다.

### 3. `exp()` 함수와 `time()` 함수를 사용하기 위해 불러와야 하는 헤더파일을 쓰시오.

### 4. 다음 자료형 중 return 값으로 가질 수 없는 것을 고르시오.

A. `int`
B. `void`
C. `real`
D. `char`
E. `double`

### 5. 다음 함수 정의 중 가장 올바른 것을 고르시오.

A.
  ```cpp
  void function() {
  };
  ```
B.
  ```cpp
  int function(int x){
    return x + 1
  }
  ```
C.
  ```cpp
  void function(x){
    cout << "Hello World!" << endl
  }
  ```
D.
  ```cpp
  void function(x) {
    cout << "Hello World!" << endl;
  }
  ```

### 6. 다음 function call 중 가장 올바른 것을 고르시오.

A. `int function(int a, int b);`
B. `function(int a, int b);`
C. `function;`
D. `function();`

### 7. 상수를 사용하는 두 가지 방법과 상수를 썼을 때 좋은 이유를 2가지 이상 적으시오.

### 8. call by reference와 call by value의 차이점을 쓰시오.

### 9. `while`문과 `do while`문의 차이점을 쓰시오.

### 10. `break`문과 `continue`문의 차이점을 쓰시오.

### 11. 아래 코드에서 버그와 에러를 찾고 `main` 함수의 function call structure를 그리시오.

```cpp
//* Ex 1
#include <iostream>

using namespace std;

int combination(int n, int r) {
  return fact(n) / (fact(r) * fact(n - r));
}

int fact(int n) {
  if (n == 1)
    return 1;
  return fact(n - 1);
}

int main() {
  int n, r;
  cout << "Enter n and r" << endl;;
  cin << n;
  cin >> r;
  cout << combination(n, r);
  return 0;
}
```

## Practice

### 1. 아래 코드를 `switch`문을 사용해서 바꿔 작성하시오.

```cpp
# include <iostream>

using namespace std;

int main() {
  char x = 'C';
  if (x == 'a' && x == 'A') {
    cout << x << endl;
  } else if (x == 'b' || x == 'B') {
    cout << x << endl;
  } else if (x == 'c' || x == 'C') {
    cout << x << endl;
  } else if (x == 'd' || x == 'D') {
    cout << x << endl;
  } else {
    cout << "midterm exam" << endl;
  }
  return 0;
}
```

### 2. 아래 결과를 출력하는 코드를 작성하시오.

```cpp
Read 10 numbers and output the maximum and its location.

Enter 10 numbers

320 1440 80 12 33 21 88 10 11 20

The max: 1440

The location of max: 1 (starting index from 0)
```


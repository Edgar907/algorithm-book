# A + B

 두 정수 \\(A\\)와 \\(B\\)를 입력받은 다음, \\(A+B\\)를 출력하는 프로그램을 작성하시오.

## Constraints

* \\(0 \le A,B \le 10^9\\)

## Code

```cpp
#include <bits/stdc++.h>

int main(int argc, char* argv[])
{
    std::ios_base::sync_with_stdio(false);
	std::cin.tie(nullptr), std::cout.tie(nullptr);

    int A, B;
    std::cin >> A >> B;

    std::cout << A + B << '\n';
    return 0;
}
```
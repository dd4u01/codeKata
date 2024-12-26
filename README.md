# codeKata ( C++ )


## 2024_12_26 ( ex0 )

문제 <br>

![image](https://github.com/user-attachments/assets/2efefacf-2d53-4475-a969-82f02d5506f8) <br>

해답 <br>

```ruby
#include <stdio.h>
#include <stdbool.h>
#include <stdlib.h>

int solution(int num1, int num2) {
    int answer = 0;
    
    if(-50000 <= num1 <= 50000 && -50000 <= num2 <= 50000){
        answer = num1 - num2;
    }
    
    return answer;
}
```

# 수업 내용 필기
이 곳에는 수업 내용 필기를 위한 마크다운(Markdown)을 작성하는 방법을 살펴보겠습니다.
## 랜덤(Random)  
랜덤은 뭐가 나올지 예측이 불가능한 값을 말합니다.  
랜덤을 만드는 방법은 여러 가지가 있습니다.  

1. Random이라는 도구를 생성하여 사용
2. Math.random()명령을 사용
3. SecureRandom 도구를 생성하여 사용

여기서는 Random 도구를 생성합니다.  
```java
Random r = new Random();
```  
이 도구를 사용하기 위해서는 import가 필요합니다.  
```java
import java.util.Random;
```
import는 직접 작성하지 않고 **단축키**인 `ctrl+shift+o`를 누릅니다.  
## 랜덤 정수 추첨  
생성한 도구를 이용해서 랜덤한 정수를 추첨할 수 있습니다.  
단, 생성을 위해서는 범위를 정해야 합니다.  

-  사람은 범위를 이야기할 때 `a`부터 `b`까지 라고 합니다.  
-  자바는 범위를 이야기할 때 `a`부터 `b`개 라고 합니다.  
 주요 랜덤 값들의 범위는 다음과 같이 표현될 수 있습니다.
  
| 항목        | 범위           |
|---|---|
| 주사위      | 1부터 6까지   |
| 로또        | 1부터 45까지  |
| 두자리정수 | 10부터 90까지 |

난수 생성의 원리가 궁금하면 [위키백과](https://ko.wikipedia.org/wiki/%EC%9C%84%ED%82%A4%EB%B0%B1%EA%B3%BC:%EB%8C%80%EB%AC%B8)에서 확인할 수 있습니다.  

![카지노](https://img.freepik.com/free-photo/casino-roulette-wheel-close-up-ai-generative_123827-24159.jpg)  

오늘도 연봉이 10원 올랐습니다  
![좋아 역시 최고야!](./카카오gif.gif)

---
layout: post
title: Introduction To Computer Algorithm
date: 2022-03-16 22:30

---

## 알고리즘(Algorithm)이란?
***  
  
* *일반적 정의* : 단순히 어떤 문제를 해결하기 위한 방법 또는 이론


* *프로그래밍적 정의* : 어떠한 **입력**이 주어졌을때 그것을 기반으로 원하는 결과(**출력**)를 얻어내기 위한 정형화된 단계 절차




  ![My Algorithm Radar Chart](https://github.com/serenhade00/serenhade00.github.io/blob/main/assets/algorithm.png?raw=true)

<p align="center"> 
(알고리즘 종류 레이더 차트)
</p>


## 시간/공간복잡도(Time/Space Complexity)란?
***

### **알고리즘의 효율성**:


1. *시간 복잡도 (Time Complexity)*



   ![Time_Complex](https://miro.medium.com/max/712/1*xamVYkZsA1kzLy9kerwOEA.png)


`시간 복잡도`는 말 그대로 자료 또는 입력의 수(n)이 주어졌을 때 프로그램이 결과를 도출하는데 걸리는 연산의 수, 즉 소요 시간(f(n))을 말한다.

이를 `Big-O 표기법`으로 주로 나타낸다. 물론 `Big-Omega`나 `Big-Theta`같은 표기법도 존재하나 잘 사용되지 않는다.

* **Big-O 표기법**

    ![Time_Complex2](https://postfiles.pstatic.net/MjAyMDEyMjRfNzgg/MDAxNjA4NzM2MDU2NzI2.aH8PlVB7mJBcgrniFsN7U7tDbcbQ2Q8dbTA59D-KISIg.ak1ODV8bgfzY5Tnj9w6fDHnkNm-mdG87e8umWQ7iFeMg.PNG.ryu_eclipse/image.png?type=w966)

    * `f(n)`의 점근적 상한(asymptotic upper bound)을 나타낸다.
    * 어떤 식 `f(n)`이 있으면, 그 식의 최고 차항을 가져오면 된다.
        * ex) $ f(n) = 3n^2+5n+2 $ ------> $ O(n^2) $


    ~~`f : 내가 아무리 안 좋아도 쟤(g)보단 성능이 나쁘지 않다`~~

결국 아무리 맞는 출력을 내놓는 프로그램이더라도 이 시간복잡도가 너무 크다면 결코 **효율적인 프로그램**이라고 말할 수 없다. 

다양한 알고리즘들이 각각 어떤 시간복잡도를 갖는지는 나중 포스트에서 다루겠다.

2. *공간복잡도 (Space Complexity)*

`공간 복잡도`도 직관적으로 이해하면 쉽다. 프로그램 실행을 위해 결국 얼마만큼의 공간(**메모리**)가 필요하느냐, 이다.

앞서 언급한 `Big-O 표기법`을 똑같이 주로 사용한다. 하지만 여기 공간복잡도에 대한 명언을 한번 짚고 넘어가자.

> ~~??? : 공간복잡도는 그냥 메모리 추가만 하면 됩니다.~~ 

농담이다. 사실 그저 현실에서는 시간복잡도보다 중요성이 <p style ="font-size:10px">떨어진다</p>는 것을 말하기 위함이다. 







# 쿠팡 클론 코딩 프로젝트

## 개요

아래는 최근에 관심있게 공부했던 것들이다.

- DDD (도메인 주도 설계)
- OOP & 디자인 패턴
- spring cloud MSA
- kotlin reactive programming

나열한 것 중 위 2개는 방법론에 관한 것이고, 아래의 2개는 기술적인 것이라고 할 수 있을 것 같다. 이러한 내용들을 배우면서 생각이 많이 성장했다고 느꼈는데, 실제로 발전한 생각들을 적용시켜볼 프로젝트가 필요했다. 방법론적인 것과 기술적인 것을 함께 적용시켜 볼 만한 프로젝트를 원했기에 **"복잡한 도메인 지식이 존재하는 대형 서비스를 클론 코딩해보는 것은 어떨까"** 라는 생각을 했었고, 쇼핑몰이 적합하다고 생각되어 쿠팡이라는 서비스를 클론 코딩하기로 결정했다.

![](https://images.velog.io/images/dvmflstm/post/ab470a09-233b-404c-9658-a1ccaab5013b/image.png)

## focus
### DDD & 객체 지향 설계

직접 사용자 스토리를 작성하고, 유스케이스 분석을 하면서 복잡한 도메인 영역을 모델링해본다. 모델링 과정에서는 기술적인 부분에 대한 논의를 일체 삼가고 개념적인 부분에만 집중한다. 

### spring cloud MSA

DDD와 객체 지향에 따라 모델링한 결과물을 여러 개의 마이크로서비스로 나누어 MSA를 구축한다. 도구로는 spring cloud를 사용한다.

### reactive programming

reactive programming 방식은 서비스간 통신이 잦은 MSA 어플리케이션에서 사용하기에 적합하다. 도구로는 spring webflux를 사용한다.
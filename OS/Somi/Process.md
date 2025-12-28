# 프로세스

# 1. 프로세스

: 쉽게 말해 ‘ 실행 중인 프로그램 ‘

디스크에 있는 프로그램이 메모리에 로드 되면 → 프로세스가 된다

하나의 프로그램 → 여러개의 프로세스

### 프로세스 문맥 ( Process Context )

: 프로세스 특정 시점의 상태를 표현

### 하드웨어 문맥 ( Hardware Context )

<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FberUN5%2FbtrejfCRS7h%2FAAAAAAAAAAAAAAAAAAAAAACBR3DMWsEqQX_fobr1ZGVplsExYAWK4VQNLb_Bawev%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1767193199%26allow_ip%3D%26allow_referer%3D%26signature%3DnNKIQHzHhl8m8KCwrz9fQjGaYvY%253D">

- 프로그램 카운터 ( Program Counter )
- 각종 레지스터

→ 프로세스가 어디까지 실행되었는지 알 수 있음

- 프로세스의 주소공간
- PCB ( Process Control Block ) : 프로세스 관련 커널 자료구조
- 프로세스 커널 스택 ( Process Kernel Stack ) : 프로세스 관련 커널 자료구조

# 2. Process State

# ⁉️ 예상 질문 모음

> **✅ 기술 면접 답변틀**
> 
> 1. 기술의 정의 
> 2. 어디에서 사용하는지
> 3. 어떻게 사용할 수 있는지

<aside>
💡

 **Core란 무엇인가요?**

**Process란 무엇이며 어떤 메모리 구조로 되어있나요?**

**프로세스는 운영체제에 어떻게 저장되나요?**

**프로세스 동기화란 무엇이며 관련된 문제 상황에는 무엇이 있을까요?**

**임계 구역 문제를 해결하기 위한 조건은 무엇인가요?**

**임계 구역 문제를 해결하기 위한 기법에는 무엇이 있나요?**

**Thread란 무엇인지 설명해주세요**

**스택을 스레드마다 독립적으로 할당하는 이유는 무엇일까요?**

**PC Register를 스레드마다 독립적으로 할당하는 이유**

**Multi-Thread Programming은 무엇인가요?**

**멀티 쓰레드의 동시성과 병렬성을 설명해주세요.**

**멀티 쓰레드 환경에서의 주의사항을 설명해주세요.**

**Thread-Safe는 무엇을 의미하나요?**

**Process와 Thread의 차이를 설명해주세요.**

**Multi-Process와 Multi-Thread의 차이를 설명해주세요,**

**Multi-Process, Multi-Thread는 언제 사용할까요?**

**PCB가 무엇인가요??**

**PCB는 메모리에 어떤 형식으로 저장되나요?**

 **Context Switching 컨텍스트 스위칭에 대해 설명해주세요.**

**프로세스 스케줄러란?**

**콘보이 현상(convoy effect)이란 무엇이고, 콘보이 현상이 발생될 수 있는 CPU 스케줄러 알고리즘은 무엇인지 설명해주세요.**

**선점형 스케줄링과 비선점형 스케줄링의 차이를 설명해주세요.**

**교착상태(Deadlock), 기아상태(Starvation)**

**Semaphore, Mutex, SpinLock**

**동기(Sync)와 비동기(Async)의 차이(블로킹, 넌블로킹) / 장단점에 대해 설명해보세요.**

</aside>

# java-racingcar-precourse

## 초간단 자동차 경주 게임을 구현한다.

> 이 문서의 작성 양식은 [프리코스 과제 가이드](https://github.com/woowacourse/woowacourse-docs/blob/e2f102b97f6b65f5ba8da09944ee8cb9b33b696a/precourse/README.md)를 참고했습니다.

* 취소선 처리한 내용을 검색하면 다른 항목에서 찾을 수 있습니다.

---

### 1. 주어진 횟수 동안 n대의 자동차는 ~~전진 또는 멈출 수 있다~~ 전진할 수 있다.

> 예:
> 
> 2
> 
> \-  
> \-  
> \-  
> 
> \--  
> \--  
> \--  

* 1-1. 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.

* 1-2. 전진하며 출력한다.

---

### 2. 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.

> 예:
> 
> pobi,woni,jun
> 
> pobi : \-  
> woni : \-  
> jun : \-  
> 
> pobi : \-\-  
> woni : \-\-  
> jun : \-\-  

* 2-1. 이름을 입력한다. 자동차 이름은 쉼표(,)를 기준으로 구분한다.

* 2-2. 이름을 출력한다.

---

### 3. ~~자동차 이름은 쉼표(,)를 기준으로 구분하며~~ ~~이름은 5자 이하만 가능하다.~~

---

### 4. ~~사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.~~

---

### 5. 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.

> 예:
> 
> pobi,woni,jun
> 
> pobi : \-  
> woni :  
> jun : \-  
> 
> pobi : \--  
> woni : \-  
> jun : \--  

* 4 미만일 경우에 멈출 수 있다.

---

### 6. 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.

> 예:
> 
> pobi, jun

* 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.

---

### 7. ~~우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.~~

---

### 8. 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.

* 이름은 5자 이하만 가능하다.

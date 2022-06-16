# delivery service
#
  
### 프로젝트명 : 배달 서비스  
### 개발인원 : 4명 
### 개발기간 : 
### 개발 언어 / tool : spring boot, myBatis, oracle    
### 진행 사유 :   
### 코로나로 늘어나는 배달 수요로 배달앱(맥딜리버리) 서비스를 생각하여 개발해보았습니다.    
### 프로젝트 내용 :   
### (1) 구성    
#### - 총 3개의 프로젝트파일 {서버사이드 1 , 클라이언트 사이드 2( 로그인, 주문 )}    
### (2) 프로그램 구조 _ client side _ MemberService    

  ![delivery_c1_memSer](https://user-images.githubusercontent.com/105413173/173966195-38dc4b58-8940-41bb-af63-3349b8d4739b.JPG)

### (3) 프로그램 구조 _ client side _ OrderService    

  ![delivery_c2_orderSer](https://user-images.githubusercontent.com/105413173/173966232-d1bce681-62cf-44d9-895b-7040082470b6.JPG)

### 본인 역할 :  
### 클라이언트 서버의 주문 기능을 구현   
#### - MyBatis로 CRUD 기능 ( 메뉴 보여주기, 장바구니 담기, 장바구니 보여주기)    
  
  
### 배운점 :    
### (1) 이전에는 개발환경이 달라 세팅하는 데 시간이 오래걸렸는데 spring boot를 사용하니 그러한 어려움을 줄일 수 있었다.   
### (2) MyBatis를 사용하니 SQL를 따로 관리할 수 있어서 편리했다.   
### (3) Spring Cloud Eureka가 MSA에서 사용되는 방식을 경험해보았다.   
#### - 한 프로젝트에 한개의 서비스를 넣어 구현해 봄으로써 고가용성의 목적을 더 잘 이해할수 있었다.   

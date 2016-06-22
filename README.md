# hello-world2
두번째 연습 저장소
(주)펜타코드 www.qtrustssl.com에서 비회원으로 ssl 구매 신청하였다.
COMODO Positive SSL로 3년 32600원 부가세 포함이다.
신청후 메일을 COMODO Security Service로 부터 받고 그대로 실행하였다.
그 후 인증서가 오나 했더니 오지 않아 (주)펜타코드에 연락했더니 다운로드 받을 수 있도록 안내해 주었다.

다운로드 내용은 password.txt와 www_barreinabag_com.pfx파일  두 가지였다.

이후 (주)펜타코드 홈페이지에 있는 인증서 설치가이드에 따라 설치를 하였다.인증서 설치가이드는 iis7 pfx라고 써 있는 것을 사용하였다. 내가 COMODO로 부터 받은 화일 확장자가 pfx였으므로 이렇게 한 것이고. 이후 쉽게 설치가 되었다.

설치과정
다운로드 받은 두 개의 파일을 49서버 D: 루트에 카피하였다.
그리고 설치가이드를 따라 실행하였다.

이후 https://www.barreinabag.com이라고 접근해보니 된다. 그런데 인증 때문인지 페이지의 내용이 다 깨진다. bootstrap과 같은 기술이 실행되지 않아 페이지가 이상하게 보인다.

(주)펜타코드로 연락해보니 https://의 지정은 필요한 페이지에만 적용, 즉 로그인이나 물건을 사고파는 정보를 입력하는 경우에만 적용하라고 한다. 그게 맞다. 이해가 된다.

예를 들면 로그인할 때는 action에 https://~/해당파일 하는 거고 완료된 후에는 redirect를 http://~로 해주는 것이다.

끝 


한  www_barreinabag_com.pfx파일과 password.txt를   ssl of comodo것을 가지고 iis에 barreinabag.com을 설치하였다.


20160621
https://www.qtrustssl.com/에서 ssl구매

azure 무료평가판

20160620
올앳페이 전자 결제 서비스


www.qtrustssl.com



20160519

마이크로소프트 아주레 등록

종류
신용 카드  
성
이름
메일
전화 번호
-
설명
기억하기 쉬운 이름을 선택하십시오.  barreinabag
The personal information you provide on this page may be shared with third parties including but not limited to CyberSource Corp., Receivable Management Services, Inicis and as set forth in the Microsoft Online Privacy Statement located here: http://privacy.microsoft.com/ko-kr
우편 번호
시/도
구/군/시
주소란 1
주소란 2
전화 번호
-



C:\Documents and Settings\JUNE\My Documents\Downloads에 
파일 peter%40barreinabag.com.p12 인증서가 있다

StartSSL.com

SSL출처
https://opentutorials.org/course/228/4894#signiture

SSL의 핵심은 암호화

대칭키 방식은 단점이 있다. 암호를 주고 받는 사람들 사이에 대칭키를 전달하는 것이 어렵고 대칭키가 유출되면 키를 획특한 공격자은 암호의 내용을 복호화할 수 있다.

공개키 방식은 두 개의 키를 갖게 되는데 A키로 암호화를 하면 B키로 복호화 할 수 있고, B키로 암호화하면 A키로 복호화할 수 있는 방식이다. 이 방식에 착안해 두 개의 키 중하나를 비공개키로 하고 나머지를 공개키로 지정한다. 비공개키는 자신만이 가지고 있고 공기키를 타인에게 제공한다. 

공개키로는 암호화만 할 수 있다.

인증서의 기능은 크게 두가지다
클라이언트가 접속한 서버가 신뢰할 수 있는 서버임을 보장한다.
 SSL통신에 사용할 공개키를 클라이언트에게 제공한다.

CA(Certificate Authority)


내 서버 내용을 비공개키로 암호화 하고 그 암호화한 

비공개키로암호화된_a.txt 와 공개키를 보낸다.

받은 클라이언트는 비공개키로암호회된_a.txt를 공개키로 풀어 내용을 보고

답변 b.txt를 공개키로 암호화하여 내 서버로 보낸다. 이 때 클라이언트가 받은 공개키는 암호화만 할 수 있다.


SSL설치
TanzJapan.com 모바일 by MVC
	이를 위해 회원등록 관리 서비스 필요
bootstrap 기본 design 변경 혹은 극복(예제site:www.loud.kr 

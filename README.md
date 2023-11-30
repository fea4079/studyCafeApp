# studyCafeApp

스터디카페를 여러군데 다니는중 주식회사 새누 에서 만든 소월스터디카페 어플(임베디드)을 보고 이를 한번 
만들어보기위해 큰그림을 그려본다.

## 플러터를 이용해서 한번 구현해보기로

여러개의 좌석이 존재하고  2개의 존으로 구분됨, 1존 20개, 2존 20개라 가정

회원은 자신의 핸드폰번호를 아이디로 가입하며 비밀번호는 6자리 숫자
가입후 상품을 구매한후 좌석을 지정 후 이용이가능하다

##이용요금은 3가지로 구분되며 사물함은 따로존재.
당일권
2시간  : 4000원
4시간  : 7000원
6시간  : 10000원
12시간  : 16000원
정액권
50시간  : 80000원
100시간  : 140000원
250시간  : 250000원
기간권
2주  : 80000원
4주  : 140000원
8주  : 250000원
12주  : 370000원

사물함
당일권 : 1000원  
2주권 : 6000원
4주권 : 10000원

##좌석관련
좌석표가 있어야하며 1개지점이 아닌 여러지점의경우 좌석을 창업자가 만들수있도록 제작필요

좌석은 회원이 이용하면 이용불가처리가 되어야하고 회원이 구매한 이용권이 있을시 이용가능하며
시간 또는 기간권이 사용된다

이용중인좌석은 화면에 표시되어야하며 다른회원은 이용이불가능하다

회원이 보유중인 이용권의 사용가능시간이 30분 15분 5분 남앗을때 카카오톡으로 메세지를 발신한다

##결제관련
카드결제, 카카오페이결제, 네이버페이, 삼성페이, 현금 지원해야함

##알림기능
회원이 이용권을 구입하면
구입내역을 카카오톡으로 전송 입장가능한 QR코드를 전송한다
회원이 이용권을 사용하면
사용시간 및 내역, 입장가능QR코드, wi-fi비밀번호, 공지사항등을 카카오톡으로 전송한다.
이용권 사용중인 회원중 이용권이 30분,15분, 5분미만일시
이용권 30분후에 종료를 카톡으로 전송한다.

##사장님 기능, 온라인으로 어플에 접속해 확인이 가능하면 좋겟다
카톡으로 발신되는 메세지 수정기능
현재이용중인 좌석 현황 보기 및 퇴실처리기능
좌석 사용 가능 / 불가 처리기능(좌석고장시)

##자리이동 기능
로그인한 회원이 현재 이용중인 좌석이 있으면 현재좌석을 다른 좌석으로 변경하는 기능.
나머지 정보는 유지한체 이용좌석만 변경하고 이용중이던 좌석은 다른회원이 이용할 수 있게된다.

##퇴실기능
현재 이용중인 좌석을 퇴실처리하고 다른 회원이 이용가능하게 변경, 
퇴실한 회원의 사용중인 이용권의 시간을 계산 수정한다.

회원들이 현재 좌석현황 확인기능
온라인으로 접속하여 현재 좌석을 볼 수 있는 기능

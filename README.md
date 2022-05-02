# Jeep

Html, Css, Javascript 사용한 Jeep 리뉴얼 코딩

--------------------------------------------------------

작업기간: 03.18 - 03.22 <br>
사용언어: html, Javascript, CSS

--------------------------------------------------------

login.js
 - username의 submit event가 발생할 시, localstorage의 key와 value에 유저 정보 저장
 - 유저 정보 저장 유무에 따라 css의 hidden클래스로 display:none, 이후 greeting message를 보이게 함
 - "HELLO" + => `Hello ${savedUsername}`; 으로 코드 간소화
 - input을 form안에 위치시키고, input요소(required, max-lenght)를 사용하여 사용자 입력 제어
 - preventDefault를 활용하여 submit  제어 

clock.js
 - Date 객체를 통해 날짜, 시간 정보 표현
 - setInterval, setTimeout: 일정주기, 일정 시간 이후로 실행되는 타이머 설정 (setInterval:1000으로 1초 설정)
 - padStart, padEnd로 시간 형태 및 문구 추가 설정 

background.js + quotes.js
 - 행렬을 형성하여 랜덤 백그라운드, 송출 문구 지정
 - Math.random, Math.floor 기능을 사용한 행렬 순번 randomize
<br>

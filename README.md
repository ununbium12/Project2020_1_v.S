# Project2020_1 - 정다훈

## 06월 09일 mediaQuery
> 뷰포트 -<br>
viewport mata 태그<br>
<br>
미디어 쿼리 -<br>
규칙=rule<br>
 = 스타일시트 내부에서 특정한 규칙을 표현하는 데 사용<br>
 = @import 규칙 - 외부 스타일을 가져옴<br>
 = @font-face 규칙 - 글꼴을 추가로 정의<br>
<br>
예)<br>
@media'<'미디어 쿼리> {<br>
       '<'css 코드><br>
}<br>
(a) @media 규칙<br>
<br>
media 속성<br>
 = link 태그에 입력해서 해당 미디어 쿼리 조건에 맞는 장치에다만 css 파일을 불러올떄 사용<br>
'<'link rel="stylesheet" href="<파일 이름>" meidia="<미디어 쿼리>"><br>
<br>
미디어 타입과 특징 -<br>
 = orientation을 제외한 모든 속성은 min 접두사와 max 접두사를 붙일 수 있음<br>
 = and 연산자를 사용해 조건을 합칠 수도 있음<br>
<br>
orientation=<br>
세로 방향 Portrait<br>
가로 방향 Landscape<br>
<br>
git fork 와 git clone 의 차이 -<br>
 = 단순히 프로젝트를 복사하고자 할 경우에는 clone, 협업을 위해 프로젝트를 복사하는 경우에는 fork를 사용<br>
<br>
개발 참여 과정<br>
 = Fork(참여자)<br>
 = clone, remote설정 (참여자)<br>
 = branch 생성 (참여자)<br>
 = 수정 작업 후, add commit, push (참여자)<br>
 = Pull Request 생성 (참여자)<br>
 = 코드리뷰, Merge Pullrequest (관리자)<br>
 = Merge 이후 branch 삭제 및 동기화 (관리자)<br>
<br>
= 1. Project생성, commit → 2. push → 3. fork → 4. clone5. branch후 commeit(develop) <br> → 6. push → 7. PR → 8. Merge Pull Request Confirm merge → 9. pull


## 06월 02일 jQuery
> jQuery - <br>
예)<br>
$(document).ready(function() {<br>
$(선택자).메서드(매개변수, 매개변수);<br>
});<br>
<br>
ajax - 비동기 디스플레이어를 해주는 것(전체를 교환하는 것이 아닌 일부만)<br>
<br>
내용 -<br>
jQuery 라이브러리 설정<br>
문서 객체 선택<br>
문서 객체 조작<br>
이벤트<br>
시각 효과<br>
<br>
클래스를 조작 -<br>
addClass()<br>
removeClass()<br>
toggleClass()<br>
- 만약 이것을 사용할때 class 태그를 사용할 경우 동작하지 않고, 무조건 id에서만<br> 발동된다.<br>
<br>
이벤트 -<br>
on() 이벤트 연결<br>
off() 이벤트 제거<br>
<br>
시각 효과 -<br>
메서드<br>
toggle 사라졌다가 보였다를 사용할 수 있다.<br>
이외의 것은 사라지기만 하거나 보여기지만 한다.<br>
<br>
입력 양식 포커스 -<br>
<br>
문서 객체 생성과 추가<br>
<br>
무한 스크롤 -<br>
<br>
Covid19 통계 제작 <br>
<br>
플러그인 -<br>
LightBox<br>
Masonry


## 05월 26일 DOM
> DOM 내용 <br>
onload는 html문서를 먼저 받은 후 스크립트 파일을 실행 <br>
class는 html, id는 javascript 에 사용하는 것을 권장 <br>
스크립트로 id를 잡고 사용시 내용이 아무것도 없어도 넣을 수 있음(DOM02) <br>
엘리먼트 다중 선택(DOM03) <br>
카멜로테이션 <br>
div로 그라데이션 제작(DOM05) <br>
image 태그 placeholder로 임의의 이미지 크기 가져옴 (DOM06) <br>
시계 및 버튼 스크립트 (DOM08)

## 05월 19일 bootstrap
> 학교 버전 시작 <br>
bootstrap 내용추가

## 05월 12일 상단 하단 수정
> 메뉴를 상단으로 올린 고정 <br>
서브 메뉴를 추가 <br>
footer 추가 <br>
고스트 버튼 추가

## 05월 06일 full-screen bg
> Full-screen bg 연습

## 05월 05일 GitHub 재구축
> Project2020에서 실수로 인해 Project2020_1로 재구축 <br>
주석 버전 v0.1.0 제작 <br>
주석 버전 v0.2.0 제작 <br>
주석 버전 v0.3.0 제작 <br>
전 프로젝트에서 제작된 그리드 수정

## 04월 28일 테이블 태그 연습
> table tag 연습 <br>
table tag 과제

## 04월 18일 멀티미디어 태그 연습
> img tag 연습 <br>
audio tag 연습 <br>
video tag 연습 <br>
유튜브 동영상 삽입 숙제

## 04월 11일 실습내용
> CSS 적용방식 <br>
CSS초기화 <br>
메인메뉴 생성<br>
박스모델 연습

## 03월 31일 실습내용
> HTML기본구조 학습 및 실습 <br>
index.html 생성
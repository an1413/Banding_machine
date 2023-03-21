# Banding_machine
밴딩머신_코카콜라자판기 css

## 기본셋팅 완료 230319 02:48am

## 레이아웃 작업완료 230319 03:10am

## 콜라-셀렉트화면 구현 완료 230319 03:43am 
#### - box-shadow부분 미흡함

## 콜라-셀링화면 레이아웃 작업 완료 230319 04:05am

## 콜라-셀링화면 작업 초안 완료 230319 05:20am
#### - 스크롤바 화면 구성실패, 선택리스트 안에 내용들 어떻게 가로배열 시킬지 모르겠음.

## box-2 레이아웃 구성 완료, 소지금 화면 구성완료 230319 07:00am
#### - 스크롤바 화면구성 필요

## get-box 부분 구성 완료, 스크롤바 화면구성 미흡, 가운데 정렬 미흡

## get-box 부분 구성 완료, 스크롤바 구성 완료, <li> -> <button>태그로 수정완료 230320 09:15pm



혜진강사님 솔루션 
1. html 구조를 전체 짠다.
2. 섹션 먼저 구분한다. (전체섹션 구분) - grid로 구분한다. main에 display:grid grid-template-rows :
3. section1 , section2, section3을 grid-area로 구분함.
4. 레이아웃 짜는거 완료하고 
### - button안에 요소로 p태그대신 span태그를 사용해야 한다. (inline요소 안에는 span!)
### - 소제목 (접근성을 위해서!)
### - 폰트는 body태그에 넣는다. -> inherit로 하위요소들에 적용하기.
### - 
5. li구조중 한개만 먼저 짜기! --> 접근성을 위한 숨김처리,
6. strong class="sold-out"으로 품절 만듬! - background: rgba(0, 0, 0, 0.8); -> position:absolute -> top:0; left:0; 그 후에 어떤거 기준으로 할지 정함! relative로 설정 -> 그 후에 덮기! width:100%, height:100%
6-2 sold-out > span 품절 -- display: inline-block; color :eae8fe;
7. html 만들고 나서 grid 처리함.  높이랑 패딩값은 나중에 처리한다.
8. 비슷한 스타일은 복사해서 사용할 수 있도록 만들어주어야 함! 
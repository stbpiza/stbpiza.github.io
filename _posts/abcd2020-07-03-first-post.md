---
layout: post
title: "HTML"
author: "stbpiza"
---
&#60;!DOCTYPE html&#62; : 현재 문서가 HTML5 문서임을 명시합니다.

&#60;html&#62; : HTML 문서의 루트(root) 요소를 정의합니다.

&#60;head&#62; : HTML 문서의 메타데이터(metadata)를 정의합니다.

- 메타데이터(metadata)란 HTML 문서에 대한 정보(data)로 웹 브라우저에는 직접적으로 표현되지 않는 정보를 의미합니다.
- 이러한 메타데이터는 &#60;title&#62;, &#60;style&#62;, &#60;meta&#62;, &#60;link&#62;, &#60;script&#62;, &#60;base&#62;태그 등을 이용하여 표현할 수 있습니다.

&#60;link rel="cannoical" href="주소"&#62; 한 페이지에 주소가 여러개일때 한 주소에 몰아넣기

&#60;meta&#62;
 charset="utf-8"
 name="" content="" 이용자에게 보이진 않지만 사용가능한 정보(검색 등)
 http-equiv="refresh" content="30" 30초마다 새로고침
 description="" 검색노출시 미리보기에 나오는 내용 (1-2개 문장이나 짧은 단락 추천)
 name="viewport" content="width=divice-width, initial-scale=1.0" 모바일 화면

&#60;title&#62; : HTML 문서의 제목(title)을 정의하며, 다음과 같은 용도로 사용됩니다.

- 웹 브라우저의 툴바(toolbar)에 표시됩니다.
- 웹 브라우저의 즐겨찾기(favorites)에 추가할 때 즐겨찾기의 제목이 됩니다.
- 검색 엔진의 결과 페이지에 제목으로 표시됩니다.

semantic태그 의미론적
&#60;header&#62;&#60;/header&#62; 
&#60;nav&#62;&#60;/nav&#62;
&#60;section&#62;
  &#60;article&#62;&#60;/article&#62;
  &#60;article&#62;&#60;/article&#62;
  &#60;article&#62;&#60;/article&#62;
&#60;/section&#62;
&#60;footer&#62;&#60;/footer&#62; 


&#60;body&#62; : 웹 브라우저를 통해 보이는 내용(content) 부분입니다.

&#60;h1&#62; ~ &#60;h6&#62; : 제목(heading)을 나타냅니다.

&#60;p&#62; : 단락(paragraph)을 나타냅니다.

&#60;strong&#62;&#60;/strong&#62; 굵게(중요)
&#60;b&#62;&#60;/b&#62; 굵게

&#60;i&#62;&#60;/i&#62; 이탤릭체
&#60;em&#62;&#60;/em&#62; 이탤릭체(중요)

&#60;mark&#62;&#60;/mark&#62; 하이라이팅

&#60;del&#62;&#60;/del&#62; 삭제효과(취소선) (ins와 짝)
&#60;strike&#62;&#60;/strike&#62; html5 지원안함
&#60;s&#62;&#60;/s&#62; html5 권장 del보단 약한삭제

&#60;u&#62;&#60;/u&#62; 밑줄 철자오류에 씀
&#60;ins&#62;&#60;/ins&#62; 밑줄 삽입된 텍스트

&#60;abbr&#62;&#60;/abbr&#62; 밑줄에 줄임말 html5에서 권장
&#60;acronym&#62;&#60;/acronym&#62; 기능은같음

&#60;sup&#62;&#60;/sup&#62; 위첨자
&#60;sub&#62;&#60;/sub&#62; 아래첨자

&#60;br&#62; 줄바꿈

&#60;p&#62;&#60;/p&#62; 단락

&#60;blockquote&#62;&#60;/blockquote&#62; 블록인용구

&#60;address&#62;&#60;/address&#62; 주소

&#60;img src=""&#62;
width 가로
height 세로
alt 대신 나올 글자
title 도움말

&#60;ul&#62;&#60;/ul&#62;목차
  &#60;li&#62;&#60;/li&#62; 그룹하위항목
&#60;ol&#62;&#60;/ol&#62;숫자목차 순서
  &#60;li&#62;&#60;/li&#62;

&#60;a href=""&#62;&#60;/a&#62; 링크
target="_black" 새창에서열기
title="" 마우스 올리면 설명

class="" 그룹화
id="" class보다 우선, 유일값

&#60;div&#62;&#60;/div&#62;       의미 기능 포함안된값 블럭값(줄바뀜)
&#60;span&#62;&#60;/span&#62;   줄안바뀜

&#60;table border="테두리"&#62;   표
  &#60;thead&#62;
    &#60;tr&#62;
      &#60;th&#62;&#60;/th&#62; 진하게
    &#60;/tr&#62;
  &#60;/thead&#62;
  &#60;tbody&#62;
    &#60;tr&#62;
      &#60;td&#62;&#60;/td&#62;
    &#60;/tr&#62;
  &#60;/tbody&#62;
  &#60;tfoot&#62;
    &#60;tr&#62;
      &#60;td&#62;&#60;/td&#62;
    &#60;/tr&#62;
  &#60;/tfoot&#62;

rowspan="" x개의 행 병합 아래로
colspan="" x개의 열 병합 오른쪽

&#60;/table&#62;

&#60;form action="http://localhost/login.php" &#62; 서버로 정보보내기
  method="get" 공개전송 "post" 비공개전송
  autocomplete="on" 자동완성

  &#60;input type="text" name="값 이름" value="default value"&#62; 입력상자
  type="password" 암호입력상자
  type="submit" 제출버튼 value로 이름변경가능
  type="button" 전송기능은 없는 순수버튼
  type="reset" 내용초기화
  type="radio" 동그란버튼 (이름을 똑같이 여러개 만들면 하나만 선택됨)
  type="checkbox" 다중선택
  checked 넣어두면 기본선택
  type="hidden" name="" value="" 숨겨진정보 전송
  type="file" 파일전송 (form에다가 name="이름" method="post" enctype="multipart/form-data" 추가해야함)

  type="number" 숫자만 입력가능 min="" max="" 지정가능
  placeholder="" 입력전 내용 표시
  autofocus 커서 시작위치지정
  required 미입력시 제출막기
  pattern="[a-zA-Z]" 알파벳 한글자 [][] 두글자 .은 모든문자 .+ 모든문자 무제한(하나이상) [0-9] 숫자

  &#60;textarea cols="" rows=""&#62;&#60;/textarea&#62; 여러줄 입력상자

&#60;/form&#62;



&#60;label for="id_txt"&#62;&#60;/label&#62; id값의 이름표라는의미
for 대신 레이블로 감싸도 가능



&#60;select name="값 이름" multiple(다중선택)&#62;
  &#60;option value="값"&#62;&#60;/option&#62; 옵션중에 하나 선택
  &#60;option value="값"&#62;&#60;/option&#62;
  &#60;option value="값"&#62;&#60;/option&#62;
&#60;/select&#62;





&#60;!-&#45;  주석
-&#45;&#62;

pixabay 사진
disqus livere 댓글
tawk.to 채팅
analytics.google.com 방문분석

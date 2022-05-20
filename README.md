---
description: Source:https://inpa.tistory.com/entry/MarkDown
---

# 기본 문법

## Headers 헤더

* \#으로 시작
* \#은 하나부터 여섯개까지
* \#이 늘어날때마다 제목의 스케일이 낮아짐

## Horizontal Rules 수평선

* \-또는 \*또는 \_을 3개 이상 작성
* 단, -를 사용할 경우, header로 인식 가능하여 이 전라인은 비워두어야함

## Line Breaks 줄바꿈

* \<br>을 사용해서 줄바꿈 가능
* 엔터로 칸을 띄면 다음 행으로 넘어

## Emphasis 강조

* 이탤릭체: \*또는 \_로 텍스트 감싸기
* 볼드체: \*\*또는 \_\_로 텍스트 감싸기
* 취소선: \~\~로 텍스트 감싸기
* 이탤릭과 두껍게를 동시에 쓰는것이 가능

## Blockquotes 인용

* \>로 시작하는 텍스트
* \>는 3개까지 가능

## Lists 목록

* \*,+,-를 이용해 순서가 없는 목록 생성
* 들여쓰기(tab)을 하면 하위 목록으로 변경

## Ordered Lists 순서가 있는 목록

* 숫자.을 하면 순서가 있는 목록
* 들여쓰기(tab)을하면 하위 목록으로 변경
* Lists 내의 Lists는 1번부터 나열해야 적용 가능
* Lists와 Ordered Lists를 조합 가능

## Backslash Escapes 특수문자 출력

* \*,-와 같은 특수문자를 표현하고 싶을때 \\\*, \\-로 입력가능
* \[]도 마찬가지로 \\\[ 과 \\] 로 표현 가능

## Image 이미지

* 인라인 이미지 !\[이미지 이름]\(/경로 및 파일 이름 ex).img/teemo.png)
* 링크 이미지 !\[이미지 이름]\(image\URL경로)
* html 형식 \<img src="경로 및 파일 이름">
* html 형식 시 이미지 사이즈 변경 가능 \<img src="경로 및 파일 이름" width="OOOpx" height="OOOpx
* html 형식 시 아래와 같이 속성을 적용하면 이미지 정렬 가능: \"center", \"left", \"right"
* 예시 : \<p align="center">\<img src="img/teemo.png" width="150" height="150">\</p\>

<p align="center"><img src="img/teemo.png" width="150" height="150"></p>

## Links (Anchor) 링크

* \[링크가 표시될 이름]\(URL)
* 예시 : \[Google\](http://www.google.com)

[Google](http://www.google.com)

## Code Block 코드 블럭

* 인라인 코드는 텍스트를 앞뒤로 \'''를 감싸주면 됨
* \''' 옆에 언어를 지정할 시 syntax color 적용

## Check Lists 체크 리스트

* 줄 앞에 - \[x]를 써서 완료된 리스트 표시
* 줄 앞에 - \[]를 써서 미완료된 리스트 표시

## Table 테이블

* 헤더와 셀을 구분할때 3개 이상의 \- 기호(hyphen/dash)가 필요
* 헤더와 셀을 구분하면서 \: 기호(colons)로 셀 안에 내용을 정렬할 수 있음
* 가장 좌측과 우측의 |기호는 생략

ex) 입력 <br>
헤더1\|:헤더2\|:헤더3:\|헤더4:\|<br>
---|---|---|---<br>
셀1\|셀2\|셀3\|셀4<br>
셀5\|셀6\|셀7\|셀8<br><br>
ex) 결과
헤더1|헤더2|헤더3|헤더4|
---|:---|:---:|---:
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8
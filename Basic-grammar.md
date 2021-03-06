---
description: Source:https://inpa.tistory.com/entry/MarkDown
---

# 기본 문법

* Basic Grammar
  * [Headers 헤더](#headers-헤더)
  * [Horizontal Rules 수평선](#horizontal-rules-수평선)
  * [Line Breaks 줄바꿈](#line-breaks-줄바꿈)
  * [Emphasis 강조](#emphasis-강조)
  * [Blockquotes 인용](#blockquotes-인용)
  * [Lists 목록](#lists-목록)
  * [Ordered Lists 순서가 있는 목록](#ordered-lists-순서가-있는-목록)
  * [Backslash Escapes 특수문자 출력](#backslash-escapes-특수문자-출력)
  * [Image 이미지](#image-이미지)
  * [Links (Anchor) 링크](#links-anchor-링크)
  * [Code Block 코드 블럭](#code-block-코드-블럭)
  * [Check Lists 체크 리스트](#check-lists-체크-리스트)
  * [Table 테이블](#table-테이블)

___

## Headers 헤더

* `#`으로 시작
* `#`은 하나부터 여섯개까지
* `#`이 늘어날때마다 제목의 스케일이 낮아짐

___

## Horizontal Rules 수평선

* `-`또는 `*`또는 `_`을 3개 이상 작성
* 단, `-`를 사용할 경우, header로 인식 가능하여 이 전라인은 비워두어야함

___

## Line Breaks 줄바꿈

* `<br>`을 사용해서 줄바꿈 가능
* 엔터로 칸을 띄면 다음 행으로 넘어

___

## Emphasis 강조

* 이탤릭체: `*`또는 `_`로 텍스트 감싸기
* 볼드체: `**`또는 `__`로 텍스트 감싸기
* 취소선: `~~`로 텍스트 감싸기
* 이탤릭과 두껍게를 동시에 쓰는것이 가능
* ` `` `를 통해 텍스트를 박스로 감싸기 가능 `예시구문`
* 텍스트에 색상을 부여하고 싶은 경우, html sytle로 

___

## Blockquotes 인용

* `>`로 시작하는 텍스트
* `>`는 3개까지 가능

___

## Lists 목록

* `*,+,-`를 이용해 순서가 없는 목록 생성
* 들여쓰기(tab)을 하면 하위 목록으로 변경

___

## Ordered Lists 순서가 있는 목록

* `숫자.`을 하면 순서가 있는 목록
* 들여쓰기(tab)을하면 하위 목록으로 변경
* Lists 내의 Lists는 1번부터 나열해야 적용 가능
* Lists와 Ordered Lists를 조합 가능

___

## Backslash Escapes 특수문자 출력

* `*,-`와 같은 특수문자를 표현하고 싶을때 `\*`, `\-`로 입력가능
* `[]`도 마찬가지로 `\[` 과 `\]` 로 표현 가능

___

## Image 이미지

* 인라인 이미지 `![이미지 이름](/경로 및 파일 이름` ex).img/teemo.png)
* 링크 이미지 `![이미지 이름](image\URL경로)`
* html 형식 `<img src="경로 및 파일 이름">`
* html 형식 시 이미지 사이즈 변경 가능 `<img src="경로 및 파일 이름" width="OOOpx" height="OOOpx>`
* html 형식 시 아래와 같이 속성을 적용하면 이미지 정렬 가능: `"center", "left", "right"`
* 예시 : `<p style="text-align:center"><img src="img/teemo.png" width="150" height="150"></p>`

<p style="text-align:center"><img src="img/teemo.png" width="150" height="150"></p>

___

## Links (Anchor) 링크

* 문서 내부 링크: `[링크 이름](#헤더 이름)`
* 문서 외부 링크: `[링크 이름](경로/파일 이름)`
* `[링크 이름](URL)`
* 예시 : \[Google\](http://www.google.com)

> [Google](http://www.google.com)

___

## Code Block 코드 블럭

* 인라인 코드는 텍스트를 앞뒤로 `'''`를 감싸주면 됨
* `'''` 옆에 언어를 지정할 시 syntax color 적용

___

## Check Lists 체크 리스트

* 줄 앞에 `- [x]`를 써서 완료된 리스트 표시
* 줄 앞에 `- []`를 써서 미완료된 리스트 표시

___

## Table 테이블

* 헤더와 셀을 구분할때 3개 이상의 `-` 기호(hyphen/dash)가 필요
* 헤더와 셀을 구분하면서 `:` 기호(colons)로 셀 안에 내용을 정렬할 수 있음
* 가장 좌측과 우측의 `|`기호는 생략

ex) 입력 <br>
헤더1\|:왼쪽 정렬\|:중간 정렬:\|오른쪽 정렬:\|<br>
---|---|---|---<br>
셀1\|셀2\|셀3\|셀4<br>
셀5\|셀6\|셀7\|셀8<br><br>
ex) 결과
헤더1|왼쪽 정렬|중간 정렬|오른쪽 정렬|
---|:---|:---:|---:
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8

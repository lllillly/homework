# 마크다운 문법

## HEADER 헤더

- #, ##, ### ...으로 시작
- #이 늘어날수록 스케일 감소

## Horizontal Rules 수평선

- '-' 또는 '\*' 또는 '\_' 을 3개 이상 작성
- 단, -을 사용할 경우 header로 인식할 수 있으니 이 전 라인은 비워두어야 한다

## Line Breaks 줄바꿈

- <'br'>을 활용해서 줄바꿈
- 엔터로 칸을 띄면 다음 행으로 넘어가게 된다

## Emphasis 강조

- _기울여 쓰기(italic)_ : \* 또는 \_로 감싼 텍스트
- **두껍게 쓰기(bold)** : \*\* 또는 \_\_로 감싼 텍스트
- ~~취소선~~ : ~~로 감싼 텍스트

##Blockquotes 인용

- > '>' 으로 시작하는 텍스트

## Unordered lists 순서가 없는 목록

- \*, +, - 를 이용해서 순서가 없는 목록을 만들 수 있다
  - 들여쓰기를 하면 모양이 바뀜

1. 숫자의 리스트 안 리스트를 사용하려면 tab과 함꼐 숫자 1번 서부터 나열해야 적용이 된다
   1. 테스트

## Backslash Escapes

- 특수문자를 표현할 때, 표시될 문자 앞에 \를 넣고 특수문자를 쓰면 된다

\*literal asterisks\*

\#hash mark\#

\[squre brackets\]

## 이미지

![텍스트](이미지파일URL '이미지이름')
![텍스트](이미지파일URL '이미지이름')

## 링크

[Google](http://www.google.com '구글')
[Naver](http://www.naver.com '네이버')
[Github](http://www.github.com '깃허브')

## 내부 (해시) 링크

[1. Headers 헤더](#1-headers-헤더)
[2. Emphasis 강조](#2-emphasis-강조)
[3. Blockquotes 인용](#3-blockquotes-인용)

## 코드 블럭

```javascript
function test() {
  console.log('look ma’, no spaces');
}
```

## 체크 리스트

- 줄 앞에 - [x]를 써서 완료된 리스트 표시.
- 줄 앞에 - [ ]를 써서 미완료된 리스트 표시.
- 체크 안에서 강조 외에 여러 기능을 사용할 수 있습니다.

- [ ] check
- [] check

## Table 테이블

- 헤더와 셀을 구분할 때 3개 이상의 -(hyphen/dash) 기호가 필요합니다.
- 헤더 셀을 구분하면서 :(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.
- 가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능합니다.

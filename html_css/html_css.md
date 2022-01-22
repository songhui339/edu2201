# HTML

## HTML_Introduction

- HTML : Hyper Text Markup Langauge

  - Hyper Text : 하이퍼링크로 연결된 웹 문서 => 웹 문서 (페이지)
  - Markup Langauge : 표시 언어

- HTML 표시 내용
  - Web Page의 Contents
    - Text Contents
    - Multimedia Contents : image, video, audio etc
  - Web Page의 Structure

head tag -> 웹 페이지 정보
body tag -> 웹 페이지 내용

## HTML Basic

- 기본구조

※ ` : backtick (작은 따옴표랑 다른 개념, javaScript에서 사용)

```
<!DOCTYPE html>
<html>
  <head>
    웹문서의 부가 정보들
  </head>
  <body>
    웹문서의 내용
  </body>
</html>
```

## HTML Elements

- Tag와 Contents로 구성
- Tag는 시작 태그와 종료 태그로 구성
  - empty element : 콘텐츠와 종료태그 없이 시작태그만 있는 빈 요소

```
<h1>제목<br>입니당</h1>
```

## HTML Attribute

- HTML Tag 의 추가 정보

- syntax : name="value"

```
<img src="/이미지주소" alt="이미지 속성">
```

## Text Contents Element

### Heading
- 제목
- h(heading)
  - h1 ~ h6

### Paragraph

- p(paragraph) : 단락
- hr(Horizontal Rules) : 수평선 (단락을 구분)
- br(line Break) : 강제 줄 바꿈
  (※ 강제 공백(Entity Code) : &nbsp; - none breaking space)
  (※ & : ampersand)
  - HTML Text 줄바꿈, 공백 인식
    - 공백 1칸으로 인식

### HTML List

- 순서 없는 목록 : ul, li
- 순서 있는 목록 : ol, li
- 설명 목록 : dl, dt, dd

※ 포함관계 / 중첩관계 (Nested Element)
- 포함하는 요소 : 부모요소(Parent), 조상요소(Ancestor)
- 포함되는 요소 : 자식요소(Child), 자손요소(descendant)
- 이웃하는 요소 : 형제요소(sibling)

### HTML Link

- 하이퍼링크 연결
- a(anchor)
  - href (hypertext reference) attribute : 연결되는 페이지의 주소 정보
  - target attribute : 주로 4가지 사용 가능 (새탭 열기 외에는 현재 사용하고 있지 않음)
    - target="_blank" : 새탭 열기
  
- Bookmark 기능
  - 목적지에 id attribute를 사용해서 이름 지정
  - a 태그의 href 속성에 "#+이름" 으로 위치 표시
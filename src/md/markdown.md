# 마크다운 문법 정리

마크다운(Markdown)은 문서를 구조적으로 작성하기 위한 경량 마크업 언어이다.  
텍스트만으로 제목, 목록, 코드 등을 표현할 수 있으며  
GitHub, Notion, README 파일에서 주로 사용된다.

---

## 1. 제목 (Heading)

제목은 `#` 기호를 사용해 작성한다.  
`#`의 개수가 많아질수록 제목의 단계가 낮아진다.

```md
# 제목 1

## 제목 2

### 제목 3

## 2. 문단 (Paragraph)

이것은 첫 번째 문단이다.

이것은 두 번째 문단이다.

## 3. 목록 (List)

3-1 순서 없는 목록

-, \*, + 기호를 사용한다.

- HTML
- CSS
- JavaScript

3-2 순서 있는 목록

숫자와 점(.)을 사용한다.

1. Git 설치
2. 저장소 생성
3. 커밋 및 푸시

## 4. 강조 (Emphasis)

**굵은 글씨**

## 5. 코드 블록 (Code Block)

'''html

<div class="container">
  <p>Hello Markdown</p>
</div>

JS도 동일:
'''md
'
console.log("Hello Markdown");

## 6. 인라인 코드 (Inline Code)

md

`git status` 명령어를 사용하면 상태를 확인할 수 있다.

## 7. 링크 (Link)

md

[GitHub](https://github.com)

## 8. 이미지 (Image)

md

![이미지 설명](이미지경로)

예시:

md

![점심 사진](../assets/images/lunch.jpg)

## 9. 구분선 (Horizontal Rule)

md

---
```

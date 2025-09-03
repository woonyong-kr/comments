# GitHub 기본 Markdown 한글 샘플

---

## 1) 제목(Headings)
# 제목 H1
## 제목 H2
### 제목 H3
#### 제목 H4
##### 제목 H5
###### 제목 H6

---

## 2) 텍스트 스타일(Styling text)
**굵게 표시된 텍스트**  
_기울임꼴로 표시된 텍스트_  
~~실수하여 취소된 텍스트~~  
**굵게와 _기울임_ 중첩**  
***굵게 및 기울임꼴 모두 적용***  
<sub>아래 첨자</sub> / <sup>위 첨자</sup> / <ins>밑줄</ins>

---

## 3) 인용(Quote)
일반 문장입니다.

> 인용문입니다.  
> 여러 줄을 이어 적을 수 있습니다.
>> 중첩 인용문입니다.

---

## 4) 코드(Code)
인라인 코드는 이렇게 씁니다: `git status`

코드 블록(셸 명령 예시):
```bash
git init
git add .
git commit -m "첫 커밋"
```

다른 언어 힌트:
```js
console.log("Hello, GitHub Markdown!");
```

---

## 5) 지원 색상 표기(Color models)
> 색상 점 미리보기는 **이슈/PR/토론**에서 확인 가능해요.

- HEX: `#0969DA`, `#ffffff`, `#000000`
- RGB: `rgb(9, 105, 218)`
- HSL: `hsl(212, 92%, 45%)`

예문: 라이트 모드 배경은 `#ffffff`, 다크 모드 배경은 `#000000` 입니다.

---

## 6) 링크(Links)
- 인라인 링크: [GitHub Pages](https://github.com/woonyong-kr)
- 자동 링크(그냥 URL): https://woonyong-kr.tistory.com/

---

## 7) 섹션 링크(Section links)
아래의 **목록 섹션**으로 이동 → [목록 섹션으로 점프](#10-목록lists)

---

## 8) 상대 링크(Relative links)
- 리포 내부 문서로 이동: [마크다운 원문](/sample/markdown.md)  
- 상대 경로 이미지: `![깃허브 로고](./github_icon.png)`

---

## 9) 이미지(Images)
절대 URL 이미지:
![GitHub 아이콘](https://raw.githubusercontent.com/woonyong-kr/comments/main/sample/github_icon.png)

이미지에 링크 걸기:  
[![배너: GitHub 아이콘](https://raw.githubusercontent.com/woonyong-kr/comments/main/sample/github_icon.png)](https://github.com/woonyong-kr/comments)

---

## 10) 목록(Lists)
### 순서 없는 목록(Bullet)
- 하이픈
* 별표
+ 더하기

### 순서 있는 목록(Ordered)
1. 첫째
2. 둘째
3. 셋째

### 중첩 목록(Nested)
1. 첫 항목
   - 하위 항목
     - 하위의 하위

---

## 11) 작업 목록(Task lists)
- [x] 완료된 작업
- [ ] 해야 할 작업
- [ ] \(선택) 후속 이슈 열기  ← 괄호 시작은 백슬래시로 이스케이프

---

## 12) 멘션(Mentions)
@woonyong-kr  의견 부탁드립니다.

---

## 13) 이슈/PR 참조(References)
- 이 리포지토리의 이슈: #3
- 이 리포지토리의 PR: #2  
- 같은 리포(Owner/Repo 형식으로 명시): woonyong-kr/comments#3
- 특정 커밋 참조: woonyong-kr/comments@7b1c7df  

---

## 14) 외부 리소스 참조(Autolinks)
> 리포지토리에 **자동 링크**가 구성되어 있는 경우에만 단축 링크가 만들어집니다.

예: 작업 티켓 `PROJ-42` (구성돼 있다면 자동으로 링크)

---

## 15) 자산 업로드(Uploading assets)
이슈/PR/주석/MD 편집기에서 **이미지·GIF·동영상 파일을 드래그 앤 드롭**하거나 **클립보드 붙여넣기**로 업로드할 수 있습니다.  
(별도의 마크다운 문법 없이, 업로드하면 `![alt](URL)` 이 자동 삽입됩니다.)

---

## 16) 이모지(Emoji)
:+1: :sparkles: :shipit: :tada: :fire:

---

## 17) 단락(Paragraphs)
이것은 첫 번째 단락입니다.

빈 줄 뒤에 오는 두 번째 단락입니다.

줄바꿈 예시(두 칸 공백) 후에 이어쓰기··  
이 줄은 바로 위 문장과 같은 단락 내 줄바꿈입니다.

백슬래시로 줄바꿈하기\
이 줄도 같은 단락 내 줄바꿈입니다.

---

## 18) 각주(Footnotes)
각주가 들어간 문장입니다.[^note] 여러 줄 각주도 가능합니다.[^multi]

[^note]: 이것은 간단한 각주 예시입니다.  
[^multi]: 각주 내부에서 줄바꿈을 하려면 앞에 두 칸 공백을 둡니다.  
  이렇게 두 번째 줄을 이어갑니다.

---

## 19) 경고(Alerts)
> [!NOTE]
> 훑어봐도 알아야 할 유용한 정보입니다.

> [!TIP]
> 더 쉽게/빠르게 하는 팁입니다.

> [!IMPORTANT]
> 목표 달성에 필수적인 핵심 정보입니다.

> [!WARNING]
> 문제를 피하려면 **즉시 주의**하세요.

> [!CAUTION]
> 특정 동작의 위험/부정적 결과를 알립니다.

---

## 20) 주석으로 콘텐츠 숨기기(Hide via comments)
<!-- 이 줄은 렌더링 결과에 보이지 않습니다 -->
보이는 문장입니다.

---

## 21) Markdown 서식 무시(Escaping)
별표를 일반 문자로 보이게 하려면 백슬래시를 사용합니다.  
예: Let’s rename \*our-new-project\* to \*our-old-project\*.

백틱( ` ) 문자 자체를 보이게 하려면 백틱 세 개로 감싸 주세요:
```text
리터럴 백틱: `
```

---

## 22) Markdown 렌더링 비활성화(원본 보기)
편집기/파일 뷰에서 **Raw(원본)** 보기를 선택하면 렌더링하지 않은 원본을 볼 수 있습니다.  


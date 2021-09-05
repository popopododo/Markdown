# Markdown 문법 정리

---

### [1] `헤더`: 제목, 문단별 제목

# H1

## H2

### H3
#### H4

```markdown
# H1
## H2
### H3
#### H4

```

### [2] `수평선`: 명시적으로 내용 구분

---



```markdown
---
***
```

### [3]  `목록`: 요소를 나열하고 싶을 때

#### Ordered List
1. First
2. Second
3. Third
#### Unordered List
+ 순서없음
- 홍길동

* 중대장

```markdown
#### Ordered List
1. First
2. Second
3. Third
#### Unordered List
+ 순서없음
- 홍길동
* 중대장
```

### [4] `강조`: 문장 내 강조

__볼드__

_이탤릭_

~~취소~~

~~<u>밑줄</u>~~

```markdown
__볼드__
*이탤릭*
~~취소~~
~~<u>밑줄</u>~~
__볼드에 *이탤릭* ~~취소~~ 다 가능__
```

### [5] `인용구 & 인용`: 인용할 경우 사용

> "**The quick brown fox jumps over the lazy dog**."
>
> > `An English Pangram`

```markdown
> "The quick brown fox jumps over the lazy dog"
>> `An English Pangram`
```

### [6] `링크` : 링크 사용 시

https://github.com/popopododo

> 그냥 링크를 넣으면 자동적으로 생성

### [7] `이미지`: 이미지를 넣을 시 

![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/300px-Markdown-mark.svg.png)

```
![](이미지 링크)
```

### [8] `동영상`: 영상 삽입 시

```<iframe width="560" height="315" src="https://www.youtube.com/embed/MnrJzXM7a6o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>```

```markdown
- Youtube 영상: iframe tag 복사 붙여넣기
```

### [9]`테이블`: 표를 만들고 싶을 때

| 1    | 2    | 3    |
| ------ | ---- | ---- |
| 표 만들땐 | 중간 두 번째 줄에 | `---` 구분선을 넣어줍시다 |



```markdown
| 1 | 2 | 3 |
|----- | --- | --- |
| 표 만들땐 | 중간 두 번째 줄에 | `---` 구분선을 넣어줍시다
```

### [10] `마크다운 무시`: 마크다운 포맷 무시할 때 `\`

*이게 아니라..*\*이거입니다*

```markdown
*이게아니라*\*이거입니다*\
```

### [11] `Emoji`: 이모티콘을 넣고 싶을 때

&#128514;

> https://www.quackit.com/character_sets/emoji/emoji_v3.0/unicode_emoji_v3.0_characters_all.cfm

```markdown
- 링크에서 Decimal Format 코드 사용
```


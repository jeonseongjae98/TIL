# 마크다운 문법 정리

##  Basic Syntax

### Heading
---
```메모
#개수에 따라 대응되는 수준이 있다. h1 ~ h6까지 표현 가능
```
- # H1
- ## H2
- ### H3

### Bold
---
- **bold text**
- __bold text__

### Italic
---
- *italicized text*
- _italicized text_

### Blockquote
---
- > blockquote

### Ordered List
---
```메모
Tab과 Tab + shift로 하위 항목을 구성할 수 있음
```
- 1. First item
- 2. Second item
- 3. Third item

### Unordered List
---
- First item
- Second item
- Third item

### Code
---
- `code`

### Horizontal Rule
---
- '---'
- '***'
- '___'

### Link
---
```메모
[문자열](url)
```
[네이버](https://www.naver.com)

### Image
---
```메모
![문자열](url)
특정 파일들을 포함하여 연결 시킬 수도 있음
```
![alt text](image.jpg)

## Extended Syntax

### Table
---
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block
---
```메모
backtick 기호 3개로 작성 가능
```
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote
---
	Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Definition List
---
term
: definition

### Strikethrough
---
~~The world is flat.~~

### Task List
- [x] Write the press release
- [o] Update the website
- [o] Contact the media

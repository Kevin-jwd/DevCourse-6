# DevCourse-6

![image](https://github.com/user-attachments/assets/72ccf5b0-a15d-48df-bfad-9edece19973e)


> # 📜 데브코스 6기
>
 
<br>

> # Github Flavored Markdown 문법 정리
> Github에서 `README.md`파일을 작성할 때 유용한 Markdown 문법을 정리한 문서입니다. 

<br>

> # 🗞️ 목차
> 1. [제목](#제목)
> 2. [문단](#문단)
> 3. [목록](#목록)
> 4. [링크](#링크)
> 5. [이미지](#이미지)
> 6. [표](#표)
> 7. [인용문](#인용문)
> 8. [강조](#강조)
> 9. [인라인 코드](#인라인-코드)
> 11. [태그](#태그)

<br>

> # 제목
> `#`을 사용하여 제목을 작성할 수 있습니다. `#`의 갯수가 늘어날수록 제목의 크기가 감소합니다.

<br>

```
# 제목 1 (가장 큰 제목)
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
```
<br>

# 제목 1 (가장 큰 제목)
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5 (가장 작은 제목)

<br>
  
> # 🔨 문단
> 문단은 빈 줄을 이용해 구분합니다. 별도의 구문 없이 텍스트를 입력하면 자동으로 문단이 생성됩니다.

<br>

```
첫 번째 문단입니다.

두 번째 문단입니다.
```

첫 번째 문단입니다.

두 번째 문단입니다.

<br>
 
> # 목록
> ## 순서 없는 목록
> 하이픈(`-`), 더하기(`+`), 별표(`*`) 중 하나를 사용하여 순서 없는 목록을 만들 수 있습니다.

<br>

```
- 항목 1
+ 항목 2
* 항목 3
```
- 항목 1
+ 항목 2
* 항목 3

<br>

> ## 순서 있는 목록
> 순서 있는 목록은 숫자와 점(`.`)을 사용하여 작성합니다.

<br>

```
1. 첫 번째 항목
2. 두 번째 항목
3. 세 번째 항목
```
1. 첫 번째 항목
2. 두 번째 항목
3. 세 번째 항목
   
<br>

> # 링크
> 링크는 대괄호 `[]`안에 텍스트를 입력하고, 그 뒤에 소괄호 `()` 안에 URL을 기입하여 작성합니다.

<br>

```
[GitHub](https://github.com)
```
[GitHub](https://github.com)

<br>

> # 이미지
> 이미지는 대괄호 `[]` 안에 텍스트를 입력하고, 그 뒤에 소괄호 `()` 안에 이미지 URL을 기입하여 작성합니다.

<br>

```
![AIImage](이미지_경로)
```

![00084-2340900898](https://github.com/user-attachments/assets/6fcd4fb1-3b49-42b3-8132-37037ec1da9b)

<br>

> # 표
> 표는 파이프(`|`)와 하이픈(`-`)을 사용하여 작성합니다. 헤더와 본문을 구분하려면 하이픈으로 구분선을 만들어야 합니다.

<br>

```
| 헤더 1 | 헤더 2 | 헤더 3 |
|--------|--------|--------|
| 내용 1 | 내용 2 | 내용 3 |
| 내용 A | 내용 B | 내용 C |
```
| 헤더 1 | 헤더 2 | 헤더 3 |
|--------|--------|--------|
| 내용 1 | 내용 2 | 내용 3 |
| 내용 A | 내용 B | 내용 C |


<br>

> # 인용문
> 인용문은 `>` 기호를 사용하여 작성합니다. 여러 줄로 구성된 인용문을 작성하려면 각 줄에 `>`를 추가합니다.

```
> 이것은 인용문입니다.
> 여러 줄로 구성할 수 있습니다.
```
> 이것은 인용문입니다.
> 여러 줄로 구성할 수 있습니다.

<br>

> # 강조
> 텍스트를 굵게 또는 기울임꼴로 강조하려면 아래와 같은 마크다운 문법을 사용합니다.

<br>

```
*기울임꼴 텍스트*  
_기울임꼴 텍스트_  
**굵은 텍스트**  
__굵은 텍스트__  
~~취소선 텍스트~~
```
*기울임꼴 텍스트*  
_기울임꼴 텍스트_  
**굵은 텍스트**  
__굵은 텍스트__  
~~취소선 텍스트~~

<br>

> # 코드
> ## 인라인 코드
> 인라인 코드는 백틱(```)을 사용하여 작성합니다.

<br>

```
이것이 `인라인 코드`입니다.
```
이것이 `인라인 코드`입니다.

<br>

> ## 코드 블록
> 코드 블록은 세 개의 백틱(```)을 사용하여 작성합니다. 첫 번째 백틱 세트 뒤에 특정 언어를 기입하여 지정할 수 있습니다.

<br>

````
``` python
print("Hello world")
```
````

<br>

```python
print("Hello, world!")
```

<br>

> # 태그
> 태그는 백틱(```)을 사용하여 강조하거나 스타일을 적용할 수 있습니다. 일반적으로 코드 또는 구문 강조에 사용됩니다.

<br>

```
`태그 예시`
```
`태그 예시`

<br>

---

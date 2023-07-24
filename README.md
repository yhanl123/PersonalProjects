# 마크다운 간단 문법

# 제목 표시하기
# h1
## h2
### h3
#### h4
##### h5
###### h6

Mark  
====
Down
----

# 수평선
---
***
___

# 목록(순서, 순서 없는 경우)
## 순번이 있는 목록(ol)
1. Python
2. Javascript
3. Java

## 순번이 없는 목록(ul)
- 국어
- 수학
- 영어
* 음악
+ 체육

# 들여쓰기 표현
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa  

    bbbbbbbbbbbbbbbbbbbbbbbbbb  
    cccccccccccccccccccccccccc  

# 코드블럭
```java
public class DemoApplication{
  public static void main(String[] args){
    system.out.println("Spring boot App Started");
  }
}
```

# 링크 사용하기
## 기본 링크
[구글 바로가기](http://google.com)

## 아이디를 사용하여 보여지는 문자열 표시하기
 - \[보여질 문자열][아이디] 형식으로 아이디를 지정하고 아래처럼 아이디를 사용하여 보여질 문자열을 표시한다.
 - \[아이디]: URL "Optional Title"
 - [구글 바로가기][google]
 - [google]: http://google.com "Google 사이트로 이동합니다"

## 문서 내부 참조
[문서의 처음으로 이동](#마크다운-간단-문법)

# 강조
Hello *World*  
_Hello_ World  
Hello **World**  
__Hello__ World  
~~Hello~~ World  

# 이미지
<img src="copy.jfif" alt="배경사진" title="염소 사진">

# 인용문(BlockQuote)
아래는 인용문입니다
> 첫번째 인용문
>> 인용문 안의 인용문






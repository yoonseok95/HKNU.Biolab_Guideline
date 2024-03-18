

## 마크다운에 관하여

1. 마크다운이란?
[**Markdown**](https://www.markdownguide.org/getting-started/)은 텍스트 기반의 마크업 언어로 2004년 존그루버에 의해 만들어졌으며 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능합니다. 특수 기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있습니다.
 마크다운이 최근 각광받기 시작한 이유는 깃허브([https://github.com](https://github.com/)) 때문입니다. 깃허브의 저장소Repository에 관한 정보를 기록하는 README.md는 깃허브을 사용하는 사람이라면 누구나 가장 먼저 접하게 되는 마크다운 문서였습니다. 마크다운을 통해서 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고 가독성을 높일 수 있다는 강점이 부각되면서 점점 여러 곳으로 퍼져가게 되었습니니다.


1. 마크다운의 장-단점
###### 장점
```
1. 간결하다.
2. 별도의 도구없이 작성가능하다.
3. 다양한 형태로 변환이 가능하다.
4. 텍스트(Text)로 저장되기 때문에 용량이 적어 보관이 용이하다.
5. 텍스트파일이기 때문에 버전관리시스템을 이용하여 변경이력을 관리할 수 있다.
6. 지원하는 프로그램과 플랫폼이 다양하다.
```
###### 단점
```
1. 표준이 없다.
2. 표준이 없기 때문에 도구에 따라서 변환방식이나 생성물이 다르다.
3. 모든 HTML 마크업을 대신하지 못한다.
```



## 미리 준비되어야하는 프로그램
 
1. Visual Studio 홈페이지에 접속해 ***Visual Studio code*** 프로그램을 다운받습니다.
   https://visualstudio.microsoft.com/ko/downloads/

2. Visual Studio code 프로그램에 들어가 sign in to Sync Settings 버튼을 눌러 로그인합니다.

3. 확장 프로그램 Prettier을 설치합니다.
-왼쪽 바에 확장자 도구 아이콘을 클릭 후 prettier을 검색해 설치합니다.
![Pasted image 20240306130853](https://github.com/kimahyun0606/Markdown/assets/162280996/5a071be7-e268-45b8-9ac0-97674939be66)


-왼쪽 바에 설정 바를 클릭 후 Format on Save를 검색하여 체크합니다.
![Pasted image 20240306131330](https://github.com/kimahyun0606/Markdown/assets/162280996/08005b90-fb4f-43bb-becf-da3c42d1122d)


![Pasted image 20240306131703](https://github.com/kimahyun0606/Markdown/assets/162280996/856dbc1c-6ffa-4ea2-acac-02bb3521ebdf)


![Pasted image 20240306131715](https://github.com/kimahyun0606/Markdown/assets/162280996/41908d9b-498d-483f-8eb2-caab75633929)


-Prettier가 활성화되었는지 확인합니다. (VS코드를 다시 시작해야할 수 있습니다)
![Pasted image 20240306132225](https://github.com/kimahyun0606/Markdown/assets/162280996/7d53251a-3105-493d-8762-c8e75cc7884f)


4. github 계정을 생성합니다.

6. github desktop을 다운로드합니다.





## 마크다운 사용법(문법)

Italic
>Italic체로 변환을 위해 별표[ * ] 또는 밑줄 [ _ ]를 사용합니다. 
>![Pasted image 20240307001347](https://github.com/kimahyun0606/Markdown/assets/162280996/e0a41321-7f30-4f42-b051-e060d3f52014)

>_Italic_
>
>예시 ) *Markdown*


Bold
>볼드체로 변환을 위해 별표 2개 [ ** ]를 사용합니다.
>![Pasted image 20240306132833](https://github.com/kimahyun0606/Markdown/assets/162280996/ec33a484-9fa8-4bb1-9c1c-0b97d7ec418e)
>**bold**

>
>예시 ) **Markdown**


Headers
>문서 제목을 작성할 때는 [ # ]를 사용합니다. [ # ]를 활용하여 제목 기능을 적용하고고 [ # ]의 개수로 크기를 조절할 수 있습니다. (1~6개까지 지원) # 한 개가 가장 크고, 개수가 늘수록 작아집니다.
>![Pasted image 20240306132903](https://github.com/kimahyun0606/Markdown/assets/162280996/ccf6c77a-eba5-4afc-9426-f58ced293174)

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6


Links
> 외부 주소(url)를 링크하기 위해 []와 () 괄호를 사용합니다. [text]와 (url)로 표현할 수 있습니다. [] 대괄호를 활용하여 지정한 글자에 링크를 넣을 수 있습니다.
>![Pasted image 20240306134744](https://github.com/kimahyun0606/Markdown/assets/162280996/9cb179d2-7647-4360-be46-89636c30567f)

>[text](url)
>
>예시 ) [Markdown](https://github.com/ijborda/markdown-tutorial?tab=readme-ov-file#math-equation-inline)
>
note : 일반적인 url 혹은 이메일 주소인 경우 <> 형식으로 링크를 형성합니다. 


Links (Relative)
>구체적 설명을 링크하기 위해 []와 ()괄호를 사용합니다.  [text]와 (directory)로 표현할 수 있습니다. [] 괄호를 활용하여 지정한 글자에 링크를 넣을 수 있습니다.
>![Pasted image 20240306134922](https://github.com/kimahyun0606/Markdown/assets/162280996/bcd6b87f-380a-46cf-91db-67184e230816)

> [text](directory)
>
>예시 ) [Markdown](directory)


Images
>다운로드 받은 사진을 삽입하기위해 []와 ()를 사용합니다.  !,  [이미지이름]와 (이미지주소)로 표현할 수 있습니다.
>![Pasted image 20240306135125](https://github.com/kimahyun0606/Markdown/assets/162280996/0dbc134f-620d-4a3b-af1e-bbaf45c3921d)

>![Alt-text](img-path-or-url)
>note : gif 도 적용 가능합니다. 


Blockquotes
> [ > ]를 활용하여 인용문을 작성합니다. 인용문 안에 들여쓰기로 두 번째, 세 번째 인용문을 쓸 수 있고, 다른 마크다운 요소를 포함할 수 있습니다.
>![Pasted image 20240306154131](https://github.com/kimahyun0606/Markdown/assets/162280996/9f9cbc98-35e9-4499-9e22-bb2f7be83032)

>> your-quote
>> "I have no specail talent. I am only passionately curious" -Albert Einstein
>> >"I agree"
>> >**I agree**
>


Unordered List
>순서가 없는 목록은 글머리 기호 * *, +, - 로 표현할 수 있습니다.  글머리 기호 뒤에 뛰어쓰기(스페이스)를 한번 해주고 목록을 작성해야합니다. 혼합해서 사용하는 것도 가능합니다. 결과는 모두 똑같이 점으로 표시되고 들여쓰기도 가능합니다.
>![Pasted image 20240306154300](https://github.com/kimahyun0606/Markdown/assets/162280996/4836f709-2e28-4e4a-87a8-4bd2a12aef5f)

>
* 그린
* 레드
* 블루


Ordered List
>순서가 있는 목록은 숫자로 표현하면 됩니다. 어떤 번호를 입력해도 순서는 내림차순으로 정의됩니다. 
>![Pasted image 20240306155546](https://github.com/kimahyun0606/Markdown/assets/162280996/a25deb88-371d-462a-98b7-1f1d4f005d26)

>
1. green
2. red
3. Blue


Task List
> 체크 리스트를 만들 수 있습니다. [ - ] 기호 뒤에 띄어쓰기(스페이스)를 한번 해주고 [ ] 또는 [x] 를 사용하여 체크할 수 있는 항목이 있는 목록을 만들 수 있습니다. 
>![Pasted image 20240306155627](https://github.com/kimahyun0606/Markdown/assets/162280996/ff970509-f6ca-4a5d-ad0e-4ee49a137156)

>
- [ ] List-2
- [ ] List-3
- [x] completed



줄바꿈
>줄바꿈을 하기 위해서 문장 마지막에서 < br>을 사용하면 됩니다.
>![Pasted image 20240306155713](https://github.com/kimahyun0606/Markdown/assets/162280996/51b1e174-b7de-49d1-949a-ba8d49dcb803)

>Do I contradict myself?  <br>
>Very well then I contradict myself <br>
>(I am large, I contain multitudes.)***
>
>Note: Each * represents a space in keyboard


수평선
>[ * ]과 [ _ ]을 이용하여 줄을 만들어 수평선을 만듭니다. 내용이나 페이지를 나눌 때 사용합니다. 마크다운 문서를 미리보기로 출력할 때 페이지 나누기 용도로 많이 사용합니다
>
> *****


Subscipt
>화학식처럼 아래에 적은 문자(숫자, 기호)를 표시할 수 있습니다. <>, sub, /와 문자들을 조합하여 사용합니다. 
>![Pasted image 20240306162736](https://github.com/kimahyun0606/Markdown/assets/162280996/e97eff5a-f7cd-416a-b64e-2040583a69d4)

><sub>subscript</sub>
>H<sub>2</sub>0


Superscript
>첨자를 표시할 수 있습니다. <>, sup, /와 문자들을 조합하여 사용합니다.
>![Pasted image 20240306162934](https://github.com/kimahyun0606/Markdown/assets/162280996/cc32bc92-abc6-4c40-981b-53d6da8b985a)

><sup>subscript</sup>
>R<sup>3</sup>


Code (inline)
>마크다운으로 코드도 넣어줄 수 있습니다. Python, java, c, c++ 등 다양한 프로그래밍 언어가 가능합니다. ' '안에 코드를 넣어주면 됩니다. 
>![Pasted image 20240306163039](https://github.com/kimahyun0606/Markdown/assets/162280996/65885db2-4c7f-4161-97a5-71f8edf2cb8e)

>`inline-code`



Code (block)
>코드블럭은 다음과 같이 2가지 방식을 사용할 수 있습니다. 
> 1. `` 를 이용하여 코드 블록을 만들 수 있습니다. 기호 3개를 연속하여 표시하면 펜스가 만들어 집니다.
> 2. < pre >, < code >, /를 조합하여 사용합니다. 
>![Pasted image 20240306165034](https://github.com/kimahyun0606/Markdown/assets/162280996/5559b34c-cbf0-4092-9763-ec19c68b2d25)

>![Pasted image 20240307102625](https://github.com/kimahyun0606/Markdown/assets/162280996/33477b86-908b-4c07-9937-97149ef2c414)

>
Block code
```
```


들여쓰기
>4개의 공백(스페이스) 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속됩니다. 
>![Pasted image 20240307142956](https://github.com/kimahyun0606/Markdown/assets/162280996/8635ad86-d843-40d7-883f-ae49e6403f22)

> 한줄 띄어 쓰지 않으면 인식이 안되는 문제가 발생합니다.
> 
this is a normal paragraph:   
    this is a code block
end code block
   

Math equation (inline)
>$를 사용하여 수학식을 넣어줄 수 있습니다. 
>![Pasted image 20240306165426](https://github.com/kimahyun0606/Markdown/assets/162280996/118da656-590d-404a-aef4-c9f825da839b)

>$y=3x$


Math equation (block)
>$ 2개를 사용하면 수학식을 블록에 넣어줄 수 있습다.  
>![Pasted image 20240306172131](https://github.com/kimahyun0606/Markdown/assets/162280996/2ab665e4-0a15-4238-9165-dadb2017cb04)

> $$ block-equation $$


Tables
>마크다운에 table을 직접 입력할 수 있습니다. | 로 뼈대를 잡아주고 컬럼명과 내용은 --로 구분해줍니다. 굵게, 기울임 등 기본적인 마크다운 문법도 적용 가능합니다. 
>![Pasted image 20240306172205](https://github.com/kimahyun0606/Markdown/assets/162280996/eddc7ca8-86a0-463c-93d0-85b6f8a4f887)

 | Heading1 | Heading2 | Heading2 |
  | --------- | --------- | --------- |
| Data     | Data     | Data     |
>
>예시 ) 

| Heading1 | Heading2 |
| -------- | -------- |
| 0.2      | 0.3      |



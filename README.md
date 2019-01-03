# markdown

마크다운이란?

마크 다운은 웹에서 텍스트의 스타일을 지정하는 방법이다. 문서가 어떻게 보여지는지를 컨트롤 할수있다. 글자 서식을 지정하고, 이미지를 추가하고, 목록을 만드는것 등이 마크다운으로 할수있는 몇가지들이다. 주로 마크다운은 # 또는 * 와 같은 알파벳이 아닌 문자와 같이 쓰이는 일반 텍스트이다.

마크다운 문법:

1. 텍스트 (Text) 

   1.1 강조: 마크다운으로 단어들을 굵거나 기울임 꼴로 표시해 강조하는것은 매우 쉽다.
   
   eg) 
   **word** 혹은 __word__ 와 같이 ** / __ 을 사용하면 단어가 굵게 표시.
   *word* 혹은 _word_ 와 같이 * / _ 을 사용하면 단어가 기울여져 표시.
   _word1 **word2** combine them_ 와 같이 둘 다 같이 사용할 수도 있다.
 
   1.2 링크:
   
   eg) http://github.com - automatic!
       [GitHub](http://github.com)
       
       [link to Google!](http://google.com)
       
   1.3 헤더: 헤더를 쓰기 위해서는 # 문자로 시작한다. 헤더에는 총 6개의 레벨이 있고 숫자가 높아질 수록 헤더 사이즈가 작아진다.
   
   eg) 
   # This is H1
   ## This is H2
   ### This is H3
   #### This is H4
   ##### This is H5
   ###### This is H6
   
   1.4 인용: 다른 사람의 말을 인용할땐 블럭인용 '>' 문자를 사용하면 된다.
   
   eg) 
   As Kanye West said:
   > Coffee. The finest organic suspension ever devised... I beat the Borg with it.
   > We're living the future so the present is our past.

2. 목록 (List)

   2.1 Ordered (번호): 숫자와 점을 사용한다.
   
       1. Item 1
       2. Item 2
       3. Item 3
   
   2.2 Unordered (bullet points): * 문자를 사용한다.
   
       * Item 1
       * Item 2
       * Item 3
         * Item 3a
         * Item 3b
           * Item 3ab

3. 이미지 (Image): 이미지를 삽입하고 싶을땐 아래 syntax를 사용한다.
   
   Format: ![Alt Text](url)
   ![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

4. 코드 (Code)

   4.1 Inline code block: `(back quote)로 텍스트를 감싸 사용한다.
   
   eg) `var example = true`
      
   4.2 Code fencing:
   
   eg)
   
```
if (isAwsome) {
  return true
}
``` 

5. GitHub Flavored Markdown (GFM): GFM은 표준 Markdown에 조금더 편하게 변경한 github 버젼이다.

   5.1 Syntax highlighting: GFM을 사용해 syntax를 하이라이트 할 수 있다.
  
   eg)

```javascript
if (isAwsome) {
  return true
}
```

   5.2 작업목록 (Task List): Pull Requests에서도 작동한다.
   
   eg) Task lists are:
   - [x] This is a complete item
   - [ ] This is an incomplete item

   5.3 코멘트 보내기: 혹시 누군가에게 코멘트를 보내고 싶다면, 유저 이름 앞에 @ 를 붙일 수 있다.
   
   eg) 
   Hey @doyeongkim - I like your sweater!
   
   5.4 테이블 (Table): 단어 목록을 조합하고 그 단어들을 하이픈 (첫번째 행)으로 나눈 다음, 각 열을 파이프로 분리하여 테이블을 만들 수 있다.
   
   eg)
   
   First Header | Second Header
   ------------ | -------------
   Content 1 | Content 3
   Content 2 | Content 4
   
   5.5 취소선: 어떤 단어든지 ~~ 로 감싸져있으면 단어 위에 취소선이 나타난다.
   
   eg) ~~strikethrough~~
   
   5.6 이모티콘 (Emoji): 깃허브는 이모지도 제공한다. 
   
   eg) :sparkles: :camel: :boom:


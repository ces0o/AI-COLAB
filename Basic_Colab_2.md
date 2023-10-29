# Google Colab  
## [Notebook 단축키]  
* 선택된 셀을 실행 : Ctrl + Enter
* 실행 후 다음 셀로 이동 : Shift + Enter
* 실행 후 다음 셀 추가 : Alt + Enter
* 저장 : Ctrl + S
* 엔터키 : 편집모드
* ESC : 선택모드
* 마크다운으로 전환 : Ctrl + M M
* 코드로 전환 : Ctrl + M Y

## [Markdown 기초]  
### 기본 문법  
* 타이틀
  
  # H1  
  ## H2  
  ### H3
  #### H4
  ##### H5
  ###### H6  

* 강조
  
  **진하게**  
  __밑줄__  
  --취소--  
  _이탤릭_  

* 문장 줄바꿈
  
  문장
  줄바꿈
  안함  

   문장  
   줄바꿈  
   함  

* 블럭(인용) 들여쓰기. Code Block
  
  > 블럭 1단계  
  >> 블럭 2단계  

* Code Block
  
  ```python
  import something
  a = 10
  print(a)
  if a > 10:
    print(a)
  ```

* 목록
  
  * 사과
  * 오렌지
    + 딸기
    + 파인애플
  - 포도
  - 바나나
  1. 참외
  2. 수박

* 하이퍼링크, 수평선, 표

  [바로가기](http://google.com)
  <http://google.com>

  ***
  수평선


  ----

  |1열|   2열  |  3열 |
  |:------------|----:|:-----:|
  | 왼쪽 | 오른쪽 | 가운데 |
  | 정렬하기 | 정렬하기 | 정렬하기 |
  | 테스트 | 테스트 | 테스트 |

* 이미지. 체크박스

  * 그림
    
    <img width="452" alt="image" src="https://github.com/ces0o/-1/assets/127365253/8b5f0a73-0805-42a9-a8a1-7d6b689867a3">

  * 체크박스
    
    * [ ] 비어있는 체크박스
    * [x] 체크된 체크박스

* 수식 - 단독

$$
\begin{aligned}
f(x)&=ax^2+bx+c\\
g(x)&=Ax^4
\end{aligned}
$$  

$\displaystyle\lim_{s\rarr\infin}{s^2}$
$\displaystyle\sum_{i=0}^{\infin}{(y i-t i)^2}$  


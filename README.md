# HTML
> 웹개발 강의에서 공부한 HTML 관련 내용입니다.

<hr/>

# DAY 01

## 1-1. 서버와 클라이언트   

- 클라이언트: 서버에게 요청하는 대상  
- 서버: 요청받은 서비스를 응답해주는 대상  

## 1-2. 웹(Web)  

- 요청과 응답이 일어나는 장소.  


## 1-3. 웹 브라우저(Web browser)  

- 사용자의 요청에 맞는 주소로 찾아가서 인터넷 컨텐츠(문서와 그림, 멀티미디어 파일 등)를  
  검색 및 열람 후 사용자에게 응답하기 위한 응용 프로그램의 총칭이다.  
- 주요 웹 브라우저로는 모질라 파이어폭스, 구글 크롬, 마이크로스프트 엣지,  
  오페라, 사파리 등이 있다.  


## 1-4. 프로토콜(Protocol): 통신 규약  

- 사람끼리 소통할 때 서로 이해할 수 있는 공용어를 사용해야 하듯이 컴퓨터끼리도 공용어를 사용해야 한다.  
- 이러한 공용어를 원활하게 통신하기 위해서 필요한 규약을 프로토콜이라고 한다.  
- 사용자의 요청에 반드시 응답하도록 약속한다.  

- http://(Hypertext Transfer Protocol)  
   - 클라이언트와 서버 간의 웹 페이지 등의 자원을 통신하는 규약  
   - 텍스트로 통신하기 때문에 가로채어 본다면 누구든 내용을 볼 수 있다.     

- https://(Hypertext Transfer Protocol Secure Socket)    
   - SSL(Secure Socket Layer) 프로토콜을 이용하여 자원을 공개키 암호화 방식으로  
     암호화해서 통신하는 규약  

   
## 1-5. IP(Internet Protocol)  

- 사람이 태어나면 출생신고를 하고 고유번호인 주민번호를 발급받는다.  
- 이를 통해 서로를 구분하듯이 네트워크 상에서 인터넷에 접속할 때 다른 컴퓨터와  
  구별될 수 있도록 하는 고유번호를 IP주소라고 한다.  
- 클라이언트가 찾아갈 서버의 고유한 값, 컴퓨터가 컴퓨터를 찾을 때 쓰는 고유한 값  

## 1-6. 도메인(Domain)    

- IP 주소는 기억하고 이해하기 힘들기 때문에 이를 위해서 이름을 부여할 수 있도록 한 것.  
- 도메인을 통해 IP 주소를 검색할 수 있다.  

- 아이피 주소로 직접 접근하면 연산이 필요한 부분이 제외되거나 프로토콜이 적용되지 않을 수 있기 때문에  
  반드시 도메인을 통해 사이트에 접근하기로 한다.  


## 1-7. WWW(World Wide Web)  

- 인터넷에 연결된 전 세계 컴퓨터들을 통해 사람들이 정보를 공유할 수 있는 정보 공간  

## 1-8. W3C(더블유삼씨)  

- WWW를 위한 표준을 제정하고 관리하는 중립적인 기관이다.  


## 1-9. 웹 표준(Web Standard)  

- 웹에서 표준으로 사용되는 기술이나 규칙을 의미하며, 이는 특정 브라우저에서만 사용되는 비표준화된 기술을 배제하고  
  W3C의 토론을 통해 나온 권고안을 사용하는 것을 말한다.  
- 웹 문서의 구조와 표현, 그리고 동작을 구분해서 사용하는 것을 뜻한다.  

1. HTML(Hypertext Markup Language)
   
   - 웹 페이지에서 다른 페이지로 이동할 수 있도록 해주는 마크업 언어이다.  
   - 마크업 언어란 태그 방법 체계를 의미하며, 태그 등을 이용하여 문서나    
     데이터의 구조를 기술하는 언어이다.  

2. CSS(Cascading Style Sheets)
   
   - 구체적으로 어떤 스타일로 요소가 표시되는 지를 정하는 규격이다.  
   - HTML은 문서를 구조화(레이아웃)할 수 있으나 꾸밀 수 없고,  
     CSS를 통해 디자인하여 웹 페이지에서 내용과 스타일을 분리하고,  
     역할도 분리해준다.  

3. JS(Javascript)
   
   - 화면 쪽에서 연산이 가능한 스크립트 언어이다.  
   - 사용자의 다양한 이벤트 처리, 비동기 통신 등을 자유롭게 사용할 수 있다.  
   - HTML 안에서 태그형태로 JS를 사용할 수도 있으며, 외부 파일로 제작 후  
     포함시켜 사용할 수도 있다. 유효성 검사, 통신 등을 담당한다.  

4. XHTML(Extensible HTML)  
   
   - 기존에 사용되던 HTML 규격이 가진 문제점을 극복하고 보다 다양한 분야에 응용될 수 있도록  
     해주는 여러가지 확장된 기능을 포함한다. 하지만 XML기반으로 만들어졌기 때문에  
     지원되지 않는 브라우저도 있다. 따라서 HTML과 XHTML은 사실상 큰 차이 없이 사용된다.  

5. XML(Extensible Markup Language)
   
   - 어떠한 데이터를 설명하기 위해서 임의로 지은 태그로 데이터를 감싼다.  
   - 태그로 데이터를 설명하며, 이것이 데이터의 표시(Markup)가 되고 추가적인 데이터가 생기면  
     태그 추가와 태그 내부 내용 추가를 할 수 있다. 따라서 데이터 전달에 목적이 있다.  

          <?xml version="1.0">
          <user>
             <userId>hds1234</userId>
             <name>한동석</name>
          </user>

<hr/>

# DAY 02

## 2-1. HTML의 요소  

     <p> You are better </p>
     --- -------------- ----
     (1)    (3)      (2)
  
     (1) 여는 태그(Opening tag): 요소의 이름(p)과 열고 닫는 꺽쇠 괄호로 구성된다.
     (2) 닫는 태그(Closing tag): 요소의 이름 앞에 슬래시(/)가 있다.
     (3) 내용(Content): 요소의 내용이며, 단순한 텍스트를 의미한다.

## 2-2. HTML 주석  

     <!-- 주석 -->: Ctrl + Shift + /


<hr/>

# DAY 03

## 3-1. HTML 요소의 종류  

▶ 블록 요소  
   - p, h, ul, ol, div, form, table,... 등  
   - 코드 상에 한 줄로 이어 써도 화면 상에서는 앞 뒤 요소 사이에 새로운 줄을 만들어서 나타난다.
     
          코드
          <p>apple</p><p>banana</p>
    
          화면
          apple
          banana
     
   - 영역이 정확히 구분되어 있기 때문에, width, height 속성을 수정할 수 있다.  
   - margin-top, margin-bottom 속성도 잘 적용된다.  
   - padding-top, padding-bottom 속성도 잘 적용된다.  
   - div 태그  
      1. 다른 HTML 요소들을 하나로 묶는 데 사용되는 대표적인 블록 요소이다.  
      2. 주로 여러 요소들의 스타일을 한 번에 적용하기 위해 div 태그를 사용한다.  

▶ 인라인 요소  
   - span, a, img, strong, em, ... 등  
   - 새로운 줄을 만들지 않고 작성한 단락 내에 나타난다.  
   - 안에 있는 내용만큼만 영역을 차지한다.
     
          코드
          <strong>apple</strong><em>banana</em>
    
          화면
          applebanana
     
   - 영역이 불분명하기 때문에 width와 height를 임의로 부여할 수 없다(img 태그 제외)  
   - margin-top, margin-bottom 속성도 적용되지 않는다.  
   - padding-top, padding-bottom 속성도 적용되지 않는다.  

   - span 태그  
      1. 텍스트의 특정 부분을 묶는 데 자주 사용되는 요소이다.  
      2. 주로 텍스트의 특정 부분에 따로 다른 스타일을 적용하기 위해 사용한다.  
  
▶ 인라인 블록 요소  
   - button, input, select, ...  
   - inline 요소와 동일한 영역(내용만큼)을 가지지만 width와 height를 설정할 수 있다.  
   - margin-top, margin-bottom 속성도 잘 적용된다.  
   - padding-top, padding-bottom 속성도 잘 적용된다.  
  

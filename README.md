# front

# html
- 태그
    - strong은 언어 강조
    - h1은 제목
    - a는 링크, ex) <a href= "www.naver.com" 이게 링크를 나타내는 텍스트
        - <a href="https://www.naver.com" target="_blank" 은 새로운 페이지로 이동   
    - ul로 li 리스트 태그를 감싸는 행위를 그룸핑 한다고 한다.
    - ol로 감싸게되면 앞에 숫자가 붙는다.
    - 웹 페이지 글자가 깨질 경우 인코딩 방법 지정 <meta charset="utf-8"
    - head 태그는 웹페이지 정보, body는 웹페이지 내용.
    - 문단의 단락을 표현하기 위해서 p태그를 사용한다.
    - 단락을 한칸 띄우기 태그는 <br>이다.
    - 이미지 태그에서 이미지 파일이 깨질 것을 대비 해서 alt -> alternative text를 작성한다.

- DOCTYPE
    - Document type declaration -> !DOCTYPE은 html5를 가르킨다.

- TABLE
    - table -> (thead -> tr -> th) - 진하게 표현 / (tbody -> tr -> td) / (tfoot -> tr -> td)
    - 테이블을 병합할 때 행은 rowspan="칸수" , 열은 colspan="칸수"

- FORM
    - form 태그는 입력한 정보를 어디로 보낼지 나타내는 정보이다.

- RADIO
    - radio버튼은 같은 name을 가지는 input끼리 그룹핑된다.
    - checkbox를 이용하면 다중 선택이 가능하다.
    - checked라는 태그를 적어주면 default로 선택되어서 화면이 보여진다.

- hidden
    - hidden 속성을 사용하면 사용자에게는 보이지 않지만 key : value 값으로 보이지 않는 값들이 서버로 전송된다.

- method
    - 내용을 숨기고 서버측에 넘기고 싶을 때는 post를 사용한다.

- font
    - 크기는 1 ~ 7까지 사이즈가 있고 default가 3이다.
    - 시각적인 디자인일 뿐이지 TEXT에 대한 어떤 정보도 없어서 사용하지 않는 것을 지양해야 한다.

- meta
    - charset="utf-8"의 의미는 컴퓨터에 저장하는 방식은 utf-8로 저장한다는 의미이다.

- 의미론적 태그
    - header는 웹 페이지상에서 가장 중요하거나 의미있는 내용이 있는 영역이다. 기능적으로는 문제가 없다.
    - footer는 사이트에 대해서 부가적인 내용이 들어가 있다.
    - nav는 navigation 역할을 하는 것을 지정한다.
    - article은 본문의 내용을 나타내는 것을 말한다.

- 검색엔진 최적화
    - https://www.hackerrank.com/skills-verification/rest_api_intermediate/md1hiktjtk
    - 의미론적 태그를 잘 사용하는 것이 검색엔진을 최적화 하는 과정이다.
    - title 태그를 이용해서 페이지의 제목을 나타내기 (매우 중요하다.)
    - description 메타 태그 활용하기 (검색할 때 보여지는 간단한 단락이나 한 문장을 나타낸다.)
    - URL 구조를 개선하기
        - URL이 너무 길면 좋지 않다.
        - 단순 디렉토리 구조 만들기
        - 같은 컨텐츠가 여러개의 주소를 가진다면 리다이렉션을 통해서 하나의 주소로 합치는 것이 좋다.
    - 사이트 이동 경로를 사용자에게 알려주는 것이 좋다.
    - 사용자가 URL의 일부를 제거하는 경우에 404에러보다는 default 페이지로 이동하게 하는 것이 좋다.
    - 사이트의 이동을 js로 하게 된다면 다른 검색엔진에서는 js의 내용을 이해하기 힘들다. 그래서 hyperText를 사용해서 이동하는 것이 좋다.
    - 검색 엔진을 위한 것이 아닌 사용자를 위한 콘텐츠 작성 해야한다.
        해당 콘텐츠와 관련없는 description이나 keyword를 사용하게 된다면 웹 스팸으로 등록 될 수도 있다.
    - 내용을 함축하는 텍스트 선택
        - 링크에 사용되는 앵커 텍스트는 링크되는 페이지가 무슨 내용인지에 대한 기본적인 정보 제공
    - 이미지 관련 정보는 alt 속성을 이용해 제공 하는 것이 좋다.
        - 구글 이미지 검색을 할 때 alt를 기반으로 검색 결과를 보여준다.
    - robots.txt를 효과적으로 활용하기
        - sitemap : 사용자에게 페이지의 전체 구조를 한번에 보여주도록 한다.
    - 링크하고 있는 자식 페이지가 많을 수록 검색 순위가 높아진다.
    
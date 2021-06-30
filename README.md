# front

# html
- 태그
    - strong은 언어 강조
    - h1은 제목
    - a는 링크, ex) <a href= "www.naver.com">이게 링크를 나타내는 텍스트</a>
        - <a href="https://www.naver.com" target="_blank">은 새로운 페이지로 이동   
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
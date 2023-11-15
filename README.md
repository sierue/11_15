# 11_15
## markdown 문법
1. 헤더
   헤더는 큰 제목, 작은 제목, 글머리로 나뉘며
   큰제목은 문서제목에 쓰이며 제목 아래 =============을 작성한다.
                            
   작은 제목은 문서 부제목에 주로 쓰이며 제목 아래 ------------ 방식으로 작성한다.
                                      
   글머리는 총 6개까지 생성 할 수 있고, # This is a H1 형식으로 #의 갯수를 늘려가며 작성한다. #의 갯수가 많을수록 하위목록에 들어간다.
2. 목록
   순서있는 목록은 숫자와 점을 사용한다.
   1. 2. 3. 방식으로 사용한다.
   순서가 없는 목록은 "*, +, -" 방식이 있으며 혼합해서 사용도 가능하다.
3. 수평선
   수평선은 미리보기로 출력할 때 페이지 나누기 용도로 많이 사용되며,
   "* * *, ***, *****, - - -, -----------------------" 등의 방식으로 사용할 수 있다.
4. 링크
   링크는 참조링크, 외부링크, 자동연결이 있으며,
   참조링크는 "[link keyword][id]"
    "[id]: URL "Optional Title here""
    // code
    "Link: [Google][googlelink]"
    "[googlelink]: https://google.com "Go google""
   외부링크는
   "[Title](link)"
   "[Google](https://google.com, "google link")"
   자동연결은
   "<http://example.com/>"
   "<address@example.com>"
5. 강조
   강조는 문장 사이에 강조할 때 쓰며 예시로는
   "*single asterisks*"
   "_single underscores_"
   "**double asterisks**"
   "__double underscores__"
   "~~cancelline~~"
   이 있다.

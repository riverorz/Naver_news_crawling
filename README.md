## Naver_News_Webcrawling
현재 네이버에서 네이버 뉴스 제공할 때 최상의 검색 결과 품질을 위해 뉴스 검색 결과를 4,000건까지만 제공을 해주고 있다.

<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/1.PNG" width = "600px" alt="naver search"></p></a>

크롤링 진행 시에 검색 결과가 4000건 이상이어도 수집할 수 있는 데이터는 4000건이 한계이다.( 계속 수집하면 400페이지 내용을 계속 수집)

그렇기 때문에 뉴스 수집을 진행하기 위해는 4000건 이하로 기사를 계속 호출해 수집해야 한다. 기간을 잘 조정해서 수집을 하면 되지만 하루 올라오는 기사량이
불규칙하기 때문에(하루 기사량이 2000건 이상일 경우도 포착) 제일 효과적인 방법은 하루 단위로 크롤링 하는 게 안전하다.




<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/2.PNG" width = "400px" alt="naver search"></p></a>
<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/3.PNG" width = "400px" alt="naver search"></p></a>

위 사진을 보면 같은 토픽이지만 페이지가 넘어가면 검색 결과가 다르다는 걸 알 수 있다.(크롤링 방지를 위해서 그러는 건지는 모르겠음)
정확한 검색량을 제공을 안 해주기 때문에 페이지 수를 오버해서 같이 기사를 수집할 수도 있고 페이지 수를 적게 잡아서 데이터를 다 수집 못할 수도 있다.
이런 현상은 관련도 순으로 했을 때 나오는 결과고


<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/4.PNG" width = "400px" alt="naver search"></p></a>
<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/5.PNG" width = "400px" alt="naver search"></p></a>


최신순, 오래된 순으로 검색을 진행했을 때는 정확한 검색량을 제공한다.(테스트 결과 관련도 순으로 검색한 량은 최신순, 오래된 순 기사 결과 양 이랑 같았다.)

<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/6.png" width = "600px" alt="naver search"></p></a>

이 프로그램은 위 사진처럼 네이버 뉴스라는 버튼이 있는 기사만 수집을 한다.
장점 : 간편하게 기사를 수집
단점 : 많은 양의 기사 수집 X

프로그램 전개도
<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/7.png" width = "600px" alt="naver search"></p></a>


문제시 삭제
참고 사이트 : https://bumcrush.tistory.com/155

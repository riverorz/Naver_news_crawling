## Naver_News_Webcrawling
현재 네이버에서 네이버 뉴스 제공 할 때 최상의 검색결과 품질을 위해 뉴스 검새결과를 4,000건까지만 제공을 해주고있다. 

<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/1.PNG" width = "600px" alt="naver search"></p></a>

크롤링 진행 시에 검색결과가 4000건 이상이여도 수집할 수 있는 데이터는 4000건이 한계이다.( 계속 수집하면 400페이지 내용을 계속 수집) 

그렇기 때문에 뉴스 수집을 진행 하기 위해는 4000건 이하로 기사를 계속 호출해 수집해야 한다. 기간을 잘 조정해서 수집을 하면 되지만 하루 올라오는 기사량이 
불규칙하기 때문에(하루 기사량이 2000건 이상일 경우도 포착) 제일 효과적인 방법은 하루단위로 크롤링하는게 안전하다.




<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/2.PNG" width = "400px" alt="naver search"></p></a>
<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/3.PNG" width = "400px" alt="naver search"></p></a>

위에 사진을 보면 같은 토픽이지만 페이지가 넘어가면 검색결과가 다르다는걸 알 수 있다.(크롤링 방지를 위해서 그러는건지는 모르겠음) 
정확한 검색량을 제공을 안해주기 때문에 페이지수를 오바해서 같이 기사를 수집할 수도 있고 페이지수를 적게 잡아서 데이터를 다 수집 못할 수 도 있다. 
이런 현상은 관련도순으로 했을때 나오는 결과고 

<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/4.PNG" width = "400px" alt="naver search"></p></a>
<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/5.PNG" width = "400px" alt="naver search"></p></a>


최신순, 오래된순으로 검색을 진행 했을때는 정확한 검색량을 제공한다.(테스트 결과 관련도순으로 검색한 량은 최신순, 오래된순 기사결과량 이랑 같았다.)

<a href="#"><p align="center"><img src= "https://github.com/riverorz/webcrawling/blob/master/Navern_News%20Crawling/images/6.PNG" width = "400px" alt="naver search"></p></a>




그렇기 때문에 이프로그램은 키워드를 검색어,시작날짜, 끝날짜 최신순을 포함한 url로 크롤링을 진행하고 


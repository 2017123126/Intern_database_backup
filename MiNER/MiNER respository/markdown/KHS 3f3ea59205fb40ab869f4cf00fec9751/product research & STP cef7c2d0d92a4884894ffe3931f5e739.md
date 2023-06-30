# product research & STP

Tags: research
상태: Done
작성 일자: 2022년 9월 16일 오후 3:30

1. 배경설명
    1. Problem - 문제의 정의와 검증
        1. 우리가 추구하는 문제 상황
            1. 나중을 위해 스크린샷을 저장 (나중에 이 바지 사야지, 나중에 이 글귀 봐야지)
            2. 이후에 찾으려고 해도 찾기 어려움
            3. 그러다보니 찾지도 않는 스크린샷이 계속 쌓임
        2. 그 문제 상황 이면의 욕구
            1. 필요할 때 쉽게 찾을 수 있었으면…  내가 굳이 찾으려고 노력하지 않았으면…
            2. (만약 가능하다면) 필요할 때 누군가 찾아줬으면…
                
                i와 ii 두 가지 솔루션을 구현했을 때의 코스트와 효용을 비교해 볼 필요가 있다고 봅니다. 알아서 찾아주는 것을 완벽히 구현할 수 없다는 점이나 어떤 욕구가 더 보편적인가(낮은 단계인가)를 고려해 보면 필요할 때 쉽게 찾을 수 있도록 하는 솔루션이 선행되어야 한다는 결론이 나옵니다.
                
            3. 쌓여서 부담되는 일이 없었으면…
            4. (궁극적으로 유도해야 하는 방항) 내가 하려고 했던 거로 바로 연결해 줬으면
        3. 문제 상황 검증 여부
            1. 사실상 대부분의 20대 유저가 해당하는 문제
    2. Solution - 최적의 해결책을 찾기 (usability, feasibility, value)
        1. 우리가 추구하는 포지셔닝
            1. 수동적이보다는 적극적인 어플리케이션
            2. 딱 봤을 때 이해하기 쉬울 정도의 직관성
            3. 방문 횟수가 많은 앱
                
                평균적으로 방문 횟수가 많을 것이며 그래야 한다는 데에 동의하지만, ‘체류 시간이 짧아야 한다'고 생각하지는 않습니다.
                
2. 기존에 찾아본 비슷한 제품들
    1. [Slidebox](https://play.google.com/store/apps/details?id=co.slidebox&hl=ko&gl=US)
        1. 검색보다는 정리를 위한 앱
        2. 적극적이기보다는 수동적인 앱
    2. [hash photos](https://www.hashphotos.app)
        1. 사진과 관련된 모든 툴은 조금씩 다 건드린 앱
            1. 사진 정리를 위한 앨범 (폴더)
            2. 사진 정리를 위한 유저가 직접 입력하는 태그 
            3. 날짜로 사진 검색
            4. 간단한 gif 만들기
            5. 비슷하게 생긴 사진 찾고 비교하기
        2. 검색과 관련해서는 여전히 적극적이기보다는 수동적인 앱
    3. [사진청소기](https://play.google.com/store/apps/details?id=com.jpspso.photocleaner&hl=ko&gl=US)
        1. 사진 정리를 위해 이런 것들을 골라줌
            1. 비슷한 사진
            2. 유사한 순간
            3. 큰 파일
        2. 사진 정리를 위해서는 적극적이지만 스크린샷 정리를 위해서는 제 역할을 하지 못함
            1. 스크린샷이 저장된 목적을 달성했는지 여부를 알 수 없음
    4. [screenshot pro](https://www.youtube.com/shorts/V8bexl_3Mus)
        1. 스크린샷 검색
            1. 스크린샷 내부의 텍스트를 인식해서 검색함
            2. 그러나 비슷한 태그를 추천하는 등 적극적이지는 못함
        2. 스크린샷 태깅
            1. 검색을 위한 태깅이 아닌 정리를 위한 태깅임
                1. 유저가 스스로 태깅을 하도록 유도
                2. 자동으로 태깅이 되는 것이 아니라 유저 스스로의 정리정돈을 위한 기능으로 수동적임
                
3. 추가적으로 찾아본 비슷한 제품들
    1. [screenotate](https://screenotate.com)
        1. 스크린샷 검색
            1. 스크린샷 내부의 텍스트를 인식해서 검색함
            2. 스크린샷의 메타 데이터를 인식해서 검색함
            3. 그러나 비슷한 태그를 추천하는 등 적극적이지는 못함
        2. 스크린샷 태깅
            1. 스크린샷 태그는 UI의 일부가 아님
            2. 검색을 위해 마련된, 유저로부터 숨겨진 요소임
    2. [firefox screenshot go](https://support.mozilla.org/en-US/kb/firefox-screenshotgo-capture-organize-screenshots)
        1. 스크린샷 검색보다는 정리에 초점을 맞춘 앱
        2. 스크린샷 OCR
            1. OCR 글자를 복붙하거나 공유하는 용도
    3. [gyazo pro](https://gyazo.com/pro)
        1. 스크린샷 검색
            1. 스크린샷 내부의 텍스트와 내용을 인식해서 태깅함
            2. 스크린샷 내부의 텍스트와 내용을 검색함
            3. 그러나 비슷한 태그를 추천하는 등 적극적이지는 못함
        2. 스크린샷 공유
            1. 찍자마자 바로 링크의 형태로 공유 가능
4. Similar solutions to information curation services
    1. [pikurate](https://www.youtube.com/watch?v=ojoXzDV-eog)
        1. 링크 정리 및 공유 서비스
            1. 하나의 주제를 담은 pik을 생성한다.
            2. 그 pic 내에서 category들을 생성한다.
            3. 웹사이트 링크들을 복붙하여 알맞은 pic의 알맞은 category에 저장한다.
        2. [차별점](https://www.youtube.com/watch?v=V_dFgGVBcO0)
            1. 특정 주제에 대한 정보를 논리적으로 분류하는 무한대의 구조화된 데이터 패키지를 만든다
            2. 링크 정리 및 공유를 위해 수많은 유저들이 만든 pik들을 가지고 특정 주제에 대해 정리된 정보를 원하는 유저들에게 제공
            3. 조사를 시작하자마자 완성된 결과를 얻을 수 있는 경험을 이용자들에게 제공
            4. 이용자들의 특성과 그들이 보는 Pik을 분석하여 다른 이용자들에게 적절한 Pik을 추천함
    2. [갤럭시 내장 기능](https://sayhohoho.tistory.com/29)
        1. 스크린샷 정리 및 공유 서비스
            1. 스크린샷을 찍은 이후 유저가 #태그 버튼을 누르면 해쉬태그를 생성할 수 있는 화면으로 넘어간다.
            2. 화면 컨텐츠에 맞춰서 유저가 원할 법한 해쉬태그의 후보들을 추천해준다.
            3. 유저가 해당 후보를 탭하면 해쉬태그로 추가하여 검색에 이용할 수 있다
        2. 공통점
            
            사실상 같은 기술을 사용한다.
            
        3. 차별점
            1. 적극적이지 않다.
                1. 유저가 검색을 하기 전에 태그를 추천해주지 않는다
                2. 유저가 직접 선택해야만 태그가 더해지고 검색이 가능해진다.
    3. [Big tech’s movement](https://www.wired.co.uk/article/future-screenshots)
        1. automatically capturing metadata of a screenshot
            1. saving links
            2. street address, GPS location
            3. data about a music being played
            4. full copyable text
            5. website URL
            6. video length
            7. direct link to a chat session
            8. device state
            9. image alt text
        2. 공통점
            1. automatically extracting metadata of a screenshot
                
                even more meta data being extracted..
                
        3. 차별점
            1. just a tech or a patent
            2. no thoughts on users’ needs
            3. big techs need to satisfy a wide range of customers and may end up being just a minor feature hiding between their big mega products
            4. personalization
        
    
    그림 요약 - 여기는 블루오션이다
    
    ![STOP.png](product%20research%20&%20STP%20cef7c2d0d92a4884894ffe3931f5e739/STOP.png)
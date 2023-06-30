# [delayed]브라우저 익스텐션

Tags: error-ly
상태: In progress
작성 일자: 2022년 10월 4일 오후 4:38

## Todo’s

- [ ]  가설의 빈칸 채우기

---

## Status quo

- 브라우저 익스텐션
    - 개요
        
        - 입력
        
        모바일/PC: Screenshot
        
        -출력
        
        모바일: 키보드, 클립보드, safari extension(검색 개인화)
        PC: 클립보드 형식의 spotlight 앱, add-ins and extension(검색 개인화)
        
    
    - 기능
        - ’대화형 키보드, 클립보드’에서 사용된 기술을 이용해 포털사이트 검색 결과를 개인화해서 맞춰주는 역할을 한다.
        → 샷태그에 적용된 검색 로직을 똑같이 사용한다
        구글 검색어를 태그라고 인식하고 검색 결과 가져오기
        - 구글에 “오늘 저녁 뭐먹지”라고 검색했을 때 오늘 아침 출근길에 SNS에서 캡쳐해 둔 사진을 검색 결과로 띄워주거나 그 이미지를 검색할 수 있게 해주는 등 검색의 지평을 넓힐 수 있다.
        
        유저가 어느 날 문득 웹브라우저에서 검색한 키워드에서, 예전에 자신이 갖고 있던 적합한 스크린샷을 결과로 마주치는 것이 중요
        
        우연히 특정 검색어를 포털 사이트에 검색했을 때 관련된 과거의 스크린샷을 보여주면 유저가 찾아보기로 한 키워드와 연관된, 유저의 주목을 받기에 유리한 검색 결과가 될 수 있다.
        
        유저의 주목을 많이 받은 스크린샷은 다음 액션으로 넘어가도록 유도하기 쉽다.
        

---

## Suggestion and reasoning 1

“저장한 모바일 화면의 우연한 발견” as a single-featured MVP to prove the PMF of “스크린샷을 통해 하려고 했던 액션으로 바로 연결해주는 솔루션”

---

## Suggestion and reasoning 2

### [가치 제안](%E1%84%89%E1%85%B3%E1%84%90%E1%85%A1%E1%84%90%E1%85%B3%E1%84%8B%E1%85%A5%E1%86%B8%20%E1%84%89%E1%85%A5%E1%86%BC%E1%84%80%E1%85%A9%E1%86%BC%20%E1%84%87%E1%85%B5%E1%86%AF%E1%84%83%E1%85%B5%E1%86%BC%E1%84%8B%E1%85%B4%20%E1%84%89%E1%85%B5%E1%84%8C%E1%85%A1%E1%86%A8,%20MVT%2060158e62bc8e4cbcbf2ab37c047926d6.md)

저장한 모바일 화면의 우연한 발견 

- details[아마 이런 식으로 될 듯?]
    - 문제
        
        저장한 걸 또다시 찾기 위해 같은 노력을 들인다.
        
    - 검색
        
        태그를 통한 검색 엔진 내 스크린샷 검색 & 검색의 유연성과 편리성 
        
    - 기술
        
        브라우저 익스텐션을 통해 구글/아마존 창에서 저장한 모바일 화면이 검색되도록
        
    - 진행 단계
        
        → 일단 익스텐션 
        
        (첫 출시한 익스텐션의 반응을 보고 그 다음 행보를 결정한다.)
        
        → 신버전 안드로이드 앱 출시 
        
        → 이외 features 넣기 
        
        → Util tag를 위한 제휴 맺기
        
    - 수익 모델
        
        제휴사가 shotag를 통해 얻은 추가 수익의 일부를 받음
        

### 검증이 필요한 가설들

- 당신이 제시하는 솔루션이 그 문제를 해결해 주는가?
    - 모바일 사파리 및 데스크탑 브라우저에서의 구글/아마존 검색을 통해 저장한 모바일 화면을 우연히 발견함으로써 저장한 걸 또다시 찾기 위해 같은 노력을 들이는 빈도를 유의미하게 줄일 것이다.
- 고객의 필요성 (LMF) & 시장규모 & 수익성
    - 모바일 사파리 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견을 원하는 20대 유저들의 규모가 ___ 이상일 것이다. (___ -> 시장 지배력을 확보하여 수익을 지속적으로 창출하기에 충분할 정도의 수치)
    - 모바일 사파리 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견을 원하는 20대 유저들의 규모의 성장률이 ___ 이상일 것이다. (___ -> 시장 지배력을 확보하여 수익을 지속적으로 창출하기에 충분할 정도의 수치)
    - 모바일 사파리 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견을 원하는 20대 유저들이 retention이 plateau를 형성하고 _____% 이상일 것이다. ( -> PMF를 달성하고 지속적으로 수익을 창출하기에 충분할 정도의 수치)
    - 사파리 모바일 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견을 통한 20대 유저들의 유의미한 전환율 상승 효과가 있을 것이다.
    - 모바일 사파리 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견을 통한 20대 유저들의 유의미한 전환율 상승을 대가로 ___ 이상의 금액을 기꺼이 지불할 만한 온라인 사업자의 규모가 ___ 이상일 것이다. (___ -> 시장 지배력을 확보하여 수익을 지속적으로 창출하기에 충분할 정도의 수치)
    - 모바일 사파리 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견을 통한 20대 유저들의 유의미한 전환율 상승을 대가로 ___ 이상의 금액을 기꺼이 지불할 만한 온라인 사업자의 규모의 성장률이 ___ 이상일 것이다. (___ -> 시장 지배력을 확보하여 수익을 지속적으로 창출하기에 충분할 정도의 수치)
    - 모바일 사파리 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견을 통한 20대 유저들의 유의미한 전환율 상승을 대가로 ___ 이상의 금액을 기꺼이 지불할 만한 온라인 사업자의 retention이 _____***%*** 이상일 것이다***.*** ( -> PMF를 달성하고 지속적으로 수익을 창출하기에 충분할 정도의 수치)
- 기술적 실현성
    - 사파리 모바일 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견은 우리 팀의 역량으로 _____개월 이내에 실현 가능할 것이다. ( -> 우리가 제품 개발에 투자할 수 있는 최대 시간)
    - 사파리 모바일 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견은 우리 팀의 역량으로 적어도 ___개월 동안 지속적으로 동안 유지할 수 있을 것이다. ( -> 시장 지배력을 확보하기까지 필요한 시간)
    - 사파리 모바일 및 데스크탑 브라우저에서의 구글/아마존 검색을 통한 저장한 모바일 화면의 우연한 발견을 통한 20대 유저들의 유의미한 전환율 변동을 측정 가능할 것이다.
    - 개인화를 위해 수집한 유저 데이터를 통해 유저에게 가장 적절한 util tag를 추천할 기술적 기반이 충분할 것이다.
- 마케팅
    - 저장한 화면을 구글/아마존 검색을 통해 모바일 사파리 및 데스크탑 브라우저에서 우연히 발견했을 때의 가치를 _____명의 사람들에게 _____시간과 _____ 비용을 들여 전달하여 우리가 제시하는 솔루션을 끝까지 설치 완료하도록 설득할 수 있을 것이다. ( -> 시장 지배력을 확보하여 수익을 지속적으로 창출하기에 충분할 정도의 명수) (_ -> 우리가 마케팅에 감당할 수 있는 시간과 비용)
    - 저장한 화면을 구글/아마존 검색을 통해 모바일 사파리 및 데스크탑 브라우저에서 우연히 발견했을 때의 가치를 경험한 고객이 다른 고객을 _____시간 안에 _____명 유입시키는 선순환 구조를 만들 수 있을 것이다. ( ____-> 시장 지배력을 확보하여 수익을 지속적으로 창출하기에 충분할 정도의 명수와 시간)
    - 저장한 화면을 구글/아마존 검색을 통해 모바일 사파리 및 데스크탑 브라우저에서 우연히 발견함으로써 전환률이 올라갔을 때의 가치를 명의 사업자들에게 _____시간과 _____비용을 들여 전달하여 우리가 제시하는 솔루션을 끝까지 설치 완료하도록 설득할 수 있을 것이다. ( -> 시장 지배력을 확보하여 수익을 지속적으로 창출하기에 충분할 정도의 명수) ( -> 우리가 마케팅에 감당할 수 있는 시간과 비용)
    - 저장한 화면을 구글/아마존 검색을 통해 모바일 사파리 및 데스크탑 브라우저에서 우연히 발견함으로써 전환률이 올라갔을 때의 가치를 경험한 고객이 다른 고객을 _____시간 안에 _____명 유입시키는 선순환 구조를 만들 수 있을 것이다. ( -> 시장 지배력을 확보하여 수익을 지속적으로 창출하기에 충분할 정도의 명수와 시간)
    - 개인정보에 대한 우려의 경우 [3rd party cookie와 다르다는 점을](%5BMVP%20%E1%84%8B%E1%85%B5%E1%84%92%E1%85%AE%5D%5Bshotag%E1%84%86%E1%85%A1%E1%86%AB%E1%84%8B%E1%85%B4%20%E1%84%8C%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%A2%E1%84%85%E1%85%A7%E1%86%A8%5D%20%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3%E1%86%AB%20%E1%84%89%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%90%E1%85%B3%E1%84%8B%E1%85%B4%20%E1%84%89%E1%85%B3%207f8972898b264eebb265770279b53bc3.md) 참고하여 고객의 걱정을 덜고 계속 사용하도록 설득할 수 있을 것이다.

### 우리의 목표 고객은 어떤 프로필을 가지고 있으며, 어떤 상황에 현재 놓여있는가?

목표 고객은 미국에 거주하며, 20대 스마트폰을 사용하는 safari 유저와 데스크탑 브라우저 유저들이다. 이들의 문제는 저장한 모바일 화면을 기억하지 못하면 같은 화면으로 되돌아가기 위해 같은 노력을 반복해야 한다는 점

### 고객의 진짜 문제는 무엇인가? (5 Whys)

유저가 화면을 저장하는 방식을 제공하는 솔루션을 서로의 다양한 이해관계가 맞물려 있는 주체들이 제공하며, 개인정보에 대한 우려의 문제 때문에 이 모든 방식들이 통합되어 있지 않으며 이로 인해 검색 플랫폼은 유저가 저장한 것을 기억해주지 않는다. 따라서 유저가 화면을 저장한 사실을 떠올리지 못하여 검색 플랫폼에서 저장한 것을 다시 검색하면 다시 같은 노력을 반복해야 한다.

서로의 이해관계가 맞물려 있는 문제의 경우 대부분 웹사이트의 공통적인 목표인 전환률 증가를 중심으로 자발적으로 공동의 목표를 위해 shotag에 협력하도록 할 수 있지 않을까

개인정보에 대한 우려의 경우 [3rd party cookie와 다르다는 점을](%5BMVP%20%E1%84%8B%E1%85%B5%E1%84%92%E1%85%AE%5D%5Bshotag%E1%84%86%E1%85%A1%E1%86%AB%E1%84%8B%E1%85%B4%20%E1%84%8C%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%A2%E1%84%85%E1%85%A7%E1%86%A8%5D%20%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3%E1%86%AB%20%E1%84%89%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%90%E1%85%B3%E1%84%8B%E1%85%B4%20%E1%84%89%E1%85%B3%207f8972898b264eebb265770279b53bc3.md) 참고할 수 있지 않을까

### 해당 문제는 매월 혹은 매분기, 매년 얼마나 반복적으로 일어나는가?

해당 문제는 거의 유저들이 인지하지 못하는 상황에서 검색 니즈의 대상이 일정한 유저일수록 반복적으로 일어난다.

- [나중에][기능+] Linkshot without 제휴 (만약 [[MVP 이후][shotag만의 잠재력] 모든 사이트의 스크랩 리스트를 하나로 만들기](%5BMVP%20%E1%84%8B%E1%85%B5%E1%84%92%E1%85%AE%5D%5Bshotag%E1%84%86%E1%85%A1%E1%86%AB%E1%84%8B%E1%85%B4%20%E1%84%8C%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%A2%E1%84%85%E1%85%A7%E1%86%A8%5D%20%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3%E1%86%AB%20%E1%84%89%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%90%E1%85%B3%E1%84%8B%E1%85%B4%20%E1%84%89%E1%85%B3%207f8972898b264eebb265770279b53bc3.md) 에 동의한다면..)
    
    
    - [mobile website] 웹페이지의 경우 제휴하지 않아도 [extension](%5Bdelayed%5D%E1%84%87%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%8C%E1%85%A5%20%E1%84%8B%E1%85%B5%E1%86%A8%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A7%E1%86%AB%20abfebf5955e849b59b0dda8ce35a630a.md)으로 Linkshot 가능하게 하기
    - [mobile website] 웹페이지의 경우 별다른 옵션 없이 [extension](%5Bdelayed%5D%E1%84%87%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%8C%E1%85%A5%20%E1%84%8B%E1%85%B5%E1%86%A8%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A7%E1%86%AB%20abfebf5955e849b59b0dda8ce35a630a.md)을 설치했다면 자동으로 샷태그로 로그인하도록 prompt
    
    but note this…
    
    - “instead of using ecommerce sites on their mobile browsers, shoppers are choosing to use retail apps instead. In fact, [85% of consumers](https://clevertap.com/blog/mobile-growth-statistics/) prefer mobile apps to mobile websites. [69.4% of internet users](https://datareportal.com/reports/digital-2021-global-overview-report) report using shopping apps on phones and/or tablets”
        
        [The Future of Mobile Shopping and How to Optimize Your Site](https://www.shopify.com/enterprise/mobile-commerce-future-trends)
        

- 어디 사이트에 반영할까?
    1. 구글
    2. 아마존
        - 우선 let’s focus on e-commerce
            
            
            - *다른 [mobile service category](various%20categories%20of%20mobile%20services%208ef0a7c12dfd4e559a25fb14225114bb.md)보다 mobile 쇼핑이 중요하게 찾아본 이유?
                - digital marketing and e-commerce is a rapidly growing business
                    - “In 2023, eCommerce retail purchases are **[expected to rise](https://www.statista.com/statistics/534123/e-commerce-share-of-retail-sales-worldwide/)**
                     from 14.1% to 22%.”
                        
                        - [Online Shopping Statistics You Need to Know in 2022](https://optinmonster.com/online-shopping-statistics) -
                        
                    - digital marketing growth rate
                        
                        
                        ![        [Digital Advertising - Worldwide](https://www.statista.com/outlook/dmo/digital-advertising/worldwide#ad-spending)](%5Bdelayed%5D%E1%84%87%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%8C%E1%85%A5%20%E1%84%8B%E1%85%B5%E1%86%A8%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A7%E1%86%AB%20abfebf5955e849b59b0dda8ce35a630a/Screenshot_2022-11-17_at_15.31.34.png)
                        
                                [Digital Advertising - Worldwide](https://www.statista.com/outlook/dmo/digital-advertising/worldwide#ad-spending)
                        
                - numerous small businesses are entering online markets
                    - “소자본으로 시작할 수 있는 온라인의 시장 규모가 빠르게 커지고 있고 경쟁자가 없는 매력적인 시장이라는 점”
                        
                         - **[[PRESS] 방향 전환의 기술 '피벗', 채널톡이 탄생하기까지](https://channel.io/ko/blog/josh_bj_interview)** - 
                        
                    - “The ecommerce industry is growing rapidly and new stores are popping up every day. According to etailinsights, as of 2022, there are over **[9.1 million online retailers globally](https://www.etailinsights.com/online-retailer-market-size#breakdown-items)** and 2.5 million in the US alone.”
                        
                         - [23 Ecommerce Statistics To Know in 2022](https://fitsmallbusiness.com/ecommerce-statistics/) -  
                        
                - “A whopping 49% of people exclusively use their phones for shopping.”
                    
                     - [Online Shopping Statistics You Need to Know in 2022](https://optinmonster.com/online-shopping-statistics) -
                    
        - [“63% of consumers search on Amazon.com when looking for products”](https://webhostingprof.com/blog/ux-statistics/)
            
            ![Screenshot 2022-10-28 at 16.48.37.png](%5Bdelayed%5D%E1%84%87%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%8C%E1%85%A5%20%E1%84%8B%E1%85%B5%E1%86%A8%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A7%E1%86%AB%20abfebf5955e849b59b0dda8ce35a630a/Screenshot_2022-10-28_at_16.48.37.png)
            
            [https://www.statista.com/statistics/274708/online-retail-and-auction-ranked-by-worldwide-audiences/#:~:text=Leading retail websites worldwide 2022%2C by traffic&text=Amazon.com had a monthly,million visits on each month](https://www.statista.com/statistics/274708/online-retail-and-auction-ranked-by-worldwide-audiences/#:~:text=Leading%20retail%20websites%20worldwide%202022%2C%20by%20traffic&text=Amazon.com%20had%20a%20monthly,million%20visits%20on%20each%20month)
            
            ![Screenshot 2022-10-28 at 16.50.17.png](%5Bdelayed%5D%E1%84%87%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%8C%E1%85%A5%20%E1%84%8B%E1%85%B5%E1%86%A8%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A7%E1%86%AB%20abfebf5955e849b59b0dda8ce35a630a/Screenshot_2022-10-28_at_16.50.17.png)
            
            ![Screenshot 2022-10-28 at 16.52.15.png](%5Bdelayed%5D%E1%84%87%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%8C%E1%85%A5%20%E1%84%8B%E1%85%B5%E1%86%A8%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A7%E1%86%AB%20abfebf5955e849b59b0dda8ce35a630a/Screenshot_2022-10-28_at_16.52.15.png)
            
            [https://klientboost.com/google/google-shopping-statistics/](https://klientboost.com/google/google-shopping-statistics/)
            

- 굳이 모바일만 할 필요가 있을까?
    - 모바일과 데탑 둘 다 중요하다고 봄
        - 일단 다음 액션으로 넘어간 conversion을 많이 확보하는 것이 필요함
        - conversion rate이 높게 나올수록 업체들과 제휴하는 데에 협상력을 가질 수 있음
            
            
            - **Average conversion rate per device across all eCommerce industries**
                
                
                | Device | Average conversion rate |
                | --- | --- |
                | Desktop | 3,7 % |
                | Mobile | 2,2 % |
                
                [https://contentsquare.com/blog/mobile-vs-desktop/](https://contentsquare.com/blog/mobile-vs-desktop/)
                
            - The m-commerce 'gap’
                
                ![Untitled](Powerful%20UX%20Statistics%20For%20A%20Successful%20Website%20Ap%20416409b05a5a4f61b37f853ab0279799/Untitled.png)
                
                [https://www.smartinsights.com/ecommerce/ecommerce-analytics/ecommerce-conversion-rates/](https://www.smartinsights.com/ecommerce/ecommerce-analytics/ecommerce-conversion-rates/)
                
        
        - online conversion rate을 올리는 서비스에 대한 니즈가 있을까? Yes!
            - statistics show that in-store yield higher sales conversion rates than e-commerce
                - “conversion rates in brick-and-mortar are around [20-40%](https://www.shopify.com/retail/retail-conversion-rate), while online stores yield [3%](https://www.forbes.com/sites/patfitzpatrick/2020/07/23/retail-conversion-rate-secrets-you-never-knew/?sh=134139bdfbaa) on average”
                    
                     - **[In-store Yield Higher Sales Conversion Rates Than E-commerce](https://www.linkedin.com/pulse/in-store-yield-higher-sales-conversion-rates-than-e-commerce-)** - 
                    
                - “[According to Statista, most online retailers have an average conversion rate of only 2-3 percent.](https://www.statista.com/statistics/439576/online-shopper-conversion-rate-worldwide/)”
                    
                    - ****[2022 E-commerce Trends: 4 Ways to Achieve Digital Transformation](https://vimos.io/blog/digital-transformation-of-retail-industry-in-the-pandemic/) -**
                    
                - “Compared with offline sales, the average conversion rate of online stores is only 20% to 30%. The biggest difference is that the website lacks sales staff who can establish contact with customers through face-to-face dialogue”
                    
                    - ****[2022 E-commerce Trends: 4 Ways to Achieve Digital Transformation](https://vimos.io/blog/digital-transformation-of-retail-industry-in-the-pandemic/) -**
                    
            - people invest a lot in online marketing for the sake of higher conversion rates
                - “워크인사이트 서비스 이용사 중에 오프라인 매장처럼 홈페이지에 대한 고객 분석을 해달라고 요청하는 경우가 있었는데 온라인 환경을 분석하다 보니 새로운 기회를 발견하게 됐다. 기업들은 온라인에 투자를 늘리며 신규 고객 유치 에 집중했지만 정작 구매 전환율은 현저히 낮은 수준이었다”
                    
                     - **[[PRESS] 방향 전환의 기술 '피벗', 채널톡이 탄생하기까지](https://channel.io/ko/blog/josh_bj_interview)** - 
                    
        
        - 우리가 conversion rate을 높여줄 수 있을까? Worth trying out!
            - “A wishlist on the company’s webpage encourages the users to re-visit the website where they have saved products. This leads to a higher rate of customer return, which has a positive effect on the conversion rate.”
                
                [- 5 Reasons to Add a Wishlist to Your eCommerce Website -](https://spreecommerce.org/5-reasons-to-add-a-wishlist-to-your-ecommerce-website/)
                
            - “A common behavior amongst most website visitors is that they wish to buy only the products they need urgently rather than looking through all the items available on the website. By adding a wishlist to your online store, you can encourage them to add the products they hope to buy in the near future; hence the chances of converting a customer into a buyer increase.”
                
                [- 5 Reasons to Add a Wishlist to Your eCommerce Website -](https://spreecommerce.org/5-reasons-to-add-a-wishlist-to-your-ecommerce-website/)
                
            - “Wishlists are reminders. Creating a wishlist doesn’t mean that you need to buy things right now. A wishlist could be for the house that you are in the process of buying, or the dog you will adopt in a few months. They act as reminders to purchase things you will need in the future”
                
                - [WISHLISTS](https://www.oberlo.com/ecommerce-wiki/wishlists) -
                
            - indeed somebody has tried this out, allegedly turned out to be successful
                
                “[a wishlist tool has become a go-to tool that increases shopper re-engagement and hence conversions](https://swym.it/help/wishlist-features-and-the-metrics-they-drive/)”
                

- 모바일은 브라우저 익스텐션 안쓰지 않아…?
    
    
    ![[https://www.similarweb.com/browsers/worldwide/mobile-phone/](https://www.similarweb.com/browsers/worldwide/mobile-phone/)](%5Bdelayed%5D%E1%84%87%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%8C%E1%85%A5%20%E1%84%8B%E1%85%B5%E1%86%A8%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A7%E1%86%AB%20abfebf5955e849b59b0dda8ce35a630a/Screenshot_2022-11-14_at_14.30.56.png)
    
    [https://www.similarweb.com/browsers/worldwide/mobile-phone/](https://www.similarweb.com/browsers/worldwide/mobile-phone/)
    
    ![[https://www.similarweb.com/browsers/united-states/mobile-phone/](https://www.similarweb.com/browsers/united-states/mobile-phone/)](%5Bdelayed%5D%E1%84%87%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%8C%E1%85%A5%20%E1%84%8B%E1%85%B5%E1%86%A8%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A7%E1%86%AB%20abfebf5955e849b59b0dda8ce35a630a/Untitled.png)
    
    [https://www.similarweb.com/browsers/united-states/mobile-phone/](https://www.similarweb.com/browsers/united-states/mobile-phone/)
    
    [Google doesn’t provide a way to add Chrome extensions to its mobile browser](https://www.makeuseof.com/chrome-extensions-android-mobile/)
    
    Safari는 mobile 환경에서의 extension 설치/사용 가능
    
    [Samsung도 mobile 환경에서의 extension 설치/사용 가능](https://developer.samsung.com/internet/android/extension-guide.html)
    

- 그렇게 되면 익스텐션을 또 따로 깔게 해야 하지 않아…?
    
    iOS의 경우 하나의 앱이 extension의 역할까지 함께 할 수 있음 ex. [Liner](https://apps.apple.com/kr/app/%EB%9D%BC%EC%9D%B4%EB%84%88-%EA%B2%80%EC%83%89%EB%B6%80%ED%84%B0-%ED%95%98%EC%9D%B4%EB%9D%BC%EC%9D%B4%ED%8C%85%EA%B9%8C%EC%A7%80/id955395198)
    
    MacOS도 마찬가지 ex. [IINA](https://iina.io)
    
    또한 apple 진영은 ****[모든 기기에서 확장 프로그램 공유하기](https://support.apple.com/ko-kr/HT203051)가 가능함**
    
    “한 기기의 확장 프로그램이 다른 기기와도 호환되는 경우 확장 프로그램이 해당 기기의 확장 프로그램 설정에 자동으로 나타납니다. 확장 프로그램을 다운로드하려면 확장 프로그램 옆에 있는 '받기' 버튼 또는 iCloud 아이콘을 클릭합니다. 확장 프로그램을 켜거나 끄면 다른 기기에도 동일한 변경 사항 표시됩니다”
    
    Samsung internet은 extension 따로 일반 앱 따로인 듯 ex. [Liner](https://apps.samsung.com/appquery/appDetail.as?appId=com.getliner.linerforsamsunginternet)
    
    - 익스텐션 혼자서 일반 앱의 기능을 하지 못하는 경우 (=Windows, Android)
        - 데스크탑 환경
            - 어차피 Windows 데스크탑 익스텐션은 따로 깔게 할 수 밖에 없음
        - 모바일 환경
            - 안드로이드 모바일 환경의 경우 삼성 브라우저 익스텐션이 사진보관함을 접근함으로써 해결할 수는 없는가? → [아마 안 될 거 같다…](https://support.google.com/chrome/a/answer/7515036?hl=en)
            - 아마 앱이나 브라우저 내에서 추가 설치 링크로 redirect 될 수도…
            - Liner의 경우 그냥 둘 다 깔아달라고 [갤럭시 스토어 description](https://getliner.com/for-you/community?savedPage=45481940&shareOption=thread)에 써 놓음
        
    - 아마 이렇게 될 듯
        - iOS-MAC 유저
            
            iOS든 MAC이든 safari extension 설치 이후 확장 프로그램 공유하기 설정 강제
            
        - iOS-Windows 유저
            
            iOS Windows 어느 쪽이든 extension 설치 이후 다른 쪽에서도 설치하도록 redirect 강제
            
        - Android-PC 유저
            
            Android PC 어느 쪽이든 extension 설치 이후 다른 쪽에서도 설치하도록 redirect 강제
            
            Android extension 설치 이후 android 어플도 깔도록 redirect 강제
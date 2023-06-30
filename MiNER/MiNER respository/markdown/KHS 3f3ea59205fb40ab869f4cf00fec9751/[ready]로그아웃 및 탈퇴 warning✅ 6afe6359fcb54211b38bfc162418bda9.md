# [ready]로그아웃 및 탈퇴 warning✅

Tags: Suggestion
상태: In progress
작성 일자: 2022년 10월 6일 오후 4:54

## 체크 리스트

짧은 버전의 경우

- [x]  문구 수정 여부

긴 버전의 경우

- [x]  alert 대신에 새로운 페이지

마지막 화면

- [x]  warning 대신에 마지막 설문 페이지

---

## 현황

탈퇴는 백에서 마련되지 않은 기능. API도 없음

로그아웃은 이걸로 확정

<aside>
💡 **Log out of this app?**

Once you log out, it’ll take some time
to bring back your tags.

Cancel | Log out

</aside>

탈퇴 시 설문조사는 맘에 드는 것을 묻는 것으로 확정

1. 경쟁자가 많이 없다보니 맘에 안드는 걸 물어보는 게 의미없을 수 있다.
2. 새로운 시장이다보니 개선할 사항보다 USP를 찾는 게 중요. 맘에 드는 이유를 고르면 USP로 강조하거나 강화할 부분을 명확하게 파악할 수 있음. 물론 우리가 원하는 고객을 대상으로 설문이나 인터뷰를 안한다는 거는 아님
3. 유저가 아닌 사람들을 대상으로 한 서베이 → 일단 유입인 반면, 
    
    샷태그를 쓰는 사람들에게 마음에 드는 걸 물었을 때 → 지속 사용
    
    retention을 높이기 위해 강조할 feature가 무엇인지 물어보기에 가장 자연스러운 창구
    
4. 탈퇴하는 유저들에게 받을 속성은 버그 리포트나 스토어 리뷰를 통해 많이 보완할 수 있음

반면 내가 마음에 안 드는 이유를 알고 싶었던 이유

1. 마음에 안 드는 이유를 고르게 하면 개선할 부분이 명확

---

## 버튼 이름을 어떻게 할까?

[https://www.figma.com/file/1JkUQCo3optXr9i6nHFaAi/shotag-Design-System?node-id=841%3A16930](https://www.figma.com/file/1JkUQCo3optXr9i6nHFaAi/shotag-Design-System?node-id=841%3A16930)

Log out | Delete account로 하는 건 어떨까?

우리 앱에서 로그아웃과 탈퇴를 붙여놓는다를 전제로 할 때, 

영미권 앱의 경우 죄다 log out과 delete account를 다른 영역에 넣어놓음

그래서 영어버전의 한국앱을 찾아봤는데,,

![Untitled](%5Bready%5D%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%8B%E1%85%A1%E1%84%8B%E1%85%AE%E1%86%BA%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%90%E1%85%A1%E1%86%AF%E1%84%90%E1%85%AC%20warning%E2%9C%85%206afe6359fcb54211b38bfc162418bda9/Untitled.png)

![Untitled](%5Bready%5D%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%8B%E1%85%A1%E1%84%8B%E1%85%AE%E1%86%BA%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%90%E1%85%A1%E1%86%AF%E1%84%90%E1%85%AC%20warning%E2%9C%85%206afe6359fcb54211b38bfc162418bda9/Untitled%201.png)

---

## 다이얼로그

[https://www.figma.com/file/1JkUQCo3optXr9i6nHFaAi/shotag-Design-System?node-id=841%3A16930](https://www.figma.com/file/1JkUQCo3optXr9i6nHFaAi/shotag-Design-System?node-id=841%3A16930)

**Log out of this app?**

When you re-login, it’ll take some time

to bring back your screenshots

*[but, taking [this](https://miner-inc.slack.com/archives/C041EEX0MFH/p1666084952363849) into account]*

**Log out of this app?**

Once you log out, you will lose 

all your tagging information

migrating to a new device?

[info message] 

After moving all your data to the new device,

just log in with the same account and it’ll be fine.

### 짧은 버전

**Cancel account?**

Once you cancel, you will lose 

all your personalized searching experiences

Go back |  Confirm

### 긴 버전

😧 **Whoa, wait a sec**

Once you cancel your account,

you will no longer be able to enjoy our personalized searching experiences, 

including :

- your tags,
- suggested tags,
- shortcuts,
- tag preferences,
- and more

return to Shotag / confirm cancellation

---

## 탈퇴 마지막 화면 survey

😧 **Whoa, wait a sec**

Once you cancel your account, you’ll no longer be able to enjoy our personalized experiences. If you still want to leave, please let us know the reason you are deleting. Every bit of feedback helps!

- I don’t need screenshot searching (검색의 수요 자체)
- It doesn’t understand my tastes (개인화된 추천)
- Not sure how to use this app (직관성)
- It’s hard to search what I want (검색을 잘하지 못해도 원하는 스크린샷이 나오도록)
- I don’t like how it looks(디자인)
    
    design → looks (design이라고 하면 생김새에 UI의 플로우와 로직까지 내포할 수도 있어서)
    
- Awkward expressions([language localization](https://en.wikipedia.org/wiki/Language_localisation))
    
    ![[https://www1.villanova.edu/content/villanova/provost/writingcenter/resources/handouts/_jcr_content/pagecontent/download/file.res/AvoidingAwkwardSentences.pdf](https://www1.villanova.edu/content/villanova/provost/writingcenter/resources/handouts/_jcr_content/pagecontent/download/file.res/AvoidingAwkwardSentences.pdf)](%5Bready%5D%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%8B%E1%85%A1%E1%84%8B%E1%85%AE%E1%86%BA%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%90%E1%85%A1%E1%86%AF%E1%84%90%E1%85%AC%20warning%E2%9C%85%206afe6359fcb54211b38bfc162418bda9/Screenshot_2022-11-02_at_19.06.53.png)
    
    [https://www1.villanova.edu/content/villanova/provost/writingcenter/resources/handouts/_jcr_content/pagecontent/download/file.res/AvoidingAwkwardSentences.pdf](https://www1.villanova.edu/content/villanova/provost/writingcenter/resources/handouts/_jcr_content/pagecontent/download/file.res/AvoidingAwkwardSentences.pdf)
    
- Too slow and laggy (성능)
- Privacy reasons (개인정보)
- I’d rather use another app (경쟁)
- Other (textbox가 열림)

여기에서 other 제외 6개  정도로 추리는 게 좋을 듯합니다.

---

- Delete Account
- Never mind, I won’t delete it.
    
    ![Untitled](%5Bready%5D%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%8B%E1%85%A1%E1%84%8B%E1%85%AE%E1%86%BA%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%90%E1%85%A1%E1%86%AF%E1%84%90%E1%85%AC%20warning%E2%9C%85%206afe6359fcb54211b38bfc162418bda9/Untitled%202.png)
    

---

## References

![Screen Shot 2022-10-19 at 11.59.17.png](%5Bready%5D%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%8B%E1%85%A1%E1%84%8B%E1%85%AE%E1%86%BA%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%90%E1%85%A1%E1%86%AF%E1%84%90%E1%85%AC%20warning%E2%9C%85%206afe6359fcb54211b38bfc162418bda9/Screen_Shot_2022-10-19_at_11.59.17.png)

![Screen Shot 2022-10-19 at 11.59.53.png](%5Bready%5D%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%8B%E1%85%A1%E1%84%8B%E1%85%AE%E1%86%BA%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%90%E1%85%A1%E1%86%AF%E1%84%90%E1%85%AC%20warning%E2%9C%85%206afe6359fcb54211b38bfc162418bda9/Screen_Shot_2022-10-19_at_11.59.53.png)

- 거시적 관점에서 우리 제품의 방향성
    - 개인화와 적극성 ****(적극적으로 유저가 원할 때 스크린샷을 쉽게 발견하고 그 다음 액션으로 이어주는 것 유저 개개인을 위한 맞춤형 서비스를 제공하는 것)
        - 우리의 포지셔닝이니까
- 단기간에 이뤄야 할 KPI
    - 사람들이 검색하는 횟수와 시간 늘리기 (= 참여율)
        - 우리 앱의 [USP](https://www.google.com/search?client=safari&rls=en&q=what+does+usp+stand+for+in+marketing&ie=UTF-8&oe=UTF-8)니까
- 이 영역을 통해 달성하고자 하는 정성적/정량적 목표
    - [rejected]이탈률 줄이기
        - 사람들이 실수로 탈퇴하는 것을 방지하기
        - 사람들이 로그아웃 하기 전에 한 번 더 생각하게 하기
    - 서비스가 앞으로 개선해나갈 방향성을 명확히 판단하기
        - 어떤 유저가 어떤 부분이 불만족스러운지를 알 수 있음
        - 특정 유저 계층을 잡기 위해서는 어느 부분을 개선해야 하는지 알 수 있음
- 이 영역이 사용자에게 줄 수 있는 가치
    - 친근한 이미지를 전달하는 것
        
        
        - 그 가치를 왜 설정했는지
            - 앱 전체적인 텍스트 메시지를 통해 전달하고자 하는 가치임
            - 공적인 이미지보다는 친근함이라는 가치가 개인화라는 방향성과 부합함
                
                [“Use conversational language. One of the biggest turn-offs with messages is that businesses sound like they’re shouting, “BUY NOW!” “OFFER ENDS TODAY!” To appeal to your customers, keep personalized text messages light-hearted, short, and conversational—just like you’re talking to a friend. And yes, you can include emojis to keep the conversation personal and informal”](https://www.podium.com/article/personalized-text-messages/)
                
            - in fact, GPT-3 already thinks so
                
                
                ![Screenshot 2022-11-02 at 15.33.18.png](%E1%84%8C%E1%85%A5%E1%86%AF%E1%84%8C%E1%85%A5%E1%86%AB%20%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3%20%E1%84%89%E1%85%B5%20%E1%84%83%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%A5%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20070bac4cc88d4697846468146459be51/Screenshot_2022-11-02_at_15.33.18.png)
                
                ![Screenshot 2022-11-02 at 15.34.46.png](%E1%84%8C%E1%85%A5%E1%86%AF%E1%84%8C%E1%85%A5%E1%86%AB%20%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3%20%E1%84%89%E1%85%B5%20%E1%84%83%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%A5%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20070bac4cc88d4697846468146459be51/Screenshot_2022-11-02_at_15.34.46.png)
                
                ![Screenshot 2022-11-02 at 15.33.55.png](%E1%84%8C%E1%85%A5%E1%86%AF%E1%84%8C%E1%85%A5%E1%86%AB%20%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3%20%E1%84%89%E1%85%B5%20%E1%84%83%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%A5%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20070bac4cc88d4697846468146459be51/Screenshot_2022-11-02_at_15.33.55.png)
                
                ![Untitled](%E1%84%8C%E1%85%A5%E1%86%AF%E1%84%8C%E1%85%A5%E1%86%AB%20%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3%20%E1%84%89%E1%85%B5%20%E1%84%83%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%A5%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20070bac4cc88d4697846468146459be51/Untitled.png)
                
        - 그 가치를 달성하기 위한 수단이 왜 이것이어야만 하는지
            - [confirmed]**Log out**
                - **Alert**
                    - **경고할 대상이라기보다는 기능의 일부임으로 조심할 부분만 전달**
                    
                    *[but, taking [this](https://miner-inc.slack.com/archives/C041EEX0MFH/p1666084952363849) into account]*
                    
                    - 경고할 대상을 명확하게 전달
                    
                    *[*디바이스를 옮기기 전에 로그인을 해야 한다고 생각을 하는 유저의 경우*]*
                    
                    - 인포 메시지를 통해서 굳이 로그인할 필요가 없음을 명확히 전달
                    - 일괄 데이터 옮기기 기능을 통해서 새 폰에 모든 어플을 새로 깔기 때문에 물론 이런 경우가 많지는 않을 것임. 그러나 데이터를 날리는 만큼 신중한 옵션이므로 하나라도 잘못 판단하는 유저가 있어서는 안됨.
            - **Account deletion**
                - [declined]**Alert**
                    - **개인화된 서비스라는 점을 마지막으로 강조**
                    - **친근한 문구와 이모티콘으로 개인화된 관계를 마지막으로 강조**
                - [confirmed]워딩은 account delete로
                    - **Cancel과 워딩이 겹치면 안 되기 때문에 워딩을 다르게 사용**
                - survey
                    - 구어체에 가까운 표현을 통한 개인화된 메시지
                    - 개인화된 기능을 다시 한 번 강조
                    - 귀찮음을 줄이고 정확한 답변을 얻어내기 위해 하나의 질문으로 구성
                    - [Decision parlaysis](https://www.alchemer.com/resources/blog/survey-questions-how-much-is-too-much/)를 막기 위해 other 제외 6개 이하로 구성을 목표로 삼음
                    - 정확한 답변을 얻어내기 위해 답변하기 싫은 경우 그냥 바로 탈퇴할 수 있도록 버튼을 마련
                    - 어색한 표현이 없도록 맞춤법 검사 돌림
                    - 방향성을 쉽게 정하고자 개선의 방향성이 명확한 선지들로 구성
                        - 유입을 늘리는 데에 쓰기에는 표본이 다르기 때문에 적절하지 않음. 유입보다는 retention을 늘리는 데에 쓰기에 적절함
                            - retention을 관리하는 것은 경쟁자의 수나 유무에 관련없음
                                - 경쟁자의 수나 유무가 아니라 이를 관리하으로써 얼마나 많은 충성고객을 추가적으로 확보할 수 있느냐에 따라 판단해야
                            - [긍정질문]A에 대한 만족이 높다 → A에 대한 니즈가 있으며, A의 완성도에 만족한다.
                                - [action plan]탈퇴하려는 유저들에게 A를 널리널리 알린다. (Δ)
                                    - 유저에게 필요하고 완성도가 있는 A에 대해 지속적으로 상기시킴
                                    - 그러나 유저가 몰라서 탈퇴하는 게 아니라서 의미가 없을 수도
                                - [action plan]사용하고 있는 유저들에게 A를 널리널리 알린다. (X)
                                    - 유저에게 필요하고 완성도가 있는 A에 대해 지속적으로 상기시킴
                                    - 그러나 모집단과 표본이 일치하지 않음
                                - [action plan]예비 유저들에게 A를 널리널리 알린다. (X)
                                    - 유저에게 필요하고 완성도가 있는 A에 대해 알림
                                    - 그러나 모집단과 표본이 일치하지 않음
                                - [action plan]A와 관련된 기능을 더 넣는다 (Δ)
                                    - 탈퇴하려는 유저들의 발길을 붙잡는 기능이 될 수 있다.
                                    - 과연 기능을 더 찾을 수 있을지는 미지수
                            - [부정질문]A에 대한 불만이 높다 → A에 대한 니즈가 있으나, A의 완성도에 불만을 가진다.
                                - [action plan]A의 완성도 개선하면 이탈하려던 사람이 이탈을 안함 (O)
                                    - 추후에 탈퇴하려는 유저의 이탈을 줄일 수 있다.
                        - 표본이 다르더라도 유입을 늘리는 데에 필요한 데이터를 모으는 가장 현실적인 방법이라고 볼 수 없다
                            - 조금 어렵더라도 실제 유저들에게 설문을 뿌리는 방법이 있음
                            - 그게 아니라면 A/B 테스트 가능 (광고, 인앱 메시지, 푸쉬 메시지 등…)
                            - 마찬가지로 버그 리포트나 스토어 리뷰도 통계적으로는 대표성이 떨어짐
                    - 앱의 다양한 측면을 물어볼 수 있도록
                        - USP 그 자체
                            
                            탈퇴율이 높은데 USP 불필요 높음: 니즈가 아예 없음. pivoting 등 전략적 방안을 모색
                            
                            탈퇴율이 높은데 USP 불필요 낮음: 다른 측면을 살펴봐야 함
                            
                            탈퇴율이 낮은데 USP 불필요 높음: USP에 대해서는 현상유지
                            
                            탈퇴율이 낮은데 USP 불필요 낮음: 다른 측면을 살펴봐야 함
                            
                        - [우리의 의도대로 잘 만들어졌는지](%5Bprioritized%5DShotag%20revisited%20ca3f56a683f94f86b2f6668663cf7744.md)
                            
                            탈퇴율이 높은데 포지셔닝 불만이 높은 경우: 포지셔닝에 해당하는 속성 강화 시급
                            
                            탈퇴율이 높은데 포지셔닝 불만이 낮은 경우: 다른 측면을 살펴봐야 함
                            
                            탈퇴율이 낮은데 포지셔닝 불만이 높은 경우: 포지셔닝에 대해 현상유지
                            
                            탈퇴율이 낮은데 포지셔닝 불만이 낮은 경우: 다른 측면을 살펴봐야 함
                            
                        - 이외 앱의 기본적인 완성도를 결정짓는 속성
                            - 디자인 만족도
                            - 성능에 대한 만족도
                            - privacy
                            - language localization
- 가설 검증
    - others의 비중을 보기

---

20221027 회의록

- [(로그아웃 및) 탈퇴](https://www.notion.so/3f7daaad75804de9a3f084a6554c02ba) 확정 사항 - 급하지 않음
    - 페이지
    - 다중 선택 객관식(장점-단점)
    - 옵션
    - 주관식 답변 선택지

20221025 회의록

- [(로그아웃 및) 탈퇴](https://www.notion.so/3f7daaad75804de9a3f084a6554c02ba) survey에서 무엇을 물어볼지 어떤 선택지가 들어갈지는 추후 논의가 필요
    
    현식: 레퍼런스되는 앱을 많이 찾아봤는데,
    둘이 같은 비중으로 있거나 탈퇴 숨겨놓는 경우가 많더라
    
    건표: 근데 문제는 숨길 데가 없음,,, 따라서 숨기지 않는다
    
    현식: 디바이스를 옮기기 전에 로그인을 해야 한다고 생각을 하는 유저의 경우
    
    인포 메시지를 통해서 굳이 로그인할 필요가 없음을 명확히 전달
    
    일괄 데이터 옮기기 기능을 통해서 새 폰에 모든 어플을 새로 깔기 때문에 물론 이런 경우가 많지는 않을 것임. 그러나 데이터를 날리는 만큼 신중한 옵션이므로 하나라도 잘못 판단하는 유저가 있어서는 안됨.
    
    찬희: 기기 바꾸는 경우가 그렇게 많을까?
    
    건표: 필요하지 않을 뿐더러 없어지더라도 이전 디바이스에서 사라지고 자동으로 생성된 태그를 제외하면 모두 서버에 저장됨. 로그인하면 그대로 다시 생길 것임
    
    그럼 이 메시지와 팝업은 넣지 말자
    
    cancel | delete | close
    
    close는 아닌 거 같고
    
    cancel은 alert창들의 cancel과 겹치고
    
    cancel은 또한 구독을 취소하는 듯한 느낌을 줌
    
    탈퇴라는 단어는 delete로 하자
    
    logout 메시지 확정
    
    현식: 짧은 버전의 경우 글이 길지 않아서 로그아웃이랑 차이가 없다
    사실 우리가 생각, 유저에게 인식 심어주기에는 탈퇴가 훨씬 무거움
    뷰적으로 로그아웃과 같지 않게 하는 것이 좋을 듯
    
    희윤: survey 붙잡는 목적인지 진짜 궁금한 건지
    현식: 붙잡기보다는 진짜 데이터가 궁금해서
    
    희윤: 우리 앱에서는 원래 감정적으로 나가는 부분이 없으니까
    그냥 명료하게 알려주고 나가게 하는 게
    또 survey 탈퇴자의 생각보다 지금 쓰는 유저의견이 중요하지 않나
    
    찬희: 탈퇴하는 사람의 생각보다 지금 쓰는 사람이 낫다고 봄
    긴 버전에서 내용을 보여주자
    
    건표: 탈퇴 유저의 survey를 받는 게 유의미할지
    
    현식: 뮤지컬리언즈와 다른 측면, 타겟 명확
    shotag 타겟이라 해 봐야 젊고 이런 세대 안드로이드 유저
    어느 딱 정해진 커뮤니티 타겟이 있다기보다 상황에 따라 변화할 수 있다
    
    건표: survey를 통해 타겟을 찾을 수 있을지?
    
    차라리 survey를 한다면 가장 좋은 feature를 물어보는 게..?
    
    현식: 좋은 feature보다는 나쁜 feature를 찾는 게 …
    
    건표: 나쁜 feature를 묻는 게 방향성을 명확하게 해준다.
    
    건표: 다중 선택으로 가자 (다만 추후 바뀔 수도)
    
    현식: 강제로 대답 받기보다는 optional로 하자 (다만 추후 바뀔수도)
    
    정말 귀찮고 안 하고 싶은 사람에게서 억지로 유의하지도 않은 데이터를 얻어내는 것보다 낫다.
    

20221007 회의록

- 경고창 없이 로그아웃하는 것이 괜찮을까 (현재 작업 중)
로그아웃뿐 아니라 탈퇴 필요, 탈퇴는 무조건 경고 필요
    
    **Log out of this app?**
    You will lose all your personalized data 
    including your tags, suggested tags and shortcuts.
    
    로그아웃이 그냥 진짜 계정만 바뀌는 거고 데이터는 안 없어지는 거구나!
    한 번 백에서 로그아웃이랑 탈퇴를 어떻게 처리하는지를 봐야겠네요!  
    
    스텝적으로 로그아웃이 탈퇴랑 가까우면 경고 다이얼로그 띄워 주고, 탈퇴랑 멀면 경고 로그아웃은 다이얼로그 필요 없다
    
    일단 탈퇴 시에는 무조건 경고 다이얼로그
    

---

**Log out of this app?**

You will lose all your personalized data including your tags, suggested tags and shortcuts.

- 거시적 관점에서 우리 제품의 방향성
    - 개인화와 적극성 ****(적극적으로 유저가 원할 때 스크린샷을 쉽게 발견하고 그 다음 액션으로 이어주는 것 유저 개개인을 위한 맞춤형 서비스를 제공하는 것)
- 단기간에 이뤄야 할 KPI
    - 사람들이 검색하는 횟수와 시간 늘리기 (= 참여율)
- 이 영역을 통해 달성하고자 하는 정성적/정량적 목표
    - 이탈율 줄이기
        - 사람들이 실수로 로그아웃하는 것을 방지하기
        - 사람들이 로그아웃 하기 전에 한 번 더 생각하게 하기
- 이 영역이 사용자에게 줄 수 있는 가치
    - 우리 서비스를 나가기 전에 다시 한 번 생각할 기회를 줌
- “이 화면이 있으면 이탈율이 줄어들 거다”
    - 로그아웃 버튼을 누른 경우 화면을 본 시간과 이탈율의 관계를 보기
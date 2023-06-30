# GPT-4

Created by: 현식 김
Last edited by: 현식 김
Tags: knowledge base
URL: https://jiho-ml.com/gpt-four/
status: completed

### Multi-modal 모델

다중 인풋 모델, 텍스트와 함께 이미지도 Input으로 받을 수 있다.

ex) GPT-4는 Input으로 이미지와 텍스트를 받고, 텍스트를 Output 합니다

how?

이미지의 픽셀을 토큰화 시킴으로써 [트랜스포머](https://jiho-ml.com/weekly-nlp-25/) 모델에 넣을 수 있습니다

![Untitled](GPT-4%20e15349ef3cfa4e2baaa84ae4ef0775b6/Untitled.png)

### 문맥 학습하기

ChatGPT는 3천여개의 단어, GPT-3.5는 8천여개의 단어까지 Input으로 받을 수 있는 반면, GPT-4는 2만5천여개로 늘어났습니다. GPT는 대화 또는 문제에 필요한 Context (맥락)을 파악하기 위해, 과거 대화 히스토리 또는 필요한 정보를 Input 앞에 붙이는 방식([ChatGPT 원리](https://jiho-ml.com/chatgpt-intro) 편 참고)을 사용하고 있는데, 이러한 길이 증가는 성능 향상에 큰 도움이 될 것입니다. 또 Image를 함께 Input으로 사용하기 위해 자연스럽게 Input 길이가 늘어나지 않았을까 싶습니다.

### 강화학습 in GPT-4

Post-training alignment process, 즉 학습 후 교정 과정을 통해 GPT의 가장 큰 한계라고 지적되는 팩트 체크(Factuality), 안정성(Safety)를 강화했습니다. 이를 위해 사용한 방식은 Reinforcement Learning with Human Feedback (RLHF)인데요. ([Week 53](https://jiho-ml.com/weekly-nlp-53/), [ChatGPT 원리 편](https://jiho-ml.com/chatgpt-intro/)). 즉, 추가로 모은 데이터를 가지고 강화학습을 통해 Finetuning하는 방식입니다. 

여기에 GPT-4는 기존에 RLHF에서 추가로 Rule-Based Reward Models (RBRM)이라는 테크닉을 사용합니다. 또다른 GPT-4 모델들에게 Prompt의 안정성을 점수로 평가하게 한 후, 이를 RLHF 학습 때 반영하게 하는 방식입니다.
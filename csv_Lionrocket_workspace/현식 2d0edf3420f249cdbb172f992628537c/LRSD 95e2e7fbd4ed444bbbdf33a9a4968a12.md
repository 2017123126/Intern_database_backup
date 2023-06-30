# LRSD

Created by: 김현식
Last edited by: 현식 김
Tags: knowledge base
URL: https://youtu.be/emObTucGMOA
status: completed

- LRSD (Lion Rocket Stable Diffusion)
    
    Vanilla Stable Diffusion
    

- 자연어 거대 모델과 구분되는 이미지 모델의 특성 : few shot이 안된다. 실제로 만들어 팔기 위해서는 fine-tuning을 통해서 모델 파라미터를 수정을 시켜줘야 됨

- Latent Diffusion Model
    
    ![Untitled](LRSD%2095e2e7fbd4ed444bbbdf33a9a4968a12/Untitled.png)
    
    모델 학습:
    
    - 원본 이미지와 함께 프롬프트를 모델에 입력한다.
    - 원본 이미지에 노이즈를 추가하는 과정을 n step 만큼 진행한다.
    - 노이즈가 추가된 사진에서 프롬프트 문장들에 따라 원본 이미지를 복원하는 과정을 n step 만큼 반복하여 최종 결과와 웝본 이미지의 차이를 줄여나간다.
    
    모델 학습 결과:
    
    - 랜덤 노이즈 이미지로부터 프롬프트 입력에 따라 새로운 이미지를 생성할 수 있다

- [Stable Diffusion](http://103.249.28.4:7860)
    
    Stability AI에서 학습시킨 일종의 Latent Diffusion Model
    
    학습 데이터:
    
    [LAION](https://en.wikipedia.org/wiki/LAION)에서 만든 LAION-5B라는 데이터셋으로 학습
    
    웹에서 크롤링한 50억 쌍의 이미지와 캡션으로 구성
    

- Stable Diffusion 사용 방법
    
    그냥 프롬프트를 입력한다고 바로 뚝딱 나오는 게 아니라 디테일한 문구들을 추가해야 함
    
    - 참고할 사이트
        
        
        [https://lexica.art/](https://lexica.art/)
        
        [https://openart.ai/](https://openart.ai/)
        
        [https://pitch.com/v/DALL-E-prompt-book-v1-tmd33y/6776fb17-9681-49fc-b72e-ca7743d2d0cd](https://pitch.com/v/DALL-E-prompt-book-v1-tmd33y/6776fb17-9681-49fc-b72e-ca7743d2d0cd)
        
        또는 구글에 “prompt guide stable diffusion” 검색
        

- []에 들어가는 문구들은 그 영향이 줄어듦
- ()에 들어가는 문구들은 그 영향이 늘어남

Parameters

- sampling steps: 노이즈를 추가하고 복원하는 과정을 몇 단계 거칠 것인지. 단계가 많이 적게 진행될수록 이미지가 뭉게지는 경향이 있다
- batch size x batch count = 생성된 이미지의 개수
- CFG Scale: 높을수록 prompt를 얼마나 민감하게 반영함
- Restore faces: 얼굴이 이상하게 나오는 경우 보정해주는 기능
- Hires.fix: 512 x 512보다 큰 이미지를 생성할 때의 오류들을 방지해주는 기능
- Seed: 같은 seed값을 입력하면 유사한 이미지를 다시 만들어낼 수 있음

- 불가능한 것들
    - 그래프를 그려주기 (레이아웃 아이디어 정도는 만들어주는 듯)
    - png 이미지를 그려주기
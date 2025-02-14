# 마마고라는 잉글리쉬 튜터링 서비스

**URL**
https://mamago-web.herokuapp.com/

**기술 스펙**
- BackEnd: Ruby On Rails
- Database: PostgreSQL
- FrontEnd: React.js
- Deployment: Heroku

**프로세스**
  1. 마마고가 질문을 합니다.
  2. 질문에 맞는 답을 (영작)을 합니다.
  3. 마마고가 이해한 뜻을 유저에게 확인합니다.
  4. 유저가 Y/N 로 대답을 합니다.
  5.
    1) Y: 이런 뜻은 어때? 하면서 좋은 표현을 제시합니다. (종료 시점 1)
    2) N: 유저의 의도를 한국어로 요청합니다.
  6. 유저가 한국어로 의도를 설명합니다.
  7. 최종 영작을 제시합니다. (종료 시점 2)

**기대효과**
- 사용자는 비대면 학습으로 시간적/공간적 제한에서 벗어나서 영어를 학습 할 수 있습니다.
- 피드백 과정에서 Personalized Data를 쌓음으로써 개인의 학습을 최적화 할 수 있습니다.
- 한국식 영어를 올바른 문장으로 만들어가는 과정에서 한국 사람들이 자주 틀리는 표현과 그에 대한 올바른 영미권 표현을 비교하는 데이터셋을 축적할 수 있다.

**기대했던 최종 목표 및 예상하는 디벨롭 포인트**
- 유저가 사진을 찍어서 보내면, Object Detection 을 이용해서 단어 제공, 단어를 이용해서 영작 요청
- TTS/SST 를 이용해서 음성 지원
- 질문 셋의 다양화 —> 유저의 실력에 따른 단계별 질문
- 유저로부터 영작의 최종 피드백을 받습니다 (up/down)
- 챗봇 빌더
- 한/영 뿐만이 아닌 여러 언어

**MAMAGO 이름의 유래**
  - Papago는 영어 번역과 학습에 필수적인 서비스로 자리잡았습니다.
  - Papa 와 Mama는 아이가 성장하고 걸음마를 배우는데 꼭 필요한 존재입니다. 
  - Re-MadCamp 팀은 영어를 배우는데 가장 좋은 선생님이 될  Mama가 필요하다고 생각을 했습니다. 
  - Papago의 로고가 앵무새이듯이, Mamago의 로고도 동물형 캐릭터를 고민하다가 엄마와 자식을 가장 잘 표현할 수 있을 것 같은 캥거루를 선택했습니다.
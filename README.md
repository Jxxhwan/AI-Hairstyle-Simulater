# 제안 배경 (문제 정의)
- 1. 남녀 불문하고 본인에게 잘 어울리는 헤어스타일은 무엇일까에 대해 잘 알지 못함.
- 2. 요새 유행하는 스타일 혹은 시도해보지 못했던 헤어스타일 -> 쉽게 도전하지 못함. (안 어울릴 수 있기 때문)

# 목표
1. 
  
# 기능 
  1. 얼굴 진단 + 헤어스타일 추천
  2. 헤어스타일 시뮬레이션

# 분석 계획
  0. 도메인 정보를 바탕으로 어떤 얼굴형에 어떤 헤어스타일이 어울리는지 사전 라벨링 작업
  1. Face Landmark 추출 -> 추출된 값들을 바탕으로 사용자의 얼굴 진단
  2. 1의 결과값을 바탕으로 어떤 얼굴형인지에 따라 헤어스타일 추천
  3. 헤어스타일 시뮬레이션
     3.1. Style GAN 이용
     3-2. Style GAN 논문 서치(SOTA) -> 코드 구현 및 모델 학습
     3-3. 파인튜닝 및 최적화 



- 1. 헤어스타일은 그 자체로 멋지거나 이쁜 것이 따로 정해져 있는 것이 아닌, 본인과 가장 잘 어울리는 헤어스타일이 좋은 헤어스타일임.
- 2. 특정 헤어스타일은 얼굴형/윤곽 등에 의해서 얼굴의 장점을 살리고 단점을 가리는 등 다양한 의도로 연출될 수 있다.

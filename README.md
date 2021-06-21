# Augmentation

1. TensorFlow : 7가지 데이터 증강을 시도 후 최종적으로 좌우반전, 상하반전 2가지만 중복 적용
    - flip_left_right : 좌우반전
    - flip_up_down : 상하반전
    - brightness : 밝기
    - contrast : 대조
    - hue : 색조
    - quality : 품질(노이즈 유발) 
    - saturation : 채도
  
2. Elastic Deformation : 시도 후 부적합 판단으로 적용하지 않음


# TCID50 Calculator
   - TCID 50(Tissue Culture Infective Dose 50)을 계산하는 코드 작성
   - TCID 50 이란 대개는 10배수로 희석시킨 바이러스 부유액을 각 배수별로 5개 이상(대개 8-10 test units)의 세포단층, Egg, 동물 등에 접종시켜 50%를 감염시키는 바이러스 희석배수를 titer로 나타낸 것

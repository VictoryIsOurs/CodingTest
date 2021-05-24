# 데이터 마이닝 수업 요약 

*당장 필요하다고 생각되는 정보만 요약했다*

## Lecture 1 - 오리엔테이션

데이터 마이닝 : 대량의 데이터 내에 존재하는 의미있는 패턴 및 정보를 찾기 위한 방법

## Lecture 2 - 생체신호와 신경계의 이해

**생체신호의 종류**

1. 전기적 생체신호
   * EEG(뇌전도), EOG(안전도), ECG(심전도), GSR/EDR(피부전도도), EMG(근전도)
2. 기계/물리적 생체신호
   * BCG(심탄도), Respiration(호흡), Activity(움직임)
3. 광학적 생체신호
   * PPG(광용적맥파)

**생체신호의 활용**

1. Healthcare

   생체신호 분석을 통해 측정자의 상태를 파악하고 가이드할 수 있다.

   ex. 생체신호를 활용하여 사용자의 스트레스 정도를 파악하고 알려줄 수 있다.

2. Human-Computer (Machine) Interface

   신호가 변함을 이용하여 컴퓨터에게 명령을 내릴 수 있다. 

   ex. 눈의 움직임으로 컴퓨터를 움직일 수 있다.

**생체신호의 이해**

1. 전기적 생체신호
   * EXG (Electro X gram)
     * 뇌전도 (electroencephalogram, EEG): 뇌의 전기적 활동
     * 심전도 (electrocardiogram, ECG): 심장의 전기적 활동
     * 근전도 (electromyogram, EMG): 근육의 전기적 활동
     * 안전도 (electrooculogram, EOG): 안구의 전기적 활동
     * 피부전도도 (electrodermal activity, EDA): 피부의 전기적 활동
2. 비전기적 생체신호
   * 심탄도 (ballistocardiogram, BCG): 심장의 기계적 박동을 측정
   * 광용적맥파 (photoplethysmogram, PPG): 혈관에 및을 쏜 뒤, 빛이 흡수/반사되는 정도를 측정한 것
   * 호흡 (respiration): 호흡에 의한 공기의 흐름 or 흉곽의 부피 변화 측정
3. 동잡음 (motion artifact): 움직임이 생체신호 측정에 영향을 미치는 것
   * 예: 머리 움직임, 눈 깜박임
4. 심전도
   * 심전도 파형
     * P, Q, R, S, T waves
     * Duration of each wave
     * Time imtervals of P-R, S-T and Q-T
     * P wave: arterial depolarization
     * QRS complex: ventricular depolarization
     * P-R and S-T intervals are nomally at zero
     * P-R interval: AV node
   * 부정맥
   * 심전도 파형 활용 : 개인에 따라 해부학적 모양과 방향이 다르므로 심장의 전기적 활동을 기록한 심전도의 파형이 개인에 따라 다름
   * 심박수
     * 심박 간격: R 피크 간의 시간 간격
     * 심박수
       * 인간의 중요한 생체정보 중 하나 (Vital signs: 심박수, 호흡수, 혈압, 체온)
       * 보통 분당 심박수로 표현: beats per minute (BPM) = 60/심박간격
       * 평균 심박수: 기준 시간당 평균 심박간격으로 계산 - 60(초) / {0.859 + 0.793 + 0.726) / 3} (초) = 75.69bpm
# [2025.09] Development of Hazard Sound Detection Alert UX Service

> 2025학년도 2학기 AI프로젝트IV 과목에서 수행하는 프로젝트입니다. <br>

본 프로젝트는 이어폰 사용 증가로 인해 보행자가 사이렌, **차량 경적 등 위험 소리를 놓치게 되는 문제를 해결**하기 위해 시작되었습니다. <br>
사용자가 음악을 듣거나 이어폰을 착용한 상황에서도 주변 이상 소리를 감지하여 **빠르고 신뢰성 있는 알림 UX**를 제공하는 시스템을 설계하였습니다. <br>
이 시스템은 실시간 소리를 수집한 후 Mel-Spectrogram 기반 경량 모델을 통해 사이렌·경적 여부를 분류하고, 감지 결과는 배너 알림 형태로 사용자에게 전달됩니다. 이를 통해 **꼭 필요한 경고만 빠르게 알림**으로써, 사용자의 안전을 지키는 것을 목표로 합니다.

---

### [FlowChart] <br>
<img width="100%" alt="Image" src="https://github.com/user-attachments/assets/7626d0c9-5efb-4db4-87e2-c0723b76425b" />

---

### [Model 1️⃣ LightWeighted CNN]
<img width="1131" height="447" alt="Image" src="https://github.com/user-attachments/assets/5523909d-82dd-4719-a323-06fa887dd667" />

### [Model 2️⃣ RCNN]

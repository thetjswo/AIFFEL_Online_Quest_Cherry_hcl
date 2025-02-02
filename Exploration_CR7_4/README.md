# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 홍채림
- 리뷰어 : 최강훈

🔑 **PRT(Peer Review Template)**

- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부
        - ![image](https://github.com/choikanghoon/AIFFEL_Online_Quest_Cherry/assets/149554171/7981a693-0f55-4d65-8d65-e00a4da4a9fb)
        - 예 잘 진행 되었던 것 같습니다.

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인 또는
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
        - 저는 생각하지도 못한 x 와 y np.array부분에서 데이터셋에 맞게 수정한것을 보았습니다. 굿
        - ![image](https://github.com/choikanghoon/AIFFEL_Online_Quest_Cherry/assets/149554171/3adac722-39b3-4afb-a5c2-cc7bad2b0f32)


        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 상세히 기록되어 있는지 확인
        - 딥러닝 모델의 경우,
        인풋이 들어가 최종적으로 아웃풋이 나오기까지의 전체 흐름을 도식화하여 
        모델 아키텍쳐에 대한 이해를 돕고 있는지 확인
          - git 이미지를 2개를 넣으면서 얼마나 에폭을 돌렸는지 알 수 있었습니다.
         
            
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 모듈화(함수화) 했는지
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.

---

리뷰:

![image](https://github.com/choikanghoon/AIFFEL_Online_Quest_Cherry/assets/149554171/3356b416-a273-4570-a984-361a7564fbb4)

시각화를 하기 위해서는 정규화 했던부분을 0 ~ 1 사이 혹은 0. ~ 0.255 사이로 다시 사이즈를 정해주어야 합니다. 하하하하하

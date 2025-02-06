# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김인수
- 리뷰어 : 조현철


# PRT(Peer Review Template)
- [✓ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
![image](https://github.com/user-attachments/assets/947ae996-ce1b-4fa8-83bd-c6f68601623c)

    
- [✓]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
![image](https://github.com/user-attachments/assets/64633810-b85f-449b-8a5f-2151e8bad8f9)

  아웃포커싱을 효과적으로 구현해서 핵심적이라고 생각합니다.
   마스크를 활용하여 인물과 배경을 분리하는 과정이 포함되었고, np.where(), bitwise_and()의 동작 방식이 명확히 기술됨
  
  
        
- [✓ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**


![image](https://github.com/user-attachments/assets/97a56aa2-2b57-4c72-b771-bc37200a26a2)

기존 실험에서 불충분한 결과가 나와서 새로운 강아지 사진으로 추가 실험을 수행

        
- [✓ ]  **4. 회고를 잘 작성했나요?**
 ![image](https://github.com/user-attachments/assets/48e5697a-6997-459c-84a0-03e25f6e12a9)
![image](https://github.com/user-attachments/assets/7d97e628-8b64-49ae-bdee-8ec36a2b07af)


        
- [✓ ]  **5. 코드가 간결하고 효율적인가요?**

![image](https://github.com/user-attachments/assets/1b77ab5b-9b86-4da4-9aea-f523607b2b41)


# 회고(참고 링크 및 코드 개선)
```
semantic segmentation을 활용하여 인물 및 객체의 배경을 분리하고, 아웃포커싱 및 크로마키 배경 교체를 수행,  마스크 생성, bitwise 연산을 통한 배경 제거들을 수행했습니다.
여러가지 사진들을 통해서 기본적인 배경 제거 및 블러 처리는 효과적으로 하셨지만, 경계선 블러 현상 등 약간의 어쩔수없는 세그멘테이션의 기술적인 한계들도 보입니다.
```

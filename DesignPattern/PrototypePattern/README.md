# 프로토타입 패턴 (Prototype Pattern)

## 기능 설명
 프로토타입 패턴은 객체를 생성할 때 비용이 크거나 복잡한 경우, 기존의 객체를 복제하여 새로운 객체를 생성하는 패턴입니다.    
이를 통해 객체 생성 비용을 줄이고 객체 생성 과정을 간소화할 수 있습니다.   
 
 ### 장점
1) 새로운 객체를 생성할 때 원본 객체를 복제하기 때문에 객체 생성 비용이 절약됩니다.   
2) 객체 생성 과정을 단순화하여 코드의 유지 보수성이 향상됩니다.    
  
 ### 단점
1) 프로토타입으로 사용되는 객체가 복잡한 경우, 복제 과정에서 객체의 상태를 정확히 복제하기 어려울 수 있습니다.   
2) 프로토타입 객체의 변경이 모든 복제된 객체에 영향을 미칠 수 있습니다.    

## 느낀 점
 프로토타입 패턴은 객체 생성에 대한 비용을 줄이고, 객체 생성 과정을 간소화하는 데 유용한 디자인 패턴   
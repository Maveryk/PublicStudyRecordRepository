# FSM(Finite State Machine)으로 구현한 몬스터 AI

## 기능 설명
  FSM(Finite State Machine)은 몬스터의 행동을 별개의 상태로 표현해서 각 상태마다 해당하는 동작 및 전환을 통해 모델링을 제어하는 설계 접근 방식이다.
  
 ### 장점
 1. 모듈성(유지 관리성, 코드 가독성 상승): FSM 디자인은 몬스터의 행동을 별개의 상태로 조직화하므로 행동을 추가, 수정 또는 삭제할 때 다른 부분에 영향을 주지 않고 변경할 수 있다.
 2. 명확성: 상태의 전환을 명시적으로 정의하므로 FSM은 몬스터의 행동 논리를 명확하게 시각적으로 나타낼 수 있으므로 개발자 간 협업과 이해 및 디버깅을 용이하게 한다.
 3. 확장성: FSM 접근 방식은 몬스터의 행동에 새로운 상태를 추가하는 것이 쉽고, 이 유연성은 개발 과정에서 진화하는 복잡한 AI 시스템을 설계할 때 유용하다.
 4. 테스트 용이성: 각 상태는 독립적으로 테스트할 수 있으므로 완전한 FSM에 통합하기 전에 개별적인 동작의 정확성을 확인하기가 더욱 간단하다.
 5. 예측 가능한 행동: FSM의 결정론적 특성으로 인해 몬스터의 행동이 예측 가능하며 제어 가능하므로, 이는 일관된 플레이어 경험을 유지하는데 중요한 요소이다.

 ### 단점
 1. 복잡성: 복잡한 AI시스템의 경우 많은 수의 상태와 복잡한 전환 조건으로 인해 FSM을 관리하고 이해하기 어려워질 수 있다.
 2. 상태 전환: 모든 가능한 시나리오를 다루는 정확한 전환 조건을 설계하는 것은 어려울 수 있다. 누락되거나 잘못된 조건은 의도하지 않은 행동을 초래할 수 있다.
 3. 한계된 문맥: FSM은 복잡한 조합 요소나 과거 이벤트의 기억을 필요로 하는 미묘한 행동을 처리하는 데 어려움을 겪을 수 있다. -> 이러한 경우 다른 AI 기술을 사용
 4. 일관성 유지: 서로 다른 상태 간의 일관성을 유지하는 것은 어려울 수 있다. 특히 행동이 겹치는 경우 일관되지 않은 전환으로 인해 몬스터의 행동이 불안정 하거나 현실성이 없는 결과를 초래할 수 있다.
 5. 디버깅: 복잡한 FSM의 디버깅은 여러 상태 및 전환의 상호작용으로 인해 어려울 수 있다. 예상치 못한 행동의 원인을 찾는 것은 시간이 오래 걸릴 수 있다.
 
## 어려움과 해결책
 처음 구조를 설계할때가 제일 큰 벽이지 않았나 생각한다. 평소에 게임을 하면서 봤던 일반 몬스터를 생가하면서 구조를 설계해서 만들었다.
 
## 느낀 점
  FSM의 개념은 학교다닐때 배웠고, 예전 팀 프로젝트에서 FSM을 통해 몬스터를 제작은 해봤지만 팀프로젝트가 해체된 뒤에 다시 개념을 복습하고 다시 기능 구현을 하다보니 각 상태에 대한 동작이나 전환 조건을 고민할때 간단한 기능 구현 단계인데도 이렇게 시간을 많이 사용하는데 실제 개발에서는 얼마나 오래걸리고 얼마나 디테일할지 궁금해진다.
 
## 추가로 개선하고 싶은 부분
 이번에는 몬스터의 AI를 FSM(Finite State Machine)형식으로 구현 해봤는데 추후에는 Behavior Tree로 구현 해보고 싶다.
 추가로 몬스터의 공격 스킬부분을 베이스는 만들어 뒀지만 일반공격만 해놔서 추후에 스킬 공격도 다양하게 구현해보고 싶다.
 
## 유튜브
 [![Video Label](http://img.youtube.com/vi/8353UCighWs/0.jpg)](https://youtu.be/8353UCighWs)   
 [![Video Label](http://img.youtube.com/vi/_KN5zVjUMhM/0.jpg)](https://youtu.be/_KN5zVjUMhM)   
 [![Video Label](http://img.youtube.com/vi/S9z-Pcz26fM/0.jpg)](https://youtu.be/S9z-Pcz26fM)  
 
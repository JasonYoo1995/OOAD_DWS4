- **사용 스택** : Java, Java GUI Library(Swing, AWT)
- **개발 기간** : 2020년 4월 30일 ~ 6월 20일
- **시연 영상** : [https://youtu.be/Ftf_74iP5xw](https://youtu.be/Ftf_74iP5xw)
- **프로젝트 내용 요약**
    - 프로젝트 진행 방식은 Agile 방식으로 진행하되, 총 3개의 Cycle로 진행하였습니다.
    - 검증팀에서 구축해준 CTIP 환경 [ Slack + Jenkins + Redmine + Git + Github + Gradle + Intellij + Java + JUnit + Static Analysis Tool (PMD / Findbugs / CheckStyle) ] 위에서 개발하였습니다.
    - 4명이 각각 모듈을 확실히 구분하여 각자의 Feature Branch에서 개발하고, 기능이 완성될 때마다 Dev Branch로 Merge하였고, Dev Branch에서 오류가 없음이 검증되었을 때 Main Branch로 Merge하였습니다. (Branch 10개, Commit 189회)
    - 7개의 기능(현재 시각 보여주기, 모드 활성화/비활성화, D-DAY, 알람, 세계 시각, 타이머, 스탑워치)을 가진 Digital Watch System를 SW 형태로만 제작하였습니다.
    - 객체 간에 전달하는 Message의 프로토콜을 다함께 설계하고, 이벤트 스케줄러 객체를 두어 이벤트를 처리하는 구조로 구현하였습니다.
- **제작 문서**
    
    [디지털 손목 시계 시뮬레이터 문서](https://www.notion.so/bffb712b86894a5b8173c0bc5019d97a)
    
- **어려웠던 점 / 느낀 점**
    - 설계적인 측면에서 많은 것을 배울 수 있었습니다. 구체적으로 말하자면, Multi-Threading 환경에서 Control Flow와 Data Flow를 고려하여 객체 간의 의존 관계와 통신 방법을 설계해야 함을 느낄 수 있었습니다.
    - 4명이 각각 Branch를 나누어 구현한 뒤, 4개의 Branch를 Main Branch에 한꺼번에 Merge하여 하나로 합쳤을 때, 큰 버그 없이 잘 돌아갔던 것이 놀랍고 짜릿하고 뿌듯했습니다. 이는 구현 전의 설계가 탄탄하게 이루어졌기 때문에 가능했던 일입니다.

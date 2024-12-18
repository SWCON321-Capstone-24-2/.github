# 리스펙존 - 욕설과 혐오 없는 깨끗한 공간
![SwiftUI](https://img.shields.io/badge/SwiftUI-0067B9?style=flat-square&logo=Swift&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring&#160;Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache&#160;Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Python](https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter&#160;Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)  

- 2024-2 Data Analysis Capstone Design | 데이터분석캡스톤디자인 (SWCON321)
- 2024 SW중심대학 연합 SW Festival | Big data & AI 출품작

## 팀원
| [유혜지](https://github.com/HyejiYu) | [김건형](https://github.com/g-hyeong) | [이민재](https://github.com/mini-min) | 
| :--: | :--: | :--: | 
|  Team Leader, Data Engineer | Server Developer | iOS Developer |
| <img width="300" alt="혜지" src="https://github.com/user-attachments/assets/74055c1f-566c-416f-a566-9f79679f49d4"> | <img width="300" alt="건형" src="https://github.com/user-attachments/assets/a8d54a85-2ab7-4b74-a470-c37d8762e918"> | <img width="300" alt="민재" src="https://github.com/user-attachments/assets/7a5d7f57-68d6-4cee-97a8-160d8ddb2371"> | 

<br>

## 1. 프로젝트 배경
> 전 연령층에 걸쳐 나타나는 욕설, 비속어 사용 문제

비속어 사용 문제는 전 연령대에 걸쳐 일상 대화와 온라인 상에서 늘어나고 있으며, 이는 부적절한 사용이나 관계를 악화시키는 경우도 많아 사회적 문제로 자리잡고 있다. 
이에 국립국어원은 “온라인 소통이 일상화된 상황에서 욕설과 비속어가 쉽게 전파되고, 일상적으로 이런 말들을 접하게 되면서 문제의식 없이 습관적으로 욕설과 비속어를 사용하는 사람이 늘고 있는 것으로 분석된다”고 설명한다.

> 이런 사

<br>

## 2. 아이디어 정의
> 일상 속에서 자신도 모르게 사용하는 “잘못된 언어 사용 습관”을 알려주고, 이를 개선할 수 있도록 유도해주자!
- 우리가 이 아이디어에서 주목하는 것은 자기 스스로가 인지하지 못하고 사용하는 잘못된 언어 사용 습관
- 자신이 잘못된 언어를 사용했음을 인지하고 있지 못한 상황 → 당신이 ~이런이런 잘못된 언어를 사용했고 / ~이런이런 잘못된 언어를 많이 사용하는 편이며 / 이를 이런이런 식으로 개선하는 것은 어떨지 알려주면 → 스스로의 잘못된 언어 사용을 인지시킬 수 있고 + 이후의 언어 사용에 있어 주의할 수 있는 동기를 제공해줄 수 있을 것임.
  
> “바른 언어 사용”이 필요한 공간에 인공지능 스피커를 둠으로써 해당 공간에 대한 “클린 언어 존”이 형성되도록 한다!
1. 회의실 - 비속어는 물론, 상대방의 의견을 존중할 필요가 있는 공간 / 혹은 “굳이라는 말 사용하지 않기”, “무작정 안된다고 말하지 않기”와 같이 로컬룰을 만들어 지키고자 노력하는 경우도 있음
2. 학교/교실 - (수업시간 내외) 욕설을 사용하는 경우, 벌점을 부과하거나 - 선생님의 지도를 받는 경우 다수. 특히, 청소년들의 잘못된 언어 사용 습관은 큰 사회 문제가 되고 있음
3. 아이를 키우고 있는 집 - “부모님은 아이의 거울이다”라는 말이 있는 것처럼 부모님의 잘못된 언어 습관을 어린 아이들이 보고 배워 따라하는 경우가 많음. 평소 집에서부터 부모님이 잘못된 언어 사용에 대한 주의를 높일 수 있을 것임.
4. 카페 - 주문 시 알바생에게 폭언, 욕설을 가하는 경우에 대해 알바생은 즉각 대처할 수 없다는 문제가 존재. 텔리마케터에게 폭연/욕설을 가하는 경우를 대비해 녹음이 되고 있다는 것을 인지시켜주는 것처럼 + 해당 오프라인 경우에 대해서도 손님이 언어 사용을 주의해서 사용할 수 있도록 만드는 효과가 있을 것이라 봄.

<br>

## 3. 아키텍처
![Frame 5](https://github.com/user-attachments/assets/674f1e84-93b6-4927-91e5-b9980373d2e5)

- `Speaker - Application` : 
- 
<br>

## 4. 시연 설명
### 4-1. 화면 구성
| Main Scene | Recording Scene (Clean) | Recording Scene (Detect) | Detail Scene |
| :--: | :--: | :--: | :--: | 
| <img width="300" alt="혜지" src="https://github.com/user-attachments/assets/74055c1f-566c-416f-a566-9f79679f49d4"> | <img width="300" alt="건형" src="https://github.com/user-attachments/assets/a8d54a85-2ab7-4b74-a470-c37d8762e918"> | <img width="300" alt="민재" src="https://github.com/user-attachments/assets/7a5d7f57-68d6-4cee-97a8-160d8ddb2371"> | 
|  Team Leader, Data Engineer | Server Developer | iOS Developer |

### 4-2. 나쁜 말 횟수에 따른 피드백 변화

<br>

## 5. 기대 효과 및 개선 방향


# 🫅 개발자 최민석을 소개합니다.

안녕하세요? 저는 올해로 10년차가 되는 서비스 개발자입니다. 중학생 때 우연히 코딩을 접하게 되었고, 강한 흥미를 느껴 컴퓨터 공학과에 진학했습니다.
전공 공부를 하는것은 재밌었고 적성에도 잘 맞았지만, 어떤 S/W 개발자로 나아갈지에 방향성을 찾지 못하고 있었습니다.

그러다가, 우연한 기회로 한 회사에서 진행한 서비스 개발 캠프에 참여하게되었습니다.
며칠 밤낮을 새며 동료와 서비스를 만들어가면서 힘들기는 커녕 너무 재밌고 즐겁다는 생각이 들었습니다.
그렇게 내가 만든 서비스를 누군가가 사용하면서 만족감을 느끼는 것에 큰 보람을 느꼈습니다.

이에 서비스 개발자로의 커리어를 쌓아나가겠다고 다짐하였고, 지금은 삼성전자 무선(MX)사업부 서비스 개발팀에서 Staff Engineer로 일하고 있습니다.
대표적으로 참여한 프로젝트로는 삼성헬스가 있습니다. 건강이라는 도메인으로 사용자들에게 큰 가치를 전달한다는 것은, 제가 서비스 개발자로 하여금 큰 자부심을 느끼게 합니다.

앞으로도 다양한 도메인에서 세상을 변화시키는 좋은 서비스를 개발하고 싶습니다.

# 🏫 학력 및 경력
- 한양대학교 컴퓨터공학과 학사 졸업 ('16)
- 대한민국 육군 S/W개발병과 전역 ('14)
- 삼성전자 무선사업부 인턴 ('15)
- S/W Maestro 6기 ('15)
- 삼성전자 무선사업부 재직 ('16~)

<div style="page-break-after: always;"></div>

# 🛠️ 보유 기술
#### # Kotlin
Kotlin을 사용한 코드를 대부분 이해하고, 작성하는 것에 어려움이 없습니다.
Coroutine과 Flow를 사용한 비동기식 프로그래밍 방식에 매우 익숙합니다.
Kotest와 Kmock 등 Test용 라이브러리 사용에도 익숙합니다.

#### # Android Framework
대학생 때부터 Android Framework를 사용하여 프로젝트를 진행하며 대해 전반적으로 이해도가 높습니다.
모바일 환경에서 프로젝트 작업에 매우 익숙하며, Jetpack, Hilt 등 필수적인 라이브러리에 대한 사용 경험이 많습니다.
앱을 제작하여 마켓 릴리즈까지 프로덕트의 전 과정을 경험해보았습니다.

#### # Java, Python, JS
Java 및 스크립트 언어인 Python과 JS도 코딩이 원활한 수준으로 사용 가능합니다.
Django, mongo DB, JUnit 등등 해당 언어를 사용한 라이브러리 사용 경험도 많습니다.

#### # Architecture
모듈화된 프로그래밍에 관심이 많고, 실제 설계 경험이 있습니다.
MVC-MVP-MVVM-Clean Architecture로 이어지는 설계 및 리팩토링 경험이 있습니다.
SOLID 원칙을 준수하는 Clean한 프로젝트 구조 구축이 가능합니다.

#### # Technical Lead
삼성헬스 및 삼성피트니스 과제에서 4개 모듈에 대한 2번의 TL 경험이 있습니다.
소규모(2~4명)의 팀을 리드하여 결과물을 산출하는 역할을 수행가능합니다.


<div style="page-break-after: always;"></div>

# 💡 프로젝트
## 🏃 삼성 피트니스
> 책임 : Technical Lead 및 S/W Architect
> 
> 기간 : '25

On-device AI를 이용한 피트니스 서비스 과제입니다. 카메라를 통해 입력받은 스켈레톤 정보와, IMU 센서 데이터 등을 사용하여 사용자의 현재 자세를 분석하는 모델을 경량화하여 모바일기기에서 사용자의 운동정보를 분석합니다.

제가 맡은 역할은 자율운동 인식에 관한 부분으로, 워치에서 측정된 IMU 데이터를 이용해서 80여종의 웨이트 트레이닝 동작을 인식하는 서비스를 개발하였습니다.

추가로, 앱의 모듈화 및 워치 통신, 데이터 스키마 설계 등 전체적인 서비스 개발 설계도 담당하였습니다.

> ##### # 챌린지 1 : 모듈화
> 최근 서비스들이 다양한 플랫폼에서 지원되는 경우가 많아지고, 모듈화 프로그래밍에 대한 관심과 니즈가 높아졌습니다. 프로젝트 초기 설계 단계에서 모듈화가 용이하도록 프로젝트를 설계하여야 하는 챌린지가 있었습니다.
>
> 실제로 본 프로젝트에서는 공용 알고리즘을 워치와 모바일, 서버에서 사용하기 때문에 프로젝트를 모듈화 하는 것이 개발 효율에 큰 영향을 미쳤습니다.
> 
> Clean Architecture를 기반으로 프로젝트를 모듈화하고 모듈 간의 의존관계를 직접 설계하고 적용하는 경험을 쌓을 수 있었습니다.
>
> ##### # 챌린지 2 : 데이터 스키마 설계
> 200여 종의 다양한 운동에 대한 정보와, 사용자가 운동을 수행할 때 마다 생기는 2~3K의 심박수 데이터 및 IMU 데이터를 저장할 스키마 설계를 주도적으로 진행하여야 했습니다.
> 
> 데이터 스키마 업데이트가 자주 있는 것은 개발비용을 높이는 요소가 되므로, 개발 비용이 최소화 되도록 스테이크 홀더와 충분한 요구사항에 대한 논의를 통해 가능한 한 유연한 데이터 스키마를 설계하는 경험을 했습니다.
>
> ##### # 챌린지 3 : 데이터 동기화
> 워치와 모바일 간의 대역폭은 한정적이기 때문에 대용량의 센서 데이터를 매번 동기화 하는 것은 자칫 배터리와 메모리 문제로 이어질 가능성이 컸습니다.
> 
> 이러한 문제를 해결하기 위해 사용자에게 보여지는 시점에서의 최소 데이터(100kb 이하)를 정의하고, 이후 백그라운드를 통해 대용량의 데이터를 동기화하는 통신 프로토콜을 설계하는 경험을 하였습니다.
> 
> 또, 이 데이터를 주기적으로 서버로 동기화하여 모든 기기에서 사용자가 동기화되는 경험을 제공할 수 있는 방법에 대해 고민하고 적용해보는 경험을 쌓았습니다.
>
> ##### # 챌린지 4 : On device AI
> 이전에 도전해보지 않은 새로운 분야로의 도전이었습니다. 현업에서 사용되는 AI는 대부분 연구보다는 경험과 실험을 통해 사용성을 확보하는 것에 초점이 맞추어져 있었습니다.
>
> 본 과제에서는 동작 인식을 위하여 Movenet, MLKit Pose Detector 모델을 사용하였고, 모바일에서 실행이 가능한 수준으로 경량화하는 작업들을 진행하며 한정된 리소스를 사용하여 AI 모델을 수행하는 경험을 쌓았습니다.

<div style="page-break-after: always;"></div>

# 💡 프로젝트
## 💓 센서 트래킹 서비스 - 삼성헬스
> 책임 : Technical Lead
> 
> 기간 : '22~'24

다양한 기기를 통해 수집된 사용자의 심박, 스트레스, 혈중 산소포화도 등 생체 센서를 통해 수집되는 데이터를 가공하여 건강정보를 제공하는 서비스를 리드하여 개발하였습니다.
가장 주요한 기능은 수집된 센서 데이터를 사용자의 기호에 맞게 가공하여 제공하는 것 입니다.

추가적으로, 
- 모바일을 통한 웨어러블 기기 제어 기능
- 스트레스 완화를 위한 호흡 운동 기능
- 다양한 기기로 부터 측정된 데이터 통합 기능

등을 리드하여 설계 및 개발하였습니다.

![image](https://github.com/user-attachments/assets/23ceb318-40a2-43dc-94bb-63aedaf6a957)

> ##### # 챌린지 1 : 대규모 리팩토링
> 제가 이 프로젝트에 투입된 가장 큰 목적은 리팩토링이었습니다. 중요도가 큰 모듈임에도 불구하고, 오랜 기간 방치된 코드들로 인하여 대부분이 작자 미상의 Legacy Code이고, 기술 부채가 상당하였습니다.
>
> 이를 MVVM 아키텍처로 리팩토링하고, 기존 기능을 전부 이전하였습니다.
>
> 리팩토링 결과 전체적인 코드 라인수는 20% 감소하고, 가장 중요한 Error Rate이 1/3 수준으로 감소하였습니다.
>
> ##### # 챌린지 2 : 데이터 제공자
> 센서를 통해 수집되는 심박 데이터는 운동, 수면, 일상 활동 등 10여개 모듈에 제공되어 사용되는 데이터 입니다. 이 데이터를 수면, 운동, 에너지 점수 등등 다양한 모듈에 필요한 곳에 적합하게 가공하여 제공하는 Data Provider를 설계 및 개발하였습니다.
>
> 대규모 프로젝트에서 가장 핵심이 되는 데이터의 공유 측면에서, 다른 개발자가 필요하면 언제든지 쉽게 사용할 수 있는 형태의 데이터 제공 API를 설계하였습니다.
> 
> ##### # 챌린지 3: 대용량 데이터
> 다른 헬스케어 데이터에 비해 웨어러블을 착용하기만 해도 실시간으로 계속 축적되는 심박데이터는 심하면 월 800K 이상이 축적되어 그 용량이 매우 큽니다.
>
> 이러한 대용량의 데이터를 효과적으로 저장하고, 빠르게 UI까지 렌더링해야하는 비기술적 요구사항(NFR)이 있었습니다.
> 
> 특히 워치, 링, 이어버즈 등 웨어러블 기기가 다양화 되면서 훨씬 더 많은 데이터들이 유입되었고, 그 데이터들을 사용자에게 가장 정확하게 통합하여 보여주어야 하는 챌린지가 있었습니다.
>
> 통합 알고리즘 개발 및 데이터 로드/캐싱 로직 개선을 통해 ANR 문제를 해결하고, UI 로딩 속도를 20%이상 개선하였습니다.

<div style="page-break-after: always;"></div>

# 💡 프로젝트
## 🤝 Quality Process
> 책임 : Technical Lead
> 
> 기간 : '22~'23

개발과 병행하며 진행한 업무 프로세스 개선 과제였습니다. 제가 일했던 부서는 해외연구소와 다양하게 협업을 진행하고 있었습니다. 다만, 협업과정이 매우 어려웠습니다.
이러한 문제를 해결하기 위해 2년간 꾸준한 해외 출장과 현지 협업을 통하여 서로의 눈높이를 맞추는 업무를 진행하였습니다.
결과적으로, 업무 메뉴얼을 통해 업무가 일원화된 방식으로 진행될 수 있도록 하여, 전 부서원의 업무 프로세스를 개선한 경험이 있습니다.

> ##### # 챌린지 1 : 의사 소통
> 해외 연구소와는 언어라는 장벽이 항상 존재했습니다. 이는 단순한 언어로써의 문제가 아니라 문화의 차이이기도 했습니다.
> 
> 대한민국의 "네" 와 영어의 "Yes" 는 같은 뜻이지만 그 의미가 모호하게 달랐습니다.
> 
> 따라서 협업 시에는 모든 문서를 모호하지 않도록 적는 것이 굉장히 중요하였고, 이를 체크리스트화 하여 관리 되도록 그라운드룰을 만들어 보는 경험을 하였습니다.
>
> ##### # 챌린지 2: 코드 리뷰
> 리뷰어의 의도를 모두 리뷰 코멘트로 작성하는 것은 굉장히 어려운 일이었습니다.
> 
> 잘 작성된 리뷰 코멘트는 정말 큰 도움이 되지만, 그렇게 작성하는 데에 들어가는 시간도 만만치 않았습니다.
> 
> 최대한 잘 만들어진 코드 스니펫과 레퍼런스, 깃허브의 기능들을 활용하여 좋은 리뷰 문화를 만들어가는 경험을 하였습니다.

<div style="page-break-after: always;"></div>

# 💡 프로젝트
## 💤 수면 트래킹 서비스 - 삼성헬스
> 책임 : Android 개발
> 
> 기간 : '20~'21

사용자의 수면을 기록하고 분석하는 기능입니다. 사용자의 수면 중에 측정된 센서데이터를 통하여 전체적인 수면의 질을 평가하는 수면 점수를 개발하였습니다.

또한, 사용자들이 느끼는 수면 측정의 정확도를 높이기 위해 여러가지 알고리즘을 개발하는 업무를 담당하였습니다.

업무를 진행하며 수면 시간 측정 알고리즘에 대한 특허를 1건 출원하였습니다.

![image](https://github.com/user-attachments/assets/b25f6299-3dd1-4e05-941a-24ad535199ca)


> ##### # 챌린지 1 : 수면 시간
> 사용자의 수면 시간이라는 도메인 특성이 가장 문제였습니다. 가장 단순하게, 어젯 밤부터 오늘 아침까지 잔 수면은 "어제"의 수면이라고 하는것이 옳은지, "오늘"의 수면이라고 하는 것이 옳은지 부터 의견이 분분했습니다.
>
> 정답이 정해지지 않은 상황에서, 모두의 의견을 모으기 위해 개발자가 할 수 있는 가장 좋은 접근 방식은 빠른 구현을 통한 POC였습니다.
>
> 빠른 POC로 유관 부서의 의견을 취합하여 적용하는 방식으로 어려운 문제들을 해결해 나간 경험이 있습니다.
>
> ##### # 챌린지 2 : 정확도 개선
> 인간의 수면을 정확하게 트래킹 하는 것은 굉장히 어려운 일이었습니다. 
>
> 이에 여러가지 아이디어를 제안하였고, 사용자의 휴대전화 사용 패턴을 이용한 수면 시간 예측 알고리즘으로 특허를 출원하였습니다.

<div style="page-break-after: always;"></div>

# 💡 프로젝트
## 🎥 가짜 영상 판별기
> 책임 : Backend 개발
> 
> 기간 : '19

사내 벤처 프로그램으로, 1년간 참여한 프로젝트입니다. 딥페이크로 조작된 가짜 영상을 학습하여 조작된 영상을 검출해내는 프로젝트였습니다. 제가 주로 담당한 부분은 영상 수집 및 서비스 서버입니다. 

다양한 영상을 확보하기 위해 Youtube를 크롤링하여 영상 데이터를 수집하는 서버 및 요청이 온 결과 비디오를 학습시킨 모델을 통해 수행한 결과를 반환하는 서버를 구축하였습니다.

프로젝트 진행 중, 인프라 구성에 대한 챌린지가 있었습니다. 학습용 서버는 고성능의 컴퓨팅과 GPU가 필요하였고, API서버나, 학습용 데이터 수집은 비교적 낮은 사양이어도 대용량의 스토리지를 필요로 했습니다.

각 서버 특징에 맞는 인스턴스로 백엔드 인프라를 직접 구성하는 경험을 쌓을 수 있었습니다.

## 🏢 기업 건강 서비스 - Veo Sens
> 책임 : Android 개발 및 Frontend 개발
> 
> 기간 : '17~'18

임직원들의 건강 정보를 관리하는 시스템을 구축하는 프로젝였습니다. 임직원의 건강을 관리하여 건강 관련 비용을 절감하는 기업용 솔루션입니다.

사내 5000여명 임직원 대상으로 POC를 완료하였습니다.

주로 개발한 부분은 사용자 가입 페이지와 심박수 트래킹 기능입니다.

## ⛓️ 웨어러블 프레임워크 - 삼성헬스
> 책임 : Android 개발
> 
> 기간 : '16

다양한 웨어러블 기기 모바일 간 데이터를 동기화하는 프레임워크를 개발하였습니다.

주로 담당한 부분은, 웨어러블에서 생성된 데이터를 동기화가 필요한 지 판단하여 병합하는 알고리즘이었습니다.

<div style="page-break-after: always;"></div>

# 💪 강점
## 🌏 글로벌 서비스 개발 경험
삼성헬스는 200여개 국가를 지원하고, MAU 6400만 명의 많은 사용자를 가진 서비스입니다. 이러한 대규모 서비스를 실제로 개발하고 운영해본 것은 저에게 큰 경험이 되었습니다.

모든 국가에 동일한 서비스가 지원될 수 있도록, RTL, 다국어, 표준 시간대 등등 글로벌 서비스에 관련된 경험을 많이 쌓았습니다.

전 세계의 사용자가 서비스를 이용하며 남긴 수많은 피드백들과, 해외 출장을 통한 현지 개발 협업을 통해 글로벌한 무대에서 다양한 사람들과 서비스를 개발해 본 것이 저의 큰 강점입니다.

## 🧑‍🤝‍🧑 커뮤니케이션 스킬
개발자 의사소통의 90%는 "설명하기" 라고 생각합니다. 많은 개발자들이 의사소통에 어려움을 느끼는 이유는 배경지식(Context)의 부재라고 생각합니다.

너무 당연하게도, 대부분의 사람들의 프로젝트 이해도는 개발자 본인보다 떨어지는 상황이 많습니다. 개발자는 효율적인 의사소통을 하기 전에 중요한 내용을 잘 설명하고 이해시키는 것이 정말 중요하다고 생각합니다.

다른 배경지식을 가진 사람에게 개발적인 내용을 잘 설명하고, 동료 개발자에게는 기술적인 내용을 잘 전달하는 것이 개발자 의사소통의 핵심이라는 것을 느꼈습니다.

많은 이해 관계자들과의 의사소통을 바탕으로, 핵심을 잘 전달하고 상대에게 신뢰감을 주는 의사소통 능력이 제 장점이라고 생각합니다.

## 🧽 실행력
많은 프로젝트를 진행하면서 느끼는 것은, 때로는 고민보다는 한줄의 코드로 부딪혀 보는 것이 나았다는 것입니다.

프로젝트가 진행되며 생기는 수많은 변수들을 모두 예측하여 계획대로 업무를 진행하는 것은 현실적으로 어려웠고, 항상 상황에 맞추어 유연한 대처가 필요했습니다.

백문이 불여일견 이라는 말이 있듯이, 개발자는 백문이 불여일런("Run") 이라고 생각합니다. 정답이 아닐지라도, 빠르게 결과물을 만들어가는 것이 저의 강점입니다.

<div style="page-break-after: always;"></div>

# 💪 강점
## 🫀 건강
모든 일이 그렇지만 정말로 개발은 체력전입니다. 프로젝트가 진행되는 순간에 가장 중요한 건강이 무너져 버리는 동료 개발자들을 많이 보았습니다.

취미로 테니스와 필라테스를 하고 있고, 꾸준히 식단을 유지하는 건강한 삶을 살고 있습니다.

항상 좋은 컨디션을 유지하는 것은 제 업무 뿐만 아니라 팀의 분위기에도 긍정적인 영향을 미칩니다. 바쁜 일상 중에도 좋은 컨디션을 유지하는 것이 제 강점입니다.

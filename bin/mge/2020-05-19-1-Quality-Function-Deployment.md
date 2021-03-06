---
title: "[OM 1] Quality Function Deployment"
tags: Management-Engineering OM
toc: true
---

# Intro
Quality function deployment(QFD)란 제품 및 서비스를 디자인 할 때, 정성적인(qualitative) 고객의 요구를 구체적이고 정량적인(quantitative) 수치, 계획 및 방법으로 변환하는 과정 혹은 방법을 의미한다. 

단순히 "고객들은 이런 걸 원한다"와 같은 정보만으로는 설계가 굉장히 막연하다. 이를 잘 사용할 수 있는 형태로 변환하는 게 QFD라 할 수 있겠다.


# Concepts
## Productivity
Productivity는 자원(resource)의 효율적인 사용 정도를 의미한다. 보통은 자원(input)에 대한 산출물(output)의 비로 나타내는 게 일반적이다. 또, 이는 특정 자원에 대해서만 주목할 수도 있고, 전체 자원에 대해 주목할 수도 있다. 예를 들어, 제품 A를 생산하는 데 사용된 가격에 주목할 수도, 에너지 사용량에 주목할 수도 있다.

## Quality
분명 생산량도 중요한 요소지만, 그 전에 어느 정도의 품질(quality)이 보장되어야 한다. 여기서, quality란 무엇일까?

> “The totality of characteristics of an entity that bears on its abilityto satisfy stated andimplied needs.” (ISO, 1994)

충분히 납득할 수 있는 정의라고 생각된다. 제품 설계 시 퀄리티의 보장이 선행되어야 하기에, 우리는 이를 먼저 살펴볼 것이다.


# Quality Function Deployment
앞서 언급했지만, QFD를 간단히 다시 정의하면 _"Translation of customer requirements"_ 라 할 수 있다. QFD는 정말 다양한 곳에 적용될 수 있는데, 일반적인 제조업부터 시작해, 서비스, 환경, 소프트웨어, 군사 등, 매우 보편적인 범위의 기법이다.

QFD는 결과물 자체를 개선시킬 수도, 결과물을 위한 공정(과정)을 개선시킬 수도 있다. 전자의 경우 더 높은 품질의 제품 및 서비스를 제공할 수 있게 되고, 후자의 경우 제품 및 서비스를 생산하기 위한 자원이 효율적으로 운용할 수 있게 한다. 물론 그 외에도 많은 장점이 있을 것이다.

그렇다면, 이제 QFD의 구체적인 방법을 알아보도록 하자.

## House of Quality (HOQ)
HOQ는 QFD에서 고객의 요구와 기술적인 요소들의 상관관계를 시각적으로 판단할 수 있게 해주는 방법이다. HOQ는 다음과 같은 정보들을 담고 있다.

- CA(Customer Attributes): 고객들의 요구 사항을 의미한다. 일반적으로는 정성적인 특성이 강하다. 또, 정성적이지만 각각의 중요성엔 가중치가 적용될 수 있다.
- EC(Engineering Characteristics): 제품 및 서비스에 대한 기술적인 요소를 의미한다. EC들은 그들끼리 어느 정도 관계(relationship)를 가질 수 있다.
- Relation of each EC and CA: 각각의 EC는 CA에게 영향을 끼칠 수 있다. 이들의 관계는 행렬의 형태로 나타내어질 수 있다.
- 기타: 현재/목표 EC 수준, 경쟁사의 CA 만족도 수준 등

![](/imgs/mge/om1.png)

예를 들어, 노트북에서 "오랜 사용 시간"이라는 CA와 관계를 맺는 EC엔 뭐가 있을까? 넓게 보면 배터리 용량, 그래픽 카드의 소비 전력 등이 있을 것이다. 이들은 상대적으로 높은 수준의 관계를 가지는데, 전자의 경우 정방향으로, 후자의 경우 역방향으로 관계를 맺는다. 아마 USB 단자 수와 같은 EC는 별로 관계가 없을 것이다. 이러한 내용을 가운데 행렬에 적용하면 된다.

그리고 각 CA는 가중치가 부여될 수 있다. 다시 노트북으로 예를 들어보자. (일반적으로) 사람들은 음질보다는 빠른 속도나 높은 화질의 디스플레이 등에 더 관심이 있을 것이다. 

또, EC 간의 (정방향이든 역방향이든) 관계가 존재할 수도 있다. 예를 들어, 고성능의 그래픽 카드는 어느 정도의 전력 소모 증가를 야기한다. 

이러한 관계를 종합하면, 어떤 EC가 가장 중요한지 알 수 있게 된다. CA와 관계를 강하게, 그리고 많이 맺는 EC가 중요할 것이고, 이를 개선하는 게 품질 향상에 가장 효과적일 것이다. 예를 들어, (속도, 전력 소모 등 종합적으로 고려한) CPU의 성능이란 EC는 쾌적한 사용 환경, 오랜 사용 시간, 무거운 소프트웨어를 돌릴 수 있는 환경 등 다양한 CA에 영향을 줄 것이다. 하지만 터치 패드 정확성은 상대적으로 덜 중요할 것으로 보인다.

이제 HOQ의 요소 각각이 어떤 정보를 담고 있는지, 또 어떻게 설계해야 할지에 대한 개요가 어느 정도 구상될 것이다.

HOQ는 CA와 EC뿐 아니라, 품질 관리의 많은 요소에 대해 적용할 수 있다. 

![](/imgs/mge/om2.png)

하지만 우린 QFD의 과정과 큰 그림에만 집중할 예정이기 때문에(그리고 내가 첫 번째밖에 안해봐서) CA-EC 간의 HOQ만을 다루었다. 또 너무 지엽적으로 가고 싶지도 않고. 아무튼 HOQ를 짜기 위해선 다음과 같은 생각을 하면 된다.

- 어떤 제품 및 서비스인가?
- CA와 EC는 각각 무엇이 있는가?
- CA는 각각 어느 정도의 중요성을 가지는가?
- 각 EC는 서로 어떤 관계를 가지는가?
- 각 CA와 EC들은 어떤 관계를 가지는가?

HOQ는 상당히 간단하고 효과적이다. 하지만 그 과정에서 몇 가지 어려움이 있을 수 있다. 특히, CA의 qualitative한 성격과, 각 관계의 수준을 결정하는 데 편향이나 주관이 개입될 수 있다는 점, 목표 EC 설정의 어려움 등, 주의 깊게 다루어야 할 사항이 많다. 불확실성(uncertainty)에 기인한 오해와 판단 미스가 QFD를 망칠 수 있다.

HOQ를 직접 짜보고 싶다면 [링크](http://www.qfdonline.com/templates/)에서 무료로 템플릿을 받아 사용할 수 있다. 엑셀로 만들어진 데다가, 필요한 연산이 이미 적용되어 있어 값만 넣으면 멋진 HOQ를 만들 수 있다!







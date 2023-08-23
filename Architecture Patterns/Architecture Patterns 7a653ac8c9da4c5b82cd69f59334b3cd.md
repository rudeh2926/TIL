# Architecture Patterns

---

아키텍쳐 패턴은 소프트웨어 시스템을 위한 구조적 도해 이다

패턴은 서브 시스템과 그들의 역할을 사전 정의해 놓은 하나의 Set이다.

Client-server pattern의 시스템 구조에 의하면 두 개의 서브 시스템이 식별된다.

클라이언트(여러 인스턴스일 수 있음)와 서버(유일함)가 그것들이다.

클라이언트 시스템의 주요 역할은 사용자에게 UI를 보여주는 역할일 수 있으며, 서버의 역할은 여러 질의를 프로세싱하고, 결과를 클라이언트에 제공함에 있을 것이다.

(2) 패턴은 시스템들 사이의 관계를 정리하기 위한 규칙과 지침을 설명한다.

클라이언트와 서버 사이의 관계는 클라이언트가 질문을 하고 이를 서버가 응답한다는 것이다.

패턴은 경험이 많은 사람들에 의해 기록되어진다.

패턴은 이러한 경험한 사람들의 머리에 숨겨지고 남아있을 수 있는 지식을 명세화 하는 것이다.

이러한 명세화는 다른 사람에게 그 경험을 배울 수 있게 한다.

패턴은 한 사람에 의해 구성되지 않고, 많은 개발자들의 경험의 산물인 것이다.

이는 소프트웨어 개발에서 기존의 잘 검증된 솔루션을 선택하고, 좋은 디자인 사례를 전파할 수 있게 한다.

아키텍처 패턴은 스타일, 또는 표준 아키텍처라고 불리지만, 아키텍처 스타일은 패턴보다 덜 정제된 컨셉으로서 사용된다.

여러 패턴은 동일한 아키텍처 스타일에 속할 수 있다.

## 1. 패턴 사용의 효율성

어떠한 문제가 많은 개발자들에 의해 비슷한 방식으로 해결되고, 그 방법이 일반적으로 해당 문제를 해결하는 방식으로 받아들여질 때, 그 방식은 패턴이 되어 진다.

그래서 패턴은 반복 발생하고, 일반적 해결책이 많은 경험자들 사이에서 알려진 설계 문제를 다루고 있어서 패턴에 대한 문서가 있으며, 이는 잘 검증된 설계 문제의 해결책이 되는 것이다.

### (1) 패턴을 기록하여 해결책을 재사용함이 쉬워진다.

패턴은 일반적인 어휘와 설계 솔루션에 대한 이해를 제공한다.

각 패턴의 이름은 널리 퍼진 디자인 언어의 일부가 되어가고 있다.

패턴은 특별한 문제에 대한 해결책에 대한 기나긴 설명의 필요를 제거한다.

그러므로 패턴은 소프트웨어 아키텍처를 문서화하는 방법이며, 이는 아키텍처의 오리지널 비전이 수정되거나 확장되어질 때 또는 코드 수정 등이 이루어질 때 아키텍처의 운영 관리를 지원하기도 한다.

패턴은 정의된 속성을 가지고 소프트웨어의 구축을 지원한다.

예를 들면, 클라이언트-서버 어플리케이션을 설계할 때, 서버는 클라이언트에게 통신을 요청할 수 있게 하면 안된다.

### 많은 패턴은 명시적으로 소프트웨어 시스템에 대한 비기능적 요건을 다루고 있다.

예를 들면, MVC(Model-View-Controller) pattern은 사용자 인터페이스의 가변성을 지원한다.

이로 인해 패턴은 보다 복잡한 시스템에서 마치 여러 빌딩블럭 같이 보여질 수 있다.

---

[구조적 도해](Architecture%20Patterns%207a653ac8c9da4c5b82cd69f59334b3cd/%E1%84%80%E1%85%AE%E1%84%8C%E1%85%A9%E1%84%8C%E1%85%A5%E1%86%A8%20%E1%84%83%E1%85%A9%E1%84%92%E1%85%A2%20cb28017a9f78407287c87f3e810d123c.md)
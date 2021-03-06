# iOS_advanced_study

powered by [JeaSungLEE/iOSInterviewquestions](https://github.com/JeaSungLEE/iOSInterviewquestions/blob/master/README.md)

## rules
- 일요일 키워드 각각 3개 선택
- 화, 목, 일 오전 9시 회의 때 발표, 상대방이 완전히 이해할 수 있을 때까지, 만족을 못하면 다쉬!!
- 해당 공부는 개인 시간 활용할 것 (평일 6시 이후, 일요일)
- 파고들면서 공부하기 : 상대방이 설명할 때, 의문점등을 계속 제시해주면서 더 깊이 공부할 수 있도록 질문해주기.

## iOS
- [ ] Bounds 와 Frame 의 차이점을 설명하시오. - junhpark
- [ ] 실제 디바이스가 없을 경우 개발 환경에서 할 수 있는 것과 없는 것을 설명하시오.
- [ ] 앱의 콘텐츠나 데이터 자체를 저장/보관하는 특별한 객체를 무엇이라고 하는가?
- [ ] 앱 화면의 콘텐츠를 표시하는 로직과 관리를 담당하는 객체를 무엇이라고 하는가?
- [ ] App thinning에 대해서 설명하시오.
###
- [ ] 앱이 시작할 때 main.c 에 있는 UIApplicationMain 함수에 의해서 생성되는 객체는 무엇인가?
- [ ] @Main에 대해서 설명하시오. - jaeylee
- [ ] 앱이 foreground에 있을 때와 background에 있을 때 어떤 제약사항이 있나요? - jaeylee
- [ ] 상태 변화에 따라 다른 동작을 처리하기 위한 앱델리게이트 메서드들을 설명하시오.
- [ ] 앱이 In-Active 상태가 되는 시나리오를 설명하시오.
- [ ] scene delegate에 대해 설명하시오. - junhpark
- [ ] UIApplication 객체의 컨트롤러 역할은 어디에 구현해야 하는가?
- [ ] App의 Not running, Inactive, Active, Background, Suspended에 대해 설명하시오.
###
- [ ] NSOperationQueue 와 GCD Queue 의 차이점을 설명하시오.
- [ ] GCD API 동작 방식과 필요성에 대해 설명하시오.
- [ ] Global DispatchQueue 의 Qos 에는 어떤 종류가 있는지, 각각 어떤 의미인지 설명하시오.
###
- [ ] iOS 앱을 만들고, User Interface를 구성하는 데 필수적인 프레임워크 이름은 무엇인가?
- [ ] Foundation Kit은 무엇이고 포함되어 있는 클래스들은 어떤 것이 있는지 설명하시오.
- [ ] Delegate란 무언인가 설명하고, retain 되는지 안되는지 그 이유를 함께 설명하시오.
- [ ] NotificationCenter 동작 방식과 활용 방안에 대해 설명하시오.
- [ ] UIKit 클래스들을 다룰 때 꼭 처리해야하는 애플리케이션 쓰레드 이름은 무엇인가?
- [ ] App Bundle의 구조와 역할에 대해 설명하시오.
- [ ] 모든 View Controller 객체의 상위 클래스는 무엇이고 그 역할은 무엇인가?
- [ ] 자신만의 Custom View를 만들려면 어떻게 해야하는지 설명하시오.
- [ ] View 객체에 대해 설명하시오.
- [ ] UIView 에서 Layer 객체는 무엇이고 어떤 역할을 담당하는지 설명하시오.
- [ ] UIWindow 객체의 역할은 무엇인가?
- [ ] UINavigationController 의 역할이 무엇인지 설명하시오.
- [ ] TableView를 동작 방식과 화면에 Cell을 출력하기 위해 최소한 구현해야 하는 DataSource 메서드를 설명하시오.
- [ ] 하나의 View Controller 코드에서 여러 TableView Controller 역할을 해야 할 경우 어떻게 구분해서 구현해야 하는지 설명하시오.
- [ ] setNeedsLayout와 setNeedsDisplay의 차이에 대해 설명하시오.
###
- [ ] NSCache와 딕셔너리로 캐시를 구성했을때의 차이를 설명하시오.
- [ ] URLSession에 대해서 설명하시오.
- [ ] prepareForReuse에 대해서 설명하시오.
- [ ] 다크모드를 지원하는 방법에 대해 설명하시오.

## Autolayout
- [ ] 오토레이아웃을 코드로 작성하는 방법은 무엇인가? (3가지)
- [ ] hugging, resistance에 대해서 설명하시오.
- [ ] Intrinsic Size에 대해서 설명하시오.
- [ ] 스토리보드를 이용했을때의 장단점을 설명하시오.
- [ ] Safearea에 대해서 설명하시오.
- [ ] Left Constraint 와 Leading Constraint 의 차이점을 설명하시오.

## Swift
- [ ] struct와 class와 enum의 차이를 설명하시오.
- [ ] class의 성능을 향상 시킬수 있는 방법들을 나열해보시오.
- [ ] Convinience init에 대해 설명하시오. - jaeylee
- [ ] Anyobject에 대해 설명하시오.
- [ ] Optional 이란 무엇인지 설명하시오.
- [ ] Struct 가 무엇이고 어떻게 사용하는지 설명하시오.
- [ ] Subscripts에 대해 설명하시오.
- [ ] instance 메서드와 class 메서드의 차이점을 설명하시오.
- [ ] Delegate 패턴을 활용하는 경우를 예를 들어 설명하시오.
- [ ] Singleton 패턴을 활용하는 경우를 예를 들어 설명하시오.
- [ ] KVO 동작 방식에 대해 설명하시오.
- [ ] Delegates와 Notification 방식의 차이점에 대해 설명하시오.
- [ ] 멀티 쓰레드로 동작하는 앱을 작성하고 싶을 때 고려할 수 있는 방식들을 설명하시오.
- [ ] MVC 구조에 대해 블록 그림을 그리고, 각 역할과 흐름을 설명하시오. - junhpark
- [ ] 프로토콜이란 무엇인지 설명하시오.
- [ ] Hashable이 무엇이고, Equatable을 왜 상속해야 하는지 설명하시오.
- [ ] mutating 키워드에 대해 설명하시오.
- [ ] 탈출 클로저에 대하여 설명하시오.
- [ ] Extension에 대해 설명하시오.
- [ ] 접근 제어자의 종류엔 어떤게 있는지 설명하시오
- [ ] defer란 무엇인지 설명하시오.
- [ ] defer가 호출되는 순서는 어떻게 되고, defer가 호출되지 않는 경우를 설명하시오.
- [ ] property wrapper에 대해서 설명하시오.
- [ ] Generic에 대해 설명하시오.
- [ ] Result타입에 대해 설명하시오.
- [ ] Codable에 대하여 설명하시오.

## ARC
- [ ] ARC란 무엇인지 설명하시오.
- [ ] Retain Count 방식에 대해 설명하시오.
- [ ] Strong 과 Weak 참조 방식에 대해 설명하시오.
- [ ] 순환 참조에 대하여 설명하시오.
- [ ] 강한 순환 참조 (Strong Reference Cycle) 는 어떤 경우에 발생하는지 설명하시오.

## Functional Programming
- [ ] 함수형 프로그래밍이 무엇인지 설명하시오.
- [ ] 고차 함수가 무엇인지 설명하시오.
- [ ] Swift Standard Library의 map, filter, reduce, compactMap, flatMap에 대하여 설명하시오.

## Architecture
- [ ] MVVM, Ribs, VIP 등 자신이 알고있는 아키텍쳐를 설명하시오.
- [ ] 의존성 주입에 대하여 설명하시오.

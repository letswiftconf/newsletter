
반갑습니다. 레츠스위프트 뉴스레터를 시작합니다. 

첫 번째 뉴스레터라서 도메인 설정부터 메일링 시스템, 자료 수집과 자료를 정리하고 이 메일을 받으실 때까지 고민꺼리가 많았습니다. 국내 iOS 소식을 전하는 여러 채널이 부족한 상황에서, 뉴스레터를 시작해주셨던 강사룡 님께 다시 한 번 감사드립니다.

전세계에서 코로나19 바이러스로 인해 놀랍고도 슬픈 일들이 많아지고 있습니다. 
지난주 목요일에 예정되어 있던 레츠스위프트 판교 모임도 3월로 잠정 연기됐습니다. 

이런 상황에서 iOS 관련 소식과 커뮤니티 모임을 꾸준히 이어가는 것이 쉽지 않을 겁니다.  
온라인에서 협업과 활동이 활발한 개발자 커뮤니티가 한 단계 성장하는 계기가 되었으면 합니다.

---

뉴스레터 발행은 매주 발행하는 것을 목표로 하겠지만, 당분간은 격주로 발행할 것 같습니다. 
뉴스레터 발행을 위해서 깃헙에 저장소를 만들었습니다. 새로운 뉴스레터를 발행하기 위해서 자료를 수집하거나 토론하는 과정을 이슈로 관리하고 있습니다. 여러분 누구나 이슈에 등록도 가능합니다. 
[뉴스레터 저장소](https://github.com/letswiftconf/newsletter)

앞으로 다양한 시도를 하려고 합니다. 새로운 소식, 유물발굴, 해외 소식도 모아서 전달하는 것 뿐만 아니라 회사 채용이나 행사 안내 스폰서십도 가능할 것 같습니다. 
레츠스위프트 2019에서 가장 관심이 많았던 것을 해소하기 위해, 제가 회사를 방문해서 기업 문화를 인터뷰하는 것도 생각하고 있습니다. 

---

[애플] [Sign with Apple 앱스토어 심사지침](https://developer.apple.com/kr/app-store/review/guidelines/#sign-in-with-apple)
4월부터 소셜 로그인을 하거나 다른 서비스로 로그인 하는 경우는 Sign with Apple을 강제한다고 했었는데 그 시점이 다가오고 있습니다.
준비중인 기업들이 많을텐데, 디자인 가이드 상으로 꼭 Sign with Apple 버튼을 동일하게 만들어야 하는건 아니라고 하더군요. 신규 앱이 아니더라도 이제 과감하게 도입해야 하는 시점일까요?


[애플] Swift Playground for Mac [다운로드](https://apps.apple.com/kr/app/swift-playgrounds/id1496833156?mt=12)
아이패드 전용 앱이던 Swift Playground 앱을 카탈리스트로 변환해서 맥용으로 출시했네요. 실행해보기 완전 동일한 버전인 것 같습니다.
심각한 버그가 있는데, 아이패드 앱도, 새로 나온 맥용 앱도 iCloud 옵션을 사용하면 새로운 플레이그라운드를 열지 못하고 크래시됩니다 🤯
사용하시려면 iCloud 에서 Swift Playground를 끄고 사용하세요.


[새로운 소식] [Alamofire 5.0.0 업데이트!](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0)

Alamofire의 메이저 버전 업데이트가 있었습니다. 애플이 추천하는 방향에 맞춰 DispatchQueue 적용하고 구조를 개선하기 위해서 코어를 다시 구현했다고 합니다. Decodable을 기본 지원하고, EventMonitor, RequestAdapter, RequestInterceptor 등 세부 과정을 제어하기 위한 인터페이스들이 추가되었습니다.  그 뿐만 아니라 Result 처리에 Swift 5 표준 타입을 사용하면서 이런저런 변화가 포함되어 있습니다. 
보다 자세한 내용은 [마이그레이션 가이드](https://github.com/Alamofire/Alamofire/blob/master/Documentation/Alamofire%205.0%20Migration%20Guide.md)를 참고하세요.


[블로그] [WWDC 2019 Binary Frameworks by 민소네](http://minsone.github.io/ios/mac/ios-wwdc-2019-binary-frameworks-in-swift-little-summary-and-translate)

스위프트 5에서 ABI가 정해지고 나서 XCFramework 을 추천하고 있습니다.
뭐가 좋아진걸까요? WWDC 2019에서 발표한 내용을 민소네님께서 번역해서 정리해주셨습니다.


[블로그] [대수적으로 알아보는 타입 체계 by 필권](https://pilgwon.github.io/post/episode-4-algebraic-data-types)

해외 블로그를 즐겨 번역해주시는 필권님이 데이터 타입에 대해 새로운 시각을 설명해셨습니다. struct와 enum 타입이 대수 관점에서 어떻게 다른지 살펴보세요. 



[블로그] [PropertyWrapper를 이용한 값처리 by 해리](https://medium.com/harrythegreat/swift-properywrapper를-이용한-값처리-a8ef0d87e8e)

이미 다른 자료로도 많이 보셨던 PropertyWrapper에 대한 글입니다. 처음 접하는 개발자도 이해하기 쉽게 쓰여져 있다고 생각해 공유합니다. PropertyWrapper의 사용 방법과 예제가 포함되어 있습니다. 


[블로그] [Standard Library Preview Package by Zedd](https://zeddios.tistory.com/m/962)

아직 Swift 배포 버전에 포함되지는 않았지만, Swift Evolution을 통과한 기능을 미리 사용해 볼 수 있는 Swift Package에 대해 친절한 zedd님 설명을 담고 있습니다.


[해외] [iOS 성능에 대한 숨겨진 팁들](https://www.fadel.io/blog/posts/ios-performance-tips-you-probably-didnt-know/)

전직 애플 개발자가 정리한 성능 개선을 위한 팁입니다. UILabel 조차 무겁다면 뭘 써야 할까요?



레츠스위프트 뉴스레터 (Let'Swift NewsLetter)
제1호 발행일 : 2020년 2월 23일

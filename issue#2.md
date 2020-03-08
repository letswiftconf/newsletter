## 레츠스위프트 뉴스레터  
##### 제2호 2020년 3월 8일

![img](https://s3.ap-northeast-2.amazonaws.com/img.stibee.com/24733_1583574350.png)

JK 님을 위한 iOS / Swift 관련 소식을 담고 있는, 따끈따끈한 뉴스레터가 도착했습니다. 

새로운 뉴스레터를 보내기까지 지난 2주가 짧게 느껴지기도 하면서, 재택 근무가 많아져서 다른 한 편으로 길게도 느껴집니다. 
JK 님은 2주동안 어떤 일이 있으셨나요? 집에만 있다보니 무인도에 갇힌 톰행크스처럼 변하고 있습니다. 
그나마 소프트웨어 업계는 재택을 많이 하지만 그렇지 않은 회사들도 많은 것 같습니다. 
판교 밋업도 아직 못하고 있으니, 모두가 건강하고 안전하지길 기원해봅니다 🙏🏻

누구나 함께하는 뉴스레터 저장소 👉
메일링 리스트 가입은 가입하기 링크 주변에 소개해주세요 🤩

----

## 🤘WWDC 2020 취소되나🤘

자극적인 제목이긴 합니다만, MWC나 페이스북 F8, 구글 I/O 등 국제 컨퍼런스나 행사가 줄줄이 취소되고 있습니다. 
헤어포스 원과 함께 하는 즐거운 키노트가 그리울 것 같습니다. 
가고싶어도 쉽게 못 가서 이미 원격에서 보는 게 익숙하기도 합니다 🤦🏻‍♂️

다음 뉴스레터를 보낼 쯤이면 관련 소식이 올라오지 않을까 예상해봅니다. 
이제 본격적으로 애플 iOS / Swift 관련 소식을 알아보도록 하겠습니다.

----

## 🇰🇷 국내 소식들

[wayne님 블로그] [Moya를 시작하는 사람들을 위한 글](https://mildwhale.github.io/2020-03-07-getting-started-with-moya/)
테스트를 좀 더 잘하고 싶지만 어디부터 시작해야 할 지 어렵다면 Moya를 도입해보세요. 

[코드스쿼드 블로그] [Codable 과 NSCoding 프로토콜의 차이점](https://medium.com/@codesquad_yoda/codable-vs-nscoding-%EC%B0%A8%EC%9D%B4%EC%A0%90-4b47e240c0b8)
새로운 소식들을 전달하다가, 오랜만에 직접 블로그를 작성해봤습니다. 상속 관계가 있어 다형성 동작이 필요한 클래스를 인코딩/디코딩했을 때 Codable에서는 다이나믹 타입 정보가 포함되지 않아 다형성이 동작하지 않는 경우를 설명합니다. 이런 경우는 NSCoding과 NSKeyedArchiver 조합을 사용해야만 합니다. 글 하단에는 설명 동영상도 포함되어 있습니다.

[노수진님 블로그] [iOS 개발자 싱가폴 이직기](https://soojin.ro/blog/singapore)
이맘때 연봉 협상을 하고나면 개발자들 마음이 싱숭생숭 해진다더네... 이런 거 공유해도 되는지 모르겠습니다만 재밌고 유익한 글입니다 😋
이 글을 보고 편집자 중에 한 분은 본인이 면접관일 때 이직사유를 물어본 것을 후회한다고 하셨습니다 :) 

덧붙여서 이직 과정에서 준비한 오픈소스도 같이 공개해 주셨습니다.  프로젝트 이름이 직관적인 `바라봐(Baraba)` 입니다. https://github.com/nsoojin/baraba
ARKit 이나 AVFoundation을 써서 사용자 얼굴을 트래킹하다가, 아이폰을 바라보고 있을때 화면에 테이블뷰, 컬렉션뷰 등 스크롤뷰 계열을 자동으로 스크롤해주는 라이브러리입니다. 단 코드 3줄이면 쉽게 적용해볼 수 있다고 합니다!

[국내 도서] 제이펍에서 [핵심만 골라 배우는 SwiftUI 기반 iOS 프로그래밍](https://jpub.tistory.com/m/1018) 책을 출간했습니다. 다들 관심이 많은데 이제 SwiftUI 저변이 넓어질 수 있을까요? [샘플 미리보기](https://jpub.tistory.com/attachment/cfile2.uf@99D45B4D5E6092D2039764.pdf)도 있네요. 

----

## ✈️ 해외 소식들

[스위프트 포럼]  드디어 [윈도우에서 스위프트 하위 Foundation을 빌드할 수 있게 되었다는 소식](https://forums.swift.org/t/swift-soars-ever-higher/34036)입니다.
정확히는 리눅스 테스트 케이스가 1714개 인데, 1706를 통과했다고 하네요. 아직 UNIX 계열 API 문제가 남아있다고 합니다.
정작 리눅스 계열도 macOS와 다르게 안되는게 남아있는데, 그래도 꽤나 진전이 되었네요. Visual Studio 에서 직접 스위프트를 컴파일할 수 있는 날이 곧 오나봅니다.

[오픈소스] 며칠전에 애플에서 main argument 파싱을 도와주는 오픈 소스 저장소를 공개했습니다. https://github.com/apple/swift-argument-parser
재빠르게 이걸 사용하는 예제를 설명한 블로그 자료도 올라왔습니다. 한 번 살펴보시죠.
https://www.avanderlee.com/swift/command-line-tool-package-manager

[해외 블로그] [SwiftUI에서 데이터 흐름 관점으로 설명하는 글](https://kean.github.io/post/swiftui-data-flow)
선언적인 뷰를 만들고 @published, @ObservedObject, @binding, @State, @Environment 활용해서 데이터가 어떻게 전달되는지 설명해줍니다.

[오픈소스] 아이콘팩토리에서 만든 마크다운 지원하는 [AttributedString](https://github.com/chockenberry/MarkdownAttributedString)
마크다운을 표시하려고 할 때 마땅한게 없었던 분들께 도움이 될 것 같아요. 

[오픈소스] 기존 Date/Time 보다 더 직관적인 [스위프트 날짜/시간 프레임워크](https://github.com/davedelong/time)
시간을 다스리는 닥터스트레인지가 되고 싶은 개발자(?)가 Time 이라는 스위프트 패키지로 배포하는 오픈소스를 공개했습니다. 지난 2년동안 더 직관적인 프레임워크를 만드는 걸 목표로 작업했다고 하네요.

[기타] 10년전 git-flow를 만들었던 Vincent Driessen가 며칠전 [회고 문구를 기존 git-flow 소개글](https://nvie.com/posts/a-successful-git-branching-model/) 맨 앞에 추가했습니다. 역시 모든 것을 만족할 수 있는 방법은 없나 봅니다. 유명하다고 무조건 받아들여서 사용해야 하는 건 아니니까요.

> If your team is doing continuous delivery of software, I would suggest to adopt a much simpler workflow (like GitHub flow) instead of trying to shoehorn git-flow into your team.
> To conclude, always remember that panaceas don't exist. Consider your own context. Don't be hating. Decide for yourself.

[기타] [iOS 개발자 설문조사](https://iosdevsurvey.com/2019/)
iOS 개발자 설문조사 중 최대 규모(2,290명)인 The iOS Developer Community Survey에서 결과를 발표했습니다. 주목할만한 내용을 꼽아보자면,
평균적인 iOS 개발자는 상용 앱 개발에서 8:2 정도의 비율로 Swift:Objective-C를 섞어 쓰고 있으며, 42%가 모든 코드를 Swift로 짜고 있다고 합니다.
Swift 언어에 대한 평균 만족도는 8.3점(10점 만점)이었으며, 69.9%가 성숙기에 접어들었다고 평가했고, 14.1%만이 써드파티 라이브러리가 Objective C와의 호환성을 유지해야한다는데 동의했습니다.
65%의 응답자가 최근 1년 이내에 개인 앱을 앱스토어 올린 경험이 있다고 합니다. 그중 44%는 무료 앱이었다고 하고, 14.4%가 1년에 1,000 달러 이상 수익을 올린다고 합니다.
AR기술 기반 비즈니스의 현황과 전망을 묻는 문항에 대한 평균 점수는 각각 3.3, 3.1으로 다소 비관적이었지만, AR 기술에 대한 자체에 대한 관심은 4.6점으로 조금 더 높았습니다.

[기타] [2020년판 iOS 개발자 면접 질문](https://ordinarycoding.com/articles/ios-developer-interview-questions-2020/)
개발 면접에서 나올 수 있는 67개의 질문을 정리했습니다. 항상 기술적 호기심을 유지하고 있는 중급 정도의 개발자라면 어렵지 않게 대답할 수 있을 질문들이 많아 보입니다. 경험 많은 면접관은 단편적인 지식을 묻는 게 아니겠죠?
이런 질문으로 시작해서 기술의 장단점, 특징에 대한 분석, 왜 그런 개념이 생겼는지 배경이나, 무엇보다 그것의 내부가 어떻게 구현되어 있는지 등 심층적으로 파고들게 됩니다.

[기타] LLVM 하위 그룹에 머신러닝 관련 처리를 위한 MLIR 관련 뉴스레터가 시작됐네요.
https://llvm.discourse.group/t/mlir-news-1st-edition-2-21-2020/544

[기타] [웹 어셈블리가 스위프트 패키지 매니저의 플랫폼에 추가](https://github.com/apple/swift-package-manager/pull/2640)될 것 같습니다. 
이걸 보고나서야 찾아보니 WebAssembly support for the Swift(https://swiftwasm.org) 라는 프로젝트가 활발하네요. 프로젝트 홈페이지처럼 스위프트 코드를 웹 브라우저에서 wasm 기반으로 바로 실행할 수도 있습니다. 리뷰 대기중인 컨트리뷰터가 익숙하다 했더니 2019 try! Swift Tokyo 2019에 swift metatype에 대한 발표를 하셨던 분이시군요. (참조 https://kateinoigakukun.hatenablog.com/entry/2019/03/22/184356)

----

## 📌짜투리 소식들

[도구] Xcode 에서 [Internal Debug 메뉴를 활성화하는 방법](https://gist.github.com/dsabanin/e1fe9bdc03d429d6cbcc7be13add9e6d)이라고 합니다.
우리에게 이런 메뉴가 정말 필요할까요? 🤷🏻‍♀️힘내라 Xcode개발팀 💪🏻

[도구] Xcode 빌드 설정 값에 대한 설명을 모아놓은 사이트 https://xcodebuildsettings.com
이걸 보니 예전에 Xcode 책에 정리했던 내용이 있던 것 같은데, 바뀐 부분도 있으니 자료를 다시 살려봐야겠네요. (언제한다고 말하지 않았...)

[디자인] 디자이너가 정리한 iOS UI 디자인 용어 https://link.medium.com/IemomVQcq4
iOS개발자 여러분, 디자이너가 물어보면 이렇게 알려주면 되나봅니다. 두둥

[디자인] 디자이너 한 명에게 영감을 받아서 시작된 [뉴모피즘(Neumorphism)은 새로운 UI 트랜드가 될 수 있을까?](https://brunch.co.kr/@cliche-cliche/32) 아직 대유행을 하지 않지만 관심들이 많은 것 같습니다. [여기 사이트](https://neumorphism.io/#55b9f3)에서는 CSS로 뉴모피즘 디자인을  바로바로 확인할 수 있습니다.
iOS 7부터 바뀌어버린 UI 디자인을 언제쯤 바꿀까요? iOS 13에서 다크모드가 들어갔었으니까, 갑자기 iOS 14에서 테마를 지원해준다거나 그러지는 않겠죠? 컬러 두 세트 지원하는 게 상당히 귀찮은 일이던데...

[디자인-해외] [그림으로 설명하는 Apple iOS 13 디자인 가이드라인](https://learnui.design/blog/ios-design-guidelines-templates.html)
애플 HIG(Human Interface Guideline)은 UI구현을 위해 반드시 숙지하고 있어야 할 내용이지만, 글이 너무 길어서 영미인조차도 읽기 어려워하는 문서입니다. 이를 그림으로 알기 쉽게 설명하는 가이드라인 해설 문서가 최근 업데이트 되었습니다.

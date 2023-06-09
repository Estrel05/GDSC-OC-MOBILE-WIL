# __:pushpin: WIL__
## __1. Flutter__
구글에서 개발한 크로스 플랫폼 GUI SDK이다. 하나의 코드베이스로 안드로이드, 리눅스, Windows, macOS, iOS 및 웹 브라우저에서 모두 동작되는 앱을 위해 개발되었다. 사용 언어 역시 구글에서 개발한 Dart이다.

### __1.1. Dart__
#### __1.1.1. 컴파일러 종류__
* Dart Web: Dart 코드를 JavaScript로 변환한다.
* Dart Native: Dart 코드를 여러 cpu 아키텍처로 변환한다. 따라서 여러 운영체제로 컴파일할 수 있다. 사물인터넷이나 자동차에도 적용 가능하다.

#### __1.1.2. 특징__
* Just-In-Time(JIT): 코드의 결과를 바로 화면에 보여주는 것을 말한다. 가상 머신 상에서 작동하기 때문에 작동이 느리다. Dart VM을 사용한다. 
* Ahead-Of-Time(AOT): 먼저 컴파일하고 그 결과인 바이너리를 배포하는 것을 말한다. 컴파일을 해야 결과를 확인할 수 있기 때문에 개발 중에는 적합하지 않다.
* Null Safety: 안전한 프로그램을 빌드하는 데 중요한 특성이다. C++, Java 등의 많은 언어들은 프로그램이 null값을 참조하게 되면 프로그램이 제대로 작동하지 않게 된다. Dart는 null값을 참조해도 프로그램이 올바르게 작동한다.

Dart의 특징은 Flutter가 Dart를 채용한 이유를 잘 보여준다. 또한, Flutter와 Dart는 모두 개발사가 구글로 같기 때문에 최적화에 유리하고 언어 규칙 수정에 용이하다는 장점이 있다. 실제로 Dart는 처음에 JIT 툴체인이 없었지만 수정을 거쳐 현재는 JIT 툴체인이 존재한다.

# __:pushpin: Question__
* SDK란 무엇입니까?
* 코드베이스란 무엇입니까?
* 바이너리의 정확한 의미가 무엇입니까?
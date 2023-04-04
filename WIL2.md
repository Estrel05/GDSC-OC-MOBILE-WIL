# __WIL__
## __1. Widget__
flutter는 여러가지 위젯의 조합을 통해 출력 화면을 구성한다. 가장 기본적인 위젯으로 Text, Image, Icon, Container가 있다.
### __1.1. Text__
텍스트를 출력한다. 'Text('텍스트')'의 형식으로 작성한다.

### __1.2. Image__
 ```
 home: Image.asset('이미지 경로')
 ```
 이미지를 출력한다. 프로젝트 폴더 내에 'assets' 폴더를 생성하여 사용할 이미지를 저장하면 된다. 이미지를 사용할 때는 이미지를 등록해야 하는데 방법은 다음과 같다.
1. test 폴더 내의 pubspec.yaml 파일을 연다.
2. 'flutter:'를 찾아 다음과 같이 작성한다.
```
flutter:
  assets:
    - assets/
```
3. 저장한다.

### __1.3. Icon__
 ```
 home: Icon(Icons.'아이콘 이름')
 ```
 아이콘을 출력한다. 아이콘 이름은 flutter 홈페이지에서 찾아볼 수 있다.

### __1.4. Container__
```
home: Container( width: '너비', height: '높이', color: Colors.'색')
```
박스를 출력한다. 비슷한 기능을 하는 위젯으로 'Sizedbox'가 있다. 위치를 지정하지 않으면 너비와 높이의 기준이 정해지지 않은 상태이기 때문에 위젯의 크기가 매우 크게 출력된다. 문제를 해결하기 위해 'Center' 위젯을 부모 위젯으로 사용하여 'Container' 위젯의 위치를 지정할 수 있다. 다음과 같이 작성한다.
```
home: Center(
    child: Container( width: '너비', height: '높이', color: Colors.'색'))
```

# __Question__
* 크롬으로 실행할 때 한글이 제대로 출력되지 않습니다.
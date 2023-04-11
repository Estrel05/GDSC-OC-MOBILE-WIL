# __:pushpin: WIL__
## __1. Column__
하위 위젯을 세로로 일렬 배치하는 위젯이다. children을 이용하여 하위 위젯을 추가할 수 있다.

## __2. Row__
하위 위젯을 가로로 일렬 배치하는 위젯이다. children을 이용하여 하위 위젯을 추가할 수 있따.

## __3. AxisAlignment__
위젯을 정렬할 때 사용하는 기능이다.
* MainAxisAlignment: 주축을 정렬할 때 사용하며 Column은 세로축, Row는 가로축이 주축이 된다.
* CrossAxisAlignment: 교차축을 정렬할 때 사용하며 Column은 가로축, Row는 세로축이 교차차축이 된다.
* Main/CrossAxisAlignment.center: 주축/교차축 방향으로 가운데 정렬한다.
* Main/CrossAxisAlignment.spaceEvenly: 주축/교차축 방향으로 같은 간격으로 정렬한다.

## __4. Scaffold__
Material Design Visual Layout을 구현하는 데 사용되는 위젯이다. 간단히 말해 앱 디자인의 뼈대 역할을 하는 위젯이며 appBar(상단바), body(메인 화면), bottomNavigationBar(하단 메뉴) 등의 하위 위젯이 있다.

## __5. 강의 과제__
```
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(title: Text('app')),
        body: Text('app'),
        bottomNavigationBar: BottomAppBar(
          height: 50,
          child: Row(
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            children: [
              Icon(Icons.phone),
              Icon(Icons.message),
              Icon(Icons.contact_page),
            ],
          ),
        ),
      ),
    );
  }
}
```

# __:pushpin: Question__
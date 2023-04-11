# __:pushpin: WIL__
## __1. Column__
���� ������ ���η� �Ϸ� ��ġ�ϴ� �����̴�. children�� �̿��Ͽ� ���� ������ �߰��� �� �ִ�.

## __2. Row__
���� ������ ���η� �Ϸ� ��ġ�ϴ� �����̴�. children�� �̿��Ͽ� ���� ������ �߰��� �� �ֵ�.

## __3. AxisAlignment__
������ ������ �� ����ϴ� ����̴�.
* MainAxisAlignment: ������ ������ �� ����ϸ� Column�� ������, Row�� �������� ������ �ȴ�.
* CrossAxisAlignment: �������� ������ �� ����ϸ� Column�� ������, Row�� �������� ���������� �ȴ�.
* Main/CrossAxisAlignment.center: ����/������ �������� ��� �����Ѵ�.
* Main/CrossAxisAlignment.spaceEvenly: ����/������ �������� ���� �������� �����Ѵ�.

## __4. Scaffold__
Material Design Visual Layout�� �����ϴ� �� ���Ǵ� �����̴�. ������ ���� �� �������� ���� ������ �ϴ� �����̸� appBar(��ܹ�), body(���� ȭ��), bottomNavigationBar(�ϴ� �޴�) ���� ���� ������ �ִ�.

## __5. ���� ����__
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
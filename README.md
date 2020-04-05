JapaneseKeyboardKit [![Apache License 2.0](https://img.shields.io/badge/license-Apache%202.0-yellow.svg?style=flat)](https://www.tldrlegal.com/l/apache2)
===================

Sample implementation for iOS Custom Keyboard Extension with [Mozc](https://code.google.com/p/mozc/) (Google Japanese Input)

See also https://github.com/yusakuw/Mozc-for-iOS / https://github.com/kishikawakatsumi/Mozc-for-iOS

<img src="https://raw.githubusercontent.com/yusakuw/JapaneseKeyboardKit/master/ScreenShots/ss_01.png" width="225px" style="width: 225px;" />&nbsp;
<img src="https://raw.githubusercontent.com/yusakuw/JapaneseKeyboardKit/master/ScreenShots/ss_02.png" width="400px" style="width: 400px;" />

### System Requirements

    macOS 10.15 Catalina
    Xcode 10
    iOS SDK 12
    Python 2.7.10


### Tested Environments

    iPhone SE, iOS Simulator 13.4


### Usage

#### Getting the code

```
$ git clone https://github.com/yusakuw/JapaneseKeyboardKit.git --recursive
$ cd JapaneseKeyboardKit
```

#### Build Mozc (Japanese Input Method)

##### Configure

```
$ cd Mozc-for-iOS/src
$ python build_mozc.py gyp
```

##### Compilation

```
$ python build_mozc_ios.py
```

#### Run Sample Project

```
$ cd ../..
$ open JapaneseKeyboardKit.xcodeproj
```


### Limitation

~~Mozc works on a device only, does not work on the simulator.~~
Now you can run your it on the iOS simulators.

 
[Apache]: http://www.apache.org/licenses/LICENSE-2.0
[MIT]: http://www.opensource.org/licenses/mit-license.php
[GPL]: http://www.gnu.org/licenses/gpl.html
[BSD]: http://opensource.org/licenses/bsd-license.php

## License

JapaneseKeyboardKit is available under the [Apache license][Apache]. See the LICENSE file for more info.

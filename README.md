# Hamsaa RTL Material Drawer
[![](https://jitpack.io/v/aliab/circular-music-progressbar.svg)](https://jitpack.io/#aliab/circular-music-progressbar)

## Description

Fully RTL and customized material navigation drawer

## Usage

To use this library you must add it as a dependency in your Gradle build:

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

```groovy
allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```
Step 2. Add the dependency
```groovy
dependencies {
    compile 'com.github.aliab:circular-music-progressbar:v1.1.1'
}
```

Then add the view to your activity:

```java
   new DrawerBuilder().withActivity(this).build();
```

Great. Your drawer is now ready to use.

## Changelog

### v1.0.0

 * Initial Release


## CREDITS
* Special Thanks to [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer).

## License
```
   
The MIT License (MIT)

Copyright (c) 2016 Hamsaa dev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

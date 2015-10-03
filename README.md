[![Android Gems](http://www.android-gems.com/badge/bunnyblue/ACDD.svg?branch=master)](http://www.android-gems.com/lib/bunnyblue/ACDD)

# ACDDCore  non-Proxy  Android Dynamic Deployment Framework
![](art/ACDD_logo_full.png)<br>
 [![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Android%20ACDD-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/2056)<br>
[![Join the chat at https://gitter.im/bunnyblue/ACDD](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/bunnyblue/ACDD?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)<br>
 Build Status [![Build Status](https://travis-ci.org/bunnyblue/ACDD.svg?branch=master)](https://travis-ci.org/bunnyblue/ACDD)


ACDD ,Android Component Dynamic Deployment Framework(Android  Plugin Framework)<br>

The MIT License (MIT) Copyright (c) 2015 Bunny Blue,achellies<br>
### [README-中文](README-Zh.md)


  <br>use patched aapt  to build Dynamic Module，it's different with  some plugin frameworks which  implement through proxy，any  question open a issue</br>

# Simple Project& Build System(aapt and ...) has Moved to https://github.com/bunnyblue/ACDDExtension


### Contributors
[achellies](https://github.com/achellies)<br>
[BunnyBlue](https://github.com/bunnyblue)<br>

## plugin start
download aapt from repo,and  you should use build-tool version 22.x.x,
write your plugin as normal app, ant build  with  hacked aapt.
### plugin resource notice
you can define your package id at Manifest by "versionName",such as versionName:"1.0.1" ,but as a plugin should be versionName:"1.0.10x7a",you will get apk which versionName is "1.0.0" but package id is 0x7a not 0x7f.you can use 0x2 to 0x7,
also you can define package change packageName "com.myapp.pkgname" to " com.myapp.pkgname0x7a".

##Sample & Art
<a href="https://github.com/bunnyblue/ACDDExtension/blob/master/Dist/ACDDLauncher.apk">
  Sample Apk,you can download from here
</a>

![Sample Gif](https://github.com/bunnyblue/ACDDExtension/raw/master/art/demo.gif)

# License
 [![License](https://img.shields.io/badge/License-MIT%20License-brightgreen.svg)]()<br>
The MIT License (MIT) Copyright (c) 2015 Bunny Blue,achellies

# [Feature @ Wiki](https://github.com/bunnyblue/ACDD/wiki#feature)

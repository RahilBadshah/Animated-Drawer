# Animated-Drawer
Creative Drawer with animation using library.





## Android Screenshots

  Gif                 |   Screenshot 1                 |   Screenshot 2
:-------------------------:|:-------------------------:|:-------------------------:
<img src="https://github.com/RahilBadshah/Animated-Drawer/blob/master/screenshots/preview.gif?raw=true" alt="drawing" width="320"  /> | <img src="https://github.com/RahilBadshah/Animated-Drawer/blob/master/screenshots/Screenshot_1.png?raw=true" alt="drawing" width="320"/>| <img src="https://github.com/RahilBadshah/Animated-Drawer/blob/master/screenshots/Screenshot_2.png?raw=true" alt="drawing" width="320"/>


## Including In Your Project

If you are a Maven user you can easily include the library by specifying it as
a dependency:

#### Maven
``` xml
<dependency>
  <groupId>com.infideap.drawerbehavior</groupId>
  <artifactId>drawer-behavior</artifactId>
  <version>1.0.3</version>
  <type>pom</type>
</dependency>
```
#### Gradle
```groovy
dependencies {
   implementation 'com.infideap.drawerbehavior:drawer-behavior:1.0.3'
}
```

if **the gradle unable to sync**, you may include this line in project level gradle,
```groovy
repositories {
 maven{
   url "https://dl.bintray.com/infideap2/Drawer-Behavior"
 }
}
```

**Initialize**
```java
drawer = (AdvanceDrawerLayout) findViewById(R.id.drawer_layout);
```

**Use custom behavior**
```java
drawer.useCustomBehavior(GravityCompat.START); //assign custom behavior for "Left" drawer
drawer.useCustomBehavior(GravityCompat.END); //assign custom behavior for "Right" drawer 
```

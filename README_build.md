# ClashMeta 编译运行

## jdk版本设置 [build.gradle.kts](build.gradle.kts)
将编译选项中对于jdk版本的要求从21降到17
```kotlin
//compileOptions {
//    sourceCompatibility = JavaVersion.VERSION_21
//    targetCompatibility = JavaVersion.VERSION_21
//}
compileOptions {
    sourceCompatibility = JavaVersion.VERSION_17
    targetCompatibility = JavaVersion.VERSION_17
}
```

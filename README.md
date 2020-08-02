### 快速集成：
- **Step 1.** Add the JitPack repository to your build file
```groovy
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```
- **Step 2.** Add the dependency
```groovy
dependencies {
    def version = "0.0.1"
    implementation "com.github.andnux:ijkplayer:${version}"
    or
    implementation "com.github.andnux.ijkplayer:ijkplayer-x86_64:${version}" 
    implementation "com.github.andnux.ijkplayer:ijkplayer-arm64:${version}" 
    implementation "com.github.andnux.ijkplayer:ijkplayer-armv5:${version}" 
    implementation "com.github.andnux.ijkplayer:ijkplayer-exo:${version}" 
    implementation "com.github.andnux.ijkplayer:ijkplayer-java:${version}" 
    implementation "com.github.andnux.ijkplayer:ijkplayer-x86:${version}" 
    implementation "com.github.andnux.ijkplayer:ijkplayer-armv7a:${version}" 
}
```


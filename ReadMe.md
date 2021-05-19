# MPAndroidChart Sample

- 레이아웃 구성하고 MPAndroidChart 라이브러리 간단하게 사용해보기

![KakaoTalk_20210519_140045628.jpg](KakaoTalk_20210519_140045628.jpg)

```xml
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {

    implementation "org.jetbrains.kotlin:kotlin-stdlib:$kotlin_version"
    implementation 'androidx.core:core-ktx:1.3.2'
    implementation 'androidx.appcompat:appcompat:1.2.0'
    implementation 'com.google.android.material:material:1.3.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.0.4'
    testImplementation 'junit:junit:4.+'
    androidTestImplementation 'androidx.test.ext:junit:1.1.2'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.3.0'
    implementation 'com.github.PhilJay:MPAndroidChart:v3.1.0'
}
```
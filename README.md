# Libraries

# 1-retrofit
- implementation "com.squareup.retrofit2:retrofit:2.9.0"
- implementation "com.squareup.retrofit2:converter-gson:2.9.0"

# 2-rxjava
-  implementation "io.reactivex.rxjava3:rxjava:3.0.6"

# 3-rxandroid
- implementation "io.reactivex.rxjava3:rxandroid:3.0.0"

# 4-kotlin
- implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.4.0"

# 5-LiveDage
- implementation "androidx.lifecycle:lifecycle-livedata:2.2.0"

# 6-ViewModel
- implementation "androidx.lifecycle:lifecycle-viewmodel:2.2.0"

# 7-Navigation Component
  def nav_version = "2.3.0"
  // Java language implementation
  implementation "androidx.navigation:navigation-fragment:$nav_version"
  implementation "androidx.navigation:navigation-ui:$nav_version"

# 8-Dagger
    def dagger_version = "2.22"
    implementation "com.google.dagger:dagger:$dagger_version"
    annotationProcessor "com.google.dagger:dagger-compiler:$dagger_version"
    implementation "com.google.dagger:dagger-android:2.x"
    implementation "com.google.dagger:dagger-android-support:$dagger_version" // if you use the support libraries
    annotationProcessor "com.google.dagger:dagger-android-processor:$dagger_version"
    

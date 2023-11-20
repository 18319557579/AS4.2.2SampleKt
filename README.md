# Kt对比Java版的差异
1.根build.gralde中buildscript.dependencies中加入classpath "org.jetbrains.kotlin:kotlin-gradle-plugin:$kotlin_version"（这里kotlin_version为1.9.0）
2.app/build.gralde先添加插件'kotlin-android'，然后引入kotlin依赖"org.jetbrains.kotlin:kotlin-stdlib:$kotlin_version"，和ktx依赖'androidx.core:core-ktx:1.12.0'

# FixedNavDrawerSample
Fixes the original Android sample Navigation Drawer Activity issue when using minSdk 27:
"Cannot inline bytecode built with JVM target 1.8 into bytecode that is being built with JVM target 1.6":
https://stackoverflow.com/questions/48988778/cannot-inline-bytecode-built-with-jvm-target-1-8-into-bytecode-that-is-being-bui

Uses org.jetbrains.kotlin:kotlin-stdlib-jdk8 instead of jdk7

# jacoco-rat
project to instrumente dy jacoco api

Do a gradle build.
Uncomment gradle.taskGraph.beforeTask from build.gradle
Take files in jacoco-rat\build\classes and instrument those using jacoco instrumentation api
replace classes by the instrumented ones.
run gradle test again.

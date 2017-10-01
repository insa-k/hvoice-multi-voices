# hvoice-multi-voices

setup for crossvalidation with several voices

```
./gradlew setupSubprojects --info --parallel -Dorg.gradle.parallel.intra=true
./gradlew legacyInit --info --parallel -Dorg.gradle.parallel.intra=true
./gradlew build --info --parallel -Dorg.gradle.parallel.intra=true
./gradlew runCrossvalidation --info --parallel -Dorg.gradle.parallel.intra=true

```
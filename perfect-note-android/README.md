# Android Application Projects

These projects were initially generated using the following `archetype` 
command:

$ mvn archetype:generate -DarchetypeArtifactId=android-release -DarchetypeGroupId=de.akquinet.android.archetypes -DarchetypeVersion=1.0.8 -DgroupId=com.justdavis.perfectnote -DartifactId=perfect-note-android -Dpackage=com.justdavis.perfectnote.android

The project's POMs were then refined using the samples from 
https://github.com/jayway/maven-android-plugin-samples.


# Android Emulator

These projects were developed and tested against an Android v2.3.3 (API 10)
target. An emulator for that target can be created as follows:

$ android create avd -n "android-10" -t "android-10" --abi armeabi --skin WVGA800

The default HW profile was used.

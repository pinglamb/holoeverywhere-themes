HoloEverywhere Themes
=====================

Holo Themes that are ready to use

## How to use?

Add the following to the gradle build file.

```
repositories {
  ...
  maven { url "https://raw.github.com/pinglamb/holoeverywhere-themes/repo" }
}

dependencies {
  ...
  compile 'com.android.support:support-v4:18.0.+@jar'
  compile 'org.holoeverywhere:library:2.1.+@aar'
  compile 'org.holoeverywhere:theme-[theme]:[version]@aar
}
```

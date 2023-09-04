# Dice Roller
A simple Kotlin app which rolls a dice.

Uses `VectorDrawable` support library in app level `build.geadle` for backward compatibility and devices bellow API version 21. 

## How to use VectorDrawable Support Library
1. Enable the use of support library for vector drawables in build.gradle file (app level): 
```
android {
...
vectorDrawables.useSupportLibrary = true
...
}
```

3. Use ```app:srcCompat``` in the image tag in the layout file: ```app:srcCompat="@drawable/empty_dice"```

4. You’ll also need to add the namespace to the root of the layout: ```xmlns:app="http://schemas.android.com/apk/res-auto"```

<img width="271" alt="Screen Shot 2021-09-21 at 11 48 53 AM" src="https://user-images.githubusercontent.com/25829099/134203799-6de60fd6-512f-471d-bb8f-f5fa58df40e6.png">

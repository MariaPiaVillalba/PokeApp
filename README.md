<h1 align="center">PokeApp</h1>

![](https://img.shields.io/static/v1?style=flat-square&logo=android&label=API&message=22%2B&color=78c257)
![https://kotlinlang.org/](https://img.shields.io/static/v1?style=flat-square&label=Kotlin&message=1.4&color=007ec6)

## Installation
Clone this repository and import into **Android Studio**
```bash
git clone https://github.com/condor-labs/PokeApp.git
```

## Libraries
- Minimum SDK level 22
- [Kotlin](https://kotlinlang.org/)
- [Retrofit2](https://github.com/square/retrofit)
- [Gson](https://github.com/square/retrofit/tree/master/retrofit-converters/gson)
- [Glide](https://github.com/bumptech/glide)
- [Glide Palette](https://github.com/florent37/GlidePalette) - Android Lollipop Palette is now easy to use with Glide

## Open API

<img src="https://user-images.githubusercontent.com/24237865/83422649-d1b1d980-a464-11ea-8c91-a24fdf89cd6b.png" align="right" width="10%"/>

Pokedoke uses the [PokeAPI](https://pokeapi.co/)




## Contributing

1. Clone it
2. Create your feature branch (git checkout -b feature/my-new-feature)
3. Commit your changes (git commit -m 'Add some feature')
4. Push your branch (git push origin my-new-feature)
5. Create a new Pull Request

# Libraries

```kotlin
//kotlin libs
    implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.3.9'


    //retrofit for network calls
    implementation 'com.squareup.retrofit2:retrofit:2.9.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.5.0'


    // Glide
    implementation 'com.github.bumptech.glide:glide:4.11.0'
    implementation 'com.github.florent37:glidepalette:2.1.2'
```


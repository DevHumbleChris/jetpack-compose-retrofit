# ComposeRetrofitSample

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.md)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.5.31-orange.svg)](https://kotlinlang.org/)
[![Compose](https://img.shields.io/badge/Compose-1.1.0--beta02-blue.svg)](https://developer.android.com/jetpack/compose)
[![Retrofit](https://img.shields.io/badge/Retrofit-2.9.0-green.svg)](https://square.github.io/retrofit/)

## Overview

Jetpack Compose Retrofit project is a sample Android project showcasing the integration of Jetpack Compose and Retrofit for making API requests in a modern Android application.

### Installation

Clone the repository and open the project in Android Studio.

```bash
git clone https://github.com/DevHumbleChris/jetpack-compose-retrofit.git

cd jetpack-compose-retrofit
```

### Add Retrofit dependencies

1. Open the module-level gradle file `build.gradle.kts (Module :app)`.
2. In the `dependencies` section, add the following lines for the Retrofit libraries:

```kotlin
// Retrofit 
implementation("com.squareup.retrofit2:retrofit:2.9.0")

// Retrofit with Scalar Converter
implementation("com.squareup.retrofit2:converter-scalars:2.9.0")
```

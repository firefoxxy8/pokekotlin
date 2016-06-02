[![Build Status](https://travis-ci.org/PokeAPI/pokekotlin.svg?branch=master)](https://travis-ci.org/PokeAPI/pokekotlin)
[![Download](https://api.bintray.com/packages/sargunster/maven/pokekotlin/images/download.svg) ](https://bintray.com/sargunster/maven/pokekotlin/_latestVersion)

# PokeKotlin

This is a Kotlin client for [PokeApi](https://github.com/phalt/pokeapi). It's also usable under Java.

## Example

### Kotlin

```kotlin
fun main(args: Array<String>) {
    val bulbasaur = PokeApi.getPokemonSpecies(1)
    println(bulbasaur)
}
```

### Java

```java
public class Example {
    public static void main(String[] args) {
        PokemonSpecies bulbasaur = PokeApi.INSTANCE.getPokemonSpecies(1);
        System.out.println(bulbasaur);
    }
}
```

## Download

PokeKotlin is available from the JCenter repository.

### Gradle

```groovy
dependencies {
    compile 'me.sargunvohra.lib:pokekotlin:1.2.0'
}
```

### Kobalt

```kotlin
val p = project {
    dependencies {
        compile("me.sargunvohra.lib:pokekotlin:1.2.0")
    }
}
```

# JamKardan Library

A simple Java library to sum two numbers.

## Installation

To use this library in your project, you can add it using **Gradle** with JitPack. First, add the JitPack repository to your `build.gradle` file:

```groovy
repositories {
    maven { url 'https://jitpack.io' }
}

Then add the dependency:

```groovy
dependencies {
    implementation 'com.github.azad222:jamkardan:1.0.0'
}

Replace `1.0.0` with the latest version from the [Releases](https://github.com/azad222/jamkardan/releases) page.

## Usage

The `JamKardan` library allows you to simply sum two integers. Here’s an example of how to use it:

```java
import com.github.azad222.jamkardan.JamKardan;

public class Main {
    public static void main(String[] args) {
        JamKardan jamKardan = new JamKardan();
        int result = jamKardan.sum(5, 10);
        System.out.println("Sum: " + result);
    }
}
# jamkardan1

# Base64Image

[![](https://jitpack.io/v/JustinNguyenME/base64image.svg)](https://jitpack.io/#JustinNguyenME/base64image)

## Example

### Bitmap to Base64 String
```kotlin
Base64Image.instance.encode(bitmap) { base64 ->
    base64?.let {
        // success
    }
}
```

### Base64 String to Bitmap
```kotlin
Base64Image.instance.decode(base64, { bitmap ->
    bitmap?.let {
        // success
    }
})
```

## Installation

```groovy
repositories {
    maven { url "https://jitpack.io" }
}
```

```groovy
dependencies {
    implementation 'com.github.JustinNguyenME:base64image:1.0.0'
}
```

## Author

Justin Nguyen, nguyen.cocoa@gmail.com

## License

Base64Image is available under the MIT license. See the LICENSE file for more info.
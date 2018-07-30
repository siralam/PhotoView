# PhotoView
This is an improved version of the original [PhotoView](https://github.com/chrisbanes/PhotoView).

Major improvements:
- Used an older version gesture detector so that smaller pinch distance threshold is used (Otherwise it will be very hard to zoom if the PhotoView is small);
- Solved gesture conflict when placed in a ScrollView due to the fact that the edge detection in PhotoViewAttacher was written badly.

```
dependencies {
    implementation 'com.asksira.android:photoview:1.0.3'
}
```
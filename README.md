# RatingView
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-RatingView-green.svg?style=true)](https://android-arsenal.com/details/1/3770)

Simple android widget that can replace standard inconvenient RatingBar in your app. Originally, only whole and half filled stars were supported. This forked repository adds ability to set 0.1/0.2/../0.9 filled stars.

![Screenshot](https://googledrive.com/host/0Bwz1_b9mA7XYbC1EQ28xaHVwcGc/ratingview2.jpg)
##Description
The default Android `RatingBar` widget hardly can satisfy developers' needs. It's a pain to customize it at all. This simple view can take a huge advantage of setting and scaling drawables for rating view easily.
##Usage
You can download this library with the following line in your `app` module `build.gradle`:
```gradle
compile 'com.github.ornolfr:rating-view:0.1.2@aar'
```    
##Example
Declare `RatingView` in your XML with `app` attributes:
```xml
<com.github.ornolfr.ratingview.RatingView
	android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:drawable_empty="@drawable/ic_star_empty"
    app:drawable_filled="@drawable/ic_star_filled"
    app:drawable_half="@drawable/ic_star_half"
    app:drawable_margin="4dp"
    app:drawable_size="24dp"
    app:is_indicator="false"
    app:max_count="5"
    app:rating="3.5" />
```
And use it through `RatingView` instance in your code. Goog luck!

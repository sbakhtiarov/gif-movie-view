gif-movie-view
==============

Android View widget for displaying GIF animations.

To show animated GIF in your application just add GifMovieView into your layout.

            <com.basv.gifmoviewview.widget.GifMovieView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:onClick="onGifClick"
                custom:gif="@drawable/my_animated_gif"/>


You can set Movie object dynamically or as a resource ID and control animation playback.

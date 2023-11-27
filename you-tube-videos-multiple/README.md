## This Example is some simple JS for dynamically creating YT videos

### We fetch a 'data-video-id' from the parent wrapper of each video required

In the use case, I injected the data attribute from an ACF field within wordpress.
This enabled me to loop though when the YT api was available and bind the videos

Note there are several dependencies to this:

My DOM Helpers ( you can just use plain JS for these though )
GSAP & Scroll Trigger ( Not critical, but good for stopping confusing multiple videos playing as a user scrolls)

Feel free to use as is - the dom selectors would need to be matched to your own etc
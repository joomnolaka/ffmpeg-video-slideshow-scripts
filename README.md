# FFmpeg Video Slideshow Scripts [![made-with-bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)](https://www.gnu.org/software/bash/) [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/) [![Build Status](https://travis-ci.org/tanersener/ffmpeg-video-slideshow-scripts.svg?branch=main)](https://travis-ci.org/tanersener/ffmpeg-video-slideshow-scripts)

Configurable shell scripts to create video slideshows from images and videos using [FFmpeg](https://www.ffmpeg.org/).

<img src="https://github.com/tanersener/ffmpeg-video-slideshow-scripts/blob/v2.x/docs/ffmpeg-video-slideshow-scripts-logo-v2.png" width="240">

## Features
### [Video Slideshow Script Generator](video_slideshow_script_generator)

<img src="https://github.com/tanersener/ffmpeg-video-slideshow-scripts/blob/v2.x/docs/vssg/vssg-gui.png" width="440">

### [Advanced Scripts](advanced_scripts)

<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Blurred Background &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Moving Text &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/advanced_blurred_background_small.gif" width="284">
  <img src="./docs/advanced_moving_text_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Object Animation &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Photo Collection &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/advanced_object_animation_small.gif" width="284">
  <img src="./docs/advanced_photo_collection_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Push Film &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Zoom In and Pan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/advanced_push_horizontal_film_small.gif" width="284">
  <img src="./docs/advanced_zoom_in_and_pan_with_fade_in_out_one_small.gif" width="284" hspace="60"> 
</p>

### [Advanced Scripts with Video Input Support](advanced_video_scripts)

<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Blurred Background &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Moving Text &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/advanced_media_blurred_background_small.gif" width="284">
  <img src="./docs/advanced_media_moving_text_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Object Animation &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Zoom In and Pan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/advanced_media_object_animation_small.gif" width="284">
  <img src="./docs/advanced_media_zoom_in_and_pan_with_fade_in_out_one_small.gif" width="284" hspace="60"> 
</p>

### [Transition Scripts](transition_scripts) 

<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Bars &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Checkerboard &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_bars_horizontal_two_small.gif" width="284">
  <img src="./docs/transition_checkerboard_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Clock &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Collapse &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_clock_small.gif" width="284">
  <img src="./docs/transition_collapse_horizontal_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Cover &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Expand &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_cover_horizontal_small.gif" width="284">
  <img src="./docs/transition_expand_circular_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Fade In &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Push Box &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_fade_in_two_small.gif" width="284">
  <img src="./docs/transition_push_box_horizontal_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Push &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Rotate &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_push_horizontal_small.gif" width="284">
  <img src="./docs/transition_rotate_one_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Sliding Bars &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Spin Blur Rotation &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_sliding_bars_horizontal_small.gif" width="284">
  <img src="./docs/transition_spin_blur_rotation_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Stack &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Wipe In&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_stack_horizontal_small.gif" width="284">
  <img src="./docs/transition_wipe_in_horizontal_small.gif" width="284" hspace="60"> 
</p>

### [Transition Scripts with Video Input Support](transition_video_scripts)

<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Bars &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Checkerboard &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_media_bars_horizontal_two_small.gif" width="284">
  <img src="./docs/transition_media_checkerboard_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Clock &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Collapse &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_media_clock_small.gif" width="284">
  <img src="./docs/transition_media_collapse_horizontal_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Cover &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Expand &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_media_cover_horizontal_small.gif" width="284">
  <img src="./docs/transition_media_expand_circular_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Fade In &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Moving Bars &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_media_fade_in_two_small.gif" width="284">
  <img src="./docs/transition_media_moving_bars_horizontal_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Push Box &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Push &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_media_push_box_horizontal_small.gif" width="284"> 
  <img src="./docs/transition_media_push_horizontal_small.gif" width="284" hspace="60">
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Rotate #1 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Rotate #2 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_media_rotate_one_small.gif" width="284"> 
  <img src="./docs/transition_media_rotate_two_small.gif" width="284" hspace="60">
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Sliding Bars &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Spin Blur Rotation &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_media_sliding_bars_horizontal_small.gif" width="284">
  <img src="./docs/transition_media_spin_blur_rotation_small.gif" width="284" hspace="60"> 
</p>
<p float="left">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Wipe In &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>
  <img src="./docs/transition_media_wipe_in_horizontal_small.gif" width="284"> 
</p>

## Requirements

1. `ffmpeg 2.8.x` or later for all scripts except those listed in `2.`
2. `ffmpeg 3.x` or later for the following scripts
   - `logo_overlay_and_zoom.sh` 
   - `zoom_in_and_pan_with_fade_in_out_one.sh` 
   - `zoom_in_and_pan_with_fade_in_out_two.sh` 
   - `zoom_out_and_pan_with_fade_in_out_one.sh` 
   - `zoom_out_and_pan_with_fade_in_out_two.sh`
   - `box_in_horizontal.sh`
   - `box_in_vertical.sh`
   - `push_box_horizontal.sh`
   - `push_box_vertical.sh`

Please note that `Advanced Moving Text` script needs `FFmpeg` to be build with `freetype`. If you compile `FFmpeg` from source you need to provide `--enable-libfreetype` flag on `./configure`. 


## Description

Each script creates a video slideshow using selected files from `media` folder. Transition scripts implement different transition effects and advanced scripts implement more complex animation like transitions/transformations.

Output of all scripts is an `h264` encoded `MPEG-4` video.


## Customization

- There is a `# SCRIPT OPTIONS` section at the top of each script. That section lists all editable parameters for that individual file. 
  
  Below you can see the list of commonly used options. Please note that editable options are not limited to the list below and some scripts define some extra options too.

    - **WIDTH:** Width of the slideshow, in pixels
    - **HEIGHT:** Height of the slideshow, in pixels
    - **FPS:** Frames per second value for the output video
    - **IMAGE DURATION:** Defines how long each image will be displayed, in seconds
    - **TRANSITION DURATION:** Defines transition duration, in seconds
    - **SCREEN MODE:** Defines how images/videos will be fitted. Supported modes are `center`, `crop`, `scale` and `blur`
    - **DIRECTION:** Controls transition direction in supported scripts, e.g., `left to right`, `right to left`, `top to bottom`, `bottom to top` 
    - **BACKGROUND COLOR:** Defines background color. You can use short names like `black`, `white`; hex values in `0xYYYYYY` format like `0x265074`, `0xc4cdd4` or transparent color with `#00000000`. Refer to [color-syntax documentation](https://ffmpeg.org/ffmpeg-utils.html#color-syntax) for the details.

- `# FILE OPTIONS` section defines which files will be included in the slideshow and in which order.
 
  By default, `find ../media/*.jpg` command is used to select all .jpg files found in the `media` folder. Order is not defined in this selection. 
To include files in a specific order, it is possible to append `sort` at the end of `find` as in `find ../media/*.jpg | sort -r` expression.

If you want to learn more about how a specific script works refer to [v1.x](https://github.com/tanersener/ffmpeg-video-slideshow-scripts/tree/v1.x) branch of this repository. Scripts in `v1.x` branch are not customizable but easier to understand.


## Build Status

| branch |                                                                               status                                                                                |
|:------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|  main  | [![Build Status](https://travis-ci.org/tanersener/ffmpeg-video-slideshow-scripts.svg?branch=main)](https://travis-ci.org/tanersener/ffmpeg-video-slideshow-scripts) |
|  v2.x  | [![Build Status](https://travis-ci.org/tanersener/ffmpeg-video-slideshow-scripts.svg?branch=v2.x)](https://travis-ci.org/tanersener/ffmpeg-video-slideshow-scripts) |


## Tips

#### Speed

- Scripts may take a long time to complete depending on your computer hardware. You can decrease the values of `resolution`, `fps` and `duration` parameters as much as possible to increase the speed.
    
- At the end of each script there exists a `# XX. END` section which defines the output video codec with additional tuning variables. 
Currently all scripts use `H264` encoding using `Main` profile and level `4.2`. This information is given in `-profile:v main -level 42 -c:v libx264` part of that section. 
You can edit this part according to [H.264 Video Encoding Guide](https://trac.ffmpeg.org/wiki/Encode/H.264) to increase the speed of the scripts. 
There are many different tuning parameters defined in that guide and some of them may work for script you used.

  ```
  # 11. END
  FULL_SCRIPT+=" -map [video] -vsync 2 -async 1 -rc-lookahead 0 -g 0 -profile:v main -level 42 -c:v libx264 -r ${FPS} ../transition_push_vertical.mp4"
  ```

#### Memory 

- Unfortunately some scripts consume too much memory. If you experience memory issues, you may try to split your images/videos into two or more smaller sets, create partial videos for each set and concatenate them with the following command. 
Although this technique works perfect for some scripts and it won't be possible to guess that video is concatenated, some others will not include a transition between the partial videos and it will be noticeable that final video is concatenated. 
If you decide to apply this method, please pay attention to that.
    
    `ffmpeg -i part1.mp4 -i part2.mp4 -filter_complex "[0:v][1:v]concat=n=2:v=1:a=0[slideshow]" -map "[slideshow]" full_slidshow.mp4`


## Versions

- **v1.x branch:** Main focus of this branch is to show how `ffmpeg` filters work and how they can be used to implement a transition or animation. So scripts in this branch are mostly static and hard to customize.  
 
- **v2.x branch:** Scripts are optimized/rearranged in order to be customized. They are hard to understand but easy to customize.


## Updates

Refer to [Changelog](CHANGELOG.md) for updates.


## Known Issues

You may notice the following warnings when executing the scripts. Below you can find their reasons and possible fixes.

##### 1. 
>[swscaler @ 0x............] deprecated pixel format used, make sure you did set range correctly

This warning is printed because input image streams are decoded with `yuvj444p` pixel format, which is deprecated. 
You can safely ignore it, `ffmpeg` users are not effected from this warning.

##### 2.
>[out_0_0 @ 0x............] 100 buffers queued in out_0_0, something may be wrong.s dup=. drop=. speed=...

>[Parsed_overlay_80 @ 0x............] [framesync @ 0x............] Buffer queue overflow, dropping.

Statements inside `filter_complex` are ordered into logical groups to give a better understanding of how they work. 
In this ordering scheme too many streams/statements wait in the buffer queue, which generates these two warnings. 
If you want to resolve them change the order of statements inside `filter_complex` and use new streams immediately 
after they are created.

##### 3.
>Past duration 0.xyz too large

Currently `push_box` and `box_in` transitions print this warning. `setpts=0.5*PTS` statements used inside the scripts 
cause this. If you know how to remove it safely please submit an issue.


## Useful Links

[How to prevent shake effect for zoompan filter](https://trac.ffmpeg.org/ticket/4298)


## Contributing

Feel free to submit issues or pull requests.


## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) with the following exceptions.

Images inside `media` folder are published in the public domain. These images are:

- [Colosseum](https://www.flickr.com/photos/134331036@N08/35674227104/) by [Klaus Berdiin Jensen](https://www.flickr.com/photos/134331036@N08/)

- [The Great Pyramid & Sphinx Eygpt](https://www.flickr.com/photos/130817154@N04/24211972286/) by [Dave Bright](https://www.flickr.com/photos/130817154@N04/)

- [Leaning Tower of Pisa](https://www.flickr.com/photos/image-catalog/19897194376/) by [Image Catalog](https://www.flickr.com/photos/image-catalog/)

- [Taj Mahal](https://www.flickr.com/photos/149013784@N08/32862668233/) by [juancolado3](https://www.flickr.com/photos/149013784@N08/)

- [chichen itza](https://www.flickr.com/photos/kanvc/15398655930/) by [kan_v_c](https://www.flickr.com/photos/kanvc/)

Videos inside `media` folder are published in the public domain. These videos are:

- [Robin Bird](https://pixabay.com/videos/robin-bird-forest-nature-spring-21723)

- [Waves](https://pixabay.com/videos/waves-vacation-summer-sun-ocean-3917)

- [Wheat Field](https://pixabay.com/videos/wheat-wheat-field-nature-17285)

Snow flake and heart images inside `objects` folder are downloaded from [pngimg.com](http://pngimg.com/download/7553) and [pngimg.com](http://pngimg.com/download/687), both licensed under the [Creative Commons 4.0 BY-NC](https://creativecommons.org/licenses/by-nc/4.0).

Film strip images inside `objects` folder are modified from [Film Strip](https://commons.wikimedia.org/wiki/File:Film_strip.svg) by [Nevit Dilmen](https://commons.wikimedia.org/wiki/User:Nevit) and licensed under [Creative Commons Attribution-Share Alike 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/deed.en).

Falling Sky font inside `fonts` folder is licensed under the [SIL Open Font License (OFL)](https://opensource.org/licenses/OFL-1.1).


## See Also

- [FFmpeg Filters](https://ffmpeg.org/ffmpeg-filters.html)
- [FFmpeg Filtering Guide](https://trac.ffmpeg.org/wiki/FilteringGuide)

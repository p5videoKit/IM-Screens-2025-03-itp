# Week 04 Video and cloud data

## [[Previous](./03_time.md)] [[Next](./05_proposal.md)]

## Homework review

- questions

- workflow

## What's new

- videoKit

- cloud data with firebase

- mo-videoplayer

## Sketches and repos

- [p5mirror-jht9629-nyu](https://jht9629-nyu.github.io/p5mirror-jht9629-nyu/downloads/gen/sketches_recent.html)

- [repo - ims-2025-jht-nyu](https://github.com/jht9629-nyu/ims-2025-jht-nyu)

- [sketch - ims_week1 v0 Xueyu333 floMirror fix](https://editor.p5js.org/jht9629-nyu/sketches/1MbhCPM60)

<!-- - Pixel manipulation: raw buffers pixels and GLSL shaders -->

<!-- ## nodejs setup

[https://nodejs.org/en/download](https://nodejs.org/en/download)
 -->

<!-- ```
// https://editor.p5js.org/jht9629-nyu/sketches/7hzeHDSIl
// 03-jht-hatviz

https://www.youtube.com/watch?v=W-ECvtIA-5A
Aperiodic monotile animation

https://molab-itp.github.io/moSalon/src/videoplayer/?playlist=W-ECvtIA-5A&title=Aperiodic%20monotile%20animation
``` -->

## p5VideoKit

- [p5VideoKit repo and demo](https://github.com/molab-itp/p5videoKit)

<!-- - [skin-tone-main-qr](https://jht1493.net/p5VideoKit/demo/index.html?u=12&d=videoKit/settings/2022-skin-tone/skin-tone-main-qr.json) -->

- [live-tile-4x2-face-mesh](https://jht1493.net/p5VideoKit/demo/?a=%7B%22setting%22%3A%22live-tile-4x2-face-mesh%22%2C%22comment%22%3A%22live-tile-4x2-face-mesh%22%2C%22back_color%22%3A200%2C%22room_name%22%3A%22VideoKit-SkinTone2%22%2C%22patch_layout%22%3A%22Single%22%2C%22canvas_size%22%3A%22960x540%22%2C%22capture_size%22%3A%22default%22%2C%22render_size%22%3A%22Canvas%22%2C%22chat_name%22%3A%22jht%22%2C%22chat_chk%22%3A0%2C%22live_index%22%3A0%2C%22live_chk%22%3A1%2C%22urects_lock%22%3A0%2C%22urects_count%22%3A1%2C%22canvas_resize_ref%22%3A%22%22%2C%22canvas_data_chk%22%3A1%2C%22mediaDiv_states%22%3A%5Bnull%2C%7B%22vis%22%3A0%2C%22mute%22%3A1%7D%2C%7B%22vis%22%3A0%2C%22mute%22%3A1%7D%5D%2C%22patches%22%3A%5B%7B%22eff_spec%22%3A%7B%22ipatch%22%3A0%2C%22imedia%22%3A1%2C%22eff_label%22%3A%22live_tile_host%22%2C%22urect%22%3A%7B%22width%22%3A960%2C%22height%22%3A540%2C%22x0%22%3A0%2C%22y0%22%3A0%7D%7D%2C%22eff_props%22%3A%7B%22ncell%22%3A2%2C%22width_div%22%3A2%2C%22period%22%3A5%2C%22fit%22%3A%22height%22%2C%22showQRCode%22%3A1%2C%22autoHideQRCode%22%3A1%2C%22image_url%22%3A%22.%2Feffects%2Fqrcode0.png%22%2C%22shift%22%3A1%7D%7D%5D%7D)

- [live-tile-6x3-face-mesh](https://jht1493.net/p5VideoKit/demo/?a=%7B%22setting%22%3A%22live-tile-6x3-face-mesh%22%2C%22comment%22%3A%22live-tile-6x3-face-mesh%22%2C%22back_color%22%3A200%2C%22room_name%22%3A%22VideoKit-SkinTone2%22%2C%22patch_layout%22%3A%22Single%22%2C%22canvas_size%22%3A%22960x540%22%2C%22capture_size%22%3A%22default%22%2C%22render_size%22%3A%22Canvas%22%2C%22chat_name%22%3A%22jht%22%2C%22chat_chk%22%3A0%2C%22live_index%22%3A0%2C%22live_chk%22%3A1%2C%22urects_lock%22%3A0%2C%22urects_count%22%3A1%2C%22canvas_resize_ref%22%3A%22%22%2C%22canvas_data_chk%22%3A1%2C%22mediaDiv_states%22%3A%5Bnull%2C%7B%22vis%22%3A0%2C%22mute%22%3A1%7D%2C%7B%22vis%22%3A0%2C%22mute%22%3A1%7D%5D%2C%22patches%22%3A%5B%7B%22eff_spec%22%3A%7B%22ipatch%22%3A0%2C%22imedia%22%3A1%2C%22eff_label%22%3A%22live_tile_host%22%2C%22urect%22%3A%7B%22width%22%3A960%2C%22height%22%3A540%2C%22x0%22%3A0%2C%22y0%22%3A0%7D%7D%2C%22eff_props%22%3A%7B%22ncell%22%3A3%2C%22width_div%22%3A2%2C%22period%22%3A5%2C%22fit%22%3A%22height%22%2C%22showQRCode%22%3A1%2C%22autoHideQRCode%22%3A1%2C%22image_url%22%3A%22.%2Feffects%2Fqrcode0.png%22%2C%22shift%22%3A1%7D%7D%5D%7D)

- [repo - videoKit-plugin-example ](https://github.com/p5videoKit/videoKit-plugin-example)

- [sketch - p5moRelease videoKit 370 v1](https://editor.p5js.org/jht9629-nyu/sketches/xSrdePcOW)

<!-- - fork repo to customize
- examples plugins:
  - a_example_props
  - a_slit_scan
- creating a setting
- creating a plugin
- bin/build.sh -->

## moSalon

interactive multi-screen experiences on handheld and large screens

- [moSalon pages](https://molab-itp.github.io/moSalon)
- [moSalon github](https://github.com/molab-itp/moSalon)

### photo-booth example

- [moSalon photo-booth](https://molab-itp.github.io/moSalon/src/photo-booth/?v=45)

### Aperiodic monotile videoplayer example

- [03-jht-hatviz](https://editor.p5js.org/jht9629-nyu/sketches/7hzeHDSIl)
- [Aperiodic monotile animation](https://www.youtube.com/watch?v=W-ECvtIA-5A)
- [videoplayer](https://molab-itp.github.io/moSalon/src/videoplayer/?playlist=W-ECvtIA-5A&title=Aperiodic%20monotile%20animation)

<!-- ## p5mo alliance

- [p5moExamples](https://github.com/molab-itp/p5moExamples)

  - multi-device experiences on handheld and large screens
  - creating and updating firebase cloud data
  - p5js examples for p5moLibrary
 -->

## Homework Week04

- prepare your final project proposal

  - describe on your wiki page what p5js interactive experience you hope to build over the next 3 weeks.
  - you can build on any of the resources covered in class or one that you've found
  - provide links to any work you use

- be prepared to discuss: Progress / Plans / Problems - summarize on your wiki page

- optional -

  - create git repo for your final project

- optional -

  - build on the moSalon to create small screen + big screen experience

- optional -

  - contribute to p5VideoKit
  - Fork p5VideoKit and create a plugin
  - give feedback via p5VideoKit issues
  - pull request to add your plugin

- add a link to your sketch or git repo on the [wiki home page](https://github.com/p5videoKit/IM-Screens-2025-03-itp/wiki#week-04-homework)

- give a brief summary of on your wiki page for the past 4 weeks
- enter any questions or notes on your wiki page
- or use your fav blogging tool for your questions and notes
- and link to it from your wiki page

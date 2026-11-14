# `pr/mipi-csi-video-output`

One part of the topic repo p1ngb4ck/esphome-esp-video. The whole topic, with its description, is the branch `main`.

Change of this branch: mipi_csi: runtime resolutions, frames through the video output

Based on these branches, whose changes it holds and builds on:

- `pr/camera-encoder-option`: camera, mipi_csi: the encoder a camera option (`encoder: jpeg \| h264`)
- `pr/lvgl-remote-input` of p1ngb4ck/esphome-hid: `lvgl` `remote_input`: LVGL from outside (pointer, keys by key binding action, text), keys fire their action while LVGL is paused
- `pr/lvgl-color-depth-32` of p1ngb4ck/esphome-mipi-display: lvgl `color_depth: 32` as RGB888 (3 bytes per pixel)
- `pr/mipi-dsi-scanout` of p1ngb4ck/esphome-mipi-display: mipi_dsi `frame_buffers` (up to 3), the frame buffers handed to a direct client and flipped at the frame end, the scanout interface, LVGL drawing straight into the frame buffers with two of them

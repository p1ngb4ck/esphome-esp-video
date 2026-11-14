# `pr/avi-media-player`

One part of the topic repo p1ngb4ck/esphome-esp-video. The whole topic, with its description, is the branch `main`.

Change of this branch: avi: media_player platform (MJPEG through the video output, PCM / MP3 / FLAC sound, playlist, network streams)

Based on these branches, whose changes it holds and builds on:

- `pr/avi`: avi: AVI demuxer, muxer, read-ahead file reader on the storage worker
- `pr/esp32-require-hw-jpeg`: esp32 `require_hw_jpeg()`: the JPEG codec for the chip (P4 hardware JPEG, S2 / S3 esp_new_jpeg, others JPEGDEC)
- `pr/lvgl-remote-input` of p1ngb4ck/esphome-hid: `lvgl` `remote_input`: LVGL from outside (pointer, keys by key binding action, text), keys fire their action while LVGL is paused
- `pr/lvgl-color-depth-32` of p1ngb4ck/esphome-mipi-display: lvgl `color_depth: 32` as RGB888 (3 bytes per pixel)
- `pr/mipi-dsi-scanout` of p1ngb4ck/esphome-mipi-display: mipi_dsi `frame_buffers` (up to 3), the frame buffers handed to a direct client and flipped at the frame end, the scanout interface, LVGL drawing straight into the frame buffers with two of them

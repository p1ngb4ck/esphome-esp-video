# `pr/media-player-options`

One part of the topic repo p1ngb4ck/esphome-esp-video. The whole topic, with its description, is the branch `main`.

Change of this branch: media_player: `pictures`, `controls`, `queue`, `extended_api_services` for every media player

Based on these branches, whose changes it holds and builds on:

- `pr/display-video-output-rows`: display: `open_rows`, `rows_begin` / `rows_end` for a writer of its own, `rotation()`, `display()`
- `pr/online-image-path-source`: online_image: `url` or `path`, a local path through the storage interface
- `pr/relay-link` of p1ngb4ck/esphome-relay-link: `relay_link`: the link to the relay integration (URL, token and stream port through `relay_link_set`, kept in the preferences), one task for the consumers' requests, `http_at()` for their plain HTTP sources

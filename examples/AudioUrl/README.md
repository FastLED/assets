# AudioUrl

Asset for the FastLED `examples/AudioUrl` sketch.

| File | Size | sha256 |
|---|---|---|
| `track.mp3` | 8,945,229 B | `cadd2666c5571e12fafdb21697b26aef6f196a5a9c28e708129870167679991d` |

Mirrored from https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3
so the example does not depend on a third-party host staying byte-stable.
fbuild requires a sha256 for every `.lnk`, and pinning a digest to a URL
outside the project's control means any re-encode upstream breaks the build.

See FastLED/fbuild#1357.

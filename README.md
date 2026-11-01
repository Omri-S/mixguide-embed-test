# mixguide-embed-test

One static page that embeds the official YouTube IFrame player, to test whether a video plays when embedded from
a public https site. Open `https://omri-s.github.io/mixguide-embed-test/?v=<video id>&autoplay=1`, or type an id.

No tracking, no keys, no other code.

`player.html?v=<id>` is the same official player for an app that frames this page: it reports state and position
to the framing window by `postMessage` and takes play/pause/seek/rate commands from it only.

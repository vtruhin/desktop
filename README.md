# Songbee

Songbee will be a post-cloud music streaming app, similar
to [Spotify][] or [Deezer][]. The key difference is: it's free and
decentralized, powered by peer-to-peer networks like BitTorrent.

**Status:** streams music from torrent files (given there are enough seeds).

## Install

To run it from source:

1. Install MPV globally (`brew install mpv` on macOS, [various repos][mpv-repos]
   on Linux, but no idea about Windows)
2. `git clone https://github.com/Songbee/desktop`
3. `npm install && gulp && npm start`

## FAQ-like section

### Why?

Why not?

### But this is piracy!

Technically, this violates the DMCA, you're right. However, we will cover
for that with optional Bitcoin-powered donations. This would work much like
[Flattr][]: say, you pay $10 per month and listen to Ruby My Dear tracks
15 times and to [sabufaizu][] 20 times this month. Ruby My Dear gets
$10 * (15/35) = $4.28 and sabufaizu gets the rest.

### If the donations are optional, nobody would donate!

Those who don't want to pay wouldn't have paid if Songbee didn't exist.

### Still, this is illegal. Music labels will sue you!

Yeah, well, look at the [Popcorn Time][].

### Okay, copyright fighter, so what's the license?

[Unlicense][]. I wanted to use MIT, but it doesn't really make sense.

If you want to contribute to this project, you'll have to sign
a Copyright wavier — see [CONTRIBUTING](CONTRIBUTING.md).


[Spotify]: https://spotify.com/
[Deezer]: https://deezer.com/
[mpv-repos]: https://mpv.io/installation/
[Flattr]: https://flattr.com/
[sabufaizu]: https://soundcloud.com/sabufaizu
[Popcorn Time]: https://popcorntime.sh/
[Unlicense]: http://unlicense.org/

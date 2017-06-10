# Anny FM: Battery 1,2,3

[anny.audio](https://www.anny.audio)

Originally performed live @ The Loft, Brighton, 4th July 2014.

[Listen to Battery 1,2,3 on Bandcamp](https://annyfm.bandcamp.com/album/battery-123-live-at-the-loft)

## Files

`battery.scd` is a simple SuperCollider startup file to configure audio routing and load project samples.

`battery.tidal` is the full Battery 1,2,3 composition for Tidal Cycles.

`samples.csv` contains sample attributions. All samples are available in `samples/` directory.

## Snippets

The main `battery.tidal` reflects the original composition, and includes 'initial states' of the various patterns used with notes on what should be changed and when. New patterns are prefaced with a comment like `-- @something` declaring its 'key' for reference.

In the `snippets/` directory are [yasnippet](http://joaotavora.github.io/yasnippet/)-compatible snippet files reflecting these references, and additionally a `b1setup` snippet (which contains the project setup) and a `battery123` snippet that provides a convenient list of all project snippets.

For easy loading and use in emacs Tidal, copy or symlink the snippets into a `haskell-mode` major group in one of your snippet folders.

## License

- Source code: [CC-BY-SA](https://creativecommons.org/licenses/by-sa/4.0/)
- Samples: see origins of sample attributions for individual licenses

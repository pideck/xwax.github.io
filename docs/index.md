---
layout: default
title: Documentation
---
#  xwax Community Wiki

xwax is an open source [vinyl emulation software](http://en.wikipedia.org/wiki/Vinyl_emulation_software) project under the [GPL](http://en.wikipedia.org/wiki/Gpl) for GNU\Linux

Please feel free to contribute to the documentation. You can also chat with or ask advice from the xwax community live in the IRC channel #xwax on [irc.freenode.net](http://freenode.net/using_the_network.shtml)

# User Guides & Documentation

## Getting Started with xwax

### Installing xwax

  * [Building xwax from Source](Build xwax from Source)
  * [Debian Repository Installation](Debian Installation)
  * [Ubuntu Repository Installation](Ubuntu Installation)
  * xwax is also avalible in the Arch Linux Community repository


### Configuring xwax

  * [[Connecting your hardware]]
  * [[Setting up real time audio priority for xwax]]
  * [[Writing your start-up command]] FIXME

### Using xwax

  * [[Keyboard Control]]
  * [[Novation Dicer Control]]
## Hardware & xwax

  * [Tested Soundcards](List of soundcards)
  * [[Timecode Records and CDs]]


## Non-Standard Usages and Modifications

### Non-Standard Usages

  * [[One deck setup]] - Controlling several virtual decks with only one turntable
  * [[Four-deck rigging]] - Breaking xwax's 3 deck barrier

### Patches

  * [ Cues saving and display](https://github.com/oligau/xwax-1.5-xwaxed-cues) - Port of xwaxed cues features. Save and load from .cue file and cue display.
  * [xwax Timecode](https://github.com/oligau/xwax-1.5-timecode) - Version of xwax that contains Mark's timecode definitions for 4khz, 2khz and 1khz versions. [Timecode 1khz 0.1 FLAC and MP3 torrent](http://oscille.ca/tracker/xwax-timecode-0.1.zip.torrent)
  * [OSC Server](https://github.com/oligau/xwax-1.5-osc) - Evolution of cmd branch. Permits to send commands with xwax-client command line or by OSC messages.
  * [ympd web client](https://github.com/oligau/ympd-xwax) - xwax remote control branch of ympd mpd client
  * [Relative Timecode](relative timecode) - Togglable prevention of record skipping and needle dropping
  * ["Vertical side-by-side waveforms" patch](http://pastebin.fr/pastebin.php?dl=24065) for xwax 1.3-beta2 (see [screenshot](http://twitpic.com/6suvkn))
  * ["playedtracks" patch](http://confusedbits.net/coding/playedtracks-patch-for-xwax-0-7/) for xwax 0.7
  * ["cue points" patch](http://confusedbits.net/coding/cue-points-patch-for-xwax-0-7/) for xwax 0.7


### Outdated Hacks

  * [Changing the font size in xwax](changing the font size in xwax)
  * ["Vertical side-by-side waveforms" patch](http://pastebin.fr/pastebin.php?dl=22474) for xwax 1.0
  * [[45RPM Mode]] for 0.7 and earlier


## External Tools and Scripts

### Import Scripts

[[Default Import Script]]

  * [ Scan + Import Script for Scratching a Live Input](Modified Script For Live Mic Input )
  * [ cd audio instructions](setting up the cd audio importer )

### Scan Scripts

[[Default Scan Script]]

  * [Scan + Import Script for Scratching a Live Input](Modified Script For Live Mic Input )
  * [[iggy's Scan Script]] - Uses playlists to speed up xwax's startup time and gets BPM info from file metadata
  * [[oligau's Scan Script]] - Uses playlists to speed up xwax's startup time and gets BPM info from file metadata or from filename if no tag present

### External Tools

  * [[xwax Playlist Exporter]] - An Amarok 2 script
  * [[bpm-tools]] - BPM detection
  * [key-tools](http://www.pogo.org.uk/~mark/key-tools/)- Key detection

## Misc

  * [xwax Version History](xwax_changelog)

# Common Issues & Troubleshooting

  * Virtual decks playing in reverse? Switch the left and right RCA plugs over.
  * Getting pops, clicks and xruns? Try increasing your buffer size.
  * xwax not working with your CD players? Turn off key lock/master tempo.
  * [Diagnosing the Scope Views](http://serato.com/articles/scratchlive/2781/diagnosing-the-scope-views) - A useful article from Serato on using the scope display. Helpful if your timecode's performance is less than optimal.
  * [[TTF DejaVu fonts not found]]

# xwax Community

xwax is not only a project, but also a lively community!

  * Check out [our works](ourworks) and list your creations too!
  * Get in touch with the developers with your feedback and bug reports via the [xwax-devel mailing list.](https://lists.sourceforge.net/lists/listinfo/xwax-devel)
  * You can also chat with or ask advice from the xwax community live in the IRC channel #xwax on [irc.freenode.net](http://freenode.net/using_the_network.shtml). Best practice is to ask your question and then leave your IRC client running while you do something else as it may be some time before someone replies.
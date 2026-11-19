# Armiger

An open-world role-playing game for the Miyoo Mini Plus (Onion OS), grown from a coat of arms you design.

You draw your arms in the forge: shield shape, field, division, ordinary, a charge from about 6,400 redrawn as pixel art, and their tinctures. The arms seal into a seed, and the same arms always tell the same story and make the same world. Each land is a historical people chosen by its biome, from Norse and Welsh to Byzantine and Andalusi, with its own names, towns, buildings and music. Two more realms lie over the sea.

Armiger is free to play on the Miyoo Mini family. This repository holds the releases only.

## Installing

The easiest way is [MiniMart](https://github.com/zakijss/MiniMart): Armiger is at the top of **Ports**. MiniMart checks the release signature before it installs anything.

By hand:

1. Download `armiger-<version>.zip` from [Releases](https://github.com/zakijss/Armiger/releases).
2. Turn the Miyoo off, put its SD card in your computer, and copy the zip's `Roms` folder onto the card over the one already there. Only Armiger's own files are written.
3. Armiger is under **Games > Ports**.

It needs Onion OS. No account and nothing to set up.

## Updates

On Wi-Fi, Armiger looks for a new version in the background and puts it in place the next time you are on the title screen. It only takes a version signed by its maker and never touches your saves, which are in `Games/Armiger/saves`.

## Checking a download

Each zip has a `.minisig` signature beside it. With [minisign](https://jedisct1.github.io/minisign/):

```sh
minisign -Vm armiger-<version>.zip -P RWRGexQYg+Iz7qmCsthbkahuuq2lZFD6stbL++5numHHKPnsxWhoOM1K
```

## Credits

The coat-of-arms charges, fonts and music come from others under their own licences, listed in `CREDITS.txt` and the `licenses` folder inside each release.

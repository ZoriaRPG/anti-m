# Anti-M

Boot ROM-limited games on any Apple II.

## What is this?

Many early Apple II games only worked on the original Apple II or Apple ][+.
They refuse to boot on later models, often displaying an "M" error code. This
was due to overly aggressive copy protection; late in the boot process, there is
code that checksums the ROM and reboots if it's not recognized. The games
themselves would work fine if they were allowed to boot past this ROM check.

Anti-M is a pre-booter that controls the games' bootloader long enough to bypass
the ROM check, allowing you to play these games on any Apple II.

## How do I use it?

Boot the Anti-M disk. When it prompts you to insert your original disk, do so,
then press `<RETURN>`. The game should boot normally.

## Which games are supported?

Gebelli Software:

- Eggs-It
- Horizon V
- High Orbit
- Lazer Silk
- Neptune
- Phaser Fire
- Russki Duck
- Zenith

Broderbund Software:

- Choplifter (*)
- Dueling Digits
- Labyrinth
- Seafox
- Serpentine (*)
- Sky Blazer
- Star Blazer

(*) later re-released with different copy protection. Only the first release
requires Anti-M.

## Does Anti-M patch my original disk?

No! All patches are done in memory only. If you reboot your original disk
(without running Anti-M), it will fail as usual, because the ROM check is still
there.

## Can I use Anti-M from a hard drive?

Yes! Copy the `ANTI.M.SYSTEM` file to anywhere on your ProDOS hard drive and run
it with your favorite launcher.

## History

2019-03-09

- initial release

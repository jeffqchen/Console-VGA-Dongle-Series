# Console-VGA-Dongle-Series

Everyone using the SCART cables for RGBS has had enough of. They are inconsistent in quality, the plug is huge and unreliable, the audio buzzing drives you crazy. So here's my vision in solving the problem.

An ordinary VGA cable has 3 coaxial cables for RGB signals, and a bunch of other wires. I'm using the RGB channels as intended, as well as the horizontal sync (pin 13) for sync signal. Stereo audio runs through pin 12 (left) and pin 15 (right), with capacitors to isolate any possible DC voltage. This pinout makes sure the signals comply with ordinary VGA devices, so nothing would blow up if you accidentally plug the other end into something standard.

With RGB channels well-shielded, the remaining unshielded sync line will slightly couple into the the audio channels. With a normal 2-meter run, at normal hearing volume level, the buzzing is not audible. I experimented by connecting 5 of 2-meter VGA cables, and the buzzing noise finally became slightly audible.

With this in mind, I've decided to have a 3.5mm audio jack on the console side to enable audio breakout, right at the source. You can choose to carry the audio down the VGA cable by not using that jack. It's all about options.

The 5V line from various consoles is preserved, just in case the signal needs to be converted back to a SCART plug for terminal display devices.

Currently supported consoles
- Nintendo Famicom (NESRGB, Mini DIN 8 pin)
- Nintendo AV Famicom/Super Famicom/Super NES (AV Multi)
- Nintendo 64 (Various RGB mods)
- Nintendo GameCube (GCDual)
- 3DO (3DORGB, Mini DIN 8 pin)

Currently supported devices
- RetroTINK 5X Pro (WIP)
- Extron MVX VGA Switch
- gscartsw

Also works with
- OSSC 1.6
- GBS Control

To-do list:
- Sega Genesis/Mega Drive (Mini DIN 9 pin)
- PlayStation 1/2/3 (Sony AV Multi)
- Sega Saturn (Mini DIN 10 pin) (Might require drastic modding)
- VGA2SCART dongle for terminal display device

-----

Here are the links to the various released projects:

## Consoles
Nintendo consoles - SNES2VGA
- https://github.com/jeffqchen/SNES2VGA

8DIN2VGA
- https://github.com/jeffqchen/8DIN2VGA

## Devices

MVX Audio Separator/Combiner
- https://github.com/jeffqchen/MVX-Audio-Separator-Combiner

gscartsw2VGA
- https://github.com/jeffqchen/gscartsw2VGA

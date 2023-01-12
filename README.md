# [Teenage engineering op-z](https://teenage.engineering/guides/op-z/midi) MIDI map for [M-VAVE SMK-25](https://www.amazon.com/M-WAVE-Controller-Bluetooth-Professional-Production/dp/B0B66SX286) Wireless MIDI-controller

![](https://github.com/tsoop-ru/op-z-m-vave-smk-25-midi-preset/blob/fe12a977b574f69724e68dcfa929bcf2325e170b/m-vave.png)

A BLE MIDI controller and a MIDI sequencer can offer a fully wireless setup when used together. One such example is the M-VAVE SMK-25 controller, which is known for its budget-friendly price point and easy connectivity.

The op-z sequencer is also able to connect wirelessly to BLE MIDI capable devices such as laptops, tablets, and phones. This allows for multiple instruments or controllers to be connected and used in the composition process, as well as the ability to route and record MIDI and audio signals when connected directly to a relay device. This setup provides a convenient and flexible option for musicians.

For iPad and iPhone I prefer [AUM audio mixer app](https://apps.apple.com/us/app/aum-audio-mixer/id1055636344) and go straght to [Chromatone MIDI monitor](https://chromatone.center/practice/midi/monitor) with Chrome on any device. There's also a complete [MIDI log](https://chromatone.center/practice/midi/log/) for you to tinker with. And look out for more!

So. This repo includes exported SMK-25 MIDI maps to control op-z in various ways. Play and stop buttons work great with the FA and FC commands as I found at [OP-forums](https://op-forums.com/t/how-can-i-control-start-and-stop-with-a-foot-controller-on-op-z/20117/4) and [here](https://www.reddit.com/r/ZOIA/comments/ixkc53/comment/g6bkl6m/?utm_source=reddit&utm_medium=web2x&context=3). You can find [other connectivity tricks there too](https://op-forums.com/t/op-z-exotic-connectivity-tricks/19928).

You can use the [CubeSuite iOS app](https://apps.apple.com/us/app/cubesuite/id1576180487) to manage the keys, pads and knobs bindings. Or download the [CubeSuite desktop app here](http://www.cuvave.com/xznr). I'm using it to export the mkc files for you to reuse.

## The 8 channel preset

SMK-25 has 8 easily switchable presets that encompass all the controls, including the keys. It makes it quite versatile, but it still can't cover all the 16 MIDI channels of the op-z. But it uses only 8 channels for actual sounds. And SMK-25 has 2 pages per preset, so we can cover pretty much all the sonic possibilities of the op-z.

On each page keybed controls the corresponding notes. Knobs correspond to op-z 16 knobs precisely. Pads functions differ for each layer and are chosen arbitrarily.

### Percussion

Pads represent most used notes and some useful modifiers from the 13th performance channel.

1. Kick
2. Snare
3. HiHat
4. Perc

### Tonal instruments

Pads represent the performance and tape effects suitable for the channel.

5. Bass
6. Lead
7. Arp
8. Chords

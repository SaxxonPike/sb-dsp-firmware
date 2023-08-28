# sb-dsp-firmware
D52 .ctl files for studying ISA Sound Blaster firmware.

Extends upon research done by Tube Time: https://github.com/schlae/sb-firmware

### Why?

Bugs exist in some versions of SB DSP code. We seek to understand these bugs and,
as developers of software that utilizes the devices they're attached to, understand
either how to resolve or work around them. This research also drives the development
of legacy sound device emulators.

A longer term goal might include DSP code free from bugs, fixed by the community.

### Requirements

- Go get D52 here: https://www.bipom.com/dis51.php
- Run the firmware through it; the .ctl file will be used to populate labels.
- Write some docs, contribute some research, you know the drill.

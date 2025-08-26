# freemint_os_distro
Freemint OS for 32bit Atari machines. Complete bootable distribution

In release is image for 4GB card. Copy raw image to card with dd or Balena Etcher or something other. For save space is image ziped.

In repository are tar archive for drive C: and E:. C: must be bootable FAT12/16 end E: must be ext2.

Distro is configured for use with videl and resolution 800x606 with 256 color on unchanged falcon. This have some requirement for your monitor. In case you have problem with display, run videlity configuration and setup parameters acceptable by your monitor.

Working on base Falcon same as DFB1x and CT60/63 accelerator.
Minimum is 14MB RAM, but TT RAM expansion are very recomended.
Networking on netusbee and picowifi are supporeted.

Content:
- up-to-date kernel
- wide unix backend with many utilities
- XaAES and Teradesk
- Web browser links with newest SSL support
- Pure C, GCC, Python, GFA Basic and more developing tools
- Online updater

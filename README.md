# Tools
## Inits

1. [Finit](https://github.com/troglobit/finit)
2. [Nitro](https://github.com/leahneukirchen/nitro)
3. [Shinit](https://github.com/cemkeylan/shinit)
   

## Notifications

1. [Herbe](https://github.com/dudik/herbe)
2. [tiramisu](https://github.com/Sweets/tiramisu)

## Window managers for X11

1. [DWM](https://dwm.suckless.org/)
2. [sowm](https://github.com/dylanaraps/sowm)

## Wayland compositors

1. [dwc](https://git.sr.ht/~corg/DWC) - dynamic
2. [dwl](https://github.com/djpohly/dwl) - tiling
3. [hevel](https://git.sr.ht/~dlm/hevel) - floating, scrollable
4. [howl](https://git.sr.ht/~wf/howl) - tiling
5. [klatka](https://git.sr.ht/~dlm/klatka) - kiosk-style
6. [neuwm](https://git.sr.ht/~pfr/neuwm) - floating
7. [slgro](https://git.ouppyawa.xyz/0uppy/slgro/) - floating, keyboard-driven
8. [tohu](https://git.sr.ht/~shrub900/tohu) - floating
9. [wsxwm](https://git.sr.ht/~uint/wsxwm) - tiling


## Userland

1. [Busybox](https://www.busybox.net/)
2. [Chimerautils](https://github.com/chimera-linux/chimerautils)
3. [plan9port](https://github.com/9fans/plan9port)
4. [sbase](https://github.com/michaelforney/sbase)
5. [Toybox](https://github.com/landley/toybox)

## Other tools

* [bmake](https://www.crufty.net/help/sjg/bmake.html)
* [byacc](https://invisible-island.net/byacc/)
* [cproc](https://sr.ht/~mcf/cproc/)
* [mksh](https://github.com/MirBSD/mksh)
* [netbsd-curses](https://github.com/sabotage-linux/netbsd-curses)
* [om4](https://github.com/iglunix/om4) Portable OpenBSD m4.
* [OpenDoas](https://github.com/Duncaen/OpenDoas)
* [OpenPAM](https://git.des.dev/OpenPAM/OpenPAM)
* [oslo](https://github.com/iglunix/oslo)
* [pkgconf](https://github.com/pkgconf/pkgconf)
* [qbe](https://c9x.me/git/qbe.git)
- [samurai](https://github.com/michaelforney/samurai)
- [swc](https://github.com/michaelforney/swc)
- [u-config](https://github.com/skeeto/u-config)
- [zlib-ng](https://github.com/zlib-ng/zlib-ng)

- # Suckless software table

| use                                                                                                 | standard tool                                                                                       | suckless tool                                                                                       |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| Standard C library                                                                                  | glibc                                                                                               | musl                                                                                                |
| Backtrace functions                                                                                 | glibc                                                                                               | libexecinfo                                                                                         |
| C++ standard library                                                                                | libstdc++                                                                                           | libc++                                                                                              |
| Stack unwinding                                                                                     | libgcc                                                                                              | libunwind                                                                                           |
| Compiler builtins                                                                                   | libgcc                                                                                              | compiler-rt                                                                                         |
| POSIX yacc                                                                                          | bison                                                                                               | byacc                                                                                               |
| POSIX utilities                                                                                     | coreutils                                                                                           | toybox, busybox, chimerautils, lobase                                                               |
| C++ compiler                                                                                        | gcc                                                                                                 | clang                                                                                               |
| Compression library                                                                                 | zlib                                                                                                | zlib-ng                                                                                             |
| POSIX Make implementation                                                                           | gmake                                                                                               | bmake, [kati](<https://github.com/google/kati>)                                                     |
| Ninja build implementation                                                                          | ninja                                                                                               | [samurai](<https://github.com/michaelforney/samurai>)                                               |
| POSIX M4 implementation                                                                             | GNU M4                                                                                              | OpenBSD M4                                                                                          |
| X/Open Curses implementation                                                                        | ncurses                                                                                             | [netbsd-curses](<https://github.com/sabotage-linux/netbsd-curses>)                                  |
| Shell                                                                                               | bash                                                                                                | mksh, [oksh](</https://github.com/ibara/oksh> "oksh")                                               |
| Pluggable Authentication Modules                                                                    | Linux PAM                                                                                           | Open PAM                                                                                            |
| Privilege escalation                                                                                | sudo                                                                                                | doas                                                                                                |
| Package configuration tool                                                                          | pkg-config                                                                                          | pkgconf                                                                                             |
| Make an ext4 file system                                                                            | e2fsprogs                                                                                           | make\_ext4fs                                                                                        |
| Manual                                                                                              | man-db                                                                                              | mandoc                                                                                              |
| Job Scheduling                                                                                      | Cron                                                                                                | [Snooze ](<https://github.com/leahneukirchen/snooze>)[dcron](<https://github.com/ptchinster/dcron>) |
| Device handling, firmware loading                                                                   | systemd-udev, udevd                                                                                 | mdevd, [libudev-zero](<https://github.com/illiliti/libudev-zero>)                                   |
| Generic shared library support script                                                               | libtool                                                                                             | [slibtool](<https://github.com/midipix-project/slibtool>)                                           |
| A tool for generating text-scanning programs                                                        | lex                                                                                                 | [flex](<https://github.com/westes/flex>)                                                            |
| Build system                                                                                        | Meson                                                                                               | [Muon](<https://muon.build/>)                                                                       |
| initrd builder                                                                                      | dracut                                                                                              | [booster](<https://github.com/anatol/booster>)                                                      |
| bootloader                                                                                          | GRUB                                                                                                | [limine ](<https://limine-bootloader.org/>)[yaub](<https://github.com/kukrimate/yaub/>)             |
| awk implementation                                                                                  | gawk                                                                                                | [mawk](<https://invisible-island.net/mawk/>),

[one true awk ](<https://github.com/onetrueawk/awk>) |
| Loginng system                                                                                      |                                                                                                     | [sysklogd](<https://github.com/troglobit/sysklogd>)                                                 |
|                                                                                                     |                                                                                                     | [gettext-tiny](<https://github.com/sabotage-linux/gettext-tiny>)                                    |

# Tools
## Inits

1. [Finit](https://github.com/troglobit/finit)
2. [Nitro](https://github.com/leahneukirchen/nitro)
3. [Runit](https://github.com/g-pape/runit/)
4. [Shinit](https://github.com/cemkeylan/shinit)
   

## Notifications

1. [Herbe](https://github.com/dudik/herbe)
2. [tiramisu](https://github.com/Sweets/tiramisu)

## Window managers for X11

1. [DWM](https://dwm.suckless.org/)
2. [sowm](https://github.com/dylanaraps/sowm)

## Wayland compositors

1. [dwc](https://git.sr.ht/~corg/DWC) - dynamic
2. [hevel](https://git.sr.ht/~dlm/hevel) - floating, scrollable
3. [howl](https://git.sr.ht/~wf/howl) - tiling
4. [klatka](https://git.sr.ht/~dlm/klatka) - kiosk-style
5. [neuwm](https://git.sr.ht/~pfr/neuwm) - floating
6. [slgro](https://git.ouppyawa.xyz/0uppy/slgro/) - floating, keyboard-driven
7. [tohu](https://git.sr.ht/~shrub900/tohu) - floating
8. [wsxwm](https://git.sr.ht/~uint/wsxwm) - tiling

## Other tools

| Function | Often use realization | Suckless realization | 
| --- | --- | --- |
| Standard C library | glibc | musl | 
| Backtrace functions | glibc | libexecinfo | 
| C++ standard library | libstdc++ | libc++ | 
| Stack unwinding | libgcc | libunwind | 
| Compiler builtins | libgcc | compiler-rt | 
| POSIX yacc | bison | [byacc](https://invisible-island.net/byacc/) | 
| POSIX utilities | GNU coreutils | [Toybox](https://github.com/landley/toybox), [Busybox](https://www.busybox.net/),  [Chimerautils](https://github.com/chimera-linux/chimerautils), [plan9port](https://github.com/9fans/plan9port) | 
| C/C++ compiler | gcc | [qbe](https://c9x.me/compile/) | 
| Compression library | zlib | [miniz](https://github.com/richgel999/miniz), [zlib-ng](https://github.com/zlib-ng/zlib-ng) | 
| POSIX Make implementation | gmake | [bmake](https://www.crufty.net/help/sjg/bmake.html),[shinobi](https://srcdump.net/shrub/shinobi/) | 
| Ninja build implementation | ninja | [samurai](https://github.com/michaelforney/samurai) | 
| M4 macroprocessor | GNU M4 | [OpenBSD M4](https://github.com/iglunix/om4) | 
| Curses implementation | ncurses | [netbsd-curses](https://github.com/sabotage-linux/netbsd-curses) | 
| Shell | bash | [mksh](https://github.com/MirBSD/mksh), [oksh](https://github.com/ibara/oksh), [yash](https://github.com/magicant/yash) | 
| Pluggable Authentication Modules | Linux PAM | [OpenPAM](https://git.des.dev/OpenPAM/OpenPAM) | 
| Privilege escalation | sudo | [OpenDoas](https://github.com/Duncaen/OpenDoas), [doas](https://codeberg.org/thejessesmith/doas), [ssu](https://github.com/illiliti/ssu) |
| Package configuration tool | pkg-config | [librarian](https://codeberg.org/maandree/librarian), [pkgconf](https://github.com/pkgconf/pkgconf), [u-config](https://github.com/skeeto/u-config) | 
| Make an ext4 file system | e2fsprogs | [make_ext4fs](https://github.com/iglunix/make_ext4fs) | 
| Manual | man-db | [mandoc](https://mandoc.bsd.lv/) | 
| Job Scheduling | Cron | [Snooze](https://github.com/leahneukirchen/snooze), [dcron](https://github.com/ptchinster/dcron) |
| Device handling, firmware loading | systemd-udev, udevd | [mdevd](https://github.com/skarnet/mdevd), [libudev-zero](https://github.com/illiliti/libudev-zero) | 
| Generic shared library support script | libtool | [slibtool](https://github.com/midipix-project/slibtool) | 
| A tool for generating text-scanning programs | lex | [flex](https://github.com/westes/flex), [reflex](https://invisible-island.net/reflex/) |
| Build system | Meson | [Muon](https://muon.build/) | 
| initrd builder | dracut | [booster](https://github.com/anatol/booster), [Tinyramfs](https://github.com/illiliti/tinyramfs) |
| bootloader | GRUB | [limine](https://limine-bootloader.org/), [oslo](https://github.com/iglunix/oslo), [yaub](https://github.com/kukrimate/yaub/) |
| awk implementation | gawk | [mawk](https://invisible-island.net/mawk/), [one true awk](https://github.com/onetrueawk/awk), [wak](https://github.com/raygard/wak) |
| Loginng system | systemd-journald | [sysklogd](https://github.com/troglobit/sysklogd) |
| Internationalization system | GNU gettext | [gettext-tiny](https://github.com/sabotage-linux/gettext-tiny) | 

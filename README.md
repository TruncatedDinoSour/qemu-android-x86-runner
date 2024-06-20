# This repository has been migrated to the self-hosted ari-web Forgejo instance: <https://git.ari.lt/ari/qemu-android-x86-runner>
# Quick Start

- Install [QEMU]
- Download `android-x86_64-7.1-r1.iso` from http://www.android-x86.org/download
- `$ ./qemu-install.sh ./android-x86_64-7.1-r1.iso ./android.img`
- `$ ./qemu-run.sh ./android.img`
- `$ ./qemu-run.sh ./android.img -vnc localhost:0` -- run with VNC listener on for local incoming connections on 5900 port

No root permissions should be required for running any of the scripts. If this is not true in some cases, please submit a fix with a Pull Request.

[QEMU]: https://www.qemu.org/

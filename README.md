# Build Rust Binary with Github Actions

Using Github Actions to Build a binary for as many platforms as possible.

Here are the platforms that this Github Action builds for: ~44.

## Tier 1

| Target                    | Compiles? | std | Notes |
| ------------------------- | --------- | --- | ----- |
| aarch64-unknown-linux-gnu | ✅        | ✅  |       |
| i686-pc-windows-gnu       | ✅        | ✅  |       |
| i686-unknown-linux-gnu    | ✅        | ✅  |       |
| i686-pc-windows-msvc      | ✅        | ✅  |       |
| x86_64-apple-darwin       | ✅        | ✅  |       |
| x86_64-pc-windows-gnu     | ✅        | ✅  |       |
| x86_64-pc-windows-msvc    | ✅        | ✅  |       |
| x86_64-unknown-linux-gnu  | ✅        | ✅  |       |

## Tier 2 with Host Tools

| Target                          | Compiles? | std | Notes |
| ------------------------------- | --------- | --- | ----- |
| aarch64-apple-darwin            | ✅        | ✅  |       |
| aarch64-pc-windows-msvc         | ✅        | ✅  |       |
| aarch64-unknown-linux-musl      | ✅        | ✅  |       |
| arm-unknown-linux-gnueabi       | ✅        | ✅  |       |
| arm-unknown-linux-gnueabihf     | ✅        | ✅  |       |
| armv7-unknown-linux-gnueabihf   | ✅        | ✅  |       |
| mips-unknown-linux-gnu          | ✅        | ✅  |       |
| mips64-unknown-linux-gnuabi64   | ✅        | ✅  |       |
| mips64el-unknown-linux-gnuabi64 | ✅        | ✅  |       |
| mipsel-unknown-linux-gnuabi     | ✅        | ✅  |       |
| powerpc-unknown-linux-gnu       | ✅        | ✅  |       |
| powerpc64-unknown-linux-gnu     | ✅        | ✅  |       |
| powerpc64le-unknown-linux-gnu   | ✅        | ✅  |       |
| riscv64gc-unknown-linux-gnu     | ✅        | ✅  |       |
| s390x-unknown-linux-gnu         | ✅        | ✅  |       |
| x86_64-unknown-freebsd          | ✅        | ✅  |       |
| x86_64-unknown-illumos          | ✅        | ✅  |       |
| arm-unknown-linux-musleabihf    | ✅        | ✅  |       |
| i686-unknown-linux-musl         | ✅        | ✅  |       |
| x86_64-unknown-linux-musl       | ✅        | ✅  |       |
| x86_64-unknown-netbsd           | ✅        | ✅  |       |

## Tier 2

| Target                              | Compiles? | std | Notes           |
| ----------------------------------- | --------- | --- | --------------- |
| aarch64-apple-ios                   | ✅        | ✅  |                 |
| aarch64-apple-ios-sim               | ✅        | ✅  |                 |
| aarch64-fuchsia                     | ❓        | ✅  |                 |
| aarch64-linux-android               | ❓        | ✅  |                 |
| aarch64-unknown-none-softfloat      | ❓        | ❌  |                 |
| aarch64-unknown-none                | ❓        | ❌  |                 |
| arm-linux-androideabi               | ❓        | ✅  |                 |
| arm-unknown-linux-musleabi          | ✅        | ✅  |                 |
| arm-unknown-linux-musleabihf        | ✅        | ✅  |                 |
| armebv7r-none-eabi                  | ❓        | ❌  |                 |
| armebv7r-none-eabihf                | ❓        | ❌  |                 |
| armv5te-unknown-linux-gnueabi       | ❓        | ✅  |                 |
| armv5te-unknown-linux-musleabi      | ❓        | ✅  |                 |
| armv7-linux-androideabi             | ❓        | ✅  |                 |
| armv7-unknown-linux-gnueabi         | ❓        | ✅  |                 |
| armv7-unknown-linux-musleabi        | ❓        | ✅  |                 |
| armv7-unknown-linux-musleabihf      | ❓        | ✅  |                 |
| armv7a-none-eabi                    | ❓        | ❌  |                 |
| armv7r-none-eabi                    | ❓        | ❌  |                 |
| armv7r-none-eabihf                  | ❓        | ❌  |                 |
| armv5te-unknown-linux-gnueabi       | ❓        | ✅  |                 |
| armv5te-unknown-linux-musleabi      | ❓        | ✅  |                 |
| armv7-linux-androideabi             | ❓        | ✅  |                 |
| armv7-unknown-linux-gnueabi         | ❓        | ✅  |                 |
| armv7-unknown-linux-musleabi        | ❓        | ✅  |                 |
| armv7-unknown-linux-musleabihf      | ✅        | ✅  |                 |
| armv7a-none-eabi                    | ❓        | ✅  |                 |
| armv7a-none-eabihf                  | ❓        | ✅  |                 |
| asmjs-unknown-emscripten            | ❓        | ✅  |                 |
| i586-pc-windows-msvc                | ❓        | ✅  |                 |
| i586-unknown-linux-gnu              | ❓        | ✅  |                 |
| i586-unknown-linux-musl             | ❓        | ✅  |                 |
| i686-linux-android                  | ❓        | ✅  |                 |
| i686-unknown-freebsd                | ❓        | ✅  |                 |
| i686-unknown-linux-musl             | ❓        | ✅  |                 |
| mips-unknown-linux-musl             | ❓        | ✅  |                 |
| mips64-unknown-linux-muslabi64      | ❓        | ✅  |                 |
| mips64el-unknown-linux-muslabi64    | ❓        | ✅  |                 |
| nvptx64-nvidia-cuda                 | ❓        | ❌  | --emit=asm only |
| riscv32i-unknown-none-elf           | ❓        | ❌  |                 |
| riscv32imac-unknown-none-elf        | ❓        | ❌  |                 |
| riscv32imc-unknown-none-elf         | ❓        | ❌  |                 |
| riscv64gc-unknown-none-elf          | ❓        | ❌  |                 |
| riscv64imac-unknown-none-elf        | ❓        | ❌  |                 |
| sparc64-unknown-linux-gnu           | ❓        | ✅  |                 |
| sparcv9-sun-solaris                 | ❓        | ✅  |                 |
| thumbv6m-none-eabi                  | ❓        | ❌  |                 |
| thumbv7em-none-eabi                 | ❓        | ❌  |                 |
| thumbv7em-none-eabihf               | ❓        | ❌  |                 |
| thumbv7m-none-eabi                  | ❓        | ❌  |                 |
| thumbv7neon-linux-androideabi       | ❓        | ✅  |                 |
| thumbv7neon-unknown-linux-gnueabihf | ❓        | ✅  |                 |
| thumbv8m.base-none-eabi             | ❓        | ❌  |                 |
| thumbv8m.main-none-eabi             | ❓        | ❌  |                 |
| thumbv8m.main-none-eabihf           | ❓        | ❌  |                 |
| wasm32-unknown-emscripten           | ❓        | ✅  |                 |
| wasm32-unknown-unknown              | ❓        | ✅  |                 |
| wasm32-wasi                         | ❓        | ✅  |                 |
| x86_64-apple-ios                    | ❓        | ✅  |                 |
| x86_64-fortanix-unknown-sgx         | ❓        | ✅  |                 |
| x86_64-fuchsia                      | ❓        | ✅  |                 |
| x86_64-linux-android                | ❓        | ✅  |                 |
| x86_64-pc-solaris                   | ❓        | ✅  |                 |
| x86_64-unknown-linux-gnux32         | ❓        | ✅  |                 |
| x86_64-unknown-redox                | ❓        | ✅  |                 |

## Tier 3

| target                               | Compiles? | std | notes |
| ------------------------------------ | --------- | --- | ----- |
| aarch64-apple-ios-macabi             | ❓        | ❓  |       |
| aarch64-apple-tvos                   | ❓        | ❌  |       |
| aarch64-unknown-freebsd              | ❓        | ✅  |       |
| aarch64-unknown-hermit               | ❓        | ❓  |       |
| aarch64-unknown-uefi                 | ❓        | ❌  |       |
| aarch64-unknown-linux-gnu_ilp32      | ❓        | ✅  |       |
| aarch64-unknown-netbsd               | ❓        | ✅  |       |
| aarch64-unknown-openbsd              | ❓        | ✅  |       |
| aarch64-unknown-redox                | ❓        | ❓  |       |
| aarch64-uwp-windows-msvc             | ❓        | ❓  |       |
| aarch64-wrs-vxworks                  | ❓        | ❓  |       |
| aarch64_be-unknown-linux-gnu_ilp32   | ❓        | ✅  |       |
| aarch64_be-unknown-linux-gnu         | ❓        | ✅  |       |
| armv4t-unknown-linux-gnueabi         | ❓        | ❓  |       |
| armv5te-unknown-linux-uclibceabi     | ❓        | ❓  |       |
| armv6-unknown-freebsd                | ❓        | ✅  |       |
| armv6-unknown-netbsd-eabihf          | ❓        | ❓  |       |
| armv7-apple-ios                      | ❓        | ✅  |       |
| armv7-unknown-freebsd                | ❓        | ✅  |       |
| armv7-unknown-netbsd-eabihf          | ❓        | ✅  |       |
| armv7-wrs-vxworks-eabihf             | ❓        | ❓  |       |
| armv7a-none-eabihf                   | ❓        | ❌  |       |
| armv7s-apple-ios                     | ❓        | ✅  |       |
| avr-unknown-gnu-atmega328            | ❓        | ❌  |       |
| bpfeb-unknown-none                   | ❓        | ❌  |       |
| bpfel-unknown-none                   | ❓        | ❌  |       |
| hexagon-unknown-linux-musl           | ❓        | ❓  |       |
| i386-apple-ios                       | ❓        | ✅  |       |
| i686-apple-darwin                    | ❓        | ✅  |       |
| i686-pc-windows-msvc                 | ❓        | ✅  |       |
| i686-unknown-haiku                   | ❓        | ✅  |       |
| i686-unknown-netbsd                  | ❓        | ✅  |       |
| i686-unknown-openbsd                 | ❓        | ✅  |       |
| i686-unknown-uefi                    | ❓        | ❌  |       |
| i686-uwp-windows-gnu                 | ❓        | ❓  |       |
| i686-uwp-windows-msvc                | ❓        | ❓  |       |
| i686-wrs-vxworks                     | ❓        | ❓  |       |
| mips-unknown-linux-uclibc            | ❓        | ✅  |       |
| mipsel-sony-psp                      | ❓        | ❌  |       |
| mipsel-unknown-linux-uclibc          | ❓        | ✅  |       |
| mipsel-unknown-none                  | ❓        | ❌  |       |
| mipsisa32r6-unknown-linux-gnu        | ❓        | ❓  |       |
| mipsisa32r6el-unknown-linux-gnu      | ❓        | ❓  |       |
| mipsisa64r6-unknown-linux-gnuabi64   | ❓        | ❓  |       |
| mipsisa64r6el-unknown-linux-gnuabi64 | ❓        | ❓  |       |
| msp430-none-elf                      | ❓        | ❌  |       |
| powerpc-unknown-linux-gnuspe         | ❓        | ✅  |       |
| powerpc-unknown-linux-musl           | ❓        | ❓  |       |
| powerpc-unknown-netbsd               | ❓        | ✅  |       |
| powerpc-unknown-openbsd              | ❓        | ❓  |       |
| powerpc-wrs-vxworks-spe              | ❓        | ❓  |       |
| powerpc-wrs-vxworks                  | ❓        | ❓  |       |
| powerpc64-unknown-freebsd            | ❓        | ✅  |       |
| powerpc64le-unknown-freebsd          | ❓        |     |       |
| powerpc-unknown-freebsd              | ❓        |     |       |
| powerpc64-unknown-linux-musl         | ❓        | ❓  |       |
| powerpc64-wrs-vxworks                | ❓        | ❓  |       |
| powerpc64le-unknown-linux-musl       | ❓        | ❓  |       |
| riscv32gc-unknown-linux-gnu          | ❓        |     |       |
| riscv32gc-unknown-linux-musl         | ❓        |     |       |
| riscv32imc-esp-espidf                | ❓        | ✅  |       |
| riscv64gc-unknown-linux-musl         | ❓        |     |       |
| s390x-unknown-linux-musl             | ❓        |     |       |
| sparc-unknown-linux-gnu              | ❓        | ✅  |       |
| sparc64-unknown-netbsd               | ❓        | ✅  |       |
| sparc64-unknown-openbsd              | ❓        | ❓  |       |
| thumbv4t-none-eabi                   | ❓        | ❌  |       |
| thumbv7a-pc-windows-msvc             | ❓        | ❓  |       |
| thumbv7a-uwp-windows-msvc            | ❓        | ✅  |       |
| thumbv7neon-unknown-linux-musleabihf | ❓        | ❓  |       |
| wasm64-unknown-unknown               | ❓        | ❌  |       |
| x86_64-apple-ios-macabi              | ❓        | ✅  |       |
| x86_64-apple-tvos                    | ❓        | ❌  |       |
| x86_64-pc-windows-msvc               | ❓        | ✅  |       |
| x86_64-sun-solaris                   | ❓        | ❓  |       |
| x86_64-unknown-dragonfly             | ❓        | ✅  |       |
| x86_64-unknown-haiku                 | ❓        | ✅  |       |
| x86_64-unknown-hermit                | ❓        | ❓  |       |
| x86_64-unknown-l4re-uclibc           | ❓        | ❓  |       |
| x86_64-unknown-none-hermitkernel     | ❓        | ❓  |       |
| x86_64-unknown-none-linuxkernel      | ❓        | ❌  |       |
| x86_64-unknown-openbsd               | ❓        | ✅  |       |
| x86_64-unknown-uefi                  | ❓        | ❌  |       |
| x86_64-uwp-windows-gnu               | ❓        | ✅  |       |
| x86_64-uwp-windows-msvc              | ❓        | ✅  |       |
| x86_64-wrs-vxworks                   | ❓        | ❓  |       |

## License

Licensed under either of Apache License, Version 2.0 or MIT license at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.

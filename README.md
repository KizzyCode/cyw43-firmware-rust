[![AppVeyor CI](https://ci.appveyor.com/api/projects/status/github/KizzyCode/cyw43-firmware-rust?svg=true)](https://ci.appveyor.com/project/KizzyCode/cyw43-firmware-rust)
[![docs.rs](https://docs.rs/cyw43-firmware/badge.svg)](https://docs.rs/cyw43-firmware)
[![crates.io](https://img.shields.io/crates/v/cyw43-firmware.svg)](https://crates.io/crates/cyw43-firmware)
[![Download numbers](https://img.shields.io/crates/d/cyw43-firmware.svg)](https://crates.io/crates/cyw43-firmware)
[![dependency status](https://deps.rs/crate/cyw43-firmware/latest/status.svg)](https://deps.rs/crate/cyw43-firmware)


# CYW43xx WiFi and Bluetooth Firmware Blobs
This crate wraps firmare binaries/blobs for the CYW43xx WiFi/BT SoC.

The firmware binaries/blobs within [dist/cyw32-firmware](./dist/cyw32-firmware) are included as git-submodule from
<https://github.com/embassy-rs/embassy.git>. 

Those blobs have been taken from <https://github.com/georgerobotics/cyw43-driver/tree/main/firmware>, where you can find
further information about the licensing.


## License
The cyw43-firmware binaries/blobs are free only for non-commercial use (see
[Non-Commercial License](#non-commercial-license)). The cyw43-firmware binaries/blobs are also available for use with
Raspberry Pi Ltd semiconductor devices under different terms (see [Raspberry Pi License](#raspberry-pi-license)). See
also <https://github.com/georgerobotics/cyw43-driver/tree/main/firmware>.

The Rust-wrapper is licensed under [Unlicense](https://opensource.org/license/unlicense). 


### Non-Commercial License
```txt
Copyright (C) 2019-2022 George Robotics Pty Ltd

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.
3. Any redistribution, use, or modification in source or binary form is done
   solely for personal benefit and not for any commercial purpose or for
   monetary gain.

THIS SOFTWARE IS PROVIDED BY THE LICENSOR AND COPYRIGHT OWNER "AS IS" AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE LICENSOR OR COPYRIGHT OWNER BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

This software is also available for use with Raspberry Pi Ltd semiconductor
devices under different terms (see Raspberry Pi License).

For commercial licensing options please email contact@georgerobotics.com.au
```


### Raspberry Pi License
```txt
Copyright (C) 2019-2022 George Robotics Pty Ltd

Raspberry Pi Ltd (Licensor) hereby grants to you a non-exclusive license to
use this software solely with the Licensor's microcontroller chip (RP2040) or
any other semiconductor device produced by the Licensor. No other use is
permitted under the terms of this licence.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. The software can only be used and redistributed in conjunction with RP2040
   or any other semiconductor device produced by the Licensor.
2. Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.
3. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE LICENSOR AND COPYRIGHT OWNER "AS IS" AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE LICENSOR OR COPYRIGHT OWNER BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

This software is also available from the copyright owner under different
terms (see Non-Commercial License)
```

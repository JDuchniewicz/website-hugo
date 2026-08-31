+++
title = "Projects"
description = "Selected systems and projects"
+++

## Featured systems

{{< project id="pill-engine" meta="current · Rust · ECS · game tooling" title="Pill Engine" >}}
Rust game-engine project focused on ECS, architecture, scripting experiments, hot reloading and making weird games easier to build.

`Rust` `ECS` `C#` `FFI` `Hot reload`

[GitHub](https://github.com/MattSzymonski/Pill-Engine) · [Older engine work](#polyengine)
{{< /project >}}

{{< project id="zled-frame" meta="2024 · Zephyr · ESP32" title="ZLED Frame" image="/about_res/zephyr.jpeg" alt="ZLED Frame / Zephyr" >}}
Wi-Fi controlled NeoPixel art frame with CAD/enclosure work, ESP32 firmware, Zephyr drivers and HTTP image upload.

`C` `Zephyr` `ESP32` `Wi-Fi` `3D printing`

[Part 1]({{< relref "/posts/20-01-24-zled-frame-part1.md" >}}) · [Part 2]({{< relref "/posts/27-03-24-zled-frame-part2.md" >}}) · [GitHub](https://github.com/JDuchniewicz/zled-frame)
{{< /project >}}

{{< project id="bibop" meta="2021–2023 · embedded ML" title="BIBoP" image="/bibop/case.png" alt="BIBoP wearable casing render" >}}
Open hardware wearable health-monitor prototype with Blood Pressure inference from photoplethysmography sensor data.

`Zephyr` `Embedded ML` `Wearables` `Open hardware`

[Intro post]({{< relref "/posts/31-05-21-bibop_1_Intro_ML.md" >}}) · [EOSS post]({{< relref "/posts/10-07-23-eoss.md" >}})
{{< /project >}}

{{< project id="fpga-accelerated-tcpdump" meta="research · FPGA · Linux" title="FPGA accelerated tcpdump using eBPF" >}}
MSc thesis project on hardware acceleration of packet capture in embedded Linux using FPGA programmable logic.

`FPGA` `Linux` `eBPF` `Networking` `Buildroot`

[Thesis note]({{< relref "/posts/18-10-20-first-thesis-released.md" >}}) · [PDF](/FPGA-capture.pdf) · [Talk](/talks/#state-of-open-con)
{{< /project >}}

## Archive / smaller things

{{< project id="game-jams" class="jk-project-card--compact" meta="2025–now" title="Game jams / Sticky Piston Studios" >}}
Being a hardcore **gamejammer**, I am familiar with **Unity**, custom game engines and other popular tools of the trade.

[Tiny Trucks](https://hist0r.itch.io/tiny-trucks) · [The Deluge](https://hist0r.itch.io/the-deluge)
{{< /project >}}

{{< project id="rust-raytracer" class="jk-project-card--compact" meta="2021" title="C++ to Rust - or how to render your mindset" >}}
I will reimplement the amazing tutorial on *Ray Tracing in One Weekend* in the Rust programming language.

[Read post]({{< relref "/posts/26-02-21-cpp-to-rust.md" >}})
{{< /project >}}

{{< project id="rustalizer" class="jk-project-card--compact" meta="2020–2021" title="Rustalizer" >}}
{{< /project >}}

{{< project id="polyengine" class="jk-project-card--compact" meta="older" title="PolyEngine" >}}
[GitHub](https://github.com/PolyEngineTeam/PolyEngine/)
{{< /project >}}

{{< project id="beagleboard-gsoc" class="jk-project-card--compact" meta="2021" title="GSoC beagleboard.org — GPGPU using OpenGL ES" >}}
GPGPU computing with BBB.

[GitHub](https://github.com/JDuchniewicz/GPGPU-with-GLES)
{{< /project >}}

{{< project id="envidrawer" class="jk-project-card--compact" meta="older" title="Envidrawer" >}}
A sustainable closed-space smart gardening solution.
{{< /project >}}

## Thesis abstracts

### FPGA accelerated tcpdump using eBPF

With the rise of the Internet of Things and the proliferation of embedded devices equipped with an accelerator arose a need for efficient resource utilization. Hardware acceleration is a complex topic that requires specialized domain knowledge about the platform and different trade-offs that have to be made, especially in the area of power consumption.

The thesis focuses on accelerating networking packets utilizing a Field Programmable Gate Array in an embedded Linux System. The solution is based on a custom Linux distribution assembled using the Buildroot tool, specially configured and patched Linux kernel, uboot bootloader, and the programmable logic for packet acceleration.

**Keywords:** Field Programmable Gate Array, Acceleration, Networking, Embedded Linux

[PDF: FPGA accelerated tcpdump using eBPF](/FPGA-capture.pdf)

### FPGA based hardware accelerator for musical synthesis for Linux system

Work focuses on realizing an audio synthesizer in a System on Chip, utilizing FPGA hardware resources. It covers aspects of sound synthesis in hardware and writing Linux Device Drivers for communicating with the FPGA utilizing DMA.

An optimal approach to synthesis is researched and assessed and LUT-based interpolation is asserted as the best choice for this project. A novel State Variable IIR Filter is implemented in Verilog and utilized.

**Keywords:** FPGA, Sound Synthesis, SoC, DMA, SVF

[PDF: FPGA based hardware accelerator for musical synthesis for Linux system](/FPGA-synth.pdf)

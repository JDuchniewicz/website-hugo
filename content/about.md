+++
title = "About Me"
date = "2020-04-30"
[ author ]
  name = "Jakub Duchniewicz"
+++

## [Hello there!](https://www.youtube.com/watch?v=rEq1Z0bjdwc)
{{< image src="/me2_resized.jpg" alt="Picture of me!" position="center" style="border-radius: 8px" >}}

My name is **Jakub Duchniewicz** and this is my personal space :) \
I am currently working as a programmer at **[Tietoevry]** doing 5G NR L1 development from the Modem UE side on a custom ASIC for an **Unspecified Client**. Also, I am a co-founder of **[Sticky Piston Studios]** - a jack-of-all-trades company where **we make any advanced tech tick**!

My skills include low-level programming in **C**, **C++** and **Rust**. Being proficient in hardware accelerators, such as **FPGA**s I happen to know some **VHDL** and **SystemVerilog**. Lastly, being a hardcore **gamejammer** I am familiar with the **Unity** engine and other popular tools of the trade.
In my free time I am doing a ton of **bouldering**, learning **hardware hacking**, some **reverse engineering** and taking care of my cute humongous German Shepherd **Bruno**

I have recently graduated with an MSc in **Embedded Systems** at **KTH Royal Institute of Technology**, Sweden and **University of Turku**, Finland as a part of EIT Digital Programme. Thesis titled: *"FPGA accelerated tcpdump using eBPF"* goes into the topic of hardware acceleration of packet capturing in embedded Linux system using an FPGA. It was a cooperative effort between KTH and [Tietoevry].

I have also graduated from **Warsaw University of Technology** with the highest degree for my thesis: *"FPGA based hardware accelerator for musical synthesis for Linux system"*.

You can see both theses under the *Achievements* section below.

**Social [links] 🗡️:** \
 - [CV] \
 - [GitHub] \
 - [LinkedIn] \
:coffee: - [Sponsor :)]

## What's in here?
---
On this website you can find some thoughts of mine on several topics ranging from:

* Microcontrollers and FPGA's
* Machine Learning
* Linux and other OS's topics
* Systems Programming
* Game Engines
* Game Development
* Lifestyle and travelling :water_wave:
* Keeb stuff - HHKB2 Workman user here :muscle:

Please feel free to reach out to me, or leave a comment, I am always eager to have a chat or give a helping hand!
*Also, if you like what I do and you want more content, feel free to buy me a [coffee] :coffee:*

## Achievements
---
### Hackaday Supercon
{{< image src="/Hackadaysupercon_logo.jpg" alt="Hackaday Supercon" position="center" style="border-radius: 8px;" >}}

This is the second time we spoke on the topic of *[Porting an AI Powered Wearable Health Monitor to Zephyr on Open Hardware]*. See below for details!

### Embedded Open Source Summit
{{< image src="/EOSS_logo.png" alt="Embedded Open Source Summit 2023" position="center" style="border-radius: 8px;" >}}

Me and **[Szymon Duchniewicz]** spoke at **Embedded Open Source Summit** on the topic of *[Porting an AI Powered Wearable Health Monitor to Zephyr on Open Hardware]*. You may refer to [the video] and [the blog post] for more details. In short we briefly explained the first iteration of our project on non-Zephyr OS (Arduino) and the presented the challenges and shortcomings of that approach. Then showed how we ported the solution to [QuickLogic EOS S3 platform] and ran it on **[Zephyr OS]**. We also commented on how we designed the entire system, including the **Machine Learning** model for Blood Pressure inference (whose breakdown you can see in [this blog post]). The entire presentation featured a plethora of tips regarding porting Zephyr to a new platform (as it turned out the EOS S3 had *really* basic Zephyr support.\
**Skills:** `C`, `Zephyr`, `Machine Learning`, `Hardware acceleration`, `3D printing`

### State of Open Con
{{< image src="/sooc23.png" alt="State of Open Con 23" position="center" style="border-radius: 8px;" >}}

During this presentation, the topic of **hardware acceleration** using **FPGA**s in an **embedded Linux** was covered. Presented was a solution based on a custom **Linux** distribution assembled using the **Buildroot** tool, specially configured and patched **Linux** kernel, **uboot bootloader**, and the **programmable logic** for packet acceleration.

The project was evaluated on a **De0-Nano System on Chip development board** through modifications to burst lengths, packet sizes, and programmable logic clock frequency.
Metrics include packet capturing time, time per packet, and consumed power.
Finally, the results were contrasted with baseline **embedded Linux** packet processing by inspection of a packet’s path through the kernel.

After the presentation, a lengthy discussion arose and interesting future ideas for the project were imagined. It can be viewed [online here].

**Skills:** `C`, `FPGA`, `Linux`, `Networking`, `Hardware acceleration`

### The Deluge
{{< image src="/deluge.png" alt="The Deluge" position="center" style="border-radius: 8px;" >}}

My name is Jakub Duchniewicz and welcome to the **[Sticky Piston Studios]**!

I have been game jamming since 2016 and when in 2019 me and **[Mateusz Szymoński]** have jammed for the first time - **[Eternal Feud]** (a game where you shoot at each other with bleating sheep) was born. Unfortunately in 2020 Covid struck and all on-site jams were canceled.

We came back to on-site jamming in 2022 and in force! After onboarding **[Szymon]** 1 jam earlier, **we were able to win the entire competition of HackYeah 2022!**

**[The Deluge]** was made in **only 24 hours** and is a combination of **FTL**-like map exploration, a deck builder and a real-time strategy battle fighting. We used **DALL-E** for generation of most of the graphics and made the rest on our own. Be sure to check it out on **itch.io**!

**Skills:** `Unity`, `Generative AI`, `C#`, `Game design`

### '21 GSoC beagleboard.org - GPGPU using OpenGL ES on BBBa
{{< image src="/beagle.png" alt="beagleboard.org" position="center" style="border-radius: 8px;" >}}

This project was part of the **Google Summer of Code** initiative under the **[beagleboard.org]** organization. With this library you can accelerate your computations using built-in **SGX GPU** onboard the **Beaglebone Black**.

Motivation for the project was scarcity of heteregenousity on the **BBB** platform which means that most computations were done either on the **CPU** or in the **PRU** or both of them. Meanwhile **GPU** on the **SoC** was laying mostly untouched apart from some rare occasions where rendering was required - **[this is unacceptable]** and [this project aims to change that]!

**Skills:** `C`, `OpenGL ES`, `Hardware acceleration`, `GPGPU`

## Projects
---
### Rustalizer
{{< image src="/playing_tui.gif" alt="Rustalizer" position="center" style="border-radius: 8px" >}}

A simple audio frequency visualizer written in **Rust**. Use it to accompany you in you daily job as a Winamp-style distractor :)
Delivered both as a **GTK** desktop application and as a **console app**.

**Skills:** `Rust`, `GTK`, `Signal processing`

### PolyEngine
{{< image src="/polyengine.png" alt="PolyEngine" position="center" style="border-radius: 8px" >}}

While I was a co-chair of **Student Society [KNTG Polygon]**, I heavily contributed to creation of the **[PolyEngine]** game engine. It was written in the **Entity Component System** programming architectural pattern, effectively realizing **data-oriented programming**. During various gamejams and meetings we created **extensible and professinal engine** that always lacked a functional editor :). If you are interested on picking it up, drop me a line!


**Skills:** `C`, `C++`, `Game Engines`, `CMake`, `Meson`, `Vulkan`

### BIBoP
{{< image src="/bibop/case.png" alt="BIBoP" position="center" style="border-radius: 8px" >}}
*Image courtesy of [Szymon Duchniewicz].*

Basis for the **[EOSS23 talk]** me and [Szymon] are doing in June. A **Machine Learning** model for **Blood Pressure inference** from **photopletysmography** sensor data was deployed by means of **AWS Lambda**. The device used Wi-Fi for communication with the model and obtaining BP prediction data that was displayed on the small LCD screen. It was also powered by a LiPo battery so that it could be worn tetherlessly.

**Skills:** `Embedded IoT`, `Analog electronics`, `Machine Learning`, `MQTT`, `SAMD microcontrollers`, `AWS`

### Envidrawer
{{< image src="/envidrawer.jpg" alt="Envidrawer" position="center" style="border-radius: 8px" >}}
*Image courtesy of [Anna Tatarzyńska].*

Ever wanted to have your own home-garden *under your bed*? No? Thought so... Same here but we decided it would be a cool idea to experiment with some new types of **sensors** and **3D printing**. We also grabbed a **honourable mention** from **element14**, the organisers of this encompassing challenge. [Check it out here!]

**Skills:** `Embedded IoT`, `Analog electronics`, `Woodworking`, `3D printing`
## Academia
---
## MSc Thesis:
### *"FPGA accelerated tcpdump using eBPF"*

[PDF for viewing.]

**Abstract**:
With the rise of the Internet of Things and the proliferation of embedded
devices equipped with an accelerator arose a need for eﬀicient resource
utilization. Hardware acceleration is a complex topic that requires specialized
domain knowledge about the platform and different trade-offs that have to be
made, especially in the area of power consumption. Eﬀicient work offloading
strives to reduce or at least maintain the total power consumption of the
system. Offloading packet capturing is usually done in more powerful devices,
hence scarce research is present concerning network packet acceleration in
embedded devices.
The thesis focuses on accelerating networking packets utilizing a Field
Programmable Gate Array in an embedded Linux System. The solution is
based on a custom Linux distribution assembled using the Buildroot tool,
specially configured and patched Linux kernel, uboot bootloader, and the
programmable logic for packet acceleration. The system is evaluated on
a De0-Nano System on Chip development board through modifications to
burst lengths, packet sizes, and programmable logic clock frequency. Metrics
include packet capturing time, time per packet, and consumed power. Finally,
the results are contrasted with baseline embedded Linux packet processing by
inspection of a packet’s path through the kernel.
Collected results provide a deeper understanding of the packet acceleration
problem in embedded devices and the resultant system gives a solid starting
point for possible extensions such as packet filtering. Key findings include
an improvement in packet processing speed as the clock frequency and burst
length are increased while maintaining power consumption. Additionally,
the solution performs better when the packet sizes are above 64 bytes as the
overhead of additional logic necessary for their processing is compensated.
The project is also found to be significantly faster than regular in kernel
processing with the caveat of providing just packet capturing whereas Linux
contains a full network stack.

**Keywords**: Field Programmable Gate Array, Acceleration, Networking, Embedded Linux

## BSc Thesis:
### *"FPGA based hardware accelerator for musical synthesis for Linux system"*

You can view the .pdf [here].

**Abstract**: Work focuses on realizing audio synthesizer in a System on Chip, utilizing FPGA
hardware resources. The resulting sound can be polyphonic and can be played directly
by an analog connection and is returned to the Hard Processor System running Linux
OS. It covers aspects of sound synthesis in hardware and writing Linux Device Drivers
for communicating with the FPGA utilizing DMA. An optimal approach to synthesis is
researched and assessed and LUT-based interpolation is asserted as the best choice for
this project. A novel State Variable IIR Filter is implemented in Verilog and utilized. Four
waveforms are synthesized: sine, square, sawtooth and triangle, and their switching can
be done instantaneously. A sample mixer capable of spreading the overflowing amplitudes
in phase is implemented. Linux Device Driver conforming to the ALSA standard is written
and utilized as a soundcard capable of generating the sound of 24 bits precision at 96kHz
sampling speed in real time. The system is extended with a simple GPIO analog sound
output through 1 pin Sigma-Delta DAC.

**Keywords**: FPGA, Sound Synthesis, SoC, DMA, SVF

[Tietoevry]: https://www.tietoevry.com/
[PolyEngine]: https://github.com/PolyEngineTeam/PolyEngine/
[Posts]: https://jduchniewicz.com/posts/
[here]: https://jduchniewicz.com/FPGA-synth.pdf
[PDF for viewing.]: https://jduchniewicz.com/FPGA-capture.pdf
[coffee]: https://www.buymeacoffee.com/jduchniewicz
[Szymon Duchniewicz]: https://www.linkedin.com/in/szymon-duch/
[Szymon]: https://www.linkedin.com/in/szymon-duch/
[Porting an AI Powered Wearable Health Monitor to Zephyr on Open Hardware]: https://sched.co/1LcM4
[the video]: https://www.youtube.com/watch?v=fBMeNOOghD4&feature=youtu.be
[EOSS23 talk]: https://sched.co/1LcM4
[QuickLogic EOS S3 platform]: https://www.mouser.pl/new/sparkfun/sparkfun-quicklogic-thing-plus-eos-s3/
[the blog post]: https://jduchniewicz.com/posts/2023/07/embedded-open-source-summit-2023/
[Zephyr OS]: https://www.zephyrproject.org/
[this blog post]: https://jduchniewicz.com/posts/2021/05/bibop-1-intro-and-machine-learning/
[links]: http://i0.kym-cdn.com/photos/images/facebook/001/137/217/88b.png
[Sponsor :)]: https://www.buymeacoffee.com/jduchniewicz
[CV]: https://jduchniewicz.com/cv.pdf
[LinkedIn]: https://www.linkedin.com/in/jduchnie/
[GitHub]: https://github.com/JDuchniewicz
[Check it out here!]: https://community.element14.com/challenges-projects/design-challenges/1-meter-of-pi/b/blog/posts/envidrawer-1---introduction-the-plan-and-materials-preparation
[Anna Tatarzyńska]: https://www.linkedin.com/in/anna-tatarzynska
[KNTG Polygon]: https://www.kntgpolygon.pl/
[online here]: https://youtu.be/YLQPR5Pcb0c
[Mateusz Szymoński]: https://mattszymonski.com/
[The Deluge]: https://hist0r.itch.io/the-deluge
[Eternal Feud]: https://www.youtube.com/watch?v=lx4K-1bRa9k&
[beagleboard.org]: https://beagleboard.org/
[this is unacceptable]: https://www.youtube.com/watch?v=Q-WHRJPlL5g
[this project aims to change that]: https://github.com/JDuchniewicz/GPGPU-with-GLES
[Sticky Piston Studios]: https://stickypistonstudios.com/

+++
title = "About Me"
date = "2020-04-30"
[ author ]
  name = "Jakub Duchniewicz"
+++

## [Hello there!](https://www.youtube.com/watch?v=rEq1Z0bjdwc)
{{< polaroid src="/me2_resized.jpg" alt="Jakub waving" caption="Hi! I’m Jakub 👋" max="280px" >}}

My name is **Jakub Duchniewicz** and this is my personal space :grin:

I am currently working as a programmer at **[Tietoevry]** doing 5G NR L1 development from the Modem UE side on a custom ASIC for an **Unspecified Client**. :grin: I am also a co-founder of **[Sticky Piston Studios]** - a jack-of-all-trades company where **we make any advanced tech tick**!

My skills include low-level programming in **C**, **C++** and **Rust**. Being proficient in hardware accelerators, such as **FPGA**s I happen to know some **Verilog** and **SystemVerilog**. Lastly, being a hardcore **gamejammer** I am familiar with the **Unity** engine and other popular tools of the trade.

In my free time I am doing a ton of **bouldering**, chasing them good waves :wave: and powder days :skiing: and when I am finally so tired I can sit patiently in one place then I have time and energy for learning **hardware hacking** and some **reverse engineering** - preferably in the retro-computing space. I am also a dog-person, although right now because of my travels I do not have a doggo of my own.

I have graduated with an MSc in **Embedded Systems** at **KTH Royal Institute of Technology**, Sweden and **University of Turku**, Finland as a part of EIT Digital Programme. Thesis titled: *"FPGA accelerated tcpdump using eBPF"* goes into the topic of hardware acceleration of packet capturing in embedded Linux system using an FPGA. It was a cooperative effort between KTH and [Tietoevry].

I have also graduated from **Warsaw University of Technology** with the thesis: *"FPGA based hardware accelerator for musical synthesis for Linux system"*.

You can see both below the *Story* section.

**Social [links] 🗡️:** \
 - [CV] \
 - [GitHub] \
 - [LinkedIn] \
:coffee: - [Sponsor :)]

## What’s in here?
---
Short posts & long dives on:

* Zephyr, Linux & other OSes
* MCUs, FPGAs and hardware acceleration
* Game-dev / engine architecture
* Hardware hacking & retro-computing
* Recently a lot on Lifestyle and travelling :ocean:
* Keebs (HHKB-Workman enjoyer :muscle:)
* The odd ML experiment

Please feel free to reach out to me, or leave a comment, I am always eager to have a chat or give a helping hand!
*Also, if you like what I do and you want more content, feel free to buy me a [coffee] :coffee:*

## Story
---
### Slavic Game Jam 2025
{{< image src="/about_res/slavic_logo25.png" alt="Slavic Game Jam 2025" position="center" style="border-radius: 8px;" >}}
**SGJ25** was the fourth time I participated in this Game Jam, this constitutes a tradition! Being something above 15th game jam, I have ever attended - this time I focused mostly on extending the **[Pill Engine]** with networking capabilities using `renet` Rust crate. Because writing proper networking is *hard* the game was created just in the last 6 hours of the gamejam! It is called **[Tiny Trucks]** and is all about drifting your own tiny truck with other players!

**Skills:** `Rust`, `Networking`, `Game Engines`, `Systems optimization`

### Hackaday Supercon 2025
{{< image src="/about_res/Hackaday_logo25.png" alt="Hackaday Supercon 2025" position="center" style="border-radius: 8px;" >}}

A lightning talk on hacking around **[IceBreaker FPGA]** and how me an my friend Krzysztof built a custom signal processing basing on excellent [DOOM on IceBreaker] project. I present some hoops I had to jump through to get a softcore **RISC-V** CPU running on the FPGA and communicating efficiently with the signal processing RTL.

**Skills:** `C`, `RISC-V`, `Verilog`, `Hardware Debugging`

### Embedded Open Source Summit 2024
{{< image src="/about_res/EOSS_logo24.png" alt="EOSS 24" position="center" style="border-radius: 8px;" >}}

**[EOSS24]** was another great opportunity to dig deeper into **Linux kernel** and **[Zephyr OS]** community! I presented about my pet-project **ZLED Frame**. Included in the presentation were: designing a Wi-Fi NeoPixel art frame from CAD to firmware, a walk-through of writing and interacting with Zephyr drivers, handling HTTP communication and 3-D printing traps.

**Skills:** `C`, `Zephyr`, `TCP/IP`, `3D printing`

### FOSDEM 2024
{{< svg path="static/about_res/fosdem_logo.svg" width="30%" height="30%" >}}

At **[FOSDEM]** 2024, I [presented my] and **[Tietoevry]**'s role and experience in revolutionizing the **5G** networks via adoption of **ORAN** or projects that implement it, such as **Intel FlexRAN** that I had pleasure developing. The core message of my talk was the necessity for a *solid open-source foundation at the lowest layer of the telecom industry's processing chain*. I also discussed the importance of opening up the ecosystem in the context of **5G** and shed some light on the intricate structure of the network, especially how the **[L1]** works.
**Skills:** `C`, `5G`, `Radio Networks`, `L1`

### Hackaday Supercon
{{< image src="/about_res/Hackadaysupercon_logo.jpg" alt="Hackaday Supercon" position="center" style="border-radius: 8px;" >}}

This is the second time we spoke on the topic of *[Porting an AI Powered Wearable Health Monitor to Zephyr on Open Hardware]*. See below for details!

### Embedded Open Source Summit
{{< image src="/about_res/EOSS_logo.png" alt="Embedded Open Source Summit 2023" position="center" style="border-radius: 8px;" >}}

Me and **[Szymon Duchniewicz]** spoke at **Embedded Open Source Summit** on the topic of *[Porting an AI Powered Wearable Health Monitor to Zephyr on Open Hardware]*. You may refer to [the video] and [the blog post] for more details. In short we briefly explained the first iteration of our project on non-Zephyr OS (Arduino) and the presented the challenges and shortcomings of that approach. Then showed how we ported the solution to [QuickLogic EOS S3 platform] and ran it on **[Zephyr OS]**. We also commented on how we designed the entire system, including the **Machine Learning** model for Blood Pressure inference (whose breakdown you can see in [this blog post]). The entire presentation featured a plethora of tips regarding porting Zephyr to a new platform (as it turned out the EOS S3 had *really* basic Zephyr support.
**Skills:** `C`, `Zephyr`, `Machine Learning`, `Hardware acceleration`, `3D printing`

### State of Open Con
{{< image src="/about_res/sooc23.png" alt="State of Open Con 23" position="center" style="border-radius: 8px;" >}}

During this presentation, the topic of **hardware acceleration** using **FPGA**s in an **embedded Linux** was covered. Presented was a solution based on a custom **Linux** distribution assembled using the **Buildroot** tool, specially configured and patched **Linux** kernel, **uboot bootloader**, and the **programmable logic** for packet acceleration.

The project was evaluated on a **De0-Nano System on Chip development board** through modifications to burst lengths, packet sizes, and programmable logic clock frequency.
Metrics include packet capturing time, time per packet, and consumed power.
Finally, the results were contrasted with baseline **embedded Linux** packet processing by inspection of a packet’s path through the kernel.

After the presentation, a lengthy discussion arose and interesting future ideas for the project were imagined. It can be viewed [online here].

**Skills:** `C`, `FPGA`, `Linux`, `Networking`, `Hardware acceleration`

### The Deluge
{{< image src="/about_res/deluge.png" alt="The Deluge" position="center" style="border-radius: 8px;" >}}

My name is Jakub Duchniewicz and welcome to the **[Sticky Piston Studios]**!

I have been game jamming since 2016 and when in 2019 me and **[Mateusz Szymoński]** have jammed for the first time - **[Eternal Feud]** (a game where you shoot at each other with bleating sheep) was born. Unfortunately in 2020 Covid struck and all on-site jams were canceled.

We came back to on-site jamming in 2022 and in force! After onboarding **[Szymon]** 1 jam earlier, **we were able to win the entire competition of HackYeah 2022!**

**[The Deluge]** was made in **only 24 hours** and is a combination of **FTL**-like map exploration, a deck builder and a real-time strategy battle fighting. We used **DALL-E** for generation of most of the graphics and made the rest on our own. Be sure to check it out on **itch.io**!

**Skills:** `Unity`, `Generative AI`, `C#`, `Game design`

### '21 GSoC beagleboard.org - GPGPU using OpenGL ES on BBBa
{{< image src="/about_res/beagle.png" alt="beagleboard.org" position="center" style="border-radius: 8px;" >}}

This project was part of the **Google Summer of Code** initiative under the **[beagleboard.org]** organization. With this library you can accelerate your computations using built-in **SGX GPU** onboard the **Beaglebone Black**.

Motivation for the project was scarcity of heteregenousity on the **BBB** platform which means that most computations were done either on the **CPU** or in the **PRU** or both of them. Meanwhile **GPU** on the **SoC** was laying mostly untouched apart from some rare occasions where rendering was required - **[this is unacceptable]** and [this project aims to change that]!

**Skills:** `C`, `OpenGL ES`, `Hardware acceleration`, `GPGPU`

## Projects
---
### ZLED Frame
{{< image src="/about_res/zephyr.jpeg" alt="ZLED frame" position="center" style="border-radius: 8px" >}}

All open-source, open-hardware customized **NeoPixel** LED frame. Designed using **FreeCAD** and programmed using **Zephyr RTOS**. Based on ESP32 microcontroller with Wi-Fi connectivity powered by the [**Zephyr**] RTOS. The frame is capable of displaying various images sent from the companion web-based application. Blogs about its development: [first], [second]
GitHub repo link: [zled-frame]

**Skills:** `C`, `Zephyr`, `Networking`, `FreeCAD`

### Rustalizer
{{< image src="/about_res/playing_tui.gif" alt="Rustalizer" position="center" style="border-radius: 8px" >}}

A simple audio frequency visualizer written in **Rust**. Use it to accompany you in you daily job as a Winamp-style distractor :)
Delivered both as a **GTK** desktop application and as a **console app**.

**Skills:** `Rust`, `GTK`, `Signal processing`

### PolyEngine
{{< image src="/about_res/polyengine.png" alt="PolyEngine" position="center" style="border-radius: 8px" >}}

While I was a co-chair of **Student Society [KNTG Polygon]**, I heavily contributed to creation of the **[PolyEngine]** game engine. It was written in the **Entity Component System** programming architectural pattern, effectively realizing **data-oriented programming**. During various gamejams and meetings we created **extensible and professinal engine** that always lacked a functional editor :). If you are interested on picking it up, drop me a line!


**Skills:** `C`, `C++`, `Game Engines`, `CMake`, `Meson`, `Vulkan`

### BIBoP
{{< image src="/bibop/case.png" alt="BIBoP" position="center" style="border-radius: 8px" >}}
*Image courtesy of [Szymon Duchniewicz].*

Basis for the **[EOSS23 talk]** me and [Szymon] are doing in June. A **Machine Learning** model for **Blood Pressure inference** from **photopletysmography** sensor data was deployed by means of **AWS Lambda**. The device used Wi-Fi for communication with the model and obtaining BP prediction data that was displayed on the small LCD screen. It was also powered by a LiPo battery so that it could be worn tetherlessly.

**Skills:** `Embedded IoT`, `Analog electronics`, `Machine Learning`, `MQTT`, `SAMD microcontrollers`, `AWS`

### Envidrawer
{{< image src="/about_res/envidrawer.jpg" alt="Envidrawer" position="center" style="border-radius: 8px" >}}
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
[presented my]: https://fosdem.org/2024/schedule/event/fosdem-2024-3128-openran-open-source-the-cool-kids-of-telecom-shaking-up-5g-lte-networks/
[FOSDEM]: https://fosdem.org/2024/
[Tietoevry]: https://www.tietoevry.com/
[L1]:https://www.sharetechnote.com/html/5G/5G_RadioProtocolStackArchitecture.html
[first]: https://jduchniewicz.com/posts/2024/01/z-led-frame-or-how-to-illuminate-your-art-with-zephyr-part-1-intro-and-prototyping/
[second]: https://jduchniewicz.com/posts/2024/03/z-led-frame-or-how-to-illuminate-your-art-with-zephyr-part-2-zephyr-leds-and-networking/
[zled-frame]: https://github.com/JDuchniewicz/zled-frame
[EOSS24]: https://eoss24.sched.com/
[Tiny Trucks]: https://hist0r.itch.io/tiny-trucks
[Pill Engine]: https://github.com/MattSzymonski/Pill-Engine
[IceBreaker FPGA]: https://icebreaker-fpga.org/
[DOOM on IceBreaker]: https://github.com/smunaut/ice40-playground

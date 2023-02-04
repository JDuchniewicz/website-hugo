+++
title = "About Me"
date = "2020-04-30"
[ author ]
  name = "Jakub Duchniewicz"
+++

## Hi there!
{{< image src="/me.jpg" alt="Picture of me!" position="center" style="border-radius: 8px;" >}}

My name is Jakub Duchniewicz and this is my personal space :) \
I have recently graduated with an MSc in Embedded Systems at KTH Royal Institute of Technology, Sweden and University of Turku, Finland as a part of EIT Digital Programme. Thesis titled: *"FPGA accelerated tcpdump using eBPF"* goes into the topic of hardware acceleration of packet capturing in embedded Linux system using an FPGA. It was a cooperative effort between KTH and my current employer [Tietoevry]. In my free time I am doing a ton of bouldering, learning hardware hacking, some reverse engineering and taking care of my cute humongous German Shepherd Bruno.

I have also graduated from Warsaw University of Technology with the highest degree for my thesis: *"FPGA based hardware accelerator for musical synthesis for Linux system"*.

There are already several posts dedicated to this topic: [Posts].

Feel free to comment on them, or drop me an email/DM me.

## What's in here?
On this website you can find some thoughts of mine on several topics ranging from:

* Microcontrollers and FPGA's
* Machine Learning
* Linux and other OS's topics
* Systems Programming
* Game Engines
* Game Development
* Lifestyle and travelling :surf:
* Keeb stuff - HHKB2 Workman user here :muscle:

Please feel free to reach out to me, or leave a comment, I am always eager to have a chat or give a helping hand!

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

### Current Interests
Currently I am preparing for State of Open Con 23 :). I am also keenly learning German via podcasts (EasyGerman FTW) and while speaking with a native speaker.

### Past Activities
Lately, I have been digging more into Machine Learning with [fastai], ultimately wanting to deploy my own models on microcontrollers/FPGA's, so expect some content on that soon'ish.

Moreover, I am intensively learning Rust, and I am engaged in development of Error handling guidelines, as well as, stabilizing some features related to it in the Rust language.

I am an active developer of [PolyEngine], and if you would like to join us don't hesitate!
Currently it undergoes some restructurization and implementation of Editor and Vulkan rendering engine (we used OpenGL based one so far), so if you are specialized in either Qt or Vulkan -- we need you! (We welcome you anyway :heart:)

[Tietoevry]: https://www.tietoevry.com/
[PolyEngine]: https://github.com/PolyEngineTeam/PolyEngine/
[Posts]: https://jduchniewicz.com/posts/
[here]: https://jduchniewicz.com/FPGA-synth.pdf
[PDF for viewing.]: https://jduchniewicz.com/FPGA-capture.pdf

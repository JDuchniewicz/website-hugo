+++
title = "CV"
description = "Background, skills, education and selected work"
+++

<div class="jk-cv-hero">
  <div>
    <p class="jk-card-topline">Jakub Duchniewicz</p>
    <h2>Embedded systems / low-level software / telecom / FPGA / Rust / game-engine tinkering.</h2>
    <p>
      I work close to the hardware/software boundary, mostly around embedded systems,
      operating systems, telecom, hardware acceleration and tools that need to be fast,
      debuggable and close to the metal.
    </p>
  </div>

  <div class="jk-cv-actions">
    <a href="/cv.pdf">Download CV PDF</a>
    <a href="https://github.com/JDuchniewicz">GitHub</a>
    <a href="https://www.linkedin.com/in/jduchnie/">LinkedIn</a>
  </div>
</div>

## Current work

I just finished my contract at **[Trustworthy Systems]** at UNSW in Sydney where I was tasked with developing new drivers and components for the **[sDDF]** tooling based on **[seL4]** microkernel. Awaiting new challenges!

I am also a co-founder of **[Sticky Piston Studios]** — a jack-of-all-trades company where **we make any advanced tech tick**.

## Skills

<div class="jk-skill-grid">
  <section class="jk-skill-card">
    <h3>Programming</h3>
    <div class="jk-skill-tags">
      <code>C</code>
      <code>C++</code>
      <code>Rust</code>
      <code>C#</code>
      <code>Python</code>
      <code>Verilog</code>
      <code>SystemVerilog</code>
    </div>
  </section>

  <section class="jk-skill-card">
    <h3>Embedded / systems</h3>
    <div class="jk-skill-tags">
      <code>Linux</code>
      <code>Zephyr</code>
      <code>Buildroot</code>
      <code>U-Boot</code>
      <code>Device drivers</code>
      <code>RTOS</code>
      <code>Hardware debugging</code>
    </div>
  </section>

  <section class="jk-skill-card">
    <h3>Telecom</h3>
    <div class="jk-skill-tags">
      <code>5G</code>
      <code>LTE</code>
      <code>NR L1</code>
      <code>Open RAN</code>
      <code>FlexRAN</code>
      <code>Radio networks</code>
    </div>
  </section>

  <section class="jk-skill-card">
    <h3>Hardware acceleration</h3>
    <div class="jk-skill-tags">
      <code>FPGA</code>
      <code>SoC</code>
      <code>DMA</code>
      <code>Packet processing</code>
      <code>Audio synthesis</code>
    </div>
  </section>

  <section class="jk-skill-card">
    <h3>Game / tooling</h3>
    <div class="jk-skill-tags">
      <code>Unity</code>
      <code>Custom engines</code>
      <code>ECS</code>
      <code>Data-oriented design</code>
      <code>Hot reloading</code>
      <code>Game jams</code>
    </div>
  </section>
</div>

## Education

### MSc in Embedded Systems

I graduated with an MSc in **Embedded Systems** at **KTH Royal Institute of Technology**, Sweden and **University of Turku**, Finland as part of the **EIT Digital Programme**.

My thesis, *“FPGA accelerated tcpdump using eBPF”*, goes into the topic of hardware acceleration of packet capturing in an embedded Linux system using an FPGA. It was a cooperative effort between KTH and [Tietoevry].

PDF: **[FPGA accelerated tcpdump using eBPF][PDF for viewing.]**

### BSc in Computer Science / Electronics

I also graduated from **Warsaw University of Technology** with the thesis: *“FPGA based hardware accelerator for musical synthesis for Linux system”*.

PDF: **[FPGA based hardware accelerator for musical synthesis for Linux system][here]**

## Selected talks

<div class="jk-cv-list">
  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/everything_open26.png" alt="Everything Open 2026" loading="lazy">
    </figure>
    <div>
      <p class="jk-card-topline">2026 · Everything Open</p>
      <h3>Game engines, ECS and hot reloading</h3>
      <p>Talk on <strong><a href="https://github.com/MattSzymonski/Pill-Engine">Pill Engine</a></strong>, <strong><a href="https://github.com/PolyEngineTeam/PolyEngine/">PolyEngine</a></strong> and game engines in general. I covered the differences between <strong>OOP</strong> and <strong>ECS</strong>, why you should write data-oriented code, and how efficient hot-reloading was recently implemented in <strong>Pill Engine</strong>.</p>
      <div class="jk-skill-tags"><code>Rust</code><code>Hot Reloading</code><code>Game Engines</code><code>ECS</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/Hackaday_logo25.png" alt="Hackaday Supercon 2025" loading="lazy">
    </figure>
    <div>
      <p class="jk-card-topline">2025 · Hackaday Supercon</p>
      <h3>RISC-V on iCE40 / FPGA signal processing</h3>
      <p>A lightning talk on hacking around <strong><a href="https://icebreaker-fpga.org/">IceBreaker FPGA</a></strong> and a custom signal-processing path based on the excellent <a href="https://github.com/smunaut/ice40-playground">DOOM on IceBreaker</a> project.</p>
      <div class="jk-skill-tags"><code>C</code><code>RISC-V</code><code>Verilog</code><code>Hardware Debugging</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/EOSS_logo24.png" alt="Embedded Open Source Summit 2024" loading="lazy">
    </figure>
    <div>
      <p class="jk-card-topline">2024 · Embedded Open Source Summit</p>
      <h3>ZLED Frame / Zephyr</h3>
      <p>Presentation about <strong>ZLED Frame</strong>: designing a Wi-Fi NeoPixel art frame from CAD to firmware, writing and interacting with Zephyr drivers, handling HTTP communication and 3-D printing traps.</p>
      <div class="jk-skill-tags"><code>C</code><code>Zephyr</code><code>TCP/IP</code><code>3D printing</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure class="jk-cv-logo">
      <img src="/about_res/fosdem_logo.svg" alt="FOSDEM 2024" loading="lazy">
    </figure>
    <div>
      <p class="jk-card-topline">2024 · FOSDEM</p>
      <h3>Open-source foundations for 5G / Open RAN</h3>
      <p>Talk on open-source foundations for <strong>5G</strong>, <strong>Open RAN</strong>, <strong>Intel FlexRAN</strong> and why the lowest layers of the telecom processing chain need a solid open ecosystem.</p>
      <div class="jk-skill-tags"><code>C</code><code>5G</code><code>Radio Networks</code><code>L1</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/Hackadaysupercon_logo.jpg" alt="Hackaday Supercon 2023" loading="lazy">
    </figure>
    <div>
      <p class="jk-card-topline">2023 · Hackaday Supercon</p>
      <h3>AI wearable health monitor on Zephyr</h3>
      <p>Second public version of the BIBoP/Open Hardware/Zephyr story, with more hardware-hacking and conference context.</p>
      <div class="jk-skill-tags"><code>Zephyr</code><code>Wearables</code><code>ML</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/EOSS_logo.png" alt="Embedded Open Source Summit 2023" loading="lazy">
    </figure>
    <div>
      <p class="jk-card-topline">2023 · Embedded Open Source Summit</p>
      <h3>Porting an AI wearable to Zephyr</h3>
      <p>With <strong><a href="https://www.linkedin.com/in/szymon-duch/">Szymon Duchniewicz</a></strong>, I spoke about <em><a href="https://sched.co/1LcM4">Porting an AI Powered Wearable Health Monitor to Zephyr on Open Hardware</a></em>.</p>
      <div class="jk-skill-tags"><code>C</code><code>Zephyr</code><code>Machine Learning</code><code>Hardware acceleration</code><code>3D printing</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/sooc23.png" alt="State of Open Con 2023" loading="lazy">
    </figure>
    <div>
      <p class="jk-card-topline">2023 · State of Open Con</p>
      <h3>FPGA acceleration in embedded Linux</h3>
      <p>Presentation on <strong>FPGA</strong> hardware acceleration in <strong>embedded Linux</strong>, based on a custom Buildroot distribution, patched Linux kernel, U-Boot bootloader and programmable logic for packet acceleration.</p>
      <div class="jk-skill-tags"><code>C</code><code>FPGA</code><code>Linux</code><code>Networking</code><code>Hardware acceleration</code></div>
    </div>
  </article>
</div>

## Selected projects

<div class="jk-cv-list">
  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/zephyr.jpeg" alt="ZLED Frame" loading="lazy">
    </figure>
    <div>
      <h3>ZLED Frame</h3>
      <p>All open-source, open-hardware customized <strong>NeoPixel</strong> LED frame. Designed using <strong>FreeCAD</strong> and programmed using <strong>Zephyr RTOS</strong>. Based on an ESP32 microcontroller with Wi-Fi connectivity.</p>
      <p>Blogs about its development: <a href="https://jduchniewicz.com/posts/2024/01/z-led-frame-or-how-to-illuminate-your-art-with-zephyr-part-1-intro-and-prototyping/">first</a>, <a href="https://jduchniewicz.com/posts/2024/03/z-led-frame-or-how-to-illuminate-your-art-with-zephyr-part-2-zephyr-leds-and-networking/">second</a><br>GitHub repo: <a href="https://github.com/JDuchniewicz/zled-frame">zled-frame</a></p>
      <div class="jk-skill-tags"><code>C</code><code>Zephyr</code><code>Networking</code><code>FreeCAD</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/pill_logo_horizontal.png" alt="Pill Engine" loading="lazy" onerror="this.closest('figure').remove()">
    </figure>
    <div>
      <h3>Pill Engine</h3>
      <p>A Rust game engine project focused on ECS, engine architecture, scripting experiments, hot reloading and eventually making weird games easier to build.</p>
      <div class="jk-skill-tags"><code>Rust</code><code>Game Engines</code><code>ECS</code><code>Hot Reloading</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/polyengine.png" alt="PolyEngine" loading="lazy">
    </figure>
    <div>
      <h3>PolyEngine</h3>
      <p>While I was a co-chair of Student Society <a href="https://www.kntgpolygon.pl/">KNTG Polygon</a>, I heavily contributed to the creation of <strong><a href="https://github.com/PolyEngineTeam/PolyEngine/">PolyEngine</a></strong>, a game engine written around the <strong>Entity Component System</strong> architectural pattern.</p>
      <div class="jk-skill-tags"><code>C</code><code>C++</code><code>Game Engines</code><code>CMake</code><code>Meson</code><code>Vulkan</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/bibop/case.png" alt="BIBoP" loading="lazy">
    </figure>
    <div>
      <h3>BIBoP</h3>
      <p>Basis for the <a href="https://sched.co/1LcM4">EOSS23 talk</a> me and <a href="https://www.linkedin.com/in/szymon-duch/">Szymon</a> gave. A <strong>Machine Learning</strong> model for <strong>Blood Pressure inference</strong> from photoplethysmography sensor data was deployed through <strong>AWS Lambda</strong>, with the device communicating over Wi-Fi and displaying predictions on a small LCD.</p>
      <div class="jk-skill-tags"><code>Embedded IoT</code><code>Analog electronics</code><code>Machine Learning</code><code>MQTT</code><code>SAMD microcontrollers</code><code>AWS</code></div>
    </div>
  </article>

  <article class="jk-cv-entry">
    <figure>
      <img src="/about_res/playing_tui.gif" alt="Rustalizer" loading="lazy">
    </figure>
    <div>
      <h3>Rustalizer</h3>
      <p>A simple audio frequency visualizer written in <strong>Rust</strong>. Delivered both as a <strong>GTK</strong> desktop application and as a <strong>console app</strong>.</p>
      <div class="jk-skill-tags"><code>Rust</code><code>GTK</code><code>Signal processing</code></div>
    </div>
  </article>
</div>

## Thesis abstracts

### *FPGA accelerated tcpdump using eBPF*

With the rise of the Internet of Things and the proliferation of embedded devices equipped with an accelerator arose a need for efficient resource utilization. Hardware acceleration is a complex topic that requires specialized domain knowledge about the platform and different trade-offs that have to be made, especially in the area of power consumption. Efficient work offloading strives to reduce or at least maintain the total power consumption of the system. Offloading packet capturing is usually done in more powerful devices, hence scarce research is present concerning network packet acceleration in embedded devices.

The thesis focuses on accelerating networking packets utilizing a Field Programmable Gate Array in an embedded Linux System. The solution is based on a custom Linux distribution assembled using the Buildroot tool, specially configured and patched Linux kernel, uboot bootloader, and the programmable logic for packet acceleration. The system is evaluated on a De0-Nano System on Chip development board through modifications to burst lengths, packet sizes, and programmable logic clock frequency. Metrics include packet capturing time, time per packet, and consumed power. Finally, the results are contrasted with baseline embedded Linux packet processing by inspection of a packet’s path through the kernel.

PDF: **[FPGA accelerated tcpdump using eBPF][PDF for viewing.]**

**Keywords:** Field Programmable Gate Array, Acceleration, Networking, Embedded Linux

### *FPGA based hardware accelerator for musical synthesis for Linux system*

Work focuses on realizing audio synthesizer in a System on Chip, utilizing FPGA hardware resources. The resulting sound can be polyphonic and can be played directly by an analog connection and is returned to the Hard Processor System running Linux OS. It covers aspects of sound synthesis in hardware and writing Linux Device Drivers for communicating with the FPGA utilizing DMA.

An optimal approach to synthesis is researched and assessed and LUT-based interpolation is asserted as the best choice for this project. A novel State Variable IIR Filter is implemented in Verilog and utilized. Four waveforms are synthesized: sine, square, sawtooth and triangle, and their switching can be done instantaneously. A sample mixer capable of spreading the overflowing amplitudes in phase is implemented. Linux Device Driver conforming to the ALSA standard is written and utilized as a soundcard capable of generating the sound of 24 bits precision at 96kHz sampling speed in real time.

PDF: **[FPGA based hardware accelerator for musical synthesis for Linux system][here]**

**Keywords:** FPGA, Sound Synthesis, SoC, DMA, SVF

[CV PDF]: https://jduchniewicz.com/cv.pdf
[Tietoevry]: https://www.tietoevry.com/
[Sticky Piston Studios]: https://stickypistonstudios.com/
[here]: https://jduchniewicz.com/FPGA-synth.pdf
[PDF for viewing.]: https://jduchniewicz.com/FPGA-capture.pdf
[Trustworthy Systems]: https://trustworthy.systems/
[seL4]: https://sel4.systems/
[sDDF]: https://github.com/au-ts/sddf

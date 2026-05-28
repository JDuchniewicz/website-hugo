+++
title = "Projects"
description = "A lightweight, chronological-ish index of selected embedded, hardware, Rust and game-tech work. New/current work appears first."
+++

<div class="jk-project-list">
  <article class="jk-project-card" id="pill-engine">
    <div class="jk-project-thumb">
      <img src="/about_res/polyengine.png" alt="Game engine experiments" loading="lazy" onerror="this.remove()">
    </div>
    <div class="jk-project-body">
      <div class="jk-project-when">current · Rust · ECS · game tooling</div>
      <h3>Pill Engine / game-tech experiments</h3>
      <p>Rust game-engine experiments around ECS, hot reload, C# scripting, FFI, networking and editor/tooling architecture.</p>
      <div class="jk-chip-row"><span class="jk-chip">Rust</span><span class="jk-chip">ECS</span><span class="jk-chip">C#</span><span class="jk-chip">FFI</span><span class="jk-chip">Game engine</span></div>
      <div class="jk-card-links"><a href="{{< relref "/about.md" >}}#polyengine">Older engine work</a></div>
    </div>
  </article>

  <article class="jk-project-card" id="zled-frame">
    <div class="jk-project-thumb">
      <img src="/about_res/zephyr.jpeg" alt="ZLED Frame / Zephyr" loading="lazy" onerror="this.remove()">
    </div>
    <div class="jk-project-body">
      <div class="jk-project-when">2024 · hardware · firmware · enclosure</div>
      <h3>ZLED Frame</h3>
      <p>Open-source/open-hardware NeoPixel LED frame: FreeCAD enclosure work, ESP32 firmware, Zephyr drivers, Wi‑Fi networking and HTTP image upload.</p>
      <div class="jk-chip-row"><span class="jk-chip">C</span><span class="jk-chip">Zephyr</span><span class="jk-chip">ESP32</span><span class="jk-chip">Wi‑Fi</span><span class="jk-chip">3D printing</span></div>
      <div class="jk-card-links">
        <a href="{{< relref "/posts/20-01-24-zled-frame-part1.md" >}}">Part 1</a>
        <a href="{{< relref "/posts/27-03-24-zled-frame-part2.md" >}}">Part 2</a>
        <a href="{{< relref "/about.md" >}}#zled-frame">About entry</a>
      </div>
    </div>
  </article>

  <article class="jk-project-card" id="game-jams">
    <div class="jk-project-thumb">
      <img src="/about_res/deluge.png" alt="The Deluge / game jam project" loading="lazy" onerror="this.remove()">
    </div>
    <div class="jk-project-body">
      <div class="jk-project-when">2023–now · Sticky Piston Studios · prototypes</div>
      <h3>Game jams / Sticky Piston Studios</h3>
      <p>Small games, prototypes, jam experiments and the recurring habit of building too much engine/tooling for too little time.</p>
      <div class="jk-chip-row"><span class="jk-chip">Unity</span><span class="jk-chip">Rust</span><span class="jk-chip">Game design</span><span class="jk-chip">Networking</span></div>
      <div class="jk-card-links">
        <a href="{{< relref "/about.md" >}}#the-deluge">The Deluge</a>
        <a href="{{< relref "/posts/20-05-23-digital-dragons.md" >}}">Digital Dragons</a>
      </div>
    </div>
  </article>

  <article class="jk-project-card" id="bibop">
    <div class="jk-project-thumb">
      <img src="/bibop/case.png" alt="BIBoP wearable casing render" loading="lazy" onerror="this.remove()">
    </div>
    <div class="jk-project-body">
      <div class="jk-project-when">2021–2023 · open hardware · embedded ML</div>
      <h3>BIBoP wearable health monitor</h3>
      <p>Open hardware wearable health-monitor prototype with embedded ML ambitions, later ported toward Zephyr and used for conference talks.</p>
      <div class="jk-chip-row"><span class="jk-chip">Zephyr</span><span class="jk-chip">Embedded ML</span><span class="jk-chip">Wearables</span><span class="jk-chip">Open hardware</span></div>
      <div class="jk-card-links">
        <a href="{{< relref "/posts/31-05-21-bibop_1_Intro_ML.md" >}}">Intro post</a>
        <a href="{{< relref "/posts/10-07-23-eoss.md" >}}">EOSS post</a>
        <a href="{{< relref "/about.md" >}}#embedded-open-source-summit">Talk entry</a>
      </div>
    </div>
  </article>

  <article class="jk-project-card" id="fpga-accelerated-tcpdump">
    <div class="jk-project-thumb">
      <img src="/about_res/sooc23.png" alt="FPGA acceleration in embedded Linux" loading="lazy" onerror="this.remove()">
    </div>
    <div class="jk-project-body">
      <div class="jk-project-when">2020–2023 · MSc thesis · packet capture</div>
      <h3>FPGA accelerated tcpdump using eBPF</h3>
      <p>MSc thesis work on hardware-accelerated packet capture in embedded Linux using programmable logic, custom Linux/kernel work and power/performance measurements.</p>
      <div class="jk-chip-row"><span class="jk-chip">FPGA</span><span class="jk-chip">Linux</span><span class="jk-chip">eBPF</span><span class="jk-chip">Networking</span><span class="jk-chip">Buildroot</span></div>
      <div class="jk-card-links">
        <a href="{{< relref "/posts/18-10-20-first-thesis-released.md" >}}">Thesis note</a>
        <a href="{{< relref "/about.md" >}}#msc-thesis">Thesis abstract</a>
        <a href="{{< relref "/talks/_index.md" >}}#state-of-open-con">Talk</a>
      </div>
    </div>
  </article>

  <article class="jk-project-card" id="rust-raytracer">
    <div class="jk-project-thumb">
      <img src="/raytracing/image.png" alt="Rust ray tracer render" loading="lazy" onerror="this.remove()">
    </div>
    <div class="jk-project-body">
      <div class="jk-project-when">2021 · learning project · language bridge</div>
      <h3>C++ to Rust ray tracer</h3>
      <p>Ray Tracing in One Weekend style exercise used as a practical bridge between C++ habits and Rust’s ownership-heavy mental model.</p>
      <div class="jk-chip-row"><span class="jk-chip">Rust</span><span class="jk-chip">C++</span><span class="jk-chip">Rendering</span></div>
      <div class="jk-card-links"><a href="{{< relref "/posts/26-02-21-cpp-to-rust.md" >}}">Read post</a></div>
    </div>
  </article>

  <article class="jk-project-card" id="rustalizer">
    <div class="jk-project-thumb">
      <img src="/about_res/playing_tui.gif" alt="Rustalizer terminal visualizer" loading="lazy" onerror="this.remove()">
    </div>
    <div class="jk-project-body">
      <div class="jk-project-when">2020–2021 · audio · GUI/TUI</div>
      <h3>Rustalizer</h3>
      <p>Audio frequency visualizer written in Rust, delivered as both a GTK desktop app and a console distraction in the spirit of old-school Winamp toys.</p>
      <div class="jk-chip-row"><span class="jk-chip">Rust</span><span class="jk-chip">GTK</span><span class="jk-chip">DSP</span><span class="jk-chip">Audio</span></div>
      <div class="jk-card-links">
        <a href="{{< relref "/about.md" >}}#rustalizer">About entry</a>
        <a href="{{< relref "/posts/29-09-20-alsa-adventures.md" >}}">ALSA notes</a>
      </div>
    </div>
  </article>

  <article class="jk-project-card" id="polyengine">
    <div class="jk-project-thumb">
      <img src="/about_res/polyengine.png" alt="PolyEngine" loading="lazy" onerror="this.remove()">
    </div>
    <div class="jk-project-body">
      <div class="jk-project-when">older · engine architecture · tooling</div>
      <h3>PolyEngine</h3>
      <p>Student-society game engine work using ECS/data-oriented design, C/C++, CMake/Meson and graphics/tooling experiments around Vulkan.</p>
      <div class="jk-chip-row"><span class="jk-chip">C</span><span class="jk-chip">C++</span><span class="jk-chip">Vulkan</span><span class="jk-chip">ECS</span></div>
      <div class="jk-card-links">
        <a href="{{< relref "/about.md" >}}#polyengine">About entry</a>
        <a href="{{< relref "/posts/08-05-20-github-actions.md" >}}">CI post</a>
      </div>
    </div>
  </article>
</div>

<p class="jk-page-subtitle">Keep this page compact: if a project grows into a proper write-up, link to the post instead of turning this index into another giant About page.</p>

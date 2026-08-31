+++
title = "Projects"
description = "Selected systems, hardware, Rust and game-tech work, newest/current work first."
+++

<p class="jk-page-subtitle">
A compact index of things I have built or hacked on. Bigger stories link out to posts instead of turning this page into another giant About page.
</p>

<section class="jk-project-feature-section" aria-labelledby="featured-projects">
  <h2 id="featured-projects">Featured systems</h2>

  <div class="jk-project-feature-grid">
    <article class="jk-project-feature" id="pill-engine">
      <div class="jk-project-feature-body">
        <p class="jk-card-topline">current · Rust · ECS · game tooling</p>
        <h3>Pill Engine / game-tech experiments</h3>
        <p>Rust game-engine experiments around ECS, hot reload, C# scripting, FFI, networking and editor/tooling architecture.</p>
        <div class="jk-skill-tags"><code>Rust</code><code>ECS</code><code>C#</code><code>FFI</code><code>Hot reload</code></div>
        <div class="jk-card-links"><a href="https://github.com/MattSzymonski/Pill-Engine">GitHub</a><a href="#polyengine">Older engine work</a></div>
      </div>
    </article>

    <article class="jk-project-feature" id="zled-frame">
      <img src="/about_res/zephyr.jpeg" alt="ZLED Frame / Zephyr" loading="lazy" onerror="this.remove()">
      <div class="jk-project-feature-body">
        <p class="jk-card-topline">2024 · hardware · firmware · enclosure</p>
        <h3>ZLED Frame</h3>
        <p>Open-source/open-hardware NeoPixel LED frame: FreeCAD enclosure work, ESP32 firmware, Zephyr drivers, Wi-Fi networking and HTTP image upload.</p>
        <div class="jk-skill-tags"><code>C</code><code>Zephyr</code><code>ESP32</code><code>Wi-Fi</code><code>3D printing</code></div>
        <div class="jk-card-links"><a href="{{< relref "/posts/20-01-24-zled-frame-part1.md" >}}">Part 1</a><a href="{{< relref "/posts/27-03-24-zled-frame-part2.md" >}}">Part 2</a><a href="https://github.com/JDuchniewicz/zled-frame">GitHub</a></div>
      </div>
    </article>

    <article class="jk-project-feature" id="bibop">
      <img src="/bibop/case.png" alt="BIBoP wearable casing render" loading="lazy" onerror="this.remove()">
      <div class="jk-project-feature-body">
        <p class="jk-card-topline">2021–2023 · open hardware · embedded ML</p>
        <h3>BIBoP wearable health monitor</h3>
        <p>Open hardware wearable health-monitor prototype with embedded ML ambitions, later ported toward Zephyr and used for conference talks.</p>
        <div class="jk-skill-tags"><code>Zephyr</code><code>Embedded ML</code><code>Wearables</code><code>Open hardware</code></div>
        <div class="jk-card-links"><a href="{{< relref "/posts/31-05-21-bibop_1_Intro_ML.md" >}}">Intro post</a><a href="{{< relref "/posts/10-07-23-eoss.md" >}}">EOSS post</a></div>
      </div>
    </article>

    <article class="jk-project-feature" id="fpga-accelerated-tcpdump">
      <div class="jk-project-feature-body">
        <p class="jk-card-topline">research · FPGA · Linux · networking</p>
        <h3>FPGA accelerated tcpdump using eBPF</h3>
        <p>MSc thesis work on hardware-accelerated packet capture in embedded Linux using programmable logic, custom Linux/kernel work and power/performance measurements.</p>
        <div class="jk-skill-tags"><code>FPGA</code><code>Linux</code><code>eBPF</code><code>Networking</code><code>Buildroot</code></div>
        <div class="jk-card-links"><a href="{{< relref "/posts/18-10-20-first-thesis-released.md" >}}">Thesis note</a><a href="/FPGA-capture.pdf">PDF</a><a href="{{< relref "/talks/_index.md" >}}#state-of-open-con">Talk</a></div>
      </div>
    </article>
  </div>
</section>

<section class="jk-project-feature-section" aria-labelledby="project-archive">
  <h2 id="project-archive">Archive / smaller things</h2>

  <div class="jk-project-archive">
    <article id="game-jams">
      <time>2025–now</time>
      <div>
        <h3>Game jams / Sticky Piston Studios</h3>
        <p>Small games, prototypes, jam experiments and the recurring habit of building too much engine/tooling for too little time. Includes <a href="https://hist0r.itch.io/tiny-trucks">Tiny Trucks</a> and <a href="https://hist0r.itch.io/the-deluge">The Deluge</a>.</p>
      </div>
    </article>

    <article id="rust-raytracer">
      <time>2021</time>
      <div>
        <h3>C++ to Rust ray tracer</h3>
        <p>Ray Tracing in One Weekend style exercise used as a practical bridge between C++ habits and Rust’s ownership-heavy mental model. <a href="{{< relref "/posts/26-02-21-cpp-to-rust.md" >}}">Read post</a>.</p>
      </div>
    </article>

    <article id="rustalizer">
      <time>2020–2021</time>
      <div>
        <h3>Rustalizer</h3>
        <p>Audio frequency visualizer written in Rust, delivered as both a GTK desktop app and a console distraction in the spirit of old-school Winamp toys.</p>
      </div>
    </article>

    <article id="polyengine">
      <time>older</time>
      <div>
        <h3>PolyEngine</h3>
        <p>Student-society game engine work using ECS/data-oriented design, C/C++, CMake/Meson and graphics/tooling experiments around Vulkan. <a href="https://github.com/PolyEngineTeam/PolyEngine/">GitHub</a>.</p>
      </div>
    </article>

    <article id="beagleboard-gsoc">
      <time>2021</time>
      <div>
        <h3>GSoC beagleboard.org — GPGPU using OpenGL ES</h3>
        <p>Computation acceleration on the BeagleBone Black using the SGX GPU instead of leaving it untouched except for rendering. <a href="https://github.com/JDuchniewicz/GPGPU-with-GLES">GitHub</a>.</p>
      </div>
    </article>

    <article id="envidrawer">
      <time>older</time>
      <div>
        <h3>Envidrawer</h3>
        <p>Embedded IoT / sensor / 3D-printing experiment: a home-garden under the bed, because apparently someone had to try it.</p>
      </div>
    </article>
  </div>
</section>

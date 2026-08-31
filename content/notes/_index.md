+++
title = "Notes"
description = "Shorter engineering notes, debug logs and project breadcrumbs."
+++

<p class="jk-page-subtitle">
This section is intentionally lighter than the blog. Use it for debug logs, architecture sketches, toolchain notes and short discoveries that do not deserve a full polished article.
</p>

<div class="jk-callout">
  <p><strong>Suggested use:</strong> keep posts for polished articles; use notes for 300–800 word write-ups from current work. That makes the site look alive without forcing every update to become a big essay.</p>
</div>

<div class="jk-card-grid">
  <article class="jk-card">
    <div class="jk-card-topline">Good note topics</div>
    <h3>Low-level debugging breadcrumbs</h3>
    <p>virtio-net checksum weirdness, seL4/sDDF vswitch experiments, FPGA timing traps, hostfxr runtime-loading gotchas, Neovim/LSP tooling fixes.</p>
  </article>

  <article class="jk-card">
    <div class="jk-card-topline">Format</div>
    <h3>Small and useful beats perfect</h3>
    <p>A note can be a problem statement, a few failed attempts, the fix, and the one thing future-you should remember.</p>
  </article>
</div>

Create a note with:

```bash
hugo new notes/name-of-the-note.md
```

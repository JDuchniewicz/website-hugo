+++
title = "Pill Engine? What is that?"
description = "Why we're building yet another game engine, what makes Pill different, and where we want to take it."
summary = "Why we're building yet another game engine, what makes Pill different, and where we want to take it."
date = 2026-10-16T12:47:48+02:00
draft = false
type = "posts"
toc = true
tags = ["PillEngine", "Gamedev", "ECS", "Unity", "Unreal", "Bevy", "Rust"]
categories = []

thumbnail = "/pill_engine/pill_pile_white.png"
images = ["/pill_engine/pill_pile_white.png"]

[author]
  name = "Jakub Duchniewicz"
+++

<style>
/* Image and video captions */
.pill-media-caption {
    display: block;
    max-width: 680px;
    margin: 10px auto 30px;
    padding: 0 12px;
    text-align: center;
    font-size: 0.88rem;
    font-style: italic;
    line-height: 1.6;
    opacity: 0.72;
}

.pill-media-caption strong {
    font-weight: 600;
}

/* Section dividers */
.pill-divider {
    border: 0;
    height: 1px;
    max-width: 80%;
    margin: 42px auto;
    background: linear-gradient(
        90deg,
        transparent,
        currentColor,
        transparent
    );
    opacity: 0.18;
}
</style>

**Long time no see (or hear)** Much has happened since I last posted here, including me living for a while in *Down Under*, making a **[presentation]** on game engines and joining forces in a novel project… **drums** 🥁 **[Pill Engine]**!

<video
    src="https://pillengine.org/images/xenium_30fps_4k.mp4"
    style="display: block; width: 100%; height: auto; border-radius: 8px;"
    controls
    autoplay
    muted
    playsinline
    preload="metadata">
</video>

<p class="pill-media-caption">
    Pill Engine demo showcased at <strong>Xenium 2026</strong>.
</p>

<hr class="pill-divider">

## The situation right now

Before I explain why I decided to work on yet another game engine, let's look at some observations of mine and folks closer to the gamedev industry.

First, the current market of game engines IMHO does not solve the immediate need for an **easy-to-use** and **highly performant** engine with a modern editor.

Sure, one can use Unity and pretend that the gazillion of `GameObject` scripts somehow execute in parallel and do not impact their game's performance at all. Yes, there is a new ECS implementation called **DOTS**, but *have you actually tried using it?*

On the other hand, we have Unreal Engine: it looks amazing, but every developer who has worked with it will tell you one thing: **"The development cycle is painfully slow."**

*Remember this meme from xkcd?*

That's what working with Unreal looks like (but exchange compiling for `reloading`).

{{< image src="https://imgs.xkcd.com/comics/compiling.png" alt="xkcd compiling meme" position="center" style="border-radius: 8px;" >}}

<p class="pill-media-caption">
    The legendary <strong>xkcd #303 — Compiling</strong>. Some things never change. Except now we're reloading.
</p>

Enter open source: **Godot** or **Bevy**.

The former gained a lot of popularity after some bad press from Unity about increasing royalties, while the latter is a pioneer of Rust in gamedev.

Even though Godot has improved a lot over the years, there are some things that *"just work"* in Unity. And, as for Bevy, there is a **really steep learning curve** to do anything productive in it, which is sad as it's an amazing project.

And yes, I am strongly biased towards many of Unity's solutions, as I was simply dumbstruck when I encountered them early in my career, and I still keep learning from them.

Thus, when I had a chat with my friend (and Pill Engine lead developer) Matt (aka [HIST0R]), my main question was:

<hr class="pill-divider">

## Why write yet another engine?

This short Venn diagram should quickly answer your questions:

{{< image src="/pill_engine/game_engines_venn.png" alt="A Venn diagram of existing game engines" position="center" style="border-radius: 8px;" >}}

<p class="pill-media-caption">
    The game engine holy trinity: <strong>open-source, highly performant, and developer-friendly</strong>. An entirely unbiased scientific study, of course. 😉
</p>

I know I am **kicking the hornet's nest** and, *shudders*, infuriating fans of said engines. Please take that with a grain of salt (and rub it in the wound), and remember that there is a saying in Polish: *"Opinia jest jak dupa, każdy ma własną."* which translates roughly to: *"An opinion is like a butt, everybody has their own."*

Having said so, I think we can all agree that we are yet to see an engine that satisfies all three criteria: being **open-source**, being **easy to use**, and **not sacrificing performance**.

As many great things are born from ambitious goals, why not aim high and try to achieve that **holy grail**?

Some of you who know me already know that I enjoy working on projects that offer a high level of innovation or where *reinventing the wheel* is necessary.

Ultimately, what is better than actually bridging the technological gap and potentially helping many devs do their work much faster and with less frustration at their tools?

With Pill, we have spent heaps of cycles on some really cool tech challenges, such as:

- **Reinventing the best approach to ECS** - settling on the archetype ECS variant.
- **Hot-reloading** that *even patches the binary in place*, saving precious recompilation time.
- **Scripting** that works with probably the most popular language among devs - C#.
- **Innovative rendering** based on [Aaltonen's gems].
- **Modularity** - while still making it all modular and future-proof.

Besides, we think it's time that fellow developers received something that is **familiar**, yet does not trade **performance for ease of use**.

We need more like-minded people on the project as we are gaining momentum, especially after our recent debut at the [**Xenium**] demoscene event with the demo you have already seen above.

<hr class="pill-divider">

## What's on the menu?

I have some personal goals I would like to achieve with this engine. After all, *what is a better driver of innovation than immediate needs?*

I strongly believe that as hardware gets cheaper and more powerful every year (well, maybe barring GPUs and RAM - **no thanks to AI lords...**), having a performant game engine that you can freely modify might actually come across as useful in scenarios like:

- **Distributed gaming & simulation** - have a central compute engine streaming video and gameplay to multiple connected devices.
- **Custom hardware & tiny consoles** - push the boundaries of hardware and try creating a console capable of hosting the engine and tiny games.
- **Browser-native experiences** - have the engine hosted remotely or make it so tiny that it can run from your browser on any modern device.

I know those are quite grandiose-sounding goals, so to keep things real, let's now **Make The Engine Great** (**not again -.-**)(TM).

<hr class="pill-divider">

### 💊 Choose your Pill

Check out our [project webpage] and don't forget to join the **Discord server!**


<div style="display: flex; justify-content: center; align-items: center; gap: 24px; margin: 32px 0;">
    <a href="https://pill.rocks/" target="_blank" rel="noopener noreferrer">
        <img src="/pill_engine/pill_blue.png"
             alt="Pill Engine Website"
             width="180"
             style="display: block; max-width: 100%; height: auto;">
    </a>
    <a href="https://discord.gg/rag9CXvUW" target="_blank" rel="noopener noreferrer">
        <img src="/pill_engine/pill_red.png"
             alt="Pill Engine Discord"
             width="180"
             style="display: block; max-width: 100%; height: auto;">
    </a>
</div>

<p align="center">
    🔵 <a href="https://pill.rocks/">Explore Pill Engine</a>
    &nbsp;&nbsp; | &nbsp;&nbsp;
    🔴 <a href="https://discord.gg/rag9CXvUW">Join the community</a>
</p>

And don't forget to **vote on your most desired features!** We will prioritize the backlog accordingly :)

{{< image src="/pill_engine/pill_pile_white.png" alt="Just a pill pile" position="center" style="border-radius: 8px;" >}}

<p class="pill-media-caption">
    One Pill is never enough. <strong>Take as many as you need.</strong> 💊
</p>

[presentation]: https://youtu.be/kQ2d5bvrRJA?si=sDaxZZToOK9aGpxd
[HIST0R]: https://mattszymonski.com/posts/pill-engine-rethinking-the-game-engine/
[Pill Engine]: https://pill.rocks/
[Xenium]: https://2026.xenium.rocks/
[project webpage]: https://pill.rocks/
[Aaltonen's gems]: https://advances.realtimerendering.com/s2023/AaltonenHypeHypeAdvances2023.pdf


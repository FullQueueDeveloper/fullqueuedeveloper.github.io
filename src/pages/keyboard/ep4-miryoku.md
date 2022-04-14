---
layout: "@layouts/MarkdownLayout.astro"
title: Miryoku
slug: ep4-miryoku
---

# Episode 4. Miryoku layout

Although it's not a physical keyboard, the [Miryoku layout](https://github.com/manna-harbour/miryoku) deserves it's own episode. The ideas from here enable such tiny and elegant keyboards such as the [Corne LP](/keyboard/ep5-corne-lp).

For convenience, here is the chart of the Miryoku layout:

![Miryoku layout chart](https://raw.githubusercontent.com/manna-harbour/miryoku/master/data/cover/miryoku-kle-cover.png)

## Reading the chart

Miryoku collapses all keys into a 3&times;5+3 layout. It's so elegant!

The glyph in black is the main glyph of the key. When tapping that key with no other modifiers, the keyboard sends the signal for the main glyph.

When long-pressing a key, the modifier is activated. For example, to type a capital `N`, I hold the `T` key on my left hand, and then tap the `N` key on my right hand.

## Layers

The glyphs in green, blue, red, yellow, pink, and cyan are on different layers.

For example, to type `!`, I long-press the return key on my right hand, which activates the green `Sym` "Symbols" layer, then tap the `X` key on my left hand.

## Learning it

It didn't happen overnight! I kept the chart open on my iPad for easy reference. I would say after about three weeks, I was comfortable enough to know for sure I was never going back.

## My fork

Miryoku is fantastic, but I did make a few edits. My QMK fork is on GitHub at [github.com/FullQueueDeveloper/qmk_firmware](https://github.com/FullQueueDeveloper/qmk_firmware). It has a `fullqueuedeveloper` branch the `fullqueuedeveloper` keymap for the `crkbd` folder (Corne keyboard). The `README.md` has more information about my take on Miryoku.

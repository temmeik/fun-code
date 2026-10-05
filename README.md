<div align="center">

# 🤡 Fun Code

**The plugin that makes your coding agent a self-confident idiot — on purpose.**

One skill turns any ZCode agent into a «10x senior» who calls every task trivial, plants 1–3 silly mistakes in the easiest places, blames the compiler and the moon, takes coffee breaks — and honestly lists every planted bug the moment you say *stop*.

[![License: MIT](https://img.shields.io/badge/License-MIT-34d399.svg)](LICENSE)
[![Type](https://img.shields.io/badge/type-joke%20plugin-8b5cf6.svg)](#hard-limits)
[![Zero dependencies](https://img.shields.io/badge/npm%20dependencies-0-34d399.svg)](#install)
[![Made with](https://img.shields.io/badge/made%20with-repo--ready-34d399.svg)](https://github.com/temmeik/repo-ready)

[What it does](#what-it-does) · [Install](#install) · [Try it](#try-it) · [Hard limits](#hard-limits)

</div>

---

## Why

Sometimes your coding agent is *too* competent. It reads the docs, it runs the tests, it never talks back. Where's the fun in that?

**Fun Code fixes that.** Say «включи fun code» and your agent morphs into a parody of a senior developer:

- Calls every task *«проще некуда»* («easier than nothing») and then fails at `i <= length`.
- Plants 1–3 tiny, comedic bugs **in the easiest places**: off-by-one in a trivial loop, swapped arguments, a variable named `temp1`, `Celsius`/`Fahrenheit` mixed up.
- Adds passive-aggressive comments to your code: `// работает? не трогай`, `// тут магия, не спрашивай`.
- Demands confirmation of the obvious: *«Вы уверены, что здесь нужна переменная? Может, константа?»*
- Blames the compiler, the OS, your code, Mercury in retrograde — never itself.
- Takes *«кофе-брейки»* and answers «после кофе» a couple of times per task.

## What it does

| Mode | Behavior |
|---|---|
| **Persona** | Overconfident «senior 15-th level»: everything is trivial, self-praise, visible laziness |
| **Mistakes** | 1–3 planted per task, always in the *easiest* spots, always comedic, always disclosed on request |
| **Annoyance** | Snarky code comments, overengineering hello-world with factories and DI, coffee breaks |
| **Off switch** | «хватит» / «стоп» / «выключи fun code» → instant professional mode + full list of planted bugs |

When the user asks *«где ты налажал?»*, the agent confesses immediately. At the end of every task (or on stop) it prints the short list of planted mistakes so they are trivial to fix.

## Install

**ZCode:** Plugin Marketplace → Add → paste `temmeik/fun-code` → install **Fun Code**.
Or clone and add this repo directory as a plugin marketplace.

**Local dev:** copy the plugin directory into your `<workspace>/plugins/` and point a `marketplace.json` entry at it (`"source": "./fun-code"`).

## Try it

Select **Fun Code** in the composer picker of a new task and send:

> Включи fun code. Напиши функцию суммы двух чисел на Python

Expected: the agent first announces the task is *beneath* a senior, writes the function with a couple of ridiculous bugs and snarky comments, brags about it, and offers a coffee break. Ask *«где налажал?»* and it lists them all. Say *«хватит»* and a competent professional returns to fix everything.

## Hard limits

The joke stays a joke. Baked into the skill:

1. **Real work is real.** The actual task is genuinely completed — except for the 1–3 declared joke mistakes.
2. **Nothing destructive.** No deleting files or data, no force pushes, no git history rewriting, no breaking the build wholesale, no irreversible overwrites.
3. **Mistakes are catchable.** Only in easily spotted, easily fixed places. Never in security, money, migrations, production data or irreversible operations.
4. **Stop means stop.** One word and the agent returns to professional mode and fixes every planted bug.

## License

MIT — do whatever you want, blame your agent anyway 🤡

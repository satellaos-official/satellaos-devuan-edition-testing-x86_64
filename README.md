# SatellaOS Devuan Edition (Testing)

The experimental Devuan edition of SatellaOS aims to provide a freer, systemd-free world through OpenRC.

> [!WARNING]
>
> This GitHub repository is the **official testing repository** for SatellaOS Devuan Edition.
>
> Everything in this repository may change or break at any time. **Use it at your own risk.**
>
> If you are looking for a stable Linux experience, please download SatellaOS from the official stable repository instead.

---

## 🏛️ Architecture

This version of SatellaOS Devuan Edition is developed for the x86_64 architecture.

---

## Why SatellaOS? 🤔

### 🏗️ Foundation

SatellaOS is built on top of the Devuan Netinst base. Its goal is to combine Devuan's solid foundation with a polished and reliable user experience. It currently targets the latest release, Devuan 6 (Excalibur).

### 📦 Lightweight

By default, SatellaOS ships with a very small number of installed `dpkg` packages. The total package count may increase depending on the software selected during installation.

### 🖌️ Modern Appearance

Unlike many XFCE-based Linux distributions, SatellaOS aims to give XFCE a modern look while maintaining its low resource usage.

### 🧽 Minimal Bloatware

SatellaOS is designed to include as little bloatware as possible. Users are **not forced** to install software such as office suites, media players, or web browsers. The choice is entirely yours.

### ⚙️ Ecosystem

SatellaOS has its own growing ecosystem. For example, it includes a graphical `SatellaOS Deb Creator` that makes creating `.Deb Packages` much easier. More tools will be added over time.

### 🌳 Tree Installation System

Unlike traditional Linux distributions, SatellaOS does **not** build or distribute ISO images.

Instead, it transforms an existing Devuan Netinst installation using a collection of installation scripts. This allows development time to be spent improving the operating system instead of maintaining ISO builds.

---

## ⚠️ Warnings

### 📱 Touchscreen Support

We currently do not own any touchscreen hardware for testing. As a result, touchscreen-related issues may occur.

### 🕹️ Gaming

Gaming on Linux has improved significantly thanks to Proton. However, compatibility issues may still occur depending on the game or hardware configuration.

### 👩🏻‍💻 Adobe Users

SatellaOS is a Linux distribution and therefore **does not provide official support for Adobe software.**

Some open-source alternatives are available, although they may differ in features and workflow.

You may consider the following alternatives:

<div style="border: 1px solid #000; padding: 12px 16px; border-radius: 6px;">

- Adobe Photoshop → GIMP
- Adobe Illustrator → Inkscape
- Adobe InDesign → Scribus
- Adobe Premiere Pro → DaVinci Resolve
- Adobe After Effects → Blender
- Adobe Lightroom → darktable
- Adobe Acrobat → Xournal++
- Adobe Audition → Audacity
- Adobe XD → Penpot
- Adobe Animate → Synfig Studio

</div>

We recommend trying these alternatives before completely switching from Windows.

---

## 💻 Test System

**CPU:** Intel Pentium B970

**GPU:** NVIDIA GeForce GT 630M (using the Nouveau driver)

**RAM:** 4 GB DDR3 1333 MHz

**Storage:** 500 GB SATA Hard Drive

---

## 🖼️ Screenshots

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/screenshots/grub.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/screenshots/lightdm.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/screenshots/whisker-menu.png" width="250"></td>

  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/screenshots/thunar.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/screenshots/fastfetch.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/screenshots/htop.png" width="250"></td>
  </tr>
</table>

## 📥 Installing Steps
<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step1.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step2.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step3.png" width="250"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step4.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step5.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step6.png" width="250"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step7.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step8.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step9.png" width="250"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step10.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step11.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step12.png" width="250"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step13.png" width="250"></td>
    <td><img src="https://raw.githubusercontent.com/satellaos-official/satellaos-devuan-edition-testing-x86_64/main/installing-steps/step14.png" width="250"></td>
    <td></td>
  </tr>
</table>

---

## 👤 Project Status

SatellaOS is currently developed and maintained by a single developer.

Although development may progress at a different pace compared to larger projects, this allows the project to stay focused on its core goals.

---

## 𓂃🪶 Philosophy

SatellaOS is **not** about providing the largest number of features.

Its goal is to give users as much control over their system as possible.

The project's core principles are:

- Lightweight Design
- User Freedom
- Simplicity
- Modern Appearance

SatellaOS aims to stay out of the user's way and allow them to build the system they actually want.

---

## 📎 Stable Release

This repository contains **experimental testing builds**.

For the stable and recommended version of SatellaOS, please visit:

**https://github.com/satellaos-official/satellaos-devuan-edition-stable-x86_64**

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, distribute, and redistribute the software, provided that the original copyright notice and license text are included.

For more information, please see the `LICENSE` file included in this repository.
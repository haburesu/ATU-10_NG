# 📻 ATU-10_NG - Smarter Tuning for QRP Operators

[![Download ATU-10_NG](https://img.shields.io/badge/Download-ATU--10__NG-brightgreen?style=for-the-badge&logo=github)](https://github.com/haburesu/ATU-10_NG/releases)

ATU-10_NG is a complete, from-scratch rewrite of the firmware that runs your ATU-10 QRP antenna tuner. If you own an ATU-10 and want it to find a better match, remember more of your favourite settings, and give you a proper setup menu you can actually read and understand, this is the software for you. You do not need to know anything about programming to install it. Everything you need is on the download page, and this guide walks you through it one step at a time.

---

## ✨ What This Software Does

An antenna tuner is a small box that sits between your radio and your antenna. Its job is to make the radio and the antenna "agree" with each other so that your signal actually gets out into the air instead of bouncing back into your transmitter. The ATU-10 does this automatically by trying different internal settings until it finds the combination that works best.

The ATU-10_NG firmware replaces the software inside that tuner with a newer, cleaner version written from the ground up. It searches harder for the best possible match, stores twelve of your tuned settings in its memory so it can jump straight back to them next time, and gives you a proper setup menu instead of a hidden set of key combinations. There is also a Cells editor that lets you look at and adjust the tuning behaviour in fine detail.

In plain terms: your tuner gets better at its job, remembers more, and becomes easier to configure.

---

## 🎯 Who This Is For

This software is built for anyone using an ATU-10 QRP antenna tuner. That includes:

- Radio amateurs operating low-power portable setups who need a fast, reliable tune on a windy hilltop.
- Home station operators who switch between several antennas and want the tuner to remember each one.
- Radio hobbyists who enjoy experimenting and want to see exactly what the tuner is doing.
- Anyone who finds the stock menu confusing and wants something clearer.

You do not need any electronics skills to update the firmware. You do need your ATU-10 hardware and a computer running Windows.

---

## 💡 Key Features

**Best match engine.** The tuner does not stop at the first acceptable result. It keeps working toward the strongest possible match for the antenna in front of it, which means more of your transmitted power reaches the air.

**Memory for 12 tunes.** Up to twelve separate tuning solutions can be stored. Switch antennas, change bands, or move to a different spot in the field, and the tuner can recall the right setting instantly instead of hunting from scratch.

**A real setup menu.** Adjust the behaviour of the tuner through a clear, structured menu instead of guessing at button combinations. Every option is visible and can be changed deliberately.

**Cells editor.** For the tinkerers, a dedicated editor exposes the internal tuning cells so you can inspect and refine them. This is optional, but it is there when you want it.

**Written from scratch.** The firmware is a fresh codebase rather than a patch on top of something old. That means a cleaner internal structure, fewer inherited quirks, and behaviour that is easier to reason about.

**Built for QRP.** Everything is tuned around the low-power operating style, where efficiency and reliability matter more than raw output.

---

## 🚀 Getting Started

Getting started takes only a few minutes. You do not need to install any developer tools, compilers, or additional software packages. There is nothing to configure before you begin.

The only thing you need is the download page, which is linked in the next section. Read through the download section carefully, follow the single set of instructions given there, and you will be ready to go.

Before you start, make sure your ATU-10 is powered off and disconnected from your radio. It is always good practice to work on hardware when it is not live.

---

## 📥 Download and Install

[![Get ATU-10_NG](https://img.shields.io/badge/Get%20ATU--10__NG-Releases-blueviolet?style=for-the-badge&logo=github)](https://github.com/haburesu/ATU-10_NG/releases)

Visit this link to download the application: **https://github.com/haburesu/ATU-10_NG/releases**

On that page you will find the list of available releases. Take the release marked as the latest one — it is listed at the top and is the version you should use. Each release lists the files that belong to it, along with short notes describing what changed in that version. Reading those notes is a good habit, because they tell you what is new or improved since the last release.

Click the file you need from the latest release to begin the download. Your browser will show the progress in its downloads area. When it finishes, the file will be in your Downloads folder unless you chose a different location.

Because the files come from a public release page rather than a signed commercial installer, Windows may show a warning the first time you open something you downloaded. If that happens, look for the option that lets you keep the file — usually hidden behind a "More info" link in the warning dialog. This is normal behaviour for small open-source projects.

Once the download is complete, keep the file somewhere you can find it again. You will be coming back to this page whenever a new version is published, so it is worth bookmarking it now.

---

## 🖥️ First Run

The first time you use the new firmware, take a moment to let the tuner settle in. Power the unit up as you normally would and let it complete its start-up sequence. The display should come alive and show you the main screen.

From there, do a single tune on a familiar antenna and band. This gives the tuner a baseline to work from and confirms that everything is communicating correctly. You should notice the search process completing and a match being reported.

After that first successful tune, the stored memory begins to fill. Each new tune in a new situation is a new memory slot. Over a few operating sessions you will build up a useful library of settings that makes future tuning almost instant.

If you want to change how the tuner behaves — how long it searches, how it reports results, how the menu is laid out — open the setup menu. Everything is organised into clear groups. Move through the groups, look at each option, and change only the ones you understand. The defaults are chosen to work well for most people, so leaving things alone is a perfectly good decision.

The Cells editor is available for advanced adjustment. Treat it as an optional extra. If you are happy with how the tuner performs, there is no need to touch it at all.

---

## 🧠 Tips for Best Results

**Tune on a clear frequency.** Give the tuner a moment of quiet air. It works best when it is not competing with strong signals.

**Tune once per band and antenna.** Each successful tune is a memory slot. Repeating the same tune wastes memory that could hold a different configuration.

**Use a good ground or counterpoise.** The tuner can only match what the antenna system presents. A solid ground reference makes its job much easier and produces a better final match.

**Keep notes.** Write down which memory slot corresponds to which antenna and band. Twelve slots is generous, but they fill up faster than you expect when you are experimenting.

**Update when new releases appear.** The releases page is the single place where new versions are published. Checking it occasionally keeps you on the most refined build.

---

## ❓ Troubleshooting

**The tuner does not respond after start-up.** Power the unit down completely, wait a few seconds, and power it back up. Confirm the connections to your radio and antenna are seated properly.

**A tune takes a long time to complete.** This is normal on difficult antennas. The best-match search is thorough by design. If it consistently fails to find any match, the antenna may be outside the range the tuner can handle on that band.

**A memory slot does not recall the right setting.** Memory slots are tied to the conditions under which they were saved. If you have changed the antenna layout, retune and let the tuner save a fresh entry.

**The display shows something unexpected.** Return to the setup menu and review the options you have changed. Restoring defaults is always possible and is the quickest way back to a known-good state.

**Windows warns about the downloaded file.** This is expected for small independent projects. Choose the option to keep the file and continue.

**You cannot find the download page.** The link is repeated here for convenience: https://github.com/haburesu/ATU-10_NG/releases

---

## 🔧 About the Project

ATU-10_NG is an open firmware project for the ATU-10 QRP antenna tuner. It is written in embedded C for Microchip PIC microcontrollers and built with the XC8 toolchain. The project covers the amateur radio, antenna tuning, impedance matching, and embedded firmware space.

Because the source is open, the behaviour of the tuner is not a black box. Anyone curious about how the matching algorithm works, how memory is stored, or how the menu is structured can read the code and understand it. That transparency is a large part of what makes this project worth using.

Feedback, bug reports, and suggestions are welcome through the repository. If you find a bug, describe what you were doing, what you expected, and what happened instead. Clear reports make fixes faster for everyone.

---

## 📄 License

Refer to the repository for the license terms that apply to this firmware and its source code.

---

Keywords: amateur-radio, antenna, antenna-tuner, atu, atu-10, embedded, embedded-c, firmware, ham-radio, hamradio, hf-radio, impedance-matching, microchip, pic, pic16, qrp, xc8
<a href="https://github.com/SyscallBrain">
  <img src="assets/banner.svg" alt="Tiago Correia: fast terminal tools in Rust and private, offline-first Android apps in Kotlin" width="100%">
</a>

<p align="center">
  <a href="mailto:tiagorcorreia87@gmail.com"><img src="https://img.shields.io/badge/email-tiagorcorreia87%40gmail.com-f7768e?style=flat-square&labelColor=1a1b26&logo=gmail&logoColor=c0caf5" alt="Email: tiagorcorreia87@gmail.com"></a>
  <a href="https://github.com/SyscallBrain?tab=repositories"><img src="https://img.shields.io/badge/repos-browse-7aa2f7?style=flat-square&labelColor=1a1b26&logo=github&logoColor=c0caf5" alt="Browse repositories"></a>
  <a href="https://crates.io/crates/quotop"><img src="https://img.shields.io/crates/v/quotop?style=flat-square&label=quotop%20on%20crates.io&color=ff9e64&labelColor=1a1b26&logo=rust&logoColor=c0caf5" alt="quotop on crates.io"></a>
  <a href="https://syscallbrain.github.io/virsh-tui/"><img src="https://img.shields.io/badge/virsh--tui-docs-9ece6a?style=flat-square&labelColor=1a1b26&logo=mdbook&logoColor=c0caf5" alt="virsh-tui documentation"></a>
  <a href="https://syscallbrain.github.io/lictor/"><img src="https://img.shields.io/badge/lictor-docs-bb9af7?style=flat-square&labelColor=1a1b26&logo=mdbook&logoColor=c0caf5" alt="Lictor documentation"></a>
</p>

## 👋 Hi, I'm Tiago

I build software I want to use myself, and I hold it to the standard I expect as a user: private, fast, documented, and proven to work.

- 🦀 **In the terminal**, I write keyboard-driven tools in **Rust** with [ratatui](https://ratatui.rs): a full manager for KVM/libvirt virtual machines, a dashboard for API quotas and a watcher for coding agents running in parallel.
- 📱 **On Android**, I make **Kotlin** apps and games, mostly with **Jetpack Compose**, that work without an internet connection: no ads, no accounts and no tracking.
- 🧪 **I prefer proof to promises**: my games run on deterministic engines, and every level of the Night series and NeonLine ships with a machine-checked solution certificate.
- 🐧 **Day to day**, I live on Linux and care about virtualization, tooling and small, fast binaries.
- 🇵🇹 Some of my games are made first for **European Portuguese**, a language most word games ignore.

<img src="assets/stats.svg" alt="4 Rust terminal tools, 10 Android apps and games, 9,000 certified level variants, and 0 ads, trackers or accounts" width="100%">

## 🦀 Terminal tools

Keyboard-driven Rust tools built on [ratatui](https://ratatui.rs), each shipped as a single fast binary.

<table>
  <tr>
    <td width="50%"><a href="https://github.com/SyscallBrain/virsh-tui"><img src="assets/cards/virsh-tui.svg" alt="virsh-tui: keyboard-driven terminal UI for libvirt/virsh" width="100%"></a></td>
    <td width="50%"><a href="https://github.com/SyscallBrain/quotop"><img src="assets/cards/quotop.svg" alt="quotop: terminal dashboard for API balances and quotas" width="100%"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/SyscallBrain/lictor"><img src="assets/cards/lictor.svg" alt="lictor: watches every terminal and coding agent in Herdr" width="100%"></a></td>
    <td width="50%"><a href="https://github.com/SyscallBrain/todo-ratatui"><img src="assets/cards/todo-ratatui.svg" alt="todo-ratatui: to-do manager TUI with categories, priorities and a crash-proof trash bin" width="100%"></a></td>
  </tr>
</table>

## 🌙 The Night series and NeonLine

Five offline Android games built the same way: a deterministic Kotlin engine shared by the game and its offline solver, 600 levels in three separately tuned difficulties, and a **solution certificate for each of the 1,800 variants in every game**. CI replays all of them, so an impossible level can never ship. The only permission they ask for is `VIBRATE`.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SyscallBrain/bubble-night"><img src="assets/games/bubble-night.jpg" alt="Bubble Night: an offline bubble shooter for Android" width="100%"></a>
      <br><b><a href="https://github.com/SyscallBrain/bubble-night">Bubble Night</a></b> · bubble shooter
      <br><sub>600 constellations across 12 orbits</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SyscallBrain/block-night"><img src="assets/games/block-night.jpg" alt="Block Night: an offline falling-blocks game for Android" width="100%"></a>
      <br><b><a href="https://github.com/SyscallBrain/block-night">Block Night</a></b> · falling blocks
      <br><sub>600 floors across 12 Lisbon districts</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SyscallBrain/night-fleet"><img src="assets/games/night-fleet.jpg" alt="Night Fleet: an offline naval battle for Android" width="100%"></a>
      <br><b><a href="https://github.com/SyscallBrain/night-fleet">Night Fleet</a></b> · naval battle
      <br><sub>600 missions against 12 admirals who never cheat</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SyscallBrain/duck-night"><img src="assets/games/duck-night.jpg" alt="Duck Night: photograph ducks at dusk" width="100%"></a>
      <br><b><a href="https://github.com/SyscallBrain/duck-night">Duck Night</a></b> · reflex game
      <br><sub>Photograph ducks at dusk: 600 levels, 48 birds</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SyscallBrain/neon-line"><img src="assets/games/neon-line.jpg" alt="NeonLine: an offline four-in-a-row game for Android" width="100%"></a>
      <br><b><a href="https://github.com/SyscallBrain/neon-line">NeonLine</a></b> · four in a row
      <br><sub>600 levels along a neon road, against 12 rivals</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SyscallBrain/neon-line#architecture"><img src="assets/games/proof.svg" alt="How every level is proven: the solver writes a certificate, CI replays it with the same engine, and the build fails if a level can no longer be won" width="100%"></a>
      <br><b><a href="https://github.com/SyscallBrain/neon-line#architecture">How it works</a></b> · one engine, two jobs
      <br><sub>The build fails if any level can no longer be won</sub>
    </td>
  </tr>
</table>

## 📱 More for Android

Retro arcade games drawn entirely in code, word games written for European Portuguese, and a habit tracker that keeps your data on your phone.

<table>
  <tr>
    <td width="50%"><a href="https://github.com/SyscallBrain/steel-eagle"><img src="assets/cards/steel-eagle.svg" alt="Steel Eagle: faithful 8-bit tank battle for Android with 50 stages, a level editor and two-player co-op" width="100%"></a></td>
    <td width="50%"><a href="https://github.com/SyscallBrain/Kaboom"><img src="assets/cards/kaboom.svg" alt="Kaboom: maze bomber in 16-bit pixel art for Android" width="100%"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/SyscallBrain/PalavrasCruzadas"><img src="assets/cards/palavrascruzadas.svg" alt="Palavras Cruzadas: offline crossword game in European Portuguese" width="100%"></a></td>
    <td width="50%"><a href="https://github.com/SyscallBrain/SopaDeLetras"><img src="assets/cards/sopadeletras.svg" alt="Sopa de Letras: word search for Android" width="100%"></a></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><a href="https://github.com/SyscallBrain/SmokeTracker"><img src="assets/cards/smoketracker.svg" alt="SmokeTracker: one-tap cigarette counter for Android" width="50%"></a></td>
  </tr>
</table>

<details>
<summary><b>📸 Screenshots</b></summary>
<br>

**virsh-tui**: domains dashboard

<img src="https://raw.githubusercontent.com/SyscallBrain/virsh-tui/main/book/src/images/dashboard.png" alt="virsh-tui domains dashboard" width="100%">

**quotop**: balances and quotas at a glance

<img src="https://raw.githubusercontent.com/SyscallBrain/quotop/main/docs/screenshot.svg" alt="quotop showing the balances and quotas of several API services" width="100%">

**lictor**: a live, read-only mirror of two rotating lanes in Herdr

<img src="https://raw.githubusercontent.com/SyscallBrain/lictor/main/docs/src/images/mirror.png" alt="A Lictor mirror tab in Herdr: a workspace with its agent and server log on the left, a blocked agent asking for permission on the right" width="100%">

**NeonLine**: the neon road, a duel against Sparky with his threat marked, and the rival gallery

<p>
  <img src="https://raw.githubusercontent.com/SyscallBrain/neon-line/main/docs/screenshots/home.jpg" alt="NeonLine home screen with the current stop and the neon road" width="32%">
  <img src="https://raw.githubusercontent.com/SyscallBrain/neon-line/main/docs/screenshots/duel.jpg" alt="A NeonLine duel against Sparky with an immediate rival threat marked" width="32%">
  <img src="https://raw.githubusercontent.com/SyscallBrain/neon-line/main/docs/screenshots/rivals.jpg" alt="NeonLine rival gallery" width="32%">
</p>

**Steel Eagle**: defending the eagle with the NES-style cross pad, one of four touch layouts

<img src="https://raw.githubusercontent.com/SyscallBrain/steel-eagle/main/docs/screenshots/nes-pad.jpg" alt="Steel Eagle gameplay with the NES-style cross pad and A/B buttons" width="100%">

**Kaboom**: the four worlds, every sprite drawn in code

<img src="https://raw.githubusercontent.com/SyscallBrain/Kaboom/master/docs/worlds.png" alt="The four Kaboom worlds: The Meadow, The Desert, The Ice and The Castle" width="100%">

**Palavras Cruzadas** and **Sopa de Letras**

<p>
  <img src="https://raw.githubusercontent.com/SyscallBrain/PalavrasCruzadas/main/docs/screenshots/game.jpg" alt="Palavras Cruzadas crossword grid" width="49%">
  <img src="https://raw.githubusercontent.com/SyscallBrain/SopaDeLetras/main/docs/screenshots/jogo.jpg" alt="Sopa de Letras word search board" width="49%">
</p>

</details>

## 🧭 How I build

| Principle | In practice |
|---|---|
| 🔒 **Private by default** | Nine of my ten Android apps don't even request the `INTERNET` permission, so they *can't* phone home. The tenth, Steel Eagle, uses the network only for two-player co-op over local Wi-Fi, phone to phone. No ads, no accounts, no analytics anywhere, and your data stays on the device. |
| 🧪 **Proven, not hoped** | The Night games and NeonLine ship more than 9,000 solution certificates that CI replays with the real engine; if a level becomes impossible, the build fails. Steel Eagle runs a deterministic 60 Hz simulation covered by 466 JVM tests, including host/guest sync over real sockets. Night Fleet and Duck Night also rebuild every release from two fresh clones and compare the APKs byte for byte. |
| ⌨️ **Keyboard first** | Vim keys, discoverable shortcuts and which-key hints. virsh-tui shows the exact `virsh` command before it runs, and Lictor only ever observes your agents, never types into them. |
| ♿ **Accessible** | Colour-blind palettes, TalkBack descriptions, left-handed layouts and reduced motion, built into most of my games. |
| 📖 **Documented** | Real screenshots, install guides, changelogs, READMEs in English and Portuguese, and mdBook sites for [virsh-tui](https://syscallbrain.github.io/virsh-tui/) and [Lictor](https://syscallbrain.github.io/lictor/). |
| 🆓 **Open** | MIT licensed. Fork it, read it, learn from it. |

## 🛠️ Toolbox

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Rust-1a1b26?style=for-the-badge&logo=rust&logoColor=ff9e64" alt="Rust">
      <img src="https://img.shields.io/badge/Kotlin-1a1b26?style=for-the-badge&logo=kotlin&logoColor=bb9af7" alt="Kotlin">
      <img src="https://img.shields.io/badge/Python-1a1b26?style=for-the-badge&logo=python&logoColor=7dcfff" alt="Python">
      <img src="https://img.shields.io/badge/Shell-1a1b26?style=for-the-badge&logo=gnubash&logoColor=9ece6a" alt="Shell">
    </td>
  </tr>
  <tr>
    <td><b>Terminal</b></td>
    <td>
      <img src="https://img.shields.io/badge/Ratatui-1a1b26?style=for-the-badge&logo=ratatui&logoColor=c0caf5" alt="Ratatui">
      <img src="https://img.shields.io/badge/Tokio-1a1b26?style=for-the-badge&logo=rust&logoColor=c0caf5" alt="Tokio">
      <img src="https://img.shields.io/badge/tmux-1a1b26?style=for-the-badge&logo=tmux&logoColor=9ece6a" alt="tmux">
    </td>
  </tr>
  <tr>
    <td><b>Android</b></td>
    <td>
      <img src="https://img.shields.io/badge/Jetpack_Compose-1a1b26?style=for-the-badge&logo=jetpackcompose&logoColor=7aa2f7" alt="Jetpack Compose">
      <img src="https://img.shields.io/badge/Material_3-1a1b26?style=for-the-badge&logo=materialdesign&logoColor=7dcfff" alt="Material 3">
      <img src="https://img.shields.io/badge/Android_SDK-1a1b26?style=for-the-badge&logo=android&logoColor=9ece6a" alt="Android SDK">
      <img src="https://img.shields.io/badge/Room-1a1b26?style=for-the-badge&logo=sqlite&logoColor=7aa2f7" alt="Room">
      <img src="https://img.shields.io/badge/Gradle-1a1b26?style=for-the-badge&logo=gradle&logoColor=9ece6a" alt="Gradle">
    </td>
  </tr>
  <tr>
    <td><b>Systems</b></td>
    <td>
      <img src="https://img.shields.io/badge/Linux-1a1b26?style=for-the-badge&logo=linux&logoColor=e0af68" alt="Linux">
      <img src="https://img.shields.io/badge/Debian-1a1b26?style=for-the-badge&logo=debian&logoColor=f7768e" alt="Debian">
      <img src="https://img.shields.io/badge/QEMU%2FKVM-1a1b26?style=for-the-badge&logo=qemu&logoColor=ff9e64" alt="QEMU/KVM">
      <img src="https://img.shields.io/badge/libvirt-1a1b26?style=for-the-badge&logo=redhat&logoColor=f7768e" alt="libvirt">
      <img src="https://img.shields.io/badge/Docker-1a1b26?style=for-the-badge&logo=docker&logoColor=7aa2f7" alt="Docker">
    </td>
  </tr>
  <tr>
    <td><b>Shipping</b></td>
    <td>
      <img src="https://img.shields.io/badge/GitHub_Actions-1a1b26?style=for-the-badge&logo=githubactions&logoColor=7aa2f7" alt="GitHub Actions">
      <img src="https://img.shields.io/badge/mdBook-1a1b26?style=for-the-badge&logo=mdbook&logoColor=c0caf5" alt="mdBook">
      <img src="https://img.shields.io/badge/crates.io-1a1b26?style=for-the-badge&logo=rust&logoColor=e0af68" alt="crates.io">
      <img src="https://img.shields.io/badge/Git-1a1b26?style=for-the-badge&logo=git&logoColor=ff9e64" alt="Git">
    </td>
  </tr>
</table>

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SyscallBrain/SyscallBrain/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SyscallBrain/SyscallBrain/output/snake-light.svg">
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/SyscallBrain/SyscallBrain/output/snake-dark.svg" width="100%">
</picture>

## 📫 Get in touch

Questions, feedback or an idea worth building together? Email me at **[tiagorcorreia87@gmail.com](mailto:tiagorcorreia87@gmail.com)**. For bugs or feature requests, open an issue on the project's repository.

---

<p align="center">
  <sub><code>exit_group(0)</code>: thanks for stopping by. ⭐ a repo if it's useful to you.</sub>
</p>

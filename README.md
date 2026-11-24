<div align="center">

<p><b>English</b> &nbsp;|&nbsp; <a href="./README.ja.md">日本語 (Japanese)</a></p>

# BLÅHAJ KIKKOU 3D Viewer

**Interactive 3D Viewer for Kikkou-Bound IKEA Shark (Blåhaj) & "傻眼……" Witness Shark**  
**Full-3D GPU-Rigged Edition (`TWIST` × `PIXEL+AA` × `DOT SIZE 1.30` Default) · 60 FPS · Single Self-Contained HTML**

<p>
  <img src="https://img.shields.io/badge/Engine-WebGL%202--Pass%20SSAA-2e7df6?style=flat-square" alt="WebGL 2-Pass SSAA" />
  <img src="https://img.shields.io/badge/Motion-TWIST%20%C3%97%206%20Actions%20(60FPS)-00b8e6?style=flat-square" alt="60 FPS 6 Motions" />
  <img src="https://img.shields.io/badge/Preset-PIXEL%2BAA%20%2F%20DOT%201.30-6c5ce7?style=flat-square" alt="PIXEL+AA DOT 1.30" />
  <img src="https://img.shields.io/badge/Runtime-Single%20HTML%20(802KB)-10b981?style=flat-square" alt="Single HTML 802KB" />
  <img src="https://img.shields.io/badge/License-MIT-f59e0b?style=flat-square" alt="MIT License" />
</p>

<p>
  <a href="https://kuraneko1.github.io/blahaj-kikkou-3d/"><b>🚀 Live Demo (`TWIST` + `PIXEL+AA 1.3`)</b></a> &nbsp;|&nbsp;
  <a href="https://kuraneko1.github.io/blahaj-kikkou-3d/smooth.html">Smooth AA Edition</a> &nbsp;|&nbsp;
  <a href="https://kuraneko1.github.io/blahaj-kikkou-3d/pseudo3d.html">128-Slice Pseudo-3D Edition</a>
</p>

</div>

---

Packed into a **single zero-dependency HTML file (`802 KB`)** with no external libraries or server required: 60° kikkou shibari ropework, tail-tie wrapping, plush belly indentation, twisting suspension-rope physics, a swimming 3D witness shark with a `"傻眼……"` (dumbfounded) pixel speech bubble, 6 interactive motions, and in-browser `.GLB` / `.PNG` export.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="assets/gifs/twist_pixel13.gif" alt="TWIST 360° PIXEL+AA DOT 1.3" width="380" /><br />
      <b>5. TWIST (Default: PIXEL+AA / DOT SIZE 1.30)</b><br />
      <sub>Twisting suspension rope, 360° turntable orbit, dizzy eyes &amp; sparkle FX</sub>
    </td>
    <td align="center" width="50%">
      <img src="assets/gifs/witness_pixel13.gif" alt="DUMBFOUND 3D Witness Meme PIXEL+AA" width="380" /><br />
      <b>1. DUMBFOUND (3D Witness Shark + 傻眼……)</b><br />
      <sub>Orbiting 3D witness shark with head-tracking pixel speech bubble</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="assets/gifs/chomp_pixel13.gif" alt="CHOMP Shark Snap PIXEL+AA" width="380" /><br />
      <b>4. CHOMP (Shark Snap)</b><br />
      <sub>Fierce squinted eyes, articulated jaw snap &amp; snout water-splash FX</sub>
    </td>
    <td align="center" width="50%">
      <img src="assets/gifs/full3d_orbit.gif" alt="Full-3D 360 & Pitch Orbit" width="380" /><br />
      <b>Full-3D 360° &amp; Vertical Pitch Orbit (Smooth AA)</b><br />
      <sub>Full `-85° to +90°` pitch, 3D frosted pedestal &amp; unified belly shading</sub>
    </td>
  </tr>
</table>

<p align="center">
  <img src="assets/viewer_preview.png" alt="BLÅHAJ KIKKOU 3D Viewer UI (TWIST + PIXEL+AA DOT 1.30)" width="840" />
</p>

---

## Included Files

| File | Format / Size | Highlights &amp; Default Preset |
| :--- | :--- | :--- |
| [`index.html`](./index.html) | **Single HTML (`802 KB`)** | **Default: `5. TWIST` · `PIXEL+AA` · `DOT SIZE 1.30`** / 60 FPS Full-3D GPU Rig |
| [`smooth.html`](./smooth.html) | Single HTML (`802 KB`) | Default: `1. DUMBFOUND` · `SMOOTH AA` / Smooth-shaded edition of the same model |
| [`pseudo3d.html`](./pseudo3d.html) | Single HTML (`4.1 MB`) | 128-slice sprite-stacking edition (24 FPS / `.ap3d` import &amp; export supported) |
| [`models/blahaj-kikkou-full3d.glb`](./models/blahaj-kikkou-full3d.glb) | glTF 2.0 Binary (`765 KB`) | Ready-to-use kikkou-bound Blåhaj 3D model for Blender / Unity (38,624 tris) |
| [`models/witness-shark-full3d.glb`](./models/witness-shark-full3d.glb) | glTF 2.0 Binary (`284 KB`) | Witness shark companion 3D model (14,464 tris) |
| [`models/blahaj-shibari-3d.ap3d`](./models/blahaj-shibari-3d.ap3d) | `.ap3d` Package (`3.0 MB`) | Pseudo-3D sprite-stack package containing all 6 motions |

## Controls

- **Drag**: 360° horizontal orbit &amp; `-85° to +90°` vertical pitch (inspect the back knots and frosted-glass pedestal from any angle)
- **Mouse Wheel**: Zoom in / out
- **`1`–`6` / `[` `]`**: Switch motion (`1. DUMBFOUND` / `2. DANGLE` / `3. STRUGGLE` / `4. CHOMP` / `5. TWIST` / `6. BUNGEE`)
- **`SPACE`**: Play / Pause (click or scrub individual timeline frames)
- **`F` / `B` / `R`**: Focus face (`FACE`) / Plush bounce (`BOUNCE`) / Reset (`RESET`)
- **Export (bottom-right panel)**: Download `.GLB (3D)`, `.GLB+PET`, or `.PNG` directly from the browser

---

Built with pure GPU SDF sculpting, 2-Pass SSAA silhouettes, and `AnimeUIKit` using the [kuraneko1/anime-pseudo-3d](https://github.com/kuraneko1/anime-pseudo-3d) workflow.

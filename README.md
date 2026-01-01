## Quick Brush Size

The default shortcuts keys `[` and `]` increase or decrease your brush size in Krita.
When you hold down a key, the brush size changes rather slowly making you hold and wait longer than necessary. 

Quick Brush Size is a Krita plugin that adds two keyboard shortcuts that increase or decrease your brush size faster than Krita's default shortcuts. It also recognizes when you tap your shortcut keys rapidly to change the brush size quicker. This effectively gives you three input modes for more nuanced brush size control rather than just the original two (tap and hold).

#### Tapping

<img src="https://github.com/user-attachments/assets/4edd5afe-1fa6-42ad-87dc-ebc201122a28" alt="1tapping" width="50%">


#### Double-tapping / Rapid-tapping

<img src="https://github.com/user-attachments/assets/14971262-ed44-4c7b-a5e9-aad93d4ba575" alt="2doubletapping" width="50%">

#### Holding

<img src="https://github.com/user-attachments/assets/40f6a781-ad02-4562-bec8-5857e11f4af5" alt="3holding" width="50%">

## Installation

* Download the [latest version](https://github.com/10zindraws/Scrubby-Zoom/releases/download/v1.0.1/scrubby_zoom-1.0.1.zip) or scroll up and click the green "Code" button, then click "Download ZIP"

* `Tools → Scripts → Import Python Plugin From File →` select the zip file

* Restart Krita

## Settings

You can disable any of the input methods and adjust how fast they change brush sizes in the Quick Brush Size docker. Top bar in Krita: `Settings → Dockers → Quick Brush Size`

<img width="383" height="603" alt="2026-01-01 09-01-03" src="https://github.com/user-attachments/assets/448ba9f3-deb1-49f7-8585-e7c8419135bf" />

When rapid double-taps are detected by the plugin, the double tap multiplier is applied to make brush size changes more dramatic while you tap at that speed. Adjust the burst counts if you feel like the taps change brush size too much or too little.

### Assign your Keyboard Shortcuts

Top bar in Krita: `Settings → Configure Krita → Keyboard Shortcuts → Quick Brush Size`

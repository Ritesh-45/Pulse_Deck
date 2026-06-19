# PulseDeck 🎛️

PulseDeck is a custom USB macro pad built using the **RP2040 Zero**. It provides one-touch access to frequently used websites, media controls, and audio controls, helping users work faster and more efficiently.

---

## ✨ Features

### 🌐 Quick Access Buttons

* Open Google Chrome
* Open YouTube
* Open Spotify
* Open LeetCode

### 🎵 Media Controls

* Previous Track
* Next Track
* Play / Pause

### 🔊 Audio Controls

* Volume Up
* Volume Down
* Speaker Mute
* Microphone Mute

---

## 🛠 Hardware

### Components Used

* RP2040 Zero
* Push Buttons
* USB-C Connection
* Custom Enclosure

### Connectivity

* USB HID (Human Interface Device)
* Plug-and-Play
* No additional drivers required

---

## ⚙️ How It Works

PulseDeck functions as a USB HID device. When a button is pressed, the RP2040 sends predefined keyboard shortcuts or media commands to the connected computer.

### Button Functions

| Button       | Action                 |
| ------------ | ---------------------- |
| Chrome       | Opens Google Chrome    |
| YouTube      | Opens YouTube          |
| Spotify      | Opens Spotify          |
| LeetCode     | Opens LeetCode         |
| Previous     | Previous Track         |
| Next         | Next Track             |
| Play/Pause   | Toggle Media Playback  |
| Vol +        | Increase System Volume |
| Vol -        | Decrease System Volume |
| Speaker Mute | Toggle Speaker Mute    |
| Mic Mute     | Toggle Microphone Mute |

---

## 🔌 Setup

1. Connect PulseDeck to your computer using a USB-C cable.
2. The device powers on automatically.
3. No external power source is required.
4. Press any button to trigger its assigned action.

---

## 🎯 Purpose

PulseDeck simplifies everyday computer interactions by providing dedicated physical controls for commonly used applications and media functions. It reduces reliance on keyboard shortcuts and improves workflow efficiency for daily computer use.

**Project:** PulseDeck
**Version:** 1.0
**Controller:** RP2040 Zero 🎛️

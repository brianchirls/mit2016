class: center, middle

# WebVR: Accessibility, Democratization, <span style="font-size: 0.7em">yadda yadda yadda</span>

---

# Who is this guy?

- Brian Chirls
- NYC, US
- Does code, media
- CTO, Datavized, data-driven immersive media
- Likes audiences, tolerates creators

---

# What is Web VR?
- It's just a web page
- WebGL for hardware accelerated graphics
- WebVR API for position/orientation ("Pose") tracking
- Positional audio (Web Audio API)

---

# Limitations

- CPU Some performance cost
- Graphics API limited to what's available on mobile
- Limited graphical authoring tools
- Not amazing for video (yet)

---

# Physical Distribution
- Delivered as a web page
- Commodity web servers, CDN
- No app install required
- Streaming content, start VR < 1 second
- Browser's built-in security sandbox

---
# Distribution: Bullets Dodged
- No app approval process
- No censorship (political, anti-competitive)
- Own your data
- Archivable: Standard tech outlasts proprietary tech
- Developer tools are free (as in beer 🍺 and as in 🗣)

---

class: center

# Responsive Web

![Responsive Web](images/responsive_web_design.png)
<!-- image under MIT License by https://github.com/johnpolacek/scrolldeck.js -->

---
# Technical Responsive Factors
- Screen size
- Inputs (mouse, touch, keys, gamepad, etc)
- CPU/GPU performance
- Network bandwidth/latency
- ...

---
# Human Responsive Factors
- Education
- Language
- Physical abilities
- Wealth/Income
- Attention
- ...

---
# How the web adapts
- Graceful degredation
- Feature detection
- Adaptive rendering

---
# Broken assumptions of "native" VR
- Fast, reliable network
- Content downloaded, installed in advance
- Functioning spinny chair
- or dedicated VR real estate
- No distractions (kids, pets, job)

---

# Design Implications
- Even the best scenarios occasionally break
- Build for the worst-case scenario
- ~~How well does it work?~~
- How well does it fail?
- Best-case scenario becomes smoother, more reliable

---

class:center

# Basic Example
<div>.center[<iframe width="100%" height="500" src="https://brillsnthrills.surge.sh" frameborder="0" allowfullscreen></iframe>]</div>
https://brillsnthrills.surge.sh/

---

class: middle, smaller

# Example
<div style="float: right; margin-left: 10px">.center[<iframe width="600" height="500" src="https://bb8.surge.sh" frameborder="0" allowfullscreen></iframe>]</div>
- BB-8 fan art
- 2.6 MB over the wire(less)
- < 700kb to first frame in VR
- Experience adapts to technology
- Immediately display sky, dunes
- Robot model loads in background

---

# Inclusion
- Minimal cost of creation: ~$150
- Google Cardboard
- School/Public library computer and WiFi
- Free hosting (github, codepen, jsbin, etc)
- WebVR Starter Kit
- A-Frame https://aframe.io

---

class: smaller

# Current support

- Chrome (experimental)
  - Oculus Rift (Windows only)
  - HTC Vive (Windows only, for now?)
- Firefox (Nightly)
  - Oculus Rift (Windows only)
  - WebVR deprecated API
- GearVR, Samsung Internet browser
  - enabled with flag
  - performance upgrades in progress
- Cardboard
  - Android
  - iPhone
  - Available today with polyfill

---

# Future
- Release in stable browsers, Q4 2016?
- Faster, smaller, cheaper hardware
- WebGL 2
- Improving design practices and content

---

# Thank you

## Follow
- [@bchirls](http://twitter.com/bchirls), [@datavized](http://twitter.com/datavized)

## Work
- [datavized.com](http://datavized.com)

## Code
- [github.com/brianchirls](http://github.com/brianchirls)
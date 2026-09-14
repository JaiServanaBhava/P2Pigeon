<div align="center">

# 🕊️ P2PIGEON

### `Where messages don't just get sent — they FLY.` 🌍

**A P2P messaging experiment that turns digital messages into pigeons traveling across a real 3D Earth.**

<br>

<a href="YOUR_WEBSITE_LINK">
<img src="https://jaiservanabhava.github.io/P2Pigeon/">
</a>

<a href="YOUR_GITHUB_LINK">
<img src="https://img.shields.io/badge/💻%20SOURCE%20CODE-GitHub-181717?style=for-the-badge&logo=github">
</a>

<br><br>

<img src="https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square&logo=javascript">
<img src="https://img.shields.io/badge/Three.js-WebGL-black?style=flat-square&logo=threedotjs">
<img src="https://img.shields.io/badge/PeerJS-P2P-blue?style=flat-square">
<img src="https://img.shields.io/badge/HTML5-orange?style=flat-square&logo=html5">
<img src="https://img.shields.io/badge/Privacy-Local%20First-success?style=flat-square">

</div>

---

# 🕊️ What is P2Pigeon?

**P2Pigeon** is a different kind of messaging experience.

Instead of:

> Type → Send → Message appears

P2Pigeon turns communication into a **visible journey across Earth**.

```text
        👤 YOU
          │
          │
          ▼
       📍 YOUR LOFT
          │
          │
          │     🕊️
          │    ╱
          │   ╱
          │  ╱
          ▼ ╱
    🌍 ───────────── 🌍
          ╲
           ╲
            ╲
             ▼
          📍 FRIEND
             │
             ▼
          💬 MESSAGE
```

You choose your location on the globe, connect directly with another person, write a message and **release a virtual pigeon**.

Then...

### 🕊️ You watch your message fly across the Earth.

---

# 🚀 LIVE WEBSITE

<div align="center">

<a href="YOUR_WEBSITE_LINK">

<img src="https://img.shields.io/badge/🕊️%20OPEN%20P2PIGEON-CLICK%20TO%20FLY-ffcc00?style=for-the-badge&labelColor=161b22">

</a>

### 🌍 Try it yourself

**Drag the Earth → Choose your loft → Connect → Write → RELEASE 🕊️**

</div>

---

# 🎯 The Problem

Modern messaging is incredibly fast.

But there is something missing.

### We completely lost the feeling of distance.

When you send a message from India to someone thousands of kilometres away:

```text
You
 │
 │  "Hey!"
 ▼
WhatsApp
 │
 ▼
Delivered ✓
```

Everything happens instantly.

You don't **see** the distance.

You don't experience the journey.

You don't feel that the person you're talking to may be **thousands of kilometres away**.

---

# 💡 The P2Pigeon Idea

What if sending a message felt more like sending a letter?

What if you could actually **see the message travel?**

That's the idea behind P2Pigeon.

```text
        MESSAGE
           ↓
       🕊️ PIGEON
           ↓
     🌍 REAL EARTH
           ↓
     ✈️ FLIGHT PATH
           ↓
       📍 DESTINATION
           ↓
      🎉 DELIVERED
```

---

# ✨ Why Is P2Pigeon Different?

P2Pigeon is **not another chat clone**.

It combines several concepts into one playful experience:

| Concept                       | P2Pigeon |
| ----------------------------- | -------- |
| 💬 Messaging                  | ✅        |
| 🌍 3D Earth                   | ✅        |
| 🔗 P2P Communication          | ✅        |
| 📍 Location Visualization     | ✅        |
| 🕊️ Animated Message Delivery | ✅        |
| 📏 Real Geographic Distance   | ✅        |
| ⏱️ Flight ETA                 | ✅        |
| 👥 Group Messaging            | ✅        |
| 📱 Mobile Support             | ✅        |
| 🔐 Local Identity Storage     | ✅        |

### The unusual part?

**The message itself becomes the journey.**

---

# 🌍 A 3D EARTH, NOT A CHAT WINDOW

P2Pigeon uses a WebGL-powered 3D globe.

You can:

🖱️ Drag
🔍 Zoom
📱 Pinch
🌎 Rotate
📍 Select locations

The Earth uses Blue Marble-style imagery and additional surface maps for a more realistic appearance.

---

# 📍 YOUR "LOFT"

Instead of entering a boring location field:

> `Location: India`

You simply:

### Zoom into Earth → Find your location → Tap it.

That becomes your **Pigeon Loft**. 🏠🕊️

Your selected location is represented on the globe.

---

# 🔗 DIRECT P2P CONNECTION

P2Pigeon uses **PeerJS** for its optional peer-to-peer messaging layer.

The basic idea:

```text
       👤 YOU
          │
          │
     Share ID
          │
          ▼
    🔗 P2P CONNECTION
          │
          │
          ▼
       👤 FRIEND
```

Once connected, the application exchanges messages and location updates directly through the peer connection.

There is no traditional application database storing your chat history in this project.

---

# 🕊️ THE MAIN EXPERIENCE

### 01 — Choose your identity

```text
🪪 Temporary Name
       +
📍 Your Loft
```

Your identity is stored locally on your device.

---

### 02 — Generate a Share ID

P2Pigeon creates a temporary ID such as:

```text
swift-owl-482
```

Send that ID to your friend.

---

### 03 — Link with your friend

Your friend enters your ID.

```text
YOU  ─────────── 🔗 ─────────── FRIEND
```

The P2P connection is established.

---

### 04 — Write your message

```text
┌──────────────────────────┐
│ Message strapped to      │
│ pigeon's leg...          │
└──────────────────────────┘

       🕊️ RELEASE PIGEON
```

---

### 05 — WATCH IT FLY

This is where P2Pigeon gets weird. 😄

Your message becomes a flying pigeon.

```text
🇮🇳 INDIA
    🕊️
     \
      \
       \───────────────🌍
                       \
                        \
                         🕊️
                          \
                           ▼
                         🇺🇸 USA
```

The flight path is rendered around the globe.

---

### 06 — DELIVERY

When the pigeon reaches the destination:

```text
╔════════════════════════════╗
║    🎉 PIGEON ARRIVED!     ║
║                            ║
║  Your message has landed.  ║
╚════════════════════════════╝
```

The receiver also gets a delivery confirmation.

---

# 📏 REAL DISTANCE

P2Pigeon calculates the geographic distance between the two selected locations.

For example:

```text
📍 YOUR LOFT
        ↓
     6,420 km
        ↓
📍 FRIEND'S LOFT
```

It also estimates how long the journey would take at the project's virtual pigeon speed.

### 🐦 Pigeon Speed

```text
80 km/h
```

So the interface can show:

```text
📏 Distance       6,420 km
🐦 Pigeon speed   80 km/h
⏱️ Flight time    80.3 h
✈️ Progress       64%
```

---

# 👥 FLOCK MODE

Why send one pigeon when you can release a flock?

P2Pigeon supports sending a message to multiple linked friends.

```text
                 🕊️
                ↙
YOU 🕊️ ────────→ 👤 FRIEND 1
                ↘
                 🕊️
                  \
                   → 👤 FRIEND 2
```

---

# 📍 LIVE LOCATION UPDATES

Friends can change their loft location.

When they relocate, the connected peer can receive the update and the visual route is rebuilt.

So your globe isn't just a map.

### It's a live visualization of your connected flock.

---

# 🔐 PRIVACY

P2Pigeon follows a simple principle:

> **Don't build a database if the experience doesn't need one.**

Your identity is persisted locally using browser storage.

Messages are exchanged through the peer connection rather than being stored in a conventional application database.

### Important technical note

P2Pigeon is **not completely serverless**.

PeerJS still requires Internet connectivity and signaling infrastructure to establish peer connections.

The goal is instead to avoid a traditional centralized **message-storage backend**.

---

# 🧠 UNDER THE HOOD

```text
                         P2PIGEON
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
       THREE.JS           PEERJS          LOCALSTORAGE
          │                 │                 │
          ▼                 ▼                 ▼
      3D EARTH          P2P DATA          IDENTITY
          │                 │
          ▼                 ▼
      FLIGHT PATH       MESSAGES
          │                 │
          └──────────┬──────┘
                     ▼
                 🕊️ PIGEON
```

---

# 🛠️ TECHNOLOGY

<div align="center">

| Technology      | Used For                      |
| --------------- | ----------------------------- |
| 🌐 HTML5        | Application structure         |
| 🎨 CSS3         | Interface & responsive design |
| ⚡ JavaScript    | Application logic             |
| 🌍 Three.js     | 3D Earth rendering            |
| 🖥️ WebGL       | GPU-powered graphics          |
| 🔗 PeerJS       | P2P communication             |
| 💾 LocalStorage | Local identity persistence    |

</div>

---

# ⚡ PERFORMANCE

The globe is rendered using WebGL instead of repeatedly drawing the Earth pixel-by-pixel with JavaScript.

The project also adjusts the 3D geometry and star count depending on whether the device appears to be mobile.

### Designed to feel lightweight.

---

# 📱 MOBILE SUPPORT

P2Pigeon isn't locked to desktop.

It supports:

* 📱 Touch rotation
* 🤏 Pinch zoom
* 🔍 Zoom controls
* 📲 Responsive panel
* 🖥️ Desktop interface
* 🕹️ Momentum-based globe interaction

---

# 📂 PROJECT STRUCTURE

```text
P2Pigeon/
│
├── index.html
│
└── README.md
```

The current implementation is intentionally lightweight and can run as a single HTML application.

---

# ▶️ RUN LOCALLY

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY
cd P2Pigeon
```

Start a local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

# 🌐 REQUIRED INTERNET

The full experience uses external resources including:

* Three.js
* PeerJS
* Earth textures

Therefore Internet access is required for the complete experience.

If the Earth imagery cannot be loaded, the application has a fallback texture.

---

# 🔮 FUTURE POSSIBILITIES

P2Pigeon can become much more than a fun experiment.

Possible future features:

```text
🔐 End-to-End Encryption
        ↓
📨 Message History
        ↓
🌦️ Weather-Based Flights
        ↓
🗺️ Better Geographic Data
        ↓
🐦 Custom Pigeon Types
        ↓
🎨 Pigeon Skins
        ↓
🔊 Flight Sounds
        ↓
📱 Installable PWA
        ↓
🌐 Better Offline Support
```

---

# 🧪 PROJECT STATUS

### 🟢 Working

* [x] 3D Earth
* [x] Earth interaction
* [x] Location selection
* [x] Local identity
* [x] P2P connection
* [x] Friend linking
* [x] Real geographic distance
* [x] Flight visualization
* [x] ETA calculation
* [x] Message delivery
* [x] Delivery acknowledgement
* [x] Group messaging
* [x] Live location updates
* [x] Mobile controls

---

# ❤️ THE IDEA

P2Pigeon isn't trying to make messaging **faster**.

The Internet already solved that.

It asks a different question:

## **What if sending a message was an experience?**

Instead of:

```text
SEND ✓
```

You get:

```text
WRITE
  ↓
RELEASE
  ↓
🕊️
  ↓
🌍
  ↓
✈️
  ↓
📍
  ↓
🎉
```

---

<div align="center">

# 🕊️ P2PIGEON

### **Messages have wings.**

🌍 **See the distance.**
🕊️ **Watch the journey.**
💬 **Experience the message.**

<br>

<a href="YOUR_WEBSITE_LINK">
<img src="https://jaiservanabhava.github.io/P2Pigeon/">
</a>

<br><br>

**Built with JavaScript • Three.js • WebGL • PeerJS**

⭐ If you like the idea, give the repository a star!

</div>

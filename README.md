<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:0e7490&height=180&section=header&text=Web%20Component%20Event%20Lab&fontSize=32&fontColor=ffffff" width="100%" alt="Web Component Event Lab banner"></p>
<p align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=22D3EE&center=true&vCenter=true&width=620&lines=Explore+event+bubbling+and+capture;See+what+composed+means+for+Shadow+DOM" alt="Animated tagline"></p>
<p align="center"><img src="assets/mark.svg" width="100" alt="Web component icon"></p>
<p align="center"><img src="https://img.shields.io/github/license/CyberLoop-dev/web-component-event-lab?style=flat-square" alt="License"><img src="https://img.shields.io/github/languages/top/CyberLoop-dev/web-component-event-lab?style=flat-square" alt="Language"><img src="https://img.shields.io/github/stars/CyberLoop-dev/web-component-event-lab?style=flat-square" alt="Stars"><img src="https://img.shields.io/github/last-commit/CyberLoop-dev/web-component-event-lab?style=flat-square" alt="Last commit"></p>

## 🧭 Overview
Web Component Event Lab is a hands-on demonstration of DOM event propagation. Dispatch custom events from inside a Shadow DOM component and compare what listeners can observe when `composed` is enabled or disabled.

## ✨ Features
- 🧪 Dispatch composed and non-composed custom events.
- ↕️ Observe capture and bubbling listeners.
- 🫥 Compare event-target retargeting at the shadow boundary.
- 🧭 Inspect the composed event path.
- 🔒 Everything runs in the local browser.

## 🎬 Demo
No hosted demo is published. Start the server, then use the two event buttons to compare propagation.

## 🚀 Quick Start
Requires Node.js 18 or newer.
```bash
npm start
```
Open [http://localhost:4178](http://localhost:4178).

## 🧰 Tech Stack
- Node.js built-in HTTP server
- Web Components, Shadow DOM, CustomEvent
- HTML, CSS, and browser JavaScript

## 🗂️ Folder Structure
```text
web-component-event-lab/
├── assets/mark.svg
├── public/{app.js,index.html,style.css}
├── .gitignore
├── LICENSE
├── package.json
├── README.md
└── server.js
```

## 🗺️ Roadmap
- [ ] Add composed-path highlighting.
- [ ] Add a slotting example.
- [ ] Add pointer and keyboard event comparisons.

## 🤝 Contributing
Contributions are welcome. Keep event examples reproducible and explain the browser behavior being demonstrated.

## 📄 License
Released under the [MIT License](LICENSE).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0e7490,100:111827&height=100&section=footer" width="100%" alt="Footer wave"></p>
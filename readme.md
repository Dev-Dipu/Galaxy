## 🌌 Three.js Galaxy Generator

> A beautiful, procedural spiral galaxy generator built with [Three.js](https://threejs.org/) + [dat.GUI](https://github.com/dataarts/dat.gui) – explore the cosmos from your browser 🪐

---

### 🚀 Features

* 🌀 **Procedural Spiral Galaxy**
* 🎨 **Color Gradients** (inner + outer color)
* 🎚️ **Interactive Controls** (count, spin, randomness, branches)
* 🧪 **Live Preview via `dat.GUI`**
* 🛰️ **OrbitControls** to fly around your stars
* 📏 **Responsive resizing** for all screen sizes

---

### 🛠️ Installation & Setup

```bash
# 1. Clone the repo
git clone https://github.com/Dev-Dipu/Galaxy.git

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev
```

---

### 🧪 Customize Your Galaxy

| Control           | Description                     |
| ----------------- | ------------------------------- |
| `count`           | Number of stars                 |
| `size`            | Size of each star               |
| `radius`          | Radius of galaxy arms           |
| `branches`        | Number of spiral arms           |
| `spin`            | Spin intensity                  |
| `randomness`      | Random deviation from spiral    |
| `randomnessPower` | Falloff intensity of randomness |
| `insideColor`     | Color at galaxy center          |
| `outsideColor`    | Color toward galaxy edges       |

All parameters are live-editable using the right-side dat.GUI panel!

---

### 🔭 Built With

* [Three.js](https://threejs.org/) – 3D rendering engine
* [dat.GUI](https://github.com/dataarts/dat.gui) – live parameter tweaking
* [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) – mouse drag and zoom


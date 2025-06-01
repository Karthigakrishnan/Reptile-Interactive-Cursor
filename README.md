# 🦎 Reptile Interactive Cursor

An interactive, animated cursor made with JavaScript and HTML5 Canvas that mimics the behavior of a reptilian creature. It follows your mouse using articulated limbs, simulating lifelike movement through inverse kinematics.

## 🚀 Features

- Dynamic limb movement with physics-based articulation
- Responsive to mouse movement and clicks
- Canvas-based rendering for lightweight performance
- Uses inverse kinematics and custom joint stiffness logic
- Reptile-like leg movement simulation
- Extendable segment system for customizable creatures

## 🖥️ Demo

Move your mouse around the screen and watch the reptile cursor follow you with smooth limb motion. It reacts to:

- **Mouse position** (for target following)
- **Mouse button clicks** (left, middle, right)
- **Keyboard keys** (stored in input array for possible future control extensions)

## 📂 Project Structure

- `Input` – Tracks keyboard and mouse inputs
- `Segment` – Basic segment for limbs
- `LimbSystem` – A system of segments forming a limb
- `LegSystem` – Specialized for foot placement and step mechanics
- `Creature` – Represents the full creature, combining physics and rendering

## 📦 Setup Instructions

1. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/reptile-cursor.git
   cd reptile-cursor
   Open index.html in a modern web browser.

No installation or build tools required — it's pure HTML and JavaScript.

##🧠 How It Works
Segment Chains simulate the body and limbs using simple trigonometry.

Inverse Kinematics ensure each limb ends up in a target position with natural motion.

Mouse Movement is continuously tracked and used as the creature’s follow target.

##🐛 Known Issues
Limb positions may jitter slightly if frame rate drops.

Edge collision or screen wrapping is not handled yet.

##🔧 Customization
You can modify the creature’s:

Limb length and stiffness

Speed and acceleration parameters

Number of limbs or segments

Footstep dynamics and swing angles

##📝 License
This project is licensed under the MIT License.

##🙌 Credits
Inspired by physics simulations and organic cursor design. Built entirely with vanilla JS and Canvas.

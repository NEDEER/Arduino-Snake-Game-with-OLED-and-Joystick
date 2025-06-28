# 🐍 Arduino Snake Game with OLED and Joystick

This project is a classic **Snake Game** built on the **Arduino Nano**, using a **128x64 OLED display (SSD1306)** and a **joystick module** for control.

---

## 📦 Components Used

- Arduino Nano
- 0.96" OLED Display (SSD1306, 128x64, I2C)
- Joystick Module (X, Y, Button)
- Breadboard & Wires

---

## 🔌 Wiring

### OLED Display:
| OLED Pin | Arduino Pin |
|----------|-------------|
| VCC      | 5V          |
| GND      | GND         |
| SDA      | A4          |
| SCL      | A5          |

### Joystick:
| Joystick Pin | Arduino Pin |
|--------------|-------------|
| VRx          | A0          |
| VRy          | A1          |
| SW (Button)  | D2          |
| VCC          | 5V          |
| GND          | GND         |

---

## 🎮 Game Features

- 128x64 pixel OLED display grid
- Joystick-based directional control
- Start screen with splash image
- Growing snake with food spawning
- Game over screen and restart on button press

---

## 📷 Splash Screen

The game shows a custom bitmap splash screen on startup (a simple snake logo). You can replace this with your own by converting an image to bitmap using tools like [Image2cpp](https://javl.github.io/image2cpp/).

---

## 📥 Installation & Upload

1. Install the following libraries in Arduino IDE:
   - `Adafruit GFX`
   - `Adafruit SSD1306`

2. Connect the components as shown above.

3. Upload the sketch to your Arduino Nano.

---

## ▶️ Controls

- **Move Snake**: Use joystick to change direction.
- **Start/Restart Game**: Press joystick button (SW).

---

## 📁 File Structure

Arduino-Snake-Game/
│
├── snake_game.ino # Main Arduino code
└── README.md # This file

---

## 🛠️ Credits

Developed by **NEDERR**  
Using open-source Arduino libraries and hardware.

---

## 📃 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

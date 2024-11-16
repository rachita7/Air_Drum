# 🎵 Air Drums: Drum Anywhere, Anytime! 🥁

Are you looking to unleash your inner musician?  
Do you want to carry a full drumset in your backpack?  
Bored in class, with only two pens and a laptop in hand?  
**Air Drums** gives you the ultimate opportunity to drum without the need for any actual drums. Simply use two green and pink objects as your drumsticks and enjoy a real drumming experience right at your fingertips!

---

## 🚀 Features
- **Virtual Drumming Experience**: Use any two objects (green and pink) as your drumsticks to simulate real drumming.  
- **Easy to Play**: All you need is a webcam and some objects of the right colors.  
- **Customizable Sound Effects**: Enjoy a variety of drum sounds as you play, including snare, bass, and cymbals.  
- **Portable Drumming**: Carry your drumset anywhere, from class to work, or even while traveling.  

---

## 📦 Requirements

Before running **Air Drums**, make sure to install the following dependencies:

- `imutils`
- `numpy`
- `argparse`
- `OpenCV 3.4.5.20** (Note: May not work with version 4.x.x)
- `threading`
- `screeninfo`
- `time`
- `winsound` (Windows Only)
- `pygame`
- `flask`

You can install them using pip:

```bash
pip install imutils numpy argparse opencv-python==3.4.5.20 threading screeninfo pygame flask
```

---

## 🛠️ Instructions

### 1. Install Dependencies  
Make sure all required libraries are installed by following the above instructions.

### 2. Run the Program  
You can run **Air Drums** in two ways:

- **Standalone Mode**: To run the program directly without the Flask front-end, execute:  
  ```bash
  python Air_Drums_Final.py
  ```

- **Web App Mode**: If you prefer using a web-based interface, run the Flask web app:  
  ```bash
  python app.py
  ```

### 3. Compatibility  
- **Operating System**: Currently, **Air Drums** is only compatible with **Windows** (due to the use of `winsound`).

---

## 🎤 How It Works
1. **Set Up Your Drums**: Place two objects of green and pink color in front of your webcam as your drumsticks.
2. **Start Playing**: The program tracks the colors of the objects in real-time, triggering drum sounds as you simulate drumming motions.
3. **Enjoy**: Play along with your favorite beats or create your own rhythm!

---

## 🌟 Future Enhancements
- **Cross-Platform Support**: Make the app compatible with macOS and Linux.
- **Advanced Drum Sounds**: Add more drum variations and sound effects for a richer experience.
- **Multi-User Mode**: Allow multiple users to play simultaneously with separate drumsticks.


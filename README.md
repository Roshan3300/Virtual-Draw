##Structure (suggested)**

```
Hand-Controlled-Cursor/
│
├── virtual_draw.py
├── jpg.png
├── requirements.txt
└── README.md
```

* **virtual_draw.py** → Your Python code.
* **requirements.txt** → List of required packages.
* **README.md** → Setup and usage guide.

---

## **requirements.txt**

```
pip install opencv-python
pip install mediapipe
pip install pyautogui
pip install pynput
pip install numpy
```

---

## **README.md

-
Virtual Drawing App (Hand Gesture Based) An interactive virtual drawing tool that allows users to draw on the screen using hand gestures tracked via webcam. Built with Python, OpenCV, and MediaPipe, this project turns your hand into a brush — no mouse or touchscreen needed!

🔧 Technologies Used Python

OpenCV

MediaPipe

NumPy

✨ Features Real-time hand tracking

Finger used as a drawing tool

Virtual color selection palette

Eraser mode via hand gesture

Clean and responsive interface

## Setup Guide in VS Code

Follow these steps to get this project running on your system:

### 1. Install Python
Make sure Python 3.9+ is installed. You can download it from [python.org](https://www.python.org/downloads/).

Check the version in terminal:

```bash
python --version
````

---

### 2. Clone the Repository

Open VS Code terminal and run:

```bash
[git clone https://github.com/YOUR_USERNAME/Hand-Controlled-Cursor.git
cd Hand-Controlled-Cursor](https://github.com/Roshan3300/Virtual-Draw)
```

---

### 3. Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

This will install:

* OpenCV (`opencv-python`)
* Mediapipe (`mediapipe`)
* PyAutoGUI (`pyautogui`)
* Pynput (`pynput`)
* Numpy (`numpy`)

---

### 4. Open the Project in VS Code

1. Open VS Code.
2. Go to **File → Open Folder** and select the project folder.
3. Ensure the **Python interpreter** in VS Code is set to the Python version you installed (3.9+).
   Check in bottom-right corner → select Python 3.9.x.

---

### 5. Run the Program

1. Open `virtual_draw.py`.
2. Press `F5` or run in terminal:

```bash
python virtual_draw.py
```

3. A window will open showing your webcam feed.

   * Move your **index finger** → cursor moves.
   * Pinch **thumb + index** → click.
   * Press `ESC` → exit program.

---

---

### Troubleshooting

* If you get errors like `module 'mediapipe' has no attribute 'solutions'` → Make sure **mediapipe is updated**:

```bash
pip install --upgrade mediapipe
```

* If cursor jitters → increase smoothing by adding a moving average for coordinates.
* Ensure no other program is using the webcam.

---

### License

This project is open-source. Feel free to use and modify it.

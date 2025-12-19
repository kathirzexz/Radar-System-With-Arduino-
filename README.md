# Radar-System-With-Arduino-
An Arduino radar system uses an Arduino board, ultrasonic sensor, and servo motor to detect objects. The sensor scans an area by rotating, measures distance using sound waves, and displays object position, simulating basic radar operation.

PROCEDURE :

Step 1: Upload Arduino Code

1. Open Arduino IDE on your computer

2. Connect your Arduino board to your PC via USB.

3. Open your Arduino sketch (.ino file).

4. Select the correct board type (e.g., Arduino Uno) under Tools → Board.

5. Select the correct COM port under Tools → Port.

6. Click Upload. Wait until it shows “Done uploading”.

---

Step 2: Download Processing Software

1. Go to Processing Download. [ Download Processing ](https://processing.org/download)

2. Download and install Processing for your operating system (Windows, macOS, or Linux).

---

Step 3: Paste the Processing Code

1. Open Processing.

2. Create a new sketch (File → New).

3. Copy your Processing code and paste it into this new sketch.

---

Step 4: Update COM Port in Processing Code


1. Look at line 23 in your Processing code. It usually looks like this:

myPort = new Serial(this, "COM3", 9600);

2. Replace "COM3" with the same COM port you used to upload the Arduino code.

Example: If Arduino is on COM5, change line 23 to:

myPort = new Serial(this, "COM5", 9600);

---

Step 5: Run the Processing Code

1. Click the Run button (▶) in Processing.

2. The Processing window should now communicate with your Arduino.



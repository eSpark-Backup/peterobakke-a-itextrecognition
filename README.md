# peterobakke-AItextrecognition

To build a wearable prototype that uses a miniature camera to capture printed text (e.g. multiple-choice questions), processes the input via OpenAI’s API to understand and answer the question, and then returns the result via a physical interface such as:
 
a modified analog watch date display, or
 
a vibration-based feedback device (e.g. 1–5 vibrations for A–E)
 
Core Tasks:
Use a camera module (ESP32-CAM or Raspberry Pi Cam) to capture printed text
 
Send the captured image or extracted text to OpenAI's API (e.g. GPT-4 Vision or Chat Completion API)
 
Receive and interpret the answer (e.g. A/B/C/D)
 
Trigger physical feedback:
 
update an e-ink or mechanical display on a watch face
 
or control a vibration motor (e.g. 3 pulses = option C)
 
Technology Preferences:
Hardware: ESP32-CAM or Raspberry Pi Zero
 
AI/OCR/Answering: OpenAI (Vision + Text)
 
Output Channels: E-Ink, stepper motor, or vibration motor
 
Programming: Python / MicroPython / Arduino C++
 
Bonus: Low-latency optimization, offline mode handling, compact embedded design
 
Ideal Skills:
Experience with camera-based microcontroller systems
 
Familiarity with OpenAI’s APIs (Vision + Chat)
 
Knowledge of hardware feedback mechanisms (vibration, display drivers, stepper motors)
 
Prototyping mindset and experience with wearables or custom devices
 
Optional but useful: UX awareness for minimalist physical interaction
 
Goal:
Build a portable, discreet device that allows the user to point the camera at a printed multiple-choice question, and receive the correct answer through physical feedback without using a screen or audio.


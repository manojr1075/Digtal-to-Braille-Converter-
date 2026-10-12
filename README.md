# ♿ Realtime Braille Conversion for Digital Content

## 📌 Overview
This project converts digital text into Braille format in real-time using a mobile application, helping visually impaired users access digital content easily.

## 🎯 Objective
To design an app-controlled system that translates text into Braille output.

## ⚙️ Working
- User inputs text through the mobile app
- The app processes the text
- The system converts it into Braille output

## 🛠️ Technologies Used
- MIT App Inventor
- Embedded System / Hardware Interface

## 📱 App Interface
![App](images/app_interface.jpeg)

## 🧩 Block Programming
![Block1](codeblocks/blocks1.png)
![Block2](codeblocks/blocks2.png)
![Block3](codeblocks/blocks3.png)

## 🔧 Circuit Diagram
![Circuit](images/circuit diagram.jpeg)

## 📊 Output
![Output](images/result.jpeg)

## 🌍 Applications
- Assistive devices for visually impaired
- Educational tools
- Accessibility systems

## 👥 Team
This project was developed as a team of 4 members.

## 🏆 Achievements
- Selected among **Top 20** projects in Plutonium 2026
- Awarded participation certificate
=======
Real-Time Braille Converter for Digital Content:
A real-time system that converts digital/text content into tactile Braille output using OCR, Python, Arduino, and a solenoid-based Braille display.

🎯 Objective:
To help visually impaired users access digital text by converting captured text into readable Braille characters.

💡 How It Works:
The system captures text using a camera and processes the image using OCR. The extracted text is converted into Braille patterns and sent to the Arduino, which controls the solenoids to produce the corresponding tactile Braille dots.

Workflow:
Image Capture → OCR → Text Extraction → Braille Conversion → Arduino → Solenoid Activation → Braille Output

🔧 Hardware Used:
- Arduino Uno
- Solenoids
- TIP122 power transistors
- 1N4007 flyback diodes
- Buck converter
- Battery
- USB-to-TTL module

💻 Software & Technologies:
- Python
- OCR (Optical Character Recognition)
- Arduino IDE
- MIT App Inventor
- Serial Communication

📁 Project Files:
- "braille_ocr.py" – OCR and text processing
- "braille_sender.py" – Sends processed data to the hardware
- "Braille Report.pdf" – Project documentation
- "app_interface.jpeg" – Mobile application interface
- "circuit diagram.jpeg" – Hardware circuit
- "result.jpeg" – Project output 

🚀 Future Improvements:
- Support for multiple languages
- Faster text-to-Braille conversion
- Smaller and more portable hardware
- Improved Braille display mechanism.
>>>>>>> ocr/main

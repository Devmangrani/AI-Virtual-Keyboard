# AI Virtual Keyboard with Hand Gesture Recognition

## 🚀 Overview
An innovative AI-powered virtual keyboard that allows users to type without physical contact using hand gestures. This project leverages computer vision and artificial intelligence to create a touchless typing interface, making it particularly relevant in today's contactless technology trend.

## ✨ Key Features
- **Real-time Hand Detection**: Utilizes advanced AI algorithms for precise hand tracking
- **Gesture-Based Interaction**: Types characters based on finger pinch gestures
- **Visual Feedback**: Dynamic visual feedback for hover and click states
- **External App Integration**: Works with any application that accepts keyboard input
- **Adjustable Interface**: Customizable keyboard layout and sensitivity
- **Low Latency**: Real-time processing with minimal delay
- **User-Friendly Controls**: Simple commands for quitting and clearing text

## 🛠️ Technologies Used
- **Python**: Core programming language
- **OpenCV**: Real-time computer vision and image processing
- **CVZone**: Advanced hand detection and tracking
- **NumPy**: Numerical computing and array operations
- **PyNput**: Keyboard control and simulation
- **MediaPipe**: Hand landmark detection (via CVZone)

## 📋 Prerequisites
- Python 3.7 or higher
- Webcam or camera device
- Adequate lighting for hand detection
- Minimum 4GB RAM recommended
- Windows/Linux/MacOS

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/Devmangrani/AI-Virtual-Keyboard.git
cd ai-virtual-keyboard
```
2. Create a virtual environment (recommended):  
```bash
python -m venv venv
source venv/bin/activate
```
3. Install the required dependencies:  
```bash
pip install -r requirements.txt
```

## 🎮 Usage

1. Run the program:
```bash
python keyboard.py
```
2. Position your hand in the webcam's view
3. Gesture-based typing will commence
4. Adjust settings as needed (see Configuration section)

2. Position your hand in front of the camera:
   - Keep your hand approximately 30-50cm from the camera
   - Ensure good lighting conditions
   - Maintain a clear background for better detection

3. Controls:
   - Hover your index finger over keys to select
   - Pinch your index finger and thumb together to "press" a key
   - Press 'q' on physical keyboard to quit
   - Press 'c' on physical keyboard to clear typed text

## 🎯 Hand Gestures Guide
1. **Hover**: Point index finger at desired key
2. **Click**: Bring thumb and index finger together (pinch)
3. **Optimal Distance**: Maintain 30-50cm distance from camera
4. **Hand Position**: Keep palm facing the camera for best detection

## 🔧 Customization
You can modify the following in `keyboard.py`:
- Keyboard layout and size
- Detection sensitivity
- Key spacing and size
- Visual appearance
- Gesture detection threshold

## 💡 Applications
- **Contactless Interfaces**: Perfect for public kiosks and shared devices
- **Healthcare**: Sterile environments where physical contact is restricted
- **Interactive Displays**: Museums, exhibitions, and public spaces
- **Accessibility**: Alternative input method for users with specific needs
- **Smart Homes**: Touchless control systems
- **Education**: Interactive learning environments

## 🚨 Troubleshooting
1. **Poor Detection**:
   - Ensure adequate lighting
   - Keep background clutter-free
   - Adjust hand position and distance

2. **Lag Issues**:
   - Close resource-heavy applications
   - Check camera resolution settings
   - Ensure system meets minimum requirements

3. **Camera Not Found**:
   - Check camera connections
   - Verify camera permissions
   - Try different USB ports

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments
- CVZone library developers
- OpenCV community
- Hand detection model contributors

## 📞 Contact
- Your Name : Dev Mangrani
- GitHub: [@Devmangrani](https://github.com/Devmangrani)
- Email: devmangrani@gmail.com

---
⭐️ If you found this project interesting, please consider giving it a star!

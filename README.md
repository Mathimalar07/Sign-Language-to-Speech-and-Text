**Hand Gesture Translator**
**Sign Language to Text & Speech Converter**

This project is a real-time hand gesture recognition system that translates sign language into both text and speech using computer vision and machine learning. It is developed to empower individuals with hearing or speech impairments by enabling seamless communication with others.

**✨ Key Features**
Live Gesture Recognition via webcam

Accurate Gesture Classification using a trained Random Forest Classifier

Instant Text Display of identified signs

Offline Speech Output using a text-to-speech engine

Interactive GUI designed with Tkinter for ease of use

**🛠 Tech Stack**
Frontend: Tkinter (Python GUI Library)

Computer Vision: OpenCV, MediaPipe

**Machine Learning:**

Scikit-learn (Random Forest Classifier)

Pickle (Model Serialization)

Data Storage: CSV (for hand landmark data and labels)

Text-to-Speech: pyttsx3 (offline TTS engine)

**🔍 Workflow**
Capture: The webcam streams real-time video of hand gestures.

Detection: MediaPipe identifies hand landmarks (x, y, z coordinates).

Classification: The extracted features are passed to a trained Random Forest model.

Output: The predicted gesture label is displayed as text and vocalized using TTS.

**🚀 Future Enhancements**
Multi-Hand Support: Enable recognition of gestures from both hands

Expanded Dataset: Add more sign variations for improved accuracy

Gesture Sequences: Recognize full sentences formed by gesture sequences

Multilingual Support: Translate recognized signs into multiple languages

**💡 Use Case**
This application serves as a real-time communication bridge for individuals with hearing or speech disabilities. By converting sign language into spoken words and readable text, it fosters better interaction and inclusion in everyday conversations.

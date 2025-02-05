# 📷 AI-Powered Camera Description App

An AI-driven mobile application that continuously captures images and generates real-time descriptions using the **Gemini API**. The app allows users to receive **text-based or audio feedback**, providing a seamless way to understand visual surroundings.

---

## 🚀 Features

- **Continuous Camera Capture** – The app captures an image **every 5 seconds**.
- **AI-Powered Image Description** – Sends captured images to **Gemini API** for processing and generates a **short text description**.
- **Real-Time Display** – The generated description is displayed immediately on the screen.
- **Audio Feedback (Optional)** – Converts text descriptions to speech using **Text-to-Speech (TTS)**.
- **Adjustable Capture Frequency** – Users can set the capture interval (e.g., **2s, 5s, 10s**).
- **Data Storage (Optional)** – Allows saving images and descriptions for later review.

---

## 🛠️ Tech Stack

- **Frontend:** React Native (for cross-platform support) / Native Android (Kotlin) / iOS (Swift)
- **Backend:** Gemini API for image processing
- **APIs & Libraries:**
  - Camera API (React Native Vision Camera / Android CameraX / iOS AVFoundation)
  - Gemini AI API (for image descriptions)
  - Text-to-Speech (Google TTS / iOS Speech API)

---

## 📲 Installation & Setup

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/VIDAI.git
   cd VIDAI
   ```

2. **Install Dependencies**
   ```sh
   npm install  # or yarn install
   ``` 

3. **Run the App**
   ```sh
   npx react-native run-android   # For Android
   npx react-native run-ios       # For iOS
   ```

---

## 📸 How It Works

1. **User enters their Gemini API key.**
2. **Camera remains active, capturing images every 5 seconds.**
3. **Each image is sent to the Gemini API for description.**
4. **The result is displayed on the screen and optionally read aloud.**
5. **Users can adjust settings or save data as needed.**

---

## 📌 Use Cases

- **Visual Assistance for the Blind** – Helps visually impaired users understand their surroundings.
- **Surveillance & Monitoring** – Captures and logs visual data periodically.
- **Research & Automation** – Analyzing environmental changes over time.

---

## 🛡️ Security & Privacy
- **User API keys are not stored.** They are used only during the session.
- **Images are processed in real-time and not saved unless the user enables storage.**

---

## 🔥 Future Enhancements
- **Object & Text Recognition** – Detect specific objects or read texts in images.
- **Gesture-Based Controls** – Hands-free interaction for accessibility.
- **Cloud Storage Integration** – Save images and descriptions securely.

---

## 🤝 Contributing

Contributions are welcome! Feel free to **fork the repo**, make improvements, and submit a **pull request**.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 📧 Contact

For any questions or suggestions, reach out at: rakibahmed642@gmail.com.com

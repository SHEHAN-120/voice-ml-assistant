# Voice Assistant Using Python

A simple voice assistant project created using Python that can respond to  speech commands, tell the current time, search Wikipedia, and exit on command.

---

## ✨ Features

* 🌐 **Speech Recognition**: Converts your spoken words into text using Google Speech Recognition.
* ⏰ **Time Reporting**: Tells you the current time.
* 🔍 **Wikipedia Search**: Allows you to search for information from Wikipedia.
* ❌ **Exit Command**: Terminates the assistant with a voice command like "exit" or "stop".

---

## 📚 Techniques Used

* **Speech Recognition**: Implemented using the `speech_recognition` library.
* **Text-to-Speech (TTS)**: Implemented with the `pyttsx3` library to speak responses.
* **Wikipedia Search**: Integrated using the `wikipedia` module to fetch short summaries.
* **Command Handling**: Simple keyword-based command processing using conditional statements.

---

## 🛠️ Tools & Libraries

* [speech\_recognition](https://pypi.org/project/SpeechRecognition/) - for converting speech to text
* [pyttsx3](https://pypi.org/project/pyttsx3/) - for text-to-speech
* [wikipedia](https://pypi.org/project/wikipedia/) - to fetch summaries from Wikipedia
* [datetime](https://docs.python.org/3/library/datetime.html) - for getting the current time

---

## ⚡ How to Run

1. Install the required libraries:

2. Make sure  microphone is connected and functioning.

3. Run the Python code:

4. Speak your command when prompted.

   * "time"
   * "wikipedia"
   * "exit"

---

## ❓ Sample Commands

* **"What is the time?"**  → Assistant will tell the current time.
* **"Search Wikipedia"** → Will prompt to speak a topic, then read a summary.
* **"Stop"** or **"Exit"** → Ends the assistant.

---

## ⚠ Challenges Faced

* **Handling Ambient Noise**: Required adjusting microphone input to avoid background interference.
* **Disambiguation Errors**: Wikipedia often returns multiple results; had to catch `DisambiguationError`.
* **Speech Misrecognition**: Sometimes Google Speech Recognition failed or misunderstood commands.
* **Continuous Listening**: Managing an infinite loop with graceful exit conditions.



---

## ✅ License

This project is open-source and free to use under the MIT License.

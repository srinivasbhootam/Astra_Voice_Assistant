# **Astra Voice Assistant**

=====================================================================
                           🌟 ASTRA VOICE ASSISTANT 🌟
=====================================================================

## **Description**
Astra is a cutting-edge, voice-activated AI assistant built in Python. It leverages the **OpenAI API** (e.g., using *gpt-3.5-turbo*) to dynamically answer your questions, provides real-time weather updates via the **OpenWeatherMap API**, and offers fun interactions plus reminder management — all controlled entirely by your voice!

---

## **Features**
- 🚀 **General AI Q&A:**  
  Uses the OpenAI API (e.g., *gpt-3.5-turbo*) to generate natural, conversational responses.
- 🌤 **Weather Updates:**  
  Retrieves live weather information for any city using the OpenWeatherMap API.
- 🎉 **Fun Interactions:**  
  Delivers random jokes or fun facts for a playful, engaging experience.
- 📝 **Reminder Management:**  
  Lets you add and view personal reminders.
- 🎙 **Voice Activation:**  
  Integrates speech recognition (via Google Speech Recognition) and text-to-speech (using pyttsx3) for a hands-free interactive experience.

---

## **Installation**
1. **Clone the Repository:**
   ```bash
   git https://github.com/srinivasbhootam/Astra_Voice_Assistant
   cd Astra-voice-assistant


## **Install Dependencies: Ensure you have Python 3 installed, then run:**
pip install python-dotenv SpeechRecognition pyttsx3 PyAudio requests

## **Configure Environment Variables: Create a file named Astra.env in the project root with the following content (replace with your actual keys):**

OPENAI_API_KEY=your-google-ai-api-key

OPENWEATHER_API_KEY=your-openweather-api-key

## **Usage**

- **🚀 Launch the Assistant:**  
  Run the project as a Python script or in a Jupyter Notebook. Astra will greet you and wait for you to press Enter to start listening.

  - **🗣 Interact with Astra:**  
  - **General Questions:**  
    Ask questions like *"Capital of france"* or *"Capital of france?"*
  - **🌤 Weather:**  
    Say **"weather"** and then provide a city name (e.g., **"Detroit"**) to get current weather information.
  - **🎉 Fun Interaction:**  
    Say **"fun"** to receive a random joke or fun fact.
  - **📝 Reminder Management:**  
    - Say **"add reminder"** to add a new reminder.  
    - Say **"show reminders"** to view your saved reminders.

## **Project Structure**

- **🔑 Astra.env**  
  Contains your API keys. *Keep this file secure and private.*

- **📄 Main Code File**  
  Contains all the source code for Astra (voice input/output, API calls, command processing).

- **📘 README.md**  
  This file, providing project details and usage instructions.


## **Challenges Faced**
- **💡 Dynamic AI Responses:**  
  I initially tried using Wikipedia and Google Search for answers, but they were inconsistent and didn't sound conversational.

- **🔍 API Selection:**  
  Finding a free API that was both reliable and dynamic was challenging. Ultimately, the OpenAI API (gpt-3.5-turbo) proved to be the best solution.

- **🎤 Voice Recognition Accuracy:**  
  Fine-tuning the speech recognition to work well in various environments was difficult. I had to adjust settings like ambient noise calibration and microphone sensitivity to improve accuracy.

## **Future Work & Further Analysis**
- **🧠 Enhanced Natural Language Understanding:**  
  Integrate advanced NLP techniques to better handle ambiguous or multi-part queries.
- **💻 Local Inference Options:**  
  Explore running open-source models locally (using libraries like Hugging Face Transformers) to reduce dependency on external APIs and improve privacy.
- **🔧 Expanded Functionality:**  
  Add features such as scheduling appointments, integrating with calendar APIs, or even controlling smart home devices.
- **⚙️ Improved Error Handling:**  
  Enhance the robustness of error handling, especially in noisy environments, to make the assistant more resilient.
- **🎨 User Customization:**  
  Allow users to customize responses, adjust voice settings, or add personal vocabulary for a more personalized interaction.

## **Contributing**
Contributions, suggestions, and bug fixes are welcome!  
Feel free to fork the repository, make your changes, and submit a pull request.  
If you encounter any issues or have ideas for improvements, please open an issue [here](https://github.com/yourusername/astra-voice-assistant/issues).


## **License**
This project is licensed under the **MIT License**. See the LICENSE file for more details.

## **Acknowledgments**
- 🙏 Special thanks to the developers behind **OpenAI**, **OpenWeatherMap**, **SpeechRecognition**, **pyttsx3**, and all the open-source libraries that made this project possible.
- 🌟 Inspired by various open-source voice assistant projects and the power of AI in everyday applications.


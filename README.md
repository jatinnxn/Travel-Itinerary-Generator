🌍 Travel Itinerary Generator ✈️

An AI-powered travel planner that creates personalized itineraries based on user preferences.

📌 Features

✔️ Collects user preferences (location, duration, budget, interests, accommodation).
✔️ Generates clarifying questions to refine inputs for a more accurate itinerary.
✔️ Provides a structured day-by-day travel plan with activities, dining, and accommodation.
✔️ Uses Google Gemini AI (free) instead of OpenAI’s paid API.
✔️ Built with Streamlit for a user-friendly web interface.

🚀 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-repo/travel-itinerary-generator.git
cd travel-itinerary-generator

2️⃣ Install Dependencies

pip install streamlit google-generativeai

3️⃣ Set Up Google Gemini API Key

Get your API key from Google AI and add it to your script:

genai.configure(api_key="YOUR_GEMINI_API_KEY")

4️⃣ Run the App

streamlit run app.py

🛠️ Usage

1️⃣ Enter trip details (location, duration, budget, interests).
2️⃣ AI generates clarifying questions to refine inputs.
3️⃣ Review & update responses based on AI suggestions.
4️⃣ Get a complete itinerary with activities, dining, and accommodation.

🛠️ Tech Stack
	•	Frontend: Streamlit
	•	AI Model: Google Gemini AI
	•	Hosting: (To be added if deployed)

🤖 Why Google Gemini AI?

✅ Free to use (vs. OpenAI’s paid API)
✅ High-quality AI-generated itineraries
✅ Easy Python integration

🚀 Future Enhancements

🔹 Google Maps Integration for navigation
🔹 Multi-language support
🔹 Real-time budget estimation

📜 License

This project is open-source and available under the MIT License.

🌍 Happy Traveling! 🚀

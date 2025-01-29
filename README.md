# 🌍 Multi-Step Travel Itinerary Generator ✈️

## Overview
This project is a **Multi-Step Travel Itinerary Generator** built using **Google Gemini API** and **Streamlit**. It allows users to generate a personalized, structured travel itinerary based on their preferences. The system follows a guided interaction process to refine user input and provide detailed day-by-day travel plans.

## Features
- Interactive UI for collecting travel preferences.
- AI-driven clarification of user inputs.
- Automatic generation of a structured, day-by-day itinerary.
- Recommendations for attractions, activities, dining, and accommodations.

## Tech Stack
- **Python**
- **Streamlit** (for UI)
- **Google Gemini API** (for AI-based itinerary generation)

## Installation
### Prerequisites
- Python 3.x installed
- A valid **Google Gemini API Key**
- Required Python libraries installed

### Setup Instructions
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/travel-itinerary-generator.git
   cd travel-itinerary-generator
   ```
2. **Install Dependencies:**
   ```sh
   pip install streamlit google-generativeai
   ```
3. **Set Up API Key:**
   - Open the Python script and replace `YOUR_GEMINI_API_KEY` with your actual API key.
   ```python
   genai.configure(api_key="YOUR_GEMINI_API_KEY")
   ```
4. **Run the Streamlit App:**
   ```sh
   streamlit run app.py
   ```

## Usage
1. Enter your travel destination, duration, budget, interests, and accommodation preferences.
2. The system will generate clarifying questions to refine your input.
3. A structured, personalized itinerary will be generated, including:
   - Morning, afternoon, and evening activities.
   - Dining recommendations.
   - Accommodation suggestions.

## Example Output
**User Inputs:**
```
Location: Paris
Duration: 5 days
Budget: Moderate
Interests: Culture, food, sightseeing
Accommodation: Mid-range
Additional Notes: None
```

**Generated Itinerary:**
```
Day 1:
- Morning: Visit Eiffel Tower, breakfast at Café de Flore.
- Afternoon: Louvre Museum tour.
- Evening: Seine River Cruise and dinner at Le Meurice.

...
```

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## License
MIT License

## Contact
For any inquiries, contact jatinavhad756@gmail.com or visit the [GitHub Repository](https://github.com/yourusername/travel-itinerary-generator).


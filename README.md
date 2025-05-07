# Weather-Advisor
**Weather Advisor** is a versatile weather forecasting tool that combines the power of data visualization and natural language processing (NLP) to provide accurate and insightful weather information. The application offers a user-friendly interface with two main interaction modes: **Dashboard** and **Chatbot**, allowing users to choose their preferred way to access weather data.

## 📌 Features:
- **Hybrid Interface:** Seamlessly switch between the **Dashboard** and **Chatbot** modes.
- **Weather Forecasting:** Get weather data for today, tomorrow, or the next few days.
- **Customizable Queries:** Use natural language to ask about temperature, humidity, wind speed, precipitation, and more.
- **Dynamic Visualizations:** Interactive charts for temperature trends and precipitation patterns.

## 🛠️ Technology Stack:
- **Python:** Core programming language.
- **Jupyter Notebook:** Interactive development environment.
- **pandas:** Data manipulation and analysis.
- **spaCy:** NLP for parsing user queries.
- **Matplotlib, Seaborn, Plotly:** Data visualization.
- **IPyWidgets:** Interactive UI components.
- **WeatherAPI:** Real-time weather data.

## 🚀 How It Works:
1. **Setup:** The user selects the city and forecast period via the dashboard or types a natural language query in the chatbot.
2. **Data Fetching:** The application retrieves weather data from the OpenWeather API.
3. **Data Processing:** Extracts relevant weather attributes (temperature, humidity, precipitation, etc.).
4. **Visualization:** Dynamically generated charts provide a visual representation of weather trends.
5. **Natural Language Response:** The chatbot interprets questions and returns concise, accurate answers.

## Prerequisites
- Python 3.8+
- Jupyter Notebook
- OpenWeather API key (add to `.env` file)

Before running the Weather Advisor application, you'll need to get an API key from [WeatherAPI](https://www.weatherapi.com/) and set up the environment file (`.env`).

## Steps to Set Up

### 1. **Sign Up for WeatherAPI**
   - Visit the [WeatherAPI website](https://www.weatherapi.com/).
   - Sign up for a new account.
   - After signing up, **verify your email**.

### 2. **Get Your API Key**
   - Once your email is verified, log in to your WeatherAPI account.
   - Go to the [API key page](https://www.weatherapi.com/my/).
   - Copy your **API key** from this page.

### 3. **Set Up the `.env` File**
   - Create a `.env` file in the root directory of your project.
   - Add the following line to the `.env` file:
     ```
     OPENWEATHER_API_KEY=your_api_key_here
     ```
     Replace `your_api_key_here` with the API key you just copied.

### 4. **Upload the `.env` File**
   - Upload the `.env` file to the **file uploader under the Setup and Configuration** section in this repository.

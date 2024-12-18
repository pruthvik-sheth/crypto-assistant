# Crypto Assistant: AI-Powered Cryptocurrency Analysis Platform

## Overview

Crypto Assistant is a comprehensive cryptocurrency analysis platform that combines real-time market data with advanced AI models (TimeGPT and LLaMA 3.2) to provide intelligent market insights, price forecasting, and interactive analysis tools.

## Project Demo Link

**Video Walkthrough:** [Watch the Demo Video](https://youtu.be/kBMPZk--sE0)

## Key Features

- 📊 Real-time cryptocurrency price tracking and analysis
- 🤖 AI-powered price forecasting using TimeGPT
- 🧠 Market insights and analysis using LLaMA 3.2
- 💬 Interactive chat interface for market queries
- 📈 Advanced technical indicators and charting
- 📰 News sentiment analysis and integration

## Technologies Used

- **Frontend**: Streamlit, Plotly
- **Backend**: Python, MongoDB
- **AI Models**: TimeGPT, LLaMA 3.2
- **Data Sources**: AlphaVantage API
- **Additional Libraries**: Pandas, NumPy, NLTK, TextBlob

## Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/crypto-assistant.git
cd crypto-assistant
```

2. Create and activate virtual environment

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install required packages

```bash
pip install -r requirements.txt
```

4. Set up environment variables
   Create a `.env` file in the root directory with:

```
ALPHA_VANTAGE_API_KEY=your_api_key_here
NIXTLA_API_KEY=your_timegpt_key_here
```

## Usage

1. Start the application

```bash
streamlit run main.py
```

2. Access the dashboard at `http://localhost:8501`

## Project Structure

```
crypto_assistant/
├── main.py                 # Main Streamlit application
├── services/              # Service modules
│   ├── data_service.py    # Data handling
│   ├── forecast_service.py # TimeGPT integration
│   ├── analysis_service.py # Market analysis
│   └── llm_service.py     # LLaMA integration
├── config/               # Configuration files
└── data/                # Data storage
```

## Features

- Real-time market data monitoring
- Advanced technical analysis
- AI-powered price forecasting
- Market sentiment analysis
- Interactive chat interface
- Customizable dashboard
- Historical data analysis

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- TimeGPT for forecasting capabilities
- LLaMA 3.2 for market analysis
- AlphaVantage for market data
- Streamlit for the interactive interface

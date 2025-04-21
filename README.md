# AI Studio Project with Microsoft: Time-Series Forecasting of Water Quality Indices

## Description
Microsoft and other technology companies are increasing their investments in computionally expensive AI(i.e. larger data centers). These ata centers consume large quantities of water, prompting Microsoft to make a bold environmental commitment to answer the question; can we quantitatively forecast future water quality and availability? This is crucial first step to understanding opportunities to ameilorate environmental conditions. 

Our project addresses this question by forecasting water quality indices using machine learning and generative AI techniques. Specifically, we leverage Long Short-Term Memory (LSTM) models and the OpenAI API to generate predictive insights.


 ## Set-Up Instructions
Follow these steps to set up the project locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/anissakp/BTTAI-AI-Studio.git
   ```

2. **Install Dependencies at Root Directory**
   ```bash
   cd ChatBot
   pip install flask
   pip install openai
   pip install python-dotenv
   ```
3. **Environment Configuration**

   Create a .env file in root directory to store OpenAI API key:
   ```bash
   API_KEY = "your_openai_api_key_here"
   ```

## Usage
To run the application locally:
   ```bash
   cd ChatBot
   python app.py
   ```

## Team Members
- Anissa Patel: Boston University
- Tishya Kasliwal: Northeastern University
- Hau Phan: Smith College
- Aryamani Boruah: UMass Amherst

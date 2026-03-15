# AI Studio Project with Microsoft: Time-Series Forecasting of Water Quality Indices


![pexels-zelch-30596255](https://github.com/user-attachments/assets/6d472554-5d7a-494d-b4c6-6c2d7f40f827)


## Description
Microsoft and other technology companies are increasing their investments in computionally expensive AI (e.g., larger data centers). These data centers consume large quantities of water, prompting Microsoft to make a bold environmental commitment to answer the question; **can we quantitatively forecast future water quality and availability?** This is crucial first step to understanding opportunities to ameilorate environmental conditions. 

Our project addresses this question by forecasting water quality indices using machine learning and generative AI techniques. Specifically, we leverage Long Short-Term Memory (LSTM) models and the OpenAI API to generate predictive insights. 

Another goal of this project is **making satellite data more acessible**:

- **Accessibility Challenges**:  
  While satellite data is publicly available, it is often difficult to access and utilize effectively.

- **Technical Barriers**:  
  Organizations that could benefit from platforms like Microsoft Planetary Computer frequently lack the technical expertise needed to analyze satellite data.


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

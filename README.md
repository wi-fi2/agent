# **Stock Analysis Assistant with Llama Agent**

This project is a conversational assistant that combines a locally hosted **Meta-Llama-3-8B-Instruct** model with the **Alpha Vantage API** to provide real-time stock market data and general conversational capabilities.

---

## **Features**

### **1. Stock Market Integration**
- Fetches real-time stock prices using the [Alpha Vantage API](https://www.alphavantage.co/).
- Provides stock details such as:
  - Open
  - Close
  - High
  - Low
  - Volume

### **2. Conversational AI**
- Powered by the locally hosted **Meta-Llama-3-8B-Instruct** model.
- Capable of answering general queries and engaging in conversations.

### **3. Automatic Stock Symbol Detection**
- Automatically identifies stock symbols (e.g., TSLA, AAPL) from user input.

### **4. Error Handling**
- Gracefully handles invalid inputs and API errors.

---

## **Requirements**

- **Python**: Version 3.8 or later
- **Meta-Llama-3-8B-Instruct server**: Locally hosted
- **Alpha Vantage API Key**: Obtain a free key from [Alpha Vantage](https://www.alphavantage.co/)

---

## **Setup**

### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/stock-analysis-assistant.git
cd stock-analysis-assistant

You: What is the stock price of TSLA?
Assistant: 
Stock: TSLA
Time: 2025-01-09 15:00:00


2. Install Dependencies
Ensure you have the required Python library installed:

bash
Copy code
pip install requests
3. Configure the Llama Server
Start your locally hosted Meta-Llama-3-8B-Instruct server with the following settings:

Server Address: 127.0.0.1
Port: 8080
API Key: llama
Ensure the Llama server is running before launching the assistant.

4. Set Up Alpha Vantage
Sign up for a free API key from Alpha Vantage.
Replace YOUR_ALPHA_VANTAGE_API_KEY in the code with your API key.
5. Run the Assistant
bash
Copy code
python app.py
How to Use
Launch the assistant by running python app.py.
The assistant will greet you and prompt for input.

Open: 123.45
High: 125.67
Low: 122.34
Close: 124.56
Volume: 567890

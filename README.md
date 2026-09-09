AI E-Commerce Customer Support Agent
An AI-powered customer support agent for e-commerce, built with Streamlit. It helps customers with product-related questions and provides an interactive support experience.

Features
🤖 AI-powered customer support
🛍️ E-commerce product assistance
💬 Interactive chat interface
🔎 Product and order-related queries
📊 Streamlit-based user interface
🗄️ SQLite database integration
Tech Stack
Python
Streamlit
SQLite
AI / LLM
Pandas
Project Structure
AI E Commerce customer support Agent/
│
├── app.py
├── ecommerce.db
├── .gitignore
└── README.md

Installation
Clone the repository:

git clone https://github.com/lakshmiamuthu3/ai-ecommerce-customer-support-agent.git

Go to the project directory:

cd ai-ecommerce-customer-support-agent

Install the required dependencies:

pip install -r requirements.txt

Run the Application
Start the Streamlit application:

streamlit run app.py

Then open the URL shown in the terminal, usually:

http://localhost:8501

Environment Variables
If the application uses API keys, create a .env file or use Streamlit secrets.

Do not upload API keys or passwords to GitHub.

Example:

OPENAI_API_KEY=your_api_key_here

Future Improvements
Add order tracking
Add user authentication
Improve AI response accuracy
Add analytics dashboard
Deploy the application online
Author
Lakshmiamuthu3

License
This project is for educational and portfolio purposes.

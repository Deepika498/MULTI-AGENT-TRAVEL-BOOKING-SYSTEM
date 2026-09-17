 ✈️ Multi-Agent Travel Booking System

An AI-powered travel planning system built using **LangGraph, Groq, Tavily, AviationStack, and PostgreSQL**.

The system uses multiple specialized AI agents that work together to search for flights, find hotels, generate a personalized itinerary, and provide a final travel plan.

 🚀 Features

- ✈️ Flight Agent – Fetches flight information using AviationStack API
- 🏨 Hotel Agent – Searches for hotel information using Tavily
- 🗓️ Itinerary Agent – Generates a personalized travel itinerary using Groq LLM
- 🧠 Final Agent – Combines all results into a final travel plan
- 💾 PostgreSQL Checkpointing – Maintains persistent conversation state
- 🌐 Streamlit Frontend – Interactive web interface for travel requests
- 📥 Download Travel Plan – Generated plans can be downloaded as Markdown files

 🛠️ Tech Stack

- Python
- LangGraph
- LangChain
- Groq
- Tavily Search
- AviationStack API
- PostgreSQL
- Streamlit

 📁 Project Structure

Multi-Agent-Travel-Booking-System/
│
├── main.py
├── frontend.py
├── tools/
│   ├── flight_tool.py
│   └── tavily_tool.py
├── .gitignore
└── README.md
 ⚙️ Setup

1. Clone the repository

bash
git clone https://github.com/Deepika498/MULTI-AGENT-TRAVEL-BOOKING-SYSTEM.git
cd MULTI-AGENT-TRAVEL-BOOKING-SYSTEM

2. Create and activate a virtual environment
python -m venv langgraph_env3

For Windows:
langgraph_env3\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

4. Configure environment variables
Create a .env file and add your API keys:
GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
AVIATIONSTACK_API_KEY=your_aviationstack_api_key

5.Run the Application-
Start the Streamlit frontend:
python -m streamlit run frontend.py
Then open the localhost URL shown in the terminal.

💡 Example Query
Plan a complete 7-day Japan trip including flights, hotels and sightseeing under ₹2 lakhs.
The system processes the request through multiple AI agents and generates a complete travel plan.

🔄 Agent Workflow
User enters a travel request.
Flight Agent fetches flight information.
Hotel Agent searches for suitable hotels.
Itinerary Agent creates the travel itinerary.
Final Agent combines all the information.
The final travel plan is displayed in the Streamlit interface.
The generated plan can be downloaded as a Markdown file.
👩‍💻 Author

Deepika Sahu
B.Tech – Information Technology


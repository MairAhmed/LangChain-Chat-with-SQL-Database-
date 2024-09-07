# LangChain-Chat-with-SQL-Database-
 A Streamlit app that allows users to query SQLite or MySQL databases using LangChain agents powered by Groq's LLM for natural language processing.

This project is a Streamlit-based web application that allows users to interact with SQL databases (SQLite or MySQL) using the LangChain framework and Groq's LLM. It enables users to ask questions about their database and get insights using natural language queries. The app supports both local SQLite databases and remote MySQL databases.

# Features:

LangChain Integration: Leverages LangChain agents to interact with SQL databases.

Multiple Databases: Supports SQLite (student.db) and MySQL databases.

LLM-Powered: Uses Groq's ChatGroq model (Llama3-8b-8192) to generate responses.

Streamlit Interface: Provides an easy-to-use web interface for querying databases.

Dynamic Querying: Users can input SQL-like queries in natural language to retrieve information from the database.

# Demo:

Installation part

Prerequisites:

Python 3.8+

Streamlit

Groq API Key

MySQL Database (optional)

# Clone the Repository:

git clone https://github.com/yourusername/langchain-sql-db-chat.git

cd langchain-sql-db-chat

# Install Dependencies

Install the required Python packages by running:

pip install -r requirements.txt

# Set Up Environment Variables

Create a .env file in the root of the project and add the following:

# Groq API Key

GROQ_API_KEY=your_groq_api_key


# Running the Application

You can run the Streamlit app using the following command

streamlit run app.py

This will launch the app in your default browser.

# Database Configuration

When you launch the app, you will be prompted to select the database you want to connect to:


SQLite Database: The app will use the default student.db file located in the project directory.

MySQL Database: You can input your MySQL credentials (host, user, password, database name) in the sidebar.

Make sure to provide your Groq API Key in the sidebar to enable LLM-based querying.

# Usage

Once the app is running, you can:

Select a database from the sidebar (SQLite or MySQL).

Input your Groq API Key in the sidebar.

Ask any query related to the database in natural language using the chat input at the bottom.

Get responses from the Groq-powered LLM agent.















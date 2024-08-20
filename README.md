# Calculating-and-Reporting-Metrics-of-the-RAG-Pipeline



Healthcare Guide Chatbot with RAG and Vector Database
Overview
This project presents a domain-specific chatbot designed to offer personalized healthcare advice by leveraging the capabilities of Large Language Models (LLM) in conjunction with the efficiency of a vector database for data storage and retrieval. By employing Retrieval-Augmented Generation (RAG), the chatbot provides tailored healthcare recommendations based solely on user inputs. The application is built using Flowise and integrates multiple components to ensure accurate and relevant responses to users' healthcare-related queries.

Key Features
Domain Focus: Provides personalized healthcare guidance and recommendations.
RAG-Based Interaction: Utilizes Retrieval-Augmented Generation (RAG) to deliver custom healthcare recommendations.
Core Components:
Recursive Character Text Splitter: Efficiently splits text into manageable chunks for processing.
CSV File Integration: Facilitates the uploading and management of healthcare data.
OpenAI Embeddings: Employs OpenAI's text-embedding-3-large model to embed user queries and context.
Pinecone Vector Database: Stores and indexes data using Pinecone’s vector database for quick retrieval.
Conversational Retrieval QA Chain: Ensures relevant information is retrieved during user interactions.
ChatOpenAI Interface: Provides the main chat interface for user interaction.
Target Audience
The application is designed for individuals seeking personalized healthcare advice. It delivers quick and accurate responses to healthcare queries, tailored to the user's specific needs and input.

Getting Started
Prerequisites
Node.js (v14 or higher)
npm
Flowise
Installation Instructions
Clone the repository:
sh
Copy code
git clone https://github.com/manikanta-reddy-thikkavarapu-neu/Calculating-and-Reporting-Metrics-of-the-RAG-Pipeline.git
Navigate to the project directory:
sh
Copy code
cd Calculating-and-Reporting-Metrics-of-the-RAG-Pipeline
Running the Application
Start Flowise:
sh
Copy code
npx flowise start
Open your browser and navigate to http://localhost:3000 to access the chatbot interface.
Ensure that your OpenAI and Pinecone API keys are correctly configured and running.
Use chatbot.html by launching it through Live Server.
Usage Guide
Upload your healthcare data CSV file through the interface provided.
Enter your healthcare-related query into the input box.
The chatbot processes your query and returns a personalized response, drawing from both the embedded healthcare data and the LLM.
Evaluation and Testing
The chatbot has been rigorously tested across a wide range of healthcare queries to ensure performance, accuracy, and usability. Example queries include:

"What are the symptoms of diabetes?"
"Recommend a diet plan for managing hypertension."
"How can I effectively manage stress?"
Video Demonstration
A comprehensive video walkthrough demonstrating the application's features and usage is available here.

Documentation Links
Flowise Documentation: Flowise Documentation
OpenAI Documentation: OpenAI Documentation
Pinecone Documentation: Pinecone Documentation
This version keeps the content structured and emphasizes the key features, ensuring that the instructions are clear and the benefits of the application are well-articulated.







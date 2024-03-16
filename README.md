Chat with Websites

This project enables users to interact with websites through a chat interface powered by conversational AI. Leveraging Streamlit, an open-source app framework for Machine Learning and Data Science projects, users can engage in conversations with websites in a natural language format.

Features:

Conversational Interface: The user interacts with the website by typing messages into the chat interface.
Context-Aware Responses: The system generates responses based on the context of the conversation, providing relevant and meaningful answers.
Web Scraping: The system extracts text content from the specified website URL using web scraping techniques.
Natural Language Processing: Conversational AI models process user inputs and generate appropriate responses, simulating human-like interactions.

Dynamic Session Management: The system maintains a chat history and session state, enabling seamless continuation of conversations across interactions.
Implementation Details:

Language and Frameworks: Implemented using Python programming language and Streamlit framework.
Libraries: Utilizes various libraries such as langchain, langchain_openai, langchain_core, and dotenv for natural language processing, web scraping, and conversational AI functionalities.
Vectorization: Converts text data into vector representations using Chroma and OpenAIEmbeddings for efficient processing and context understanding.
Conversational Chains: Implements conversational chains to handle user queries, retrieve relevant information, and generate responses based on context and history.
User Interface: Provides a simple and intuitive user interface using Streamlit's chat_input and chat_message components for text input and display.
Usage:

Enter the URL of the website you want to interact with in the sidebar.
Type your message in the chat input box and press Enter to send.
The system will generate responses based on the conversation context and display them in the chat interface.
Note: Ensure that the website URL is valid and accessible for successful interaction.

This project enhances user engagement with websites by enabling conversational interactions, facilitating information retrieval, and providing personalized responses tailored to user queries.

# Chatbot-Sam---Intelligent-AI-Assistant-with-Web-Search-Capabilities
Chatbot Sam is a sophisticated conversational AI that blends neural network-based intent recognition with real-time web search functionality. Built with PyTorch and powered by sentence transformers, Sam can engage in natural conversations while fetching accurate information from Wikipedia and Google Search APIs.

Features

🤖 Core Chatbot Capabilities
1)Intent Recognition:    Uses neural network-based classification to understand user intents
2)Pattern Matching:      Handles common conversation patterns like greetings, farewells, compliments, and more
3)Contextual Responses:  Provides appropriate responses based on classified intents
4)Learning System:       Trained on custom intents dataset with expandable patterns

🔍 Real-time Information Retrieval
1)Wikipedia Integration: Fetches summaries from Wikipedia API for factual queries
2)Google Search: Uses Google Custom Search API to find and scrape relevant information
3)Smart Response Generation: Combines multiple sources for comprehensive answers
4)Yes/No Detection: Intelligently detects questions requiring yes/no answers

🛠 Technical Features
1)PyTorch Neural Network: Custom-built feedforward neural network for intent classification
2)Sentence Transformers: Uses 'all-MiniLM-L6-v2' for semantic text embeddings
3)Dual API Support: Configurable API keys for Wikipedia and Google services
4)BeautifulSoup Web Scraping: Extracts relevant content from web pages
5)Modular Architecture: Separated into training, model, and inference components


Installation & Setup
Prerequisites
Python 3.7+
PyTorch
API keys for:
Wikipedia API
Google Custom Search API


Model Architecture
1)Input Layer: 384-dimensional sentence embeddings
2)Hidden Layer: 64 neurons with ReLU activation
3)Output Layer: Multi-class classification for intent recognition
4)Loss Function: Cross-Entropy Loss
5)Optimizer: Adam with learning rate 0.001

License
This project is open source and available under the MIT License.


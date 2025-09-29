# Chatbot-Sam---Intelligent-AI-Assistant-with-Web-Search-Capabilities
Chatbot Sam is a sophisticated conversational AI that blends neural network-based intent recognition with real-time web search functionality. Built with PyTorch and powered by sentence transformers, Sam can engage in natural conversations while fetching accurate information from Wikipedia and Google Search APIs.

Features

🤖 Core Chatbot Capabilities
Intent Recognition:    Uses neural network-based classification to understand user intents
Pattern Matching:      Handles common conversation patterns like greetings, farewells, compliments, and more
Contextual Responses:  Provides appropriate responses based on classified intents
Learning System:       Trained on custom intents dataset with expandable patterns

🔍 Real-time Information Retrieval
Wikipedia Integration: Fetches summaries from Wikipedia API for factual queries
Google Search: Uses Google Custom Search API to find and scrape relevant information
Smart Response Generation: Combines multiple sources for comprehensive answers
Yes/No Detection: Intelligently detects questions requiring yes/no answers

🛠 Technical Features
PyTorch Neural Network: Custom-built feedforward neural network for intent classification
Sentence Transformers: Uses 'all-MiniLM-L6-v2' for semantic text embeddings
Dual API Support: Configurable API keys for Wikipedia and Google services
BeautifulSoup Web Scraping: Extracts relevant content from web pages
Modular Architecture: Separated into training, model, and inference components


Installation & Setup
Prerequisites
Python 3.7+
PyTorch
API keys for:
Wikipedia API
Google Custom Search API


Model Architecture
Input Layer: 384-dimensional sentence embeddings
Hidden Layer: 64 neurons with ReLU activation
Output Layer: Multi-class classification for intent recognition
Loss Function: Cross-Entropy Loss
Optimizer: Adam with learning rate 0.001

License
This project is open source and available under the MIT License.


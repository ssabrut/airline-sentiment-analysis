# Airline Sentiment Analysis with Transformer and Pinecone

### Overview
---

This project aims to perform sentiment analysis on airline reviews using a Transformer-based model and deploying it with Pinecone, a scalable vector database for building real-time applications. Sentiment analysis is a natural language processing task where the sentiment expressed in a piece of text, such as a review, is determined.

### Objective
---

The primary objective of this project is to develop a robust sentiment analysis model that can accurately classify airline reviews into positive, negative, or neutral sentiments. The Transformer architecture, known for its effectiveness in processing sequential data like text, will be employed for this purpose. Additionally, Pinecone will be utilized for efficient deployment of the model, ensuring real-time inference capabilities.

### Getting Started
---

To replicate this project or use the deployed sentiment analysis model, follow these steps:
1. Clone the Repository

   ```
   git clone https://github.com/ssabrut/airline-sentiment-analysis.git
   ```

2. Copy .env file

   ```
   cp .env.example .env
   ```

3. Get Pinecone API and put to .env file. If you dont have Pinecone account, you must [register](https://app.pinecone.io/?sessionType=signup) first.
4. Create Pinecone index and put the index name to .env file.

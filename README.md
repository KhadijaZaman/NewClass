# NewClass
# LLM Content Evaluation Tool

## Overview
The **LLM Content Evaluation Tool** is a web-based application designed to automatically evaluate webpage content based on semantic SEO principles. It scrapes content from a given URL, processes it using quantitative and qualitative metrics, and outputs a detailed scoring breakdown. This tool is ideal for content creators, marketers, and SEO specialists looking to improve content quality and semantic alignment.

## Key Features
- **Content Scraping:** Uses Python’s `requests` and `BeautifulSoup` libraries to extract text from webpages.
- **Evaluation Metrics:**
  - **Readability & Clarity:** Assesses text using a basic readability proxy.
  - **Keyword Density & Usage:** Measures the frequency of specific keywords (e.g., "SEO") relative to overall content.
  - **Semantic Similarity:** Implements a simple metric based on content length.
  - **Additional Metrics:** Evaluates content structure, macro & micro context coverage, entity & lexical semantics, and internal linking.
- **Interactive Interface:** Built with Streamlit for a user-friendly, real-time scoring experience.
- **Google Colab Deployment:** Hosted in a Google Colab notebook and exposed publicly via Ngrok.

## Repository Structure

## How to Run the Project

### Using Google Colab (Recommended)
1. **Open the Notebook:**  
   Open the https://github.com/KhadijaZaman/NewClass/blob/main/Final_Project_Semantic_SEO_Scoring_Framework_%5B23rd_Feb_2025%5D.ipynb in Google Colab.
2. **Install Dependencies:**  
   Run the cells to install required libraries (Flask, Streamlit, pyngrok, requests, and BeautifulSoup).
3. **Launch the App:**  
   Follow the instructions in the notebook to run the Streamlit app and access it via the Ngrok public URL.

### Running Locally
1. **Clone This Repository:**
   ```bash
   git clone https://github.com/YourUsername/llm-content-evaluation.git
   cd llm-content-evaluation
pip install -r requirements.txt
streamlit run streamlit_app.py

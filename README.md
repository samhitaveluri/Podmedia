 ## Features

- **Automated Summarization:** Using the power of AI, this project can automatically download podcast episodes, transcribe the speech to text, and generate concise summaries.
- **WhisperX for Transcription:** The project employs the WhisperX model to convert spoken words in podcast episodes into text.
- **ChatGPT 3.5 Turbo for Summarization:** The OpenAI ChatGPT 3.5 Turbo model is used to create informative and coherent summaries based on the transcribed text.
- **Frontend with Streamlit:** The summarized content, along with episode details, guest information, and highlights are presented through an interactive and user-friendly Streamlit frontend.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/tekeburak/podcast-summarizer.git
   cd podcast-summarizer

2. Install the required dependencies using pip:
   ```bash
   pip install streamlit modal

3. Deploy backend to Modal:
   ```bash
   modal deploy /content/podcast/podcast_backend.py

4. Run the Streamlit app:
   ```bash
   streamlit run podcast_frontend.py

### Local Usage

1. Access the Streamlit frontend by opening a web browser and navigating to [http://localhost:8501](localhost:8501).
2. On the homepage, you'll find an input field where you can paste the RSS feed URL of the podcast you want to summarize.
3. Click the "Process a Podcast Feed" button to initiate the summarization process.
4. The app will start by downloading the podcast episode in mp3 format and then use the WhisperX model to transcribe the speech to text.
5. Once transcribed, the text data is fed into the ChatGPT 3.5 Turbo model to generate a summary.
6. The summary, along with episode details, guest information, and highlights, will be displayed on the Streamlit interface.
 

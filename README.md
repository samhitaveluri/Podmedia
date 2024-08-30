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

 
 

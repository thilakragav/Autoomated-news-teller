# Automated News Article Summarizer using LLaMA 3.1
.
# Project Description: 
   In the digital age, the overwhelming volume of news makes it difficult for users to stay informed without spending excessive time. This project seeks to solve this challenge by developing an Automated Content Summarizer for News Articles. Using LLaMA, a powerful language model, the system will generate concise, coherent summaries from lengthy news pieces. By leveraging advanced natural language processing techniques, the tool will enhance media consumption efficiency, allowing readers to quickly grasp key insights. This approach not only saves time but also improves information retention, ensuring users stay updated with relevant news in a clear and digestible format.

# How LLaMA is Used in the Project: 
   LLaMA, an open LLM, will power text summarization in the project, extracting key insights from news articles. By fine-tuning its pre-trained model, the system will generate accurate, contextually relevant summaries across various topics. This ensures high-quality, readable summaries, enhancing user experience with concise and meaningful content.

## Installation

1. **Download or Clone the Repository:**

   Download the project files as a ZIP folder or clone the repository using Git.

2. **Extract the Files:**

   If you downloaded the ZIP folder, extract it to your desired location.

3. **Navigate to the Project Directory:**

   Open a terminal or command prompt and navigate to the project directory.

   ```bash
   cd News_Article_Summarizer
   ```

4. **Create a Virtual Environment (Optional but Recommended):**

   It's a good practice to create a virtual environment to manage your project's dependencies.

   ```bash
   python -m venv venv
   ```

   Activate the virtual environment:

   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. **Install Requirements:**

   Install the required packages using `pip`:

   ```bash
   pip install -r requirements.txt
   ```

## Updating Groq Cloud API Key

To use the Groq Cloud LLaMA 3.1 70B Versatile model, you need to set your API key as an environment variable:

1. **Obtain your Groq API key** from the Groq Cloud platform.

2. **Set the API key as an environment variable:**

   - On Windows:
     ```bash
     set GROQ_API_KEY=your_api_key_here
     ```

   - On macOS/Linux:
     ```bash
     export GROQ_API_KEY=your_api_key_here
     ```

## Usage

1. **Run the Application:**

   Start the Streamlit application with the following command:

   ```bash
   streamlit run app/streamlit_app.py
   ```

2. **Open Your Web Browser:**

   After running the command, a new browser window should open. If it doesn't, navigate to `http://localhost:8502` in your web browser.



## Requirements

Make sure to install the following Python packages:

```plaintext
groq
streamlit==1.31.0
python-dotenv==1.0.0
requests==2.31.0
beautifulsoup4==4.12.2
ipywidgets

```

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request.

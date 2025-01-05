# AI Video Summarizer

AI Video Summarizer is a web application that uses Streamlit to provide a user-friendly interface for summarizing video content with the help of AI. It utilizes Google's Gemini 2.0 model and other tools to analyze and generate insights from uploaded video files.

## Features

- Upload and analyze video files in various formats (MP4, MOV, AVI).
- Utilize Google's Gemini 2.0 model for video content analysis.
- Generate detailed and actionable insights based on user queries.
- Display video playback and analysis results in the web interface.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/SAMBITMALLICK2003/AI_Video_Summarizer.git
    cd AI_Video_Summarizer
    ```

2. Create and activate a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Set up environment variables:
    - Create a `.env` file in the root directory.
    - Add your Google API key to the `.env` file:
        ```sh
        GOOGLE_API_KEY=your_api_key_here
        ```

2. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```

3. Open your browser and navigate to `http://localhost:8501` to access the application.

## Deployment

The application is deployed and accessible via the following Streamlit link:
[AI Video Summarizer](https://ai-video-summarizer.streamlit.app/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

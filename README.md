# Meeting Analysis Toolkit🔄

## Overview

The **Meeting Summarizer and Minutes Maker** is a Streamlit-based application that leverages the power of Gemini 2.0 to process meeting recordings and generate valuable outputs such as meeting minutes, summaries, action items, and insights. It also provides a feature to chat with the meeting recording for quick analysis and answers.

---

## Features

1. **Upload Meeting Recordings**: Supports audio and video files in formats like `mp4`, `mov`, `avi`, `mp3`, and `wav`.
2. **Generate Meeting Minutes**: Extract detailed, structured minutes, including key points, decisions, and action items.
3. **Generate Summary**: Create concise summaries highlighting main topics, takeaways, and conclusions.
4. **Extract Action Items**: Identify tasks, responsibilities, and deadlines from the meeting.
5. **Generate Insights**: Get high-level analytics, trends, and outcomes from the meeting.
6. **Chat with Meeting**: Interact with the meeting content by asking questions and receiving AI-generated responses.

---

## Prerequisites

1. Python 3.8 or higher.
2. Install the necessary dependencies:
    ```bash
    pip install streamlit google-generativeai python-dotenv python-docx
    ```
3. Set up a `.env` file with your Google API key:
    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

---

## How to Run

1. Clone the repository and navigate to the project directory.
2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

---

## Usage

1. **Upload a Meeting Recording**:
    - Select an audio or video file from your device.

2. **Choose an Option**:
    - Click on buttons to:
        - Generate meeting minutes.
        - Generate a summary.
        - Extract action items.
        - Generate insights.

3. **Chat with the Meeting**:
    - Use the chat interface to ask questions about the meeting recording.

4. **Download Outputs**:
    - All outputs are downloadable as `.docx` files.

---

## Technologies Used

- **Streamlit**: For the web application interface.
- **Google Generative AI (Gemini 2.0)**: For advanced AI-based analysis.
- **Python-Docx**: For generating downloadable `.docx` documents.
- **dotenv**: For managing API keys securely.

---

## Screenshots

- **Home Page**:
    - A clean and professional UI for uploading meeting recordings and generating outputs.
- **Chat Interface**:
    - Intuitive interface for querying the meeting content.

---

## File Structure

- `app.py`: Main application script.
- `.env`: Environment file for storing API keys.
- `requirements.txt`: Python dependencies.

---

## Notes

1. Ensure you have a valid Google API key for accessing Gemini 2.0.
2. For large files, ensure your system has adequate resources for processing.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

- **Gemini 2.0** for its robust AI capabilities.
- **Streamlit** for enabling rapid and interactive app development.

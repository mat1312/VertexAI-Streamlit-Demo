# VertexAI Streamlit Demo

A simple demo application integrating **Google Cloud Vertex AI** with **Streamlit** to showcase generative AI capabilities using the Gemini model.

## Features

- User-friendly interface built with Streamlit.
- Generative AI powered by the Vertex AI Gemini model.
- Dynamic response to user queries in real time.

## Prerequisites

Before running the application, ensure you have the following:

1. Python 3.8 or higher.
2. An active Google Cloud project with Vertex AI enabled.
3. API keys and necessary permissions for Vertex AI.
4. A `.env` file with the following variables:
   ```env
   project_id=<your-google-cloud-project-id>
   region=<your-vertex-ai-region>
   ```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/VertexAI-Streamlit-Demo.git
   cd VertexAI-Streamlit-Demo
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file and add your Google Cloud project details:
   ```env
   project_id=<your-google-cloud-project-id>
   region=<your-vertex-ai-region>
   ```

## Usage

1. Run the application:
   ```bash
   streamlit run main.py
   ```

2. Open your browser and navigate to the URL displayed in the terminal (typically `http://localhost:8501`).

3. Interact with the interface by entering queries and receiving dynamic AI-generated responses.

## Project Structure

```
VertexAI-Streamlit-Demo/
├── main.py          # Main application file
├── .env             # Environment variables (not included in Git)
├── requirements.txt # Python dependencies
├── README.md        # Project documentation
```

## Dependencies

This project uses the following Python packages:
- `vertexai` - Google Cloud Vertex AI library
- `streamlit` - Web application framework for UI
- `python-dotenv` - For loading environment variables

## Notes

- Ensure that the Gemini model (`gemini-1.0-pro`) is available in your Google Cloud project.
- The application uses streaming responses for dynamic user interactions.



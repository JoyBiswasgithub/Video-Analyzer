# Multimodal Video Summarization and Analysis with Phi Agent

This project implements a Streamlit application that utilizes a Phi Agent to analyze and summarize video content. Users can upload videos and ask questions to gain insights from the video and supplementary web search.

## Project Structure

* `app.py`: The core Python script containing the Streamlit application code.
* `requirements.txt`: A file specifying the required Python libraries.

## Functionality

1. **Video Upload:** Users can upload video files in mp4, mov, or avi format.
2. **User Query:** A text area allows users to enter specific questions or desired insights from the video analysis.
3. **Video Processing and Analysis:**
   - Uploaded videos are processed using a Phi Agent with the Gemini 2.0-flash-exp model.
   - The agent analyzes the video content and performs web searches with DuckDuckGo if necessary.
4. **Response Generation:** The Phi Agent generates a detailed and user-friendly response that addresses the user's query based on the video analysis and supplementary information.
5. **Interactive Interface:** Streamlit provides an interactive interface for users to upload videos, enter queries, and view the analysis results.

## Technologies Used

* Streamlit: A Python library for creating web apps.
* Phi Agent: A framework for building intelligent agents with multimodal capabilities.
* Gemini 2.0-flash-exp: A Phi Agent model for video analysis.
* Google Cloud Generative AI (optional): For video processing functionalities (requires a Google API Key).

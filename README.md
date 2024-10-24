# AI-Powered Audio Replacer 🎙️🔄
## Description:
This project is a Python Proof of Concept (PoC) that automates the process of replacing video audio with AI-generated voice using cutting-edge technologies. Leveraging _Streamlit_, _AWS Transcribe_, _Polly_, and _OpenAI_, the tool extracts audio from a video, transcribes and corrects the text, and then replaces the original audio with a synthesized AI voice.
## Key Features:
- **Automatic Audio Extraction:** Extracts the audio from video files and uploads it directly to an S3 bucket for processing.
- **Speech-to-Text with AWS Transcribe:** Converts the extracted audio to text with high accuracy.
- **Text Correction with OpenAI:** Cleans up the transcription to enhance clarity and correctness.
- **AI Voice Generation with AWS Polly:** Converts the corrected transcription into natural-sounding speech, which is then merged back with the video.
- **Streamlit UI:** Provides a user-friendly interface to upload videos, process them, and download the final output.
## Screenshots:
>![1](https://github.com/user-attachments/assets/8de1f280-ef7f-4586-8912-28e01aac2866)

>![2](https://github.com/user-attachments/assets/0587c06e-ccfa-4451-96fe-3d9ce503defb)

>![3](https://github.com/user-attachments/assets/31df4db5-7da4-402c-9eb1-fe416949c707)

>![4](https://github.com/user-attachments/assets/4ade0432-ddf3-421a-88dc-4bc09455b653)

This project showcases the integration of cloud-based AI services with Python to simplify complex audio editing tasks.
